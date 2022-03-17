# 5001_Kaggle
5001 Kaggle Compitition(Individual Course Project)

# Stage 1
5001_Kaggle_FirstTry.ipynb is the code for the first stage. In this stage, the main target is to achieve 100% accuracy on the test set, so that we can augment the training set by adding the test set into it. 

In 5001_Kaggle_FirstTry.ipynb, the training sample No.39 has been removed as it contains NAN features. By using the LR classifier without normalization, the best result of 96.51% is achieved. By combing predictions given by different classifiers, we know there are 2 errors in the first 10 test samples. I manually fix it and achieved 100% accuracy.The 100% acc submission file is named sample_submission_ground.csv.

Adding the test set into the training set we got an augmented training set with 143 samples(including training samples No.39), which is named train_aug.csv. We try to train a classifier on this augmented dataset to get a better result in the rest of 51% evaluation data. 

# Stage 2
