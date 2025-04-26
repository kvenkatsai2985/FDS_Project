
# Pneumothorax Detection

In this project uses deep learning to detect the **Pneumothorax** (collapsed lung) in chest X-ray images.

## Dataset

- **Source:** SIIM-ACR Pneumothorax Segmentation (Kaggle)
- **Format:** DICOM images with mask annotations

## Workflow

1. we Loaded and preprocess DICOM images.
2. Build classification and segmentation models (e.g., U-Net, ResNet). 
3. Train, evaluate, and visualize predictions.

## Tools

- Python, Keras, TensorFlow, OpenCV, Pydicom

## How to Use

1. Download dataset from Kaggle  
2. Run notebooks in order:  
   - `Pneumothorax1.ipynb` (EDA + Preprocessing)  
   - `Pneumothorax2.ipynb` (Model Training)  
   - `Pneumothorax3.ipynb` (Predictions + Visualization)

## Results

- Accurate segmentation and detection of pneumothorax
- Good performance using U-Net and transfer learning
