# GAN Image Generation - September 15 Exam

## Task

The purpose of the project is to test the ability of Generative Adversial
Networks (GANs) in generating realistic-looking images. The network has to
generate realistic-looking images as similar as possible to the images contained
in the test set.

## Data

FashionMNIST is used as a training and test data. The notebook contains more
informations about it.

## Structure

Write a notebook explaining every step you take and DON'T clear the output of
the cells when you submit it.

You may possibly discuss and provide results for more models, but at most a
couple of them should be presented in the notebook.

The metric you will need to use to evaluate the results is the Fréchet Inception
Distance (FID). More informations and the implementation are contained into the
attached files. Remember to test it over 10k test images and 10k generated
images.

## Limitations

You are required to implement a vanilla Generative Adversarial Network (GAN),
not a variant of it (e.g. PixelGAN, CycleGAN, ... are not accepted). The maximum
number of parameters is 15 million, and every pre-trained network can be used as
an add-on. Clearly, only the training set can be used to train the network, no
additional images (Data Augmentation is ok).

## Recommendation

Save the weights of your model and keep them until the discussion, we might ask
you to provide them.
