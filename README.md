# OPD-LASEX-GMTJ Tools

Welcome to the repository for tools developed by the **LASEX/OV** group during observations at the Observatório do Pico dos Dias (OPD), specifically for the **SPARC4** instrument on the 1.6m telescope.  
This repository is intended to assist current and future observers in efficiently planning, selecting, and analyzing extragalactic targets.

---

## About LASEX/OV

Extragalactic Astrophysics is one of the most active fields in contemporary Astronomy, and at the Valongo Observatory we created the **LASEX** (Laboratório de Astrofísica Extragaláctica) group in 2013 to foster collaboration among students, postdocs, and faculty.  
We work observationally across almost the entire electromagnetic spectrum — from radio to X-ray — and our research covers galaxy formation, evolution, and the role of dark matter, among other key topics.

LASEX researchers are actively involved in projects at major observatories like Keck, VLT/ESO, and ALMA.

Learn more about our group here: [lasex-valongo.com](http://lasex-valongo.com)

---

## About SPARC4

**SPARC4** (Simultaneous Polarimeter and Rapid Camera in 4 bands) is a new instrument installed on the 1.6m telescope at OPD, developed through a collaboration between INPE and LNA.  
Since its first light in 2022, SPARC4 has been successfully commissioned and is now fully operational, offering simultaneous imaging in four optical bands (**griz**) and polarimetry capabilities.  
A full data reduction pipeline in Python is available, and the instrument is now an official facility of OPD starting from semester **2024A**.

---

## Project Science Focus

Our observing program focuses on studying **50 Milky Way analog galaxies** to better understand the distribution of **dark matter** in galaxies similar to our own.  
By combining SPARC4's multi-band imaging with deep infrared data, we perform detailed stellar population analyses to decompose rotation curves and isolate the dark matter contribution.

---

## Available Tools

We currently provide **three Jupyter Notebooks**, each designed to streamline a specific part of the observing and data preparation workflow:

| Notebook | Purpose | Link |
|:---------|:--------|:-----|
| **Finders** | Generate finder charts for galaxies to preview morphology and size before observations. | [Finders.ipynb](./Finders.ipynb) |
| **OPDsample** | Filter and select galaxies for the sample, excluding targets already observed in previous cycles. | [OPDsample.ipynb](./aOPDsample.ipynb) |
| **Counts** | Calculate the exposure time needed to achieve the desired signal-to-noise ("contagem") for each target. | [Counts.ipynb](./Counts.ipynb) |

We also provide a **galaxy list file** ([S4G_1.csv](./S4G_1.csv)) needed by the Finders notebook.

## Guide Spreadsheet

You can download and use the example spreadsheet as a guide:
[![Spreadsheet](https://img.shields.io/badge/Download-Spreadsheet-blue?logo=microsoft-excel)](./Example Spreadsheet.csv)


---

## Tutorial

[![Watch the tutorial](https://img.shields.io/badge/Watch-Tutorial-red?logo=youtube)](https://drive.google.com/file/d/15Jnu3qd1T8AuGmhn2P0TUGlE4PRaZz6v/view?usp=sharing)

---

## Contributions

Contributions to this repository are very welcome!  
You can:

- Open Issues with feature requests, bugs, or suggestions.
- Submit Pull Requests with improvements, new notebooks, or corrections.
- Fork the repository and adapt the tools for your own observing runs (just don't forget to give credit).

Future upgrades may include new tools for data reduction and advanced planning features.

---

## Contact

For questions, feedback, or collaboration opportunities, feel free to contact the maintainers or reach out to the group:

- [LASEX/OV official website](http://lasex-valongo.com)

Or open an Issue directly here on GitHub.

---

## Authors

- **Gabriel Pampolha**
- **Juan Maldonado**
- **Maria Cavalcante**
- **Thiago Bueno**

---

## Installation

Clone the repository and install the dependencies listed in `requirements.txt`:

```bash
git clone https://github.com/Astro-cat-mistry/OPD-LASEX-GMTJ.git
cd OPD-LASEX-GMTJ
pip install -r requirements.txt


Clone the repository and install the dependencies listed in `requirements.txt`:

```bash
git clone https://github.com/Astro-cat-mistry/OPD-LASEX-GMTJ.git
cd OPD-LASEX-GMTJ
pip install -r requirements.txt


