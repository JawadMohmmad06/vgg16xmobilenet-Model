
# Vgg16xMobilenet

My project focuses on sign language recognition, utilizing tools such as TensorFlow, Keras, and Python. The core of the project is a model created by merging the VGG16 and MobileNet models. The input layer includes a convolutional layer with 32 filters and a kernel size of (3,3), activated by the ReLU function. Following this, a max pooling layer with a pool size of (2,2) is applied. This layer is essential for the concatenation of the VGG16 and MobileNet architectures, resulting in an effective sign language recognition system.