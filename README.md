## Synopsis

This is a simple image classification probem of cat and dogs. the model was developed using tensorflow and keras. 
The working model consists of Convolution nueral network. Acheived >83% validation accuration and >90% training accurancy. 

## Model Architecture:

Input Data Shape: 150x150x3
Layer 1:

Convolutional Layer 32 filter Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2

Layer 2:

Convolutional Layer 64 filter Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2

Layer 3:

Convolutional Layer 128 filter Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2

Layer 4:

Convolutional Layer 128 filter Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2

Classification:

Flatten

Dense Size: 512

Activation Function: ReLu

Dense Size: 1

Activation Function: Sigmoid

Optimizer: rmsprop

Loss: Binary Crossentropy

Adding new train dataset:

If you want to add new dataset to datasets, you create a directory and rename what you want to add category (like 'cat' or 'phone').

If you want to add a new training image to previously category datasets, you add a image to about category directory and if you have npy files in Data folder delete npy_train_data folder.
