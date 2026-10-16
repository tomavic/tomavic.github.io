# tomavic.github.io

Source of my personal site: **[tomavic.github.io](https://tomavic.github.io/)**

The site tells my career as seven short chapters, from mathematics and design to mobile apps, national-scale web platforms, frontend architecture and founding Enigma Technology Lab. After the chapters come what I do, how I think, what colleagues say, and how to reach me.

It reads in English and Arabic. The language switch flips the whole page to right-to-left.

## How it's built

- One `index.html` file with inline CSS and JavaScript. There is no framework and no build step.
- Translations live in the page as `data-i18n` keys.
- Fonts come from Google Fonts: IBM Plex Sans, IBM Plex Sans Arabic, IBM Plex Mono, Bricolage Grotesque and Noto Kufi Arabic.
- GitHub Pages serves it from `main`.

## Edit it locally

```shell
git clone https://github.com/tomavic/tomavic.github.io.git
cd tomavic.github.io
npx serve .
```

Edit `index.html`, refresh the page, and push to `main` to publish.
