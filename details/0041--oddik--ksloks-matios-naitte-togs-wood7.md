### Roster Details<br />
Team Name: ODDIK<br />
Roster: ksloks, matios, naitte, togs, WOOD7<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [12]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1057.9<br />
<br />
Final Rank Value (1057.9) = Starting Rank Value (1143.5) + Head To Head Adjustments (-85.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.581[<sup>1</sup>](#table2)
- Bounty Collected: 0.394[<sup>2</sup>](#table1)
- Opponent Network: 0.250[<sup>2</sup>](#table1)
- LAN Wins: 0.312[<sup>2</sup>](#table1)

The average of these factors is 0.384<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1143.5
- 400 + ( ( 0.384 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1143.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          121 |       32 | 2024-09-06 | Imperial          | L   | 1.000      | -            | -                | -                | -         |   -10.55 | ksloks, matios, naitte, togs, WOOD7    |
|          120 |       34 | 2024-09-06 | Imperial          | L   | 1.000      | -            | -                | -                | -         |   -11.43 | ksloks, matios, naitte, togs, WOOD7    |
|          119 |      106 | 2024-09-04 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -16.58 | ksloks, matios, naitte, togs, WOOD7    |
|          118 |      109 | 2024-09-04 | Sharks            | W   | 1.000      | 0.371        | 0.056 (0.021)    | -                | 0 (0.000) |    11.43 | ksloks, matios, naitte, togs, WOOD7    |
|          117 |      141 | 2024-09-03 | Solid             | W   | 1.000      | 0.371        | -                | 0.692 (0.257)    | 0 (0.000) |     9.64 | ksloks, matios, naitte, togs, WOOD7    |
|          116 |      175 | 2024-09-02 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.28 | ksloks, matios, naitte, togs, WOOD7    |
|          115 |      316 | 2024-08-28 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |   -16.34 | ksloks, matios, naitte, togs, WOOD7    |
|          114 |      375 | 2024-08-27 | Sharks            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.54 | ksloks, matios, naitte, togs, WOOD7    |
|          113 |      426 | 2024-08-26 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.08 | ksloks, matios, naitte, togs, WOOD7    |
|          112 |      454 | 2024-08-26 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -27.14 | ksloks, matios, naitte, togs, WOOD7    |
|          111 |      680 | 2024-08-20 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -25.72 | ksloks, matios, naitte, togs, WOOD7    |
|          110 |      681 | 2024-08-20 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.629 (0.283)    | 0 (0.000) |     5.29 | ksloks, matios, naitte, togs, WOOD7    |
|          109 |      783 | 2024-08-16 | Sharks            | W   | 1.000      | 0.423        | 0.056 (0.024)    | 0.537 (0.227)    | 1 (1.000) |    11.40 | ksloks, matios, naitte, togs, WOOD7    |
|          108 |      818 | 2024-08-15 | Sharks            | W   | 1.000      | 0.423        | 0.056 (0.024)    | 0.537 (0.227)    | 1 (1.000) |    11.96 | ksloks, matios, naitte, togs, WOOD7    |
|          107 |      843 | 2024-08-14 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.73 | ksloks, matios, naitte, togs, WOOD7    |
|          106 |      860 | 2024-08-13 | Case              | W   | 1.000      | 0.450        | -                | 0.727 (0.327)    | 0 (0.000) |     7.33 | ksloks, matios, naitte, togs, WOOD7    |
|          105 |      866 | 2024-08-13 | Case              | L   | 1.000      | -            | -                | -                | -         |   -24.73 | ksloks, matios, naitte, togs, WOOD7    |
|          104 |      994 | 2024-08-09 | Hype              | W   | 1.000      | -            | -                | -                | -         |     4.43 | ksloks, matios, naitte, togs, WOOD7    |
|          103 |      997 | 2024-08-09 | Hype              | W   | 1.000      | -            | -                | -                | -         |     4.63 | ksloks, matios, naitte, togs, WOOD7    |
|          102 |     1187 | 2024-08-03 | RED Canids        | W   | 0.963      | -            | -                | -                | -         |    14.70 | ksloks, matios, naitte, togs, WOOD7    |
|          101 |     1195 | 2024-08-03 | BESTIA            | W   | 0.962      | -            | -                | -                | -         |    10.19 | ksloks, matios, naitte, togs, WOOD7    |
|          100 |     1201 | 2024-08-03 | paiN              | L   | 0.961      | -            | -                | -                | -         |    -2.15 | ksloks, matios, naitte, togs, WOOD7    |
|           99 |     1225 | 2024-08-02 | MIBR              | W   | 0.955      | 0.143        | 0.156 (0.021)    | -                | -         |    24.09 | ksloks, matios, naitte, togs, WOOD7    |
|           98 |     1256 | 2024-08-01 | Case              | W   | 0.950      | -            | -                | -                | -         |     8.24 | ksloks, matios, naitte, togs, WOOD7    |
|           97 |     1266 | 2024-08-01 | MIBR              | L   | 0.949      | -            | -                | -                | -         |    -5.50 | ksloks, matios, naitte, togs, WOOD7    |
|           96 |     1308 | 2024-07-31 | paiN              | L   | 0.943      | -            | -                | -                | -         |    -1.99 | ksloks, matios, naitte, togs, WOOD7    |
|           95 |     1319 | 2024-07-31 | MIBR              | L   | 0.941      | -            | -                | -                | -         |    -5.93 | ksloks, matios, naitte, togs, WOOD7    |
|           94 |     1324 | 2024-07-31 | MIBR              | L   | 0.941      | -            | -                | -                | -         |    -6.25 | ksloks, matios, naitte, togs, WOOD7    |
|           93 |     1355 | 2024-07-30 | inSanitY          | W   | 0.936      | -            | -                | -                | -         |     9.74 | ksloks, matios, naitte, togs, WOOD7    |
|           92 |     1368 | 2024-07-30 | Dusty Roots       | W   | 0.934      | -            | -                | -                | -         |     4.63 | lineko, matios, naitte, togs, WOOD7    |
|           91 |     1456 | 2024-07-27 | Galorys           | W   | 0.916      | -            | -                | -                | -         |     5.65 | ksloks, matios, naitte, togs, WOOD7    |
|           90 |     1476 | 2024-07-26 | Patins da Ferrari | W   | 0.909      | -            | -                | -                | -         |     4.39 | ksloks, matios, naitte, togs, WOOD7    |
|           89 |     1482 | 2024-07-26 | RED Canids        | W   | 0.908      | -            | -                | -                | -         |    17.07 | ksloks, matios, naitte, togs, WOOD7    |
|           88 |     1488 | 2024-07-26 | Patins da Ferrari | W   | 0.907      | -            | -                | -                | -         |     4.96 | ksloks, matios, naitte, togs, WOOD7    |
|           87 |     1508 | 2024-07-25 | W7M               | L   | 0.903      | -            | -                | -                | -         |   -21.98 | ksloks, matios, naitte, togs, WOOD7    |
|           86 |     1516 | 2024-07-25 | LaChampionsLiga   | W   | 0.903      | -            | -                | -                | -         |     1.46 | ksloks, matios, naitte, togs, WOOD7    |
|           85 |     1551 | 2024-07-24 | RED Canids        | L   | 0.896      | -            | -                | -                | -         |   -12.50 | ksloks, matios, naitte, togs, WOOD7    |
|           84 |     1581 | 2024-07-23 | Sharks            | W   | 0.890      | -            | -                | -                | -         |    11.57 | ksloks, matios, naitte, togs, WOOD7    |
|           83 |     1620 | 2024-07-22 | Hype              | L   | 0.881      | -            | -                | -                | -         |   -20.30 | ksloks, matios, naitte, togs, WOOD7    |
|           82 |     1628 | 2024-07-22 | Patins da Ferrari | W   | 0.881      | -            | -                | -                | -         |     3.99 | ksloks, matios, naitte, togs, WOOD7    |
|           81 |     1672 | 2024-07-20 | Hype              | W   | 0.868      | -            | -                | -                | -         |     7.25 | ksloks, matios, naitte, togs, WOOD7    |
|           80 |     1683 | 2024-07-20 | Fluxo             | L   | 0.868      | -            | -                | -                | -         |   -11.06 | ksloks, matios, naitte, togs, WOOD7    |
|           79 |     1754 | 2024-07-18 | Case              | L   | 0.856      | -            | -                | -                | -         |   -20.02 | ksloks, matios, naitte, togs, WOOD7    |
|           78 |     1765 | 2024-07-18 | Imperial          | W   | 0.855      | 0.143        | 0.150 (0.018)    | -                | -         |    14.21 | ksloks, matios, naitte, togs, WOOD7    |
|           77 |     1769 | 2024-07-18 | BESTIA            | W   | 0.854      | -            | -                | -                | -         |     9.50 | ksloks, matios, naitte, togs, WOOD7    |
|           76 |     1814 | 2024-07-17 | Sharks            | L   | 0.849      | -            | -                | -                | -         |   -16.25 | ksloks, matios, naitte, togs, WOOD7    |
|           75 |     1824 | 2024-07-17 | Sharks            | L   | 0.849      | -            | -                | -                | -         |   -17.43 | ksloks, matios, naitte, togs, WOOD7    |
|           74 |     1883 | 2024-07-16 | BESTIA            | W   | 0.843      | 0.450        | 0.107 (0.041)    | 0.807 (0.306)    | -         |     9.26 | ksloks, matios, naitte, togs, WOOD7    |
|           73 |     1887 | 2024-07-16 | BESTIA            | L   | 0.843      | -            | -                | -                | -         |   -17.71 | ksloks, matios, naitte, togs, WOOD7    |
|           72 |     1896 | 2024-07-16 | BESTIA            | W   | 0.841      | 0.333        | 0.107 (0.030)    | 0.807 (0.226)    | -         |     8.65 | ksloks, matios, naitte, togs, WOOD7    |
|           71 |     1937 | 2024-07-15 | Case              | W   | 0.835      | 0.333        | -                | 0.727 (0.202)    | -         |     7.35 | ksloks, matios, naitte, togs, WOOD7    |
|           70 |     1973 | 2024-07-14 | Legacy            | W   | 0.827      | 0.371        | 0.092 (0.028)    | 0.730 (0.224)    | -         |     9.59 | ksloks, matios, naitte, togs, WOOD7    |
|           69 |     1984 | 2024-07-13 | KRÜ               | W   | 0.821      | -            | -                | -                | -         |     6.18 | ksloks, matios, naitte, togs, WOOD7    |
|           68 |     1985 | 2024-07-13 | KRÜ               | W   | 0.821      | -            | -                | -                | -         |     5.87 | ksloks, matios, naitte, togs, WOOD7    |
|           67 |     2005 | 2024-07-11 | Legacy            | W   | 0.809      | 0.371        | 0.092 (0.028)    | 0.730 (0.219)    | -         |     9.52 | ksloks, matios, naitte, togs, WOOD7    |
|           66 |     2024 | 2024-07-10 | Patins da Ferrari | W   | 0.802      | -            | -                | -                | -         |     3.97 | ksloks, matios, naitte, togs, WOOD7    |
|           65 |     2033 | 2024-07-10 | Hype              | W   | 0.801      | -            | -                | -                | -         |     7.09 | ksloks, matios, naitte, togs, WOOD7    |
|           64 |     2074 | 2024-07-08 | Sharks Youngsters | W   | 0.787      | -            | -                | -                | -         |     2.82 | ksloks, matios, naitte, togs, WOOD7    |
|           63 |     2088 | 2024-07-06 | W7M               | W   | 0.774      | -            | -                | -                | -         |     4.24 | ksloks, matios, naitte, togs, WOOD7    |
|           62 |     2201 | 2024-06-15 | paiN              | L   | 0.634      | -            | -                | -                | -         |    -1.03 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           61 |     2270 | 2024-06-13 | Hype              | W   | 0.621      | -            | -                | -                | -         |     5.56 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           60 |     2340 | 2024-06-10 | W7M               | W   | 0.601      | -            | -                | -                | -         |     3.63 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           59 |     2371 | 2024-06-09 | Galorys           | W   | 0.596      | -            | -                | -                | -         |     4.55 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           58 |     2391 | 2024-06-09 | Imperial          | L   | 0.594      | -            | -                | -                | -         |    -6.53 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           57 |     2430 | 2024-06-08 | W7M               | W   | 0.590      | -            | -                | -                | -         |     3.46 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           56 |     2497 | 2024-06-07 | BESTIA            | L   | 0.582      | -            | -                | -                | -         |   -10.18 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           55 |     2573 | 2024-06-06 | Patins da Ferrari | L   | 0.574      | -            | -                | -                | -         |   -15.43 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           54 |     2670 | 2024-06-04 | paiN              | L   | 0.563      | -            | -                | -                | -         |    -0.88 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           53 |     3040 | 2024-05-21 | Case              | L   | 0.468      | -            | -                | -                | -         |    -9.83 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           52 |     3097 | 2024-05-19 | Case              | W   | 0.456      | -            | -                | -                | -         |     4.76 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           51 |     3122 | 2024-05-18 | RED Canids        | L   | 0.449      | -            | -                | -                | -         |    -7.89 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           50 |     3128 | 2024-05-18 | Galorys           | W   | 0.448      | -            | -                | -                | -         |     2.28 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           49 |     3161 | 2024-05-17 | FURIA Academy     | W   | 0.442      | -            | -                | -                | -         |     0.67 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           48 |     3165 | 2024-05-17 | Sharks            | W   | 0.441      | -            | -                | -                | -         |     6.94 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           47 |     3191 | 2024-05-16 | 9z                | L   | 0.436      | -            | -                | -                | -         |    -1.34 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           46 |     3196 | 2024-05-16 | Solid             | L   | 0.435      | -            | -                | -                | -         |   -10.63 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           45 |     3241 | 2024-05-15 | BESTIA            | L   | 0.429      | -            | -                | -                | -         |    -9.20 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           44 |     3242 | 2024-05-15 | BESTIA            | L   | 0.429      | -            | -                | -                | -         |    -9.50 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           43 |     3288 | 2024-05-14 | Solid             | L   | 0.423      | -            | -                | -                | -         |   -10.77 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           42 |     3291 | 2024-05-14 | Solid             | W   | 0.423      | -            | -                | -                | -         |     2.56 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           41 |     3306 | 2024-05-14 | KRÜ               | W   | 0.422      | -            | -                | -                | -         |     3.04 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           40 |     3317 | 2024-05-14 | Fluxo             | L   | 0.421      | -            | -                | -                | -         |    -7.95 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           39 |     3332 | 2024-05-13 | Solid             | W   | 0.415      | -            | -                | -                | -         |     2.50 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           38 |     3356 | 2024-05-12 | Intense           | W   | 0.408      | -            | -                | -                | -         |     1.33 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           37 |     3378 | 2024-05-11 | ex-Corinthians    | W   | 0.402      | -            | -                | -                | -         |     0.55 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           36 |     3434 | 2024-05-09 | inSanitY          | L   | 0.388      | -            | -                | -                | -         |    -9.47 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           35 |     3469 | 2024-05-07 | Imperial          | L   | 0.376      | -            | -                | -                | -         |    -6.17 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           34 |     3502 | 2024-05-05 | Case              | W   | 0.363      | -            | -                | -                | -         |     3.39 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           33 |     3560 | 2024-05-02 | Case              | L   | 0.343      | -            | -                | -                | -         |    -7.74 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           32 |     3561 | 2024-05-02 | Case              | W   | 0.343      | -            | -                | -                | -         |     3.08 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           31 |     3698 | 2024-04-26 | W7M               | W   | 0.302      | -            | -                | -                | -         |     1.33 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           30 |     3699 | 2024-04-26 | W7M               | W   | 0.302      | -            | -                | -                | -         |     1.35 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           29 |     3749 | 2024-04-24 | paiN              | L   | 0.290      | -            | -                | -                | -         |    -0.43 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           28 |     3750 | 2024-04-24 | paiN              | W   | 0.289      | 0.450        | 0.420 (0.055)    | -                | -         |     8.71 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           27 |     3957 | 2024-04-17 | Fluxo             | L   | 0.243      | -            | -                | -                | -         |    -6.65 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           26 |     3963 | 2024-04-17 | W7M               | W   | 0.242      | -            | -                | -                | -         |     1.10 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           25 |     3995 | 2024-04-16 | SPORT             | W   | 0.236      | -            | -                | -                | -         |     0.66 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           24 |     4048 | 2024-04-13 | paiN              | L   | 0.215      | -            | -                | -                | -         |    -0.27 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           23 |     4069 | 2024-04-12 | Solid             | W   | 0.207      | -            | -                | -                | -         |     1.20 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           22 |     4116 | 2024-04-10 | Sharks            | L   | 0.196      | -            | -                | -                | -         |    -5.54 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           21 |     4120 | 2024-04-10 | Sharks            | W   | 0.196      | -            | -                | -                | -         |     0.65 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           20 |     4174 | 2024-04-09 | Fluxo             | L   | 0.189      | -            | -                | -                | -         |    -5.28 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           19 |     4179 | 2024-04-09 | Fluxo             | L   | 0.189      | -            | -                | -                | -         |    -5.30 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           18 |     4215 | 2024-04-08 | Fluxo             | L   | 0.182      | -            | -                | -                | -         |    -5.13 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           17 |     4268 | 2024-04-06 | Sharks            | L   | 0.168      | -            | -                | -                | -         |    -4.82 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           16 |     4271 | 2024-04-06 | LA RUGONETA       | W   | 0.167      | -            | -                | -                | -         |     0.09 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           15 |     4285 | 2024-04-05 | MIBR              | L   | 0.162      | -            | -                | -                | -         |    -1.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           14 |     4310 | 2024-04-04 | Imperial          | L   | 0.156      | -            | -                | -                | -         |    -2.96 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           13 |     4316 | 2024-04-04 | Imperial          | L   | 0.156      | -            | -                | -                | -         |    -3.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           12 |     4349 | 2024-04-03 | RED Canids        | L   | 0.149      | -            | -                | -                | -         |    -3.36 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           11 |     4352 | 2024-04-03 | RED Canids        | L   | 0.149      | -            | -                | -                | -         |    -3.39 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           10 |     4528 | 2024-03-26 | MIBR              | L   | 0.096      | -            | -                | -                | -         |    -0.64 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            9 |     4530 | 2024-03-26 | MIBR              | L   | 0.096      | -            | -                | -                | -         |    -0.64 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            8 |     4637 | 2024-03-18 | RED Canids        | L   | 0.042      | -            | -                | -                | -         |    -0.95 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            7 |     4662 | 2024-03-17 | Case              | W   | 0.035      | -            | -                | -                | -         |     0.28 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            6 |     4680 | 2024-03-16 | RED Canids        | L   | 0.029      | -            | -                | -                | -         |    -0.66 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            5 |     4695 | 2024-03-15 | 2GAME             | W   | 0.023      | -            | -                | -                | -         |     0.04 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            4 |     4696 | 2024-03-15 | 2GAME             | W   | 0.023      | -            | -                | -                | -         |     0.04 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            3 |     4700 | 2024-03-15 | MIBR Academy      | W   | 0.021      | -            | -                | -                | -         |     0.01 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            2 |     4755 | 2024-03-13 | Sharks            | L   | 0.009      | -            | -                | -                | -         |    -0.18 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            1 |     4772 | 2024-03-13 | Case              | W   | 0.007      | -            | -                | -                | -         |     0.06 | matios, naitte, ponter, Tuurtle, WOOD7 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($57,580.62)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-04 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-08-16 |      1.000 | $27,900.00     | $27,900.00      |
| 2024-08-02 |      0.956 | $750.00        | $716.94         |
| 2024-07-27 |      0.916 | $9,100.00      | $8,334.93       |
| 2024-07-22 |      0.881 | $3,000.00      | $2,644.17       |
| 2024-07-14 |      0.827 | $10,000.00     | $8,272.92       |
| 2024-06-16 |      0.641 | $5,000.00      | $3,206.94       |
| 2024-06-09 |      0.595 | $1,500.00      | $893.19         |
| 2024-05-21 |      0.468 | $1,500.00      | $702.08         |
| 2024-05-19 |      0.455 | $2,000.00      | $909.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
