### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: empathy, Juli, Lx, madss, phoebe<br />
Global Rank: [155](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [42]( ../standings_americas.md)<br />
<br />
Final Rank Value:  692.8<br />
<br />
Final Rank Value (692.8) = Starting Rank Value (712.3) + Head To Head Adjustments (-19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.3
- 400 + ( ( 0.153 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 712.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      225 | 2024-07-28 | Nouns fe         | W   | 1.000      | 0.250        | 0.003 (0.001)    | 0.035 (0.009)    | 0 (0.000) |    12.62 | empathy, Juli, Lx, madss, phoebe   |
|           22 |      952 | 2024-06-16 | Lotus fe         | W   | 0.880      | 0.250        | 0.005 (0.001)    | 0.038 (0.008)    | 0 (0.000) |    12.31 | abby, empathy, Juli, Lx, madss     |
|           21 |     1177 | 2024-06-09 | Perseverance     | L   | 0.832      | -            | -                | -                | -         |   -18.32 | abby, empathy, Florence, Lx, madss |
|           20 |     1279 | 2024-06-07 | Zomblers         | L   | 0.821      | -            | -                | -                | -         |   -19.00 | abby, empathy, Florence, Lx, madss |
|           19 |     1427 | 2024-06-05 | Asian Kings      | W   | 0.805      | -            | -                | -                | 0 (0.000) |     3.80 | abby, empathy, Florence, Lx, madss |
|           18 |     1470 | 2024-06-04 | Nouns            | L   | 0.800      | -            | -                | -                | -         |    -4.63 | abby, empathy, Florence, Lx, madss |
|           17 |     1472 | 2024-06-04 | Homyno           | L   | 0.799      | -            | -                | -                | -         |   -12.80 | abby, empathy, Florence, Lx, madss |
|           16 |     1579 | 2024-05-31 | NAVI Javelins    | L   | 0.774      | -            | -                | -                | -         |    -7.61 | abby, empathy, Lx, madss, phoebe   |
|           15 |     1585 | 2024-05-31 | panelinha        | L   | 0.772      | -            | -                | -                | -         |    -7.82 | abby, empathy, Lx, madss, phoebe   |
|           14 |     1699 | 2024-05-26 | FlyQuest RED     | L   | 0.739      | -            | -                | -                | -         |   -10.66 | abby, empathy, Lx, madss, phoebe   |
|           13 |     1700 | 2024-05-26 | Karma            | W   | 0.739      | 0.303        | 0.004 (0.001)    | 0.073 (0.016)    | 0 (0.000) |     9.41 | abby, empathy, Lx, madss, phoebe   |
|           12 |     2298 | 2024-05-05 | Lotus fe         | W   | 0.600      | 0.250        | 0.005 (0.001)    | 0.038 (0.006)    | 0 (0.000) |     7.40 | abby, empathy, Lx, madss, phoebe   |
|           11 |     2653 | 2024-04-19 | Limitless Angels | W   | 0.494      | 0.322        | 0.003 (0.000)    | 0.049 (0.008)    | 0 (0.000) |     6.10 | abby, empathy, Lx, madss, phoebe   |
|           10 |     2831 | 2024-04-14 | FlyQuest RED     | L   | 0.460      | -            | -                | -                | -         |    -6.81 | abby, empathy, Lx, madss, phoebe   |
|            9 |     2878 | 2024-04-11 | COVEN            | W   | 0.440      | 0.322        | 0.002 (0.000)    | -                | 0 (0.000) |     3.29 | abby, empathy, Lx, madss, phoebe   |
|            8 |     3045 | 2024-04-07 | Limitless Angels | W   | 0.413      | 0.250        | 0.003 (0.000)    | 0.049 (0.005)    | 0 (0.000) |     5.12 | abby, empathy, Lx, madss, phoebe   |
|            7 |     3143 | 2024-04-03 | WG Bandits       | W   | 0.387      | 0.322        | 0.002 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     4.35 | abby, empathy, Lx, madss, phoebe   |
|            6 |     3276 | 2024-03-27 | cleanup crew fe  | W   | 0.340      | 0.322        | -                | 0.021 (0.002)    | 0 (0.000) |     4.17 | abby, empathy, Lx, madss, phoebe   |
|            5 |     3371 | 2024-03-21 | Karma            | W   | 0.300      | 0.322        | 0.004 (0.000)    | 0.073 (0.007)    | -         |     4.00 | abby, empathy, Lx, madss, phoebe   |
|            4 |     3515 | 2024-03-14 | Nouns fe         | W   | 0.254      | 0.322        | 0.003 (0.000)    | 0.035 (0.003)    | -         |     3.36 | abby, empathy, Lx, madss, phoebe   |
|            3 |     3724 | 2024-03-06 | FlyQuest RED     | L   | 0.201      | -            | -                | -                | -         |    -2.99 | abby, empathy, Lx, madss, phoebe   |
|            2 |     3808 | 2024-03-03 | FlyQuest RED     | L   | 0.180      | -            | -                | -                | -         |    -2.73 | abby, empathy, Lx, madss, phoebe   |
|            1 |     3948 | 2024-02-25 | FlyQuest RED     | L   | 0.133      | -            | -                | -                | -         |    -2.04 | abby, empathy, Lx, madss, phoebe   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,616.46)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $750.00        | $750.00         |
| 2024-06-16 |      0.880 | $750.00        | $660.03         |
| 2024-06-02 |      0.786 | $4,000.00      | $3,144.44       |
| 2024-05-26 |      0.739 | $1,500.00      | $1,108.68       |
| 2024-05-05 |      0.600 | $750.00        | $450.03         |
| 2024-04-14 |      0.460 | $250.00        | $114.93         |
| 2024-04-07 |      0.413 | $750.00        | $310.00         |
| 2024-03-03 |      0.180 | $250.00        | $45.01          |
| 2024-02-25 |      0.133 | $250.00        | $33.33          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
