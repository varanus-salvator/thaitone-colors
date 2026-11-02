# ThaiTone Color System

A searchable digitisation of the physical **ThaiTone color fan deck** — 330 Thai
traditional colors. Open `index.html`, or visit the GitHub Pages site.

Each color shows its code, Thai name, romanisation, English meaning, the **CMYK as
printed on the deck**, and an sRGB hex derived by a color-managed conversion for
on-screen preview.

## Attribution & scope

- The ThaiTone color system and the Thai color names are the work of
  **Prof. Pairoj Pittayamatee (ไพโรจน์ พิทยเมธี)**, creator of ThaiTone.
- Official announcement of the 330-color fan deck:
  <https://www.facebook.com/thaitonecolor/posts/706089547539678/>
- CMYK values are transcribed from the physical cards. The sRGB hex values are an
  **independent, unofficial** color-managed conversion and are not part of the
  original work.

This is an unofficial, **non-commercial** reference for study, published with
attribution. It is not affiliated with or endorsed by the author. If you are the
rights holder and would like changes, please open an issue.

## Data

`index.html` embeds the full dataset. A standalone `thaitone.json` is also included:

```json
{ "code": "T1010", "thai": "แดงชาด", "latin": "Dangchad",
  "en": "vermilion", "cmyk": {"c":20,"m":100,"y":100,"k":0},
  "hex": "#B82C23", "segment": "red" }
```
