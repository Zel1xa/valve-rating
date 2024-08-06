### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [61](../standings_global.md)<br />
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
|          103 |       60 | 2024-08-03 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.42 | luchov, naz, Noktse, tomaszin, zock    |
|          102 |       67 | 2024-08-03 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.08 | luchov, naz, Noktse, tomaszin, zock    |
|          101 |       96 | 2024-08-02 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.68 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |      105 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -17.48 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |      126 | 2024-08-01 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.95 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |      130 | 2024-08-01 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.01 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |      143 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.85 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      225 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.45 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      231 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | 0 (0.000) |     7.55 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      239 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.23 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      266 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.03 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      295 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.84 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      377 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.14 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      385 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.05 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      454 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.29 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      459 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.59 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      494 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.123 (0.047)    | 0.701 (0.269)    | -         |    23.66 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      519 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.076 (0.029)    | 0.732 (0.281)    | -         |    23.58 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      576 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.75 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      587 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.84 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      627 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.27 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      629 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     1.14 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      641 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.28 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      688 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.49 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      693 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.24 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      703 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.85 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      757 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |    18.51 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      766 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.74 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      815 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.49 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      847 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.85 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      860 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -25.90 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      891 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -17.00 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      919 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.60 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      934 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.02 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      942 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.15 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1074 | 2024-06-15 | 9z                | L   | 0.854      | -            | -                | -                | -         |    -2.53 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1105 | 2024-06-14 | paiN              | L   | 0.848      | -            | -                | -                | -         |    -3.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1204 | 2024-06-10 | paiN              | L   | 0.823      | -            | -                | -                | -         |    -3.95 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1210 | 2024-06-10 | Bounty Hunters    | W   | 0.822      | -            | -                | -                | -         |     8.79 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1238 | 2024-06-09 | RED Canids        | W   | 0.817      | -            | -                | -                | -         |    17.35 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1266 | 2024-06-09 | Sharks            | L   | 0.814      | -            | -                | -                | -         |   -12.56 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1305 | 2024-06-08 | Solid             | W   | 0.809      | 0.371        | -                | 0.807 (0.242)    | -         |     7.83 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1320 | 2024-06-08 | Vikings KR        | L   | 0.808      | -            | -                | -                | -         |   -20.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1366 | 2024-06-07 | ODDIK             | W   | 0.802      | 0.450        | 0.099 (0.036)    | 0.805 (0.291)    | -         |     8.85 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1426 | 2024-06-06 | inSanitY          | L   | 0.796      | -            | -                | -                | -         |   -15.46 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1486 | 2024-06-05 | MIBR              | L   | 0.790      | -            | -                | -                | -         |    -2.54 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1538 | 2024-06-04 | Sharks            | L   | 0.783      | -            | -                | -                | -         |   -13.86 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1852 | 2024-05-22 | Case              | W   | 0.697      | 0.450        | -                | 0.778 (0.244)    | -         |     6.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1858 | 2024-05-22 | Case              | W   | 0.696      | 0.450        | -                | 0.778 (0.244)    | -         |     7.30 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1860 | 2024-05-22 | Fluxo             | W   | 0.696      | 0.450        | 0.123 (0.039)    | -                | -         |    12.09 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1863 | 2024-05-22 | Fluxo             | W   | 0.696      | 0.450        | 0.123 (0.038)    | -                | -         |    12.84 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1899 | 2024-05-21 | Smoke             | W   | 0.690      | -            | -                | -                | -         |     3.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1902 | 2024-05-21 | Smoke             | W   | 0.690      | -            | -                | -                | -         |     3.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1905 | 2024-05-21 | Imperial          | W   | 0.689      | 0.450        | 0.233 (0.072)    | -                | -         |    17.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1906 | 2024-05-21 | Imperial          | W   | 0.689      | 0.450        | 0.233 (0.072)    | -                | -         |    18.17 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1938 | 2024-05-20 | Corinthians       | W   | 0.683      | -            | -                | -                | -         |     1.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1940 | 2024-05-20 | 9z                | W   | 0.683      | 0.450        | 0.404 (0.124)    | -                | -         |    20.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1943 | 2024-05-20 | 9z                | L   | 0.682      | -            | -                | -                | -         |    -1.24 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     2025 | 2024-05-17 | Solid             | L   | 0.664      | -            | -                | -                | -         |   -13.03 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     2026 | 2024-05-17 | Solid             | W   | 0.663      | 0.450        | -                | 0.807 (0.241)    | -         |     7.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2110 | 2024-05-15 | ODDIK             | W   | 0.650      | 0.450        | -                | 0.805 (0.235)    | -         |    10.06 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2111 | 2024-05-15 | ODDIK             | W   | 0.649      | -            | -                | -                | -         |    10.66 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2121 | 2024-05-15 | Hype              | L   | 0.648      | -            | -                | -                | -         |   -12.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2172 | 2024-05-14 | Imperial          | L   | 0.643      | -            | -                | -                | -         |    -3.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2182 | 2024-05-14 | RED Canids        | L   | 0.642      | -            | -                | -                | -         |    -6.93 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2222 | 2024-05-12 | Solid             | W   | 0.629      | -            | -                | -                | -         |     7.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2229 | 2024-05-12 | O PLANO           | W   | 0.628      | -            | -                | -                | -         |     1.62 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2256 | 2024-05-11 | paiN              | L   | 0.622      | -            | -                | -                | -         |    -1.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2280 | 2024-05-10 | Imperial          | W   | 0.615      | 0.435        | 0.233 (0.062)    | -                | -         |    16.61 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2299 | 2024-05-09 | Sharks            | W   | 0.610      | -            | -                | -                | -         |    10.52 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2326 | 2024-05-08 | Vikings KR        | W   | 0.602      | -            | -                | -                | -         |     6.82 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2357 | 2024-05-06 | Sharks            | L   | 0.590      | -            | -                | -                | -         |    -8.35 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2596 | 2024-04-25 | RED Canids        | L   | 0.517      | -            | -                | -                | -         |    -4.97 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2598 | 2024-04-25 | RED Canids        | L   | 0.516      | -            | -                | -                | -         |    -5.17 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2863 | 2024-04-16 | O PLANO           | L   | 0.457      | -            | -                | -                | -         |   -13.24 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2960 | 2024-04-11 | Galorys           | L   | 0.422      | -            | -                | -                | -         |    -7.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3042 | 2024-04-09 | Galorys           | L   | 0.410      | -            | -                | -                | -         |    -7.93 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     3047 | 2024-04-09 | Galorys           | W   | 0.410      | -            | -                | -                | -         |     5.06 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3083 | 2024-04-08 | RED Canids        | L   | 0.403      | -            | -                | -                | -         |    -4.60 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3126 | 2024-04-07 | Sharks            | L   | 0.394      | -            | -                | -                | -         |    -9.66 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3134 | 2024-04-06 | Fluxo             | W   | 0.390      | -            | -                | -                | -         |     7.40 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3171 | 2024-04-04 | adalYamigos       | L   | 0.377      | -            | -                | -                | -         |   -10.68 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3180 | 2024-04-04 | adalYamigos       | W   | 0.376      | -            | -                | -                | -         |     1.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3188 | 2024-04-04 | Imperial          | L   | 0.375      | -            | -                | -                | -         |    -2.14 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3225 | 2024-04-03 | Fluxo             | L   | 0.369      | -            | -                | -                | -         |    -5.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3261 | 2024-04-02 | Sharks            | W   | 0.363      | -            | -                | -                | -         |     2.35 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3266 | 2024-04-02 | Fluxo             | L   | 0.362      | -            | -                | -                | -         |    -5.01 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3355 | 2024-03-27 | W7M               | L   | 0.324      | -            | -                | -                | -         |    -7.52 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3359 | 2024-03-27 | W7M               | W   | 0.323      | -            | -                | -                | -         |     2.69 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3670 | 2024-03-12 | RED Canids        | L   | 0.222      | -            | -                | -                | -         |    -2.89 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3680 | 2024-03-11 | FURIA Academy     | W   | 0.217      | -            | -                | -                | -         |     0.40 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3703 | 2024-03-10 | adalYamigos       | L   | 0.210      | -            | -                | -                | -         |    -6.04 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3751 | 2024-03-08 | FURIA Academy     | W   | 0.197      | -            | -                | -                | -         |     0.35 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3916 | 2024-03-02 | Wildcard          | L   | 0.155      | -            | -                | -                | -         |    -3.39 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3933 | 2024-03-01 | Liquid            | L   | 0.150      | -            | -                | -                | -         |    -0.18 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     4057 | 2024-02-24 | Imperial          | L   | 0.108      | -            | -                | -                | -         |    -0.72 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4076 | 2024-02-23 | 9z                | L   | 0.102      | -            | -                | -                | -         |    -0.17 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4086 | 2024-02-22 | Imperial          | W   | 0.097      | -            | -                | -                | -         |     2.42 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4093 | 2024-02-22 | 9z                | L   | 0.096      | -            | -                | -                | -         |    -0.15 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4115 | 2024-02-21 | W7M               | W   | 0.088      | -            | -                | -                | -         |     0.75 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4192 | 2024-02-18 | FURIA Academy     | W   | 0.068      | -            | -                | -                | -         |     0.12 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4237 | 2024-02-16 | Case              | L   | 0.057      | -            | -                | -                | -         |    -1.09 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4356 | 2024-02-12 | FURIA Academy     | W   | 0.030      | -            | -                | -                | -         |     0.05 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,695.19)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.864 | $1,500.00      | $1,295.28       |
| 2024-06-10 |      0.823 | $4,000.00      | $3,292.87       |
| 2024-06-09 |      0.816 | $2,000.00      | $1,632.04       |
| 2024-05-12 |      0.629 | $5,000.00      | $3,145.83       |
| 2024-02-25 |      0.116 | $5,000.00      | $579.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
