# Predicting Crowdfunding Success for Classroom Projects on DonorsChoose.org

## Background
DonorsChoose.org is a crowdfunding website that connect public school teachers to donors on classroom projects. I would like to build a tool for new teachers to predict whether their first classroom project will get funded on the website.

## Description
I implemented logistic regression, K-nearest Neighbors, Random Forest and Gradient Boosting classifiers to predict the crowdfunding success probability of new classroom projects on DonorsChoose.org.

## Result
My final model is a gradient boosting classifier model with Area Under the ROC Curve (AUC) score of 0.718.

| Model        | AUC           |
| ------------- |:-------------:|
| Gradient Boosting + KNN | 0.718 |
| Random Forest + KNN | 0.711      |
| Logistic Regression + Select K Best + KNN | 0.664 |

More details are coming soon!

# Licenses
See the [LICENSE](LICENSE.md) file for license rights and limitations (MIT).
