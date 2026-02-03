# MITE: Designing your Educational Technology Project

![Jupyter Book](https://img.shields.io/badge/Built%20with-Jupyter%20Book-blue?logo=jupyter)
![MyST](https://img.shields.io/badge/Powered%20by-MyST-orange?logo=markdown)
![Python](https://img.shields.io/badge/Python-3.14-blue?logo=python)

This repository hosts the source files for the **"TFM in Action: Designing your Educational Technology Project"** course materials. This resource is specifically designed for students within the Master's in Digital Education at the **University of Extremadura (UNEX)**.

The project is built using **Jupyter Book 2.1.2** and **MyST Markdown (mystmd)**.

## 🚀 About the Project

The core mission of this site is to guide students through the creation of a high-quality initial draft of their **Master's Thesis (TFM)**. The content focuses on developing a rigorous **Conceptual Framework**, which is the heart of any scientific research in the field of Educational Technology.

### Technical Key Features:
- **Engine:** Jupyter Book 2.1.2 via Conda.
- **Content Format:** MyST Markdown for enhanced technical documentation.
- **Visualizations:** Integrated Mermaid.js for learning itineraries.
- **Citations:** Full support for **APA 7th Edition** referencing styles.

## 🛠️ Environment Setup & Usage

This project uses **Conda** to manage dependencies. Ensure you have [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/) installed.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/danloi2/mite.git](https://github.com/danloi2/mite.git)
   cd mite

```

2. **Create the environment:**
Use the provided `environment.yml` (or create it manually with the following specifications):
```bash
conda create -n MITE -c conda-forge jupyter-book==2.1.2 mystmd nodejs python=3.14

```


3. **Activate the environment:**
```bash
conda activate MITE

```


4. **Build the project:**
```bash
jb build .

```



## 📁 Repository Structure

* `index.md`: The landing page and course introduction.
* `_config.yml`: Global configuration (metadata and build settings).
* `_toc.yml`: Table of Contents defining the pedagogical itinerary.
* `references.bib`: BibTeX file containing academic sources cited (APA 7).

## 👨‍🏫 Academic Team

* **Daniel Losada Iglesias** (Coordinator) – University of the Basque Country / Euskal Herriko Unibertsitatea.
* **Héctor Galindo**.
* **Lucía Campo**.

*Developed for the Master's in Digital Education (UPV/EHU).*


## 👥 Author

**Developed by Daniel Losada**

[![GitHub](https://img.shields.io/badge/GitHub-danloi2-181717?style=for-the-badge&logo=github)](https://github.com/danloi2)
[![Researcher EHU](https://img.shields.io/badge/Researcher-EHU-blue?style=for-the-badge&logo=researchgate)](https://github.com/danloi2)

### Quick Tips for your MyST setup:
* **Hero Component:** Since you are using `:::{hero}`, ensure your `_config.yml` or custom CSS is set up to handle that specific class for the "orange" accent to display correctly.
* **Mermaid Diagrams:** Ensure the `sphinxcontrib-mermaid` extension is enabled in your configuration to render the `gitGraph` you included in the index.

## Personal Note
BASE_URL="/zonauex/avuex/pluginfile.php/2761687/mod_resource/content/2/artifact" myst build --html
zip `_build/html` folder

