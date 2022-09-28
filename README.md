# nba_project
**Goal: Create a program using ML/AI that builds the optimal nba starting lineup. Allow for users to input X amount of players and have the program fill in the rest.**

High Level Methodology:
**Source Data**
  NBA API
Create some sort of database
  Can be a massive csv or something more complex like a SQL database
Identify data/features that historically contributes the most to a winning team
  Feature ranking for a simple model that predicts records of teams
Create an optimal nba lineup
  No restrictions
Create the best nba lineup including restrictions
  Salary cap
Take an input of X players and fill the rest of the lineup to create the best lineup possible
  With restrictions
Create mini front end demo

Deeper Dive into Each Step

Source Data
Use nba_api for python
  https://github.com/swar/nba_api
**Data Setup**
Players season stats
    Table for active nba players
  Team level season stats
  Create UML diagram to show
Clean all of the data coming from the api before sending it to database

