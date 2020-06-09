# Trash Classification Using Convolutional Neural Networks
Spring 2020 CS230 Project code of Yujie He, Qinyue Gu, and Maoguo Shi.

Dataset: We use TrashNet collected by Gary Thung and Mindy Yang, which can be accessed here: https://github.com/garythung/trashnet. 

ResNet50_Modified contains our code for the modified ResNet50 Model. We consulted and adopted functions from Coursera Programming Assignment on Residual Networks, which can be accessed here: https://www.coursera.org/learn/convolutional-neural-networks/notebook/jK9EQ/residual-networks. We changed the AveragePooling layer before fully-connected layers to MaxPooling layer with the same filter size and stride. 

VGG11 conatins our code for VGG11 Model. We consulted these website: https://neurohive.io/en/popular-networks/vgg16/ and https://towardsdatascience.com/step-by-step-vgg16-implementation-in-keras-for-beginners-a833c686ae6c. 

AlexNet_Modified contains our code for the modified AlexNet Model. We developed our model following lecture slides on course website, and add normalization following this website: https://medium.com/@smallfishbigsea/a-walk-through-of-alexnet-6cbd137a5637. We also consult the above website on adding dropout. We deactivated two convolutional layer in original AlexNet model.

For full description of our models and results, as well as a full reference list, please refer to our Milestone #2 Writeup.
