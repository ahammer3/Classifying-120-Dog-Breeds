# Classifying-Dog-Breeds
Building a model to classify 120 types of dog breeds 
***NOTE: This repo does not contain any data that can already be accessed using the Stanford link below. I chose to not upload out of sheer size (I used the uncompressed version) and redundancy.***

I wanted to try a simple deep learning style/format of a project, and when I saw that Stanford had collected and made public a dataset that contained over 20000 images of dogs representing 120 different breeds, I definitely wanted to give it a spin.

After getting halfway through the project, whilst exploring, debugging, etc., I realized that this dataset is in fact pretty old and I had just never heard of it before! It was even a competition on Kaggle at one point...but I decided to press on because of my own interest, and I thought that even if the dataset was relatively old, if I had never heard of it until 2019, hopefully others haven't either and can gain something from this. It is certainly much better than beating the old Boston Housing Market or Titanic dataset even further into the Earth's core... (jk, but not really)

The dataset can be found and downloaded here: http://vision.stanford.edu/aditya86/ImageNetDogs/, but is also copied into the Github repo for ease of use. We'll kick things off here with just looking at what the data has to offer!

TODO:
Machine Learning:

1) try out a grid approach to find the best model parameters
2) generate new features to feed into this approach (Now that I have gotten this far, I realize that this is very important.      Having different objects such as cats and humans and more than 1 dog in images affects a lot. Also, I realized that just      by cropping an image, sometimes the model will predict something different entirely.)
3) train more extensively in general

Analysis:
1) work with the confusion matrix to isolate most troublesome classes
2) implement and use the bounding boxes given in the dataset by Stanford for something cool (not sure what yet)
3) perhaps even implement an app to go along with this!
