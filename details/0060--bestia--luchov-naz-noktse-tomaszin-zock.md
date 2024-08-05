### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, naz, Noktse, tomaszin, zock<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  999.7<br />
<br />
Final Rank Value (999.7) = Starting Rank Value (1022.5) + Head To Head Adjustments (-22.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.446[<sup>2</sup>](#table1)
- Opponent Network: 0.275[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.304<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1022.5
- 400 + ( ( 0.304 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1022.5


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
|          103 |       41 | 2024-08-03 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.40 | luchov, naz, Noktse, tomaszin, zock    |
|          102 |       48 | 2024-08-03 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.08 | luchov, naz, Noktse, tomaszin, zock    |
|          101 |       77 | 2024-08-02 | Case              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.66 | luchov, naz, Noktse, tomaszin, zock    |
|          100 |       86 | 2024-08-02 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -17.49 | luchov, naz, Noktse, tomaszin, zock    |
|           99 |      107 | 2024-08-01 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.91 | luchov, naz, Noktse, tomaszin, zock    |
|           98 |      111 | 2024-08-01 | LaChampionsLiga   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.00 | luchov, naz, Noktse, tomaszin, zock    |
|           97 |      124 | 2024-08-01 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.84 | luchov, naz, Noktse, tomaszin, zock    |
|           96 |      206 | 2024-07-30 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.47 | luchov, naz, Noktse, tomaszin, zock    |
|           95 |      212 | 2024-07-30 | Galorys           | W   | 1.000      | 0.450        | -                | 0.550 (0.247)    | 0 (0.000) |     7.53 | luchov, naz, Noktse, tomaszin, zock    |
|           94 |      220 | 2024-07-30 | KRÜ               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.22 | luchov, naz, Noktse, tomaszin, zock    |
|           93 |      247 | 2024-07-29 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.99 | luchov, naz, Noktse, tomaszin, zock    |
|           92 |      276 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.82 | luchov, naz, Noktse, tomaszin, zock    |
|           91 |      358 | 2024-07-25 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.14 | luchov, naz, Noktse, tomaszin, zock    |
|           90 |      366 | 2024-07-25 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.02 | luchov, naz, Noktse, tomaszin, zock    |
|           89 |      435 | 2024-07-23 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.27 | luchov, naz, Noktse, tomaszin, zock    |
|           88 |      440 | 2024-07-23 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.57 | luchov, naz, Noktse, tomaszin, zock    |
|           87 |      475 | 2024-07-22 | Fluxo             | W   | 1.000      | 0.384        | 0.123 (0.047)    | 0.724 (0.278)    | -         |    23.68 | luchov, naz, Noktse, tomaszin, zock    |
|           86 |      500 | 2024-07-21 | RED Canids        | W   | 1.000      | 0.384        | 0.077 (0.030)    | 0.757 (0.291)    | -         |    23.59 | luchov, naz, Noktse, tomaszin, zock    |
|           85 |      557 | 2024-07-19 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.73 | luchov, naz, Noktse, tomaszin, zock    |
|           84 |      568 | 2024-07-19 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -21.87 | luchov, naz, Noktse, tomaszin, zock    |
|           83 |      608 | 2024-07-18 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -7.24 | luchov, naz, Noktse, tomaszin, zock    |
|           82 |      610 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     1.13 | luchov, naz, Noktse, tomaszin, zock    |
|           81 |      622 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.30 | luchov, naz, Noktse, tomaszin, zock    |
|           80 |      669 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -9.46 | luchov, naz, Noktse, tomaszin, zock    |
|           79 |      674 | 2024-07-17 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -10.20 | luchov, naz, Noktse, tomaszin, zock    |
|           78 |      684 | 2024-07-17 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.83 | luchov, naz, Noktse, tomaszin, zock    |
|           77 |      738 | 2024-07-16 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.832 (0.374)    | -         |    18.50 | luchov, naz, Noktse, tomaszin, zock    |
|           76 |      747 | 2024-07-16 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.76 | luchov, naz, Noktse, tomaszin, zock    |
|           75 |      796 | 2024-07-15 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     8.46 | luchov, naz, Noktse, tomaszin, zock    |
|           74 |      828 | 2024-07-13 | Intense           | W   | 1.000      | -            | -                | -                | -         |     6.79 | luchov, naz, Noktse, tomaszin, zock    |
|           73 |      841 | 2024-07-12 | SPORT             | L   | 1.000      | -            | -                | -                | -         |   -25.99 | luchov, naz, Noktse, tomaszin, zock    |
|           72 |      872 | 2024-07-10 | Sharks            | L   | 1.000      | -            | -                | -                | -         |   -16.99 | luchov, naz, Noktse, tomaszin, zock    |
|           71 |      900 | 2024-07-09 | SPORT             | W   | 1.000      | -            | -                | -                | -         |     4.53 | luchov, naz, Noktse, tomaszin, zock    |
|           70 |      915 | 2024-07-08 | Intense           | W   | 1.000      | -            | -                | -                | -         |     5.97 | luchov, naz, Noktse, tomaszin, zock    |
|           69 |      923 | 2024-07-08 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -19.16 | luchov, naz, Noktse, tomaszin, zock    |
|           68 |     1055 | 2024-06-15 | 9z                | L   | 0.860      | -            | -                | -                | -         |    -2.56 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |     1086 | 2024-06-14 | paiN              | L   | 0.854      | -            | -                | -                | -         |    -3.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |     1185 | 2024-06-10 | paiN              | L   | 0.829      | -            | -                | -                | -         |    -3.96 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |     1191 | 2024-06-10 | Bounty Hunters    | W   | 0.828      | -            | -                | -                | -         |     8.85 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |     1219 | 2024-06-09 | RED Canids        | W   | 0.823      | -            | -                | -                | -         |    17.50 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |     1247 | 2024-06-09 | Sharks            | L   | 0.820      | -            | -                | -                | -         |   -12.62 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |     1286 | 2024-06-08 | Solid             | W   | 0.815      | 0.371        | -                | 0.835 (0.252)    | -         |     7.88 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |     1301 | 2024-06-08 | Vikings KR        | L   | 0.814      | -            | -                | -                | -         |   -20.28 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |     1347 | 2024-06-07 | ODDIK             | W   | 0.809      | 0.450        | 0.099 (0.036)    | 0.832 (0.303)    | -         |     8.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |     1407 | 2024-06-06 | inSanitY          | L   | 0.802      | -            | -                | -                | -         |   -15.57 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |     1467 | 2024-06-05 | MIBR              | L   | 0.796      | -            | -                | -                | -         |    -2.55 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1519 | 2024-06-04 | Sharks            | L   | 0.789      | -            | -                | -                | -         |   -13.94 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1833 | 2024-05-22 | Case              | W   | 0.703      | 0.450        | -                | 0.805 (0.254)    | -         |     6.96 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1839 | 2024-05-22 | Case              | W   | 0.703      | 0.450        | -                | 0.805 (0.254)    | -         |     7.35 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1841 | 2024-05-22 | Fluxo             | W   | 0.702      | 0.450        | 0.123 (0.039)    | -                | -         |    12.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1844 | 2024-05-22 | Fluxo             | W   | 0.702      | 0.450        | 0.123 (0.039)    | -                | -         |    12.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1880 | 2024-05-21 | Smoke             | W   | 0.696      | -            | -                | -                | -         |     3.10 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1883 | 2024-05-21 | Smoke             | W   | 0.696      | -            | -                | -                | -         |     3.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1886 | 2024-05-21 | Imperial          | W   | 0.695      | 0.450        | 0.235 (0.074)    | -                | -         |    17.73 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1887 | 2024-05-21 | Imperial          | W   | 0.695      | 0.450        | 0.235 (0.073)    | -                | -         |    18.36 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1919 | 2024-05-20 | Corinthians       | W   | 0.689      | -            | -                | -                | -         |     1.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1921 | 2024-05-20 | 9z                | W   | 0.689      | 0.450        | 0.405 (0.125)    | -                | -         |    20.36 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1924 | 2024-05-20 | 9z                | L   | 0.688      | -            | -                | -                | -         |    -1.25 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     2006 | 2024-05-17 | Solid             | L   | 0.670      | -            | -                | -                | -         |   -13.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     2007 | 2024-05-17 | Solid             | W   | 0.669      | 0.450        | -                | 0.835 (0.251)    | -         |     8.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     2091 | 2024-05-15 | ODDIK             | W   | 0.656      | 0.450        | -                | 0.832 (0.245)    | -         |    10.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     2092 | 2024-05-15 | ODDIK             | W   | 0.656      | -            | -                | -                | -         |    10.76 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2102 | 2024-05-15 | Hype              | L   | 0.654      | -            | -                | -                | -         |   -12.27 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2153 | 2024-05-14 | Imperial          | L   | 0.649      | -            | -                | -                | -         |    -3.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2163 | 2024-05-14 | RED Canids        | L   | 0.648      | -            | -                | -                | -         |    -6.97 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     2203 | 2024-05-12 | Solid             | W   | 0.636      | -            | -                | -                | -         |     7.90 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     2210 | 2024-05-12 | O PLANO           | W   | 0.634      | -            | -                | -                | -         |     1.62 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     2237 | 2024-05-11 | paiN              | L   | 0.628      | -            | -                | -                | -         |    -1.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     2261 | 2024-05-10 | Imperial          | W   | 0.621      | 0.435        | 0.235 (0.063)    | -                | -         |    16.80 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     2280 | 2024-05-09 | Sharks            | W   | 0.616      | -            | -                | -                | -         |    10.67 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     2307 | 2024-05-08 | Vikings KR        | W   | 0.608      | -            | -                | -                | -         |     6.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     2338 | 2024-05-06 | Sharks            | L   | 0.596      | -            | -                | -                | -         |    -8.38 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     2577 | 2024-04-25 | RED Canids        | L   | 0.523      | -            | -                | -                | -         |    -5.00 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     2579 | 2024-04-25 | RED Canids        | L   | 0.522      | -            | -                | -                | -         |    -5.20 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     2844 | 2024-04-16 | O PLANO           | L   | 0.463      | -            | -                | -                | -         |   -13.43 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     2941 | 2024-04-11 | Galorys           | L   | 0.428      | -            | -                | -                | -         |    -8.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3023 | 2024-04-09 | Galorys           | L   | 0.416      | -            | -                | -                | -         |    -8.05 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     3028 | 2024-04-09 | Galorys           | W   | 0.416      | -            | -                | -                | -         |     5.13 | luchov, meyern, naz, Noktse, tomaszin  |
|           25 |     3064 | 2024-04-08 | RED Canids        | L   | 0.409      | -            | -                | -                | -         |    -4.65 | luchov, meyern, naz, Noktse, tomaszin  |
|           24 |     3107 | 2024-04-07 | Sharks            | L   | 0.400      | -            | -                | -                | -         |    -9.84 | luchov, meyern, naz, Noktse, tomaszin  |
|           23 |     3115 | 2024-04-06 | Fluxo             | W   | 0.396      | -            | -                | -                | -         |     7.54 | luchov, meyern, naz, Noktse, tomaszin  |
|           22 |     3152 | 2024-04-04 | adalYamigos       | L   | 0.383      | -            | -                | -                | -         |   -10.84 | luchov, meyern, naz, Noktse, tomaszin  |
|           21 |     3161 | 2024-04-04 | adalYamigos       | W   | 0.383      | -            | -                | -                | -         |     1.21 | luchov, meyern, naz, Noktse, tomaszin  |
|           20 |     3169 | 2024-04-04 | Imperial          | L   | 0.382      | -            | -                | -                | -         |    -2.15 | luchov, meyern, naz, Noktse, tomaszin  |
|           19 |     3206 | 2024-04-03 | Fluxo             | L   | 0.375      | -            | -                | -                | -         |    -5.06 | luchov, meyern, naz, Noktse, tomaszin  |
|           18 |     3242 | 2024-04-02 | Sharks            | W   | 0.370      | -            | -                | -                | -         |     2.36 | luchov, meyern, naz, Noktse, tomaszin  |
|           17 |     3247 | 2024-04-02 | Fluxo             | L   | 0.368      | -            | -                | -                | -         |    -5.08 | luchov, meyern, naz, Noktse, tomaszin  |
|           16 |     3336 | 2024-03-27 | W7M               | L   | 0.330      | -            | -                | -                | -         |    -7.67 | luchov, meyern, naz, Noktse, tomaszin  |
|           15 |     3340 | 2024-03-27 | W7M               | W   | 0.329      | -            | -                | -                | -         |     2.73 | luchov, meyern, naz, Noktse, tomaszin  |
|           14 |     3651 | 2024-03-12 | RED Canids        | L   | 0.228      | -            | -                | -                | -         |    -2.97 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     3661 | 2024-03-11 | FURIA Academy     | W   | 0.223      | -            | -                | -                | -         |     0.41 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     3684 | 2024-03-10 | adalYamigos       | L   | 0.216      | -            | -                | -                | -         |    -6.21 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     3732 | 2024-03-08 | FURIA Academy     | W   | 0.203      | -            | -                | -                | -         |     0.35 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     3897 | 2024-03-02 | Wildcard          | L   | 0.161      | -            | -                | -                | -         |    -3.54 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     3914 | 2024-03-01 | Liquid            | L   | 0.156      | -            | -                | -                | -         |    -0.20 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     4038 | 2024-02-24 | Imperial          | L   | 0.114      | -            | -                | -                | -         |    -0.75 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4057 | 2024-02-23 | 9z                | L   | 0.108      | -            | -                | -                | -         |    -0.17 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4067 | 2024-02-22 | Imperial          | W   | 0.103      | -            | -                | -                | -         |     2.58 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     4074 | 2024-02-22 | 9z                | L   | 0.102      | -            | -                | -                | -         |    -0.16 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     4096 | 2024-02-21 | W7M               | W   | 0.094      | -            | -                | -                | -         |     0.80 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     4173 | 2024-02-18 | FURIA Academy     | W   | 0.075      | -            | -                | -                | -         |     0.13 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     4218 | 2024-02-16 | Case              | L   | 0.063      | -            | -                | -                | -         |    -1.21 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     4337 | 2024-02-12 | FURIA Academy     | W   | 0.036      | -            | -                | -                | -         |     0.06 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,802.13)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-07-22 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-06-16 |      0.870 | $1,500.00      | $1,304.44       |
| 2024-06-10 |      0.829 | $4,000.00      | $3,317.31       |
| 2024-06-09 |      0.822 | $2,000.00      | $1,644.26       |
| 2024-05-12 |      0.635 | $5,000.00      | $3,176.39       |
| 2024-02-25 |      0.122 | $5,000.00      | $609.72         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
