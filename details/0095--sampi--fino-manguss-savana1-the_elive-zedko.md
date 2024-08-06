### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  887.7<br />
<br />
Final Rank Value (887.7) = Starting Rank Value (886.4) + Head To Head Adjustments (1.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.373[<sup>2</sup>](#table1)
- Opponent Network: 0.183[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.236<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 886.4
- 400 + ( ( 0.236 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 886.4


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
|           94 |       41 | 2024-08-05 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           93 |      168 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -14.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |      178 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |      208 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -13.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      227 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.44 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      264 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | 0.378 (0.161)    | 0 (0.000) |    16.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      275 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      302 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      323 | 2024-07-28 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      371 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.540 (0.235)    | 0 (0.000) |    12.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      383 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      453 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      484 | 2024-07-23 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.39 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      524 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      535 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      611 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -12.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      659 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      785 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.479 (0.208)    | 0 (0.000) |    15.27 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      800 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      850 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.93 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      854 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | -         |     6.42 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           73 |      915 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    10.98 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      954 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.82 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           71 |     1156 | 2024-06-13 | Rebels            | W   | 0.840      | 0.379        | 0.038 (0.012)    | 0.578 (0.184)    | -         |    17.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1163 | 2024-06-13 | Sashi             | L   | 0.839      | -            | -                | -                | -         |    -3.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1187 | 2024-06-12 | Enterprise        | L   | 0.833      | -            | -                | -                | -         |   -11.08 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1206 | 2024-06-11 | Astralis Talent   | W   | 0.826      | -            | -                | -                | -         |     8.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1216 | 2024-06-11 | Illuminar         | L   | 0.824      | -            | -                | -                | -         |   -12.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1276 | 2024-06-09 | Aurora Young Blud | L   | 0.813      | -            | -                | -                | -         |   -12.87 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           65 |     1345 | 2024-06-08 | MOUZ NXT          | L   | 0.806      | -            | -                | -                | -         |    -6.49 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1364 | 2024-06-08 | CYBERSHOKE        | L   | 0.805      | -            | -                | -                | -         |   -14.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1466 | 2024-06-06 | Nemiga            | L   | 0.793      | -            | -                | -                | -         |    -6.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1482 | 2024-06-06 | HAVU              | W   | 0.792      | -            | -                | -                | -         |     6.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1525 | 2024-06-05 | NAVI Junior       | W   | 0.786      | -            | -                | -                | -         |     6.08 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1562 | 2024-06-04 | INFINITE          | W   | 0.780      | -            | -                | -                | -         |     2.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1582 | 2024-06-04 | DMS               | W   | 0.778      | 0.500        | -                | 0.428 (0.166)    | -         |    14.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1606 | 2024-06-03 | Rare Atom         | W   | 0.771      | 0.435        | -                | 0.465 (0.156)    | -         |     9.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1657 | 2024-06-01 | SINNERS           | L   | 0.759      | -            | -                | -                | -         |    -6.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1678 | 2024-05-31 | ECLOT             | L   | 0.754      | -            | -                | -                | -         |    -4.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1702 | 2024-05-30 | 3DMAX             | L   | 0.747      | -            | -                | -                | -         |    -0.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1755 | 2024-05-28 | Enterprise        | L   | 0.733      | -            | -                | -                | -         |   -11.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1758 | 2024-05-28 | Rhyno             | W   | 0.732      | 0.435        | 0.071 (0.022)    | -                | -         |    13.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1793 | 2024-05-26 | SINNERS           | L   | 0.720      | -            | -                | -                | -         |    -6.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1811 | 2024-05-25 | Passion UA        | L   | 0.713      | -            | -                | -                | -         |    -7.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1842 | 2024-05-23 | GUN5              | W   | 0.700      | 0.435        | 0.072 (0.022)    | 0.550 (0.168)    | -         |    12.08 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1877 | 2024-05-22 | VENI VIDI VICI    | W   | 0.694      | -            | -                | -                | -         |     1.20 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1966 | 2024-05-20 | Illuminar         | W   | 0.680      | -            | -                | -                | -         |    10.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1974 | 2024-05-20 | Verdant           | L   | 0.678      | -            | -                | -                | -         |   -10.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     2029 | 2024-05-18 | DMS               | L   | 0.665      | -            | -                | -                | -         |   -10.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2092 | 2024-05-16 | MOUZ NXT          | L   | 0.653      | -            | -                | -                | -         |    -6.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2100 | 2024-05-16 | B8                | L   | 0.652      | -            | -                | -                | -         |    -5.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2228 | 2024-05-13 | Nexus             | W   | 0.632      | -            | -                | -                | -         |     6.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2316 | 2024-05-09 | BLEED             | L   | 0.607      | -            | -                | -                | -         |    -6.08 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2393 | 2024-05-05 | RUSH B            | W   | 0.580      | -            | -                | -                | -         |     7.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2422 | 2024-05-04 | Endpoint          | L   | 0.571      | -            | -                | -                | -         |    -8.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2454 | 2024-05-02 | Permitta          | W   | 0.560      | 0.435        | -                | 0.919 (0.223)    | -         |     9.65 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2481 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.552      | -            | -                | -                | -         |    -7.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2488 | 2024-05-01 | ENCE Academy      | W   | 0.551      | -            | -                | -                | -         |     4.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2493 | 2024-04-30 | GL Academy        | W   | 0.548      | -            | -                | -                | -         |     4.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2511 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.545      | -            | -                | -                | -         |    -7.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2629 | 2024-04-25 | ECLOT             | L   | 0.511      | -            | -                | -                | -         |    -2.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2648 | 2024-04-24 | Permitta          | W   | 0.504      | 0.371        | -                | 0.919 (0.172)    | -         |     9.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2667 | 2024-04-23 | ECLOT             | L   | 0.498      | -            | -                | -                | -         |    -2.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2703 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.484      | -            | -                | -                | -         |     8.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2777 | 2024-04-19 | BLEED             | L   | 0.472      | -            | -                | -                | -         |    -5.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2836 | 2024-04-18 | Permitta          | W   | 0.464      | 0.371        | -                | 0.919 (0.158)    | -         |     9.00 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2858 | 2024-04-17 | NOM               | L   | 0.459      | -            | -                | -                | -         |   -12.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2896 | 2024-04-16 | SAW               | W   | 0.452      | 0.384        | 0.104 (0.018)    | -                | -         |    11.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2900 | 2024-04-16 | Secret            | W   | 0.451      | -            | -                | -                | -         |     1.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2910 | 2024-04-15 | ENCE Academy      | L   | 0.446      | -            | -                | -                | -         |   -10.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2945 | 2024-04-13 | BetBoom           | L   | 0.432      | -            | -                | -                | -         |    -0.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2989 | 2024-04-11 | PGE Turow         | W   | 0.418      | -            | -                | -                | -         |     2.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3162 | 2024-04-06 | Enterprise        | W   | 0.385      | -            | -                | -                | -         |     6.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3268 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.365      | 0.384        | 0.253 (0.036)    | -                | -         |    11.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3390 | 2024-03-27 | B8                | L   | 0.320      | -            | -                | -                | -         |    -2.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3531 | 2024-03-18 | ex-Preasy         | L   | 0.258      | -            | -                | -                | -         |    -5.21 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3562 | 2024-03-17 | Passion UA        | W   | 0.251      | 0.371        | 0.173 (0.016)    | -                | -         |     5.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3570 | 2024-03-16 | SINNERS           | L   | 0.246      | -            | -                | -                | -         |    -1.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3573 | 2024-03-16 | MOUZ NXT          | W   | 0.245      | 0.371        | 0.139 (0.013)    | -                | -         |     5.33 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3588 | 2024-03-15 | ECLOT             | L   | 0.239      | -            | -                | -                | -         |    -1.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3594 | 2024-03-15 | Permitta          | W   | 0.238      | -            | -                | -                | -         |     4.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3624 | 2024-03-14 | Passion UA        | L   | 0.232      | -            | -                | -                | -         |    -1.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3694 | 2024-03-12 | MOUZ NXT          | W   | 0.218      | -            | -                | -                | -         |     4.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3736 | 2024-03-10 | Sashi             | W   | 0.205      | 0.358        | 0.184 (0.013)    | -                | -         |     5.21 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3762 | 2024-03-09 | Enterprise        | W   | 0.199      | -            | -                | -                | -         |     3.39 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3847 | 2024-03-06 | AURA              | W   | 0.178      | -            | -                | -                | -         |     0.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3893 | 2024-03-04 | Sangal            | L   | 0.165      | -            | -                | -                | -         |    -0.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3947 | 2024-03-02 | Enterprise        | L   | 0.151      | -            | -                | -                | -         |    -2.15 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3985 | 2024-02-28 | Sashi             | L   | 0.133      | -            | -                | -                | -         |    -0.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     4050 | 2024-02-25 | ECLOT             | L   | 0.111      | -            | -                | -                | -         |    -0.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4096 | 2024-02-23 | Entropiq          | W   | 0.098      | -            | -                | -                | -         |     0.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4138 | 2024-02-21 | Sashi             | L   | 0.085      | -            | -                | -                | -         |    -0.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4242 | 2024-02-17 | Secret            | W   | 0.059      | -            | -                | -                | -         |     0.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4389 | 2024-02-10 | Zero Tenacity     | W   | 0.013      | -            | -                | -                | -         |     0.33 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,623.35)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.841 | $3,268.00      | $2,747.09       |
| 2024-06-02 |      0.766 | $653.00        | $500.51         |
| 2024-05-18 |      0.667 | $1,000.00      | $666.81         |
| 2024-04-25 |      0.511 | $5,000.00      | $2,554.86       |
| 2024-04-14 |      0.439 | $1,600.00      | $702.44         |
| 2024-03-18 |      0.258 | $5,000.00      | $1,289.58       |
| 2024-03-17 |      0.254 | $639.00        | $162.06         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
