### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1009.9<br />
<br />
Final Rank Value (1009.9) = Starting Rank Value (998.3) + Head To Head Adjustments (11.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.425[<sup>2</sup>](#table1)
- Opponent Network: 0.085[<sup>2</sup>](#table1)
- LAN Wins: 0.122[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 998.3
- 400 + ( ( 0.293 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 998.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      215 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.37 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      252 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1662 | 2024-05-30 | Chinggis Warriors | L   | 0.759      | -            | -                | -                | -         |   -19.80 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1690 | 2024-05-29 | ATOX              | L   | 0.751      | -            | -                | -                | -         |   -17.10 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1949 | 2024-05-19 | paiN              | L   | 0.685      | -            | -                | -                | -         |    -2.89 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1957 | 2024-05-18 | Liquid            | L   | 0.681      | -            | -                | -                | -         |    -1.03 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2423 | 2024-05-01 | Insilio           | L   | 0.567      | -            | -                | -                | -         |   -12.04 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2452 | 2024-04-30 | Sashi             | L   | 0.559      | -            | -                | -                | -         |    -6.22 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2674 | 2024-04-20 | MIBR              | L   | 0.492      | -            | -                | -                | -         |    -1.57 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2689 | 2024-04-19 | 9z                | W   | 0.489      | 0.589        | 0.405 (0.117)    | 0.618 (0.178)    | 1 (0.489) |    14.41 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2700 | 2024-04-19 | Monte             | W   | 0.487      | 0.589        | 0.057 (0.016)    | 0.160 (0.046)    | 1 (0.487) |     6.51 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2744 | 2024-04-18 | MIBR              | L   | 0.481      | -            | -                | -                | -         |    -1.56 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2873 | 2024-04-14 | Aurora            | L   | 0.453      | -            | -                | -                | -         |    -0.51 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2882 | 2024-04-13 | BetBoom           | W   | 0.447      | 0.684        | 0.251 (0.077)    | 0.541 (0.165)    | 0 (0.000) |    12.46 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2891 | 2024-04-13 | BIG               | W   | 0.445      | 0.684        | 0.155 (0.047)    | 0.304 (0.093)    | 0 (0.000) |    11.48 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2904 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.439      | 0.684        | 0.254 (0.076)    | 0.553 (0.166)    | 0 (0.000) |    13.45 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     2976 | 2024-04-10 | ENCE              | W   | 0.426      | 0.684        | 0.169 (0.049)    | 0.400 (0.117)    | 0 (0.000) |    12.30 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3054 | 2024-04-08 | Aurora            | L   | 0.413      | -            | -                | -                | -         |    -0.33 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3676 | 2024-03-10 | SAW               | L   | 0.220      | -            | -                | -                | -         |    -1.92 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3701 | 2024-03-09 | HEROIC            | W   | 0.213      | 0.535        | 0.229 (0.026)    | 0.373 (0.042)    | 0 (0.000) |     6.43 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3744 | 2024-03-07 | Complexity        | W   | 0.200      | 0.535        | 0.342 (0.037)    | 0.380 (0.041)    | 0 (0.000) |     6.16 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4085 | 2024-02-21 | GamerLegion       | L   | 0.099      | -            | -                | -                | -         |    -2.43 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4118 | 2024-02-20 | Gaimin Gladiators | L   | 0.092      | -            | -                | -                | -         |    -1.58 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4135 | 2024-02-19 | ex-Preasy         | W   | 0.087      | 0.143        | 0.012 (0.000)    | 0.112 (0.001)    | 1 (0.087) |     0.62 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4142 | 2024-02-19 | Apeks             | L   | 0.086      | -            | -                | -                | -         |    -1.71 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,974.26)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.573 | $1,000.00      | $573.22         |
| 2024-04-20 |      0.495 | $10,000.00     | $4,945.14       |
| 2024-04-14 |      0.453 | $70,000.00     | $31,696.06      |
| 2024-03-10 |      0.221 | $12,500.00     | $2,759.84       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
