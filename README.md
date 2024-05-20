# Handwritten Digit Recognition

## Introduction
This project implements a neural network for recognizing handwritten digits using the MNIST dataset. 
The model is built with Keras and TensorFlow,and it is capable of classifying digits from 0 to 9. 
The project includes a Jupyter notebook with the main code, a saved model file, and sample images of handwritten digits for testing.

## Files
- HandWrittenDigitRecognition.ipynb: Jupyter notebook containing the main code for training, evaluating, and using the digit recognition model.
- handwrittendigit.h5: The saved model file from the training process.
- dig1.png to dig13.png: PNG files containing sample handwritten digits drawn by me.

## Requirements
- Python 3.6 or higher
- Jupyter Notebook
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- OpenCV
You can install the required packages using the following command:
  -pip install tensorflow numpy matplotlib opencv-python

## Instructions
1. Clone the Repository:
   -git clone https://github.com/Vasundar05/handwritten_digit_recognition.git
   -cd handwritten_digit_recognition
2. Open the Jupyter Notebook
   -Launch Jupyter Notebook from the project directory
   -jupyter notebook
   -Open HandWrittenDigitRecognition.ipynb in your Jupyter Notebook interface.
3. Run the Notebook:
   -Run all the cells in the notebook to see the complete process of:
   -1.Loading and preprocessing the MNIST dataset.
   -2.Building and training the neural network model.
   -3.Evaluating the model's performance.
   -4.Loading the saved model and making predictions on new handwritten digit images.
4. Test the Model with Your Own Images
   -To test the model with your own handwritten digits, follow these steps:
   -1.Ensure your images are in grayscale and of size 28x28 pixels.
   -2.Place your images in the project directory.
   -3.Modify the code in the last section of the notebook to load and preprocess your images.

## Results
The model predicts hand written digits with reasonable accuracy. Further details and results can be viewed in the Jupyter notebook.


