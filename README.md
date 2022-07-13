## MNIST dataset - the case of split images

The premise is as follows.
We consider the MNIST dataset of handwritten digits (http://yann.lecun.com/exdb/mnist/).
Unfortunately, the test set suffers an "accident" and all the images in it are cut in half and then shuffled around.
We want to find a way to restore the original test set from these halves, while at the same time keeping the overall matching accuracy as high as possible.
The training set remains intact.