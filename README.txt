README Tournament Challenge

To run this application first create a database called tournament.

Then you can run the tournament_test.py program to test out each of the SQL functions.

Functions with their intended parameters:
1) connect()
2) deleteMatches()
3) deletePlayers()
4) countPlayers()
5) registerPlayers(name) - name should be text
6) playerStandings()
7) reportMatch(winner, loser) - winner and loser are names (i.e. text)
8) swissPairings()

In tournament SQL the following tables are created:
1) Players - list of player names and a unique ID
2) Matches - list of matches taken place so far (ID of Winner - ID of Loser)


In tournament SQL the following views are created:
1) num_matches - number of matches each player has has (ID - NAME - num_matches)
2) num_wins - number of wins each player has has (ID - Name - Wins)
3) player_standings - the rankings of the tournament (ID - Name - Wins - Matches)