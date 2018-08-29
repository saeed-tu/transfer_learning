# transfer_learning
Transfer learning is a learning method where we reuse a developed model for a different task as a start point for another task.   
In this script, we implement a simple transfer learning example with fine-tuning for the task of classifying cats and dogs using a 
trained model of VGG19 on ImageNet dataset. We remove the last FC layers of the VGG19 and attach a simple top model classifier.   
We have also chosen to fine tune the last block (block5) of VGG16 model and our top model which would increase the accuracy.  
Platform: Keras API (2.2.2) on top of TensorFlow GPU, tested on Windows10   
Python 3.5.2   
Jupyter Notebook 5.0.0  

[[(https://github.com/saeed-tu/transfer_learning/blob/master/transfer_learning_fine_tune.tif|alt=octocat]]
