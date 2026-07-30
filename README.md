# Cat vs Dog Image Classification using Convolutional Neural Networks (CNN)

## Objective
The objective of this project is to build a Convolutional Neural Network (CNN) model to classify images as either cats or dogs. The model learns patterns from image data and predicts the correct class.

Dataset
Dataset Name: CIFAR-10 Dataset (Filtered)

Source: Kaggle

Dataset Link:
https://www.kaggle.com/datasets/cifar-10/cifar10-python

Note: Only cat and dog classes were used. Dataset is not included in this repository.

Libraries Used
NumPy
Matplotlib
Seaborn
TensorFlow / Keras
Scikit-learn

Modules Used
Conv2D
MaxPooling2D
Flatten
Dense
confusion_matrix
classification_report

Methodology
Loaded the CIFAR-10 dataset
Filtered cat and dog classes
Normalized pixel values (0–1)
Built CNN model with Conv2D, MaxPooling and Dense layers
Trained model for 5 epochs
Evaluated model using accuracy, confusion matrix and classification report

Model Architecture
Input Layer: 32x32x3
Conv Layer 1: 32 filters (ReLU)
MaxPooling Layer
Conv Layer 2: 64 filters (ReLU)
MaxPooling Layer
Flatten Layer
Dense Layer: 64 neurons (ReLU)
Output Layer: 1 neuron (Sigmoid)

Results
Achieved approximately 74% accuracy
Accuracy improved over epochs
Loss decreased during training

Conclusion
The CNN model successfully classifies cat and dog images. CNN helps in extracting features from images. Performance can be improved using larger datasets and deeper models.

Repository Structure
Assignment-9/
Assignment-9.ipynb
README.md

Author
Name: Riya Shukla
Registration Number: 23BCE11293
Application Number: IN26012655
Batch Number: 2(B)
