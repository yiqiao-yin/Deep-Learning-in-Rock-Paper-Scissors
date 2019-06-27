# Deep Learning in Rock, Paper, and Scissors

<p align="center">
  <img width="1000" src="https://github.com/yiqiao-yin/Deep-Learning-in-Rock-Paper-Scissors/blob/master/figs/background.gif">
</p>

This is a mini project (I did it for fun!) on multi-label classification using deep learning.

# Acknowledgement

This mini project is sourced from Convolutional Neural Network in TensorFlow taught by Professor Andrew Ng and Google veteran Laurence Moroney on Coursera. It is also a part of the TensorFlow Concentration Certificate.

# Data

Rock Paper Scissors is a dataset containing 2,892 images of diverse hands in Rock/Paper/Scissors poses. It is licensed [CC By 2.0](https://creativecommons.org/licenses/by/2.0/) and available for all purposes, but it’s intent is primarily for learning and research.

Rock Paper Scissors contains images from a variety of different hands,  from different races, ages and genders, posed into Rock / Paper or Scissors and labelled as such. You can download the [training set here](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/rps.zip), and the [test set here](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/rps-test-set.zip). These images have all been generated using CGI techniques as an experiment in determining if a CGI-based dataset can be used for classification against real images. I also generated a few images that you can use for predictions. You can find them [here](https://github.com/yiqiao-yin/Deep-Learning-in-Rock-Paper-Scissors/tree/master/figs).

Note that all of this data is posed against a white background.

Each image is 300×300 pixels in 24-bit color

# Train and Validate Using Convolution Neural Network

Once we understand the data, we create an algorithm to train a neural network to learn the patterns from the images. In this case, we choose Convolutional Neural Network. 

The following is a summary of the CNN model.

<p align="center">
  <img width="800" src="https://github.com/yiqiao-yin/Deep-Learning-in-Rock-Paper-Scissors/blob/master/figs/summary.PNG">
</p>

Next we have the performance of training and validating for this machine.

<p align="center">
  <img width="400" src="https://github.com/yiqiao-yin/Deep-Learning-in-Rock-Paper-Scissors/blob/master/figs/train-validate.png">
</p>


# Notebook

Notebook (written in .ipynb) is uploaded [here](https://github.com/yiqiao-yin/Deep-Learning-in-Rock-Paper-Scissors/blob/master/python/rock_paper_scissors.ipynb) for replicable purpose. One can load the notebook in Google Colab and upload an image. The notebook will tell you which one the image is (Rock, Paper, or Scissors). 

For example, I uploaded 6 images randomly and they are classified correctly (screenshot below).

<p align="center">
  <img width="300" src="https://github.com/yiqiao-yin/Deep-Learning-in-Rock-Paper-Scissors/blob/master/figs/validate.PNG">
</p>

# Future Work

There are images in the [Figure Folder](https://github.com/yiqiao-yin/Deep-Learning-in-Rock-Paper-Scissors/tree/master/figs) that are classified incorrectly. 

A good exercise would be to find these images. See if you can reset the parameters in the convolutional neural network so that these images can be correctly labeled by machine!
