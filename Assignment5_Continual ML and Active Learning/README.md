Assignment 5 : Continual ML and Active Learning 

Part A: 
end2end well annotated and commented demo of continual learning using avalanche library in colab (https://colab.research.google.com/drive/1X-QiZSDFmifUbkf6YfSNTFDPMEHddwOs?usp=sharing)

We are taking one of the benchamark datasets that available in avalanche framework ie PermutedMNIST and use Naive strategy to train the models. We leveraging the simpleMLP model and predict the hand writing digits
 
 
 Part B:
 Active learning with lightly.ai (https://colab.research.google.com/drive/1aYQ0hgXug-dpk4ICPflkN5OXF8ZMAZse?usp=sharing)
 Here we use lightly ai to create the embeddings for the training data and use that embeddings to train the classifier for prediction. The LogisticRegression classifier needs the embeddings as features for its classification
 
 
 Part C:
 Active learning with label studio (https://colab.research.google.com/drive/1BcJlwUk8FBiQmhFBxJ2dJHmgegxc2Emt?usp=sharing)
 Here we are label studio and label the data manually and use it for helping the model to understand while training, and predict the correct category.
