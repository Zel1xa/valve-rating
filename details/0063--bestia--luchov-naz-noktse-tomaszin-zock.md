### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  997.5<br />
<br />
Final Rank Value (997.5) = Starting Rank Value (1019.6) + Head To Head Adjustments (-22.1)<br />

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
|          103 |       63 | 2024-08-03 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.42 | luchov, naz, Noktse, tomaszin, zock    |
|          102 |       70 | 2024-08-03 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.08 | luchov, naz, Noktse, tomaszin, zock    |
|          101 |       99 | 2024-08-02 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.68 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |      108 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -17.48 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |      129 | 2024-08-01 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.95 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |      133 | 2024-08-01 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.01 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |      146 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.85 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      228 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.45 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      234 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | 0 (0.000) |     7.55 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      242 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.23 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      269 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.03 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      298 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.84 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      380 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.14 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      388 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.05 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      457 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.29 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      462 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.60 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      497 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.123 (0.047)    | 0.701 (0.269)    | -         |    23.66 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      522 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.076 (0.029)    | 0.732 (0.281)    | -         |    23.57 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      579 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.75 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      590 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.83 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      630 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.27 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      632 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     1.14 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      644 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.28 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      691 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.49 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      696 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.24 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      706 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.85 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      760 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |    18.52 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      769 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.74 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      818 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.49 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      850 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.85 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      863 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -25.90 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      894 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -17.00 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      922 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.60 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      937 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.02 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      945 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.15 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1077 | 2024-06-15 | 9z                | L   | 0.854      | -            | -                | -                | -         |    -2.53 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1108 | 2024-06-14 | paiN              | L   | 0.848      | -            | -                | -                | -         |    -3.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1207 | 2024-06-10 | paiN              | L   | 0.823      | -            | -                | -                | -         |    -3.95 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1213 | 2024-06-10 | Bounty Hunters    | W   | 0.822      | -            | -                | -                | -         |     8.79 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1241 | 2024-06-09 | RED Canids        | W   | 0.817      | -            | -                | -                | -         |    17.34 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1269 | 2024-06-09 | Sharks            | L   | 0.814      | -            | -                | -                | -         |   -12.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1308 | 2024-06-08 | Solid             | W   | 0.809      | 0.371        | -                | 0.807 (0.242)    | -         |     7.83 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1323 | 2024-06-08 | Vikings KR        | L   | 0.808      | -            | -                | -                | -         |   -20.10 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1369 | 2024-06-07 | ODDIK             | W   | 0.802      | 0.450        | 0.099 (0.036)    | 0.805 (0.291)    | -         |     8.85 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1429 | 2024-06-06 | inSanitY          | L   | 0.795      | -            | -                | -                | -         |   -15.46 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1489 | 2024-06-05 | MIBR              | L   | 0.789      | -            | -                | -                | -         |    -2.54 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1541 | 2024-06-04 | Sharks            | L   | 0.783      | -            | -                | -                | -         |   -13.85 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1855 | 2024-05-22 | Case              | W   | 0.696      | 0.450        | -                | 0.778 (0.244)    | -         |     6.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1861 | 2024-05-22 | Case              | W   | 0.696      | 0.450        | -                | 0.778 (0.244)    | -         |     7.30 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1863 | 2024-05-22 | Fluxo             | W   | 0.696      | 0.450        | 0.123 (0.038)    | -                | -         |    12.08 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1866 | 2024-05-22 | Fluxo             | W   | 0.695      | 0.450        | 0.123 (0.038)    | -                | -         |    12.83 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1902 | 2024-05-21 | Smoke             | W   | 0.690      | -            | -                | -                | -         |     3.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1905 | 2024-05-21 | Smoke             | W   | 0.689      | -            | -                | -                | -         |     3.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1908 | 2024-05-21 | Imperial          | W   | 0.689      | 0.450        | 0.233 (0.072)    | -                | -         |    17.54 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1909 | 2024-05-21 | Imperial          | W   | 0.689      | 0.450        | 0.233 (0.072)    | -                | -         |    18.16 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1941 | 2024-05-20 | Corinthians       | W   | 0.683      | -            | -                | -                | -         |     1.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1943 | 2024-05-20 | 9z                | W   | 0.682      | 0.450        | 0.404 (0.124)    | -                | -         |    20.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1946 | 2024-05-20 | 9z                | L   | 0.682      | -            | -                | -                | -         |    -1.24 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     2028 | 2024-05-17 | Solid             | L   | 0.663      | -            | -                | -                | -         |   -13.03 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     2029 | 2024-05-17 | Solid             | W   | 0.663      | 0.450        | -                | 0.807 (0.241)    | -         |     7.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2113 | 2024-05-15 | ODDIK             | W   | 0.649      | 0.450        | -                | 0.805 (0.235)    | -         |    10.06 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2114 | 2024-05-15 | ODDIK             | W   | 0.649      | -            | -                | -                | -         |    10.65 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2124 | 2024-05-15 | Hype              | L   | 0.648      | -            | -                | -                | -         |   -12.14 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2175 | 2024-05-14 | Imperial          | L   | 0.642      | -            | -                | -                | -         |    -3.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2185 | 2024-05-14 | RED Canids        | L   | 0.641      | -            | -                | -                | -         |    -6.93 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2225 | 2024-05-12 | Solid             | W   | 0.629      | -            | -                | -                | -         |     7.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2232 | 2024-05-12 | O PLANO           | W   | 0.628      | -            | -                | -                | -         |     1.62 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2259 | 2024-05-11 | paiN              | L   | 0.621      | -            | -                | -                | -         |    -1.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2283 | 2024-05-10 | Imperial          | W   | 0.615      | 0.435        | 0.233 (0.062)    | -                | -         |    16.59 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2302 | 2024-05-09 | Sharks            | W   | 0.610      | -            | -                | -                | -         |    10.52 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2329 | 2024-05-08 | Vikings KR        | W   | 0.601      | -            | -                | -                | -         |     6.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2360 | 2024-05-06 | Sharks            | L   | 0.590      | -            | -                | -                | -         |    -8.34 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2599 | 2024-04-25 | RED Canids        | L   | 0.516      | -            | -                | -                | -         |    -4.97 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2601 | 2024-04-25 | RED Canids        | L   | 0.516      | -            | -                | -                | -         |    -5.17 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2866 | 2024-04-16 | O PLANO           | L   | 0.457      | -            | -                | -                | -         |   -13.23 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2963 | 2024-04-11 | Galorys           | L   | 0.421      | -            | -                | -                | -         |    -7.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3045 | 2024-04-09 | Galorys           | L   | 0.410      | -            | -                | -                | -         |    -7.93 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     3050 | 2024-04-09 | Galorys           | W   | 0.409      | -            | -                | -                | -         |     5.06 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3086 | 2024-04-08 | RED Canids        | L   | 0.403      | -            | -                | -                | -         |    -4.60 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3129 | 2024-04-07 | Sharks            | L   | 0.394      | -            | -                | -                | -         |    -9.66 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3137 | 2024-04-06 | Fluxo             | W   | 0.390      | -            | -                | -                | -         |     7.39 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3174 | 2024-04-04 | adalYamigos       | L   | 0.377      | -            | -                | -                | -         |   -10.66 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3183 | 2024-04-04 | adalYamigos       | W   | 0.376      | -            | -                | -                | -         |     1.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3191 | 2024-04-04 | Imperial          | L   | 0.375      | -            | -                | -                | -         |    -2.14 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3228 | 2024-04-03 | Fluxo             | L   | 0.369      | -            | -                | -                | -         |    -4.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3264 | 2024-04-02 | Sharks            | W   | 0.363      | -            | -                | -                | -         |     2.34 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3269 | 2024-04-02 | Fluxo             | L   | 0.362      | -            | -                | -                | -         |    -5.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3358 | 2024-03-27 | W7M               | L   | 0.323      | -            | -                | -                | -         |    -7.51 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3362 | 2024-03-27 | W7M               | W   | 0.323      | -            | -                | -                | -         |     2.69 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3673 | 2024-03-12 | RED Canids        | L   | 0.221      | -            | -                | -                | -         |    -2.89 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3683 | 2024-03-11 | FURIA Academy     | W   | 0.216      | -            | -                | -                | -         |     0.40 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3706 | 2024-03-10 | adalYamigos       | L   | 0.210      | -            | -                | -                | -         |    -6.03 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3754 | 2024-03-08 | FURIA Academy     | W   | 0.196      | -            | -                | -                | -         |     0.35 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3919 | 2024-03-02 | Wildcard          | L   | 0.155      | -            | -                | -                | -         |    -3.38 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3936 | 2024-03-01 | Liquid            | L   | 0.149      | -            | -                | -                | -         |    -0.18 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     4060 | 2024-02-24 | Imperial          | L   | 0.108      | -            | -                | -                | -         |    -0.72 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4079 | 2024-02-23 | 9z                | L   | 0.102      | -            | -                | -                | -         |    -0.16 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4089 | 2024-02-22 | Imperial          | W   | 0.096      | -            | -                | -                | -         |     2.41 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4096 | 2024-02-22 | 9z                | L   | 0.095      | -            | -                | -                | -         |    -0.15 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4118 | 2024-02-21 | W7M               | W   | 0.088      | -            | -                | -                | -         |     0.75 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4195 | 2024-02-18 | FURIA Academy     | W   | 0.068      | -            | -                | -                | -         |     0.12 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4240 | 2024-02-16 | Case              | L   | 0.056      | -            | -                | -                | -         |    -1.08 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4359 | 2024-02-12 | FURIA Academy     | W   | 0.030      | -            | -                | -                | -         |     0.05 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,688.70)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.863 | $1,500.00      | $1,294.72       |
| 2024-06-10 |      0.823 | $4,000.00      | $3,291.39       |
| 2024-06-09 |      0.816 | $2,000.00      | $1,631.30       |
| 2024-05-12 |      0.629 | $5,000.00      | $3,143.98       |
| 2024-02-25 |      0.115 | $5,000.00      | $577.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
