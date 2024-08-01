### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [41]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1005.4<br />
<br />
Final Rank Value (1005.4) = Starting Rank Value (999.8) + Head To Head Adjustments (5.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.542[<sup>1</sup>](#table2)
- Bounty Collected: 0.410[<sup>2</sup>](#table1)
- Opponent Network: 0.084[<sup>2</sup>](#table1)
- LAN Wins: 0.130[<sup>2</sup>](#table1)

The average of these factors is 0.292<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 999.8
- 400 + ( ( 0.292 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 999.8


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
|           25 |      101 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.44 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      138 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.18 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1571 | 2024-05-30 | Chinggis Warriors | L   | 0.778      | -            | -                | -                | -         |   -21.12 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1599 | 2024-05-29 | ATOX              | L   | 0.770      | -            | -                | -                | -         |   -17.26 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1885 | 2024-05-19 | paiN              | L   | 0.704      | -            | -                | -                | -         |    -3.94 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1893 | 2024-05-18 | Liquid            | L   | 0.701      | -            | -                | -                | -         |    -1.43 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2373 | 2024-05-01 | Insilio           | L   | 0.586      | -            | -                | -                | -         |   -12.31 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2403 | 2024-04-30 | Sashi             | L   | 0.579      | -            | -                | -                | -         |    -6.27 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2631 | 2024-04-20 | MIBR              | L   | 0.512      | -            | -                | -                | -         |    -1.67 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2646 | 2024-04-19 | 9z                | W   | 0.509      | 0.589        | 0.138 (0.041)    | 0.553 (0.166)    | 1 (0.509) |    10.29 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2658 | 2024-04-19 | Monte             | W   | 0.507      | 0.589        | 0.062 (0.018)    | 0.168 (0.050)    | 1 (0.507) |     7.09 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2703 | 2024-04-18 | MIBR              | L   | 0.501      | -            | -                | -                | -         |    -1.69 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2834 | 2024-04-14 | Aurora            | L   | 0.472      | -            | -                | -                | -         |    -0.52 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2843 | 2024-04-13 | BetBoom           | W   | 0.467      | 0.684        | 0.257 (0.082)    | 0.551 (0.176)    | 0 (0.000) |    13.05 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2852 | 2024-04-13 | BIG               | W   | 0.465      | 0.684        | 0.132 (0.042)    | 0.299 (0.095)    | 0 (0.000) |    10.96 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2865 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.459      | 0.684        | 0.207 (0.065)    | 0.447 (0.140)    | 0 (0.000) |    13.64 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     2938 | 2024-04-10 | ENCE              | W   | 0.445      | 0.684        | 0.173 (0.053)    | 0.403 (0.123)    | 0 (0.000) |    12.90 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3016 | 2024-04-08 | Aurora            | L   | 0.433      | -            | -                | -                | -         |    -0.34 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3656 | 2024-03-10 | SAW               | L   | 0.240      | -            | -                | -                | -         |    -1.99 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3682 | 2024-03-09 | HEROIC            | W   | 0.232      | 0.535        | 0.208 (0.026)    | 0.380 (0.047)    | 0 (0.000) |     7.04 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3725 | 2024-03-07 | Complexity        | W   | 0.220      | 0.535        | 0.318 (0.037)    | 0.366 (0.043)    | 0 (0.000) |     6.75 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4082 | 2024-02-21 | GamerLegion       | L   | 0.119      | -            | -                | -                | -         |    -2.84 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4114 | 2024-02-20 | Gaimin Gladiators | L   | 0.111      | -            | -                | -                | -         |    -1.84 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4131 | 2024-02-19 | ex-Preasy         | W   | 0.107      | 0.143        | 0.013 (0.000)    | 0.121 (0.002)    | 1 (0.107) |     0.79 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4138 | 2024-02-19 | Apeks             | L   | 0.105      | -            | -                | -                | -         |    -2.03 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46,803.14)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-01 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.593 | $1,000.00      | $592.78         |
| 2024-04-20 |      0.514 | $10,000.00     | $5,140.74       |
| 2024-04-14 |      0.472 | $70,000.00     | $33,065.28      |
| 2024-03-10 |      0.240 | $12,500.00     | $3,004.34       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
