### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [61](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  999.0<br />
<br />
Final Rank Value (999.0) = Starting Rank Value (1021.5) + Head To Head Adjustments (-22.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.446[<sup>2</sup>](#table1)
- Opponent Network: 0.272[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.303<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1021.5
- 400 + ( ( 0.303 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1021.5


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
|          103 |       49 | 2024-08-03 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.41 | luchov, naz, Noktse, tomaszin, zock    |
|          102 |       56 | 2024-08-03 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.08 | luchov, naz, Noktse, tomaszin, zock    |
|          101 |       85 | 2024-08-02 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.66 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |       94 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -17.48 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |      115 | 2024-08-01 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.92 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |      119 | 2024-08-01 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.00 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |      132 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.84 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      214 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.47 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      220 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.543 (0.244)    | 0 (0.000) |     7.53 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      228 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.22 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      255 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.00 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      284 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.82 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      366 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.14 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      374 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.03 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      443 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.28 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      448 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.57 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      483 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.123 (0.047)    | 0.716 (0.275)    | -         |    23.68 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      508 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.077 (0.029)    | 0.748 (0.287)    | -         |    23.59 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      565 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.74 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      576 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.86 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      616 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.25 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      618 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     1.13 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      630 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.29 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      677 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.47 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      682 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.21 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      692 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.83 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      746 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |    18.50 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      755 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.76 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      804 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.47 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      836 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.81 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      849 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -25.96 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      880 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.99 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      908 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.55 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      923 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     5.98 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      931 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.16 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1063 | 2024-06-15 | 9z                | L   | 0.859      | -            | -                | -                | -         |    -2.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1094 | 2024-06-14 | paiN              | L   | 0.853      | -            | -                | -                | -         |    -3.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1193 | 2024-06-10 | paiN              | L   | 0.828      | -            | -                | -                | -         |    -3.96 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1199 | 2024-06-10 | Bounty Hunters    | W   | 0.827      | -            | -                | -                | -         |     8.84 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1227 | 2024-06-09 | RED Canids        | W   | 0.822      | -            | -                | -                | -         |    17.48 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1255 | 2024-06-09 | Sharks            | L   | 0.819      | -            | -                | -                | -         |   -12.61 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1294 | 2024-06-08 | Solid             | W   | 0.814      | 0.371        | -                | 0.825 (0.249)    | -         |     7.87 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1309 | 2024-06-08 | Vikings KR        | L   | 0.813      | -            | -                | -                | -         |   -20.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1355 | 2024-06-07 | ODDIK             | W   | 0.807      | 0.450        | 0.099 (0.036)    | 0.822 (0.299)    | -         |     8.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1415 | 2024-06-06 | inSanitY          | L   | 0.801      | -            | -                | -                | -         |   -15.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1475 | 2024-06-05 | MIBR              | L   | 0.795      | -            | -                | -                | -         |    -2.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1527 | 2024-06-04 | Sharks            | L   | 0.788      | -            | -                | -                | -         |   -13.93 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1841 | 2024-05-22 | Case              | W   | 0.702      | 0.450        | -                | 0.795 (0.251)    | -         |     6.96 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1847 | 2024-05-22 | Case              | W   | 0.701      | 0.450        | -                | 0.795 (0.251)    | -         |     7.34 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1849 | 2024-05-22 | Fluxo             | W   | 0.701      | 0.450        | 0.123 (0.039)    | -                | -         |    12.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1852 | 2024-05-22 | Fluxo             | W   | 0.701      | 0.450        | 0.123 (0.039)    | -                | -         |    12.95 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1888 | 2024-05-21 | Smoke             | W   | 0.695      | -            | -                | -                | -         |     3.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1891 | 2024-05-21 | Smoke             | W   | 0.695      | -            | -                | -                | -         |     3.20 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1894 | 2024-05-21 | Imperial          | W   | 0.694      | 0.450        | 0.235 (0.073)    | -                | -         |    17.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1895 | 2024-05-21 | Imperial          | W   | 0.694      | 0.450        | 0.235 (0.073)    | -                | -         |    18.33 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1927 | 2024-05-20 | Corinthians       | W   | 0.688      | -            | -                | -                | -         |     1.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1929 | 2024-05-20 | 9z                | W   | 0.688      | 0.450        | 0.404 (0.125)    | -                | -         |    20.33 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1932 | 2024-05-20 | 9z                | L   | 0.687      | -            | -                | -                | -         |    -1.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     2014 | 2024-05-17 | Solid             | L   | 0.669      | -            | -                | -                | -         |   -13.13 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     2015 | 2024-05-17 | Solid             | W   | 0.668      | 0.450        | -                | 0.825 (0.248)    | -         |     7.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2099 | 2024-05-15 | ODDIK             | W   | 0.655      | 0.450        | -                | 0.822 (0.242)    | -         |    10.14 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2100 | 2024-05-15 | ODDIK             | W   | 0.654      | -            | -                | -                | -         |    10.74 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2110 | 2024-05-15 | Hype              | L   | 0.653      | -            | -                | -                | -         |   -12.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2161 | 2024-05-14 | Imperial          | L   | 0.648      | -            | -                | -                | -         |    -3.17 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2171 | 2024-05-14 | RED Canids        | L   | 0.647      | -            | -                | -                | -         |    -6.96 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2211 | 2024-05-12 | Solid             | W   | 0.634      | -            | -                | -                | -         |     7.88 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2218 | 2024-05-12 | O PLANO           | W   | 0.633      | -            | -                | -                | -         |     1.63 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2245 | 2024-05-11 | paiN              | L   | 0.627      | -            | -                | -                | -         |    -1.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2269 | 2024-05-10 | Imperial          | W   | 0.620      | 0.435        | 0.235 (0.063)    | -                | -         |    16.77 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2288 | 2024-05-09 | Sharks            | W   | 0.615      | -            | -                | -                | -         |    10.64 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2315 | 2024-05-08 | Vikings KR        | W   | 0.607      | -            | -                | -                | -         |     6.88 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2346 | 2024-05-06 | Sharks            | L   | 0.595      | -            | -                | -                | -         |    -8.38 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2585 | 2024-04-25 | RED Canids        | L   | 0.522      | -            | -                | -                | -         |    -4.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2587 | 2024-04-25 | RED Canids        | L   | 0.521      | -            | -                | -                | -         |    -5.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2852 | 2024-04-16 | O PLANO           | L   | 0.462      | -            | -                | -                | -         |   -13.40 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2949 | 2024-04-11 | Galorys           | L   | 0.427      | -            | -                | -                | -         |    -7.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3031 | 2024-04-09 | Galorys           | L   | 0.415      | -            | -                | -                | -         |    -8.03 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     3036 | 2024-04-09 | Galorys           | W   | 0.415      | -            | -                | -                | -         |     5.12 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3072 | 2024-04-08 | RED Canids        | L   | 0.408      | -            | -                | -                | -         |    -4.64 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3115 | 2024-04-07 | Sharks            | L   | 0.399      | -            | -                | -                | -         |    -9.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3123 | 2024-04-06 | Fluxo             | W   | 0.395      | -            | -                | -                | -         |     7.51 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3160 | 2024-04-04 | adalYamigos       | L   | 0.382      | -            | -                | -                | -         |   -10.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3169 | 2024-04-04 | adalYamigos       | W   | 0.381      | -            | -                | -                | -         |     1.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3177 | 2024-04-04 | Imperial          | L   | 0.380      | -            | -                | -                | -         |    -2.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3214 | 2024-04-03 | Fluxo             | L   | 0.374      | -            | -                | -                | -         |    -5.05 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3250 | 2024-04-02 | Sharks            | W   | 0.368      | -            | -                | -                | -         |     2.36 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3255 | 2024-04-02 | Fluxo             | L   | 0.367      | -            | -                | -                | -         |    -5.06 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3344 | 2024-03-27 | W7M               | L   | 0.329      | -            | -                | -                | -         |    -7.64 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3348 | 2024-03-27 | W7M               | W   | 0.328      | -            | -                | -                | -         |     2.73 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3659 | 2024-03-12 | RED Canids        | L   | 0.227      | -            | -                | -                | -         |    -2.95 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3669 | 2024-03-11 | FURIA Academy     | W   | 0.222      | -            | -                | -                | -         |     0.41 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3692 | 2024-03-10 | adalYamigos       | L   | 0.215      | -            | -                | -                | -         |    -6.18 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3740 | 2024-03-08 | FURIA Academy     | W   | 0.202      | -            | -                | -                | -         |     0.35 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3905 | 2024-03-02 | Wildcard          | L   | 0.160      | -            | -                | -                | -         |    -3.51 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3922 | 2024-03-01 | Liquid            | L   | 0.155      | -            | -                | -                | -         |    -0.19 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     4046 | 2024-02-24 | Imperial          | L   | 0.113      | -            | -                | -                | -         |    -0.75 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4065 | 2024-02-23 | 9z                | L   | 0.107      | -            | -                | -                | -         |    -0.17 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4075 | 2024-02-22 | Imperial          | W   | 0.102      | -            | -                | -                | -         |     2.55 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4082 | 2024-02-22 | 9z                | L   | 0.101      | -            | -                | -                | -         |    -0.16 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4104 | 2024-02-21 | W7M               | W   | 0.093      | -            | -                | -                | -         |     0.79 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4181 | 2024-02-18 | FURIA Academy     | W   | 0.073      | -            | -                | -                | -         |     0.13 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4226 | 2024-02-16 | Case              | L   | 0.062      | -            | -                | -                | -         |    -1.19 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4345 | 2024-02-12 | FURIA Academy     | W   | 0.035      | -            | -                | -                | -         |     0.06 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,782.69)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.869 | $1,500.00      | $1,302.78       |
| 2024-06-10 |      0.828 | $4,000.00      | $3,312.87       |
| 2024-06-09 |      0.821 | $2,000.00      | $1,642.04       |
| 2024-05-12 |      0.634 | $5,000.00      | $3,170.83       |
| 2024-02-25 |      0.121 | $5,000.00      | $604.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
