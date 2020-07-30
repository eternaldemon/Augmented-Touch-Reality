# Augmented-Touch-Reality
This repository contains the code(s) for me&amp;my team's Capstone Project for Jan-Dec 2020. 

1. Touch Detection:

    Programming Language Used: Python 3.6
    
    Libraries and Technologies Used:
    •	Tensorflow
    •	Keras
    •	Matplotlib
    •	Os
    •	Numpy
    •	Google colab


    •	Created a dataset with images (320x240). It contains 2 class of images.
    •	Class 1 has images with finger touching a surface (like a wall/table/any other plain surface).
    •	Class 2 has images with finger/ hand, a short distance (0.5 feet at max) away from the surface and images of surface as well.
    •	There are 50 sets taken for initial training. Each set containing 1 image from class 1 & 2 images from class2. Hence we trained it    on a total of 150 images.
    •	Both Classes contains images having same surface but from different orientations.
    •	ImageDataGenerator has been used in the code to improve classification.
    •	4 Conv2D, 4 Batch Normalization, 2 MaxPooling2D, 1 Flatten, 1 Dropout and 2 dense layers have been used to create the initial model.
  
    Dataset : https://drive.google.com/drive/folders/1siaauNRkofa029iyKFbTmwHJ9fmogRpy?usp=sharing  
    
    It has also been put in Datasets folders of this repository.
    
    

2. Contour(s), Hull and Touch Co-ordinate Detection

    Libraries Used: Opencv2 and numpy.
	
    
    
    
    
    

