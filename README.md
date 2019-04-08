# FacialEmoRecognizer
FacialEmoRecognizer is a python based Machine Learning Application used to detect and recognize human facial expressions, which can further be used for affective computing and many real life purposes in future.

This project can be done in two ways:
1. Using CNN for emotion recognition from a static image.
2. Emotion recognition over a real time data using a pre-trained model.

For this, the dataset issued by Kaggle in 2013 for Facial Emotion Recognition Challenge is used, the dataset is called 'fer2013.csv' and can be obtained on Kaggle's website here: https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

The dependencies that are required for running this project successfully (or else you might get stuck in various different errors at each stage of the program) are as follows:

1. Python Version : 3.6.0 (In case of multiple python versions, make sure that the default version for Python is 3.6.0 by ensuring the Path in environment variables.)
2. Tensorflow : 1.10 (Tensorflow v1.10 works completely fine for Python v3.6, other versions of the former may cause various DLL Import Errors for Python v3.6)
3. OpenCV
4. Keras

And that's all, now our model is ready to recognize the human facial recognition with both static and dynamic data as input and that too with a high rate of accuracy.
