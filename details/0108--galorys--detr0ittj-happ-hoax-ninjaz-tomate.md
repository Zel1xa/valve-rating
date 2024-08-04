### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Global Rank: [108](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
<br />
Final Rank Value:  844.6<br />
<br />
Final Rank Value (844.6) = Starting Rank Value (905.5) + Head To Head Adjustments (-60.8)<br />

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
|           95 |      165 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.801 (0.360)    | 0 (0.000) |    23.50 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      171 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.50 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      268 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.44 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      286 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.805 (0.294)    | 0 (0.000) |    19.43 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      330 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.22 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      331 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      403 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.58 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      453 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.07 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      493 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.91 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      575 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.90 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      623 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.97 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      626 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.369 (0.166)    | 0 (0.000) |    13.33 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      639 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.01 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      691 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      712 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.29 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      737 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.01 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      743 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.463 (0.208)    | 0 (0.000) |    24.04 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      819 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      838 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.70 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      880 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.15 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      910 | 2024-06-30 | Vikings KR        | L   | 0.968      | -            | -                | -                | -         |   -16.41 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      917 | 2024-06-29 | inSanitY          | L   | 0.962      | -            | -                | -                | -         |    -8.62 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      928 | 2024-06-27 | Sharks            | L   | 0.950      | -            | -                | -                | -         |    -8.63 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      930 | 2024-06-27 | KRÜ               | W   | 0.949      | 0.333        | -                | 0.492 (0.156)    | 0 (0.000) |    15.58 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |      953 | 2024-06-18 | inSanitY          | L   | 0.889      | -            | -                | -                | -         |    -9.18 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1180 | 2024-06-09 | ODDIK             | L   | 0.829      | -            | -                | -                | -         |   -10.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1274 | 2024-06-08 | Case              | W   | 0.820      | 0.450        | 0.029 (0.011)    | 0.805 (0.297)    | 0 (0.000) |    12.66 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1303 | 2024-06-07 | Imperial          | L   | 0.816      | -            | -                | -                | -         |    -2.35 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1331 | 2024-06-07 | W7M               | L   | 0.814      | -            | -                | -                | -         |   -15.69 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1349 | 2024-06-06 | paiN              | L   | 0.810      | -            | -                | -                | -         |    -1.85 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1362 | 2024-06-06 | ex-Corinthians    | W   | 0.809      | -            | -                | -                | -         |     3.32 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1480 | 2024-06-04 | MIBR              | L   | 0.796      | -            | -                | -                | -         |    -0.99 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1519 | 2024-06-03 | Intense           | L   | 0.788      | -            | -                | -                | -         |   -16.71 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1567 | 2024-06-01 | Hype              | L   | 0.775      | -            | -                | -                | -         |   -12.63 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1620 | 2024-05-30 | Hawks             | W   | 0.762      | -            | -                | -                | -         |     2.92 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1706 | 2024-05-27 | Dusty Roots       | W   | 0.741      | -            | -                | -                | -         |     9.84 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1886 | 2024-05-20 | Case              | L   | 0.695      | -            | -                | -                | -         |   -10.55 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1911 | 2024-05-19 | Solid             | W   | 0.688      | 0.303        | -                | 0.835 (0.174)    | -         |    10.40 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1937 | 2024-05-18 | ODDIK             | L   | 0.682      | -            | -                | -                | -         |    -8.99 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2053 | 2024-05-15 | Hype              | W   | 0.662      | -            | -                | -                | -         |    10.46 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2062 | 2024-05-15 | Case              | L   | 0.661      | -            | -                | -                | -         |   -10.98 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2103 | 2024-05-14 | Case              | L   | 0.656      | -            | -                | -                | -         |   -11.56 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2108 | 2024-05-14 | Case              | W   | 0.656      | 0.450        | 0.029 (0.009)    | 0.805 (0.238)    | -         |     9.25 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2120 | 2024-05-14 | 9z                | L   | 0.655      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2139 | 2024-05-13 | 9z                | L   | 0.650      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2144 | 2024-05-13 | Yawara            | W   | 0.648      | -            | -                | -                | -         |     2.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2164 | 2024-05-12 | KRÜ               | W   | 0.642      | -            | -                | -                | -         |    10.79 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2203 | 2024-05-11 | Case              | W   | 0.634      | 0.384        | -                | 0.805 (0.196)    | -         |    10.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2262 | 2024-05-08 | paiN              | L   | 0.615      | -            | -                | -                | -         |    -1.01 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2265 | 2024-05-08 | paiN              | L   | 0.615      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2287 | 2024-05-07 | KRÜ               | L   | 0.607      | -            | -                | -                | -         |    -9.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2322 | 2024-05-05 | W7M               | L   | 0.594      | -            | -                | -                | -         |   -11.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2630 | 2024-04-20 | Solid             | W   | 0.496      | 0.450        | -                | 0.835 (0.187)    | -         |     7.48 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2631 | 2024-04-20 | Solid             | L   | 0.496      | -            | -                | -                | -         |    -8.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2807 | 2024-04-16 | Case              | L   | 0.470      | -            | -                | -                | -         |    -7.50 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2845 | 2024-04-14 | MIBR              | L   | 0.455      | -            | -                | -                | -         |    -0.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2864 | 2024-04-13 | Fluxo             | W   | 0.447      | 0.435        | 0.124 (0.024)    | -                | -         |    10.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2873 | 2024-04-12 | Sharks            | W   | 0.442      | -            | -                | -                | -         |     4.59 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2893 | 2024-04-11 | Vikings KR        | L   | 0.436      | -            | -                | -                | -         |    -8.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2900 | 2024-04-11 | BESTIA            | W   | 0.435      | 0.435        | 0.095 (0.018)    | -                | -         |     8.13 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2928 | 2024-04-10 | MIBR              | L   | 0.430      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2932 | 2024-04-10 | MIBR              | L   | 0.429      | -            | -                | -                | -         |    -0.72 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     2982 | 2024-04-09 | BESTIA            | W   | 0.423      | 0.450        | 0.095 (0.018)    | -                | -         |     8.18 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     2987 | 2024-04-09 | BESTIA            | L   | 0.423      | -            | -                | -                | -         |    -5.22 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3060 | 2024-04-07 | paiN              | L   | 0.409      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3290 | 2024-03-27 | Fluxo             | W   | 0.337      | 0.450        | 0.124 (0.019)    | -                | -         |     7.51 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3296 | 2024-03-27 | Fluxo             | L   | 0.336      | -            | -                | -                | -         |    -3.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3336 | 2024-03-26 | 2GAME             | W   | 0.330      | -            | -                | -                | -         |     2.43 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3338 | 2024-03-26 | 2GAME             | W   | 0.330      | -            | -                | -                | -         |     2.48 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3532 | 2024-03-14 | W7M               | W   | 0.250      | -            | -                | -                | -         |     3.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3534 | 2024-03-14 | W7M               | W   | 0.250      | -            | -                | -                | -         |     3.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3578 | 2024-03-13 | RED Canids        | L   | 0.242      | -            | -                | -                | -         |    -1.94 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3622 | 2024-03-11 | LA RUGONETA       | L   | 0.229      | -            | -                | -                | -         |    -6.32 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3644 | 2024-03-10 | MIBR              | L   | 0.223      | -            | -                | -                | -         |    -0.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3702 | 2024-03-08 | ODDIK             | W   | 0.207      | 0.435        | 0.098 (0.009)    | -                | -         |     4.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     3983 | 2024-02-24 | Sharks            | L   | 0.123      | -            | -                | -                | -         |    -1.52 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     3991 | 2024-02-24 | Sharks            | L   | 0.123      | -            | -                | -                | -         |    -1.53 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4014 | 2024-02-23 | Corinthians       | L   | 0.116      | -            | -                | -                | -         |    -3.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4015 | 2024-02-23 | Corinthians       | W   | 0.116      | -            | -                | -                | -         |     0.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4032 | 2024-02-22 | MIBR Academy      | W   | 0.109      | -            | -                | -                | -         |     0.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4047 | 2024-02-21 | adalYamigos       | L   | 0.103      | -            | -                | -                | -         |    -2.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4051 | 2024-02-21 | adalYamigos       | L   | 0.103      | -            | -                | -                | -         |    -2.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4058 | 2024-02-21 | Sharks            | L   | 0.101      | -            | -                | -                | -         |    -1.30 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4126 | 2024-02-18 | Sharks            | L   | 0.083      | -            | -                | -                | -         |    -1.08 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4128 | 2024-02-18 | Case              | W   | 0.082      | -            | -                | -                | -         |     1.44 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4154 | 2024-02-17 | Sharks            | W   | 0.075      | -            | -                | -                | -         |     1.41 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4157 | 2024-02-17 | Corinthians       | W   | 0.075      | -            | -                | -                | -         |     0.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4178 | 2024-02-16 | Flamengo          | W   | 0.069      | -            | -                | -                | -         |     0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4181 | 2024-02-16 | Imperial          | L   | 0.068      | -            | -                | -                | -         |    -0.25 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4186 | 2024-02-16 | Imperial          | L   | 0.068      | -            | -                | -                | -         |    -0.25 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4212 | 2024-02-15 | 9z Academy        | W   | 0.062      | -            | -                | -                | -         |     0.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4239 | 2024-02-14 | Solid             | L   | 0.056      | -            | -                | -                | -         |    -0.90 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4253 | 2024-02-14 | Sharks            | L   | 0.055      | -            | -                | -                | -         |    -0.70 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4288 | 2024-02-13 | Case              | L   | 0.048      | -            | -                | -                | -         |    -0.68 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4298 | 2024-02-12 | inSanitY          | W   | 0.042      | -            | -                | -                | -         |     0.07 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,680.18)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.895 | $1,075.00      | $962.55         |
| 2024-06-09 |      0.829 | $1,500.00      | $1,243.37       |
| 2024-04-15 |      0.462 | $5,000.00      | $2,310.30       |
| 2024-04-11 |      0.436 | $592.00        | $258.08         |
| 2024-02-22 |      0.109 | $1,417.00      | $154.46         |
| 2024-02-21 |      0.101 | $1,500.00      | $151.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
