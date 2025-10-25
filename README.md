# Toxicology in Art (ToxArt)

**Year:** 2025  
**Type:** Quarto book (HTML & PDF)  
**Repository:** [Tox_Art](https://github.com/DocNikPV/TOX_ART)

---

## The project concept

_Toxicology in Art_ is an art-book exploring the intersection between **visual art** and **toxicology** — paintings, drawings, and engravings that depict, allude to, or symbolize **poisonings, toxins, or adverse drug effects**.

Each chapter presents:

- A brief historical-narrative **fabule** about the person/place depicted, as well as a relevant **medico-toxicological commentary**.
- A **high-quality image** of the artwork and its **author** and **name**.

## The project structure

ToxArt/
├── \_quarto.yml
├── index.qmd
├── preface.qmd
├── references.qmd
├── chapters/
│ └── Sophonisba.qmd
├── images/
│ └── Brouwer_Sophonisba.jpg
│ └── ...
├── styles/
│ └── custom.scss ← optional, for custom CSS theme
├── .github/
│ └── workflows/
│ └── quarto-publish.yml ← GitHub Actions workflow
├── .gitignore
├── LICENSE
└── README.md

## Rendering and publishing

This project is built with **[Quarto](https://quarto.org/)**.

Written entirely in Quarto Markdown (.qmd).

Compatible with RStudio (Visual Editor recommended for image-rich chapters).

Each image resides under /images/ and is referenced with root-relative paths:

## License and citation

All text © 2025 Nik Danilov.

Artwork images are open-sourced and reproduced for educational and scholarly purposes only, under fair-use principles.

If you cite this project, please use:

Danilov, N. (2025). Toxicology in Art: A Quarto-based illustrated compendium. GitHub: https://github.com/DocNikPV/tox-art
