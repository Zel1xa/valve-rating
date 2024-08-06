### Roster Details<br />
Team Name: ODDIK<br />
Roster: ksloks, matios, naitte, togs, WOOD7<br />
Global Rank: [44](../standings_global.md)<br />
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
|          108 |       61 | 2024-08-03 | RED Canids        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.21 | ksloks, matios, naitte, togs, WOOD7    |
|          107 |       69 | 2024-08-03 | BESTIA            | W   | 1.000      | 0.143        | 0.096 (0.014)    | -                | 0 (0.000) |    12.08 | ksloks, matios, naitte, togs, WOOD7    |
|          106 |       75 | 2024-08-03 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -4.09 | ksloks, matios, naitte, togs, WOOD7    |
|          105 |       99 | 2024-08-02 | MIBR              | W   | 1.000      | 0.143        | 0.208 (0.030)    | -                | 0 (0.000) |    25.96 | ksloks, matios, naitte, togs, WOOD7    |
|          104 |      130 | 2024-08-01 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.31 | ksloks, matios, naitte, togs, WOOD7    |
|          103 |      140 | 2024-08-01 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.01 | ksloks, matios, naitte, togs, WOOD7    |
|          102 |      183 | 2024-07-31 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -4.13 | ksloks, matios, naitte, togs, WOOD7    |
|          101 |      190 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.49 | ksloks, matios, naitte, togs, WOOD7    |
|          100 |      196 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.78 | ksloks, matios, naitte, togs, WOOD7    |
|           99 |      230 | 2024-07-30 | inSanitY          | W   | 1.000      | 0.371        | 0.048 (0.018)    | -                | 0 (0.000) |    12.78 | ksloks, matios, naitte, togs, WOOD7    |
|           98 |      242 | 2024-07-30 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.07 | lineko, matios, naitte, togs, WOOD7    |
|           97 |      330 | 2024-07-27 | Galorys           | W   | 1.000      | 0.365        | -                | 0.530 (0.193)    | 0 (0.000) |     7.48 | ksloks, matios, naitte, togs, WOOD7    |
|           96 |      350 | 2024-07-26 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.61 | ksloks, matios, naitte, togs, WOOD7    |
|           95 |      356 | 2024-07-26 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |    22.47 | ksloks, matios, naitte, togs, WOOD7    |
|           94 |      362 | 2024-07-26 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     6.56 | ksloks, matios, naitte, togs, WOOD7    |
|           93 |      382 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.89 | ksloks, matios, naitte, togs, WOOD7    |
|           92 |      390 | 2024-07-25 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | -         |     0.90 | ksloks, matios, naitte, togs, WOOD7    |
|           91 |      425 | 2024-07-24 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -9.72 | ksloks, matios, naitte, togs, WOOD7    |
|           90 |      455 | 2024-07-23 | Sharks            | W   | 1.000      | -            | -                | -                | -         |    14.05 | ksloks, matios, naitte, togs, WOOD7    |
|           89 |      494 | 2024-07-22 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.05 | ksloks, matios, naitte, togs, WOOD7    |
|           88 |      502 | 2024-07-22 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     6.36 | ksloks, matios, naitte, togs, WOOD7    |
|           87 |      546 | 2024-07-20 | Hype              | W   | 1.000      | -            | -                | -                | -         |    10.37 | ksloks, matios, naitte, togs, WOOD7    |
|           86 |      557 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.24 | ksloks, matios, naitte, togs, WOOD7    |
|           85 |      628 | 2024-07-18 | Case              | L   | 1.000      | -            | -                | -                | -         |   -22.27 | ksloks, matios, naitte, togs, WOOD7    |
|           84 |      639 | 2024-07-18 | Imperial          | W   | 1.000      | 0.143        | 0.233 (0.033)    | -                | -         |    22.43 | ksloks, matios, naitte, togs, WOOD7    |
|           83 |      643 | 2024-07-18 | BESTIA            | W   | 1.000      | 0.143        | 0.096 (0.014)    | -                | -         |    14.28 | ksloks, matios, naitte, togs, WOOD7    |
|           82 |      687 | 2024-07-17 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -17.45 | ksloks, matios, naitte, togs, WOOD7    |
|           81 |      698 | 2024-07-17 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -19.02 | ksloks, matios, naitte, togs, WOOD7    |
|           80 |      759 | 2024-07-16 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |   -18.52 | ksloks, matios, naitte, togs, WOOD7    |
|           79 |      768 | 2024-07-16 | BESTIA            | W   | 1.000      | 0.333        | 0.096 (0.032)    | 0.776 (0.259)    | -         |    12.74 | ksloks, matios, naitte, togs, WOOD7    |
|           78 |      808 | 2024-07-15 | Case              | W   | 1.000      | 0.333        | -                | 0.778 (0.259)    | -         |    10.20 | ksloks, matios, naitte, togs, WOOD7    |
|           77 |      844 | 2024-07-14 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.620 (0.230)    | -         |    17.27 | ksloks, matios, naitte, togs, WOOD7    |
|           76 |      855 | 2024-07-13 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.13 | ksloks, matios, naitte, togs, WOOD7    |
|           75 |      856 | 2024-07-13 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |     9.39 | ksloks, matios, naitte, togs, WOOD7    |
|           74 |      876 | 2024-07-11 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.620 (0.230)    | -         |    18.30 | ksloks, matios, naitte, togs, WOOD7    |
|           73 |      895 | 2024-07-10 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.59 | ksloks, matios, naitte, togs, WOOD7    |
|           72 |      904 | 2024-07-10 | Hype              | W   | 1.000      | -            | -                | -                | -         |    12.84 | ksloks, matios, naitte, togs, WOOD7    |
|           71 |      945 | 2024-07-08 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | -         |     4.86 | ksloks, matios, naitte, togs, WOOD7    |
|           70 |      959 | 2024-07-06 | W7M               | W   | 0.995      | -            | -                | -                | -         |     8.21 | ksloks, matios, naitte, togs, WOOD7    |
|           69 |     1072 | 2024-06-15 | paiN              | L   | 0.854      | -            | -                | -                | -         |    -2.63 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           68 |     1141 | 2024-06-13 | Hype              | W   | 0.841      | -            | -                | -                | -         |    11.56 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           67 |     1211 | 2024-06-10 | W7M               | W   | 0.822      | -            | -                | -                | -         |     7.84 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           66 |     1242 | 2024-06-09 | Galorys           | W   | 0.816      | 0.450        | 0.030 (0.011)    | 0.530 (0.195)    | -         |    10.47 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           65 |     1262 | 2024-06-09 | Imperial          | L   | 0.814      | -            | -                | -                | -         |    -3.09 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           64 |     1301 | 2024-06-08 | W7M               | W   | 0.810      | -            | -                | -                | -         |     7.95 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           63 |     1368 | 2024-06-07 | BESTIA            | L   | 0.802      | -            | -                | -                | -         |    -8.85 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           62 |     1444 | 2024-06-06 | Patins da Ferrari | L   | 0.795      | -            | -                | -                | -         |   -17.53 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           61 |     1541 | 2024-06-04 | paiN              | L   | 0.783      | -            | -                | -                | -         |    -2.48 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           60 |     1911 | 2024-05-21 | Case              | L   | 0.688      | -            | -                | -                | -         |   -12.01 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           59 |     1968 | 2024-05-19 | Case              | W   | 0.676      | -            | -                | -                | -         |     9.31 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           58 |     1993 | 2024-05-18 | RED Canids        | L   | 0.669      | -            | -                | -                | -         |    -6.06 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           57 |     1999 | 2024-05-18 | Galorys           | W   | 0.668      | -            | -                | -                | -         |     8.83 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           56 |     2032 | 2024-05-17 | FURIA Academy     | W   | 0.662      | -            | -                | -                | -         |     1.84 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           55 |     2036 | 2024-05-17 | Sharks            | W   | 0.662      | -            | -                | -                | -         |    12.18 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           54 |     2062 | 2024-05-16 | 9z                | L   | 0.656      | -            | -                | -                | -         |    -0.95 | lineko, matios, naitte, Tuurtle, WOOD7 |
|           53 |     2067 | 2024-05-16 | Solid             | L   | 0.655      | -            | -                | -                | -         |   -12.25 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           52 |     2112 | 2024-05-15 | BESTIA            | L   | 0.649      | -            | -                | -                | -         |   -10.06 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           51 |     2113 | 2024-05-15 | BESTIA            | L   | 0.649      | -            | -                | -                | -         |   -10.65 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           50 |     2159 | 2024-05-14 | Solid             | L   | 0.643      | -            | -                | -                | -         |   -13.01 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           49 |     2162 | 2024-05-14 | Solid             | W   | 0.643      | 0.450        | -                | 0.807 (0.234)    | -         |     7.29 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           48 |     2177 | 2024-05-14 | KRÜ               | W   | 0.642      | -            | -                | -                | -         |     8.24 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           47 |     2188 | 2024-05-14 | Fluxo             | L   | 0.641      | -            | -                | -                | -         |    -6.88 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           46 |     2203 | 2024-05-13 | Solid             | W   | 0.636      | -            | -                | -                | -         |     7.57 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           45 |     2227 | 2024-05-12 | Intense           | W   | 0.629      | -            | -                | -                | -         |     4.43 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           44 |     2249 | 2024-05-11 | ex-Corinthians    | W   | 0.622      | -            | -                | -                | -         |     1.73 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           43 |     2305 | 2024-05-09 | inSanitY          | L   | 0.608      | -            | -                | -                | -         |   -10.88 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           42 |     2340 | 2024-05-07 | Imperial          | L   | 0.596      | -            | -                | -                | -         |    -2.95 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           41 |     2373 | 2024-05-05 | Case              | W   | 0.583      | 0.435        | -                | 0.778 (0.197)    | -         |     7.63 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           40 |     2431 | 2024-05-02 | Case              | L   | 0.563      | -            | -                | -                | -         |   -10.62 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           39 |     2432 | 2024-05-02 | Case              | W   | 0.563      | 0.450        | -                | 0.778 (0.197)    | -         |     7.22 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           38 |     2569 | 2024-04-26 | W7M               | W   | 0.523      | -            | -                | -                | -         |     5.06 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           37 |     2570 | 2024-04-26 | W7M               | W   | 0.522      | -            | -                | -                | -         |     5.26 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           36 |     2620 | 2024-04-24 | paiN              | L   | 0.510      | -            | -                | -                | -         |    -1.37 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           35 |     2621 | 2024-04-24 | paiN              | W   | 0.509      | 0.450        | 0.324 (0.074)    | 0.838 (0.192)    | -         |    14.82 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           34 |     2828 | 2024-04-17 | Fluxo             | L   | 0.463      | -            | -                | -                | -         |    -4.97 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           33 |     2834 | 2024-04-17 | W7M               | W   | 0.462      | -            | -                | -                | -         |     5.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           32 |     2866 | 2024-04-16 | SPORT             | W   | 0.457      | -            | -                | -                | -         |     3.01 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           31 |     2919 | 2024-04-13 | paiN              | L   | 0.435      | -            | -                | -                | -         |    -1.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           30 |     2940 | 2024-04-12 | Solid             | W   | 0.427      | -            | -                | -                | -         |     5.63 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           29 |     2987 | 2024-04-10 | Sharks            | L   | 0.417      | -            | -                | -                | -         |    -9.63 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           28 |     2991 | 2024-04-10 | Sharks            | W   | 0.416      | -            | -                | -                | -         |     3.51 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           27 |     3045 | 2024-04-09 | Fluxo             | L   | 0.410      | -            | -                | -                | -         |    -4.53 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           26 |     3050 | 2024-04-09 | Fluxo             | L   | 0.409      | -            | -                | -                | -         |    -4.68 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           25 |     3086 | 2024-04-08 | Fluxo             | L   | 0.402      | -            | -                | -                | -         |    -4.75 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           24 |     3139 | 2024-04-06 | Sharks            | L   | 0.388      | -            | -                | -                | -         |    -9.43 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           23 |     3142 | 2024-04-06 | LA RUGONETA       | W   | 0.387      | -            | -                | -                | -         |     1.01 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           22 |     3156 | 2024-04-05 | MIBR              | L   | 0.382      | -            | -                | -                | -         |    -0.97 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           21 |     3181 | 2024-04-04 | Imperial          | L   | 0.376      | -            | -                | -                | -         |    -1.93 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           20 |     3187 | 2024-04-04 | Imperial          | L   | 0.376      | -            | -                | -                | -         |    -1.96 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           19 |     3220 | 2024-04-03 | RED Canids        | L   | 0.370      | -            | -                | -                | -         |    -4.14 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           18 |     3223 | 2024-04-03 | RED Canids        | L   | 0.369      | -            | -                | -                | -         |    -4.27 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           17 |     3399 | 2024-03-26 | MIBR              | L   | 0.317      | -            | -                | -                | -         |    -0.90 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           16 |     3401 | 2024-03-26 | MIBR              | L   | 0.316      | -            | -                | -                | -         |    -0.90 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           15 |     3508 | 2024-03-18 | RED Canids        | L   | 0.262      | -            | -                | -                | -         |    -3.12 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           14 |     3533 | 2024-03-17 | Case              | W   | 0.255      | -            | -                | -                | -         |     3.23 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           13 |     3551 | 2024-03-16 | RED Canids        | L   | 0.249      | -            | -                | -                | -         |    -3.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           12 |     3566 | 2024-03-15 | 2GAME             | W   | 0.243      | -            | -                | -                | -         |     1.16 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           11 |     3567 | 2024-03-15 | 2GAME             | W   | 0.243      | -            | -                | -                | -         |     1.17 | matios, naitte, ponter, Tuurtle, WOOD7 |
|           10 |     3571 | 2024-03-15 | MIBR Academy      | W   | 0.242      | -            | -                | -                | -         |     0.49 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            9 |     3626 | 2024-03-13 | Sharks            | L   | 0.229      | -            | -                | -                | -         |    -3.83 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            8 |     3643 | 2024-03-13 | Case              | W   | 0.228      | -            | -                | -                | -         |     3.00 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            7 |     3712 | 2024-03-10 | Solid             | W   | 0.208      | -            | -                | -                | -         |     2.43 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            6 |     3718 | 2024-03-10 | LA RUGONETA       | L   | 0.207      | -            | -                | -                | -         |    -6.07 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            5 |     3764 | 2024-03-08 | Galorys           | L   | 0.194      | -            | -                | -                | -         |    -3.93 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            4 |     3875 | 2024-03-04 | paiN              | L   | 0.168      | -            | -                | -                | -         |    -0.51 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            3 |     3891 | 2024-03-03 | RED Canids        | W   | 0.162      | -            | -                | -                | 1 (0.162) |     3.10 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            2 |     3915 | 2024-03-02 | Elevate           | W   | 0.155      | -            | -                | -                | 1 (0.155) |     2.51 | matios, naitte, ponter, Tuurtle, WOOD7 |
|            1 |     3940 | 2024-03-01 | M80               | L   | 0.149      | -            | -                | -                | -         |    -1.01 | matios, naitte, ponter, Tuurtle, WOOD7 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,773.43)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-27 |      1.000 | $9,100.00      | $9,100.00       |
| 2024-07-22 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-07-14 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.862 | $5,000.00      | $4,307.87       |
| 2024-06-10 |      0.823 | $750.00        | $617.14         |
| 2024-06-09 |      0.816 | $1,500.00      | $1,223.47       |
| 2024-05-21 |      0.688 | $1,500.00      | $1,032.36       |
| 2024-05-19 |      0.675 | $2,000.00      | $1,349.81       |
| 2024-03-18 |      0.262 | $1,500.00      | $392.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
