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
https://www.google.com/imgres?imgurl=https%3A%2F%2Feditor.analyticsvidhya.com%2Fuploads%2F90650dnn2.jpeg&tbnid=LJE62p6XfyT2-M&vet=12ahUKEwjP8NCK_JiBAxVZq2MGHdIHAeYQMygAegQIARBy..i&imgrefurl=https%3A%2F%2Fwww.analyticsvidhya.com%2Fblog%2F2020%2F10%2Fwhat-is-the-convolutional-neural-network-architecture%2F&docid=rOrj5qxKPbPf9M&w=1644&h=880&q=convolutional%20neural%20network%20architecture&ved=2ahUKEwjP8NCK_JiBAxVZq2MGHdIHAeYQMygAegQIARBy
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
>https://www.google.com/url?sa=i&url=https%3A%2F%2Fpyimagesearch.com%2F2021%2F05%2F14%2Fconvolutional-neural-networks-cnns-and-layer-types%2F&psig=AOvVaw0NdTYY3lW-wOEDP4pM8DS3&ust=1694192276928000&source=images&cd=vfe&opi=89978449&ved=0CBAQjRxqFwoTCMCF-5j8mIEDFQAAAAAdAAAAABAE
