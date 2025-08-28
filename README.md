# Brain Tumor Classification Project (7PAM2002)

This repository contains code for classifying brain tumors using T1-weighted MRI images with a custom CNN, EfficientNetB0, and ResNet50, developed for the 7PAM2002 module.

## Files
- `CNN_final.py`: Custom CNN with Keras Tuner (150x150 input).
- `EfficientNetB0_Final.py`: EfficientNetB0 with three-phase transfer learning (224x224 input).
- `Restnet_Final.py`: ResNet50 with two-phase training (224x224 input).

## Requirements
- Python 3.8+
- Install dependencies: `pip install -r requirements.txt

## Dataset
- Source: Brain tumor MRI dataset (`/content/drive/MyDrive/Colab_Datasets/brain-tumor-mri-dataset`)
- Classes: Glioma, Meningioma, No Tumor, Pituitary
- Annotations: `_annotations.csv`

## Usage
1. Mount Google Drive in Colab with the dataset.
2. Run each script to train and evaluate models.
3. Outputs include accuracy (`test_acc`) and classification reports.

## Commits
- Multiple commits show development, including data preprocessing, model tuning, and evaluation.

## Author
Fahim, for 7PAM2002, University of Hertfordshire, 2025.
