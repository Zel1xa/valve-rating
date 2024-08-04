### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1078.1<br />
<br />
Final Rank Value (1078.1) = Starting Rank Value (998.3) + Head To Head Adjustments (79.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.479[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.240[<sup>2</sup>](#table1)
- LAN Wins: 0.040[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 998.3
- 400 + ( ( 0.293 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 998.3


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
|           61 |       15 | 2024-08-04 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.41 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           60 |       44 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.42 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           59 |       72 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.537 (0.229)    | 0 (0.000) |    10.42 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |       85 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.84 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |      105 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.41 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |      198 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.44 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      208 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.90 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      267 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.76 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      432 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | -         |     4.20 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      672 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.15 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1186 | 2024-06-10 | Aurora            | L   | 0.832      | -            | -                | -                | -         |    -3.50 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1189 | 2024-06-10 | SINNERS           | W   | 0.832      | -            | -                | -                | -         |    12.83 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1194 | 2024-06-10 | 3DMAX             | L   | 0.832      | -            | -                | -                | -         |    -3.13 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1226 | 2024-06-09 | RUSH B            | L   | 0.826      | -            | -                | -                | -         |   -17.96 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1233 | 2024-06-09 | PARIVISION        | L   | 0.826      | -            | -                | -                | -         |   -12.67 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1241 | 2024-06-09 | SAW               | W   | 0.825      | 0.143        | 0.105 (0.012)    | -                | -         |    16.24 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1252 | 2024-06-09 | Monte             | W   | 0.825      | -            | -                | -                | -         |    11.31 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1516 | 2024-06-04 | Sangal            | L   | 0.793      | -            | -                | -                | -         |   -10.42 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1740 | 2024-05-26 | MOUZ NXT          | W   | 0.733      | 0.435        | 0.139 (0.044)    | 1.000 (0.319)    | -         |    11.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1744 | 2024-05-26 | 1WIN              | W   | 0.732      | 0.435        | -                | 0.707 (0.225)    | -         |    10.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1758 | 2024-05-25 | Space             | W   | 0.727      | -            | -                | -                | -         |     6.23 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1784 | 2024-05-24 | SINNERS           | W   | 0.718      | 0.435        | 0.037 (0.012)    | 0.797 (0.249)    | -         |    12.45 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1913 | 2024-05-20 | BLEED             | L   | 0.693      | -            | -                | -                | -         |    -2.68 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1968 | 2024-05-18 | Passion UA        | W   | 0.680      | 0.500        | 0.172 (0.059)    | 1.000 (0.340)    | -         |    10.86 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     2039 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.666      | 0.500        | 0.031 (0.010)    | 0.560 (0.187)    | -         |     8.88 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2199 | 2024-05-12 | BetBoom           | L   | 0.639      | -            | -                | -                | -         |    -2.21 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2225 | 2024-05-11 | RUBY              | W   | 0.633      | 0.435        | 0.095 (0.026)    | -                | -         |     8.23 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2272 | 2024-05-09 | Zero Tenacity     | W   | 0.619      | 0.435        | 0.137 (0.037)    | 1.000 (0.269)    | -         |    11.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2312 | 2024-05-07 | Sashi             | L   | 0.606      | -            | -                | -                | -         |    -4.53 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2357 | 2024-05-05 | ARCRED            | W   | 0.591      | -            | -                | -                | -         |     6.39 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2365 | 2024-05-04 | BetBoom           | L   | 0.586      | -            | -                | -                | -         |    -1.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2372 | 2024-05-03 | fnatic            | W   | 0.580      | 0.435        | 0.371 (0.094)    | 0.708 (0.179)    | -         |    17.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2416 | 2024-05-02 | MOUZ NXT          | W   | 0.571      | 0.435        | 0.139 (0.034)    | 1.000 (0.248)    | -         |    11.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2462 | 2024-04-30 | Passion UA        | L   | 0.558      | -            | -                | -                | -         |    -7.57 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2501 | 2024-04-28 | Gaimin Gladiators | W   | 0.545      | -            | -                | -                | -         |     9.72 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2539 | 2024-04-26 | Passion UA        | L   | 0.533      | -            | -                | -                | -         |    -7.45 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2540 | 2024-04-26 | Passion UA        | L   | 0.533      | -            | -                | -                | -         |    -7.11 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2730 | 2024-04-19 | Alliance          | L   | 0.485      | -            | -                | -                | -         |   -10.29 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2823 | 2024-04-17 | Sangal            | L   | 0.471      | -            | -                | -                | -         |    -4.51 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2963 | 2024-04-10 | SAW               | L   | 0.427      | -            | -                | -                | -         |    -3.54 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     3019 | 2024-04-09 | SINNERS           | L   | 0.420      | -            | -                | -                | -         |    -3.96 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3039 | 2024-04-09 | Aurora            | L   | 0.418      | -            | -                | -                | -         |    -0.33 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3052 | 2024-04-08 | 1WIN              | L   | 0.413      | -            | -                | -                | -         |    -7.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3060 | 2024-04-08 | Metizport         | W   | 0.413      | -            | -                | -                | -         |     4.63 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3123 | 2024-04-05 | Secret            | L   | 0.392      | -            | -                | -                | -         |   -11.54 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3153 | 2024-04-04 | TSM               | W   | 0.387      | -            | -                | -                | -         |     1.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3199 | 2024-04-03 | EYEBALLERS        | W   | 0.380      | -            | -                | -                | -         |     4.24 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3206 | 2024-04-03 | 9INE              | W   | 0.379      | -            | -                | -                | -         |     0.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3237 | 2024-04-02 | Sangal            | W   | 0.373      | 0.500        | 0.219 (0.041)    | 0.861 (0.161)    | -         |     8.02 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3769 | 2024-03-06 | KOI               | L   | 0.194      | -            | -                | -                | -         |    -2.33 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3908 | 2024-03-01 | Aurora            | L   | 0.159      | -            | -                | -                | -         |    -0.12 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3915 | 2024-02-29 | FORZE             | L   | 0.154      | -            | -                | -                | -         |    -3.14 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3928 | 2024-02-28 | Spirit Academy    | W   | 0.147      | -            | -                | -                | -         |     0.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3933 | 2024-02-28 | Croatia           | W   | 0.146      | -            | -                | -                | -         |     0.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4026 | 2024-02-24 | GamerLegion       | W   | 0.119      | -            | -                | -                | 1 (0.119) |     0.84 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4043 | 2024-02-23 | Astralis          | W   | 0.112      | -            | -                | -                | 1 (0.112) |     3.46 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4192 | 2024-02-17 | AMKAL             | L   | 0.072      | -            | -                | -                | -         |    -0.69 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4215 | 2024-02-16 | 3DMAX             | W   | 0.066      | -            | -                | -                | 1 (0.066) |     2.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4246 | 2024-02-15 | KOI               | L   | 0.058      | -            | -                | -                | -         |    -0.70 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4280 | 2024-02-14 | SAW               | W   | 0.053      | -            | -                | -                | 1 (0.053) |     1.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4292 | 2024-02-14 | FaZe              | L   | 0.052      | -            | -                | -                | -         |    -0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,396.41)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.826 | $5,000.00      | $4,132.41       |
| 2024-05-26 |      0.733 | $22,000.00     | $16,130.79      |
| 2024-05-12 |      0.640 | $5,000.00      | $3,200.46       |
| 2024-05-04 |      0.587 | $5,000.00      | $2,932.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
