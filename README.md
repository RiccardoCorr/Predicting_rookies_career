# Predicting rookies' career

## Abstract
In the NBA, where competition reigns supreme, only the best players secure a spot on the court. Every team must carefully curate their roster, balancing competitiveness with fiscal responsibility, adhering to the league's salary caps. Choosing the right players becomes a strategic imperative for each franchise. As a new wave of rookie players enters the league every year, not all will rise to the occasion. Hence, it's crucial to anticipate and predict the potential of these newcomers. Our project aims to forecast the performance of the 2023 rookie class based on their first-year achievements.

## Proposed Method explained
The project idea was to start with an exploratory data analysis to identify any outliers that necessitated modifications to our dataset. The stat we wanted to predict for the rookies of the 2023 season was the Player Efficiency Rating (PER). PER is a per-minute rating that summarizes a player's statistical accomplishments in a single number.

Next, we would build a linear regression model using 80% of the dataset and then test its performance on the remaining 20%. The result obtained would be the subject of our next step. Additionally, we would explore another path, comparing by position and conducting a more in-depth analysis, using clustering algorithms to perform a more detailed analysis.

Finally, we would predict the rookies' PER with the models built before and evaluate the accuracy achieved.
