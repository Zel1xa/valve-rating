### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1148.3<br />
<br />
Final Rank Value (1148.3) = Starting Rank Value (1104.7) + Head To Head Adjustments (43.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.542[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.352[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.344<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1104.7
- 400 + ( ( 0.344 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1104.7


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
|          104 |        2 | 2024-08-05 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -22.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |       33 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      186 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      236 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.983 (0.492)    | 0 (0.000) |    17.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      424 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.553 (0.276)    | 0 (0.000) |     8.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      513 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      540 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.165 (0.082)    | 0.935 (0.468)    | 0 (0.000) |    16.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      635 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.697 (0.348)    | 0 (0.000) |    27.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      751 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.611 (0.305)    | 0 (0.000) |    13.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      773 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |     6.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1020 | 2024-06-16 | FAVBET            | W   | 0.867      | -            | -                | -                | 0 (0.000) |     5.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1052 | 2024-06-15 | Nemiga            | L   | 0.860      | -            | -                | -                | -         |   -10.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1093 | 2024-06-14 | RUBY              | W   | 0.853      | -            | -                | -                | 0 (0.000) |     7.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1133 | 2024-06-13 | Monte             | L   | 0.846      | -            | -                | -                | -         |   -15.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1158 | 2024-06-12 | 9INE              | W   | 0.840      | -            | -                | -                | -         |     1.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1178 | 2024-06-11 | DMS               | W   | 0.833      | -            | -                | -                | -         |     7.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1187 | 2024-06-11 | EYEBALLERS        | W   | 0.832      | -            | -                | -                | -         |     6.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1264 | 2024-06-09 | HAVU              | W   | 0.819      | -            | -                | -                | -         |     3.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1279 | 2024-06-09 | Nemiga            | L   | 0.818      | -            | -                | -                | -         |   -10.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1298 | 2024-06-08 | Insilio           | L   | 0.814      | -            | -                | -                | -         |   -17.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1317 | 2024-06-08 | Passion UA        | W   | 0.813      | 0.500        | 0.173 (0.070)    | 1.000 (0.406)    | -         |    11.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1356 | 2024-06-07 | DMS               | W   | 0.807      | -            | -                | -                | -         |     7.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1373 | 2024-06-07 | EYEBALLERS        | L   | 0.806      | -            | -                | -                | -         |   -19.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1393 | 2024-06-07 | 5W                | L   | 0.804      | -            | -                | -                | -         |   -18.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1417 | 2024-06-06 | FAVBET            | W   | 0.800      | -            | -                | -                | -         |     3.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1443 | 2024-06-06 | Permitta          | L   | 0.799      | -            | -                | -                | -         |   -19.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1462 | 2024-06-06 | GhoulsW           | W   | 0.798      | -            | -                | -                | -         |     0.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1498 | 2024-06-05 | Aurora Young Blud | W   | 0.793      | -            | -                | -                | -         |     4.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1537 | 2024-06-04 | CYBERSHOKE        | W   | 0.787      | -            | -                | -                | -         |     4.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1547 | 2024-06-04 | Grannys Knockers  | W   | 0.786      | -            | -                | -                | -         |     3.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1577 | 2024-06-03 | Johnny Speeds     | L   | 0.778      | -            | -                | -                | -         |    -8.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1583 | 2024-06-02 | DMS               | W   | 0.774      | -            | -                | -                | -         |     7.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1590 | 2024-06-02 | SAW               | W   | 0.773      | -            | -                | -                | -         |    15.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1610 | 2024-06-01 | RUBY              | L   | 0.767      | -            | -                | -                | -         |   -17.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1626 | 2024-06-01 | DMS               | W   | 0.766      | -            | -                | -                | -         |     6.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1628 | 2024-06-01 | KOI               | W   | 0.766      | -            | -                | -                | -         |     9.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1635 | 2024-06-01 | FURIA             | L   | 0.764      | -            | -                | -                | -         |    -1.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1664 | 2024-05-31 | Passion UA        | W   | 0.759      | 0.435        | 0.173 (0.057)    | 1.000 (0.330)    | -         |    10.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1672 | 2024-05-30 | ThunderFlash      | W   | 0.754      | -            | -                | -                | -         |     0.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1685 | 2024-05-30 | Passion UA        | L   | 0.752      | -            | -                | -                | -         |   -13.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1701 | 2024-05-29 | JANO              | W   | 0.747      | -            | -                | -                | -         |     1.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1771 | 2024-05-26 | RUBY              | W   | 0.725      | -            | -                | -                | -         |     6.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1784 | 2024-05-25 | ex-Guild Eagles   | W   | 0.720      | -            | -                | -                | -         |     4.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1787 | 2024-05-25 | Serbia            | W   | 0.719      | -            | -                | -                | -         |     3.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1797 | 2024-05-25 | Rhyno             | W   | 0.718      | -            | -                | -                | -         |     8.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1802 | 2024-05-24 | ex-Guild Eagles   | L   | 0.714      | -            | -                | -                | -         |   -18.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1805 | 2024-05-24 | The Suspect       | W   | 0.713      | -            | -                | -                | -         |     3.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1821 | 2024-05-23 | 3DMAX             | L   | 0.706      | -            | -                | -                | -         |    -1.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1828 | 2024-05-23 | brazylijski luz   | W   | 0.704      | -            | -                | -                | -         |     3.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1861 | 2024-05-22 | Sangal            | L   | 0.699      | -            | -                | -                | -         |   -10.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1871 | 2024-05-22 | Illuminar         | W   | 0.698      | -            | -                | -                | -         |     4.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1905 | 2024-05-21 | BLEED             | W   | 0.693      | 0.500        | 0.126 (0.044)    | -                | -         |    18.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1910 | 2024-05-21 | Verdant           | W   | 0.691      | -            | -                | -                | -         |     6.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1933 | 2024-05-20 | Metizport         | W   | 0.687      | -            | -                | -                | -         |     4.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1968 | 2024-05-19 | B8                | W   | 0.679      | 0.500        | 0.165 (0.056)    | 0.935 (0.317)    | -         |    12.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     2022 | 2024-05-17 | PARIVISION        | L   | 0.667      | -            | -                | -                | -         |   -10.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2030 | 2024-05-17 | Endpoint          | W   | 0.666      | -            | -                | -                | -         |     6.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2072 | 2024-05-16 | 1WIN              | L   | 0.658      | -            | -                | -                | -         |   -12.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2079 | 2024-05-16 | kONO              | W   | 0.657      | -            | -                | -                | -         |     4.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2121 | 2024-05-15 | 3DMAX             | W   | 0.652      | 0.500        | 0.508 (0.166)    | 1.000 (0.326)    | -         |    19.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2181 | 2024-05-14 | Preasy            | W   | 0.645      | -            | -                | -                | -         |     1.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2199 | 2024-05-13 | EYEBALLERS        | W   | 0.639      | -            | -                | -                | -         |     5.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2227 | 2024-05-12 | Verdant           | W   | 0.632      | -            | -                | -                | -         |     6.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2297 | 2024-05-09 | 9 Pandas          | L   | 0.612      | -            | -                | -                | -         |   -11.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2352 | 2024-05-06 | Insilio           | W   | 0.593      | -            | -                | -                | -         |     6.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2398 | 2024-05-03 | EYEBALLERS        | L   | 0.574      | -            | -                | -                | -         |   -12.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2411 | 2024-05-03 | Metizport         | L   | 0.572      | -            | -                | -                | -         |   -13.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2439 | 2024-05-02 | HAVU              | W   | 0.564      | -            | -                | -                | -         |     2.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2461 | 2024-05-01 | KOI               | W   | 0.558      | -            | -                | -                | -         |     8.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2474 | 2024-04-30 | Sangal            | L   | 0.553      | -            | -                | -                | -         |    -7.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2486 | 2024-04-30 | B8                | W   | 0.551      | 0.435        | 0.165 (0.039)    | -                | -         |     7.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2501 | 2024-04-29 | PARIVISION        | L   | 0.545      | -            | -                | -                | -         |    -8.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2518 | 2024-04-28 | SINNERS           | W   | 0.539      | -            | -                | -                | -         |     9.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2531 | 2024-04-27 | 500               | W   | 0.534      | -            | -                | -                | -         |     2.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2551 | 2024-04-27 | SINNERS           | W   | 0.531      | -            | -                | -                | -         |     9.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2575 | 2024-04-26 | Illuminar         | W   | 0.525      | -            | -                | -                | -         |     0.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2597 | 2024-04-25 | EYEBALLERS        | L   | 0.519      | -            | -                | -                | -         |   -12.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2620 | 2024-04-24 | ex-Guild Eagles   | L   | 0.512      | -            | -                | -                | -         |   -12.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2636 | 2024-04-23 | Nemiga            | L   | 0.505      | -            | -                | -                | -         |    -5.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2646 | 2024-04-22 | Grannys Knockers  | W   | 0.500      | -            | -                | -                | -         |     2.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2652 | 2024-04-22 | Nexus             | W   | 0.499      | -            | -                | -                | -         |     3.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2696 | 2024-04-20 | RUBY              | W   | 0.486      | -            | -                | -                | -         |     4.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2726 | 2024-04-19 | PARIVISION        | W   | 0.480      | -            | -                | -                | -         |     7.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2750 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.478      | -            | -                | -                | -         |     5.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2809 | 2024-04-18 | B8                | L   | 0.471      | -            | -                | -                | -         |    -8.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2831 | 2024-04-17 | B8                | W   | 0.465      | -            | -                | -                | -         |     6.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2860 | 2024-04-16 | Sangal            | L   | 0.460      | -            | -                | -                | -         |    -5.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2882 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.453      | -            | -                | -                | -         |     5.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2932 | 2024-04-12 | JANO              | L   | 0.431      | -            | -                | -                | -         |   -12.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2959 | 2024-04-11 | Alliance          | L   | 0.425      | -            | -                | -                | -         |   -10.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3057 | 2024-04-09 | MOUZ NXT          | L   | 0.412      | -            | -                | -                | -         |    -7.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3120 | 2024-04-07 | ex-Preasy         | L   | 0.398      | -            | -                | -                | -         |   -10.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3289 | 2024-04-01 | Nemiga            | L   | 0.358      | -            | -                | -                | -         |    -4.64 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3697 | 2024-03-10 | CYBERSHOKE        | L   | 0.214      | -            | -                | -                | -         |    -6.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3709 | 2024-03-10 | ECLOT             | W   | 0.212      | -            | -                | -                | -         |     4.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3728 | 2024-03-09 | Sangal            | W   | 0.206      | -            | -                | -                | -         |     3.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3774 | 2024-03-07 | Nemiga            | L   | 0.193      | -            | -                | -                | -         |    -2.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3809 | 2024-03-06 | AURA              | W   | 0.186      | -            | -                | -                | -         |     0.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3840 | 2024-03-05 | AMKAL             | L   | 0.180      | -            | -                | -                | -         |    -2.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3899 | 2024-03-03 | Secret            | W   | 0.165      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3919 | 2024-03-02 | Secret            | W   | 0.158      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3945 | 2024-02-29 | Young Ninjas      | W   | 0.146      | -            | -                | -                | -         |     0.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4210 | 2024-02-17 | Sashi             | L   | 0.066      | -            | -                | -                | -         |    -0.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4363 | 2024-02-10 | Sampi             | L   | 0.020      | -            | -                | -                | -         |    -0.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46,042.50)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.827 | $2,000.00      | $1,654.17       |
| 2024-06-02 |      0.773 | $2,000.00      | $1,545.56       |
| 2024-05-22 |      0.699 | $25,000.00     | $17,486.11      |
| 2024-05-16 |      0.657 | $5,000.00      | $3,287.50       |
| 2024-05-04 |      0.580 | $2,000.00      | $1,159.44       |
| 2024-04-24 |      0.513 | $12,500.00     | $6,409.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
