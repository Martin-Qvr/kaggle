## mnist_digit_recognition

I used this kaggle competition as a way to introduce computer vision and to train on building neural networks with Keras. 

The MNIST (http://yann.lecun.com/exdb/mnist) dataset contains images representing handwritten digits.  Each input image is a 28 x 28 matrix, each entry representing a gray level.  Each input data is then a $d=784$ dimensional vector.  The goal is to label the digits correctly. 

### model : 

After exploring with keras with a simple NN working as a logistic regression, I implemented a Feed Forward Neural Network taking a d = 784 vectords using first a relu function then a softmax regression as hidden layers to output one of the 10 digits. 

### results : 

I achieved an accuracy (classifcation error) of 0.93 on kaggle after submission. 



