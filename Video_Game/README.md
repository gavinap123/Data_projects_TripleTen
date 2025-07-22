Video Game Sales Analysis Project
Overview
This comprehensive data analysis project explores video game sales data from multiple perspectives, including platform lifecycle analysis, regional sales trends, and genre profitability. The project consists of five sequential parts that clean, analyze, and visualize game sales data from 1980-2016.

Project Structure
Part 1: Data Exploration and Cleaning
Imported and examined the games dataset
Handled missing values in key columns (name, genre, ratings)
Converted data types for proper analysis
Calculated total sales across regions
Key Findings:

Identified missing values in critic and user scores
Established baseline metrics for data cleaning
Part 2: Platform Lifecycle Analysis
Calculated average platform lifecycle (~9 years)
Identified top-performing platforms (PS2 sales leader)
Visualized sales trends by platform over time
Analyzed growing/shrinking platforms
Key Visualization:
Stacked bar chart of platform sales by year

Part 3: Regional Sales Analysis
Compared sales performance across NA, EU, and JP markets
Identified platform preferences by region:
NA: Action games dominate
EU: PlayStation loyalty
JP: 3DS leads in role-playing games
Examined rating preferences by region
Part 4: Genre Profitability Study
Action genre leads in sales but faces market saturation
Role-playing games most profitable in Japan
Sports games perform well in NA and EU markets
Visualized genre distributions and platform-specific sales
Part 5: Hypothesis Testing
Compared user ratings between Xbox One and PC platforms (no significant difference)
Found significant difference in user ratings between Action and Sports genres
Statistical confirmation of regional preferences We can reject the hypotheses that:
Action and Sports games receive the same user ratings (p<0.05)
Xbox One and PC platforms receive the same user ratings (p>0.05)
Key Conclusions
Platform Insights:
Average platform lifespan: 9 years
PS2 had highest historical sales but is now inactive
Action genre dominates but shows market saturation
Regional Preferences:
North America: Favor action/shooter games (M-rated)
Europe: Strong PlayStation loyalty
Japan: Prefers role-playing/action games on 3DS
Market Opportunities:
For action/sports games: Focus on NA/EU via PS4/Xbox One
For Japanese market: Develop RPGs for 3DS
Not Rated games represent untapped potential
Technologies Used
Python (Pandas, NumPy)
Data Visualization (Matplotlib, Seaborn)
Statistical Analysis (SciPy)
Jupyter Notebooks
How to Run the Analysis
Install requirements:
bash

Run
Copy code
pip install pandas matplotlib seaborn scipy jupyter
Run Jupyter Notebook:
bash

Run
Copy code
jupyter notebook