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

- Fonts in v1.0:
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

```
Persian-OCR-Dataset/
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
│   ├── Font_Names_and_Numbers.txt
│   ├── Label_names.yaml
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
│   ├── Font_Names_and_Numbers.txt
│   ├── Label_names.yaml
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
│   ├── Font_Names_and_Numbers.txt
│   ├── Label_names.yaml
│   └── List_of_Strings.txt.cff
```

---

##  Format

- Annotations in YOLO format
- Compatible with YOLOv5, YOLOv8
- Each image includes bounding boxes and class IDs

---

##  License

This dataset is distributed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

With attribution to: Mojtaba Gandomkar and Sahar Khoramipour 

---

##  Citation

If you use this dataset in your research, please cite the following paper:

> Gandomkar, M., & Khoramipour, S. (2025).  
> Towards Omni-Font OCR for Persian Script using YOLO.  
> Majlesi Journal of Electrical Engineering.  
> DOI: 10.57647/j.mjee.2025.17063

---

##  Contributions

We welcome contributions such as:
- Additional fonts (especially handwritten ones)
- Annotated word-level datasets
- Utility scripts and improvements

Please feel free to open an issue or pull request, or contact us via the email listed in the paper.

---
