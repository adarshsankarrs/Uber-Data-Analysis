
# Uber Data Analysis

This Uber Data Classification process simplifies the prediction of the number of trips based on travel distance. First, it categorizes distances into 'Low,' 'Medium,' and 'High.' Relevant features like starting point, destination, and purpose, along with the target variable 'Number of Trips,' are selected. Categorical variables are converted for machine learning. The dataset is split for training and testing. A Random Forest Classifier is employed, tuning hyperparameters for better performance. The model's accuracy in predicting trip categories is then evaluated on the test set. In essence, this approach helps anticipate whether an Uber trip will fall into categories of 'Low,' 'Medium,' or 'High' trip numbers, offering insights into travel patterns



Table of Contents 
=================
- [Dataset Information](#Dataset-Information)
- [Work Done](#Work-Done)


## Dataset Information: 


The Uber Drives dataset contains information about Uber trips, and the analysis in this code focuses on visualizing the distribution of trips over different hours of the day. The dataset likely includes details such as the date and time of each trip, the starting and ending locations.



## Work Done 
Five segments of analysis performed as follows:

 1.⁠ ⁠Purpose Analysis:
   - Counts and lists trip purposes.
   - Visualizes purpose distribution with a bar plot.

 2.⁠ ⁠Location Analysis:
   - Counts unique start and end locations.
   - Displays counts with a horizontal bar plot.

 3.⁠ ⁠Category Analysis:
   - Shows the proportion of trip categories in a pie chart.

 4.⁠ ⁠Monthly Analysis:
   - Illustrates trip distribution across months with a bar plot.

 5.⁠ ⁠Hourly Analysis:
   - Plots a line graph to reveal how trip numbers change throughout the day.