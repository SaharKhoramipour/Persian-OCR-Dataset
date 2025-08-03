# Persian OCR Dataset – Omni-Font Synthetic Dataset for YOLO
This repository contains a high-quality synthetic dataset developed for character-level recognition of Persian script using YOLO object detection models. The dataset is specifically designed to address the challenges of omni-font recognition across formal, informal, and handwritten-style Persian fonts.

---

##  Associated Research

This dataset was created as part of the following peer-reviewed publication:

“Towards Omni-Font Optical Character Recognition (OCR) for Persian Script Using the YOLO Object Detection Model”  
Majlesi Journal of Electrical Engineering (MJEE), 2025 
[DOI: 10.57647/j.mjee.2025.17063](https://doi.org/10.57647/j.mjee.2025.17063)

The paper introduces a scalable method for Persian OCR using object detection, with special attention to whitespace characters, font generalization, and character-level recognition in complex scripts.

---

## Dataset Highlights

- 70 total character classes, including:
  - 32 Persian letters in contextual forms (isolated, initial, medial, final)
  - Arabic-based characters used in Persian (e.g., آ، أ، ؤ، ئ، ء)
  - Digits (۰–۹)
  - Punctuation marks (، ؛ ؟ ! . : () [] « »)
  - Mathematical symbols (+ – = × ÷ < > /)
  - Regular space and non-breaking space

- Fonts included in this version:
  - Arial
  - BKamran
  - BLotus  
  (More fonts will be added in future updates.)

- Typographic diversity: Formal, informal, and handwriting-like fonts  
- Data split: Each font includes train, validation, and test sets  
- Annotation format: YOLO format (bounding box + class ID)  

---

##  Dataset Structure

Each font directory follows the structure below:

Persian-OCR-Dataset/
│
├── Arial/
│   ├── AA/
│   │   ├── images/
│   │   │   ├── train/
│   │   │   ├── val/
│   │   │   └── test/
│   │   ├── labels/
│   │   │   ├── train/
│   │   │   ├── val/
│   │   │   └── test/
│   │   ├── Label_names.yaml
│   │   └── Label_names2.yaml
│   └── Font_Names_and_Numbers.txt
│   └── Label_names.yaml
│   └── List_of_Strings.txt
├── BKamran/
│   ├── AA/
│   │   ├── images/
│   │   │   ├── train/
│   │   │   ├── val/
│   │   │   └── test/
│   │   ├── labels/
│   │   │   ├── train/
│   │   │   ├── val/
│   │   │   └── test/
│   │   ├── Label_names.yaml
│   │   └── Label_names2.yaml
│   └── Font_Names_and_Numbers.txt
│   └── Label_names.yaml
│   └── List_of_Strings.txt
├── BLotus/
│   ├── AA/
│   │   ├── images/
│   │   │   ├── train/
│   │   │   ├── val/
│   │   │   └── test/
│   │   ├── labels/
│   │   │   ├── train/
│   │   │   ├── val/
│   │   │   └── test/
│   │   ├── Label_names.yaml
│   │   └── Label_names2.yaml
│   └── Font_Names_and_Numbers.txt
│   └── Label_names.yaml
│   └── List_of_Strings.txt.cff

Each `AA/` subfolder corresponds to one group of generated strings from the target font.  
YAML and TXT files define class names, character mappings, and bounding box details.  

---

##  Model Compatibility

This dataset is compatible with:
- YOLOv5, YOLOv8
- Any object detection model supporting standard YOLO format

---

##  License

This dataset is released under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
You may copy, adapt, and use this dataset for any purpose, including commercial use, with proper attribution to the authors and source paper.

© 2025 Mojtaba Gandomkar, Sahar Khoramipour

---

##  Contributions

We welcome contributions such as:
- Additional fonts (especially handwritten ones)
- Annotated word-level datasets
- Utility scripts and improvements

Please feel free to open an issue or pull request, or contact us via the email listed in the paper.

---
