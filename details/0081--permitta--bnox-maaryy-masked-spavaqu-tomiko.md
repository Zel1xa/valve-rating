### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, mASKED, SpavaQu, tomiko<br />
Global Rank: [81](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  927.4<br />
<br />
Final Rank Value (927.4) = Starting Rank Value (944.7) + Head To Head Adjustments (-17.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.381[<sup>1</sup>](#table2)
- Bounty Collected: 0.431[<sup>2</sup>](#table1)
- Opponent Network: 0.252[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 944.7
- 400 + ( ( 0.266 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 944.7


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
|           97 |        5 | 2024-08-03 | Nemiga            | W   | 1.000      | 0.435        | 0.318 (0.138)    | 0.719 (0.313)    | 0 (0.000) |    24.10 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |       65 | 2024-08-01 | K27               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.42 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |      116 | 2024-07-31 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -18.75 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |      119 | 2024-07-31 | 9INE              | W   | 1.000      | 0.435        | -                | 0.553 (0.240)    | 0 (0.000) |    18.21 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      162 | 2024-07-30 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |    -8.43 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      186 | 2024-07-29 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.84 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |      207 | 2024-07-28 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.58 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           90 |      258 | 2024-07-26 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.70 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           89 |      264 | 2024-07-26 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.83 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |      302 | 2024-07-25 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -23.13 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |      350 | 2024-07-24 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -22.91 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |      401 | 2024-07-22 | Metizport         | W   | 1.000      | 0.435        | -                | 0.433 (0.188)    | 0 (0.000) |    17.43 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |      474 | 2024-07-20 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.588 (0.256)    | 0 (0.000) |    17.07 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |      563 | 2024-07-18 | INFINITE          | L   | 1.000      | -            | -                | -                | -         |   -27.42 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |      689 | 2024-07-16 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.66 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |      720 | 2024-07-15 | Space             | L   | 1.000      | -            | -                | -                | -         |   -17.21 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |      746 | 2024-07-14 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -15.28 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |      808 | 2024-07-10 | Passion UA        | W   | 1.000      | 0.371        | 0.172 (0.064)    | 1.000 (0.371)    | 0 (0.000) |    18.83 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           79 |      929 | 2024-06-16 | 3DMAX             | L   | 0.879      | -            | -                | -                | -         |    -1.59 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           78 |      967 | 2024-06-15 | BIG               | W   | 0.871      | 0.435        | 0.156 (0.059)    | -                | 0 (0.000) |    24.40 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           77 |      997 | 2024-06-14 | PARIVISION        | W   | 0.865      | 0.435        | -                | 0.553 (0.208)    | -         |    19.43 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           76 |     1011 | 2024-06-13 | 9INE              | L   | 0.860      | -            | -                | -                | -         |   -24.07 | bnox, maaryy, mASKED, morelz, Vegi    |
|           75 |     1044 | 2024-06-12 | Nexus             | W   | 0.853      | -            | -                | -                | -         |     7.05 | bnox, maaryy, mASKED, morelz, Vegi    |
|           74 |     1059 | 2024-06-11 | Nemiga            | L   | 0.847      | -            | -                | -                | -         |    -5.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|           73 |     1082 | 2024-06-10 | Rebels            | L   | 0.840      | -            | -                | -                | -         |    -9.94 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           72 |     1322 | 2024-06-06 | Zero Tenacity     | W   | 0.813      | 0.435        | 0.137 (0.048)    | 1.000 (0.353)    | -         |    19.31 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           71 |     1456 | 2024-06-03 | GUN5              | W   | 0.792      | 0.435        | 0.073 (0.025)    | 0.588 (0.202)    | -         |    15.44 | bnox, Markoś, mASKED, morelz, tomiko  |
|           70 |     1512 | 2024-06-01 | Enterprise        | L   | 0.778      | -            | -                | -                | -         |   -11.97 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           69 |     1523 | 2024-05-31 | AMKAL             | L   | 0.774      | -            | -                | -                | -         |    -4.19 | bnox, mASKED, morelz, Sidney, tomiko  |
|           68 |     1556 | 2024-05-30 | NAVI Junior       | W   | 0.766      | -            | -                | -                | -         |     2.92 | bnox, maaryy, mASKED, morelz, tomiko  |
|           67 |     1564 | 2024-05-30 | Serbia            | L   | 0.765      | -            | -                | -                | -         |   -16.42 | bnox, maaryy, mASKED, morelz, tomiko  |
|           66 |     1609 | 2024-05-28 | Preasy            | W   | 0.752      | -            | -                | -                | -         |     7.71 | bnox, maaryy, mASKED, morelz, tomiko  |
|           65 |     1611 | 2024-05-28 | GUN5              | W   | 0.751      | 0.435        | 0.073 (0.024)    | 0.588 (0.192)    | -         |    12.59 | bnox, maaryy, mASKED, morelz, tomiko  |
|           64 |     1629 | 2024-05-27 | VP.Prodigy        | L   | 0.746      | -            | -                | -                | -         |   -11.96 | bnox, maaryy, mASKED, morelz, tomiko  |
|           63 |     1652 | 2024-05-26 | ECLOT             | W   | 0.738      | -            | -                | -                | -         |    18.46 | bnox, maaryy, mASKED, morelz, tomiko  |
|           62 |     1667 | 2024-05-25 | Nexus             | W   | 0.732      | -            | -                | -                | -         |     8.19 | bnox, maaryy, mASKED, morelz, tomiko  |
|           61 |     1737 | 2024-05-22 | Endpoint          | W   | 0.713      | -            | -                | -                | -         |    12.16 | bnox, maaryy, mASKED, morelz, tomiko  |
|           60 |     1751 | 2024-05-22 | Johnny Speeds     | L   | 0.711      | -            | -                | -                | -         |    -2.43 | bnox, maaryy, mASKED, morelz, Vegi    |
|           59 |     1772 | 2024-05-21 | INFINITE          | W   | 0.707      | -            | -                | -                | -         |     2.94 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     1825 | 2024-05-20 | Passion UA        | L   | 0.698      | -            | -                | -                | -         |    -7.10 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     1916 | 2024-05-17 | Sangal            | L   | 0.678      | -            | -                | -                | -         |    -5.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           56 |     1983 | 2024-05-15 | EYEBALLERS        | L   | 0.667      | -            | -                | -                | -         |   -10.94 | bnox, maaryy, mASKED, morelz, Vegi    |
|           55 |     2068 | 2024-05-13 | 1WIN              | L   | 0.653      | -            | -                | -                | -         |    -9.05 | bnox, maaryy, mASKED, morelz, Vegi    |
|           54 |     2214 | 2024-05-07 | Enterprise        | L   | 0.611      | -            | -                | -                | -         |   -10.48 | bnox, maaryy, mASKED, morelz, Sobol   |
|           53 |     2230 | 2024-05-06 | ENCE Academy      | W   | 0.605      | -            | -                | -                | -         |     4.64 | bnox, maaryy, mASKED, morelz, Sobol   |
|           52 |     2274 | 2024-05-03 | Insilio           | L   | 0.586      | -            | -                | -                | -         |    -8.77 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           51 |     2301 | 2024-05-02 | Sampi             | L   | 0.579      | -            | -                | -                | -         |    -9.39 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           50 |     2313 | 2024-05-02 | B8                | L   | 0.578      | -            | -                | -                | -         |    -6.72 | bnox, maaryy, mASKED, morelz, Sobol   |
|           49 |     2361 | 2024-04-30 | BLEED             | L   | 0.564      | -            | -                | -                | -         |    -5.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|           48 |     2369 | 2024-04-29 | AMKAL             | L   | 0.559      | -            | -                | -                | -         |    -4.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     2378 | 2024-04-29 | RUBY              | W   | 0.558      | 0.435        | 0.095 (0.023)    | -                | -         |     8.63 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           46 |     2417 | 2024-04-27 | Insilio           | L   | 0.546      | -            | -                | -                | -         |    -9.28 | bnox, maaryy, mASKED, morelz, Vegi    |
|           45 |     2423 | 2024-04-27 | Enterprise        | W   | 0.545      | -            | -                | -                | -         |     7.33 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     2445 | 2024-04-26 | ARCRED            | L   | 0.538      | -            | -                | -                | -         |   -10.59 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     2466 | 2024-04-25 | 1WIN              | L   | 0.533      | -            | -                | -                | -         |    -9.38 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     2483 | 2024-04-24 | BLEED             | L   | 0.527      | -            | -                | -                | -         |    -6.36 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     2488 | 2024-04-24 | Passion UA        | W   | 0.526      | 0.384        | 0.172 (0.035)    | 1.000 (0.202)    | -         |     9.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     2494 | 2024-04-24 | Sampi             | L   | 0.524      | -            | -                | -                | -         |    -9.35 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     2516 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.517      | -            | -                | -                | -         |     7.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     2530 | 2024-04-22 | Grannys Knockers  | W   | 0.511      | -            | -                | -                | -         |     3.80 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     2550 | 2024-04-21 | Insilio           | W   | 0.504      | -            | -                | -                | -         |     6.88 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     2575 | 2024-04-20 | Nexus             | L   | 0.499      | -            | -                | -                | -         |   -10.24 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     2580 | 2024-04-20 | Passion UA        | W   | 0.498      | 0.371        | 0.172 (0.032)    | -                | -         |     9.53 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     2671 | 2024-04-18 | Passion UA        | L   | 0.485      | -            | -                | -                | -         |    -5.88 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     2682 | 2024-04-18 | Sampi             | L   | 0.484      | -            | -                | -                | -         |    -8.77 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     2700 | 2024-04-17 | PARIVISION        | W   | 0.479      | -            | -                | -                | -         |     9.76 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     2740 | 2024-04-16 | Gaimin Gladiators | L   | 0.472      | -            | -                | -                | -         |    -6.60 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     2802 | 2024-04-12 | MOUZ NXT          | W   | 0.445      | -            | -                | -                | -         |     8.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     2883 | 2024-04-10 | EYEBALLERS        | W   | 0.431      | -            | -                | -                | -         |     5.68 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     2959 | 2024-04-08 | HAVU              | W   | 0.419      | -            | -                | -                | -         |     2.63 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     2970 | 2024-04-08 | JANO              | W   | 0.418      | -            | -                | -                | -         |     2.32 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3097 | 2024-04-03 | Enterprise        | L   | 0.386      | -            | -                | -                | -         |    -6.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3109 | 2024-04-03 | ECLOT             | L   | 0.385      | -            | -                | -                | -         |    -2.48 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3142 | 2024-04-02 | 3DMAX             | L   | 0.379      | -            | -                | -                | -         |    -0.24 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3151 | 2024-04-02 | Sashi             | L   | 0.378      | -            | -                | -                | -         |    -3.29 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3410 | 2024-03-16 | RUBY              | L   | 0.266      | -            | -                | -                | -         |    -4.59 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3429 | 2024-03-15 | The Chosen Few    | W   | 0.259      | -            | -                | -                | -         |     1.45 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3434 | 2024-03-15 | Sampi             | L   | 0.258      | -            | -                | -                | -         |    -4.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3482 | 2024-03-13 | MOUZ NXT          | W   | 0.247      | -            | -                | -                | -         |     4.66 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3498 | 2024-03-13 | ECLOT             | W   | 0.246      | -            | -                | -                | -         |     6.17 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3513 | 2024-03-13 | ECLOT             | W   | 0.244      | -            | -                | -                | -         |     6.23 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3553 | 2024-03-11 | ex-Preasy         | L   | 0.232      | -            | -                | -                | -         |    -5.17 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     3598 | 2024-03-09 | Sashi             | L   | 0.219      | -            | -                | -                | -         |    -1.85 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     3635 | 2024-03-07 | VP.Prodigy        | W   | 0.207      | -            | -                | -                | -         |     2.50 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     3645 | 2024-03-07 | kONO              | W   | 0.205      | -            | -                | -                | -         |     1.95 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     3673 | 2024-03-06 | Passion UA        | W   | 0.199      | -            | -                | -                | -         |     4.29 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     3674 | 2024-03-06 | Enterprise        | W   | 0.199      | -            | -                | -                | -         |     2.91 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     3714 | 2024-03-05 | Young Ninjas      | W   | 0.192      | -            | -                | -                | -         |     1.62 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     3781 | 2024-03-02 | AURA              | W   | 0.172      | -            | -                | -                | -         |     0.41 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     3825 | 2024-02-28 | Secret            | L   | 0.152      | -            | -                | -                | -         |    -4.36 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     3829 | 2024-02-28 | ECLOT             | L   | 0.151      | -            | -                | -                | -         |    -0.86 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     3848 | 2024-02-27 | Sprout            | W   | 0.145      | -            | -                | -                | -         |     0.20 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     3921 | 2024-02-24 | ECLOT             | W   | 0.125      | -            | -                | -                | -         |     3.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     3954 | 2024-02-22 | PGE Turow         | W   | 0.111      | -            | -                | -                | -         |     0.57 | bnox, maaryy, mASKED, morelz, reiko   |
|            3 |     3988 | 2024-02-21 | ECLOT             | L   | 0.104      | -            | -                | -                | -         |    -0.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|            2 |     4033 | 2024-02-19 | ECLOT             | W   | 0.092      | -            | -                | -                | -         |     2.39 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4269 | 2024-02-07 | Endpoint          | L   | 0.012      | -            | -                | -                | -         |    -0.21 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,768.60)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.880 | $5,000.00      | $4,398.84       |
| 2024-06-13 |      0.861 | $545.00        | $468.98         |
| 2024-05-02 |      0.580 | $500.00        | $289.88         |
| 2024-04-25 |      0.531 | $3,000.00      | $1,592.64       |
| 2024-03-25 |      0.326 | $1,250.00      | $408.04         |
| 2024-02-28 |      0.151 | $3,000.00      | $453.47         |
| 2024-02-21 |      0.104 | $1,500.00      | $156.74         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
