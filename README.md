# Image Classification
classifying images using convolutional neural networks.

Description of the model:
            Input data is of the form 3x32x32, since each image is a coloured image in RGB framework. Convolutional Layer1 will map the input images into 6X28X28 feature map using a kernel(filter) of size 5x5. Maxpooling operation is then performed resulting in 6x14x14 feature maps. Convolutional Layer2 will map the output of Maxpooling operation to 16x10x10 feature map which after performing maxpooling operation gets converted into 16x5x5 dimensions. Now this output is converted into a row vector of size 400 which is then fed to a fully connected layer (Logistic regression operation). Activation function used in this operation is ReLU (Rectified Linear Activation Function). After using one hidden layer we get the output which tells us the probabilites of image belonging to a particular class. Class with highest probability will be considered as the predicted output of the model.

 
