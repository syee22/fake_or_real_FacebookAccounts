# fake_or_real_jupyter
Hello !
To compare machine learning techniques performances of SVM,kNN,RandomForest,NaiveBayes etc,.i used data about that facebook's accounts are real or fake?
I get data from "Kaggle.com" and analyzed  about accounts look as a real but really not. 
I stored the data separately as test data and train data, didn't put data irrelevant variables.

* TRAIN DATA RESULT
kNN was 84.38%, DecisionTree method was 93.24%, RandomForest method was 95.04%, NaiveBayes was 79.58%, and SVM was 90.38%. RandomForest method showed the highest accuracy and NaiveBayes method showed the lowest accuracy.

* TEST DATA RESULT
The match rate between the predicted data and the test data set was calculated as the match rate with the real or fake of the original data by saving the predicted real or fake data as a csv file using Excel.
 As a result, kNN 80.7%, DecisionTree 97.7%, RandomForest 93%, NaiveBayes 83.4%, SVM 83%, and NaiveBayes 83.4% were the highest in DecisionTree and lowest in kNN.


As a result of applying various classification prediction techniques, the low probability was 80.7% and the highest prediction accuracy was 97.7%. When building an algorithm to predict real or fake, it is important to select the necessary variables and convert the numerical data into categorical data to 'the most appropriate' category of the category. to be. However, the prediction accuracy of 97.7% proved that the category was well categorized. In conclusion, whether it is a real account or a fake account can be said to be determined by variables No.Frirend and education, about me, family, gender, relationship, phototag, phototag, checkin, like, and notes.


** All variables have been preprocessed for better readability.
I showed you the conclusion that i tried to make
You can try it following my code

THANKS.
