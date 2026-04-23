# Memory Match

Flip cards to find matching emoji pairs on a 4×4 grid. Tests your memory and speed.

## How to Play

- Click any card to flip it and reveal the emoji underneath
- Click a second card to try to find its pair
- If they match, both cards stay face-up
- If they don't match, both cards flip back over after a short delay
- Match all 8 pairs to complete the game

## Scoring

Your score is calculated when all pairs are matched:

```
score = 1000 - (extra_moves × 10) - (seconds × 2)
```

- **extra_moves** = total moves minus the minimum 8 needed to solve the board
- **seconds** = total time elapsed in seconds
- Minimum possible score is 0

**Example:** 10 moves in 20 seconds → `1000 - (2 × 10) - (20 × 2)` = **940 pts**

## Leaderboard

Click **$ push_score** after completing the board to submit your score. Higher scores rank better.
