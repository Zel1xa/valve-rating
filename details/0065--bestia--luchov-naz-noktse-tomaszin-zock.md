### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  997.4<br />
<br />
Final Rank Value (997.4) = Starting Rank Value (1019.6) + Head To Head Adjustments (-22.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.445[<sup>2</sup>](#table1)
- Opponent Network: 0.265[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.301<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1019.6
- 400 + ( ( 0.301 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1019.6


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
|          103 |       73 | 2024-08-03 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.42 | luchov, naz, Noktse, tomaszin, zock    |
|          102 |       80 | 2024-08-03 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.08 | luchov, naz, Noktse, tomaszin, zock    |
|          101 |      109 | 2024-08-02 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.68 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |      118 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -17.47 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |      139 | 2024-08-01 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.95 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |      143 | 2024-08-01 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.01 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |      156 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.86 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      238 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.45 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      244 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | 0 (0.000) |     7.56 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      252 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.23 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      279 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.03 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      308 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.84 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      390 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.14 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      398 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.05 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      467 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.29 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      472 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.60 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      507 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.123 (0.047)    | 0.701 (0.270)    | -         |    23.65 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      532 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.076 (0.029)    | 0.732 (0.281)    | -         |    23.57 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      589 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.75 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      600 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.83 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      640 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.28 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      642 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     1.14 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      654 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.28 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      701 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.50 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      706 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.25 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      716 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.85 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      770 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |    18.52 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      779 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.74 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      828 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.49 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      860 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.85 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      873 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -25.90 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      904 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -17.00 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      932 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.61 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      947 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.02 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      955 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.15 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1087 | 2024-06-15 | 9z                | L   | 0.853      | -            | -                | -                | -         |    -2.53 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1118 | 2024-06-14 | paiN              | L   | 0.847      | -            | -                | -                | -         |    -3.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1217 | 2024-06-10 | paiN              | L   | 0.822      | -            | -                | -                | -         |    -3.95 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1223 | 2024-06-10 | Bounty Hunters    | W   | 0.821      | -            | -                | -                | -         |     8.78 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1251 | 2024-06-09 | RED Canids        | W   | 0.816      | -            | -                | -                | -         |    17.31 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1279 | 2024-06-09 | Sharks            | L   | 0.813      | -            | -                | -                | -         |   -12.54 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1318 | 2024-06-08 | Solid             | W   | 0.808      | 0.371        | -                | 0.807 (0.242)    | -         |     7.82 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1333 | 2024-06-08 | Vikings KR        | L   | 0.807      | -            | -                | -                | -         |   -20.07 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1379 | 2024-06-07 | ODDIK             | W   | 0.801      | 0.450        | 0.099 (0.036)    | 0.805 (0.290)    | -         |     8.84 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1439 | 2024-06-06 | inSanitY          | L   | 0.794      | -            | -                | -                | -         |   -15.44 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1499 | 2024-06-05 | MIBR              | L   | 0.788      | -            | -                | -                | -         |    -2.54 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1551 | 2024-06-04 | Sharks            | L   | 0.782      | -            | -                | -                | -         |   -13.83 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1865 | 2024-05-22 | Case              | W   | 0.695      | 0.450        | -                | 0.778 (0.244)    | -         |     6.91 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1871 | 2024-05-22 | Case              | W   | 0.695      | 0.450        | -                | 0.778 (0.243)    | -         |     7.29 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1873 | 2024-05-22 | Fluxo             | W   | 0.694      | 0.450        | 0.123 (0.038)    | -                | -         |    12.06 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1876 | 2024-05-22 | Fluxo             | W   | 0.694      | 0.450        | 0.123 (0.038)    | -                | -         |    12.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1912 | 2024-05-21 | Smoke             | W   | 0.689      | -            | -                | -                | -         |     3.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1915 | 2024-05-21 | Smoke             | W   | 0.688      | -            | -                | -                | -         |     3.20 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1918 | 2024-05-21 | Imperial          | W   | 0.688      | 0.450        | 0.233 (0.072)    | -                | -         |    17.50 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1919 | 2024-05-21 | Imperial          | W   | 0.688      | 0.450        | 0.233 (0.072)    | -                | -         |    18.13 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1951 | 2024-05-20 | Corinthians       | W   | 0.682      | -            | -                | -                | -         |     1.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1953 | 2024-05-20 | 9z                | W   | 0.681      | 0.450        | 0.404 (0.124)    | -                | -         |    20.14 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1956 | 2024-05-20 | 9z                | L   | 0.681      | -            | -                | -                | -         |    -1.24 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     2038 | 2024-05-17 | Solid             | L   | 0.662      | -            | -                | -                | -         |   -13.01 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     2039 | 2024-05-17 | Solid             | W   | 0.662      | 0.450        | -                | 0.807 (0.240)    | -         |     7.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2123 | 2024-05-15 | ODDIK             | W   | 0.648      | 0.450        | -                | 0.805 (0.235)    | -         |    10.04 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2124 | 2024-05-15 | ODDIK             | W   | 0.648      | -            | -                | -                | -         |    10.63 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2134 | 2024-05-15 | Hype              | L   | 0.647      | -            | -                | -                | -         |   -12.13 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2185 | 2024-05-14 | Imperial          | L   | 0.641      | -            | -                | -                | -         |    -3.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2195 | 2024-05-14 | RED Canids        | L   | 0.640      | -            | -                | -                | -         |    -6.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2235 | 2024-05-12 | Solid             | W   | 0.628      | -            | -                | -                | -         |     7.79 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2242 | 2024-05-12 | O PLANO           | W   | 0.627      | -            | -                | -                | -         |     1.62 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2269 | 2024-05-11 | paiN              | L   | 0.620      | -            | -                | -                | -         |    -1.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2293 | 2024-05-10 | Imperial          | W   | 0.614      | 0.435        | 0.233 (0.062)    | -                | -         |    16.56 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2312 | 2024-05-09 | Sharks            | W   | 0.609      | -            | -                | -                | -         |    10.49 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2339 | 2024-05-08 | Vikings KR        | W   | 0.600      | -            | -                | -                | -         |     6.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2370 | 2024-05-06 | Sharks            | L   | 0.589      | -            | -                | -                | -         |    -8.34 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2609 | 2024-04-25 | RED Canids        | L   | 0.515      | -            | -                | -                | -         |    -4.97 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2611 | 2024-04-25 | RED Canids        | L   | 0.515      | -            | -                | -                | -         |    -5.16 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2876 | 2024-04-16 | O PLANO           | L   | 0.456      | -            | -                | -                | -         |   -13.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2973 | 2024-04-11 | Galorys           | L   | 0.420      | -            | -                | -                | -         |    -7.88 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3055 | 2024-04-09 | Galorys           | L   | 0.409      | -            | -                | -                | -         |    -7.91 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     3060 | 2024-04-09 | Galorys           | W   | 0.408      | -            | -                | -                | -         |     5.04 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3096 | 2024-04-08 | RED Canids        | L   | 0.402      | -            | -                | -                | -         |    -4.59 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3139 | 2024-04-07 | Sharks            | L   | 0.393      | -            | -                | -                | -         |    -9.63 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3147 | 2024-04-06 | Fluxo             | W   | 0.389      | -            | -                | -                | -         |     7.37 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3184 | 2024-04-04 | adalYamigos       | L   | 0.376      | -            | -                | -                | -         |   -10.64 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3193 | 2024-04-04 | adalYamigos       | W   | 0.375      | -            | -                | -                | -         |     1.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3201 | 2024-04-04 | Imperial          | L   | 0.374      | -            | -                | -                | -         |    -2.14 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3238 | 2024-04-03 | Fluxo             | L   | 0.368      | -            | -                | -                | -         |    -4.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3274 | 2024-04-02 | Sharks            | W   | 0.362      | -            | -                | -                | -         |     2.34 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3279 | 2024-04-02 | Fluxo             | L   | 0.361      | -            | -                | -                | -         |    -4.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3368 | 2024-03-27 | W7M               | L   | 0.322      | -            | -                | -                | -         |    -7.49 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3372 | 2024-03-27 | W7M               | W   | 0.322      | -            | -                | -                | -         |     2.68 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3683 | 2024-03-12 | RED Canids        | L   | 0.220      | -            | -                | -                | -         |    -2.88 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3693 | 2024-03-11 | FURIA Academy     | W   | 0.215      | -            | -                | -                | -         |     0.40 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3716 | 2024-03-10 | adalYamigos       | L   | 0.209      | -            | -                | -                | -         |    -6.00 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3764 | 2024-03-08 | FURIA Academy     | W   | 0.195      | -            | -                | -                | -         |     0.34 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3929 | 2024-03-02 | Wildcard          | L   | 0.154      | -            | -                | -                | -         |    -3.36 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3946 | 2024-03-01 | Liquid            | L   | 0.148      | -            | -                | -                | -         |    -0.18 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     4070 | 2024-02-24 | Imperial          | L   | 0.107      | -            | -                | -                | -         |    -0.71 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4089 | 2024-02-23 | 9z                | L   | 0.101      | -            | -                | -                | -         |    -0.16 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4099 | 2024-02-22 | Imperial          | W   | 0.095      | -            | -                | -                | -         |     2.38 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4106 | 2024-02-22 | 9z                | L   | 0.094      | -            | -                | -                | -         |    -0.15 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4128 | 2024-02-21 | W7M               | W   | 0.087      | -            | -                | -                | -         |     0.74 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4205 | 2024-02-18 | FURIA Academy     | W   | 0.067      | -            | -                | -                | -         |     0.12 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4250 | 2024-02-16 | Case              | L   | 0.055      | -            | -                | -                | -         |    -1.06 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4369 | 2024-02-12 | FURIA Academy     | W   | 0.029      | -            | -                | -                | -         |     0.05 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,670.88)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.862 | $1,500.00      | $1,293.19       |
| 2024-06-10 |      0.822 | $4,000.00      | $3,287.31       |
| 2024-06-09 |      0.815 | $2,000.00      | $1,629.26       |
| 2024-05-12 |      0.628 | $5,000.00      | $3,138.89       |
| 2024-02-25 |      0.114 | $5,000.00      | $572.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
