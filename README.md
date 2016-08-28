HZ2421
DSP2124
In part III, we developed a log in and sign up interface for users and designed a page for them to look up player bio, team information and past games. For play bio, users are prompted to enter the name of the player in a text field. If the name exists in our database, the result will show up below. Otherwise an error will flash out. Similarly for team stats, users will be required to enter a team name and a season between 2011 and 2016 to access the data. For past games search, a game date is required in addition to the name of the home team. We have also implemented the betting system in which the page displays a random match played in the past. Users can bet on either team based on their preferences and get instant result of whether they win or not. Our table game_bet will record the bet made by the user and his name in the back-end. We slightly modified our betting game because we figured it would be more fun if a user could bet against the house on past games, instead of betting against other users on future games. We mentioned in part I that it would also be interesting to implement a function which automatically updates bets and user data (wins) as new data becomes available. However, due to the complexity of the process and time constraint, we are only going to display the result of the current bet made by users. 
Three interesting page:
1.	The player info request page. Our page can display multiple players at the same time based on user input(either the player’s last name or his full name”. 
2.	The Game look-up page displays the home games a team has played in the past 5 seasons, along with the scores. (Due to the enormous size of data, we randomly stored 40 past games in our database)
3.	Betting page. The current logged in user makes a bet on a random game in the past and our application stores the bet in our database.  Results are shown
PSQL Account: dsp2124
Server Adress: http://40.121.86.201:8111/

