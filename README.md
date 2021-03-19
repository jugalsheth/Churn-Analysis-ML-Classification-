
![image](https://user-images.githubusercontent.com/49743328/111844446-70ff6a80-88d9-11eb-9095-264084a93962.png)

# Churn Classification
Here i have tried to explore the churn dataset and applied Analytical and Machine learning principles to classify on validation and new data if the customer will be retained or convereted

# Motivation
AIskunkworks : The Machine learning and Artificial Intelligence club at Northeastern University-Boston,USA, Gave me this challenge in order to test my skills to join the Model Interpretability Research Group.
This Dataset was perfect to showcase all the basic skills that i have learned and honed over the years

# Understanding and explaination in short
- pandas to load csv
- .info() to check the structure, thankfully no null values
- SPlit columns to dependant and independant features, converted the target values from categorical to 0 and 1
- Vital utilization of Sklearn, train_test_split, StandardScalar{ to normalize the nymerical data }
- pandas.get_dummies for encoding
- seaborn to plot the structure of columns  ---> explored the distribution of data
- Applied KNearestNeighbour(unspervised) and RandomForest(supervised) algorithms to classify
- Validated both of them with Accuracy score, confusion matrix and precision, recall, f1-score, support
- Randomforest performed well, atleast in this case

# Usage
Please take a look at my code, its inspired by the concepts and practices i learned from @krishnaik 

