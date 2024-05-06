# NBA Play Type Data - 2016-2024

NBA regular season play type data from 2015-16 to the recently completed 2023-24 season.

Some of the coolest NBA data resides on NBA.com but is not easily accessible. Their play type data, provided by Synergy Sports, is unique in that in provides extreme nuance about a player's game but is hard to find in publicly available data. So... I've scraped all 9 seasons of available play type data since 2015 (began tracking in 2015) and provided it in the link below! I've also cleaned it quite a bit to improve uniformity and also added percentile ranks to allow for easier comparisons between players. Hoping it can help inspire some cool projects!

--- Data Source

NBA.com via Synergy Sports

--- Link to Data 

Here is the link to the google drive folder: https://drive.google.com/file/d/1_P2ZYwkEMX0Lqpl27oA5mfN9RCMluCcl/view?usp=sharing


--- Data Dictionary

- POSS: Number of possessions used by that player, in that play type, in that year.
- FREQ: Frequency of play type used by that player, in that play type, in that year. (%)
  - FREQ_PCTL: Percentile rank of play type frequency.
  - Scale of 0 to 100 --- (0 relates to worst while 100 relates to best)
- PPP: Points per possessions of that player, in that play type, in that year. (%)
  - PPP_PCTL: Percentile rank of PPP variable. 
  - Scale of 0 to 100 --- (0 relates to worst while 100 relates to best)
- GP: Games Played
- PTS: Points
- FG: Field goals made
- FGA: Field goals attempted
- FG_PCT: Field goal percentage (%)
- EFG_PCT: Effective field goal percentage (%)
- SF_FREQ: Frequency of shooting fouls drawn (%)
- FTA_FREQ: Frequency of free throws attempted (%)
- AND1_FREQ: Frequency of and one plays made (%)
- TOV_FREQ: Frequenyc of turnovers committed (%)



--- Snapshot of Data 

<img width="1330" alt="Screenshot 2023-04-12 at 8 52 07 AM" src="https://user-images.githubusercontent.com/70119566/231479173-463e8dbd-cc06-4612-b189-ae6ba36cfdda.png">


--- Example of Potential Data Viz

![23_04_06_Markkanen](https://user-images.githubusercontent.com/70119566/231478790-981daa2e-9bf4-49a6-a2a6-2a0839ebb46d.jpg)

