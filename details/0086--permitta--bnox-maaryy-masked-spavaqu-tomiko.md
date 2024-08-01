### Roster Details<br />
Team Name: Permitta<br />
Roster: bnox, maaryy, mASKED, SpavaQu, tomiko<br />
Global Rank: [86](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  912.6<br />
<br />
Final Rank Value (912.6) = Starting Rank Value (932.0) + Head To Head Adjustments (-19.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.241[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 932.0
- 400 + ( ( 0.259 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 932.0


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
|          100 |       59 | 2024-07-31 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -18.52 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           99 |       63 | 2024-07-31 | 9INE              | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |    18.55 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           98 |      106 | 2024-07-30 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |    -8.65 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           97 |      130 | 2024-07-29 | HAVU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.50 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           96 |      151 | 2024-07-28 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.63 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           95 |      202 | 2024-07-26 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.67 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           94 |      208 | 2024-07-26 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.97 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           93 |      246 | 2024-07-25 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -23.53 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           92 |      294 | 2024-07-24 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -23.35 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           91 |      346 | 2024-07-22 | Metizport         | W   | 1.000      | 0.435        | -                | 0.424 (0.184)    | 0 (0.000) |    16.78 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           90 |      421 | 2024-07-20 | GUN5              | W   | 1.000      | 0.435        | 0.074 (0.032)    | 0.555 (0.241)    | 0 (0.000) |    17.01 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           89 |      516 | 2024-07-18 | INFINITE          | L   | 1.000      | -            | -                | -                | -         |   -27.73 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           88 |      566 | 2024-07-17 | ALTERNATE aTTaX   | W   | 1.000      | 0.435        | -                | 0.563 (0.245)    | 0 (0.000) |    11.98 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           87 |      650 | 2024-07-16 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -12.14 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           86 |      682 | 2024-07-15 | Space             | L   | 1.000      | -            | -                | -                | -         |   -17.96 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           85 |      712 | 2024-07-14 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -15.48 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           84 |      777 | 2024-07-10 | Passion UA        | W   | 1.000      | 0.371        | 0.173 (0.064)    | 1.000 (0.371)    | 0 (0.000) |    18.23 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           83 |      903 | 2024-06-16 | 3DMAX             | L   | 0.892      | -            | -                | -                | -         |    -1.66 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           82 |      944 | 2024-06-15 | BIG               | W   | 0.884      | 0.435        | 0.132 (0.051)    | -                | 0 (0.000) |    23.67 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           81 |      975 | 2024-06-14 | PARIVISION        | W   | 0.878      | -            | -                | -                | 0 (0.000) |    19.69 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           80 |      989 | 2024-06-13 | 9INE              | L   | 0.873      | -            | -                | -                | -         |   -24.44 | bnox, maaryy, mASKED, morelz, Vegi    |
|           79 |     1023 | 2024-06-12 | Nexus             | W   | 0.866      | -            | -                | -                | -         |     6.95 | bnox, maaryy, mASKED, morelz, Vegi    |
|           78 |     1040 | 2024-06-11 | Nemiga            | L   | 0.860      | -            | -                | -                | -         |    -5.87 | bnox, maaryy, mASKED, morelz, Vegi    |
|           77 |     1066 | 2024-06-10 | Rebels            | L   | 0.853      | -            | -                | -                | -         |   -10.08 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           76 |     1183 | 2024-06-08 | Space             | W   | 0.840      | -            | -                | -                | -         |    11.77 | bnox, maaryy, mASKED, SpavaQu, tomiko |
|           75 |     1323 | 2024-06-06 | Zero Tenacity     | W   | 0.826      | 0.435        | 0.139 (0.050)    | 1.000 (0.359)    | -         |    19.65 | bnox, Markoś, mASKED, SpavaQu, tomiko |
|           74 |     1461 | 2024-06-03 | GUN5              | W   | 0.805      | 0.435        | 0.074 (0.026)    | 0.555 (0.194)    | -         |    16.49 | bnox, Markoś, mASKED, morelz, tomiko  |
|           73 |     1520 | 2024-06-01 | Enterprise        | L   | 0.791      | -            | -                | -                | -         |   -12.13 | bnox, mASKED, morelz, SpavaQu, tomiko |
|           72 |     1531 | 2024-05-31 | AMKAL             | L   | 0.787      | -            | -                | -                | -         |    -4.13 | bnox, mASKED, morelz, Sidney, tomiko  |
|           71 |     1564 | 2024-05-30 | NAVI Junior       | W   | 0.779      | -            | -                | -                | -         |     3.07 | bnox, maaryy, mASKED, morelz, tomiko  |
|           70 |     1572 | 2024-05-30 | Serbia            | L   | 0.778      | -            | -                | -                | -         |   -16.50 | bnox, maaryy, mASKED, morelz, tomiko  |
|           69 |     1617 | 2024-05-28 | Preasy            | W   | 0.765      | -            | -                | -                | -         |     8.01 | bnox, maaryy, mASKED, morelz, tomiko  |
|           68 |     1619 | 2024-05-28 | GUN5              | W   | 0.764      | 0.435        | 0.074 (0.025)    | -                | -         |    13.71 | bnox, maaryy, mASKED, morelz, tomiko  |
|           67 |     1637 | 2024-05-27 | VP.Prodigy        | L   | 0.759      | -            | -                | -                | -         |   -11.87 | bnox, maaryy, mASKED, morelz, tomiko  |
|           66 |     1663 | 2024-05-26 | ECLOT             | W   | 0.751      | -            | -                | -                | -         |    16.97 | bnox, maaryy, mASKED, morelz, tomiko  |
|           65 |     1678 | 2024-05-25 | Nexus             | W   | 0.745      | -            | -                | -                | -         |     8.50 | bnox, maaryy, mASKED, morelz, tomiko  |
|           64 |     1748 | 2024-05-22 | Endpoint          | W   | 0.726      | -            | -                | -                | -         |    12.89 | bnox, maaryy, mASKED, morelz, tomiko  |
|           63 |     1772 | 2024-05-22 | Johnny Speeds     | L   | 0.724      | -            | -                | -                | -         |    -2.35 | bnox, maaryy, mASKED, morelz, Vegi    |
|           62 |     1797 | 2024-05-21 | INFINITE          | W   | 0.720      | -            | -                | -                | -         |     3.08 | bnox, maaryy, mASKED, morelz, Vegi    |
|           61 |     1856 | 2024-05-20 | Passion UA        | L   | 0.711      | -            | -                | -                | -         |    -7.38 | bnox, maaryy, mASKED, morelz, Vegi    |
|           60 |     1954 | 2024-05-17 | Sangal            | L   | 0.691      | -            | -                | -                | -         |    -5.68 | bnox, maaryy, mASKED, morelz, Vegi    |
|           59 |     2021 | 2024-05-15 | EYEBALLERS        | L   | 0.680      | -            | -                | -                | -         |   -10.91 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     2115 | 2024-05-13 | 1WIN              | L   | 0.666      | -            | -                | -                | -         |    -9.02 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     2264 | 2024-05-07 | Enterprise        | L   | 0.624      | -            | -                | -                | -         |   -10.72 | bnox, maaryy, mASKED, morelz, Sobol   |
|           56 |     2280 | 2024-05-06 | ENCE Academy      | W   | 0.618      | -            | -                | -                | -         |     4.95 | bnox, maaryy, mASKED, morelz, Sobol   |
|           55 |     2324 | 2024-05-03 | Insilio           | L   | 0.599      | -            | -                | -                | -         |    -8.76 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           54 |     2352 | 2024-05-02 | Sampi             | L   | 0.593      | -            | -                | -                | -         |    -9.73 | bnox, maaryy, mASKED, Sidney, Sobol   |
|           53 |     2364 | 2024-05-02 | B8                | L   | 0.591      | -            | -                | -                | -         |    -6.82 | bnox, maaryy, mASKED, morelz, Sobol   |
|           52 |     2414 | 2024-04-30 | BLEED             | L   | 0.578      | -            | -                | -                | -         |    -5.83 | bnox, maaryy, mASKED, morelz, Vegi    |
|           51 |     2422 | 2024-04-29 | AMKAL             | L   | 0.572      | -            | -                | -                | -         |    -4.55 | bnox, maaryy, mASKED, morelz, Vegi    |
|           50 |     2431 | 2024-04-29 | RUBY              | W   | 0.571      | 0.435        | 0.097 (0.024)    | -                | -         |     9.17 | bnox, maaryy, mASKED, Sidney, Vegi    |
|           49 |     2468 | 2024-04-27 | MOUZ NXT          | L   | 0.559      | -            | -                | -                | -         |    -6.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           48 |     2471 | 2024-04-27 | Insilio           | L   | 0.559      | -            | -                | -                | -         |    -9.49 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     2477 | 2024-04-27 | Enterprise        | W   | 0.558      | -            | -                | -                | -         |     7.32 | bnox, maaryy, mASKED, morelz, Vegi    |
|           46 |     2499 | 2024-04-26 | ARCRED            | L   | 0.551      | -            | -                | -                | -         |   -11.09 | bnox, maaryy, mASKED, morelz, Vegi    |
|           45 |     2520 | 2024-04-25 | 1WIN              | L   | 0.546      | -            | -                | -                | -         |    -9.61 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     2537 | 2024-04-24 | BLEED             | L   | 0.540      | -            | -                | -                | -         |    -6.66 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     2542 | 2024-04-24 | Passion UA        | W   | 0.539      | 0.384        | 0.173 (0.036)    | 1.000 (0.207)    | -         |     9.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     2548 | 2024-04-24 | Sampi             | L   | 0.537      | -            | -                | -                | -         |    -9.87 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     2573 | 2024-04-23 | ALTERNATE aTTaX   | W   | 0.530      | -            | -                | -                | -         |     7.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     2587 | 2024-04-22 | Grannys Knockers  | W   | 0.524      | -            | -                | -                | -         |     4.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     2588 | 2024-04-22 | MOUZ NXT          | W   | 0.524      | 0.371        | 0.141 (0.027)    | 1.000 (0.194)    | -         |    10.24 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     2608 | 2024-04-21 | Insilio           | W   | 0.517      | -            | -                | -                | -         |     7.29 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     2635 | 2024-04-20 | Nexus             | L   | 0.512      | -            | -                | -                | -         |   -10.29 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     2640 | 2024-04-20 | Passion UA        | W   | 0.511      | 0.371        | 0.173 (0.033)    | 1.000 (0.189)    | -         |    10.07 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     2733 | 2024-04-18 | Passion UA        | L   | 0.498      | -            | -                | -                | -         |    -5.73 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     2744 | 2024-04-18 | Sampi             | L   | 0.497      | -            | -                | -                | -         |    -9.02 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     2763 | 2024-04-17 | PARIVISION        | W   | 0.492      | -            | -                | -                | -         |    10.24 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     2804 | 2024-04-16 | Gaimin Gladiators | L   | 0.485      | -            | -                | -                | -         |    -6.30 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     2867 | 2024-04-12 | MOUZ NXT          | W   | 0.458      | -            | -                | -                | -         |     9.52 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     2948 | 2024-04-10 | EYEBALLERS        | W   | 0.444      | -            | -                | -                | -         |     6.12 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     3024 | 2024-04-08 | HAVU              | W   | 0.432      | -            | -                | -                | -         |     2.91 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     3035 | 2024-04-08 | JANO              | W   | 0.431      | -            | -                | -                | -         |     2.60 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     3164 | 2024-04-03 | Enterprise        | L   | 0.399      | -            | -                | -                | -         |    -6.71 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     3180 | 2024-04-03 | ECLOT             | L   | 0.398      | -            | -                | -                | -         |    -3.79 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     3215 | 2024-04-02 | 3DMAX             | L   | 0.392      | -            | -                | -                | -         |    -0.23 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     3224 | 2024-04-02 | Sashi             | L   | 0.391      | -            | -                | -                | -         |    -3.33 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     3493 | 2024-03-16 | RUBY              | L   | 0.279      | -            | -                | -                | -         |    -4.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     3513 | 2024-03-15 | The Chosen Few    | W   | 0.272      | -            | -                | -                | -         |     1.62 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     3518 | 2024-03-15 | Sampi             | L   | 0.271      | -            | -                | -                | -         |    -4.93 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     3571 | 2024-03-13 | MOUZ NXT          | W   | 0.260      | -            | -                | -                | -         |     5.28 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     3587 | 2024-03-13 | ECLOT             | W   | 0.259      | -            | -                | -                | -         |     5.65 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     3602 | 2024-03-13 | ECLOT             | W   | 0.258      | -            | -                | -                | -         |     5.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     3644 | 2024-03-11 | ex-Preasy         | L   | 0.245      | -            | -                | -                | -         |    -5.29 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     3690 | 2024-03-09 | Sashi             | L   | 0.232      | -            | -                | -                | -         |    -1.84 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     3727 | 2024-03-07 | VP.Prodigy        | W   | 0.220      | -            | -                | -                | -         |     2.78 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     3737 | 2024-03-07 | kONO              | W   | 0.218      | -            | -                | -                | -         |     2.23 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     3765 | 2024-03-06 | Passion UA        | W   | 0.212      | -            | -                | -                | -         |     4.73 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     3766 | 2024-03-06 | Enterprise        | W   | 0.212      | -            | -                | -                | -         |     3.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     3811 | 2024-03-05 | Young Ninjas      | W   | 0.205      | -            | -                | -                | -         |     1.86 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     3878 | 2024-03-02 | AURA              | W   | 0.185      | -            | -                | -                | -         |     0.48 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     3924 | 2024-02-28 | Secret            | L   | 0.165      | -            | -                | -                | -         |    -4.70 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     3928 | 2024-02-28 | ECLOT             | L   | 0.164      | -            | -                | -                | -         |    -1.45 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     3947 | 2024-02-27 | Sprout            | W   | 0.158      | -            | -                | -                | -         |     0.23 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     3963 | 2024-02-26 | MOUZ NXT          | W   | 0.152      | -            | -                | -                | -         |     3.22 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     4024 | 2024-02-24 | ECLOT             | W   | 0.138      | -            | -                | -                | -         |     3.16 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     4060 | 2024-02-22 | PGE Turow         | W   | 0.124      | -            | -                | -                | -         |     0.69 | bnox, maaryy, mASKED, morelz, reiko   |
|            3 |     4095 | 2024-02-21 | ECLOT             | L   | 0.117      | -            | -                | -                | -         |    -1.02 | bnox, maaryy, mASKED, morelz, Vegi    |
|            2 |     4140 | 2024-02-19 | ECLOT             | W   | 0.105      | -            | -                | -                | -         |     2.42 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     4387 | 2024-02-07 | Endpoint          | L   | 0.025      | -            | -                | -                | -         |    -0.41 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,961.07)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.893 | $5,000.00      | $4,463.89       |
| 2024-06-13 |      0.874 | $545.00        | $476.07         |
| 2024-05-02 |      0.593 | $500.00        | $296.39         |
| 2024-04-25 |      0.544 | $3,000.00      | $1,631.67       |
| 2024-03-25 |      0.339 | $1,250.00      | $424.31         |
| 2024-02-28 |      0.164 | $3,000.00      | $492.50         |
| 2024-02-21 |      0.117 | $1,500.00      | $176.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
