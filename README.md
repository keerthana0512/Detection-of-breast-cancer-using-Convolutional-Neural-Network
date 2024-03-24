# Detection of Breast Cancer using Convolutional Neural Network

### Objective
The primary objective of this project is to develop a system capable of detecting breast cancer using machine learning algorithms based on image processing techniques.

### Problem Statement
- Understand the challenges associated with identifying breast tumors.
- Explore various image processing methods for early detection.
- Assess the effectiveness of CNN algorithms in detecting breast cancer.

### Scope of Work
- Utilize image processing techniques and machine learning algorithms for breast cancer detection.
- Focus on identifying symptoms such as breast lumps, changes in size, shape, or appearance of the breast.
- Employ convolutional neural networks for accurate classification of cancerous and non-cancerous cells.

## System Requirements Specifications

### Software Requirements
- Operating System: Windows 10
- Front end tools: Python, Data Analytics
- Web browser: Google Chrome
- Software: Jupyter Notebook

### Hardware Requirements
- Machine name: HP
- Processor: Intel Core i5, 2.50 GHz
- RAM: 4 GB

### Methodology
The project follows a structured workflow:
1. **Data Collection**: Utilize Kaggle dataset consisting of 277,524 50x50 pixel RGB digital image patches derived from breast histopathology samples.
2. **Image Preprocessing**: Apply compression techniques and image processing to remove redundant pixels and enhance data quality.
3. **Feature Extraction**: Use pre-trained CNN models such as ResNet-50, InceptionV3, and VGG-16 to extract features from images.
4. **Classification**: Develop a CNN classifier (CancerNet) using Keras to train on the dataset and classify images as benign or malignant.
5. **Evaluation**: Assess the performance of the model using validation and testing datasets.

### Dataset Split
The dataset is split into three categories:
1. Training set: 80% of images used for model training.
2. Validation set: 10% of images for model validation.
3. Testing set: 10% of images for evaluating model performance.

### CancerNet Architecture
CancerNet architecture includes:
- Use of exclusively 3x3 CONV filters.
- Stacking multiple 3x3 CONV filters prior to max-pooling.
- Utilization of depth-wise separable convolution for improved performance.

## Conclusion

This project demonstrates the feasibility of using convolutional neural networks for breast cancer detection. By leveraging image processing techniques and machine learning algorithms, accurate classification of cancerous and non-cancerous cells can be achieved, contributing to early diagnosis and improved patient outcomes.

