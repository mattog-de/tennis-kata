- Write an application that shows tennis scores:
    - Example: 2-1 -> "30 - 15", 1-0 -> "15 - love"
- You have to win by 2 points: when one player has 4 points the other has 2 or less, the play with 4 points with
    - Example: 4-2 -> "Game Player 1", 1-4 -> "Game Player 2"
- When both players have the same score, the score of second player is "all"
    -  Example: 1-1 -> "15 - all"
- When both player have the same score and >=3, the score is "deuce", not "all"
    -  Example: 3-3 -> "deuce"

Points won -> Scoring
- 0 -> "love"
- 1 -> "15"
- 2 -> "30"
- 3 -> "40"
- Winning Player X -> "Game Player X"

- When reaching a 3-3 ("deuce"), scoring changes to "advantage scoring" until on player has 2 points more than the other:
    - 4-3 -> "Advantage Player 1"
    - 4-4 -> "deuce"
    - 4-5 -> "Advantage Player 2"
    - 4-6 -> "Game Player 1"

- Bonus Task: After 2 games have been played:
    - If one player won both games, the text ist not "Game Player X" but "Set Player X"
    - if each player has won one game, the "tie break" match begins:
        - Scores are called by their numbers instead of "Love, 15, 30, 40"
        - There is no deuce or advantage, just "all"
        - There is no "Game Player X", just "Set Player X"
