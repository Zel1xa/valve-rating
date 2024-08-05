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
- Opponent Network: 0.224[<sup>2</sup>](#table1)
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
|           95 |      214 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.792 (0.356)    | 0 (0.000) |    23.47 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      220 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.53 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      317 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.46 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      335 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.795 (0.290)    | 0 (0.000) |    19.43 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      379 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.22 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      380 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.24 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      452 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.56 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      502 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.08 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      542 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.93 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      621 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      672 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.96 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      675 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.366 (0.165)    | 0 (0.000) |    13.34 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      688 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.02 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      740 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.63 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      761 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.29 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      786 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.06 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      792 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.457 (0.206)    | 0 (0.000) |    23.98 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      868 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      887 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.74 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      929 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.16 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      959 | 2024-06-30 | Vikings KR        | L   | 0.960      | -            | -                | -                | -         |   -16.30 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      966 | 2024-06-29 | inSanitY          | L   | 0.954      | -            | -                | -                | -         |    -8.60 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      977 | 2024-06-27 | Sharks            | L   | 0.942      | -            | -                | -                | -         |    -8.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      979 | 2024-06-27 | KRÜ               | W   | 0.941      | 0.333        | -                | 0.488 (0.153)    | 0 (0.000) |    15.44 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |     1002 | 2024-06-18 | inSanitY          | L   | 0.882      | -            | -                | -                | -         |    -9.15 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1229 | 2024-06-09 | ODDIK             | L   | 0.821      | -            | -                | -                | -         |   -10.53 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1323 | 2024-06-08 | Case              | W   | 0.813      | 0.450        | 0.029 (0.011)    | 0.795 (0.291)    | 0 (0.000) |    12.55 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1352 | 2024-06-07 | Imperial          | L   | 0.808      | -            | -                | -                | -         |    -2.37 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1380 | 2024-06-07 | W7M               | L   | 0.806      | -            | -                | -                | -         |   -15.54 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1398 | 2024-06-06 | paiN              | L   | 0.802      | -            | -                | -                | -         |    -1.85 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1411 | 2024-06-06 | ex-Corinthians    | W   | 0.801      | -            | -                | -                | -         |     3.30 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1529 | 2024-06-04 | MIBR              | L   | 0.788      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1568 | 2024-06-03 | Intense           | L   | 0.780      | -            | -                | -                | -         |   -16.54 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1616 | 2024-06-01 | Hype              | L   | 0.767      | -            | -                | -                | -         |   -12.50 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1669 | 2024-05-30 | Hawks             | W   | 0.754      | -            | -                | -                | -         |     2.90 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1755 | 2024-05-27 | Dusty Roots       | W   | 0.733      | -            | -                | -                | -         |     9.77 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1935 | 2024-05-20 | Case              | L   | 0.687      | -            | -                | -                | -         |   -10.44 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1960 | 2024-05-19 | Solid             | W   | 0.680      | 0.303        | -                | 0.825 (0.170)    | -         |    10.28 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1986 | 2024-05-18 | ODDIK             | L   | 0.674      | -            | -                | -                | -         |    -8.89 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2102 | 2024-05-15 | Hype              | W   | 0.654      | -            | -                | -                | -         |    10.35 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2111 | 2024-05-15 | Case              | L   | 0.653      | -            | -                | -                | -         |   -10.85 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2152 | 2024-05-14 | Case              | L   | 0.648      | -            | -                | -                | -         |   -11.40 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2157 | 2024-05-14 | Case              | W   | 0.648      | 0.450        | 0.029 (0.009)    | 0.795 (0.232)    | -         |     9.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2169 | 2024-05-14 | 9z                | L   | 0.647      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2188 | 2024-05-13 | 9z                | L   | 0.642      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2193 | 2024-05-13 | Yawara            | W   | 0.640      | -            | -                | -                | -         |     2.00 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2213 | 2024-05-12 | KRÜ               | W   | 0.634      | -            | -                | -                | -         |    10.64 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2252 | 2024-05-11 | Case              | W   | 0.626      | 0.384        | -                | 0.795 (0.191)    | -         |    10.09 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2311 | 2024-05-08 | paiN              | L   | 0.607      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2314 | 2024-05-08 | paiN              | L   | 0.607      | -            | -                | -                | -         |    -1.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2336 | 2024-05-07 | KRÜ               | L   | 0.599      | -            | -                | -                | -         |    -9.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2371 | 2024-05-05 | W7M               | L   | 0.586      | -            | -                | -                | -         |   -11.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2679 | 2024-04-20 | Solid             | W   | 0.488      | 0.450        | -                | 0.825 (0.181)    | -         |     7.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2680 | 2024-04-20 | Solid             | L   | 0.488      | -            | -                | -                | -         |    -8.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2856 | 2024-04-16 | Case              | L   | 0.462      | -            | -                | -                | -         |    -7.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2894 | 2024-04-14 | MIBR              | L   | 0.448      | -            | -                | -                | -         |    -0.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2913 | 2024-04-13 | Fluxo             | W   | 0.439      | 0.435        | 0.123 (0.024)    | -                | -         |     9.90 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2922 | 2024-04-12 | Sharks            | W   | 0.434      | -            | -                | -                | -         |     4.51 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2942 | 2024-04-11 | Vikings KR        | L   | 0.428      | -            | -                | -                | -         |    -8.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2949 | 2024-04-11 | BESTIA            | W   | 0.427      | 0.435        | 0.096 (0.018)    | -                | -         |     7.99 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2977 | 2024-04-10 | MIBR              | L   | 0.422      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2981 | 2024-04-10 | MIBR              | L   | 0.421      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3031 | 2024-04-09 | BESTIA            | W   | 0.415      | 0.450        | 0.096 (0.018)    | -                | -         |     8.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3036 | 2024-04-09 | BESTIA            | L   | 0.415      | -            | -                | -                | -         |    -5.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3109 | 2024-04-07 | paiN              | L   | 0.401      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3339 | 2024-03-27 | Fluxo             | W   | 0.329      | 0.450        | 0.123 (0.018)    | -                | -         |     7.32 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3345 | 2024-03-27 | Fluxo             | L   | 0.328      | -            | -                | -                | -         |    -3.06 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3385 | 2024-03-26 | 2GAME             | W   | 0.322      | -            | -                | -                | -         |     2.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3387 | 2024-03-26 | 2GAME             | W   | 0.322      | -            | -                | -                | -         |     2.41 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3581 | 2024-03-14 | W7M               | W   | 0.242      | -            | -                | -                | -         |     3.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3583 | 2024-03-14 | W7M               | W   | 0.242      | -            | -                | -                | -         |     3.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3627 | 2024-03-13 | RED Canids        | L   | 0.234      | -            | -                | -                | -         |    -1.90 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3671 | 2024-03-11 | LA RUGONETA       | L   | 0.221      | -            | -                | -                | -         |    -6.11 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3693 | 2024-03-10 | MIBR              | L   | 0.215      | -            | -                | -                | -         |    -0.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3751 | 2024-03-08 | ODDIK             | W   | 0.199      | 0.435        | 0.099 (0.009)    | -                | -         |     4.04 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     4032 | 2024-02-24 | Sharks            | L   | 0.115      | -            | -                | -                | -         |    -1.42 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4040 | 2024-02-24 | Sharks            | L   | 0.115      | -            | -                | -                | -         |    -1.44 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4063 | 2024-02-23 | Corinthians       | L   | 0.108      | -            | -                | -                | -         |    -3.07 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4064 | 2024-02-23 | Corinthians       | W   | 0.108      | -            | -                | -                | -         |     0.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4081 | 2024-02-22 | MIBR Academy      | W   | 0.101      | -            | -                | -                | -         |     0.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4096 | 2024-02-21 | adalYamigos       | L   | 0.095      | -            | -                | -                | -         |    -2.56 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4100 | 2024-02-21 | adalYamigos       | L   | 0.095      | -            | -                | -                | -         |    -2.56 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4107 | 2024-02-21 | Sharks            | L   | 0.093      | -            | -                | -                | -         |    -1.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4175 | 2024-02-18 | Sharks            | L   | 0.075      | -            | -                | -                | -         |    -0.97 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4177 | 2024-02-18 | Case              | W   | 0.074      | -            | -                | -                | -         |     1.30 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4203 | 2024-02-17 | Sharks            | W   | 0.067      | -            | -                | -                | -         |     1.26 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4206 | 2024-02-17 | Corinthians       | W   | 0.067      | -            | -                | -                | -         |     0.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4227 | 2024-02-16 | Flamengo          | W   | 0.061      | -            | -                | -                | -         |     0.18 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4230 | 2024-02-16 | Imperial          | L   | 0.060      | -            | -                | -                | -         |    -0.22 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4235 | 2024-02-16 | Imperial          | L   | 0.060      | -            | -                | -                | -         |    -0.22 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4261 | 2024-02-15 | 9z Academy        | W   | 0.054      | -            | -                | -                | -         |     0.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4288 | 2024-02-14 | Solid             | L   | 0.049      | -            | -                | -                | -         |    -0.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4302 | 2024-02-14 | Sharks            | L   | 0.047      | -            | -                | -                | -         |    -0.60 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4337 | 2024-02-13 | Case              | L   | 0.040      | -            | -                | -                | -         |    -0.57 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4347 | 2024-02-12 | inSanitY          | W   | 0.034      | -            | -                | -                | -         |     0.06 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,592.69)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.887 | $1,075.00      | $954.06         |
| 2024-06-09 |      0.821 | $1,500.00      | $1,231.53       |
| 2024-04-15 |      0.454 | $5,000.00      | $2,270.83       |
| 2024-04-11 |      0.428 | $592.00        | $253.41         |
| 2024-02-22 |      0.101 | $1,417.00      | $143.27         |
| 2024-02-21 |      0.093 | $1,500.00      | $139.58         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
