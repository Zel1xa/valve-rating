### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, mASKED, SpavaQu, tomiko<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  910.1<br />
<br />
Final Rank Value (910.1) = Starting Rank Value (930.9) + Head To Head Adjustments (-20.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.382[<sup>1</sup>](#table2)
- Bounty Collected: 0.412[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.9
- 400 + ( ( 0.257 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 930.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           97 |       24 | 2024-07-31 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -19.17 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |       27 | 2024-07-31 | 9INE              | W   | 1.000      | 0.435        | -                | 0.487 (0.211)    | 0 (0.000) |    17.91 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |       71 | 2024-07-30 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |    -8.84 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |       95 | 2024-07-29 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.55 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      116 | 2024-07-28 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.83 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      167 | 2024-07-26 | Space             | W   | 1.000      | 0.435        | -                | 0.406 (0.176)    | 0 (0.000) |    15.75 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |      173 | 2024-07-26 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.48 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           90 |      211 | 2024-07-25 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -24.26 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           89 |      259 | 2024-07-24 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -23.32 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |      310 | 2024-07-22 | Metizport         | W   | 1.000      | 0.435        | -                | 0.427 (0.186)    | 0 (0.000) |    16.99 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |      383 | 2024-07-20 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.516 (0.224)    | 0 (0.000) |    16.11 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |      472 | 2024-07-18 | INFINITE          | L   | 1.000      | -            | -                | -                | -         |   -27.75 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |      522 | 2024-07-17 | ALTERNATE aTTaX   | W   | 1.000      | 0.435        | -                | 0.564 (0.245)    | 0 (0.000) |    12.70 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |      601 | 2024-07-16 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.77 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |      632 | 2024-07-15 | Space             | L   | 1.000      | -            | -                | -                | -         |   -17.89 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |      660 | 2024-07-14 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -15.36 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |      725 | 2024-07-10 | Passion UA        | W   | 1.000      | 0.371        | 0.171 (0.063)    | 1.000 (0.371)    | 0 (0.000) |    18.67 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |      853 | 2024-06-16 | 3DMAX             | L   | 0.898      | -            | -                | -                | -         |    -1.61 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           79 |      897 | 2024-06-15 | BIG               | W   | 0.890      | 0.435        | 0.157 (0.061)    | -                | 0 (0.000) |    24.22 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           78 |      934 | 2024-06-14 | PARIVISION        | W   | 0.884      | -            | -                | -                | 0 (0.000) |    19.61 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           77 |      948 | 2024-06-13 | 9INE              | L   | 0.879      | -            | -                | -                | -         |   -24.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           76 |      982 | 2024-06-12 | Nexus             | W   | 0.872      | -            | -                | -                | -         |     7.02 | bnox, maaryy, mASKED, morelz, Vegi    |
|           75 |      998 | 2024-06-11 | Nemiga            | L   | 0.866      | -            | -                | -                | -         |    -5.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           74 |     1023 | 2024-06-10 | Rebels            | L   | 0.859      | -            | -                | -                | -         |   -10.07 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           73 |     1138 | 2024-06-08 | Space             | W   | 0.846      | -            | -                | -                | -         |    11.95 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           72 |     1269 | 2024-06-06 | Zero Tenacity     | W   | 0.832      | 0.435        | 0.138 (0.050)    | 1.000 (0.361)    | -         |    20.27 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           71 |     1404 | 2024-06-03 | GUN5              | W   | 0.811      | 0.435        | 0.073 (0.026)    | 0.516 (0.182)    | -         |    15.88 | bnox, Markoś, mASKED, morelz, tomiko  |
|           70 |     1462 | 2024-06-01 | Enterprise        | L   | 0.797      | -            | -                | -                | -         |   -11.95 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           69 |     1473 | 2024-05-31 | AMKAL             | L   | 0.793      | -            | -                | -                | -         |    -3.92 | bnox, mASKED, morelz, Sidney, tomiko  |
|           68 |     1506 | 2024-05-30 | NAVI Junior       | W   | 0.785      | -            | -                | -                | -         |     3.12 | bnox, maaryy, mASKED, morelz, tomiko  |
|           67 |     1514 | 2024-05-30 | Serbia            | L   | 0.784      | -            | -                | -                | -         |   -16.51 | bnox, maaryy, mASKED, morelz, tomiko  |
|           66 |     1559 | 2024-05-28 | Preasy            | W   | 0.771      | -            | -                | -                | -         |     8.16 | bnox, maaryy, mASKED, morelz, tomiko  |
|           65 |     1561 | 2024-05-28 | GUN5              | W   | 0.770      | 0.435        | 0.073 (0.025)    | -                | -         |    12.96 | bnox, maaryy, mASKED, morelz, tomiko  |
|           64 |     1579 | 2024-05-27 | VP.Prodigy        | L   | 0.765      | -            | -                | -                | -         |   -11.91 | bnox, maaryy, mASKED, morelz, tomiko  |
|           63 |     1603 | 2024-05-26 | ECLOT             | W   | 0.757      | -            | -                | -                | -         |    17.19 | bnox, maaryy, mASKED, morelz, tomiko  |
|           62 |     1618 | 2024-05-25 | Nexus             | W   | 0.751      | -            | -                | -                | -         |     8.64 | bnox, maaryy, mASKED, morelz, tomiko  |
|           61 |     1688 | 2024-05-22 | Endpoint          | W   | 0.732      | -            | -                | -                | -         |    12.75 | bnox, maaryy, mASKED, morelz, tomiko  |
|           60 |     1702 | 2024-05-22 | Johnny Speeds     | L   | 0.730      | -            | -                | -                | -         |    -2.34 | bnox, maaryy, mASKED, morelz, Vegi    |
|           59 |     1723 | 2024-05-21 | INFINITE          | W   | 0.726      | -            | -                | -                | -         |     3.14 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     1776 | 2024-05-20 | Passion UA        | L   | 0.717      | -            | -                | -                | -         |    -6.98 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     1868 | 2024-05-17 | Sangal            | L   | 0.697      | -            | -                | -                | -         |    -5.63 | bnox, maaryy, mASKED, morelz, Vegi    |
|           56 |     1935 | 2024-05-15 | EYEBALLERS        | L   | 0.686      | -            | -                | -                | -         |   -10.88 | bnox, maaryy, mASKED, morelz, Vegi    |
|           55 |     2020 | 2024-05-13 | 1WIN              | L   | 0.672      | -            | -                | -                | -         |    -9.08 | bnox, maaryy, mASKED, morelz, Vegi    |
|           54 |     2167 | 2024-05-07 | Enterprise        | L   | 0.630      | -            | -                | -                | -         |   -10.54 | bnox, maaryy, mASKED, morelz, Sobol   |
|           53 |     2183 | 2024-05-06 | ENCE Academy      | W   | 0.624      | -            | -                | -                | -         |     5.07 | bnox, maaryy, mASKED, morelz, Sobol   |
|           52 |     2227 | 2024-05-03 | Insilio           | L   | 0.605      | -            | -                | -                | -         |    -8.73 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           51 |     2254 | 2024-05-02 | Sampi             | L   | 0.599      | -            | -                | -                | -         |    -9.47 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           50 |     2266 | 2024-05-02 | B8                | L   | 0.597      | -            | -                | -                | -         |    -6.63 | bnox, maaryy, mASKED, morelz, Sobol   |
|           49 |     2314 | 2024-04-30 | BLEED             | L   | 0.584      | -            | -                | -                | -         |    -5.49 | bnox, maaryy, mASKED, morelz, Vegi    |
|           48 |     2322 | 2024-04-29 | AMKAL             | L   | 0.578      | -            | -                | -                | -         |    -4.43 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     2331 | 2024-04-29 | RUBY              | W   | 0.577      | 0.435        | 0.096 (0.024)    | -                | -         |     9.25 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           46 |     2370 | 2024-04-27 | Insilio           | L   | 0.565      | -            | -                | -                | -         |    -9.31 | bnox, maaryy, mASKED, morelz, Vegi    |
|           45 |     2376 | 2024-04-27 | Enterprise        | W   | 0.564      | -            | -                | -                | -         |     7.87 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     2399 | 2024-04-26 | ARCRED            | L   | 0.557      | -            | -                | -                | -         |   -10.95 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     2420 | 2024-04-25 | 1WIN              | L   | 0.552      | -            | -                | -                | -         |    -9.47 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     2437 | 2024-04-24 | BLEED             | L   | 0.546      | -            | -                | -                | -         |    -6.11 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     2442 | 2024-04-24 | Passion UA        | W   | 0.545      | 0.384        | 0.171 (0.036)    | 1.000 (0.209)    | -         |    10.06 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     2448 | 2024-04-24 | Sampi             | L   | 0.543      | -            | -                | -                | -         |    -9.41 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     2470 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.536      | -            | -                | -                | -         |     8.14 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     2484 | 2024-04-22 | Grannys Knockers  | W   | 0.530      | -            | -                | -                | -         |     4.20 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     2504 | 2024-04-21 | Insilio           | W   | 0.523      | -            | -                | -                | -         |     7.46 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     2529 | 2024-04-20 | Nexus             | L   | 0.518      | -            | -                | -                | -         |   -10.35 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     2534 | 2024-04-20 | Passion UA        | W   | 0.517      | 0.371        | 0.171 (0.033)    | 1.000 (0.191)    | -         |    10.09 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     2625 | 2024-04-18 | Passion UA        | L   | 0.504      | -            | -                | -                | -         |    -5.90 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     2636 | 2024-04-18 | Sampi             | L   | 0.503      | -            | -                | -                | -         |    -8.79 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     2654 | 2024-04-17 | PARIVISION        | W   | 0.498      | -            | -                | -                | -         |    10.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     2694 | 2024-04-16 | Gaimin Gladiators | L   | 0.491      | -            | -                | -                | -         |    -6.22 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     2756 | 2024-04-12 | MOUZ NXT          | W   | 0.464      | 0.371        | 0.140 (0.024)    | -                | -         |     9.53 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     2837 | 2024-04-10 | EYEBALLERS        | W   | 0.450      | -            | -                | -                | -         |     6.31 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     2913 | 2024-04-08 | HAVU              | W   | 0.438      | -            | -                | -                | -         |     2.99 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     2924 | 2024-04-08 | JANO              | W   | 0.437      | -            | -                | -                | -         |     2.63 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3051 | 2024-04-03 | Enterprise        | L   | 0.405      | -            | -                | -                | -         |    -6.75 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3063 | 2024-04-03 | ECLOT             | L   | 0.404      | -            | -                | -                | -         |    -3.76 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3096 | 2024-04-02 | 3DMAX             | L   | 0.398      | -            | -                | -                | -         |    -0.22 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3105 | 2024-04-02 | Sashi             | L   | 0.397      | -            | -                | -                | -         |    -3.31 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3369 | 2024-03-16 | RUBY              | L   | 0.285      | -            | -                | -                | -         |    -4.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3389 | 2024-03-15 | The Chosen Few    | W   | 0.278      | -            | -                | -                | -         |     1.70 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3394 | 2024-03-15 | Sampi             | L   | 0.277      | -            | -                | -                | -         |    -5.00 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3442 | 2024-03-13 | MOUZ NXT          | W   | 0.266      | -            | -                | -                | -         |     5.33 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3459 | 2024-03-13 | ECLOT             | W   | 0.265      | -            | -                | -                | -         |     5.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3474 | 2024-03-13 | ECLOT             | W   | 0.264      | -            | -                | -                | -         |     5.93 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3515 | 2024-03-11 | ex-Preasy         | L   | 0.251      | -            | -                | -                | -         |    -5.32 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     3560 | 2024-03-09 | Sashi             | L   | 0.238      | -            | -                | -                | -         |    -1.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     3597 | 2024-03-07 | VP.Prodigy        | W   | 0.226      | -            | -                | -                | -         |     2.89 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     3607 | 2024-03-07 | kONO              | W   | 0.224      | -            | -                | -                | -         |     2.29 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     3634 | 2024-03-06 | Passion UA        | W   | 0.218      | -            | -                | -                | -         |     4.83 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     3636 | 2024-03-06 | Enterprise        | W   | 0.218      | -            | -                | -                | -         |     3.38 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     3676 | 2024-03-05 | Young Ninjas      | W   | 0.211      | -            | -                | -                | -         |     1.97 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     3743 | 2024-03-02 | AURA              | W   | 0.191      | -            | -                | -                | -         |     0.51 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     3787 | 2024-02-28 | Secret            | L   | 0.171      | -            | -                | -                | -         |    -4.86 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     3791 | 2024-02-28 | ECLOT             | L   | 0.170      | -            | -                | -                | -         |    -1.45 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     3810 | 2024-02-27 | Sprout            | W   | 0.164      | -            | -                | -                | -         |     0.24 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     3883 | 2024-02-24 | ECLOT             | W   | 0.144      | -            | -                | -                | -         |     3.32 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     3916 | 2024-02-22 | PGE Turow         | W   | 0.130      | -            | -                | -                | -         |     0.73 | bnox, maaryy, mASKED, morelz, reiko   |
|            3 |     3950 | 2024-02-21 | ECLOT             | L   | 0.124      | -            | -                | -                | -         |    -1.05 | bnox, maaryy, mASKED, morelz, Vegi    |
|            2 |     3995 | 2024-02-19 | ECLOT             | W   | 0.111      | -            | -                | -                | -         |     2.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4232 | 2024-02-07 | Endpoint          | L   | 0.031      | -            | -                | -                | -         |    -0.53 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,049.91)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.899 | $5,000.00      | $4,493.91       |
| 2024-06-13 |      0.880 | $545.00        | $479.34         |
| 2024-05-02 |      0.599 | $500.00        | $299.39         |
| 2024-04-25 |      0.550 | $3,000.00      | $1,649.68       |
| 2024-03-25 |      0.345 | $1,250.00      | $431.81         |
| 2024-02-28 |      0.170 | $3,000.00      | $510.51         |
| 2024-02-21 |      0.124 | $1,500.00      | $185.26         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
