# Personal-Dataset

I chose to look at ice hockey data specifically for the NHL. NHL hockey games are my 	favorite thing to watch on TV and I love the game. Something very relevant to the 	outcome of a game is the number of penalties taken by a team. Not only is a player put in 	the penalty box and you are a man down, but penalties can also change the emotions of 	the team and cause more aggression between players and the teams overall if they feel it 	was a bad call or biased one way. 

With this motivation in mind I chose to answer the following question: Which team in the NHL was the most highly penalized in the 2018-2019 playoffs?

Link to the original data source: https://www.icydata.hockey/player_stats/28/penalties 
I decided on this data source because it had the exact information I was looking for to 	answer my guiding question. Also, I looked into the sources the pulled information from 	to create the dataset I chose and it seemed reasonable and reliable. I did an overview of the data multiple times and there was nothing immediately alarming 	or concerning about any data entry. Therefore, I did not cut any rows of data. However, 	there was a column for the “minutes” spent in the penalty box for each penalty take, and I 	did not use this column in my analysis, therefore I cut it altogether.	
 
 I chose to visualize the average penalties per game for each team in the 2019 playoffs. I 	chose to do the average per game because it would disregard the fact of how far each 	team went in the playoffs. It would only take into account the average penalties. To do this, I made a little table in excel and made a row for each team that played in the 	playoffs. I made a column for the total number of penalties taken, and a column for the 	total number of games that team played. To find the number of penalties taken by each 	team, I used the count if function to search for how many rows were for each team. I then 	had to manually go through and count how many games each team played in. Finally, I 	took the total number of penalties divided by the total number of games played in order to 	find the average number of penalties per game.

![Average Number of Penalties Per Game](https://raw.githubusercontent.com/morganpalmerton/Personal-Dataset/master/HockeyFigure.png)

This bar graph demonstrates the average number of penalties per game for each team that played in the 2019 NHL playoffs. 
