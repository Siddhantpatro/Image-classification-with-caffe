# Image-classification-with-caffe
It is a python program for classifying images using a deep learning tool called Caffe.
The system accepts images from local storage or from webcam in real-time.It finally outputs the
predicted class labels with corresponding probabilities.It has an easy to use GUI for selecting images
through webcam or local filesystem.The caffe model was trained on over 2 lakh images with the help of 
a GPU and consists of 50 different classes.

## Getting Started

Recommended basic knowledge of Python, Image Processing and Linux.

## Prerequisites

PC with Ubuntu 16.04 and NVIDIA GPU (optional).

### Installing

See:-

https://github.com/BVLC/caffe/wiki/Ubuntu-16.04-or-15.10-Installation-Guide

http://caffe.berkeleyvision.org/installation.html

https://github.com/NVIDIA/DIGITS

Additionally install the following libraries from terminal

Easygui : pip install --upgrade easygui

SimpleCV : https://github.com/sightmachine/SimpleCV

Also install Numpy and Pyttsx

If you are using NVIDIA GPU, ensure proper CUDA drivers are installed.

### Running the tests

First, make sure the caffe and related libraries are installed properly.Also, make sure your webcam is working properly.
Keep some images for testing purpose.

Replce the file path as required for the inputs.

In terminal:-

Firstly,make  sure caffe path is properly set and execute the following commands:-

python fin_imclassify.py

NB: Python v2.7 

Now follow the prompts and test the system with any suitable images.
In the case of webcam just click on the webcam window to capture the image.

## Versioning

Version 1.0

## Authors

Anil Sathyan
## License

Free to use, share or modify!! ... Copyleft!!

## Acknowledgments
* "http://shengshuyang.github.io/A-step-by-step-guide-to-Caffe.html"
* "http://adilmoujahid.com/posts/2016/06/introduction-deep-learning-python-caffe/"
* "http://christopher5106.github.io/deep/learning/2015/09/04/Deep-learning-tutorial-on-Caffe-Technology.html"
* "https://github.com/NVIDIA/DIGITS/blob/master/docs/GettingStarted.md"
* "http://caffe.berkeleyvision.org/"
* "https://github.com/BVLC/caffe/blob/master/examples/00-classification.ipynb" 
