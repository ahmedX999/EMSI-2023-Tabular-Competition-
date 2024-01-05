Overview
Welcome to the EMSI 2023 Tabular Competition!

Your Goal: Your task is to use binary classification to predict a patient's smoking status given information about various other health indicators. Good luck! Have fun!
Evaluation
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

Submission File
For each id in the test set, you must predict the probability for the target variable smoking. The file should contain a header and have the following format:

id,smoking
159256,0.5
159257,0.5
159258,0.5
etc.
Timeline
Start Date - November 22, 2023
Entry Deadline - Same as the Final Submission Deadline
Team Merger Deadline - Same as the Final Submission Deadline
Final Submission Deadline - January 3, 2024
Prizes
1st Place - 3 bonus points on the Final Exam + 2 bonus points (in this competition) for the entire class of the winning team.
2nd Place - 2 bonus points on the Final Exam
3rd Place - 1 bonus point on the Final Exam
Please note:
Places cannot be shared:

In the event that several teams have the same ranking, priority will be given to the smallest team.
If several teams of the same size have the same ranking, a draw will determine which team will receive the bonus.
About the Tabular Playground Series
The goal of the Tabular Playground Series is to provide the Kaggle community with a variety of fairly light-weight challenges that can be used to learn and sharpen skills in different aspects of machine learning and data science. The duration of each competition will generally only last a few weeks, and may have longer or shorter durations depending on the challenge. The challenges will generally use fairly light-weight datasets that are synthetically generated from real-world data, and will provide an opportunity to quickly iterate through various model and feature engineering ideas, create visualizations, etc.

Synthetically-Generated Datasets
Using synthetic data for Playground competitions allows us to strike a balance between having real-world data (with named features) and ensuring test labels are not publicly available. This allows us to host competitions with more interesting datasets than in the past. While there are still challenges with synthetic data generation, the state-of-the-art is much better now than when we started the Tabular Playground Series two years ago, and that goal is to produce datasets that have far fewer artifacts. Please feel free to give us feedback on the datasets for the different competitions so that we can continue to improve!
