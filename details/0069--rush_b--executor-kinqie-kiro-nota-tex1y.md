### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [69](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  952.7<br />
<br />
Final Rank Value (952.7) = Starting Rank Value (845.8) + Head To Head Adjustments (106.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.360[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.150[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.218<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 845.8
- 400 + ( ( 0.218 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 845.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |       21 | 2024-08-03 | Alliance        | W   | 1.000      | 0.342        | 0.017 (0.006)    | 0.300 (0.103)    | 0 (0.000) |    11.85 | executor, kinqie, Kiro, nota, tex1y |
|           29 |       59 | 2024-08-02 | Astralis Talent | W   | 1.000      | 0.342        | -                | 0.162 (0.056)    | 0 (0.000) |     6.83 | executor, kinqie, Kiro, nota, tex1y |
|           28 |      168 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.599 (0.300)    | 0 (0.000) |    19.94 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      398 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.037 (0.019)    | 0.758 (0.379)    | 0 (0.000) |    18.48 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      522 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.09 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      638 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -18.65 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      740 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.20 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1152 | 2024-06-10 | PARIVISION      | L   | 0.834      | -            | -                | -                | -         |    -8.03 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1160 | 2024-06-10 | SAW             | L   | 0.834      | -            | -                | -                | -         |    -5.60 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1165 | 2024-06-10 | Monte           | W   | 0.833      | 0.143        | 0.080 (0.010)    | 0.618 (0.074)    | 0 (0.000) |    16.57 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1194 | 2024-06-09 | 9 Pandas        | W   | 0.828      | 0.143        | 0.082 (0.010)    | 0.690 (0.082)    | 0 (0.000) |    18.27 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1203 | 2024-06-09 | Aurora          | W   | 0.828      | 0.143        | 0.424 (0.050)    | 0.793 (0.094)    | 0 (0.000) |    24.97 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1210 | 2024-06-09 | SINNERS         | W   | 0.827      | 0.143        | 0.037 (0.004)    | 0.758 (0.090)    | 0 (0.000) |    18.01 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1221 | 2024-06-09 | 3DMAX           | L   | 0.827      | -            | -                | -                | -         |    -0.85 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1372 | 2024-06-06 | Aurora          | L   | 0.809      | -            | -                | -                | -         |    -0.65 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1435 | 2024-06-05 | SINNERS         | L   | 0.802      | -            | -                | -                | -         |    -8.23 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1483 | 2024-06-04 | SAW             | W   | 0.795      | 0.500        | 0.105 (0.042)    | 0.540 (0.215)    | 0 (0.000) |    21.68 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2281 | 2024-05-07 | MOUZ NXT        | L   | 0.608      | -            | -                | -                | -         |    -5.23 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2310 | 2024-05-05 | Sampi           | L   | 0.595      | -            | -                | -                | -         |    -7.77 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2331 | 2024-05-04 | HAVU            | W   | 0.588      | -            | -                | -                | 0 (0.000) |     5.55 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2376 | 2024-05-02 | EYEBALLERS      | L   | 0.574      | -            | -                | -                | -         |    -8.18 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2433 | 2024-04-29 | ENCE Academy    | W   | 0.556      | -            | -                | -                | -         |     5.46 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     2936 | 2024-04-10 | KOI             | L   | 0.429      | -            | -                | -                | -         |    -3.08 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     2990 | 2024-04-09 | PARIVISION      | W   | 0.422      | 0.500        | 0.017 (0.004)    | 0.534 (0.113)    | -         |    10.52 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3225 | 2024-04-01 | PERA            | L   | 0.368      | -            | -                | -                | -         |    -4.90 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3234 | 2024-03-31 | Monte           | W   | 0.362      | 0.500        | 0.059 (0.011)    | -                | -         |     7.80 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3246 | 2024-03-29 | System5         | W   | 0.349      | -            | -                | -                | -         |     3.06 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3563 | 2024-03-13 | Betera          | W   | 0.242      | -            | -                | -                | -         |     2.31 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3828 | 2024-03-03 | Metizport       | L   | 0.175      | -            | -                | -                | -         |    -2.32 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     3939 | 2024-02-26 | SAW             | L   | 0.136      | -            | -                | -                | -         |    -0.61 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,383.72)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
