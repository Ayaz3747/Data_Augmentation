# Data_Augmentation
 the word “augment” means to make something “greater” or “increase” something (in this case, data), the Keras ImageDataGenerator class actually works by:

 1. Accepting a batch of images used for training.
 2. Taking this batch and applying a series of random transformations to each image in the batch (including random rotation, resizing, shearing, etc.).
 3. Replacing the original batch with the new, randomly transformed batch.
 4. Training the CNN on this randomly transformed batch (i.e., the original data itself is not used for training).
