### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
<br />
Final Rank Value:  844.6<br />
<br />
Final Rank Value (844.6) = Starting Rank Value (905.5) + Head To Head Adjustments (-60.9)<br />

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
|           95 |      157 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.801 (0.360)    | 0 (0.000) |    23.50 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      163 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.50 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      260 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.44 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      278 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.805 (0.294)    | 0 (0.000) |    19.43 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      322 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.22 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      323 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      395 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.58 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      445 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.07 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      485 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.91 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      567 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.90 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      615 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.97 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      618 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.369 (0.166)    | 0 (0.000) |    13.33 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      631 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.02 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      683 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      704 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.29 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      729 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.00 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      735 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.463 (0.208)    | 0 (0.000) |    24.05 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      811 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      830 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.71 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      872 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.15 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      902 | 2024-06-30 | Vikings KR        | L   | 0.969      | -            | -                | -                | -         |   -16.42 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      909 | 2024-06-29 | inSanitY          | L   | 0.963      | -            | -                | -                | -         |    -8.62 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      920 | 2024-06-27 | Sharks            | L   | 0.950      | -            | -                | -                | -         |    -8.64 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      922 | 2024-06-27 | KRÜ               | W   | 0.949      | 0.333        | -                | 0.492 (0.156)    | 0 (0.000) |    15.60 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |      945 | 2024-06-18 | inSanitY          | L   | 0.890      | -            | -                | -                | -         |    -9.18 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1172 | 2024-06-09 | ODDIK             | L   | 0.830      | -            | -                | -                | -         |   -10.62 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1266 | 2024-06-08 | Case              | W   | 0.821      | 0.450        | 0.029 (0.011)    | 0.805 (0.297)    | 0 (0.000) |    12.68 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1295 | 2024-06-07 | Imperial          | L   | 0.816      | -            | -                | -                | -         |    -2.35 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1323 | 2024-06-07 | W7M               | L   | 0.814      | -            | -                | -                | -         |   -15.70 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1341 | 2024-06-06 | paiN              | L   | 0.811      | -            | -                | -                | -         |    -1.85 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1354 | 2024-06-06 | ex-Corinthians    | W   | 0.810      | -            | -                | -                | -         |     3.33 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1472 | 2024-06-04 | MIBR              | L   | 0.797      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1511 | 2024-06-03 | Intense           | L   | 0.789      | -            | -                | -                | -         |   -16.73 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1559 | 2024-06-01 | Hype              | L   | 0.775      | -            | -                | -                | -         |   -12.65 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1612 | 2024-05-30 | Hawks             | W   | 0.763      | -            | -                | -                | -         |     2.93 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1698 | 2024-05-27 | Dusty Roots       | W   | 0.741      | -            | -                | -                | -         |     9.85 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1878 | 2024-05-20 | Case              | L   | 0.696      | -            | -                | -                | -         |   -10.56 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1903 | 2024-05-19 | Solid             | W   | 0.689      | 0.303        | -                | 0.835 (0.174)    | -         |    10.41 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1929 | 2024-05-18 | ODDIK             | L   | 0.682      | -            | -                | -                | -         |    -9.00 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2045 | 2024-05-15 | Hype              | W   | 0.663      | -            | -                | -                | -         |    10.47 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2054 | 2024-05-15 | Case              | L   | 0.662      | -            | -                | -                | -         |   -11.00 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2095 | 2024-05-14 | Case              | L   | 0.657      | -            | -                | -                | -         |   -11.57 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2100 | 2024-05-14 | Case              | W   | 0.657      | 0.450        | 0.029 (0.009)    | 0.805 (0.238)    | -         |     9.26 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2112 | 2024-05-14 | 9z                | L   | 0.656      | -            | -                | -                | -         |    -0.67 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2131 | 2024-05-13 | 9z                | L   | 0.650      | -            | -                | -                | -         |    -0.67 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2136 | 2024-05-13 | Yawara            | W   | 0.649      | -            | -                | -                | -         |     2.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2156 | 2024-05-12 | KRÜ               | W   | 0.643      | -            | -                | -                | -         |    10.80 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2195 | 2024-05-11 | Case              | W   | 0.635      | 0.384        | -                | 0.805 (0.196)    | -         |    10.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2254 | 2024-05-08 | paiN              | L   | 0.616      | -            | -                | -                | -         |    -1.01 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2257 | 2024-05-08 | paiN              | L   | 0.616      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2279 | 2024-05-07 | KRÜ               | L   | 0.608      | -            | -                | -                | -         |    -9.30 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2314 | 2024-05-05 | W7M               | L   | 0.594      | -            | -                | -                | -         |   -11.38 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2622 | 2024-04-20 | Solid             | W   | 0.497      | 0.450        | -                | 0.835 (0.187)    | -         |     7.50 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2623 | 2024-04-20 | Solid             | L   | 0.497      | -            | -                | -                | -         |    -8.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2799 | 2024-04-16 | Case              | L   | 0.471      | -            | -                | -                | -         |    -7.51 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2837 | 2024-04-14 | MIBR              | L   | 0.456      | -            | -                | -                | -         |    -0.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2856 | 2024-04-13 | Fluxo             | W   | 0.448      | 0.435        | 0.124 (0.024)    | -                | -         |    10.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2865 | 2024-04-12 | Sharks            | W   | 0.443      | -            | -                | -                | -         |     4.60 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2885 | 2024-04-11 | Vikings KR        | L   | 0.437      | -            | -                | -                | -         |    -8.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2892 | 2024-04-11 | BESTIA            | W   | 0.435      | 0.435        | 0.095 (0.018)    | -                | -         |     8.14 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2920 | 2024-04-10 | MIBR              | L   | 0.430      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2924 | 2024-04-10 | MIBR              | L   | 0.430      | -            | -                | -                | -         |    -0.72 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     2974 | 2024-04-09 | BESTIA            | W   | 0.424      | 0.450        | 0.095 (0.018)    | -                | -         |     8.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     2979 | 2024-04-09 | BESTIA            | L   | 0.423      | -            | -                | -                | -         |    -5.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3052 | 2024-04-07 | paiN              | L   | 0.409      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3282 | 2024-03-27 | Fluxo             | W   | 0.337      | 0.450        | 0.124 (0.019)    | -                | -         |     7.53 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3288 | 2024-03-27 | Fluxo             | L   | 0.337      | -            | -                | -                | -         |    -3.13 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3328 | 2024-03-26 | 2GAME             | W   | 0.331      | -            | -                | -                | -         |     2.44 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3330 | 2024-03-26 | 2GAME             | W   | 0.330      | -            | -                | -                | -         |     2.48 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3524 | 2024-03-14 | W7M               | W   | 0.251      | -            | -                | -                | -         |     3.28 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3526 | 2024-03-14 | W7M               | W   | 0.250      | -            | -                | -                | -         |     3.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3570 | 2024-03-13 | RED Canids        | L   | 0.242      | -            | -                | -                | -         |    -1.95 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3614 | 2024-03-11 | LA RUGONETA       | L   | 0.229      | -            | -                | -                | -         |    -6.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3636 | 2024-03-10 | MIBR              | L   | 0.223      | -            | -                | -                | -         |    -0.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3694 | 2024-03-08 | ODDIK             | W   | 0.208      | 0.435        | 0.098 (0.009)    | -                | -         |     4.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     3975 | 2024-02-24 | Sharks            | L   | 0.124      | -            | -                | -                | -         |    -1.52 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     3983 | 2024-02-24 | Sharks            | L   | 0.124      | -            | -                | -                | -         |    -1.54 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4006 | 2024-02-23 | Corinthians       | L   | 0.117      | -            | -                | -                | -         |    -3.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4007 | 2024-02-23 | Corinthians       | W   | 0.117      | -            | -                | -                | -         |     0.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4024 | 2024-02-22 | MIBR Academy      | W   | 0.110      | -            | -                | -                | -         |     0.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4039 | 2024-02-21 | adalYamigos       | L   | 0.104      | -            | -                | -                | -         |    -2.79 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4043 | 2024-02-21 | adalYamigos       | L   | 0.104      | -            | -                | -                | -         |    -2.79 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4050 | 2024-02-21 | Sharks            | L   | 0.102      | -            | -                | -                | -         |    -1.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4118 | 2024-02-18 | Sharks            | L   | 0.084      | -            | -                | -                | -         |    -1.09 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4120 | 2024-02-18 | Case              | W   | 0.083      | -            | -                | -                | -         |     1.45 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4146 | 2024-02-17 | Sharks            | W   | 0.076      | -            | -                | -                | -         |     1.43 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4149 | 2024-02-17 | Corinthians       | W   | 0.075      | -            | -                | -                | -         |     0.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4170 | 2024-02-16 | Flamengo          | W   | 0.070      | -            | -                | -                | -         |     0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4173 | 2024-02-16 | Imperial          | L   | 0.069      | -            | -                | -                | -         |    -0.25 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4178 | 2024-02-16 | Imperial          | L   | 0.069      | -            | -                | -                | -         |    -0.25 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4204 | 2024-02-15 | 9z Academy        | W   | 0.062      | -            | -                | -                | -         |     0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4231 | 2024-02-14 | Solid             | L   | 0.057      | -            | -                | -                | -         |    -0.91 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4245 | 2024-02-14 | Sharks            | L   | 0.055      | -            | -                | -                | -         |    -0.70 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4280 | 2024-02-13 | Case              | L   | 0.049      | -            | -                | -                | -         |    -0.69 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4290 | 2024-02-12 | inSanitY          | W   | 0.043      | -            | -                | -                | -         |     0.08 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,688.14)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.896 | $1,075.00      | $963.32         |
| 2024-06-09 |      0.830 | $1,500.00      | $1,244.44       |
| 2024-04-15 |      0.463 | $5,000.00      | $2,313.89       |
| 2024-04-11 |      0.437 | $592.00        | $258.51         |
| 2024-02-22 |      0.110 | $1,417.00      | $155.48         |
| 2024-02-21 |      0.102 | $1,500.00      | $152.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
