# implement-CNN-at-Kannada-MNIST

Convolutional neural network -- CNN is good at picture processing. It's inspired by the human visual nervous system.

CNN has two major characteristics:
1. It can effectively reduce the dimensionality of large data into small data;
2. Can effectively retain the characteristics of the picture, in line with the principles of image processing. At present, CNN has been widely used.

Because convolutional neural networks have been applied to MNIST handwritten digit datasets for various experiments, I use the Kannada hand-written dataset . Kannada is the official administrative language of Karnataka, India, and is spoken by nearly 60 million people worldwide. Different symbols are used to represent the numbers 0-9 in the language, which are different from the modern Arabic numerals popular in many parts of the world today.

![img](https://pic1.zhimg.com/v2-2ea3b454dacb13f077d497daa54fb550_720w.jpg?source=172ae18b)

Like the above picture shows, "1" in Kannada hand writting more seems like "0", "3" and "7" in Kannada is more like "2". Unlike the MNIST handwritten digit dataset, Kannada's replacement of MNIST adds a new challenge to the CNN experiment.


Many machine learning problems (especially CNNS applied to image processing) consist of hundreds or thousands of features. 
The main problems with having so many characteristics are:

1. It slows down the training process
2. It is difficult to find a cost-effective and efficient solution


Regarding the application of CNN in Kannada handwritten data processing, I will achieve two goals:

1. Use dimensionality reduction tools to reduce and visualize hyperdimensional datasets. Getting down to two or three features helps us visualize the data, which is an important part of data analysis; The differences between PCA and t-SNE were also compared (in folder 1)

2. Establish the CNN model (including dropout), analyze the impact of epochs on accuracy, and ensure that the accuracy is more than 98% (in folder 2)
