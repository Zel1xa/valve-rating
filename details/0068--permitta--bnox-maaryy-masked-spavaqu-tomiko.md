### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, mASKED, SpavaQu, tomiko<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  981.5<br />
<br />
Final Rank Value (981.5) = Starting Rank Value (980.4) + Head To Head Adjustments (1.0)<br />

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
|          101 |        7 | 2024-08-06 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.64 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|          100 |       19 | 2024-08-06 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.51 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           99 |       24 | 2024-08-05 | B8                | W   | 1.000      | 0.435        | 0.170 (0.074)    | 0.912 (0.396)    | 0 (0.000) |    23.80 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           98 |       90 | 2024-08-03 | Nemiga            | W   | 1.000      | 0.435        | 0.314 (0.137)    | 0.704 (0.306)    | 0 (0.000) |    23.65 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           97 |      171 | 2024-08-01 | K27               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.81 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |      223 | 2024-07-31 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -19.71 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |      227 | 2024-07-31 | 9INE              | W   | 1.000      | 0.435        | -                | 0.523 (0.227)    | 0 (0.000) |    17.14 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |      271 | 2024-07-30 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |    -8.58 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      294 | 2024-07-29 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.77 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      315 | 2024-07-28 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.74 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |      366 | 2024-07-26 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.25 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           90 |      372 | 2024-07-26 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.46 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           89 |      410 | 2024-07-25 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -24.03 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |      458 | 2024-07-24 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -23.70 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |      509 | 2024-07-22 | Metizport         | W   | 1.000      | 0.435        | -                | 0.510 (0.222)    | 0 (0.000) |    16.57 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |      582 | 2024-07-20 | GUN5              | W   | 1.000      | 0.435        | 0.072 (0.031)    | 0.550 (0.239)    | 0 (0.000) |    15.62 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |      671 | 2024-07-18 | INFINITE          | L   | 1.000      | -            | -                | -                | -         |   -28.02 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |      721 | 2024-07-17 | ALTERNATE aTTaX   | W   | 1.000      | 0.435        | -                | 0.537 (0.233)    | -         |    12.37 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |      800 | 2024-07-16 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -12.10 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |      831 | 2024-07-15 | Space             | L   | 1.000      | -            | -                | -                | -         |   -18.49 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |      859 | 2024-07-14 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -16.07 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |      924 | 2024-07-10 | Passion UA        | W   | 1.000      | 0.371        | 0.173 (0.064)    | 1.000 (0.371)    | -         |    18.44 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           79 |     1052 | 2024-06-16 | 3DMAX             | L   | 0.859      | -            | -                | -                | -         |    -1.62 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           78 |     1096 | 2024-06-15 | BIG               | W   | 0.851      | 0.435        | 0.154 (0.057)    | -                | -         |    23.44 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           77 |     1133 | 2024-06-14 | PARIVISION        | W   | 0.845      | 0.435        | -                | 0.590 (0.217)    | -         |    19.11 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           76 |     1147 | 2024-06-13 | 9INE              | L   | 0.840      | -            | -                | -                | -         |   -23.82 | bnox, maaryy, mASKED, morelz, Vegi    |
|           75 |     1181 | 2024-06-12 | Nexus             | W   | 0.833      | -            | -                | -                | -         |     6.31 | bnox, maaryy, mASKED, morelz, Vegi    |
|           74 |     1197 | 2024-06-11 | Nemiga            | L   | 0.827      | -            | -                | -                | -         |    -5.72 | bnox, maaryy, mASKED, morelz, Vegi    |
|           73 |     1222 | 2024-06-10 | Rebels            | L   | 0.820      | -            | -                | -                | -         |   -10.57 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           72 |     1337 | 2024-06-08 | Space             | W   | 0.807      | -            | -                | -                | -         |    10.52 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           71 |     1468 | 2024-06-06 | Zero Tenacity     | W   | 0.793      | 0.435        | 0.143 (0.049)    | 1.000 (0.344)    | -         |    18.78 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           70 |     1603 | 2024-06-03 | GUN5              | W   | 0.772      | 0.435        | 0.072 (0.024)    | -                | -         |    14.52 | bnox, Markoś, mASKED, morelz, tomiko  |
|           69 |     1661 | 2024-06-01 | Enterprise        | L   | 0.758      | -            | -                | -                | -         |   -12.20 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           68 |     1672 | 2024-05-31 | AMKAL             | L   | 0.754      | -            | -                | -                | -         |    -4.43 | bnox, mASKED, morelz, Sidney, tomiko  |
|           67 |     1705 | 2024-05-30 | NAVI Junior       | W   | 0.746      | -            | -                | -                | -         |     5.80 | bnox, maaryy, mASKED, morelz, tomiko  |
|           66 |     1713 | 2024-05-30 | Serbia            | L   | 0.745      | -            | -                | -                | -         |   -16.40 | bnox, maaryy, mASKED, morelz, tomiko  |
|           65 |     1758 | 2024-05-28 | Preasy            | W   | 0.732      | -            | -                | -                | -         |     6.93 | bnox, maaryy, mASKED, morelz, tomiko  |
|           64 |     1760 | 2024-05-28 | GUN5              | W   | 0.731      | 0.435        | 0.072 (0.023)    | -                | -         |    11.75 | bnox, maaryy, mASKED, morelz, tomiko  |
|           63 |     1778 | 2024-05-27 | VP.Prodigy        | L   | 0.726      | -            | -                | -                | -         |   -12.21 | bnox, maaryy, mASKED, morelz, tomiko  |
|           62 |     1802 | 2024-05-26 | ECLOT             | W   | 0.718      | -            | -                | -                | -         |    17.67 | bnox, maaryy, mASKED, morelz, tomiko  |
|           61 |     1817 | 2024-05-25 | Nexus             | W   | 0.712      | -            | -                | -                | -         |     7.54 | bnox, maaryy, mASKED, morelz, tomiko  |
|           60 |     1887 | 2024-05-22 | Endpoint          | W   | 0.693      | -            | -                | -                | -         |    11.32 | bnox, maaryy, mASKED, morelz, tomiko  |
|           59 |     1901 | 2024-05-22 | Johnny Speeds     | L   | 0.691      | -            | -                | -                | -         |    -2.48 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     1922 | 2024-05-21 | INFINITE          | W   | 0.687      | -            | -                | -                | -         |     2.61 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     1975 | 2024-05-20 | Passion UA        | L   | 0.678      | -            | -                | -                | -         |    -7.03 | bnox, maaryy, mASKED, morelz, Vegi    |
|           56 |     2067 | 2024-05-17 | Sangal            | L   | 0.658      | -            | -                | -                | -         |    -5.18 | bnox, maaryy, mASKED, morelz, Vegi    |
|           55 |     2134 | 2024-05-15 | EYEBALLERS        | L   | 0.647      | -            | -                | -                | -         |   -11.13 | bnox, maaryy, mASKED, morelz, Vegi    |
|           54 |     2219 | 2024-05-13 | 1WIN              | L   | 0.634      | -            | -                | -                | -         |    -8.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           53 |     2366 | 2024-05-07 | Enterprise        | L   | 0.592      | -            | -                | -                | -         |   -10.61 | bnox, maaryy, mASKED, morelz, Sobol   |
|           52 |     2382 | 2024-05-06 | ENCE Academy      | W   | 0.585      | -            | -                | -                | -         |     4.30 | bnox, maaryy, mASKED, morelz, Sobol   |
|           51 |     2426 | 2024-05-03 | Insilio           | L   | 0.566      | -            | -                | -                | -         |    -8.94 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           50 |     2453 | 2024-05-02 | Sampi             | L   | 0.560      | -            | -                | -                | -         |    -9.65 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           49 |     2465 | 2024-05-02 | B8                | L   | 0.558      | -            | -                | -                | -         |    -6.88 | bnox, maaryy, mASKED, morelz, Sobol   |
|           48 |     2513 | 2024-04-30 | BLEED             | L   | 0.545      | -            | -                | -                | -         |    -6.05 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     2521 | 2024-04-29 | AMKAL             | L   | 0.539      | -            | -                | -                | -         |    -4.85 | bnox, maaryy, mASKED, morelz, Vegi    |
|           46 |     2530 | 2024-04-29 | RUBY              | W   | 0.538      | -            | -                | -                | -         |     7.80 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           45 |     2569 | 2024-04-27 | Insilio           | L   | 0.526      | -            | -                | -                | -         |    -9.41 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     2575 | 2024-04-27 | Enterprise        | W   | 0.525      | -            | -                | -                | -         |     6.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     2598 | 2024-04-26 | ARCRED            | L   | 0.518      | -            | -                | -                | -         |    -9.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     2619 | 2024-04-25 | 1WIN              | L   | 0.513      | -            | -                | -                | -         |    -8.81 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     2636 | 2024-04-24 | BLEED             | L   | 0.507      | -            | -                | -                | -         |    -6.65 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     2641 | 2024-04-24 | Passion UA        | W   | 0.506      | 0.384        | 0.173 (0.034)    | 1.000 (0.194)    | -         |     8.94 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     2647 | 2024-04-24 | Sampi             | L   | 0.504      | -            | -                | -                | -         |    -9.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     2669 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.497      | -            | -                | -                | -         |     6.87 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     2683 | 2024-04-22 | Grannys Knockers  | W   | 0.491      | -            | -                | -                | -         |     3.26 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     2703 | 2024-04-21 | Insilio           | W   | 0.484      | -            | -                | -                | -         |     6.13 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     2728 | 2024-04-20 | Nexus             | L   | 0.479      | -            | -                | -                | -         |   -10.30 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     2733 | 2024-04-20 | Passion UA        | W   | 0.478      | 0.371        | 0.173 (0.031)    | -                | -         |     8.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     2824 | 2024-04-18 | Passion UA        | L   | 0.465      | -            | -                | -                | -         |    -5.96 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     2835 | 2024-04-18 | Sampi             | L   | 0.464      | -            | -                | -                | -         |    -9.00 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     2853 | 2024-04-17 | PARIVISION        | W   | 0.459      | -            | -                | -                | -         |     9.62 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     2893 | 2024-04-16 | Gaimin Gladiators | L   | 0.452      | -            | -                | -                | -         |    -7.10 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     2955 | 2024-04-12 | MOUZ NXT          | W   | 0.425      | -            | -                | -                | -         |     7.99 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     3036 | 2024-04-10 | EYEBALLERS        | W   | 0.411      | -            | -                | -                | -         |     4.95 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     3112 | 2024-04-08 | HAVU              | W   | 0.399      | -            | -                | -                | -         |     2.16 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3123 | 2024-04-08 | JANO              | W   | 0.398      | -            | -                | -                | -         |     1.94 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3250 | 2024-04-03 | Enterprise        | L   | 0.366      | -            | -                | -                | -         |    -6.87 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3262 | 2024-04-03 | ECLOT             | L   | 0.365      | -            | -                | -                | -         |    -2.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3295 | 2024-04-02 | 3DMAX             | L   | 0.359      | -            | -                | -                | -         |    -0.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3304 | 2024-04-02 | Sashi             | L   | 0.358      | -            | -                | -                | -         |    -3.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3568 | 2024-03-16 | RUBY              | L   | 0.246      | -            | -                | -                | -         |    -4.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3588 | 2024-03-15 | The Chosen Few    | W   | 0.239      | -            | -                | -                | -         |     1.15 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3593 | 2024-03-15 | Sampi             | L   | 0.238      | -            | -                | -                | -         |    -4.80 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3641 | 2024-03-13 | MOUZ NXT          | W   | 0.228      | -            | -                | -                | -         |     4.10 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3658 | 2024-03-13 | ECLOT             | W   | 0.226      | -            | -                | -                | -         |     5.45 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3673 | 2024-03-13 | ECLOT             | W   | 0.225      | -            | -                | -                | -         |     5.50 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     3714 | 2024-03-11 | ex-Preasy         | L   | 0.212      | -            | -                | -                | -         |    -5.01 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     3759 | 2024-03-09 | Sashi             | L   | 0.199      | -            | -                | -                | -         |    -1.90 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     3796 | 2024-03-07 | VP.Prodigy        | W   | 0.187      | -            | -                | -                | -         |     2.01 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     3806 | 2024-03-07 | kONO              | W   | 0.185      | -            | -                | -                | -         |     1.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     3833 | 2024-03-06 | Passion UA        | W   | 0.179      | -            | -                | -                | -         |     3.68 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     3835 | 2024-03-06 | Enterprise        | W   | 0.179      | -            | -                | -                | -         |     2.34 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     3875 | 2024-03-05 | Young Ninjas      | W   | 0.172      | -            | -                | -                | -         |     1.26 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     3942 | 2024-03-02 | AURA              | W   | 0.152      | -            | -                | -                | -         |     0.29 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     3986 | 2024-02-28 | Secret            | L   | 0.132      | -            | -                | -                | -         |    -3.85 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     3990 | 2024-02-28 | ECLOT             | L   | 0.131      | -            | -                | -                | -         |    -0.88 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     4009 | 2024-02-27 | Sprout            | W   | 0.125      | -            | -                | -                | -         |     0.14 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     4082 | 2024-02-24 | ECLOT             | W   | 0.105      | -            | -                | -                | -         |     2.62 | bnox, maaryy, mASKED, morelz, Vegi    |
|            3 |     4115 | 2024-02-22 | PGE Turow         | W   | 0.091      | -            | -                | -                | -         |     0.39 | bnox, maaryy, mASKED, morelz, reiko   |
|            2 |     4149 | 2024-02-21 | ECLOT             | L   | 0.085      | -            | -                | -                | -         |    -0.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4194 | 2024-02-19 | ECLOT             | W   | 0.072      | -            | -                | -                | -         |     1.80 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,474.07)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.860 | $5,000.00      | $4,299.31       |
| 2024-06-13 |      0.841 | $545.00        | $458.13         |
| 2024-05-02 |      0.560 | $500.00        | $279.93         |
| 2024-04-25 |      0.511 | $3,000.00      | $1,532.92       |
| 2024-03-25 |      0.307 | $1,250.00      | $383.16         |
| 2024-02-28 |      0.131 | $3,000.00      | $393.75         |
| 2024-02-21 |      0.085 | $1,500.00      | $126.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
