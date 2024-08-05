### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  945.0<br />
<br />
Final Rank Value (945.0) = Starting Rank Value (924.1) + Head To Head Adjustments (20.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.009[<sup>2</sup>](#table1)

The average of these factors is 0.254<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 924.1
- 400 + ( ( 0.254 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 924.1


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
|           61 |       78 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.072 (0.010)    | -                | 0 (0.000) |    18.33 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      303 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.64 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      318 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.44 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      325 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.95 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      348 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.57 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      417 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    17.43 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      545 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.08 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      644 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.21 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      682 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.68 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      763 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.11 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |      859 | 2024-06-16 | 3DMAX             | L   | 0.897      | -            | -                | -                | -         |    -1.57 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |      947 | 2024-06-13 | PERA              | L   | 0.880      | -            | -                | -                | -         |   -12.40 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |      964 | 2024-06-13 | Illuminar         | W   | 0.878      | 0.450        | -                | 0.348 (0.138)    | 0 (0.000) |    12.04 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |      987 | 2024-06-12 | Sampi             | W   | 0.872      | 0.379        | 0.028 (0.009)    | 1.000 (0.330)    | 0 (0.000) |    11.24 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1028 | 2024-06-10 | SINNERS           | W   | 0.859      | 0.379        | 0.038 (0.012)    | 0.721 (0.234)    | 0 (0.000) |    16.06 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1044 | 2024-06-10 | Gaimin Gladiators | W   | 0.857      | 0.450        | 0.040 (0.015)    | 0.363 (0.140)    | -         |    16.52 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1083 | 2024-06-09 | ECLOT             | L   | 0.851      | -            | -                | -                | -         |    -6.93 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1126 | 2024-06-08 | Nexus             | W   | 0.846      | 0.450        | -                | 0.465 (0.177)    | -         |     8.34 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1210 | 2024-06-07 | Entropiq          | W   | 0.838      | -            | -                | -                | -         |     1.51 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1264 | 2024-06-06 | Illuminar         | L   | 0.832      | -            | -                | -                | -         |   -16.35 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1309 | 2024-06-05 | Verdant           | L   | 0.826      | -            | -                | -                | -         |   -13.83 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1326 | 2024-06-05 | Serbia            | L   | 0.825      | -            | -                | -                | -         |   -17.29 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1383 | 2024-06-04 | Johnny Speeds     | W   | 0.817      | 0.371        | 0.123 (0.037)    | 0.817 (0.247)    | -         |    21.98 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1405 | 2024-06-03 | UNiTY             | W   | 0.810      | -            | -                | -                | -         |    14.25 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1447 | 2024-06-01 | ARCRED            | L   | 0.799      | -            | -                | -                | -         |   -13.82 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1462 | 2024-06-01 | Permitta          | W   | 0.797      | 0.371        | -                | 0.799 (0.236)    | -         |    11.95 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1500 | 2024-05-30 | RUSTEC            | W   | 0.786      | -            | -                | -                | -         |     1.34 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1516 | 2024-05-30 | brazylijski luz   | L   | 0.783      | -            | -                | -                | -         |   -14.86 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1529 | 2024-05-29 | FLuffy Gangsters  | W   | 0.779      | -            | -                | -                | -         |     2.93 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1555 | 2024-05-28 | Sampi             | W   | 0.772      | 0.379        | -                | 1.000 (0.292)    | -         |    12.17 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1636 | 2024-05-24 | Illuminar         | W   | 0.744      | -            | -                | -                | -         |    10.37 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1686 | 2024-05-22 | Entropiq          | W   | 0.732      | -            | -                | -                | -         |     1.32 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1772 | 2024-05-20 | ECSTATIC          | W   | 0.717      | -            | -                | -                | -         |     1.31 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2100 | 2024-05-10 | BetBoom           | L   | 0.651      | -            | -                | -                | -         |    -1.16 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2167 | 2024-05-07 | Permitta          | W   | 0.630      | 0.435        | -                | 0.799 (0.219)    | -         |    10.54 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2181 | 2024-05-06 | B8                | L   | 0.625      | -            | -                | -                | -         |    -5.69 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2209 | 2024-05-04 | MOUZ NXT          | W   | 0.613      | 0.435        | 0.140 (0.037)    | 1.000 (0.266)    | -         |    13.45 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2270 | 2024-05-01 | ENCE Academy      | W   | 0.593      | -            | -                | -                | -         |     5.49 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2298 | 2024-04-30 | EYEBALLERS        | L   | 0.585      | -            | -                | -                | -         |    -8.89 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2334 | 2024-04-29 | Nexus             | L   | 0.577      | -            | -                | -                | -         |   -10.45 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2376 | 2024-04-27 | Permitta          | L   | 0.564      | -            | -                | -                | -         |    -7.87 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2394 | 2024-04-26 | Insilio           | L   | 0.558      | -            | -                | -                | -         |    -8.28 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2468 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.537      | -            | -                | -                | -         |    -7.85 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2533 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.517      | -            | -                | -                | -         |    -7.21 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2618 | 2024-04-18 | MOUZ NXT          | L   | 0.505      | -            | -                | -                | -         |    -5.24 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2630 | 2024-04-18 | Nexus             | W   | 0.504      | -            | -                | -                | -         |     6.61 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2656 | 2024-04-17 | ENCE              | L   | 0.498      | -            | -                | -                | -         |    -0.81 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2788 | 2024-04-11 | Sashi             | L   | 0.457      | -            | -                | -                | -         |    -3.48 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     2832 | 2024-04-10 | AMKAL             | W   | 0.450      | 0.384        | 0.131 (0.023)    | -                | -         |    10.95 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     2962 | 2024-04-06 | Sampi             | L   | 0.424      | -            | -                | -                | -         |    -6.74 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3051 | 2024-04-03 | Permitta          | W   | 0.405      | -            | -                | -                | -         |     6.75 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3111 | 2024-04-01 | BLEED             | W   | 0.391      | 0.384        | 0.095 (0.014)    | -                | -         |     7.51 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3550 | 2024-03-09 | kONO              | L   | 0.239      | -            | -                | -                | -         |    -4.86 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3562 | 2024-03-09 | Sampi             | L   | 0.238      | -            | -                | -                | -         |    -4.05 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3630 | 2024-03-06 | INGLORIOUS        | L   | 0.219      | -            | -                | -                | -         |    -6.19 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3636 | 2024-03-06 | Permitta          | L   | 0.218      | -            | -                | -                | -         |    -3.38 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3747 | 2024-03-02 | Sampi             | W   | 0.190      | -            | -                | -                | -         |     2.71 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4058 | 2024-02-16 | SAW               | L   | 0.093      | -            | -                | -                | -         |    -0.57 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4095 | 2024-02-15 | BetBoom           | L   | 0.084      | -            | -                | -                | -         |    -0.14 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4122 | 2024-02-14 | Natus Vincere     | L   | 0.080      | -            | -                | -                | -         |    -0.01 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4134 | 2024-02-14 | AMKAL             | W   | 0.078      | -            | -                | -                | 1 (0.078) |     1.93 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,100.14)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.904 | $5,000.00      | $4,520.30       |
| 2024-06-13 |      0.880 | $5,447.00      | $4,790.76       |
| 2024-06-06 |      0.830 | $3,000.00      | $2,489.68       |
| 2024-05-02 |      0.599 | $500.00        | $299.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
