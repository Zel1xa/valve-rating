### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Global Rank: [106](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
<br />
Final Rank Value:  844.2<br />
<br />
Final Rank Value (844.2) = Starting Rank Value (904.4) + Head To Head Adjustments (-60.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.365[<sup>2</sup>](#table1)
- Opponent Network: 0.223[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 904.4
- 400 + ( ( 0.246 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 904.4


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
|           95 |      215 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.792 (0.356)    | 0 (0.000) |    23.47 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      221 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.53 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      318 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.46 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      336 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.795 (0.290)    | 0 (0.000) |    19.43 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      380 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      381 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.24 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      453 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.56 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      503 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.08 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      543 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.93 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      622 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      673 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.96 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      676 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.366 (0.165)    | 0 (0.000) |    13.34 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      689 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.02 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      741 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.63 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      762 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.29 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      787 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.06 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      793 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.457 (0.206)    | 0 (0.000) |    23.98 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      869 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      888 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.74 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      930 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.16 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      960 | 2024-06-30 | Vikings KR        | L   | 0.960      | -            | -                | -                | -         |   -16.29 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      967 | 2024-06-29 | inSanitY          | L   | 0.954      | -            | -                | -                | -         |    -8.60 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      978 | 2024-06-27 | Sharks            | L   | 0.941      | -            | -                | -                | -         |    -8.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      980 | 2024-06-27 | KRÜ               | W   | 0.940      | 0.333        | -                | 0.488 (0.153)    | 0 (0.000) |    15.43 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |     1003 | 2024-06-18 | inSanitY          | L   | 0.881      | -            | -                | -                | -         |    -9.15 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1230 | 2024-06-09 | ODDIK             | L   | 0.821      | -            | -                | -                | -         |   -10.52 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1324 | 2024-06-08 | Case              | W   | 0.812      | 0.450        | 0.029 (0.011)    | 0.795 (0.291)    | 0 (0.000) |    12.54 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1353 | 2024-06-07 | Imperial          | L   | 0.807      | -            | -                | -                | -         |    -2.37 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1381 | 2024-06-07 | W7M               | L   | 0.805      | -            | -                | -                | -         |   -15.53 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1399 | 2024-06-06 | paiN              | L   | 0.802      | -            | -                | -                | -         |    -1.85 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1412 | 2024-06-06 | ex-Corinthians    | W   | 0.801      | -            | -                | -                | -         |     3.30 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1530 | 2024-06-04 | MIBR              | L   | 0.788      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1569 | 2024-06-03 | Intense           | L   | 0.780      | -            | -                | -                | -         |   -16.53 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1617 | 2024-06-01 | Hype              | L   | 0.766      | -            | -                | -                | -         |   -12.49 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1670 | 2024-05-30 | Hawks             | W   | 0.754      | -            | -                | -                | -         |     2.90 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1756 | 2024-05-27 | Dusty Roots       | W   | 0.732      | -            | -                | -                | -         |     9.76 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1936 | 2024-05-20 | Case              | L   | 0.687      | -            | -                | -                | -         |   -10.43 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1961 | 2024-05-19 | Solid             | W   | 0.680      | 0.303        | -                | 0.825 (0.170)    | -         |    10.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1987 | 2024-05-18 | ODDIK             | L   | 0.673      | -            | -                | -                | -         |    -8.89 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2103 | 2024-05-15 | Hype              | W   | 0.654      | -            | -                | -                | -         |    10.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2112 | 2024-05-15 | Case              | L   | 0.653      | -            | -                | -                | -         |   -10.84 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2153 | 2024-05-14 | Case              | L   | 0.648      | -            | -                | -                | -         |   -11.40 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2158 | 2024-05-14 | Case              | W   | 0.648      | 0.450        | 0.029 (0.009)    | 0.795 (0.232)    | -         |     9.15 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2170 | 2024-05-14 | 9z                | L   | 0.647      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2189 | 2024-05-13 | 9z                | L   | 0.641      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2194 | 2024-05-13 | Yawara            | W   | 0.640      | -            | -                | -                | -         |     2.00 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2214 | 2024-05-12 | KRÜ               | W   | 0.634      | -            | -                | -                | -         |    10.63 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2253 | 2024-05-11 | Case              | W   | 0.626      | 0.384        | -                | 0.795 (0.191)    | -         |    10.08 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2312 | 2024-05-08 | paiN              | L   | 0.607      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2315 | 2024-05-08 | paiN              | L   | 0.607      | -            | -                | -                | -         |    -1.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2337 | 2024-05-07 | KRÜ               | L   | 0.599      | -            | -                | -                | -         |    -9.18 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2372 | 2024-05-05 | W7M               | L   | 0.585      | -            | -                | -                | -         |   -11.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2680 | 2024-04-20 | Solid             | W   | 0.488      | 0.450        | -                | 0.825 (0.181)    | -         |     7.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2681 | 2024-04-20 | Solid             | L   | 0.488      | -            | -                | -                | -         |    -8.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2857 | 2024-04-16 | Case              | L   | 0.461      | -            | -                | -                | -         |    -7.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2895 | 2024-04-14 | MIBR              | L   | 0.447      | -            | -                | -                | -         |    -0.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2914 | 2024-04-13 | Fluxo             | W   | 0.439      | 0.435        | 0.123 (0.024)    | -                | -         |     9.89 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2923 | 2024-04-12 | Sharks            | W   | 0.434      | -            | -                | -                | -         |     4.51 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2943 | 2024-04-11 | Vikings KR        | L   | 0.428      | -            | -                | -                | -         |    -8.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2950 | 2024-04-11 | BESTIA            | W   | 0.426      | 0.435        | 0.096 (0.018)    | -                | -         |     7.99 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2978 | 2024-04-10 | MIBR              | L   | 0.421      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2982 | 2024-04-10 | MIBR              | L   | 0.421      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3032 | 2024-04-09 | BESTIA            | W   | 0.415      | 0.450        | 0.096 (0.018)    | -                | -         |     8.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3037 | 2024-04-09 | BESTIA            | L   | 0.414      | -            | -                | -                | -         |    -5.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3110 | 2024-04-07 | paiN              | L   | 0.400      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3340 | 2024-03-27 | Fluxo             | W   | 0.328      | 0.450        | 0.123 (0.018)    | -                | -         |     7.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3346 | 2024-03-27 | Fluxo             | L   | 0.328      | -            | -                | -                | -         |    -3.06 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3386 | 2024-03-26 | 2GAME             | W   | 0.322      | -            | -                | -                | -         |     2.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3388 | 2024-03-26 | 2GAME             | W   | 0.321      | -            | -                | -                | -         |     2.40 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3582 | 2024-03-14 | W7M               | W   | 0.242      | -            | -                | -                | -         |     3.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3584 | 2024-03-14 | W7M               | W   | 0.241      | -            | -                | -                | -         |     3.22 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3628 | 2024-03-13 | RED Canids        | L   | 0.233      | -            | -                | -                | -         |    -1.90 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3672 | 2024-03-11 | LA RUGONETA       | L   | 0.220      | -            | -                | -                | -         |    -6.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3694 | 2024-03-10 | MIBR              | L   | 0.214      | -            | -                | -                | -         |    -0.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3752 | 2024-03-08 | ODDIK             | W   | 0.199      | 0.435        | 0.099 (0.009)    | -                | -         |     4.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     4033 | 2024-02-24 | Sharks            | L   | 0.115      | -            | -                | -                | -         |    -1.42 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4041 | 2024-02-24 | Sharks            | L   | 0.115      | -            | -                | -                | -         |    -1.43 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4064 | 2024-02-23 | Corinthians       | L   | 0.108      | -            | -                | -                | -         |    -3.06 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4065 | 2024-02-23 | Corinthians       | W   | 0.108      | -            | -                | -                | -         |     0.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4082 | 2024-02-22 | MIBR Academy      | W   | 0.101      | -            | -                | -                | -         |     0.32 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4097 | 2024-02-21 | adalYamigos       | L   | 0.095      | -            | -                | -                | -         |    -2.55 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4101 | 2024-02-21 | adalYamigos       | L   | 0.095      | -            | -                | -                | -         |    -2.55 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4108 | 2024-02-21 | Sharks            | L   | 0.093      | -            | -                | -                | -         |    -1.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4176 | 2024-02-18 | Sharks            | L   | 0.075      | -            | -                | -                | -         |    -0.97 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4178 | 2024-02-18 | Case              | W   | 0.074      | -            | -                | -                | -         |     1.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4204 | 2024-02-17 | Sharks            | W   | 0.067      | -            | -                | -                | -         |     1.25 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4207 | 2024-02-17 | Corinthians       | W   | 0.066      | -            | -                | -                | -         |     0.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4228 | 2024-02-16 | Flamengo          | W   | 0.061      | -            | -                | -                | -         |     0.18 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4231 | 2024-02-16 | Imperial          | L   | 0.060      | -            | -                | -                | -         |    -0.22 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4236 | 2024-02-16 | Imperial          | L   | 0.060      | -            | -                | -                | -         |    -0.22 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4262 | 2024-02-15 | 9z Academy        | W   | 0.053      | -            | -                | -                | -         |     0.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4289 | 2024-02-14 | Solid             | L   | 0.048      | -            | -                | -                | -         |    -0.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4303 | 2024-02-14 | Sharks            | L   | 0.046      | -            | -                | -                | -         |    -0.59 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4338 | 2024-02-13 | Case              | L   | 0.040      | -            | -                | -                | -         |    -0.56 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4348 | 2024-02-12 | inSanitY          | W   | 0.034      | -            | -                | -                | -         |     0.06 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,588.07)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.887 | $1,075.00      | $953.61         |
| 2024-06-09 |      0.821 | $1,500.00      | $1,230.90       |
| 2024-04-15 |      0.454 | $5,000.00      | $2,268.75       |
| 2024-04-11 |      0.428 | $592.00        | $253.16         |
| 2024-02-22 |      0.101 | $1,417.00      | $142.68         |
| 2024-02-21 |      0.093 | $1,500.00      | $138.96         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
