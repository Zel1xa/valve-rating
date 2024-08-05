### Roster Details<br />
Team Name: ODDIK<br />
Roster: ksloks, matios, naitte, togs, WOOD7<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [12]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1104.5<br />
<br />
Final Rank Value (1104.5) = Starting Rank Value (995.1) + Head To Head Adjustments (109.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.499[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.224[<sup>2</sup>](#table1)
- LAN Wins: 0.038[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 995.1
- 400 + ( ( 0.290 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 995.1


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
|          108 |       49 | 2024-08-03 | RED Canids        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.23 | ksloks, matios, naitte, togs, WOOD7    |
|          107 |       57 | 2024-08-03 | BESTIA            | W   | 1.000      | 0.143        | 0.096 (0.014)    | -                | 0 (0.000) |    12.08 | ksloks, matios, naitte, togs, WOOD7    |
|          106 |       63 | 2024-08-03 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -4.08 | ksloks, matios, naitte, togs, WOOD7    |
|          105 |       87 | 2024-08-02 | MIBR              | W   | 1.000      | 0.143        | 0.208 (0.030)    | -                | 0 (0.000) |    25.98 | ksloks, matios, naitte, togs, WOOD7    |
|          104 |      118 | 2024-08-01 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.30 | ksloks, matios, naitte, togs, WOOD7    |
|          103 |      128 | 2024-08-01 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.00 | ksloks, matios, naitte, togs, WOOD7    |
|          102 |      171 | 2024-07-31 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -4.11 | ksloks, matios, naitte, togs, WOOD7    |
|          101 |      178 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.47 | ksloks, matios, naitte, togs, WOOD7    |
|          100 |      184 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.76 | ksloks, matios, naitte, togs, WOOD7    |
|           99 |      218 | 2024-07-30 | inSanitY          | W   | 1.000      | 0.371        | 0.048 (0.018)    | -                | 0 (0.000) |    12.79 | ksloks, matios, naitte, togs, WOOD7    |
|           98 |      230 | 2024-07-30 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.04 | lineko, matios, naitte, togs, WOOD7    |
|           97 |      318 | 2024-07-27 | Galorys           | W   | 1.000      | 0.365        | -                | 0.543 (0.198)    | 0 (0.000) |     7.46 | ksloks, matios, naitte, togs, WOOD7    |
|           96 |      338 | 2024-07-26 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.60 | ksloks, matios, naitte, togs, WOOD7    |
|           95 |      344 | 2024-07-26 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |    22.49 | ksloks, matios, naitte, togs, WOOD7    |
|           94 |      350 | 2024-07-26 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     6.54 | ksloks, matios, naitte, togs, WOOD7    |
|           93 |      370 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.90 | ksloks, matios, naitte, togs, WOOD7    |
|           92 |      378 | 2024-07-25 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | -         |     0.89 | ksloks, matios, naitte, togs, WOOD7    |
|           91 |      413 | 2024-07-24 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -9.69 | ksloks, matios, naitte, togs, WOOD7    |
|           90 |      443 | 2024-07-23 | Sharks            | W   | 1.000      | -            | -                | -                | -         |    14.07 | ksloks, matios, naitte, togs, WOOD7    |
|           89 |      482 | 2024-07-22 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.06 | ksloks, matios, naitte, togs, WOOD7    |
|           88 |      490 | 2024-07-22 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     6.34 | ksloks, matios, naitte, togs, WOOD7    |
|           87 |      534 | 2024-07-20 | Hype              | W   | 1.000      | -            | -                | -                | -         |    10.36 | ksloks, matios, naitte, togs, WOOD7    |
|           86 |      545 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.21 | ksloks, matios, naitte, togs, WOOD7    |
|           85 |      616 | 2024-07-18 | Case              | L   | 1.000      | -            | -                | -                | -         |   -22.29 | ksloks, matios, naitte, togs, WOOD7    |
|           84 |      627 | 2024-07-18 | Imperial          | W   | 1.000      | 0.143        | 0.234 (0.033)    | -                | -         |    22.46 | ksloks, matios, naitte, togs, WOOD7    |
|           83 |      631 | 2024-07-18 | BESTIA            | W   | 1.000      | 0.143        | 0.096 (0.014)    | -                | -         |    14.29 | ksloks, matios, naitte, togs, WOOD7    |
|           82 |      675 | 2024-07-17 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -17.43 | ksloks, matios, naitte, togs, WOOD7    |
|           81 |      686 | 2024-07-17 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -19.00 | ksloks, matios, naitte, togs, WOOD7    |
|           80 |      747 | 2024-07-16 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |   -18.50 | ksloks, matios, naitte, togs, WOOD7    |
|           79 |      756 | 2024-07-16 | BESTIA            | W   | 1.000      | 0.333        | 0.096 (0.032)    | 0.792 (0.264)    | -         |    12.76 | ksloks, matios, naitte, togs, WOOD7    |
|           78 |      796 | 2024-07-15 | Case              | W   | 1.000      | 0.333        | -                | 0.795 (0.265)    | -         |    10.19 | ksloks, matios, naitte, togs, WOOD7    |
|           77 |      832 | 2024-07-14 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.635 (0.235)    | -         |    17.29 | ksloks, matios, naitte, togs, WOOD7    |
|           76 |      843 | 2024-07-13 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.13 | ksloks, matios, naitte, togs, WOOD7    |
|           75 |      844 | 2024-07-13 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |     9.40 | ksloks, matios, naitte, togs, WOOD7    |
|           74 |      864 | 2024-07-11 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.635 (0.235)    | -         |    18.32 | ksloks, matios, naitte, togs, WOOD7    |
|           73 |      883 | 2024-07-10 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.57 | ksloks, matios, naitte, togs, WOOD7    |
|           72 |      892 | 2024-07-10 | Hype              | W   | 1.000      | -            | -                | -                | -         |    12.83 | ksloks, matios, naitte, togs, WOOD7    |
|           71 |      933 | 2024-07-08 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | -         |     4.80 | ksloks, matios, naitte, togs, WOOD7    |
|           70 |      947 | 2024-07-06 | W7M               | W   | 1.000      | -            | -                | -                | -         |     8.24 | ksloks, matios, naitte, togs, WOOD7    |
|           69 |     1060 | 2024-06-15 | paiN              | L   | 0.859      | -            | -                | -                | -         |    -2.62 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           68 |     1129 | 2024-06-13 | Hype              | W   | 0.846      | -            | -                | -                | -         |    11.62 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           67 |     1199 | 2024-06-10 | W7M               | W   | 0.827      | -            | -                | -                | -         |     7.88 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           66 |     1230 | 2024-06-09 | Galorys           | W   | 0.821      | 0.450        | 0.030 (0.011)    | 0.543 (0.201)    | -         |    10.52 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           65 |     1250 | 2024-06-09 | Imperial          | L   | 0.819      | -            | -                | -                | -         |    -3.09 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           64 |     1289 | 2024-06-08 | W7M               | W   | 0.815      | -            | -                | -                | -         |     7.99 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           63 |     1356 | 2024-06-07 | BESTIA            | L   | 0.807      | -            | -                | -                | -         |    -8.88 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           62 |     1432 | 2024-06-06 | Patins da Ferrari | L   | 0.800      | -            | -                | -                | -         |   -17.66 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           61 |     1529 | 2024-06-04 | paiN              | L   | 0.788      | -            | -                | -                | -         |    -2.48 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           60 |     1899 | 2024-05-21 | Case              | L   | 0.693      | -            | -                | -                | -         |   -12.10 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           59 |     1956 | 2024-05-19 | Case              | W   | 0.681      | -            | -                | -                | -         |     9.37 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           58 |     1981 | 2024-05-18 | RED Canids        | L   | 0.674      | -            | -                | -                | -         |    -6.08 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           57 |     1987 | 2024-05-18 | Galorys           | W   | 0.673      | -            | -                | -                | -         |     8.89 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           56 |     2020 | 2024-05-17 | FURIA Academy     | W   | 0.667      | -            | -                | -                | -         |     1.84 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           55 |     2024 | 2024-05-17 | Sharks            | W   | 0.667      | -            | -                | -                | -         |    12.30 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           54 |     2050 | 2024-05-16 | 9z                | L   | 0.661      | -            | -                | -                | -         |    -0.96 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           53 |     2055 | 2024-05-16 | Solid             | L   | 0.660      | -            | -                | -                | -         |   -12.33 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           52 |     2100 | 2024-05-15 | BESTIA            | L   | 0.654      | -            | -                | -                | -         |   -10.13 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           51 |     2101 | 2024-05-15 | BESTIA            | L   | 0.654      | -            | -                | -                | -         |   -10.74 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           50 |     2147 | 2024-05-14 | Solid             | L   | 0.648      | -            | -                | -                | -         |   -13.12 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           49 |     2150 | 2024-05-14 | Solid             | W   | 0.648      | 0.450        | -                | 0.825 (0.241)    | -         |     7.35 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           48 |     2165 | 2024-05-14 | KRÜ               | W   | 0.647      | -            | -                | -                | -         |     8.31 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           47 |     2176 | 2024-05-14 | Fluxo             | L   | 0.646      | -            | -                | -                | -         |    -6.90 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           46 |     2191 | 2024-05-13 | Solid             | W   | 0.641      | -            | -                | -                | -         |     7.63 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           45 |     2215 | 2024-05-12 | Intense           | W   | 0.634      | -            | -                | -                | -         |     4.44 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           44 |     2237 | 2024-05-11 | ex-Corinthians    | W   | 0.627      | -            | -                | -                | -         |     1.73 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           43 |     2293 | 2024-05-09 | inSanitY          | L   | 0.613      | -            | -                | -                | -         |   -10.95 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           42 |     2328 | 2024-05-07 | Imperial          | L   | 0.601      | -            | -                | -                | -         |    -2.95 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           41 |     2361 | 2024-05-05 | Case              | W   | 0.588      | 0.435        | -                | 0.795 (0.203)    | -         |     7.70 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           40 |     2419 | 2024-05-02 | Case              | L   | 0.568      | -            | -                | -                | -         |   -10.71 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           39 |     2420 | 2024-05-02 | Case              | W   | 0.568      | 0.450        | -                | 0.795 (0.203)    | -         |     7.28 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           38 |     2557 | 2024-04-26 | W7M               | W   | 0.527      | -            | -                | -                | -         |     5.10 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           37 |     2558 | 2024-04-26 | W7M               | W   | 0.527      | -            | -                | -                | -         |     5.30 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           36 |     2608 | 2024-04-24 | paiN              | L   | 0.515      | -            | -                | -                | -         |    -1.37 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           35 |     2609 | 2024-04-24 | paiN              | W   | 0.514      | 0.450        | 0.325 (0.075)    | 0.856 (0.198)    | -         |    14.98 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           34 |     2816 | 2024-04-17 | Fluxo             | L   | 0.468      | -            | -                | -                | -         |    -5.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           33 |     2822 | 2024-04-17 | W7M               | W   | 0.467      | -            | -                | -                | -         |     5.05 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           32 |     2854 | 2024-04-16 | SPORT             | W   | 0.462      | -            | -                | -                | -         |     3.02 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           31 |     2907 | 2024-04-13 | paiN              | L   | 0.440      | -            | -                | -                | -         |    -0.99 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           30 |     2928 | 2024-04-12 | Solid             | W   | 0.432      | -            | -                | -                | -         |     5.71 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           29 |     2975 | 2024-04-10 | Sharks            | L   | 0.422      | -            | -                | -                | -         |    -9.76 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           28 |     2979 | 2024-04-10 | Sharks            | W   | 0.421      | -            | -                | -                | -         |     3.54 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           27 |     3033 | 2024-04-09 | Fluxo             | L   | 0.415      | -            | -                | -                | -         |    -4.57 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           26 |     3038 | 2024-04-09 | Fluxo             | L   | 0.414      | -            | -                | -                | -         |    -4.72 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           25 |     3074 | 2024-04-08 | Fluxo             | L   | 0.407      | -            | -                | -                | -         |    -4.80 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           24 |     3127 | 2024-04-06 | Sharks            | L   | 0.393      | -            | -                | -                | -         |    -9.57 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           23 |     3130 | 2024-04-06 | LA RUGONETA       | W   | 0.392      | -            | -                | -                | -         |     1.02 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           22 |     3144 | 2024-04-05 | MIBR              | L   | 0.387      | -            | -                | -                | -         |    -0.98 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           21 |     3169 | 2024-04-04 | Imperial          | L   | 0.381      | -            | -                | -                | -         |    -1.93 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           20 |     3175 | 2024-04-04 | Imperial          | L   | 0.381      | -            | -                | -                | -         |    -1.96 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           19 |     3208 | 2024-04-03 | RED Canids        | L   | 0.375      | -            | -                | -                | -         |    -4.19 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           18 |     3211 | 2024-04-03 | RED Canids        | L   | 0.374      | -            | -                | -                | -         |    -4.31 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           17 |     3387 | 2024-03-26 | MIBR              | L   | 0.322      | -            | -                | -                | -         |    -0.90 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           16 |     3389 | 2024-03-26 | MIBR              | L   | 0.321      | -            | -                | -                | -         |    -0.91 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           15 |     3496 | 2024-03-18 | RED Canids        | L   | 0.267      | -            | -                | -                | -         |    -3.17 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           14 |     3521 | 2024-03-17 | Case              | W   | 0.260      | -            | -                | -                | -         |     3.29 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           13 |     3539 | 2024-03-16 | RED Canids        | L   | 0.254      | -            | -                | -                | -         |    -3.05 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           12 |     3554 | 2024-03-15 | 2GAME             | W   | 0.248      | -            | -                | -                | -         |     1.18 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           11 |     3555 | 2024-03-15 | 2GAME             | W   | 0.248      | -            | -                | -                | -         |     1.19 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           10 |     3559 | 2024-03-15 | MIBR Academy      | W   | 0.247      | -            | -                | -                | -         |     0.50 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            9 |     3614 | 2024-03-13 | Sharks            | L   | 0.234      | -            | -                | -                | -         |    -3.91 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            8 |     3631 | 2024-03-13 | Case              | W   | 0.233      | -            | -                | -                | -         |     3.06 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            7 |     3700 | 2024-03-10 | Solid             | W   | 0.213      | -            | -                | -                | -         |     2.49 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            6 |     3706 | 2024-03-10 | LA RUGONETA       | L   | 0.212      | -            | -                | -                | -         |    -6.22 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            5 |     3752 | 2024-03-08 | Galorys           | L   | 0.199      | -            | -                | -                | -         |    -4.03 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            4 |     3863 | 2024-03-04 | paiN              | L   | 0.173      | -            | -                | -                | -         |    -0.52 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            3 |     3879 | 2024-03-03 | RED Canids        | W   | 0.167      | -            | -                | -                | 1 (0.167) |     3.20 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            2 |     3903 | 2024-03-02 | Elevate           | W   | 0.160      | -            | -                | -                | 1 (0.160) |     2.58 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            1 |     3928 | 2024-03-01 | M80               | L   | 0.154      | -            | -                | -                | -         |    -1.05 | matios, naitte, ponter, Tuurtle, WOOD7 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,834.11)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-27 |      1.000 | $9,100.00      | $9,100.00       |
| 2024-07-22 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-07-14 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.867 | $5,000.00      | $4,332.64       |
| 2024-06-10 |      0.828 | $750.00        | $620.85         |
| 2024-06-09 |      0.821 | $1,500.00      | $1,230.90       |
| 2024-05-21 |      0.693 | $1,500.00      | $1,039.79       |
| 2024-05-19 |      0.680 | $2,000.00      | $1,359.72       |
| 2024-03-18 |      0.267 | $1,500.00      | $400.21         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
