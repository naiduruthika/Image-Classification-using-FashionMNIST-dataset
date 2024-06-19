# Image Classification using FashionMNIST dataset
 This project uses PyTorch to perform image classification on the FashionMNIST dataset. This project is a deep learning solution for classifying fashion-related images into 10 categories using the FashionMNIST dataset. It employs convolutional neural networks (CNNs) for image recognition tasks.

 # FashionMNIST Dataset
 The FashionMNIST dataset(https://github.com/zalandoresearch/fashion-mnist) consists of 60,000 training images and 10,000 test images, categorized into 10 fashion classes:
0: T-shirt/top
1: Trouser
2: Pullover
3: Dress
4: Coat
5: Sandal
6: Shirt
7: Sneaker
8: Bag
9: Ankle boot

# How to run
1. Import datasets from torchvision.
2. Build a class to load the dataset.
3. Define architecture of the model:
   Input Linear layer
   Output Linear layer with 10 classes
   Activation function- ReLU
   Loss function- Cross Entropy Loss
   Optimizer- SGD
4. Training the model, while calculating accuracy, loss
5. Plot the loss and accuracy.
 
