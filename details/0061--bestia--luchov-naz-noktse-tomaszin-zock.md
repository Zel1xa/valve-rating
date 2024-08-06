### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [61](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  998.8<br />
<br />
Final Rank Value (998.8) = Starting Rank Value (1021.4) + Head To Head Adjustments (-22.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.445[<sup>2</sup>](#table1)
- Opponent Network: 0.271[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.303<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1021.4
- 400 + ( ( 0.303 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1021.4


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
|          103 |       52 | 2024-08-03 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.41 | luchov, naz, Noktse, tomaszin, zock    |
|          102 |       59 | 2024-08-03 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.08 | luchov, naz, Noktse, tomaszin, zock    |
|          101 |       88 | 2024-08-02 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.67 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |       97 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -17.48 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |      118 | 2024-08-01 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.93 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |      122 | 2024-08-01 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.00 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |      135 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.85 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      217 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.46 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      223 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.543 (0.244)    | 0 (0.000) |     7.54 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      231 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.22 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      258 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.01 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      287 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.83 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      369 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.14 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      377 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.03 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      446 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.28 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      451 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.58 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      486 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.123 (0.047)    | 0.716 (0.275)    | -         |    23.67 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      511 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.077 (0.029)    | 0.748 (0.287)    | -         |    23.59 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      568 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.74 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      579 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.85 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      619 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.26 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      621 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     1.13 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      633 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.29 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      680 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.48 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      685 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.22 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      695 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.84 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      749 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |    18.51 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      758 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.75 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      807 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.48 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      839 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.82 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      852 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -25.95 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      883 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.99 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      911 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.56 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      926 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     5.99 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      934 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.15 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1066 | 2024-06-15 | 9z                | L   | 0.857      | -            | -                | -                | -         |    -2.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1097 | 2024-06-14 | paiN              | L   | 0.851      | -            | -                | -                | -         |    -3.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1196 | 2024-06-10 | paiN              | L   | 0.826      | -            | -                | -                | -         |    -3.96 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1202 | 2024-06-10 | Bounty Hunters    | W   | 0.825      | -            | -                | -                | -         |     8.82 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1230 | 2024-06-09 | RED Canids        | W   | 0.820      | -            | -                | -                | -         |    17.42 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1258 | 2024-06-09 | Sharks            | L   | 0.817      | -            | -                | -                | -         |   -12.58 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1297 | 2024-06-08 | Solid             | W   | 0.812      | 0.371        | -                | 0.825 (0.248)    | -         |     7.85 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1312 | 2024-06-08 | Vikings KR        | L   | 0.811      | -            | -                | -                | -         |   -20.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1358 | 2024-06-07 | ODDIK             | W   | 0.805      | 0.450        | 0.099 (0.036)    | 0.822 (0.298)    | -         |     8.87 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1418 | 2024-06-06 | inSanitY          | L   | 0.799      | -            | -                | -                | -         |   -15.51 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1478 | 2024-06-05 | MIBR              | L   | 0.793      | -            | -                | -                | -         |    -2.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1530 | 2024-06-04 | Sharks            | L   | 0.786      | -            | -                | -                | -         |   -13.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1844 | 2024-05-22 | Case              | W   | 0.699      | 0.450        | -                | 0.795 (0.250)    | -         |     6.94 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1850 | 2024-05-22 | Case              | W   | 0.699      | 0.450        | -                | 0.795 (0.250)    | -         |     7.33 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1852 | 2024-05-22 | Fluxo             | W   | 0.699      | 0.450        | 0.123 (0.039)    | -                | -         |    12.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1855 | 2024-05-22 | Fluxo             | W   | 0.698      | 0.450        | 0.123 (0.039)    | -                | -         |    12.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1891 | 2024-05-21 | Smoke             | W   | 0.693      | -            | -                | -                | -         |     3.10 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1894 | 2024-05-21 | Smoke             | W   | 0.693      | -            | -                | -                | -         |     3.20 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1897 | 2024-05-21 | Imperial          | W   | 0.692      | 0.450        | 0.234 (0.073)    | -                | -         |    17.63 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1898 | 2024-05-21 | Imperial          | W   | 0.692      | 0.450        | 0.234 (0.073)    | -                | -         |    18.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1930 | 2024-05-20 | Corinthians       | W   | 0.686      | -            | -                | -                | -         |     1.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1932 | 2024-05-20 | 9z                | W   | 0.685      | 0.450        | 0.404 (0.125)    | -                | -         |    20.26 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1935 | 2024-05-20 | 9z                | L   | 0.685      | -            | -                | -                | -         |    -1.24 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     2017 | 2024-05-17 | Solid             | L   | 0.666      | -            | -                | -                | -         |   -13.09 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     2018 | 2024-05-17 | Solid             | W   | 0.666      | 0.450        | -                | 0.825 (0.247)    | -         |     7.95 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2102 | 2024-05-15 | ODDIK             | W   | 0.652      | 0.450        | -                | 0.822 (0.241)    | -         |    10.10 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2103 | 2024-05-15 | ODDIK             | W   | 0.652      | -            | -                | -                | -         |    10.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2113 | 2024-05-15 | Hype              | L   | 0.651      | -            | -                | -                | -         |   -12.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2164 | 2024-05-14 | Imperial          | L   | 0.646      | -            | -                | -                | -         |    -3.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2174 | 2024-05-14 | RED Canids        | L   | 0.644      | -            | -                | -                | -         |    -6.95 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2214 | 2024-05-12 | Solid             | W   | 0.632      | -            | -                | -                | -         |     7.85 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2221 | 2024-05-12 | O PLANO           | W   | 0.631      | -            | -                | -                | -         |     1.62 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2248 | 2024-05-11 | paiN              | L   | 0.624      | -            | -                | -                | -         |    -1.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2272 | 2024-05-10 | Imperial          | W   | 0.618      | 0.435        | 0.234 (0.063)    | -                | -         |    16.69 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2291 | 2024-05-09 | Sharks            | W   | 0.613      | -            | -                | -                | -         |    10.59 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2318 | 2024-05-08 | Vikings KR        | W   | 0.604      | -            | -                | -                | -         |     6.85 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2349 | 2024-05-06 | Sharks            | L   | 0.593      | -            | -                | -                | -         |    -8.36 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2588 | 2024-04-25 | RED Canids        | L   | 0.519      | -            | -                | -                | -         |    -4.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2590 | 2024-04-25 | RED Canids        | L   | 0.519      | -            | -                | -                | -         |    -5.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2855 | 2024-04-16 | O PLANO           | L   | 0.460      | -            | -                | -                | -         |   -13.33 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2952 | 2024-04-11 | Galorys           | L   | 0.424      | -            | -                | -                | -         |    -7.95 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3034 | 2024-04-09 | Galorys           | L   | 0.413      | -            | -                | -                | -         |    -7.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     3039 | 2024-04-09 | Galorys           | W   | 0.412      | -            | -                | -                | -         |     5.09 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3075 | 2024-04-08 | RED Canids        | L   | 0.406      | -            | -                | -                | -         |    -4.63 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3118 | 2024-04-07 | Sharks            | L   | 0.397      | -            | -                | -                | -         |    -9.75 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3126 | 2024-04-06 | Fluxo             | W   | 0.393      | -            | -                | -                | -         |     7.46 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3163 | 2024-04-04 | adalYamigos       | L   | 0.380      | -            | -                | -                | -         |   -10.75 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3172 | 2024-04-04 | adalYamigos       | W   | 0.379      | -            | -                | -                | -         |     1.20 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3180 | 2024-04-04 | Imperial          | L   | 0.378      | -            | -                | -                | -         |    -2.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3217 | 2024-04-03 | Fluxo             | L   | 0.372      | -            | -                | -                | -         |    -5.03 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3253 | 2024-04-02 | Sharks            | W   | 0.366      | -            | -                | -                | -         |     2.35 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3258 | 2024-04-02 | Fluxo             | L   | 0.365      | -            | -                | -                | -         |    -5.04 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3347 | 2024-03-27 | W7M               | L   | 0.326      | -            | -                | -                | -         |    -7.59 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3351 | 2024-03-27 | W7M               | W   | 0.326      | -            | -                | -                | -         |     2.71 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3662 | 2024-03-12 | RED Canids        | L   | 0.224      | -            | -                | -                | -         |    -2.93 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3672 | 2024-03-11 | FURIA Academy     | W   | 0.220      | -            | -                | -                | -         |     0.40 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3695 | 2024-03-10 | adalYamigos       | L   | 0.213      | -            | -                | -                | -         |    -6.12 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3743 | 2024-03-08 | FURIA Academy     | W   | 0.199      | -            | -                | -                | -         |     0.35 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3908 | 2024-03-02 | Wildcard          | L   | 0.158      | -            | -                | -                | -         |    -3.46 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3925 | 2024-03-01 | Liquid            | L   | 0.153      | -            | -                | -                | -         |    -0.19 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     4049 | 2024-02-24 | Imperial          | L   | 0.111      | -            | -                | -                | -         |    -0.74 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4068 | 2024-02-23 | 9z                | L   | 0.105      | -            | -                | -                | -         |    -0.17 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4078 | 2024-02-22 | Imperial          | W   | 0.100      | -            | -                | -                | -         |     2.49 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4085 | 2024-02-22 | 9z                | L   | 0.098      | -            | -                | -                | -         |    -0.16 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4107 | 2024-02-21 | W7M               | W   | 0.091      | -            | -                | -                | -         |     0.77 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4184 | 2024-02-18 | FURIA Academy     | W   | 0.071      | -            | -                | -                | -         |     0.12 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4229 | 2024-02-16 | Case              | L   | 0.059      | -            | -                | -                | -         |    -1.14 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4348 | 2024-02-12 | FURIA Academy     | W   | 0.033      | -            | -                | -                | -         |     0.06 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,743.80)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.866 | $1,500.00      | $1,299.44       |
| 2024-06-10 |      0.826 | $4,000.00      | $3,303.98       |
| 2024-06-09 |      0.819 | $2,000.00      | $1,637.59       |
| 2024-05-12 |      0.632 | $5,000.00      | $3,159.72       |
| 2024-02-25 |      0.119 | $5,000.00      | $593.06         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
