 ## IPL Data Analysis Project
📌 Project Overview

This project presents a comprehensive analysis of the Indian Premier League (IPL) dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn. The analysis covers match-level and ball-by-ball data to uncover insights related to team performance, batting trends, bowling efficiency, toss impact, venue influence, and death-over scoring patterns.

The project follows the complete Data Science workflow:

Data Collection
Data Wrangling
Data Cleaning
Feature Engineering
Exploratory Data Analysis (EDA)
Data Visualization
Insight Generation
Business Recommendations
🎯 Objectives

The primary objectives of this project are:

Analyze IPL match and delivery-level data.
Perform data cleaning and preprocessing.
Create meaningful features for analysis.
Identify top-performing batsmen and bowlers.
Study the impact of toss decisions on match outcomes.
Analyze seasonal batting trends.
Evaluate venue-based performance.
Investigate death-over scoring patterns.
Generate actionable cricket strategy recommendations.
📂 Dataset Information

The project uses two datasets:

1. matches.csv

Contains match-level information:

Match ID
Season
Date
Teams
Venue
Toss Winner
Toss Decision
Match Winner
Player of the Match
2. deliveries.csv

Contains ball-by-ball information:

Match ID
Inning
Over
Ball
Batter
Bowler
Runs Scored
Extras
Wickets
Dismissal Type
Dataset Size
Matches: 1,095+
Deliveries: 260,000+
Seasons Covered: 2008–2024
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
📊 Project Workflow
Part A: Data Wrangling & Exploration
Data Loading and Merging
Loaded match-level and ball-by-ball datasets.
Merged datasets using Match ID.
Missing Value Handling
Identified missing values.
Handled null values in:
City
Player of Match
Dismissal Kind
Feature Engineering

Created new features:

Total Runs
Boundary Indicator
Over Phase Classification
Year
Month
Aggregation Analysis
Top 5 Batsmen
Bowler Economy Rates
Highest Win Percentage by Season
Part B: Visual Analysis & Pattern Discovery
Toss Impact Analysis
Compared batting-first and fielding-first winning percentages.
Top Run Scorers
Identified top run scorers.
Analyzed dismissal patterns.
Seasonal Trends
Average runs per match.
Long-term scoring trends using regression.
Venue Analysis
Top venues by matches hosted.
Venue-wise winning patterns.
Death Over Analysis
Performance in overs 16–20.
Team consistency and explosiveness.
📈 Key Findings
1. Virat Kohli is the Leading Run Scorer

Virat Kohli emerged as the highest run scorer in IPL history with more than 8,000 runs.

2. Chasing Teams Have an Advantage

Teams choosing to field first after winning the toss achieved a higher winning percentage than teams choosing to bat first.

3. IPL Has Become More High-Scoring

Average runs per match have increased significantly over the years, indicating increasingly aggressive batting approaches.

4. Mumbai Indians Have Been Consistently Successful

Mumbai Indians achieved the highest win percentage in multiple IPL seasons.

5. Death Overs Are Critical

Teams with strong finishers consistently outperformed others during overs 16–20.

📷 Visualizations Included
Bar Charts
Horizontal Bar Charts
Line Charts
Regression Plots
Heatmaps
Box Plots
Stacked Bar Charts
💡 Business & Cricket Insights

Based on the analysis:

Teams should prefer chasing when conditions are favorable.
Strong death-over batting significantly increases winning probability.
Venue-specific strategies can improve match outcomes.
Investment in power hitters and finishers provides a competitive advantage.
⚠️ Limitations

The dataset does not include:

Weather Conditions
Pitch Reports
Player Fitness Information
Batting Positions
Detailed Field Placements

Including these factors could enable deeper predictive analysis.

🚀 Future Scope

Future enhancements may include:

Match Outcome Prediction Models
Player Performance Prediction
Venue Recommendation Systems
Win Probability Models
Interactive Dashboards using Power BI or Tableau
👨‍💻 Author

Reenu Kaswan
B.Tech (Computer Science & Engineering)
Data Science Summer Training Project

⭐ Conclusion

This project demonstrates how Data Science techniques can transform raw cricket data into actionable insights. Through data preprocessing, feature engineering, exploratory analysis, and visualization, valuable patterns were discovered regarding team strategies, player performances, and evolving IPL trends
