# Kathakali-face-expression-detection
Kathakali is one of the famous classical Indian dances. Due to the complex makeup and fancy decorations to hardly understand the expression of the character in a show. This work uses tools of machine learning to observe the Kathakali facial expression.

The code of this work is running in the Google Colab platform with the Kathakali image dataset stored in the Google Drive below. Please note that there are nine facial expressions with two files in each type. One is the cropped image for training and testing the model, and another is the original image for testing both the face detector and the model. https://drive.google.com/drive/folders/1PDpj5jMWHqlz3y_pMZ4ZQtAhWJCR-kOa?usp=sharing 

Copy the code into your Google Colab and the images into your Google Drive. Once the basic elements are set, there are a couple of things you have to adjust in the code to avoid an error. There are some cells of code to load the images from a Google Drive into a variable. You have to change the file path to where the download images are. First, it is cell 4 which is the preparation of the dataset, and the first cell in the "Face detection and emotion prediction" session which is the original image.

After the adjustment, please take time for the code execution as it consumes some amount of computational resources. So, it would be good if you change the run time type in the Google Colab to T4 GPU. Otherwise, it would be a long time to execute the code around half an hour approximately.
