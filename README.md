#Predicting the status of an applicant whether he/she is eligible for Loan

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. 

Models used:
  1. Random Forest - with accuracy of 80% and then extracted the most important features with use of feature_importances_ from RandomForestClassifier model
  2. Gradient Boosting - achieved the accuracy of 99%
  3. Logistic Regression - with accuracy of 81%
  
 From the above models, we can say that the model which is boosted(Gradient Boosting) has the high accuracy when compared with others. So, we can clearly say that the Ensemble methods are very useful in improving the accuracy of the model.
 
 Findings are:
  1. Applicants who are male and married tends to have more applicant income whereas applicant who are female and married have least applicant income

  2. Applicants who are male and are graduated have more applicant income over the applicants who have not graduated.

  3. Again the applicants who are married and graduated have the more applicant income.

  4. Applicants who are not self employed have more applicant income than the applicants who are self employed.

  5. Applicants who have more dependents have least applicant income whereas applicants which have no dependents have maximum applicant income.

  6. Applicants who have property in urban and have credit history have maximum applicant income

  7. Applicants who are graduate and have credit history have more applicant income.

  8. Loan Amount is linearly dependent on Applicant income

  9. From heatmaps, applicant income and loan amount are highly positively correlated.

  10. Male applicants are more than female applicants.

  11. No of applicants who are married are more than no of applicants who are not married.

  12. Applicants with no dependents are maximum.

  13. Applicants with graduation are more than applicants whith no graduation.

  14. Property area is to be find more in semi urban areas and minimum in rural areas.
