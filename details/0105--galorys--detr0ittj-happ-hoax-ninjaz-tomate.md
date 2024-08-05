### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
<br />
Final Rank Value:  844.8<br />
<br />
Final Rank Value (844.8) = Starting Rank Value (905.4) + Head To Head Adjustments (-60.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.365[<sup>2</sup>](#table1)
- Opponent Network: 0.227[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.247<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.4
- 400 + ( ( 0.247 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 905.4


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
|           95 |      193 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.802 (0.361)    | 0 (0.000) |    23.48 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      199 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.51 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      296 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.45 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      314 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.806 (0.294)    | 0 (0.000) |    19.43 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      358 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.22 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      359 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.24 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      431 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.57 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      481 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.06 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      521 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.92 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      600 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.91 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      651 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.97 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      654 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.370 (0.167)    | 0 (0.000) |    13.33 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      667 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.01 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      719 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.62 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      740 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.30 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      765 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.03 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      771 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.463 (0.209)    | 0 (0.000) |    24.02 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      847 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      866 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.70 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      908 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.16 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      938 | 2024-06-30 | Vikings KR        | L   | 0.964      | -            | -                | -                | -         |   -16.36 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      945 | 2024-06-29 | inSanitY          | L   | 0.958      | -            | -                | -                | -         |    -8.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      956 | 2024-06-27 | Sharks            | L   | 0.946      | -            | -                | -                | -         |    -8.62 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      958 | 2024-06-27 | KRÜ               | W   | 0.945      | 0.333        | -                | 0.494 (0.156)    | 0 (0.000) |    15.53 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |      981 | 2024-06-18 | inSanitY          | L   | 0.886      | -            | -                | -                | -         |    -9.16 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1208 | 2024-06-09 | ODDIK             | L   | 0.826      | -            | -                | -                | -         |   -10.57 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1302 | 2024-06-08 | Case              | W   | 0.817      | 0.450        | 0.029 (0.011)    | 0.806 (0.296)    | 0 (0.000) |    12.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1331 | 2024-06-07 | Imperial          | L   | 0.812      | -            | -                | -                | -         |    -2.36 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1359 | 2024-06-07 | W7M               | L   | 0.810      | -            | -                | -                | -         |   -15.62 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1377 | 2024-06-06 | paiN              | L   | 0.807      | -            | -                | -                | -         |    -1.85 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1390 | 2024-06-06 | ex-Corinthians    | W   | 0.806      | -            | -                | -                | -         |     3.31 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1508 | 2024-06-04 | MIBR              | L   | 0.793      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1547 | 2024-06-03 | Intense           | L   | 0.785      | -            | -                | -                | -         |   -16.64 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1595 | 2024-06-01 | Hype              | L   | 0.771      | -            | -                | -                | -         |   -12.58 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1648 | 2024-05-30 | Hawks             | W   | 0.759      | -            | -                | -                | -         |     2.91 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1734 | 2024-05-27 | Dusty Roots       | W   | 0.737      | -            | -                | -                | -         |     9.80 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1914 | 2024-05-20 | Case              | L   | 0.691      | -            | -                | -                | -         |   -10.50 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1939 | 2024-05-19 | Solid             | W   | 0.685      | 0.303        | -                | 0.836 (0.173)    | -         |    10.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1965 | 2024-05-18 | ODDIK             | L   | 0.678      | -            | -                | -                | -         |    -8.95 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2081 | 2024-05-15 | Hype              | W   | 0.659      | -            | -                | -                | -         |    10.41 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2090 | 2024-05-15 | Case              | L   | 0.658      | -            | -                | -                | -         |   -10.92 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2131 | 2024-05-14 | Case              | L   | 0.653      | -            | -                | -                | -         |   -11.49 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2136 | 2024-05-14 | Case              | W   | 0.652      | 0.450        | 0.029 (0.009)    | 0.806 (0.237)    | -         |     9.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2148 | 2024-05-14 | 9z                | L   | 0.651      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2167 | 2024-05-13 | 9z                | L   | 0.646      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2172 | 2024-05-13 | Yawara            | W   | 0.645      | -            | -                | -                | -         |     2.00 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2192 | 2024-05-12 | KRÜ               | W   | 0.639      | -            | -                | -                | -         |    10.73 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2231 | 2024-05-11 | Case              | W   | 0.631      | 0.384        | -                | 0.806 (0.195)    | -         |    10.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2290 | 2024-05-08 | paiN              | L   | 0.612      | -            | -                | -                | -         |    -1.01 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2293 | 2024-05-08 | paiN              | L   | 0.611      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2315 | 2024-05-07 | KRÜ               | L   | 0.604      | -            | -                | -                | -         |    -9.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2350 | 2024-05-05 | W7M               | L   | 0.590      | -            | -                | -                | -         |   -11.30 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2658 | 2024-04-20 | Solid             | W   | 0.493      | 0.450        | -                | 0.836 (0.185)    | -         |     7.43 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2659 | 2024-04-20 | Solid             | L   | 0.492      | -            | -                | -                | -         |    -8.28 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2835 | 2024-04-16 | Case              | L   | 0.466      | -            | -                | -                | -         |    -7.44 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2873 | 2024-04-14 | MIBR              | L   | 0.452      | -            | -                | -                | -         |    -0.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2892 | 2024-04-13 | Fluxo             | W   | 0.444      | 0.435        | 0.124 (0.024)    | -                | -         |    10.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2901 | 2024-04-12 | Sharks            | W   | 0.439      | -            | -                | -                | -         |     4.55 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2921 | 2024-04-11 | Vikings KR        | L   | 0.432      | -            | -                | -                | -         |    -8.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2928 | 2024-04-11 | BESTIA            | W   | 0.431      | 0.435        | 0.095 (0.018)    | -                | -         |     8.07 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2956 | 2024-04-10 | MIBR              | L   | 0.426      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2960 | 2024-04-10 | MIBR              | L   | 0.426      | -            | -                | -                | -         |    -0.72 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3010 | 2024-04-09 | BESTIA            | W   | 0.419      | 0.450        | 0.095 (0.018)    | -                | -         |     8.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3015 | 2024-04-09 | BESTIA            | L   | 0.419      | -            | -                | -                | -         |    -5.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3088 | 2024-04-07 | paiN              | L   | 0.405      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3318 | 2024-03-27 | Fluxo             | W   | 0.333      | 0.450        | 0.124 (0.019)    | -                | -         |     7.43 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3324 | 2024-03-27 | Fluxo             | L   | 0.333      | -            | -                | -                | -         |    -3.09 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3364 | 2024-03-26 | 2GAME             | W   | 0.327      | -            | -                | -                | -         |     2.39 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3366 | 2024-03-26 | 2GAME             | W   | 0.326      | -            | -                | -                | -         |     2.44 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3560 | 2024-03-14 | W7M               | W   | 0.246      | -            | -                | -                | -         |     3.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3562 | 2024-03-14 | W7M               | W   | 0.246      | -            | -                | -                | -         |     3.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3606 | 2024-03-13 | RED Canids        | L   | 0.238      | -            | -                | -                | -         |    -1.93 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3650 | 2024-03-11 | LA RUGONETA       | L   | 0.225      | -            | -                | -                | -         |    -6.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3672 | 2024-03-10 | MIBR              | L   | 0.219      | -            | -                | -                | -         |    -0.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3730 | 2024-03-08 | ODDIK             | W   | 0.204      | 0.435        | 0.099 (0.009)    | -                | -         |     4.14 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     4011 | 2024-02-24 | Sharks            | L   | 0.120      | -            | -                | -                | -         |    -1.48 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4019 | 2024-02-24 | Sharks            | L   | 0.119      | -            | -                | -                | -         |    -1.49 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4042 | 2024-02-23 | Corinthians       | L   | 0.113      | -            | -                | -                | -         |    -3.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4043 | 2024-02-23 | Corinthians       | W   | 0.113      | -            | -                | -                | -         |     0.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4060 | 2024-02-22 | MIBR Academy      | W   | 0.106      | -            | -                | -                | -         |     0.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4075 | 2024-02-21 | adalYamigos       | L   | 0.100      | -            | -                | -                | -         |    -2.68 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4079 | 2024-02-21 | adalYamigos       | L   | 0.099      | -            | -                | -                | -         |    -2.68 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4086 | 2024-02-21 | Sharks            | L   | 0.098      | -            | -                | -                | -         |    -1.26 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4154 | 2024-02-18 | Sharks            | L   | 0.080      | -            | -                | -                | -         |    -1.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4156 | 2024-02-18 | Case              | W   | 0.079      | -            | -                | -                | -         |     1.38 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4182 | 2024-02-17 | Sharks            | W   | 0.072      | -            | -                | -                | -         |     1.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4185 | 2024-02-17 | Corinthians       | W   | 0.071      | -            | -                | -                | -         |     0.22 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4206 | 2024-02-16 | Flamengo          | W   | 0.066      | -            | -                | -                | -         |     0.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4209 | 2024-02-16 | Imperial          | L   | 0.065      | -            | -                | -                | -         |    -0.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4214 | 2024-02-16 | Imperial          | L   | 0.064      | -            | -                | -                | -         |    -0.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4240 | 2024-02-15 | 9z Academy        | W   | 0.058      | -            | -                | -                | -         |     0.18 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4267 | 2024-02-14 | Solid             | L   | 0.053      | -            | -                | -                | -         |    -0.84 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4281 | 2024-02-14 | Sharks            | L   | 0.051      | -            | -                | -                | -         |    -0.65 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4316 | 2024-02-13 | Case              | L   | 0.045      | -            | -                | -                | -         |    -0.63 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4326 | 2024-02-12 | inSanitY          | W   | 0.039      | -            | -                | -                | -         |     0.07 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,641.95)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.892 | $1,075.00      | $958.84         |
| 2024-06-09 |      0.825 | $1,500.00      | $1,238.19       |
| 2024-04-15 |      0.459 | $5,000.00      | $2,293.06       |
| 2024-04-11 |      0.432 | $592.00        | $256.04         |
| 2024-02-22 |      0.106 | $1,417.00      | $149.57         |
| 2024-02-21 |      0.098 | $1,500.00      | $146.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
