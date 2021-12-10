# C_Sharp-Tournament-Tracker
A Tournament Tracker written in C# that sets up a schedule for teams to play each other in a single-elimination style matcchups.

## Useful for:
- Office ping pongtournaments
- Rec league playoffs
- 3v3 basketball leagues
- And many more...

# Technology Utilized
## The C# "technology" I will use in this application includes:
- Multi-form WinForms application
- In-depth Class Library
- SQL Database
- Text File Storage
- Dapper
- Linq
- Interfaces
- Emailing from C#
- Custom Events
- Advanced Debugging

## This is what a typical bracket looks like:
<img width="677" alt="Screen Shot 2021-12-10 at 3 04 31 PM" src="https://user-images.githubusercontent.com/52815609/145634768-4704ea1c-bff8-444d-8915-9d9a7712ee4e.png">

## Scenario
My friends come to me and ask me to create a tournament tracker. They are always playing games and want to determine who is the best. The idea is that I create a bracket tournament system where the computer will tell them who to play in a single-elimination style bracket. In the end, the winner should be identified. Their model is the NCAA Basketball tournament bracket from March Madness.

## Features
1. Tracks games played and their outcome (who won).
2. Multiple competitors play in the tournament.
3. Creates a tournament plan (who plays in what order).
4. Schedules games.
5. A single loss eliminates a player.
6. The last player standing is the winner.

# Predevelopment Q&A:
### How many players will the tournament handle? Is it variable?
The application should be able to handle a variable number of players in a tournament.
### If a tournament has less than the full complement of players, how does the system handle it?
A tournament with less than the perfect number (a multiple of 2, so 4, 8, 16, 32, etc.) should add in "byes". Basically, certain people selected at random get to skip the first round and act as if they won.
### Should the ordering of who plays each other be random or ordered by input order?
The ordering of the tournament should be random.
### Should the system schedule the Games or are they just played whenever?
The games should be played in whatever order and whenever the players want to play them.
### If the games are played whenever, can a game from the second round be played before the first round is complete?
No. Each round should be fully completed before the next round is displayed.
### Does the system need to store a score of some kind or just who won?
The system should store a score. Just a number for each player. That way the tracker can be flexible enough to handle a checkers tournament (the winner would have a 1 and the loser a 0) or a basketball tournament.
### What type of front-end should this system have (form, webpage, app, etc.)?
The system should be a desktop system for now, but down the road I may want to turn it into an app or a website.
### Where will the data be stored?
The data should be stored in a Microsoft SQL database by default but have an option to store to a text file instead.
### Will this system handle entry fees, prizes or other payouts?
Yes. The tournament should have the option of charging an entry fee. Prizes should also be an option, where the tournament administrator chooses how much money to award a variable number of places. The total cash amount should not exceed the income from the tournament. A percentage-based system would also be nice to specify.
### What type of reporting is needed?
A simple report specifying the outcome of the games per round as well as a report that specifies who won and how much they won. These can be just displayed on a fomr or they can be emailed to tournament competitors and the administrator.
### Who can fill in the results of a game?
Anyone using the application should be able to fill in the game scores.
### Are there varying levels of access?
No. They only method of varied access is if the competitors are not allowed into the application and instead, they do everything via email.
### Should this system contact users about upcoming games?
Yes, the system should email users that they are due to play in a round as well as who they are scheduled to play.
### Is each player on their own or can teams use this tournament tracker?
The tournament tracker should be able to handle the addition of other memebers. All members should be treated as equals in that they all get tournament emails. Teams should also be able to name their team.
