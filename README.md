# Pytorch_train_test_split
Pytorch code for mimicking SKLearn's train-test-split function. Randomizes data into train/test iterators from single directory

This code was originally written by Chris Fotache as part of a larger article here: https://towardsdatascience.com/how-to-train-an-image-classifier-in-pytorch-and-use-it-to-perform-basic-inference-on-single-images-99465a1e9bf5

This randomization and test/train split feature, all from same directory, was something I think should be developed as it's own dedicated module as every Pytorch project arguably could use it (probably should go into Pytorch directly eventually).
Thus, I simply pulled it out from the larger project and modularized it a bit for the first commit.

