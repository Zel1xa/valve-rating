### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  941.5<br />
<br />
Final Rank Value (941.5) = Starting Rank Value (917.6) + Head To Head Adjustments (23.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.229[<sup>2</sup>](#table1)
- LAN Wins: 0.007[<sup>2</sup>](#table1)

The average of these factors is 0.253<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 917.6
- 400 + ( ( 0.253 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 917.6


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
|           61 |      191 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    18.09 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      417 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.78 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      432 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      439 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.85 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      462 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.68 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      531 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    17.55 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      659 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.05 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      756 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.24 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      795 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.85 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      876 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.10 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |      972 | 2024-06-16 | 3DMAX             | L   | 0.876      | -            | -                | -                | -         |    -1.55 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1060 | 2024-06-13 | PERA              | L   | 0.859      | -            | -                | -                | -         |   -12.22 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1077 | 2024-06-13 | Illuminar         | W   | 0.857      | 0.450        | -                | 0.351 (0.135)    | 0 (0.000) |    11.68 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1100 | 2024-06-12 | Sampi             | W   | 0.851      | 0.379        | 0.027 (0.009)    | 1.000 (0.322)    | 0 (0.000) |    11.08 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1141 | 2024-06-10 | SINNERS           | W   | 0.838      | 0.379        | 0.037 (0.012)    | 0.758 (0.240)    | 0 (0.000) |    16.15 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1157 | 2024-06-10 | Gaimin Gladiators | W   | 0.836      | 0.450        | 0.038 (0.014)    | 0.353 (0.133)    | -         |    15.72 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1196 | 2024-06-09 | ECLOT             | L   | 0.831      | -            | -                | -                | -         |    -5.11 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1239 | 2024-06-08 | Nexus             | W   | 0.825      | 0.450        | -                | 0.465 (0.173)    | -         |     8.17 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1323 | 2024-06-07 | Entropiq          | W   | 0.817      | -            | -                | -                | -         |     1.50 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1377 | 2024-06-06 | Illuminar         | L   | 0.811      | -            | -                | -                | -         |   -15.94 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1422 | 2024-06-05 | Verdant           | L   | 0.805      | -            | -                | -                | -         |   -13.51 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1439 | 2024-06-05 | Serbia            | L   | 0.804      | -            | -                | -                | -         |   -16.90 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1496 | 2024-06-04 | Johnny Speeds     | W   | 0.796      | 0.371        | 0.122 (0.036)    | 0.901 (0.266)    | -         |    21.38 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1518 | 2024-06-03 | UNiTY             | W   | 0.789      | -            | -                | -                | -         |    14.04 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1560 | 2024-06-01 | ARCRED            | L   | 0.778      | -            | -                | -                | -         |   -13.18 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1575 | 2024-06-01 | Permitta          | W   | 0.776      | 0.371        | -                | 0.876 (0.252)    | -         |    11.97 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1613 | 2024-05-30 | RUSTEC            | W   | 0.765      | -            | -                | -                | -         |     1.34 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1629 | 2024-05-30 | brazylijski luz   | L   | 0.762      | -            | -                | -                | -         |   -14.52 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1642 | 2024-05-29 | FLuffy Gangsters  | W   | 0.759      | -            | -                | -                | -         |     2.90 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1668 | 2024-05-28 | Sampi             | W   | 0.751      | 0.379        | -                | 1.000 (0.284)    | -         |    11.91 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1749 | 2024-05-24 | Illuminar         | W   | 0.723      | -            | -                | -                | -         |    10.08 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1799 | 2024-05-22 | Entropiq          | W   | 0.711      | -            | -                | -                | -         |     1.32 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1885 | 2024-05-20 | ECSTATIC          | W   | 0.697      | -            | -                | -                | -         |     1.30 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2213 | 2024-05-10 | BetBoom           | L   | 0.630      | -            | -                | -                | -         |    -1.20 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2280 | 2024-05-07 | Permitta          | W   | 0.610      | 0.435        | -                | 0.876 (0.232)    | -         |    10.47 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2294 | 2024-05-06 | B8                | L   | 0.604      | -            | -                | -                | -         |    -5.55 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2322 | 2024-05-04 | MOUZ NXT          | W   | 0.592      | 0.435        | 0.139 (0.036)    | 1.000 (0.257)    | -         |    13.05 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2383 | 2024-05-01 | ENCE Academy      | W   | 0.572      | -            | -                | -                | -         |     5.47 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2411 | 2024-04-30 | EYEBALLERS        | L   | 0.565      | -            | -                | -                | -         |    -8.61 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2447 | 2024-04-29 | Nexus             | L   | 0.556      | -            | -                | -                | -         |   -10.09 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2489 | 2024-04-27 | Permitta          | L   | 0.543      | -            | -                | -                | -         |    -7.28 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2506 | 2024-04-26 | Insilio           | L   | 0.537      | -            | -                | -                | -         |    -8.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2580 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.516      | -            | -                | -                | -         |    -7.52 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2645 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.496      | -            | -                | -                | -         |    -6.90 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2730 | 2024-04-18 | MOUZ NXT          | L   | 0.484      | -            | -                | -                | -         |    -5.05 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2742 | 2024-04-18 | Nexus             | W   | 0.483      | -            | -                | -                | -         |     6.34 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2768 | 2024-04-17 | ENCE              | L   | 0.477      | -            | -                | -                | -         |    -0.84 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2900 | 2024-04-11 | Sashi             | L   | 0.436      | -            | -                | -                | -         |    -3.34 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     2944 | 2024-04-10 | AMKAL             | W   | 0.430      | 0.384        | 0.130 (0.021)    | -                | -         |    10.42 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3074 | 2024-04-06 | Sampi             | L   | 0.403      | -            | -                | -                | -         |    -6.42 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3163 | 2024-04-03 | Permitta          | W   | 0.385      | -            | -                | -                | -         |     6.74 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3223 | 2024-04-01 | BLEED             | W   | 0.371      | 0.384        | 0.092 (0.013)    | -                | -         |     7.01 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3661 | 2024-03-09 | kONO              | L   | 0.218      | -            | -                | -                | -         |    -4.42 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3673 | 2024-03-09 | Sampi             | L   | 0.217      | -            | -                | -                | -         |    -3.69 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3741 | 2024-03-06 | INGLORIOUS        | L   | 0.198      | -            | -                | -                | -         |    -5.59 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3747 | 2024-03-06 | Permitta          | L   | 0.197      | -            | -                | -                | -         |    -2.87 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3858 | 2024-03-02 | Sampi             | W   | 0.169      | -            | -                | -                | -         |     2.42 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4168 | 2024-02-16 | SAW               | L   | 0.072      | -            | -                | -                | -         |    -0.46 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4205 | 2024-02-15 | BetBoom           | L   | 0.064      | -            | -                | -                | -         |    -0.11 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4232 | 2024-02-14 | Natus Vincere     | L   | 0.059      | -            | -                | -                | -         |    -0.01 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4244 | 2024-02-14 | AMKAL             | W   | 0.057      | -            | -                | -                | 1 (0.057) |     1.41 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,811.06)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.883 | $5,000.00      | $4,416.67       |
| 2024-06-13 |      0.859 | $5,447.00      | $4,677.86       |
| 2024-06-06 |      0.809 | $3,000.00      | $2,427.50       |
| 2024-05-02 |      0.578 | $500.00        | $289.03         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
