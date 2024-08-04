### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1076.8<br />
<br />
Final Rank Value (1076.8) = Starting Rank Value (998.1) + Head To Head Adjustments (78.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.479[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.240[<sup>2</sup>](#table1)
- LAN Wins: 0.041[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 998.1
- 400 + ( ( 0.293 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 998.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           61 |        3 | 2024-08-04 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.76 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           60 |       22 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.46 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           59 |       50 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.537 (0.229)    | 0 (0.000) |    10.48 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |       63 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.88 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |       83 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.43 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |      174 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.41 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      184 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.15 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      243 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.77 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      407 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | -         |     4.24 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      645 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.14 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1162 | 2024-06-10 | Aurora            | L   | 0.833      | -            | -                | -                | -         |    -3.49 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1165 | 2024-06-10 | SINNERS           | W   | 0.833      | -            | -                | -                | -         |    12.24 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1170 | 2024-06-10 | 3DMAX             | L   | 0.833      | -            | -                | -                | -         |    -3.13 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1202 | 2024-06-09 | RUSH B            | L   | 0.827      | -            | -                | -                | -         |   -17.99 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1209 | 2024-06-09 | PARIVISION        | L   | 0.827      | -            | -                | -                | -         |   -12.71 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1217 | 2024-06-09 | SAW               | W   | 0.826      | 0.143        | 0.105 (0.012)    | -                | -         |    16.29 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1228 | 2024-06-09 | Monte             | W   | 0.826      | -            | -                | -                | -         |    11.37 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1492 | 2024-06-04 | Sangal            | L   | 0.795      | -            | -                | -                | -         |   -10.47 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1716 | 2024-05-26 | MOUZ NXT          | W   | 0.734      | 0.435        | 0.139 (0.044)    | 1.000 (0.319)    | -         |    11.78 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1720 | 2024-05-26 | 1WIN              | W   | 0.733      | 0.435        | -                | 0.707 (0.225)    | -         |    10.57 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1734 | 2024-05-25 | Space             | W   | 0.728      | -            | -                | -                | -         |     6.45 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1760 | 2024-05-24 | SINNERS           | W   | 0.720      | 0.435        | 0.037 (0.012)    | 0.757 (0.237)    | -         |    11.48 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1889 | 2024-05-20 | BLEED             | L   | 0.694      | -            | -                | -                | -         |    -2.69 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1944 | 2024-05-18 | Passion UA        | W   | 0.681      | 0.500        | 0.172 (0.059)    | 1.000 (0.340)    | -         |    10.78 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     2015 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.667      | 0.500        | 0.031 (0.011)    | 0.560 (0.187)    | -         |     8.86 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2175 | 2024-05-12 | BetBoom           | L   | 0.640      | -            | -                | -                | -         |    -2.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2201 | 2024-05-11 | RUBY              | W   | 0.634      | 0.435        | 0.095 (0.026)    | -                | -         |     8.36 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2248 | 2024-05-09 | Zero Tenacity     | W   | 0.620      | 0.435        | 0.137 (0.037)    | 1.000 (0.269)    | -         |    11.15 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2288 | 2024-05-07 | Sashi             | L   | 0.607      | -            | -                | -                | -         |    -4.54 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2333 | 2024-05-05 | ARCRED            | W   | 0.592      | -            | -                | -                | -         |     6.42 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2341 | 2024-05-04 | BetBoom           | L   | 0.587      | -            | -                | -                | -         |    -1.62 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2348 | 2024-05-03 | fnatic            | W   | 0.582      | 0.435        | 0.371 (0.094)    | 0.708 (0.179)    | -         |    17.37 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2392 | 2024-05-02 | MOUZ NXT          | W   | 0.572      | 0.435        | 0.139 (0.035)    | 1.000 (0.249)    | -         |    11.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2438 | 2024-04-30 | Passion UA        | L   | 0.559      | -            | -                | -                | -         |    -7.63 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2477 | 2024-04-28 | Gaimin Gladiators | W   | 0.546      | -            | -                | -                | -         |     9.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2515 | 2024-04-26 | Passion UA        | L   | 0.534      | -            | -                | -                | -         |    -7.52 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2516 | 2024-04-26 | Passion UA        | L   | 0.534      | -            | -                | -                | -         |    -7.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2706 | 2024-04-19 | Alliance          | L   | 0.486      | -            | -                | -                | -         |   -10.33 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2799 | 2024-04-17 | Sangal            | L   | 0.472      | -            | -                | -                | -         |    -4.58 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2939 | 2024-04-10 | SAW               | L   | 0.428      | -            | -                | -                | -         |    -3.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     2995 | 2024-04-09 | SINNERS           | L   | 0.422      | -            | -                | -                | -         |    -4.84 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3015 | 2024-04-09 | Aurora            | L   | 0.420      | -            | -                | -                | -         |    -0.33 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3028 | 2024-04-08 | 1WIN              | L   | 0.415      | -            | -                | -                | -         |    -7.99 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3036 | 2024-04-08 | Metizport         | W   | 0.414      | -            | -                | -                | -         |     5.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3099 | 2024-04-05 | Secret            | L   | 0.393      | -            | -                | -                | -         |   -11.57 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3129 | 2024-04-04 | TSM               | W   | 0.388      | -            | -                | -                | -         |     1.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3175 | 2024-04-03 | EYEBALLERS        | W   | 0.381      | -            | -                | -                | -         |     4.26 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3182 | 2024-04-03 | 9INE              | W   | 0.380      | -            | -                | -                | -         |     0.74 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3213 | 2024-04-02 | Sangal            | W   | 0.375      | 0.500        | 0.219 (0.041)    | 0.861 (0.161)    | -         |     7.99 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3745 | 2024-03-06 | KOI               | L   | 0.195      | -            | -                | -                | -         |    -2.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3884 | 2024-03-01 | Aurora            | L   | 0.161      | -            | -                | -                | -         |    -0.12 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3891 | 2024-02-29 | FORZE             | L   | 0.155      | -            | -                | -                | -         |    -3.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3904 | 2024-02-28 | Spirit Academy    | W   | 0.148      | -            | -                | -                | -         |     0.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3909 | 2024-02-28 | Croatia           | W   | 0.147      | -            | -                | -                | -         |     0.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4002 | 2024-02-24 | GamerLegion       | W   | 0.120      | -            | -                | -                | 1 (0.120) |     0.85 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4019 | 2024-02-23 | Astralis          | W   | 0.113      | -            | -                | -                | 1 (0.113) |     3.50 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4168 | 2024-02-17 | AMKAL             | L   | 0.073      | -            | -                | -                | -         |    -0.70 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4191 | 2024-02-16 | 3DMAX             | W   | 0.067      | -            | -                | -                | 1 (0.067) |     2.07 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4222 | 2024-02-15 | KOI               | L   | 0.060      | -            | -                | -                | -         |    -0.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4256 | 2024-02-14 | SAW               | W   | 0.054      | -            | -                | -                | 1 (0.054) |     1.23 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4268 | 2024-02-14 | FaZe              | L   | 0.053      | -            | -                | -                | -         |    -0.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,435.81)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $5,000.00      | $4,137.73       |
| 2024-05-26 |      0.734 | $22,000.00     | $16,154.21      |
| 2024-05-12 |      0.641 | $5,000.00      | $3,205.79       |
| 2024-05-04 |      0.588 | $5,000.00      | $2,938.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
