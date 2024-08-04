### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1010.1<br />
<br />
Final Rank Value (1010.1) = Starting Rank Value (999.0) + Head To Head Adjustments (11.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.539[<sup>1</sup>](#table2)
- Bounty Collected: 0.424[<sup>2</sup>](#table1)
- Opponent Network: 0.086[<sup>2</sup>](#table1)
- LAN Wins: 0.123[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 999.0
- 400 + ( ( 0.293 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 999.0


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
|           25 |      180 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.43 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      216 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1626 | 2024-05-30 | Chinggis Warriors | L   | 0.763      | -            | -                | -                | -         |   -19.92 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1654 | 2024-05-29 | ATOX              | L   | 0.756      | -            | -                | -                | -         |   -17.24 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1913 | 2024-05-19 | paiN              | L   | 0.690      | -            | -                | -                | -         |    -2.90 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1921 | 2024-05-18 | Liquid            | L   | 0.686      | -            | -                | -                | -         |    -1.59 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2387 | 2024-05-01 | Insilio           | L   | 0.572      | -            | -                | -                | -         |   -12.18 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2416 | 2024-04-30 | Sashi             | L   | 0.564      | -            | -                | -                | -         |    -6.36 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2637 | 2024-04-20 | MIBR              | L   | 0.497      | -            | -                | -                | -         |    -1.58 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2652 | 2024-04-19 | 9z                | W   | 0.494      | 0.589        | 0.406 (0.118)    | 0.619 (0.180)    | 1 (0.494) |    14.54 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2663 | 2024-04-19 | Monte             | W   | 0.492      | 0.589        | 0.060 (0.017)    | 0.162 (0.047)    | 1 (0.492) |     6.63 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2707 | 2024-04-18 | MIBR              | L   | 0.486      | -            | -                | -                | -         |    -1.57 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2836 | 2024-04-14 | Aurora            | L   | 0.458      | -            | -                | -                | -         |    -0.53 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2845 | 2024-04-13 | BetBoom           | W   | 0.452      | 0.684        | 0.252 (0.078)    | 0.543 (0.168)    | 0 (0.000) |    12.59 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2854 | 2024-04-13 | BIG               | W   | 0.450      | 0.684        | 0.155 (0.048)    | 0.305 (0.094)    | 0 (0.000) |    11.61 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2867 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.444      | 0.684        | 0.223 (0.068)    | 0.553 (0.168)    | 0 (0.000) |    13.57 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     2939 | 2024-04-10 | ENCE              | W   | 0.431      | 0.684        | 0.170 (0.050)    | 0.401 (0.118)    | 0 (0.000) |    12.42 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3017 | 2024-04-08 | Aurora            | L   | 0.418      | -            | -                | -                | -         |    -0.34 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3638 | 2024-03-10 | SAW               | L   | 0.225      | -            | -                | -                | -         |    -1.97 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3663 | 2024-03-09 | HEROIC            | W   | 0.218      | 0.535        | 0.229 (0.027)    | 0.375 (0.044)    | 0 (0.000) |     6.58 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3706 | 2024-03-07 | Complexity        | W   | 0.205      | 0.535        | 0.311 (0.034)    | 0.380 (0.042)    | 0 (0.000) |     6.30 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4047 | 2024-02-21 | GamerLegion       | L   | 0.104      | -            | -                | -                | -         |    -2.53 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4080 | 2024-02-20 | Gaimin Gladiators | L   | 0.097      | -            | -                | -                | -         |    -1.66 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4097 | 2024-02-19 | ex-Preasy         | W   | 0.092      | 0.143        | 0.012 (0.000)    | 0.114 (0.001)    | 1 (0.092) |     0.66 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4104 | 2024-02-19 | Apeks             | L   | 0.090      | -            | -                | -                | -         |    -1.79 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,426.61)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.578 | $1,000.00      | $578.06         |
| 2024-04-20 |      0.499 | $10,000.00     | $4,993.52       |
| 2024-04-14 |      0.458 | $70,000.00     | $32,034.72      |
| 2024-03-10 |      0.226 | $12,500.00     | $2,820.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
