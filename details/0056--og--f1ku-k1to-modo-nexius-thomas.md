### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [41]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1005.5<br />
<br />
Final Rank Value (1005.5) = Starting Rank Value (1000.5) + Head To Head Adjustments (5.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.542[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.083[<sup>2</sup>](#table1)
- LAN Wins: 0.130[<sup>2</sup>](#table1)

The average of these factors is 0.292<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1000.5
- 400 + ( ( 0.292 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1000.5


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
|           25 |       95 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.44 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      132 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.18 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1565 | 2024-05-30 | Chinggis Warriors | L   | 0.780      | -            | -                | -                | -         |   -21.16 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1593 | 2024-05-29 | ATOX              | L   | 0.772      | -            | -                | -                | -         |   -17.27 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1879 | 2024-05-19 | paiN              | L   | 0.706      | -            | -                | -                | -         |    -3.92 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1887 | 2024-05-18 | Liquid            | L   | 0.702      | -            | -                | -                | -         |    -1.97 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2367 | 2024-05-01 | Insilio           | L   | 0.588      | -            | -                | -                | -         |   -12.34 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2397 | 2024-04-30 | Sashi             | L   | 0.581      | -            | -                | -                | -         |    -6.28 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2625 | 2024-04-20 | MIBR              | L   | 0.514      | -            | -                | -                | -         |    -1.66 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2640 | 2024-04-19 | 9z                | W   | 0.510      | 0.589        | 0.138 (0.041)    | 0.554 (0.166)    | 1 (0.510) |    10.31 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2652 | 2024-04-19 | Monte             | W   | 0.509      | 0.589        | 0.062 (0.018)    | 0.168 (0.050)    | 1 (0.509) |     7.12 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2697 | 2024-04-18 | MIBR              | L   | 0.502      | -            | -                | -                | -         |    -1.68 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2828 | 2024-04-14 | Aurora            | L   | 0.474      | -            | -                | -                | -         |    -0.53 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2837 | 2024-04-13 | BetBoom           | W   | 0.468      | 0.684        | 0.257 (0.082)    | 0.551 (0.177)    | 0 (0.000) |    13.09 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2846 | 2024-04-13 | BIG               | W   | 0.467      | 0.684        | 0.132 (0.042)    | 0.299 (0.095)    | 0 (0.000) |    11.01 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2859 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.460      | 0.684        | 0.207 (0.065)    | 0.409 (0.129)    | 0 (0.000) |    13.42 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     2932 | 2024-04-10 | ENCE              | W   | 0.447      | 0.684        | 0.174 (0.053)    | 0.403 (0.123)    | 0 (0.000) |    12.95 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3010 | 2024-04-08 | Aurora            | L   | 0.435      | -            | -                | -                | -         |    -0.34 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3650 | 2024-03-10 | SAW               | L   | 0.241      | -            | -                | -                | -         |    -1.99 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3676 | 2024-03-09 | HEROIC            | W   | 0.234      | 0.535        | 0.209 (0.026)    | 0.381 (0.048)    | 0 (0.000) |     7.09 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3719 | 2024-03-07 | Complexity        | W   | 0.222      | 0.535        | 0.318 (0.038)    | 0.366 (0.043)    | 0 (0.000) |     6.80 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4076 | 2024-02-21 | GamerLegion       | L   | 0.121      | -            | -                | -                | -         |    -2.88 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4108 | 2024-02-20 | Gaimin Gladiators | L   | 0.113      | -            | -                | -                | -         |    -1.86 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4125 | 2024-02-19 | ex-Preasy         | W   | 0.108      | 0.143        | 0.013 (0.000)    | 0.121 (0.002)    | 1 (0.108) |     0.80 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4132 | 2024-02-19 | Apeks             | L   | 0.107      | -            | -                | -                | -         |    -2.06 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46,958.97)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-01 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.594 | $1,000.00      | $594.44         |
| 2024-04-20 |      0.516 | $10,000.00     | $5,157.41       |
| 2024-04-14 |      0.474 | $70,000.00     | $33,181.94      |
| 2024-03-10 |      0.242 | $12,500.00     | $3,025.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
