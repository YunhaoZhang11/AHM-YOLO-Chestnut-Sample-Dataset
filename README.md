# AHM-YOLO-Chestnut-Sample-Dataset
Sample subset of the chestnut maturity dataset used in the paper "Chestnut Maturity Detection and Segmentation in Orchard Environments Using an Improved YOLO-Based Method". Only representative sample images and annotation examples are included.
# AHM-YOLO Chestnut Maturity Sample Dataset

This repository provides a representative **sample subset** of the dataset used in the paper:

**"Chestnut Maturity Detection and Segmentation in Orchard Environments Using an Improved YOLO-Based Method".**

The purpose of this repository is to demonstrate the **data structure**, **annotation format**, and **typical image conditions** used in the study, in accordance with transparency requirements of peer-reviewed publications.

Only **a small portion** of the original dataset is released here.  
The complete dataset cannot be published due to orchard confidentiality agreements, ongoing research plans, and deployment considerations for orchard automation.

AHM-YOLO-Chestnut-Sample-Dataset/
│
├── README.md
│
├── images/ # Example chestnut images (22 samples)
│     └── ...
│
└── labels/ # Corresponding annotation JSON files

└── ...


---

## 📝 Dataset Description

This sample dataset includes:

- **22 representative orchard RGB images**
- Two chestnut maturity categories: **unripe** and **ripe**
- **Polygon-based instance segmentation annotations** stored in `.json` format
- Various orchard scene conditions:
  - Leaf and branch occlusion  
  - Dense fruit clusters  
  - Different shooting distances and angles

This sample illustrates the **annotation standard** and **data organization** used in the full study.

---

## ⚠️ Full Dataset Availability

The complete dataset **cannot be made publicly available** due to:

1. Confidentiality agreements with orchard partners  
2. Ongoing research and extended experiments based on the same dataset  
3. Planned lightweight deployment of AHM-YOLO in commercial orchards  
4. Protection of orchard location and sensitive raw visual data  

However, a limited portion of the dataset can be shared **upon reasonable request** for academic research.

---

## 📤 How to Use This Sample Dataset

1. Download images and labels  
2. Use JSON files to understand:
   - annotation format  
   - polygon structure  
   - instance segmentation rules  
3. Convert JSON annotations to YOLO segmentation format if needed  
4. Use samples to test:
   - training scripts  
   - data loaders  
   - visualization pipelines  

Note: This subset is **not sufficient for training** but is suitable for demonstrating the data standard.



## 📧 Contact

For dataset access requests and inquiries:

**Corresponding Author:**  
Juan Li  
College of Mechanical and Electronic Engineering, Qingdao Agricultural University  
Email: liuan@gau.edu.cn


