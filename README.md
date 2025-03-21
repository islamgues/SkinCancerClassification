# Skin Cancer Classification
# Overview
This project aims to classify skin cancer images into benign and malignant categories using a Support Vector Machine (SVM) classifier. The model is trained on a dataset of skin lesion images and achieves high accuracy in detecting malignancy.
# Dataset
Examples of data used

![image](https://github.com/user-attachments/assets/f6de6ca3-b1c5-419f-a3a6-6229b57a2bb6)

**Training Data**

![image](https://github.com/user-attachments/assets/82dfeb0e-a9d7-4c0a-a34b-6979d096f6f8)

**Test Data**

![image](https://github.com/user-attachments/assets/ae89123a-1fd1-4e8a-b0d0-2cb9015e4793)

# Data Preprocessing
- Images are loaded and converted to RGB format.
- They are normalized by scaling pixel values between 0 and 1.
- The dataset is shuffled before training.
- Labels: **0 = Benign, 1 = Malignant**
# Model Training
The model is trained using Support Vector Machine (SVM):
- Kernel: linear
- Uses a hinge loss function for optimization.
- Probability estimation enabled.

# Model Performance
**Classification Metrics**
- **Accuracy** 85.2%
- **Precision** 79.5%
- **Recall** 85.7%
- **F1-Score** 82.5%

**Confusion Matrix**

![image](https://github.com/user-attachments/assets/2e65325d-753d-4017-8058-065397b7d387)

# Usage
Executing **SkinCancerClassificationTraining.ipynb** save the model as **SkinCancerDetection.joblib**, then you run **SkinCancer.ipynb** that open UI to test it.

# Future Improvements
- Implement Deep Learning (CNN) for better accuracy.
- Add data augmentation to improve model generalization.
- Develop a web-based interface for easier use.
