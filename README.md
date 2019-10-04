# Sign Language Recognizer
###  Project Report For 7th Semester (Minor Project)
####   Tutorial can be found here: https://www.tensorflow.org/hub/tutorials/image_retraining

####   Data Set: https://drive.google.com/drive/folders/1wgXtF6QHKBuXRx3qxuf-o6aOmN87t8G-

####   Dependencies pip3, python3, Tensorflow, OpenCV, MatplotLib
 
####  To run use:$ python3 classify_webcam.py
 
####  To run on simple images: python3 classify.py [address to image]
 
####  Log(Link:https://drive.google.com/open?id=1NEa8Wf_UFwoh9ZDvS83IRADquEMgZt_z ) Folder contains the trained model using CNN(Inception V3 Model)

####   To retrain or using other data set train.py
The project focuses on translating American Sign Language (ASL) fingerspelled alphabet (26 letters). I utilised transfer learning to extract features, followed by a custom classification block to classify letters. This model is then implemented in a real-time system with OpenCV - reading frames from a web camera and classifying them frame-by-frame. This repository contains the code & the corresponsing weights for classifying the American Sign Language (ASL) alphabet in real-time.

