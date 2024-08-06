### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Global Rank: [107](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
<br />
Final Rank Value:  844.3<br />
<br />
Final Rank Value (844.3) = Starting Rank Value (904.2) + Head To Head Adjustments (-60.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.223[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 904.2
- 400 + ( ( 0.246 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 904.2


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
|           95 |      221 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.793 (0.357)    | 0 (0.000) |    23.45 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      227 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.55 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      324 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.47 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      342 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.795 (0.290)    | 0 (0.000) |    19.42 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      386 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      387 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.25 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      459 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.55 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      509 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.08 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      549 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      628 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.96 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      679 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.96 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      682 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.366 (0.165)    | 0 (0.000) |    13.35 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      695 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.02 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      747 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.64 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      768 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.30 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      793 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.09 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      799 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.457 (0.206)    | 0 (0.000) |    23.95 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      875 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      894 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.74 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      936 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.17 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      966 | 2024-06-30 | Vikings KR        | L   | 0.955      | -            | -                | -                | -         |   -16.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      973 | 2024-06-29 | inSanitY          | L   | 0.949      | -            | -                | -                | -         |    -8.59 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      984 | 2024-06-27 | Sharks            | L   | 0.937      | -            | -                | -                | -         |    -8.60 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      986 | 2024-06-27 | KRÜ               | W   | 0.936      | 0.333        | -                | 0.489 (0.153)    | 0 (0.000) |    15.36 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |     1009 | 2024-06-18 | inSanitY          | L   | 0.877      | -            | -                | -                | -         |    -9.13 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1236 | 2024-06-09 | ODDIK             | L   | 0.816      | -            | -                | -                | -         |   -10.48 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1330 | 2024-06-08 | Case              | W   | 0.808      | 0.450        | 0.029 (0.011)    | 0.795 (0.289)    | 0 (0.000) |    12.48 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1359 | 2024-06-07 | Imperial          | L   | 0.803      | -            | -                | -                | -         |    -2.38 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1387 | 2024-06-07 | W7M               | L   | 0.801      | -            | -                | -                | -         |   -15.45 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1405 | 2024-06-06 | paiN              | L   | 0.797      | -            | -                | -                | -         |    -1.86 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1418 | 2024-06-06 | ex-Corinthians    | W   | 0.796      | -            | -                | -                | -         |     3.28 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1536 | 2024-06-04 | MIBR              | L   | 0.783      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1575 | 2024-06-03 | Intense           | L   | 0.775      | -            | -                | -                | -         |   -16.44 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1623 | 2024-06-01 | Hype              | L   | 0.762      | -            | -                | -                | -         |   -12.42 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1676 | 2024-05-30 | Hawks             | W   | 0.750      | -            | -                | -                | -         |     2.88 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1762 | 2024-05-27 | Dusty Roots       | W   | 0.728      | -            | -                | -                | -         |     9.71 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1942 | 2024-05-20 | Case              | L   | 0.682      | -            | -                | -                | -         |   -10.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1967 | 2024-05-19 | Solid             | W   | 0.676      | 0.303        | -                | 0.825 (0.169)    | -         |    10.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1993 | 2024-05-18 | ODDIK             | L   | 0.669      | -            | -                | -                | -         |    -8.84 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2109 | 2024-05-15 | Hype              | W   | 0.650      | -            | -                | -                | -         |    10.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2118 | 2024-05-15 | Case              | L   | 0.649      | -            | -                | -                | -         |   -10.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2159 | 2024-05-14 | Case              | L   | 0.644      | -            | -                | -                | -         |   -11.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2164 | 2024-05-14 | Case              | W   | 0.643      | 0.450        | 0.029 (0.008)    | 0.795 (0.230)    | -         |     9.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2176 | 2024-05-14 | 9z                | L   | 0.642      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2195 | 2024-05-13 | 9z                | L   | 0.637      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2200 | 2024-05-13 | Yawara            | W   | 0.636      | -            | -                | -                | -         |     1.98 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2220 | 2024-05-12 | KRÜ               | W   | 0.629      | -            | -                | -                | -         |    10.56 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2259 | 2024-05-11 | Case              | W   | 0.621      | 0.384        | -                | 0.795 (0.190)    | -         |    10.01 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2318 | 2024-05-08 | paiN              | L   | 0.603      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2321 | 2024-05-08 | paiN              | L   | 0.602      | -            | -                | -                | -         |    -1.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2343 | 2024-05-07 | KRÜ               | L   | 0.594      | -            | -                | -                | -         |    -9.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2378 | 2024-05-05 | W7M               | L   | 0.581      | -            | -                | -                | -         |   -11.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2686 | 2024-04-20 | Solid             | W   | 0.484      | 0.450        | -                | 0.825 (0.180)    | -         |     7.28 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2687 | 2024-04-20 | Solid             | L   | 0.483      | -            | -                | -                | -         |    -8.13 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2863 | 2024-04-16 | Case              | L   | 0.457      | -            | -                | -                | -         |    -7.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2901 | 2024-04-14 | MIBR              | L   | 0.443      | -            | -                | -                | -         |    -0.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2920 | 2024-04-13 | Fluxo             | W   | 0.434      | 0.435        | 0.123 (0.023)    | -                | -         |     9.79 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2929 | 2024-04-12 | Sharks            | W   | 0.430      | -            | -                | -                | -         |     4.46 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2949 | 2024-04-11 | Vikings KR        | L   | 0.423      | -            | -                | -                | -         |    -8.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2956 | 2024-04-11 | BESTIA            | W   | 0.422      | 0.435        | 0.096 (0.018)    | -                | -         |     7.91 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2984 | 2024-04-10 | MIBR              | L   | 0.417      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2988 | 2024-04-10 | MIBR              | L   | 0.417      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3038 | 2024-04-09 | BESTIA            | W   | 0.410      | 0.450        | 0.096 (0.018)    | -                | -         |     7.94 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3043 | 2024-04-09 | BESTIA            | L   | 0.410      | -            | -                | -                | -         |    -5.06 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3116 | 2024-04-07 | paiN              | L   | 0.396      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3346 | 2024-03-27 | Fluxo             | W   | 0.324      | 0.450        | 0.123 (0.018)    | -                | -         |     7.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3352 | 2024-03-27 | Fluxo             | L   | 0.324      | -            | -                | -                | -         |    -3.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3392 | 2024-03-26 | 2GAME             | W   | 0.317      | -            | -                | -                | -         |     2.32 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3394 | 2024-03-26 | 2GAME             | W   | 0.317      | -            | -                | -                | -         |     2.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3588 | 2024-03-14 | W7M               | W   | 0.237      | -            | -                | -                | -         |     3.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3590 | 2024-03-14 | W7M               | W   | 0.237      | -            | -                | -                | -         |     3.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3634 | 2024-03-13 | RED Canids        | L   | 0.229      | -            | -                | -                | -         |    -1.87 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3678 | 2024-03-11 | LA RUGONETA       | L   | 0.216      | -            | -                | -                | -         |    -5.99 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3700 | 2024-03-10 | MIBR              | L   | 0.210      | -            | -                | -                | -         |    -0.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3758 | 2024-03-08 | ODDIK             | W   | 0.194      | 0.435        | 0.099 (0.008)    | -                | -         |     3.94 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     4039 | 2024-02-24 | Sharks            | L   | 0.111      | -            | -                | -                | -         |    -1.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4047 | 2024-02-24 | Sharks            | L   | 0.110      | -            | -                | -                | -         |    -1.38 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4070 | 2024-02-23 | Corinthians       | L   | 0.104      | -            | -                | -                | -         |    -2.94 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4071 | 2024-02-23 | Corinthians       | W   | 0.103      | -            | -                | -                | -         |     0.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4088 | 2024-02-22 | MIBR Academy      | W   | 0.096      | -            | -                | -                | -         |     0.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4103 | 2024-02-21 | adalYamigos       | L   | 0.091      | -            | -                | -                | -         |    -2.44 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4107 | 2024-02-21 | adalYamigos       | L   | 0.090      | -            | -                | -                | -         |    -2.44 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4114 | 2024-02-21 | Sharks            | L   | 0.088      | -            | -                | -                | -         |    -1.14 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4182 | 2024-02-18 | Sharks            | L   | 0.070      | -            | -                | -                | -         |    -0.91 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4184 | 2024-02-18 | Case              | W   | 0.069      | -            | -                | -                | -         |     1.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4210 | 2024-02-17 | Sharks            | W   | 0.063      | -            | -                | -                | -         |     1.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4213 | 2024-02-17 | Corinthians       | W   | 0.062      | -            | -                | -                | -         |     0.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4234 | 2024-02-16 | Flamengo          | W   | 0.057      | -            | -                | -                | -         |     0.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4237 | 2024-02-16 | Imperial          | L   | 0.056      | -            | -                | -                | -         |    -0.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4242 | 2024-02-16 | Imperial          | L   | 0.055      | -            | -                | -                | -         |    -0.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4268 | 2024-02-15 | 9z Academy        | W   | 0.049      | -            | -                | -                | -         |     0.15 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4295 | 2024-02-14 | Solid             | L   | 0.044      | -            | -                | -                | -         |    -0.70 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4309 | 2024-02-14 | Sharks            | L   | 0.042      | -            | -                | -                | -         |    -0.54 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4344 | 2024-02-13 | Case              | L   | 0.036      | -            | -                | -                | -         |    -0.50 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4354 | 2024-02-12 | inSanitY          | W   | 0.030      | -            | -                | -                | -         |     0.05 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,540.35)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.883 | $1,075.00      | $948.99         |
| 2024-06-09 |      0.816 | $1,500.00      | $1,224.44       |
| 2024-04-15 |      0.449 | $5,000.00      | $2,247.22       |
| 2024-04-11 |      0.423 | $592.00        | $250.61         |
| 2024-02-22 |      0.096 | $1,417.00      | $136.58         |
| 2024-02-21 |      0.088 | $1,500.00      | $132.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
