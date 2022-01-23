# Handwritten Digit Recognizer

Aim: To build a model which can classify digits 0 to 9. The images are in greyscale of size 32 by 32 pixels.  The dataset was taken from Kaggle. 
Data link: https://www.kaggle.com/c/digit-recognizer

We have been provided with two dataset

1.  Training - 42000 images 
2.  Test - 28000 images

The submission has to be by running the model on the training dataset. To test the model, Scikit-learn train_test_split was usedon the Training dataset.

For the Analysis, four custom models were tested.

1. Two Conventional Neural Networks.
    
    1. Shallow Model: 25450 trainable parameters , 2 layers
       
       Accuracy on Test set: 0.972
       
    2. Deep Neural Network: 1,494,154 trainable parameters,5 layers 
      
       Accuracy on Test set: 0.972

2. Two Convolution Neural Networks.
    
    1. Shallow Model(CNN1): 131,114trainable parameters , 5 layers
       
       Accuracy on Test set: 0.987
       
    2. Deep Neural Network(CNN2): 37,242 trainable parameters,7 layers 
      
       Accuracy on Test set: 0.972
       
       
 After looking at the results CNN1 was choosen for Kaggle  submission. 
 Was placed in top (35 percentile)
