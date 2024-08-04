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
- 400 + ( ( 0.293 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 998.4


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
|           25 |      191 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.41 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      228 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1638 | 2024-05-30 | Chinggis Warriors | L   | 0.760      | -            | -                | -                | -         |   -19.82 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1666 | 2024-05-29 | ATOX              | L   | 0.752      | -            | -                | -                | -         |   -17.12 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1925 | 2024-05-19 | paiN              | L   | 0.686      | -            | -                | -                | -         |    -2.90 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1933 | 2024-05-18 | Liquid            | L   | 0.682      | -            | -                | -                | -         |    -1.04 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2399 | 2024-05-01 | Insilio           | L   | 0.568      | -            | -                | -                | -         |   -12.06 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2428 | 2024-04-30 | Sashi             | L   | 0.560      | -            | -                | -                | -         |    -6.26 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2650 | 2024-04-20 | MIBR              | L   | 0.494      | -            | -                | -                | -         |    -1.57 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2665 | 2024-04-19 | 9z                | W   | 0.490      | 0.589        | 0.405 (0.117)    | 0.618 (0.178)    | 1 (0.490) |    14.44 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2676 | 2024-04-19 | Monte             | W   | 0.488      | 0.589        | 0.058 (0.017)    | 0.160 (0.046)    | 1 (0.488) |     6.55 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2720 | 2024-04-18 | MIBR              | L   | 0.482      | -            | -                | -                | -         |    -1.56 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2849 | 2024-04-14 | Aurora            | L   | 0.454      | -            | -                | -                | -         |    -0.52 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2858 | 2024-04-13 | BetBoom           | W   | 0.448      | 0.684        | 0.251 (0.077)    | 0.541 (0.166)    | 0 (0.000) |    12.49 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2867 | 2024-04-13 | BIG               | W   | 0.446      | 0.684        | 0.155 (0.047)    | 0.304 (0.093)    | 0 (0.000) |    11.51 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2880 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.440      | 0.684        | 0.255 (0.077)    | 0.553 (0.167)    | 0 (0.000) |    13.48 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     2952 | 2024-04-10 | ENCE              | W   | 0.427      | 0.684        | 0.169 (0.049)    | 0.400 (0.117)    | 0 (0.000) |    12.32 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3030 | 2024-04-08 | Aurora            | L   | 0.414      | -            | -                | -                | -         |    -0.34 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3652 | 2024-03-10 | SAW               | L   | 0.221      | -            | -                | -                | -         |    -1.94 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3677 | 2024-03-09 | HEROIC            | W   | 0.214      | 0.535        | 0.229 (0.026)    | 0.373 (0.043)    | 0 (0.000) |     6.46 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3720 | 2024-03-07 | Complexity        | W   | 0.202      | 0.535        | 0.310 (0.033)    | 0.380 (0.041)    | 0 (0.000) |     6.19 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4061 | 2024-02-21 | GamerLegion       | L   | 0.100      | -            | -                | -                | -         |    -2.45 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4094 | 2024-02-20 | Gaimin Gladiators | L   | 0.093      | -            | -                | -                | -         |    -1.60 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4111 | 2024-02-19 | ex-Preasy         | W   | 0.088      | 0.143        | 0.012 (0.000)    | 0.112 (0.001)    | 1 (0.088) |     0.63 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4118 | 2024-02-19 | Apeks             | L   | 0.087      | -            | -                | -                | -         |    -1.72 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,073.82)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.574 | $1,000.00      | $574.28         |
| 2024-04-20 |      0.496 | $10,000.00     | $4,955.79       |
| 2024-04-14 |      0.454 | $70,000.00     | $31,770.60      |
| 2024-03-10 |      0.222 | $12,500.00     | $2,773.15       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
