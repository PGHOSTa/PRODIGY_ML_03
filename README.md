# PRODIGY_ML_03
 
# Cat vs Dog Image Classifier using SVM

This project implements a machine learning classifier that uses Support Vector Machine (SVM) to classify images of cats and dogs. The model is trained on the **PetImages** dataset, which contains images of cats and dogs. The images are resized and preprocessed before being fed into the model.

## How it Works
1. **Dataset**: The images are organized into two categories: "Cat" and "Dog". The images are resized to a fixed size (64x64 pixels) and converted to grayscale for processing.
2. **Model**: A Support Vector Machine (SVM) classifier with a linear kernel is used to classify the images as either "Cat" or "Dog".
3. **Prediction**: After training, the model can be used to predict whether a given image contains a cat or a dog.

## Requirements
- Python 3.x
- `numpy`
- `scikit-learn`
- `Pillow`
- `scikit-image`
- `joblib`

Dataset link: https://www.microsoft.com/en-us/download/details.aspx?id=54765

I have used following images to test the model which i downloaded from google.
![catts](https://github.com/user-attachments/assets/cb510462-d555-489e-a014-ac1d3ef61466)
![dogggs](https://github.com/user-attachments/assets/4d3a261a-60c2-4241-9e71-aadbb251791d)
