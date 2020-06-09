# Trash Classification Using Convolutional Neural Networks
Spring 2020 CS230 Project code of Yujie He, Qinyue Gu, and Maoguo Shi.

Dataset: We use TrashNet collected by Gary Thung and Mindy Yang, which can be accessed here: https://github.com/garythung/trashnet. 

Model Structure: We use a modified AlexNet architecture with two convolutional layers of 384 filters taken out. We developed our model following lecture slides on course website, and add normalization following this website: https://medium.com/@smallfishbigsea/a-walk-through-of-alexnet-6cbd137a5637. We also consult the above website on adding dropout.

AlexCE_Plain contains our code for plain model with Softmax classifier in the last fully connected layer. AlexCE_Aug contains our code for model with Softmax classifier adding data augmentation and partial data augmentation. AlexCE_Drop contains our code for model with Softmax classifier adding dropout rate of 0.5 to the first and second fully connected layers.

AlexHinge_Plain contains our code for plain model with SVM classifier in the last fully connected layer. AlexHinge_Aug contains our code for model with SVM classifier adding data augmentation and partial data augmentation. AlexHinge_Drop contains our code for model with SVM classifier adding dropout rate of 0.5 to the first and second fully connected layers. We consulted the following website:
1. https://github.com/keras-team/keras/issues/2588
2. https://stackoverflow.com/questions/53019301/add-svm-to-last-layer

We also consulted the following websites for technical details in our code:
1. https://matplotlib.org/gallery/api/two_scales.html
2. https://stackoverflow.com/questions/42504652/how-to-update-tensorflow-on-mac
3. https://stackoverflow.com/questions/48608776/how-to-suppress-tensorflow-warning-displayed-in-result
4. https://stackoverflow.com/questions/59317919/warningtensorflowsample-weight-modes-were-coerced-from-to

For full description of our models and results, as well as a full reference list, please refer to our final report. For our Milestone #2 code, please see here: https://github.com/yujiehe05/YH_QG_MS_Milestone2
