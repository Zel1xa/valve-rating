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
Final Rank Value (1005.5) = Starting Rank Value (999.8) + Head To Head Adjustments (5.6)<br />

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
|           25 |       99 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.44 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      136 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.18 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1569 | 2024-05-30 | Chinggis Warriors | L   | 0.778      | -            | -                | -                | -         |   -21.13 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1597 | 2024-05-29 | ATOX              | L   | 0.771      | -            | -                | -                | -         |   -17.26 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1883 | 2024-05-19 | paiN              | L   | 0.705      | -            | -                | -                | -         |    -3.94 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1891 | 2024-05-18 | Liquid            | L   | 0.701      | -            | -                | -                | -         |    -1.43 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2371 | 2024-05-01 | Insilio           | L   | 0.587      | -            | -                | -                | -         |   -12.32 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2401 | 2024-04-30 | Sashi             | L   | 0.579      | -            | -                | -                | -         |    -6.28 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2629 | 2024-04-20 | MIBR              | L   | 0.512      | -            | -                | -                | -         |    -1.67 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2644 | 2024-04-19 | 9z                | W   | 0.509      | 0.589        | 0.138 (0.041)    | 0.553 (0.166)    | 1 (0.509) |    10.29 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2656 | 2024-04-19 | Monte             | W   | 0.507      | 0.589        | 0.062 (0.018)    | 0.168 (0.050)    | 1 (0.507) |     7.09 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2701 | 2024-04-18 | MIBR              | L   | 0.501      | -            | -                | -                | -         |    -1.69 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2832 | 2024-04-14 | Aurora            | L   | 0.473      | -            | -                | -                | -         |    -0.53 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2841 | 2024-04-13 | BetBoom           | W   | 0.467      | 0.684        | 0.257 (0.082)    | 0.551 (0.176)    | 0 (0.000) |    13.05 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2850 | 2024-04-13 | BIG               | W   | 0.465      | 0.684        | 0.132 (0.042)    | 0.299 (0.095)    | 0 (0.000) |    10.97 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2863 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.459      | 0.684        | 0.207 (0.065)    | 0.447 (0.140)    | 0 (0.000) |    13.65 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     2936 | 2024-04-10 | ENCE              | W   | 0.446      | 0.684        | 0.174 (0.053)    | 0.403 (0.123)    | 0 (0.000) |    12.90 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3014 | 2024-04-08 | Aurora            | L   | 0.433      | -            | -                | -                | -         |    -0.34 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3654 | 2024-03-10 | SAW               | L   | 0.240      | -            | -                | -                | -         |    -1.99 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3680 | 2024-03-09 | HEROIC            | W   | 0.233      | 0.535        | 0.208 (0.026)    | 0.380 (0.047)    | 0 (0.000) |     7.05 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3723 | 2024-03-07 | Complexity        | W   | 0.220      | 0.535        | 0.318 (0.037)    | 0.366 (0.043)    | 0 (0.000) |     6.76 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4080 | 2024-02-21 | GamerLegion       | L   | 0.119      | -            | -                | -                | -         |    -2.85 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4112 | 2024-02-20 | Gaimin Gladiators | L   | 0.112      | -            | -                | -                | -         |    -1.84 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4129 | 2024-02-19 | ex-Preasy         | W   | 0.107      | 0.143        | 0.013 (0.000)    | 0.121 (0.002)    | 1 (0.107) |     0.79 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4136 | 2024-02-19 | Apeks             | L   | 0.105      | -            | -                | -                | -         |    -2.04 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46,829.11)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-01 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.593 | $1,000.00      | $593.06         |
| 2024-04-20 |      0.514 | $10,000.00     | $5,143.52       |
| 2024-04-14 |      0.473 | $70,000.00     | $33,084.72      |
| 2024-03-10 |      0.241 | $12,500.00     | $3,007.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
