# Machine Learning Engineer Nanodegree
# Capstone Proposal
# Identify Monkey

#Domain Background:
-Monkey classification is to classify major types of monkeys based on biometric cues. Usually facial images are used to extract features and then a classifier is applied to the extracted features to learn a type of monkey recognizer. That’s in Computer Vision and Biometrics fields. The monkey classification result is often a type of monkey. I used two pre-trained model to compare between them and to find the best accuracy.


#Download dataset: "https://www.kaggle.com/slothkong/10-monkey-species/data"

#I used vgg16 the top accuracy= 0.9818
#And inception_v3 the top accuracy= 0.9945

#Project Design

My libraries : pandas, numpy, os, keras, matplotlib
My workflow :
- choosing model for extracted features from keras then load the model from keras.
- remove the predicted layer.
- load data-set.
- build a dense and dropout layer.
- train the layers of a dense and dropout to predict type of monkey.
- use another pre-trained model.
- try use different numbers of  a dense layer, dropout layer and neurons to find the best numbers of a dense layer, dropout layer and neurons get high validation accuracy.
- test the best numbers  of  a dense layer, dropout layer and neurons find it on test data.
- by using the model make predict for monkeys.

#the best accuracy when using inception_v3 accuracy= 0.9945
