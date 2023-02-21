### League of Legends Champion Analysis

This project analyzes data about the champions in the popular online game, League of Legends. The data includes various statistics for each champion, such as win rate, pick rate, role, and more. The goal of the project is to gain insights into which champions are performing well, which roles are most popular, and how different factors impact a champion's success.

# Data
The data used in this project was obtained from "https://www.kaggle.com/datasets/vivovinco/league-of-legends-stats-s13", a popular website for data scientists and machine learning engineers to access datasets, participate in competitions, and collaborate with other data enthusiasts, Kaggle hosts a variety of datasets. The dataset includes information on 162 champions on the current season of the game which is season 13.

# Tools Used
This project uses several tools and libraries, including:

- Python
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

# Methodology

The project begins with data exploration, using Pandas to analyze and clean the data. Various visualizations are created using Matplotlib to better understand the data and uncover any patterns or trends. The project then moves on to modeling, using Scikit-learn to create clustering models.

# Data exploration and data wrangling

In the data exploration and data wrangling part, we analyzed the League of Legends dataset to understand the structure of the data and its variables. We checked for missing values, outliers, and duplicates in the data, and handled them accordingly. We also performed data cleaning, where we removed unnecessary columns and rows that did not contribute to the analysis.

Furthermore, we created several visualizations to gain insights into the data, such as bar charts and scatterplots to visualize the distribution and relationship of variables. We also used statistical measures like mean, median, and standard deviation to summarize the data.

Overall, the data exploration and data wrangling steps were crucial in preparing the data for further analysis and modeling. We were able to identify important variables and patterns in the data that could be useful for making predictions and drawing conclusions.

# Clustering Model

We used a clustering model with the columns Pick %, Win %, and KDA. Clustering is a technique used in unsupervised learning to group similar data points together. The objective is to create clusters of data points that are similar to each other and different from other clusters.

We first preprocessed the data by dropping missing values, filtering out champions with low pick rates, and normalizing the data. Then, we used the KMeans algorithm to create clusters of champions based on their Pick %, Win %, and KDA values.

The clustering allowed us to identify groups of champions that share similar characteristics in terms of their performance in the game. This can help us gain insights into the game's meta and inform strategic decisions for players and teams.

# Results
The project found several interesting insights into the League of Legends champion data, including:

- The most popular role is ADC, followed closely by Mid and Top.
- Tanks have the highest win rate, while Assassins have the lowest.
- There is a positive correlation between a champion's pick rate and win rate.
- The champions can be grouped into several distinct clusters based on their attributes.

# Conclusion
Overall, this project provides valuable insights into the League of Legends champion data, which could be useful for players looking to improve their gameplay or for game developers looking to balance the game. The project also demonstrates several key skills for data science, including data exploration, visualization, and modeling.
