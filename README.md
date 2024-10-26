![Noto](https://raw.githubusercontent.com/RadekBledowski/noto-emoji-plus/main/images/noto.png
# Noto Emoji Plus
Noto Emoji (Stands for No Tofu) is an open source (Open Font License 1.1) emoji library that provides standard Unicode emoji support and tools for working with them including:

- A Unicode compliant color emoji [font](ttps://github.com/RadekBledowski/noto-emoji-plus/raw/main/fonts/NotoColorEmoji.ttf).
- A full library of Noto color emoji font files including vector svgs and pngs
- [Metadata](https://github.com/googlefonts/emoji-metadata) for Emoji Input (including shortcodes, emoji ordering, ascii equivalents)

Plus stands for more emojis and changes by me (RKBDI)

## Color Font

The latest font file is found [here](https://github.com/RadekBledowski/noto-emoji-plus/raw/main/fonts/Noto-COLRv1.ttf). If you want to download a specific version, please look at the gh-pages branch, where you will find the built assets for both our latest and older versions. 

## Using NotoColorEmoji

NotoColorEmoji uses the CBDT/CBLC color font format, which is supported by Android
and Chrome/Chromium OS.  Windows supports it starting with Windows 10 Anniversary
Update in Chrome and Edge.  On macOS, only Chrome supports it, while on Linux it will
support it with some fontconfig tweaking, see [issue #36](https://github.com/googlei18n/noto-emoji/issues/36). Currently we do not build other color font formats.

## A note about PNGs

The assets provided in the repo are all those used to build the NotoColorEmoji font. With one exception: the flag images in the font are PNG images to which transforms have been applied to standardize the size and generate the wave and border shadow. We do not have SVG versions that reflect these transforms.

## License

Emoji fonts (under the fonts subdirectory) are under the
[SIL Open Font License, version 1.1](fonts/LICENSE).<br/>
Tools and most image resources are under the [Apache license, version 2.0](./LICENSE).
Flag images under third_party/region-flags are in the public domain or
otherwise exempt from copyright ([more info](third_party/region-flags/LICENSE)).
