### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, mASKED, SpavaQu, tomiko<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  942.0<br />
<br />
Final Rank Value (942.0) = Starting Rank Value (944.8) + Head To Head Adjustments (-2.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.381[<sup>1</sup>](#table2)
- Bounty Collected: 0.431[<sup>2</sup>](#table1)
- Opponent Network: 0.254[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 944.8
- 400 + ( ( 0.266 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 944.8


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
|           99 |       40 | 2024-08-03 | Nemiga            | W   | 1.000      | 0.435        | 0.317 (0.138)    | 0.734 (0.319)    | 0 (0.000) |    24.05 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           98 |      121 | 2024-08-01 | K27               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.11 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           97 |      173 | 2024-07-31 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -19.54 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |      176 | 2024-07-31 | 9INE              | W   | 1.000      | 0.435        | -                | 0.537 (0.234)    | 0 (0.000) |    17.59 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |      220 | 2024-07-30 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |    -8.85 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |      244 | 2024-07-29 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.27 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      265 | 2024-07-28 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.80 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      316 | 2024-07-26 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.51 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |      322 | 2024-07-26 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.42 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           90 |      360 | 2024-07-25 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -23.59 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           89 |      408 | 2024-07-24 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -23.28 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |      459 | 2024-07-22 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.39 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |      532 | 2024-07-20 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.570 (0.248)    | 0 (0.000) |    16.14 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |      621 | 2024-07-18 | INFINITE          | L   | 1.000      | -            | -                | -                | -         |   -27.82 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |      671 | 2024-07-17 | ALTERNATE aTTaX   | W   | 1.000      | 0.435        | -                | 0.560 (0.243)    | 0 (0.000) |    12.73 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |      750 | 2024-07-16 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.79 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |      781 | 2024-07-15 | Space             | L   | 1.000      | -            | -                | -                | -         |   -18.41 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |      809 | 2024-07-14 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -15.73 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |      874 | 2024-07-10 | Passion UA        | W   | 1.000      | 0.371        | 0.172 (0.064)    | 1.000 (0.371)    | 0 (0.000) |    18.62 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |     1002 | 2024-06-16 | 3DMAX             | L   | 0.872      | -            | -                | -                | -         |    -1.60 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           79 |     1046 | 2024-06-15 | BIG               | W   | 0.864      | 0.435        | 0.155 (0.058)    | -                | -         |    24.08 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           78 |     1083 | 2024-06-14 | PARIVISION        | W   | 0.859      | 0.435        | -                | 0.534 (0.199)    | -         |    19.08 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           77 |     1097 | 2024-06-13 | 9INE              | L   | 0.854      | -            | -                | -                | -         |   -24.04 | bnox, maaryy, mASKED, morelz, Vegi    |
|           76 |     1131 | 2024-06-12 | Nexus             | W   | 0.847      | -            | -                | -                | -         |     6.66 | bnox, maaryy, mASKED, morelz, Vegi    |
|           75 |     1147 | 2024-06-11 | Nemiga            | L   | 0.840      | -            | -                | -                | -         |    -5.45 | bnox, maaryy, mASKED, morelz, Vegi    |
|           74 |     1172 | 2024-06-10 | Rebels            | L   | 0.834      | -            | -                | -                | -         |   -10.19 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           73 |     1287 | 2024-06-08 | Space             | W   | 0.820      | -            | -                | -                | -         |    10.99 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           72 |     1418 | 2024-06-06 | Zero Tenacity     | W   | 0.806      | 0.435        | 0.137 (0.048)    | 1.000 (0.350)    | -         |    19.37 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           71 |     1553 | 2024-06-03 | GUN5              | W   | 0.785      | 0.435        | 0.073 (0.025)    | 0.570 (0.194)    | -         |    15.25 | bnox, Markoś, mASKED, morelz, tomiko  |
|           70 |     1611 | 2024-06-01 | Enterprise        | L   | 0.771      | -            | -                | -                | -         |   -11.93 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           69 |     1622 | 2024-05-31 | AMKAL             | L   | 0.767      | -            | -                | -                | -         |    -4.14 | bnox, mASKED, morelz, Sidney, tomiko  |
|           68 |     1655 | 2024-05-30 | NAVI Junior       | W   | 0.760      | -            | -                | -                | -         |     2.87 | bnox, maaryy, mASKED, morelz, tomiko  |
|           67 |     1663 | 2024-05-30 | Serbia            | L   | 0.758      | -            | -                | -                | -         |   -16.34 | bnox, maaryy, mASKED, morelz, tomiko  |
|           66 |     1708 | 2024-05-28 | Preasy            | W   | 0.745      | -            | -                | -                | -         |     7.60 | bnox, maaryy, mASKED, morelz, tomiko  |
|           65 |     1710 | 2024-05-28 | GUN5              | W   | 0.745      | 0.435        | 0.073 (0.024)    | 0.570 (0.184)    | -         |    12.38 | bnox, maaryy, mASKED, morelz, tomiko  |
|           64 |     1728 | 2024-05-27 | VP.Prodigy        | L   | 0.740      | -            | -                | -                | -         |   -11.90 | bnox, maaryy, mASKED, morelz, tomiko  |
|           63 |     1752 | 2024-05-26 | ECLOT             | W   | 0.731      | -            | -                | -                | -         |    18.30 | bnox, maaryy, mASKED, morelz, tomiko  |
|           62 |     1767 | 2024-05-25 | Nexus             | W   | 0.725      | -            | -                | -                | -         |     8.04 | bnox, maaryy, mASKED, morelz, tomiko  |
|           61 |     1837 | 2024-05-22 | Endpoint          | W   | 0.706      | -            | -                | -                | -         |    11.99 | bnox, maaryy, mASKED, morelz, tomiko  |
|           60 |     1851 | 2024-05-22 | Johnny Speeds     | L   | 0.704      | -            | -                | -                | -         |    -2.35 | bnox, maaryy, mASKED, morelz, Vegi    |
|           59 |     1872 | 2024-05-21 | INFINITE          | W   | 0.700      | -            | -                | -                | -         |     2.89 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     1925 | 2024-05-20 | Passion UA        | L   | 0.691      | -            | -                | -                | -         |    -6.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     2017 | 2024-05-17 | Sangal            | L   | 0.671      | -            | -                | -                | -         |    -5.40 | bnox, maaryy, mASKED, morelz, Vegi    |
|           56 |     2084 | 2024-05-15 | EYEBALLERS        | L   | 0.660      | -            | -                | -                | -         |   -10.99 | bnox, maaryy, mASKED, morelz, Vegi    |
|           55 |     2169 | 2024-05-13 | 1WIN              | L   | 0.647      | -            | -                | -                | -         |    -8.42 | bnox, maaryy, mASKED, morelz, Vegi    |
|           54 |     2316 | 2024-05-07 | Enterprise        | L   | 0.605      | -            | -                | -                | -         |   -10.40 | bnox, maaryy, mASKED, morelz, Sobol   |
|           53 |     2332 | 2024-05-06 | ENCE Academy      | W   | 0.598      | -            | -                | -                | -         |     4.77 | bnox, maaryy, mASKED, morelz, Sobol   |
|           52 |     2376 | 2024-05-03 | Insilio           | L   | 0.580      | -            | -                | -                | -         |    -8.72 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           51 |     2403 | 2024-05-02 | Sampi             | L   | 0.573      | -            | -                | -                | -         |    -9.35 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           50 |     2415 | 2024-05-02 | B8                | L   | 0.571      | -            | -                | -                | -         |    -6.63 | bnox, maaryy, mASKED, morelz, Sobol   |
|           49 |     2463 | 2024-04-30 | BLEED             | L   | 0.558      | -            | -                | -                | -         |    -5.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           48 |     2471 | 2024-04-29 | AMKAL             | L   | 0.553      | -            | -                | -                | -         |    -4.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     2480 | 2024-04-29 | RUBY              | W   | 0.551      | 0.435        | 0.095 (0.023)    | -                | -         |     8.34 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           46 |     2519 | 2024-04-27 | Insilio           | L   | 0.539      | -            | -                | -                | -         |    -9.22 | bnox, maaryy, mASKED, morelz, Vegi    |
|           45 |     2525 | 2024-04-27 | Enterprise        | W   | 0.538      | -            | -                | -                | -         |     7.20 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     2548 | 2024-04-26 | ARCRED            | L   | 0.532      | -            | -                | -                | -         |   -10.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     2569 | 2024-04-25 | 1WIN              | L   | 0.526      | -            | -                | -                | -         |    -8.71 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     2586 | 2024-04-24 | BLEED             | L   | 0.520      | -            | -                | -                | -         |    -6.26 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     2591 | 2024-04-24 | Passion UA        | W   | 0.519      | 0.384        | 0.172 (0.034)    | 1.000 (0.200)    | -         |     9.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     2597 | 2024-04-24 | Sampi             | L   | 0.518      | -            | -                | -                | -         |    -9.27 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     2619 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.511      | -            | -                | -                | -         |     7.48 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     2633 | 2024-04-22 | Grannys Knockers  | W   | 0.505      | -            | -                | -                | -         |     3.75 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     2653 | 2024-04-21 | Insilio           | W   | 0.498      | -            | -                | -                | -         |     6.77 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     2678 | 2024-04-20 | Nexus             | L   | 0.492      | -            | -                | -                | -         |   -10.15 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     2683 | 2024-04-20 | Passion UA        | W   | 0.491      | 0.371        | 0.172 (0.031)    | -                | -         |     9.48 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     2774 | 2024-04-18 | Passion UA        | L   | 0.479      | -            | -                | -                | -         |    -5.72 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     2785 | 2024-04-18 | Sampi             | L   | 0.478      | -            | -                | -                | -         |    -8.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     2803 | 2024-04-17 | PARIVISION        | W   | 0.473      | -            | -                | -                | -         |     9.61 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     2843 | 2024-04-16 | Gaimin Gladiators | L   | 0.465      | -            | -                | -                | -         |    -6.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     2905 | 2024-04-12 | MOUZ NXT          | W   | 0.438      | -            | -                | -                | -         |     8.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     2986 | 2024-04-10 | EYEBALLERS        | W   | 0.425      | -            | -                | -                | -         |     5.59 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     3062 | 2024-04-08 | HAVU              | W   | 0.412      | -            | -                | -                | -         |     2.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     3073 | 2024-04-08 | JANO              | W   | 0.411      | -            | -                | -                | -         |     2.28 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3200 | 2024-04-03 | Enterprise        | L   | 0.380      | -            | -                | -                | -         |    -6.65 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3212 | 2024-04-03 | ECLOT             | L   | 0.378      | -            | -                | -                | -         |    -2.44 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3245 | 2024-04-02 | 3DMAX             | L   | 0.372      | -            | -                | -                | -         |    -0.23 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3254 | 2024-04-02 | Sashi             | L   | 0.371      | -            | -                | -                | -         |    -3.31 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3518 | 2024-03-16 | RUBY              | L   | 0.260      | -            | -                | -                | -         |    -4.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3538 | 2024-03-15 | The Chosen Few    | W   | 0.253      | -            | -                | -                | -         |     1.41 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3543 | 2024-03-15 | Sampi             | L   | 0.251      | -            | -                | -                | -         |    -4.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3591 | 2024-03-13 | MOUZ NXT          | W   | 0.241      | -            | -                | -                | -         |     4.62 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3608 | 2024-03-13 | ECLOT             | W   | 0.239      | -            | -                | -                | -         |     6.00 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3623 | 2024-03-13 | ECLOT             | W   | 0.238      | -            | -                | -                | -         |     6.05 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3664 | 2024-03-11 | ex-Preasy         | L   | 0.225      | -            | -                | -                | -         |    -5.04 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     3709 | 2024-03-09 | Sashi             | L   | 0.212      | -            | -                | -                | -         |    -1.79 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     3746 | 2024-03-07 | VP.Prodigy        | W   | 0.200      | -            | -                | -                | -         |     2.41 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     3756 | 2024-03-07 | kONO              | W   | 0.198      | -            | -                | -                | -         |     1.90 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     3783 | 2024-03-06 | Passion UA        | W   | 0.193      | -            | -                | -                | -         |     4.17 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     3785 | 2024-03-06 | Enterprise        | W   | 0.192      | -            | -                | -                | -         |     2.80 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     3825 | 2024-03-05 | Young Ninjas      | W   | 0.186      | -            | -                | -                | -         |     1.54 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     3892 | 2024-03-02 | AURA              | W   | 0.165      | -            | -                | -                | -         |     0.39 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     3936 | 2024-02-28 | Secret            | L   | 0.146      | -            | -                | -                | -         |    -4.17 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     3940 | 2024-02-28 | ECLOT             | L   | 0.145      | -            | -                | -                | -         |    -0.83 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     3959 | 2024-02-27 | Sprout            | W   | 0.138      | -            | -                | -                | -         |     0.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     4032 | 2024-02-24 | ECLOT             | W   | 0.119      | -            | -                | -                | -         |     3.07 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     4065 | 2024-02-22 | PGE Turow         | W   | 0.105      | -            | -                | -                | -         |     0.53 | bnox, maaryy, mASKED, morelz, reiko   |
|            3 |     4099 | 2024-02-21 | ECLOT             | L   | 0.098      | -            | -                | -                | -         |    -0.55 | bnox, maaryy, mASKED, morelz, Vegi    |
|            2 |     4144 | 2024-02-19 | ECLOT             | W   | 0.085      | -            | -                | -                | -         |     2.22 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4381 | 2024-02-07 | Endpoint          | L   | 0.005      | -            | -                | -                | -         |    -0.09 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,671.67)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.873 | $5,000.00      | $4,366.09       |
| 2024-06-13 |      0.854 | $545.00        | $465.41         |
| 2024-05-02 |      0.573 | $500.00        | $286.61         |
| 2024-04-25 |      0.524 | $3,000.00      | $1,572.99       |
| 2024-03-25 |      0.320 | $1,250.00      | $399.86         |
| 2024-02-28 |      0.145 | $3,000.00      | $433.82         |
| 2024-02-21 |      0.098 | $1,500.00      | $146.91         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
