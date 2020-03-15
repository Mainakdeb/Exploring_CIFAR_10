# Exploring_CIFAR_10

Download- [CIFAR-10 raw jpeg images](https://github.com/YoongiKim/CIFAR-10-images)

I downloaded the raw jpeg format on purpose to get comfortable with handling RGB-image datasets.

***

The CIFAR-10 dataset consists of 60,000 32x32x3 (RGB) images in 10 classes, with 6,000 images per class. There are 50,000 training images (5,000 per class) and 10,000 test images.

A CNN is trained to classify images to one of the above given classes.
The model has an accuracy of 68% on 10,000 test images.

## Stuff I learnt:
* Handling raw RGB image datasets.
* Augmenting training images to increase model robustness.
* Implemented a checkpoint mechanism to aid long duration training on colab.
