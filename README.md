# Eye Tracker
This project was created in 2021 spring semester for AIT Deep Learning course.
The only author is Ágoston István Csehi.

## Topic
My goal is to predict the position of the eyes of a person on an image.

## Data
The dataset was retrieved from [here](https://gazecapture.csail.mit.edu/).
The Gaze capture datase consists of 1,490,959 frames taken of over 1450 people
with labeled by metadata, such as left eye x coordinate, measured by IPhone devices.

## Source
Three source files are provided. The preprocessing script should be executed on a local machine.
EyeTracker.ipynb contains the traing and the modell creation.
The Evaluation.ipynb can be used to render some footage using an uploaded model for prediction.

## Trained models
Some of the results of the many experiments on model configuration are provided as saved models.
They can be used in the eval script.

## Acknowledgments
Kyle Krafka, Aditya Khosla, Petr Kellnhofer, Harini Kannan, Suchi Bhandarkar, Wojciech Matusik and Antonio Torralba. “Eye Tracking for Everyone”. IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016.
