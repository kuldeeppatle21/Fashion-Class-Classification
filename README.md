# Fashion-Class-Classification
Objective is to build classifier or to build a kind of deep learning network(Convolution Neural Network)that can classifies the images belongs to target class.


# Dataset: Fashion MNIST Dataset
Dataset Link:   https://www.kaggle.com/zalando-research/fashionmnist


Fashion training set consists of 70,000 images divided into 60,000 training and 10,000 testing samples. Dataset sample consists of 28x28 grayscale image, associated with a label from 10 classes.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255.


The 10 classes are as follows:
* 0 => T-shirt/top 
* 1 => Trouser 
* 2 => Pullover 
* 3 => Dress 
* 4 => Coat 
* 5 => Sandal 
* 6 => Shirt 
* 7 => Sneaker 
* 8 => Bag 
* 9 => Ankle boot


-> CNN was able to classify 10 target classes with 95% of accuracy.

**(32,3,3) kernel without dropout:
      * Accuracy: 0.9559
      * Test accuracy: 0.911
 
 

**(64,3,3) kernel without dropout:
      * Accuracy: 0.9634
      * Test accuracy: 0.916
      
      
 

**(32,3,3) kernel with dropout:
      * Accuracy: 0.948
      * Test accuracy: 0.919    
      
