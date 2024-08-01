### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [81](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  928.4<br />
<br />
Final Rank Value (928.4) = Starting Rank Value (924.2) + Head To Head Adjustments (4.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.417[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.008[<sup>2</sup>](#table1)

The average of these factors is 0.255<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 924.2
- 400 + ( ( 0.255 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 924.2


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
|           64 |        8 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -23.32 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           63 |      111 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.072 (0.010)    | -                | 0 (0.000) |    18.06 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           62 |      336 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.22 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           61 |      352 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.29 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      359 | 2024-07-22 | Illuminar         | W   | 1.000      | 0.371        | -                | 0.376 (0.139)    | 0 (0.000) |    16.02 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      383 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -13.91 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           58 |      455 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    16.38 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           57 |      587 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.23 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      636 | 2024-07-16 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.77 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      692 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.24 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      732 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.59 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           53 |      813 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.21 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      907 | 2024-06-16 | 3DMAX             | L   | 0.891      | -            | -                | -                | -         |    -1.59 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |      986 | 2024-06-13 | PERA              | L   | 0.874      | -            | -                | -                | -         |   -12.42 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1003 | 2024-06-13 | Illuminar         | W   | 0.872      | 0.450        | -                | 0.376 (0.148)    | 0 (0.000) |    12.64 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1026 | 2024-06-12 | Sampi             | W   | 0.866      | 0.379        | -                | 1.000 (0.328)    | 0 (0.000) |    11.22 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1069 | 2024-06-10 | SINNERS           | W   | 0.853      | 0.379        | 0.038 (0.012)    | 0.768 (0.248)    | -         |    16.37 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1085 | 2024-06-10 | Gaimin Gladiators | W   | 0.851      | 0.450        | 0.040 (0.015)    | -                | -         |    16.45 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1124 | 2024-06-09 | ECLOT             | L   | 0.846      | -            | -                | -                | -         |    -6.81 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1169 | 2024-06-08 | Nexus             | W   | 0.840      | 0.450        | -                | 0.504 (0.191)    | -         |     8.42 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1260 | 2024-06-07 | Entropiq          | W   | 0.832      | -            | -                | -                | -         |     1.53 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1316 | 2024-06-06 | Illuminar         | L   | 0.826      | -            | -                | -                | -         |   -15.44 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1363 | 2024-06-05 | Verdant           | L   | 0.820      | -            | -                | -                | -         |   -13.48 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1381 | 2024-06-05 | Serbia            | L   | 0.819      | -            | -                | -                | -         |   -17.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1438 | 2024-06-04 | Johnny Speeds     | W   | 0.811      | 0.371        | 0.124 (0.037)    | 0.819 (0.246)    | -         |    21.90 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1460 | 2024-06-03 | UNiTY             | W   | 0.804      | -            | -                | -                | -         |    14.18 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1502 | 2024-06-01 | ARCRED            | L   | 0.793      | -            | -                | -                | -         |   -13.55 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1518 | 2024-06-01 | Permitta          | W   | 0.791      | 0.371        | -                | 0.801 (0.235)    | -         |    12.17 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1556 | 2024-05-30 | RUSTEC            | W   | 0.780      | -            | -                | -                | -         |     1.37 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1572 | 2024-05-30 | brazylijski luz   | L   | 0.777      | -            | -                | -                | -         |   -13.92 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1585 | 2024-05-29 | FLuffy Gangsters  | W   | 0.774      | -            | -                | -                | -         |     3.00 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1611 | 2024-05-28 | Sampi             | W   | 0.766      | 0.379        | -                | 1.000 (0.290)    | -         |    12.13 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1694 | 2024-05-24 | Illuminar         | W   | 0.738      | -            | -                | -                | -         |    11.18 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           31 |     1744 | 2024-05-22 | Entropiq          | W   | 0.726      | -            | -                | -                | -         |     1.37 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           30 |     1850 | 2024-05-20 | ECSTATIC          | W   | 0.712      | -            | -                | -                | -         |     1.35 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     2193 | 2024-05-10 | BetBoom           | L   | 0.645      | -            | -                | -                | -         |    -1.17 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           28 |     2262 | 2024-05-07 | Permitta          | W   | 0.625      | 0.435        | -                | 0.801 (0.218)    | -         |    10.76 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2276 | 2024-05-06 | B8                | L   | 0.619      | -            | -                | -                | -         |    -5.64 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2304 | 2024-05-04 | MOUZ NXT          | W   | 0.607      | 0.435        | 0.141 (0.037)    | 1.000 (0.264)    | -         |    13.01 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2367 | 2024-05-01 | ENCE Academy      | W   | 0.587      | -            | -                | -                | -         |     5.59 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2396 | 2024-04-30 | EYEBALLERS        | L   | 0.580      | -            | -                | -                | -         |    -8.66 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           23 |     2432 | 2024-04-29 | Nexus             | L   | 0.571      | -            | -                | -                | -         |   -10.15 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2475 | 2024-04-27 | Permitta          | L   | 0.558      | -            | -                | -                | -         |    -7.28 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2492 | 2024-04-26 | Insilio           | L   | 0.552      | -            | -                | -                | -         |    -8.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2568 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.531      | -            | -                | -                | -         |    -7.64 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2637 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.511      | -            | -                | -                | -         |    -7.02 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2724 | 2024-04-18 | MOUZ NXT          | L   | 0.499      | -            | -                | -                | -         |    -4.84 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2736 | 2024-04-18 | Nexus             | W   | 0.498      | -            | -                | -                | -         |     6.75 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2763 | 2024-04-17 | ENCE              | L   | 0.492      | -            | -                | -                | -         |    -0.81 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2797 | 2024-04-16 | kONO              | L   | 0.486      | -            | -                | -                | -         |    -9.92 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2897 | 2024-04-11 | Sashi             | L   | 0.451      | -            | -                | -                | -         |    -3.47 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     2941 | 2024-04-10 | AMKAL             | W   | 0.445      | 0.384        | 0.132 (0.022)    | -                | -         |    10.74 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3071 | 2024-04-06 | Sampi             | L   | 0.418      | -            | -                | -                | -         |    -6.66 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3162 | 2024-04-03 | Permitta          | W   | 0.400      | -            | -                | -                | -         |     6.76 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3228 | 2024-04-01 | BLEED             | W   | 0.386      | 0.384        | 0.095 (0.014)    | -                | -         |     7.32 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3678 | 2024-03-09 | kONO              | L   | 0.233      | -            | -                | -                | -         |    -4.70 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3690 | 2024-03-09 | Sampi             | L   | 0.232      | -            | -                | -                | -         |    -3.95 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3758 | 2024-03-06 | INGLORIOUS        | L   | 0.213      | -            | -                | -                | -         |    -6.03 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3764 | 2024-03-06 | Permitta          | L   | 0.212      | -            | -                | -                | -         |    -3.22 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3880 | 2024-03-02 | Sampi             | W   | 0.184      | -            | -                | -                | -         |     2.63 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4201 | 2024-02-16 | SAW               | L   | 0.087      | -            | -                | -                | -         |    -0.54 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4238 | 2024-02-15 | BetBoom           | L   | 0.079      | -            | -                | -                | -         |    -0.13 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4265 | 2024-02-14 | Natus Vincere     | L   | 0.074      | -            | -                | -                | -         |    -0.01 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4277 | 2024-02-14 | AMKAL             | W   | 0.072      | -            | -                | -                | 1 (0.072) |     1.78 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,020.26)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.898 | $5,000.00      | $4,491.67       |
| 2024-06-13 |      0.874 | $5,447.00      | $4,759.57       |
| 2024-06-06 |      0.824 | $3,000.00      | $2,472.50       |
| 2024-05-02 |      0.593 | $500.00        | $296.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
