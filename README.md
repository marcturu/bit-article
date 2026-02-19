# <img src="img/bit-logo.svg" alt="Bit Article" width="150"/> — Structured web content

<sub>🗓️ Developed in November 2025</sub>

This project is a **structured webpage developed with HTML5 & CSS3**, composed of three pages: `index.html`, `recursos.html`, and `glossari.html`, along with additional assets such as CSS stylesheets in `/css`, images in `/img`, and audio files in `/music`.  
The goal was to reinforce the basic concepts from HTML & CSS by presenting well-organized HTML documents using semantic elements and proper styling.

---

## ✅ Features

- Basic structuring for **HTML5 documents**, including `<!DOCTYPE html>`, `<html lang="ca">`, `<head>`, `<body>`, `<header>`, `<nav>`, `<main>`, and `<footer>`.
- **Semantic content organization** using `<article>` for editorial content units and `<section>` for independent thematic subunits, with heading hierarchy (`h1`, `h2`, `h3`) and text elements (`p`).
- **List structures** including unordered lists (`ul`, `li`) to represent article elements, and description lists (`dl`, `dt`, `dd`) to represent the full AI glossary in `glossari.html`.
- **Semantic text elements** for clarity: `<blockquote>` for long quotes with context, `<q>` for short inline quotes, `<cite>` for work titles, `<abbr>` for acronyms with full descriptions on hover, and `<em>` for semantic emphasis on key words.
- **Multimedia and embedded content**: images (`<img>`), inline video frames (`<iframe>` with `aspect-ratio: 16/9` for proper YouTube proportions), and audio players (`<audio>`, `<source>`), all organized within semantic `<figure>` and `<figcaption>` containers.
- **External and internal links** (`<a>`) with `target="_blank"` to open external links in a new tab, and CSS-based external link icons via `a[href^="http"]:not(.no-icon)::after` to avoid repetitive HTML markup.
- **CSS styling and custom properties**: Variables for colors and font families defined in `:root` for consistency across the stylesheet, styles for semantic text elements, and specific styles for navigation, footer, article containers, responsive video ratios, and hover/active states.
- **Accessibility and validation**: All HTML files validated with [W3C Validator](https://validator.w3.org/) and CSS validated with [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) — no errors or warnings found across all pages.

---

## 🛠 Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/marcturu/bit-article.git
```

### 2. Try the webpage locally
Open the ```.html``` files directly in a browser or use **Live Server**. 

The webpage will typically be available at `http://127.0.0.1:5500/`.

---

## 📂 Documentation

All additional documentation is in the `/DOCS` directory:
- **HTML entities**
- **CSS styles**
- **Significant aportations**
- **Accessibility and validation** 

---
## 📷 Screenshots 

### Article (Desktop):
![Article(Desktop)](screenshots/Desktop_article.png)

### Recursos (Desktop):
![Recursos(Desktop)](screenshots/Desktop_recursos.png)

### Glossari (Desktop):
![Glossari(Desktop)](screenshots/Desktop_glossari.png)

### Article (Tablet):
![Article(Tablet)](screenshots/Tablet_article.png)

### Recursos (Tablet):
![Recursos(Tablet)](screenshots/Tablet_recursos.png)

### Glossari (Tablet):
![Glossari(Tablet)](screenshots/Tablet_glossari.png)

### Article (Mobile):
![Article(Mobile)](screenshots/Mobile_article.png)

### Recursos (Mobile):
![Recursos(Mobile)](screenshots/Mobile_recursos.png)

### Glossari (Mobile):
![Glossari(Mobile)](screenshots/Mobile_glossari.png)

---

## ⚖️ Copyright & License

© 2025 Marc Turu Roca. All rights reserved.

This project and its contents are the exclusive intellectual property of Marc Turu Roca.  
All rights reserved. No part of this project may be copied, modified, distributed, or used without prior written permission from the author.
