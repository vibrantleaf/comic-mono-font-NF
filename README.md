# Comic Mono
A legible monospace font... the very typeface you’ve been trained to recognize since childhood. This font is a fork of [Thai Pangsakulyanont ](https://github.com/dtinth)'s [Comic Mono](https://github.com/dtinth/comic-mono-font) which itself is a fork of [Shannon Miwa](https://github.com/shannpersand)’s [Comic Shanns](https://github.com/shannpersand/comic-shanns) (version 1).

<p class="website-hidden">
  <a href="https://dtinth.github.io/comic-mono-font/">
    <img src="https://repository-images.githubusercontent.com/164606802/cd83d680-894c-11e9-83f7-c353c70df1cb" alt="Screenshot">
  </a>
</p>

## Download
### Base
- [ComicMono.ttf](https://dtinth.github.io/comic-mono-font/ComicMono.ttf)
- [ComicMono-Bold.ttf](https://dtinth.github.io/comic-mono-font/ComicMono-Bold.ttf)

### Patched with [Nerd font's](https://github.com/dtinth/comic-mono-font) glyph sets
- [Comic.Mono.Nerd.Font.Complete.ttf](https://github.com/vibrantleaf/comic-mono-font-NF/releases/download/2022-12-3/Comic.Mono.Nerd.Font.Complete.ttf)
- [Comic.Mono.Bold.Nerd.Font.Complete.ttf](https://github.com/vibrantleaf/comic-mono-font-NF/releases/download/2022-12-3/Comic.Mono.Bold.Nerd.Font.Complete.ttf)

### Patched with [Nerd font's](https://github.com/dtinth/comic-mono-font) glyph sets, Windows Compatible 
- [Comic.Mono.Nerd.Font.Complete.Windows.Compatible.ttf](https://github.com/vibrantleaf/comic-mono-font-NF/releases/download/2022-12-3/Comic.Mono.Nerd.Font.Complete.Windows.Compatible.ttf)
- [Comic.Mono.Bold.Nerd.Font.Complete.Windows.Compatible.ttf](https://github.com/vibrantleaf/comic-mono-font-NF/releases/download/2022-12-3/Comic.Mono.Bold.Nerd.Font.Complete.Windows.Compatible.ttf)

## Differences from Comic Mono
1. Added all of [Nerd font's](https://github.com/dtinth/comic-mono-font) glyph sets with [Nerd Font's Patcher](https://github.com/NerdFonts/patcher)
The following Sankey flow diagram shows the current glyph sets included:

![Sankey flow diagram showing the current glyph sets included](https://raw.githubusercontent.com/ryanoasis/nerd-fonts/master/images/sankey-glyphs-combined-diagram.svg) -image credits [ryanoasis/nerd-fonts](https://github.com/ryanoasis/nerd-fonts)

## Differences from Comic Shanns
1. All glyphs have been [adjusted](https://www.reddit.com/r/programming/comments/kj0prs/comic_mono_font/ghc7krt/?utm_source=reddit&utm_medium=web2x&context=3) to have exactly the same width (using code based on [monospacifier](https://github.com/cpitclaudel/monospacifier)).
2. The glyph metrics have been adjusted to make it display better alongside system font, based on [Cousine](https://fonts.google.com/specimen/Cousine)’s metrics.
3. The name is changed to `Comic Mono`.
4. A bold version of the font is generated using [FontForge’s Embolden](https://fontforge.github.io/Styles.html#Embolden) operation.

I have no font creation skills; I’m just a software developer. This font family is created by patching the original font, [Comic Shanns (v1)](https://github.com/shannpersand/comic-shanns), using a Python script, [`generate.py`](generate.py).

## What does it look like?
<p class="website-hidden">
  <a href="https://dtinth.github.io/comic-mono-font/#what-does-it-look-like">
    Check it out!
  </a>
</p>

```python
{% include_relative generate.py %}
```

## CDN
You can use this font in your web pages by including the stylesheet. Based on by [jsDelivr](https://www.jsdelivr.com/package/npm/comic-mono). Hosed via Github Releases. 
```html
<link rel="stylesheet" href="https://github.com/vibrantleaf/comic-mono-font-NF/releases/download/2022-12-3/comic-mono-font-NF.css">
```

## Confermed Working Gliphs Sets
- Emoji
- Latin
- German
- Arabic
- Arabic Numerals
- Persian
- Cyrillic
- Coptic
- Hebrew
- Polish
- Simplified Chinese
- Korean Hangul
- Japanese Katakana
- Japanese Hiragana
- Thai
- Lao
- Turkish
- Ukrainian
- Ethiopic Geʻez

## Limitations 
Some of the following gliphs sets may have issuse rendering, i would recomend you to install a fallback font like liberation sans or ms fonts
- Traditional, Chinese (probably incomplete)
- Balinese, (missing)
- Mongolian, (missing)
- Deseret, (missing)
- Hungarian, (incomplete)
- Myanmar, (incomplete)

- Many other gliphs sets may have errors
- Some Ligatures may be missing

## License
It is licensed under the [MIT License](LICENSE).
