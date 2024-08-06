### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1151.6<br />
<br />
Final Rank Value (1151.6) = Starting Rank Value (1103.5) + Head To Head Adjustments (48.1)<br />

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
|          104 |       16 | 2024-08-05 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -22.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |       47 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      200 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      250 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.958 (0.479)    | 0 (0.000) |    16.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      438 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.539 (0.270)    | 0 (0.000) |     8.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      527 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      554 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | 0 (0.000) |    16.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      649 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.680 (0.340)    | 0 (0.000) |    27.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      765 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.598 (0.299)    | 0 (0.000) |    13.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      787 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |     6.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1034 | 2024-06-16 | FAVBET            | W   | 0.861      | -            | -                | -                | 0 (0.000) |     5.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1066 | 2024-06-15 | Nemiga            | L   | 0.855      | -            | -                | -                | -         |   -10.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1107 | 2024-06-14 | RUBY              | W   | 0.848      | -            | -                | -                | 0 (0.000) |     7.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1147 | 2024-06-13 | Monte             | L   | 0.840      | -            | -                | -                | -         |   -15.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1172 | 2024-06-12 | 9INE              | W   | 0.835      | -            | -                | -                | -         |     1.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1192 | 2024-06-11 | DMS               | W   | 0.828      | -            | -                | -                | -         |     7.71 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1201 | 2024-06-11 | EYEBALLERS        | W   | 0.826      | -            | -                | -                | -         |     6.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1278 | 2024-06-09 | HAVU              | W   | 0.813      | -            | -                | -                | -         |     2.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1293 | 2024-06-09 | Nemiga            | L   | 0.812      | -            | -                | -                | -         |   -11.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1312 | 2024-06-08 | Insilio           | L   | 0.808      | -            | -                | -                | -         |   -17.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1331 | 2024-06-08 | Passion UA        | W   | 0.807      | 0.500        | 0.173 (0.070)    | 1.000 (0.404)    | -         |    11.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1370 | 2024-06-07 | DMS               | W   | 0.802      | -            | -                | -                | -         |     7.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1387 | 2024-06-07 | EYEBALLERS        | L   | 0.801      | -            | -                | -                | -         |   -19.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1407 | 2024-06-07 | 5W                | L   | 0.799      | -            | -                | -                | -         |   -18.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1431 | 2024-06-06 | FAVBET            | W   | 0.795      | -            | -                | -                | -         |     3.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1457 | 2024-06-06 | Permitta          | L   | 0.794      | -            | -                | -                | -         |   -18.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1476 | 2024-06-06 | GhoulsW           | W   | 0.792      | -            | -                | -                | -         |     0.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1512 | 2024-06-05 | Aurora Young Blud | W   | 0.787      | -            | -                | -                | -         |     5.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1551 | 2024-06-04 | CYBERSHOKE        | W   | 0.781      | -            | -                | -                | -         |     4.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1561 | 2024-06-04 | Grannys Knockers  | W   | 0.780      | -            | -                | -                | -         |     3.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1591 | 2024-06-03 | Johnny Speeds     | L   | 0.773      | -            | -                | -                | -         |    -8.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1597 | 2024-06-02 | DMS               | W   | 0.768      | -            | -                | -                | -         |     7.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1604 | 2024-06-02 | SAW               | W   | 0.767      | -            | -                | -                | -         |    14.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1624 | 2024-06-01 | RUBY              | L   | 0.762      | -            | -                | -                | -         |   -17.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1640 | 2024-06-01 | DMS               | W   | 0.761      | -            | -                | -                | -         |     6.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1642 | 2024-06-01 | KOI               | W   | 0.760      | -            | -                | -                | -         |     9.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1649 | 2024-06-01 | FURIA             | L   | 0.759      | -            | -                | -                | -         |    -1.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1678 | 2024-05-31 | Passion UA        | W   | 0.753      | 0.435        | 0.173 (0.057)    | 1.000 (0.327)    | -         |    10.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1686 | 2024-05-30 | ThunderFlash      | W   | 0.748      | -            | -                | -                | -         |     0.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1699 | 2024-05-30 | Passion UA        | L   | 0.747      | -            | -                | -                | -         |   -13.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1715 | 2024-05-29 | JANO              | W   | 0.742      | -            | -                | -                | -         |     1.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1785 | 2024-05-26 | RUBY              | W   | 0.720      | -            | -                | -                | -         |     6.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1798 | 2024-05-25 | ex-Guild Eagles   | W   | 0.715      | -            | -                | -                | -         |     4.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1801 | 2024-05-25 | Serbia            | W   | 0.714      | -            | -                | -                | -         |     3.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1811 | 2024-05-25 | Rhyno             | W   | 0.712      | -            | -                | -                | -         |     7.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1816 | 2024-05-24 | ex-Guild Eagles   | L   | 0.708      | -            | -                | -                | -         |   -18.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1819 | 2024-05-24 | The Suspect       | W   | 0.707      | -            | -                | -                | -         |     3.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1835 | 2024-05-23 | 3DMAX             | L   | 0.700      | -            | -                | -                | -         |    -1.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1842 | 2024-05-23 | brazylijski luz   | W   | 0.699      | -            | -                | -                | -         |     3.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1875 | 2024-05-22 | Sangal            | L   | 0.694      | -            | -                | -                | -         |   -10.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1885 | 2024-05-22 | Illuminar         | W   | 0.692      | -            | -                | -                | -         |     4.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1919 | 2024-05-21 | BLEED             | W   | 0.687      | 0.500        | 0.126 (0.043)    | -                | -         |    17.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1924 | 2024-05-21 | Verdant           | W   | 0.686      | -            | -                | -                | -         |     6.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1947 | 2024-05-20 | Metizport         | W   | 0.682      | -            | -                | -                | -         |     7.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1982 | 2024-05-19 | B8                | W   | 0.673      | 0.500        | 0.170 (0.057)    | 0.912 (0.307)    | -         |    12.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     2036 | 2024-05-17 | PARIVISION        | L   | 0.662      | -            | -                | -                | -         |   -10.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2044 | 2024-05-17 | Endpoint          | W   | 0.660      | -            | -                | -                | -         |     6.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2086 | 2024-05-16 | 1WIN              | L   | 0.653      | -            | -                | -                | -         |   -12.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2093 | 2024-05-16 | kONO              | W   | 0.652      | -            | -                | -                | -         |     4.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2135 | 2024-05-15 | 3DMAX             | W   | 0.647      | 0.500        | 0.510 (0.165)    | 1.000 (0.323)    | -         |    19.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2195 | 2024-05-14 | Preasy            | W   | 0.640      | -            | -                | -                | -         |     1.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2213 | 2024-05-13 | EYEBALLERS        | W   | 0.634      | -            | -                | -                | -         |     6.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2241 | 2024-05-12 | Verdant           | W   | 0.626      | -            | -                | -                | -         |     6.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2311 | 2024-05-09 | 9 Pandas          | L   | 0.607      | -            | -                | -                | -         |   -11.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2366 | 2024-05-06 | Insilio           | W   | 0.588      | -            | -                | -                | -         |     6.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2412 | 2024-05-03 | EYEBALLERS        | L   | 0.568      | -            | -                | -                | -         |   -12.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2425 | 2024-05-03 | Metizport         | L   | 0.566      | -            | -                | -                | -         |   -11.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2453 | 2024-05-02 | HAVU              | W   | 0.559      | -            | -                | -                | -         |     2.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2475 | 2024-05-01 | KOI               | W   | 0.553      | -            | -                | -                | -         |     8.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2488 | 2024-04-30 | Sangal            | L   | 0.547      | -            | -                | -                | -         |    -6.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2500 | 2024-04-30 | B8                | W   | 0.546      | 0.435        | 0.170 (0.040)    | -                | -         |     7.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2515 | 2024-04-29 | PARIVISION        | L   | 0.540      | -            | -                | -                | -         |    -7.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2532 | 2024-04-28 | SINNERS           | W   | 0.534      | -            | -                | -                | -         |     9.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2545 | 2024-04-27 | 500               | W   | 0.528      | -            | -                | -                | -         |     2.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2565 | 2024-04-27 | SINNERS           | W   | 0.526      | -            | -                | -                | -         |     9.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2589 | 2024-04-26 | Illuminar         | W   | 0.519      | -            | -                | -                | -         |     0.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2611 | 2024-04-25 | EYEBALLERS        | L   | 0.513      | -            | -                | -                | -         |   -11.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2634 | 2024-04-24 | ex-Guild Eagles   | L   | 0.506      | -            | -                | -                | -         |   -12.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2650 | 2024-04-23 | Nemiga            | L   | 0.500      | -            | -                | -                | -         |    -5.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2660 | 2024-04-22 | Grannys Knockers  | W   | 0.495      | -            | -                | -                | -         |     2.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2666 | 2024-04-22 | Nexus             | W   | 0.493      | -            | -                | -                | -         |     3.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2710 | 2024-04-20 | RUBY              | W   | 0.480      | -            | -                | -                | -         |     5.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2740 | 2024-04-19 | PARIVISION        | W   | 0.475      | -            | -                | -                | -         |     7.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2764 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.473      | -            | -                | -                | -         |     5.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2823 | 2024-04-18 | B8                | L   | 0.466      | -            | -                | -                | -         |    -7.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2845 | 2024-04-17 | B8                | W   | 0.460      | -            | -                | -                | -         |     6.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2874 | 2024-04-16 | Sangal            | L   | 0.455      | -            | -                | -                | -         |    -5.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2896 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.448      | -            | -                | -                | -         |     5.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2946 | 2024-04-12 | JANO              | L   | 0.425      | -            | -                | -                | -         |   -12.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2973 | 2024-04-11 | Alliance          | L   | 0.420      | -            | -                | -                | -         |   -10.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3071 | 2024-04-09 | MOUZ NXT          | L   | 0.407      | -            | -                | -                | -         |    -6.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3134 | 2024-04-07 | ex-Preasy         | L   | 0.393      | -            | -                | -                | -         |   -10.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3303 | 2024-04-01 | Nemiga            | L   | 0.353      | -            | -                | -                | -         |    -4.58 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3711 | 2024-03-10 | CYBERSHOKE        | L   | 0.208      | -            | -                | -                | -         |    -6.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3723 | 2024-03-10 | ECLOT             | W   | 0.207      | -            | -                | -                | -         |     4.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3742 | 2024-03-09 | Sangal            | W   | 0.200      | -            | -                | -                | -         |     3.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3788 | 2024-03-07 | Nemiga            | L   | 0.188      | -            | -                | -                | -         |    -2.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3823 | 2024-03-06 | AURA              | W   | 0.180      | -            | -                | -                | -         |     0.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3854 | 2024-03-05 | AMKAL             | L   | 0.175      | -            | -                | -                | -         |    -2.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3913 | 2024-03-03 | Secret            | W   | 0.159      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3933 | 2024-03-02 | Secret            | W   | 0.153      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3959 | 2024-02-29 | Young Ninjas      | W   | 0.140      | -            | -                | -                | -         |     0.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4224 | 2024-02-17 | Sashi             | L   | 0.061      | -            | -                | -                | -         |    -0.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4377 | 2024-02-10 | Sampi             | L   | 0.015      | -            | -                | -                | -         |    -0.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,782.04)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.822 | $2,000.00      | $1,643.43       |
| 2024-06-02 |      0.767 | $2,000.00      | $1,534.81       |
| 2024-05-22 |      0.694 | $25,000.00     | $17,351.85      |
| 2024-05-16 |      0.652 | $5,000.00      | $3,260.65       |
| 2024-05-04 |      0.574 | $2,000.00      | $1,148.70       |
| 2024-04-24 |      0.507 | $12,500.00     | $6,342.59       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
