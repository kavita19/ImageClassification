# ImageClassification

Summary of report:
To improve accuracy of image classification task I have applied transfer learning techniques by using InceptionResNetV2 and ResNet152V2 pretrained models. I have created my base model using Keras and TensorFlow library. In addition, I preprocessed the data according to pretrained model i.e., changed input shape and freeze top layers according to requirement of each imagenet model. Also, I have added my own layers for transfer learning and trained my model with Adam optimizer by changing learning rate. For InceptionReseNetV2 pretrained weights I got 92.21 % and for ResNet152V2 90.58% accuracy.
