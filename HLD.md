 **FIFA_20: Data Analysis Report**

**Business Case**

This comprehensive data analysis report is based on FIFA player data with the goal of gaining valuable insights into football players' characteristics and attributes. The project consists of three main tasks:
Task 1: Data Analysis
- In this task, we explore the FIFA player dataset, examining attributes such as age, height, overall performance, potential, preferred foot, and various positional skills.
  We aim to understand the distribution of player characteristics and identify patterns in the data.
Task 2: Player Clustering
- Task 2 involves clustering football players based on their attributes. By applying machine learning techniques, we group players with similar skill sets into distinct clusters.
  This provides a deeper understanding of the diverse talents present in the football world.
Task 3: Answering Key Questions
- In this task, we address specific questions:
  1. Ranking Countries: We prepare a ranked list of the top 10 countries with the most football players, shedding light on which nations produce the most footballers at this level.
  2. Performance vs. Age: We analyzed the relationship between a player's age and their overall performance. Our goal is to identify the age at which a player typically stops improving.
  3. Highest-Paid Offensive Players: We investigate which type of offensive players, including strikers, right-wingers, and left-wingers, tend to receive the highest average pay based on their team position.

This is a High Level Design of this project, in the ipynb file everything is present like after every plot I have written significant Insights about the players and their attributes.
it is just an in-depth overview and description of the project.
<br>
<br>
Insights from Data Analysis:
<br>
Age: The majority of players are between 20 and 25 years old, with a decline in numbers after 35.
Height: Most players' heights fall within the range of 170 to 190 centimeters.
Weight: Player weights are primarily distributed between 65 to 85 kilograms, with the highest concentration at 70 kilograms.
Overall Performance: The overall performance of most players is between 60 and 75 out of 99, with some exceptional players scoring above 90.
Potential: Player potential is distributed between 65 and 80, with a few players having potential ratings above 90.

Clustering:
- We performed clustering to group players based on their skill sets, revealing distinctive clusters representing various skill levels.
- First I Clustered the players on the basis of their attributes and performance. After visualizing the clusters I realized that there were plenty of players like average performers, weak performers, strong performers, and top players. The dataset contains more than 1800 records which means I need to proceed with those many players, Then I did this.
-	To refine our focus and extract insights about players with exceptional abilities, a filtering process was implemented. Specifically,
-	the dataset was filtered to include only those players whose overall performance score falls below the 75th percentile.
-	This strategic filtering allowed us to concentrate solely on players who demonstrate a high degree of skill and proficiency

  
Insights from Pair Plots:
- Players with overall performance above 80 tend to command higher wages and possess greater market value.
- Players aged between 25 and 35 typically have the highest wages and values.

Challenges Faced:

1. Data Volume: Managing a dataset with numerous attributes and a large number of players presented challenges in terms of preprocessing and computational resources.
2. Understanding Features: With 105 features, comprehending each attribute's significance for analysis was daunting.
3. Feature Selection: Selecting the most relevant attributes from 60 numerical features required careful consideration.
4. Data Loss During PCA: Applying Principal Component Analysis (PCA) for feature reduction resulted in the loss of 10% to 15% of the data.
5. Determining Optimal Clusters: Choosing the optimal number of clusters, in our case, four, can be an iterative process.
6. Data Visualization: Understanding and interpreting complex scatterplots with over 18,000 data points posed a challenge.
7. Task Complexity: Task 3 involved addressing tricky questions, especially regarding offensive player salaries, where three types of strikers were considered.
   
**Conclusion:**

In this FIFA player analysis, we explored a wide range of player attributes and characteristics. Key findings revealed the typical age range of football players,
the relationship between performance and age, and insights into offensive player salaries. Challenges included managing a vast dataset and interpreting complex visualizations.
This project underscores the power of data analysis in understanding the world of sports and making data-driven decisions in the football industry.
