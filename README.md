# AwardLens Catalog

This repository hosts signed, encrypted data updates for the native AwardLens
1.2 beta. It is not the app's source repository or an award-availability service.

Each immutable `catalog-N` release contains only:

- `catalog.alc` and `preview.alc`: encrypted catalog and published article data.
- `catalog-manifest.json` and `preview-manifest.json`: signed update metadata.

Signing keys, client trust, decryption keys, account data and private sources
are not published here. On-device encryption is best-effort protection; it
does not make data impossible to extract from a device running the app.

[Privacy policy](PRIVACY.md) | [Support](SUPPORT.md)
