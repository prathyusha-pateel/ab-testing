# Game Retention A/B Testing (Cookie Cats Dataset)

Cookie Cats is a popular mobile puzzle game where players solve puzzles to help a cat collect cookies. The game includes "gates" that require players to wait or make in-app purchases to progress.

**The Question:** Does moving the first gate from level 30 to level 40 increase player retention and engagement?

**Test Groups:**

* Control Group: Gate at level 30
* Treatment Group: Gate at level 40

**Key Metrics:**

* Day 1 Retention: Whether players return 1 day after installation
* Day 7 Retention: Whether players return 7 days after installation
* Game Rounds: Number of game rounds played within 14 days

### Chi-Square Test

The Chi-Square test was used for retention rate comparisons because:

*   It's appropriate for comparing proportions (retention rates) between two groups
*   It doesn't assume normal distribution
*  It's suitable for categorical outcomes (retained vs. not retained)


### Mann-Whitney U Test

The Mann-Whitney U test was used for game rounds comparison because:

* It's a non-parametric test that doesn't assume normal distribution
* The distribution of game rounds is highly skewed
* It compares the distribution of values rather than just means


### Key Findings

1. **Day 1 Retention**: The difference in Day 1 retention between Gate 30 (44.8%) and Gate 40 (44.2%) is 1.3%, which is not statistically significant (p = 0.0755). However, it's very close to the significance threshold and shows a positive trend favoring Gate 30.

2. **Day 7 Retention**: The difference in Day 7 retention between Gate 30 (19.0%) and Gate 40 (18.2%) is 4.5%, which is statistically significant (p = 0.0016). This provides strong evidence that Gate 30 placement leads to better long-term retention.

3. **Game Rounds**: Players with Gate 30 play a median of 17 rounds, while those with Gate 40 play a median of 16 rounds. This 6.2% difference is nearly statistically significant (p = 0.0502), again favoring Gate 30.

4. **Retention by Game Rounds**: There's a clear positive relationship between the number of game rounds played and retention rates, for both Day 1 and Day 7 retention. This suggests that engaging players early (during their first sessions) is crucial for long-term retention.

### Business Recommendation

Based on the statistically significant improvement in 7-day retention with Gate 30, we recommend keeping the gate at level 30 rather than moving it to level 40. The combined evidence from all metrics consistently favors the Gate 30 placement, with the Day 7 retention improvement being particularly important as it's a strong indicator of long-term player value.

Why might Gate 30 perform better?
- Players may find level 30 a more natural stopping point than level 40
- The earlier gate may create a more balanced gaming experience
- The 30-level gate may better align with the game's difficulty curve

This analysis demonstrates the importance of data-driven decision making in game design, as small changes in game mechanics can have significant impacts on player retention and engagement.

