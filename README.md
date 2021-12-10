# C_Sharp-Tournament-Tracker
A Tournament Tracker written in C# that sets up a schedule for teams to play each other in a single-elimination style matcchups.

## Scenario
My friends come to me and ask me to create a tournament tracker. They are always playing games and want to determine who is the best. The idea is that I create a bracket tournament system where the computer will tell them who to play in a single-elimination style bracket. In the end, the winner should be identified. Their model is the NCAA Basketball tournament bracket from March Madness.

## Features
1. Tracks games played and their outcome (who won).
2. Multiple competitors play in the tournament.
3. Creates a tournament plan (who plays in what order).
4. Schedules games.
5. A single loss eliminates a player.
6. The last player standing is the winner.

## Questions
### How many players will the tournament handle? Is it variable?
The application should be able to handle a variable number of players in a tournament.
### If a tournament has less than the full complement of players, how do we handle it?
A tournament with less than the perfect number (a multiple of 2, so 4, 8, 16, 32, etc.) should add in "byes". Basically, certain people selected at random get to skip the first round and act as if they won.

## Useful for:
- Office ping pongtournaments
- Rec league playoffs
- 3v3 basketball leagues
- And many more...

### This is what a typical bracket looks like:
<img width="677" alt="Screen Shot 2021-12-10 at 3 04 31 PM" src="https://user-images.githubusercontent.com/52815609/145634768-4704ea1c-bff8-444d-8915-9d9a7712ee4e.png">

# Technology Utilized
### The C# "technology" I will use in this application includes:
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
