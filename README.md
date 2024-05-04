# Fake vs. Real Image Classification with KNN
This project aims to classify images as either fake or real using the K-Nearest Neighbors (KNN) algorithm. The dataset consists of images categorized into two classes: 'Real' and 'Fake'. The KNN model is trained on the provided dataset, and its accuracy is evaluated on a separate test set.<br>

https://github.com/vidurAgg22/Deepfake-Analyzer/assets/165144144/3b372da3-c15c-4c57-981b-d1f8a088d9c4



## Introduction

The code demonstrates the process of training a KNN classifier to distinguish between real and fake images. The images are preprocessed and resized to a standard size before being fed into the classifier. The trained model is then used to classify new images uploaded by the user.

## Usage

1. Mount Google Drive: Mount your Google Drive to access the dataset and save the trained model.

2. Run the provided code in a Jupyter notebook or a Python environment that supports the necessary libraries.

3. Upload the dataset to the specified directory on Google Drive ('/content/drive/MyDrive/Dataset1/').

4. Run the code to preprocess the images, train the KNN model, and evaluate its accuracy.

5. Save the trained model to Google Drive for future use.

6. Upload new images for classification using the trained model.

## File Description

- `- deepfake_detection.ipynb`:  Jupyter notebook containing the code for training the KNN classifier and classifying images.
- `README.md`: This file providing an overview of the project.
- `imagemodel.joblib`: Pre-trained KNN model saved using joblib.

- Dataset directory:
  - `Train`: Directory containing training images categorized into 'Real' and 'Fake' classes.
  - `Test`: Directory containing test images for evaluation.

## Requirements

- Python 3.x
- scikit-learn
- numpy
- PIL (Python Imaging Library)
- joblib
- Google Colab (for online execution)

## License

This project is licensed under the MIT License.

