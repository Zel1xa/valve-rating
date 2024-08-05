### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1009.5<br />
<br />
Final Rank Value (1009.5) = Starting Rank Value (998.0) + Head To Head Adjustments (11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.425[<sup>2</sup>](#table1)
- Opponent Network: 0.085[<sup>2</sup>](#table1)
- LAN Wins: 0.121[<sup>2</sup>](#table1)

The average of these factors is 0.292<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 998.0
- 400 + ( ( 0.292 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 998.0


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
|           25 |      219 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.37 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      254 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1666 | 2024-05-30 | Chinggis Warriors | L   | 0.756      | -            | -                | -                | -         |   -19.73 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1694 | 2024-05-29 | ATOX              | L   | 0.748      | -            | -                | -                | -         |   -17.04 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1953 | 2024-05-19 | paiN              | L   | 0.682      | -            | -                | -                | -         |    -2.89 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1961 | 2024-05-18 | Liquid            | L   | 0.679      | -            | -                | -                | -         |    -1.02 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2427 | 2024-05-01 | Insilio           | L   | 0.564      | -            | -                | -                | -         |   -11.98 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2456 | 2024-04-30 | Sashi             | L   | 0.557      | -            | -                | -                | -         |    -6.18 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2678 | 2024-04-20 | MIBR              | L   | 0.490      | -            | -                | -                | -         |    -1.56 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2693 | 2024-04-19 | 9z                | W   | 0.487      | 0.589        | 0.405 (0.116)    | 0.617 (0.177)    | 1 (0.487) |    14.34 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2704 | 2024-04-19 | Monte             | W   | 0.485      | 0.589        | 0.057 (0.016)    | 0.159 (0.045)    | 1 (0.485) |     6.47 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2748 | 2024-04-18 | MIBR              | L   | 0.479      | -            | -                | -                | -         |    -1.56 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2877 | 2024-04-14 | Aurora            | L   | 0.450      | -            | -                | -                | -         |    -0.51 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2886 | 2024-04-13 | BetBoom           | W   | 0.445      | 0.684        | 0.250 (0.076)    | 0.540 (0.164)    | 0 (0.000) |    12.39 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2895 | 2024-04-13 | BIG               | W   | 0.443      | 0.684        | 0.155 (0.047)    | 0.303 (0.092)    | 0 (0.000) |    11.42 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2908 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.437      | 0.684        | 0.254 (0.076)    | 0.553 (0.165)    | 0 (0.000) |    13.38 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     2980 | 2024-04-10 | ENCE              | W   | 0.423      | 0.684        | 0.168 (0.049)    | 0.439 (0.127)    | 0 (0.000) |    12.26 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3058 | 2024-04-08 | Aurora            | L   | 0.411      | -            | -                | -                | -         |    -0.33 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3680 | 2024-03-10 | SAW               | L   | 0.218      | -            | -                | -                | -         |    -1.91 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3705 | 2024-03-09 | HEROIC            | W   | 0.210      | 0.535        | 0.226 (0.025)    | 0.372 (0.042)    | 0 (0.000) |     6.36 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3748 | 2024-03-07 | Complexity        | W   | 0.198      | 0.535        | 0.342 (0.036)    | 0.380 (0.040)    | 0 (0.000) |     6.09 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4089 | 2024-02-21 | GamerLegion       | L   | 0.097      | -            | -                | -                | -         |    -2.37 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4122 | 2024-02-20 | Gaimin Gladiators | L   | 0.089      | -            | -                | -                | -         |    -1.54 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4139 | 2024-02-19 | ex-Preasy         | W   | 0.085      | 0.143        | 0.012 (0.000)    | 0.111 (0.001)    | 1 (0.085) |     0.60 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4146 | 2024-02-19 | Apeks             | L   | 0.083      | -            | -                | -                | -         |    -1.66 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,751.33)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.571 | $1,000.00      | $570.83         |
| 2024-04-20 |      0.492 | $10,000.00     | $4,921.30       |
| 2024-04-14 |      0.450 | $70,000.00     | $31,529.17      |
| 2024-03-10 |      0.218 | $12,500.00     | $2,730.03       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
