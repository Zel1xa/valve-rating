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
|          103 |       23 | 2024-08-03 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.39 | luchov, naz, Noktse, tomaszin, zock    |
|          102 |       30 | 2024-08-03 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.08 | luchov, naz, Noktse, tomaszin, zock    |
|          101 |       59 | 2024-08-02 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.64 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |       68 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -17.50 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |       89 | 2024-08-01 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.90 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |       93 | 2024-08-01 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.00 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |      106 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.82 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      188 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.49 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      194 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | 0 (0.000) |     7.51 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      202 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.20 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      229 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.97 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      258 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.80 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      340 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.14 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      348 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.01 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      417 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.26 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      422 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.55 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      457 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.124 (0.048)    | 0.724 (0.278)    | -         |    23.70 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      482 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.077 (0.030)    | 0.758 (0.291)    | -         |    23.61 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      539 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.71 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      550 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.90 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      590 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.20 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      592 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     1.12 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      604 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.31 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      651 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.44 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      656 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.18 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      666 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.81 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      720 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.831 (0.374)    | -         |    18.49 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      729 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.77 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      778 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.45 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      810 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.78 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      823 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -26.01 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      854 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.99 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      882 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.50 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      897 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     5.95 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      905 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.17 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1037 | 2024-06-15 | 9z                | L   | 0.866      | -            | -                | -                | -         |    -2.58 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1068 | 2024-06-14 | paiN              | L   | 0.860      | -            | -                | -                | -         |    -3.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1167 | 2024-06-10 | paiN              | L   | 0.835      | -            | -                | -                | -         |    -3.97 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1173 | 2024-06-10 | Bounty Hunters    | W   | 0.834      | -            | -                | -                | -         |     8.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1201 | 2024-06-09 | RED Canids        | W   | 0.829      | -            | -                | -                | -         |    17.66 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1229 | 2024-06-09 | Sharks            | L   | 0.826      | -            | -                | -                | -         |   -12.69 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1268 | 2024-06-08 | Solid             | W   | 0.821      | 0.371        | -                | 0.836 (0.254)    | -         |     7.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1283 | 2024-06-08 | Vikings KR        | L   | 0.821      | -            | -                | -                | -         |   -20.45 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1329 | 2024-06-07 | ODDIK             | W   | 0.815      | 0.450        | 0.099 (0.036)    | 0.831 (0.305)    | -         |     8.94 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1389 | 2024-06-06 | inSanitY          | L   | 0.808      | -            | -                | -                | -         |   -15.68 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1449 | 2024-06-05 | MIBR              | L   | 0.802      | -            | -                | -                | -         |    -2.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1501 | 2024-06-04 | Sharks            | L   | 0.795      | -            | -                | -                | -         |   -14.05 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1815 | 2024-05-22 | Case              | W   | 0.709      | 0.450        | -                | 0.805 (0.257)    | -         |     7.01 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1821 | 2024-05-22 | Case              | W   | 0.709      | 0.450        | -                | 0.805 (0.257)    | -         |     7.40 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1823 | 2024-05-22 | Fluxo             | W   | 0.708      | 0.450        | 0.124 (0.040)    | -                | -         |    12.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1826 | 2024-05-22 | Fluxo             | W   | 0.708      | 0.450        | 0.124 (0.039)    | -                | -         |    13.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1862 | 2024-05-21 | Smoke             | W   | 0.702      | -            | -                | -                | -         |     3.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1865 | 2024-05-21 | Smoke             | W   | 0.702      | -            | -                | -                | -         |     3.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1868 | 2024-05-21 | Imperial          | W   | 0.701      | 0.450        | 0.236 (0.075)    | -                | -         |    17.93 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1869 | 2024-05-21 | Imperial          | W   | 0.701      | 0.450        | 0.236 (0.075)    | -                | -         |    18.57 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1901 | 2024-05-20 | Corinthians       | W   | 0.695      | -            | -                | -                | -         |     1.33 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1903 | 2024-05-20 | 9z                | W   | 0.695      | 0.450        | 0.405 (0.127)    | -                | -         |    20.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1906 | 2024-05-20 | 9z                | L   | 0.694      | -            | -                | -                | -         |    -1.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     1988 | 2024-05-17 | Solid             | L   | 0.676      | -            | -                | -                | -         |   -13.26 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     1989 | 2024-05-17 | Solid             | W   | 0.675      | 0.450        | -                | 0.836 (0.254)    | -         |     8.08 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2073 | 2024-05-15 | ODDIK             | W   | 0.662      | 0.450        | -                | 0.831 (0.248)    | -         |    10.26 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2074 | 2024-05-15 | ODDIK             | W   | 0.662      | -            | -                | -                | -         |    10.88 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2084 | 2024-05-15 | Hype              | L   | 0.660      | -            | -                | -                | -         |   -12.38 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2135 | 2024-05-14 | Imperial          | L   | 0.655      | -            | -                | -                | -         |    -3.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2145 | 2024-05-14 | RED Canids        | L   | 0.654      | -            | -                | -                | -         |    -7.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2185 | 2024-05-12 | Solid             | W   | 0.642      | -            | -                | -                | -         |     7.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2192 | 2024-05-12 | O PLANO           | W   | 0.640      | -            | -                | -                | -         |     1.64 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2219 | 2024-05-11 | paiN              | L   | 0.634      | -            | -                | -                | -         |    -1.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2243 | 2024-05-10 | Imperial          | W   | 0.627      | 0.435        | 0.236 (0.064)    | -                | -         |    17.01 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2262 | 2024-05-09 | Sharks            | W   | 0.622      | -            | -                | -                | -         |    10.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2289 | 2024-05-08 | Vikings KR        | W   | 0.614      | -            | -                | -                | -         |     6.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2320 | 2024-05-06 | Sharks            | L   | 0.602      | -            | -                | -                | -         |    -8.44 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2559 | 2024-04-25 | RED Canids        | L   | 0.529      | -            | -                | -                | -         |    -5.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2561 | 2024-04-25 | RED Canids        | L   | 0.529      | -            | -                | -                | -         |    -5.22 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2826 | 2024-04-16 | O PLANO           | L   | 0.469      | -            | -                | -                | -         |   -13.61 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2923 | 2024-04-11 | Galorys           | L   | 0.434      | -            | -                | -                | -         |    -8.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3005 | 2024-04-09 | Galorys           | L   | 0.422      | -            | -                | -                | -         |    -8.17 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     3010 | 2024-04-09 | Galorys           | W   | 0.422      | -            | -                | -                | -         |     5.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3046 | 2024-04-08 | RED Canids        | L   | 0.415      | -            | -                | -                | -         |    -4.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3089 | 2024-04-07 | Sharks            | L   | 0.406      | -            | -                | -                | -         |    -9.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3097 | 2024-04-06 | Fluxo             | W   | 0.402      | -            | -                | -                | -         |     7.67 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3134 | 2024-04-04 | adalYamigos       | L   | 0.389      | -            | -                | -                | -         |   -11.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3143 | 2024-04-04 | adalYamigos       | W   | 0.389      | -            | -                | -                | -         |     1.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3151 | 2024-04-04 | Imperial          | L   | 0.388      | -            | -                | -                | -         |    -2.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3188 | 2024-04-03 | Fluxo             | L   | 0.381      | -            | -                | -                | -         |    -5.13 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3224 | 2024-04-02 | Sharks            | W   | 0.376      | -            | -                | -                | -         |     2.40 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3229 | 2024-04-02 | Fluxo             | L   | 0.374      | -            | -                | -                | -         |    -5.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3318 | 2024-03-27 | W7M               | L   | 0.336      | -            | -                | -                | -         |    -7.82 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3322 | 2024-03-27 | W7M               | W   | 0.335      | -            | -                | -                | -         |     2.78 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3633 | 2024-03-12 | RED Canids        | L   | 0.234      | -            | -                | -                | -         |    -3.04 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3643 | 2024-03-11 | FURIA Academy     | W   | 0.229      | -            | -                | -                | -         |     0.42 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3666 | 2024-03-10 | adalYamigos       | L   | 0.222      | -            | -                | -                | -         |    -6.38 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3714 | 2024-03-08 | FURIA Academy     | W   | 0.209      | -            | -                | -                | -         |     0.36 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3879 | 2024-03-02 | Wildcard          | L   | 0.167      | -            | -                | -                | -         |    -3.67 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3896 | 2024-03-01 | Liquid            | L   | 0.162      | -            | -                | -                | -         |    -0.20 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     4020 | 2024-02-24 | Imperial          | L   | 0.120      | -            | -                | -                | -         |    -0.78 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4039 | 2024-02-23 | 9z                | L   | 0.114      | -            | -                | -                | -         |    -0.18 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4049 | 2024-02-22 | Imperial          | W   | 0.109      | -            | -                | -                | -         |     2.74 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4056 | 2024-02-22 | 9z                | L   | 0.108      | -            | -                | -                | -         |    -0.17 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4078 | 2024-02-21 | W7M               | W   | 0.100      | -            | -                | -                | -         |     0.85 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4155 | 2024-02-18 | FURIA Academy     | W   | 0.081      | -            | -                | -                | -         |     0.14 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4200 | 2024-02-16 | Case              | L   | 0.069      | -            | -                | -                | -         |    -1.32 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4319 | 2024-02-12 | FURIA Academy     | W   | 0.042      | -            | -                | -                | -         |     0.07 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,907.45)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.876 | $1,500.00      | $1,313.47       |
| 2024-06-10 |      0.835 | $4,000.00      | $3,341.39       |
| 2024-06-09 |      0.828 | $2,000.00      | $1,656.30       |
| 2024-05-12 |      0.641 | $5,000.00      | $3,206.48       |
| 2024-02-25 |      0.128 | $5,000.00      | $639.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
