# Image_Classification_Using-_CNN
This is my ML project on Image Classification using convolutional neural networks, where we classify corresponding images to there corresponding classes

In this project, we address the problem of image classification using Convolutional Neural Networks (CNNs) on the CIFAR-10 dataset(10 Classes).
Image classification is the task of assigning a label or category to an input image based on its visual content.

In this work, we aim to design, train, and evaluate a CNN model capable of achieving high classification accuracy on CIFAR-10, while exploring ways to improve performance through model design and training strategies.

We designed a 7-layer CNN (5 convolutional layers + 2 fully connected layers) that balances model complexity and training efficiency, tailored for small 32×32 images of CIFAR-10.Unlike AlexNet, which uses large filters like 11×11, we use smaller 3×3 filters to better capture fine features in tiny images.

Reference  -  NIPS 2012 paper on  ImageNet Classification with Deep Convolutional  Neural Networks(it actually comsists of 10,000 classes and 16 million images to Large to handle on a PC).
