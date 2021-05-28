## Credit_Risk_Analysis

OVERVIEW

The Purpose

The purpose of this analysis is to use the credit card dataset from a peer-to-peer lending services company called LendingClub. The dataset from this company will allow analysts to use algorithms to oversample the data, use a combinational approach, and compare 2 machine learning models. Using the final results of the dataset, analysts will evaluate the performance of the models and recommend whether or not the models should be used to predict credit risk for the LendingClub. 

RESULTS

Oversampling

* For the Native Random Oversampling data, results shows that the balanced accuracy test is 64.94%(0.6494575410534504), the precision is 1%(1.00), and the recall is 73%( 0.73).

Open the file containing Native_Random_Oversampling.
![Native_Random_Oversampling](/resources/Native_Random_Oversampling.png)
Close the file.
		
SMOTE Oversampling

*  For SMOTE Oversampling data, results shows that the balanced accuracy test is 64.94%(0.6494575410534504), the precision is 1%(1.00), and the recall is 73%( 0.73).

Open the file containing SMOTE_Oversampling.
![SMOTE_Oversampling](/resources/SMOTE_Oversampling.png)
Close the file.

Undersampling

*  For Undersampling data, results shows that the balanced accuracy test is 64%(0.6494575410534504), the precision is 1%(1.00), and the recall is 69%( 0.69).

Open the file containing Undersampling.
![Undersampling](/resources/Undersampling.png)
Close the file.

Combination

*  For the Combination of Oversampling and Undersampling data (Combination(Over and Under) Sampling), results shows that
the balanced accuracy test is 54.42%(0.5442369453268994), the precision is 1%(1.00), and the recall is 73%( 0.73).

Open the file containing Combination_of_Oversampling_and_Undersampling.
![Combination_of_Oversampling_and_Undersampling](/resources/Combination_of_Oversampling_and_Undersampling.png)
Close the file.

Balanced Random Forest Classifier

* For Balanced Random Forest Classifier data, results shows that the balanced accuracy test is 76.17%(0.7617095603945788), the precision is 1%(1.00), and the recall is 64%( 0.64).

Open the file containing Balanced_Random_Forest_Classifier.
![Balanced_Random_Forest_Classifier](/resources/Balanced_Random_Forest_Classifier.png)
Close the file.

Easy Ensemble

* For Easy Ensemble AdaBoost Classifier data, results shows that the balanced accuracy test is 91.78%(0.9178773283613644), the precision is 1%(1.00), and the recall is 89%(0.89).

Open the file containing Easy_Ensemble_AdaBoost_Classifier.
![Easy_Ensemble_AdaBoost_Classifier](/resources/Easy_Ensemble_AdaBoost_Classifier.png)
Close the file.

SUMMARY

Results

The Oversampled, Undersampled, and Combination of (Over and Under) Sampled data predicted which loans are at higher risk for LendingClub. The accuracy rate of the data provided was lower than the data provided for Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier. In addition, the accuracy rate of the data provided from Easy Ensemble AdaBoost Classifier was higher than Balanced Random Forest Classifier. As aforementioned, Easy Ensemble AdaBoost Classifier data results shows that the balanced accuracy test is 91.78%(0.9178773283613644), the precision is 1%(1.00), and the recall is 89%(0.89).

Recommendation

With Easy Ensemble AdaBoost Classifier having the highest percentage of accuracy score, balance of precision, and recall scores. It is recommended that LendingClub uses Easy Ensemble AdaBoost Classifier's data to predict credit risk. 
