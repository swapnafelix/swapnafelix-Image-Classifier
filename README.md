# swapnafelix-Image-Classifier

## Image-Classifier

In this project, you'll train an image classifier to recognize different species of flowers. 
You can imagine using something like this in a phone app that tells you the name of the flower 
your camera is looking at. In practice, you'd train this classifier, then export it for use in
your application. We'll be using this dataset of 102 flower categories.

When you've completed this project, you'll have an application that can be trained on any
set of labelled images. Here your network will be learning about flowers and end up as a command line application.

## Prerequisites
The Code is written in Python 3.6.5 . If you don't have Python installed you can find it here. Ensure you have the latest version of pip.
Additional Packages that are required are: Numpy, Pandas, MatplotLib, Pytorch, PIL and json.

## Data
The data used specifically for this assignment are a flower database(.json file). It is not provided in the repository as it's larger than what github allows.
The data need to comprised of 3 folders:

test
train
validate
Generally the proportions should be 70% training 10% validate and 20% test.

Inside the train, test and validate folders there should be folders bearing a specific number which corresponds to a specific category, clarified in the json file. For example if we have the image x.jpg and it is a lotus it could be in a path like this /test/5/x.jpg and json file would be like this {...5:"lotus",...}.

GPU/CPU
As this project uses deep CNNs, for training of network you need to use a GPU. However after training you can always use normal CPU for the prediction phase.
