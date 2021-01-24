# Abnormality Detection in bone X-Rays

On this project we are going to use MURA dataset which consists of 40,895 musculoskeletal radiograph images from 14,982 studies, where each study is manually labeled by radiologists as either normal or abnormal. Our task is to build at least 2 deep learning models to perform abnormality detection per study on MURA dataset. The models which used for this classification task are: 

* 2D Convolution Neural Network (2 different architectures) 
* 169-Layer DenseNet Pretrained Convolutional Neural Network

### Data Augmentation
Before feeding the images into the network, we applied normalization and transformations on the training and validation dataset. We scaled the variable-sized images to 224x224. On the training dataset, a Keras ImageDataGenerator object is used to apply data augmentation. The augmentation techniques that we used are Brightness Range and Zoom Range.

### Pixel Scaling
We also performed pixel Centering and Pixel Standardization.
