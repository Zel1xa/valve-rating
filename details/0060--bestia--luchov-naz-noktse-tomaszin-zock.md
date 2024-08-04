### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1000.2<br />
<br />
Final Rank Value (1000.2) = Starting Rank Value (1022.8) + Head To Head Adjustments (-22.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.447[<sup>2</sup>](#table1)
- Opponent Network: 0.277[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.305<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1022.8
- 400 + ( ( 0.305 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1022.8


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
|          103 |       24 | 2024-08-03 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.39 | luchov, naz, Noktse, tomaszin, zock    |
|          102 |       31 | 2024-08-03 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.08 | luchov, naz, Noktse, tomaszin, zock    |
|          101 |       60 | 2024-08-02 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.64 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |       69 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -17.50 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |       90 | 2024-08-01 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.90 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |       94 | 2024-08-01 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.00 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |      107 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.82 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      189 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.49 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      195 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | 0 (0.000) |     7.51 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      203 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.20 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      230 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.97 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      259 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.80 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      341 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.14 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      349 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.01 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      418 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.26 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      423 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.55 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      458 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.124 (0.048)    | 0.724 (0.278)    | -         |    23.70 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      483 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.077 (0.030)    | 0.758 (0.291)    | -         |    23.61 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      540 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.72 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      551 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.90 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      591 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.20 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      593 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     1.12 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      605 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.31 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      652 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.44 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      657 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.18 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      667 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.81 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      721 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.832 (0.374)    | -         |    18.49 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      730 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.77 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      779 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.45 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      811 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.78 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      824 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -26.01 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      855 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.99 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      883 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.50 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      898 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     5.95 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      906 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.17 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1038 | 2024-06-15 | 9z                | L   | 0.866      | -            | -                | -                | -         |    -2.58 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1069 | 2024-06-14 | paiN              | L   | 0.860      | -            | -                | -                | -         |    -3.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1168 | 2024-06-10 | paiN              | L   | 0.835      | -            | -                | -                | -         |    -3.97 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1174 | 2024-06-10 | Bounty Hunters    | W   | 0.834      | -            | -                | -                | -         |     8.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1202 | 2024-06-09 | RED Canids        | W   | 0.829      | -            | -                | -                | -         |    17.66 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1230 | 2024-06-09 | Sharks            | L   | 0.826      | -            | -                | -                | -         |   -12.69 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1269 | 2024-06-08 | Solid             | W   | 0.821      | 0.371        | -                | 0.836 (0.254)    | -         |     7.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1284 | 2024-06-08 | Vikings KR        | L   | 0.820      | -            | -                | -                | -         |   -20.44 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1330 | 2024-06-07 | ODDIK             | W   | 0.814      | 0.450        | 0.099 (0.036)    | 0.832 (0.305)    | -         |     8.93 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1390 | 2024-06-06 | inSanitY          | L   | 0.808      | -            | -                | -                | -         |   -15.68 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1450 | 2024-06-05 | MIBR              | L   | 0.802      | -            | -                | -                | -         |    -2.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1502 | 2024-06-04 | Sharks            | L   | 0.795      | -            | -                | -                | -         |   -14.04 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1816 | 2024-05-22 | Case              | W   | 0.709      | 0.450        | -                | 0.805 (0.257)    | -         |     7.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1822 | 2024-05-22 | Case              | W   | 0.708      | 0.450        | -                | 0.805 (0.257)    | -         |     7.40 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1824 | 2024-05-22 | Fluxo             | W   | 0.708      | 0.450        | 0.124 (0.039)    | -                | -         |    12.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1827 | 2024-05-22 | Fluxo             | W   | 0.707      | 0.450        | 0.124 (0.039)    | -                | -         |    13.10 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1863 | 2024-05-21 | Smoke             | W   | 0.702      | -            | -                | -                | -         |     3.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1866 | 2024-05-21 | Smoke             | W   | 0.702      | -            | -                | -                | -         |     3.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1869 | 2024-05-21 | Imperial          | W   | 0.701      | 0.450        | 0.236 (0.075)    | -                | -         |    17.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1870 | 2024-05-21 | Imperial          | W   | 0.701      | 0.450        | 0.236 (0.075)    | -                | -         |    18.56 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1902 | 2024-05-20 | Corinthians       | W   | 0.695      | -            | -                | -                | -         |     1.33 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1904 | 2024-05-20 | 9z                | W   | 0.694      | 0.450        | 0.405 (0.127)    | -                | -         |    20.54 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1907 | 2024-05-20 | 9z                | L   | 0.694      | -            | -                | -                | -         |    -1.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     1989 | 2024-05-17 | Solid             | L   | 0.675      | -            | -                | -                | -         |   -13.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     1990 | 2024-05-17 | Solid             | W   | 0.675      | 0.450        | -                | 0.836 (0.254)    | -         |     8.07 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2074 | 2024-05-15 | ODDIK             | W   | 0.662      | 0.450        | -                | 0.832 (0.248)    | -         |    10.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2075 | 2024-05-15 | ODDIK             | W   | 0.661      | -            | -                | -                | -         |    10.87 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2085 | 2024-05-15 | Hype              | L   | 0.660      | -            | -                | -                | -         |   -12.38 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2136 | 2024-05-14 | Imperial          | L   | 0.655      | -            | -                | -                | -         |    -3.16 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2146 | 2024-05-14 | RED Canids        | L   | 0.653      | -            | -                | -                | -         |    -6.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2186 | 2024-05-12 | Solid             | W   | 0.641      | -            | -                | -                | -         |     7.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2193 | 2024-05-12 | O PLANO           | W   | 0.640      | -            | -                | -                | -         |     1.64 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2220 | 2024-05-11 | paiN              | L   | 0.633      | -            | -                | -                | -         |    -1.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2244 | 2024-05-10 | Imperial          | W   | 0.627      | 0.435        | 0.236 (0.064)    | -                | -         |    17.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2263 | 2024-05-09 | Sharks            | W   | 0.622      | -            | -                | -                | -         |    10.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2290 | 2024-05-08 | Vikings KR        | W   | 0.613      | -            | -                | -                | -         |     6.97 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2321 | 2024-05-06 | Sharks            | L   | 0.602      | -            | -                | -                | -         |    -8.43 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2560 | 2024-04-25 | RED Canids        | L   | 0.528      | -            | -                | -                | -         |    -5.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2562 | 2024-04-25 | RED Canids        | L   | 0.528      | -            | -                | -                | -         |    -5.22 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2827 | 2024-04-16 | O PLANO           | L   | 0.469      | -            | -                | -                | -         |   -13.60 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2924 | 2024-04-11 | Galorys           | L   | 0.433      | -            | -                | -                | -         |    -8.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3006 | 2024-04-09 | Galorys           | L   | 0.422      | -            | -                | -                | -         |    -8.16 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     3011 | 2024-04-09 | Galorys           | W   | 0.422      | -            | -                | -                | -         |     5.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3047 | 2024-04-08 | RED Canids        | L   | 0.415      | -            | -                | -                | -         |    -4.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3090 | 2024-04-07 | Sharks            | L   | 0.406      | -            | -                | -                | -         |    -9.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3098 | 2024-04-06 | Fluxo             | W   | 0.402      | -            | -                | -                | -         |     7.66 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3135 | 2024-04-04 | adalYamigos       | L   | 0.389      | -            | -                | -                | -         |   -10.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3144 | 2024-04-04 | adalYamigos       | W   | 0.388      | -            | -                | -                | -         |     1.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3152 | 2024-04-04 | Imperial          | L   | 0.387      | -            | -                | -                | -         |    -2.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3189 | 2024-04-03 | Fluxo             | L   | 0.381      | -            | -                | -                | -         |    -5.13 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3225 | 2024-04-02 | Sharks            | W   | 0.375      | -            | -                | -                | -         |     2.40 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3230 | 2024-04-02 | Fluxo             | L   | 0.374      | -            | -                | -                | -         |    -5.14 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3319 | 2024-03-27 | W7M               | L   | 0.335      | -            | -                | -                | -         |    -7.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3323 | 2024-03-27 | W7M               | W   | 0.335      | -            | -                | -                | -         |     2.77 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3634 | 2024-03-12 | RED Canids        | L   | 0.233      | -            | -                | -                | -         |    -3.03 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3644 | 2024-03-11 | FURIA Academy     | W   | 0.229      | -            | -                | -                | -         |     0.42 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3667 | 2024-03-10 | adalYamigos       | L   | 0.222      | -            | -                | -                | -         |    -6.37 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3715 | 2024-03-08 | FURIA Academy     | W   | 0.208      | -            | -                | -                | -         |     0.36 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3880 | 2024-03-02 | Wildcard          | L   | 0.167      | -            | -                | -                | -         |    -3.66 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3897 | 2024-03-01 | Liquid            | L   | 0.162      | -            | -                | -                | -         |    -0.20 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     4021 | 2024-02-24 | Imperial          | L   | 0.120      | -            | -                | -                | -         |    -0.78 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4040 | 2024-02-23 | 9z                | L   | 0.114      | -            | -                | -                | -         |    -0.18 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4050 | 2024-02-22 | Imperial          | W   | 0.109      | -            | -                | -                | -         |     2.73 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4057 | 2024-02-22 | 9z                | L   | 0.108      | -            | -                | -                | -         |    -0.17 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4079 | 2024-02-21 | W7M               | W   | 0.100      | -            | -                | -                | -         |     0.85 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4156 | 2024-02-18 | FURIA Academy     | W   | 0.080      | -            | -                | -                | -         |     0.14 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4201 | 2024-02-16 | Case              | L   | 0.068      | -            | -                | -                | -         |    -1.32 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4320 | 2024-02-12 | FURIA Academy     | W   | 0.042      | -            | -                | -                | -         |     0.07 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,902.19)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.875 | $1,500.00      | $1,313.02       |
| 2024-06-10 |      0.835 | $4,000.00      | $3,340.19       |
| 2024-06-09 |      0.828 | $2,000.00      | $1,655.69       |
| 2024-05-12 |      0.641 | $5,000.00      | $3,204.98       |
| 2024-02-25 |      0.128 | $5,000.00      | $638.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
