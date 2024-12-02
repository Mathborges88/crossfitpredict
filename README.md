# Exploratory Analysis of CrossFit Athletes

When planning my first data science project to showcase in my portfolio, I spent a lot of time envisioning something robust, with multiple advanced tools and techniques. However, I realized that this pursuit of 'perfection' was delaying both practice and the demonstration of the skills I already possess. Therefore, I decided to start with something more straightforward: a simple exploratory analysis that could pave the way for new insights and future, more elaborate projects. I chose CrossFit as the theme, both because it is a personal passion and due to my prior knowledge of the sport.

The detailed dataset has been compiled from competitions and events held globally. This dataset contains data on athlete demographics, including age, gender, and experience in training, alongside performance metrics like time, weight lifted, and personal records.

My goal is to uncover patterns and correlations to understand how performance can be improved and how physiology interferes with the results of the athletes.

# Conclusion

After identifying which variables have the greatest importance, meaning those that most influence the prediction of the workouts, I expected the results to closely mirror the correlation table, but it wasn't exactly like that. For example, for the workout Fran, the most correlated variable (among the independent variables) in the correlation table was run400, yet after running the machine learning models, Pull-up was identified as the most important, followed by run5k, with run400 coming in sixth place.

It was interesting to see that for the workout Grace, which consists of just 30 CandJ, the most important variable turned out to be CandJ itself.

As for the metrics, MSE and R² are not optimal and can be improved, but for the goal of identifying the variables that most impact the results of the workouts, they were satisfactory.

# Next Steps

* Improve the evaluation metrics by refining the models, tuning hyperparameters, and further processing the data. Assess whether the results change after these improvements.
* Handle the ignored categorical columns through feature engineering, and then build another machine learning model to determine if these columns help predict the workout results.
* Most importantly, finding better datasets, possibly through web scraping, to develop a machine learning model capable of predicting, based on PR results and other workouts, the results of any input workout following predefined rules.

