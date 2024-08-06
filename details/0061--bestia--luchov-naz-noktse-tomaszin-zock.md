### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [61](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  998.7<br />
<br />
Final Rank Value (998.7) = Starting Rank Value (1021.3) + Head To Head Adjustments (-22.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.445[<sup>2</sup>](#table1)
- Opponent Network: 0.271[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.303<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1021.3
- 400 + ( ( 0.303 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1021.3


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
|          103 |       56 | 2024-08-03 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.41 | luchov, naz, Noktse, tomaszin, zock    |
|          102 |       63 | 2024-08-03 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.08 | luchov, naz, Noktse, tomaszin, zock    |
|          101 |       92 | 2024-08-02 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.67 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |      101 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -17.48 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |      122 | 2024-08-01 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.93 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |      126 | 2024-08-01 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.01 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |      139 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.85 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      221 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.45 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      227 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.542 (0.244)    | 0 (0.000) |     7.55 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      235 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.23 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      262 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.01 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      291 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.83 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      373 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.14 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      381 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.03 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      450 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.29 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      455 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.59 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      490 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.123 (0.047)    | 0.716 (0.275)    | -         |    23.66 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      515 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.076 (0.029)    | 0.748 (0.287)    | -         |    23.58 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      572 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.75 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      583 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.84 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      623 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.28 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      625 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     1.13 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      637 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.29 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      684 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.49 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      689 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.23 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      699 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.84 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      753 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.823 (0.370)    | -         |    18.51 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      762 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.75 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      811 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.48 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      843 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.82 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      856 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -25.95 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      887 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.99 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      915 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.56 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      930 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.00 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      938 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.15 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1070 | 2024-06-15 | 9z                | L   | 0.854      | -            | -                | -                | -         |    -2.54 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1101 | 2024-06-14 | paiN              | L   | 0.849      | -            | -                | -                | -         |    -3.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1200 | 2024-06-10 | paiN              | L   | 0.823      | -            | -                | -                | -         |    -3.96 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1206 | 2024-06-10 | Bounty Hunters    | W   | 0.822      | -            | -                | -                | -         |     8.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1234 | 2024-06-09 | RED Canids        | W   | 0.817      | -            | -                | -                | -         |    17.35 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1262 | 2024-06-09 | Sharks            | L   | 0.814      | -            | -                | -                | -         |   -12.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1301 | 2024-06-08 | Solid             | W   | 0.810      | 0.371        | -                | 0.825 (0.247)    | -         |     7.83 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1316 | 2024-06-08 | Vikings KR        | L   | 0.809      | -            | -                | -                | -         |   -20.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1362 | 2024-06-07 | ODDIK             | W   | 0.803      | 0.450        | 0.099 (0.036)    | 0.823 (0.297)    | -         |     8.85 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1422 | 2024-06-06 | inSanitY          | L   | 0.796      | -            | -                | -                | -         |   -15.47 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1482 | 2024-06-05 | MIBR              | L   | 0.790      | -            | -                | -                | -         |    -2.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1534 | 2024-06-04 | Sharks            | L   | 0.783      | -            | -                | -                | -         |   -13.85 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1848 | 2024-05-22 | Case              | W   | 0.697      | 0.450        | -                | 0.795 (0.249)    | -         |     6.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1854 | 2024-05-22 | Case              | W   | 0.697      | 0.450        | -                | 0.795 (0.249)    | -         |     7.30 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1856 | 2024-05-22 | Fluxo             | W   | 0.696      | 0.450        | 0.123 (0.039)    | -                | -         |    12.10 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1859 | 2024-05-22 | Fluxo             | W   | 0.696      | 0.450        | 0.123 (0.039)    | -                | -         |    12.85 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1895 | 2024-05-21 | Smoke             | W   | 0.690      | -            | -                | -                | -         |     3.09 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1898 | 2024-05-21 | Smoke             | W   | 0.690      | -            | -                | -                | -         |     3.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1901 | 2024-05-21 | Imperial          | W   | 0.690      | 0.450        | 0.233 (0.072)    | -                | -         |    17.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1902 | 2024-05-21 | Imperial          | W   | 0.689      | 0.450        | 0.233 (0.072)    | -                | -         |    18.17 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1934 | 2024-05-20 | Corinthians       | W   | 0.683      | -            | -                | -                | -         |     1.31 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1936 | 2024-05-20 | 9z                | W   | 0.683      | 0.450        | 0.404 (0.124)    | -                | -         |    20.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1939 | 2024-05-20 | 9z                | L   | 0.682      | -            | -                | -                | -         |    -1.24 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     2021 | 2024-05-17 | Solid             | L   | 0.664      | -            | -                | -                | -         |   -13.04 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     2022 | 2024-05-17 | Solid             | W   | 0.664      | 0.450        | -                | 0.825 (0.246)    | -         |     7.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2106 | 2024-05-15 | ODDIK             | W   | 0.650      | 0.450        | -                | 0.823 (0.241)    | -         |    10.06 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2107 | 2024-05-15 | ODDIK             | W   | 0.650      | -            | -                | -                | -         |    10.65 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2117 | 2024-05-15 | Hype              | L   | 0.649      | -            | -                | -                | -         |   -12.16 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2168 | 2024-05-14 | Imperial          | L   | 0.643      | -            | -                | -                | -         |    -3.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2178 | 2024-05-14 | RED Canids        | L   | 0.642      | -            | -                | -                | -         |    -6.94 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2218 | 2024-05-12 | Solid             | W   | 0.630      | -            | -                | -                | -         |     7.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2225 | 2024-05-12 | O PLANO           | W   | 0.629      | -            | -                | -                | -         |     1.61 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2252 | 2024-05-11 | paiN              | L   | 0.622      | -            | -                | -                | -         |    -1.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2276 | 2024-05-10 | Imperial          | W   | 0.615      | 0.435        | 0.233 (0.062)    | -                | -         |    16.61 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2295 | 2024-05-09 | Sharks            | W   | 0.610      | -            | -                | -                | -         |    10.54 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2322 | 2024-05-08 | Vikings KR        | W   | 0.602      | -            | -                | -                | -         |     6.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2353 | 2024-05-06 | Sharks            | L   | 0.590      | -            | -                | -                | -         |    -8.34 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2592 | 2024-04-25 | RED Canids        | L   | 0.517      | -            | -                | -                | -         |    -4.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2594 | 2024-04-25 | RED Canids        | L   | 0.517      | -            | -                | -                | -         |    -5.17 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2859 | 2024-04-16 | O PLANO           | L   | 0.457      | -            | -                | -                | -         |   -13.26 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2956 | 2024-04-11 | Galorys           | L   | 0.422      | -            | -                | -                | -         |    -7.91 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3038 | 2024-04-09 | Galorys           | L   | 0.410      | -            | -                | -                | -         |    -7.94 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     3043 | 2024-04-09 | Galorys           | W   | 0.410      | -            | -                | -                | -         |     5.06 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3079 | 2024-04-08 | RED Canids        | L   | 0.403      | -            | -                | -                | -         |    -4.61 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3122 | 2024-04-07 | Sharks            | L   | 0.394      | -            | -                | -                | -         |    -9.69 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3130 | 2024-04-06 | Fluxo             | W   | 0.390      | -            | -                | -                | -         |     7.41 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3167 | 2024-04-04 | adalYamigos       | L   | 0.377      | -            | -                | -                | -         |   -10.69 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3176 | 2024-04-04 | adalYamigos       | W   | 0.377      | -            | -                | -                | -         |     1.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3184 | 2024-04-04 | Imperial          | L   | 0.376      | -            | -                | -                | -         |    -2.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3221 | 2024-04-03 | Fluxo             | L   | 0.369      | -            | -                | -                | -         |    -5.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3257 | 2024-04-02 | Sharks            | W   | 0.364      | -            | -                | -                | -         |     2.33 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3262 | 2024-04-02 | Fluxo             | L   | 0.363      | -            | -                | -                | -         |    -5.01 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3351 | 2024-03-27 | W7M               | L   | 0.324      | -            | -                | -                | -         |    -7.53 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3355 | 2024-03-27 | W7M               | W   | 0.324      | -            | -                | -                | -         |     2.69 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3666 | 2024-03-12 | RED Canids        | L   | 0.222      | -            | -                | -                | -         |    -2.90 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3676 | 2024-03-11 | FURIA Academy     | W   | 0.217      | -            | -                | -                | -         |     0.40 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3699 | 2024-03-10 | adalYamigos       | L   | 0.210      | -            | -                | -                | -         |    -6.05 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3747 | 2024-03-08 | FURIA Academy     | W   | 0.197      | -            | -                | -                | -         |     0.34 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3912 | 2024-03-02 | Wildcard          | L   | 0.156      | -            | -                | -                | -         |    -3.40 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3929 | 2024-03-01 | Liquid            | L   | 0.150      | -            | -                | -                | -         |    -0.19 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     4053 | 2024-02-24 | Imperial          | L   | 0.109      | -            | -                | -                | -         |    -0.72 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4072 | 2024-02-23 | 9z                | L   | 0.103      | -            | -                | -                | -         |    -0.17 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4082 | 2024-02-22 | Imperial          | W   | 0.097      | -            | -                | -                | -         |     2.42 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4089 | 2024-02-22 | 9z                | L   | 0.096      | -            | -                | -                | -         |    -0.15 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4111 | 2024-02-21 | W7M               | W   | 0.089      | -            | -                | -                | -         |     0.75 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4188 | 2024-02-18 | FURIA Academy     | W   | 0.069      | -            | -                | -                | -         |     0.12 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4233 | 2024-02-16 | Case              | L   | 0.057      | -            | -                | -                | -         |    -1.09 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4352 | 2024-02-12 | FURIA Academy     | W   | 0.030      | -            | -                | -                | -         |     0.05 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,700.05)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.864 | $1,500.00      | $1,295.69       |
| 2024-06-10 |      0.823 | $4,000.00      | $3,293.98       |
| 2024-06-09 |      0.816 | $2,000.00      | $1,632.59       |
| 2024-05-12 |      0.629 | $5,000.00      | $3,147.22       |
| 2024-02-25 |      0.116 | $5,000.00      | $580.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
