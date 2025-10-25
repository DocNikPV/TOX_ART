Toxicology in Art (ToxArt)
===========================

**Year:** 2025  
**Type:** Quarto book (HTML & PDF)  
**Repository:** [Tox_Art](https://github.com/DocNikPV/tox-art)

---

## The project concept

*Toxicology in Art* is an art-book exploring the intersection between **visual art** and **toxicology** — paintings, drawings, and engravings that depict, allude to, or symbolize **poisonings, toxins, or adverse drug effects**.

Each artist page presents:
- A **high-quality image** of the artwork and its **author** and **name**
- A brief **toxicological commentary** describing the subject or its historical medical context  

## The project structure

Tox_Art/
│
├── artworks/ # Individual artist pages (.qmd)
│ ├── caroto.qmd
│ └── ...
│
├── images/ # Artwork images used across the book
│
├── styles/ # Custom SCSS theme and visual assets
│
├── _quarto.yml # Main Quarto configuration (book metadata, structure)
├── index.qmd # Preface / introduction page
├── intro.qmd # General introduction
├── gallery.qmd # Artists index (auto-generated gallery of artworks)
├── summary.qmd # Summary and reflections
├── cover.png # Book cover
├── README.md # This file
└── Tox_Art.Rproj # RStudio project configuration

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
