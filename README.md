The data used here was scraped from the SOFIFA website. The data set included data for over 18,000 players.
A Apte and Danielle Romanoff were the data scientists working on this project.
Danielle Romanoff cleaned data after the raw data was split into three separate dataframes.
Danielle created smaller dataframes including the Club and Club Logo to connect the two.
Danielle changed all abbreviations for position to a clear indication of what the position was.
Danielle created a couple groupby dataframes to connect player names to different skills. This was not the best approach so a
different direction was taken.
Danielle created a new dataframe connection the nationalities to the continents they are part of. In addition, she connected
the player name, overall score, club, and jersey number to the nationality and continent.
Danielle created a heatmap to see what correlation might exist between skills.
She also created a boxplot using the top 10 nationalities that had the most players.
Danielle created a second boxplot showing eight of the clubs and the range of wages.
The last visualization Danielle created was a violin plot again showing the clubs and wages but with the violin plot it was 
easier to discertain the spread of the data.
Finally, Danielle provided ratings for players based on each of 26 positions on the field. With Danielle's knowledge of the 
sport of soccer, she developed her own formulas to determine proper ratings. There were formulas found on the web but they
were incredibly simplified. There were far more skills that needed to be weighed in determining ratings for each position. 
Danielle developed formulas for each position using a weighted average or four weighted averages. The final step was to code those 
formulas to provide dataframes for each position with the appropriate rankings for each score. This code can be found in the
FIFA19_PositionStats.ipynb file. She created both csv and json files for each position. Danielle's other notebook title is FIFA19.ipynb.
She created two other csv files that included Play Information... playerinfo.csv and name.csv.
Danielle plans on combining several dataframes to use for interactive visualizations done on Plotly.
