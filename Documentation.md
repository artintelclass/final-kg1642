
# Are you more of a dog person or a cat? 

![](https://github.com/artintelclass/final-kg1642/blob/master/Images/CatorDog.jpg)
It is an webapp which allows users to take a photo of them using a webcamp and tells them whether they look more like a dog person or a cat person. Flask framework of Python will be used 
to create an webapp. I am choosing Flask as it is a framework for python and being able to write the backend in python will allow me to take the benefot of tensorflow and keras. Front-end will be written in Javascript.

The model used to compare the users photo will be trained on 25000 images of cats and dogs found [here.](https://www.kaggle.com/c/dogs-vs-cats) Convolutional neural network will be used to train on those images. 

Below are some of the resources that I will be using.

[Cats vs Dogs Classifier](https://github.com/neungkl/cat-vs-dog-classification) 

[Classifying Cats vs Dogs with a Convolutional Neural Network on Kaggle](https://pythonprogramming.net/convolutional-neural-network-kats-vs-dogs-machine-learning-tutorial/) 

[Cats and dogs and convolutional neural networks](http://www.subsubroutine.com/sub-subroutine/2016/9/30/cats-and-dogs-and-convolutional-neural-networks) 

[Flask, Python's web framework](http://flask.pocoo.org/) 


## Process:
1. Train the model on 25000 images of cats and dogs using Convolutional neural network.
2. Create an webapp that allows users to take a photo via a webcamp.
3. Compare the photo taken by the user with the trained model. 
4. Based on the result obtained at 3, let the users know whether they are more of a dog person or a cat person. 
