# Vazirmatn Font فونت وزیرمتن

Vazirmatn is a Persian/Arabic font project that started in 2015 under the name of Vazir with the idea of a new simple and legible typeface suitable for web pages and applications. Design and development have taken a long way but I hope the results are worth it. Thanks to DejaVu Sans font (v2.35) published in public domain there was a free software base to start the Vazir project. Although Vazir was completely different in typeface, still the original software was common. The design is done in Fontforge. For Latin glyphs, Vazirmatn is combined with Roboto font by a build script, however there is also a version without Latin glyphs (Non-Latin). ([More info](https://rastikerdar.github.io/vazirmatn/fa/docs))

- [Website](https://rastikerdar.github.io/vazirmatn)
- [Docs](https://rastikerdar.github.io/vazirmatn/fa/docs)
- [Test the font](https://rastikerdar.github.io/vazirmatn/fa/lab)

## Install

### Download

Grab the [latest release](https://github.com/rastikerdar/vazirmatn/releases/latest) zip package.

TTF files are in folder `fonts/ttf`. There is also a rounded dots version in folder `Round-Dots/`.

### [npm](https://www.npmjs.com/package/vazirmatn)

```
npm install vazirmatn
```
or
```
yarn add vazirmatn
```

### CDN

```html
<link href="https://cdn.jsdelivr.net/gh/rastikerdar/vazirmatn@v32.101/Vazirmatn-font-face.css" rel="stylesheet" type="text/css" />
```

`*-font-face.css` for other versions are in `misc` and `Round-Dots` folders.

```css
body {
    font-family: Vazirmatn, sans-serif;
}
```

### Arch Linux ([AUR](https://aur.archlinux.org/packages/vazirmatn-fonts))
```
yay -S vazirmatn-fonts
```

## Build

All weights other than Thin, Regular and Black are generated by interpolation method by [fontmake](https://github.com/googlefonts/fontmake) library. See [README.md](/scripts/README.md) in `scripts/`. All build steps (generating files) are done by scripts.

## Thank you

- [fontforge](https://fontforge.org/)
- [fontmake](https://github.com/googlefonts/fontmake)
- [fonttools](https://github.com/fonttools/fonttools)
- [ttfautohint](https://www.freetype.org/ttfautohint/)
- [DejaVu Fonts v2.35](https://dejavu-fonts.github.io) (used for the first version)

## License
This Font Software is licensed under the SIL Open Font License, Version 1.1. See [OFL.txt](OFL.txt).

## Authors
See [AUTHORS.txt](OFL.txt).
