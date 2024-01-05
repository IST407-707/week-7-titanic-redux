# Case Study:  Titanic Data

In this study, you will use the Titanic Data set (introduced in the `Decision Tree` lab) to build a classifier that predicts the `survived` column.  You can access the titanic dataset through the `seaborn` library. Following from the exercise in the lab:

- Be thoughtful about the removal of NAs; are there features you can safely drop?  Can imputation help?
- Evaluate your performance using cross validation; manually tune your parameters (ccp_alpha, max_depth) to identify the best performance (f1-score) you can.  Does traiing with imputed data help?  Make sure you explain in your methods section how you used imputation.
- After tuning, inspect your decision tree.  Which features are most important?  Does this make sense to you?  What does it tell you about what happened on the titanic?  Research the disaster a little and see if your data makes sense given what you find.

You should be able to achieve an f1-score of better than 70%.
