### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1014.7<br />
<br />
Final Rank Value (1014.7) = Starting Rank Value (1024.9) + Head To Head Adjustments (-10.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.450[<sup>2</sup>](#table1)
- Opponent Network: 0.268[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.303<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1024.9
- 400 + ( ( 0.303 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1024.9


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
|           99 |       40 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.67 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |       46 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.553 (0.249)    | 0 (0.000) |     7.33 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |       54 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.06 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |       81 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.90 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      110 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.71 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      192 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.18 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      200 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.99 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      269 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.22 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      274 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.42 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      309 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.126 (0.048)    | 0.685 (0.263)    | 0 (0.000) |    23.74 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      334 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.079 (0.030)    | 0.738 (0.284)    | 0 (0.000) |    23.76 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      391 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.52 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      402 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.05 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      442 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -6.84 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      444 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.11 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      456 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.45 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      503 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.38 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      508 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.12 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      518 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.70 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      572 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.097 (0.044)    | 0.781 (0.352)    | -         |    18.32 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      581 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.95 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      630 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.31 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      662 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.68 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      675 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -26.06 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      706 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -17.05 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      734 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.46 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      749 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     5.86 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      757 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.28 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      889 | 2024-06-15 | 9z                | L   | 0.891      | -            | -                | -                | -         |    -2.57 | luchov, meyern, naz, Noktse, tomaszin  |
|           70 |      920 | 2024-06-14 | paiN              | L   | 0.886      | -            | -                | -                | -         |    -3.83 | luchov, meyern, naz, Noktse, tomaszin  |
|           69 |     1019 | 2024-06-10 | paiN              | L   | 0.861      | -            | -                | -                | -         |    -3.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           68 |     1025 | 2024-06-10 | Bounty Hunters    | W   | 0.859      | -            | -                | -                | -         |     9.06 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1053 | 2024-06-09 | RED Canids        | W   | 0.854      | -            | -                | -                | -         |    18.41 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1081 | 2024-06-09 | Sharks            | L   | 0.852      | -            | -                | -                | -         |   -13.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1120 | 2024-06-08 | Solid             | W   | 0.847      | 0.371        | -                | 0.817 (0.256)    | -         |     8.04 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1135 | 2024-06-08 | Vikings KR        | L   | 0.846      | -            | -                | -                | -         |   -21.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1181 | 2024-06-07 | ODDIK             | W   | 0.840      | 0.450        | 0.097 (0.037)    | 0.781 (0.295)    | -         |     9.07 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1241 | 2024-06-06 | inSanitY          | L   | 0.833      | -            | -                | -                | -         |   -16.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1301 | 2024-06-05 | MIBR              | L   | 0.827      | -            | -                | -                | -         |    -2.52 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1353 | 2024-06-04 | Sharks            | L   | 0.821      | -            | -                | -                | -         |   -14.52 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1667 | 2024-05-22 | Case              | W   | 0.734      | 0.450        | -                | 0.720 (0.238)    | -         |     7.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1673 | 2024-05-22 | Case              | W   | 0.734      | -            | -                | -                | -         |     7.60 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1675 | 2024-05-22 | Fluxo             | W   | 0.733      | 0.450        | 0.126 (0.042)    | -                | -         |    12.74 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1678 | 2024-05-22 | Fluxo             | W   | 0.733      | 0.450        | 0.126 (0.042)    | -                | -         |    13.58 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1714 | 2024-05-21 | Smoke             | W   | 0.727      | -            | -                | -                | -         |     3.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1717 | 2024-05-21 | Smoke             | W   | 0.727      | -            | -                | -                | -         |     3.31 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1720 | 2024-05-21 | Imperial          | W   | 0.727      | 0.450        | 0.243 (0.079)    | -                | -         |    18.91 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1721 | 2024-05-21 | Imperial          | W   | 0.726      | 0.450        | 0.243 (0.079)    | -                | -         |    19.56 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1753 | 2024-05-20 | Corinthians       | W   | 0.720      | -            | -                | -                | -         |     1.39 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1755 | 2024-05-20 | 9z                | W   | 0.720      | 0.450        | 0.408 (0.132)    | -                | -         |    21.39 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1758 | 2024-05-20 | 9z                | L   | 0.720      | -            | -                | -                | -         |    -1.20 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1840 | 2024-05-17 | Solid             | L   | 0.701      | -            | -                | -                | -         |   -13.79 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1841 | 2024-05-17 | Solid             | W   | 0.701      | 0.450        | -                | 0.817 (0.258)    | -         |     8.33 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1925 | 2024-05-15 | ODDIK             | W   | 0.687      | 0.450        | -                | 0.781 (0.242)    | -         |    10.63 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     1926 | 2024-05-15 | ODDIK             | W   | 0.687      | 0.450        | -                | 0.781 (0.242)    | -         |    11.30 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     1936 | 2024-05-15 | Hype              | L   | 0.686      | -            | -                | -                | -         |   -12.88 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     1987 | 2024-05-14 | Imperial          | L   | 0.680      | -            | -                | -                | -         |    -2.95 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     1997 | 2024-05-14 | RED Canids        | L   | 0.679      | -            | -                | -                | -         |    -7.05 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2037 | 2024-05-12 | Solid             | W   | 0.667      | -            | -                | -                | -         |     8.27 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2044 | 2024-05-12 | O PLANO           | W   | 0.666      | -            | -                | -                | -         |     1.73 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2071 | 2024-05-11 | paiN              | L   | 0.659      | -            | -                | -                | -         |    -1.72 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2095 | 2024-05-10 | Imperial          | W   | 0.653      | 0.435        | 0.243 (0.069)    | -                | -         |    18.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2114 | 2024-05-09 | Sharks            | W   | 0.647      | -            | -                | -                | -         |    11.31 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2141 | 2024-05-08 | Vikings KR        | W   | 0.639      | -            | -                | -                | -         |     7.28 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2172 | 2024-05-06 | Sharks            | L   | 0.627      | -            | -                | -                | -         |    -8.71 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2411 | 2024-04-25 | RED Canids        | L   | 0.554      | -            | -                | -                | -         |    -5.04 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2413 | 2024-04-25 | RED Canids        | L   | 0.554      | -            | -                | -                | -         |    -5.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2678 | 2024-04-16 | O PLANO           | L   | 0.494      | -            | -                | -                | -         |   -14.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2775 | 2024-04-11 | Galorys           | L   | 0.459      | -            | -                | -                | -         |    -8.64 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2857 | 2024-04-09 | Galorys           | L   | 0.447      | -            | -                | -                | -         |    -8.72 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2862 | 2024-04-09 | Galorys           | W   | 0.447      | -            | -                | -                | -         |     5.46 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2898 | 2024-04-08 | RED Canids        | L   | 0.440      | -            | -                | -                | -         |    -4.83 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     2941 | 2024-04-07 | Sharks            | L   | 0.432      | -            | -                | -                | -         |   -10.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     2949 | 2024-04-06 | Fluxo             | W   | 0.427      | -            | -                | -                | -         |     8.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     2986 | 2024-04-04 | adalYamigos       | L   | 0.414      | -            | -                | -                | -         |   -11.64 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     2995 | 2024-04-04 | adalYamigos       | W   | 0.414      | -            | -                | -                | -         |     1.40 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3003 | 2024-04-04 | Imperial          | L   | 0.413      | -            | -                | -                | -         |    -2.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3040 | 2024-04-03 | Fluxo             | L   | 0.406      | -            | -                | -                | -         |    -5.49 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3076 | 2024-04-02 | Sharks            | W   | 0.401      | -            | -                | -                | -         |     2.60 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3081 | 2024-04-02 | Fluxo             | L   | 0.400      | -            | -                | -                | -         |    -5.53 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3170 | 2024-03-27 | W7M               | L   | 0.361      | -            | -                | -                | -         |    -8.44 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3174 | 2024-03-27 | W7M               | W   | 0.361      | -            | -                | -                | -         |     2.95 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3485 | 2024-03-12 | RED Canids        | L   | 0.259      | -            | -                | -                | -         |    -3.28 | deco, luchov, meyern, Noktse, tomaszin |
|           16 |     3495 | 2024-03-11 | FURIA Academy     | W   | 0.254      | -            | -                | -                | -         |     0.47 | deco, luchov, meyern, Noktse, tomaszin |
|           15 |     3518 | 2024-03-10 | adalYamigos       | L   | 0.248      | -            | -                | -                | -         |    -7.08 | deco, luchov, meyern, Noktse, tomaszin |
|           14 |     3566 | 2024-03-08 | FURIA Academy     | W   | 0.234      | -            | -                | -                | -         |     0.41 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3731 | 2024-03-02 | Wildcard          | L   | 0.193      | -            | -                | -                | -         |    -4.04 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3748 | 2024-03-01 | Liquid            | L   | 0.187      | -            | -                | -                | -         |    -0.45 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3872 | 2024-02-24 | Imperial          | L   | 0.146      | -            | -                | -                | -         |    -0.85 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3891 | 2024-02-23 | 9z                | L   | 0.140      | -            | -                | -                | -         |    -0.21 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3901 | 2024-02-22 | Imperial          | W   | 0.134      | -            | -                | -                | -         |     3.47 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     3908 | 2024-02-22 | 9z                | L   | 0.133      | -            | -                | -                | -         |    -0.19 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     3930 | 2024-02-21 | W7M               | W   | 0.126      | -            | -                | -                | -         |     1.05 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4007 | 2024-02-18 | FURIA Academy     | W   | 0.106      | -            | -                | -                | -         |     0.19 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4052 | 2024-02-16 | Case              | L   | 0.094      | -            | -                | -                | -         |    -1.79 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4171 | 2024-02-12 | FURIA Academy     | W   | 0.067      | -            | -                | -                | -         |     0.12 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4306 | 2024-02-02 | Imperial          | L   | 0.002      | -            | -                | -                | -         |    -0.01 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4308 | 2024-02-02 | ODDIK             | W   | 0.001      | -            | -                | -                | -         |     0.02 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4312 | 2024-02-02 | Imperial          | L   | 0.001      | -            | -                | -                | -         |    -0.00 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,349.57)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.901 | $1,500.00      | $1,351.37       |
| 2024-06-10 |      0.861 | $4,000.00      | $3,442.44       |
| 2024-06-09 |      0.853 | $2,000.00      | $1,706.82       |
| 2024-05-12 |      0.667 | $5,000.00      | $3,332.80       |
| 2024-02-25 |      0.153 | $5,000.00      | $766.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
