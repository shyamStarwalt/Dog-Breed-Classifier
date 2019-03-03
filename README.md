# Dog-Breed-Classifier
Given an image of a dog, algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

As part of my deep learning nanodegree (Convolutional Neural Networks (CNN)), I created a cnn (from scratch) and (transfer learning) to classify images as containing humans, dogs, or neither, and in the first two cases predict the best resembling dog breed of the images subject.

The breed classifier model was trained on a dataset of 13000+ dog images labeled by breed and ran for 100 epochs with a 0.0001 learning rate. The model used a pretrained resnet50 model as it's base, with one fully connected layer as final linear layer to handle the classification of 133 different dog breeds.

# Download
Download dog image file from https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip

Download dog image file from https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip
