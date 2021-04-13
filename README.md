# MultiLabelClassification
  Model ResNet-50, Optimizer Adam
  
#  Description of the task
  When marking out personal protective equipment, several attributes are noted for one class. Thus, it turns out that one object belongs to several categories at once. Therefore,  the neural network needs to be trained for multivalued classification.

#  Learning outcomes of the NN:
  After the final training, the NN showed an accuracy of 83%. The value of the loss function was 0.0463. Accuracy has been improved with:
  1. Data augmentation - added random rotation by 10 degrees.
  2. Change of the optimizer - the smallest accuracy was in the case of stochastic gradient descent, the greatest accuracy was shown by Adam.

  As part of the exam work on the course "Machine Learning", the Resnet-50 neural network was trained. For this purpose, training and test datasets were formed, Adam was used as an optimizer, functions were developed to calculate the accuracy and losses of the neural network during training.
