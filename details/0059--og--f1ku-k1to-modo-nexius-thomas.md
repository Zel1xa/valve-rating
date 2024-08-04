### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1010.0<br />
<br />
Final Rank Value (1010.0) = Starting Rank Value (998.4) + Head To Head Adjustments (11.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.425[<sup>2</sup>](#table1)
- Opponent Network: 0.085[<sup>2</sup>](#table1)
- LAN Wins: 0.122[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 998.4
- 400 + ( ( 0.293 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 998.4


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
|           25 |      214 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.37 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      251 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1661 | 2024-05-30 | Chinggis Warriors | L   | 0.759      | -            | -                | -                | -         |   -19.80 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1689 | 2024-05-29 | ATOX              | L   | 0.751      | -            | -                | -                | -         |   -17.11 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1948 | 2024-05-19 | paiN              | L   | 0.685      | -            | -                | -                | -         |    -2.89 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1956 | 2024-05-18 | Liquid            | L   | 0.681      | -            | -                | -                | -         |    -1.03 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2422 | 2024-05-01 | Insilio           | L   | 0.567      | -            | -                | -                | -         |   -12.05 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2451 | 2024-04-30 | Sashi             | L   | 0.560      | -            | -                | -                | -         |    -6.23 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2673 | 2024-04-20 | MIBR              | L   | 0.493      | -            | -                | -                | -         |    -1.57 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2688 | 2024-04-19 | 9z                | W   | 0.489      | 0.589        | 0.405 (0.117)    | 0.618 (0.178)    | 1 (0.489) |    14.42 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2699 | 2024-04-19 | Monte             | W   | 0.488      | 0.589        | 0.058 (0.017)    | 0.160 (0.046)    | 1 (0.488) |     6.51 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2743 | 2024-04-18 | MIBR              | L   | 0.481      | -            | -                | -                | -         |    -1.56 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2872 | 2024-04-14 | Aurora            | L   | 0.453      | -            | -                | -                | -         |    -0.52 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2881 | 2024-04-13 | BetBoom           | W   | 0.447      | 0.684        | 0.251 (0.077)    | 0.541 (0.166)    | 0 (0.000) |    12.47 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2890 | 2024-04-13 | BIG               | W   | 0.446      | 0.684        | 0.155 (0.047)    | 0.304 (0.093)    | 0 (0.000) |    11.49 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2903 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.439      | 0.684        | 0.255 (0.076)    | 0.553 (0.166)    | 0 (0.000) |    13.46 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     2975 | 2024-04-10 | ENCE              | W   | 0.426      | 0.684        | 0.169 (0.049)    | 0.400 (0.117)    | 0 (0.000) |    12.31 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3053 | 2024-04-08 | Aurora            | L   | 0.414      | -            | -                | -                | -         |    -0.34 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3675 | 2024-03-10 | SAW               | L   | 0.220      | -            | -                | -                | -         |    -1.93 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3700 | 2024-03-09 | HEROIC            | W   | 0.213      | 0.535        | 0.229 (0.026)    | 0.373 (0.043)    | 0 (0.000) |     6.44 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3743 | 2024-03-07 | Complexity        | W   | 0.201      | 0.535        | 0.342 (0.037)    | 0.380 (0.041)    | 0 (0.000) |     6.17 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4084 | 2024-02-21 | GamerLegion       | L   | 0.100      | -            | -                | -                | -         |    -2.44 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4117 | 2024-02-20 | Gaimin Gladiators | L   | 0.092      | -            | -                | -                | -         |    -1.58 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4134 | 2024-02-19 | ex-Preasy         | W   | 0.087      | 0.143        | 0.012 (0.000)    | 0.112 (0.001)    | 1 (0.087) |     0.62 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4141 | 2024-02-19 | Apeks             | L   | 0.086      | -            | -                | -                | -         |    -1.71 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,002.40)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.574 | $1,000.00      | $573.52         |
| 2024-04-20 |      0.495 | $10,000.00     | $4,948.15       |
| 2024-04-14 |      0.453 | $70,000.00     | $31,717.13      |
| 2024-03-10 |      0.221 | $12,500.00     | $2,763.60       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
