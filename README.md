# Adversarial Camouflage in Autonomous Vehicles

Thesis notebooks for adversarial camouflage in autonomous vehicles (YOLOv8 + experiments).

## Notebooks (open directly in Colab)
- **final.ipynb** – end-to-end workflow and results  
  👉 https://colab.research.google.com/github/Sumanjali23/Adversarial-camouflage-in-Autonomous-Vehicles/blob/main/notebooks/final.ipynb
  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sumanjali23/Adversarial-camouflage-in-Autonomous-Vehicles/blob/main/notebooks/final.ipynb)


- **YOLOv8_Stage3_Adversarial_Training.ipynb** – training + adversarial experiments  
  👉 https://colab.research.google.com/github/Sumanjali23/Adversarial-camouflage-in-Autonomous-Vehicles/blob/main/notebooks/YOLOv8_Stage3_Adversarial_Training.ipynb
  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sumanjali23/Adversarial-camouflage-in-Autonomous-Vehicles/blob/main/notebooks/YOLOv8_Stage3_Adversarial_Training.ipynb)


## How to run (Colab)
1. Open a notebook using one of the links above.
2. Run the setup cells to install dependencies.
3. Download the dataset (see below) and put it under `data/`.

## Data (not stored in this repo)
Large datasets and weights are **excluded** from git (`data/`, `runs/`, `weights/` are ignored).

**Option A – Google Drive via gdown**
```python
!pip install -q gdown
DATA_ID = "1YzRfUeD6LOru8fdzQi4ElmkqpibxarEK"
!gdown {DATA_ID} -O data.zip
!unzip -q data.zip -d data/
```
## Run locally (optional)
```bash
pip install -r requirements.txt

# 🚗 Adversarial Camouflage in Autonomous Vehicles

> Thesis research exploring how adversarial camouflage patterns can fool YOLOv8-based object detection systems in autonomous vehicles.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

## 📌 Overview

This project investigates **adversarial camouflage attacks** on autonomous vehicle perception systems. Using **FGSM** and **PGD** adversarial attack techniques combined with **YOLOv8**, the research demonstrates how carefully crafted perturbations can evade detection — posing real-world safety risks.

---

## 🧪 Notebooks

| Notebook | Description | Open |
|---|---|---|
| `final.ipynb` | End-to-end workflow and results | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sumanjali23/Adversarial-camouflage-in-Autonomous-Vehicles/blob/main/notebooks/final.ipynb) |
| `YOLOv8_Stage3_Adversarial_Training.ipynb` | YOLOv8 training + adversarial experiments | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sumanjali23/Adversarial-camouflage-in-Autonomous-Vehicles/blob/main/notebooks/YOLOv8_Stage3_Adversarial_Training.ipynb) |

---

## ⚙️ Tech Stack

- **Model**: YOLOv8 (Ultralytics)
- **Attack Methods**: FGSM, PGD
- **Framework**: PyTorch
- **Platform**: Google Colab

---

## 🚀 Getting Started

### Run on Colab (Recommended)
Click the Colab badges above to open notebooks directly in your browser — no setup needed.

### Run Locally
```bash
pip install -r requirements.txt
```

### Dataset Setup
Large datasets are excluded from git. Download via gdown:
```bash
pip install gdown
DATA_ID="1YzRfUeD6LOru8fdzQi4ElmkqpibxarEK"
gdown $DATA_ID -O data.zip
unzip -q data.zip -d data/
```

---

## 📁 Project Structure
