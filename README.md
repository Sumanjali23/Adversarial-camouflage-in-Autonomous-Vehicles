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
📦 Adversarial-camouflage-in-Autonomous-Vehicles
┣ 📂 notebooks/
┃ ┣ 📓 final.ipynb
┃ ┗ 📓 YOLOv8_Stage3_Adversarial_Training.ipynb
┣ 📄 requirements.txt
┗ 📄 .gitignore

> ⚠️ `data/`, `runs/`, and `weights/` directories are git-ignored due to size.

---

## 🔬 Topics

`computer-vision` `adversarial-attacks` `yolov8` `autonomous-vehicles` `pgd` `fgsm` `pytorch` `deep-learning`

---

## 📜 License

MIT License — see [LICENSE](LICENSE) for details.

---

<p align="center">Made with 🔬 by <a href="https://github.com/Sumanjali23">Grace Sumanjali Pagolu</a></p>
