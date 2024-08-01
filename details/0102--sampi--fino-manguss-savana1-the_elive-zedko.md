### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  856.8<br />
<br />
Final Rank Value (856.8) = Starting Rank Value (891.7) + Head To Head Adjustments (-34.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.392[<sup>1</sup>](#table2)
- Bounty Collected: 0.376[<sup>2</sup>](#table1)
- Opponent Network: 0.188[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.239<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 891.7
- 400 + ( ( 0.239 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 891.7


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
|           95 |        2 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -20.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           94 |        9 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -17.37 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           93 |       40 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |       57 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -14.65 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |       97 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.040 (0.017)    | -                | 0 (0.000) |    17.08 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      108 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      135 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      156 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.360 (0.156)    | 0 (0.000) |    13.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      204 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.555 (0.241)    | 0 (0.000) |    13.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      216 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -2.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      286 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -11.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      317 | 2024-07-23 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.360 (0.156)    | 0 (0.000) |    13.93 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      357 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.44 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      370 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      449 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -12.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      501 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      629 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.097 (0.042)    | 0.544 (0.236)    | 0 (0.000) |    15.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      643 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.90 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      698 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.81 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           76 |      702 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.98 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           75 |      765 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.73 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      804 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.96 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           73 |      995 | 2024-06-13 | Rebels            | W   | 0.873      | 0.379        | 0.040 (0.013)    | 0.635 (0.210)    | -         |    18.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           72 |     1002 | 2024-06-13 | Sashi             | L   | 0.872      | -            | -                | -                | -         |    -3.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           71 |     1026 | 2024-06-12 | Enterprise        | L   | 0.866      | -            | -                | -                | -         |   -11.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1046 | 2024-06-11 | Astralis Talent   | W   | 0.859      | -            | -                | -                | -         |     8.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1056 | 2024-06-11 | Illuminar         | L   | 0.858      | -            | -                | -                | -         |   -11.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1117 | 2024-06-09 | Aurora Young Blud | L   | 0.846      | -            | -                | -                | -         |   -13.77 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           67 |     1188 | 2024-06-08 | MOUZ NXT          | L   | 0.839      | -            | -                | -                | -         |    -6.37 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           66 |     1208 | 2024-06-08 | CYBERSHOKE        | L   | 0.838      | -            | -                | -                | -         |   -14.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           65 |     1318 | 2024-06-06 | Nemiga            | L   | 0.826      | -            | -                | -                | -         |    -6.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           64 |     1335 | 2024-06-06 | HAVU              | W   | 0.825      | -            | -                | -                | -         |     6.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1380 | 2024-06-05 | NAVI Junior       | W   | 0.819      | -            | -                | -                | -         |     3.21 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1417 | 2024-06-04 | INFINITE          | W   | 0.814      | -            | -                | -                | -         |     3.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1437 | 2024-06-04 | DMS               | W   | 0.811      | 0.500        | -                | 0.447 (0.181)    | -         |    15.33 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1461 | 2024-06-03 | Rare Atom         | W   | 0.804      | 0.435        | -                | 0.437 (0.153)    | -         |     5.09 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1513 | 2024-06-01 | SINNERS           | L   | 0.792      | -            | -                | -                | -         |    -7.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1534 | 2024-05-31 | ECLOT             | L   | 0.787      | -            | -                | -                | -         |    -7.09 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1558 | 2024-05-30 | 3DMAX             | L   | 0.780      | -            | -                | -                | -         |    -0.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1611 | 2024-05-28 | Enterprise        | L   | 0.766      | -            | -                | -                | -         |   -12.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1614 | 2024-05-28 | Rhyno             | W   | 0.765      | 0.435        | 0.072 (0.024)    | -                | -         |    15.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1651 | 2024-05-26 | SINNERS           | L   | 0.753      | -            | -                | -                | -         |    -7.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1669 | 2024-05-25 | Passion UA        | L   | 0.746      | -            | -                | -                | -         |    -7.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1700 | 2024-05-23 | GUN5              | W   | 0.734      | 0.435        | 0.074 (0.024)    | 0.555 (0.177)    | -         |    13.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1735 | 2024-05-22 | VENI VIDI VICI    | W   | 0.727      | -            | -                | -                | -         |     1.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1842 | 2024-05-20 | Illuminar         | W   | 0.713      | -            | -                | -                | -         |    12.37 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1852 | 2024-05-20 | Verdant           | L   | 0.711      | -            | -                | -                | -         |   -10.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1913 | 2024-05-18 | DMS               | L   | 0.698      | -            | -                | -                | -         |   -10.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1976 | 2024-05-16 | MOUZ NXT          | L   | 0.686      | -            | -                | -                | -         |    -7.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     1984 | 2024-05-16 | B8                | L   | 0.685      | -            | -                | -                | -         |    -5.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2121 | 2024-05-13 | Nexus             | W   | 0.665      | -            | -                | -                | -         |     7.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2209 | 2024-05-09 | BLEED             | L   | 0.640      | -            | -                | -                | -         |    -6.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2288 | 2024-05-05 | RUSH B            | W   | 0.613      | -            | -                | -                | -         |     8.14 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2317 | 2024-05-04 | Endpoint          | L   | 0.604      | -            | -                | -                | -         |    -8.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2350 | 2024-05-02 | Permitta          | W   | 0.593      | 0.435        | -                | 0.801 (0.206)    | -         |     9.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2378 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.585      | -            | -                | -                | -         |    -7.99 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2385 | 2024-05-01 | ENCE Academy      | W   | 0.585      | -            | -                | -                | -         |     4.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2391 | 2024-04-30 | GL Academy        | W   | 0.581      | -            | -                | -                | -         |     5.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2409 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.578      | -            | -                | -                | -         |    -7.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2527 | 2024-04-25 | ECLOT             | L   | 0.544      | -            | -                | -                | -         |    -4.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2546 | 2024-04-24 | Permitta          | W   | 0.537      | 0.371        | -                | 0.801 (0.160)    | -         |     9.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2567 | 2024-04-23 | ECLOT             | L   | 0.531      | -            | -                | -                | -         |    -4.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2605 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.517      | -            | -                | -                | -         |     9.12 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2682 | 2024-04-19 | BLEED             | L   | 0.505      | -            | -                | -                | -         |    -5.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2742 | 2024-04-18 | Permitta          | W   | 0.497      | -            | -                | -                | -         |     9.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2752 | 2024-04-17 | JANO              | L   | 0.495      | -            | -                | -                | -         |   -12.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2765 | 2024-04-17 | NOM               | L   | 0.492      | -            | -                | -                | -         |   -13.85 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2804 | 2024-04-16 | SAW               | W   | 0.485      | 0.384        | 0.108 (0.020)    | -                | -         |    12.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2808 | 2024-04-16 | Secret            | W   | 0.484      | -            | -                | -                | -         |     1.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2818 | 2024-04-15 | ENCE Academy      | L   | 0.479      | -            | -                | -                | -         |   -11.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2853 | 2024-04-13 | BetBoom           | L   | 0.465      | -            | -                | -                | -         |    -0.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2898 | 2024-04-11 | PGE Turow         | W   | 0.451      | -            | -                | -                | -         |     2.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     3071 | 2024-04-06 | Enterprise        | W   | 0.418      | -            | -                | -                | -         |     6.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3183 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.398      | 0.384        | 0.207 (0.032)    | -                | -         |    12.21 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3308 | 2024-03-27 | B8                | L   | 0.354      | -            | -                | -                | -         |    -2.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3453 | 2024-03-18 | ex-Preasy         | L   | 0.291      | -            | -                | -                | -         |    -5.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3484 | 2024-03-17 | Passion UA        | W   | 0.284      | 0.371        | 0.173 (0.018)    | -                | -         |     6.44 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3492 | 2024-03-16 | SINNERS           | L   | 0.279      | -            | -                | -                | -         |    -2.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3495 | 2024-03-16 | MOUZ NXT          | W   | 0.278      | 0.371        | 0.141 (0.014)    | -                | -         |     6.11 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3510 | 2024-03-15 | ECLOT             | L   | 0.273      | -            | -                | -                | -         |    -2.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3516 | 2024-03-15 | Permitta          | W   | 0.271      | -            | -                | -                | -         |     4.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3550 | 2024-03-14 | Passion UA        | L   | 0.265      | -            | -                | -                | -         |    -2.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3621 | 2024-03-12 | MOUZ NXT          | W   | 0.251      | -            | -                | -                | -         |     5.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3663 | 2024-03-10 | Sashi             | W   | 0.238      | 0.358        | 0.187 (0.016)    | -                | -         |     6.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3690 | 2024-03-09 | Enterprise        | W   | 0.232      | -            | -                | -                | -         |     3.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3775 | 2024-03-06 | AURA              | W   | 0.211      | -            | -                | -                | -         |     0.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3826 | 2024-03-04 | Sangal            | L   | 0.198      | -            | -                | -                | -         |    -1.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3880 | 2024-03-02 | Enterprise        | L   | 0.184      | -            | -                | -                | -         |    -2.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3920 | 2024-02-28 | Sashi             | L   | 0.166      | -            | -                | -                | -         |    -0.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3987 | 2024-02-25 | ECLOT             | L   | 0.144      | -            | -                | -                | -         |    -1.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     4037 | 2024-02-23 | Entropiq          | W   | 0.131      | -            | -                | -                | -         |     0.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4081 | 2024-02-21 | Sashi             | L   | 0.119      | -            | -                | -                | -         |    -0.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4184 | 2024-02-17 | Secret            | W   | 0.092      | -            | -                | -                | -         |     0.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4341 | 2024-02-10 | Zero Tenacity     | W   | 0.047      | -            | -                | -                | -         |     1.12 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |
|            1 |     4401 | 2024-02-05 | Imperial fe       | W   | 0.013      | -            | -                | -                | -         |     0.28 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,192.97)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.874 | $3,268.00      | $2,855.57       |
| 2024-06-02 |      0.800 | $653.00        | $522.19         |
| 2024-05-18 |      0.700 | $1,000.00      | $700.00         |
| 2024-04-25 |      0.544 | $5,000.00      | $2,720.83       |
| 2024-04-14 |      0.472 | $1,600.00      | $755.56         |
| 2024-03-18 |      0.291 | $5,000.00      | $1,455.56       |
| 2024-03-17 |      0.287 | $639.00        | $183.27         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
