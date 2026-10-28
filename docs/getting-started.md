# Read and write your first tag

[Home](../README.md) · [简体中文](zh-CN/getting-started.md) · [FAQ](faq.md)

## Before you begin

Use Android 7.0 or later on a device with NFC hardware. Enable NFC in system settings. Some phones place the antenna near the camera; others use the center of the back. A blank, writable NDEF-compatible tag is a good first test. Capability varies by device and tag.

## Read

1. Open NFC Studio and keep it in the foreground.
2. Hold the tag near the antenna until a result appears. Move it slowly if necessary.
3. Inspect technologies, NDEF support, capacity and available record details. Not all tags expose the same fields. An identifier or technology name alone does not mean the protected content is readable.

## Write

1. Open the writing screen and choose a supported record type, such as text or a URL.
2. Enter non-sensitive test content, such as `https://example.com`, and review the records.
3. Start writing and place a compatible writable tag against the antenna.
4. Keep the tag still until the write operation and read-back verification complete. A completed write and successful verification are distinct results; inspect the result before removing the tag.
5. Read the tag again to confirm the content. If another device does not offer the expected action, check that it supports that NDEF record type.

Writing replaces the tag's existing NDEF content. Back up content you need first. Erasing clears supported NDEF content; it does not remove hardware locks or reset a protected credential. Making a tag permanently read-only, where supported, cannot be undone.

## Reuse and back up

Save frequent content as templates. Use My Tags to add names, categories and notes. Export or import local JSON through the app's data tools; inspect the export scope before sharing. Import skips duplicate records. Exported files can include personal content and are not suitable for public issue attachments.

QR import requests camera permission when used. Supported content is recognized locally with the bundled model; paste the content if you prefer not to grant camera access. Third-party SDK diagnostics are described in the [privacy policy](https://hienao-apps.pages.dev/nfc-studio/privacy/).

## Advanced tools

With Pro access, use batch writing, comparison, reports and supported authentication/security tools. Only supply keys or passwords you are authorized to use. Supported MIFARE data copying skips manufacturer and sector-trailer blocks; it does not clone UID, keys or a working access/payment credential. Access restrictions and hardware compatibility still apply.
