# Cat-and-Dog-Classifier
#### Introduction
In this Project I will be solving an image classification problem, where our goal will be to tell which class the input image belongs to. The way I'm going to achieve it is by training an artificial neural network on few thousand images of cats and dogs and make the NN(Neural Network) learn to predict which class the image belongs to, next time it sees an image having a cat or dog in it. The key thing to understand while following this project is that the model we are building now can be trained on any type of class you want, I am using cat and dog only as a simple example for making you understand how convolutional neural networks work.

#### Problem Statement

Computers cannot see images like humans do. While even toddlers can easily distinguish a dog from a cat, the computer reads two numeric matrices lacking semantic meaning. We are given a set of dog and cat images. The task is to build a model to predict the category of an animal: dog or cat?
#### Proposed Solution

An image classification problem is to identify an image of an animal as a dog or cat. The  most common approaches for image classification are to use a standard deep neural network (DNN). In this project I'll use the DNN approach, using the Tensorflow and Keras code library.
Given a set of labeled images of cats and dogs, a machine learning model is to be learnt and later it is to be used to classify a set of new images as cats or dogs. The accuracy on the test dataset is not going to be good in general for the abovementioned reason.In order to obtain good accuracy on the test dataset using deep learning, we need to train the models with a large number of input images.
So coming to the coding part, we are going to use Keras deep learning library in python to build our CNN(Convolutional Neural Network).
Before we jump into building the model, i need you to download all the required training and test dataset, download both the folders named “ test” and “train” into your working directory, it may take a while as there are 25,000 images in both folders, which is the training data as well as the test dataset. Make sure to create a new directory and name it “whatever_you_want” and paste the above downloaded dataset folders into it.
Let’s see what does the folders you just downloaded have in them. First, the folder “training_set” contains two sub folders cats and dogs, each holding 9375 images of the respective category. Second, the folder “test_set” contains two sub folders cats and dogs, each holding 3125 images of respective category.
After training completed, the demo applied the trained model to a test dataset of 100 items. The model's accuracy is 80.00 percent so 80 of the few test images were correctly classified.
