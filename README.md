# senworksheet# ARASAAC SEN Worksheet Generator

A lightweight, single-file web app for creating printable A4 English-as-a-Second-Language (ESL) and Special Educational Needs (SEN) vocabulary worksheets using live pictograms from the [ARASAAC](https://arasaac.org/) database.

🔗 **Live App:** `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

---

## Features

- **Live ARASAAC Pictogram Search:** Type your target vocabulary (one word or phrase per line) and fetch matching pictograms automatically. Supports searching in English (`en`), Spanish (`es`), and Catalan (`ca`).
- **Pictogram Switcher:** Cycle through alternative ARASAAC symbols (`◀` / `▶`) directly on the preview until you find the clearest match for your student.
- **Three Worksheet Modes:**
  - **Match & Trace:** Dotted uppercase words on the left with shuffled pictograms on the right.
  - **Vocabulary Reference:** Aligned word-and-picture pairs for visual anchoring.
  - **Cut & Paste Sort:** Target word boxes with a dashed cut-out strip of shuffled pictograms at the bottom.
- **Multimodal Scaffolding:**
  - Toggle between **Dotted (Tracing)** and **Solid Bold** uppercase lettering.
  - **Editable Color Dots:** Click any colored dot on the worksheet preview to cycle its color and keep consistent color-coding across lessons.
  - **Quick Size Sliders:** Adjust word and pictogram sizes live so 3-word or 7-word sheets fit cleanly on a single A4 page.
- **Custom School Branding:** Upload your school logo (PNG, JPG, or SVG), scale its size, and customize the school name, subtitle, and worksheet title.
- **Save & Reload Units:** Save vocabulary sets—including your chosen pictograms, dot colors, and layout settings—for quick reuse.
- **Print-Ready A4 Output:** One-click **Print / Save PDF** automatically hides all sidebar controls and pictogram switcher buttons.

---

## How to Use

### Option 1: Use Online (GitHub Pages)
Open the live link above in any modern browser (Chrome, Edge, Safari, or Firefox). No installation or login required.

### Option 2: Run Locally
1. Download `index.html` from this repository.
2. Double-click `index.html` to open it in your browser.
3. Enter your target words, click **Fetch Pictograms & Build**, customize your layout, and click **Print / Save PDF**.

---

## Privacy & Local Storage

All saved vocabulary units and uploaded school logos are stored locally in your own browser (`localStorage`). Nothing is uploaded to external servers, and each teacher using the page has their own private saved lists.

---

## Credits & License

- **Pictograms:** Author: Sergio Palao. Origin: [ARASAAC](http://www.arasaac.org) (Government of Aragón). License: **CC (BY-NC-SA)**.
- **Fonts:** *Atkinson Hyperlegible* and *Raleway Dots* via Google Fonts.
