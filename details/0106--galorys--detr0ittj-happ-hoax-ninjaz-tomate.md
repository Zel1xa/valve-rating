### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Global Rank: [106](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
<br />
Final Rank Value:  843.2<br />
<br />
Final Rank Value (843.2) = Starting Rank Value (902.8) + Head To Head Adjustments (-59.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.218[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 902.8
- 400 + ( ( 0.244 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 902.8


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
|           95 |      223 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.776 (0.349)    | 0 (0.000) |    23.45 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      229 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.55 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      326 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.48 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      344 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.778 (0.284)    | 0 (0.000) |    19.42 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      388 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      389 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.25 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      461 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.56 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      511 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.10 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      551 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      630 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.96 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      681 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      684 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.359 (0.161)    | 0 (0.000) |    13.37 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      697 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.04 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      749 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.65 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      770 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.27 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      795 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.10 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      801 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.447 (0.201)    | 0 (0.000) |    23.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      877 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.90 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      896 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.80 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      938 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.17 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      968 | 2024-06-30 | Vikings KR        | L   | 0.954      | -            | -                | -                | -         |   -16.20 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      975 | 2024-06-29 | inSanitY          | L   | 0.948      | -            | -                | -                | -         |    -8.59 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      986 | 2024-06-27 | Sharks            | L   | 0.936      | -            | -                | -                | -         |    -8.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      988 | 2024-06-27 | KRÜ               | W   | 0.935      | 0.333        | -                | 0.479 (0.149)    | 0 (0.000) |    15.33 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |     1011 | 2024-06-18 | inSanitY          | L   | 0.876      | -            | -                | -                | -         |    -9.13 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1238 | 2024-06-09 | ODDIK             | L   | 0.815      | -            | -                | -                | -         |   -10.47 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1332 | 2024-06-08 | Case              | W   | 0.807      | 0.450        | 0.029 (0.011)    | 0.778 (0.283)    | 0 (0.000) |    12.46 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1361 | 2024-06-07 | Imperial          | L   | 0.802      | -            | -                | -                | -         |    -2.38 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1389 | 2024-06-07 | W7M               | L   | 0.800      | -            | -                | -                | -         |   -15.43 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1407 | 2024-06-06 | paiN              | L   | 0.797      | -            | -                | -                | -         |    -1.86 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1420 | 2024-06-06 | ex-Corinthians    | W   | 0.795      | -            | -                | -                | -         |     3.30 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1538 | 2024-06-04 | MIBR              | L   | 0.783      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1577 | 2024-06-03 | Intense           | L   | 0.774      | -            | -                | -                | -         |   -16.40 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1625 | 2024-06-01 | Hype              | L   | 0.761      | -            | -                | -                | -         |   -12.40 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1678 | 2024-05-30 | Hawks             | W   | 0.749      | -            | -                | -                | -         |     2.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1764 | 2024-05-27 | Dusty Roots       | W   | 0.727      | -            | -                | -                | -         |     9.73 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1944 | 2024-05-20 | Case              | L   | 0.681      | -            | -                | -                | -         |   -10.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1969 | 2024-05-19 | Solid             | W   | 0.675      | 0.303        | -                | 0.807 (0.165)    | -         |    10.18 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1995 | 2024-05-18 | ODDIK             | L   | 0.668      | -            | -                | -                | -         |    -8.82 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2111 | 2024-05-15 | Hype              | W   | 0.649      | -            | -                | -                | -         |    10.26 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2120 | 2024-05-15 | Case              | L   | 0.648      | -            | -                | -                | -         |   -10.75 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2161 | 2024-05-14 | Case              | L   | 0.643      | -            | -                | -                | -         |   -11.30 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2166 | 2024-05-14 | Case              | W   | 0.642      | 0.450        | 0.029 (0.008)    | 0.778 (0.225)    | -         |     9.09 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2178 | 2024-05-14 | 9z                | L   | 0.641      | -            | -                | -                | -         |    -0.65 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2197 | 2024-05-13 | 9z                | L   | 0.636      | -            | -                | -                | -         |    -0.65 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2202 | 2024-05-13 | Yawara            | W   | 0.635      | -            | -                | -                | -         |     2.00 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2222 | 2024-05-12 | KRÜ               | W   | 0.628      | -            | -                | -                | -         |    10.53 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2261 | 2024-05-11 | Case              | W   | 0.620      | 0.384        | -                | 0.778 (0.186)    | -         |    10.00 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2320 | 2024-05-08 | paiN              | L   | 0.602      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2323 | 2024-05-08 | paiN              | L   | 0.601      | -            | -                | -                | -         |    -1.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2345 | 2024-05-07 | KRÜ               | L   | 0.594      | -            | -                | -                | -         |    -9.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2380 | 2024-05-05 | W7M               | L   | 0.580      | -            | -                | -                | -         |   -11.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2688 | 2024-04-20 | Solid             | W   | 0.483      | 0.450        | -                | 0.807 (0.175)    | -         |     7.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2689 | 2024-04-20 | Solid             | L   | 0.482      | -            | -                | -                | -         |    -8.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2865 | 2024-04-16 | Case              | L   | 0.456      | -            | -                | -                | -         |    -7.28 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2903 | 2024-04-14 | MIBR              | L   | 0.442      | -            | -                | -                | -         |    -0.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2922 | 2024-04-13 | Fluxo             | W   | 0.434      | 0.435        | 0.123 (0.023)    | -                | -         |     9.76 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2931 | 2024-04-12 | Sharks            | W   | 0.429      | -            | -                | -                | -         |     4.47 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2951 | 2024-04-11 | Vikings KR        | L   | 0.422      | -            | -                | -                | -         |    -8.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2958 | 2024-04-11 | BESTIA            | W   | 0.421      | 0.435        | 0.096 (0.018)    | -                | -         |     7.89 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2986 | 2024-04-10 | MIBR              | L   | 0.416      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2990 | 2024-04-10 | MIBR              | L   | 0.416      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3040 | 2024-04-09 | BESTIA            | W   | 0.409      | 0.450        | 0.096 (0.018)    | -                | -         |     7.92 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3045 | 2024-04-09 | BESTIA            | L   | 0.409      | -            | -                | -                | -         |    -5.05 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3118 | 2024-04-07 | paiN              | L   | 0.395      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3348 | 2024-03-27 | Fluxo             | W   | 0.323      | 0.450        | 0.123 (0.018)    | -                | -         |     7.18 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3354 | 2024-03-27 | Fluxo             | L   | 0.323      | -            | -                | -                | -         |    -3.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3394 | 2024-03-26 | 2GAME             | W   | 0.316      | -            | -                | -                | -         |     2.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3396 | 2024-03-26 | 2GAME             | W   | 0.316      | -            | -                | -                | -         |     2.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3590 | 2024-03-14 | W7M               | W   | 0.236      | -            | -                | -                | -         |     3.09 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3592 | 2024-03-14 | W7M               | W   | 0.236      | -            | -                | -                | -         |     3.15 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3636 | 2024-03-13 | RED Canids        | L   | 0.228      | -            | -                | -                | -         |    -1.86 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3680 | 2024-03-11 | LA RUGONETA       | L   | 0.215      | -            | -                | -                | -         |    -5.96 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3702 | 2024-03-10 | MIBR              | L   | 0.209      | -            | -                | -                | -         |    -0.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3760 | 2024-03-08 | ODDIK             | W   | 0.194      | 0.435        | 0.099 (0.008)    | -                | -         |     3.92 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     4041 | 2024-02-24 | Sharks            | L   | 0.110      | -            | -                | -                | -         |    -1.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4049 | 2024-02-24 | Sharks            | L   | 0.109      | -            | -                | -                | -         |    -1.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4072 | 2024-02-23 | Corinthians       | L   | 0.103      | -            | -                | -                | -         |    -2.91 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4073 | 2024-02-23 | Corinthians       | W   | 0.102      | -            | -                | -                | -         |     0.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4090 | 2024-02-22 | MIBR Academy      | W   | 0.095      | -            | -                | -                | -         |     0.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4105 | 2024-02-21 | adalYamigos       | L   | 0.090      | -            | -                | -                | -         |    -2.41 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4109 | 2024-02-21 | adalYamigos       | L   | 0.089      | -            | -                | -                | -         |    -2.41 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4116 | 2024-02-21 | Sharks            | L   | 0.087      | -            | -                | -                | -         |    -1.13 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4184 | 2024-02-18 | Sharks            | L   | 0.070      | -            | -                | -                | -         |    -0.90 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4186 | 2024-02-18 | Case              | W   | 0.068      | -            | -                | -                | -         |     1.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4212 | 2024-02-17 | Sharks            | W   | 0.062      | -            | -                | -                | -         |     1.15 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4215 | 2024-02-17 | Corinthians       | W   | 0.061      | -            | -                | -                | -         |     0.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4236 | 2024-02-16 | Flamengo          | W   | 0.056      | -            | -                | -                | -         |     0.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4239 | 2024-02-16 | Imperial          | L   | 0.055      | -            | -                | -                | -         |    -0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4244 | 2024-02-16 | Imperial          | L   | 0.054      | -            | -                | -                | -         |    -0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4270 | 2024-02-15 | 9z Academy        | W   | 0.048      | -            | -                | -                | -         |     0.15 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4297 | 2024-02-14 | Solid             | L   | 0.043      | -            | -                | -                | -         |    -0.68 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4311 | 2024-02-14 | Sharks            | L   | 0.041      | -            | -                | -                | -         |    -0.53 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4346 | 2024-02-13 | Case              | L   | 0.035      | -            | -                | -                | -         |    -0.49 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4356 | 2024-02-12 | inSanitY          | W   | 0.029      | -            | -                | -                | -         |     0.05 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,530.09)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.882 | $1,075.00      | $947.99         |
| 2024-06-09 |      0.815 | $1,500.00      | $1,223.06       |
| 2024-04-15 |      0.449 | $5,000.00      | $2,242.59       |
| 2024-04-11 |      0.422 | $592.00        | $250.07         |
| 2024-02-22 |      0.095 | $1,417.00      | $135.27         |
| 2024-02-21 |      0.087 | $1,500.00      | $131.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
