## Money_Mapper

## Problem Statement:- 
Small grocery stores and general stores often deal with a high volume of currency transactions on a daily basis. However, manual currency recognition can be time-consuming and error-prone, especially when employees are tired or stressed. This can lead to financial losses for the business if human errors occur during the transaction process. Therefore, there is a need to develop a more efficient and accurate method for currency recognition using deep learning techniques. The goal is to create a system that can automatically detect the value of the note from images and provide voice output.

## Objectives :
The objective of this Money Mapper is to analyze and detect a note fed to it as input and generate favorable output in an efficient manner by the use of Image Processing and Deeplearning techniques.
Note: This money mapper is only used for classifying 10 and 20 

## Prerequisites: 
Python 3 installed \
Keras library installed (pip install keras) \
OpenCV library installed (pip install opencv-python) \
NumPy library installed (pip install numpy) \ 
scikit-learn library installed (pip install scikit-learn) \

## Dataset:
https://www.kaggle.com/datasets/gauravsahani/indian-currency-notes-classifier \
https://www.kaggle.com/datasets/vishalmane109/indian-currency-note-images-dataset-2020 \

## Proposed system:
The proposed system will be a hybrid system that combines image processing and Deep learning techniques. \
The image processing techniques will be used to extract features from currency images, such as the color, shape, and size of the notes. \
These features will then be used to train a machine learning model. The machine learning model will be used to classify new currency images.\
Following the classification of the note and model, the output of voice of the currency value will be useful for blind people.\

## Conclusion :
Our model extracts features of a currency note in an hierarchical manner that is from edges and corners of a note to high level features.\
so, based on those features it recognize and classify the given note whether it is 10 or 20 or invalid note . \
After classification of given note it result in voice output .\


