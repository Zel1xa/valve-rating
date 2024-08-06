### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, mASKED, SpavaQu, tomiko<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  979.4<br />
<br />
Final Rank Value (979.4) = Starting Rank Value (980.4) + Head To Head Adjustments (-1.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.415[<sup>1</sup>](#table2)
- Bounty Collected: 0.438[<sup>2</sup>](#table1)
- Opponent Network: 0.275[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.282<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 980.4
- 400 + ( ( 0.282 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 980.4


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
|          101 |        1 | 2024-08-06 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.79 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|          100 |       13 | 2024-08-06 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.54 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           99 |       18 | 2024-08-05 | B8                | W   | 1.000      | 0.435        | 0.170 (0.074)    | 0.912 (0.396)    | 0 (0.000) |    23.79 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           98 |       84 | 2024-08-03 | Nemiga            | W   | 1.000      | 0.435        | 0.314 (0.137)    | 0.704 (0.306)    | 0 (0.000) |    23.67 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           97 |      165 | 2024-08-01 | K27               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.85 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |      217 | 2024-07-31 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -19.69 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |      221 | 2024-07-31 | 9INE              | W   | 1.000      | 0.435        | -                | 0.523 (0.227)    | 0 (0.000) |    17.20 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |      265 | 2024-07-30 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |    -9.15 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      288 | 2024-07-29 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.81 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      309 | 2024-07-28 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.77 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |      360 | 2024-07-26 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.29 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           90 |      366 | 2024-07-26 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.66 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           89 |      404 | 2024-07-25 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -24.00 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |      452 | 2024-07-24 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -23.65 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |      503 | 2024-07-22 | Metizport         | W   | 1.000      | 0.435        | -                | 0.510 (0.222)    | 0 (0.000) |    16.54 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |      576 | 2024-07-20 | GUN5              | W   | 1.000      | 0.435        | 0.072 (0.031)    | 0.550 (0.239)    | 0 (0.000) |    15.60 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |      665 | 2024-07-18 | INFINITE          | L   | 1.000      | -            | -                | -                | -         |   -27.99 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |      715 | 2024-07-17 | ALTERNATE aTTaX   | W   | 1.000      | 0.435        | -                | 0.537 (0.233)    | -         |    12.36 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |      794 | 2024-07-16 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -12.10 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |      825 | 2024-07-15 | Space             | L   | 1.000      | -            | -                | -                | -         |   -18.46 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |      853 | 2024-07-14 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -16.03 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |      918 | 2024-07-10 | Passion UA        | W   | 1.000      | 0.371        | 0.173 (0.064)    | 1.000 (0.371)    | -         |    18.45 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           79 |     1046 | 2024-06-16 | 3DMAX             | L   | 0.860      | -            | -                | -                | -         |    -1.62 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           78 |     1090 | 2024-06-15 | BIG               | W   | 0.852      | 0.435        | 0.154 (0.057)    | -                | -         |    23.48 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           77 |     1127 | 2024-06-14 | PARIVISION        | W   | 0.846      | 0.435        | -                | 0.590 (0.217)    | -         |    18.55 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           76 |     1141 | 2024-06-13 | 9INE              | L   | 0.841      | -            | -                | -                | -         |   -23.83 | bnox, maaryy, mASKED, morelz, Vegi    |
|           75 |     1175 | 2024-06-12 | Nexus             | W   | 0.834      | -            | -                | -                | -         |     6.32 | bnox, maaryy, mASKED, morelz, Vegi    |
|           74 |     1191 | 2024-06-11 | Nemiga            | L   | 0.828      | -            | -                | -                | -         |    -5.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|           73 |     1216 | 2024-06-10 | Rebels            | L   | 0.821      | -            | -                | -                | -         |   -10.58 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           72 |     1331 | 2024-06-08 | Space             | W   | 0.807      | -            | -                | -                | -         |    10.54 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           71 |     1462 | 2024-06-06 | Zero Tenacity     | W   | 0.793      | 0.435        | 0.143 (0.049)    | 1.000 (0.345)    | -         |    18.76 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           70 |     1597 | 2024-06-03 | GUN5              | W   | 0.772      | 0.435        | 0.072 (0.024)    | -                | -         |    14.49 | bnox, Markoś, mASKED, morelz, tomiko  |
|           69 |     1655 | 2024-06-01 | Enterprise        | L   | 0.758      | -            | -                | -                | -         |   -12.19 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           68 |     1666 | 2024-05-31 | AMKAL             | L   | 0.754      | -            | -                | -                | -         |    -4.42 | bnox, mASKED, morelz, Sidney, tomiko  |
|           67 |     1699 | 2024-05-30 | NAVI Junior       | W   | 0.747      | -            | -                | -                | -         |     5.83 | bnox, maaryy, mASKED, morelz, tomiko  |
|           66 |     1707 | 2024-05-30 | Serbia            | L   | 0.746      | -            | -                | -                | -         |   -16.38 | bnox, maaryy, mASKED, morelz, tomiko  |
|           65 |     1752 | 2024-05-28 | Preasy            | W   | 0.732      | -            | -                | -                | -         |     6.96 | bnox, maaryy, mASKED, morelz, tomiko  |
|           64 |     1754 | 2024-05-28 | GUN5              | W   | 0.732      | 0.435        | 0.072 (0.023)    | -                | -         |    11.71 | bnox, maaryy, mASKED, morelz, tomiko  |
|           63 |     1772 | 2024-05-27 | VP.Prodigy        | L   | 0.727      | -            | -                | -                | -         |   -12.20 | bnox, maaryy, mASKED, morelz, tomiko  |
|           62 |     1796 | 2024-05-26 | ECLOT             | W   | 0.718      | -            | -                | -                | -         |    17.70 | bnox, maaryy, mASKED, morelz, tomiko  |
|           61 |     1811 | 2024-05-25 | Nexus             | W   | 0.713      | -            | -                | -                | -         |     7.55 | bnox, maaryy, mASKED, morelz, tomiko  |
|           60 |     1881 | 2024-05-22 | Endpoint          | W   | 0.694      | -            | -                | -                | -         |    11.31 | bnox, maaryy, mASKED, morelz, tomiko  |
|           59 |     1895 | 2024-05-22 | Johnny Speeds     | L   | 0.692      | -            | -                | -                | -         |    -2.47 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     1916 | 2024-05-21 | INFINITE          | W   | 0.688      | -            | -                | -                | -         |     2.63 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     1969 | 2024-05-20 | Passion UA        | L   | 0.679      | -            | -                | -                | -         |    -7.05 | bnox, maaryy, mASKED, morelz, Vegi    |
|           56 |     2061 | 2024-05-17 | Sangal            | L   | 0.658      | -            | -                | -                | -         |    -5.54 | bnox, maaryy, mASKED, morelz, Vegi    |
|           55 |     2128 | 2024-05-15 | EYEBALLERS        | L   | 0.648      | -            | -                | -                | -         |   -11.14 | bnox, maaryy, mASKED, morelz, Vegi    |
|           54 |     2213 | 2024-05-13 | 1WIN              | L   | 0.634      | -            | -                | -                | -         |    -8.61 | bnox, maaryy, mASKED, morelz, Vegi    |
|           53 |     2360 | 2024-05-07 | Enterprise        | L   | 0.592      | -            | -                | -                | -         |   -10.61 | bnox, maaryy, mASKED, morelz, Sobol   |
|           52 |     2376 | 2024-05-06 | ENCE Academy      | W   | 0.585      | -            | -                | -                | -         |     4.32 | bnox, maaryy, mASKED, morelz, Sobol   |
|           51 |     2420 | 2024-05-03 | Insilio           | L   | 0.567      | -            | -                | -                | -         |    -8.95 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           50 |     2447 | 2024-05-02 | Sampi             | L   | 0.560      | -            | -                | -                | -         |    -9.65 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           49 |     2459 | 2024-05-02 | B8                | L   | 0.559      | -            | -                | -                | -         |    -6.90 | bnox, maaryy, mASKED, morelz, Sobol   |
|           48 |     2507 | 2024-04-30 | BLEED             | L   | 0.545      | -            | -                | -                | -         |    -6.08 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     2515 | 2024-04-29 | AMKAL             | L   | 0.540      | -            | -                | -                | -         |    -4.85 | bnox, maaryy, mASKED, morelz, Vegi    |
|           46 |     2524 | 2024-04-29 | RUBY              | W   | 0.539      | -            | -                | -                | -         |     7.82 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           45 |     2563 | 2024-04-27 | Insilio           | L   | 0.526      | -            | -                | -                | -         |    -9.42 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     2569 | 2024-04-27 | Enterprise        | W   | 0.525      | -            | -                | -                | -         |     6.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     2592 | 2024-04-26 | ARCRED            | L   | 0.519      | -            | -                | -                | -         |    -9.75 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     2613 | 2024-04-25 | 1WIN              | L   | 0.513      | -            | -                | -                | -         |    -8.83 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     2630 | 2024-04-24 | BLEED             | L   | 0.507      | -            | -                | -                | -         |    -6.68 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     2635 | 2024-04-24 | Passion UA        | W   | 0.507      | 0.384        | 0.173 (0.034)    | 1.000 (0.195)    | -         |     8.96 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     2641 | 2024-04-24 | Sampi             | L   | 0.505      | -            | -                | -                | -         |    -9.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     2663 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.498      | -            | -                | -                | -         |     6.85 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     2677 | 2024-04-22 | Grannys Knockers  | W   | 0.492      | -            | -                | -                | -         |     3.28 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     2697 | 2024-04-21 | Insilio           | W   | 0.485      | -            | -                | -                | -         |     6.14 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     2722 | 2024-04-20 | Nexus             | L   | 0.479      | -            | -                | -                | -         |   -10.31 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     2727 | 2024-04-20 | Passion UA        | W   | 0.478      | 0.371        | 0.173 (0.031)    | -                | -         |     8.86 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     2818 | 2024-04-18 | Passion UA        | L   | 0.466      | -            | -                | -                | -         |    -5.96 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     2829 | 2024-04-18 | Sampi             | L   | 0.465      | -            | -                | -                | -         |    -9.01 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     2847 | 2024-04-17 | PARIVISION        | W   | 0.460      | -            | -                | -                | -         |     9.00 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     2887 | 2024-04-16 | Gaimin Gladiators | L   | 0.453      | -            | -                | -                | -         |    -7.11 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     2949 | 2024-04-12 | MOUZ NXT          | W   | 0.426      | -            | -                | -                | -         |     7.96 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     3030 | 2024-04-10 | EYEBALLERS        | W   | 0.412      | -            | -                | -                | -         |     4.95 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     3106 | 2024-04-08 | HAVU              | W   | 0.400      | -            | -                | -                | -         |     2.16 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3117 | 2024-04-08 | JANO              | W   | 0.398      | -            | -                | -                | -         |     1.94 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3244 | 2024-04-03 | Enterprise        | L   | 0.367      | -            | -                | -                | -         |    -6.88 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3256 | 2024-04-03 | ECLOT             | L   | 0.366      | -            | -                | -                | -         |    -2.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3289 | 2024-04-02 | 3DMAX             | L   | 0.360      | -            | -                | -                | -         |    -0.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3298 | 2024-04-02 | Sashi             | L   | 0.358      | -            | -                | -                | -         |    -3.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3562 | 2024-03-16 | RUBY              | L   | 0.247      | -            | -                | -                | -         |    -4.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3582 | 2024-03-15 | The Chosen Few    | W   | 0.240      | -            | -                | -                | -         |     1.15 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3587 | 2024-03-15 | Sampi             | L   | 0.239      | -            | -                | -                | -         |    -4.82 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3635 | 2024-03-13 | MOUZ NXT          | W   | 0.228      | -            | -                | -                | -         |     4.09 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3652 | 2024-03-13 | ECLOT             | W   | 0.226      | -            | -                | -                | -         |     5.47 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3667 | 2024-03-13 | ECLOT             | W   | 0.225      | -            | -                | -                | -         |     5.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     3708 | 2024-03-11 | ex-Preasy         | L   | 0.213      | -            | -                | -                | -         |    -5.02 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     3753 | 2024-03-09 | Sashi             | L   | 0.199      | -            | -                | -                | -         |    -1.90 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     3790 | 2024-03-07 | VP.Prodigy        | W   | 0.188      | -            | -                | -                | -         |     2.01 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     3800 | 2024-03-07 | kONO              | W   | 0.185      | -            | -                | -                | -         |     1.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     3827 | 2024-03-06 | Passion UA        | W   | 0.180      | -            | -                | -                | -         |     3.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     3829 | 2024-03-06 | Enterprise        | W   | 0.179      | -            | -                | -                | -         |     2.35 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     3869 | 2024-03-05 | Young Ninjas      | W   | 0.173      | -            | -                | -                | -         |     1.27 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     3936 | 2024-03-02 | AURA              | W   | 0.153      | -            | -                | -                | -         |     0.29 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     3980 | 2024-02-28 | Secret            | L   | 0.133      | -            | -                | -                | -         |    -3.87 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     3984 | 2024-02-28 | ECLOT             | L   | 0.132      | -            | -                | -                | -         |    -0.88 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     4003 | 2024-02-27 | Sprout            | W   | 0.126      | -            | -                | -                | -         |     0.14 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     4076 | 2024-02-24 | ECLOT             | W   | 0.106      | -            | -                | -                | -         |     2.63 | bnox, maaryy, mASKED, morelz, Vegi    |
|            3 |     4109 | 2024-02-22 | PGE Turow         | W   | 0.092      | -            | -                | -                | -         |     0.39 | bnox, maaryy, mASKED, morelz, reiko   |
|            2 |     4143 | 2024-02-21 | ECLOT             | L   | 0.085      | -            | -                | -                | -         |    -0.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4188 | 2024-02-19 | ECLOT             | W   | 0.073      | -            | -                | -                | -         |     1.81 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,482.97)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.860 | $5,000.00      | $4,302.31       |
| 2024-06-13 |      0.841 | $545.00        | $458.46         |
| 2024-05-02 |      0.560 | $500.00        | $280.23         |
| 2024-04-25 |      0.512 | $3,000.00      | $1,534.72       |
| 2024-03-25 |      0.307 | $1,250.00      | $383.91         |
| 2024-02-28 |      0.132 | $3,000.00      | $395.56         |
| 2024-02-21 |      0.085 | $1,500.00      | $127.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
