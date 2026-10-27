# Ehsan Suez — classic Minima academic website

This version uses **Jekyll's actual `minima` theme**, matching the theme specified in [Mallory Harris's public repository](https://github.com/mjharris95/mjharris95.github.io). The `assets/main.scss` file makes minor sizing/spacing tweaks to approximate her larger desktop layout from the screenshot. This is not a byte-for-byte clone of her repository.

## Preview on Mac

```bash
cd ~/Desktop/ehsan-minima-mallory-style
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000

## Editing
- `index.md`: homepage biography
- `research.md`, `teaching.md`, `publications.md`, `cv.md`: content pages
- `_config.yml`: site title, links, footer
- `assets/main.scss`: appearance (the actual Minima stylesheet is imported)
- `assets/headshot.jpg`: your headshot. Add your own JPG with this exact filename; until then a plain placeholder appears.

If Jekyll was already running in another folder, stop it with Control+C. Restart the server after editing `_config.yml`.

The original Jekyll `minima` theme is free/open-source. This version does not contain Mallory's personal imagery, articles, PDFs, or copy.

No content is published until you upload the files to your own GitHub Pages repository.
