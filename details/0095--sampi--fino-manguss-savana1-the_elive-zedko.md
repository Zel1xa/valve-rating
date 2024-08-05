### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  876.4<br />
<br />
Final Rank Value (876.4) = Starting Rank Value (885.6) + Head To Head Adjustments (-9.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.184[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.237<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 885.6
- 400 + ( ( 0.237 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 885.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           94 |        6 | 2024-08-05 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.81 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           93 |      134 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -14.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |      144 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |      174 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.49 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      193 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      230 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    17.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      241 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.20 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      268 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      289 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.365 (0.159)    | 0 (0.000) |    13.09 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      337 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.520 (0.226)    | 0 (0.000) |    12.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      349 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.33 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      419 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.37 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      450 | 2024-07-23 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.365 (0.159)    | 0 (0.000) |    13.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      490 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      501 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.37 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      577 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -18.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      625 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -16.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      751 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.499 (0.217)    | 0 (0.000) |    15.16 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      766 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      816 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.87 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      820 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | -         |     6.61 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           73 |      881 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.22 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      920 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.89 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           71 |     1122 | 2024-06-13 | Rebels            | W   | 0.847      | 0.379        | 0.038 (0.012)    | 0.598 (0.192)    | -         |    17.90 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1129 | 2024-06-13 | Sashi             | L   | 0.847      | -            | -                | -                | -         |    -3.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1153 | 2024-06-12 | Enterprise        | L   | 0.841      | -            | -                | -                | -         |   -11.12 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1172 | 2024-06-11 | Astralis Talent   | W   | 0.834      | -            | -                | -                | -         |     8.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1182 | 2024-06-11 | Illuminar         | L   | 0.832      | -            | -                | -                | -         |   -12.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1242 | 2024-06-09 | Aurora Young Blud | L   | 0.820      | -            | -                | -                | -         |   -14.60 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           65 |     1311 | 2024-06-08 | MOUZ NXT          | L   | 0.814      | -            | -                | -                | -         |    -6.55 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1330 | 2024-06-08 | CYBERSHOKE        | L   | 0.812      | -            | -                | -                | -         |   -14.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1432 | 2024-06-06 | Nemiga            | L   | 0.801      | -            | -                | -                | -         |    -6.19 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1448 | 2024-06-06 | HAVU              | W   | 0.799      | -            | -                | -                | -         |     6.27 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1491 | 2024-06-05 | NAVI Junior       | W   | 0.794      | -            | -                | -                | -         |     2.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1528 | 2024-06-04 | INFINITE          | W   | 0.788      | -            | -                | -                | -         |     2.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1548 | 2024-06-04 | DMS               | W   | 0.786      | 0.500        | -                | 0.444 (0.174)    | -         |    14.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1572 | 2024-06-03 | Rare Atom         | W   | 0.779      | 0.435        | -                | 0.480 (0.162)    | -         |     9.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1623 | 2024-06-01 | SINNERS           | L   | 0.766      | -            | -                | -                | -         |    -6.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1644 | 2024-05-31 | ECLOT             | L   | 0.761      | -            | -                | -                | -         |    -5.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1668 | 2024-05-30 | 3DMAX             | L   | 0.755      | -            | -                | -                | -         |    -0.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1721 | 2024-05-28 | Enterprise        | L   | 0.741      | -            | -                | -                | -         |   -11.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1724 | 2024-05-28 | Rhyno             | W   | 0.740      | 0.435        | 0.071 (0.023)    | -                | -         |    14.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1759 | 2024-05-26 | SINNERS           | L   | 0.727      | -            | -                | -                | -         |    -6.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1777 | 2024-05-25 | Passion UA        | L   | 0.721      | -            | -                | -                | -         |    -7.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1808 | 2024-05-23 | GUN5              | W   | 0.708      | 0.435        | 0.073 (0.022)    | 0.569 (0.175)    | -         |    12.14 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1843 | 2024-05-22 | VENI VIDI VICI    | W   | 0.702      | -            | -                | -                | -         |     1.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1932 | 2024-05-20 | Illuminar         | W   | 0.687      | -            | -                | -                | -         |    10.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1940 | 2024-05-20 | Verdant           | L   | 0.686      | -            | -                | -                | -         |   -10.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     1995 | 2024-05-18 | DMS               | L   | 0.673      | -            | -                | -                | -         |   -10.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2058 | 2024-05-16 | MOUZ NXT          | L   | 0.660      | -            | -                | -                | -         |    -6.85 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2066 | 2024-05-16 | B8                | L   | 0.659      | -            | -                | -                | -         |    -5.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2194 | 2024-05-13 | Nexus             | W   | 0.639      | -            | -                | -                | -         |     6.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2282 | 2024-05-09 | BLEED             | L   | 0.615      | -            | -                | -                | -         |    -6.15 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2359 | 2024-05-05 | RUSH B            | W   | 0.588      | -            | -                | -                | -         |     7.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2388 | 2024-05-04 | Endpoint          | L   | 0.579      | -            | -                | -                | -         |    -8.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2420 | 2024-05-02 | Permitta          | W   | 0.567      | 0.435        | -                | 0.873 (0.215)    | -         |     9.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2447 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.560      | -            | -                | -                | -         |    -7.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2454 | 2024-05-01 | ENCE Academy      | W   | 0.559      | -            | -                | -                | -         |     4.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2459 | 2024-04-30 | GL Academy        | W   | 0.555      | -            | -                | -                | -         |     4.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2477 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.552      | -            | -                | -                | -         |    -7.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2595 | 2024-04-25 | ECLOT             | L   | 0.519      | -            | -                | -                | -         |    -2.90 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2614 | 2024-04-24 | Permitta          | W   | 0.512      | 0.371        | -                | 0.873 (0.166)    | -         |     9.19 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2633 | 2024-04-23 | ECLOT             | L   | 0.506      | -            | -                | -                | -         |    -2.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2669 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.492      | -            | -                | -                | -         |     8.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2743 | 2024-04-19 | BLEED             | L   | 0.479      | -            | -                | -                | -         |    -5.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2802 | 2024-04-18 | Permitta          | W   | 0.472      | -            | -                | -                | -         |     8.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2824 | 2024-04-17 | NOM               | L   | 0.466      | -            | -                | -                | -         |   -13.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2862 | 2024-04-16 | SAW               | W   | 0.459      | 0.384        | 0.105 (0.018)    | -                | -         |    11.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2866 | 2024-04-16 | Secret            | W   | 0.459      | -            | -                | -                | -         |     1.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2876 | 2024-04-15 | ENCE Academy      | L   | 0.454      | -            | -                | -                | -         |   -10.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2911 | 2024-04-13 | BetBoom           | L   | 0.439      | -            | -                | -                | -         |    -0.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2955 | 2024-04-11 | PGE Turow         | W   | 0.425      | -            | -                | -                | -         |     2.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3128 | 2024-04-06 | Enterprise        | W   | 0.393      | -            | -                | -                | -         |     6.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3234 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.372      | 0.384        | 0.254 (0.036)    | -                | -         |    11.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3356 | 2024-03-27 | B8                | L   | 0.328      | -            | -                | -                | -         |    -2.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3497 | 2024-03-18 | ex-Preasy         | L   | 0.266      | -            | -                | -                | -         |    -5.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3528 | 2024-03-17 | Passion UA        | W   | 0.259      | 0.371        | 0.173 (0.017)    | -                | -         |     5.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3536 | 2024-03-16 | SINNERS           | L   | 0.254      | -            | -                | -                | -         |    -1.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3539 | 2024-03-16 | MOUZ NXT          | W   | 0.252      | 0.371        | 0.139 (0.013)    | -                | -         |     5.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3554 | 2024-03-15 | ECLOT             | L   | 0.247      | -            | -                | -                | -         |    -1.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3560 | 2024-03-15 | Permitta          | W   | 0.246      | -            | -                | -                | -         |     4.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3590 | 2024-03-14 | Passion UA        | L   | 0.240      | -            | -                | -                | -         |    -2.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3660 | 2024-03-12 | MOUZ NXT          | W   | 0.226      | -            | -                | -                | -         |     5.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3702 | 2024-03-10 | Sashi             | W   | 0.213      | 0.358        | 0.184 (0.014)    | -                | -         |     5.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3728 | 2024-03-09 | Enterprise        | W   | 0.206      | -            | -                | -                | -         |     3.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3813 | 2024-03-06 | AURA              | W   | 0.186      | -            | -                | -                | -         |     0.60 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3859 | 2024-03-04 | Sangal            | L   | 0.173      | -            | -                | -                | -         |    -0.99 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3913 | 2024-03-02 | Enterprise        | L   | 0.159      | -            | -                | -                | -         |    -2.27 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3951 | 2024-02-28 | Sashi             | L   | 0.140      | -            | -                | -                | -         |    -0.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     4016 | 2024-02-25 | ECLOT             | L   | 0.119      | -            | -                | -                | -         |    -0.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4062 | 2024-02-23 | Entropiq          | W   | 0.106      | -            | -                | -                | -         |     0.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4104 | 2024-02-21 | Sashi             | L   | 0.093      | -            | -                | -                | -         |    -0.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4208 | 2024-02-17 | Secret            | W   | 0.066      | -            | -                | -                | -         |     0.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4355 | 2024-02-10 | Zero Tenacity     | W   | 0.021      | -            | -                | -                | -         |     0.51 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,754.43)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.848 | $3,268.00      | $2,772.05       |
| 2024-06-02 |      0.774 | $653.00        | $505.50         |
| 2024-05-18 |      0.674 | $1,000.00      | $674.44         |
| 2024-04-25 |      0.519 | $5,000.00      | $2,593.06       |
| 2024-04-14 |      0.447 | $1,600.00      | $714.67         |
| 2024-03-18 |      0.266 | $5,000.00      | $1,327.78       |
| 2024-03-17 |      0.261 | $639.00        | $166.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
