### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1123.4<br />
<br />
Final Rank Value (1123.4) = Starting Rank Value (1100.8) + Head To Head Adjustments (22.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.479[<sup>2</sup>](#table1)
- Opponent Network: 0.344[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.340<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1100.8
- 400 + ( ( 0.340 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1100.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          111 |       40 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          110 |       92 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.187 (0.093)    | 0.971 (0.485)    | 0 (0.000) |    18.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          109 |      279 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.554 (0.277)    | 0 (0.000) |     9.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          108 |      370 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -15.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          107 |      398 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.878 (0.439)    | 0 (0.000) |    18.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          106 |      500 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.292 (0.146)    | 0.529 (0.265)    | 0 (0.000) |    25.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          105 |      616 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | -                | 0.614 (0.307)    | 0 (0.000) |    15.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          104 |      640 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.513 (0.256)    | 0 (0.000) |     8.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |      891 | 2024-06-16 | FAVBET            | W   | 0.895      | -            | -                | -                | 0 (0.000) |     7.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      921 | 2024-06-15 | Nemiga            | L   | 0.888      | -            | -                | -                | -         |    -9.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      955 | 2024-06-14 | RUBY              | W   | 0.881      | -            | -                | -                | 0 (0.000) |     9.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      994 | 2024-06-13 | Monte             | L   | 0.874      | -            | -                | -                | -         |   -13.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |     1019 | 2024-06-12 | 9INE              | W   | 0.868      | -            | -                | -                | 0 (0.000) |     1.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |     1040 | 2024-06-11 | DMS               | W   | 0.861      | -            | -                | -                | -         |     9.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |     1049 | 2024-06-11 | EYEBALLERS        | W   | 0.860      | -            | -                | -                | -         |     8.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |     1127 | 2024-06-09 | HAVU              | W   | 0.847      | -            | -                | -                | -         |     4.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |     1134 | 2024-06-09 | Endpoint          | L   | 0.846      | -            | -                | -                | -         |   -18.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1143 | 2024-06-09 | Nemiga            | L   | 0.846      | -            | -                | -                | -         |   -10.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1163 | 2024-06-08 | Insilio           | L   | 0.842      | -            | -                | -                | -         |   -16.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1182 | 2024-06-08 | Passion UA        | W   | 0.841      | 0.500        | 0.172 (0.072)    | 1.000 (0.420)    | -         |    13.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1195 | 2024-06-08 | 9INE              | L   | 0.840      | -            | -                | -                | -         |   -17.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1220 | 2024-06-07 | Aurora Young Blud | L   | 0.836      | -            | -                | -                | -         |   -20.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1228 | 2024-06-07 | DMS               | W   | 0.835      | -            | -                | -                | -         |     8.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1245 | 2024-06-07 | EYEBALLERS        | L   | 0.834      | -            | -                | -                | -         |   -19.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1265 | 2024-06-07 | 5W                | L   | 0.833      | -            | -                | -                | -         |   -18.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1291 | 2024-06-06 | FAVBET            | W   | 0.829      | -            | -                | -                | -         |     4.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1317 | 2024-06-06 | Permitta          | L   | 0.827      | -            | -                | -                | -         |   -19.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1337 | 2024-06-06 | GhoulsW           | W   | 0.826      | -            | -                | -                | -         |     0.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1375 | 2024-06-05 | Aurora Young Blud | W   | 0.821      | -            | -                | -                | -         |     4.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1414 | 2024-06-04 | CYBERSHOKE        | W   | 0.815      | -            | -                | -                | -         |     5.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1424 | 2024-06-04 | Grannys Knockers  | W   | 0.814      | -            | -                | -                | -         |     3.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1454 | 2024-06-03 | Johnny Speeds     | L   | 0.806      | -            | -                | -                | -         |    -8.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1461 | 2024-06-02 | DMS               | W   | 0.802      | -            | -                | -                | -         |     8.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1467 | 2024-06-02 | SAW               | W   | 0.801      | -            | -                | -                | -         |    16.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1488 | 2024-06-01 | RUBY              | L   | 0.795      | -            | -                | -                | -         |   -17.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1504 | 2024-06-01 | DMS               | W   | 0.794      | -            | -                | -                | -         |     7.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1506 | 2024-06-01 | KOI               | W   | 0.794      | -            | -                | -                | -         |     7.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1513 | 2024-06-01 | FURIA             | L   | 0.792      | -            | -                | -                | -         |    -1.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1542 | 2024-05-31 | Passion UA        | W   | 0.787      | 0.435        | 0.172 (0.059)    | 1.000 (0.342)    | -         |    11.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1550 | 2024-05-30 | ThunderFlash      | W   | 0.782      | -            | -                | -                | -         |     0.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1563 | 2024-05-30 | Passion UA        | L   | 0.781      | -            | -                | -                | -         |   -13.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1579 | 2024-05-29 | JANO              | W   | 0.775      | -            | -                | -                | -         |     2.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1637 | 2024-05-27 | ALTERNATE aTTaX   | W   | 0.759      | -            | -                | -                | -         |     5.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1651 | 2024-05-26 | RUBY              | W   | 0.753      | -            | -                | -                | -         |     7.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1664 | 2024-05-25 | ex-Guild Eagles   | W   | 0.748      | -            | -                | -                | -         |     5.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1667 | 2024-05-25 | Serbia            | W   | 0.748      | -            | -                | -                | -         |     3.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1677 | 2024-05-25 | Rhyno             | W   | 0.746      | -            | -                | -                | -         |     9.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1682 | 2024-05-24 | ex-Guild Eagles   | L   | 0.742      | -            | -                | -                | -         |   -18.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1685 | 2024-05-24 | The Suspect       | W   | 0.741      | -            | -                | -                | -         |     4.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1701 | 2024-05-23 | 3DMAX             | L   | 0.734      | -            | -                | -                | -         |    -1.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1708 | 2024-05-23 | brazylijski luz   | W   | 0.732      | -            | -                | -                | -         |     4.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1741 | 2024-05-22 | Sangal            | L   | 0.728      | -            | -                | -                | -         |   -10.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1761 | 2024-05-22 | Illuminar         | W   | 0.726      | -            | -                | -                | -         |     5.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1800 | 2024-05-21 | BLEED             | W   | 0.721      | 0.500        | 0.128 (0.046)    | -                | -         |    19.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1805 | 2024-05-21 | Verdant           | W   | 0.719      | -            | -                | -                | -         |     7.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1808 | 2024-05-21 | GUN5              | L   | 0.719      | -            | -                | -                | -         |   -14.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1830 | 2024-05-20 | Metizport         | W   | 0.715      | -            | -                | -                | -         |     8.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1861 | 2024-05-19 | SINNERS           | L   | 0.709      | -            | -                | -                | -         |   -12.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1873 | 2024-05-19 | B8                | W   | 0.707      | 0.500        | 0.168 (0.059)    | 0.878 (0.310)    | -         |    13.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1928 | 2024-05-17 | PARIVISION        | L   | 0.695      | -            | -                | -                | -         |   -10.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1936 | 2024-05-17 | Endpoint          | W   | 0.694      | -            | -                | -                | -         |     7.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1978 | 2024-05-16 | 1WIN              | L   | 0.686      | -            | -                | -                | -         |   -14.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     1985 | 2024-05-16 | kONO              | W   | 0.686      | -            | -                | -                | -         |     5.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2031 | 2024-05-15 | 3DMAX             | W   | 0.680      | 0.500        | 0.505 (0.172)    | 1.000 (0.340)    | -         |    20.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2094 | 2024-05-14 | Preasy            | W   | 0.673      | -            | -                | -                | -         |     4.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2114 | 2024-05-13 | EYEBALLERS        | W   | 0.667      | -            | -                | -                | -         |     6.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2142 | 2024-05-12 | Verdant           | W   | 0.660      | -            | -                | -                | -         |     7.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2212 | 2024-05-09 | 9 Pandas          | L   | 0.640      | -            | -                | -                | -         |   -11.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2269 | 2024-05-06 | Insilio           | W   | 0.621      | -            | -                | -                | -         |     7.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2315 | 2024-05-03 | EYEBALLERS        | L   | 0.602      | -            | -                | -                | -         |   -12.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2328 | 2024-05-03 | Metizport         | L   | 0.600      | -            | -                | -                | -         |   -12.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2357 | 2024-05-02 | HAVU              | W   | 0.593      | -            | -                | -                | -         |     2.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2380 | 2024-05-01 | KOI               | W   | 0.586      | -            | -                | -                | -         |     6.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2394 | 2024-04-30 | Sangal            | L   | 0.581      | -            | -                | -                | -         |    -7.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2406 | 2024-04-30 | B8                | W   | 0.579      | 0.435        | 0.168 (0.042)    | -                | -         |     8.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2421 | 2024-04-29 | PARIVISION        | L   | 0.573      | -            | -                | -                | -         |    -8.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2438 | 2024-04-28 | SINNERS           | W   | 0.567      | -            | -                | -                | -         |     8.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2451 | 2024-04-27 | 500               | W   | 0.562      | -            | -                | -                | -         |     2.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2472 | 2024-04-27 | SINNERS           | W   | 0.559      | -            | -                | -                | -         |     8.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2495 | 2024-04-26 | Illuminar         | W   | 0.553      | -            | -                | -                | -         |     1.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2517 | 2024-04-25 | EYEBALLERS        | L   | 0.547      | -            | -                | -                | -         |   -12.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2540 | 2024-04-24 | ex-Guild Eagles   | L   | 0.540      | -            | -                | -                | -         |   -12.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2558 | 2024-04-23 | Nemiga            | L   | 0.533      | -            | -                | -                | -         |    -6.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2569 | 2024-04-22 | Grannys Knockers  | W   | 0.528      | -            | -                | -                | -         |     2.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2575 | 2024-04-22 | Nexus             | W   | 0.527      | -            | -                | -                | -         |     3.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2622 | 2024-04-20 | RUBY              | W   | 0.514      | -            | -                | -                | -         |     5.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2653 | 2024-04-19 | PARIVISION        | W   | 0.508      | -            | -                | -                | -         |     8.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2677 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.506      | -            | -                | -                | -         |     5.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2737 | 2024-04-18 | B8                | L   | 0.499      | -            | -                | -                | -         |    -8.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2760 | 2024-04-17 | B8                | W   | 0.493      | 0.500        | 0.168 (0.041)    | -                | -         |     7.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2789 | 2024-04-16 | Sangal            | L   | 0.488      | -            | -                | -                | -         |    -6.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2812 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.481      | -            | -                | -                | -         |     6.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2863 | 2024-04-12 | JANO              | L   | 0.459      | -            | -                | -                | -         |   -12.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2890 | 2024-04-11 | Alliance          | L   | 0.453      | -            | -                | -                | -         |   -10.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2988 | 2024-04-09 | MOUZ NXT          | L   | 0.441      | -            | -                | -                | -         |    -7.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     3051 | 2024-04-07 | ex-Preasy         | L   | 0.426      | -            | -                | -                | -         |   -10.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     3228 | 2024-04-01 | Nemiga            | L   | 0.386      | -            | -                | -                | -         |    -5.01 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           14 |     3646 | 2024-03-10 | CYBERSHOKE        | L   | 0.242      | -            | -                | -                | -         |    -7.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3658 | 2024-03-10 | ECLOT             | W   | 0.240      | -            | -                | -                | -         |     3.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3678 | 2024-03-09 | Sangal            | W   | 0.234      | -            | -                | -                | -         |     4.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           11 |     3724 | 2024-03-07 | Nemiga            | L   | 0.221      | -            | -                | -                | -         |    -2.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3758 | 2024-03-06 | AURA              | W   | 0.214      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3795 | 2024-03-05 | AMKAL             | L   | 0.208      | -            | -                | -                | -         |    -2.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3854 | 2024-03-03 | Secret            | W   | 0.193      | -            | -                | -                | -         |     0.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3874 | 2024-03-02 | Secret            | W   | 0.186      | -            | -                | -                | -         |     0.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3901 | 2024-02-29 | Young Ninjas      | W   | 0.174      | -            | -                | -                | -         |     0.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     4027 | 2024-02-23 | ex-Anonymo        | W   | 0.134      | -            | -                | -                | -         |     0.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     4174 | 2024-02-17 | Sashi             | L   | 0.094      | -            | -                | -                | -         |    -1.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     4337 | 2024-02-10 | Sampi             | L   | 0.048      | -            | -                | -                | -         |    -1.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4419 | 2024-02-04 | 500               | L   | 0.007      | -            | -                | -                | -         |    -0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4432 | 2024-02-03 | The Chosen Few    | W   | 0.002      | -            | -                | -                | -         |     0.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,403.19)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.855 | $2,000.00      | $1,710.28       |
| 2024-06-02 |      0.801 | $2,000.00      | $1,601.67       |
| 2024-05-22 |      0.728 | $25,000.00     | $18,187.50      |
| 2024-05-16 |      0.686 | $5,000.00      | $3,427.78       |
| 2024-05-04 |      0.608 | $2,000.00      | $1,215.56       |
| 2024-04-24 |      0.541 | $12,500.00     | $6,760.42       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
