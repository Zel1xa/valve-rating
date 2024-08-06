### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1152.3<br />
<br />
Final Rank Value (1152.3) = Starting Rank Value (1103.5) + Head To Head Adjustments (48.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.542[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.345[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.342<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1103.5
- 400 + ( ( 0.342 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1103.5


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
|          104 |       21 | 2024-08-05 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -22.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |       52 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      205 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      255 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.958 (0.479)    | 0 (0.000) |    16.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      443 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.539 (0.270)    | 0 (0.000) |     8.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      532 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -16.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      559 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | 0 (0.000) |    16.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      654 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.680 (0.340)    | 0 (0.000) |    27.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      770 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.598 (0.299)    | 0 (0.000) |    13.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      792 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |     6.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1039 | 2024-06-16 | FAVBET            | W   | 0.861      | -            | -                | -                | 0 (0.000) |     5.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1071 | 2024-06-15 | Nemiga            | L   | 0.854      | -            | -                | -                | -         |   -10.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1112 | 2024-06-14 | RUBY              | W   | 0.847      | -            | -                | -                | 0 (0.000) |     7.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1152 | 2024-06-13 | Monte             | L   | 0.840      | -            | -                | -                | -         |   -15.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1177 | 2024-06-12 | 9INE              | W   | 0.834      | -            | -                | -                | -         |     1.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1197 | 2024-06-11 | DMS               | W   | 0.827      | -            | -                | -                | -         |     7.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1206 | 2024-06-11 | EYEBALLERS        | W   | 0.826      | -            | -                | -                | -         |     6.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1283 | 2024-06-09 | HAVU              | W   | 0.813      | -            | -                | -                | -         |     2.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1298 | 2024-06-09 | Nemiga            | L   | 0.812      | -            | -                | -                | -         |   -11.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1317 | 2024-06-08 | Insilio           | L   | 0.808      | -            | -                | -                | -         |   -17.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1336 | 2024-06-08 | Passion UA        | W   | 0.807      | 0.500        | 0.173 (0.070)    | 1.000 (0.403)    | -         |    11.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1375 | 2024-06-07 | DMS               | W   | 0.801      | -            | -                | -                | -         |     7.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1392 | 2024-06-07 | EYEBALLERS        | L   | 0.800      | -            | -                | -                | -         |   -19.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1412 | 2024-06-07 | 5W                | L   | 0.799      | -            | -                | -                | -         |   -18.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1436 | 2024-06-06 | FAVBET            | W   | 0.795      | -            | -                | -                | -         |     3.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1462 | 2024-06-06 | Permitta          | L   | 0.793      | -            | -                | -                | -         |   -18.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1481 | 2024-06-06 | GhoulsW           | W   | 0.792      | -            | -                | -                | -         |     0.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1517 | 2024-06-05 | Aurora Young Blud | W   | 0.787      | -            | -                | -                | -         |     5.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1556 | 2024-06-04 | CYBERSHOKE        | W   | 0.781      | -            | -                | -                | -         |     4.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1566 | 2024-06-04 | Grannys Knockers  | W   | 0.780      | -            | -                | -                | -         |     3.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1596 | 2024-06-03 | Johnny Speeds     | L   | 0.772      | -            | -                | -                | -         |    -8.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1602 | 2024-06-02 | DMS               | W   | 0.768      | -            | -                | -                | -         |     7.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1609 | 2024-06-02 | SAW               | W   | 0.767      | -            | -                | -                | -         |    14.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1629 | 2024-06-01 | RUBY              | L   | 0.761      | -            | -                | -                | -         |   -17.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1645 | 2024-06-01 | DMS               | W   | 0.760      | -            | -                | -                | -         |     6.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1647 | 2024-06-01 | KOI               | W   | 0.760      | -            | -                | -                | -         |     9.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1654 | 2024-06-01 | FURIA             | L   | 0.759      | -            | -                | -                | -         |    -1.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1683 | 2024-05-31 | Passion UA        | W   | 0.753      | 0.435        | 0.173 (0.057)    | 1.000 (0.327)    | -         |    10.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1691 | 2024-05-30 | ThunderFlash      | W   | 0.748      | -            | -                | -                | -         |     0.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1704 | 2024-05-30 | Passion UA        | L   | 0.747      | -            | -                | -                | -         |   -13.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1720 | 2024-05-29 | JANO              | W   | 0.741      | -            | -                | -                | -         |     1.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1790 | 2024-05-26 | RUBY              | W   | 0.719      | -            | -                | -                | -         |     6.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1803 | 2024-05-25 | ex-Guild Eagles   | W   | 0.714      | -            | -                | -                | -         |     4.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1806 | 2024-05-25 | Serbia            | W   | 0.714      | -            | -                | -                | -         |     3.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1816 | 2024-05-25 | Rhyno             | W   | 0.712      | -            | -                | -                | -         |     7.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1821 | 2024-05-24 | ex-Guild Eagles   | L   | 0.708      | -            | -                | -                | -         |   -18.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1824 | 2024-05-24 | The Suspect       | W   | 0.707      | -            | -                | -                | -         |     3.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1840 | 2024-05-23 | 3DMAX             | L   | 0.700      | -            | -                | -                | -         |    -1.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1847 | 2024-05-23 | brazylijski luz   | W   | 0.698      | -            | -                | -                | -         |     3.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1880 | 2024-05-22 | Sangal            | L   | 0.694      | -            | -                | -                | -         |    -9.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1890 | 2024-05-22 | Illuminar         | W   | 0.692      | -            | -                | -                | -         |     4.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1924 | 2024-05-21 | BLEED             | W   | 0.687      | 0.500        | 0.126 (0.043)    | -                | -         |    17.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1929 | 2024-05-21 | Verdant           | W   | 0.685      | -            | -                | -                | -         |     6.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1952 | 2024-05-20 | Metizport         | W   | 0.681      | -            | -                | -                | -         |     7.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1987 | 2024-05-19 | B8                | W   | 0.673      | 0.500        | 0.170 (0.057)    | 0.912 (0.307)    | -         |    12.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     2041 | 2024-05-17 | PARIVISION        | L   | 0.661      | -            | -                | -                | -         |   -10.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2049 | 2024-05-17 | Endpoint          | W   | 0.660      | -            | -                | -                | -         |     6.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2091 | 2024-05-16 | 1WIN              | L   | 0.652      | -            | -                | -                | -         |   -12.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2098 | 2024-05-16 | kONO              | W   | 0.652      | -            | -                | -                | -         |     4.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2140 | 2024-05-15 | 3DMAX             | W   | 0.646      | 0.500        | 0.510 (0.165)    | 1.000 (0.323)    | -         |    19.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2200 | 2024-05-14 | Preasy            | W   | 0.639      | -            | -                | -                | -         |     1.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2218 | 2024-05-13 | EYEBALLERS        | W   | 0.633      | -            | -                | -                | -         |     6.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2246 | 2024-05-12 | Verdant           | W   | 0.626      | -            | -                | -                | -         |     6.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2316 | 2024-05-09 | 9 Pandas          | L   | 0.606      | -            | -                | -                | -         |   -11.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2371 | 2024-05-06 | Insilio           | W   | 0.587      | -            | -                | -                | -         |     6.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2417 | 2024-05-03 | EYEBALLERS        | L   | 0.568      | -            | -                | -                | -         |   -12.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2430 | 2024-05-03 | Metizport         | L   | 0.566      | -            | -                | -                | -         |   -11.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2458 | 2024-05-02 | HAVU              | W   | 0.559      | -            | -                | -                | -         |     2.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2480 | 2024-05-01 | KOI               | W   | 0.552      | -            | -                | -                | -         |     8.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2493 | 2024-04-30 | Sangal            | L   | 0.547      | -            | -                | -                | -         |    -6.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2505 | 2024-04-30 | B8                | W   | 0.545      | 0.435        | 0.170 (0.040)    | -                | -         |     7.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2520 | 2024-04-29 | PARIVISION        | L   | 0.539      | -            | -                | -                | -         |    -7.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2537 | 2024-04-28 | SINNERS           | W   | 0.533      | -            | -                | -                | -         |     9.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2550 | 2024-04-27 | 500               | W   | 0.528      | -            | -                | -                | -         |     2.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2570 | 2024-04-27 | SINNERS           | W   | 0.525      | -            | -                | -                | -         |     9.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2594 | 2024-04-26 | Illuminar         | W   | 0.519      | -            | -                | -                | -         |     0.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2616 | 2024-04-25 | EYEBALLERS        | L   | 0.513      | -            | -                | -                | -         |   -11.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2639 | 2024-04-24 | ex-Guild Eagles   | L   | 0.506      | -            | -                | -                | -         |   -12.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2655 | 2024-04-23 | Nemiga            | L   | 0.499      | -            | -                | -                | -         |    -5.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2665 | 2024-04-22 | Grannys Knockers  | W   | 0.494      | -            | -                | -                | -         |     2.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2671 | 2024-04-22 | Nexus             | W   | 0.493      | -            | -                | -                | -         |     3.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2715 | 2024-04-20 | RUBY              | W   | 0.480      | -            | -                | -                | -         |     5.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2745 | 2024-04-19 | PARIVISION        | W   | 0.474      | -            | -                | -                | -         |     7.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2769 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.472      | -            | -                | -                | -         |     5.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2828 | 2024-04-18 | B8                | L   | 0.465      | -            | -                | -                | -         |    -7.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2850 | 2024-04-17 | B8                | W   | 0.459      | -            | -                | -                | -         |     6.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2879 | 2024-04-16 | Sangal            | L   | 0.454      | -            | -                | -                | -         |    -5.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2901 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.447      | -            | -                | -                | -         |     5.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2951 | 2024-04-12 | JANO              | L   | 0.425      | -            | -                | -                | -         |   -12.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2978 | 2024-04-11 | Alliance          | L   | 0.420      | -            | -                | -                | -         |   -10.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3076 | 2024-04-09 | MOUZ NXT          | L   | 0.407      | -            | -                | -                | -         |    -6.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3139 | 2024-04-07 | ex-Preasy         | L   | 0.392      | -            | -                | -                | -         |   -10.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3308 | 2024-04-01 | Nemiga            | L   | 0.352      | -            | -                | -                | -         |    -4.58 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3716 | 2024-03-10 | CYBERSHOKE        | L   | 0.208      | -            | -                | -                | -         |    -6.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3728 | 2024-03-10 | ECLOT             | W   | 0.206      | -            | -                | -                | -         |     4.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3747 | 2024-03-09 | Sangal            | W   | 0.200      | -            | -                | -                | -         |     3.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3793 | 2024-03-07 | Nemiga            | L   | 0.187      | -            | -                | -                | -         |    -2.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3828 | 2024-03-06 | AURA              | W   | 0.180      | -            | -                | -                | -         |     0.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3859 | 2024-03-05 | AMKAL             | L   | 0.174      | -            | -                | -                | -         |    -2.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3918 | 2024-03-03 | Secret            | W   | 0.159      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3938 | 2024-03-02 | Secret            | W   | 0.152      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3964 | 2024-02-29 | Young Ninjas      | W   | 0.140      | -            | -                | -                | -         |     0.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4229 | 2024-02-17 | Sashi             | L   | 0.060      | -            | -                | -                | -         |    -0.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4382 | 2024-02-10 | Sampi             | L   | 0.014      | -            | -                | -                | -         |    -0.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,755.09)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.821 | $2,000.00      | $1,642.31       |
| 2024-06-02 |      0.767 | $2,000.00      | $1,533.70       |
| 2024-05-22 |      0.694 | $25,000.00     | $17,337.96      |
| 2024-05-16 |      0.652 | $5,000.00      | $3,257.87       |
| 2024-05-04 |      0.574 | $2,000.00      | $1,147.59       |
| 2024-04-24 |      0.507 | $12,500.00     | $6,335.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
