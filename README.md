# Multi-Disease Diagnosis from Fundus Images

## Project Overview
Fundus imaging is a critical tool for assessing eye health, enabling the diagnosis of conditions such as glaucoma, diabetic retinopathy, and hypertension. This project aims to develop an innovative system capable of multi-disease diagnosis from fundus images.

## Methodology
The project employs a multi-step approach:

1. **Preprocessing**  
   Fundus images are enhanced using **Contrast Limited Adaptive Histogram Equalization (CLAHE)** to improve clarity and highlight discriminative features.

2. **Model Architecture**  
   Advanced deep learning models **VGG16** and **ResNet** are utilized, augmented with an **attention mechanism**. This enhancement focuses on improving the detection of small, subtle features relevant to various eye diseases.

3. **Transfer Learning**  
   The preprocessed images are used to fine-tune the networks, aiming to overcome common limitations associated with transfer learning.

4. **Cross-Dataset Validation**  
   To increase dataset diversity and ensure robust model performance, **cross-validation across multiple datasets** is performed. This approach defines training and test splits in a way that maximizes generalization.

## Expected Impact
The proposed system is designed to:

- Enable **accurate and fast early diagnosis** of multiple eye diseases.
- Provide a **robust tool for ophthalmologists** and medical professionals.
- Contribute **novel methods to the literature** on medical image analysis and multi-disease classification.

## Technologies & Tools
- **Deep Learning Frameworks:** TensorFlow / PyTorch
- **Preprocessing:** OpenCV, CLAHE
- **Model Architectures:** VGG16, ResNet with Attention Mechanisms
- **Evaluation:** Cross-dataset validation, standard classification metrics

## Usage
1. Preprocess fundus images using CLAHE.
2. Feed the preprocessed images into the attention-augmented VGG16 or ResNet model.
3. Obtain predictions for multiple eye diseases.
4. Evaluate model performance using cross-dataset validation.

## Future Work
- Integration of additional datasets to enhance model generalization.
- Deployment as a web-based diagnostic assistant for ophthalmology clinics.
- Exploration of other attention mechanisms to further improve small-lesion detection.

---

**Note:** This project is intended for research and clinical support purposes. It does not replace professional medical diagnosis.
