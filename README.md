# CNN_MRI
# Brain Tumor Classification using VGG16 and Grad-CAM

This project uses a Convolutional Neural Network based on VGG16 to classify brain MRI images into four categories:
- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- No Tumor

In addition to classification, the model provides visual explanations using Grad-CAM heatmaps.

## Project Overview

Brain tumor detection is an important task in medical imaging. This project uses deep learning to:
- Automatically classify MRI scans
- Improve interpretability using heatmaps
- Highlight important regions influencing predictions

## Model Details

- Base Model: VGG16 (Pretrained on ImageNet)
- Architecture: Transfer learning with custom classification layers
- Classes: 4 (Glioma, Meningioma, Pituitary, No Tumor)
- Framework: TensorFlow / Keras

## Grad-CAM Visualization

The model generates Grad-CAM heatmaps to show which parts of the MRI image contributed most to the prediction.

### Example Output

- Original MRI Image
- Grad-CAM Heatmap
- Overlayed Image

## Sample Result

![Grad-CAM Output](brain canc3r folder)

<img width="601" height="618" alt="image" src="https://github.com/user-attachments/assets/0bdf9ea1-99c9-4a53-92a2-f8697c24b63c" />
<img width="492" height="472" alt="image" src="https://github.com/user-attachments/assets/c4382dff-a09c-4320-bd34-fc40126edea8" />
<img width="642" height="656" alt="image" src="https://github.com/user-attachments/assets/7b4b6cbf-724b-4dcb-ba93-809f2f51e18c" />
<img width="273" height="301" alt="image" src="https://github.com/user-attachments/assets/06380adf-2327-455b-9690-67894ca3caae" />

## Features

- Multi-class brain tumor classification
- Transfer learning using VGG16
- Grad-CAM explainability
- Visualization of model attention

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/CNN_MRI.git
cd CNN_MRI
```

## Results

The trained VGG16-based model was able to successfully classify brain MRI images into four categories: Glioma, Meningioma, Pituitary, and No Tumor.

The model demonstrated good performance on the validation dataset, correctly identifying tumor types in most cases. The use of transfer learning helped improve accuracy and reduced training time.

In addition to classification, Grad-CAM was used to generate heatmaps for model interpretability. These heatmaps highlight the regions of the MRI image that contributed most to the model’s prediction.

### Key Observations

- The model is able to distinguish between different tumor types with reasonable accuracy.
- Grad-CAM visualizations show that the model focuses on relevant regions in the brain scans.
- Heatmaps provide useful insights into the decision-making process of the model.
- The combination of classification and visualization makes the model more reliable and interpretable.

### Sample Output

The output consists of:
- Predicted class label (Glioma, Meningioma, Pituitary, or No Tumor)
- Confidence score (if implemented)
- Grad-CAM heatmap
- Overlay of heatmap on the original MRI image

<img width="955" height="456" alt="image" src="https://github.com/user-attachments/assets/f46fa38e-c767-4fdb-bf9b-2da9829e3ef8" />

  
