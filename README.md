

### Goal Kicker Simulator: Rules & Guidelines

#### Objective
Test your luck and explore probability by guessing where a third card falls relative to two initial cards, with a betting system to calculate expected payouts.

#### Rules
1. **Card Deck**: Uses a standard 52-card deck (Ace = 1, 2-10, Jack = 11, Queen = 12, King = 13), reshuffled before each trial.
2. **Gameplay**:
   - Two cards are drawn to set a range (e.g., 3 and 8).
   - A third card is drawn and compared to the range:
     - **Within**: Third card is between the first two (e.g., 5 between 3 and 8).
     - **Outside**: Third card is below the lower or above the higher (e.g., 2 or 9).
     - **Same**: Third card matches one of the first two (e.g., 3).
3. **Betting**:
   - Set a Bet amount and payouts for Within, Outside, Same (e.g., Bet: 1, Within: 2, Outside: 0, Same: -5).
   - Outcome = Payout - Bet per trial (e.g., Within: 2 - 1 = 1).

#### Modes
- **Interactive Mode**: See two cards, guess the third card’s position (Within, Outside, Same), then check the result. No stats or payouts tracked.
- **Auto Mode**: Runs one trial, shows three cards (0.7s), calculates outcome, updates stats and table.
- **Run Trials**: Runs multiple trials (set number, e.g., 17), shows each trial (0.7s), tracks stats and payouts.

#### Guidelines
1. **Setup**:
   - Enter Bet (must be > 0) and payouts for Within, Outside, Same (any integers) in the input table.
   - All inputs must be whole numbers; invalid entries block trial results.
2. **Running Trials**:
   - Use Auto Mode for a single test or Run Trials for a batch.
   - Watch the table for each trial’s cards, result, outcome, and running payout (10 rows per page, use Forward/Backward).
3. **Stats**:
   - View Total Trials, Within, Outside, Same counts, and Final Payout (sum of outcomes) at the top.
   - Reset Stats clears everything to start a new round.
4. **Tips**:
   - Third card appears below the first two for clarity.
   - Experiment with payouts to see how they affect the Final Payout!

---

