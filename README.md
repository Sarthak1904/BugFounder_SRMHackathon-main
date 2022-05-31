# BugFounder_SRMHackathon
AI based accident detection system
The problem
According to a data, around one and a half lakh persons die due to road accidents per year in India alone . 30-40% of these road accidents goes unnoticed or neglected by the general public to avoid the unwanted enquiry that can cost lives of several people.
The delay in the response time to these accidents leads to delayed arrival of ambulance or fire brigade to the spot. In these critical situations every second counts for the life.

There is not any concrete step to stop the loss of lives due to such road accidents.

Solution to the Problem

Most of these deaths are avoidable. Then the million-dollar question is, “what can we do to avoid it”? The idea is to use the CCTV cameras on the road to detect the road accident and then if it suspects an accident or the chance of occurrence of accident then it generates a signal and informs it to the nearest available services like ambulance, fire brigade and police station. Now, comes the question on the availability of cctv cameras. Delhi reporting highest no. of road accidents (1591) has 100 cameras at present to monitor the speed limit. These cameras can be used to monitor the occurrence of accident. Chennai records the highest no. of accidents. Third Eye campaign in Chennai has installed 34,293 cameras to monitor the speed activities which can be deployed for accident detection as well. Bengaluru has also put 5000 surveillance cameras on the road.

Technologies Used

1-TensorFlow

2-Keras

3-OpenCv

4-pickle

5-twilio

6-scikitlearn

7-matplotlib



WorkFlow


We have designed a Deep Learning Neural Network which will feed on real time video captured through cctv cameras installed at accidents prone part of the city. The algorithm was trained on accident images from kaggle
The first step after obtaining images was to pre process the image into a vector containing RGB values. The values obtained were normalized to avoid biases among features
The model uses RESnet as a deep learning neural network to obtain a higher accuracy in predicting the possibility of an accident. In this step the image is convoluted, spooled and fed into layers of neural network.
The model then predicts probability of accident for each frame of video and if the value reaches the threshold it sends a text message to the nearest police station, hospital.



The Team

AJAY GANGWAR

SARTHAK CHOUDHARY

PRACHI JHA

ANANYA ROHATGI
