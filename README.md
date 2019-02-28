# Dog-Breed-Classifier
Given an image of a dog, algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.
As part of my deep learning education in working with Convolutional Neural Networks (CNN), I used pretrained pytorch models and transfer learning to build an algorithim that is able to accurately classify images as containing humans, dogs, or neither, and in the first two cases predict the best resembling dog breed of the images subject.

The breed classifier model was trained on a dataset of 13000+ dog images labeled by breed and ran for 100 epochs with a 0.0001 learning rate. The model used a pretrained VGG19 model as it's base, with one custom fully connected layer inserted as its final linear layer to handle the classification of 133 different dog breeds.
