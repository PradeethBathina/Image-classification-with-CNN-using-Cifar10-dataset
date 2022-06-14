# Image-classification-with-CNN-using-Cifar10-dataset

1)First we need to import all the required libraries and modules. This includes importing TensorFlow and other modules like NumPy. 
2)we need to load data, the dataset of CIFAR-10 is available on TensorFlow Keras API, and we can download it on our local machine using TensorFlow.Keras.datasets.cifar10 and then distribute it to train and test set using load_data() function. 
3)we have 5000 training images and 1000 test images as specified above and all the images are of 32 by 32 size and have 3 color channels. 
4)all the image pixels are in a range from 1 to 256, and we need to reduce those values to a value ranging between 0 and 1. We can do this simply by dividing all pixel values by 255.0. 
5)After we want to do is to flatten and rearrange them in form of a row of the label values using the flatten() function. 
6)visualizing data by plotting images. 
7)Creating the model it includes using a convolution layer in this which is Conv2d layer, dropout function as well as pooling we’ll pass it into a dense layer and the final dense layer which is our output layer. We are using the ‘relu‘ activation function, the output layer uses a “softmax” function. 
8)we use different Callbacks are classes with specific methods, that have access to the whole information inside the neural net while the model is being trained. We can make use of this technique to, Adaptively adjust the learning rate. 
9)By using model. fit we ran the model for 20 epocs and we got 77% accuracy. 
10)By using prediction we predictied the first 4 images of the test data and find out the labels for those images 11)We have taken Random data and load the data and ran the same model for random data set and predictied the labels with accuracy 83%.
