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
|           95 |      239 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.776 (0.349)    | 0 (0.000) |    23.44 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      245 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.56 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      342 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.48 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      360 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.778 (0.284)    | 0 (0.000) |    19.42 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      404 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      405 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.25 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      477 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.56 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      527 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.10 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      567 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      646 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.97 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      697 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      700 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.359 (0.162)    | 0 (0.000) |    13.37 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      713 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.04 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      765 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.65 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      786 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.27 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      811 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.11 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      817 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.448 (0.201)    | 0 (0.000) |    23.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      893 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.90 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      912 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.80 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      954 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.18 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      984 | 2024-06-30 | Vikings KR        | L   | 0.953      | -            | -                | -                | -         |   -16.19 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      991 | 2024-06-29 | inSanitY          | L   | 0.948      | -            | -                | -                | -         |    -8.59 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |     1002 | 2024-06-27 | Sharks            | L   | 0.935      | -            | -                | -                | -         |    -8.60 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |     1004 | 2024-06-27 | KRÜ               | W   | 0.934      | 0.333        | -                | 0.479 (0.149)    | 0 (0.000) |    15.31 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |     1027 | 2024-06-18 | inSanitY          | L   | 0.875      | -            | -                | -                | -         |    -9.13 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1254 | 2024-06-09 | ODDIK             | L   | 0.815      | -            | -                | -                | -         |   -10.46 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1348 | 2024-06-08 | Case              | W   | 0.806      | 0.450        | 0.029 (0.011)    | 0.778 (0.282)    | 0 (0.000) |    12.45 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1377 | 2024-06-07 | Imperial          | L   | 0.801      | -            | -                | -                | -         |    -2.38 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1405 | 2024-06-07 | W7M               | L   | 0.799      | -            | -                | -                | -         |   -15.41 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1423 | 2024-06-06 | paiN              | L   | 0.796      | -            | -                | -                | -         |    -1.86 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1436 | 2024-06-06 | ex-Corinthians    | W   | 0.795      | -            | -                | -                | -         |     3.30 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1554 | 2024-06-04 | MIBR              | L   | 0.782      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1593 | 2024-06-03 | Intense           | L   | 0.774      | -            | -                | -                | -         |   -16.38 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1641 | 2024-06-01 | Hype              | L   | 0.760      | -            | -                | -                | -         |   -12.39 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1694 | 2024-05-30 | Hawks             | W   | 0.748      | -            | -                | -                | -         |     2.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1780 | 2024-05-27 | Dusty Roots       | W   | 0.726      | -            | -                | -                | -         |     9.72 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1960 | 2024-05-20 | Case              | L   | 0.680      | -            | -                | -                | -         |   -10.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1985 | 2024-05-19 | Solid             | W   | 0.674      | 0.303        | -                | 0.807 (0.165)    | -         |    10.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     2011 | 2024-05-18 | ODDIK             | L   | 0.667      | -            | -                | -                | -         |    -8.81 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2127 | 2024-05-15 | Hype              | W   | 0.648      | -            | -                | -                | -         |    10.25 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2136 | 2024-05-15 | Case              | L   | 0.647      | -            | -                | -                | -         |   -10.74 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2177 | 2024-05-14 | Case              | L   | 0.642      | -            | -                | -                | -         |   -11.28 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2182 | 2024-05-14 | Case              | W   | 0.642      | 0.450        | 0.029 (0.008)    | 0.778 (0.225)    | -         |     9.08 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2194 | 2024-05-14 | 9z                | L   | 0.640      | -            | -                | -                | -         |    -0.65 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2213 | 2024-05-13 | 9z                | L   | 0.635      | -            | -                | -                | -         |    -0.65 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2218 | 2024-05-13 | Yawara            | W   | 0.634      | -            | -                | -                | -         |     1.99 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2238 | 2024-05-12 | KRÜ               | W   | 0.628      | -            | -                | -                | -         |    10.51 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2277 | 2024-05-11 | Case              | W   | 0.620      | 0.384        | -                | 0.778 (0.185)    | -         |     9.98 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2336 | 2024-05-08 | paiN              | L   | 0.601      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2339 | 2024-05-08 | paiN              | L   | 0.600      | -            | -                | -                | -         |    -1.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2361 | 2024-05-07 | KRÜ               | L   | 0.593      | -            | -                | -                | -         |    -9.11 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2396 | 2024-05-05 | W7M               | L   | 0.579      | -            | -                | -                | -         |   -11.08 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2704 | 2024-04-20 | Solid             | W   | 0.482      | 0.450        | -                | 0.807 (0.175)    | -         |     7.25 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2705 | 2024-04-20 | Solid             | L   | 0.482      | -            | -                | -                | -         |    -8.11 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2881 | 2024-04-16 | Case              | L   | 0.455      | -            | -                | -                | -         |    -7.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2919 | 2024-04-14 | MIBR              | L   | 0.441      | -            | -                | -                | -         |    -0.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2938 | 2024-04-13 | Fluxo             | W   | 0.433      | 0.435        | 0.123 (0.023)    | -                | -         |     9.73 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2947 | 2024-04-12 | Sharks            | W   | 0.428      | -            | -                | -                | -         |     4.46 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2967 | 2024-04-11 | Vikings KR        | L   | 0.422      | -            | -                | -                | -         |    -8.08 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2974 | 2024-04-11 | BESTIA            | W   | 0.420      | 0.435        | 0.096 (0.017)    | -                | -         |     7.87 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     3002 | 2024-04-10 | MIBR              | L   | 0.415      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     3006 | 2024-04-10 | MIBR              | L   | 0.415      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3056 | 2024-04-09 | BESTIA            | W   | 0.408      | 0.450        | 0.096 (0.018)    | -                | -         |     7.91 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3061 | 2024-04-09 | BESTIA            | L   | 0.408      | -            | -                | -                | -         |    -5.04 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3134 | 2024-04-07 | paiN              | L   | 0.394      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3364 | 2024-03-27 | Fluxo             | W   | 0.322      | 0.450        | 0.123 (0.018)    | -                | -         |     7.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3370 | 2024-03-27 | Fluxo             | L   | 0.322      | -            | -                | -                | -         |    -3.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3410 | 2024-03-26 | 2GAME             | W   | 0.316      | -            | -                | -                | -         |     2.32 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3412 | 2024-03-26 | 2GAME             | W   | 0.315      | -            | -                | -                | -         |     2.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3606 | 2024-03-14 | W7M               | W   | 0.235      | -            | -                | -                | -         |     3.08 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3608 | 2024-03-14 | W7M               | W   | 0.235      | -            | -                | -                | -         |     3.14 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3652 | 2024-03-13 | RED Canids        | L   | 0.227      | -            | -                | -                | -         |    -1.86 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3696 | 2024-03-11 | LA RUGONETA       | L   | 0.214      | -            | -                | -                | -         |    -5.93 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3718 | 2024-03-10 | MIBR              | L   | 0.208      | -            | -                | -                | -         |    -0.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3776 | 2024-03-08 | ODDIK             | W   | 0.193      | 0.435        | 0.099 (0.008)    | -                | -         |     3.90 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     4057 | 2024-02-24 | Sharks            | L   | 0.109      | -            | -                | -                | -         |    -1.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4065 | 2024-02-24 | Sharks            | L   | 0.108      | -            | -                | -                | -         |    -1.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4088 | 2024-02-23 | Corinthians       | L   | 0.102      | -            | -                | -                | -         |    -2.88 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4089 | 2024-02-23 | Corinthians       | W   | 0.102      | -            | -                | -                | -         |     0.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4106 | 2024-02-22 | MIBR Academy      | W   | 0.095      | -            | -                | -                | -         |     0.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4121 | 2024-02-21 | adalYamigos       | L   | 0.089      | -            | -                | -                | -         |    -2.39 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4125 | 2024-02-21 | adalYamigos       | L   | 0.088      | -            | -                | -                | -         |    -2.39 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4132 | 2024-02-21 | Sharks            | L   | 0.087      | -            | -                | -                | -         |    -1.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4200 | 2024-02-18 | Sharks            | L   | 0.069      | -            | -                | -                | -         |    -0.89 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4202 | 2024-02-18 | Case              | W   | 0.068      | -            | -                | -                | -         |     1.18 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4228 | 2024-02-17 | Sharks            | W   | 0.061      | -            | -                | -                | -         |     1.14 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4231 | 2024-02-17 | Corinthians       | W   | 0.060      | -            | -                | -                | -         |     0.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4252 | 2024-02-16 | Flamengo          | W   | 0.055      | -            | -                | -                | -         |     0.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4255 | 2024-02-16 | Imperial          | L   | 0.054      | -            | -                | -                | -         |    -0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4260 | 2024-02-16 | Imperial          | L   | 0.053      | -            | -                | -                | -         |    -0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4286 | 2024-02-15 | 9z Academy        | W   | 0.047      | -            | -                | -                | -         |     0.15 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4313 | 2024-02-14 | Solid             | L   | 0.042      | -            | -                | -                | -         |    -0.67 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4327 | 2024-02-14 | Sharks            | L   | 0.040      | -            | -                | -                | -         |    -0.51 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4362 | 2024-02-13 | Case              | L   | 0.034      | -            | -                | -                | -         |    -0.48 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4372 | 2024-02-12 | inSanitY          | W   | 0.028      | -            | -                | -                | -         |     0.05 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,520.34)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.881 | $1,075.00      | $947.05         |
| 2024-06-09 |      0.814 | $1,500.00      | $1,221.74       |
| 2024-04-15 |      0.448 | $5,000.00      | $2,238.19       |
| 2024-04-11 |      0.422 | $592.00        | $249.54         |
| 2024-02-22 |      0.095 | $1,417.00      | $134.02         |
| 2024-02-21 |      0.087 | $1,500.00      | $129.79         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
