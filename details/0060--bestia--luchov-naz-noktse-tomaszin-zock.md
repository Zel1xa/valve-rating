### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1002.8<br />
<br />
Final Rank Value (1002.8) = Starting Rank Value (1022.5) + Head To Head Adjustments (-19.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.447[<sup>2</sup>](#table1)
- Opponent Network: 0.276[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.304<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1022.5
- 400 + ( ( 0.304 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1022.5


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
|          101 |       38 | 2024-08-02 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.64 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |       48 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -17.50 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |       68 | 2024-08-01 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.90 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |       72 | 2024-08-01 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.00 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |       85 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.82 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      165 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.50 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      171 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | 0 (0.000) |     7.50 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      180 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.20 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      206 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.97 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      235 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.80 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      317 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.14 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      325 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.01 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      394 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.26 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      399 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.55 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      434 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.124 (0.048)    | 0.723 (0.278)    | 0 (0.000) |    23.70 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      459 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.077 (0.030)    | 0.743 (0.286)    | -         |    23.62 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      516 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.71 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      527 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.90 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      567 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.19 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      569 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     1.12 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      581 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.31 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      628 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.44 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      633 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.18 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      643 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.81 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      697 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.831 (0.374)    | -         |    18.48 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      707 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.78 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      755 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.45 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      787 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.78 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      800 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -26.01 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      831 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.99 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      859 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.50 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      874 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     5.95 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      882 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.17 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1014 | 2024-06-15 | 9z                | L   | 0.867      | -            | -                | -                | -         |    -2.58 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1045 | 2024-06-14 | paiN              | L   | 0.861      | -            | -                | -                | -         |    -3.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1144 | 2024-06-10 | paiN              | L   | 0.836      | -            | -                | -                | -         |    -3.97 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1150 | 2024-06-10 | Bounty Hunters    | W   | 0.835      | -            | -                | -                | -         |     8.91 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1178 | 2024-06-09 | RED Canids        | W   | 0.830      | -            | -                | -                | -         |    17.69 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1206 | 2024-06-09 | Sharks            | L   | 0.827      | -            | -                | -                | -         |   -12.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1245 | 2024-06-08 | Solid             | W   | 0.822      | 0.371        | -                | 0.835 (0.255)    | -         |     7.93 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1260 | 2024-06-08 | Vikings KR        | L   | 0.821      | -            | -                | -                | -         |   -20.47 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1306 | 2024-06-07 | ODDIK             | W   | 0.815      | 0.450        | 0.098 (0.036)    | 0.831 (0.305)    | -         |     8.94 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1366 | 2024-06-06 | inSanitY          | L   | 0.809      | -            | -                | -                | -         |   -15.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1426 | 2024-06-05 | MIBR              | L   | 0.803      | -            | -                | -                | -         |    -2.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1478 | 2024-06-04 | Sharks            | L   | 0.796      | -            | -                | -                | -         |   -14.06 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1792 | 2024-05-22 | Case              | W   | 0.710      | 0.450        | -                | 0.805 (0.257)    | -         |     7.01 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1798 | 2024-05-22 | Case              | W   | 0.709      | 0.450        | -                | 0.805 (0.257)    | -         |     7.41 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1800 | 2024-05-22 | Fluxo             | W   | 0.709      | 0.450        | 0.124 (0.040)    | -                | -         |    12.34 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1803 | 2024-05-22 | Fluxo             | W   | 0.708      | 0.450        | 0.124 (0.040)    | -                | -         |    13.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1839 | 2024-05-21 | Smoke             | W   | 0.703      | -            | -                | -                | -         |     3.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1842 | 2024-05-21 | Smoke             | W   | 0.703      | -            | -                | -                | -         |     3.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1845 | 2024-05-21 | Imperial          | W   | 0.702      | 0.450        | 0.237 (0.075)    | -                | -         |    17.96 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1846 | 2024-05-21 | Imperial          | W   | 0.702      | 0.450        | 0.237 (0.075)    | -                | -         |    18.60 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1878 | 2024-05-20 | Corinthians       | W   | 0.696      | -            | -                | -                | -         |     1.33 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1880 | 2024-05-20 | 9z                | W   | 0.695      | 0.450        | 0.405 (0.127)    | -                | -         |    20.57 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1883 | 2024-05-20 | 9z                | L   | 0.695      | -            | -                | -                | -         |    -1.26 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     1965 | 2024-05-17 | Solid             | L   | 0.676      | -            | -                | -                | -         |   -13.27 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     1966 | 2024-05-17 | Solid             | W   | 0.676      | 0.450        | -                | 0.835 (0.254)    | -         |     8.09 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2050 | 2024-05-15 | ODDIK             | W   | 0.663      | 0.450        | -                | 0.831 (0.248)    | -         |    10.27 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2051 | 2024-05-15 | ODDIK             | W   | 0.662      | -            | -                | -                | -         |    10.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2061 | 2024-05-15 | Hype              | L   | 0.661      | -            | -                | -                | -         |   -12.40 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2112 | 2024-05-14 | Imperial          | L   | 0.656      | -            | -                | -                | -         |    -3.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2122 | 2024-05-14 | RED Canids        | L   | 0.655      | -            | -                | -                | -         |    -7.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2162 | 2024-05-12 | Solid             | W   | 0.642      | -            | -                | -                | -         |     8.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2169 | 2024-05-12 | O PLANO           | W   | 0.641      | -            | -                | -                | -         |     1.64 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2196 | 2024-05-11 | paiN              | L   | 0.635      | -            | -                | -                | -         |    -1.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2220 | 2024-05-10 | Imperial          | W   | 0.628      | 0.435        | 0.237 (0.065)    | -                | -         |    17.04 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2239 | 2024-05-09 | Sharks            | W   | 0.623      | -            | -                | -                | -         |    10.82 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2266 | 2024-05-08 | Vikings KR        | W   | 0.615      | -            | -                | -                | -         |     6.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2297 | 2024-05-06 | Sharks            | L   | 0.603      | -            | -                | -                | -         |    -8.45 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2536 | 2024-04-25 | RED Canids        | L   | 0.530      | -            | -                | -                | -         |    -5.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2538 | 2024-04-25 | RED Canids        | L   | 0.529      | -            | -                | -                | -         |    -5.22 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2803 | 2024-04-16 | O PLANO           | L   | 0.470      | -            | -                | -                | -         |   -13.63 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2900 | 2024-04-11 | Galorys           | L   | 0.435      | -            | -                | -                | -         |    -8.13 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     2982 | 2024-04-09 | Galorys           | L   | 0.423      | -            | -                | -                | -         |    -8.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     2987 | 2024-04-09 | Galorys           | W   | 0.423      | -            | -                | -                | -         |     5.22 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3023 | 2024-04-08 | RED Canids        | L   | 0.416      | -            | -                | -                | -         |    -4.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3066 | 2024-04-07 | Sharks            | L   | 0.407      | -            | -                | -                | -         |   -10.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3074 | 2024-04-06 | Fluxo             | W   | 0.403      | -            | -                | -                | -         |     7.68 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3111 | 2024-04-04 | adalYamigos       | L   | 0.390      | -            | -                | -                | -         |   -11.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3120 | 2024-04-04 | adalYamigos       | W   | 0.389      | -            | -                | -                | -         |     1.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3128 | 2024-04-04 | Imperial          | L   | 0.388      | -            | -                | -                | -         |    -2.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3165 | 2024-04-03 | Fluxo             | L   | 0.382      | -            | -                | -                | -         |    -5.14 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3201 | 2024-04-02 | Sharks            | W   | 0.376      | -            | -                | -                | -         |     2.40 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3206 | 2024-04-02 | Fluxo             | L   | 0.375      | -            | -                | -                | -         |    -5.16 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3295 | 2024-03-27 | W7M               | L   | 0.336      | -            | -                | -                | -         |    -7.84 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3299 | 2024-03-27 | W7M               | W   | 0.336      | -            | -                | -                | -         |     2.78 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3610 | 2024-03-12 | RED Canids        | L   | 0.235      | -            | -                | -                | -         |    -3.04 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3620 | 2024-03-11 | FURIA Academy     | W   | 0.230      | -            | -                | -                | -         |     0.42 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3643 | 2024-03-10 | adalYamigos       | L   | 0.223      | -            | -                | -                | -         |    -6.40 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3691 | 2024-03-08 | FURIA Academy     | W   | 0.210      | -            | -                | -                | -         |     0.37 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3856 | 2024-03-02 | Wildcard          | L   | 0.168      | -            | -                | -                | -         |    -3.47 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3873 | 2024-03-01 | Liquid            | L   | 0.163      | -            | -                | -                | -         |    -0.21 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     3997 | 2024-02-24 | Imperial          | L   | 0.121      | -            | -                | -                | -         |    -0.79 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4016 | 2024-02-23 | 9z                | L   | 0.115      | -            | -                | -                | -         |    -0.18 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4026 | 2024-02-22 | Imperial          | W   | 0.110      | -            | -                | -                | -         |     2.76 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4033 | 2024-02-22 | 9z                | L   | 0.109      | -            | -                | -                | -         |    -0.17 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4055 | 2024-02-21 | W7M               | W   | 0.101      | -            | -                | -                | -         |     0.85 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4132 | 2024-02-18 | FURIA Academy     | W   | 0.081      | -            | -                | -                | -         |     0.14 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4177 | 2024-02-16 | Case              | L   | 0.070      | -            | -                | -                | -         |    -1.34 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4296 | 2024-02-12 | FURIA Academy     | W   | 0.043      | -            | -                | -                | -         |     0.07 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,920.82)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.876 | $1,500.00      | $1,314.62       |
| 2024-06-10 |      0.836 | $4,000.00      | $3,344.44       |
| 2024-06-09 |      0.829 | $2,000.00      | $1,657.82       |
| 2024-05-12 |      0.642 | $5,000.00      | $3,210.30       |
| 2024-02-25 |      0.129 | $5,000.00      | $643.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
