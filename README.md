# Spam-SMS-Classification-and-Clustering.

 The Dataset is open-source from Kaggle https://www.kaggle.com/uciml/sms-spam-collection-dataset.

 Dataset has 5,574 observations and heavliy imbalanced. It is then splitted into Trainset and Testset by ratio of 85% - 15%.

## 1. Classification:
The first part is to build binary classifier to recoginize either the message is spam or ham.
Model 1 is CNN With Embedding Layer. This model has F-1 of 96%.
Model 2 is Multi-Chanel Input CNN with Embedding Layter. This model has F-1 score of 96.8%  and Accuracy = 99.2%.

## 2. Topic Modelling.
Both KMeans with SVD and Latent Dirichlet Allocation (LDA) suggest 2 clusters for this dataset.
For LDA, topic 1 is most likely to be "spam" and topic 2 is most like to be "ham".



