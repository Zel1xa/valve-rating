### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1152.5<br />
<br />
Final Rank Value (1152.5) = Starting Rank Value (1103.4) + Head To Head Adjustments (49.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.542[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.345[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.342<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1103.4
- 400 + ( ( 0.342 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1103.4


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
|          104 |       24 | 2024-08-05 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -22.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |       55 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      208 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      259 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.958 (0.479)    | 0 (0.000) |    16.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      446 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.539 (0.270)    | 0 (0.000) |     8.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      535 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -16.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      562 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | 0 (0.000) |    16.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      657 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.680 (0.340)    | 0 (0.000) |    27.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      773 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.598 (0.299)    | 0 (0.000) |    13.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      795 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |     6.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1042 | 2024-06-16 | FAVBET            | W   | 0.860      | -            | -                | -                | 0 (0.000) |     5.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1074 | 2024-06-15 | Nemiga            | L   | 0.854      | -            | -                | -                | -         |   -10.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1115 | 2024-06-14 | RUBY              | W   | 0.847      | -            | -                | -                | 0 (0.000) |     7.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1155 | 2024-06-13 | Monte             | L   | 0.839      | -            | -                | -                | -         |   -15.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1180 | 2024-06-12 | 9INE              | W   | 0.834      | -            | -                | -                | -         |     1.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1200 | 2024-06-11 | DMS               | W   | 0.827      | -            | -                | -                | -         |     7.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1209 | 2024-06-11 | EYEBALLERS        | W   | 0.825      | -            | -                | -                | -         |     6.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1286 | 2024-06-09 | HAVU              | W   | 0.812      | -            | -                | -                | -         |     2.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1301 | 2024-06-09 | Nemiga            | L   | 0.811      | -            | -                | -                | -         |   -11.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1320 | 2024-06-08 | Insilio           | L   | 0.807      | -            | -                | -                | -         |   -17.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1339 | 2024-06-08 | Passion UA        | W   | 0.806      | 0.500        | 0.173 (0.070)    | 1.000 (0.403)    | -         |    11.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1378 | 2024-06-07 | DMS               | W   | 0.801      | -            | -                | -                | -         |     7.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1395 | 2024-06-07 | EYEBALLERS        | L   | 0.800      | -            | -                | -                | -         |   -19.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1415 | 2024-06-07 | 5W                | L   | 0.798      | -            | -                | -                | -         |   -18.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1439 | 2024-06-06 | FAVBET            | W   | 0.794      | -            | -                | -                | -         |     3.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1465 | 2024-06-06 | Permitta          | L   | 0.793      | -            | -                | -                | -         |   -18.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1484 | 2024-06-06 | GhoulsW           | W   | 0.791      | -            | -                | -                | -         |     0.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1520 | 2024-06-05 | Aurora Young Blud | W   | 0.786      | -            | -                | -                | -         |     5.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1559 | 2024-06-04 | CYBERSHOKE        | W   | 0.780      | -            | -                | -                | -         |     4.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1569 | 2024-06-04 | Grannys Knockers  | W   | 0.779      | -            | -                | -                | -         |     3.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1599 | 2024-06-03 | Johnny Speeds     | L   | 0.772      | -            | -                | -                | -         |    -8.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1605 | 2024-06-02 | DMS               | W   | 0.767      | -            | -                | -                | -         |     7.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1612 | 2024-06-02 | SAW               | W   | 0.766      | -            | -                | -                | -         |    14.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1632 | 2024-06-01 | RUBY              | L   | 0.761      | -            | -                | -                | -         |   -17.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1648 | 2024-06-01 | DMS               | W   | 0.760      | -            | -                | -                | -         |     6.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1650 | 2024-06-01 | KOI               | W   | 0.759      | -            | -                | -                | -         |     9.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1657 | 2024-06-01 | FURIA             | L   | 0.758      | -            | -                | -                | -         |    -1.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1686 | 2024-05-31 | Passion UA        | W   | 0.752      | 0.435        | 0.173 (0.057)    | 1.000 (0.327)    | -         |    10.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1694 | 2024-05-30 | ThunderFlash      | W   | 0.747      | -            | -                | -                | -         |     0.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1707 | 2024-05-30 | Passion UA        | L   | 0.746      | -            | -                | -                | -         |   -13.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1723 | 2024-05-29 | JANO              | W   | 0.741      | -            | -                | -                | -         |     1.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1793 | 2024-05-26 | RUBY              | W   | 0.719      | -            | -                | -                | -         |     6.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1806 | 2024-05-25 | ex-Guild Eagles   | W   | 0.714      | -            | -                | -                | -         |     4.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1809 | 2024-05-25 | Serbia            | W   | 0.713      | -            | -                | -                | -         |     3.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1819 | 2024-05-25 | Rhyno             | W   | 0.711      | -            | -                | -                | -         |     7.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1824 | 2024-05-24 | ex-Guild Eagles   | L   | 0.707      | -            | -                | -                | -         |   -18.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1827 | 2024-05-24 | The Suspect       | W   | 0.706      | -            | -                | -                | -         |     3.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1843 | 2024-05-23 | 3DMAX             | L   | 0.699      | -            | -                | -                | -         |    -1.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1850 | 2024-05-23 | brazylijski luz   | W   | 0.698      | -            | -                | -                | -         |     3.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1883 | 2024-05-22 | Sangal            | L   | 0.693      | -            | -                | -                | -         |    -9.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1893 | 2024-05-22 | Illuminar         | W   | 0.691      | -            | -                | -                | -         |     4.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1927 | 2024-05-21 | BLEED             | W   | 0.686      | 0.500        | 0.126 (0.043)    | -                | -         |    17.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1932 | 2024-05-21 | Verdant           | W   | 0.685      | -            | -                | -                | -         |     5.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1955 | 2024-05-20 | Metizport         | W   | 0.681      | -            | -                | -                | -         |     7.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1990 | 2024-05-19 | B8                | W   | 0.672      | 0.500        | 0.170 (0.057)    | 0.912 (0.307)    | -         |    12.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     2044 | 2024-05-17 | PARIVISION        | L   | 0.661      | -            | -                | -                | -         |   -10.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2052 | 2024-05-17 | Endpoint          | W   | 0.659      | -            | -                | -                | -         |     6.71 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2094 | 2024-05-16 | 1WIN              | L   | 0.652      | -            | -                | -                | -         |   -12.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2101 | 2024-05-16 | kONO              | W   | 0.651      | -            | -                | -                | -         |     4.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2143 | 2024-05-15 | 3DMAX             | W   | 0.646      | 0.500        | 0.510 (0.165)    | 1.000 (0.323)    | -         |    19.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2203 | 2024-05-14 | Preasy            | W   | 0.639      | -            | -                | -                | -         |     1.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2221 | 2024-05-13 | EYEBALLERS        | W   | 0.633      | -            | -                | -                | -         |     6.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2249 | 2024-05-12 | Verdant           | W   | 0.625      | -            | -                | -                | -         |     6.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2319 | 2024-05-09 | 9 Pandas          | L   | 0.606      | -            | -                | -                | -         |   -10.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2374 | 2024-05-06 | Insilio           | W   | 0.587      | -            | -                | -                | -         |     6.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2420 | 2024-05-03 | EYEBALLERS        | L   | 0.567      | -            | -                | -                | -         |   -12.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2433 | 2024-05-03 | Metizport         | L   | 0.565      | -            | -                | -                | -         |   -11.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2461 | 2024-05-02 | HAVU              | W   | 0.558      | -            | -                | -                | -         |     2.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2483 | 2024-05-01 | KOI               | W   | 0.552      | -            | -                | -                | -         |     8.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2496 | 2024-04-30 | Sangal            | L   | 0.546      | -            | -                | -                | -         |    -6.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2508 | 2024-04-30 | B8                | W   | 0.545      | 0.435        | 0.170 (0.040)    | -                | -         |     7.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2523 | 2024-04-29 | PARIVISION        | L   | 0.539      | -            | -                | -                | -         |    -7.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2540 | 2024-04-28 | SINNERS           | W   | 0.532      | -            | -                | -                | -         |     9.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2553 | 2024-04-27 | 500               | W   | 0.527      | -            | -                | -                | -         |     2.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2573 | 2024-04-27 | SINNERS           | W   | 0.525      | -            | -                | -                | -         |     9.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2597 | 2024-04-26 | Illuminar         | W   | 0.518      | -            | -                | -                | -         |     0.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2619 | 2024-04-25 | EYEBALLERS        | L   | 0.512      | -            | -                | -                | -         |   -11.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2642 | 2024-04-24 | ex-Guild Eagles   | L   | 0.505      | -            | -                | -                | -         |   -12.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2658 | 2024-04-23 | Nemiga            | L   | 0.499      | -            | -                | -                | -         |    -5.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2668 | 2024-04-22 | Grannys Knockers  | W   | 0.494      | -            | -                | -                | -         |     2.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2674 | 2024-04-22 | Nexus             | W   | 0.492      | -            | -                | -                | -         |     3.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2718 | 2024-04-20 | RUBY              | W   | 0.479      | -            | -                | -                | -         |     5.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2748 | 2024-04-19 | PARIVISION        | W   | 0.474      | -            | -                | -                | -         |     7.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2772 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.472      | -            | -                | -                | -         |     5.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2831 | 2024-04-18 | B8                | L   | 0.465      | -            | -                | -                | -         |    -7.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2853 | 2024-04-17 | B8                | W   | 0.459      | -            | -                | -                | -         |     6.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2882 | 2024-04-16 | Sangal            | L   | 0.454      | -            | -                | -                | -         |    -5.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2904 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.447      | -            | -                | -                | -         |     5.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2954 | 2024-04-12 | JANO              | L   | 0.424      | -            | -                | -                | -         |   -12.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2981 | 2024-04-11 | Alliance          | L   | 0.419      | -            | -                | -                | -         |   -10.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3079 | 2024-04-09 | MOUZ NXT          | L   | 0.406      | -            | -                | -                | -         |    -6.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3142 | 2024-04-07 | ex-Preasy         | L   | 0.392      | -            | -                | -                | -         |   -10.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3311 | 2024-04-01 | Nemiga            | L   | 0.352      | -            | -                | -                | -         |    -4.58 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3719 | 2024-03-10 | CYBERSHOKE        | L   | 0.207      | -            | -                | -                | -         |    -6.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3731 | 2024-03-10 | ECLOT             | W   | 0.206      | -            | -                | -                | -         |     4.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3750 | 2024-03-09 | Sangal            | W   | 0.199      | -            | -                | -                | -         |     3.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3796 | 2024-03-07 | Nemiga            | L   | 0.187      | -            | -                | -                | -         |    -2.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3831 | 2024-03-06 | AURA              | W   | 0.179      | -            | -                | -                | -         |     0.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3862 | 2024-03-05 | AMKAL             | L   | 0.174      | -            | -                | -                | -         |    -2.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3921 | 2024-03-03 | Secret            | W   | 0.158      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3941 | 2024-03-02 | Secret            | W   | 0.152      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3967 | 2024-02-29 | Young Ninjas      | W   | 0.139      | -            | -                | -                | -         |     0.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4232 | 2024-02-17 | Sashi             | L   | 0.060      | -            | -                | -                | -         |    -0.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4385 | 2024-02-10 | Sampi             | L   | 0.014      | -            | -                | -                | -         |    -0.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,732.64)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.821 | $2,000.00      | $1,641.39       |
| 2024-06-02 |      0.766 | $2,000.00      | $1,532.78       |
| 2024-05-22 |      0.693 | $25,000.00     | $17,326.39      |
| 2024-05-16 |      0.651 | $5,000.00      | $3,255.56       |
| 2024-05-04 |      0.573 | $2,000.00      | $1,146.67       |
| 2024-04-24 |      0.506 | $12,500.00     | $6,329.86       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
