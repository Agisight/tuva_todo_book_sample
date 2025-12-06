# Tuva Todo Bichig Temple Corpus

![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)
![Language: Tuvan](https://img.shields.io/badge/Language-Tuvan-green)
![Language: Oirat](https://img.shields.io/badge/Language-Oirat_(xal)-blue)
![Script: Todo_Bichig](https://img.shields.io/badge/Script-Todo_Bichig-orange)

## 📄 Abstract
This repository contains a digital dataset of Buddhist manuscripts written in the **Oirat Clear Script (Todo Bichig)**. The materials originate from the Buddhist heritage of the **Tyva Republic** (the Russian Federation).

This pilot dataset consists of **some digitized pages** (images) collected from Buddhist temples in Tuva. It is intended for:
* **Archival purposes:** Preserving endangered texts.
* **Computer Vision:** Training OCR/HTR models for vertical scripts.
* **Linguistic Analysis:** Study of Oirat texts in the Tuvan tradition.

## 📂 Dataset Structure

The repository is organized as follows:

* 📁 **tuva_todo_book_sample/**
  * 📁 **data/**
    * 📁 **images/** — Raw images (e.g., `doc_01.jpg`)
    * 📁 **annotations/** — *(Future)* Text transcriptions
  * 📄 **metadata.json** — Technical description
  * 📁 **parse/** — AI parse-transcriptions-translations results (by Gemini)
  * 📄 **README.md** — This documentation

## 📍 Metadata & Provenance

* **Language:** Oirat (ISO 639-3: `xal`), Tuvan (ISO 639-3: `tyv`)
* **Script:** Todo Bichig (Clear Script) - Vertical
* **Region:** Republic of Tuva, the Russian Federation
* **Source Type:** Buddhist Temple Archives
* **Data Size:** 11 Images (Pilot)

## 🔓 License
This dataset is licensed under the **MIT**.
You are free to share and adapt the material, provided you give appropriate credit.

## 📚 Citation
If you use this dataset, please cite:

```bibtex
@misc{tuva_todo_sample_2025,
  author = {Agisight},
  title = {Tuva Todo Bichig Temple Corpus},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\\url{[https://github.com/Agisight/tuva_todo_book_sample](https://github.com/Agisight/tuva_todo_book_sample)}}
}
