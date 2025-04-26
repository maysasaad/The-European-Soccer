# The European Soccer
<img src='image/euroclublogos.jpg'>

## Project Overview
This project uses SQL queries to extract, clean, and analyze data from the European Soccer Database, aiming to deliver actionable insights for a sports channel's content strategy.

### Business Problem
A leading sports channel seeks to enhance its soccer coverage by offering engaging, data-driven content and in-depth analysis. Leveraging historical data from the European Soccer Database will help uncover patterns, performance metrics, and insights that inform both editorial decisions and audience engagement strategies.

### The Data Source and Data Exploration
The dataset used in this project is sourced from Kaggle's European Soccer Database, consisting of six key tables: :

Country - Country names.

Matches – Results, team stats

Teams – Information on clubs

Players – Player statistics, attributes, and career history

Leagues –  league's names

Team_Attributes – Performance metrics of teams

Player_Attributes – Player skills and ratings

### Data Analysis
Data only speaks when asked the right questions. To turn raw data into actionable insights, I focused on addressing the following business-driven questions:

How many teams are there in each country?

How many matches were played in each league?

Which teams belong to each league?

Who are the top ten teams by performance over multiple seasons?

Who are the top ten players in Europe over the period?

Which season can be considered a "trend season"?

What are the total home goals scored, grouped by country and team?

How many goals did each team score, grouped by season?

How do leagues differ in terms of average goals per match?

How many total goals were scored by home and away teams, grouped by country and season?

What were the win percentages and aggregated win/loss records, along with goals scored and conceded per team, per season?

Which teams had the most wins across all seasons and leagues?

Which team attributes have the biggest impact on total goals scored?

How did the aggregated goals for the top five scoring teams in Spain's La Liga evolve over time?

Did a player's BMI influence their performance score (overall rating)?



### Results

The analysis addressed each of the questions above, offering valuable insights:

1.League Popularity
France's Ligue 1 features the highest number of teams, followed by England’s La Liga (likely meant to be Premier League — double-check this!).
<img src='image/result1.png'>

2.League Activity
Spain’s La Liga recorded the highest number of matches, attributed to its large number of teams and extended seasons.
<img src='image/result2.png'>

3.Top Ten Teams by Performance
Real Madrid, Barcelona, and Bayern Munich consistently rank among the highest-performing teams across multiple seasons.
<img src='image/result3.png'>

4.Top 10 Players in Europe
The standout players include Cristiano Ronaldo, Franck Ribéry, Lionel Messi, Philipp Lahm, Wayne Rooney, Xavi Hernández, Zlatan Ibrahimović, Arjen Robben, Cesc Fàbregas, and Petr Čech.
<img src='image/result5.png'>

5.Trend Season
The 2015-2016 season saw the highest number of goals (9,162), marking it as a standout "trend season."
<img src='image/result4.png'>

6.Goals by Team and Season
Real Madrid CF scored the highest number of home goals in the 2015-2016 season.
<img src='image/result6.png'>

7.Goals Per League: 2011/2012 Season
<img src='image/avg.png'>

8.Real Madrid CF Performance Over Seasons
<img src='image/R.M%20goals%20per%20season.png'>

9.Real Madrid's Home vs. Away Wins
<img src='image/Real%20Madid%20wins%20(home%20or%20away).png'>

10.Real Madrid Home & Away Goals per Season
<img src='image/Real%20Madrid%20CF%20-%20Home%20%26%20Away%20Goals%20per%20Season.png'>

11.Average Goals per Season for Real Madrid
<img src='image/AVG%20goals%20Real%20Madrid%20CF%20scored%20in%20each%20season.png'>

12.Top 3 Teams with Highest Average Home Goals (Spain 2011/2012)
<img src='image/Top%203%20Teams.png'>

13.Win Percentage and Match Outcomes
Juventus and Real Madrid stand out with high win percentages over multiple seasons.
<img src='image/win%20persentage.png'>

14.Average Goals per Match by Country (2008/2009)
<img src='image/Avg%20Goals%20%2020082009.png'>

15.Monthly Goal Trends
Goal-scoring totals fluctuate significantly by month.
<img src='image/monthly.png'>

16.Country-Wise Average Goals
Country-specific goal averages deviate from the overall mean.
<img src ="image/country's%20avarage%20goals.png">

17.Top Ten Teams by Wins
Real Madrid, Barcelona, and Bayern Munich lead in total wins across seasons.
<img src='image/result7.png'>

18.Key Team Attributes Affecting Performance
Offensive strategies, player quality, and defensive tactics are highly correlated with goal-scoring success.
<img src='image/result8.png'>

19.Goal Trends for Top La Liga Teams
Top clubs like Real Madrid and Barcelona show consistent goal-scoring with minor seasonal fluctuations.
<img src='image/result11.png'>

20.Player BMI and Performance
A slight positive correlation suggests that players with an optimal BMI often achieve higher overall ratings.
<img src='image/result12.png'>


    
# Conclusion 

In conclusion, this data analysis project using the European Soccer Database provided useful insights to help improve a sports channel’s soccer coverage. The analysis explored team performance, match activity, player achievements, and trends, helping to create interesting stories and better fan engagement.

The results showed that teams like Real Madrid, Barcelona, and Bayern Munich were consistently strong, while players like Cristiano Ronaldo, Lionel Messi, and Franck Ribéry stood out for their performances. The 2015–2016 season was especially important because of the high number of goals scored.

The project also uncovered patterns in tactics, team strategies, and the link between player fitness (BMI) and performance. These insights can help the sports channel create more interesting and informative content for its audience.

# Recommendations

1.Tell Stories with Data

Use the insights to create interesting stories about top-performing players, famous team rivalries, and goal trends for match previews and reviews.

2.Predict Match Results

Use historical data to predict future games, spot rising star players, and build excitement before matches.

3.Engage Fans

Turn the insights into fun polls, quizzes, and graphics for social media and live shows to get fans more involved.

4.Player Fitness Content

Develop content that connects player fitness and BMI data with performance, offering unique insights for health-conscious fans and sports analysts alike.

5.Season Highlights
Make special episodes to review standout seasons like 2015–2016, focusing on goal records and team achievements.

6.Support for Analysts and Commentators

Give data and visuals to presenters and analysts to help them share deeper insights during matches.

7.Tactical Breakdowns
Use the analysis on team tactics and goal patterns to create simple videos or articles that explain how teams win matches.


###  Thank you!

Email: mays802004@gmail.com

GitHub: @maysasaad   

### Repository Structure

├── data ├── images ├── README.md ├── Presentation.pdf └── Jupyter notebook.ipynb