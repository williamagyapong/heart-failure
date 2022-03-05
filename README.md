
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Predicting Mortality by Heart Failure

According to the World Health Organization, cardiovascular diseases
(CVDs) are the number one cause of death globally, taking an estimated
**17.9 million** lives each year, which accounts for 31% of all deaths
worlwide. Of these deaths, 85% are due to heart attack and stroke. Heart
failure is a common event caused by cardiovascular diseases.

The early detection of people with cardiovascular diseases or who are at
high cardiovascular risk due to the presence of one or more risk factors
is paramount to reducing deaths arising from heart failures. As a
result, predictive models become indispensable. The dataset explored in
this project contains 12 features that can be used to predict mortality
by heart failure. The goal of this project, therefore, is to **identify
an appropriate classification model that can accurately predict the
mortality of patients with heart failure**.

<!-- Various classification models, as can be found in the Predictive Model section of this report, will be explored with the hope of coming up with a model that has high prediction accuracy.  -->

Ten different classification models were fitted to the heart failure
data set. From these models, three classifiers - *Linear Discriminant
Analysis (LDA)* model, *Logistic Regression* model, and *Random Forest*
model - emerged as best models with the same predictive accuracy of `78
%`. The LDA model was dropped because it was the most complex model
among the three since it was based on 11 predictors. The other two
models were each based on only 4 predictors but the Random Forest model
was chosen as the overall best model because of some advantages it has
over the competing Logistic Regression model. That is, unlike the
Logistic Regression model, the Random Forest model is non-linear
classifier which does not require the data to be linearly separable.
Therefore, it was concluded that a Random Forest model with `Ejection
Fraction`, `Serum Creatinine`, `Anaemia`, and `High Blood Pressure` is
the best model for predicting the death event of a patient with a heart
failure.

I consider this to be a preliminary analysis since more can be done to
improve the predictive power. For instance, treating the issue of class
imbalance and handling outliers could enhance model performance. Again, a formal
modeling procedure such as PCA could be utilized to identify the most significant features.

Please see the full report
[here](https://github.com/williamagyapong/heart-failure/blob/master/report.pdf).
You can also access the codes in the [RMarkdown
file](https://github.com/williamagyapong/heart-failure/blob/master/report.Rmd).

<!-- badges: start -->

<!-- badges: end -->
