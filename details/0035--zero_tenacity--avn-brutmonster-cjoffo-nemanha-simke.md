### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1166.4<br />
<br />
Final Rank Value (1166.4) = Starting Rank Value (1100.4) + Head To Head Adjustments (66.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.352[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1100.4
- 400 + ( ( 0.343 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1100.4


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
|          102 |      137 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      188 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.962 (0.481)    | 0 (0.000) |    17.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      375 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.561 (0.281)    | 0 (0.000) |     8.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      464 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      491 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.912 (0.456)    | 0 (0.000) |    16.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      587 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.708 (0.354)    | 0 (0.000) |    27.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      701 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.619 (0.309)    | 0 (0.000) |    13.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      725 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.510 (0.255)    | 0 (0.000) |     6.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |      971 | 2024-06-16 | FAVBET            | W   | 0.875      | -            | -                | -                | 0 (0.000) |     5.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1003 | 2024-06-15 | Nemiga            | L   | 0.868      | -            | -                | -                | -         |   -10.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1044 | 2024-06-14 | RUBY              | W   | 0.861      | -            | -                | -                | 0 (0.000) |     7.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1084 | 2024-06-13 | Monte             | L   | 0.854      | -            | -                | -                | -         |   -15.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1109 | 2024-06-12 | 9INE              | W   | 0.848      | -            | -                | -                | 0 (0.000) |     1.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1129 | 2024-06-11 | DMS               | W   | 0.841      | -            | -                | -                | -         |     7.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1138 | 2024-06-11 | EYEBALLERS        | W   | 0.840      | -            | -                | -                | -         |     6.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1215 | 2024-06-09 | HAVU              | W   | 0.826      | -            | -                | -                | -         |     3.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1230 | 2024-06-09 | Nemiga            | L   | 0.826      | -            | -                | -                | -         |   -11.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1249 | 2024-06-08 | Insilio           | L   | 0.822      | -            | -                | -                | -         |   -17.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1268 | 2024-06-08 | Passion UA        | W   | 0.821      | 0.500        | 0.172 (0.071)    | 1.000 (0.410)    | -         |    11.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1307 | 2024-06-07 | DMS               | W   | 0.815      | -            | -                | -                | -         |     7.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1324 | 2024-06-07 | EYEBALLERS        | L   | 0.814      | -            | -                | -                | -         |   -19.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1344 | 2024-06-07 | 5W                | L   | 0.812      | -            | -                | -                | -         |   -18.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1368 | 2024-06-06 | FAVBET            | W   | 0.808      | -            | -                | -                | -         |     3.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1394 | 2024-06-06 | Permitta          | L   | 0.807      | -            | -                | -                | -         |   -19.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1413 | 2024-06-06 | GhoulsW           | W   | 0.806      | -            | -                | -                | -         |     0.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1449 | 2024-06-05 | Aurora Young Blud | W   | 0.801      | -            | -                | -                | -         |     4.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1488 | 2024-06-04 | CYBERSHOKE        | W   | 0.795      | -            | -                | -                | -         |     4.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1498 | 2024-06-04 | Grannys Knockers  | W   | 0.794      | -            | -                | -                | -         |     3.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1528 | 2024-06-03 | Johnny Speeds     | L   | 0.786      | -            | -                | -                | -         |    -8.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1534 | 2024-06-02 | DMS               | W   | 0.782      | -            | -                | -                | -         |     7.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1541 | 2024-06-02 | SAW               | W   | 0.781      | -            | -                | -                | -         |    15.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1561 | 2024-06-01 | RUBY              | L   | 0.775      | -            | -                | -                | -         |   -17.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1577 | 2024-06-01 | DMS               | W   | 0.774      | -            | -                | -                | -         |     6.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1579 | 2024-06-01 | KOI               | W   | 0.773      | -            | -                | -                | -         |     9.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1586 | 2024-06-01 | FURIA             | L   | 0.772      | -            | -                | -                | -         |    -1.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1615 | 2024-05-31 | Passion UA        | W   | 0.767      | 0.435        | 0.172 (0.057)    | 1.000 (0.333)    | -         |    10.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1623 | 2024-05-30 | ThunderFlash      | W   | 0.762      | -            | -                | -                | -         |     0.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1636 | 2024-05-30 | Passion UA        | L   | 0.760      | -            | -                | -                | -         |   -13.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1652 | 2024-05-29 | JANO              | W   | 0.755      | -            | -                | -                | -         |     1.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1722 | 2024-05-26 | RUBY              | W   | 0.733      | -            | -                | -                | -         |     6.71 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1735 | 2024-05-25 | ex-Guild Eagles   | W   | 0.728      | -            | -                | -                | -         |     4.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1738 | 2024-05-25 | Serbia            | W   | 0.727      | -            | -                | -                | -         |     3.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1748 | 2024-05-25 | Rhyno             | W   | 0.726      | -            | -                | -                | -         |     8.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1753 | 2024-05-24 | ex-Guild Eagles   | L   | 0.722      | -            | -                | -                | -         |   -18.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1756 | 2024-05-24 | The Suspect       | W   | 0.721      | -            | -                | -                | -         |     3.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1772 | 2024-05-23 | 3DMAX             | L   | 0.714      | -            | -                | -                | -         |    -1.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1779 | 2024-05-23 | brazylijski luz   | W   | 0.712      | -            | -                | -                | -         |     4.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1812 | 2024-05-22 | Sangal            | L   | 0.707      | -            | -                | -                | -         |   -10.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1822 | 2024-05-22 | Illuminar         | W   | 0.706      | -            | -                | -                | -         |     4.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1856 | 2024-05-21 | BLEED             | W   | 0.701      | 0.500        | 0.126 (0.044)    | -                | -         |    18.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1861 | 2024-05-21 | Verdant           | W   | 0.699      | -            | -                | -                | -         |     6.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1884 | 2024-05-20 | Metizport         | W   | 0.695      | -            | -                | -                | -         |     8.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1919 | 2024-05-19 | B8                | W   | 0.687      | 0.500        | 0.165 (0.057)    | 0.912 (0.313)    | -         |    13.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     1973 | 2024-05-17 | PARIVISION        | L   | 0.675      | -            | -                | -                | -         |   -10.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     1981 | 2024-05-17 | Endpoint          | W   | 0.674      | -            | -                | -                | -         |     6.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2023 | 2024-05-16 | 1WIN              | L   | 0.666      | -            | -                | -                | -         |   -13.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2030 | 2024-05-16 | kONO              | W   | 0.665      | -            | -                | -                | -         |     4.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2072 | 2024-05-15 | 3DMAX             | W   | 0.660      | 0.500        | 0.506 (0.167)    | 1.000 (0.330)    | -         |    19.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2132 | 2024-05-14 | Preasy            | W   | 0.653      | -            | -                | -                | -         |     3.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2150 | 2024-05-13 | EYEBALLERS        | W   | 0.647      | -            | -                | -                | -         |     6.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2178 | 2024-05-12 | Verdant           | W   | 0.640      | -            | -                | -                | -         |     7.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2248 | 2024-05-09 | 9 Pandas          | L   | 0.620      | -            | -                | -                | -         |   -11.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2303 | 2024-05-06 | Insilio           | W   | 0.601      | -            | -                | -                | -         |     6.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2349 | 2024-05-03 | EYEBALLERS        | L   | 0.582      | -            | -                | -                | -         |   -12.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2362 | 2024-05-03 | Metizport         | L   | 0.580      | -            | -                | -                | -         |   -11.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2390 | 2024-05-02 | HAVU              | W   | 0.572      | -            | -                | -                | -         |     2.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2412 | 2024-05-01 | KOI               | W   | 0.566      | -            | -                | -                | -         |     9.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2425 | 2024-04-30 | Sangal            | L   | 0.561      | -            | -                | -                | -         |    -7.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2437 | 2024-04-30 | B8                | W   | 0.559      | 0.435        | 0.165 (0.040)    | -                | -         |     8.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2452 | 2024-04-29 | PARIVISION        | L   | 0.553      | -            | -                | -                | -         |    -8.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2469 | 2024-04-28 | SINNERS           | W   | 0.547      | -            | -                | -                | -         |     8.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2482 | 2024-04-27 | 500               | W   | 0.542      | -            | -                | -                | -         |     2.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2502 | 2024-04-27 | SINNERS           | W   | 0.539      | -            | -                | -                | -         |     8.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2526 | 2024-04-26 | Illuminar         | W   | 0.532      | -            | -                | -                | -         |     1.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2548 | 2024-04-25 | EYEBALLERS        | L   | 0.527      | -            | -                | -                | -         |   -12.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2571 | 2024-04-24 | ex-Guild Eagles   | L   | 0.520      | -            | -                | -                | -         |   -12.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2587 | 2024-04-23 | Nemiga            | L   | 0.513      | -            | -                | -                | -         |    -6.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2597 | 2024-04-22 | Grannys Knockers  | W   | 0.508      | -            | -                | -                | -         |     2.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2603 | 2024-04-22 | Nexus             | W   | 0.507      | -            | -                | -                | -         |     3.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2647 | 2024-04-20 | RUBY              | W   | 0.494      | -            | -                | -                | -         |     5.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2677 | 2024-04-19 | PARIVISION        | W   | 0.488      | -            | -                | -                | -         |     7.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2701 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.486      | -            | -                | -                | -         |     5.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2760 | 2024-04-18 | B8                | L   | 0.479      | -            | -                | -                | -         |    -8.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2782 | 2024-04-17 | B8                | W   | 0.473      | -            | -                | -                | -         |     7.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2811 | 2024-04-16 | Sangal            | L   | 0.468      | -            | -                | -                | -         |    -5.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2833 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.461      | -            | -                | -                | -         |     5.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2883 | 2024-04-12 | JANO              | L   | 0.439      | -            | -                | -                | -         |   -12.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2910 | 2024-04-11 | Alliance          | L   | 0.433      | -            | -                | -                | -         |   -10.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3008 | 2024-04-09 | MOUZ NXT          | L   | 0.420      | -            | -                | -                | -         |    -7.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3071 | 2024-04-07 | ex-Preasy         | L   | 0.406      | -            | -                | -                | -         |   -10.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3240 | 2024-04-01 | Nemiga            | L   | 0.366      | -            | -                | -                | -         |    -4.99 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3648 | 2024-03-10 | CYBERSHOKE        | L   | 0.222      | -            | -                | -                | -         |    -6.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3660 | 2024-03-10 | ECLOT             | W   | 0.220      | -            | -                | -                | -         |     4.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3679 | 2024-03-09 | Sangal            | W   | 0.214      | -            | -                | -                | -         |     3.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3725 | 2024-03-07 | Nemiga            | L   | 0.201      | -            | -                | -                | -         |    -2.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3760 | 2024-03-06 | AURA              | W   | 0.194      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3791 | 2024-03-05 | AMKAL             | L   | 0.188      | -            | -                | -                | -         |    -2.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3850 | 2024-03-03 | Secret            | W   | 0.173      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3870 | 2024-03-02 | Secret            | W   | 0.166      | -            | -                | -                | -         |     0.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3896 | 2024-02-29 | Young Ninjas      | W   | 0.153      | -            | -                | -                | -         |     0.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4161 | 2024-02-17 | Sashi             | L   | 0.074      | -            | -                | -                | -         |    -0.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4314 | 2024-02-10 | Sampi             | L   | 0.028      | -            | -                | -                | -         |    -0.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,425.34)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.835 | $2,000.00      | $1,669.95       |
| 2024-06-02 |      0.781 | $2,000.00      | $1,561.34       |
| 2024-05-22 |      0.707 | $25,000.00     | $17,683.45      |
| 2024-05-16 |      0.665 | $5,000.00      | $3,326.97       |
| 2024-05-04 |      0.588 | $2,000.00      | $1,175.23       |
| 2024-04-24 |      0.521 | $12,500.00     | $6,508.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
