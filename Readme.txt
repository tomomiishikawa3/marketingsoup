Modeling this one:
https://github.com/marcotav/supervised-machine-learning/blob/master/tennis/README.md

1. Problem Statement and Hypothesis
The goal of the project is to predict the probability that the higher-ranked player will win a tennis match. I will call that a win(as opposed to an upset).

2. Dataset
Results for the men's ATP tour date back to January 2000 from the dateset http://www.tennis-data.co.uk/data.php (obtained from Kaggle). The features for each match that were used in the project were:
Date: date of the match
Series: name of ATP tennis series (we kept the four main current categories namely Grand Slams, Masters 1000, ATP250, ATP500)
Surface: type of surface (clay, hard or grass)
Round: round of match (from first round to the final)
Best of: maximum number of sets playable in match (Best of 3 or Best of 5)
WRank: ATP Entry ranking of the match winner as of the start of the tournament
LRank: ATP Entry ranking of the match loser as of the start of the tournament
The output variable is binary. The better player has higher rank by definition. The win variable is 1 if the higher-ranked player wins and 0 otherwise.

3. Importing basic modules
import numpy as np
import statsmodels.api as sm
import matplotlib.pyplot as plt
from sklearn import metrics
import seaborn as sns
sns.set_style("darkgrid")
import pylab as pl
%matplotlib inline

4. Pre-Processing of dataset

5. Exploratory Analysis 

6. Dummy variables

7. Facter Analysis

8. Cluster Analysis

9. Conclusion