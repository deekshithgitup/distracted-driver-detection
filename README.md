# distracted-driver-detection
Distracted Driver Detection using Machine Learning techniques

Project Topic: Distracted Driver Detection Using Machine Learning

Group Members:

Deekshith Sathrasala Gangadharaiah

How to Run the Project Locally
Step 1: Download the dataset from Kaggle into Jupyter Notebook.
Please download the dataset from the following link:
https://www.kaggle.com/competitions/state-farm-distracted-driver-detection

Note:
To download the dataset, you must first join the competition on Kaggle.
The dataset contains around 20,000 images and is approximately 40GB in size, so we are unable to upload it to a drive or share it directly.

Step 2:
After downloading the dataset, update the dataset path in the Python code accordingly.

Step 3:
We trained the model using a Convolutional Neural Network (CNN) for feature extraction.
After extracting features from the images, we applied Principal Component Analysis (PCA) to reduce the dimensionality.
We built two models—one using PCA-reduced features and one using the original features using KNN, Random forest, SVM.

Each image results in 128 extracted features.

Step 4:
Our final model takes a random image as input and predicts the class of driver behavior, such as:

Driving safely

Texting

Talking on the phone

Reaching behind

Operating the radio, etc.
