# FAQ and troubleshooting

[Home](../README.md) · [简体中文](zh-CN/faq.md) · [Getting started](getting-started.md)

## Why is no tag detected?

Confirm the phone has NFC hardware and NFC is enabled. Keep NFC Studio open in the foreground, hold one tag near the antenna, remove thick or metallic cases and try another known-compatible tag. Contactless cards may use protocols or access controls the phone cannot read.

## Why can I see a UID but no content?

A tag can expose an identifier or technology without supporting NDEF or allowing access to its content. This does not indicate a successful credential copy. MIFARE Classic support also depends on the phone's NFC chipset.

## Why does writing fail?

Check NDEF support, writable status, capacity and access restrictions. Reduce the content size, keep the tag still and try a compatible blank tag. Read-only tags cannot be unlocked by the app. Authentication tools require supported tags, Pro access and valid credentials.

## Can it clone an access card, bank card or transit card?

It does not simulate or rewrite tag UIDs, extract keys or bypass authentication. Copying standard NDEF content or supported MIFARE data blocks does not reproduce a protected credential. Use the issuer's supported replacement or provisioning process.

## What is free? Does the trial charge me?

Basic reading, standard NDEF writing/verification, history, templates and local JSON backup are free. Pro adds advanced tools and suppresses banners while active. The seven-day trial starts only when you activate it; it requires no payment and does not charge at expiry. Lifetime purchase is a one-time in-app purchase.

Version 1.1.14 adds an annual subscription and was submitted for review on October 28, 2026; public availability is not yet confirmed. Annual subscriptions renew automatically unless canceled in Google Play. Check available plans, price and terms in the app. Canceling a paid annual plan stops renewal; access normally continues until its paid period ends.

## How do I restore Pro?

Use the original Google Play account and the restore-purchases action in the main app. Check your internet connection and allow Play to refresh purchase status. A legacy separate Pro app purchase is not described here as a transferable main-app entitlement. For help, email support without posting order or payment details publicly.

## Does Pro remove every Google service?

Pro suppresses banner ads while access is active. It does not remove all SDKs. Usage analytics and crash reporting are optional and off by default; billing, advertising and ML Kit diagnostics are described in the [privacy policy](https://hienao-apps.pages.dev/nfc-studio/privacy/).

## Where is my data? Can I move it?

Tag data, history, templates and saved tags are processed/stored locally. Scan/write history has a 30-day retention period with startup cleanup. Templates and saved tags remain until deleted or app data is cleared. Automatic Android backup is disabled; use the app's JSON export/import before changing phones or uninstalling. Keep exports private. Expired Pro does not delete history or templates or block existing data backup/restore/export paths.

## What should a bug report contain?

App version, Pro status, Android version, phone model, tag technology, operation, exact error and reproduction steps. Remove UIDs, NDEF personal data, Wi-Fi passwords, authentication keys and real backups. Use the [bug form](https://github.com/hienao/NFC-Studio/issues/new?template=bug_report.yml) or contact [private support](mailto:shiwentao666@gmail.com).
