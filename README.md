
#FIFA Raw Dataset from Kaggle
##FIFA 19 Data including players, biographies, positions, and skills.
Dataset
- The data used here was scraped from the SOFIFA website. 
- The data set included data for over 18,000 players.
--

Data Scientists
###- A Apte
###- Danielle Romanoff

####Contributions from A Apte (DS1):

Data Cleaning of the raw Dataset (FIFA_19_Cleanup_to_JSON.ipynb)

Exporting the dataset into usable JSON files for an MVP (FIFA_19_Cleanup_to_JSON.ipynb)

Using the cleaned data set, calculated the Base Statistics for Player Badges (FIFA_Stats.ipynb)

Used the player information to make a Similarity Analysis (five closest players) (FIFA_Similarity_Analysis.ipynb)


####Danielle's Contributions
-Danielle Romanoff assisted in cleaning data after the raw data was split into three separate dataframes.

-Danielle created smaller dataframes including the Club with Club Logo to isolate the two.

-Danielle changed all abbreviations for positions to a clear indication of what the position was.

-Danielle created a couple groupby dataframes to connect player names to different skills. This was not the best approach so a different direction was taken.

-Danielle created a new dataframe connection the nationalities to the continents they are part of. In addition, she connected the
player name, overall score, club, and jersey number to thenationality and continent.

-Danielle created a heatmap to see what correlation might exist between skills.

-She also created a boxplot using the top 10 nationalities that had the most players.

-Danielle created a second boxplot and an additional violin plot showing eight of the clubs and the range of wages. The violin plot showed the spread of the data more clearly.

-Danielle provided ratings for players based on each of 26 positions on the field. With Danielle's expertise of the sport of soccer, she developed her own formulas to determine proper ratings.

-There were formulas found on the web but they were incredibly simplified. There were far more skills that needed to be weighed in determining ratings for each position.

-Danielle developed formulas for each position using a weighted average or four weighted averages.

-The final step was to code those formulas to provide dataframes for each position with the appropriate rankings for each score. This code can be found in the FIFA19_PositionStats.ipynb file. She created both csv and json files for each position. Danielle's other notebook is titled FIFA19.ipynb. She created two other csv files that included Play Information... playerinfo.csv and name.csv. Danielle plans on combining several dataframes to use for interactive visualizations done on Plotly.
