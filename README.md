# mss-portfolio-Wang-Qinzhe-2022

## Modern Statistical Machine Learning Methods Applied to Airbnb
 
## Abstract:

Airbnb is one of the most popular room-booking platforms. The majority of bookings go successfully. However, some may run into a problem with availability. My research attempts to help consumers avoid being unable to book their favorite listings by examining how numerous criteria such as location, host, property condition, and seasonality, affect listing availability. More specifically, I consider regional data from Asheville, North Carolina, which is considered a tourist destination and is increasing in its popularity with regard to bookings. Motivated as such, I consider a data set from Inside Airbnb Data Platform, which covers such data as already mentioned. This data set has both categorical and numerical predictors.

My project's main purpose is to forecast whether or not an Airbnb listing is available, which is a classification problem. The primary choices of models are AdaBoost, regarding decision trees as weak leaners, and Random Forest. On the one hand, both models perform well in a dataset containing both categorical and numerical predictors. On the other hand, ensemble learning methods usually outperform a single tree (CART) with bagging (Random Forest) and boosting (AdaBoost) techniques to reduce the dispersion of the predictions. I trained each technique, tuned hyper-parameters, and evaluated performance with K-fold cross-validation, using accuracy rate as the evaluation metric. In addition, I connected the top 5 most important features to real-world reasons.
