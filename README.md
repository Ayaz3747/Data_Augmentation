# Data_Augmentation
 The word “augment” means to make something “greater” or “increase” something (in this case, data), the Keras ImageDataGenerator class actually works by:

 1. Accepting a batch of images used for training.
 2. Taking this batch and applying a series of random transformations to each image in the batch (including random rotation, resizing, shearing, etc.).
 3. Replacing the original batch with the new, randomly transformed batch.
 4. Training the CNN on this randomly transformed batch (i.e., the original data itself is not used for training).
 </br>
 What is data augmentation?

Data augmentation encompasses a wide range of techniques used to generate “new” training samples from the original ones by applying random jitters and perturbations (but at the same time ensuring that the class labels of the data are not changed).

Our goal when applying data augmentation is to increase the generalizability of the model.

Given that our network is constantly seeing new, slightly modified versions of the input data, the network is able to learn more robust features.
