### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [57](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [41]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1009.7<br />
<br />
Final Rank Value (1009.7) = Starting Rank Value (996.8) + Head To Head Adjustments (12.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.424[<sup>2</sup>](#table1)
- Opponent Network: 0.083[<sup>2</sup>](#table1)
- LAN Wins: 0.120[<sup>2</sup>](#table1)

The average of these factors is 0.291<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 996.8
- 400 + ( ( 0.291 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 996.8


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
|           25 |      240 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.37 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      275 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1687 | 2024-05-30 | Chinggis Warriors | L   | 0.752      | -            | -                | -                | -         |   -18.08 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1715 | 2024-05-29 | ATOX              | L   | 0.744      | -            | -                | -                | -         |   -16.89 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1974 | 2024-05-19 | paiN              | L   | 0.678      | -            | -                | -                | -         |    -2.88 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1982 | 2024-05-18 | Liquid            | L   | 0.674      | -            | -                | -                | -         |    -1.00 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2448 | 2024-05-01 | Insilio           | L   | 0.560      | -            | -                | -                | -         |   -11.83 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2477 | 2024-04-30 | Sashi             | L   | 0.552      | -            | -                | -                | -         |    -6.10 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2699 | 2024-04-20 | MIBR              | L   | 0.486      | -            | -                | -                | -         |    -1.56 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2714 | 2024-04-19 | 9z                | W   | 0.482      | 0.589        | 0.404 (0.115)    | 0.607 (0.172)    | 1 (0.482) |    14.21 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2725 | 2024-04-19 | Monte             | W   | 0.481      | 0.589        | 0.057 (0.016)    | 0.155 (0.044)    | 1 (0.481) |     6.42 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2769 | 2024-04-18 | MIBR              | L   | 0.474      | -            | -                | -                | -         |    -1.55 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2898 | 2024-04-14 | Aurora            | L   | 0.446      | -            | -                | -                | -         |    -0.49 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2907 | 2024-04-13 | BetBoom           | W   | 0.440      | 0.684        | 0.249 (0.075)    | 0.529 (0.159)    | 0 (0.000) |    12.27 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2916 | 2024-04-13 | BIG               | W   | 0.438      | 0.684        | 0.154 (0.046)    | 0.298 (0.089)    | 0 (0.000) |    11.32 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2929 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.432      | 0.684        | 0.254 (0.075)    | 0.544 (0.161)    | 0 (0.000) |    13.24 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     3001 | 2024-04-10 | ENCE              | W   | 0.419      | 0.684        | 0.174 (0.050)    | 0.432 (0.124)    | 0 (0.000) |    12.16 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3079 | 2024-04-08 | Aurora            | L   | 0.407      | -            | -                | -                | -         |    -0.32 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3701 | 2024-03-10 | SAW               | L   | 0.213      | -            | -                | -                | -         |    -1.87 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3726 | 2024-03-09 | HEROIC            | W   | 0.206      | 0.535        | 0.225 (0.025)    | 0.365 (0.040)    | 0 (0.000) |     6.22 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3769 | 2024-03-07 | Complexity        | W   | 0.194      | 0.535        | 0.342 (0.035)    | 0.373 (0.039)    | 0 (0.000) |     5.95 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4110 | 2024-02-21 | GamerLegion       | L   | 0.092      | -            | -                | -                | -         |    -2.27 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4143 | 2024-02-20 | Gaimin Gladiators | L   | 0.085      | -            | -                | -                | -         |    -1.47 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4160 | 2024-02-19 | ex-Preasy         | W   | 0.080      | 0.143        | 0.012 (0.000)    | 0.107 (0.001)    | 1 (0.080) |     0.57 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4167 | 2024-02-19 | Apeks             | L   | 0.079      | -            | -                | -                | -         |    -1.57 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,335.78)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.566 | $1,000.00      | $566.39         |
| 2024-04-20 |      0.488 | $10,000.00     | $4,876.85       |
| 2024-04-14 |      0.446 | $70,000.00     | $31,218.06      |
| 2024-03-10 |      0.214 | $12,500.00     | $2,674.48       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
