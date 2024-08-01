### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1053.3<br />
<br />
Final Rank Value (1053.3) = Starting Rank Value (1003.8) + Head To Head Adjustments (49.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.481[<sup>1</sup>](#table2)
- Bounty Collected: 0.410[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.050[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1003.8
- 400 + ( ( 0.293 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1003.8


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
|           55 |       77 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.53 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |       87 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.89 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      147 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.76 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      312 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.10 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |      558 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.38 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1074 | 2024-06-10 | Aurora            | L   | 0.854      | -            | -                | -                | -         |    -3.70 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1077 | 2024-06-10 | SINNERS           | W   | 0.853      | -            | -                | -                | 0 (0.000) |    12.23 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1082 | 2024-06-10 | 3DMAX             | L   | 0.853      | -            | -                | -                | -         |    -3.41 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1114 | 2024-06-09 | RUSH B            | L   | 0.847      | -            | -                | -                | -         |   -18.90 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1121 | 2024-06-09 | PARIVISION        | L   | 0.847      | -            | -                | -                | -         |   -13.14 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1129 | 2024-06-09 | SAW               | W   | 0.847      | 0.143        | 0.108 (0.013)    | -                | 0 (0.000) |    16.63 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1141 | 2024-06-09 | Monte             | W   | 0.846      | -            | -                | -                | 0 (0.000) |    11.25 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1418 | 2024-06-04 | Sangal            | L   | 0.815      | -            | -                | -                | -         |   -11.76 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           42 |     1645 | 2024-05-26 | MOUZ NXT          | W   | 0.754      | 0.435        | 0.141 (0.046)    | 1.000 (0.328)    | -         |    11.83 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1649 | 2024-05-26 | 1WIN              | W   | 0.754      | 0.435        | -                | 0.630 (0.206)    | -         |    10.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1663 | 2024-05-25 | Space             | W   | 0.748      | -            | -                | -                | -         |     6.56 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1689 | 2024-05-24 | SINNERS           | W   | 0.740      | 0.435        | 0.038 (0.012)    | 0.768 (0.247)    | -         |    11.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1836 | 2024-05-20 | BLEED             | L   | 0.714      | -            | -                | -                | -         |    -2.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     1898 | 2024-05-18 | Passion UA        | W   | 0.701      | 0.500        | 0.172 (0.060)    | 1.000 (0.350)    | -         |    10.82 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     1970 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.688      | 0.500        | -                | 0.564 (0.194)    | -         |     8.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2139 | 2024-05-12 | BetBoom           | L   | 0.660      | -            | -                | -                | -         |    -2.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2165 | 2024-05-11 | RUBY              | W   | 0.654      | 0.435        | 0.097 (0.027)    | 0.544 (0.155)    | -         |     8.72 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2212 | 2024-05-09 | Zero Tenacity     | W   | 0.640      | 0.435        | 0.139 (0.039)    | 1.000 (0.278)    | -         |    11.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2254 | 2024-05-07 | Sashi             | L   | 0.627      | -            | -                | -                | -         |    -4.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2299 | 2024-05-05 | ARCRED            | W   | 0.612      | -            | -                | -                | -         |     6.31 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2307 | 2024-05-04 | BetBoom           | L   | 0.607      | -            | -                | -                | -         |    -1.67 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2314 | 2024-05-03 | fnatic            | W   | 0.602      | 0.435        | 0.292 (0.076)    | 0.529 (0.138)    | -         |    16.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2359 | 2024-05-02 | MOUZ NXT          | W   | 0.592      | 0.435        | 0.141 (0.036)    | 1.000 (0.257)    | -         |    11.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2407 | 2024-04-30 | Passion UA        | L   | 0.579      | -            | -                | -                | -         |    -8.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2446 | 2024-04-28 | Gaimin Gladiators | W   | 0.566      | 0.500        | 0.040 (0.011)    | -                | -         |    10.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2485 | 2024-04-26 | Passion UA        | L   | 0.554      | -            | -                | -                | -         |    -7.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2682 | 2024-04-19 | Alliance          | L   | 0.506      | -            | -                | -                | -         |   -10.73 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2777 | 2024-04-17 | Sangal            | L   | 0.492      | -            | -                | -                | -         |    -4.96 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2919 | 2024-04-10 | SAW               | L   | 0.448      | -            | -                | -                | -         |    -3.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     2975 | 2024-04-09 | SINNERS           | L   | 0.442      | -            | -                | -                | -         |    -5.64 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     2995 | 2024-04-09 | Aurora            | L   | 0.440      | -            | -                | -                | -         |    -0.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3008 | 2024-04-08 | 1WIN              | L   | 0.435      | -            | -                | -                | -         |    -8.82 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3016 | 2024-04-08 | Metizport         | W   | 0.434      | -            | -                | -                | -         |     5.86 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3079 | 2024-04-05 | Secret            | L   | 0.413      | -            | -                | -                | -         |   -12.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3109 | 2024-04-04 | TSM               | W   | 0.408      | -            | -                | -                | -         |     1.70 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3157 | 2024-04-03 | EYEBALLERS        | W   | 0.401      | -            | -                | -                | -         |     4.49 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3168 | 2024-04-03 | 9INE              | W   | 0.400      | -            | -                | -                | -         |     0.76 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3201 | 2024-04-02 | Sangal            | W   | 0.395      | 0.500        | 0.221 (0.044)    | 0.823 (0.162)    | -         |     8.21 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3744 | 2024-03-06 | KOI               | L   | 0.215      | -            | -                | -                | -         |    -3.98 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3889 | 2024-03-01 | Aurora            | L   | 0.181      | -            | -                | -                | -         |    -0.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3896 | 2024-02-29 | FORZE             | L   | 0.175      | -            | -                | -                | -         |    -3.53 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3909 | 2024-02-28 | Spirit Academy    | W   | 0.168      | -            | -                | -                | -         |     0.38 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3915 | 2024-02-28 | Croatia           | W   | 0.167      | -            | -                | -                | -         |     0.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4012 | 2024-02-24 | GamerLegion       | W   | 0.141      | -            | -                | -                | 1 (0.141) |     1.06 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4031 | 2024-02-23 | Astralis          | W   | 0.133      | -            | -                | -                | 1 (0.133) |     4.10 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4181 | 2024-02-17 | AMKAL             | L   | 0.093      | -            | -                | -                | -         |    -0.90 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4205 | 2024-02-16 | 3DMAX             | W   | 0.087      | -            | -                | -                | 1 (0.087) |     2.69 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4236 | 2024-02-15 | KOI               | L   | 0.080      | -            | -                | -                | -         |    -1.49 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4270 | 2024-02-14 | SAW               | W   | 0.074      | -            | -                | -                | 1 (0.074) |     1.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4282 | 2024-02-14 | FaZe              | L   | 0.073      | -            | -                | -                | -         |    -0.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,181.81)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.848 | $5,000.00      | $4,238.54       |
| 2024-05-26 |      0.754 | $22,000.00     | $16,597.78      |
| 2024-05-12 |      0.661 | $5,000.00      | $3,306.60       |
| 2024-05-04 |      0.608 | $5,000.00      | $3,038.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
