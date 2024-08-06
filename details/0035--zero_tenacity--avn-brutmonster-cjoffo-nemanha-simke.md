### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1148.5<br />
<br />
Final Rank Value (1148.5) = Starting Rank Value (1104.5) + Head To Head Adjustments (44.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.542[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.351[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1104.5
- 400 + ( ( 0.343 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1104.5


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
|          104 |        5 | 2024-08-05 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -22.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |       36 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      189 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      239 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.982 (0.491)    | 0 (0.000) |    17.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      427 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.552 (0.276)    | 0 (0.000) |     8.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      516 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      543 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.164 (0.082)    | 0.934 (0.467)    | 0 (0.000) |    16.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      638 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.696 (0.348)    | 0 (0.000) |    27.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      754 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.611 (0.306)    | 0 (0.000) |    13.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      776 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |     6.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1023 | 2024-06-16 | FAVBET            | W   | 0.864      | -            | -                | -                | 0 (0.000) |     5.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1055 | 2024-06-15 | Nemiga            | L   | 0.858      | -            | -                | -                | -         |   -10.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1096 | 2024-06-14 | RUBY              | W   | 0.851      | -            | -                | -                | 0 (0.000) |     7.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1136 | 2024-06-13 | Monte             | L   | 0.844      | -            | -                | -                | -         |   -15.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1161 | 2024-06-12 | 9INE              | W   | 0.838      | -            | -                | -                | -         |     1.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1181 | 2024-06-11 | DMS               | W   | 0.831      | -            | -                | -                | -         |     7.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1190 | 2024-06-11 | EYEBALLERS        | W   | 0.830      | -            | -                | -                | -         |     6.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1267 | 2024-06-09 | HAVU              | W   | 0.816      | -            | -                | -                | -         |     3.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1282 | 2024-06-09 | Nemiga            | L   | 0.816      | -            | -                | -                | -         |   -10.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1301 | 2024-06-08 | Insilio           | L   | 0.812      | -            | -                | -                | -         |   -17.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1320 | 2024-06-08 | Passion UA        | W   | 0.811      | 0.500        | 0.173 (0.070)    | 1.000 (0.405)    | -         |    11.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1359 | 2024-06-07 | DMS               | W   | 0.805      | -            | -                | -                | -         |     7.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1376 | 2024-06-07 | EYEBALLERS        | L   | 0.804      | -            | -                | -                | -         |   -19.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1396 | 2024-06-07 | 5W                | L   | 0.802      | -            | -                | -                | -         |   -18.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1420 | 2024-06-06 | FAVBET            | W   | 0.798      | -            | -                | -                | -         |     3.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1446 | 2024-06-06 | Permitta          | L   | 0.797      | -            | -                | -                | -         |   -19.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1465 | 2024-06-06 | GhoulsW           | W   | 0.796      | -            | -                | -                | -         |     0.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1501 | 2024-06-05 | Aurora Young Blud | W   | 0.791      | -            | -                | -                | -         |     4.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1540 | 2024-06-04 | CYBERSHOKE        | W   | 0.785      | -            | -                | -                | -         |     4.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1550 | 2024-06-04 | Grannys Knockers  | W   | 0.783      | -            | -                | -                | -         |     3.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1580 | 2024-06-03 | Johnny Speeds     | L   | 0.776      | -            | -                | -                | -         |    -8.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1586 | 2024-06-02 | DMS               | W   | 0.772      | -            | -                | -                | -         |     7.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1593 | 2024-06-02 | SAW               | W   | 0.771      | -            | -                | -                | -         |    15.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1613 | 2024-06-01 | RUBY              | L   | 0.765      | -            | -                | -                | -         |   -17.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1629 | 2024-06-01 | DMS               | W   | 0.764      | -            | -                | -                | -         |     6.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1631 | 2024-06-01 | KOI               | W   | 0.763      | -            | -                | -                | -         |     9.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1638 | 2024-06-01 | FURIA             | L   | 0.762      | -            | -                | -                | -         |    -1.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1667 | 2024-05-31 | Passion UA        | W   | 0.756      | 0.435        | 0.173 (0.057)    | 1.000 (0.329)    | -         |    10.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1675 | 2024-05-30 | ThunderFlash      | W   | 0.752      | -            | -                | -                | -         |     0.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1688 | 2024-05-30 | Passion UA        | L   | 0.750      | -            | -                | -                | -         |   -13.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1704 | 2024-05-29 | JANO              | W   | 0.745      | -            | -                | -                | -         |     1.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1774 | 2024-05-26 | RUBY              | W   | 0.723      | -            | -                | -                | -         |     6.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1787 | 2024-05-25 | ex-Guild Eagles   | W   | 0.718      | -            | -                | -                | -         |     4.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1790 | 2024-05-25 | Serbia            | W   | 0.717      | -            | -                | -                | -         |     3.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1800 | 2024-05-25 | Rhyno             | W   | 0.716      | -            | -                | -                | -         |     8.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1805 | 2024-05-24 | ex-Guild Eagles   | L   | 0.711      | -            | -                | -                | -         |   -18.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1808 | 2024-05-24 | The Suspect       | W   | 0.711      | -            | -                | -                | -         |     3.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1824 | 2024-05-23 | 3DMAX             | L   | 0.704      | -            | -                | -                | -         |    -1.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1831 | 2024-05-23 | brazylijski luz   | W   | 0.702      | -            | -                | -                | -         |     3.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1864 | 2024-05-22 | Sangal            | L   | 0.697      | -            | -                | -                | -         |   -10.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1874 | 2024-05-22 | Illuminar         | W   | 0.696      | -            | -                | -                | -         |     4.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1908 | 2024-05-21 | BLEED             | W   | 0.691      | 0.500        | 0.126 (0.043)    | -                | -         |    18.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1913 | 2024-05-21 | Verdant           | W   | 0.689      | -            | -                | -                | -         |     6.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1936 | 2024-05-20 | Metizport         | W   | 0.685      | -            | -                | -                | -         |     4.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1971 | 2024-05-19 | B8                | W   | 0.676      | 0.500        | 0.164 (0.056)    | 0.934 (0.316)    | -         |    12.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     2025 | 2024-05-17 | PARIVISION        | L   | 0.665      | -            | -                | -                | -         |   -10.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2033 | 2024-05-17 | Endpoint          | W   | 0.664      | -            | -                | -                | -         |     6.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2075 | 2024-05-16 | 1WIN              | L   | 0.656      | -            | -                | -                | -         |   -12.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2082 | 2024-05-16 | kONO              | W   | 0.655      | -            | -                | -                | -         |     4.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2124 | 2024-05-15 | 3DMAX             | W   | 0.650      | 0.500        | 0.509 (0.165)    | 1.000 (0.325)    | -         |    19.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2184 | 2024-05-14 | Preasy            | W   | 0.643      | -            | -                | -                | -         |     1.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2202 | 2024-05-13 | EYEBALLERS        | W   | 0.637      | -            | -                | -                | -         |     5.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2230 | 2024-05-12 | Verdant           | W   | 0.630      | -            | -                | -                | -         |     6.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2300 | 2024-05-09 | 9 Pandas          | L   | 0.610      | -            | -                | -                | -         |   -11.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2355 | 2024-05-06 | Insilio           | W   | 0.591      | -            | -                | -                | -         |     6.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2401 | 2024-05-03 | EYEBALLERS        | L   | 0.571      | -            | -                | -                | -         |   -12.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2414 | 2024-05-03 | Metizport         | L   | 0.569      | -            | -                | -                | -         |   -13.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2442 | 2024-05-02 | HAVU              | W   | 0.562      | -            | -                | -                | -         |     2.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2464 | 2024-05-01 | KOI               | W   | 0.556      | -            | -                | -                | -         |     8.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2477 | 2024-04-30 | Sangal            | L   | 0.551      | -            | -                | -                | -         |    -7.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2489 | 2024-04-30 | B8                | W   | 0.549      | 0.435        | 0.164 (0.039)    | -                | -         |     7.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2504 | 2024-04-29 | PARIVISION        | L   | 0.543      | -            | -                | -                | -         |    -8.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2521 | 2024-04-28 | SINNERS           | W   | 0.537      | -            | -                | -                | -         |     9.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2534 | 2024-04-27 | 500               | W   | 0.531      | -            | -                | -                | -         |     2.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2554 | 2024-04-27 | SINNERS           | W   | 0.529      | -            | -                | -                | -         |     9.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2578 | 2024-04-26 | Illuminar         | W   | 0.522      | -            | -                | -                | -         |     0.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2600 | 2024-04-25 | EYEBALLERS        | L   | 0.516      | -            | -                | -                | -         |   -11.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2623 | 2024-04-24 | ex-Guild Eagles   | L   | 0.509      | -            | -                | -                | -         |   -12.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2639 | 2024-04-23 | Nemiga            | L   | 0.503      | -            | -                | -                | -         |    -5.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2649 | 2024-04-22 | Grannys Knockers  | W   | 0.498      | -            | -                | -                | -         |     2.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2655 | 2024-04-22 | Nexus             | W   | 0.496      | -            | -                | -                | -         |     3.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2699 | 2024-04-20 | RUBY              | W   | 0.484      | -            | -                | -                | -         |     4.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2729 | 2024-04-19 | PARIVISION        | W   | 0.478      | -            | -                | -                | -         |     7.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2753 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.476      | -            | -                | -                | -         |     5.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2812 | 2024-04-18 | B8                | L   | 0.469      | -            | -                | -                | -         |    -7.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2834 | 2024-04-17 | B8                | W   | 0.463      | -            | -                | -                | -         |     6.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2863 | 2024-04-16 | Sangal            | L   | 0.458      | -            | -                | -                | -         |    -5.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2885 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.451      | -            | -                | -                | -         |     5.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2935 | 2024-04-12 | JANO              | L   | 0.429      | -            | -                | -                | -         |   -12.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2962 | 2024-04-11 | Alliance          | L   | 0.423      | -            | -                | -                | -         |   -10.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3060 | 2024-04-09 | MOUZ NXT          | L   | 0.410      | -            | -                | -                | -         |    -7.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3123 | 2024-04-07 | ex-Preasy         | L   | 0.396      | -            | -                | -                | -         |   -10.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3292 | 2024-04-01 | Nemiga            | L   | 0.356      | -            | -                | -                | -         |    -4.63 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3700 | 2024-03-10 | CYBERSHOKE        | L   | 0.211      | -            | -                | -                | -         |    -6.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3712 | 2024-03-10 | ECLOT             | W   | 0.210      | -            | -                | -                | -         |     4.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3731 | 2024-03-09 | Sangal            | W   | 0.204      | -            | -                | -                | -         |     3.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3777 | 2024-03-07 | Nemiga            | L   | 0.191      | -            | -                | -                | -         |    -2.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3812 | 2024-03-06 | AURA              | W   | 0.184      | -            | -                | -                | -         |     0.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3843 | 2024-03-05 | AMKAL             | L   | 0.178      | -            | -                | -                | -         |    -2.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3902 | 2024-03-03 | Secret            | W   | 0.163      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3922 | 2024-03-02 | Secret            | W   | 0.156      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3948 | 2024-02-29 | Young Ninjas      | W   | 0.143      | -            | -                | -                | -         |     0.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4213 | 2024-02-17 | Sashi             | L   | 0.064      | -            | -                | -                | -         |    -0.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4366 | 2024-02-10 | Sampi             | L   | 0.018      | -            | -                | -                | -         |    -0.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,934.72)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.825 | $2,000.00      | $1,649.72       |
| 2024-06-02 |      0.771 | $2,000.00      | $1,541.11       |
| 2024-05-22 |      0.697 | $25,000.00     | $17,430.56      |
| 2024-05-16 |      0.655 | $5,000.00      | $3,276.39       |
| 2024-05-04 |      0.578 | $2,000.00      | $1,155.00       |
| 2024-04-24 |      0.511 | $12,500.00     | $6,381.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
