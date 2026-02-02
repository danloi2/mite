# MITE: Designing your Educational Technology Project

[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://danloi2.github.io/mite)
[![MyST](https://img.shields.io/badge/powered_by-MyST-orange)](https://mystmd.org)

This repository hosts the source files for the **"TFM in Action: Designing your Educational Technology Project"** course materials. This resource is specifically designed for students within the Master's in Digital Education.

The project is built using **Jupyter Book 2.1.0** and **MyST Markdown (mystmd)**.

## 🚀 About the Project

The core mission of this site is to guide students through the creation of a high-quality initial draft of their **Master's Thesis (TFM)**. The content focuses on developing a rigorous **Conceptual Framework**, which is the heart of any scientific research in the field of Educational Technology.

### Technical Key Features:
- **Engine:** Jupyter Book 2.1.0.
- **Content Format:** MyST Markdown for enhanced technical documentation.
- **Visualizations:** Integrated Mermaid.js for learning itineraries and flowcharts.
- **Citations:** Full support for **APA 7th Edition** referencing styles.
- **Interactive Elements:** Dropdown admonitions, glossaries, and call-to-action blocks.

## 🛠️ Local Development

To build or modify this book locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/danloi2/mite.git](https://github.com/danloi2/mite.git)
   cd mite

```

2. **Install Jupyter Book:**
```bash
pip install jupyter-book==2.1.0

```


3. **Build the HTML version:**
```bash
jb build .

```


4. **Preview:**
Open `_build/html/index.html` in your preferred web browser.

## 📁 Repository Structure

* `index.md`: The landing page and course introduction.
* `_config.yml`: Global configuration (metadata, execution settings, and HTML buttons).
* `_toc.yml`: Table of Contents defining the pedagogical flow.
* `references.bib`: BibTeX file containing all academic sources cited in the materials.

## 👨‍🏫 Academic Team

* **Daniel Losada Iglesias** (Coordinator) – University of the Basque Country / Euskal Herriko Unibertsitatea.
* **Héctor Galindo**.
* **Lucía Campo**.

---

*Developed for the Master's in Digital Education.*

## 👥 Author

**Developed by Daniel Losada**

[![GitHub](https://img.shields.io/badge/GitHub-danloi2-181717?style=for-the-badge&logo=github)](https://github.com/danloi2)
[![Researcher EHU](https://img.shields.io/badge/Researcher-EHU-blue?style=for-the-badge&logo=researchgate)](https://github.com/danloi2)

---

```

### Quick Tips for your MyST setup:
* **Hero Component:** Since you are using `:::{hero}`, ensure your `_config.yml` or custom CSS is set up to handle that specific class for the "orange" accent to display correctly.
* **Mermaid Diagrams:** Ensure the `sphinxcontrib-mermaid` extension is enabled in your configuration to render the `gitGraph` you included in the index.


```
