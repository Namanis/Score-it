# Score-it
Sport Games prediction game

## Description

Sports Match score prediction web app where friends predict the winner and point margin of upcoming EuroLeague games, and earn points for accurate calls.

## Functionality

- Register and log in with role-based access: a USER plays and creates leagues, and an ADMIN manages teams, games and results.
- Create a private league, invite friends and let the league owner remove members.
- Browse upcoming games.
- Predict each game by picking the winner and tries to guess final score. Predictions can be edited or deleted until game start, then lock automatically.
- Validate input, for example rejecting negative score, or predicting after game starts.
- Keep friends predictions hidden until game starts, then reveal them to the whole league.
- Score predictions automatically when the admin enters the final score. (Perhaps its possible to automate with API)
- Show a league table with total points, correct winners, exact margins and positions.
- Show a round summary with each player’s picks vs. the final scores, points earned and accuracy percentage.
- Load the schedule and results from an external basketball API (extra mile).
