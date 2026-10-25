# BRND ProType

![BRND ProType: the word ProType from margin to margin, each letter in one of the seven weights](images/protype-01-brnd-protype.webp)

A neo-grotesque superfamily designed and drawn from scratch by [BRND](https://www.brndconsulting.com) in Maracaibo, Venezuela. Free for personal and commercial use under the SIL Open Font License 1.1.

**Try it online and download it:** [BRND® ProType & Grid System](https://www.brndconsulting.com/post/brnd-protype-grid-system)

[Español](#en-español)

## The family

- 49 static styles in four families: Condensed, Normal, Extended and Mono.
- Seven weights, from Light to Black (300 to 900).
- Italics for Condensed, Normal and Extended: 21 italic styles.
- Three variable fonts:
  - **BRND ProType Variable**: weight from 300 to 900 and width from 88.1 to 114.5 (Condensed to Extended), with 21 named instances.
  - **BRND ProType Variable Italic**: weight from 300 to 900, with 7 named instances.
  - **BRND ProType Mono Variable**: weight from 300 to 900, with 7 named instances.
- 566 characters per style (561 in Mono): Latin-1 and extended Latin, punctuation, figures, currencies, fractions, arrows, geometric shapes and symbols.
- OpenType features: kerning, ligatures (ff fi fl ffi ffl), automatic fractions, numerators and denominators, case-sensitive forms and combining accents.
- Drawn with a low node count, so it also works well in physical applications, from plotter cutting to embroidery.

![Widths: Maracaibo, Venezuela in Condensed, Normal and Extended](images/protype-13-anchuras.webp)

![Weights: the seven weights from Light 300 to Black 900](images/protype-05-pesos.webp)

![Italics: the roman and italic a with their 10 degree slant](images/protype-15-italicas.webp)

![Mono: the fixed width of 620 units in seven weights](images/protype-17-mono.webp)

![Construction: the S and the a in outline with their nodes and Bézier handles](images/protype-03-construccion.webp)

## In use

![Newspaper front page](images/protype-14-periodico.webp)

![Metro station signage and map](images/protype-04-metro.webp)

![Beer bottles and can](images/protype-16-envase.webp)

![Mobile app for a lakeside park](images/protype-18-aplicacion.webp)

![Music festival poster](images/protype-20-cartel.webp)

![Tourism: the Catatumbo lightning](images/protype-10-turismo.webp)

![Baseball scoreboard and line-up](images/protype-06-beisbol.webp)

![Space mission timeline](images/protype-02-orbita.webp)

![Architecture: museum facade with letter tower](images/protype-12-arquitectura.webp)

![Museum room: type anatomy](images/protype-08-anatomia.webp)

![Text: four columns at 27, 21, 16.5 and 13 px](images/protype-19-texto.webp)

## Characters

![Letters: the alphabet in Light, Regular and Black and every accented letter](images/protype-07-letras.webp)

![Punctuation by group in Light, Regular and Black](images/protype-09-puntuacion.webp)

![Symbols and figures by group in Light and Black](images/protype-11-simbolos.webp)

## What is in this repository

| Path | Contents |
| --- | --- |
| `Normal/`, `Condensed/`, `Extended/` | 14 OTF files each: seven weights and their italics |
| `Mono/` | 7 OTF files |
| `Variable/` | The three variable fonts (OTF) |
| `Web/` | WOFF2 for every style, `brnd-protype.css` with its `@font-face` rules, `ejemplo.html` and `glifos.html` |
| `BRNDProType-1.0.2-especimen.pdf` | Specimen: widths, weights, every character and the features |
| `FONTLOG.txt` | Version history |
| `OFL.txt` | License |
| `SUMAS-SHA256.txt` | SHA-256 of every file: `shasum -a 256 -c SUMAS-SHA256.txt` |

The same package, as a single zip, is attached to each [release](https://github.com/brndconsulting/brnd-protype-font/releases).

## Install

- **Mac:** quit your apps with Cmd+Q, remove any earlier BRND ProType in Font Book, then double-click each `.otf` file and click Install.
- **Windows:** remove any earlier BRND ProType in Settings > Personalization > Fonts, then right-click each `.otf` file and choose Install for all users.
- Install either the static fonts or the variable fonts, not both in the same app.

## Web

Copy the `Web/` folder to your site and load its stylesheet:

```html
<link rel="stylesheet" href="Web/brnd-protype.css">
```

```css
h1   { font-family: "BRND ProType"; font-weight: 900; font-stretch: 114.5%; }
p    { font-family: "BRND ProType"; font-weight: 400; }
code { font-family: "BRND ProType Mono"; }
```

`font-stretch` picks the width: 88.1% Condensed, 100% Normal, 114.5% Extended.

## License

Copyright 2026 BRND Consulting, with Reserved Font Name "BRND ProType". This Font Software is licensed under the [SIL Open Font License, Version 1.1](OFL.txt). You can use it, embed it and redistribute it, also in commercial work; modified versions must be released under another name.

## Version

1.0.2, 2026-10-24. The full history is in [FONTLOG.txt](FONTLOG.txt).

---

## En español

Superfamilia neogrotesca diseñada y dibujada desde cero por [BRND](https://www.brndconsulting.com) en Maracaibo, Venezuela. Gratis para uso personal y comercial con la licencia SIL Open Font License 1.1.

**Pruébala en línea y descárgala:** [BRND® ProType & Grid System](https://www.brndconsulting.com/post/brnd-protype-grid-system)

- 49 estilos en cuatro familias: Condensed, Normal, Extended y Mono, en siete pesos de Light a Black. Condensed, Normal y Extended llevan además su itálica: 21 en total.
- Tres fuentes variables: la de peso (300 a 900) y anchura (88,1 a 114,5), la itálica de peso y la Mono de peso.
- 566 caracteres por estilo (561 en la Mono), con kerning, ligaduras, fracciones automáticas, numeradores, denominadores, formas para mayúsculas y acentos combinantes.
- Dibujada con pocos nodos, para que funcione también en aplicaciones físicas, del corte en plotter al bordado.

Las instrucciones para instalarla están en [LEEME.txt](LEEME.txt) y el historial de versiones en [FONTLOG.txt](FONTLOG.txt).
