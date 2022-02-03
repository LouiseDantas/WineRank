# Introduction
### This project is an **exploratory analysis** and a **quality prediction** of a wine dataset in Kaggle.
We used machine learning concepts and data mining to train a model able to classify new wines as low, medium or high quality.




# Exploratory Analysis

The data provided comprised white and red wines (didn't mention the grape) with variaton of chemical components and properties as sugar, acids, pH, density, alcohol etc.

We saw that 93% of the data is about medium-quality wines, 4% about low-quality and 3% about high-quality.
Which is not ideal for an analysis and machine learning model.

We found there's a moderate correlation between wine quality and **alcohool presence (+0.48)** and also moderate correlation with **volatile acidity (-0.4%)**.

The data shows **correlation between total sulfur dioxide and residual sugar**. Which makes us believe we could drop one of the features.

We also see **red wines** tend to have lower total sulfur dioxide, higher volatile acidity and lower residual sugar when compared to **white wines**.

# Machine Learning Model

We trained 6 models and found Decision as the better performing one.
Since the train data is not well balanced, the model is not generalizing well for low and high quality wines. **Decision Tree** identified 70% of the low-quality wines, which can be useful for a wine boutique that wants to avoid ordering low-quality from a distributor.


# Next Steps

We would need a better ballance between low quality, medium and high quality.
More features such as wine grapes and wine price which can be very useful in our model.

Work with inferential statistics to validade hypotesis.
