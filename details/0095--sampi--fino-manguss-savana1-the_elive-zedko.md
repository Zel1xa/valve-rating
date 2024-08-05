### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  878.0<br />
<br />
Final Rank Value (878.0) = Starting Rank Value (884.9) + Head To Head Adjustments (-6.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.237<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 884.9
- 400 + ( ( 0.237 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 884.9


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
|           94 |       15 | 2024-08-05 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           93 |      142 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -14.39 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |      152 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |      182 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.00 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      201 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      238 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    17.09 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      249 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      276 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      297 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.361 (0.157)    | 0 (0.000) |    13.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      345 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.514 (0.223)    | 0 (0.000) |    12.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      357 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.34 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      427 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      458 | 2024-07-23 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.361 (0.157)    | 0 (0.000) |    13.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      498 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      509 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.34 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      585 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -18.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      633 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.39 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      759 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.492 (0.214)    | 0 (0.000) |    15.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      774 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      824 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.87 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      828 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | -         |     6.59 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           73 |      889 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.20 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      928 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.88 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           71 |     1130 | 2024-06-13 | Rebels            | W   | 0.846      | 0.379        | 0.038 (0.012)    | 0.591 (0.190)    | -         |    17.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1137 | 2024-06-13 | Sashi             | L   | 0.845      | -            | -                | -                | -         |    -3.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1161 | 2024-06-12 | Enterprise        | L   | 0.839      | -            | -                | -                | -         |   -11.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1180 | 2024-06-11 | Astralis Talent   | W   | 0.833      | -            | -                | -                | -         |     8.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1190 | 2024-06-11 | Illuminar         | L   | 0.831      | -            | -                | -                | -         |   -12.49 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1250 | 2024-06-09 | Aurora Young Blud | L   | 0.819      | -            | -                | -                | -         |   -13.87 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           65 |     1319 | 2024-06-08 | MOUZ NXT          | L   | 0.813      | -            | -                | -                | -         |    -6.53 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1338 | 2024-06-08 | CYBERSHOKE        | L   | 0.811      | -            | -                | -                | -         |   -14.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1440 | 2024-06-06 | Nemiga            | L   | 0.799      | -            | -                | -                | -         |    -6.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1456 | 2024-06-06 | HAVU              | W   | 0.798      | -            | -                | -                | -         |     6.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1499 | 2024-06-05 | NAVI Junior       | W   | 0.793      | -            | -                | -                | -         |     2.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1536 | 2024-06-04 | INFINITE          | W   | 0.787      | -            | -                | -                | -         |     2.94 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1556 | 2024-06-04 | DMS               | W   | 0.784      | 0.500        | -                | 0.438 (0.172)    | -         |    14.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1580 | 2024-06-03 | Rare Atom         | W   | 0.777      | 0.435        | -                | 0.474 (0.160)    | -         |     9.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1631 | 2024-06-01 | SINNERS           | L   | 0.765      | -            | -                | -                | -         |    -6.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1652 | 2024-05-31 | ECLOT             | L   | 0.760      | -            | -                | -                | -         |    -5.00 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1676 | 2024-05-30 | 3DMAX             | L   | 0.754      | -            | -                | -                | -         |    -0.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1729 | 2024-05-28 | Enterprise        | L   | 0.739      | -            | -                | -                | -         |   -11.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1732 | 2024-05-28 | Rhyno             | W   | 0.739      | 0.435        | 0.071 (0.023)    | -                | -         |    14.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1767 | 2024-05-26 | SINNERS           | L   | 0.726      | -            | -                | -                | -         |    -6.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1785 | 2024-05-25 | Passion UA        | L   | 0.719      | -            | -                | -                | -         |    -7.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1816 | 2024-05-23 | GUN5              | W   | 0.707      | 0.435        | 0.073 (0.022)    | 0.562 (0.173)    | -         |    12.15 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1851 | 2024-05-22 | VENI VIDI VICI    | W   | 0.701      | -            | -                | -                | -         |     1.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1940 | 2024-05-20 | Illuminar         | W   | 0.686      | -            | -                | -                | -         |    10.94 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1948 | 2024-05-20 | Verdant           | L   | 0.685      | -            | -                | -                | -         |   -10.37 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     2003 | 2024-05-18 | DMS               | L   | 0.672      | -            | -                | -                | -         |   -10.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2066 | 2024-05-16 | MOUZ NXT          | L   | 0.659      | -            | -                | -                | -         |    -6.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2074 | 2024-05-16 | B8                | L   | 0.658      | -            | -                | -                | -         |    -5.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2202 | 2024-05-13 | Nexus             | W   | 0.638      | -            | -                | -                | -         |     6.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2290 | 2024-05-09 | BLEED             | L   | 0.614      | -            | -                | -                | -         |    -6.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2367 | 2024-05-05 | RUSH B            | W   | 0.586      | -            | -                | -                | -         |     7.99 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2396 | 2024-05-04 | Endpoint          | L   | 0.578      | -            | -                | -                | -         |    -8.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2428 | 2024-05-02 | Permitta          | W   | 0.566      | 0.435        | -                | 0.863 (0.212)    | -         |     9.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2455 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.559      | -            | -                | -                | -         |    -7.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2462 | 2024-05-01 | ENCE Academy      | W   | 0.558      | -            | -                | -                | -         |     4.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2467 | 2024-04-30 | GL Academy        | W   | 0.554      | -            | -                | -                | -         |     4.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2485 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.551      | -            | -                | -                | -         |    -7.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2603 | 2024-04-25 | ECLOT             | L   | 0.517      | -            | -                | -                | -         |    -2.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2622 | 2024-04-24 | Permitta          | W   | 0.511      | 0.371        | -                | 0.863 (0.163)    | -         |     9.19 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2641 | 2024-04-23 | ECLOT             | L   | 0.505      | -            | -                | -                | -         |    -2.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2677 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.491      | -            | -                | -                | -         |     8.60 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2751 | 2024-04-19 | BLEED             | L   | 0.478      | -            | -                | -                | -         |    -5.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2810 | 2024-04-18 | Permitta          | W   | 0.471      | -            | -                | -                | -         |     8.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2832 | 2024-04-17 | NOM               | L   | 0.465      | -            | -                | -                | -         |   -13.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2870 | 2024-04-16 | SAW               | W   | 0.458      | 0.384        | 0.105 (0.018)    | -                | -         |    11.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2874 | 2024-04-16 | Secret            | W   | 0.458      | -            | -                | -                | -         |     1.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2884 | 2024-04-15 | ENCE Academy      | L   | 0.453      | -            | -                | -                | -         |   -10.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2919 | 2024-04-13 | BetBoom           | L   | 0.438      | -            | -                | -                | -         |    -0.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2963 | 2024-04-11 | PGE Turow         | W   | 0.424      | -            | -                | -                | -         |     2.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3136 | 2024-04-06 | Enterprise        | W   | 0.391      | -            | -                | -                | -         |     6.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3242 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.371      | 0.384        | 0.254 (0.036)    | -                | -         |    11.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3364 | 2024-03-27 | B8                | L   | 0.327      | -            | -                | -                | -         |    -2.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3505 | 2024-03-18 | ex-Preasy         | L   | 0.264      | -            | -                | -                | -         |    -5.32 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3536 | 2024-03-17 | Passion UA        | W   | 0.258      | 0.371        | 0.173 (0.017)    | -                | -         |     5.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3544 | 2024-03-16 | SINNERS           | L   | 0.253      | -            | -                | -                | -         |    -1.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3547 | 2024-03-16 | MOUZ NXT          | W   | 0.251      | 0.371        | 0.139 (0.013)    | -                | -         |     5.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3562 | 2024-03-15 | ECLOT             | L   | 0.246      | -            | -                | -                | -         |    -1.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3568 | 2024-03-15 | Permitta          | W   | 0.244      | -            | -                | -                | -         |     4.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3598 | 2024-03-14 | Passion UA        | L   | 0.239      | -            | -                | -                | -         |    -1.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3668 | 2024-03-12 | MOUZ NXT          | W   | 0.224      | -            | -                | -                | -         |     5.00 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3710 | 2024-03-10 | Sashi             | W   | 0.212      | 0.358        | 0.184 (0.014)    | -                | -         |     5.37 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3736 | 2024-03-09 | Enterprise        | W   | 0.205      | -            | -                | -                | -         |     3.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3821 | 2024-03-06 | AURA              | W   | 0.184      | -            | -                | -                | -         |     0.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3867 | 2024-03-04 | Sangal            | L   | 0.172      | -            | -                | -                | -         |    -0.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3921 | 2024-03-02 | Enterprise        | L   | 0.158      | -            | -                | -                | -         |    -2.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3959 | 2024-02-28 | Sashi             | L   | 0.139      | -            | -                | -                | -         |    -0.81 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     4024 | 2024-02-25 | ECLOT             | L   | 0.118      | -            | -                | -                | -         |    -0.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4070 | 2024-02-23 | Entropiq          | W   | 0.104      | -            | -                | -                | -         |     0.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4112 | 2024-02-21 | Sashi             | L   | 0.092      | -            | -                | -                | -         |    -0.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4216 | 2024-02-17 | Secret            | W   | 0.065      | -            | -                | -                | -         |     0.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4363 | 2024-02-10 | Zero Tenacity     | W   | 0.020      | -            | -                | -                | -         |     0.49 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,735.37)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.847 | $3,268.00      | $2,768.42       |
| 2024-06-02 |      0.773 | $653.00        | $504.78         |
| 2024-05-18 |      0.673 | $1,000.00      | $673.33         |
| 2024-04-25 |      0.517 | $5,000.00      | $2,587.50       |
| 2024-04-14 |      0.446 | $1,600.00      | $712.89         |
| 2024-03-18 |      0.264 | $5,000.00      | $1,322.22       |
| 2024-03-17 |      0.260 | $639.00        | $166.23         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
