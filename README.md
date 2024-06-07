# ENGR7761-Computer-Vision-Vlas0022

This is the repository for my Computer Vision project for ENGR7761 

## Project Idea

The project aims to implement a computer vision preprocessing algorithm that breaks down the key details of a tire tread

The algorithm then passes the output of the preprocessing algorithm into a Convolutional Neural Network, and the CNN then makes a prediction based on a trained model

## PreProcessing Algorithm

The algorithm follows the following steps
- Equalise the image
- Greyscale the image
- Apply Binary Thresholding, used 75
- Apply Sobel X and Y operators
- Sum the sobel X and Y
- Sum Sobel with Thresholding
- Trim the image to isolate the tire tread


## Convolutional Neural Network

The CNN takes the output of the preprocessing algorithm and trains a model based on the 16 training images

The output is put in a file named "V3.pth"

The model is then loaded where a image can be tested and the prediction can be made by running the last block of code in the notebook