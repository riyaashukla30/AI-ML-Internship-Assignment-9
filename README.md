# Cat vs Dog Image Classification using CNN

## AI/ML Internship – Assignment 9

**Name:** Riya Shukla  
**Registration Number:** 23BCE11293  
**Application Number:** IN26012655  
**Batch Number:** 2(B)

---

## 📌 Objective

The objective of this project is to develop a Convolutional Neural Network (CNN) model to classify images into two categories: cats and dogs. The model learns important visual features such as edges, textures, and patterns for accurate classification.

---

## 📊 Dataset

Dataset used: CIFAR-10 (Filtered)

🔗 https://www.kaggle.com/datasets/cifar-10/cifar10-python

Note: The CIFAR-10 dataset contains 10 classes. For this project, only **cat and dog classes were filtered** to meet the assignment requirement.

---

## 🛠️ Libraries Used

- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## ⚙️ Methodology

1. Loaded CIFAR-10 dataset using TensorFlow  
2. Filtered cat (3) and dog (5) classes  
3. Converted labels into binary format (Cat = 0, Dog = 1)  
4. Normalized pixel values (0–1)  
5. Built CNN model using:
   - Convolutional Layers  
   - MaxPooling Layers  
   - Dense Layers  
6. Trained the model for 5 epochs  
7. Evaluated model performance  

---

## 📈 Results

- Achieved ~74% accuracy on test data  
- Model performance improved over epochs  
- Validation accuracy followed training accuracy  
- Loss decreased gradually  

---

## 🔍 Model Evaluation

- Accuracy Score  
- Confusion Matrix  
- Classification Report  
- Accuracy & Loss Graphs  

---

## Conclusion

The CNN model successfully classifies cat and dog images with good accuracy. It effectively learns image features through convolution layers. The performance can be further improved by using larger datasets, applying data augmentation, and building deeper neural network architectures.

---

## ⚠️ Note

Due to dataset download restrictions and runtime limitations, the CIFAR-10 dataset was used and filtered to include only cat and dog classes.

---
