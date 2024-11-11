MCU Analysis 📊
Project Overview
This project is a comprehensive analysis of the Marvel Cinematic Universe (MCU) movies, focusing on financial performance, audience reception, and critic ratings. By analyzing key financial and critical metrics, this project aims to uncover patterns in MCU movie earnings, budget allocations, and feedback from both audiences and critics.

Features

Data Collection: Data was gathered from publicly available sources and includes key metrics such as movie budgets, gross income, audience, and critic scores.
Exploratory Data Analysis (EDA): Visualizations of movie revenue trends, budget allocation, and comparison of audience vs. critic ratings.
Hypothesis Testing: Statistical testing to explore relationships between variables (e.g., budget and worldwide gross).
Visualizations:
Yearly movie releases and revenue trends
Top 10 highest-grossing MCU movies
Audience vs. critics score distribution
Budget vs. gross revenue comparison
Success metrics by movie category
Dataset
The dataset includes the following columns:

Movie: Title of the MCU movie.
Category: Sub-genre or character group, e.g., Avengers, Spider-Man.
Year: Release year of the movie.
Worldwide Gross ($M): Total worldwide gross income (in millions).
% Budget Recovered: Percentage of the budget recovered by gross earnings.
Critics % Score: Critic score on a percentage scale.
Audience % Score: Audience rating score.
Audience vs Critics % Deviance: Difference in opinion between audience and critics.
Budget ($M): Estimated production budget (in millions).
Domestic Gross ($M): Domestic gross income.
International Gross ($M): International gross income.
Opening Weekend ($M): Opening weekend revenue.
Second Weekend ($M): Revenue during the second weekend.
Installation
Ensure you have Python and the required packages installed. Use the following command to install dependencies:

bash
Copy code
pip install -r requirements.txt
Usage

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/mcu-analysis.git
cd mcu-analysis
Download the dataset:

Use gdown or manually place the dataset in the project folder as directed.

Run the Analysis

Open the Jupyter Notebook or Python script to view the analysis and visualizations.
Explore the included visualizations that provide insights into MCU movie performance.
Analysis Insights

Yearly Release Patterns: Analyze trends in MCU movie releases each year and their impact on total revenue.
Box Office Performance: Explore overall trends in box office revenue, highlighting the top 10 highest-grossing movies.
Audience vs. Critics Comparison: Examine alignment and differences between audience and critic ratings.
Budget Efficiency: Discover the relationship between a movie’s budget and its gross revenue.
Visualizations Included

Total Movies Released per Year: Bar chart showing the yearly release count of MCU movies.
Top 10 Grossing Movies: Bar chart displaying the highest-grossing MCU movies.
Budget vs. Worldwide Gross: Scatter plot illustrating the relationship between budget and revenue.
Opening Weekend Performance: Analysis of the impact of opening weekend revenue on the overall gross.
Success Metrics by Category: Comparison of average success metrics (e.g., gross income, critic/audience scores) across different MCU categories.
Hypotheses Tested

Budget and Revenue Correlation: Significant correlation exists between a movie’s budget and worldwide gross income.
Impact of Release Timing: Tests if release timing (e.g., near holidays) affects a movie's success.
Audience vs. Critics Deviation: Tests if Deadpool movies show a significant difference in audience vs. critic scores compared to other MCU movies.
Contributing
Contributions are welcome! Please fork the repository and submit pull requests for new features, bug fixes, or enhancements.
