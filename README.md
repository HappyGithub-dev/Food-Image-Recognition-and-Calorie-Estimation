# Food-Image-Recognition-and-Calorie-Estimation

This project is an introductory project to understand computer vision and object detection. 

In this project, a model based on Faster RCNN is trained to recognise multiple fruits on a dataset of 300 images. 
The dataset has images of apples, bananas and oranges and some images which are combinations of the three.

It predicts the fruits in a given image and predficts the total calories in the fruits. 

Each image has its own xml file which contains the bounding box coordinates of the fruit and fruit name label.
These are details stored in a single json file and then it is passed on to the model for training. 

The model is trained for 5 epochs, and 60 epochs per batch. 

The model is finally tested on a single random image. It predicts the fruit and its bounding box coordinates. 
Finally, it gives out the total calories based on a calorie dictionary. 

