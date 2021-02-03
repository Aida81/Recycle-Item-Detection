# Recycle-Item-Detection

Training an Object Detection Model for Raspberry Pi with TensorFlow API using Google COLAB
This Colab is for training a Tensorflow Model which is fully trained in Google Colab on Tensorflow 1.13 and then converted to a TFLite model to be used on the Raspberry Pi.

The Colab here could be easily converted to training any other type of visual detector using the same basic functions but with a different set of labeled images and just changes to the config file and label map files in the training folder.

Therefore, I am training it with my own dataset which 6 classes of Recycle Item consists of cardboard, glass, paper, metal, plastic and trash.

In file of Recycle item Image.zip, there are images dataset of the 6 classes which had split into train and test file.

In file of RecycleItem.zip, there are files of test.record, train.record, test_labels and train_labels. which used for training 

https://youtu.be/y41j4iJG6EQ
