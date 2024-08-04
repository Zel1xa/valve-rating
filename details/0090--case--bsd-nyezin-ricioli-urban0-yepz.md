### Roster Details<br />
Team Name: Case<br />
Roster: bsd, nyezin, RICIOLI, urban0, yepz<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [24]( ../standings_americas.md)<br />
<br />
Final Rank Value:  896.0<br />
<br />
Final Rank Value (896.0) = Starting Rank Value (940.8) + Head To Head Adjustments (-44.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.395[<sup>1</sup>](#table2)
- Bounty Collected: 0.409[<sup>2</sup>](#table1)
- Opponent Network: 0.254[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.264<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 940.8
- 400 + ( ( 0.264 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 940.8


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
|          124 |       60 | 2024-08-02 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |   -11.64 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          123 |       62 | 2024-08-02 | inSanitY          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    19.28 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          122 |       92 | 2024-08-01 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -9.28 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          121 |       99 | 2024-08-01 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.17 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          120 |      144 | 2024-07-31 | Legacy            | L   | 1.000      | -            | -                | -                | -         |    -8.03 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          119 |      148 | 2024-07-31 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -16.71 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          118 |      150 | 2024-07-31 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -18.24 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          117 |      160 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.61 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          116 |      209 | 2024-07-30 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -2.25 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          115 |      275 | 2024-07-28 | Solid             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.13 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          114 |      296 | 2024-07-27 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.41 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          113 |      310 | 2024-07-26 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -19.43 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          112 |      426 | 2024-07-23 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -18.54 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          111 |      428 | 2024-07-23 | Fluxo             | W   | 1.000      | 0.143        | 0.124 (0.018)    | -                | 0 (0.000) |    25.49 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          110 |      435 | 2024-07-23 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.96 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          109 |      457 | 2024-07-22 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.81 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          108 |      514 | 2024-07-20 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -5.28 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          107 |      542 | 2024-07-19 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.63 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          106 |      546 | 2024-07-19 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -18.60 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          105 |      550 | 2024-07-19 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -5.62 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          104 |      579 | 2024-07-18 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.09 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          103 |      582 | 2024-07-18 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     8.66 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          102 |      590 | 2024-07-18 | ODDIK             | W   | 1.000      | 0.384        | 0.099 (0.038)    | 0.832 (0.320)    | -         |    22.30 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          101 |      603 | 2024-07-18 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -15.15 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          100 |      653 | 2024-07-17 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -2.33 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           99 |      656 | 2024-07-17 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -2.39 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           98 |      681 | 2024-07-17 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -18.50 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           97 |      713 | 2024-07-16 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -19.22 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           96 |      719 | 2024-07-16 | Solid             | W   | 1.000      | 0.450        | 0.025 (0.011)    | 0.836 (0.376)    | -         |    11.99 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           95 |      766 | 2024-07-15 | 9z Academy        | W   | 1.000      | -            | -                | -                | -         |     2.61 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           94 |      770 | 2024-07-15 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -10.17 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           93 |      771 | 2024-07-15 | Imperial          | W   | 1.000      | 0.450        | 0.236 (0.106)    | 0.685 (0.308)    | -         |    26.79 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           92 |      777 | 2024-07-15 | Imperial          | W   | 1.000      | 0.450        | 0.236 (0.106)    | 0.685 (0.308)    | -         |    27.89 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           91 |      815 | 2024-07-13 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |    12.40 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           90 |      837 | 2024-07-11 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -18.13 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           89 |      842 | 2024-07-11 | Hawks             | W   | 1.000      | -            | -                | -                | -         |     4.10 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           88 |      843 | 2024-07-11 | Galorys           | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.552 (0.204)    | -         |    13.89 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           87 |      861 | 2024-07-10 | Legacy            | L   | 1.000      | -            | -                | -                | -         |    -7.62 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           86 |      886 | 2024-07-09 | W7M               | W   | 1.000      | 0.371        | -                | 0.537 (0.199)    | -         |    11.69 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           85 |      976 | 2024-06-19 | inSanitY          | L   | 0.894      | -            | -                | -                | -         |    -9.02 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           84 |      978 | 2024-06-18 | Solid             | W   | 0.888      | 0.337        | -                | 0.836 (0.250)    | -         |    14.20 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           83 |     1298 | 2024-06-08 | Galorys           | L   | 0.819      | -            | -                | -                | -         |   -12.65 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           82 |     1343 | 2024-06-07 | Vikings KR        | L   | 0.813      | -            | -                | -                | -         |   -15.89 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           81 |     1377 | 2024-06-06 | Bounty Hunters    | L   | 0.809      | -            | -                | -                | -         |   -12.57 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           80 |     1417 | 2024-06-06 | Bounty Hunters    | L   | 0.806      | -            | -                | -                | -         |   -13.46 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           79 |     1538 | 2024-06-03 | Solid             | L   | 0.788      | -            | -                | -                | -         |   -12.99 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           78 |     1583 | 2024-06-01 | Smoke             | W   | 0.775      | -            | -                | -                | -         |     5.93 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           77 |     1671 | 2024-05-29 | Dusty Roots       | W   | 0.754      | -            | -                | -                | -         |     9.43 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           76 |     1725 | 2024-05-27 | Hawks             | L   | 0.740      | -            | -                | -                | -         |   -20.79 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           75 |     1816 | 2024-05-22 | BESTIA            | L   | 0.709      | -            | -                | -                | -         |    -7.00 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           74 |     1822 | 2024-05-22 | BESTIA            | L   | 0.708      | -            | -                | -                | -         |    -7.40 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           73 |     1860 | 2024-05-21 | Sharks            | W   | 0.702      | 0.450        | -                | 0.565 (0.179)    | -         |    13.60 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           72 |     1861 | 2024-05-21 | Sharks            | L   | 0.702      | -            | -                | -                | -         |    -8.56 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           71 |     1873 | 2024-05-21 | ODDIK             | W   | 0.700      | 0.303        | 0.099 (0.021)    | 0.832 (0.176)    | -         |    12.22 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           70 |     1910 | 2024-05-20 | Galorys           | W   | 0.694      | -            | -                | -                | -         |    10.53 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           69 |     1930 | 2024-05-19 | ODDIK             | L   | 0.688      | -            | -                | -                | -         |    -9.47 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           68 |     1956 | 2024-05-18 | Solid             | W   | 0.681      | -            | -                | -                | -         |    10.15 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           67 |     1993 | 2024-05-17 | Fluxo             | L   | 0.675      | -            | -                | -                | -         |    -5.52 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           66 |     1999 | 2024-05-17 | Hype              | W   | 0.674      | -            | -                | -                | -         |     9.76 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           65 |     2033 | 2024-05-16 | KRÜ               | W   | 0.667      | -            | -                | -                | -         |    10.86 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           64 |     2040 | 2024-05-16 | Yawara            | W   | 0.666      | -            | -                | -                | -         |     2.19 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           63 |     2076 | 2024-05-15 | Corinthians       | W   | 0.661      | -            | -                | -                | -         |     2.12 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           62 |     2079 | 2024-05-15 | Corinthians       | W   | 0.661      | -            | -                | -                | -         |     2.16 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           61 |     2086 | 2024-05-15 | Galorys           | W   | 0.660      | -            | -                | -                | -         |    10.96 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           60 |     2127 | 2024-05-14 | Galorys           | W   | 0.655      | -            | -                | -                | -         |    11.54 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           59 |     2132 | 2024-05-14 | Galorys           | L   | 0.655      | -            | -                | -                | -         |    -9.24 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           58 |     2148 | 2024-05-14 | Hype              | L   | 0.653      | -            | -                | -                | -         |   -10.54 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           57 |     2167 | 2024-05-13 | Intense           | W   | 0.647      | -            | -                | -                | -         |     6.37 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           56 |     2194 | 2024-05-12 | Solid             | L   | 0.640      | -            | -                | -                | -         |    -9.96 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           55 |     2227 | 2024-05-11 | Galorys           | L   | 0.633      | -            | -                | -                | -         |   -10.20 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           54 |     2306 | 2024-05-07 | inSanitY          | L   | 0.607      | -            | -                | -                | -         |    -9.27 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           53 |     2335 | 2024-05-05 | ODDIK             | L   | 0.595      | -            | -                | -                | -         |    -7.79 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           52 |     2393 | 2024-05-02 | ODDIK             | W   | 0.575      | 0.450        | 0.099 (0.026)    | 0.832 (0.215)    | -         |    10.86 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           51 |     2394 | 2024-05-02 | ODDIK             | L   | 0.575      | -            | -                | -                | -         |    -7.36 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           50 |     2417 | 2024-05-01 | 9z                | L   | 0.568      | -            | -                | -                | -         |    -0.57 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           49 |     2418 | 2024-05-01 | 9z                | L   | 0.567      | -            | -                | -                | -         |    -0.57 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           48 |     2795 | 2024-04-17 | MIBR              | L   | 0.475      | -            | -                | -                | -         |    -0.78 | RCF, RICIOLI, snow, urban0, yepz       |
|           47 |     2831 | 2024-04-16 | Galorys           | W   | 0.469      | -            | -                | -                | -         |     7.48 | RCF, RICIOLI, snow, urban0, yepz       |
|           46 |     2883 | 2024-04-13 | MIBR              | L   | 0.447      | -            | -                | -                | -         |    -0.73 | pr1sma, RCF, RICIOLI, urban0, yepz     |
|           45 |     2896 | 2024-04-12 | adalYamigos       | W   | 0.442      | -            | -                | -                | -         |     2.40 | RCF, RICIOLI, snow, urban0, yepz       |
|           44 |     2931 | 2024-04-11 | FURIA Academy     | W   | 0.433      | -            | -                | -                | -         |     1.40 | RCF, RICIOLI, snow, urban0, yepz       |
|           43 |     3005 | 2024-04-09 | paiN              | L   | 0.422      | -            | -                | -                | -         |    -0.74 | RCF, RICIOLI, snow, urban0, yepz       |
|           42 |     3010 | 2024-04-09 | paiN              | L   | 0.422      | -            | -                | -                | -         |    -0.75 | RCF, RICIOLI, snow, urban0, yepz       |
|           41 |     3081 | 2024-04-07 | adalYamigos       | L   | 0.408      | -            | -                | -                | -         |   -10.80 | RCF, RICIOLI, snow, urban0, yepz       |
|           40 |     3141 | 2024-04-04 | RED Canids        | W   | 0.389      | 0.450        | 0.077 (0.013)    | -                | -         |     9.11 | RCF, RICIOLI, snow, urban0, yepz       |
|           39 |     3146 | 2024-04-04 | RED Canids        | L   | 0.388      | -            | -                | -                | -         |    -3.15 | RCF, RICIOLI, snow, urban0, yepz       |
|           38 |     3181 | 2024-04-03 | Imperial          | L   | 0.382      | -            | -                | -                | -         |    -1.43 | RCF, RICIOLI, snow, urban0, yepz       |
|           37 |     3184 | 2024-04-03 | Imperial          | L   | 0.382      | -            | -                | -                | -         |    -1.45 | RCF, RICIOLI, snow, urban0, yepz       |
|           36 |     3315 | 2024-03-27 | MIBR              | L   | 0.335      | -            | -                | -                | -         |    -0.63 | RCF, RICIOLI, snow, urban0, yepz       |
|           35 |     3321 | 2024-03-27 | MIBR              | L   | 0.335      | -            | -                | -                | -         |    -0.64 | RCF, RICIOLI, snow, urban0, yepz       |
|           34 |     3495 | 2024-03-17 | ODDIK             | L   | 0.267      | -            | -                | -                | -         |    -3.38 | RCF, RICIOLI, snow, urban0, yepz       |
|           33 |     3515 | 2024-03-16 | MIBR Academy      | W   | 0.260      | -            | -                | -                | -         |     0.76 | RCF, RICIOLI, snow, urban0, yepz       |
|           32 |     3530 | 2024-03-15 | RED Canids        | L   | 0.254      | -            | -                | -                | -         |    -2.35 | RCF, RICIOLI, snow, urban0, yepz       |
|           31 |     3569 | 2024-03-14 | FURIA Academy     | W   | 0.247      | -            | -                | -                | -         |     0.75 | RCF, RICIOLI, snow, urban0, yepz       |
|           30 |     3590 | 2024-03-13 | RED Canids        | L   | 0.241      | -            | -                | -                | -         |    -2.21 | RCF, RICIOLI, snow, urban0, yepz       |
|           29 |     3596 | 2024-03-13 | Yawara            | L   | 0.241      | -            | -                | -                | -         |    -6.90 | RCF, RICIOLI, snow, urban0, yepz       |
|           28 |     3605 | 2024-03-13 | ODDIK             | L   | 0.240      | -            | -                | -                | -         |    -3.15 | RCF, RICIOLI, snow, urban0, yepz       |
|           27 |     3639 | 2024-03-12 | LA RUGONETA       | W   | 0.233      | -            | -                | -                | -         |     0.76 | RCF, RICIOLI, snow, urban0, yepz       |
|           26 |     3669 | 2024-03-10 | FURIA Academy     | W   | 0.221      | -            | -                | -                | -         |     0.62 | RCF, RICIOLI, snow, urban0, yepz       |
|           25 |     3689 | 2024-03-09 | Sharks            | W   | 0.214      | -            | -                | -                | -         |     3.85 | RCF, RICIOLI, snow, urban0, yepz       |
|           24 |     3739 | 2024-03-07 | Fluxo             | W   | 0.201      | 0.435        | 0.124 (0.011)    | -                | -         |     4.25 | RCF, RICIOLI, snow, urban0, yepz       |
|           23 |     3801 | 2024-03-05 | adalYamigos       | L   | 0.189      | -            | -                | -                | -         |    -5.15 | RCF, RICIOLI, snow, urban0, yepz       |
|           22 |     3803 | 2024-03-05 | adalYamigos       | L   | 0.188      | -            | -                | -                | -         |    -5.18 | RCF, RICIOLI, snow, urban0, yepz       |
|           21 |     3831 | 2024-03-04 | Fluxo             | L   | 0.182      | -            | -                | -                | -         |    -1.96 | RCF, RICIOLI, snow, urban0, yepz       |
|           20 |     3832 | 2024-03-04 | Fluxo             | L   | 0.182      | -            | -                | -                | -         |    -1.98 | RCF, RICIOLI, snow, urban0, yepz       |
|           19 |     4008 | 2024-02-24 | 2GAME             | W   | 0.122      | -            | -                | -                | -         |     0.73 | RCF, RICIOLI, snow, urban0, yepz       |
|           18 |     4013 | 2024-02-24 | 2GAME             | L   | 0.122      | -            | -                | -                | -         |    -3.13 | RCF, RICIOLI, snow, urban0, yepz       |
|           17 |     4068 | 2024-02-21 | Solid             | W   | 0.103      | -            | -                | -                | -         |     1.45 | RCF, RICIOLI, snow, urban0, yepz       |
|           16 |     4070 | 2024-02-21 | Solid             | L   | 0.102      | -            | -                | -                | -         |    -1.79 | RCF, RICIOLI, snow, urban0, yepz       |
|           15 |     4077 | 2024-02-21 | Sharks            | L   | 0.101      | -            | -                | -                | -         |    -1.47 | RCF, RICIOLI, snow, urban0, yepz       |
|           14 |     4105 | 2024-02-20 | 9z                | L   | 0.095      | -            | -                | -                | -         |    -0.10 | RCF, RICIOLI, snow, urban0, yepz       |
|           13 |     4108 | 2024-02-20 | W7M               | W   | 0.095      | -            | -                | -                | -         |     1.09 | RCF, RICIOLI, snow, urban0, yepz       |
|           12 |     4112 | 2024-02-20 | Sharks            | L   | 0.093      | -            | -                | -                | -         |    -1.35 | RCF, RICIOLI, snow, urban0, yepz       |
|           11 |     4152 | 2024-02-18 | Galorys           | L   | 0.081      | -            | -                | -                | -         |    -1.42 | RCF, RICIOLI, snow, urban0, yepz       |
|           10 |     4174 | 2024-02-17 | Solid             | W   | 0.075      | -            | -                | -                | -         |     1.04 | RCF, RICIOLI, snow, urban0, yepz       |
|            9 |     4201 | 2024-02-16 | BESTIA            | W   | 0.068      | -            | -                | -                | -         |     1.32 | RCF, RICIOLI, snow, urban0, yepz       |
|            8 |     4229 | 2024-02-15 | 9z                | L   | 0.062      | -            | -                | -                | -         |    -0.06 | RCF, RICIOLI, snow, urban0, yepz       |
|            7 |     4231 | 2024-02-15 | Sharks            | W   | 0.061      | -            | -                | -                | -         |     1.05 | RCF, RICIOLI, snow, urban0, yepz       |
|            6 |     4241 | 2024-02-15 | Flamengo          | W   | 0.060      | -            | -                | -                | -         |     0.14 | RCF, RICIOLI, snow, urban0, yepz       |
|            5 |     4259 | 2024-02-14 | O PLANO C         | W   | 0.056      | -            | -                | -                | -         |     0.08 | RCF, RICIOLI, snow, urban0, yepz       |
|            4 |     4302 | 2024-02-13 | W7M               | W   | 0.049      | -            | -                | -                | -         |     0.56 | RCF, RICIOLI, snow, urban0, yepz       |
|            3 |     4307 | 2024-02-13 | W7M               | L   | 0.049      | -            | -                | -                | -         |    -0.97 | RCF, RICIOLI, snow, urban0, yepz       |
|            2 |     4312 | 2024-02-13 | Galorys           | W   | 0.047      | -            | -                | -                | -         |     0.67 | RCF, RICIOLI, snow, urban0, yepz       |
|            1 |     4325 | 2024-02-12 | Dusty Roots       | W   | 0.040      | -            | -                | -                | -         |     0.48 | RCF, RICIOLI, snow, urban0, yepz       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,496.47)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $2,700.00      | $2,700.00       |
| 2024-06-19 |      0.894 | $2,150.00      | $1,922.81       |
| 2024-06-09 |      0.828 | $600.00        | $496.71         |
| 2024-05-21 |      0.700 | $3,500.00      | $2,451.54       |
| 2024-05-19 |      0.687 | $1,000.00      | $687.11         |
| 2024-03-14 |      0.248 | $5,000.00      | $1,238.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
