# Pneumonia-Detection-ResNet18
Chest X-ray pneumonia classification using ResNet18 and PyTorch. Achieved 74.2% test accuracy with performance evaluation using precision, recall, F1-score, and confusion matrix.
# Pneumonia Detection using ResNet18

## Project Overview
This project uses the ResNet18 deep learning model to classify chest X-ray images into Normal and Pneumonia categories.

## Dataset
Chest X-ray dataset containing:
- NORMAL
- PNEUMONIA

## Model
- ResNet18
- PyTorch
- Google Colab

## Results
- Test Accuracy: 74.2%
- Precision (Pneumonia): 0.71
- Recall (Pneumonia): 1.00
- F1-Score (Pneumonia): 0.83

## Confusion Matrix

| Actual \ Predicted | Normal | Pneumonia |
|----------|----------|----------|
| Normal | 73 | 161 |
| Pneumonia | 0 | 390 |

## Conclusion
The ResNet18 model achieved 74.2% accuracy for pneumonia detection from chest X-ray images. The model showed strong pneumonia detection performance but tended to classify some normal images as pneumonia.
