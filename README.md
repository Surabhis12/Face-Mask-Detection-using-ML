# Face-Mask-Detection-using-ML
Abstract: 
With the rise of pandemic the face mask became one of the most essential part of human life. This project aims to ease the maintenance of the rules and regulations by the authorities. This system will do the task of detecting the percentage mask worn on a person’s face. This way it will detect if a person has worn the mask or if he/she has worn it properly such that it would prevent the infections. If the mask is not worn then the person would be highlighted and post the detection, we can raise an alert if used in public places
INTRODUCTION:
Nowadays the whole world is wearing masks due to COVID-19 corona virus epidemc. Scientists have proved that wearing a mask helps to stop COVID-19 transmissions. Due to its fast spreading across the world WHO has declared COVID-19 as a global pandemic. Wearing the face masks are one of the important preventive measures            given by them it is useful as it not only stops the people from getting infected but it        also help the infected people to not infect others. But we should wear the face mask   correctly, it should be covering our mouth, nose entirely. In order to check if the               person is wearing mask correctly or not we can use machine learning technique.
Face Mask Detector is the solution to check whether people are wearing masks              correctly or not, in percentage. We have used Dataset, Keras, Machine Learning,          MobileNetV2, OpenCV, Python, Tensorflow. Face mask detection will help the                 government and private bodies. It will help to stop carelessness of people and can       even be used to punish them. It can also be used to get the data of number of people following the norms in different cities. It will detect as mask and no mask and it will       also start an alarm, beeping as soon as it detects person without a mask.

IMPLEMENTATION:

Step 1 Installing all required Libraries
Installing the required libraries like OpenCV, Keras, Sklearn and others.

Step 2 Installing Dataset
This model will differentiate between people wearing and not wearing masks so We    installed our dataset. The next step is labelling the data. The data which has been        collected labelled into two groups; with and without a mask. After the data has been    labelled, it is grouped into those two groups.

Step 3 Data Pre-processing    Data pre-processing is divided in four steps           which are resizing image as we know more the smaller size of image better       will be the model so we will resize images to 224 x 224 pixels, converting               image into
array, pre-processing input using MobileNetV2 and last is performing hot             encoding on labels.
 The next will be splitting the data.
 
Final Step: Implementing the model:

Step 4: Testing the model

Step 5: Applying camera in the model

Step 6: Running and checking the output
The model implemented in the video. The video needs to read from frame to frame,
 for the face detection algorithm to work. If a face is been detected, then it proceeds 
to the next step. From the frames that detected the containing faces, reprocessing        will be carried out which would be including resizing the image size, converting to the array, pre-processing input using MobileNetV2. The next step is to predict the input     data from the model which is saved. Predicting the input image which has been                processed using a model built earlier. The video frame will also be labelled according to whether that the person is wearing a mask or not and also predictive percentage.     It will also start beeping if person is not wearing mask.

CONCLUSION:

In this project, a machine learning model is created for face mask detection using Python, Keras, and OpenCV. We developed the face mask detector model for detecting whether if the person is wearing a mask or not. We trained the model using Keras with network architecture. Training the model was the first half of our project and testing it using the webcam using OpenCV the second half. This system can therefore be used in real-time applications and places where required face mask detection for safety purposes due to outbreak of covid-19.





References:


Riya Chiragkumar Shah Department of Computer Science and Engineering Nirma University S G highway, Ahmedabad – 382481, Detection of Face Mask using Convolutional Neural Network. 
Sammy V. Militante College of Engineering & Architecture University of Antique Sibalom, Antique, Philippines .Real-Time Facemask Recognition with Alarm System using Deep Learning 2020 
  IJRASET International journal for research in applied science and technology face mask detection.
