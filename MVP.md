
# Analysis of LendingClub loan defaults

The goal of this project is predict if a loan will default based on the factors known at the time of the loan was issued. 

Revelant features will include, but are not limited to annual income, loan amount, interest rate, and homeownership. 

Since only 1/20 of the loans default, the metric to be optimized will be precision (and possibly f1 score).  
(It's more important to avoid defaults than lose potential nondefaulting loans because we as an individual investor cannot invest in all loans anyway.)

Best model so far is Logistic regression using class weights (20X the defaulted loans0 but may change as other features are added. 

![example](https://user-images.githubusercontent.com/11722304/117891454-ec9be900-b284-11eb-9260-f157532ad617.png)


Accuracy:  0.61

Precision: 0.08

***Recall: 0.68***

F1:        0.15
