<p align="center"><img src="assets/readme/icon-v2.png" width="88" height="88" alt="NFC Studio"></p>

<h1 align="center">NFC Studio</h1>

<p align="center"><strong>Read. Understand. Write.</strong></p>
<p align="center">Practical NFC tag tools for Android.</p>

<p align="center"><a href="https://play.google.com/store/apps/details?id=com.hienao.nfc.studio">Get it on Google Play</a> · <a href="https://hienao-apps.pages.dev/nfc-studio/">Website</a></p>

<p align="center">English · <a href="README.zh-CN.md">简体中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.de.md">Deutsch</a> · <a href="README.es.md">Español</a> · <a href="README.pt-BR.md">Português (Brasil)</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.ar.md">العربية</a> · <a href="README.ru.md">Русский</a></p>

<p align="center">
  <a href="assets/readme/en-US/read.png"><img src="assets/readme/en-US/read.png" width="31%" alt="NFC Studio — read tags on phone"></a>
  <a href="assets/readme/en-US/write.png"><img src="assets/readme/en-US/write.png" width="31%" alt="NFC Studio — write tags on phone"></a>
  <a href="assets/readme/en-US/tools.png"><img src="assets/readme/en-US/tools.png" width="31%" alt="NFC Studio — tools on phone"></a>
</p>

<p align="center"><a href="assets/readme/en-US/tablet.png"><img src="assets/readme/en-US/tablet.png" width="72%" alt="NFC Studio — write tags on tablet"></a></p>

<p align="center"><sub>App previews for phone and tablet. Tap to enlarge; availability and appearance may vary by version.</sub></p>


NFC Studio helps you inspect NFC tags, edit standard NDEF content and write compatible tags. Keep scan history, templates and named tags on your device, without creating an account.

## From a tap to useful information

- **Inspect a tag.** See its technologies, available capacity, writable status and NDEF records, with raw fields for troubleshooting.
- **Write everyday content.** Prepare text, links, Wi-Fi, contacts, phone numbers, email and locations; review compatibility and capacity before writing, then read back to verify.
- **Reuse your work.** Save templates, organize tags with names and notes, and move local data with JSON export and import.
- **Bring in QR content.** Import supported QR text, links or Wi-Fi details using the camera, or paste content instead.
- **Go further with Pro.** Batch writing, tag comparison, reports with CSV/PDF export, authenticated writing and tools for compatible NTAG21x and MIFARE Classic tags.

Features depend on your installed version, phone hardware and the tag's capabilities and access restrictions. Copying supported data does not copy a tag's UID or reproduce a protected credential.

## Get started

1. Install [NFC Studio from Google Play](https://play.google.com/store/apps/details?id=com.hienao.nfc.studio) on an NFC-enabled Android device (Android 7.0 or later).
2. Enable NFC in Android settings, open the app and hold a supported tag near the phone's NFC antenna.
3. Inspect the result. To write, prepare NDEF content and follow the write prompt with a compatible writable tag. Keep it still until the operation and verification finish.

[Reading and writing guide](docs/getting-started.md) · [FAQ and troubleshooting](docs/faq.md)

## Free and Pro

| | Free | Pro access |
| --- | --- | --- |
| Basic reading, standard NDEF writing and verification | Included | Included |
| History, templates and local JSON backup | Included | Included |
| Batch writing, comparison and advanced reports | — | Included |
| Supported authenticated writing and advanced tag tools | — | Included |
| Banner advertising | May be shown, subject to privacy choices | Suppressed while Pro is active |

Pro is available inside the main app: start a seven-day trial when you choose, or make a one-time lifetime purchase. The local trial does not require payment and does not charge automatically when it ends. Restore eligible purchases through Google Play using the purchasing account.

**Annual plan:** version 1.1.14 adds an annual Pro subscription alongside lifetime purchase. It was submitted for review on October 28, 2026; public availability is not yet confirmed. Annual subscriptions renew automatically unless canceled in Google Play. Available plans and local prices are shown in the app before purchase. A separate legacy Pro app is not required for the current main-app upgrade path.

## Your tags, on your device

NFC tag content is processed locally. Full UID display is hidden by default, and saving full tag content is off by default. Scan/write history is retained for 30 days, with older entries removed during startup cleanup. Templates and saved tags remain until you delete them or clear app data.

Optional Firebase usage analytics and crash reporting are off by default and can be enabled separately. Advertising, billing and ML Kit diagnostics may process data through Google services; Pro does not mean the app contains no third-party SDKs. See the [official privacy policy](https://hienao-apps.pages.dev/nfc-studio/privacy/) for details. Exported files can contain sensitive tag or template content; share them carefully.

## Languages

The interface and these introductions support English, Simplified Chinese, Japanese, German, Spanish, Portuguese, Indonesian, Arabic and Russian. Detailed guides and the FAQ are available in [English](docs/faq.md) and [Simplified Chinese](docs/zh-CN/faq.md).

## Help improve NFC Studio

[Report a problem](https://github.com/hienao/NFC-Studio/issues/new?template=bug_report.yml) or [suggest a feature](https://github.com/hienao/NFC-Studio/issues/new?template=feature_request.yml). English and Chinese reports are welcome. Include the app version, device, Android version, tag type and steps to reproduce. Remove tag UIDs, passwords, keys and personal content; do not attach real backups.

Documentation corrections and translations are welcome; see [how to contribute](CONTRIBUTING.md). Read the [release notes](CHANGELOG.md) for selected changes. A star helps others find the app.

## About this repository

This is the public home for NFC Studio's introduction, documentation and feedback. Application source code is private and is not distributed here. This repository does not grant an open-source license to the app or its assets.

[Website](https://hienao-apps.pages.dev/nfc-studio/) · [Privacy policy](https://hienao-apps.pages.dev/nfc-studio/privacy/) · [Support](mailto:shiwentao666@gmail.com)
