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
Final Rank Value (896.0) = Starting Rank Value (940.9) + Head To Head Adjustments (-44.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.395[<sup>1</sup>](#table2)
- Bounty Collected: 0.409[<sup>2</sup>](#table1)
- Opponent Network: 0.253[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.264<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 940.9
- 400 + ( ( 0.264 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 940.9


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
|          124 |       64 | 2024-08-02 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |   -11.65 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          123 |       66 | 2024-08-02 | inSanitY          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    19.27 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          122 |       96 | 2024-08-01 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -9.29 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          121 |      103 | 2024-08-01 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.17 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          120 |      148 | 2024-07-31 | Legacy            | L   | 1.000      | -            | -                | -                | -         |    -8.04 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          119 |      152 | 2024-07-31 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -16.71 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          118 |      154 | 2024-07-31 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -18.24 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          117 |      164 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.61 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          116 |      213 | 2024-07-30 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -2.25 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          115 |      279 | 2024-07-28 | Solid             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.13 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          114 |      300 | 2024-07-27 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.40 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          113 |      314 | 2024-07-26 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -19.43 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          112 |      430 | 2024-07-23 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -18.54 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          111 |      432 | 2024-07-23 | Fluxo             | W   | 1.000      | 0.143        | 0.124 (0.018)    | -                | 0 (0.000) |    25.48 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          110 |      439 | 2024-07-23 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.96 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          109 |      461 | 2024-07-22 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.81 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          108 |      518 | 2024-07-20 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -5.29 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          107 |      546 | 2024-07-19 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.63 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          106 |      550 | 2024-07-19 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -18.60 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          105 |      554 | 2024-07-19 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -5.63 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          104 |      583 | 2024-07-18 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.09 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          103 |      586 | 2024-07-18 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     8.66 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          102 |      594 | 2024-07-18 | ODDIK             | W   | 1.000      | 0.384        | 0.099 (0.038)    | 0.833 (0.320)    | -         |    22.30 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          101 |      607 | 2024-07-18 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -15.15 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          100 |      657 | 2024-07-17 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -2.34 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           99 |      660 | 2024-07-17 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -2.39 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           98 |      685 | 2024-07-17 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -18.51 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           97 |      717 | 2024-07-16 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -19.22 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           96 |      723 | 2024-07-16 | Solid             | W   | 1.000      | 0.450        | 0.025 (0.011)    | 0.836 (0.376)    | -         |    11.98 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           95 |      770 | 2024-07-15 | 9z Academy        | W   | 1.000      | -            | -                | -                | -         |     2.61 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           94 |      774 | 2024-07-15 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -10.18 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           93 |      775 | 2024-07-15 | Imperial          | W   | 1.000      | 0.450        | 0.236 (0.106)    | 0.685 (0.308)    | -         |    26.76 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           92 |      781 | 2024-07-15 | Imperial          | W   | 1.000      | 0.450        | 0.236 (0.106)    | 0.685 (0.308)    | -         |    27.87 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           91 |      819 | 2024-07-13 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |    12.40 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           90 |      841 | 2024-07-11 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -18.13 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           89 |      846 | 2024-07-11 | Hawks             | W   | 1.000      | -            | -                | -                | -         |     4.10 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           88 |      847 | 2024-07-11 | Galorys           | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.552 (0.204)    | -         |    13.89 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           87 |      865 | 2024-07-10 | Legacy            | L   | 1.000      | -            | -                | -                | -         |    -7.63 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           86 |      890 | 2024-07-09 | W7M               | W   | 1.000      | 0.371        | -                | 0.538 (0.199)    | -         |    11.69 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           85 |      980 | 2024-06-19 | inSanitY          | L   | 0.892      | -            | -                | -                | -         |    -9.01 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           84 |      982 | 2024-06-18 | Solid             | W   | 0.885      | 0.337        | -                | 0.836 (0.249)    | -         |    14.16 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           83 |     1302 | 2024-06-08 | Galorys           | L   | 0.817      | -            | -                | -                | -         |   -12.61 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           82 |     1347 | 2024-06-07 | Vikings KR        | L   | 0.811      | -            | -                | -                | -         |   -15.84 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           81 |     1381 | 2024-06-06 | Bounty Hunters    | L   | 0.807      | -            | -                | -                | -         |   -12.54 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           80 |     1421 | 2024-06-06 | Bounty Hunters    | L   | 0.804      | -            | -                | -                | -         |   -13.42 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           79 |     1542 | 2024-06-03 | Solid             | L   | 0.786      | -            | -                | -                | -         |   -12.96 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           78 |     1587 | 2024-06-01 | Smoke             | W   | 0.772      | -            | -                | -                | -         |     5.92 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           77 |     1675 | 2024-05-29 | Dusty Roots       | W   | 0.752      | -            | -                | -                | -         |     9.41 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           76 |     1729 | 2024-05-27 | Hawks             | L   | 0.738      | -            | -                | -                | -         |   -20.73 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           75 |     1820 | 2024-05-22 | BESTIA            | L   | 0.706      | -            | -                | -                | -         |    -6.99 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           74 |     1826 | 2024-05-22 | BESTIA            | L   | 0.706      | -            | -                | -                | -         |    -7.38 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           73 |     1864 | 2024-05-21 | Sharks            | W   | 0.700      | 0.450        | -                | 0.566 (0.178)    | -         |    13.55 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           72 |     1865 | 2024-05-21 | Sharks            | L   | 0.699      | -            | -                | -                | -         |    -8.54 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           71 |     1877 | 2024-05-21 | ODDIK             | W   | 0.698      | 0.303        | 0.099 (0.021)    | 0.833 (0.176)    | -         |    12.18 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           70 |     1914 | 2024-05-20 | Galorys           | W   | 0.691      | -            | -                | -                | -         |    10.50 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           69 |     1934 | 2024-05-19 | ODDIK             | L   | 0.686      | -            | -                | -                | -         |    -9.44 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           68 |     1960 | 2024-05-18 | Solid             | W   | 0.679      | -            | -                | -                | -         |    10.11 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           67 |     1997 | 2024-05-17 | Fluxo             | L   | 0.672      | -            | -                | -                | -         |    -5.51 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           66 |     2003 | 2024-05-17 | Hype              | W   | 0.671      | -            | -                | -                | -         |     9.73 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           65 |     2037 | 2024-05-16 | KRÜ               | W   | 0.665      | -            | -                | -                | -         |    10.81 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           64 |     2044 | 2024-05-16 | Yawara            | W   | 0.664      | -            | -                | -                | -         |     2.18 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           63 |     2080 | 2024-05-15 | Corinthians       | W   | 0.659      | -            | -                | -                | -         |     2.11 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           62 |     2083 | 2024-05-15 | Corinthians       | W   | 0.659      | -            | -                | -                | -         |     2.15 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           61 |     2090 | 2024-05-15 | Galorys           | W   | 0.658      | -            | -                | -                | -         |    10.92 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           60 |     2131 | 2024-05-14 | Galorys           | W   | 0.653      | -            | -                | -                | -         |    11.49 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           59 |     2136 | 2024-05-14 | Galorys           | L   | 0.652      | -            | -                | -                | -         |    -9.21 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           58 |     2152 | 2024-05-14 | Hype              | L   | 0.651      | -            | -                | -                | -         |   -10.50 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           57 |     2171 | 2024-05-13 | Intense           | W   | 0.645      | -            | -                | -                | -         |     6.34 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           56 |     2198 | 2024-05-12 | Solid             | L   | 0.638      | -            | -                | -                | -         |    -9.93 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           55 |     2231 | 2024-05-11 | Galorys           | L   | 0.631      | -            | -                | -                | -         |   -10.16 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           54 |     2310 | 2024-05-07 | inSanitY          | L   | 0.604      | -            | -                | -                | -         |    -9.24 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           53 |     2339 | 2024-05-05 | ODDIK             | L   | 0.593      | -            | -                | -                | -         |    -7.76 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           52 |     2397 | 2024-05-02 | ODDIK             | W   | 0.573      | 0.450        | 0.099 (0.025)    | 0.833 (0.215)    | -         |    10.81 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           51 |     2398 | 2024-05-02 | ODDIK             | L   | 0.573      | -            | -                | -                | -         |    -7.33 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           50 |     2421 | 2024-05-01 | 9z                | L   | 0.565      | -            | -                | -                | -         |    -0.57 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           49 |     2422 | 2024-05-01 | 9z                | L   | 0.565      | -            | -                | -                | -         |    -0.57 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           48 |     2799 | 2024-04-17 | MIBR              | L   | 0.472      | -            | -                | -                | -         |    -0.78 | RCF, RICIOLI, snow, urban0, yepz       |
|           47 |     2835 | 2024-04-16 | Galorys           | W   | 0.466      | -            | -                | -                | -         |     7.44 | RCF, RICIOLI, snow, urban0, yepz       |
|           46 |     2887 | 2024-04-13 | MIBR              | L   | 0.444      | -            | -                | -                | -         |    -0.73 | pr1sma, RCF, RICIOLI, urban0, yepz     |
|           45 |     2900 | 2024-04-12 | adalYamigos       | W   | 0.440      | -            | -                | -                | -         |     2.38 | RCF, RICIOLI, snow, urban0, yepz       |
|           44 |     2935 | 2024-04-11 | FURIA Academy     | W   | 0.430      | -            | -                | -                | -         |     1.39 | RCF, RICIOLI, snow, urban0, yepz       |
|           43 |     3009 | 2024-04-09 | paiN              | L   | 0.420      | -            | -                | -                | -         |    -0.75 | RCF, RICIOLI, snow, urban0, yepz       |
|           42 |     3014 | 2024-04-09 | paiN              | L   | 0.419      | -            | -                | -                | -         |    -0.75 | RCF, RICIOLI, snow, urban0, yepz       |
|           41 |     3085 | 2024-04-07 | adalYamigos       | L   | 0.406      | -            | -                | -                | -         |   -10.75 | RCF, RICIOLI, snow, urban0, yepz       |
|           40 |     3145 | 2024-04-04 | RED Canids        | W   | 0.386      | 0.450        | 0.077 (0.013)    | -                | -         |     9.04 | RCF, RICIOLI, snow, urban0, yepz       |
|           39 |     3150 | 2024-04-04 | RED Canids        | L   | 0.386      | -            | -                | -                | -         |    -3.14 | RCF, RICIOLI, snow, urban0, yepz       |
|           38 |     3185 | 2024-04-03 | Imperial          | L   | 0.379      | -            | -                | -                | -         |    -1.43 | RCF, RICIOLI, snow, urban0, yepz       |
|           37 |     3188 | 2024-04-03 | Imperial          | L   | 0.379      | -            | -                | -                | -         |    -1.45 | RCF, RICIOLI, snow, urban0, yepz       |
|           36 |     3319 | 2024-03-27 | MIBR              | L   | 0.333      | -            | -                | -                | -         |    -0.63 | RCF, RICIOLI, snow, urban0, yepz       |
|           35 |     3325 | 2024-03-27 | MIBR              | L   | 0.333      | -            | -                | -                | -         |    -0.63 | RCF, RICIOLI, snow, urban0, yepz       |
|           34 |     3499 | 2024-03-17 | ODDIK             | L   | 0.265      | -            | -                | -                | -         |    -3.35 | RCF, RICIOLI, snow, urban0, yepz       |
|           33 |     3519 | 2024-03-16 | MIBR Academy      | W   | 0.258      | -            | -                | -                | -         |     0.75 | RCF, RICIOLI, snow, urban0, yepz       |
|           32 |     3534 | 2024-03-15 | RED Canids        | L   | 0.252      | -            | -                | -                | -         |    -2.33 | RCF, RICIOLI, snow, urban0, yepz       |
|           31 |     3573 | 2024-03-14 | FURIA Academy     | W   | 0.245      | -            | -                | -                | -         |     0.74 | RCF, RICIOLI, snow, urban0, yepz       |
|           30 |     3594 | 2024-03-13 | RED Canids        | L   | 0.239      | -            | -                | -                | -         |    -2.20 | RCF, RICIOLI, snow, urban0, yepz       |
|           29 |     3600 | 2024-03-13 | Yawara            | L   | 0.238      | -            | -                | -                | -         |    -6.84 | RCF, RICIOLI, snow, urban0, yepz       |
|           28 |     3609 | 2024-03-13 | ODDIK             | L   | 0.237      | -            | -                | -                | -         |    -3.13 | RCF, RICIOLI, snow, urban0, yepz       |
|           27 |     3643 | 2024-03-12 | LA RUGONETA       | W   | 0.230      | -            | -                | -                | -         |     0.75 | RCF, RICIOLI, snow, urban0, yepz       |
|           26 |     3673 | 2024-03-10 | FURIA Academy     | W   | 0.219      | -            | -                | -                | -         |     0.61 | RCF, RICIOLI, snow, urban0, yepz       |
|           25 |     3693 | 2024-03-09 | Sharks            | W   | 0.212      | -            | -                | -                | -         |     3.80 | RCF, RICIOLI, snow, urban0, yepz       |
|           24 |     3743 | 2024-03-07 | Fluxo             | W   | 0.199      | 0.435        | 0.124 (0.011)    | -                | -         |     4.20 | RCF, RICIOLI, snow, urban0, yepz       |
|           23 |     3805 | 2024-03-05 | adalYamigos       | L   | 0.186      | -            | -                | -                | -         |    -5.09 | RCF, RICIOLI, snow, urban0, yepz       |
|           22 |     3807 | 2024-03-05 | adalYamigos       | L   | 0.186      | -            | -                | -                | -         |    -5.12 | RCF, RICIOLI, snow, urban0, yepz       |
|           21 |     3835 | 2024-03-04 | Fluxo             | L   | 0.180      | -            | -                | -                | -         |    -1.93 | RCF, RICIOLI, snow, urban0, yepz       |
|           20 |     3836 | 2024-03-04 | Fluxo             | L   | 0.179      | -            | -                | -                | -         |    -1.96 | RCF, RICIOLI, snow, urban0, yepz       |
|           19 |     4012 | 2024-02-24 | 2GAME             | W   | 0.120      | -            | -                | -                | -         |     0.71 | RCF, RICIOLI, snow, urban0, yepz       |
|           18 |     4017 | 2024-02-24 | 2GAME             | L   | 0.119      | -            | -                | -                | -         |    -3.07 | RCF, RICIOLI, snow, urban0, yepz       |
|           17 |     4072 | 2024-02-21 | Solid             | W   | 0.100      | -            | -                | -                | -         |     1.42 | RCF, RICIOLI, snow, urban0, yepz       |
|           16 |     4074 | 2024-02-21 | Solid             | L   | 0.100      | -            | -                | -                | -         |    -1.75 | RCF, RICIOLI, snow, urban0, yepz       |
|           15 |     4081 | 2024-02-21 | Sharks            | L   | 0.099      | -            | -                | -                | -         |    -1.43 | RCF, RICIOLI, snow, urban0, yepz       |
|           14 |     4109 | 2024-02-20 | 9z                | L   | 0.092      | -            | -                | -                | -         |    -0.10 | RCF, RICIOLI, snow, urban0, yepz       |
|           13 |     4112 | 2024-02-20 | W7M               | W   | 0.092      | -            | -                | -                | -         |     1.06 | RCF, RICIOLI, snow, urban0, yepz       |
|           12 |     4116 | 2024-02-20 | Sharks            | L   | 0.091      | -            | -                | -                | -         |    -1.31 | RCF, RICIOLI, snow, urban0, yepz       |
|           11 |     4156 | 2024-02-18 | Galorys           | L   | 0.079      | -            | -                | -                | -         |    -1.38 | RCF, RICIOLI, snow, urban0, yepz       |
|           10 |     4178 | 2024-02-17 | Solid             | W   | 0.073      | -            | -                | -                | -         |     1.01 | RCF, RICIOLI, snow, urban0, yepz       |
|            9 |     4205 | 2024-02-16 | BESTIA            | W   | 0.066      | -            | -                | -                | -         |     1.27 | RCF, RICIOLI, snow, urban0, yepz       |
|            8 |     4233 | 2024-02-15 | 9z                | L   | 0.059      | -            | -                | -                | -         |    -0.06 | RCF, RICIOLI, snow, urban0, yepz       |
|            7 |     4235 | 2024-02-15 | Sharks            | W   | 0.059      | -            | -                | -                | -         |     1.01 | RCF, RICIOLI, snow, urban0, yepz       |
|            6 |     4245 | 2024-02-15 | Flamengo          | W   | 0.057      | -            | -                | -                | -         |     0.14 | RCF, RICIOLI, snow, urban0, yepz       |
|            5 |     4263 | 2024-02-14 | O PLANO C         | W   | 0.053      | -            | -                | -                | -         |     0.08 | RCF, RICIOLI, snow, urban0, yepz       |
|            4 |     4306 | 2024-02-13 | W7M               | W   | 0.046      | -            | -                | -                | -         |     0.54 | RCF, RICIOLI, snow, urban0, yepz       |
|            3 |     4311 | 2024-02-13 | W7M               | L   | 0.046      | -            | -                | -                | -         |    -0.92 | RCF, RICIOLI, snow, urban0, yepz       |
|            2 |     4316 | 2024-02-13 | Galorys           | W   | 0.045      | -            | -                | -                | -         |     0.63 | RCF, RICIOLI, snow, urban0, yepz       |
|            1 |     4329 | 2024-02-12 | Dusty Roots       | W   | 0.038      | -            | -                | -                | -         |     0.45 | RCF, RICIOLI, snow, urban0, yepz       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,467.26)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $2,700.00      | $2,700.00       |
| 2024-06-19 |      0.892 | $2,150.00      | $1,917.68       |
| 2024-06-09 |      0.825 | $600.00        | $495.28         |
| 2024-05-21 |      0.698 | $3,500.00      | $2,443.19       |
| 2024-05-19 |      0.685 | $1,000.00      | $684.72         |
| 2024-03-14 |      0.245 | $5,000.00      | $1,226.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
