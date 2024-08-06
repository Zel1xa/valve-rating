### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1148.6<br />
<br />
Final Rank Value (1148.6) = Starting Rank Value (1104.3) + Head To Head Adjustments (44.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.542[<sup>1</sup>](#table2)
- Bounty Collected: 0.480[<sup>2</sup>](#table1)
- Opponent Network: 0.350[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1104.3
- 400 + ( ( 0.343 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1104.3


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
|          104 |        9 | 2024-08-05 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -22.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |       40 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      193 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      243 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.980 (0.490)    | 0 (0.000) |    17.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      431 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.552 (0.276)    | 0 (0.000) |     8.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      520 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -16.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      547 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.164 (0.082)    | 0.933 (0.466)    | 0 (0.000) |    16.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      642 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.695 (0.348)    | 0 (0.000) |    27.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      758 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.611 (0.306)    | 0 (0.000) |    13.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      780 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.499 (0.249)    | 0 (0.000) |     6.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1027 | 2024-06-16 | FAVBET            | W   | 0.862      | -            | -                | -                | 0 (0.000) |     5.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1059 | 2024-06-15 | Nemiga            | L   | 0.855      | -            | -                | -                | -         |   -10.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1100 | 2024-06-14 | RUBY              | W   | 0.849      | -            | -                | -                | 0 (0.000) |     7.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1140 | 2024-06-13 | Monte             | L   | 0.841      | -            | -                | -                | -         |   -15.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1165 | 2024-06-12 | 9INE              | W   | 0.835      | -            | -                | -                | -         |     1.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1185 | 2024-06-11 | DMS               | W   | 0.829      | -            | -                | -                | -         |     7.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1194 | 2024-06-11 | EYEBALLERS        | W   | 0.827      | -            | -                | -                | -         |     6.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1271 | 2024-06-09 | HAVU              | W   | 0.814      | -            | -                | -                | -         |     3.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1286 | 2024-06-09 | Nemiga            | L   | 0.813      | -            | -                | -                | -         |   -10.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1305 | 2024-06-08 | Insilio           | L   | 0.809      | -            | -                | -                | -         |   -17.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1324 | 2024-06-08 | Passion UA        | W   | 0.808      | 0.500        | 0.173 (0.070)    | 1.000 (0.404)    | -         |    11.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1363 | 2024-06-07 | DMS               | W   | 0.802      | -            | -                | -                | -         |     7.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1380 | 2024-06-07 | EYEBALLERS        | L   | 0.801      | -            | -                | -                | -         |   -19.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1400 | 2024-06-07 | 5W                | L   | 0.800      | -            | -                | -                | -         |   -18.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1424 | 2024-06-06 | FAVBET            | W   | 0.796      | -            | -                | -                | -         |     3.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1450 | 2024-06-06 | Permitta          | L   | 0.794      | -            | -                | -                | -         |   -18.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1469 | 2024-06-06 | GhoulsW           | W   | 0.793      | -            | -                | -                | -         |     0.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1505 | 2024-06-05 | Aurora Young Blud | W   | 0.788      | -            | -                | -                | -         |     4.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1544 | 2024-06-04 | CYBERSHOKE        | W   | 0.782      | -            | -                | -                | -         |     4.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1554 | 2024-06-04 | Grannys Knockers  | W   | 0.781      | -            | -                | -                | -         |     3.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1584 | 2024-06-03 | Johnny Speeds     | L   | 0.774      | -            | -                | -                | -         |    -8.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1590 | 2024-06-02 | DMS               | W   | 0.769      | -            | -                | -                | -         |     7.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1597 | 2024-06-02 | SAW               | W   | 0.768      | -            | -                | -                | -         |    14.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1617 | 2024-06-01 | RUBY              | L   | 0.762      | -            | -                | -                | -         |   -17.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1633 | 2024-06-01 | DMS               | W   | 0.761      | -            | -                | -                | -         |     6.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1635 | 2024-06-01 | KOI               | W   | 0.761      | -            | -                | -                | -         |     9.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1642 | 2024-06-01 | FURIA             | L   | 0.760      | -            | -                | -                | -         |    -1.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1671 | 2024-05-31 | Passion UA        | W   | 0.754      | 0.435        | 0.173 (0.057)    | 1.000 (0.328)    | -         |    10.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1679 | 2024-05-30 | ThunderFlash      | W   | 0.749      | -            | -                | -                | -         |     0.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1692 | 2024-05-30 | Passion UA        | L   | 0.748      | -            | -                | -                | -         |   -13.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1708 | 2024-05-29 | JANO              | W   | 0.743      | -            | -                | -                | -         |     1.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1778 | 2024-05-26 | RUBY              | W   | 0.721      | -            | -                | -                | -         |     6.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1791 | 2024-05-25 | ex-Guild Eagles   | W   | 0.715      | -            | -                | -                | -         |     4.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1794 | 2024-05-25 | Serbia            | W   | 0.715      | -            | -                | -                | -         |     3.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1804 | 2024-05-25 | Rhyno             | W   | 0.713      | -            | -                | -                | -         |     7.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1809 | 2024-05-24 | ex-Guild Eagles   | L   | 0.709      | -            | -                | -                | -         |   -18.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1812 | 2024-05-24 | The Suspect       | W   | 0.708      | -            | -                | -                | -         |     3.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1828 | 2024-05-23 | 3DMAX             | L   | 0.701      | -            | -                | -                | -         |    -1.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1835 | 2024-05-23 | brazylijski luz   | W   | 0.699      | -            | -                | -                | -         |     3.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1868 | 2024-05-22 | Sangal            | L   | 0.695      | -            | -                | -                | -         |    -9.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1878 | 2024-05-22 | Illuminar         | W   | 0.693      | -            | -                | -                | -         |     4.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1912 | 2024-05-21 | BLEED             | W   | 0.688      | 0.500        | 0.126 (0.043)    | -                | -         |    17.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1917 | 2024-05-21 | Verdant           | W   | 0.687      | -            | -                | -                | -         |     6.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1940 | 2024-05-20 | Metizport         | W   | 0.682      | -            | -                | -                | -         |     4.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1975 | 2024-05-19 | B8                | W   | 0.674      | 0.500        | 0.164 (0.055)    | 0.933 (0.314)    | -         |    12.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     2029 | 2024-05-17 | PARIVISION        | L   | 0.662      | -            | -                | -                | -         |   -10.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2037 | 2024-05-17 | Endpoint          | W   | 0.661      | -            | -                | -                | -         |     6.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2079 | 2024-05-16 | 1WIN              | L   | 0.654      | -            | -                | -                | -         |   -12.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2086 | 2024-05-16 | kONO              | W   | 0.653      | -            | -                | -                | -         |     4.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2128 | 2024-05-15 | 3DMAX             | W   | 0.647      | 0.500        | 0.509 (0.165)    | 1.000 (0.324)    | -         |    19.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2188 | 2024-05-14 | Preasy            | W   | 0.640      | -            | -                | -                | -         |     1.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2206 | 2024-05-13 | EYEBALLERS        | W   | 0.634      | -            | -                | -                | -         |     5.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2234 | 2024-05-12 | Verdant           | W   | 0.627      | -            | -                | -                | -         |     6.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2304 | 2024-05-09 | 9 Pandas          | L   | 0.607      | -            | -                | -                | -         |   -11.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2359 | 2024-05-06 | Insilio           | W   | 0.588      | -            | -                | -                | -         |     6.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2405 | 2024-05-03 | EYEBALLERS        | L   | 0.569      | -            | -                | -                | -         |   -12.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2418 | 2024-05-03 | Metizport         | L   | 0.567      | -            | -                | -                | -         |   -12.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2446 | 2024-05-02 | HAVU              | W   | 0.560      | -            | -                | -                | -         |     2.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2468 | 2024-05-01 | KOI               | W   | 0.554      | -            | -                | -                | -         |     8.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2481 | 2024-04-30 | Sangal            | L   | 0.548      | -            | -                | -                | -         |    -6.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2493 | 2024-04-30 | B8                | W   | 0.546      | 0.435        | 0.164 (0.039)    | -                | -         |     7.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2508 | 2024-04-29 | PARIVISION        | L   | 0.541      | -            | -                | -                | -         |    -7.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2525 | 2024-04-28 | SINNERS           | W   | 0.534      | -            | -                | -                | -         |     9.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2538 | 2024-04-27 | 500               | W   | 0.529      | -            | -                | -                | -         |     2.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2558 | 2024-04-27 | SINNERS           | W   | 0.526      | -            | -                | -                | -         |     9.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2582 | 2024-04-26 | Illuminar         | W   | 0.520      | -            | -                | -                | -         |     0.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2604 | 2024-04-25 | EYEBALLERS        | L   | 0.514      | -            | -                | -                | -         |   -11.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2627 | 2024-04-24 | ex-Guild Eagles   | L   | 0.507      | -            | -                | -                | -         |   -12.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2643 | 2024-04-23 | Nemiga            | L   | 0.501      | -            | -                | -                | -         |    -5.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2653 | 2024-04-22 | Grannys Knockers  | W   | 0.495      | -            | -                | -                | -         |     2.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2659 | 2024-04-22 | Nexus             | W   | 0.494      | -            | -                | -                | -         |     3.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2703 | 2024-04-20 | RUBY              | W   | 0.481      | -            | -                | -                | -         |     4.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2733 | 2024-04-19 | PARIVISION        | W   | 0.476      | -            | -                | -                | -         |     7.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2757 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.474      | -            | -                | -                | -         |     5.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2816 | 2024-04-18 | B8                | L   | 0.466      | -            | -                | -                | -         |    -7.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2838 | 2024-04-17 | B8                | W   | 0.461      | -            | -                | -                | -         |     6.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2867 | 2024-04-16 | Sangal            | L   | 0.455      | -            | -                | -                | -         |    -5.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2889 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.449      | -            | -                | -                | -         |     5.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2939 | 2024-04-12 | JANO              | L   | 0.426      | -            | -                | -                | -         |   -12.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2966 | 2024-04-11 | Alliance          | L   | 0.421      | -            | -                | -                | -         |   -10.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3064 | 2024-04-09 | MOUZ NXT          | L   | 0.408      | -            | -                | -                | -         |    -7.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3127 | 2024-04-07 | ex-Preasy         | L   | 0.393      | -            | -                | -                | -         |   -10.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3296 | 2024-04-01 | Nemiga            | L   | 0.353      | -            | -                | -                | -         |    -4.60 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3704 | 2024-03-10 | CYBERSHOKE        | L   | 0.209      | -            | -                | -                | -         |    -6.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3716 | 2024-03-10 | ECLOT             | W   | 0.207      | -            | -                | -                | -         |     4.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3735 | 2024-03-09 | Sangal            | W   | 0.201      | -            | -                | -                | -         |     3.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3781 | 2024-03-07 | Nemiga            | L   | 0.188      | -            | -                | -                | -         |    -2.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3816 | 2024-03-06 | AURA              | W   | 0.181      | -            | -                | -                | -         |     0.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3847 | 2024-03-05 | AMKAL             | L   | 0.175      | -            | -                | -                | -         |    -2.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3906 | 2024-03-03 | Secret            | W   | 0.160      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3926 | 2024-03-02 | Secret            | W   | 0.153      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3952 | 2024-02-29 | Young Ninjas      | W   | 0.141      | -            | -                | -                | -         |     0.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4217 | 2024-02-17 | Sashi             | L   | 0.061      | -            | -                | -                | -         |    -0.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4370 | 2024-02-10 | Sampi             | L   | 0.015      | -            | -                | -                | -         |    -0.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,813.47)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.822 | $2,000.00      | $1,644.72       |
| 2024-06-02 |      0.768 | $2,000.00      | $1,536.11       |
| 2024-05-22 |      0.695 | $25,000.00     | $17,368.06      |
| 2024-05-16 |      0.653 | $5,000.00      | $3,263.89       |
| 2024-05-04 |      0.575 | $2,000.00      | $1,150.00       |
| 2024-04-24 |      0.508 | $12,500.00     | $6,350.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
