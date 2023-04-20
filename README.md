# DM_Assignment-2_rxn6413
Naive Bayes Classifier

The goal is to classify the review as Fresh or Rotten based on the text reviews of rotten tomatoes review dataset from Kaggle[1] using NBC.

        https://www.kaggle.com/datasets/ulrikthygepedersen/rotten-tomatoes-reviews

 I tried to apply NBC on the given rt_review dataset where review is classified into fresh or rotten.

And then used some techniques like stemming and lemmatization and other necessary things so that unnecessary words are dropped.

Find the probabilities of each word occurence and the calculating the conditional probability and probability of fresh and rotten.

The above information helps to calculate the accuracy using dev dataset and also smoothing is done to resolve zero probability issue.

Finally calculating the accuracy using test dataset.

From the above graphs we can understood that accuracy is higher when used lemmatization than stemming.

For more info and clarity see this blog:
https://rupininuthakki.wixsite.com/rupini11/post/review-classification-using-naive-bayes-classification
