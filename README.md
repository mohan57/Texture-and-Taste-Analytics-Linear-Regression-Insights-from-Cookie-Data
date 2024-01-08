# Texture-and-Taste-Analytics-Linear-Regression-Insights-from-Cookie-Data

This project involves a comprehensive statistical analysis of cookie data to explore the relationships between various taste and texture features. It primarily focuses on linear regression techniques to understand how features like 'Texture Hardness', 'Texture Chewiness', and 'Taste Sweetness' interrelate and influence each other, using rigorous statistical tests and model evaluation criteria to draw accurate conclusions.

## Description

The project delved into a detailed analysis of the interplay between 'Texture Hardness' and 'Texture Chewiness' in cookies, using linear regression techniques. To ensure the validity of the linear regression model, key assumptions were rigorously tested. Normality of the data was assessed using distribution plots, while scatter plots were employed to verify homoscedasticity. The Durbin-Watson test was used to confirm the independence of the variables. A pivotal part of the analysis was the Linear Regression t-test, which established 'Texture Hardness' as a statistically significant predictor of 'Texture Chewiness', marking a critical finding in the study.

Further, the model demonstrated a positive correlation between 'Texture Hardness', 'Taste Sweetness', and 'Texture Chewiness', evidenced by an impressive R-squared value of 0.929. This high value indicated that the model could explain a significant proportion of the variability in 'Texture Chewiness'. An exploratory phase involved assessing 'Taste Bitterness' as a potential variable. However, 'Taste Bitterness' was found to be an insignificant predictor of 'Texture Chewiness', with a p-value of 0.717, suggesting it did not contribute meaningfully to the model.

Based on these insights, a refined predictive model was proposed: Texture Chewiness = β0 + β1 * Texture Hardness + β2 * Taste Sweetness. This model not only retained the significant predictors but also improved the R-squared value to 0.930, further enhancing the model's accuracy and reliability. This improvement underscored the model's robustness in predicting 'Texture Chewiness', making it a valuable tool for understanding and predicting cookie texture based on its hardness and taste properties.


## Authors

contact info

Mohan Thota 
mohant@bu.edu/mohan5thota@gmail.com

## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the [APACHE 2.0] License - see the LICENSE.md file for details

## Acknowledgments

Guidance, code snippets, etc.
* [Proffessor](https://www.bu.edu/cs/profiles/wayne-snyder/)

