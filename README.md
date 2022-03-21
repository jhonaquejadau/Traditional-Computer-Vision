# Traditional-Computer-Vision
This repository contains a guide and implementation about traditional tecniques in computer vision, using SIFT and HoG descriptor and detector for a course project. 
It's very important to take in account that methods are patented. 
* Sift was created by David Lowe in 1999.

# PROJECT TOPICS 

1. Create a set of images of your faces and those of your group mates. This data set should be used to train and validate your MLP (Multi-Layer-Perceptron) classical neural network. When obtaining the images, keep in mind to apply variations to them so that your network is able to "generalize" in a better way. Some of the proposed variations are rotation, translation, and illumination.  When rotating the face, keep in mind not to exceed +/-15°. Divide the set of images into training images (80%) and validation images (20%).

3. Doing a good pre-processing can improve the performance of your classifier, therefore we can do the following operations with our dataset:

* Convert images to grayscale.
* Remove noise in images.
* Normalize images.

3. Extract the features that will feed our models ANN (Artificial Neural Network using MLP function) & Support Vector Classifier (SVC). Perform one or two different functions that allow you to obtain two types of features: SIFT and HOG.

4. Implement the classifiers and test their performance using a confusion matrix.
