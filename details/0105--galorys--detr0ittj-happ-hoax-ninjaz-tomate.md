### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
<br />
Final Rank Value:  844.7<br />
<br />
Final Rank Value (844.7) = Starting Rank Value (905.5) + Head To Head Adjustments (-60.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.365[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.247<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.5
- 400 + ( ( 0.247 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 905.5


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
|           95 |      189 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.801 (0.361)    | 0 (0.000) |    23.49 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      195 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.51 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      292 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.44 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      310 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.805 (0.294)    | 0 (0.000) |    19.43 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      354 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.22 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      355 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      427 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.57 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      477 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.06 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      517 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.92 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      596 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.90 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      647 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.98 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      650 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.369 (0.166)    | 0 (0.000) |    13.33 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      663 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.01 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      715 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      736 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.30 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      761 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.02 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      767 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.463 (0.208)    | 0 (0.000) |    24.03 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      843 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      862 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.70 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      904 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.15 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      934 | 2024-06-30 | Vikings KR        | L   | 0.967      | -            | -                | -                | -         |   -16.40 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      941 | 2024-06-29 | inSanitY          | L   | 0.961      | -            | -                | -                | -         |    -8.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      952 | 2024-06-27 | Sharks            | L   | 0.948      | -            | -                | -                | -         |    -8.63 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      954 | 2024-06-27 | KRÜ               | W   | 0.948      | 0.333        | -                | 0.493 (0.156)    | 0 (0.000) |    15.56 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |      977 | 2024-06-18 | inSanitY          | L   | 0.888      | -            | -                | -                | -         |    -9.18 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1204 | 2024-06-09 | ODDIK             | L   | 0.828      | -            | -                | -                | -         |   -10.60 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1298 | 2024-06-08 | Case              | W   | 0.819      | 0.450        | 0.029 (0.011)    | 0.805 (0.297)    | 0 (0.000) |    12.65 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1327 | 2024-06-07 | Imperial          | L   | 0.814      | -            | -                | -                | -         |    -2.35 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1355 | 2024-06-07 | W7M               | L   | 0.813      | -            | -                | -                | -         |   -15.67 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1373 | 2024-06-06 | paiN              | L   | 0.809      | -            | -                | -                | -         |    -1.85 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1386 | 2024-06-06 | ex-Corinthians    | W   | 0.808      | -            | -                | -                | -         |     3.32 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1504 | 2024-06-04 | MIBR              | L   | 0.795      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1543 | 2024-06-03 | Intense           | L   | 0.787      | -            | -                | -                | -         |   -16.69 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1591 | 2024-06-01 | Hype              | L   | 0.774      | -            | -                | -                | -         |   -12.62 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1644 | 2024-05-30 | Hawks             | W   | 0.761      | -            | -                | -                | -         |     2.92 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1730 | 2024-05-27 | Dusty Roots       | W   | 0.739      | -            | -                | -                | -         |     9.83 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1910 | 2024-05-20 | Case              | L   | 0.694      | -            | -                | -                | -         |   -10.53 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1935 | 2024-05-19 | Solid             | W   | 0.687      | 0.303        | -                | 0.836 (0.174)    | -         |    10.39 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1961 | 2024-05-18 | ODDIK             | L   | 0.680      | -            | -                | -                | -         |    -8.97 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2077 | 2024-05-15 | Hype              | W   | 0.661      | -            | -                | -                | -         |    10.45 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2086 | 2024-05-15 | Case              | L   | 0.660      | -            | -                | -                | -         |   -10.96 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2127 | 2024-05-14 | Case              | L   | 0.655      | -            | -                | -                | -         |   -11.54 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2132 | 2024-05-14 | Case              | W   | 0.655      | 0.450        | 0.029 (0.009)    | 0.805 (0.237)    | -         |     9.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2144 | 2024-05-14 | 9z                | L   | 0.654      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2163 | 2024-05-13 | 9z                | L   | 0.648      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2168 | 2024-05-13 | Yawara            | W   | 0.647      | -            | -                | -                | -         |     2.01 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2188 | 2024-05-12 | KRÜ               | W   | 0.641      | -            | -                | -                | -         |    10.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2227 | 2024-05-11 | Case              | W   | 0.633      | 0.384        | -                | 0.805 (0.196)    | -         |    10.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2286 | 2024-05-08 | paiN              | L   | 0.614      | -            | -                | -                | -         |    -1.01 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2289 | 2024-05-08 | paiN              | L   | 0.614      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2311 | 2024-05-07 | KRÜ               | L   | 0.606      | -            | -                | -                | -         |    -9.28 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2346 | 2024-05-05 | W7M               | L   | 0.593      | -            | -                | -                | -         |   -11.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2654 | 2024-04-20 | Solid             | W   | 0.495      | 0.450        | -                | 0.836 (0.186)    | -         |     7.47 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2655 | 2024-04-20 | Solid             | L   | 0.495      | -            | -                | -                | -         |    -8.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2831 | 2024-04-16 | Case              | L   | 0.469      | -            | -                | -                | -         |    -7.48 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2869 | 2024-04-14 | MIBR              | L   | 0.454      | -            | -                | -                | -         |    -0.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2888 | 2024-04-13 | Fluxo             | W   | 0.446      | 0.435        | 0.124 (0.024)    | -                | -         |    10.08 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2897 | 2024-04-12 | Sharks            | W   | 0.441      | -            | -                | -                | -         |     4.58 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2917 | 2024-04-11 | Vikings KR        | L   | 0.435      | -            | -                | -                | -         |    -8.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2924 | 2024-04-11 | BESTIA            | W   | 0.433      | 0.435        | 0.095 (0.018)    | -                | -         |     8.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2952 | 2024-04-10 | MIBR              | L   | 0.429      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2956 | 2024-04-10 | MIBR              | L   | 0.428      | -            | -                | -                | -         |    -0.72 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3006 | 2024-04-09 | BESTIA            | W   | 0.422      | 0.450        | 0.095 (0.018)    | -                | -         |     8.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3011 | 2024-04-09 | BESTIA            | L   | 0.422      | -            | -                | -                | -         |    -5.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3084 | 2024-04-07 | paiN              | L   | 0.408      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3314 | 2024-03-27 | Fluxo             | W   | 0.336      | 0.450        | 0.124 (0.019)    | -                | -         |     7.49 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3320 | 2024-03-27 | Fluxo             | L   | 0.335      | -            | -                | -                | -         |    -3.11 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3360 | 2024-03-26 | 2GAME             | W   | 0.329      | -            | -                | -                | -         |     2.42 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3362 | 2024-03-26 | 2GAME             | W   | 0.328      | -            | -                | -                | -         |     2.47 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3556 | 2024-03-14 | W7M               | W   | 0.249      | -            | -                | -                | -         |     3.26 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3558 | 2024-03-14 | W7M               | W   | 0.248      | -            | -                | -                | -         |     3.32 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3602 | 2024-03-13 | RED Canids        | L   | 0.240      | -            | -                | -                | -         |    -1.94 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3646 | 2024-03-11 | LA RUGONETA       | L   | 0.228      | -            | -                | -                | -         |    -6.30 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3668 | 2024-03-10 | MIBR              | L   | 0.221      | -            | -                | -                | -         |    -0.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3726 | 2024-03-08 | ODDIK             | W   | 0.206      | 0.435        | 0.099 (0.009)    | -                | -         |     4.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     4007 | 2024-02-24 | Sharks            | L   | 0.122      | -            | -                | -                | -         |    -1.50 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4015 | 2024-02-24 | Sharks            | L   | 0.122      | -            | -                | -                | -         |    -1.51 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4038 | 2024-02-23 | Corinthians       | L   | 0.115      | -            | -                | -                | -         |    -3.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4039 | 2024-02-23 | Corinthians       | W   | 0.115      | -            | -                | -                | -         |     0.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4056 | 2024-02-22 | MIBR Academy      | W   | 0.108      | -            | -                | -                | -         |     0.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4071 | 2024-02-21 | adalYamigos       | L   | 0.102      | -            | -                | -                | -         |    -2.74 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4075 | 2024-02-21 | adalYamigos       | L   | 0.102      | -            | -                | -                | -         |    -2.75 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4082 | 2024-02-21 | Sharks            | L   | 0.100      | -            | -                | -                | -         |    -1.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4150 | 2024-02-18 | Sharks            | L   | 0.082      | -            | -                | -                | -         |    -1.06 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4152 | 2024-02-18 | Case              | W   | 0.081      | -            | -                | -                | -         |     1.42 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4178 | 2024-02-17 | Sharks            | W   | 0.074      | -            | -                | -                | -         |     1.39 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4181 | 2024-02-17 | Corinthians       | W   | 0.073      | -            | -                | -                | -         |     0.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4202 | 2024-02-16 | Flamengo          | W   | 0.068      | -            | -                | -                | -         |     0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4205 | 2024-02-16 | Imperial          | L   | 0.067      | -            | -                | -                | -         |    -0.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4210 | 2024-02-16 | Imperial          | L   | 0.067      | -            | -                | -                | -         |    -0.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4236 | 2024-02-15 | 9z Academy        | W   | 0.061      | -            | -                | -                | -         |     0.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4263 | 2024-02-14 | Solid             | L   | 0.055      | -            | -                | -                | -         |    -0.88 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4277 | 2024-02-14 | Sharks            | L   | 0.053      | -            | -                | -                | -         |    -0.68 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4312 | 2024-02-13 | Case              | L   | 0.047      | -            | -                | -                | -         |    -0.67 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4322 | 2024-02-12 | inSanitY          | W   | 0.041      | -            | -                | -                | -         |     0.07 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,668.38)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.894 | $1,075.00      | $961.40         |
| 2024-06-09 |      0.828 | $1,500.00      | $1,241.77       |
| 2024-04-15 |      0.461 | $5,000.00      | $2,304.98       |
| 2024-04-11 |      0.435 | $592.00        | $257.45         |
| 2024-02-22 |      0.108 | $1,417.00      | $152.95         |
| 2024-02-21 |      0.100 | $1,500.00      | $149.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
