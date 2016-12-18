#Udacity Tournament Project
This is a simple database project completed for full-stack nanodegree program that demonstrates PostgreSQL db to manage swiss-system tournament.
##Instructions
Create tournament database:

```CREATE DATABASE tournament;``` 


Load SQL schema:

```psql tournament < tournament.sql```

Run tests:

```vagrant@vagrant-ubuntu-trusty-32:/vagrant/tournament$ python tournament_test.py
1. countPlayers() returns 0 after initial deletePlayers() execution.
2. countPlayers() returns 1 after one player is registered.
3. countPlayers() returns 2 after two players are registered.
4. countPlayers() returns zero after registered players are deleted.
5. Player records successfully deleted.
6. Newly registered players appear in the standings with no matches.
7. After a match, players have updated standings.
8. After match deletion, player standings are properly reset.
9. Matches are properly deleted.
10. After one match, players with one win are properly paired.
Success!  All tests pass! 0.179358005524```