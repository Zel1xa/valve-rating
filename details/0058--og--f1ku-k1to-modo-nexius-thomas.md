### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1008.9<br />
<br />
Final Rank Value (1008.9) = Starting Rank Value (995.9) + Head To Head Adjustments (12.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.423[<sup>2</sup>](#table1)
- Opponent Network: 0.082[<sup>2</sup>](#table1)
- LAN Wins: 0.119[<sup>2</sup>](#table1)

The average of these factors is 0.291<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 995.9
- 400 + ( ( 0.291 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 995.9


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
|           25 |      243 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.37 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      278 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1690 | 2024-05-30 | Chinggis Warriors | L   | 0.750      | -            | -                | -                | -         |   -18.01 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1718 | 2024-05-29 | ATOX              | L   | 0.742      | -            | -                | -                | -         |   -16.82 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1977 | 2024-05-19 | paiN              | L   | 0.676      | -            | -                | -                | -         |    -2.87 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1985 | 2024-05-18 | Liquid            | L   | 0.672      | -            | -                | -                | -         |    -1.00 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2451 | 2024-05-01 | Insilio           | L   | 0.558      | -            | -                | -                | -         |   -11.73 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2480 | 2024-04-30 | Sashi             | L   | 0.550      | -            | -                | -                | -         |    -6.05 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2702 | 2024-04-20 | MIBR              | L   | 0.483      | -            | -                | -                | -         |    -1.55 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2717 | 2024-04-19 | 9z                | W   | 0.480      | 0.589        | 0.404 (0.114)    | 0.606 (0.171)    | 1 (0.480) |    14.15 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2728 | 2024-04-19 | Monte             | W   | 0.478      | 0.589        | 0.057 (0.016)    | 0.154 (0.043)    | 1 (0.478) |     6.40 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2772 | 2024-04-18 | MIBR              | L   | 0.472      | -            | -                | -                | -         |    -1.54 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2901 | 2024-04-14 | Aurora            | L   | 0.444      | -            | -                | -                | -         |    -0.48 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2910 | 2024-04-13 | BetBoom           | W   | 0.438      | 0.684        | 0.249 (0.074)    | 0.527 (0.158)    | 0 (0.000) |    12.21 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2919 | 2024-04-13 | BIG               | W   | 0.436      | 0.684        | 0.154 (0.046)    | 0.297 (0.089)    | 0 (0.000) |    11.27 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2932 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.430      | 0.684        | 0.254 (0.075)    | 0.544 (0.160)    | 0 (0.000) |    13.18 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     3004 | 2024-04-10 | ENCE              | W   | 0.417      | 0.684        | 0.174 (0.049)    | 0.432 (0.123)    | 0 (0.000) |    12.10 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3082 | 2024-04-08 | Aurora            | L   | 0.404      | -            | -                | -                | -         |    -0.31 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3704 | 2024-03-10 | SAW               | L   | 0.211      | -            | -                | -                | -         |    -1.86 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3729 | 2024-03-09 | HEROIC            | W   | 0.204      | 0.535        | 0.225 (0.025)    | 0.364 (0.040)    | 0 (0.000) |     6.16 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3772 | 2024-03-07 | Complexity        | W   | 0.191      | 0.535        | 0.342 (0.035)    | 0.373 (0.038)    | 0 (0.000) |     5.88 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4113 | 2024-02-21 | GamerLegion       | L   | 0.090      | -            | -                | -                | -         |    -2.21 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4146 | 2024-02-20 | Gaimin Gladiators | L   | 0.083      | -            | -                | -                | -         |    -1.43 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4163 | 2024-02-19 | ex-Preasy         | W   | 0.078      | 0.143        | 0.011 (0.000)    | 0.106 (0.001)    | 1 (0.078) |     0.56 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4170 | 2024-02-19 | Apeks             | L   | 0.077      | -            | -                | -                | -         |    -1.53 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,128.00)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.564 | $1,000.00      | $564.17         |
| 2024-04-20 |      0.485 | $10,000.00     | $4,854.63       |
| 2024-04-14 |      0.444 | $70,000.00     | $31,062.50      |
| 2024-03-10 |      0.212 | $12,500.00     | $2,646.70       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
