# Analysis of Blue Nile Diamond Prices
Abhishek Bada, Christian Schroeder, and Timothy Tyree

School of Data Science, University of Virginia

STAT 6021: Linear Models for Data Science

### Executive Summary
This report provides an analysis and evaluation of the variety of factors that can drive diamond pricing. The questions answered in this paper are:
* Is it beneficial to group the classes of the categorical variables?
  - Yes, by grouping certain categories in the predictor variables we were able to create a model that accounted for more variation at a slight loss of adjusted R2 value. (See “Grouping Categorical Variables” for details)
* Which variable, after carat, influences the prediction the most?
  - We found that “Clarity” was the most influential predictor variable after “Carat”. (See “Secondary Predictor Analysis” for details)
* Can we create a model that better predicts price than a model that only uses carat as the single variable?
  - Yes, the model lm(log(price)~ log(carat)+cut+color+clarity) was better than using “Carat” as our only predictor. (See “Testing the Final Model” for details)

The results of this research show what we believe to be the optimal model for determining the price of diamonds at Blue Nile. Specifically, it was determined that combining several attributes of key variables into larger groups would provide more flexibility for predicting future prices, while retaining accuracy.

Final Report: [Analysis of Blue Nile Diamond Prices](https://github.com/christianaaronschroeder/diamond-price-analysis/blob/main/Analysis%20of%20Blue%20Nile%20Diamond%20Prices.pdf)
