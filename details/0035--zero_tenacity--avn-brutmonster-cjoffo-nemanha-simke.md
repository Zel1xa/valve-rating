### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1150.3<br />
<br />
Final Rank Value (1150.3) = Starting Rank Value (1103.5) + Head To Head Adjustments (46.8)<br />

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
|          104 |       13 | 2024-08-05 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -22.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |       44 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      197 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      247 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.958 (0.479)    | 0 (0.000) |    17.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      435 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.539 (0.270)    | 0 (0.000) |     8.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      524 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      551 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | 0 (0.000) |    16.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      646 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.680 (0.340)    | 0 (0.000) |    27.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      762 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.598 (0.299)    | 0 (0.000) |    13.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      784 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |     6.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1031 | 2024-06-16 | FAVBET            | W   | 0.862      | -            | -                | -                | 0 (0.000) |     5.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1063 | 2024-06-15 | Nemiga            | L   | 0.855      | -            | -                | -                | -         |   -10.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1104 | 2024-06-14 | RUBY              | W   | 0.848      | -            | -                | -                | 0 (0.000) |     7.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1144 | 2024-06-13 | Monte             | L   | 0.841      | -            | -                | -                | -         |   -15.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1169 | 2024-06-12 | 9INE              | W   | 0.835      | -            | -                | -                | -         |     1.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1189 | 2024-06-11 | DMS               | W   | 0.828      | -            | -                | -                | -         |     7.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1198 | 2024-06-11 | EYEBALLERS        | W   | 0.827      | -            | -                | -                | -         |     6.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1275 | 2024-06-09 | HAVU              | W   | 0.814      | -            | -                | -                | -         |     3.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1290 | 2024-06-09 | Nemiga            | L   | 0.813      | -            | -                | -                | -         |   -11.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1309 | 2024-06-08 | Insilio           | L   | 0.809      | -            | -                | -                | -         |   -17.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1328 | 2024-06-08 | Passion UA        | W   | 0.808      | 0.500        | 0.173 (0.070)    | 1.000 (0.404)    | -         |    11.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1367 | 2024-06-07 | DMS               | W   | 0.802      | -            | -                | -                | -         |     7.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1384 | 2024-06-07 | EYEBALLERS        | L   | 0.801      | -            | -                | -                | -         |   -19.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1404 | 2024-06-07 | 5W                | L   | 0.799      | -            | -                | -                | -         |   -18.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1428 | 2024-06-06 | FAVBET            | W   | 0.795      | -            | -                | -                | -         |     3.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1454 | 2024-06-06 | Permitta          | L   | 0.794      | -            | -                | -                | -         |   -19.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1473 | 2024-06-06 | GhoulsW           | W   | 0.793      | -            | -                | -                | -         |     0.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1509 | 2024-06-05 | Aurora Young Blud | W   | 0.788      | -            | -                | -                | -         |     4.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1548 | 2024-06-04 | CYBERSHOKE        | W   | 0.782      | -            | -                | -                | -         |     4.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1558 | 2024-06-04 | Grannys Knockers  | W   | 0.781      | -            | -                | -                | -         |     3.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1588 | 2024-06-03 | Johnny Speeds     | L   | 0.773      | -            | -                | -                | -         |    -8.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1594 | 2024-06-02 | DMS               | W   | 0.769      | -            | -                | -                | -         |     7.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1601 | 2024-06-02 | SAW               | W   | 0.768      | -            | -                | -                | -         |    14.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1621 | 2024-06-01 | RUBY              | L   | 0.762      | -            | -                | -                | -         |   -17.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1637 | 2024-06-01 | DMS               | W   | 0.761      | -            | -                | -                | -         |     6.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1639 | 2024-06-01 | KOI               | W   | 0.761      | -            | -                | -                | -         |     9.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1646 | 2024-06-01 | FURIA             | L   | 0.759      | -            | -                | -                | -         |    -1.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1675 | 2024-05-31 | Passion UA        | W   | 0.754      | 0.435        | 0.173 (0.057)    | 1.000 (0.328)    | -         |    10.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1683 | 2024-05-30 | ThunderFlash      | W   | 0.749      | -            | -                | -                | -         |     0.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1696 | 2024-05-30 | Passion UA        | L   | 0.747      | -            | -                | -                | -         |   -13.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1712 | 2024-05-29 | JANO              | W   | 0.742      | -            | -                | -                | -         |     1.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1782 | 2024-05-26 | RUBY              | W   | 0.720      | -            | -                | -                | -         |     6.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1795 | 2024-05-25 | ex-Guild Eagles   | W   | 0.715      | -            | -                | -                | -         |     4.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1798 | 2024-05-25 | Serbia            | W   | 0.714      | -            | -                | -                | -         |     3.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1808 | 2024-05-25 | Rhyno             | W   | 0.713      | -            | -                | -                | -         |     7.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1813 | 2024-05-24 | ex-Guild Eagles   | L   | 0.709      | -            | -                | -                | -         |   -18.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1816 | 2024-05-24 | The Suspect       | W   | 0.708      | -            | -                | -                | -         |     3.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1832 | 2024-05-23 | 3DMAX             | L   | 0.701      | -            | -                | -                | -         |    -1.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1839 | 2024-05-23 | brazylijski luz   | W   | 0.699      | -            | -                | -                | -         |     3.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1872 | 2024-05-22 | Sangal            | L   | 0.694      | -            | -                | -                | -         |   -10.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1882 | 2024-05-22 | Illuminar         | W   | 0.693      | -            | -                | -                | -         |     4.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1916 | 2024-05-21 | BLEED             | W   | 0.688      | 0.500        | 0.126 (0.043)    | -                | -         |    17.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1921 | 2024-05-21 | Verdant           | W   | 0.686      | -            | -                | -                | -         |     6.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1944 | 2024-05-20 | Metizport         | W   | 0.682      | -            | -                | -                | -         |     7.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1979 | 2024-05-19 | B8                | W   | 0.674      | 0.500        | 0.170 (0.057)    | 0.912 (0.307)    | -         |    12.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     2033 | 2024-05-17 | PARIVISION        | L   | 0.662      | -            | -                | -                | -         |   -10.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2041 | 2024-05-17 | Endpoint          | W   | 0.661      | -            | -                | -                | -         |     6.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2083 | 2024-05-16 | 1WIN              | L   | 0.653      | -            | -                | -                | -         |   -12.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2090 | 2024-05-16 | kONO              | W   | 0.652      | -            | -                | -                | -         |     4.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2132 | 2024-05-15 | 3DMAX             | W   | 0.647      | 0.500        | 0.510 (0.165)    | 1.000 (0.323)    | -         |    19.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2192 | 2024-05-14 | Preasy            | W   | 0.640      | -            | -                | -                | -         |     1.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2210 | 2024-05-13 | EYEBALLERS        | W   | 0.634      | -            | -                | -                | -         |     6.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2238 | 2024-05-12 | Verdant           | W   | 0.627      | -            | -                | -                | -         |     6.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2308 | 2024-05-09 | 9 Pandas          | L   | 0.607      | -            | -                | -                | -         |   -11.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2363 | 2024-05-06 | Insilio           | W   | 0.588      | -            | -                | -                | -         |     6.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2409 | 2024-05-03 | EYEBALLERS        | L   | 0.569      | -            | -                | -                | -         |   -12.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2422 | 2024-05-03 | Metizport         | L   | 0.567      | -            | -                | -                | -         |   -11.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2450 | 2024-05-02 | HAVU              | W   | 0.559      | -            | -                | -                | -         |     2.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2472 | 2024-05-01 | KOI               | W   | 0.553      | -            | -                | -                | -         |     8.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2485 | 2024-04-30 | Sangal            | L   | 0.548      | -            | -                | -                | -         |    -7.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2497 | 2024-04-30 | B8                | W   | 0.546      | 0.435        | 0.170 (0.040)    | -                | -         |     7.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2512 | 2024-04-29 | PARIVISION        | L   | 0.540      | -            | -                | -                | -         |    -7.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2529 | 2024-04-28 | SINNERS           | W   | 0.534      | -            | -                | -                | -         |     9.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2542 | 2024-04-27 | 500               | W   | 0.529      | -            | -                | -                | -         |     2.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2562 | 2024-04-27 | SINNERS           | W   | 0.526      | -            | -                | -                | -         |     9.71 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2586 | 2024-04-26 | Illuminar         | W   | 0.520      | -            | -                | -                | -         |     0.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2608 | 2024-04-25 | EYEBALLERS        | L   | 0.514      | -            | -                | -                | -         |   -11.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2631 | 2024-04-24 | ex-Guild Eagles   | L   | 0.507      | -            | -                | -                | -         |   -12.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2647 | 2024-04-23 | Nemiga            | L   | 0.500      | -            | -                | -                | -         |    -5.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2657 | 2024-04-22 | Grannys Knockers  | W   | 0.495      | -            | -                | -                | -         |     2.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2663 | 2024-04-22 | Nexus             | W   | 0.494      | -            | -                | -                | -         |     3.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2707 | 2024-04-20 | RUBY              | W   | 0.481      | -            | -                | -                | -         |     5.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2737 | 2024-04-19 | PARIVISION        | W   | 0.475      | -            | -                | -                | -         |     7.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2761 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.473      | -            | -                | -                | -         |     5.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2820 | 2024-04-18 | B8                | L   | 0.466      | -            | -                | -                | -         |    -7.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2842 | 2024-04-17 | B8                | W   | 0.460      | -            | -                | -                | -         |     6.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2871 | 2024-04-16 | Sangal            | L   | 0.455      | -            | -                | -                | -         |    -5.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2893 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.448      | -            | -                | -                | -         |     5.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2943 | 2024-04-12 | JANO              | L   | 0.426      | -            | -                | -                | -         |   -12.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2970 | 2024-04-11 | Alliance          | L   | 0.420      | -            | -                | -                | -         |   -10.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3068 | 2024-04-09 | MOUZ NXT          | L   | 0.407      | -            | -                | -                | -         |    -6.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3131 | 2024-04-07 | ex-Preasy         | L   | 0.393      | -            | -                | -                | -         |   -10.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3300 | 2024-04-01 | Nemiga            | L   | 0.353      | -            | -                | -                | -         |    -4.59 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3708 | 2024-03-10 | CYBERSHOKE        | L   | 0.209      | -            | -                | -                | -         |    -6.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3720 | 2024-03-10 | ECLOT             | W   | 0.207      | -            | -                | -                | -         |     4.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3739 | 2024-03-09 | Sangal            | W   | 0.201      | -            | -                | -                | -         |     3.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3785 | 2024-03-07 | Nemiga            | L   | 0.188      | -            | -                | -                | -         |    -2.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3820 | 2024-03-06 | AURA              | W   | 0.181      | -            | -                | -                | -         |     0.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3851 | 2024-03-05 | AMKAL             | L   | 0.175      | -            | -                | -                | -         |    -2.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3910 | 2024-03-03 | Secret            | W   | 0.160      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3930 | 2024-03-02 | Secret            | W   | 0.153      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3956 | 2024-02-29 | Young Ninjas      | W   | 0.141      | -            | -                | -                | -         |     0.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4221 | 2024-02-17 | Sashi             | L   | 0.061      | -            | -                | -                | -         |    -0.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4374 | 2024-02-10 | Sampi             | L   | 0.015      | -            | -                | -                | -         |    -0.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,800.00)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.822 | $2,000.00      | $1,644.17       |
| 2024-06-02 |      0.768 | $2,000.00      | $1,535.56       |
| 2024-05-22 |      0.694 | $25,000.00     | $17,361.11      |
| 2024-05-16 |      0.652 | $5,000.00      | $3,262.50       |
| 2024-05-04 |      0.575 | $2,000.00      | $1,149.44       |
| 2024-04-24 |      0.508 | $12,500.00     | $6,347.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
