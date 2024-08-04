### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1169.7<br />
<br />
Final Rank Value (1169.7) = Starting Rank Value (1102.0) + Head To Head Adjustments (67.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.355[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1102.0
- 400 + ( ( 0.343 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1102.0


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
|          103 |        8 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      161 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      211 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.962 (0.481)    | 0 (0.000) |    17.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      399 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.561 (0.281)    | 0 (0.000) |     8.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      488 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      515 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.951 (0.476)    | 0 (0.000) |    16.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      610 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.708 (0.354)    | 0 (0.000) |    27.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      726 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.619 (0.309)    | 0 (0.000) |    13.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      748 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.509 (0.255)    | 0 (0.000) |     6.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |      995 | 2024-06-16 | FAVBET            | W   | 0.873      | -            | -                | -                | 0 (0.000) |     5.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1027 | 2024-06-15 | Nemiga            | L   | 0.867      | -            | -                | -                | -         |   -10.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1068 | 2024-06-14 | RUBY              | W   | 0.860      | -            | -                | -                | 0 (0.000) |     7.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1108 | 2024-06-13 | Monte             | L   | 0.853      | -            | -                | -                | -         |   -15.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1133 | 2024-06-12 | 9INE              | W   | 0.847      | -            | -                | -                | -         |     1.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1153 | 2024-06-11 | DMS               | W   | 0.840      | -            | -                | -                | -         |     7.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1162 | 2024-06-11 | EYEBALLERS        | W   | 0.839      | -            | -                | -                | -         |     6.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1239 | 2024-06-09 | HAVU              | W   | 0.825      | -            | -                | -                | -         |     3.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1254 | 2024-06-09 | Nemiga            | L   | 0.825      | -            | -                | -                | -         |   -11.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1273 | 2024-06-08 | Insilio           | L   | 0.821      | -            | -                | -                | -         |   -17.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1292 | 2024-06-08 | Passion UA        | W   | 0.820      | 0.500        | 0.172 (0.071)    | 1.000 (0.410)    | -         |    11.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1331 | 2024-06-07 | DMS               | W   | 0.814      | -            | -                | -                | -         |     7.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1348 | 2024-06-07 | EYEBALLERS        | L   | 0.813      | -            | -                | -                | -         |   -19.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1368 | 2024-06-07 | 5W                | L   | 0.811      | -            | -                | -                | -         |   -18.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1392 | 2024-06-06 | FAVBET            | W   | 0.807      | -            | -                | -                | -         |     3.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1418 | 2024-06-06 | Permitta          | L   | 0.806      | -            | -                | -                | -         |   -19.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1437 | 2024-06-06 | GhoulsW           | W   | 0.805      | -            | -                | -                | -         |     0.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1473 | 2024-06-05 | Aurora Young Blud | W   | 0.800      | -            | -                | -                | -         |     4.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1512 | 2024-06-04 | CYBERSHOKE        | W   | 0.794      | -            | -                | -                | -         |     4.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1522 | 2024-06-04 | Grannys Knockers  | W   | 0.793      | -            | -                | -                | -         |     3.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1552 | 2024-06-03 | Johnny Speeds     | L   | 0.785      | -            | -                | -                | -         |    -8.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1558 | 2024-06-02 | DMS               | W   | 0.781      | -            | -                | -                | -         |     7.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1565 | 2024-06-02 | SAW               | W   | 0.780      | -            | -                | -                | -         |    15.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1585 | 2024-06-01 | RUBY              | L   | 0.774      | -            | -                | -                | -         |   -17.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1601 | 2024-06-01 | DMS               | W   | 0.773      | -            | -                | -                | -         |     6.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1603 | 2024-06-01 | KOI               | W   | 0.772      | -            | -                | -                | -         |    10.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1610 | 2024-06-01 | FURIA             | L   | 0.771      | -            | -                | -                | -         |    -1.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1639 | 2024-05-31 | Passion UA        | W   | 0.765      | 0.435        | 0.172 (0.057)    | 1.000 (0.333)    | -         |    10.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1647 | 2024-05-30 | ThunderFlash      | W   | 0.761      | -            | -                | -                | -         |     0.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1660 | 2024-05-30 | Passion UA        | L   | 0.759      | -            | -                | -                | -         |   -13.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1676 | 2024-05-29 | JANO              | W   | 0.754      | -            | -                | -                | -         |     1.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1746 | 2024-05-26 | RUBY              | W   | 0.732      | -            | -                | -                | -         |     6.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1759 | 2024-05-25 | ex-Guild Eagles   | W   | 0.727      | -            | -                | -                | -         |     4.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1762 | 2024-05-25 | Serbia            | W   | 0.726      | -            | -                | -                | -         |     3.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1772 | 2024-05-25 | Rhyno             | W   | 0.725      | -            | -                | -                | -         |     8.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1777 | 2024-05-24 | ex-Guild Eagles   | L   | 0.720      | -            | -                | -                | -         |   -18.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1780 | 2024-05-24 | The Suspect       | W   | 0.720      | -            | -                | -                | -         |     3.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1796 | 2024-05-23 | 3DMAX             | L   | 0.713      | -            | -                | -                | -         |    -1.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1803 | 2024-05-23 | brazylijski luz   | W   | 0.711      | -            | -                | -                | -         |     4.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1836 | 2024-05-22 | Sangal            | L   | 0.706      | -            | -                | -                | -         |   -10.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1846 | 2024-05-22 | Illuminar         | W   | 0.705      | -            | -                | -                | -         |     4.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1880 | 2024-05-21 | BLEED             | W   | 0.700      | 0.500        | 0.126 (0.044)    | -                | -         |    18.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1885 | 2024-05-21 | Verdant           | W   | 0.698      | -            | -                | -                | -         |     6.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1908 | 2024-05-20 | Metizport         | W   | 0.694      | -            | -                | -                | -         |     4.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1943 | 2024-05-19 | B8                | W   | 0.685      | 0.500        | 0.165 (0.057)    | 0.951 (0.326)    | -         |    13.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     1997 | 2024-05-17 | PARIVISION        | L   | 0.674      | -            | -                | -                | -         |   -10.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2005 | 2024-05-17 | Endpoint          | W   | 0.673      | -            | -                | -                | -         |     6.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2047 | 2024-05-16 | 1WIN              | L   | 0.665      | -            | -                | -                | -         |   -13.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2054 | 2024-05-16 | kONO              | W   | 0.664      | -            | -                | -                | -         |     4.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2096 | 2024-05-15 | 3DMAX             | W   | 0.659      | 0.500        | 0.506 (0.167)    | 1.000 (0.329)    | -         |    19.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2156 | 2024-05-14 | Preasy            | W   | 0.652      | -            | -                | -                | -         |     3.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2174 | 2024-05-13 | EYEBALLERS        | W   | 0.646      | -            | -                | -                | -         |     6.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2202 | 2024-05-12 | Verdant           | W   | 0.639      | -            | -                | -                | -         |     7.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2272 | 2024-05-09 | 9 Pandas          | L   | 0.619      | -            | -                | -                | -         |   -11.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2327 | 2024-05-06 | Insilio           | W   | 0.600      | -            | -                | -                | -         |     6.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2373 | 2024-05-03 | EYEBALLERS        | L   | 0.580      | -            | -                | -                | -         |   -12.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2386 | 2024-05-03 | Metizport         | L   | 0.578      | -            | -                | -                | -         |   -13.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2414 | 2024-05-02 | HAVU              | W   | 0.571      | -            | -                | -                | -         |     2.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2436 | 2024-05-01 | KOI               | W   | 0.565      | -            | -                | -                | -         |     9.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2449 | 2024-04-30 | Sangal            | L   | 0.560      | -            | -                | -                | -         |    -7.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2461 | 2024-04-30 | B8                | W   | 0.558      | 0.435        | 0.165 (0.040)    | -                | -         |     8.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2476 | 2024-04-29 | PARIVISION        | L   | 0.552      | -            | -                | -                | -         |    -8.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2493 | 2024-04-28 | SINNERS           | W   | 0.546      | -            | -                | -                | -         |     9.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2506 | 2024-04-27 | 500               | W   | 0.540      | -            | -                | -                | -         |     2.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2526 | 2024-04-27 | SINNERS           | W   | 0.538      | -            | -                | -                | -         |     9.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2550 | 2024-04-26 | Illuminar         | W   | 0.531      | -            | -                | -                | -         |     1.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2572 | 2024-04-25 | EYEBALLERS        | L   | 0.525      | -            | -                | -                | -         |   -12.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2595 | 2024-04-24 | ex-Guild Eagles   | L   | 0.518      | -            | -                | -                | -         |   -12.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2611 | 2024-04-23 | Nemiga            | L   | 0.512      | -            | -                | -                | -         |    -5.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2621 | 2024-04-22 | Grannys Knockers  | W   | 0.507      | -            | -                | -                | -         |     2.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2627 | 2024-04-22 | Nexus             | W   | 0.505      | -            | -                | -                | -         |     3.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2671 | 2024-04-20 | RUBY              | W   | 0.493      | -            | -                | -                | -         |     5.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2701 | 2024-04-19 | PARIVISION        | W   | 0.487      | -            | -                | -                | -         |     7.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2725 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.485      | -            | -                | -                | -         |     5.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2784 | 2024-04-18 | B8                | L   | 0.478      | -            | -                | -                | -         |    -8.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2806 | 2024-04-17 | B8                | W   | 0.472      | -            | -                | -                | -         |     7.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2835 | 2024-04-16 | Sangal            | L   | 0.467      | -            | -                | -                | -         |    -5.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2857 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.460      | -            | -                | -                | -         |     5.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2907 | 2024-04-12 | JANO              | L   | 0.438      | -            | -                | -                | -         |   -12.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2934 | 2024-04-11 | Alliance          | L   | 0.432      | -            | -                | -                | -         |   -10.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3032 | 2024-04-09 | MOUZ NXT          | L   | 0.419      | -            | -                | -                | -         |    -7.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3095 | 2024-04-07 | ex-Preasy         | L   | 0.405      | -            | -                | -                | -         |   -10.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3264 | 2024-04-01 | Nemiga            | L   | 0.365      | -            | -                | -                | -         |    -4.67 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3672 | 2024-03-10 | CYBERSHOKE        | L   | 0.220      | -            | -                | -                | -         |    -6.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3684 | 2024-03-10 | ECLOT             | W   | 0.219      | -            | -                | -                | -         |     4.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3703 | 2024-03-09 | Sangal            | W   | 0.213      | -            | -                | -                | -         |     3.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3749 | 2024-03-07 | Nemiga            | L   | 0.200      | -            | -                | -                | -         |    -2.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3784 | 2024-03-06 | AURA              | W   | 0.193      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3815 | 2024-03-05 | AMKAL             | L   | 0.187      | -            | -                | -                | -         |    -2.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3874 | 2024-03-03 | Secret            | W   | 0.172      | -            | -                | -                | -         |     0.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3894 | 2024-03-02 | Secret            | W   | 0.165      | -            | -                | -                | -         |     0.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3920 | 2024-02-29 | Young Ninjas      | W   | 0.152      | -            | -                | -                | -         |     0.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4185 | 2024-02-17 | Sashi             | L   | 0.073      | -            | -                | -                | -         |    -0.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4338 | 2024-02-10 | Sampi             | L   | 0.027      | -            | -                | -                | -         |    -0.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,373.69)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.834 | $2,000.00      | $1,667.82       |
| 2024-06-02 |      0.780 | $2,000.00      | $1,559.21       |
| 2024-05-22 |      0.706 | $25,000.00     | $17,656.83      |
| 2024-05-16 |      0.664 | $5,000.00      | $3,321.64       |
| 2024-05-04 |      0.587 | $2,000.00      | $1,173.10       |
| 2024-04-24 |      0.520 | $12,500.00     | $6,495.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
