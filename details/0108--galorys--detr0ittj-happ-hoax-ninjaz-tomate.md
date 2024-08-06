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
|           95 |      225 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.775 (0.349)    | 0 (0.000) |    23.45 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      231 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.55 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      328 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.48 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      346 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.778 (0.284)    | 0 (0.000) |    19.42 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      390 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      391 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.25 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      463 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.57 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      513 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.10 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      553 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      632 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.96 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      683 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      686 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.358 (0.161)    | 0 (0.000) |    13.37 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      699 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.04 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      751 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.64 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      772 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.27 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      797 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.10 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      803 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.447 (0.201)    | 0 (0.000) |    23.95 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      879 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.90 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      898 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.80 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      940 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.17 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      970 | 2024-06-30 | Vikings KR        | L   | 0.955      | -            | -                | -                | -         |   -16.21 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      977 | 2024-06-29 | inSanitY          | L   | 0.949      | -            | -                | -                | -         |    -8.59 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      988 | 2024-06-27 | Sharks            | L   | 0.937      | -            | -                | -                | -         |    -8.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      990 | 2024-06-27 | KRÜ               | W   | 0.936      | 0.333        | -                | 0.478 (0.149)    | 0 (0.000) |    15.34 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |     1013 | 2024-06-18 | inSanitY          | L   | 0.877      | -            | -                | -                | -         |    -9.13 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1240 | 2024-06-09 | ODDIK             | L   | 0.816      | -            | -                | -                | -         |   -10.47 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1334 | 2024-06-08 | Case              | W   | 0.807      | 0.450        | 0.029 (0.011)    | 0.778 (0.283)    | 0 (0.000) |    12.47 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1363 | 2024-06-07 | Imperial          | L   | 0.803      | -            | -                | -                | -         |    -2.38 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1391 | 2024-06-07 | W7M               | L   | 0.801      | -            | -                | -                | -         |   -15.44 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1409 | 2024-06-06 | paiN              | L   | 0.797      | -            | -                | -                | -         |    -1.86 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1422 | 2024-06-06 | ex-Corinthians    | W   | 0.796      | -            | -                | -                | -         |     3.31 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1540 | 2024-06-04 | MIBR              | L   | 0.783      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1579 | 2024-06-03 | Intense           | L   | 0.775      | -            | -                | -                | -         |   -16.41 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1627 | 2024-06-01 | Hype              | L   | 0.762      | -            | -                | -                | -         |   -12.41 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1680 | 2024-05-30 | Hawks             | W   | 0.749      | -            | -                | -                | -         |     2.90 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1766 | 2024-05-27 | Dusty Roots       | W   | 0.728      | -            | -                | -                | -         |     9.74 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1946 | 2024-05-20 | Case              | L   | 0.682      | -            | -                | -                | -         |   -10.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1971 | 2024-05-19 | Solid             | W   | 0.675      | 0.303        | -                | 0.807 (0.165)    | -         |    10.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1997 | 2024-05-18 | ODDIK             | L   | 0.669      | -            | -                | -                | -         |    -8.83 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2113 | 2024-05-15 | Hype              | W   | 0.649      | -            | -                | -                | -         |    10.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2122 | 2024-05-15 | Case              | L   | 0.648      | -            | -                | -                | -         |   -10.76 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2163 | 2024-05-14 | Case              | L   | 0.643      | -            | -                | -                | -         |   -11.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2168 | 2024-05-14 | Case              | W   | 0.643      | 0.450        | 0.029 (0.008)    | 0.778 (0.225)    | -         |     9.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2180 | 2024-05-14 | 9z                | L   | 0.642      | -            | -                | -                | -         |    -0.65 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2199 | 2024-05-13 | 9z                | L   | 0.637      | -            | -                | -                | -         |    -0.65 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2204 | 2024-05-13 | Yawara            | W   | 0.635      | -            | -                | -                | -         |     2.00 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2224 | 2024-05-12 | KRÜ               | W   | 0.629      | -            | -                | -                | -         |    10.54 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2263 | 2024-05-11 | Case              | W   | 0.621      | 0.384        | -                | 0.778 (0.186)    | -         |    10.01 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2322 | 2024-05-08 | paiN              | L   | 0.602      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2325 | 2024-05-08 | paiN              | L   | 0.602      | -            | -                | -                | -         |    -1.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2347 | 2024-05-07 | KRÜ               | L   | 0.594      | -            | -                | -                | -         |    -9.13 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2382 | 2024-05-05 | W7M               | L   | 0.581      | -            | -                | -                | -         |   -11.11 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2690 | 2024-04-20 | Solid             | W   | 0.483      | 0.450        | -                | 0.807 (0.175)    | -         |     7.28 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2691 | 2024-04-20 | Solid             | L   | 0.483      | -            | -                | -                | -         |    -8.13 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2867 | 2024-04-16 | Case              | L   | 0.457      | -            | -                | -                | -         |    -7.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2905 | 2024-04-14 | MIBR              | L   | 0.443      | -            | -                | -                | -         |    -0.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2924 | 2024-04-13 | Fluxo             | W   | 0.434      | 0.435        | 0.123 (0.023)    | -                | -         |     9.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2933 | 2024-04-12 | Sharks            | W   | 0.429      | -            | -                | -                | -         |     4.48 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2953 | 2024-04-11 | Vikings KR        | L   | 0.423      | -            | -                | -                | -         |    -8.11 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2960 | 2024-04-11 | BESTIA            | W   | 0.422      | 0.435        | 0.096 (0.018)    | -                | -         |     7.90 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2988 | 2024-04-10 | MIBR              | L   | 0.417      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2992 | 2024-04-10 | MIBR              | L   | 0.416      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3042 | 2024-04-09 | BESTIA            | W   | 0.410      | 0.450        | 0.096 (0.018)    | -                | -         |     7.93 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3047 | 2024-04-09 | BESTIA            | L   | 0.410      | -            | -                | -                | -         |    -5.06 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3120 | 2024-04-07 | paiN              | L   | 0.396      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3350 | 2024-03-27 | Fluxo             | W   | 0.324      | 0.450        | 0.123 (0.018)    | -                | -         |     7.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3356 | 2024-03-27 | Fluxo             | L   | 0.323      | -            | -                | -                | -         |    -3.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3396 | 2024-03-26 | 2GAME             | W   | 0.317      | -            | -                | -                | -         |     2.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3398 | 2024-03-26 | 2GAME             | W   | 0.317      | -            | -                | -                | -         |     2.38 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3592 | 2024-03-14 | W7M               | W   | 0.237      | -            | -                | -                | -         |     3.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3594 | 2024-03-14 | W7M               | W   | 0.237      | -            | -                | -                | -         |     3.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3638 | 2024-03-13 | RED Canids        | L   | 0.229      | -            | -                | -                | -         |    -1.87 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3682 | 2024-03-11 | LA RUGONETA       | L   | 0.216      | -            | -                | -                | -         |    -5.97 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3704 | 2024-03-10 | MIBR              | L   | 0.210      | -            | -                | -                | -         |    -0.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3762 | 2024-03-08 | ODDIK             | W   | 0.194      | 0.435        | 0.099 (0.008)    | -                | -         |     3.93 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     4043 | 2024-02-24 | Sharks            | L   | 0.110      | -            | -                | -                | -         |    -1.37 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4051 | 2024-02-24 | Sharks            | L   | 0.110      | -            | -                | -                | -         |    -1.38 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4074 | 2024-02-23 | Corinthians       | L   | 0.103      | -            | -                | -                | -         |    -2.93 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4075 | 2024-02-23 | Corinthians       | W   | 0.103      | -            | -                | -                | -         |     0.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4092 | 2024-02-22 | MIBR Academy      | W   | 0.096      | -            | -                | -                | -         |     0.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4107 | 2024-02-21 | adalYamigos       | L   | 0.090      | -            | -                | -                | -         |    -2.43 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4111 | 2024-02-21 | adalYamigos       | L   | 0.090      | -            | -                | -                | -         |    -2.43 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4118 | 2024-02-21 | Sharks            | L   | 0.088      | -            | -                | -                | -         |    -1.14 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4186 | 2024-02-18 | Sharks            | L   | 0.070      | -            | -                | -                | -         |    -0.91 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4188 | 2024-02-18 | Case              | W   | 0.069      | -            | -                | -                | -         |     1.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4214 | 2024-02-17 | Sharks            | W   | 0.062      | -            | -                | -                | -         |     1.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4217 | 2024-02-17 | Corinthians       | W   | 0.062      | -            | -                | -                | -         |     0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4238 | 2024-02-16 | Flamengo          | W   | 0.056      | -            | -                | -                | -         |     0.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4241 | 2024-02-16 | Imperial          | L   | 0.055      | -            | -                | -                | -         |    -0.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4246 | 2024-02-16 | Imperial          | L   | 0.055      | -            | -                | -                | -         |    -0.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4272 | 2024-02-15 | 9z Academy        | W   | 0.049      | -            | -                | -                | -         |     0.15 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4299 | 2024-02-14 | Solid             | L   | 0.044      | -            | -                | -                | -         |    -0.69 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4313 | 2024-02-14 | Sharks            | L   | 0.042      | -            | -                | -                | -         |    -0.53 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4348 | 2024-02-13 | Case              | L   | 0.035      | -            | -                | -                | -         |    -0.50 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4358 | 2024-02-12 | inSanitY          | W   | 0.029      | -            | -                | -                | -         |     0.05 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,537.27)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.882 | $1,075.00      | $948.69         |
| 2024-06-09 |      0.816 | $1,500.00      | $1,224.03       |
| 2024-04-15 |      0.449 | $5,000.00      | $2,245.83       |
| 2024-04-11 |      0.423 | $592.00        | $250.45         |
| 2024-02-22 |      0.096 | $1,417.00      | $136.19         |
| 2024-02-21 |      0.088 | $1,500.00      | $132.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
