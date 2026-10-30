# kurdpad-assets

Images and data for the Kurd Pad keyboard app. Public on purpose: the app downloads from here.

- `backgrounds/` - keyboard background pictures (PNG, ), one by one when the user picks them
- `stickers/` - sticker pictures; every file must be listed in `stickers.json`
- `stickers.json` - list of sticker file names
- `emoji/` - ten emoji picture packs, one zip each (`openmoji-72x72-color.zip`, `twemoji-72x72.zip`, `noto-72x72.zip`, `fluent-72x72.zip`, `blobmoji-72x72.zip`, `apple-72x72.zip`, `facebook-72x72.zip`, `joypixels-72x72.zip`, `samsung-72x72.zip`, `tossface-72x72.zip`); the app downloads only the one the user picks as emoji style. Licenses and credits: `emoji/README.md`
- `themes/` - one small JSON file per keyboard theme (`<id>.json`, ), downloaded one by one when the user taps a theme

Do not put app code or secrets in this repository.
