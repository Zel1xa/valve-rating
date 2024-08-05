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
Final Rank Value (1104.5) = Starting Rank Value (995.2) + Head To Head Adjustments (109.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.499[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.224[<sup>2</sup>](#table1)
- LAN Wins: 0.038[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 995.2
- 400 + ( ( 0.290 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 995.2


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
|          108 |       48 | 2024-08-03 | RED Canids        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.23 | ksloks, matios, naitte, togs, WOOD7    |
|          107 |       56 | 2024-08-03 | BESTIA            | W   | 1.000      | 0.143        | 0.096 (0.014)    | -                | 0 (0.000) |    12.08 | ksloks, matios, naitte, togs, WOOD7    |
|          106 |       62 | 2024-08-03 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -4.08 | ksloks, matios, naitte, togs, WOOD7    |
|          105 |       86 | 2024-08-02 | MIBR              | W   | 1.000      | 0.143        | 0.208 (0.030)    | -                | 0 (0.000) |    25.98 | ksloks, matios, naitte, togs, WOOD7    |
|          104 |      117 | 2024-08-01 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.30 | ksloks, matios, naitte, togs, WOOD7    |
|          103 |      127 | 2024-08-01 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.00 | ksloks, matios, naitte, togs, WOOD7    |
|          102 |      170 | 2024-07-31 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -4.11 | ksloks, matios, naitte, togs, WOOD7    |
|          101 |      177 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.47 | ksloks, matios, naitte, togs, WOOD7    |
|          100 |      183 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.76 | ksloks, matios, naitte, togs, WOOD7    |
|           99 |      217 | 2024-07-30 | inSanitY          | W   | 1.000      | 0.371        | 0.048 (0.018)    | -                | 0 (0.000) |    12.79 | ksloks, matios, naitte, togs, WOOD7    |
|           98 |      229 | 2024-07-30 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.04 | lineko, matios, naitte, togs, WOOD7    |
|           97 |      317 | 2024-07-27 | Galorys           | W   | 1.000      | 0.365        | -                | 0.543 (0.198)    | 0 (0.000) |     7.46 | ksloks, matios, naitte, togs, WOOD7    |
|           96 |      337 | 2024-07-26 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.59 | ksloks, matios, naitte, togs, WOOD7    |
|           95 |      343 | 2024-07-26 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |    22.50 | ksloks, matios, naitte, togs, WOOD7    |
|           94 |      349 | 2024-07-26 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     6.54 | ksloks, matios, naitte, togs, WOOD7    |
|           93 |      369 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.91 | ksloks, matios, naitte, togs, WOOD7    |
|           92 |      377 | 2024-07-25 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | -         |     0.89 | ksloks, matios, naitte, togs, WOOD7    |
|           91 |      412 | 2024-07-24 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -9.69 | ksloks, matios, naitte, togs, WOOD7    |
|           90 |      442 | 2024-07-23 | Sharks            | W   | 1.000      | -            | -                | -                | -         |    14.07 | ksloks, matios, naitte, togs, WOOD7    |
|           89 |      481 | 2024-07-22 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.06 | ksloks, matios, naitte, togs, WOOD7    |
|           88 |      489 | 2024-07-22 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     6.34 | ksloks, matios, naitte, togs, WOOD7    |
|           87 |      533 | 2024-07-20 | Hype              | W   | 1.000      | -            | -                | -                | -         |    10.36 | ksloks, matios, naitte, togs, WOOD7    |
|           86 |      544 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.21 | ksloks, matios, naitte, togs, WOOD7    |
|           85 |      615 | 2024-07-18 | Case              | L   | 1.000      | -            | -                | -                | -         |   -22.29 | ksloks, matios, naitte, togs, WOOD7    |
|           84 |      626 | 2024-07-18 | Imperial          | W   | 1.000      | 0.143        | 0.235 (0.034)    | -                | -         |    22.47 | ksloks, matios, naitte, togs, WOOD7    |
|           83 |      630 | 2024-07-18 | BESTIA            | W   | 1.000      | 0.143        | 0.096 (0.014)    | -                | -         |    14.29 | ksloks, matios, naitte, togs, WOOD7    |
|           82 |      674 | 2024-07-17 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -17.43 | ksloks, matios, naitte, togs, WOOD7    |
|           81 |      685 | 2024-07-17 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -19.00 | ksloks, matios, naitte, togs, WOOD7    |
|           80 |      746 | 2024-07-16 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |   -18.50 | ksloks, matios, naitte, togs, WOOD7    |
|           79 |      755 | 2024-07-16 | BESTIA            | W   | 1.000      | 0.333        | 0.096 (0.032)    | 0.792 (0.264)    | -         |    12.76 | ksloks, matios, naitte, togs, WOOD7    |
|           78 |      795 | 2024-07-15 | Case              | W   | 1.000      | 0.333        | -                | 0.795 (0.265)    | -         |    10.19 | ksloks, matios, naitte, togs, WOOD7    |
|           77 |      831 | 2024-07-14 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.635 (0.235)    | -         |    17.30 | ksloks, matios, naitte, togs, WOOD7    |
|           76 |      842 | 2024-07-13 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.13 | ksloks, matios, naitte, togs, WOOD7    |
|           75 |      843 | 2024-07-13 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |     9.40 | ksloks, matios, naitte, togs, WOOD7    |
|           74 |      863 | 2024-07-11 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.635 (0.235)    | -         |    18.32 | ksloks, matios, naitte, togs, WOOD7    |
|           73 |      882 | 2024-07-10 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.57 | ksloks, matios, naitte, togs, WOOD7    |
|           72 |      891 | 2024-07-10 | Hype              | W   | 1.000      | -            | -                | -                | -         |    12.83 | ksloks, matios, naitte, togs, WOOD7    |
|           71 |      932 | 2024-07-08 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | -         |     4.80 | ksloks, matios, naitte, togs, WOOD7    |
|           70 |      946 | 2024-07-06 | W7M               | W   | 1.000      | -            | -                | -                | -         |     8.24 | ksloks, matios, naitte, togs, WOOD7    |
|           69 |     1059 | 2024-06-15 | paiN              | L   | 0.859      | -            | -                | -                | -         |    -2.62 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           68 |     1128 | 2024-06-13 | Hype              | W   | 0.847      | -            | -                | -                | -         |    11.62 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           67 |     1198 | 2024-06-10 | W7M               | W   | 0.827      | -            | -                | -                | -         |     7.88 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           66 |     1229 | 2024-06-09 | Galorys           | W   | 0.821      | 0.450        | 0.030 (0.011)    | 0.543 (0.201)    | -         |    10.53 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           65 |     1249 | 2024-06-09 | Imperial          | L   | 0.819      | -            | -                | -                | -         |    -3.09 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           64 |     1288 | 2024-06-08 | W7M               | W   | 0.815      | -            | -                | -                | -         |     8.00 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           63 |     1355 | 2024-06-07 | BESTIA            | L   | 0.807      | -            | -                | -                | -         |    -8.89 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           62 |     1431 | 2024-06-06 | Patins da Ferrari | L   | 0.800      | -            | -                | -                | -         |   -17.67 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           61 |     1528 | 2024-06-04 | paiN              | L   | 0.788      | -            | -                | -                | -         |    -2.48 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           60 |     1898 | 2024-05-21 | Case              | L   | 0.694      | -            | -                | -                | -         |   -12.11 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           59 |     1955 | 2024-05-19 | Case              | W   | 0.681      | -            | -                | -                | -         |     9.38 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           58 |     1980 | 2024-05-18 | RED Canids        | L   | 0.674      | -            | -                | -                | -         |    -6.08 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           57 |     1986 | 2024-05-18 | Galorys           | W   | 0.674      | -            | -                | -                | -         |     8.89 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           56 |     2019 | 2024-05-17 | FURIA Academy     | W   | 0.668      | -            | -                | -                | -         |     1.84 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           55 |     2023 | 2024-05-17 | Sharks            | W   | 0.667      | -            | -                | -                | -         |    12.31 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           54 |     2049 | 2024-05-16 | 9z                | L   | 0.661      | -            | -                | -                | -         |    -0.96 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           53 |     2054 | 2024-05-16 | Solid             | L   | 0.660      | -            | -                | -                | -         |   -12.34 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           52 |     2099 | 2024-05-15 | BESTIA            | L   | 0.655      | -            | -                | -                | -         |   -10.14 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           51 |     2100 | 2024-05-15 | BESTIA            | L   | 0.654      | -            | -                | -                | -         |   -10.74 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           50 |     2146 | 2024-05-14 | Solid             | L   | 0.649      | -            | -                | -                | -         |   -13.12 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           49 |     2149 | 2024-05-14 | Solid             | W   | 0.649      | 0.450        | -                | 0.825 (0.241)    | -         |     7.35 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           48 |     2164 | 2024-05-14 | KRÜ               | W   | 0.647      | -            | -                | -                | -         |     8.31 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           47 |     2175 | 2024-05-14 | Fluxo             | L   | 0.646      | -            | -                | -                | -         |    -6.91 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           46 |     2190 | 2024-05-13 | Solid             | W   | 0.641      | -            | -                | -                | -         |     7.64 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           45 |     2214 | 2024-05-12 | Intense           | W   | 0.634      | -            | -                | -                | -         |     4.44 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           44 |     2236 | 2024-05-11 | ex-Corinthians    | W   | 0.628      | -            | -                | -                | -         |     1.73 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           43 |     2292 | 2024-05-09 | inSanitY          | L   | 0.613      | -            | -                | -                | -         |   -10.96 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           42 |     2327 | 2024-05-07 | Imperial          | L   | 0.602      | -            | -                | -                | -         |    -2.95 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           41 |     2360 | 2024-05-05 | Case              | W   | 0.588      | 0.435        | -                | 0.795 (0.203)    | -         |     7.70 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           40 |     2418 | 2024-05-02 | Case              | L   | 0.568      | -            | -                | -                | -         |   -10.72 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           39 |     2419 | 2024-05-02 | Case              | W   | 0.568      | 0.450        | -                | 0.795 (0.203)    | -         |     7.28 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           38 |     2556 | 2024-04-26 | W7M               | W   | 0.528      | -            | -                | -                | -         |     5.10 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           37 |     2557 | 2024-04-26 | W7M               | W   | 0.527      | -            | -                | -                | -         |     5.31 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           36 |     2607 | 2024-04-24 | paiN              | L   | 0.515      | -            | -                | -                | -         |    -1.37 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           35 |     2608 | 2024-04-24 | paiN              | W   | 0.515      | 0.450        | 0.325 (0.075)    | 0.856 (0.198)    | -         |    14.99 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           34 |     2815 | 2024-04-17 | Fluxo             | L   | 0.468      | -            | -                | -                | -         |    -5.01 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           33 |     2821 | 2024-04-17 | W7M               | W   | 0.468      | -            | -                | -                | -         |     5.05 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           32 |     2853 | 2024-04-16 | SPORT             | W   | 0.462      | -            | -                | -                | -         |     3.02 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           31 |     2906 | 2024-04-13 | paiN              | L   | 0.441      | -            | -                | -                | -         |    -0.99 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           30 |     2927 | 2024-04-12 | Solid             | W   | 0.432      | -            | -                | -                | -         |     5.71 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           29 |     2974 | 2024-04-10 | Sharks            | L   | 0.422      | -            | -                | -                | -         |    -9.77 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           28 |     2978 | 2024-04-10 | Sharks            | W   | 0.422      | -            | -                | -                | -         |     3.54 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           27 |     3032 | 2024-04-09 | Fluxo             | L   | 0.415      | -            | -                | -                | -         |    -4.57 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           26 |     3037 | 2024-04-09 | Fluxo             | L   | 0.415      | -            | -                | -                | -         |    -4.72 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           25 |     3073 | 2024-04-08 | Fluxo             | L   | 0.407      | -            | -                | -                | -         |    -4.80 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           24 |     3126 | 2024-04-06 | Sharks            | L   | 0.394      | -            | -                | -                | -         |    -9.58 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           23 |     3129 | 2024-04-06 | LA RUGONETA       | W   | 0.393      | -            | -                | -                | -         |     1.02 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           22 |     3143 | 2024-04-05 | MIBR              | L   | 0.387      | -            | -                | -                | -         |    -0.98 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           21 |     3168 | 2024-04-04 | Imperial          | L   | 0.382      | -            | -                | -                | -         |    -1.93 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           20 |     3174 | 2024-04-04 | Imperial          | L   | 0.381      | -            | -                | -                | -         |    -1.96 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           19 |     3207 | 2024-04-03 | RED Canids        | L   | 0.375      | -            | -                | -                | -         |    -4.19 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           18 |     3210 | 2024-04-03 | RED Canids        | L   | 0.375      | -            | -                | -                | -         |    -4.32 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           17 |     3386 | 2024-03-26 | MIBR              | L   | 0.322      | -            | -                | -                | -         |    -0.90 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           16 |     3388 | 2024-03-26 | MIBR              | L   | 0.322      | -            | -                | -                | -         |    -0.91 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           15 |     3495 | 2024-03-18 | RED Canids        | L   | 0.267      | -            | -                | -                | -         |    -3.18 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           14 |     3520 | 2024-03-17 | Case              | W   | 0.260      | -            | -                | -                | -         |     3.30 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           13 |     3538 | 2024-03-16 | RED Canids        | L   | 0.254      | -            | -                | -                | -         |    -3.06 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           12 |     3553 | 2024-03-15 | 2GAME             | W   | 0.249      | -            | -                | -                | -         |     1.18 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           11 |     3554 | 2024-03-15 | 2GAME             | W   | 0.248      | -            | -                | -                | -         |     1.19 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           10 |     3558 | 2024-03-15 | MIBR Academy      | W   | 0.247      | -            | -                | -                | -         |     0.50 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            9 |     3613 | 2024-03-13 | Sharks            | L   | 0.234      | -            | -                | -                | -         |    -3.92 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            8 |     3630 | 2024-03-13 | Case              | W   | 0.233      | -            | -                | -                | -         |     3.07 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            7 |     3699 | 2024-03-10 | Solid             | W   | 0.213      | -            | -                | -                | -         |     2.50 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            6 |     3705 | 2024-03-10 | LA RUGONETA       | L   | 0.212      | -            | -                | -                | -         |    -6.23 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            5 |     3751 | 2024-03-08 | Galorys           | L   | 0.199      | -            | -                | -                | -         |    -4.04 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            4 |     3862 | 2024-03-04 | paiN              | L   | 0.173      | -            | -                | -                | -         |    -0.52 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            3 |     3878 | 2024-03-03 | RED Canids        | W   | 0.167      | -            | -                | -                | 1 (0.167) |     3.21 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            2 |     3902 | 2024-03-02 | Elevate           | W   | 0.161      | -            | -                | -                | 1 (0.161) |     2.59 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            1 |     3927 | 2024-03-01 | M80               | L   | 0.154      | -            | -                | -                | -         |    -1.05 | matios, naitte, ponter, Tuurtle, WOOD7 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,839.22)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-27 |      1.000 | $9,100.00      | $9,100.00       |
| 2024-07-22 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-07-14 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.867 | $5,000.00      | $4,334.72       |
| 2024-06-10 |      0.828 | $750.00        | $621.16         |
| 2024-06-09 |      0.821 | $1,500.00      | $1,231.53       |
| 2024-05-21 |      0.694 | $1,500.00      | $1,040.42       |
| 2024-05-19 |      0.680 | $2,000.00      | $1,360.56       |
| 2024-03-18 |      0.267 | $1,500.00      | $400.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
