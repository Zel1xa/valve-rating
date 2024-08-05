### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1000.0<br />
<br />
Final Rank Value (1000.0) = Starting Rank Value (1022.8) + Head To Head Adjustments (-22.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.446[<sup>2</sup>](#table1)
- Opponent Network: 0.276[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.304<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1022.8
- 400 + ( ( 0.304 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1022.8


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
|          103 |       28 | 2024-08-03 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.40 | luchov, naz, Noktse, tomaszin, zock    |
|          102 |       35 | 2024-08-03 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.08 | luchov, naz, Noktse, tomaszin, zock    |
|          101 |       64 | 2024-08-02 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.65 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |       73 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -17.49 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |       94 | 2024-08-01 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.90 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |       98 | 2024-08-01 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.00 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |      111 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.83 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      193 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.48 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      199 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | 0 (0.000) |     7.51 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      207 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.21 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      234 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.98 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      263 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.81 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      345 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.14 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      353 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.02 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      422 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.26 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      427 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.56 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      462 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.124 (0.048)    | 0.725 (0.279)    | -         |    23.69 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      487 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.077 (0.030)    | 0.758 (0.291)    | -         |    23.61 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      544 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.72 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      555 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.89 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      595 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.22 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      597 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     1.12 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      609 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.30 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      656 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.45 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      661 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.19 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      671 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.82 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      725 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.833 (0.375)    | -         |    18.49 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      734 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.77 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      783 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.46 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      815 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.78 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      828 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -26.00 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      859 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.99 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      887 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.51 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      902 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     5.95 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      910 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.16 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1042 | 2024-06-15 | 9z                | L   | 0.863      | -            | -                | -                | -         |    -2.57 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1073 | 2024-06-14 | paiN              | L   | 0.858      | -            | -                | -                | -         |    -3.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1172 | 2024-06-10 | paiN              | L   | 0.833      | -            | -                | -                | -         |    -3.96 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1178 | 2024-06-10 | Bounty Hunters    | W   | 0.831      | -            | -                | -                | -         |     8.88 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1206 | 2024-06-09 | RED Canids        | W   | 0.826      | -            | -                | -                | -         |    17.59 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1234 | 2024-06-09 | Sharks            | L   | 0.824      | -            | -                | -                | -         |   -12.66 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1273 | 2024-06-08 | Solid             | W   | 0.819      | 0.371        | -                | 0.836 (0.254)    | -         |     7.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1288 | 2024-06-08 | Vikings KR        | L   | 0.818      | -            | -                | -                | -         |   -20.38 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1334 | 2024-06-07 | ODDIK             | W   | 0.812      | 0.450        | 0.099 (0.036)    | 0.833 (0.304)    | -         |     8.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1394 | 2024-06-06 | inSanitY          | L   | 0.805      | -            | -                | -                | -         |   -15.63 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1454 | 2024-06-05 | MIBR              | L   | 0.799      | -            | -                | -                | -         |    -2.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1506 | 2024-06-04 | Sharks            | L   | 0.793      | -            | -                | -                | -         |   -14.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1820 | 2024-05-22 | Case              | W   | 0.706      | 0.450        | -                | 0.806 (0.256)    | -         |     6.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1826 | 2024-05-22 | Case              | W   | 0.706      | 0.450        | -                | 0.806 (0.256)    | -         |     7.38 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1828 | 2024-05-22 | Fluxo             | W   | 0.705      | 0.450        | 0.124 (0.039)    | -                | -         |    12.28 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1831 | 2024-05-22 | Fluxo             | W   | 0.705      | 0.450        | 0.124 (0.039)    | -                | -         |    13.05 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1867 | 2024-05-21 | Smoke             | W   | 0.699      | -            | -                | -                | -         |     3.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1870 | 2024-05-21 | Smoke             | W   | 0.699      | -            | -                | -                | -         |     3.20 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1873 | 2024-05-21 | Imperial          | W   | 0.699      | 0.450        | 0.236 (0.074)    | -                | -         |    17.84 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1874 | 2024-05-21 | Imperial          | W   | 0.698      | 0.450        | 0.236 (0.074)    | -                | -         |    18.48 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1906 | 2024-05-20 | Corinthians       | W   | 0.693      | -            | -                | -                | -         |     1.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1908 | 2024-05-20 | 9z                | W   | 0.692      | 0.450        | 0.405 (0.126)    | -                | -         |    20.46 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1911 | 2024-05-20 | 9z                | L   | 0.692      | -            | -                | -                | -         |    -1.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     1993 | 2024-05-17 | Solid             | L   | 0.673      | -            | -                | -                | -         |   -13.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     1994 | 2024-05-17 | Solid             | W   | 0.673      | 0.450        | -                | 0.836 (0.253)    | -         |     8.04 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2078 | 2024-05-15 | ODDIK             | W   | 0.659      | 0.450        | -                | 0.833 (0.247)    | -         |    10.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2079 | 2024-05-15 | ODDIK             | W   | 0.659      | -            | -                | -                | -         |    10.82 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2089 | 2024-05-15 | Hype              | L   | 0.658      | -            | -                | -                | -         |   -12.34 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2140 | 2024-05-14 | Imperial          | L   | 0.652      | -            | -                | -                | -         |    -3.17 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2150 | 2024-05-14 | RED Canids        | L   | 0.651      | -            | -                | -                | -         |    -6.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2190 | 2024-05-12 | Solid             | W   | 0.639      | -            | -                | -                | -         |     7.95 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2197 | 2024-05-12 | O PLANO           | W   | 0.638      | -            | -                | -                | -         |     1.63 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2224 | 2024-05-11 | paiN              | L   | 0.631      | -            | -                | -                | -         |    -1.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2248 | 2024-05-10 | Imperial          | W   | 0.625      | 0.435        | 0.236 (0.064)    | -                | -         |    16.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2267 | 2024-05-09 | Sharks            | W   | 0.619      | -            | -                | -                | -         |    10.75 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2294 | 2024-05-08 | Vikings KR        | W   | 0.611      | -            | -                | -                | -         |     6.94 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2325 | 2024-05-06 | Sharks            | L   | 0.599      | -            | -                | -                | -         |    -8.41 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2564 | 2024-04-25 | RED Canids        | L   | 0.526      | -            | -                | -                | -         |    -5.01 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2566 | 2024-04-25 | RED Canids        | L   | 0.526      | -            | -                | -                | -         |    -5.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2831 | 2024-04-16 | O PLANO           | L   | 0.466      | -            | -                | -                | -         |   -13.53 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2928 | 2024-04-11 | Galorys           | L   | 0.431      | -            | -                | -                | -         |    -8.07 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3010 | 2024-04-09 | Galorys           | L   | 0.419      | -            | -                | -                | -         |    -8.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     3015 | 2024-04-09 | Galorys           | W   | 0.419      | -            | -                | -                | -         |     5.17 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3051 | 2024-04-08 | RED Canids        | L   | 0.412      | -            | -                | -                | -         |    -4.68 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3094 | 2024-04-07 | Sharks            | L   | 0.404      | -            | -                | -                | -         |    -9.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3102 | 2024-04-06 | Fluxo             | W   | 0.399      | -            | -                | -                | -         |     7.61 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3139 | 2024-04-04 | adalYamigos       | L   | 0.386      | -            | -                | -                | -         |   -10.93 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3148 | 2024-04-04 | adalYamigos       | W   | 0.386      | -            | -                | -                | -         |     1.23 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3156 | 2024-04-04 | Imperial          | L   | 0.385      | -            | -                | -                | -         |    -2.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3193 | 2024-04-03 | Fluxo             | L   | 0.378      | -            | -                | -                | -         |    -5.10 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3229 | 2024-04-02 | Sharks            | W   | 0.373      | -            | -                | -                | -         |     2.38 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3234 | 2024-04-02 | Fluxo             | L   | 0.372      | -            | -                | -                | -         |    -5.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3323 | 2024-03-27 | W7M               | L   | 0.333      | -            | -                | -                | -         |    -7.75 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3327 | 2024-03-27 | W7M               | W   | 0.333      | -            | -                | -                | -         |     2.76 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3638 | 2024-03-12 | RED Canids        | L   | 0.231      | -            | -                | -                | -         |    -3.01 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3648 | 2024-03-11 | FURIA Academy     | W   | 0.226      | -            | -                | -                | -         |     0.41 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3671 | 2024-03-10 | adalYamigos       | L   | 0.220      | -            | -                | -                | -         |    -6.31 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3719 | 2024-03-08 | FURIA Academy     | W   | 0.206      | -            | -                | -                | -         |     0.36 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3884 | 2024-03-02 | Wildcard          | L   | 0.165      | -            | -                | -                | -         |    -3.61 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3901 | 2024-03-01 | Liquid            | L   | 0.159      | -            | -                | -                | -         |    -0.20 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     4025 | 2024-02-24 | Imperial          | L   | 0.118      | -            | -                | -                | -         |    -0.77 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4044 | 2024-02-23 | 9z                | L   | 0.112      | -            | -                | -                | -         |    -0.18 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4054 | 2024-02-22 | Imperial          | W   | 0.106      | -            | -                | -                | -         |     2.67 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4061 | 2024-02-22 | 9z                | L   | 0.105      | -            | -                | -                | -         |    -0.17 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4083 | 2024-02-21 | W7M               | W   | 0.098      | -            | -                | -                | -         |     0.83 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4160 | 2024-02-18 | FURIA Academy     | W   | 0.078      | -            | -                | -                | -         |     0.14 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4205 | 2024-02-16 | Case              | L   | 0.066      | -            | -                | -                | -         |    -1.27 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4324 | 2024-02-12 | FURIA Academy     | W   | 0.039      | -            | -                | -                | -         |     0.07 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,860.46)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.873 | $1,500.00      | $1,309.44       |
| 2024-06-10 |      0.833 | $4,000.00      | $3,330.65       |
| 2024-06-09 |      0.825 | $2,000.00      | $1,650.93       |
| 2024-05-12 |      0.639 | $5,000.00      | $3,193.06       |
| 2024-02-25 |      0.125 | $5,000.00      | $626.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
