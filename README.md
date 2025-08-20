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
DATA_ID = "PASTE_YOUR_DRIVE_FILE_ID"
!gdown --id {DATA_ID} -O data.zip
!unzip -q data.zip -d data/
```
## Run locally (optional)
```bash
pip install -r requirements.txt
