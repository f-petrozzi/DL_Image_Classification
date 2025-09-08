# Deep Learning for Chest X-ray Disease Classification

This project applies deep learning to classify chest X-rays into multiple disease categories simultaneously. The objective was to build models capable of handling **multi-label medical image classification** using a subset of the NIH Chest X-ray dataset.

## Project Overview
- **Problem**: Detect the presence of multiple thoracic pathologies in chest X-rays  
- **Dataset**: NIH Chest X-ray dataset (subset only, not included here)  
- **Approach**:  
  - Built a baseline CNN from scratch  
  - Applied transfer learning with ResNet-50 for improved performance  
- **Evaluation**: Performance measured using Receiver Operating Characteristic (ROC) curves, Precision-Recall (PR) curves, and class-level metrics  

## Repository Contents
- `notebooks/` — Jupyter Notebook with full training and evaluation pipeline  
- `report/` — Final project report (PDF)  
- `presentation/` — Project slides (PowerPoint)  

## Tools and Libraries
- Python 3.x  
- PyTorch & Torchvision  
- Jupyter Notebook  
- Matplotlib / Seaborn for visualization  

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/f-petrozzi/image_classification_DL.git
   cd image_classification_dl
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook notebooks/chest_xray_classification.ipynb
   ```
4. Supply your own copy of the NIH Chest X-ray dataset (download separately from NIH/Kaggle). Place image data in a local folder and update the notebook paths.

## Data Access
The dataset is not included due to size and licensing. You can download it from:  
- [NIH Clinical Center](https://nihcc.app.box.com/v/ChestXray-NIHCC)  
- [Kaggle Dataset](https://www.kaggle.com/datasets/nih-chest-xrays/data)

## Suggested Extensions
- Evaluate more advanced models (DenseNet, EfficientNet).  
- Use Grad-CAM or other explainability methods for interpretability.  
- Implement data augmentation and class rebalancing strategies.  

## License
MIT License © 2025 Fabrizio Petrozzi
