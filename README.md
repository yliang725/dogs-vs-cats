# dogs-vs-cats  

This program implemented Logistic Regression and InceptionV3 to classify the Kaggle competition dogs-vs-cats images (https://www.kaggle.com/c/dogs-vs-cats).  

## Data Preprocessing

Used torchvision transforms method to resize, center crop, to tensor and normalize the images.

## Results

The testing accuracy for Logistic Regression is 69.70%.  

The testing accuracy for InceptionV3 (transfer learning) is 99.15%.  

The above results show that the InceptionV3 method had a much better performance compared to the Logistic Regression method.  

## Environment Settings

Both methods were implemented with PyTorch API.  

The Jupyter nootbook was compiled on Anaconda, Python 3.7, and PyTorch 1.7.1.
