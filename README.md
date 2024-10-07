# DiabetesPrediction

## Conclusion
1. diabetes, prevalentStroke, currentSmoker, BPMeds are binary values with low value count for 1. Eg: 0 has 3000 records while 1 has 100 or less than 50 rows.
2. Model accuracy for training and testing dataset are around 85%
3. VIF there is no evidance of VIF > 5
4. P-values for the model 2(i.e., m2) for all values are less than 0.05. Hence we can state that model 2 is the best model.
5. According the Wald Chi-Square analysis, we can state that feature prevalentHyp, age, and cigsPerDay are the top 3 most impactful features for predicting the heart stroke.
6. Achieved the ROC at 0.53
