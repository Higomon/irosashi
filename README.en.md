# Irosashi

[日本語](README.md) · English

<br>

**A web app for creating toothpick art and pixel art templates.**

- For artwork made by inserting painted toothpicks into rigid foam, such as Styrofoam
- Photos converted into pixel art, color-numbered templates, material lists, and printable PDFs

<br>

## [Open Irosashi →](https://higomon.github.io/irosashi/)

- **iPhone and desktop support / No installation**
- Adjustable finished dimensions and color count
- **Large templates tiled across A4 sheets**
- Photo processing entirely on your device

<br>

## Example

| Original image | Generated template |
| --- | --- |
| ![House and sun sample image](docs/examples/original.png) | ![200 mm square template](docs/examples/pattern.png) |

- Finished size: 200 × 200 mm
- Toothpick center spacing: 5 mm / 40 columns × 40 rows
- Colors used: 7

<br>

### Color-numbered template

- A color number in each cell
- PDF output: material list, pattern sheets, and assembly guide

<br>

![Color-numbered template](docs/examples/layout.png)

<br>

### A4 tiled printing

- **400 × 400 mm template → 4 portrait A4 sheets**
- Layout: 2 columns × 2 rows / Margins: 5 mm
- 4 pattern sheets plus a material list / Assembly guide in a separate PDF

<br>

| Four A4 sheets | Assembled template |
| --- | --- |
| ![Template split across four portrait A4 sheets](docs/examples/a4-pages.png) | ![Template assembled in sheet-number order](docs/examples/a4-assembled.png) |

<br>

1. Paper: “A4” → “分割を見る” (Preview tiling)
2. Save PDF → **Print at actual size (100%)**
3. Trim the white margins
4. Arrange by sheet number → **Join edge to edge, without overlap**

<br>

## How to use

1. Select a photo ([sample image](docs/examples/sample.png))
2. Adjust dimensions, toothpick spacing, and color count
3. Check paper size, margins, and tiling
4. Save and print the PDFs
5. Insert painted toothpicks into the foam, following the template

- Toothpick diameter and center spacing: measured values
- Saving PDFs on iPhone: “共有して保存” (Share and save) → “Save to Files”

<br>

## Editing and updates

- Single source file: `いろさし - 図案を作る.html`
- Automatic GitHub Pages deployment on push to `main`
