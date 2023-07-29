# Waste Classification

## General info
The project contains waste classification with Convolutional Neural Networks (CNN) algorithms to determine if it may be recycle or not. The analysis has been made in three steps: the first includes data preparation and build model CNN to waste recognise, the second includes CNN model with data augumentation and the third used a transfer learning with pre-trained MobileNet V2 model  to achieve the better results.

**I have created the application in Streamlit based on this trained CNN model and is available [here](https://share.streamlit.io/aniass/waste-app/main/waste.py) . The code for this app is [here](https://github.com/aniass/Waste-app).**

### Dataset
The dataset contains the 22500 images of organic and recyclable objects. It comes from Kaggle and can be find [here](https://www.kaggle.com/techsash/waste-classification-data).

## Summary
The aim of the project was waste classification by using Deep Neural Networks. The dataset contains waste images recyclable and organic ones. I have built model to predict if the waste may be recyclable or not. In the analysis I have used Convolutional Neural Network (CNN) model with data augumentation and transfer learning to get more accurate predictions and choose the best one for that.

## Project includes:

* Waste classification with CNN model - **Waste_cnn.ipynb**
* Waste Classification with data augmentation - **Waste_Augumentation.ipynb**
* Waste Classification with transfer learning - **waste_transfer_learning.ipynb**
 
## Technologies

The project is created with:
* Python 3.8
* libraries: TensorFlow, Keras, pillow, numpy, pandas, seaborn.

**Running the project:**

To run this project use Jupyter Notebook or Google Colab.
