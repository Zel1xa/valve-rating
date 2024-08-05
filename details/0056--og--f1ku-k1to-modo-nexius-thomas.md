### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [41]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1024.4<br />
<br />
Final Rank Value (1024.4) = Starting Rank Value (1015.3) + Head To Head Adjustments (9.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.542[<sup>1</sup>](#table2)
- Bounty Collected: 0.432[<sup>2</sup>](#table1)
- Opponent Network: 0.089[<sup>2</sup>](#table1)
- LAN Wins: 0.131[<sup>2</sup>](#table1)

The average of these factors is 0.298<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1015.3
- 400 + ( ( 0.298 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1015.3


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
|           25 |       66 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.45 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      103 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1513 | 2024-05-30 | Chinggis Warriors | L   | 0.784      | -            | -                | -                | -         |   -21.57 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1541 | 2024-05-29 | ATOX              | L   | 0.776      | -            | -                | -                | -         |   -17.87 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1800 | 2024-05-19 | paiN              | L   | 0.710      | -            | -                | -                | -         |    -3.02 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1808 | 2024-05-18 | Liquid            | L   | 0.707      | -            | -                | -                | -         |    -1.95 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2274 | 2024-05-01 | Insilio           | L   | 0.592      | -            | -                | -                | -         |   -12.88 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2303 | 2024-04-30 | Sashi             | L   | 0.585      | -            | -                | -                | -         |    -6.77 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2525 | 2024-04-20 | MIBR              | L   | 0.518      | -            | -                | -                | -         |    -1.70 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2540 | 2024-04-19 | 9z                | W   | 0.515      | 0.589        | 0.408 (0.124)    | 0.625 (0.189)    | 1 (0.515) |    15.16 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2551 | 2024-04-19 | Monte             | W   | 0.513      | 0.589        | 0.062 (0.019)    | 0.170 (0.051)    | 1 (0.513) |     6.91 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2595 | 2024-04-18 | MIBR              | L   | 0.507      | -            | -                | -                | -         |    -1.70 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2724 | 2024-04-14 | Aurora            | L   | 0.478      | -            | -                | -                | -         |    -0.56 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2733 | 2024-04-13 | BetBoom           | W   | 0.473      | 0.684        | 0.256 (0.083)    | 0.554 (0.179)    | 0 (0.000) |    13.17 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2742 | 2024-04-13 | BIG               | W   | 0.471      | 0.684        | 0.157 (0.051)    | 0.300 (0.097)    | 0 (0.000) |    11.10 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2755 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.465      | 0.684        | 0.256 (0.082)    | 0.477 (0.152)    | 0 (0.000) |    14.11 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     2827 | 2024-04-10 | ENCE              | W   | 0.451      | 0.684        | 0.173 (0.053)    | 0.404 (0.125)    | 0 (0.000) |    13.05 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     2905 | 2024-04-08 | Aurora            | L   | 0.439      | -            | -                | -                | -         |    -0.36 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3527 | 2024-03-10 | SAW               | L   | 0.246      | -            | -                | -                | -         |    -2.15 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3552 | 2024-03-09 | HEROIC            | W   | 0.238      | 0.535        | 0.234 (0.030)    | 0.382 (0.049)    | 0 (0.000) |     7.22 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3595 | 2024-03-07 | Complexity        | W   | 0.226      | 0.535        | 0.348 (0.042)    | 0.367 (0.044)    | 0 (0.000) |     6.93 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     3936 | 2024-02-21 | GamerLegion       | L   | 0.125      | -            | -                | -                | -         |    -3.02 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     3969 | 2024-02-20 | Gaimin Gladiators | L   | 0.117      | -            | -                | -                | -         |    -2.00 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     3986 | 2024-02-19 | ex-Preasy         | W   | 0.113      | 0.143        | 0.014 (0.000)    | 0.123 (0.002)    | 1 (0.113) |     0.80 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     3993 | 2024-02-19 | Apeks             | L   | 0.111      | -            | -                | -                | -         |    -2.19 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($47,364.57)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.599 | $1,000.00      | $598.78         |
| 2024-04-20 |      0.520 | $10,000.00     | $5,200.79       |
| 2024-04-14 |      0.478 | $70,000.00     | $33,485.60      |
| 2024-03-10 |      0.246 | $12,500.00     | $3,079.40       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
