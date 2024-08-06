### Roster Details<br />
Team Name: ODDIK<br />
Roster: ksloks, matios, naitte, togs, WOOD7<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [12]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1102.9<br />
<br />
Final Rank Value (1102.9) = Starting Rank Value (993.5) + Head To Head Adjustments (109.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.499[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.218[<sup>2</sup>](#table1)
- LAN Wins: 0.036[<sup>2</sup>](#table1)

The average of these factors is 0.288<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 993.5
- 400 + ( ( 0.288 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 993.5


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
|          108 |       68 | 2024-08-03 | RED Canids        | W   | 1.000      | 0.143        | 0.076 (0.011)    | -                | 0 (0.000) |    18.21 | ksloks, matios, naitte, togs, WOOD7    |
|          107 |       76 | 2024-08-03 | BESTIA            | W   | 1.000      | 0.143        | 0.096 (0.014)    | -                | 0 (0.000) |    12.08 | ksloks, matios, naitte, togs, WOOD7    |
|          106 |       82 | 2024-08-03 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -4.09 | ksloks, matios, naitte, togs, WOOD7    |
|          105 |      106 | 2024-08-02 | MIBR              | W   | 1.000      | 0.143        | 0.208 (0.030)    | -                | 0 (0.000) |    25.96 | ksloks, matios, naitte, togs, WOOD7    |
|          104 |      137 | 2024-08-01 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.31 | ksloks, matios, naitte, togs, WOOD7    |
|          103 |      147 | 2024-08-01 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.02 | ksloks, matios, naitte, togs, WOOD7    |
|          102 |      190 | 2024-07-31 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -4.13 | ksloks, matios, naitte, togs, WOOD7    |
|          101 |      197 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.49 | ksloks, matios, naitte, togs, WOOD7    |
|          100 |      203 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.78 | ksloks, matios, naitte, togs, WOOD7    |
|           99 |      237 | 2024-07-30 | inSanitY          | W   | 1.000      | 0.371        | 0.048 (0.018)    | -                | 0 (0.000) |    12.78 | ksloks, matios, naitte, togs, WOOD7    |
|           98 |      249 | 2024-07-30 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.07 | lineko, matios, naitte, togs, WOOD7    |
|           97 |      337 | 2024-07-27 | Galorys           | W   | 1.000      | 0.365        | -                | 0.530 (0.193)    | 0 (0.000) |     7.48 | ksloks, matios, naitte, togs, WOOD7    |
|           96 |      357 | 2024-07-26 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.61 | ksloks, matios, naitte, togs, WOOD7    |
|           95 |      363 | 2024-07-26 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |    22.47 | ksloks, matios, naitte, togs, WOOD7    |
|           94 |      369 | 2024-07-26 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     6.56 | ksloks, matios, naitte, togs, WOOD7    |
|           93 |      389 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.89 | ksloks, matios, naitte, togs, WOOD7    |
|           92 |      397 | 2024-07-25 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | -         |     0.90 | ksloks, matios, naitte, togs, WOOD7    |
|           91 |      432 | 2024-07-24 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -9.72 | ksloks, matios, naitte, togs, WOOD7    |
|           90 |      462 | 2024-07-23 | Sharks            | W   | 1.000      | -            | -                | -                | -         |    14.05 | ksloks, matios, naitte, togs, WOOD7    |
|           89 |      501 | 2024-07-22 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.05 | ksloks, matios, naitte, togs, WOOD7    |
|           88 |      509 | 2024-07-22 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     6.36 | ksloks, matios, naitte, togs, WOOD7    |
|           87 |      553 | 2024-07-20 | Hype              | W   | 1.000      | -            | -                | -                | -         |    10.38 | ksloks, matios, naitte, togs, WOOD7    |
|           86 |      564 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.24 | ksloks, matios, naitte, togs, WOOD7    |
|           85 |      635 | 2024-07-18 | Case              | L   | 1.000      | -            | -                | -                | -         |   -22.27 | ksloks, matios, naitte, togs, WOOD7    |
|           84 |      646 | 2024-07-18 | Imperial          | W   | 1.000      | 0.143        | 0.233 (0.033)    | -                | -         |    22.42 | ksloks, matios, naitte, togs, WOOD7    |
|           83 |      650 | 2024-07-18 | BESTIA            | W   | 1.000      | 0.143        | 0.096 (0.014)    | -                | -         |    14.28 | ksloks, matios, naitte, togs, WOOD7    |
|           82 |      694 | 2024-07-17 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -17.45 | ksloks, matios, naitte, togs, WOOD7    |
|           81 |      705 | 2024-07-17 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -19.02 | ksloks, matios, naitte, togs, WOOD7    |
|           80 |      766 | 2024-07-16 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |   -18.52 | ksloks, matios, naitte, togs, WOOD7    |
|           79 |      775 | 2024-07-16 | BESTIA            | W   | 1.000      | 0.333        | 0.096 (0.032)    | 0.776 (0.259)    | -         |    12.74 | ksloks, matios, naitte, togs, WOOD7    |
|           78 |      815 | 2024-07-15 | Case              | W   | 1.000      | 0.333        | -                | 0.778 (0.259)    | -         |    10.21 | ksloks, matios, naitte, togs, WOOD7    |
|           77 |      851 | 2024-07-14 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.621 (0.230)    | -         |    17.27 | ksloks, matios, naitte, togs, WOOD7    |
|           76 |      862 | 2024-07-13 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.13 | ksloks, matios, naitte, togs, WOOD7    |
|           75 |      863 | 2024-07-13 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |     9.40 | ksloks, matios, naitte, togs, WOOD7    |
|           74 |      883 | 2024-07-11 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.621 (0.230)    | -         |    18.29 | ksloks, matios, naitte, togs, WOOD7    |
|           73 |      902 | 2024-07-10 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.59 | ksloks, matios, naitte, togs, WOOD7    |
|           72 |      911 | 2024-07-10 | Hype              | W   | 1.000      | -            | -                | -                | -         |    12.84 | ksloks, matios, naitte, togs, WOOD7    |
|           71 |      952 | 2024-07-08 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | -         |     4.86 | ksloks, matios, naitte, togs, WOOD7    |
|           70 |      966 | 2024-07-06 | W7M               | W   | 0.994      | -            | -                | -                | -         |     8.21 | ksloks, matios, naitte, togs, WOOD7    |
|           69 |     1079 | 2024-06-15 | paiN              | L   | 0.853      | -            | -                | -                | -         |    -2.63 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           68 |     1148 | 2024-06-13 | Hype              | W   | 0.841      | -            | -                | -                | -         |    11.55 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           67 |     1218 | 2024-06-10 | W7M               | W   | 0.821      | -            | -                | -                | -         |     7.83 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           66 |     1249 | 2024-06-09 | Galorys           | W   | 0.815      | 0.450        | -                | 0.530 (0.194)    | -         |    10.46 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           65 |     1269 | 2024-06-09 | Imperial          | L   | 0.813      | -            | -                | -                | -         |    -3.10 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           64 |     1308 | 2024-06-08 | W7M               | W   | 0.809      | -            | -                | -                | -         |     7.95 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           63 |     1375 | 2024-06-07 | BESTIA            | L   | 0.801      | -            | -                | -                | -         |    -8.85 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           62 |     1451 | 2024-06-06 | Patins da Ferrari | L   | 0.794      | -            | -                | -                | -         |   -17.51 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           61 |     1548 | 2024-06-04 | paiN              | L   | 0.782      | -            | -                | -                | -         |    -2.48 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           60 |     1918 | 2024-05-21 | Case              | L   | 0.688      | -            | -                | -                | -         |   -12.00 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           59 |     1975 | 2024-05-19 | Case              | W   | 0.675      | -            | -                | -                | -         |     9.30 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           58 |     2000 | 2024-05-18 | RED Canids        | L   | 0.668      | -            | -                | -                | -         |    -6.06 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           57 |     2006 | 2024-05-18 | Galorys           | W   | 0.667      | -            | -                | -                | -         |     8.82 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           56 |     2039 | 2024-05-17 | FURIA Academy     | W   | 0.662      | -            | -                | -                | -         |     1.84 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           55 |     2043 | 2024-05-17 | Sharks            | W   | 0.661      | -            | -                | -                | -         |    12.17 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           54 |     2069 | 2024-05-16 | 9z                | L   | 0.655      | -            | -                | -                | -         |    -0.95 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           53 |     2074 | 2024-05-16 | Solid             | L   | 0.654      | -            | -                | -                | -         |   -12.23 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           52 |     2119 | 2024-05-15 | BESTIA            | L   | 0.649      | -            | -                | -                | -         |   -10.04 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           51 |     2120 | 2024-05-15 | BESTIA            | L   | 0.648      | -            | -                | -                | -         |   -10.64 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           50 |     2166 | 2024-05-14 | Solid             | L   | 0.643      | -            | -                | -                | -         |   -13.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           49 |     2169 | 2024-05-14 | Solid             | W   | 0.642      | 0.450        | -                | 0.807 (0.233)    | -         |     7.29 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           48 |     2184 | 2024-05-14 | KRÜ               | W   | 0.641      | -            | -                | -                | -         |     8.23 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           47 |     2195 | 2024-05-14 | Fluxo             | L   | 0.640      | -            | -                | -                | -         |    -6.87 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           46 |     2210 | 2024-05-13 | Solid             | W   | 0.635      | -            | -                | -                | -         |     7.57 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           45 |     2234 | 2024-05-12 | Intense           | W   | 0.628      | -            | -                | -                | -         |     4.43 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           44 |     2256 | 2024-05-11 | ex-Corinthians    | W   | 0.622      | -            | -                | -                | -         |     1.73 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           43 |     2312 | 2024-05-09 | inSanitY          | L   | 0.607      | -            | -                | -                | -         |   -10.87 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           42 |     2347 | 2024-05-07 | Imperial          | L   | 0.596      | -            | -                | -                | -         |    -2.95 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           41 |     2380 | 2024-05-05 | Case              | W   | 0.582      | 0.435        | -                | 0.778 (0.197)    | -         |     7.63 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           40 |     2438 | 2024-05-02 | Case              | L   | 0.562      | -            | -                | -                | -         |   -10.60 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           39 |     2439 | 2024-05-02 | Case              | W   | 0.562      | 0.450        | -                | 0.778 (0.197)    | -         |     7.21 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           38 |     2576 | 2024-04-26 | W7M               | W   | 0.522      | -            | -                | -                | -         |     5.05 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           37 |     2577 | 2024-04-26 | W7M               | W   | 0.521      | -            | -                | -                | -         |     5.25 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           36 |     2627 | 2024-04-24 | paiN              | L   | 0.509      | -            | -                | -                | -         |    -1.37 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           35 |     2628 | 2024-04-24 | paiN              | W   | 0.509      | 0.450        | 0.324 (0.074)    | 0.839 (0.192)    | -         |    14.79 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           34 |     2835 | 2024-04-17 | Fluxo             | L   | 0.462      | -            | -                | -                | -         |    -4.97 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           33 |     2841 | 2024-04-17 | W7M               | W   | 0.462      | -            | -                | -                | -         |     4.99 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           32 |     2873 | 2024-04-16 | SPORT             | W   | 0.456      | -            | -                | -                | -         |     3.01 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           31 |     2926 | 2024-04-13 | paiN              | L   | 0.435      | -            | -                | -                | -         |    -1.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           30 |     2947 | 2024-04-12 | Solid             | W   | 0.426      | -            | -                | -                | -         |     5.62 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           29 |     2994 | 2024-04-10 | Sharks            | L   | 0.416      | -            | -                | -                | -         |    -9.61 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           28 |     2998 | 2024-04-10 | Sharks            | W   | 0.416      | -            | -                | -                | -         |     3.50 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           27 |     3052 | 2024-04-09 | Fluxo             | L   | 0.409      | -            | -                | -                | -         |    -4.52 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           26 |     3057 | 2024-04-09 | Fluxo             | L   | 0.409      | -            | -                | -                | -         |    -4.67 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           25 |     3093 | 2024-04-08 | Fluxo             | L   | 0.401      | -            | -                | -                | -         |    -4.75 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           24 |     3146 | 2024-04-06 | Sharks            | L   | 0.388      | -            | -                | -                | -         |    -9.41 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           23 |     3149 | 2024-04-06 | LA RUGONETA       | W   | 0.386      | -            | -                | -                | -         |     1.01 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           22 |     3163 | 2024-04-05 | MIBR              | L   | 0.381      | -            | -                | -                | -         |    -0.97 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           21 |     3188 | 2024-04-04 | Imperial          | L   | 0.376      | -            | -                | -                | -         |    -1.93 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           20 |     3194 | 2024-04-04 | Imperial          | L   | 0.375      | -            | -                | -                | -         |    -1.96 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           19 |     3227 | 2024-04-03 | RED Canids        | L   | 0.369      | -            | -                | -                | -         |    -4.14 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           18 |     3230 | 2024-04-03 | RED Canids        | L   | 0.369      | -            | -                | -                | -         |    -4.26 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           17 |     3406 | 2024-03-26 | MIBR              | L   | 0.316      | -            | -                | -                | -         |    -0.89 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           16 |     3408 | 2024-03-26 | MIBR              | L   | 0.316      | -            | -                | -                | -         |    -0.90 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           15 |     3515 | 2024-03-18 | RED Canids        | L   | 0.261      | -            | -                | -                | -         |    -3.11 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           14 |     3540 | 2024-03-17 | Case              | W   | 0.254      | -            | -                | -                | -         |     3.22 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           13 |     3558 | 2024-03-16 | RED Canids        | L   | 0.248      | -            | -                | -                | -         |    -2.99 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           12 |     3573 | 2024-03-15 | 2GAME             | W   | 0.242      | -            | -                | -                | -         |     1.16 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           11 |     3574 | 2024-03-15 | 2GAME             | W   | 0.242      | -            | -                | -                | -         |     1.17 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           10 |     3578 | 2024-03-15 | MIBR Academy      | W   | 0.241      | -            | -                | -                | -         |     0.49 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            9 |     3633 | 2024-03-13 | Sharks            | L   | 0.228      | -            | -                | -                | -         |    -3.82 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            8 |     3650 | 2024-03-13 | Case              | W   | 0.227      | -            | -                | -                | -         |     2.99 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            7 |     3719 | 2024-03-10 | Solid             | W   | 0.207      | -            | -                | -                | -         |     2.42 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            6 |     3725 | 2024-03-10 | LA RUGONETA       | L   | 0.206      | -            | -                | -                | -         |    -6.05 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            5 |     3771 | 2024-03-08 | Galorys           | L   | 0.193      | -            | -                | -                | -         |    -3.91 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            4 |     3882 | 2024-03-04 | paiN              | L   | 0.167      | -            | -                | -                | -         |    -0.51 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            3 |     3898 | 2024-03-03 | RED Canids        | W   | 0.161      | -            | -                | -                | 1 (0.161) |     3.09 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            2 |     3922 | 2024-03-02 | Elevate           | W   | 0.155      | -            | -                | -                | 1 (0.155) |     2.49 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            1 |     3947 | 2024-03-01 | M80               | L   | 0.148      | -            | -                | -                | -         |    -1.01 | matios, naitte, ponter, Tuurtle, WOOD7 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,764.36)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-27 |      1.000 | $9,100.00      | $9,100.00       |
| 2024-07-22 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-07-14 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.861 | $5,000.00      | $4,304.17       |
| 2024-06-10 |      0.822 | $750.00        | $616.58         |
| 2024-06-09 |      0.815 | $1,500.00      | $1,222.36       |
| 2024-05-21 |      0.688 | $1,500.00      | $1,031.25       |
| 2024-05-19 |      0.674 | $2,000.00      | $1,348.33       |
| 2024-03-18 |      0.261 | $1,500.00      | $391.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
