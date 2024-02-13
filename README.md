# Comprehensive Analytics: Unveiling the Pinnacle NBA Team across Eras
### Contributors: Devan, Erik, Michael and Nebyu

## Project summary:
We decided that we wanted to make a presentation about which teams were the best teams of all time through a statistical analysis. After deciding that we had to ask the question: How do we decide what makes a great team ‘great’? We then went out and found a dataset that contained the teams and their statistics. We eventually settled on using only 27 of those statistics for our actual analysis to decide what team was ‘great’. Afterwards we made a top 5 for the relevant statistics and made some visualizations for said data.

## Project analysis:
One thing that we found from the data is that there is very little variability between teams. Basically the top teams are within a percentage of each other. Another thing that we found was that the top teams were disproportionately closer to the present than the past. This was especially true for offensive statistics. The reason why this was the case is because there have been a ton of rule changes since the 80s and 90s. Many of the popular defensive tactics that you saw performed by players like Bill Laimbeer would get you ejected from a NBA game in the 21st century. These rule changes have favored offenses much more than defenses making it easier to score.

## Troubleshooting:
When new columns were statistically calculated, our data was not being organized in descending order. The reason this was happening was because the data that was being read in as a string rather than a float. After the data was converted to a float we were finally able to get the data looking proper. After that, getting our data into something visually appealing and readable was the last thing we achieved.

## Limitations: 
### Comparison Across Seasons: 
* Extend the analysis to compare offensive and defensive performances across multiple seasons to identify trends and patterns in team performance over time.

### Evaluate Playoff Success: 
* Assess how offensive and defensive performances correlate with playoff success to determine key factors contributing to a team's postseason performance.

### Player Contribution Analysis: 
* Explore individual player contributions to offensive and defensive performance to identify key players driving team success in different aspects of the game.

### Explore Additional Statistics: 
* Such as forced turnovers and other defensive metrics to provide a more comprehensive understanding of team performance and areas for improvement.

### Account for Rule Changes: 
* Conduct research and analysis to understand any rule changes that have occurred during the seasons under consideration and evaluate their potential impact on team performance. Incorporating this information can provide a more accurate assessment of team performance and facilitate better-informed decision-making in basketball analytics and management.

## Credits/Sources/Thanks:
https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats
https://www.basketball-reference.com
https://stackoverflow.com/questions/7908636/how-to-add-hovering-annotations-to-a-plot
https://www.nba.com/stats
https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.annotate.html
