# Class

There were many steps involved, first it was understanding the data. Then another issues I ran into was jumping into running the ML on the data set without looking at the set. I had to clean up some of the variables before I started to try the different ML options. I tried decision trees, SVM, PCA, random forests. Random forests had the best sensitivity which is what is valued in the biomedical field. The statistics for the random forest can be seen below. 


Overall Statistics

               Accuracy : 0.9986          
                 95% CI : (0.9975, 0.9993)
    No Information Rate : 0.2845          
    P-Value [Acc > NIR] : < 2.2e-16       
                                          
                  Kappa : 0.9982          
 Mcnemar's Test P-Value : NA              

Statistics by Class:

                     Class: A Class: B Class: C Class: D Class: E
Sensitivity            0.9996   0.9987   0.9985   0.9969   0.9986
Specificity            0.9996   0.9995   0.9995   0.9997   0.9998
Pos Pred Value         0.9991   0.9980   0.9978   0.9984   0.9993
Neg Pred Value         0.9998   0.9997   0.9997   0.9994   0.9997
Prevalence             0.2845   0.1935   0.1744   0.1639   0.1838
Detection Rate         0.2843   0.1932   0.1741   0.1634   0.1835
Detection Prevalence   0.2846   0.1936   0.1745   0.1637   0.1837
Balanced Accuracy      0.9996   0.9991   0.9990   0.9983   0.9992
