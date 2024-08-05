### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Global Rank: [106](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
<br />
Final Rank Value:  844.8<br />
<br />
Final Rank Value (844.8) = Starting Rank Value (905.2) + Head To Head Adjustments (-60.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.365[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.247<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.2
- 400 + ( ( 0.247 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 905.2


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
|           95 |      206 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.801 (0.361)    | 0 (0.000) |    23.47 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      212 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.53 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      309 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.46 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      327 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.805 (0.294)    | 0 (0.000) |    19.43 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      371 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.22 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      372 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.24 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      444 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.56 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      494 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.06 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      534 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.93 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      613 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.93 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      664 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.97 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      667 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.370 (0.166)    | 0 (0.000) |    13.33 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      680 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.01 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      732 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.63 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      753 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.30 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      778 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.05 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      784 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.463 (0.208)    | 0 (0.000) |    24.00 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      860 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      879 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.71 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      921 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.16 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      951 | 2024-06-30 | Vikings KR        | L   | 0.961      | -            | -                | -                | -         |   -16.32 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      958 | 2024-06-29 | inSanitY          | L   | 0.955      | -            | -                | -                | -         |    -8.60 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      969 | 2024-06-27 | Sharks            | L   | 0.943      | -            | -                | -                | -         |    -8.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      971 | 2024-06-27 | KRÜ               | W   | 0.942      | 0.333        | -                | 0.493 (0.155)    | 0 (0.000) |    15.47 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |      994 | 2024-06-18 | inSanitY          | L   | 0.883      | -            | -                | -                | -         |    -9.15 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1221 | 2024-06-09 | ODDIK             | L   | 0.822      | -            | -                | -                | -         |   -10.54 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1315 | 2024-06-08 | Case              | W   | 0.814      | 0.450        | 0.029 (0.011)    | 0.805 (0.295)    | 0 (0.000) |    12.56 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1344 | 2024-06-07 | Imperial          | L   | 0.809      | -            | -                | -                | -         |    -2.37 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1372 | 2024-06-07 | W7M               | L   | 0.807      | -            | -                | -                | -         |   -15.56 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1390 | 2024-06-06 | paiN              | L   | 0.803      | -            | -                | -                | -         |    -1.85 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1403 | 2024-06-06 | ex-Corinthians    | W   | 0.802      | -            | -                | -                | -         |     3.29 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1521 | 2024-06-04 | MIBR              | L   | 0.789      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1560 | 2024-06-03 | Intense           | L   | 0.781      | -            | -                | -                | -         |   -16.57 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1608 | 2024-06-01 | Hype              | L   | 0.768      | -            | -                | -                | -         |   -12.52 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1661 | 2024-05-30 | Hawks             | W   | 0.755      | -            | -                | -                | -         |     2.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1747 | 2024-05-27 | Dusty Roots       | W   | 0.734      | -            | -                | -                | -         |     9.76 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1927 | 2024-05-20 | Case              | L   | 0.688      | -            | -                | -                | -         |   -10.45 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1952 | 2024-05-19 | Solid             | W   | 0.681      | 0.303        | -                | 0.835 (0.172)    | -         |    10.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1978 | 2024-05-18 | ODDIK             | L   | 0.675      | -            | -                | -                | -         |    -8.91 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2094 | 2024-05-15 | Hype              | W   | 0.655      | -            | -                | -                | -         |    10.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2103 | 2024-05-15 | Case              | L   | 0.654      | -            | -                | -                | -         |   -10.87 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2144 | 2024-05-14 | Case              | L   | 0.650      | -            | -                | -                | -         |   -11.43 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2149 | 2024-05-14 | Case              | W   | 0.649      | 0.450        | 0.029 (0.009)    | 0.805 (0.235)    | -         |     9.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2161 | 2024-05-14 | 9z                | L   | 0.648      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2180 | 2024-05-13 | 9z                | L   | 0.643      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2185 | 2024-05-13 | Yawara            | W   | 0.641      | -            | -                | -                | -         |     2.00 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2205 | 2024-05-12 | KRÜ               | W   | 0.635      | -            | -                | -                | -         |    10.67 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2244 | 2024-05-11 | Case              | W   | 0.627      | 0.384        | -                | 0.805 (0.194)    | -         |    10.11 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2303 | 2024-05-08 | paiN              | L   | 0.608      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2306 | 2024-05-08 | paiN              | L   | 0.608      | -            | -                | -                | -         |    -1.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2328 | 2024-05-07 | KRÜ               | L   | 0.600      | -            | -                | -                | -         |    -9.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2363 | 2024-05-05 | W7M               | L   | 0.587      | -            | -                | -                | -         |   -11.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2671 | 2024-04-20 | Solid             | W   | 0.489      | 0.450        | -                | 0.835 (0.184)    | -         |     7.38 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2672 | 2024-04-20 | Solid             | L   | 0.489      | -            | -                | -                | -         |    -8.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2848 | 2024-04-16 | Case              | L   | 0.463      | -            | -                | -                | -         |    -7.39 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2886 | 2024-04-14 | MIBR              | L   | 0.449      | -            | -                | -                | -         |    -0.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2905 | 2024-04-13 | Fluxo             | W   | 0.440      | 0.435        | 0.123 (0.024)    | -                | -         |     9.93 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2914 | 2024-04-12 | Sharks            | W   | 0.435      | -            | -                | -                | -         |     4.51 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2934 | 2024-04-11 | Vikings KR        | L   | 0.429      | -            | -                | -                | -         |    -8.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2941 | 2024-04-11 | BESTIA            | W   | 0.428      | 0.435        | 0.096 (0.018)    | -                | -         |     8.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2969 | 2024-04-10 | MIBR              | L   | 0.423      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2973 | 2024-04-10 | MIBR              | L   | 0.422      | -            | -                | -                | -         |    -0.72 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3023 | 2024-04-09 | BESTIA            | W   | 0.416      | 0.450        | 0.096 (0.018)    | -                | -         |     8.05 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3028 | 2024-04-09 | BESTIA            | L   | 0.416      | -            | -                | -                | -         |    -5.13 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3101 | 2024-04-07 | paiN              | L   | 0.402      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3331 | 2024-03-27 | Fluxo             | W   | 0.330      | 0.450        | 0.123 (0.018)    | -                | -         |     7.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3337 | 2024-03-27 | Fluxo             | L   | 0.329      | -            | -                | -                | -         |    -3.07 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3377 | 2024-03-26 | 2GAME             | W   | 0.323      | -            | -                | -                | -         |     2.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3379 | 2024-03-26 | 2GAME             | W   | 0.323      | -            | -                | -                | -         |     2.41 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3573 | 2024-03-14 | W7M               | W   | 0.243      | -            | -                | -                | -         |     3.18 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3575 | 2024-03-14 | W7M               | W   | 0.243      | -            | -                | -                | -         |     3.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3619 | 2024-03-13 | RED Canids        | L   | 0.235      | -            | -                | -                | -         |    -1.91 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3663 | 2024-03-11 | LA RUGONETA       | L   | 0.222      | -            | -                | -                | -         |    -6.15 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3685 | 2024-03-10 | MIBR              | L   | 0.216      | -            | -                | -                | -         |    -0.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3743 | 2024-03-08 | ODDIK             | W   | 0.200      | 0.435        | 0.099 (0.009)    | -                | -         |     4.07 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     4024 | 2024-02-24 | Sharks            | L   | 0.116      | -            | -                | -                | -         |    -1.44 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4032 | 2024-02-24 | Sharks            | L   | 0.116      | -            | -                | -                | -         |    -1.45 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4055 | 2024-02-23 | Corinthians       | L   | 0.110      | -            | -                | -                | -         |    -3.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4056 | 2024-02-23 | Corinthians       | W   | 0.109      | -            | -                | -                | -         |     0.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4073 | 2024-02-22 | MIBR Academy      | W   | 0.102      | -            | -                | -                | -         |     0.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4088 | 2024-02-21 | adalYamigos       | L   | 0.096      | -            | -                | -                | -         |    -2.59 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4092 | 2024-02-21 | adalYamigos       | L   | 0.096      | -            | -                | -                | -         |    -2.60 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4099 | 2024-02-21 | Sharks            | L   | 0.094      | -            | -                | -                | -         |    -1.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4167 | 2024-02-18 | Sharks            | L   | 0.076      | -            | -                | -                | -         |    -0.99 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4169 | 2024-02-18 | Case              | W   | 0.075      | -            | -                | -                | -         |     1.32 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4195 | 2024-02-17 | Sharks            | W   | 0.068      | -            | -                | -                | -         |     1.28 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4198 | 2024-02-17 | Corinthians       | W   | 0.068      | -            | -                | -                | -         |     0.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4219 | 2024-02-16 | Flamengo          | W   | 0.062      | -            | -                | -                | -         |     0.18 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4222 | 2024-02-16 | Imperial          | L   | 0.061      | -            | -                | -                | -         |    -0.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4227 | 2024-02-16 | Imperial          | L   | 0.061      | -            | -                | -                | -         |    -0.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4253 | 2024-02-15 | 9z Academy        | W   | 0.055      | -            | -                | -                | -         |     0.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4280 | 2024-02-14 | Solid             | L   | 0.050      | -            | -                | -                | -         |    -0.79 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4294 | 2024-02-14 | Sharks            | L   | 0.048      | -            | -                | -                | -         |    -0.61 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4329 | 2024-02-13 | Case              | L   | 0.041      | -            | -                | -                | -         |    -0.59 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4339 | 2024-02-12 | inSanitY          | W   | 0.036      | -            | -                | -                | -         |     0.06 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,605.01)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.889 | $1,075.00      | $955.26         |
| 2024-06-09 |      0.822 | $1,500.00      | $1,233.19       |
| 2024-04-15 |      0.455 | $5,000.00      | $2,276.39       |
| 2024-04-11 |      0.429 | $592.00        | $254.07         |
| 2024-02-22 |      0.102 | $1,417.00      | $144.85         |
| 2024-02-21 |      0.094 | $1,500.00      | $141.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
