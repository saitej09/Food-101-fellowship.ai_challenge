# Food 101 Image Classification 

This repo contains notebooks training a classification model on the Food-101 dataset. Food-101 is a dataset consisting of 101 classes with 1000 images per class. Each class has 750 images for training data and the remaing 250 in the test data. 

This dataset is an interesting challenge due to the following reasons:

- Many classes look similar to each other.
- Several images contain multiple correct classes (ex burgers + fries), despite the dataset being  a single class classification problem. 
- There are several mislabeled images.

To train this dataset, ResNet50 pretrained model (trained on imagenet dataset) is used. Data Augmentations and Test Time Augmentations (TTA) are used to make the model more robust and increase the final accuracy.
