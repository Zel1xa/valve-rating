### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [81](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  928.7<br />
<br />
Final Rank Value (928.7) = Starting Rank Value (925.1) + Head To Head Adjustments (3.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.417[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.008[<sup>2</sup>](#table1)

The average of these factors is 0.255<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 925.1
- 400 + ( ( 0.255 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 925.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           64 |        4 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -23.86 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           63 |      107 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.072 (0.010)    | -                | 0 (0.000) |    18.06 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           62 |      332 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.22 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           61 |      348 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.28 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      355 | 2024-07-22 | Illuminar         | W   | 1.000      | 0.371        | -                | 0.376 (0.139)    | 0 (0.000) |    16.02 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      379 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -13.92 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           58 |      451 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    16.38 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           57 |      583 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.25 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      632 | 2024-07-16 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.76 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      688 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.23 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      728 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.59 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           53 |      809 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.20 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      903 | 2024-06-16 | 3DMAX             | L   | 0.893      | -            | -                | -                | -         |    -1.59 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |      982 | 2024-06-13 | PERA              | L   | 0.875      | -            | -                | -                | -         |   -12.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |      999 | 2024-06-13 | Illuminar         | W   | 0.873      | 0.450        | -                | 0.376 (0.148)    | 0 (0.000) |    12.66 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1022 | 2024-06-12 | Sampi             | W   | 0.868      | 0.379        | -                | 1.000 (0.329)    | 0 (0.000) |    11.23 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1065 | 2024-06-10 | SINNERS           | W   | 0.854      | 0.379        | 0.038 (0.012)    | 0.768 (0.249)    | -         |    16.39 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1081 | 2024-06-10 | Gaimin Gladiators | W   | 0.853      | 0.450        | 0.040 (0.015)    | -                | -         |    16.50 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1120 | 2024-06-09 | ECLOT             | L   | 0.847      | -            | -                | -                | -         |    -6.81 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1165 | 2024-06-08 | Nexus             | W   | 0.842      | 0.450        | -                | 0.504 (0.191)    | -         |     8.43 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1256 | 2024-06-07 | Entropiq          | W   | 0.833      | -            | -                | -                | -         |     1.52 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1312 | 2024-06-06 | Illuminar         | L   | 0.828      | -            | -                | -                | -         |   -15.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1359 | 2024-06-05 | Verdant           | L   | 0.822      | -            | -                | -                | -         |   -13.52 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1377 | 2024-06-05 | Serbia            | L   | 0.821      | -            | -                | -                | -         |   -17.07 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1434 | 2024-06-04 | Johnny Speeds     | W   | 0.812      | 0.371        | 0.124 (0.037)    | 0.818 (0.246)    | -         |    21.94 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1456 | 2024-06-03 | UNiTY             | W   | 0.806      | -            | -                | -                | -         |    14.21 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1498 | 2024-06-01 | ARCRED            | L   | 0.794      | -            | -                | -                | -         |   -13.57 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1514 | 2024-06-01 | Permitta          | W   | 0.792      | 0.371        | -                | 0.801 (0.235)    | -         |    12.18 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1552 | 2024-05-30 | RUSTEC            | W   | 0.782      | -            | -                | -                | -         |     1.37 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1568 | 2024-05-30 | brazylijski luz   | L   | 0.779      | -            | -                | -                | -         |   -13.95 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1581 | 2024-05-29 | FLuffy Gangsters  | W   | 0.775      | -            | -                | -                | -         |     2.99 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1607 | 2024-05-28 | Sampi             | W   | 0.767      | 0.379        | -                | 1.000 (0.291)    | -         |    12.15 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1690 | 2024-05-24 | Illuminar         | W   | 0.740      | -            | -                | -                | -         |    11.20 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           31 |     1740 | 2024-05-22 | Entropiq          | W   | 0.728      | -            | -                | -                | -         |     1.36 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           30 |     1846 | 2024-05-20 | ECSTATIC          | W   | 0.713      | -            | -                | -                | -         |     1.35 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     2189 | 2024-05-10 | BetBoom           | L   | 0.647      | -            | -                | -                | -         |    -1.17 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           28 |     2258 | 2024-05-07 | Permitta          | W   | 0.626      | 0.435        | -                | 0.801 (0.218)    | -         |    10.78 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2272 | 2024-05-06 | B8                | L   | 0.620      | -            | -                | -                | -         |    -5.65 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2300 | 2024-05-04 | MOUZ NXT          | W   | 0.608      | 0.435        | 0.141 (0.037)    | 1.000 (0.264)    | -         |    13.04 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2363 | 2024-05-01 | ENCE Academy      | W   | 0.588      | -            | -                | -                | -         |     5.60 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2392 | 2024-04-30 | EYEBALLERS        | L   | 0.581      | -            | -                | -                | -         |    -8.68 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           23 |     2428 | 2024-04-29 | Nexus             | L   | 0.572      | -            | -                | -                | -         |   -10.18 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2471 | 2024-04-27 | Permitta          | L   | 0.559      | -            | -                | -                | -         |    -7.30 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2488 | 2024-04-26 | Insilio           | L   | 0.554      | -            | -                | -                | -         |    -8.02 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2564 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.533      | -            | -                | -                | -         |    -7.66 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2633 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.512      | -            | -                | -                | -         |    -7.04 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2720 | 2024-04-18 | MOUZ NXT          | L   | 0.501      | -            | -                | -                | -         |    -4.85 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2732 | 2024-04-18 | Nexus             | W   | 0.499      | -            | -                | -                | -         |     6.76 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2759 | 2024-04-17 | ENCE              | L   | 0.493      | -            | -                | -                | -         |    -0.81 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2793 | 2024-04-16 | kONO              | L   | 0.487      | -            | -                | -                | -         |    -9.95 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2893 | 2024-04-11 | Sashi             | L   | 0.453      | -            | -                | -                | -         |    -3.48 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     2937 | 2024-04-10 | AMKAL             | W   | 0.446      | 0.384        | 0.132 (0.023)    | -                | -         |    10.78 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3067 | 2024-04-06 | Sampi             | L   | 0.419      | -            | -                | -                | -         |    -6.68 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3158 | 2024-04-03 | Permitta          | W   | 0.401      | -            | -                | -                | -         |     6.78 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3224 | 2024-04-01 | BLEED             | W   | 0.387      | 0.384        | 0.095 (0.014)    | -                | -         |     7.35 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3674 | 2024-03-09 | kONO              | L   | 0.234      | -            | -                | -                | -         |    -4.73 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3686 | 2024-03-09 | Sampi             | L   | 0.233      | -            | -                | -                | -         |    -3.98 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3754 | 2024-03-06 | INGLORIOUS        | L   | 0.214      | -            | -                | -                | -         |    -6.07 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3760 | 2024-03-06 | Permitta          | L   | 0.213      | -            | -                | -                | -         |    -3.24 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3876 | 2024-03-02 | Sampi             | W   | 0.186      | -            | -                | -                | -         |     2.64 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4197 | 2024-02-16 | SAW               | L   | 0.088      | -            | -                | -                | -         |    -0.54 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4234 | 2024-02-15 | BetBoom           | L   | 0.080      | -            | -                | -                | -         |    -0.14 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4261 | 2024-02-14 | Natus Vincere     | L   | 0.076      | -            | -                | -                | -         |    -0.01 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4273 | 2024-02-14 | AMKAL             | W   | 0.074      | -            | -                | -                | 1 (0.074) |     1.81 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,039.63)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.900 | $5,000.00      | $4,498.61       |
| 2024-06-13 |      0.875 | $5,447.00      | $4,767.13       |
| 2024-06-06 |      0.826 | $3,000.00      | $2,476.67       |
| 2024-05-02 |      0.594 | $500.00        | $297.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
