### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
<br />
Final Rank Value:  854.7<br />
<br />
Final Rank Value (854.7) = Starting Rank Value (886.0) + Head To Head Adjustments (-31.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.375[<sup>2</sup>](#table1)
- Opponent Network: 0.187[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 886.0
- 400 + ( ( 0.238 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 886.0


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
|           93 |       83 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |       92 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |      122 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.20 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      139 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      178 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    17.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      189 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      217 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.67 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      237 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.363 (0.158)    | 0 (0.000) |    12.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      284 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |    12.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      297 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      367 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      398 | 2024-07-23 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.363 (0.158)    | 0 (0.000) |    13.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      437 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      449 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      525 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -12.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      573 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -16.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      699 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.502 (0.218)    | 0 (0.000) |    15.32 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      710 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.68 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      764 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.91 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      768 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.78 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           73 |      828 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.45 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      867 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.94 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           71 |     1069 | 2024-06-13 | Rebels            | W   | 0.858      | 0.379        | 0.038 (0.012)    | 0.599 (0.195)    | -         |    18.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1076 | 2024-06-13 | Sashi             | L   | 0.857      | -            | -                | -                | -         |    -3.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1100 | 2024-06-12 | Enterprise        | L   | 0.851      | -            | -                | -                | -         |   -11.08 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1119 | 2024-06-11 | Astralis Talent   | W   | 0.844      | -            | -                | -                | -         |     8.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1129 | 2024-06-11 | Illuminar         | L   | 0.843      | -            | -                | -                | -         |   -12.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1189 | 2024-06-09 | Aurora Young Blud | L   | 0.831      | -            | -                | -                | -         |   -15.24 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           65 |     1258 | 2024-06-08 | MOUZ NXT          | L   | 0.824      | -            | -                | -                | -         |    -6.58 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1277 | 2024-06-08 | CYBERSHOKE        | L   | 0.823      | -            | -                | -                | -         |   -14.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1379 | 2024-06-06 | Nemiga            | L   | 0.811      | -            | -                | -                | -         |    -6.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1395 | 2024-06-06 | HAVU              | W   | 0.810      | -            | -                | -                | -         |     6.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1438 | 2024-06-05 | NAVI Junior       | W   | 0.804      | -            | -                | -                | -         |     3.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1475 | 2024-06-04 | INFINITE          | W   | 0.799      | -            | -                | -                | -         |     3.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1495 | 2024-06-04 | DMS               | W   | 0.796      | 0.500        | -                | 0.446 (0.178)    | -         |    14.85 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1519 | 2024-06-03 | Rare Atom         | W   | 0.789      | 0.435        | -                | 0.479 (0.164)    | -         |     6.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1570 | 2024-06-01 | SINNERS           | L   | 0.777      | -            | -                | -                | -         |    -7.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1591 | 2024-05-31 | ECLOT             | L   | 0.772      | -            | -                | -                | -         |    -5.14 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1615 | 2024-05-30 | 3DMAX             | L   | 0.765      | -            | -                | -                | -         |    -0.65 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1668 | 2024-05-28 | Enterprise        | L   | 0.751      | -            | -                | -                | -         |   -11.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1671 | 2024-05-28 | Rhyno             | W   | 0.750      | 0.435        | 0.071 (0.023)    | -                | -         |    14.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1706 | 2024-05-26 | SINNERS           | L   | 0.738      | -            | -                | -                | -         |    -7.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1724 | 2024-05-25 | Passion UA        | L   | 0.731      | -            | -                | -                | -         |    -7.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1755 | 2024-05-23 | GUN5              | W   | 0.719      | 0.435        | 0.073 (0.023)    | 0.569 (0.178)    | -         |    12.33 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1790 | 2024-05-22 | VENI VIDI VICI    | W   | 0.712      | -            | -                | -                | -         |     1.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1879 | 2024-05-20 | Illuminar         | W   | 0.698      | -            | -                | -                | -         |    11.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1887 | 2024-05-20 | Verdant           | L   | 0.696      | -            | -                | -                | -         |   -10.60 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     1942 | 2024-05-18 | DMS               | L   | 0.683      | -            | -                | -                | -         |   -10.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2005 | 2024-05-16 | MOUZ NXT          | L   | 0.671      | -            | -                | -                | -         |    -7.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2013 | 2024-05-16 | B8                | L   | 0.670      | -            | -                | -                | -         |    -5.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2141 | 2024-05-13 | Nexus             | W   | 0.650      | -            | -                | -                | -         |     7.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2229 | 2024-05-09 | BLEED             | L   | 0.625      | -            | -                | -                | -         |    -6.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2306 | 2024-05-05 | RUSH B            | W   | 0.598      | -            | -                | -                | -         |     7.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2335 | 2024-05-04 | Endpoint          | L   | 0.589      | -            | -                | -                | -         |    -9.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2367 | 2024-05-02 | Permitta          | W   | 0.578      | 0.435        | -                | 0.876 (0.220)    | -         |     9.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2394 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.570      | -            | -                | -                | -         |    -7.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2401 | 2024-05-01 | ENCE Academy      | W   | 0.570      | -            | -                | -                | -         |     4.16 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2406 | 2024-04-30 | GL Academy        | W   | 0.566      | -            | -                | -                | -         |     5.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2424 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.563      | -            | -                | -                | -         |    -7.81 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2541 | 2024-04-25 | ECLOT             | L   | 0.529      | -            | -                | -                | -         |    -3.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2560 | 2024-04-24 | Permitta          | W   | 0.522      | 0.371        | -                | 0.876 (0.170)    | -         |     9.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2579 | 2024-04-23 | ECLOT             | L   | 0.516      | -            | -                | -                | -         |    -2.89 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2615 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.502      | -            | -                | -                | -         |     8.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2689 | 2024-04-19 | BLEED             | L   | 0.490      | -            | -                | -                | -         |    -5.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2748 | 2024-04-18 | Permitta          | W   | 0.482      | -            | -                | -                | -         |     8.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2770 | 2024-04-17 | NOM               | L   | 0.477      | -            | -                | -                | -         |   -13.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2808 | 2024-04-16 | SAW               | W   | 0.470      | 0.384        | 0.106 (0.019)    | -                | -         |    12.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2812 | 2024-04-16 | Secret            | W   | 0.469      | -            | -                | -                | -         |     1.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2822 | 2024-04-15 | ENCE Academy      | L   | 0.464      | -            | -                | -                | -         |   -10.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2857 | 2024-04-13 | BetBoom           | L   | 0.450      | -            | -                | -                | -         |    -0.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2901 | 2024-04-11 | PGE Turow         | W   | 0.436      | -            | -                | -                | -         |     2.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3074 | 2024-04-06 | Enterprise        | W   | 0.403      | -            | -                | -                | -         |     6.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3180 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.383      | 0.384        | 0.223 (0.033)    | -                | -         |    11.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3302 | 2024-03-27 | B8                | L   | 0.339      | -            | -                | -                | -         |    -2.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3443 | 2024-03-18 | ex-Preasy         | L   | 0.276      | -            | -                | -                | -         |    -5.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3474 | 2024-03-17 | Passion UA        | W   | 0.269      | 0.371        | 0.172 (0.017)    | -                | -         |     6.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3482 | 2024-03-16 | SINNERS           | L   | 0.264      | -            | -                | -                | -         |    -2.33 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3485 | 2024-03-16 | MOUZ NXT          | W   | 0.263      | 0.371        | 0.139 (0.014)    | -                | -         |     5.67 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3500 | 2024-03-15 | ECLOT             | L   | 0.258      | -            | -                | -                | -         |    -1.33 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3506 | 2024-03-15 | Permitta          | W   | 0.256      | -            | -                | -                | -         |     4.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3536 | 2024-03-14 | Passion UA        | L   | 0.250      | -            | -                | -                | -         |    -2.15 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3605 | 2024-03-12 | MOUZ NXT          | W   | 0.236      | -            | -                | -                | -         |     5.21 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3647 | 2024-03-10 | Sashi             | W   | 0.223      | 0.358        | 0.184 (0.015)    | -                | -         |     5.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3673 | 2024-03-09 | Enterprise        | W   | 0.217      | -            | -                | -                | -         |     3.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3758 | 2024-03-06 | AURA              | W   | 0.196      | -            | -                | -                | -         |     0.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3804 | 2024-03-04 | Sangal            | L   | 0.183      | -            | -                | -                | -         |    -1.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3858 | 2024-03-02 | Enterprise        | L   | 0.169      | -            | -                | -                | -         |    -2.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3896 | 2024-02-28 | Sashi             | L   | 0.151      | -            | -                | -                | -         |    -0.90 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     3961 | 2024-02-25 | ECLOT             | L   | 0.129      | -            | -                | -                | -         |    -0.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4007 | 2024-02-23 | Entropiq          | W   | 0.116      | -            | -                | -                | -         |     0.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4049 | 2024-02-21 | Sashi             | L   | 0.104      | -            | -                | -                | -         |    -0.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4152 | 2024-02-17 | Secret            | W   | 0.077      | -            | -                | -                | -         |     0.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4299 | 2024-02-10 | Zero Tenacity     | W   | 0.032      | -            | -                | -                | -         |     0.77 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,935.57)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.859 | $3,268.00      | $2,806.55       |
| 2024-06-02 |      0.785 | $653.00        | $512.39         |
| 2024-05-18 |      0.685 | $1,000.00      | $685.00         |
| 2024-04-25 |      0.529 | $5,000.00      | $2,645.83       |
| 2024-04-14 |      0.457 | $1,600.00      | $731.56         |
| 2024-03-18 |      0.276 | $5,000.00      | $1,380.56       |
| 2024-03-17 |      0.272 | $639.00        | $173.68         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
