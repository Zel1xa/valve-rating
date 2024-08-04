### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
<br />
Final Rank Value:  942.9<br />
<br />
Final Rank Value (942.9) = Starting Rank Value (918.0) + Head To Head Adjustments (24.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.006[<sup>2</sup>](#table1)

The average of these factors is 0.253<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 918.0
- 400 + ( ( 0.253 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 918.0


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
|           61 |      226 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    18.04 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      451 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.80 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      466 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.45 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      473 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.85 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      496 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.71 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      565 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    17.68 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      693 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.07 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      792 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.23 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      830 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.88 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      911 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.08 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |     1007 | 2024-06-16 | 3DMAX             | L   | 0.872      | -            | -                | -                | -         |    -1.52 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1095 | 2024-06-13 | PERA              | L   | 0.854      | -            | -                | -                | -         |   -12.14 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1112 | 2024-06-13 | Illuminar         | W   | 0.852      | 0.450        | -                | 0.352 (0.135)    | 0 (0.000) |    11.63 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1135 | 2024-06-12 | Sampi             | W   | 0.847      | 0.379        | 0.027 (0.009)    | 1.000 (0.321)    | 0 (0.000) |    11.08 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1176 | 2024-06-10 | SINNERS           | W   | 0.833      | 0.379        | 0.037 (0.012)    | 0.797 (0.251)    | 0 (0.000) |    16.64 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1192 | 2024-06-10 | Gaimin Gladiators | W   | 0.832      | 0.450        | 0.038 (0.014)    | 0.351 (0.131)    | -         |    15.70 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1231 | 2024-06-09 | ECLOT             | L   | 0.826      | -            | -                | -                | -         |    -5.04 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1274 | 2024-06-08 | Nexus             | W   | 0.821      | 0.450        | -                | 0.465 (0.172)    | -         |     8.10 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1358 | 2024-06-07 | Entropiq          | W   | 0.812      | -            | -                | -                | -         |     1.48 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1412 | 2024-06-06 | Illuminar         | L   | 0.807      | -            | -                | -                | -         |   -15.81 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1457 | 2024-06-05 | Verdant           | L   | 0.801      | -            | -                | -                | -         |   -13.45 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1474 | 2024-06-05 | Serbia            | L   | 0.800      | -            | -                | -                | -         |   -16.83 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1531 | 2024-06-04 | Johnny Speeds     | W   | 0.791      | 0.371        | 0.122 (0.036)    | 0.941 (0.276)    | -         |    21.37 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1553 | 2024-06-03 | UNiTY             | W   | 0.785      | -            | -                | -                | -         |    14.11 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1595 | 2024-06-01 | ARCRED            | L   | 0.774      | -            | -                | -                | -         |   -13.13 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1610 | 2024-06-01 | Permitta          | W   | 0.771      | 0.371        | -                | 0.876 (0.250)    | -         |    11.94 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1648 | 2024-05-30 | RUSTEC            | W   | 0.761      | -            | -                | -                | -         |     1.32 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1664 | 2024-05-30 | brazylijski luz   | L   | 0.758      | -            | -                | -                | -         |   -14.39 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1677 | 2024-05-29 | FLuffy Gangsters  | W   | 0.754      | -            | -                | -                | -         |     2.89 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1703 | 2024-05-28 | Sampi             | W   | 0.747      | 0.379        | -                | 1.000 (0.283)    | -         |    11.87 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1784 | 2024-05-24 | Illuminar         | W   | 0.719      | -            | -                | -                | -         |    10.03 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1834 | 2024-05-22 | Entropiq          | W   | 0.707      | -            | -                | -                | -         |     1.30 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1920 | 2024-05-20 | ECSTATIC          | W   | 0.692      | -            | -                | -                | -         |     1.29 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2248 | 2024-05-10 | BetBoom           | L   | 0.626      | -            | -                | -                | -         |    -1.20 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2315 | 2024-05-07 | Permitta          | W   | 0.605      | 0.435        | -                | 0.876 (0.230)    | -         |    10.41 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2329 | 2024-05-06 | B8                | L   | 0.599      | -            | -                | -                | -         |    -5.50 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2357 | 2024-05-04 | MOUZ NXT          | W   | 0.587      | 0.435        | 0.139 (0.035)    | 1.000 (0.255)    | -         |    12.97 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2418 | 2024-05-01 | ENCE Academy      | W   | 0.567      | -            | -                | -                | -         |     5.42 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2446 | 2024-04-30 | EYEBALLERS        | L   | 0.560      | -            | -                | -                | -         |    -8.58 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2482 | 2024-04-29 | Nexus             | L   | 0.551      | -            | -                | -                | -         |   -10.05 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2524 | 2024-04-27 | Permitta          | L   | 0.538      | -            | -                | -                | -         |    -7.21 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2542 | 2024-04-26 | Insilio           | L   | 0.533      | -            | -                | -                | -         |    -7.92 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2616 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.512      | -            | -                | -                | -         |    -7.44 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2681 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.492      | -            | -                | -                | -         |    -6.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2766 | 2024-04-18 | MOUZ NXT          | L   | 0.480      | -            | -                | -                | -         |    -5.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2778 | 2024-04-18 | Nexus             | W   | 0.479      | -            | -                | -                | -         |     6.27 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2804 | 2024-04-17 | ENCE              | L   | 0.473      | -            | -                | -                | -         |    -0.82 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2936 | 2024-04-11 | Sashi             | L   | 0.432      | -            | -                | -                | -         |    -3.27 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     2980 | 2024-04-10 | AMKAL             | W   | 0.425      | 0.384        | 0.130 (0.021)    | -                | -         |    10.29 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3110 | 2024-04-06 | Sampi             | L   | 0.399      | -            | -                | -                | -         |    -6.34 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3199 | 2024-04-03 | Permitta          | W   | 0.380      | -            | -                | -                | -         |     6.66 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3259 | 2024-04-01 | BLEED             | W   | 0.366      | 0.384        | 0.091 (0.013)    | -                | -         |     6.90 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3698 | 2024-03-09 | kONO              | L   | 0.213      | -            | -                | -                | -         |    -4.33 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3710 | 2024-03-09 | Sampi             | L   | 0.212      | -            | -                | -                | -         |    -3.62 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3778 | 2024-03-06 | INGLORIOUS        | L   | 0.194      | -            | -                | -                | -         |    -5.46 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3784 | 2024-03-06 | Permitta          | L   | 0.192      | -            | -                | -                | -         |    -2.80 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3895 | 2024-03-02 | Sampi             | W   | 0.165      | -            | -                | -                | -         |     2.36 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4206 | 2024-02-16 | SAW               | L   | 0.067      | -            | -                | -                | -         |    -0.43 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4243 | 2024-02-15 | BetBoom           | L   | 0.059      | -            | -                | -                | -         |    -0.10 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4270 | 2024-02-14 | Natus Vincere     | L   | 0.055      | -            | -                | -                | -         |    -0.01 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4282 | 2024-02-14 | AMKAL             | W   | 0.053      | -            | -                | -                | 1 (0.053) |     1.30 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,747.78)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.879 | $5,000.00      | $4,393.98       |
| 2024-06-13 |      0.854 | $5,447.00      | $4,653.15       |
| 2024-06-06 |      0.805 | $3,000.00      | $2,413.89       |
| 2024-05-02 |      0.574 | $500.00        | $286.76         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
