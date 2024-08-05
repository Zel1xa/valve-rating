### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1169.5<br />
<br />
Final Rank Value (1169.5) = Starting Rank Value (1101.9) + Head To Head Adjustments (67.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.355[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1101.9
- 400 + ( ( 0.343 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1101.9


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
|          103 |       12 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      165 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      215 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.961 (0.480)    | 0 (0.000) |    17.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      403 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.561 (0.281)    | 0 (0.000) |     8.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      492 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      519 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.165 (0.082)    | 0.951 (0.475)    | 0 (0.000) |    16.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      614 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.708 (0.354)    | 0 (0.000) |    27.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      730 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.619 (0.310)    | 0 (0.000) |    13.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      752 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.509 (0.254)    | 0 (0.000) |     6.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |      999 | 2024-06-16 | FAVBET            | W   | 0.871      | -            | -                | -                | 0 (0.000) |     5.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1031 | 2024-06-15 | Nemiga            | L   | 0.864      | -            | -                | -                | -         |   -10.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1072 | 2024-06-14 | RUBY              | W   | 0.858      | -            | -                | -                | 0 (0.000) |     7.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1112 | 2024-06-13 | Monte             | L   | 0.850      | -            | -                | -                | -         |   -15.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1137 | 2024-06-12 | 9INE              | W   | 0.844      | -            | -                | -                | -         |     1.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1157 | 2024-06-11 | DMS               | W   | 0.838      | -            | -                | -                | -         |     7.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1166 | 2024-06-11 | EYEBALLERS        | W   | 0.836      | -            | -                | -                | -         |     6.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1243 | 2024-06-09 | HAVU              | W   | 0.823      | -            | -                | -                | -         |     3.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1258 | 2024-06-09 | Nemiga            | L   | 0.822      | -            | -                | -                | -         |   -10.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1277 | 2024-06-08 | Insilio           | L   | 0.818      | -            | -                | -                | -         |   -17.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1296 | 2024-06-08 | Passion UA        | W   | 0.817      | 0.500        | 0.172 (0.070)    | 1.000 (0.409)    | -         |    11.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1335 | 2024-06-07 | DMS               | W   | 0.812      | -            | -                | -                | -         |     7.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1352 | 2024-06-07 | EYEBALLERS        | L   | 0.811      | -            | -                | -                | -         |   -19.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1372 | 2024-06-07 | 5W                | L   | 0.809      | -            | -                | -                | -         |   -18.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1396 | 2024-06-06 | FAVBET            | W   | 0.805      | -            | -                | -                | -         |     3.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1422 | 2024-06-06 | Permitta          | L   | 0.804      | -            | -                | -                | -         |   -19.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1441 | 2024-06-06 | GhoulsW           | W   | 0.802      | -            | -                | -                | -         |     0.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1477 | 2024-06-05 | Aurora Young Blud | W   | 0.797      | -            | -                | -                | -         |     4.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1516 | 2024-06-04 | CYBERSHOKE        | W   | 0.791      | -            | -                | -                | -         |     4.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1526 | 2024-06-04 | Grannys Knockers  | W   | 0.790      | -            | -                | -                | -         |     3.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1556 | 2024-06-03 | Johnny Speeds     | L   | 0.783      | -            | -                | -                | -         |    -8.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1562 | 2024-06-02 | DMS               | W   | 0.778      | -            | -                | -                | -         |     7.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1569 | 2024-06-02 | SAW               | W   | 0.777      | -            | -                | -                | -         |    15.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1589 | 2024-06-01 | RUBY              | L   | 0.772      | -            | -                | -                | -         |   -17.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1605 | 2024-06-01 | DMS               | W   | 0.770      | -            | -                | -                | -         |     6.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1607 | 2024-06-01 | KOI               | W   | 0.770      | -            | -                | -                | -         |     9.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1614 | 2024-06-01 | FURIA             | L   | 0.769      | -            | -                | -                | -         |    -1.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1643 | 2024-05-31 | Passion UA        | W   | 0.763      | 0.435        | 0.172 (0.057)    | 1.000 (0.332)    | -         |    10.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1651 | 2024-05-30 | ThunderFlash      | W   | 0.758      | -            | -                | -                | -         |     0.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1664 | 2024-05-30 | Passion UA        | L   | 0.757      | -            | -                | -                | -         |   -13.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1680 | 2024-05-29 | JANO              | W   | 0.752      | -            | -                | -                | -         |     1.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1750 | 2024-05-26 | RUBY              | W   | 0.730      | -            | -                | -                | -         |     6.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1763 | 2024-05-25 | ex-Guild Eagles   | W   | 0.725      | -            | -                | -                | -         |     4.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1766 | 2024-05-25 | Serbia            | W   | 0.724      | -            | -                | -                | -         |     3.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1776 | 2024-05-25 | Rhyno             | W   | 0.722      | -            | -                | -                | -         |     8.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1781 | 2024-05-24 | ex-Guild Eagles   | L   | 0.718      | -            | -                | -                | -         |   -18.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1784 | 2024-05-24 | The Suspect       | W   | 0.717      | -            | -                | -                | -         |     3.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1800 | 2024-05-23 | 3DMAX             | L   | 0.710      | -            | -                | -                | -         |    -1.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1807 | 2024-05-23 | brazylijski luz   | W   | 0.709      | -            | -                | -                | -         |     4.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1840 | 2024-05-22 | Sangal            | L   | 0.704      | -            | -                | -                | -         |   -10.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1850 | 2024-05-22 | Illuminar         | W   | 0.702      | -            | -                | -                | -         |     4.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1884 | 2024-05-21 | BLEED             | W   | 0.697      | 0.500        | 0.126 (0.044)    | -                | -         |    18.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1889 | 2024-05-21 | Verdant           | W   | 0.696      | -            | -                | -                | -         |     6.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1912 | 2024-05-20 | Metizport         | W   | 0.691      | -            | -                | -                | -         |     4.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1947 | 2024-05-19 | B8                | W   | 0.683      | 0.500        | 0.165 (0.056)    | 0.951 (0.325)    | -         |    12.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     2001 | 2024-05-17 | PARIVISION        | L   | 0.671      | -            | -                | -                | -         |   -10.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2009 | 2024-05-17 | Endpoint          | W   | 0.670      | -            | -                | -                | -         |     6.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2051 | 2024-05-16 | 1WIN              | L   | 0.663      | -            | -                | -                | -         |   -13.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2058 | 2024-05-16 | kONO              | W   | 0.662      | -            | -                | -                | -         |     4.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2100 | 2024-05-15 | 3DMAX             | W   | 0.656      | 0.500        | 0.507 (0.166)    | 1.000 (0.328)    | -         |    19.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2160 | 2024-05-14 | Preasy            | W   | 0.649      | -            | -                | -                | -         |     3.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2178 | 2024-05-13 | EYEBALLERS        | W   | 0.644      | -            | -                | -                | -         |     6.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2206 | 2024-05-12 | Verdant           | W   | 0.636      | -            | -                | -                | -         |     7.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2276 | 2024-05-09 | 9 Pandas          | L   | 0.616      | -            | -                | -                | -         |   -11.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2331 | 2024-05-06 | Insilio           | W   | 0.598      | -            | -                | -                | -         |     6.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2377 | 2024-05-03 | EYEBALLERS        | L   | 0.578      | -            | -                | -                | -         |   -12.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2390 | 2024-05-03 | Metizport         | L   | 0.576      | -            | -                | -                | -         |   -13.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2418 | 2024-05-02 | HAVU              | W   | 0.569      | -            | -                | -                | -         |     2.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2440 | 2024-05-01 | KOI               | W   | 0.563      | -            | -                | -                | -         |     9.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2453 | 2024-04-30 | Sangal            | L   | 0.557      | -            | -                | -                | -         |    -7.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2465 | 2024-04-30 | B8                | W   | 0.556      | 0.435        | 0.165 (0.040)    | -                | -         |     7.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2480 | 2024-04-29 | PARIVISION        | L   | 0.550      | -            | -                | -                | -         |    -8.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2497 | 2024-04-28 | SINNERS           | W   | 0.543      | -            | -                | -                | -         |     9.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2510 | 2024-04-27 | 500               | W   | 0.538      | -            | -                | -                | -         |     2.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2530 | 2024-04-27 | SINNERS           | W   | 0.536      | -            | -                | -                | -         |     9.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2554 | 2024-04-26 | Illuminar         | W   | 0.529      | -            | -                | -                | -         |     1.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2576 | 2024-04-25 | EYEBALLERS        | L   | 0.523      | -            | -                | -                | -         |   -12.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2599 | 2024-04-24 | ex-Guild Eagles   | L   | 0.516      | -            | -                | -                | -         |   -12.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2615 | 2024-04-23 | Nemiga            | L   | 0.510      | -            | -                | -                | -         |    -5.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2625 | 2024-04-22 | Grannys Knockers  | W   | 0.504      | -            | -                | -                | -         |     2.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2631 | 2024-04-22 | Nexus             | W   | 0.503      | -            | -                | -                | -         |     3.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2675 | 2024-04-20 | RUBY              | W   | 0.490      | -            | -                | -                | -         |     5.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2705 | 2024-04-19 | PARIVISION        | W   | 0.485      | -            | -                | -                | -         |     7.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2729 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.483      | -            | -                | -                | -         |     5.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2788 | 2024-04-18 | B8                | L   | 0.476      | -            | -                | -                | -         |    -8.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2810 | 2024-04-17 | B8                | W   | 0.470      | -            | -                | -                | -         |     7.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2839 | 2024-04-16 | Sangal            | L   | 0.464      | -            | -                | -                | -         |    -5.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2861 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.458      | -            | -                | -                | -         |     5.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2911 | 2024-04-12 | JANO              | L   | 0.435      | -            | -                | -                | -         |   -12.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2938 | 2024-04-11 | Alliance          | L   | 0.430      | -            | -                | -                | -         |   -10.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3036 | 2024-04-09 | MOUZ NXT          | L   | 0.417      | -            | -                | -                | -         |    -7.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3099 | 2024-04-07 | ex-Preasy         | L   | 0.403      | -            | -                | -                | -         |   -10.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3268 | 2024-04-01 | Nemiga            | L   | 0.362      | -            | -                | -                | -         |    -4.65 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3676 | 2024-03-10 | CYBERSHOKE        | L   | 0.218      | -            | -                | -                | -         |    -6.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3688 | 2024-03-10 | ECLOT             | W   | 0.217      | -            | -                | -                | -         |     4.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3707 | 2024-03-09 | Sangal            | W   | 0.210      | -            | -                | -                | -         |     3.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3753 | 2024-03-07 | Nemiga            | L   | 0.198      | -            | -                | -                | -         |    -2.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3788 | 2024-03-06 | AURA              | W   | 0.190      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3819 | 2024-03-05 | AMKAL             | L   | 0.184      | -            | -                | -                | -         |    -2.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3878 | 2024-03-03 | Secret            | W   | 0.169      | -            | -                | -                | -         |     0.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3898 | 2024-03-02 | Secret            | W   | 0.163      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3924 | 2024-02-29 | Young Ninjas      | W   | 0.150      | -            | -                | -                | -         |     0.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4189 | 2024-02-17 | Sashi             | L   | 0.070      | -            | -                | -                | -         |    -0.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4342 | 2024-02-10 | Sampi             | L   | 0.024      | -            | -                | -                | -         |    -0.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,258.06)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.832 | $2,000.00      | $1,663.06       |
| 2024-06-02 |      0.777 | $2,000.00      | $1,554.44       |
| 2024-05-22 |      0.704 | $25,000.00     | $17,597.22      |
| 2024-05-16 |      0.662 | $5,000.00      | $3,309.72       |
| 2024-05-04 |      0.584 | $2,000.00      | $1,168.33       |
| 2024-04-24 |      0.517 | $12,500.00     | $6,465.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
