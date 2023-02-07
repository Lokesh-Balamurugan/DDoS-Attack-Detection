# DDoS-Attack-Detection

The proposed system is capable of classifying DDoS attacks as benign and malignant and also achieves high accuracy (97.6%). A total of 865893 rows and 4 features (after feature selection) are used for training and testing the models. The same system, when trained and fitted on a dataset without feature selection, achieves an accuracy higher than 99%, which ultimately may be an absolute indicator of overfitting. Five different algorithms (Random Forest Classifier, Logistic Regression, Support Vector Machine Classifier, Neural Networks, Gaussian Naïve Bayes) are employed for classification and their performances are evaluated using metrics like accuracy, precision, recall, and f1 score.

![Screenshot (367)](https://user-images.githubusercontent.com/70794697/217294111-e2f27a17-a435-43b6-8cce-0b1d68d09dc1.png)

![Screenshot (368)](https://user-images.githubusercontent.com/70794697/217294152-73dbe557-b510-4488-ac13-f15b20747a3a.png)


![Screenshot (369)](https://user-images.githubusercontent.com/70794697/217294397-50f6272c-467e-451c-9635-5588b2ba8069.png)


The graph above displays the total performance of all the employed algorithms. Random Forest Classifier performed the best, with an accuracy score of 97.60%, while Gaussian Naive Bayes received the lowest score of 78.43%. This pattern is also evident in the precision score, where Gaussian Naive Bayes received a score of 94.36% and Random Forest Classifier received a score of 99.46%, neither of which is very low.

In this project, few Machine Learning models were employed to classify whether the exposed DDoS attack is Benign or Malignant. The created system searches for any distinct pattern in the data that is recorded during an assault and divides it into the two categories that were previously discussed. Despite the fact that all of the models gave results with outstanding accuracy, Random Forest Classifier performed better than the others in terms of time consumption, precision score, recall score and f1 score, and it also had a little higher accuracy (97.80%). For each model, a total of more than 500,000 records were used for training, and the remaining records were used for validation and testing. By increasing the number of attack records, more features may be learned and retrieved by the model, thus boosting its accuracy.

