# CasestudyCNN

What is CNN?
Convolutional neural network or CNN in short is a class of deep neural network to analyze visual imageery
>Convolution is a mathemetical operation which invloves 3 operations: Multiplication, Addition, Shifting(2 functions producing third function function and expresses how one is modified by the other)
>There are 4 main components of CNN
1.Convolution
2.Non-linearity (Activation layer)
3.Pooling/sub-sampling
4.Classification(Fully connected layer/dense layer)
>The first three components come under the extraction and learning of features of an image
CNN ARCHITECTURE:
![image](https://github.com/AnanyaBathini/CasestudyCNN/assets/143894181/cb83ab6e-5b75-4174-898e-add541fc346b)

CONVOLUTIONAL LAYER:
>that performs convolution
>Types:CONV1D,CON2D
>feature size=((Image size-Kernel size)/stride)+1
PADDING:
>Extra pixels
>usually used to maintain the sizee of the input when a convolutional layer is used
>Adding a layer of pixels around the edge of an image inorder to preserve the true size of the input image when convolution is occuring?
ACTIVATION LAYER:
>Convolutional layer is followed by an activation layer
>It helps in capturing and highlighting relevant features by applying non linear transformations to the convolutional objects
>structures within that data
POOLING LAYER:
>Pooling layer is done after the convolutional layer
>It applies non linear down sampling on activation maps
>responsible for reducing spatial size of the convolved features
>decreases the computational power that is required to process the data
>We use maxpooling and average pooling
DROPOUT LAYER:
>Regularization technique used to reduce overfitting in the neura network
>reduces error causing data(?) to an extent possible
>improves generalization of the model
FLATTEN LAYER:
>flattens the pooled feature map into a column
FULLY CONNECTED LAYER:
>Dense layer
>Responsible for learning and modeling complex relationships in the data
>Relu and Softmax are commonly used activation functions in a FC layer
>We use ANN in FC layer

![image](https://github.com/AnanyaBathini/CasestudyCNN/assets/143894181/5ba7102b-5e57-48bb-b04c-8976e407a283)

