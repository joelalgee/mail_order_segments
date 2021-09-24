# Mail-Order Customer Segments Identification

Identifying segments of the population that form the core customer base for a mail-order sales company, with unsupervised learning techniques in Python

## Summary

In this project, I applied unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments could then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns.

This project had a series of predefined steps to follow, with the analysis for each step needing to be coded. Techniques called upon included cleaning, feature engineering and scaling, dimensionality reduction via PCA, and clustering.

The data for this project cannot be shared, so the only file available here is Identify_Customer_Segments.html, a static HTML version of the Jupyter Notebook file.

## Results

The proportion of people in each cluster for the general population, and the proportions for the customers were quite different, suggesting that only particular segments of the population that are interested in the company's products.

Cluster 0 was overrepresented with the mail-order company compared to the general population. This segment of the population scores low on the first principal component, and high on the third, suggesting affluent suburban/country dwellers who are males of a certain character (combative, dominant, critical, rational, event-oriented) are excellent marketing prospects.

Cluster 3 was underrepresented with the mail-order company compared to the general population. This segment of the population scores high on the first principal component, and low on the second and third, suggesting poor inner city inhabitants, who are young and impulsive are not good marketing prospects.

## Credits

This project, and parts of the code, were provided by [Udacity](https://www.udacity.com) as part of their [Intro to Machine Learning with Pytorch nanodegree](https://www.udacity.com/course/intro-to-machine-learning-nanodegree--nd229).
