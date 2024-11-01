# NBA Analytics Project - Predictive Modeling for Team Success

## Project Overview
Our team explores data from the NBA, leveraging analytics to predict valuable player attributes and team success factors. Using historical data and the Python `nba_api`, we analyze player impact scores and build predictive models to assist team managers in decision-making processes.

## Objectives
1. **Group Players by Physical Attributes**: Categorize players based on height, weight, and performance metrics rather than traditional positions.
2. **Predict Points Per Game (PPG)**: Develop a linear regression model to predict PPG based on player stats.
3. **Evaluate Team Success**: Identify key offensive metrics contributing to team performance.
4. **Assemble a "Superteam"**: Select players with top impact scores and PPG to hypothesize a high-performing team composition.

## Research Questions
- **PER (Player Efficiency Rating)**: Can we enhance its credibility in assessing individual performance?
- **Impact Score**: How does each player's impact correlate with team success?
- **Team Success Criteria**: What attributes define a successful team?
- **Impact Timeline**: How long does it take for a player to achieve significant impact based on position and experience?

## Data Collection
Using the `nba_api`, we gather player and team data across several endpoints:
- **Live Data**: Real-time game data.
- **Historical Stats**: Aggregated data on players and teams.
- **Tools & Endpoints**: Custom API calls for specific performance metrics.

## Data Cleaning & Processing
Significant effort was dedicated to handling missing values and creating robust feature sets, focusing on essential metrics like PPG and impact scores. Key data points include:
- **3-Point Percentage**: Dropped due to high null rates.
- **Free Throw Percentage**: Excluded to streamline predictive modeling.

## Machine Learning Model
We utilize historical data from the 2015-16 to 2020-21 seasons for training and test on the 2021-22 season:
- **Modeling Approach**: Linear regression to predict PPG.
- **Feature Engineering**: Impact scores and other efficiency metrics for better prediction.

## Visualizations
Data visualizations illustrate trends in scoring and efficiency across teams and seasons, with key insights on:
- **Field Goal Percentage**: Comparison across teams to infer offensive and defensive strengths.
- **Plus/Minus Scores**: Analyze the influence of individual players on team performance.

## Getting Started
1. Install the required dependencies:
   ```bash
   pip install nba_api pandas requests matplotlib seaborn
   ```
   ## Clone the Repository and Load Data

2. Clone the repository and load the cleaned data files to begin analysis.

## Key Findings
- **DEN (Denver Nuggets)** relies on high efficiency scores from a select few players.
- **MIA (Miami Heat)** showcases a more balanced approach, with multiple players contributing positively.

## Contributors
- Kapil M Tare
- Shreyas Kashyap
- Jovita Andrews
- Kunal R Jain

