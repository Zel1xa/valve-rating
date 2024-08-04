### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [59](../standings_global.md)<br />
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

The average of these factors is 0.305<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1022.5
- 400 + ( ( 0.305 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1022.5


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
|          101 |       30 | 2024-08-02 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.64 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |       40 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -17.50 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |       60 | 2024-08-01 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.90 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |       64 | 2024-08-01 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.00 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |       77 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.82 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      157 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.50 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      163 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | 0 (0.000) |     7.50 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      172 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.20 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      198 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.97 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      227 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.80 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      309 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.14 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      317 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.01 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      386 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.25 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      391 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.55 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      426 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.124 (0.048)    | 0.723 (0.278)    | 0 (0.000) |    23.70 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      451 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.077 (0.030)    | 0.743 (0.286)    | -         |    23.62 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      508 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.71 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      519 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.90 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      559 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.19 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      561 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     1.12 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      573 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.31 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      620 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.43 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      625 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.17 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      635 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.81 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      689 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.831 (0.374)    | -         |    18.49 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      699 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.78 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      747 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.45 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      779 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.78 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      792 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -26.01 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      823 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.99 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      851 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.50 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      866 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     5.95 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      874 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.16 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1006 | 2024-06-15 | 9z                | L   | 0.868      | -            | -                | -                | -         |    -2.63 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1037 | 2024-06-14 | paiN              | L   | 0.862      | -            | -                | -                | -         |    -3.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1136 | 2024-06-10 | paiN              | L   | 0.837      | -            | -                | -                | -         |    -3.97 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1142 | 2024-06-10 | Bounty Hunters    | W   | 0.836      | -            | -                | -                | -         |     8.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1170 | 2024-06-09 | RED Canids        | W   | 0.831      | -            | -                | -                | -         |    17.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1198 | 2024-06-09 | Sharks            | L   | 0.828      | -            | -                | -                | -         |   -12.71 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1237 | 2024-06-08 | Solid             | W   | 0.823      | 0.371        | -                | 0.835 (0.255)    | -         |     7.94 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1252 | 2024-06-08 | Vikings KR        | L   | 0.822      | -            | -                | -                | -         |   -20.48 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1298 | 2024-06-07 | ODDIK             | W   | 0.816      | 0.450        | 0.098 (0.036)    | 0.831 (0.305)    | -         |     8.95 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1358 | 2024-06-06 | inSanitY          | L   | 0.809      | -            | -                | -                | -         |   -15.71 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1418 | 2024-06-05 | MIBR              | L   | 0.803      | -            | -                | -                | -         |    -2.56 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1470 | 2024-06-04 | Sharks            | L   | 0.797      | -            | -                | -                | -         |   -14.07 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1784 | 2024-05-22 | Case              | W   | 0.710      | 0.450        | -                | 0.805 (0.257)    | -         |     7.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1790 | 2024-05-22 | Case              | W   | 0.710      | 0.450        | -                | 0.805 (0.257)    | -         |     7.42 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1792 | 2024-05-22 | Fluxo             | W   | 0.709      | 0.450        | 0.124 (0.040)    | -                | -         |    12.35 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1795 | 2024-05-22 | Fluxo             | W   | 0.709      | 0.450        | 0.124 (0.040)    | -                | -         |    13.14 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1831 | 2024-05-21 | Smoke             | W   | 0.704      | -            | -                | -                | -         |     3.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1834 | 2024-05-21 | Smoke             | W   | 0.703      | -            | -                | -                | -         |     3.22 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1837 | 2024-05-21 | Imperial          | W   | 0.703      | 0.450        | 0.237 (0.075)    | -                | -         |    17.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1838 | 2024-05-21 | Imperial          | W   | 0.703      | 0.450        | 0.237 (0.075)    | -                | -         |    18.62 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1870 | 2024-05-20 | Corinthians       | W   | 0.697      | -            | -                | -                | -         |     1.33 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1872 | 2024-05-20 | 9z                | W   | 0.696      | 0.450        | 0.406 (0.127)    | -                | -         |    20.58 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1875 | 2024-05-20 | 9z                | L   | 0.696      | -            | -                | -                | -         |    -1.26 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     1957 | 2024-05-17 | Solid             | L   | 0.677      | -            | -                | -                | -         |   -13.28 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     1958 | 2024-05-17 | Solid             | W   | 0.677      | 0.450        | -                | 0.835 (0.254)    | -         |     8.10 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2042 | 2024-05-15 | ODDIK             | W   | 0.663      | 0.450        | -                | 0.831 (0.248)    | -         |    10.28 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2043 | 2024-05-15 | ODDIK             | W   | 0.663      | -            | -                | -                | -         |    10.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2053 | 2024-05-15 | Hype              | L   | 0.662      | -            | -                | -                | -         |   -12.41 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2104 | 2024-05-14 | Imperial          | L   | 0.656      | -            | -                | -                | -         |    -3.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2114 | 2024-05-14 | RED Canids        | L   | 0.655      | -            | -                | -                | -         |    -7.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2154 | 2024-05-12 | Solid             | W   | 0.643      | -            | -                | -                | -         |     8.01 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2161 | 2024-05-12 | O PLANO           | W   | 0.642      | -            | -                | -                | -         |     1.65 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2188 | 2024-05-11 | paiN              | L   | 0.635      | -            | -                | -                | -         |    -1.79 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2212 | 2024-05-10 | Imperial          | W   | 0.629      | 0.435        | 0.237 (0.065)    | -                | -         |    17.07 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2231 | 2024-05-09 | Sharks            | W   | 0.624      | -            | -                | -                | -         |    10.84 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2258 | 2024-05-08 | Vikings KR        | W   | 0.615      | -            | -                | -                | -         |     7.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2289 | 2024-05-06 | Sharks            | L   | 0.604      | -            | -                | -                | -         |    -8.45 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2528 | 2024-04-25 | RED Canids        | L   | 0.530      | -            | -                | -                | -         |    -5.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2530 | 2024-04-25 | RED Canids        | L   | 0.530      | -            | -                | -                | -         |    -5.22 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2795 | 2024-04-16 | O PLANO           | L   | 0.471      | -            | -                | -                | -         |   -13.65 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2892 | 2024-04-11 | Galorys           | L   | 0.435      | -            | -                | -                | -         |    -8.14 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     2974 | 2024-04-09 | Galorys           | L   | 0.424      | -            | -                | -                | -         |    -8.20 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     2979 | 2024-04-09 | Galorys           | W   | 0.423      | -            | -                | -                | -         |     5.23 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3015 | 2024-04-08 | RED Canids        | L   | 0.417      | -            | -                | -                | -         |    -4.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3058 | 2024-04-07 | Sharks            | L   | 0.408      | -            | -                | -                | -         |   -10.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3066 | 2024-04-06 | Fluxo             | W   | 0.404      | -            | -                | -                | -         |     7.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3103 | 2024-04-04 | adalYamigos       | L   | 0.391      | -            | -                | -                | -         |   -11.03 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3112 | 2024-04-04 | adalYamigos       | W   | 0.390      | -            | -                | -                | -         |     1.26 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3120 | 2024-04-04 | Imperial          | L   | 0.389      | -            | -                | -                | -         |    -2.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3157 | 2024-04-03 | Fluxo             | L   | 0.383      | -            | -                | -                | -         |    -5.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3193 | 2024-04-02 | Sharks            | W   | 0.377      | -            | -                | -                | -         |     2.41 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3198 | 2024-04-02 | Fluxo             | L   | 0.376      | -            | -                | -                | -         |    -5.17 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3287 | 2024-03-27 | W7M               | L   | 0.337      | -            | -                | -                | -         |    -7.85 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3291 | 2024-03-27 | W7M               | W   | 0.337      | -            | -                | -                | -         |     2.79 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3602 | 2024-03-12 | RED Canids        | L   | 0.235      | -            | -                | -                | -         |    -3.05 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3612 | 2024-03-11 | FURIA Academy     | W   | 0.230      | -            | -                | -                | -         |     0.42 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3635 | 2024-03-10 | adalYamigos       | L   | 0.224      | -            | -                | -                | -         |    -6.42 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3683 | 2024-03-08 | FURIA Academy     | W   | 0.210      | -            | -                | -                | -         |     0.37 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3848 | 2024-03-02 | Wildcard          | L   | 0.169      | -            | -                | -                | -         |    -3.48 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3865 | 2024-03-01 | Liquid            | L   | 0.163      | -            | -                | -                | -         |    -0.34 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     3989 | 2024-02-24 | Imperial          | L   | 0.122      | -            | -                | -                | -         |    -0.79 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4008 | 2024-02-23 | 9z                | L   | 0.116      | -            | -                | -                | -         |    -0.19 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4018 | 2024-02-22 | Imperial          | W   | 0.110      | -            | -                | -                | -         |     2.78 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4025 | 2024-02-22 | 9z                | L   | 0.109      | -            | -                | -                | -         |    -0.17 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4047 | 2024-02-21 | W7M               | W   | 0.102      | -            | -                | -                | -         |     0.86 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4124 | 2024-02-18 | FURIA Academy     | W   | 0.082      | -            | -                | -                | -         |     0.14 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4169 | 2024-02-16 | Case              | L   | 0.070      | -            | -                | -                | -         |    -1.35 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4288 | 2024-02-12 | FURIA Academy     | W   | 0.044      | -            | -                | -                | -         |     0.07 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,933.38)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.877 | $1,500.00      | $1,315.69       |
| 2024-06-10 |      0.837 | $4,000.00      | $3,347.31       |
| 2024-06-09 |      0.830 | $2,000.00      | $1,659.26       |
| 2024-05-12 |      0.643 | $5,000.00      | $3,213.89       |
| 2024-02-25 |      0.129 | $5,000.00      | $647.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
