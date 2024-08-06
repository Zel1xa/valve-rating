### Roster Details<br />
Team Name: ODDIK<br />
Roster: ksloks, matios, naitte, togs, WOOD7<br />
Global Rank: [45](../standings_global.md)<br />
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
|          108 |       67 | 2024-08-03 | RED Canids        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.21 | ksloks, matios, naitte, togs, WOOD7    |
|          107 |       75 | 2024-08-03 | BESTIA            | W   | 1.000      | 0.143        | 0.096 (0.014)    | -                | 0 (0.000) |    12.08 | ksloks, matios, naitte, togs, WOOD7    |
|          106 |       81 | 2024-08-03 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -4.09 | ksloks, matios, naitte, togs, WOOD7    |
|          105 |      105 | 2024-08-02 | MIBR              | W   | 1.000      | 0.143        | 0.208 (0.030)    | -                | 0 (0.000) |    25.96 | ksloks, matios, naitte, togs, WOOD7    |
|          104 |      136 | 2024-08-01 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.31 | ksloks, matios, naitte, togs, WOOD7    |
|          103 |      146 | 2024-08-01 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.02 | ksloks, matios, naitte, togs, WOOD7    |
|          102 |      189 | 2024-07-31 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -4.13 | ksloks, matios, naitte, togs, WOOD7    |
|          101 |      196 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.49 | ksloks, matios, naitte, togs, WOOD7    |
|          100 |      202 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.78 | ksloks, matios, naitte, togs, WOOD7    |
|           99 |      236 | 2024-07-30 | inSanitY          | W   | 1.000      | 0.371        | 0.048 (0.018)    | -                | 0 (0.000) |    12.78 | ksloks, matios, naitte, togs, WOOD7    |
|           98 |      248 | 2024-07-30 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.07 | lineko, matios, naitte, togs, WOOD7    |
|           97 |      336 | 2024-07-27 | Galorys           | W   | 1.000      | 0.365        | -                | 0.530 (0.193)    | 0 (0.000) |     7.48 | ksloks, matios, naitte, togs, WOOD7    |
|           96 |      356 | 2024-07-26 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.61 | ksloks, matios, naitte, togs, WOOD7    |
|           95 |      362 | 2024-07-26 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |    22.47 | ksloks, matios, naitte, togs, WOOD7    |
|           94 |      368 | 2024-07-26 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     6.56 | ksloks, matios, naitte, togs, WOOD7    |
|           93 |      388 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.89 | ksloks, matios, naitte, togs, WOOD7    |
|           92 |      396 | 2024-07-25 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | -         |     0.90 | ksloks, matios, naitte, togs, WOOD7    |
|           91 |      431 | 2024-07-24 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -9.72 | ksloks, matios, naitte, togs, WOOD7    |
|           90 |      461 | 2024-07-23 | Sharks            | W   | 1.000      | -            | -                | -                | -         |    14.05 | ksloks, matios, naitte, togs, WOOD7    |
|           89 |      500 | 2024-07-22 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.05 | ksloks, matios, naitte, togs, WOOD7    |
|           88 |      508 | 2024-07-22 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     6.36 | ksloks, matios, naitte, togs, WOOD7    |
|           87 |      552 | 2024-07-20 | Hype              | W   | 1.000      | -            | -                | -                | -         |    10.38 | ksloks, matios, naitte, togs, WOOD7    |
|           86 |      563 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.24 | ksloks, matios, naitte, togs, WOOD7    |
|           85 |      634 | 2024-07-18 | Case              | L   | 1.000      | -            | -                | -                | -         |   -22.27 | ksloks, matios, naitte, togs, WOOD7    |
|           84 |      645 | 2024-07-18 | Imperial          | W   | 1.000      | 0.143        | 0.233 (0.033)    | -                | -         |    22.42 | ksloks, matios, naitte, togs, WOOD7    |
|           83 |      649 | 2024-07-18 | BESTIA            | W   | 1.000      | 0.143        | 0.096 (0.014)    | -                | -         |    14.28 | ksloks, matios, naitte, togs, WOOD7    |
|           82 |      693 | 2024-07-17 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -17.45 | ksloks, matios, naitte, togs, WOOD7    |
|           81 |      704 | 2024-07-17 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -19.02 | ksloks, matios, naitte, togs, WOOD7    |
|           80 |      765 | 2024-07-16 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |   -18.52 | ksloks, matios, naitte, togs, WOOD7    |
|           79 |      774 | 2024-07-16 | BESTIA            | W   | 1.000      | 0.333        | 0.096 (0.032)    | 0.776 (0.259)    | -         |    12.74 | ksloks, matios, naitte, togs, WOOD7    |
|           78 |      814 | 2024-07-15 | Case              | W   | 1.000      | 0.333        | -                | 0.778 (0.259)    | -         |    10.20 | ksloks, matios, naitte, togs, WOOD7    |
|           77 |      850 | 2024-07-14 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.621 (0.230)    | -         |    17.27 | ksloks, matios, naitte, togs, WOOD7    |
|           76 |      861 | 2024-07-13 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.13 | ksloks, matios, naitte, togs, WOOD7    |
|           75 |      862 | 2024-07-13 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |     9.40 | ksloks, matios, naitte, togs, WOOD7    |
|           74 |      882 | 2024-07-11 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.621 (0.230)    | -         |    18.29 | ksloks, matios, naitte, togs, WOOD7    |
|           73 |      901 | 2024-07-10 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.59 | ksloks, matios, naitte, togs, WOOD7    |
|           72 |      910 | 2024-07-10 | Hype              | W   | 1.000      | -            | -                | -                | -         |    12.84 | ksloks, matios, naitte, togs, WOOD7    |
|           71 |      951 | 2024-07-08 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | -         |     4.86 | ksloks, matios, naitte, togs, WOOD7    |
|           70 |      965 | 2024-07-06 | W7M               | W   | 0.994      | -            | -                | -                | -         |     8.21 | ksloks, matios, naitte, togs, WOOD7    |
|           69 |     1078 | 2024-06-15 | paiN              | L   | 0.854      | -            | -                | -                | -         |    -2.63 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           68 |     1147 | 2024-06-13 | Hype              | W   | 0.841      | -            | -                | -                | -         |    11.55 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           67 |     1217 | 2024-06-10 | W7M               | W   | 0.821      | -            | -                | -                | -         |     7.83 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           66 |     1248 | 2024-06-09 | Galorys           | W   | 0.815      | 0.450        | 0.030 (0.011)    | 0.530 (0.194)    | -         |    10.46 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           65 |     1268 | 2024-06-09 | Imperial          | L   | 0.813      | -            | -                | -                | -         |    -3.10 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           64 |     1307 | 2024-06-08 | W7M               | W   | 0.809      | -            | -                | -                | -         |     7.95 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           63 |     1374 | 2024-06-07 | BESTIA            | L   | 0.802      | -            | -                | -                | -         |    -8.85 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           62 |     1450 | 2024-06-06 | Patins da Ferrari | L   | 0.794      | -            | -                | -                | -         |   -17.52 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           61 |     1547 | 2024-06-04 | paiN              | L   | 0.782      | -            | -                | -                | -         |    -2.48 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           60 |     1917 | 2024-05-21 | Case              | L   | 0.688      | -            | -                | -                | -         |   -12.00 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           59 |     1974 | 2024-05-19 | Case              | W   | 0.675      | -            | -                | -                | -         |     9.30 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           58 |     1999 | 2024-05-18 | RED Canids        | L   | 0.669      | -            | -                | -                | -         |    -6.06 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           57 |     2005 | 2024-05-18 | Galorys           | W   | 0.668      | -            | -                | -                | -         |     8.82 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           56 |     2038 | 2024-05-17 | FURIA Academy     | W   | 0.662      | -            | -                | -                | -         |     1.84 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           55 |     2042 | 2024-05-17 | Sharks            | W   | 0.661      | -            | -                | -                | -         |    12.17 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           54 |     2068 | 2024-05-16 | 9z                | L   | 0.655      | -            | -                | -                | -         |    -0.95 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           53 |     2073 | 2024-05-16 | Solid             | L   | 0.654      | -            | -                | -                | -         |   -12.24 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           52 |     2118 | 2024-05-15 | BESTIA            | L   | 0.649      | -            | -                | -                | -         |   -10.05 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           51 |     2119 | 2024-05-15 | BESTIA            | L   | 0.649      | -            | -                | -                | -         |   -10.64 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           50 |     2165 | 2024-05-14 | Solid             | L   | 0.643      | -            | -                | -                | -         |   -13.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           49 |     2168 | 2024-05-14 | Solid             | W   | 0.643      | 0.450        | -                | 0.807 (0.233)    | -         |     7.29 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           48 |     2183 | 2024-05-14 | KRÜ               | W   | 0.641      | -            | -                | -                | -         |     8.23 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           47 |     2194 | 2024-05-14 | Fluxo             | L   | 0.640      | -            | -                | -                | -         |    -6.87 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           46 |     2209 | 2024-05-13 | Solid             | W   | 0.635      | -            | -                | -                | -         |     7.57 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           45 |     2233 | 2024-05-12 | Intense           | W   | 0.628      | -            | -                | -                | -         |     4.43 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           44 |     2255 | 2024-05-11 | ex-Corinthians    | W   | 0.622      | -            | -                | -                | -         |     1.73 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           43 |     2311 | 2024-05-09 | inSanitY          | L   | 0.607      | -            | -                | -                | -         |   -10.87 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           42 |     2346 | 2024-05-07 | Imperial          | L   | 0.596      | -            | -                | -                | -         |    -2.95 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           41 |     2379 | 2024-05-05 | Case              | W   | 0.582      | 0.435        | -                | 0.778 (0.197)    | -         |     7.63 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           40 |     2437 | 2024-05-02 | Case              | L   | 0.562      | -            | -                | -                | -         |   -10.61 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           39 |     2438 | 2024-05-02 | Case              | W   | 0.562      | 0.450        | -                | 0.778 (0.197)    | -         |     7.21 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           38 |     2575 | 2024-04-26 | W7M               | W   | 0.522      | -            | -                | -                | -         |     5.05 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           37 |     2576 | 2024-04-26 | W7M               | W   | 0.522      | -            | -                | -                | -         |     5.25 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           36 |     2626 | 2024-04-24 | paiN              | L   | 0.509      | -            | -                | -                | -         |    -1.37 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           35 |     2627 | 2024-04-24 | paiN              | W   | 0.509      | 0.450        | 0.324 (0.074)    | 0.839 (0.192)    | -         |    14.80 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           34 |     2834 | 2024-04-17 | Fluxo             | L   | 0.462      | -            | -                | -                | -         |    -4.97 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           33 |     2840 | 2024-04-17 | W7M               | W   | 0.462      | -            | -                | -                | -         |     4.99 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           32 |     2872 | 2024-04-16 | SPORT             | W   | 0.456      | -            | -                | -                | -         |     3.01 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           31 |     2925 | 2024-04-13 | paiN              | L   | 0.435      | -            | -                | -                | -         |    -1.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           30 |     2946 | 2024-04-12 | Solid             | W   | 0.427      | -            | -                | -                | -         |     5.63 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           29 |     2993 | 2024-04-10 | Sharks            | L   | 0.416      | -            | -                | -                | -         |    -9.62 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           28 |     2997 | 2024-04-10 | Sharks            | W   | 0.416      | -            | -                | -                | -         |     3.51 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           27 |     3051 | 2024-04-09 | Fluxo             | L   | 0.409      | -            | -                | -                | -         |    -4.52 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           26 |     3056 | 2024-04-09 | Fluxo             | L   | 0.409      | -            | -                | -                | -         |    -4.67 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           25 |     3092 | 2024-04-08 | Fluxo             | L   | 0.402      | -            | -                | -                | -         |    -4.75 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           24 |     3145 | 2024-04-06 | Sharks            | L   | 0.388      | -            | -                | -                | -         |    -9.42 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           23 |     3148 | 2024-04-06 | LA RUGONETA       | W   | 0.387      | -            | -                | -                | -         |     1.01 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           22 |     3162 | 2024-04-05 | MIBR              | L   | 0.381      | -            | -                | -                | -         |    -0.97 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           21 |     3187 | 2024-04-04 | Imperial          | L   | 0.376      | -            | -                | -                | -         |    -1.93 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           20 |     3193 | 2024-04-04 | Imperial          | L   | 0.375      | -            | -                | -                | -         |    -1.96 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           19 |     3226 | 2024-04-03 | RED Canids        | L   | 0.369      | -            | -                | -                | -         |    -4.14 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           18 |     3229 | 2024-04-03 | RED Canids        | L   | 0.369      | -            | -                | -                | -         |    -4.26 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           17 |     3405 | 2024-03-26 | MIBR              | L   | 0.316      | -            | -                | -                | -         |    -0.89 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           16 |     3407 | 2024-03-26 | MIBR              | L   | 0.316      | -            | -                | -                | -         |    -0.90 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           15 |     3514 | 2024-03-18 | RED Canids        | L   | 0.261      | -            | -                | -                | -         |    -3.12 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           14 |     3539 | 2024-03-17 | Case              | W   | 0.254      | -            | -                | -                | -         |     3.23 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           13 |     3557 | 2024-03-16 | RED Canids        | L   | 0.248      | -            | -                | -                | -         |    -2.99 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           12 |     3572 | 2024-03-15 | 2GAME             | W   | 0.243      | -            | -                | -                | -         |     1.16 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           11 |     3573 | 2024-03-15 | 2GAME             | W   | 0.242      | -            | -                | -                | -         |     1.17 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           10 |     3577 | 2024-03-15 | MIBR Academy      | W   | 0.241      | -            | -                | -                | -         |     0.49 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            9 |     3632 | 2024-03-13 | Sharks            | L   | 0.229      | -            | -                | -                | -         |    -3.83 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            8 |     3649 | 2024-03-13 | Case              | W   | 0.227      | -            | -                | -                | -         |     2.99 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            7 |     3718 | 2024-03-10 | Solid             | W   | 0.208      | -            | -                | -                | -         |     2.43 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            6 |     3724 | 2024-03-10 | LA RUGONETA       | L   | 0.207      | -            | -                | -                | -         |    -6.05 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            5 |     3770 | 2024-03-08 | Galorys           | L   | 0.193      | -            | -                | -                | -         |    -3.91 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            4 |     3881 | 2024-03-04 | paiN              | L   | 0.167      | -            | -                | -                | -         |    -0.51 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            3 |     3897 | 2024-03-03 | RED Canids        | W   | 0.161      | -            | -                | -                | 1 (0.161) |     3.09 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            2 |     3921 | 2024-03-02 | Elevate           | W   | 0.155      | -            | -                | -                | 1 (0.155) |     2.50 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            1 |     3946 | 2024-03-01 | M80               | L   | 0.148      | -            | -                | -                | -         |    -1.01 | matios, naitte, ponter, Tuurtle, WOOD7 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,766.63)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-27 |      1.000 | $9,100.00      | $9,100.00       |
| 2024-07-22 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-07-14 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.861 | $5,000.00      | $4,305.09       |
| 2024-06-10 |      0.822 | $750.00        | $616.72         |
| 2024-06-09 |      0.815 | $1,500.00      | $1,222.64       |
| 2024-05-21 |      0.688 | $1,500.00      | $1,031.53       |
| 2024-05-19 |      0.674 | $2,000.00      | $1,348.70       |
| 2024-03-18 |      0.261 | $1,500.00      | $391.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
