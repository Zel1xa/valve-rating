### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, mASKED, SpavaQu, tomiko<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  939.5<br />
<br />
Final Rank Value (939.5) = Starting Rank Value (944.2) + Head To Head Adjustments (-4.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.381[<sup>1</sup>](#table2)
- Bounty Collected: 0.431[<sup>2</sup>](#table1)
- Opponent Network: 0.253[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 944.2
- 400 + ( ( 0.266 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 944.2


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
|           99 |        7 | 2024-08-03 | Nemiga            | W   | 1.000      | 0.435        | 0.318 (0.138)    | 0.695 (0.302)    | 0 (0.000) |    23.80 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           98 |       87 | 2024-08-01 | K27               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.15 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           97 |      138 | 2024-07-31 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -19.35 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |      141 | 2024-07-31 | 9INE              | W   | 1.000      | 0.435        | -                | 0.535 (0.233)    | 0 (0.000) |    17.61 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |      185 | 2024-07-30 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |    -8.88 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |      209 | 2024-07-29 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.34 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      230 | 2024-07-28 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.94 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      281 | 2024-07-26 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.57 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |      288 | 2024-07-26 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.56 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           90 |      325 | 2024-07-25 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -23.72 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           89 |      373 | 2024-07-24 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -23.50 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |      424 | 2024-07-22 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.66 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |      497 | 2024-07-20 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.569 (0.247)    | 0 (0.000) |    16.15 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |      584 | 2024-07-18 | INFINITE          | L   | 1.000      | -            | -                | -                | -         |   -27.80 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |      639 | 2024-07-17 | ALTERNATE aTTaX   | W   | 1.000      | 0.435        | -                | 0.561 (0.244)    | 0 (0.000) |    12.58 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |      715 | 2024-07-16 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.99 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |      746 | 2024-07-15 | Space             | L   | 1.000      | -            | -                | -                | -         |   -18.09 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |      774 | 2024-07-14 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -15.72 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |      838 | 2024-07-10 | Passion UA        | W   | 1.000      | 0.371        | 0.172 (0.064)    | 1.000 (0.371)    | 0 (0.000) |    18.41 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |      966 | 2024-06-16 | 3DMAX             | L   | 0.877      | -            | -                | -                | -         |    -1.63 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           79 |     1010 | 2024-06-15 | BIG               | W   | 0.869      | 0.435        | 0.155 (0.059)    | -                | -         |    24.24 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           78 |     1047 | 2024-06-14 | PARIVISION        | W   | 0.863      | 0.435        | -                | 0.534 (0.200)    | -         |    19.13 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           77 |     1061 | 2024-06-13 | 9INE              | L   | 0.859      | -            | -                | -                | -         |   -24.15 | bnox, maaryy, mASKED, morelz, Vegi    |
|           76 |     1095 | 2024-06-12 | Nexus             | W   | 0.852      | -            | -                | -                | -         |     6.72 | bnox, maaryy, mASKED, morelz, Vegi    |
|           75 |     1111 | 2024-06-11 | Nemiga            | L   | 0.845      | -            | -                | -                | -         |    -5.78 | bnox, maaryy, mASKED, morelz, Vegi    |
|           74 |     1136 | 2024-06-10 | Rebels            | L   | 0.839      | -            | -                | -                | -         |   -10.23 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           73 |     1251 | 2024-06-08 | Space             | W   | 0.825      | -            | -                | -                | -         |    11.35 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           72 |     1382 | 2024-06-06 | Zero Tenacity     | W   | 0.811      | 0.435        | 0.137 (0.048)    | 1.000 (0.352)    | -         |    19.52 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           71 |     1517 | 2024-06-03 | GUN5              | W   | 0.790      | 0.435        | 0.073 (0.025)    | 0.569 (0.195)    | -         |    15.35 | bnox, Markoś, mASKED, morelz, tomiko  |
|           70 |     1575 | 2024-06-01 | Enterprise        | L   | 0.776      | -            | -                | -                | -         |   -11.97 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           69 |     1586 | 2024-05-31 | AMKAL             | L   | 0.772      | -            | -                | -                | -         |    -4.12 | bnox, mASKED, morelz, Sidney, tomiko  |
|           68 |     1619 | 2024-05-30 | NAVI Junior       | W   | 0.764      | -            | -                | -                | -         |     2.92 | bnox, maaryy, mASKED, morelz, tomiko  |
|           67 |     1627 | 2024-05-30 | Serbia            | L   | 0.763      | -            | -                | -                | -         |   -16.38 | bnox, maaryy, mASKED, morelz, tomiko  |
|           66 |     1672 | 2024-05-28 | Preasy            | W   | 0.750      | -            | -                | -                | -         |     7.69 | bnox, maaryy, mASKED, morelz, tomiko  |
|           65 |     1674 | 2024-05-28 | GUN5              | W   | 0.749      | 0.435        | 0.073 (0.024)    | 0.569 (0.185)    | -         |    12.49 | bnox, maaryy, mASKED, morelz, tomiko  |
|           64 |     1692 | 2024-05-27 | VP.Prodigy        | L   | 0.744      | -            | -                | -                | -         |   -11.96 | bnox, maaryy, mASKED, morelz, tomiko  |
|           63 |     1716 | 2024-05-26 | ECLOT             | W   | 0.736      | -            | -                | -                | -         |    18.39 | bnox, maaryy, mASKED, morelz, tomiko  |
|           62 |     1731 | 2024-05-25 | Nexus             | W   | 0.730      | -            | -                | -                | -         |     8.15 | bnox, maaryy, mASKED, morelz, tomiko  |
|           61 |     1801 | 2024-05-22 | Endpoint          | W   | 0.711      | -            | -                | -                | -         |    12.09 | bnox, maaryy, mASKED, morelz, tomiko  |
|           60 |     1815 | 2024-05-22 | Johnny Speeds     | L   | 0.709      | -            | -                | -                | -         |    -2.43 | bnox, maaryy, mASKED, morelz, Vegi    |
|           59 |     1836 | 2024-05-21 | INFINITE          | W   | 0.705      | -            | -                | -                | -         |     2.94 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     1889 | 2024-05-20 | Passion UA        | L   | 0.696      | -            | -                | -                | -         |    -7.09 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     1981 | 2024-05-17 | Sangal            | L   | 0.676      | -            | -                | -                | -         |    -5.51 | bnox, maaryy, mASKED, morelz, Vegi    |
|           56 |     2048 | 2024-05-15 | EYEBALLERS        | L   | 0.665      | -            | -                | -                | -         |   -10.88 | bnox, maaryy, mASKED, morelz, Vegi    |
|           55 |     2133 | 2024-05-13 | 1WIN              | L   | 0.652      | -            | -                | -                | -         |    -9.08 | bnox, maaryy, mASKED, morelz, Vegi    |
|           54 |     2280 | 2024-05-07 | Enterprise        | L   | 0.610      | -            | -                | -                | -         |   -10.47 | bnox, maaryy, mASKED, morelz, Sobol   |
|           53 |     2296 | 2024-05-06 | ENCE Academy      | W   | 0.603      | -            | -                | -                | -         |     4.83 | bnox, maaryy, mASKED, morelz, Sobol   |
|           52 |     2340 | 2024-05-03 | Insilio           | L   | 0.584      | -            | -                | -                | -         |    -8.78 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           51 |     2367 | 2024-05-02 | Sampi             | L   | 0.578      | -            | -                | -                | -         |    -9.40 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           50 |     2379 | 2024-05-02 | B8                | L   | 0.576      | -            | -                | -                | -         |    -6.70 | bnox, maaryy, mASKED, morelz, Sobol   |
|           49 |     2427 | 2024-04-30 | BLEED             | L   | 0.563      | -            | -                | -                | -         |    -5.70 | bnox, maaryy, mASKED, morelz, Vegi    |
|           48 |     2435 | 2024-04-29 | AMKAL             | L   | 0.557      | -            | -                | -                | -         |    -4.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     2444 | 2024-04-29 | RUBY              | W   | 0.556      | 0.435        | 0.095 (0.023)    | -                | -         |     8.57 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           46 |     2483 | 2024-04-27 | Insilio           | L   | 0.544      | -            | -                | -                | -         |    -9.29 | bnox, maaryy, mASKED, morelz, Vegi    |
|           45 |     2489 | 2024-04-27 | Enterprise        | W   | 0.543      | -            | -                | -                | -         |     7.28 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     2511 | 2024-04-26 | ARCRED            | L   | 0.536      | -            | -                | -                | -         |   -10.59 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     2532 | 2024-04-25 | 1WIN              | L   | 0.531      | -            | -                | -                | -         |    -9.39 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     2549 | 2024-04-24 | BLEED             | L   | 0.525      | -            | -                | -                | -         |    -6.31 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     2554 | 2024-04-24 | Passion UA        | W   | 0.524      | 0.384        | 0.172 (0.035)    | 1.000 (0.201)    | -         |     9.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     2560 | 2024-04-24 | Sampi             | L   | 0.522      | -            | -                | -                | -         |    -9.36 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     2582 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.516      | -            | -                | -                | -         |     7.53 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     2596 | 2024-04-22 | Grannys Knockers  | W   | 0.509      | -            | -                | -                | -         |     3.79 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     2616 | 2024-04-21 | Insilio           | W   | 0.502      | -            | -                | -                | -         |     6.82 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     2641 | 2024-04-20 | Nexus             | L   | 0.497      | -            | -                | -                | -         |   -10.26 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     2646 | 2024-04-20 | Passion UA        | W   | 0.496      | 0.371        | 0.172 (0.032)    | -                | -         |     9.49 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     2737 | 2024-04-18 | Passion UA        | L   | 0.484      | -            | -                | -                | -         |    -5.87 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     2748 | 2024-04-18 | Sampi             | L   | 0.482      | -            | -                | -                | -         |    -8.78 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     2766 | 2024-04-17 | PARIVISION        | W   | 0.478      | -            | -                | -                | -         |     9.68 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     2806 | 2024-04-16 | Gaimin Gladiators | L   | 0.470      | -            | -                | -                | -         |    -6.63 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     2868 | 2024-04-12 | MOUZ NXT          | W   | 0.443      | -            | -                | -                | -         |     8.75 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     2949 | 2024-04-10 | EYEBALLERS        | W   | 0.429      | -            | -                | -                | -         |     5.68 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     3025 | 2024-04-08 | HAVU              | W   | 0.417      | -            | -                | -                | -         |     2.61 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     3036 | 2024-04-08 | JANO              | W   | 0.416      | -            | -                | -                | -         |     2.31 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3163 | 2024-04-03 | Enterprise        | L   | 0.385      | -            | -                | -                | -         |    -6.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3175 | 2024-04-03 | ECLOT             | L   | 0.383      | -            | -                | -                | -         |    -2.49 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3208 | 2024-04-02 | 3DMAX             | L   | 0.377      | -            | -                | -                | -         |    -0.24 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3217 | 2024-04-02 | Sashi             | L   | 0.376      | -            | -                | -                | -         |    -3.40 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3481 | 2024-03-16 | RUBY              | L   | 0.265      | -            | -                | -                | -         |    -4.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3501 | 2024-03-15 | The Chosen Few    | W   | 0.258      | -            | -                | -                | -         |     1.44 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3506 | 2024-03-15 | Sampi             | L   | 0.256      | -            | -                | -                | -         |    -4.83 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3554 | 2024-03-13 | MOUZ NXT          | W   | 0.246      | -            | -                | -                | -         |     4.70 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3570 | 2024-03-13 | ECLOT             | W   | 0.244      | -            | -                | -                | -         |     6.11 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3585 | 2024-03-13 | ECLOT             | W   | 0.243      | -            | -                | -                | -         |     6.17 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3626 | 2024-03-11 | ex-Preasy         | L   | 0.230      | -            | -                | -                | -         |    -5.12 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     3671 | 2024-03-09 | Sashi             | L   | 0.217      | -            | -                | -                | -         |    -1.85 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     3708 | 2024-03-07 | VP.Prodigy        | W   | 0.205      | -            | -                | -                | -         |     2.47 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     3718 | 2024-03-07 | kONO              | W   | 0.203      | -            | -                | -                | -         |     1.94 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     3745 | 2024-03-06 | Passion UA        | W   | 0.198      | -            | -                | -                | -         |     4.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     3747 | 2024-03-06 | Enterprise        | W   | 0.197      | -            | -                | -                | -         |     2.87 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     3787 | 2024-03-05 | Young Ninjas      | W   | 0.191      | -            | -                | -                | -         |     1.60 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     3854 | 2024-03-02 | AURA              | W   | 0.170      | -            | -                | -                | -         |     0.41 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     3898 | 2024-02-28 | Secret            | L   | 0.151      | -            | -                | -                | -         |    -4.31 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     3902 | 2024-02-28 | ECLOT             | L   | 0.149      | -            | -                | -                | -         |    -0.86 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     3921 | 2024-02-27 | Sprout            | W   | 0.143      | -            | -                | -                | -         |     0.20 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     3994 | 2024-02-24 | ECLOT             | W   | 0.123      | -            | -                | -                | -         |     3.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     4027 | 2024-02-22 | PGE Turow         | W   | 0.109      | -            | -                | -                | -         |     0.56 | bnox, maaryy, mASKED, morelz, reiko   |
|            3 |     4061 | 2024-02-21 | ECLOT             | L   | 0.103      | -            | -                | -                | -         |    -0.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|            2 |     4106 | 2024-02-19 | ECLOT             | W   | 0.090      | -            | -                | -                | -         |     2.34 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4342 | 2024-02-07 | Endpoint          | L   | 0.010      | -            | -                | -                | -         |    -0.18 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,743.25)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.878 | $5,000.00      | $4,390.28       |
| 2024-06-13 |      0.859 | $545.00        | $468.04         |
| 2024-05-02 |      0.578 | $500.00        | $289.03         |
| 2024-04-25 |      0.529 | $3,000.00      | $1,587.50       |
| 2024-03-25 |      0.325 | $1,250.00      | $405.90         |
| 2024-02-28 |      0.149 | $3,000.00      | $448.33         |
| 2024-02-21 |      0.103 | $1,500.00      | $154.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
