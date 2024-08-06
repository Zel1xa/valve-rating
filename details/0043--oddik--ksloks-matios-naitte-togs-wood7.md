### Roster Details<br />
Team Name: ODDIK<br />
Roster: ksloks, matios, naitte, togs, WOOD7<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [12]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1103.0<br />
<br />
Final Rank Value (1103.0) = Starting Rank Value (993.5) + Head To Head Adjustments (109.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.499[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.219[<sup>2</sup>](#table1)
- LAN Wins: 0.037[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 993.5
- 400 + ( ( 0.289 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 993.5


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
|          108 |       59 | 2024-08-03 | RED Canids        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.21 | ksloks, matios, naitte, togs, WOOD7    |
|          107 |       67 | 2024-08-03 | BESTIA            | W   | 1.000      | 0.143        | 0.096 (0.014)    | -                | 0 (0.000) |    12.08 | ksloks, matios, naitte, togs, WOOD7    |
|          106 |       73 | 2024-08-03 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -4.09 | ksloks, matios, naitte, togs, WOOD7    |
|          105 |       97 | 2024-08-02 | MIBR              | W   | 1.000      | 0.143        | 0.208 (0.030)    | -                | 0 (0.000) |    25.96 | ksloks, matios, naitte, togs, WOOD7    |
|          104 |      128 | 2024-08-01 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.31 | ksloks, matios, naitte, togs, WOOD7    |
|          103 |      138 | 2024-08-01 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.01 | ksloks, matios, naitte, togs, WOOD7    |
|          102 |      181 | 2024-07-31 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -4.13 | ksloks, matios, naitte, togs, WOOD7    |
|          101 |      188 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.48 | ksloks, matios, naitte, togs, WOOD7    |
|          100 |      194 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.78 | ksloks, matios, naitte, togs, WOOD7    |
|           99 |      228 | 2024-07-30 | inSanitY          | W   | 1.000      | 0.371        | 0.048 (0.018)    | -                | 0 (0.000) |    12.78 | ksloks, matios, naitte, togs, WOOD7    |
|           98 |      240 | 2024-07-30 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.07 | lineko, matios, naitte, togs, WOOD7    |
|           97 |      328 | 2024-07-27 | Galorys           | W   | 1.000      | 0.365        | -                | 0.530 (0.193)    | 0 (0.000) |     7.48 | ksloks, matios, naitte, togs, WOOD7    |
|           96 |      348 | 2024-07-26 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.61 | ksloks, matios, naitte, togs, WOOD7    |
|           95 |      354 | 2024-07-26 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |    22.47 | ksloks, matios, naitte, togs, WOOD7    |
|           94 |      360 | 2024-07-26 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     6.56 | ksloks, matios, naitte, togs, WOOD7    |
|           93 |      380 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.89 | ksloks, matios, naitte, togs, WOOD7    |
|           92 |      388 | 2024-07-25 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | -         |     0.90 | ksloks, matios, naitte, togs, WOOD7    |
|           91 |      423 | 2024-07-24 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -9.71 | ksloks, matios, naitte, togs, WOOD7    |
|           90 |      453 | 2024-07-23 | Sharks            | W   | 1.000      | -            | -                | -                | -         |    14.05 | ksloks, matios, naitte, togs, WOOD7    |
|           89 |      492 | 2024-07-22 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.05 | ksloks, matios, naitte, togs, WOOD7    |
|           88 |      500 | 2024-07-22 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     6.36 | ksloks, matios, naitte, togs, WOOD7    |
|           87 |      544 | 2024-07-20 | Hype              | W   | 1.000      | -            | -                | -                | -         |    10.37 | ksloks, matios, naitte, togs, WOOD7    |
|           86 |      555 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.24 | ksloks, matios, naitte, togs, WOOD7    |
|           85 |      626 | 2024-07-18 | Case              | L   | 1.000      | -            | -                | -                | -         |   -22.27 | ksloks, matios, naitte, togs, WOOD7    |
|           84 |      637 | 2024-07-18 | Imperial          | W   | 1.000      | 0.143        | 0.233 (0.033)    | -                | -         |    22.43 | ksloks, matios, naitte, togs, WOOD7    |
|           83 |      641 | 2024-07-18 | BESTIA            | W   | 1.000      | 0.143        | 0.096 (0.014)    | -                | -         |    14.28 | ksloks, matios, naitte, togs, WOOD7    |
|           82 |      685 | 2024-07-17 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -17.45 | ksloks, matios, naitte, togs, WOOD7    |
|           81 |      696 | 2024-07-17 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -19.02 | ksloks, matios, naitte, togs, WOOD7    |
|           80 |      757 | 2024-07-16 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |   -18.51 | ksloks, matios, naitte, togs, WOOD7    |
|           79 |      766 | 2024-07-16 | BESTIA            | W   | 1.000      | 0.333        | 0.096 (0.032)    | 0.775 (0.258)    | -         |    12.74 | ksloks, matios, naitte, togs, WOOD7    |
|           78 |      806 | 2024-07-15 | Case              | W   | 1.000      | 0.333        | -                | 0.778 (0.259)    | -         |    10.20 | ksloks, matios, naitte, togs, WOOD7    |
|           77 |      842 | 2024-07-14 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.620 (0.230)    | -         |    17.28 | ksloks, matios, naitte, togs, WOOD7    |
|           76 |      853 | 2024-07-13 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.13 | ksloks, matios, naitte, togs, WOOD7    |
|           75 |      854 | 2024-07-13 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |     9.39 | ksloks, matios, naitte, togs, WOOD7    |
|           74 |      874 | 2024-07-11 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.620 (0.230)    | -         |    18.30 | ksloks, matios, naitte, togs, WOOD7    |
|           73 |      893 | 2024-07-10 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.59 | ksloks, matios, naitte, togs, WOOD7    |
|           72 |      902 | 2024-07-10 | Hype              | W   | 1.000      | -            | -                | -                | -         |    12.84 | ksloks, matios, naitte, togs, WOOD7    |
|           71 |      943 | 2024-07-08 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | -         |     4.86 | ksloks, matios, naitte, togs, WOOD7    |
|           70 |      957 | 2024-07-06 | W7M               | W   | 0.995      | -            | -                | -                | -         |     8.21 | ksloks, matios, naitte, togs, WOOD7    |
|           69 |     1070 | 2024-06-15 | paiN              | L   | 0.854      | -            | -                | -                | -         |    -2.63 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           68 |     1139 | 2024-06-13 | Hype              | W   | 0.842      | -            | -                | -                | -         |    11.56 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           67 |     1209 | 2024-06-10 | W7M               | W   | 0.822      | -            | -                | -                | -         |     7.84 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           66 |     1240 | 2024-06-09 | Galorys           | W   | 0.816      | 0.450        | 0.030 (0.011)    | 0.530 (0.195)    | -         |    10.47 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           65 |     1260 | 2024-06-09 | Imperial          | L   | 0.814      | -            | -                | -                | -         |    -3.09 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           64 |     1299 | 2024-06-08 | W7M               | W   | 0.810      | -            | -                | -                | -         |     7.96 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           63 |     1366 | 2024-06-07 | BESTIA            | L   | 0.802      | -            | -                | -                | -         |    -8.85 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           62 |     1442 | 2024-06-06 | Patins da Ferrari | L   | 0.795      | -            | -                | -                | -         |   -17.54 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           61 |     1539 | 2024-06-04 | paiN              | L   | 0.783      | -            | -                | -                | -         |    -2.48 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           60 |     1909 | 2024-05-21 | Case              | L   | 0.689      | -            | -                | -                | -         |   -12.02 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           59 |     1966 | 2024-05-19 | Case              | W   | 0.676      | -            | -                | -                | -         |     9.31 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           58 |     1991 | 2024-05-18 | RED Canids        | L   | 0.669      | -            | -                | -                | -         |    -6.06 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           57 |     1997 | 2024-05-18 | Galorys           | W   | 0.669      | -            | -                | -                | -         |     8.83 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           56 |     2030 | 2024-05-17 | FURIA Academy     | W   | 0.663      | -            | -                | -                | -         |     1.84 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           55 |     2034 | 2024-05-17 | Sharks            | W   | 0.662      | -            | -                | -                | -         |    12.19 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           54 |     2060 | 2024-05-16 | 9z                | L   | 0.656      | -            | -                | -                | -         |    -0.95 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           53 |     2065 | 2024-05-16 | Solid             | L   | 0.655      | -            | -                | -                | -         |   -12.25 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           52 |     2110 | 2024-05-15 | BESTIA            | L   | 0.650      | -            | -                | -                | -         |   -10.06 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           51 |     2111 | 2024-05-15 | BESTIA            | L   | 0.649      | -            | -                | -                | -         |   -10.66 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           50 |     2157 | 2024-05-14 | Solid             | L   | 0.644      | -            | -                | -                | -         |   -13.02 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           49 |     2160 | 2024-05-14 | Solid             | W   | 0.644      | 0.450        | -                | 0.807 (0.234)    | -         |     7.30 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           48 |     2175 | 2024-05-14 | KRÜ               | W   | 0.642      | -            | -                | -                | -         |     8.24 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           47 |     2186 | 2024-05-14 | Fluxo             | L   | 0.641      | -            | -                | -                | -         |    -6.88 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           46 |     2201 | 2024-05-13 | Solid             | W   | 0.636      | -            | -                | -                | -         |     7.58 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           45 |     2225 | 2024-05-12 | Intense           | W   | 0.629      | -            | -                | -                | -         |     4.43 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           44 |     2247 | 2024-05-11 | ex-Corinthians    | W   | 0.623      | -            | -                | -                | -         |     1.73 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           43 |     2303 | 2024-05-09 | inSanitY          | L   | 0.608      | -            | -                | -                | -         |   -10.88 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           42 |     2338 | 2024-05-07 | Imperial          | L   | 0.597      | -            | -                | -                | -         |    -2.95 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           41 |     2371 | 2024-05-05 | Case              | W   | 0.583      | 0.435        | -                | 0.778 (0.197)    | -         |     7.64 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           40 |     2429 | 2024-05-02 | Case              | L   | 0.563      | -            | -                | -                | -         |   -10.63 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           39 |     2430 | 2024-05-02 | Case              | W   | 0.563      | 0.450        | -                | 0.778 (0.197)    | -         |     7.22 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           38 |     2567 | 2024-04-26 | W7M               | W   | 0.523      | -            | -                | -                | -         |     5.06 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           37 |     2568 | 2024-04-26 | W7M               | W   | 0.522      | -            | -                | -                | -         |     5.26 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           36 |     2618 | 2024-04-24 | paiN              | L   | 0.510      | -            | -                | -                | -         |    -1.37 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           35 |     2619 | 2024-04-24 | paiN              | W   | 0.510      | 0.450        | 0.324 (0.074)    | 0.838 (0.192)    | -         |    14.83 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           34 |     2826 | 2024-04-17 | Fluxo             | L   | 0.463      | -            | -                | -                | -         |    -4.98 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           33 |     2832 | 2024-04-17 | W7M               | W   | 0.463      | -            | -                | -                | -         |     5.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           32 |     2864 | 2024-04-16 | SPORT             | W   | 0.457      | -            | -                | -                | -         |     3.01 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           31 |     2917 | 2024-04-13 | paiN              | L   | 0.436      | -            | -                | -                | -         |    -1.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           30 |     2938 | 2024-04-12 | Solid             | W   | 0.427      | -            | -                | -                | -         |     5.64 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           29 |     2985 | 2024-04-10 | Sharks            | L   | 0.417      | -            | -                | -                | -         |    -9.64 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           28 |     2989 | 2024-04-10 | Sharks            | W   | 0.417      | -            | -                | -                | -         |     3.52 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           27 |     3043 | 2024-04-09 | Fluxo             | L   | 0.410      | -            | -                | -                | -         |    -4.53 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           26 |     3048 | 2024-04-09 | Fluxo             | L   | 0.410      | -            | -                | -                | -         |    -4.68 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           25 |     3084 | 2024-04-08 | Fluxo             | L   | 0.403      | -            | -                | -                | -         |    -4.76 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           24 |     3137 | 2024-04-06 | Sharks            | L   | 0.389      | -            | -                | -                | -         |    -9.44 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           23 |     3140 | 2024-04-06 | LA RUGONETA       | W   | 0.388      | -            | -                | -                | -         |     1.01 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           22 |     3154 | 2024-04-05 | MIBR              | L   | 0.382      | -            | -                | -                | -         |    -0.97 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           21 |     3179 | 2024-04-04 | Imperial          | L   | 0.377      | -            | -                | -                | -         |    -1.93 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           20 |     3185 | 2024-04-04 | Imperial          | L   | 0.376      | -            | -                | -                | -         |    -1.96 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           19 |     3218 | 2024-04-03 | RED Canids        | L   | 0.370      | -            | -                | -                | -         |    -4.15 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           18 |     3221 | 2024-04-03 | RED Canids        | L   | 0.370      | -            | -                | -                | -         |    -4.27 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           17 |     3397 | 2024-03-26 | MIBR              | L   | 0.317      | -            | -                | -                | -         |    -0.90 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           16 |     3399 | 2024-03-26 | MIBR              | L   | 0.317      | -            | -                | -                | -         |    -0.90 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           15 |     3506 | 2024-03-18 | RED Canids        | L   | 0.262      | -            | -                | -                | -         |    -3.13 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           14 |     3531 | 2024-03-17 | Case              | W   | 0.255      | -            | -                | -                | -         |     3.24 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           13 |     3549 | 2024-03-16 | RED Canids        | L   | 0.249      | -            | -                | -                | -         |    -3.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           12 |     3564 | 2024-03-15 | 2GAME             | W   | 0.244      | -            | -                | -                | -         |     1.16 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           11 |     3565 | 2024-03-15 | 2GAME             | W   | 0.243      | -            | -                | -                | -         |     1.17 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           10 |     3569 | 2024-03-15 | MIBR Academy      | W   | 0.242      | -            | -                | -                | -         |     0.49 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            9 |     3624 | 2024-03-13 | Sharks            | L   | 0.229      | -            | -                | -                | -         |    -3.84 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            8 |     3641 | 2024-03-13 | Case              | W   | 0.228      | -            | -                | -                | -         |     3.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            7 |     3710 | 2024-03-10 | Solid             | W   | 0.208      | -            | -                | -                | -         |     2.44 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            6 |     3716 | 2024-03-10 | LA RUGONETA       | L   | 0.207      | -            | -                | -                | -         |    -6.08 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            5 |     3762 | 2024-03-08 | Galorys           | L   | 0.194      | -            | -                | -                | -         |    -3.93 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            4 |     3873 | 2024-03-04 | paiN              | L   | 0.168      | -            | -                | -                | -         |    -0.51 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            3 |     3889 | 2024-03-03 | RED Canids        | W   | 0.162      | -            | -                | -                | 1 (0.162) |     3.11 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            2 |     3913 | 2024-03-02 | Elevate           | W   | 0.156      | -            | -                | -                | 1 (0.156) |     2.51 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            1 |     3938 | 2024-03-01 | M80               | L   | 0.149      | -            | -                | -                | -         |    -1.01 | matios, naitte, ponter, Tuurtle, WOOD7 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,777.97)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-27 |      1.000 | $9,100.00      | $9,100.00       |
| 2024-07-22 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-07-14 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.862 | $5,000.00      | $4,309.72       |
| 2024-06-10 |      0.823 | $750.00        | $617.41         |
| 2024-06-09 |      0.816 | $1,500.00      | $1,224.03       |
| 2024-05-21 |      0.689 | $1,500.00      | $1,032.92       |
| 2024-05-19 |      0.675 | $2,000.00      | $1,350.56       |
| 2024-03-18 |      0.262 | $1,500.00      | $393.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
