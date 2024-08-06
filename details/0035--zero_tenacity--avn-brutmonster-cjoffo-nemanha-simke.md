### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1151.1<br />
<br />
Final Rank Value (1151.1) = Starting Rank Value (1103.5) + Head To Head Adjustments (47.6)<br />

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
|          104 |       17 | 2024-08-05 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -22.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |       46 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      195 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      245 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.958 (0.479)    | 0 (0.000) |    17.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      433 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.539 (0.270)    | 0 (0.000) |     8.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      522 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      549 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | 0 (0.000) |    16.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      644 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.680 (0.340)    | 0 (0.000) |    27.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      760 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.598 (0.299)    | 0 (0.000) |    13.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      782 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |     6.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1029 | 2024-06-16 | FAVBET            | W   | 0.861      | -            | -                | -                | 0 (0.000) |     5.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1061 | 2024-06-15 | Nemiga            | L   | 0.854      | -            | -                | -                | -         |   -10.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1102 | 2024-06-14 | RUBY              | W   | 0.848      | -            | -                | -                | 0 (0.000) |     7.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1142 | 2024-06-13 | Monte             | L   | 0.840      | -            | -                | -                | -         |   -15.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1167 | 2024-06-12 | 9INE              | W   | 0.834      | -            | -                | -                | -         |     1.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1187 | 2024-06-11 | DMS               | W   | 0.828      | -            | -                | -                | -         |     7.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1196 | 2024-06-11 | EYEBALLERS        | W   | 0.826      | -            | -                | -                | -         |     6.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1273 | 2024-06-09 | HAVU              | W   | 0.813      | -            | -                | -                | -         |     2.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1288 | 2024-06-09 | Nemiga            | L   | 0.812      | -            | -                | -                | -         |   -11.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1307 | 2024-06-08 | Insilio           | L   | 0.808      | -            | -                | -                | -         |   -17.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1326 | 2024-06-08 | Passion UA        | W   | 0.807      | 0.500        | 0.173 (0.070)    | 1.000 (0.404)    | -         |    11.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1365 | 2024-06-07 | DMS               | W   | 0.801      | -            | -                | -                | -         |     7.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1382 | 2024-06-07 | EYEBALLERS        | L   | 0.800      | -            | -                | -                | -         |   -19.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1402 | 2024-06-07 | 5W                | L   | 0.799      | -            | -                | -                | -         |   -18.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1426 | 2024-06-06 | FAVBET            | W   | 0.795      | -            | -                | -                | -         |     3.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1452 | 2024-06-06 | Permitta          | L   | 0.794      | -            | -                | -                | -         |   -18.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1471 | 2024-06-06 | GhoulsW           | W   | 0.792      | -            | -                | -                | -         |     0.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1507 | 2024-06-05 | Aurora Young Blud | W   | 0.787      | -            | -                | -                | -         |     5.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1546 | 2024-06-04 | CYBERSHOKE        | W   | 0.781      | -            | -                | -                | -         |     4.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1556 | 2024-06-04 | Grannys Knockers  | W   | 0.780      | -            | -                | -                | -         |     3.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1586 | 2024-06-03 | Johnny Speeds     | L   | 0.773      | -            | -                | -                | -         |    -8.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1592 | 2024-06-02 | DMS               | W   | 0.768      | -            | -                | -                | -         |     7.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1599 | 2024-06-02 | SAW               | W   | 0.767      | -            | -                | -                | -         |    14.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1619 | 2024-06-01 | RUBY              | L   | 0.762      | -            | -                | -                | -         |   -17.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1635 | 2024-06-01 | DMS               | W   | 0.760      | -            | -                | -                | -         |     6.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1637 | 2024-06-01 | KOI               | W   | 0.760      | -            | -                | -                | -         |     9.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1644 | 2024-06-01 | FURIA             | L   | 0.759      | -            | -                | -                | -         |    -1.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1673 | 2024-05-31 | Passion UA        | W   | 0.753      | 0.435        | 0.173 (0.057)    | 1.000 (0.327)    | -         |    10.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1681 | 2024-05-30 | ThunderFlash      | W   | 0.748      | -            | -                | -                | -         |     0.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1694 | 2024-05-30 | Passion UA        | L   | 0.747      | -            | -                | -                | -         |   -13.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1710 | 2024-05-29 | JANO              | W   | 0.742      | -            | -                | -                | -         |     1.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1780 | 2024-05-26 | RUBY              | W   | 0.720      | -            | -                | -                | -         |     6.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1793 | 2024-05-25 | ex-Guild Eagles   | W   | 0.714      | -            | -                | -                | -         |     4.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1796 | 2024-05-25 | Serbia            | W   | 0.714      | -            | -                | -                | -         |     3.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1806 | 2024-05-25 | Rhyno             | W   | 0.712      | -            | -                | -                | -         |     7.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1811 | 2024-05-24 | ex-Guild Eagles   | L   | 0.708      | -            | -                | -                | -         |   -18.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1814 | 2024-05-24 | The Suspect       | W   | 0.707      | -            | -                | -                | -         |     3.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1830 | 2024-05-23 | 3DMAX             | L   | 0.700      | -            | -                | -                | -         |    -1.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1837 | 2024-05-23 | brazylijski luz   | W   | 0.699      | -            | -                | -                | -         |     3.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1870 | 2024-05-22 | Sangal            | L   | 0.694      | -            | -                | -                | -         |   -10.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1880 | 2024-05-22 | Illuminar         | W   | 0.692      | -            | -                | -                | -         |     4.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1914 | 2024-05-21 | BLEED             | W   | 0.687      | 0.500        | 0.126 (0.043)    | -                | -         |    17.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1919 | 2024-05-21 | Verdant           | W   | 0.686      | -            | -                | -                | -         |     6.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1942 | 2024-05-20 | Metizport         | W   | 0.681      | -            | -                | -                | -         |     7.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1977 | 2024-05-19 | B8                | W   | 0.673      | 0.500        | 0.170 (0.057)    | 0.912 (0.307)    | -         |    12.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     2031 | 2024-05-17 | PARIVISION        | L   | 0.661      | -            | -                | -                | -         |   -10.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2039 | 2024-05-17 | Endpoint          | W   | 0.660      | -            | -                | -                | -         |     6.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2081 | 2024-05-16 | 1WIN              | L   | 0.653      | -            | -                | -                | -         |   -12.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2088 | 2024-05-16 | kONO              | W   | 0.652      | -            | -                | -                | -         |     4.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2130 | 2024-05-15 | 3DMAX             | W   | 0.646      | 0.500        | 0.510 (0.165)    | 1.000 (0.323)    | -         |    19.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2190 | 2024-05-14 | Preasy            | W   | 0.639      | -            | -                | -                | -         |     1.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2208 | 2024-05-13 | EYEBALLERS        | W   | 0.634      | -            | -                | -                | -         |     6.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2236 | 2024-05-12 | Verdant           | W   | 0.626      | -            | -                | -                | -         |     6.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2306 | 2024-05-09 | 9 Pandas          | L   | 0.606      | -            | -                | -                | -         |   -11.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2361 | 2024-05-06 | Insilio           | W   | 0.587      | -            | -                | -                | -         |     6.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2407 | 2024-05-03 | EYEBALLERS        | L   | 0.568      | -            | -                | -                | -         |   -12.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2420 | 2024-05-03 | Metizport         | L   | 0.566      | -            | -                | -                | -         |   -11.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2448 | 2024-05-02 | HAVU              | W   | 0.559      | -            | -                | -                | -         |     2.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2470 | 2024-05-01 | KOI               | W   | 0.553      | -            | -                | -                | -         |     8.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2483 | 2024-04-30 | Sangal            | L   | 0.547      | -            | -                | -                | -         |    -6.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2495 | 2024-04-30 | B8                | W   | 0.545      | 0.435        | 0.170 (0.040)    | -                | -         |     7.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2510 | 2024-04-29 | PARIVISION        | L   | 0.540      | -            | -                | -                | -         |    -7.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2527 | 2024-04-28 | SINNERS           | W   | 0.533      | -            | -                | -                | -         |     9.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2540 | 2024-04-27 | 500               | W   | 0.528      | -            | -                | -                | -         |     2.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2560 | 2024-04-27 | SINNERS           | W   | 0.525      | -            | -                | -                | -         |     9.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2584 | 2024-04-26 | Illuminar         | W   | 0.519      | -            | -                | -                | -         |     0.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2606 | 2024-04-25 | EYEBALLERS        | L   | 0.513      | -            | -                | -                | -         |   -11.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2629 | 2024-04-24 | ex-Guild Eagles   | L   | 0.506      | -            | -                | -                | -         |   -12.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2645 | 2024-04-23 | Nemiga            | L   | 0.500      | -            | -                | -                | -         |    -5.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2655 | 2024-04-22 | Grannys Knockers  | W   | 0.494      | -            | -                | -                | -         |     2.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2661 | 2024-04-22 | Nexus             | W   | 0.493      | -            | -                | -                | -         |     3.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2705 | 2024-04-20 | RUBY              | W   | 0.480      | -            | -                | -                | -         |     5.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2735 | 2024-04-19 | PARIVISION        | W   | 0.475      | -            | -                | -                | -         |     7.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2759 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.473      | -            | -                | -                | -         |     5.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2818 | 2024-04-18 | B8                | L   | 0.465      | -            | -                | -                | -         |    -7.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2840 | 2024-04-17 | B8                | W   | 0.460      | -            | -                | -                | -         |     6.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2869 | 2024-04-16 | Sangal            | L   | 0.454      | -            | -                | -                | -         |    -5.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2891 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.448      | -            | -                | -                | -         |     5.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2941 | 2024-04-12 | JANO              | L   | 0.425      | -            | -                | -                | -         |   -12.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2968 | 2024-04-11 | Alliance          | L   | 0.420      | -            | -                | -                | -         |   -10.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3066 | 2024-04-09 | MOUZ NXT          | L   | 0.407      | -            | -                | -                | -         |    -6.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3129 | 2024-04-07 | ex-Preasy         | L   | 0.392      | -            | -                | -                | -         |   -10.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3298 | 2024-04-01 | Nemiga            | L   | 0.352      | -            | -                | -                | -         |    -4.58 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3706 | 2024-03-10 | CYBERSHOKE        | L   | 0.208      | -            | -                | -                | -         |    -6.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3718 | 2024-03-10 | ECLOT             | W   | 0.207      | -            | -                | -                | -         |     4.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3737 | 2024-03-09 | Sangal            | W   | 0.200      | -            | -                | -                | -         |     3.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3783 | 2024-03-07 | Nemiga            | L   | 0.187      | -            | -                | -                | -         |    -2.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3818 | 2024-03-06 | AURA              | W   | 0.180      | -            | -                | -                | -         |     0.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3849 | 2024-03-05 | AMKAL             | L   | 0.174      | -            | -                | -                | -         |    -2.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3908 | 2024-03-03 | Secret            | W   | 0.159      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3928 | 2024-03-02 | Secret            | W   | 0.152      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3954 | 2024-02-29 | Young Ninjas      | W   | 0.140      | -            | -                | -                | -         |     0.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4219 | 2024-02-17 | Sashi             | L   | 0.060      | -            | -                | -                | -         |    -0.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4372 | 2024-02-10 | Sampi             | L   | 0.014      | -            | -                | -                | -         |    -0.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,768.56)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.821 | $2,000.00      | $1,642.87       |
| 2024-06-02 |      0.767 | $2,000.00      | $1,534.26       |
| 2024-05-22 |      0.694 | $25,000.00     | $17,344.91      |
| 2024-05-16 |      0.652 | $5,000.00      | $3,259.26       |
| 2024-05-04 |      0.574 | $2,000.00      | $1,148.15       |
| 2024-04-24 |      0.507 | $12,500.00     | $6,339.12       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
