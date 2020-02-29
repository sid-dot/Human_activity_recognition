# Human_activity_recognition

In this "Human Activity Recognition" I performed Both classical machine learning technique as well as simple LSTM Model.
Such that:* Classical Machine learning model are performed on an expert Engineered Features.
and       * In Simple LSTM Model I used the Raw Time-Series Data.

Both Deep learning and Classical machine learning Model performd better.

On Classical ML MODEL : I tried it with * Linear Models like(Logistic Regression, Linear SVC) * Non-Linear Model like(RBF SVM Classifier),
* Tree Based Models like (RandomForest and Decision Tree)

             ********************************************************************************************
                                  Comparision of Classical Machine learnin Models.
                     * *                                                                * *   
                     * *                            Accuracy     Error                  * *
                     * *                           ----------   --------                * *
                     * *     Logistic Regression :  96.27%       3.733%                 * *
                     * *     Linear SVC          : 96.61%       3.393%                  * *
                     * *     rbf SVM classifier  : 96.27%      3.733%                   * *
                     * *     DecisionTree        : 86.43%      13.57%                   * *
                     * *     Random Forest       : 91.31%      8.687%                   * *
                     * *     GradientBoosting DT : 91.31%      8.687%                   * *
              *********************************************************************************************  
 We can choose Logistic regression or Linear SVC or rbf SVM.
 Conclusion :
In the real world, domain-knowledge, EDA and feature-engineering matter most.
*********************************************************************************************************************************
                                            Model Performance of SIMPLE LSTM
 *****************************************************************************************************************************
                          With a simple 2 layer architecture we got 90.09% accuracy and a loss of 0.30
                                 We can further imporve the performace with Hyperparameter tuning.
