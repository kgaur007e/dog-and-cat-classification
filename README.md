# Dog-and-Cat-image-classification-on-my-pre-build-dataset-of-image
Who doesn’t like animals, right? Personally, if I could put them in all of my projects, I’d be living the life. If you are a little bit like me and want to explore machine learning techniques, then this tutorial might just be what you are looking for.

# What are we going to do?
In this tutorial, I’m going to show you how to take a dataset full of lovely animal images, do some black magic, and end up with a model that can classify even your personal pet pictures. This model can then be used in your personal applications so that you can show your friends and family the cool stuff you’ve been learning.

This tutorial was based on a project that I had to do for a university course with Pedro Silva, a colleague. Together, we’ve managed to create a model with 92% accuracy on the testing set. That is, it correctly classified 92% of the images in a portion of the dataset that wasn’t used for training. This is not a bad score, but it can be improved — and I’m also going to tell you how!

Before we start you should know that these techniques are very computationally expensive and will most likely take a long time to perform. Don’t let this discourage you though! There is a lot of things you can do while waiting, like taking walking your dog… or getting coffee, or taking a nap. In fact, this is a great excuse if you want to procrastinate ;)

# Data set
For our goal, we are going to use the Cats and Dogs Breeds Classification Oxford Dataset available on Kaggle (and is available to download for commercial/research purposes under a Creative Commons Attribution-ShareAlike 4.0 International License). This dataset has a total of 7384 images of pets that can be classified into 37 breeds (or, in this context, classes).


# Example of images from data set — Images from the data set
These images are all informal pet images like the ones we usually have on our phones, and this is important because it means that our model will be more versatile. Otherwise, it would only be able to understand a pet breed if the picture had a certain characteristic or was taken in a specific manner.

Another thing we need to verify is the distribution of images per class. We need to know this because if the number of images in the classes is not all roughly the same, then the model wouldn’t be very good at predicting some of the breeds. To understand this situation, let’s plot a chart and start analysing the data set!
