### Deep Learning based Object Classification

The objective of this project is to compare different models capable of classifying general objects that we observe in our day-to-day life. 
The dataset used is CIFAR-10 dataset. We implement a basic Convolutional Neural Network architecture followed by GoogLeNet architecture which contains the Inception module. 
We develop the CNN architecture from the ground up and use transfer learning approach to implement the GoogLeNet architecture. 
The latter is a pretrained model which is imported and trained on the CIFAR-10 dataset for the object classification task. 
Post training, the developed models were evaluated on the validation set and test set with the metrics of accuracy and precision. 
It could be noted that the CNN model achieved an accuracy and precision of 84 % and 76 % on the test set, whereas the GoogLeNet model performed better with an 89.13 % accuracy.

### Dataset

We implement the models on the CIFAR-10 dataset. The CIFAR-10 dataset is a collection of 60,000 32x32 color images in 10 classes, with 6,000 images per class. 
The classes are Airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. The data was collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton. 
They started with a dataset of 80 million tiny images, which were downloaded from the internet. They then manually selected 60,000 images from this dataset to create the CIFAR-10 dataset. 
The images in the CIFAR-10 dataset were then labeled by hand and the labeling was done by a team of students at the University of Toronto. 
The images were then resized to 32x32 pixels and converted to RGB color space. The CIFAR-10 dataset is a valuable resource for machine learning researchers because it is a challenging dataset that is small and easy to work with. 

#### Link to dataset: http://www.cs.toronto.edu/~kriz/cifar.html
