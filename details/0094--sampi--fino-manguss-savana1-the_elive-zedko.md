### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  884.6<br />
<br />
Final Rank Value (884.6) = Starting Rank Value (885.3) + Head To Head Adjustments (-0.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.181[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.236<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 885.3
- 400 + ( ( 0.236 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 885.3


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
|           94 |       28 | 2024-08-05 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           93 |      155 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -14.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |      165 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |      195 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -13.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      214 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      251 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    16.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      262 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.08 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      289 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      310 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.353 (0.154)    | 0 (0.000) |    12.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      358 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.502 (0.218)    | 0 (0.000) |    12.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      370 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      440 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      471 | 2024-07-23 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      511 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.20 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      522 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      598 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -12.85 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      646 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      772 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.480 (0.208)    | 0 (0.000) |    15.34 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      787 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.60 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      837 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.86 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      841 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | -         |     6.54 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           73 |      902 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.15 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      941 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.86 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           71 |     1143 | 2024-06-13 | Rebels            | W   | 0.841      | 0.379        | 0.038 (0.012)    | 0.578 (0.184)    | -         |    17.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1150 | 2024-06-13 | Sashi             | L   | 0.840      | -            | -                | -                | -         |    -3.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1174 | 2024-06-12 | Enterprise        | L   | 0.834      | -            | -                | -                | -         |   -11.00 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1193 | 2024-06-11 | Astralis Talent   | W   | 0.827      | -            | -                | -                | -         |     8.21 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1203 | 2024-06-11 | Illuminar         | L   | 0.826      | -            | -                | -                | -         |   -12.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1263 | 2024-06-09 | Aurora Young Blud | L   | 0.814      | -            | -                | -                | -         |   -12.74 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           65 |     1332 | 2024-06-08 | MOUZ NXT          | L   | 0.807      | -            | -                | -                | -         |    -6.48 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1351 | 2024-06-08 | CYBERSHOKE        | L   | 0.806      | -            | -                | -                | -         |   -14.67 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1453 | 2024-06-06 | Nemiga            | L   | 0.794      | -            | -                | -                | -         |    -6.16 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1469 | 2024-06-06 | HAVU              | W   | 0.793      | -            | -                | -                | -         |     6.20 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1512 | 2024-06-05 | NAVI Junior       | W   | 0.787      | -            | -                | -                | -         |     2.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1549 | 2024-06-04 | INFINITE          | W   | 0.782      | -            | -                | -                | -         |     2.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1569 | 2024-06-04 | DMS               | W   | 0.779      | 0.500        | -                | 0.428 (0.167)    | -         |    14.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1593 | 2024-06-03 | Rare Atom         | W   | 0.772      | 0.435        | -                | 0.464 (0.156)    | -         |     9.93 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1644 | 2024-06-01 | SINNERS           | L   | 0.760      | -            | -                | -                | -         |    -6.27 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1665 | 2024-05-31 | ECLOT             | L   | 0.755      | -            | -                | -                | -         |    -4.93 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1689 | 2024-05-30 | 3DMAX             | L   | 0.748      | -            | -                | -                | -         |    -0.60 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1742 | 2024-05-28 | Enterprise        | L   | 0.734      | -            | -                | -                | -         |   -11.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1745 | 2024-05-28 | Rhyno             | W   | 0.733      | 0.435        | 0.071 (0.023)    | -                | -         |    13.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1780 | 2024-05-26 | SINNERS           | L   | 0.721      | -            | -                | -                | -         |    -6.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1798 | 2024-05-25 | Passion UA        | L   | 0.714      | -            | -                | -                | -         |    -7.19 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1829 | 2024-05-23 | GUN5              | W   | 0.702      | 0.435        | 0.072 (0.022)    | 0.550 (0.168)    | -         |    12.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1864 | 2024-05-22 | VENI VIDI VICI    | W   | 0.695      | -            | -                | -                | -         |     1.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1953 | 2024-05-20 | Illuminar         | W   | 0.681      | -            | -                | -                | -         |    10.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1961 | 2024-05-20 | Verdant           | L   | 0.679      | -            | -                | -                | -         |   -10.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     2016 | 2024-05-18 | DMS               | L   | 0.666      | -            | -                | -                | -         |   -10.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2079 | 2024-05-16 | MOUZ NXT          | L   | 0.654      | -            | -                | -                | -         |    -6.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2087 | 2024-05-16 | B8                | L   | 0.653      | -            | -                | -                | -         |    -5.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2215 | 2024-05-13 | Nexus             | W   | 0.633      | -            | -                | -                | -         |     6.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2303 | 2024-05-09 | BLEED             | L   | 0.608      | -            | -                | -                | -         |    -6.11 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2380 | 2024-05-05 | RUSH B            | W   | 0.581      | -            | -                | -                | -         |     7.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2409 | 2024-05-04 | Endpoint          | L   | 0.572      | -            | -                | -                | -         |    -8.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2441 | 2024-05-02 | Permitta          | W   | 0.561      | 0.435        | -                | 0.919 (0.224)    | -         |     9.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2468 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.553      | -            | -                | -                | -         |    -7.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2475 | 2024-05-01 | ENCE Academy      | W   | 0.553      | -            | -                | -                | -         |     4.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2480 | 2024-04-30 | GL Academy        | W   | 0.549      | -            | -                | -                | -         |     4.90 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2498 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.546      | -            | -                | -                | -         |    -7.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2616 | 2024-04-25 | ECLOT             | L   | 0.512      | -            | -                | -                | -         |    -2.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2635 | 2024-04-24 | Permitta          | W   | 0.505      | 0.371        | -                | 0.919 (0.172)    | -         |     9.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2654 | 2024-04-23 | ECLOT             | L   | 0.499      | -            | -                | -                | -         |    -2.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2690 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.485      | -            | -                | -                | -         |     8.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2764 | 2024-04-19 | BLEED             | L   | 0.473      | -            | -                | -                | -         |    -5.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2823 | 2024-04-18 | Permitta          | W   | 0.465      | 0.371        | -                | 0.919 (0.158)    | -         |     8.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2845 | 2024-04-17 | NOM               | L   | 0.460      | -            | -                | -                | -         |   -12.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2883 | 2024-04-16 | SAW               | W   | 0.453      | 0.384        | 0.104 (0.018)    | -                | -         |    11.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2887 | 2024-04-16 | Secret            | W   | 0.452      | -            | -                | -                | -         |     1.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2897 | 2024-04-15 | ENCE Academy      | L   | 0.447      | -            | -                | -                | -         |   -10.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2932 | 2024-04-13 | BetBoom           | L   | 0.433      | -            | -                | -                | -         |    -0.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2976 | 2024-04-11 | PGE Turow         | W   | 0.419      | -            | -                | -                | -         |     2.49 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3149 | 2024-04-06 | Enterprise        | W   | 0.386      | -            | -                | -                | -         |     6.20 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3255 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.366      | 0.384        | 0.254 (0.036)    | -                | -         |    11.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3377 | 2024-03-27 | B8                | L   | 0.322      | -            | -                | -                | -         |    -2.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3518 | 2024-03-18 | ex-Preasy         | L   | 0.259      | -            | -                | -                | -         |    -5.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3549 | 2024-03-17 | Passion UA        | W   | 0.252      | 0.371        | 0.173 (0.016)    | -                | -         |     5.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3557 | 2024-03-16 | SINNERS           | L   | 0.247      | -            | -                | -                | -         |    -1.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3560 | 2024-03-16 | MOUZ NXT          | W   | 0.246      | 0.371        | 0.139 (0.013)    | -                | -         |     5.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3575 | 2024-03-15 | ECLOT             | L   | 0.240      | -            | -                | -                | -         |    -1.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3581 | 2024-03-15 | Permitta          | W   | 0.239      | -            | -                | -                | -         |     4.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3611 | 2024-03-14 | Passion UA        | L   | 0.233      | -            | -                | -                | -         |    -1.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3681 | 2024-03-12 | MOUZ NXT          | W   | 0.219      | -            | -                | -                | -         |     4.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3723 | 2024-03-10 | Sashi             | W   | 0.206      | 0.358        | 0.184 (0.014)    | -                | -         |     5.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3749 | 2024-03-09 | Enterprise        | W   | 0.200      | -            | -                | -                | -         |     3.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3834 | 2024-03-06 | AURA              | W   | 0.179      | -            | -                | -                | -         |     0.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3880 | 2024-03-04 | Sangal            | L   | 0.166      | -            | -                | -                | -         |    -0.94 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3934 | 2024-03-02 | Enterprise        | L   | 0.152      | -            | -                | -                | -         |    -2.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3972 | 2024-02-28 | Sashi             | L   | 0.134      | -            | -                | -                | -         |    -0.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     4037 | 2024-02-25 | ECLOT             | L   | 0.112      | -            | -                | -                | -         |    -0.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4083 | 2024-02-23 | Entropiq          | W   | 0.099      | -            | -                | -                | -         |     0.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4125 | 2024-02-21 | Sashi             | L   | 0.087      | -            | -                | -                | -         |    -0.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4229 | 2024-02-17 | Secret            | W   | 0.060      | -            | -                | -                | -         |     0.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4376 | 2024-02-10 | Zero Tenacity     | W   | 0.015      | -            | -                | -                | -         |     0.36 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,643.21)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.842 | $3,268.00      | $2,750.87       |
| 2024-06-02 |      0.768 | $653.00        | $501.27         |
| 2024-05-18 |      0.668 | $1,000.00      | $667.96         |
| 2024-04-25 |      0.512 | $5,000.00      | $2,560.65       |
| 2024-04-14 |      0.440 | $1,600.00      | $704.30         |
| 2024-03-18 |      0.259 | $5,000.00      | $1,295.37       |
| 2024-03-17 |      0.255 | $639.00        | $162.80         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
