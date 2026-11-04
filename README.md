# ThaiTone™ Color System

A searchable digitisation of the physical **ThaiTone™ color fan deck** — 330 Thai
traditional colors. Open `index.html`, or visit the GitHub Pages site.

Each color shows its code, Thai name, romanisation, English meaning, the **CMYK as
printed on the deck**, and an sRGB hex derived by a color-managed conversion for
on-screen preview.

## Attribution & scope

- The **ThaiTone™** color system and the Thai color names are the original work of
  **Prof. Pairoj Pittayamatee (ไพโรจน์ พิทยเมธี)**, creator of ThaiTone™.
- **ThaiTone™** is the brand / trademark of its creator. The color system is shared
  freely; this project uses the CMYK values and names with attribution and is **not
  affiliated with or endorsed by** the author.
- Official ThaiTone™ Color page: <https://www.facebook.com/thaitonecolor/>
- Announcement of the 330-color fan deck:
  <https://www.facebook.com/thaitonecolor/posts/706089547539678/>
- Feature in The Nation: <https://www.nationthailand.com/news/sunday/aec/30279713>
- ThaiTone™ color reference (PDF):
  <https://www.thailibrary.in.th/wp-content/uploads/2015/10/Thaitone-Color.pdf>
- CMYK values are transcribed from the physical cards. The sRGB hex values are an
  **independent, unofficial** color-managed conversion and are not part of the
  original work.

This is an unofficial, **non-commercial** reference for study, published with
attribution. It is not affiliated with or endorsed by the author. If you are the
rights holder and would like changes, please open an issue.

## Files

- `index.html` — the searchable site (embeds the full dataset).
- `ThaiTone.ase` — Adobe Swatch Exchange library: all 330 colors as **CMYK**
  swatches, grouped by segment, named `T-code Romanization`. Opens in Photoshop,
  Illustrator, InDesign, Affinity and PhotoCraft. Because it stores the printed CMYK,
  each app converts to screen under its own color profile.
- `thaitone.json` — the full dataset.

## Data

`index.html` embeds the full dataset. A standalone `thaitone.json` is also included:

```json
{ "code": "T1010", "thai": "แดงชาด", "latin": "Dangchad",
  "en": "vermilion", "cmyk": {"c":20,"m":100,"y":100,"k":0},
  "hex": "#B82C23", "segment": "red" }
```
