### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1075.0<br />
<br />
Final Rank Value (1075.0) = Starting Rank Value (997.1) + Head To Head Adjustments (77.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.479[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.237[<sup>2</sup>](#table1)
- LAN Wins: 0.041[<sup>2</sup>](#table1)

The average of these factors is 0.292<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 997.1
- 400 + ( ( 0.292 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 997.1


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
|           61 |        0 | 2024-08-04 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.73 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           60 |       14 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.19 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           59 |       42 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.537 (0.229)    | 0 (0.000) |    10.46 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |       56 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.91 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |       75 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.41 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |      166 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.41 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      176 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.14 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      235 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.77 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      399 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | -         |     4.27 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      637 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.13 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1154 | 2024-06-10 | Aurora            | L   | 0.834      | -            | -                | -                | -         |    -3.50 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1157 | 2024-06-10 | SINNERS           | W   | 0.834      | -            | -                | -                | -         |    12.26 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1162 | 2024-06-10 | 3DMAX             | L   | 0.833      | -            | -                | -                | -         |    -3.13 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1194 | 2024-06-09 | RUSH B            | L   | 0.828      | -            | -                | -                | -         |   -18.27 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1201 | 2024-06-09 | PARIVISION        | L   | 0.828      | -            | -                | -                | -         |   -12.68 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1209 | 2024-06-09 | SAW               | W   | 0.827      | 0.143        | 0.105 (0.012)    | -                | -         |    16.30 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1220 | 2024-06-09 | Monte             | W   | 0.827      | -            | -                | -                | -         |    11.40 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1484 | 2024-06-04 | Sangal            | L   | 0.795      | -            | -                | -                | -         |   -10.47 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1708 | 2024-05-26 | MOUZ NXT          | W   | 0.735      | 0.435        | 0.139 (0.044)    | 1.000 (0.319)    | -         |    11.81 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1712 | 2024-05-26 | 1WIN              | W   | 0.734      | 0.435        | -                | 0.628 (0.200)    | -         |    10.10 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1726 | 2024-05-25 | Space             | W   | 0.729      | -            | -                | -                | -         |     6.48 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1752 | 2024-05-24 | SINNERS           | W   | 0.720      | 0.435        | 0.037 (0.012)    | 0.758 (0.237)    | -         |    11.49 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1881 | 2024-05-20 | BLEED             | L   | 0.695      | -            | -                | -                | -         |    -2.69 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1936 | 2024-05-18 | Passion UA        | W   | 0.681      | 0.500        | 0.172 (0.059)    | 1.000 (0.341)    | -         |    10.80 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     2007 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.668      | 0.500        | 0.031 (0.011)    | 0.560 (0.187)    | -         |     8.88 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2167 | 2024-05-12 | BetBoom           | L   | 0.641      | -            | -                | -                | -         |    -2.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2193 | 2024-05-11 | RUBY              | W   | 0.635      | 0.435        | 0.095 (0.026)    | -                | -         |     8.40 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2240 | 2024-05-09 | Zero Tenacity     | W   | 0.621      | 0.435        | 0.137 (0.037)    | 1.000 (0.270)    | -         |    11.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2280 | 2024-05-07 | Sashi             | L   | 0.608      | -            | -                | -                | -         |    -4.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2325 | 2024-05-05 | ARCRED            | W   | 0.593      | -            | -                | -                | -         |     6.45 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2333 | 2024-05-04 | BetBoom           | L   | 0.588      | -            | -                | -                | -         |    -1.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2340 | 2024-05-03 | fnatic            | W   | 0.582      | 0.435        | 0.371 (0.094)    | 0.708 (0.179)    | -         |    17.39 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2384 | 2024-05-02 | MOUZ NXT          | W   | 0.573      | 0.435        | 0.139 (0.035)    | 1.000 (0.249)    | -         |    11.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2430 | 2024-04-30 | Passion UA        | L   | 0.560      | -            | -                | -                | -         |    -7.64 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2469 | 2024-04-28 | Gaimin Gladiators | W   | 0.546      | -            | -                | -                | -         |     9.74 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2507 | 2024-04-26 | Passion UA        | L   | 0.535      | -            | -                | -                | -         |    -7.52 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2508 | 2024-04-26 | Passion UA        | L   | 0.535      | -            | -                | -                | -         |    -7.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2698 | 2024-04-19 | Alliance          | L   | 0.486      | -            | -                | -                | -         |   -10.32 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2791 | 2024-04-17 | Sangal            | L   | 0.473      | -            | -                | -                | -         |    -4.58 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2931 | 2024-04-10 | SAW               | L   | 0.429      | -            | -                | -                | -         |    -3.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     2987 | 2024-04-09 | SINNERS           | L   | 0.422      | -            | -                | -                | -         |    -4.82 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3007 | 2024-04-09 | Aurora            | L   | 0.420      | -            | -                | -                | -         |    -0.33 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3020 | 2024-04-08 | 1WIN              | L   | 0.415      | -            | -                | -                | -         |    -8.40 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3028 | 2024-04-08 | Metizport         | W   | 0.414      | -            | -                | -                | -         |     5.62 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3091 | 2024-04-05 | Secret            | L   | 0.394      | -            | -                | -                | -         |   -11.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3121 | 2024-04-04 | TSM               | W   | 0.389      | -            | -                | -                | -         |     1.62 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3167 | 2024-04-03 | EYEBALLERS        | W   | 0.382      | -            | -                | -                | -         |     4.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3174 | 2024-04-03 | 9INE              | W   | 0.381      | -            | -                | -                | -         |     0.74 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3205 | 2024-04-02 | Sangal            | W   | 0.375      | 0.500        | 0.219 (0.041)    | 0.862 (0.162)    | -         |     8.01 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3737 | 2024-03-06 | KOI               | L   | 0.196      | -            | -                | -                | -         |    -2.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3876 | 2024-03-01 | Aurora            | L   | 0.161      | -            | -                | -                | -         |    -0.12 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3883 | 2024-02-29 | FORZE             | L   | 0.156      | -            | -                | -                | -         |    -3.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3896 | 2024-02-28 | Spirit Academy    | W   | 0.149      | -            | -                | -                | -         |     0.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3901 | 2024-02-28 | Croatia           | W   | 0.148      | -            | -                | -                | -         |     0.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     3994 | 2024-02-24 | GamerLegion       | W   | 0.121      | -            | -                | -                | 1 (0.121) |     0.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4011 | 2024-02-23 | Astralis          | W   | 0.114      | -            | -                | -                | 1 (0.114) |     3.50 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4160 | 2024-02-17 | AMKAL             | L   | 0.074      | -            | -                | -                | -         |    -0.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4183 | 2024-02-16 | 3DMAX             | W   | 0.068      | -            | -                | -                | 1 (0.068) |     2.09 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4214 | 2024-02-15 | KOI               | L   | 0.060      | -            | -                | -                | -         |    -0.72 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4248 | 2024-02-14 | SAW               | W   | 0.055      | -            | -                | -                | 1 (0.055) |     1.24 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4260 | 2024-02-14 | FaZe              | L   | 0.054      | -            | -                | -                | -         |    -0.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,462.36)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $5,000.00      | $4,141.32       |
| 2024-05-26 |      0.735 | $22,000.00     | $16,170.00      |
| 2024-05-12 |      0.642 | $5,000.00      | $3,209.38       |
| 2024-05-04 |      0.588 | $5,000.00      | $2,941.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
