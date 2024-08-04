### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1169.4<br />
<br />
Final Rank Value (1169.4) = Starting Rank Value (1100.4) + Head To Head Adjustments (69.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.352[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.342<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1100.4
- 400 + ( ( 0.342 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1100.4


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
|          103 |        7 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      160 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      210 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.962 (0.481)    | 0 (0.000) |    17.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      398 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.561 (0.281)    | 0 (0.000) |     8.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      487 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      514 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.912 (0.456)    | 0 (0.000) |    16.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      609 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.708 (0.354)    | 0 (0.000) |    27.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      725 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.619 (0.309)    | 0 (0.000) |    13.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      747 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.509 (0.255)    | 0 (0.000) |     6.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |      994 | 2024-06-16 | FAVBET            | W   | 0.874      | -            | -                | -                | 0 (0.000) |     5.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1026 | 2024-06-15 | Nemiga            | L   | 0.867      | -            | -                | -                | -         |   -10.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1067 | 2024-06-14 | RUBY              | W   | 0.860      | -            | -                | -                | 0 (0.000) |     7.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1107 | 2024-06-13 | Monte             | L   | 0.853      | -            | -                | -                | -         |   -15.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1132 | 2024-06-12 | 9INE              | W   | 0.847      | -            | -                | -                | -         |     1.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1152 | 2024-06-11 | DMS               | W   | 0.840      | -            | -                | -                | -         |     7.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1161 | 2024-06-11 | EYEBALLERS        | W   | 0.839      | -            | -                | -                | -         |     6.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1238 | 2024-06-09 | HAVU              | W   | 0.826      | -            | -                | -                | -         |     3.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1253 | 2024-06-09 | Nemiga            | L   | 0.825      | -            | -                | -                | -         |   -11.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1272 | 2024-06-08 | Insilio           | L   | 0.821      | -            | -                | -                | -         |   -17.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1291 | 2024-06-08 | Passion UA        | W   | 0.820      | 0.500        | 0.172 (0.071)    | 1.000 (0.410)    | -         |    11.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1330 | 2024-06-07 | DMS               | W   | 0.814      | -            | -                | -                | -         |     7.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1347 | 2024-06-07 | EYEBALLERS        | L   | 0.813      | -            | -                | -                | -         |   -19.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1367 | 2024-06-07 | 5W                | L   | 0.812      | -            | -                | -                | -         |   -18.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1391 | 2024-06-06 | FAVBET            | W   | 0.808      | -            | -                | -                | -         |     3.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1417 | 2024-06-06 | Permitta          | L   | 0.806      | -            | -                | -                | -         |   -19.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1436 | 2024-06-06 | GhoulsW           | W   | 0.805      | -            | -                | -                | -         |     0.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1472 | 2024-06-05 | Aurora Young Blud | W   | 0.800      | -            | -                | -                | -         |     4.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1511 | 2024-06-04 | CYBERSHOKE        | W   | 0.794      | -            | -                | -                | -         |     4.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1521 | 2024-06-04 | Grannys Knockers  | W   | 0.793      | -            | -                | -                | -         |     3.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1551 | 2024-06-03 | Johnny Speeds     | L   | 0.786      | -            | -                | -                | -         |    -8.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1557 | 2024-06-02 | DMS               | W   | 0.781      | -            | -                | -                | -         |     7.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1564 | 2024-06-02 | SAW               | W   | 0.780      | -            | -                | -                | -         |    15.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1584 | 2024-06-01 | RUBY              | L   | 0.774      | -            | -                | -                | -         |   -17.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1600 | 2024-06-01 | DMS               | W   | 0.773      | -            | -                | -                | -         |     6.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1602 | 2024-06-01 | KOI               | W   | 0.773      | -            | -                | -                | -         |    10.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1609 | 2024-06-01 | FURIA             | L   | 0.772      | -            | -                | -                | -         |    -1.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1638 | 2024-05-31 | Passion UA        | W   | 0.766      | 0.435        | 0.172 (0.057)    | 1.000 (0.333)    | -         |    10.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1646 | 2024-05-30 | ThunderFlash      | W   | 0.761      | -            | -                | -                | -         |     0.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1659 | 2024-05-30 | Passion UA        | L   | 0.760      | -            | -                | -                | -         |   -13.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1675 | 2024-05-29 | JANO              | W   | 0.754      | -            | -                | -                | -         |     1.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1745 | 2024-05-26 | RUBY              | W   | 0.732      | -            | -                | -                | -         |     6.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1758 | 2024-05-25 | ex-Guild Eagles   | W   | 0.727      | -            | -                | -                | -         |     4.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1761 | 2024-05-25 | Serbia            | W   | 0.727      | -            | -                | -                | -         |     3.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1771 | 2024-05-25 | Rhyno             | W   | 0.725      | -            | -                | -                | -         |     8.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1776 | 2024-05-24 | ex-Guild Eagles   | L   | 0.721      | -            | -                | -                | -         |   -18.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1779 | 2024-05-24 | The Suspect       | W   | 0.720      | -            | -                | -                | -         |     3.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1795 | 2024-05-23 | 3DMAX             | L   | 0.713      | -            | -                | -                | -         |    -1.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1802 | 2024-05-23 | brazylijski luz   | W   | 0.711      | -            | -                | -                | -         |     4.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1835 | 2024-05-22 | Sangal            | L   | 0.707      | -            | -                | -                | -         |   -10.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1845 | 2024-05-22 | Illuminar         | W   | 0.705      | -            | -                | -                | -         |     4.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1879 | 2024-05-21 | BLEED             | W   | 0.700      | 0.500        | 0.126 (0.044)    | -                | -         |    18.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1884 | 2024-05-21 | Verdant           | W   | 0.699      | -            | -                | -                | -         |     6.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1907 | 2024-05-20 | Metizport         | W   | 0.694      | -            | -                | -                | -         |     4.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1942 | 2024-05-19 | B8                | W   | 0.686      | 0.500        | 0.165 (0.057)    | 0.912 (0.313)    | -         |    13.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     1996 | 2024-05-17 | PARIVISION        | L   | 0.674      | -            | -                | -                | -         |   -10.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2004 | 2024-05-17 | Endpoint          | W   | 0.673      | -            | -                | -                | -         |     6.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2046 | 2024-05-16 | 1WIN              | L   | 0.666      | -            | -                | -                | -         |   -13.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2053 | 2024-05-16 | kONO              | W   | 0.665      | -            | -                | -                | -         |     4.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2095 | 2024-05-15 | 3DMAX             | W   | 0.659      | 0.500        | 0.506 (0.167)    | 1.000 (0.330)    | -         |    19.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2155 | 2024-05-14 | Preasy            | W   | 0.652      | -            | -                | -                | -         |     3.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2173 | 2024-05-13 | EYEBALLERS        | W   | 0.646      | -            | -                | -                | -         |     6.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2201 | 2024-05-12 | Verdant           | W   | 0.639      | -            | -                | -                | -         |     7.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2271 | 2024-05-09 | 9 Pandas          | L   | 0.619      | -            | -                | -                | -         |   -11.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2326 | 2024-05-06 | Insilio           | W   | 0.600      | -            | -                | -                | -         |     6.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2372 | 2024-05-03 | EYEBALLERS        | L   | 0.581      | -            | -                | -                | -         |   -12.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2385 | 2024-05-03 | Metizport         | L   | 0.579      | -            | -                | -                | -         |   -13.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2413 | 2024-05-02 | HAVU              | W   | 0.572      | -            | -                | -                | -         |     2.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2435 | 2024-05-01 | KOI               | W   | 0.565      | -            | -                | -                | -         |     9.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2448 | 2024-04-30 | Sangal            | L   | 0.560      | -            | -                | -                | -         |    -7.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2460 | 2024-04-30 | B8                | W   | 0.558      | 0.435        | 0.165 (0.040)    | -                | -         |     8.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2475 | 2024-04-29 | PARIVISION        | L   | 0.552      | -            | -                | -                | -         |    -8.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2492 | 2024-04-28 | SINNERS           | W   | 0.546      | -            | -                | -                | -         |     9.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2505 | 2024-04-27 | 500               | W   | 0.541      | -            | -                | -                | -         |     2.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2525 | 2024-04-27 | SINNERS           | W   | 0.538      | -            | -                | -                | -         |     9.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2549 | 2024-04-26 | Illuminar         | W   | 0.532      | -            | -                | -                | -         |     1.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2571 | 2024-04-25 | EYEBALLERS        | L   | 0.526      | -            | -                | -                | -         |   -12.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2594 | 2024-04-24 | ex-Guild Eagles   | L   | 0.519      | -            | -                | -                | -         |   -12.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2610 | 2024-04-23 | Nemiga            | L   | 0.512      | -            | -                | -                | -         |    -5.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2620 | 2024-04-22 | Grannys Knockers  | W   | 0.507      | -            | -                | -                | -         |     2.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2626 | 2024-04-22 | Nexus             | W   | 0.506      | -            | -                | -                | -         |     3.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2670 | 2024-04-20 | RUBY              | W   | 0.493      | -            | -                | -                | -         |     5.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2700 | 2024-04-19 | PARIVISION        | W   | 0.487      | -            | -                | -                | -         |     7.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2724 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.485      | -            | -                | -                | -         |     5.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2783 | 2024-04-18 | B8                | L   | 0.478      | -            | -                | -                | -         |    -8.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2805 | 2024-04-17 | B8                | W   | 0.472      | -            | -                | -                | -         |     7.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2834 | 2024-04-16 | Sangal            | L   | 0.467      | -            | -                | -                | -         |    -5.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2856 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.460      | -            | -                | -                | -         |     5.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2906 | 2024-04-12 | JANO              | L   | 0.438      | -            | -                | -                | -         |   -12.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2933 | 2024-04-11 | Alliance          | L   | 0.433      | -            | -                | -                | -         |   -10.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3031 | 2024-04-09 | MOUZ NXT          | L   | 0.420      | -            | -                | -                | -         |    -7.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3094 | 2024-04-07 | ex-Preasy         | L   | 0.405      | -            | -                | -                | -         |   -10.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3263 | 2024-04-01 | Nemiga            | L   | 0.365      | -            | -                | -                | -         |    -4.65 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3671 | 2024-03-10 | CYBERSHOKE        | L   | 0.221      | -            | -                | -                | -         |    -6.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3683 | 2024-03-10 | ECLOT             | W   | 0.219      | -            | -                | -                | -         |     4.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3702 | 2024-03-09 | Sangal            | W   | 0.213      | -            | -                | -                | -         |     3.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3748 | 2024-03-07 | Nemiga            | L   | 0.200      | -            | -                | -                | -         |    -2.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3783 | 2024-03-06 | AURA              | W   | 0.193      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3814 | 2024-03-05 | AMKAL             | L   | 0.187      | -            | -                | -                | -         |    -2.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3873 | 2024-03-03 | Secret            | W   | 0.172      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3893 | 2024-03-02 | Secret            | W   | 0.165      | -            | -                | -                | -         |     0.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3919 | 2024-02-29 | Young Ninjas      | W   | 0.153      | -            | -                | -                | -         |     0.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4184 | 2024-02-17 | Sashi             | L   | 0.073      | -            | -                | -                | -         |    -0.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4337 | 2024-02-10 | Sampi             | L   | 0.027      | -            | -                | -                | -         |    -0.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,388.29)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.834 | $2,000.00      | $1,668.43       |
| 2024-06-02 |      0.780 | $2,000.00      | $1,559.81       |
| 2024-05-22 |      0.707 | $25,000.00     | $17,664.35      |
| 2024-05-16 |      0.665 | $5,000.00      | $3,323.15       |
| 2024-05-04 |      0.587 | $2,000.00      | $1,173.70       |
| 2024-04-24 |      0.520 | $12,500.00     | $6,498.84       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
