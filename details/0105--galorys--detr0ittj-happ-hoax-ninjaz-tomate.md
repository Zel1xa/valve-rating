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
|           95 |      188 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.801 (0.361)    | 0 (0.000) |    23.49 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      194 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.51 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      291 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.44 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      309 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.805 (0.294)    | 0 (0.000) |    19.43 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      353 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.22 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      354 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      426 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.57 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      476 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.06 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      516 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.91 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      595 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.90 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      646 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.98 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      649 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.369 (0.166)    | 0 (0.000) |    13.33 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      662 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.01 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      714 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      735 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.30 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      760 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.01 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      766 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.463 (0.208)    | 0 (0.000) |    24.04 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      842 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      861 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.70 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      903 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.15 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      933 | 2024-06-30 | Vikings KR        | L   | 0.967      | -            | -                | -                | -         |   -16.40 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      940 | 2024-06-29 | inSanitY          | L   | 0.961      | -            | -                | -                | -         |    -8.62 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      951 | 2024-06-27 | Sharks            | L   | 0.949      | -            | -                | -                | -         |    -8.63 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      953 | 2024-06-27 | KRÜ               | W   | 0.948      | 0.333        | -                | 0.493 (0.156)    | 0 (0.000) |    15.57 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |      976 | 2024-06-18 | inSanitY          | L   | 0.889      | -            | -                | -                | -         |    -9.18 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1203 | 2024-06-09 | ODDIK             | L   | 0.828      | -            | -                | -                | -         |   -10.60 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1297 | 2024-06-08 | Case              | W   | 0.820      | 0.450        | 0.029 (0.011)    | 0.805 (0.297)    | 0 (0.000) |    12.65 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1326 | 2024-06-07 | Imperial          | L   | 0.815      | -            | -                | -                | -         |    -2.35 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1354 | 2024-06-07 | W7M               | L   | 0.813      | -            | -                | -                | -         |   -15.67 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1372 | 2024-06-06 | paiN              | L   | 0.809      | -            | -                | -                | -         |    -1.85 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1385 | 2024-06-06 | ex-Corinthians    | W   | 0.808      | -            | -                | -                | -         |     3.32 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1503 | 2024-06-04 | MIBR              | L   | 0.795      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1542 | 2024-06-03 | Intense           | L   | 0.787      | -            | -                | -                | -         |   -16.70 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1590 | 2024-06-01 | Hype              | L   | 0.774      | -            | -                | -                | -         |   -12.62 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1643 | 2024-05-30 | Hawks             | W   | 0.761      | -            | -                | -                | -         |     2.92 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1729 | 2024-05-27 | Dusty Roots       | W   | 0.740      | -            | -                | -                | -         |     9.83 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1909 | 2024-05-20 | Case              | L   | 0.694      | -            | -                | -                | -         |   -10.54 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1934 | 2024-05-19 | Solid             | W   | 0.687      | 0.303        | -                | 0.836 (0.174)    | -         |    10.39 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1960 | 2024-05-18 | ODDIK             | L   | 0.681      | -            | -                | -                | -         |    -8.98 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2076 | 2024-05-15 | Hype              | W   | 0.661      | -            | -                | -                | -         |    10.45 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2085 | 2024-05-15 | Case              | L   | 0.660      | -            | -                | -                | -         |   -10.97 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2126 | 2024-05-14 | Case              | L   | 0.656      | -            | -                | -                | -         |   -11.54 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2131 | 2024-05-14 | Case              | W   | 0.655      | 0.450        | 0.029 (0.009)    | 0.805 (0.237)    | -         |     9.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2143 | 2024-05-14 | 9z                | L   | 0.654      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2162 | 2024-05-13 | 9z                | L   | 0.649      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2167 | 2024-05-13 | Yawara            | W   | 0.647      | -            | -                | -                | -         |     2.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2187 | 2024-05-12 | KRÜ               | W   | 0.641      | -            | -                | -                | -         |    10.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2226 | 2024-05-11 | Case              | W   | 0.633      | 0.384        | -                | 0.805 (0.196)    | -         |    10.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2285 | 2024-05-08 | paiN              | L   | 0.614      | -            | -                | -                | -         |    -1.01 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2288 | 2024-05-08 | paiN              | L   | 0.614      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2310 | 2024-05-07 | KRÜ               | L   | 0.606      | -            | -                | -                | -         |    -9.28 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2345 | 2024-05-05 | W7M               | L   | 0.593      | -            | -                | -                | -         |   -11.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2653 | 2024-04-20 | Solid             | W   | 0.495      | 0.450        | -                | 0.836 (0.186)    | -         |     7.47 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2654 | 2024-04-20 | Solid             | L   | 0.495      | -            | -                | -                | -         |    -8.32 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2830 | 2024-04-16 | Case              | L   | 0.469      | -            | -                | -                | -         |    -7.49 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2868 | 2024-04-14 | MIBR              | L   | 0.455      | -            | -                | -                | -         |    -0.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2887 | 2024-04-13 | Fluxo             | W   | 0.446      | 0.435        | 0.124 (0.024)    | -                | -         |    10.09 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2896 | 2024-04-12 | Sharks            | W   | 0.441      | -            | -                | -                | -         |     4.58 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2916 | 2024-04-11 | Vikings KR        | L   | 0.435      | -            | -                | -                | -         |    -8.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2923 | 2024-04-11 | BESTIA            | W   | 0.434      | 0.435        | 0.095 (0.018)    | -                | -         |     8.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2951 | 2024-04-10 | MIBR              | L   | 0.429      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2955 | 2024-04-10 | MIBR              | L   | 0.429      | -            | -                | -                | -         |    -0.72 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3005 | 2024-04-09 | BESTIA            | W   | 0.422      | 0.450        | 0.095 (0.018)    | -                | -         |     8.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3010 | 2024-04-09 | BESTIA            | L   | 0.422      | -            | -                | -                | -         |    -5.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3083 | 2024-04-07 | paiN              | L   | 0.408      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3313 | 2024-03-27 | Fluxo             | W   | 0.336      | 0.450        | 0.124 (0.019)    | -                | -         |     7.50 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3319 | 2024-03-27 | Fluxo             | L   | 0.335      | -            | -                | -                | -         |    -3.11 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3359 | 2024-03-26 | 2GAME             | W   | 0.329      | -            | -                | -                | -         |     2.42 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3361 | 2024-03-26 | 2GAME             | W   | 0.329      | -            | -                | -                | -         |     2.47 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3555 | 2024-03-14 | W7M               | W   | 0.249      | -            | -                | -                | -         |     3.26 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3557 | 2024-03-14 | W7M               | W   | 0.249      | -            | -                | -                | -         |     3.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3601 | 2024-03-13 | RED Canids        | L   | 0.241      | -            | -                | -                | -         |    -1.94 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3645 | 2024-03-11 | LA RUGONETA       | L   | 0.228      | -            | -                | -                | -         |    -6.30 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3667 | 2024-03-10 | MIBR              | L   | 0.222      | -            | -                | -                | -         |    -0.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3725 | 2024-03-08 | ODDIK             | W   | 0.206      | 0.435        | 0.099 (0.009)    | -                | -         |     4.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     4006 | 2024-02-24 | Sharks            | L   | 0.122      | -            | -                | -                | -         |    -1.51 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4014 | 2024-02-24 | Sharks            | L   | 0.122      | -            | -                | -                | -         |    -1.52 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4037 | 2024-02-23 | Corinthians       | L   | 0.116      | -            | -                | -                | -         |    -3.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4038 | 2024-02-23 | Corinthians       | W   | 0.115      | -            | -                | -                | -         |     0.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4055 | 2024-02-22 | MIBR Academy      | W   | 0.108      | -            | -                | -                | -         |     0.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4070 | 2024-02-21 | adalYamigos       | L   | 0.102      | -            | -                | -                | -         |    -2.75 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4074 | 2024-02-21 | adalYamigos       | L   | 0.102      | -            | -                | -                | -         |    -2.75 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4081 | 2024-02-21 | Sharks            | L   | 0.100      | -            | -                | -                | -         |    -1.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4149 | 2024-02-18 | Sharks            | L   | 0.082      | -            | -                | -                | -         |    -1.07 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4151 | 2024-02-18 | Case              | W   | 0.081      | -            | -                | -                | -         |     1.42 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4177 | 2024-02-17 | Sharks            | W   | 0.074      | -            | -                | -                | -         |     1.40 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4180 | 2024-02-17 | Corinthians       | W   | 0.074      | -            | -                | -                | -         |     0.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4201 | 2024-02-16 | Flamengo          | W   | 0.068      | -            | -                | -                | -         |     0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4204 | 2024-02-16 | Imperial          | L   | 0.068      | -            | -                | -                | -         |    -0.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4209 | 2024-02-16 | Imperial          | L   | 0.067      | -            | -                | -                | -         |    -0.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4235 | 2024-02-15 | 9z Academy        | W   | 0.061      | -            | -                | -                | -         |     0.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4262 | 2024-02-14 | Solid             | L   | 0.056      | -            | -                | -                | -         |    -0.89 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4276 | 2024-02-14 | Sharks            | L   | 0.054      | -            | -                | -                | -         |    -0.69 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4311 | 2024-02-13 | Case              | L   | 0.047      | -            | -                | -                | -         |    -0.67 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4321 | 2024-02-12 | inSanitY          | W   | 0.042      | -            | -                | -                | -         |     0.07 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,671.72)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.895 | $1,075.00      | $961.73         |
| 2024-06-09 |      0.828 | $1,500.00      | $1,242.22       |
| 2024-04-15 |      0.461 | $5,000.00      | $2,306.48       |
| 2024-04-11 |      0.435 | $592.00        | $257.63         |
| 2024-02-22 |      0.108 | $1,417.00      | $153.38         |
| 2024-02-21 |      0.100 | $1,500.00      | $150.28         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
