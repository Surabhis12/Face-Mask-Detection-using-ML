# Face-Mask-Detection-using-ML
Abstract: 
With the rise of pandemic the face mask became one of the most essential part of human life. This project aims to ease the maintenance of the rules and regulations by the authorities. This system will do the task of detecting the percentage mask worn on a person’s face. This way it will detect if a person has worn the mask or if he/she has worn it properly such that it would prevent the infections. If the mask is not worn then the person would be highlighted and post the detection, we can raise an alert if used in public places
INTRODUCTION:
Nowadays the whole world is wearing masks due to COVID-19 corona virus epidemc. Scientists have proved that wearing a mask helps to stop COVID-19 transmissions. Due to its fast spreading across the world WHO has declared COVID-19 as a global pandemic. Wearing the face masks are one of the important preventive measures            given by them it is useful as it not only stops the people from getting infected but it        also help the infected people to not infect others. But we should wear the face mask   correctly, it should be covering our mouth, nose entirely. In order to check if the               person is wearing mask correctly or not we can use machine learning technique.
Face Mask Detector is the solution to check whether people are wearing masks              correctly or not, in percentage. We have used Dataset, Keras, Machine Learning,          MobileNetV2, OpenCV, Python, Tensorflow. Face mask detection will help the                 government and private bodies. It will help to stop carelessness of people and can       even be used to punish them. It can also be used to get the data of number of people following the norms in different cities. It will detect as mask and no mask and it will       also start an alarm, beeping as soon as it detects person without a mask.


    LITERATURE SURVEY:
In the background of the COVID-19 pandemic, institutions Behind the scenes of 
the COVID-19 pandemic, organizations, for example, the institute experience the 
ill effects of for all intents and purposes shut around the world assuming the                    current circumstance won't change. Coronavirus otherwise called Serious Acute    Respiratory Syndrome Corona infection 2 is an irresistible illness that is set                 from a contaminated debilitated individual who talks, wheezes, or hacks by                 respiratory beads. This spreads rapidly through close contact with anybody                tainted, or by contacting articles or surfaces impacted with an infection. There's       still as of now no immunization accessible to ensure against COVID-19 and forestalling openness to the infection is by all accounts the main technique to defend        ourselves. Wearing a facemask that covers the nose and mouth in a public setting and regularly washing hands or the utilization of at minimum 70% liquor based         sanitizers is one method for trying not to be presented to the infection. In the              midst of the headway of innovation, Deep Learning has demonstrated its viability   in acknowledgment and characterization through picture handling. The                         examination concentrate on involves profound learning procedures in distinctive     facial acknowledgment and perceive in the event that the individual is wearing a     facemask or not. The dataset gathered contains 25,000 pictures utilizing 224x224 pixel goal and accomplished an exactness pace of 96% concerning the exhibition of the prepared model. The framework fosters a Raspberry Pi-based constant           facemask acknowledgment that cautions and catches the facial picture assuming the individual recognized isn't wearing a facemask. This review is gainful in                  battling the spread of the infection and keeping  by from contact with the infection[1]
                 In the new occasions, the Coronaviruses that are a major group of various      infections have become exceptionally normal, infectious and perilous to the entire        mankind. It spreads human to human by breathing out the contamination breath,           which leaves drops of the infection on various surface which is then breathed in by
 other individual and gets the disease as well. So it has become vital to ensure ourselves and individuals around us from the present circumstance. We can avoid potential risk, for example, social separating, washing hands like clockwork, utilizing sanitizer, keeping social separation and the main wearing a cover. Public utilization of wearing a veil has become extremely normal wherever in the entire world at this point. From       that the most impacted and destroying condition is of India because of its outrageous populace in little region. This paper proposes a strategy to identify the facial covering is put on or not so much for workplaces, or some other work place with a many                  individuals coming to work. We have utilized convolutional neural organization for the equivalent. The model is prepared on a genuine world dataset and tried with live              video real time with a decent exactness. Further the precision of the model with                various hyper boundaries and numerous individuals at various distance and area of     the edge is finished.[2]
This task plans to recognize facial coverings and social removing on a video feed utilizing Machine Learning and Object Detection. TensorFlow and Keras were utilized to   fabricate a CNN model to distinguish facial coverings and it was prepared on a                dataset of 3800 pictures. Just go for it Object location was utilized to recognize                   individuals in a casing and check for social removing by ascertaining the Euclidean      distance between the centroids of the identified boxes. Fostered an Android                      application named "StaySafe" where the client will be advised and can screen the           infringement. 
For this reason, Firebase was utilized as the backend administration. Assuming that an infringement is identified it will transfer the picture  to a Firebase Cloud Storage with a notice, and the client will actually want to see these pictures on their Android                 application alongside the date and time. Firebase Cloud Messaging administration       was utilized to send notices which will be taken care of in the android application.           The application offers different elements like review history, saving the picture to the gadget, erasing the pictures from the cloud and so on A hotness guide can likewise      be seen which features swarmed districts which can assist authorities with distinguishing the locales that should be cleaned all the more frequently.













 At present, even with the wellbeing emergency brought about by the Coronavirus        COVID-19 which has spread all through the around the world. The battle against this pandemic has turned into an unavoidable reality for some nations. It is presently a       matter including numerous spaces of examination in the utilization of new data                 advancements, especially those connected with man-made reasoning. In this paper, we present a clever commitment to help in the battle against this pandemic. It                   concer    ns the identification of individuals wearing covers since they can't work or      move  around as common without security against COVID-19. In any  case, there are a  couple of exploration learns about facial covering  recognition. In this work, we                  researched utilizing diverse profound  Convolutional Neural Networks (CNN) to separate profound elements from pictures of appearances. 


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





References
Riya Chiragkumar Shah Department of Computer Science and Engineering Nirma University S G highway, Ahmedabad – 382481, Detection of Face Mask using Convolutional Neural Network. 
Sammy V. Militante College of Engineering & Architecture University of Antique Sibalom, Antique, Philippines .Real-Time Facemask Recognition with Alarm System using Deep Learning 2020 
  IJRASET International journal for research in applied science and technology face mask detection.
