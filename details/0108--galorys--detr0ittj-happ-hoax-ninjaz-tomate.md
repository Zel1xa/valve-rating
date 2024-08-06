### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Global Rank: [108](../standings_global.md)<br />
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
|           95 |      228 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.776 (0.349)    | 0 (0.000) |    23.45 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      234 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.55 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      331 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.48 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      349 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.778 (0.284)    | 0 (0.000) |    19.42 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      393 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      394 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.25 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      466 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.56 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      516 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.10 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      556 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      635 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.96 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      686 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      689 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.359 (0.161)    | 0 (0.000) |    13.37 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      702 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.04 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      754 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.65 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      775 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.27 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      800 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.10 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      806 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.447 (0.201)    | 0 (0.000) |    23.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      882 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.90 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      901 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.80 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      943 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.17 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      973 | 2024-06-30 | Vikings KR        | L   | 0.955      | -            | -                | -                | -         |   -16.21 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      980 | 2024-06-29 | inSanitY          | L   | 0.949      | -            | -                | -                | -         |    -8.59 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      991 | 2024-06-27 | Sharks            | L   | 0.936      | -            | -                | -                | -         |    -8.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      993 | 2024-06-27 | KRÜ               | W   | 0.935      | 0.333        | -                | 0.479 (0.149)    | 0 (0.000) |    15.33 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |     1016 | 2024-06-18 | inSanitY          | L   | 0.876      | -            | -                | -                | -         |    -9.13 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1243 | 2024-06-09 | ODDIK             | L   | 0.816      | -            | -                | -                | -         |   -10.47 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1337 | 2024-06-08 | Case              | W   | 0.807      | 0.450        | 0.029 (0.011)    | 0.778 (0.283)    | 0 (0.000) |    12.46 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1366 | 2024-06-07 | Imperial          | L   | 0.802      | -            | -                | -                | -         |    -2.38 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1394 | 2024-06-07 | W7M               | L   | 0.800      | -            | -                | -                | -         |   -15.44 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1412 | 2024-06-06 | paiN              | L   | 0.797      | -            | -                | -                | -         |    -1.86 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1425 | 2024-06-06 | ex-Corinthians    | W   | 0.796      | -            | -                | -                | -         |     3.31 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1543 | 2024-06-04 | MIBR              | L   | 0.783      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1582 | 2024-06-03 | Intense           | L   | 0.775      | -            | -                | -                | -         |   -16.41 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1630 | 2024-06-01 | Hype              | L   | 0.761      | -            | -                | -                | -         |   -12.41 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1683 | 2024-05-30 | Hawks             | W   | 0.749      | -            | -                | -                | -         |     2.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1769 | 2024-05-27 | Dusty Roots       | W   | 0.727      | -            | -                | -                | -         |     9.73 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1949 | 2024-05-20 | Case              | L   | 0.682      | -            | -                | -                | -         |   -10.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1974 | 2024-05-19 | Solid             | W   | 0.675      | 0.303        | -                | 0.807 (0.165)    | -         |    10.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     2000 | 2024-05-18 | ODDIK             | L   | 0.668      | -            | -                | -                | -         |    -8.83 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2116 | 2024-05-15 | Hype              | W   | 0.649      | -            | -                | -                | -         |    10.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2125 | 2024-05-15 | Case              | L   | 0.648      | -            | -                | -                | -         |   -10.76 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2166 | 2024-05-14 | Case              | L   | 0.643      | -            | -                | -                | -         |   -11.30 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2171 | 2024-05-14 | Case              | W   | 0.643      | 0.450        | 0.029 (0.008)    | 0.778 (0.225)    | -         |     9.09 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2183 | 2024-05-14 | 9z                | L   | 0.642      | -            | -                | -                | -         |    -0.65 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2202 | 2024-05-13 | 9z                | L   | 0.636      | -            | -                | -                | -         |    -0.65 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2207 | 2024-05-13 | Yawara            | W   | 0.635      | -            | -                | -                | -         |     2.00 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2227 | 2024-05-12 | KRÜ               | W   | 0.629      | -            | -                | -                | -         |    10.53 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2266 | 2024-05-11 | Case              | W   | 0.621      | 0.384        | -                | 0.778 (0.186)    | -         |    10.00 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2325 | 2024-05-08 | paiN              | L   | 0.602      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2328 | 2024-05-08 | paiN              | L   | 0.602      | -            | -                | -                | -         |    -1.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2350 | 2024-05-07 | KRÜ               | L   | 0.594      | -            | -                | -                | -         |    -9.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2385 | 2024-05-05 | W7M               | L   | 0.580      | -            | -                | -                | -         |   -11.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2693 | 2024-04-20 | Solid             | W   | 0.483      | 0.450        | -                | 0.807 (0.175)    | -         |     7.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2694 | 2024-04-20 | Solid             | L   | 0.483      | -            | -                | -                | -         |    -8.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2870 | 2024-04-16 | Case              | L   | 0.457      | -            | -                | -                | -         |    -7.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2908 | 2024-04-14 | MIBR              | L   | 0.442      | -            | -                | -                | -         |    -0.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2927 | 2024-04-13 | Fluxo             | W   | 0.434      | 0.435        | 0.123 (0.023)    | -                | -         |     9.76 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2936 | 2024-04-12 | Sharks            | W   | 0.429      | -            | -                | -                | -         |     4.48 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2956 | 2024-04-11 | Vikings KR        | L   | 0.423      | -            | -                | -                | -         |    -8.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2963 | 2024-04-11 | BESTIA            | W   | 0.421      | 0.435        | 0.096 (0.018)    | -                | -         |     7.89 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2991 | 2024-04-10 | MIBR              | L   | 0.416      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2995 | 2024-04-10 | MIBR              | L   | 0.416      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3045 | 2024-04-09 | BESTIA            | W   | 0.410      | 0.450        | 0.096 (0.018)    | -                | -         |     7.93 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3050 | 2024-04-09 | BESTIA            | L   | 0.409      | -            | -                | -                | -         |    -5.06 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3123 | 2024-04-07 | paiN              | L   | 0.395      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3353 | 2024-03-27 | Fluxo             | W   | 0.323      | 0.450        | 0.123 (0.018)    | -                | -         |     7.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3359 | 2024-03-27 | Fluxo             | L   | 0.323      | -            | -                | -                | -         |    -3.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3399 | 2024-03-26 | 2GAME             | W   | 0.317      | -            | -                | -                | -         |     2.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3401 | 2024-03-26 | 2GAME             | W   | 0.316      | -            | -                | -                | -         |     2.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3595 | 2024-03-14 | W7M               | W   | 0.237      | -            | -                | -                | -         |     3.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3597 | 2024-03-14 | W7M               | W   | 0.236      | -            | -                | -                | -         |     3.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3641 | 2024-03-13 | RED Canids        | L   | 0.228      | -            | -                | -                | -         |    -1.87 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3685 | 2024-03-11 | LA RUGONETA       | L   | 0.215      | -            | -                | -                | -         |    -5.96 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3707 | 2024-03-10 | MIBR              | L   | 0.209      | -            | -                | -                | -         |    -0.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3765 | 2024-03-08 | ODDIK             | W   | 0.194      | 0.435        | 0.099 (0.008)    | -                | -         |     3.93 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     4046 | 2024-02-24 | Sharks            | L   | 0.110      | -            | -                | -                | -         |    -1.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4054 | 2024-02-24 | Sharks            | L   | 0.110      | -            | -                | -                | -         |    -1.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4077 | 2024-02-23 | Corinthians       | L   | 0.103      | -            | -                | -                | -         |    -2.92 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4078 | 2024-02-23 | Corinthians       | W   | 0.103      | -            | -                | -                | -         |     0.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4095 | 2024-02-22 | MIBR Academy      | W   | 0.096      | -            | -                | -                | -         |     0.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4110 | 2024-02-21 | adalYamigos       | L   | 0.090      | -            | -                | -                | -         |    -2.42 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4114 | 2024-02-21 | adalYamigos       | L   | 0.090      | -            | -                | -                | -         |    -2.42 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4121 | 2024-02-21 | Sharks            | L   | 0.088      | -            | -                | -                | -         |    -1.13 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4189 | 2024-02-18 | Sharks            | L   | 0.070      | -            | -                | -                | -         |    -0.91 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4191 | 2024-02-18 | Case              | W   | 0.069      | -            | -                | -                | -         |     1.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4217 | 2024-02-17 | Sharks            | W   | 0.062      | -            | -                | -                | -         |     1.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4220 | 2024-02-17 | Corinthians       | W   | 0.061      | -            | -                | -                | -         |     0.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4241 | 2024-02-16 | Flamengo          | W   | 0.056      | -            | -                | -                | -         |     0.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4244 | 2024-02-16 | Imperial          | L   | 0.055      | -            | -                | -                | -         |    -0.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4249 | 2024-02-16 | Imperial          | L   | 0.055      | -            | -                | -                | -         |    -0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4275 | 2024-02-15 | 9z Academy        | W   | 0.048      | -            | -                | -                | -         |     0.15 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4302 | 2024-02-14 | Solid             | L   | 0.043      | -            | -                | -                | -         |    -0.69 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4316 | 2024-02-14 | Sharks            | L   | 0.041      | -            | -                | -                | -         |    -0.53 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4351 | 2024-02-13 | Case              | L   | 0.035      | -            | -                | -                | -         |    -0.49 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4361 | 2024-02-12 | inSanitY          | W   | 0.029      | -            | -                | -                | -         |     0.05 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,533.17)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.882 | $1,075.00      | $948.29         |
| 2024-06-09 |      0.816 | $1,500.00      | $1,223.47       |
| 2024-04-15 |      0.449 | $5,000.00      | $2,243.98       |
| 2024-04-11 |      0.423 | $592.00        | $250.23         |
| 2024-02-22 |      0.096 | $1,417.00      | $135.66         |
| 2024-02-21 |      0.088 | $1,500.00      | $131.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
