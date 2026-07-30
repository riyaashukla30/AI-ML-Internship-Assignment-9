# Cat vs Dog Image Classification using CNN

## Objective
The objective of this project is to build a Convolutional Neural Network (CNN) model to classify images into two categories: cats and dogs. The model learns patterns from image data and predicts the correct class based on learned features.

## 📂 Dataset
Dataset Name: CIFAR-10 Dataset (Filtered)  

Source: Kaggle  

Dataset Link:  
https://www.kaggle.com/datasets/cifar-10/cifar10-python  

Note: The CIFAR-10 dataset contains 10 classes. For this project, only **cat and dog classes** were used. The dataset is not included in this repository.

## 🛠️ Libraries Used
- NumPy  
- Matplotlib  
- Seaborn  
- TensorFlow / Keras  
- Scikit-learn  

### Modules Used
- Conv2D  
- MaxPooling2D  
- Flatten  
- Dense  
- confusion_matrix  
- classification_report  

## ⚙️ Methodology
- Loaded the CIFAR-10 dataset  
- Filtered only cat (3) and dog (5) classes  
- Converted labels into binary format (Cat = 0, Dog = 1)  
- Normalized pixel values (0–1)  
- Built CNN model using convolution, pooling, and dense layers  
- Trained the model for 5 epochs  
- Evaluated the model using accuracy, confusion matrix, and classification report  

## 🧠 Model Architecture
- Input Layer: 32x32x3 images  
- Conv Layer 1: 32 filters (ReLU)  
- MaxPooling Layer  
- Conv Layer 2: 64 filters (ReLU)  
- MaxPooling Layer  
- Flatten Layer  
- Dense Layer: 64 neurons (ReLU)  
- Output Layer: 1 neuron (Sigmoid)  

## 📊 Results
- Achieved approximately **74% accuracy** on test data  
- Accuracy improved over training epochs  
- Loss decreased during training  
- Model performed well on most test images  

## ✅ Conclusion
This project demonstrates image classification using CNN. The model successfully classifies cat and dog images with good accuracy. CNN helps in extracting important spatial features from images. The performance can be further improved by using larger datasets, data augmentation, or deeper architectures. However, CNN models require more computational power and training time.

##  Repository Structure
Assignment-9/  
│── Assignment-9.ipynb  
│── README.md  

##  Author
**Name:** Riya Shukla  
**Registration Number:** 23BCE11293  
**Application Number:** IN26012655  
**Batch Number:** 2(B)
