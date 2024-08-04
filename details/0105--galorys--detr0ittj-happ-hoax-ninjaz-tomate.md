### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
<br />
Final Rank Value:  844.3<br />
<br />
Final Rank Value (844.3) = Starting Rank Value (905.5) + Head To Head Adjustments (-61.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.366[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.247<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.5
- 400 + ( ( 0.247 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 905.5


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
|           95 |      154 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.799 (0.360)    | 0 (0.000) |    23.50 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      160 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.50 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      257 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.57 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      275 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.804 (0.293)    | 0 (0.000) |    19.43 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      319 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.21 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      320 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      392 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.59 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      442 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.07 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      482 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.91 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      564 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      612 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.96 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      615 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.368 (0.166)    | 0 (0.000) |    13.34 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      628 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.02 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      680 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      701 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.29 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      726 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -7.98 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      732 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.049 (0.022)    | 0.462 (0.208)    | 0 (0.000) |    24.07 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      807 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.88 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      826 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.71 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      868 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.14 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      898 | 2024-06-30 | Vikings KR        | L   | 0.972      | -            | -                | -                | -         |   -16.47 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      905 | 2024-06-29 | inSanitY          | L   | 0.966      | -            | -                | -                | -         |    -8.62 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      916 | 2024-06-27 | Sharks            | L   | 0.953      | -            | -                | -                | -         |    -8.64 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      918 | 2024-06-27 | KRÜ               | W   | 0.952      | 0.333        | -                | 0.491 (0.156)    | 0 (0.000) |    15.65 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |      941 | 2024-06-18 | inSanitY          | L   | 0.893      | -            | -                | -                | -         |    -9.19 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1168 | 2024-06-09 | ODDIK             | L   | 0.833      | -            | -                | -                | -         |   -10.65 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1262 | 2024-06-08 | Case              | W   | 0.824      | 0.450        | 0.029 (0.011)    | 0.804 (0.298)    | 0 (0.000) |    12.72 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1291 | 2024-06-07 | Imperial          | L   | 0.819      | -            | -                | -                | -         |    -2.34 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1319 | 2024-06-07 | W7M               | L   | 0.818      | -            | -                | -                | -         |   -15.76 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1337 | 2024-06-06 | paiN              | L   | 0.814      | -            | -                | -                | -         |    -1.84 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1350 | 2024-06-06 | ex-Corinthians    | W   | 0.813      | -            | -                | -                | -         |     3.34 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1468 | 2024-06-04 | MIBR              | L   | 0.800      | -            | -                | -                | -         |    -0.99 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1507 | 2024-06-03 | Intense           | L   | 0.792      | -            | -                | -                | -         |   -16.79 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1555 | 2024-06-01 | Hype              | L   | 0.778      | -            | -                | -                | -         |   -12.70 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1608 | 2024-05-30 | Hawks             | W   | 0.766      | -            | -                | -                | -         |     2.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1694 | 2024-05-27 | Dusty Roots       | W   | 0.744      | -            | -                | -                | -         |     9.88 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1874 | 2024-05-20 | Case              | L   | 0.699      | -            | -                | -                | -         |   -10.60 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1899 | 2024-05-19 | Solid             | W   | 0.692      | 0.303        | -                | 0.835 (0.175)    | -         |    10.46 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1925 | 2024-05-18 | ODDIK             | L   | 0.685      | -            | -                | -                | -         |    -9.04 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2041 | 2024-05-15 | Hype              | W   | 0.666      | -            | -                | -                | -         |    10.52 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2050 | 2024-05-15 | Case              | L   | 0.665      | -            | -                | -                | -         |   -11.05 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2091 | 2024-05-14 | Case              | L   | 0.660      | -            | -                | -                | -         |   -11.63 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2096 | 2024-05-14 | Case              | W   | 0.660      | 0.450        | 0.029 (0.009)    | 0.804 (0.239)    | -         |     9.30 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2108 | 2024-05-14 | 9z                | L   | 0.659      | -            | -                | -                | -         |    -0.67 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2127 | 2024-05-13 | 9z                | L   | 0.653      | -            | -                | -                | -         |    -0.67 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2132 | 2024-05-13 | Yawara            | W   | 0.652      | -            | -                | -                | -         |     2.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2152 | 2024-05-12 | KRÜ               | W   | 0.646      | -            | -                | -                | -         |    10.85 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2191 | 2024-05-11 | Case              | W   | 0.638      | 0.384        | -                | 0.804 (0.197)    | -         |    10.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2250 | 2024-05-08 | paiN              | L   | 0.619      | -            | -                | -                | -         |    -1.01 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2253 | 2024-05-08 | paiN              | L   | 0.619      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2275 | 2024-05-07 | KRÜ               | L   | 0.611      | -            | -                | -                | -         |    -9.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2310 | 2024-05-05 | W7M               | L   | 0.598      | -            | -                | -                | -         |   -11.44 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2617 | 2024-04-20 | Solid             | W   | 0.500      | 0.450        | -                | 0.835 (0.188)    | -         |     7.54 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2618 | 2024-04-20 | Solid             | L   | 0.500      | -            | -                | -                | -         |    -8.39 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2794 | 2024-04-16 | Case              | L   | 0.474      | -            | -                | -                | -         |    -7.56 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2832 | 2024-04-14 | MIBR              | L   | 0.459      | -            | -                | -                | -         |    -0.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2851 | 2024-04-13 | Fluxo             | W   | 0.451      | 0.435        | 0.124 (0.024)    | -                | -         |    10.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2860 | 2024-04-12 | Sharks            | W   | 0.446      | -            | -                | -                | -         |     4.64 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2880 | 2024-04-11 | Vikings KR        | L   | 0.440      | -            | -                | -                | -         |    -8.43 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2887 | 2024-04-11 | BESTIA            | W   | 0.438      | 0.435        | 0.095 (0.018)    | -                | -         |     8.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2915 | 2024-04-10 | MIBR              | L   | 0.433      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2919 | 2024-04-10 | MIBR              | L   | 0.433      | -            | -                | -                | -         |    -0.72 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     2969 | 2024-04-09 | BESTIA            | W   | 0.427      | 0.450        | 0.095 (0.018)    | -                | -         |     8.25 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     2974 | 2024-04-09 | BESTIA            | L   | 0.426      | -            | -                | -                | -         |    -5.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3047 | 2024-04-07 | paiN              | L   | 0.412      | -            | -                | -                | -         |    -0.65 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3277 | 2024-03-27 | Fluxo             | W   | 0.340      | 0.450        | 0.124 (0.019)    | -                | -         |     7.60 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3283 | 2024-03-27 | Fluxo             | L   | 0.340      | -            | -                | -                | -         |    -3.15 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3323 | 2024-03-26 | 2GAME             | W   | 0.334      | -            | -                | -                | -         |     2.46 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3325 | 2024-03-26 | 2GAME             | W   | 0.333      | -            | -                | -                | -         |     2.52 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3519 | 2024-03-14 | W7M               | W   | 0.254      | -            | -                | -                | -         |     3.32 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3521 | 2024-03-14 | W7M               | W   | 0.253      | -            | -                | -                | -         |     3.39 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3564 | 2024-03-13 | RED Canids        | L   | 0.245      | -            | -                | -                | -         |    -1.97 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3608 | 2024-03-11 | LA RUGONETA       | L   | 0.233      | -            | -                | -                | -         |    -6.42 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3630 | 2024-03-10 | MIBR              | L   | 0.226      | -            | -                | -                | -         |    -0.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3688 | 2024-03-08 | ODDIK             | W   | 0.211      | 0.435        | 0.098 (0.009)    | -                | -         |     4.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     3969 | 2024-02-24 | Sharks            | L   | 0.127      | -            | -                | -                | -         |    -1.56 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     3977 | 2024-02-24 | Sharks            | L   | 0.127      | -            | -                | -                | -         |    -1.57 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4000 | 2024-02-23 | Corinthians       | L   | 0.120      | -            | -                | -                | -         |    -3.40 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4001 | 2024-02-23 | Corinthians       | W   | 0.120      | -            | -                | -                | -         |     0.38 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4018 | 2024-02-22 | MIBR Academy      | W   | 0.113      | -            | -                | -                | -         |     0.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4033 | 2024-02-21 | adalYamigos       | L   | 0.107      | -            | -                | -                | -         |    -2.87 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4037 | 2024-02-21 | adalYamigos       | L   | 0.107      | -            | -                | -                | -         |    -2.87 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4044 | 2024-02-21 | Sharks            | L   | 0.105      | -            | -                | -                | -         |    -1.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4112 | 2024-02-18 | Sharks            | L   | 0.087      | -            | -                | -                | -         |    -1.13 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4114 | 2024-02-18 | Case              | W   | 0.086      | -            | -                | -                | -         |     1.50 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4139 | 2024-02-17 | Sharks            | W   | 0.079      | -            | -                | -                | -         |     1.48 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4142 | 2024-02-17 | Corinthians       | W   | 0.078      | -            | -                | -                | -         |     0.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4163 | 2024-02-16 | Flamengo          | W   | 0.073      | -            | -                | -                | -         |     0.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4166 | 2024-02-16 | Imperial          | L   | 0.072      | -            | -                | -                | -         |    -0.26 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4171 | 2024-02-16 | Imperial          | L   | 0.072      | -            | -                | -                | -         |    -0.26 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4197 | 2024-02-15 | 9z Academy        | W   | 0.065      | -            | -                | -                | -         |     0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4224 | 2024-02-14 | Solid             | L   | 0.060      | -            | -                | -                | -         |    -0.96 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4238 | 2024-02-14 | Sharks            | L   | 0.058      | -            | -                | -                | -         |    -0.74 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4273 | 2024-02-13 | Case              | L   | 0.052      | -            | -                | -                | -         |    -0.74 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4283 | 2024-02-12 | inSanitY          | W   | 0.046      | -            | -                | -                | -         |     0.08 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,722.00)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.899 | $1,075.00      | $966.60         |
| 2024-06-09 |      0.833 | $1,500.00      | $1,249.03       |
| 2024-04-15 |      0.466 | $5,000.00      | $2,329.17       |
| 2024-04-11 |      0.440 | $592.00        | $260.32         |
| 2024-02-22 |      0.113 | $1,417.00      | $159.81         |
| 2024-02-21 |      0.105 | $1,500.00      | $157.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
