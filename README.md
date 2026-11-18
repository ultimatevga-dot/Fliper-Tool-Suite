# Fliper Tool Suite

<div align="center">

![Fliper Tool Suite Banner](https://img.shields.io/badge/FliperOS-Tool%20Suite-3B8ED0?style=for-the-badge&logo=python&logoColor=white)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![CustomTkinter](https://img.shields.io/badge/UI-CustomTkinter-darkgreen?style=flat-square)](https://github.com/TomSchimansky/CustomTkinter)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

*A desktop application designed to extract and translate EmulationStation/Batocera game descriptions and automatically convert media assets into the exact FliperOS folder structure.*

</div>

---

## 📌 Features / Características

* **🌐 Multi-language Interface**: Supports English, Spanish, French, Italian, and Portuguese with automatic system language detection or manual switching.
* **📝 XML Text Extractor & Translator**: Parses `gamelist.xml` files, extracts game titles and descriptions, and translates them seamlessly into your target language using neural machine translation (Argos Translate).
* **🖼️ Media Converter & Organizer**: Automatically scans Batocera system folders, cleans up common suffixes (`-image`, `-thumb`, `-marquee`, `-video`, etc.), and re-organizes them into FliperOS structure (`media/box/`, `media/preview/`, `media/logo/`, etc.).
* **⚡ Modern GUI**: Built with `CustomTkinter` featuring a clean, dark-themed, multithreaded interface that keeps the application responsive during heavy text and media processing.

---

## 🛠️ Requirements & Installation / Requisitos e Instalación

1. Make sure you have **Python 3.8+** installed on your system.
2. Install the required dependencies via terminal:
   ```bash
   pip install customtkinter argostranslate langdetect

<img width="839" height="875" alt="preview" src="https://github.com/user-attachments/assets/430e6275-a572-4d37-af65-719f23510f30" />




   
