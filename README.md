# fake_or_real_Accounts

SVM, kNN, RandomForest, NaiveBayes 등의 머신 러닝 기술 성능을 비교하기 위해 페이스북 계정에 대한 데이터를 사용했습니다.
"Kaggle.com"에서 데이터를 얻고 계정이 실제처럼 보이지만 실제로는 그렇지 않은 계정에 대해 분석했습니다.
데이터를 테스트 데이터와 학습 데이터로 따로 저장하고 데이터와 무관한 변수는 넣지 않았습니다.

* train data  결과
kNN은 84.38%, DecisionTree 방법은 93.24%, RandomForest 방법은 95.04%, NaiveBayes는 79.58%, SVM은 90.38%였습니다. RandomForest 방법이 가장 높은 정확도를 보였고 NaiveBayes 방법이 가장 낮은 정확도를 보였습니다

* test 데이터 결과
예측 데이터와 테스트 데이터 세트 간의 일치율은 예측된 실제 또는 가짜 데이터를 csv 파일로 저장하여 원본 데이터의 실제 또는 가짜와의 일치율로 계산했습니다.
 그 결과 kNN 80.7%, DecisionTree 97.7%, RandomForest 93%, NaiveBayes 83.4%, SVM 83%, NaiveBayes 83.4%가 DecisionTree에서 가장 높았고 kNN에서 가장 낮았습니다.


다양한 분류 예측 기법을 적용한 결과 낮은 확률은 80.7%, 가장 높은 예측 정확도는 97.7%였다. 실제 또는 가짜를 예측하는 알고리즘을 구축할 때 필요한 변수를 선택하고 숫자 데이터를 범주의 '가장 적절한' 범주에 대한 범주 데이터로 변환하는 것이 중요합니다. 되려고. 그러나 97.7%의 예측 정확도는 카테고리가 잘 분류되었음을 입증했습니다. 결론적으로, 실제 계정인지 가짜 계정인지는 변수 No.Frirend와 학력, 나에 대한 가족, 성별, 관계, 포토태그, 체크인, 좋아요, 메모에 의해 결정된다고 할 수 있습니다.


** 모든 변수는 더 나은 가독성을 위해 사전 처리되었습니다.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
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
