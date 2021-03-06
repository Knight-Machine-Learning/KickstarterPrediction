# KickstarterPrediction
Predicting if kickstarter projects will succeed or not

Welcome to my project!

The goal of this project is to create the best classifier to predict whether or not a given kickstarter project will reach its goal. I 
will be using the XGBoost classification algorithm for my model. Kickstarter is a crowdfunding platform, and new projects on 
kickstarter must declare a goal of how much money they hope to raise. This dataset contains all kickstarter projects launched before 2018.
Since the .csv file is over 25 MB, I can't upload it to GitHub. However, the data can be obtained at the following link: https://www.kaggle.com/datasets/kemical/kickstarter-projects

Since the goal of my project is to maximize prediction accuracy, my exploratory data analysis revolves around calculating and plotting
the success rate of projects by certain features.

The features already included in the dataset proved to be beneficial, however I also found that several additional features extracted 
from a given project's title to have a positive impact on prediction accuracy. Examples of such extracted features are indicators of 
the number of words in a project's title, whether or not the project title poses a question, and whether or not the project title 
contains an exclaimation.

Expect to see a very breif data cleaning section followed by an exploratory data analysis focused around success rates, and concluded
with the creation of a model and assesment of its quality based on total accuracy and a confusion matrix.

