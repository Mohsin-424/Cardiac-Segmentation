# 🫀 ACDC Cardiac MRI Dataset

## Overview

The **ACDC (Automated Cardiac Diagnosis Challenge) dataset** is a publicly available medical imaging dataset designed for the **segmentation and analysis of cardiac structures from MRI images**. It is widely used in research for developing and evaluating deep learning algorithms for **cardiac image segmentation**.

The dataset provides **cardiac MRI scans along with expert-annotated ground truth masks** for three important anatomical structures:

* **Left Ventricle (LV)**
* **Right Ventricle (RV)**
* **Myocardium (MYO)**

These annotations allow supervised learning models to accurately segment cardiac structures and assist in automated cardiac diagnosis.

---

## Dataset Description

The dataset contains **100 patient cardiac MRI scans** collected at the **University Hospital of Dijon (France)**. Each patient case includes manual segmentation annotations provided by clinical experts.

### Segmentation Labels

| Label | Structure            |
| ----- | -------------------- |
| 0     | Background           |
| 1     | Right Ventricle (RV) |
| 2     | Myocardium (MYO)     |
| 3     | Left Ventricle (LV)  |

---

## Dataset Contents

Each patient folder typically contains:

* **Cardiac MRI images**
* **Ground truth segmentation masks**
* **Two cardiac phases:**

  * **End-Diastole (ED)**
  * **End-Systole (ES)**

These phases represent the heart during relaxation and contraction.

---

## Dataset Structure

```
ACDC_Dataset/
│
├── patient001/
│   ├── patient001_frame01.nii.gz
│   ├── patient001_frame01_gt.nii.gz
│   ├── patient001_frame12.nii.gz
│   └── patient001_frame12_gt.nii.gz
│
├── patient002/
│
└── patient100/
```

---

## Data Format

The dataset is provided in **NIfTI (.nii / .nii.gz)** format, a standard format used in medical imaging.

Each case includes:

* **MRI Image Volume**
* **Ground Truth Segmentation Mask**

These masks contain pixel-level annotations for cardiac structures.

---

## Applications

The ACDC dataset is commonly used for:

* Cardiac MRI segmentation
* Deep learning model training
* Medical image analysis
* Automated cardiac disease diagnosis
* Benchmarking segmentation algorithms

---

## Citation

If you use the dataset in research, please cite the original **Automated Cardiac Diagnosis Challenge (ACDC)** publication.

---

## License

The ACDC dataset is provided **for research and educational purposes only**. Users must follow the official dataset terms and conditions when using the data.

---

## Contact

**Author:** Engr. Muhammad Mohsin
**Field:** Artificial Intelligence / Medical Image Segmentation
**Email:** mohsinpu24@gmail.com
**GitHub:** https://github.com/Mohsin-424
