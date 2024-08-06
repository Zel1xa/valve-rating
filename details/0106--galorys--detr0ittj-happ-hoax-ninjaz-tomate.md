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
Final Rank Value (844.2) = Starting Rank Value (904.3) + Head To Head Adjustments (-60.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.223[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 904.3
- 400 + ( ( 0.246 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 904.3


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
|           95 |      217 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.792 (0.357)    | 0 (0.000) |    23.46 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      223 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.54 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      320 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.47 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      338 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.029 (0.011)    | 0.795 (0.290)    | 0 (0.000) |    19.42 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      382 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      383 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.25 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      455 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.56 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      505 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.08 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      545 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      624 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.94 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      675 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.96 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      678 | 2024-07-17 | Dusty Roots       | W   | 1.000      | 0.450        | -                | 0.366 (0.165)    | 0 (0.000) |    13.35 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      691 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.02 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      743 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.64 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      764 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.29 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      789 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.08 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      795 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.457 (0.206)    | 0 (0.000) |    23.97 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      871 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      890 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.74 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      932 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.17 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      962 | 2024-06-30 | Vikings KR        | L   | 0.958      | -            | -                | -                | -         |   -16.26 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      969 | 2024-06-29 | inSanitY          | L   | 0.952      | -            | -                | -                | -         |    -8.60 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      980 | 2024-06-27 | Sharks            | L   | 0.939      | -            | -                | -                | -         |    -8.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      982 | 2024-06-27 | KRÜ               | W   | 0.938      | 0.333        | -                | 0.488 (0.153)    | 0 (0.000) |    15.40 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |     1005 | 2024-06-18 | inSanitY          | L   | 0.879      | -            | -                | -                | -         |    -9.14 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1232 | 2024-06-09 | ODDIK             | L   | 0.819      | -            | -                | -                | -         |   -10.50 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1326 | 2024-06-08 | Case              | W   | 0.810      | 0.450        | 0.029 (0.011)    | 0.795 (0.290)    | 0 (0.000) |    12.51 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1355 | 2024-06-07 | Imperial          | L   | 0.805      | -            | -                | -                | -         |    -2.38 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1383 | 2024-06-07 | W7M               | L   | 0.804      | -            | -                | -                | -         |   -15.49 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1401 | 2024-06-06 | paiN              | L   | 0.800      | -            | -                | -                | -         |    -1.86 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1414 | 2024-06-06 | ex-Corinthians    | W   | 0.799      | -            | -                | -                | -         |     3.29 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1532 | 2024-06-04 | MIBR              | L   | 0.786      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1571 | 2024-06-03 | Intense           | L   | 0.778      | -            | -                | -                | -         |   -16.49 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1619 | 2024-06-01 | Hype              | L   | 0.765      | -            | -                | -                | -         |   -12.46 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1672 | 2024-05-30 | Hawks             | W   | 0.752      | -            | -                | -                | -         |     2.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1758 | 2024-05-27 | Dusty Roots       | W   | 0.730      | -            | -                | -                | -         |     9.74 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1938 | 2024-05-20 | Case              | L   | 0.685      | -            | -                | -                | -         |   -10.40 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1963 | 2024-05-19 | Solid             | W   | 0.678      | 0.303        | -                | 0.825 (0.169)    | -         |    10.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1989 | 2024-05-18 | ODDIK             | L   | 0.671      | -            | -                | -                | -         |    -8.87 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2105 | 2024-05-15 | Hype              | W   | 0.652      | -            | -                | -                | -         |    10.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2114 | 2024-05-15 | Case              | L   | 0.651      | -            | -                | -                | -         |   -10.81 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2155 | 2024-05-14 | Case              | L   | 0.646      | -            | -                | -                | -         |   -11.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2160 | 2024-05-14 | Case              | W   | 0.646      | 0.450        | 0.029 (0.008)    | 0.795 (0.231)    | -         |     9.13 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2172 | 2024-05-14 | 9z                | L   | 0.645      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2191 | 2024-05-13 | 9z                | L   | 0.639      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2196 | 2024-05-13 | Yawara            | W   | 0.638      | -            | -                | -                | -         |     1.99 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2216 | 2024-05-12 | KRÜ               | W   | 0.632      | -            | -                | -                | -         |    10.60 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2255 | 2024-05-11 | Case              | W   | 0.624      | 0.384        | -                | 0.795 (0.191)    | -         |    10.05 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2314 | 2024-05-08 | paiN              | L   | 0.605      | -            | -                | -                | -         |    -1.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2317 | 2024-05-08 | paiN              | L   | 0.605      | -            | -                | -                | -         |    -1.03 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2339 | 2024-05-07 | KRÜ               | L   | 0.597      | -            | -                | -                | -         |    -9.15 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2374 | 2024-05-05 | W7M               | L   | 0.584      | -            | -                | -                | -         |   -11.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2682 | 2024-04-20 | Solid             | W   | 0.486      | 0.450        | -                | 0.825 (0.180)    | -         |     7.32 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2683 | 2024-04-20 | Solid             | L   | 0.486      | -            | -                | -                | -         |    -8.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2859 | 2024-04-16 | Case              | L   | 0.460      | -            | -                | -                | -         |    -7.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2897 | 2024-04-14 | MIBR              | L   | 0.445      | -            | -                | -                | -         |    -0.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2916 | 2024-04-13 | Fluxo             | W   | 0.437      | 0.435        | 0.123 (0.023)    | -                | -         |     9.85 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2925 | 2024-04-12 | Sharks            | W   | 0.432      | -            | -                | -                | -         |     4.49 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2945 | 2024-04-11 | Vikings KR        | L   | 0.426      | -            | -                | -                | -         |    -8.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2952 | 2024-04-11 | BESTIA            | W   | 0.424      | 0.435        | 0.096 (0.018)    | -                | -         |     7.95 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2980 | 2024-04-10 | MIBR              | L   | 0.420      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2984 | 2024-04-10 | MIBR              | L   | 0.419      | -            | -                | -                | -         |    -0.71 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3034 | 2024-04-09 | BESTIA            | W   | 0.413      | 0.450        | 0.096 (0.018)    | -                | -         |     7.99 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3039 | 2024-04-09 | BESTIA            | L   | 0.412      | -            | -                | -                | -         |    -5.09 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3112 | 2024-04-07 | paiN              | L   | 0.399      | -            | -                | -                | -         |    -0.66 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3342 | 2024-03-27 | Fluxo             | W   | 0.327      | 0.450        | 0.123 (0.018)    | -                | -         |     7.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3348 | 2024-03-27 | Fluxo             | L   | 0.326      | -            | -                | -                | -         |    -3.05 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3388 | 2024-03-26 | 2GAME             | W   | 0.320      | -            | -                | -                | -         |     2.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3390 | 2024-03-26 | 2GAME             | W   | 0.319      | -            | -                | -                | -         |     2.39 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3584 | 2024-03-14 | W7M               | W   | 0.240      | -            | -                | -                | -         |     3.14 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3586 | 2024-03-14 | W7M               | W   | 0.239      | -            | -                | -                | -         |     3.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3630 | 2024-03-13 | RED Canids        | L   | 0.231      | -            | -                | -                | -         |    -1.89 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3674 | 2024-03-11 | LA RUGONETA       | L   | 0.219      | -            | -                | -                | -         |    -6.05 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3696 | 2024-03-10 | MIBR              | L   | 0.212      | -            | -                | -                | -         |    -0.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3754 | 2024-03-08 | ODDIK             | W   | 0.197      | 0.435        | 0.099 (0.008)    | -                | -         |     3.99 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     4035 | 2024-02-24 | Sharks            | L   | 0.113      | -            | -                | -                | -         |    -1.40 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4043 | 2024-02-24 | Sharks            | L   | 0.113      | -            | -                | -                | -         |    -1.41 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4066 | 2024-02-23 | Corinthians       | L   | 0.106      | -            | -                | -                | -         |    -3.01 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4067 | 2024-02-23 | Corinthians       | W   | 0.106      | -            | -                | -                | -         |     0.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4084 | 2024-02-22 | MIBR Academy      | W   | 0.099      | -            | -                | -                | -         |     0.32 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4099 | 2024-02-21 | adalYamigos       | L   | 0.093      | -            | -                | -                | -         |    -2.50 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4103 | 2024-02-21 | adalYamigos       | L   | 0.093      | -            | -                | -                | -         |    -2.51 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4110 | 2024-02-21 | Sharks            | L   | 0.091      | -            | -                | -                | -         |    -1.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4178 | 2024-02-18 | Sharks            | L   | 0.073      | -            | -                | -                | -         |    -0.95 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4180 | 2024-02-18 | Case              | W   | 0.072      | -            | -                | -                | -         |     1.26 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4206 | 2024-02-17 | Sharks            | W   | 0.065      | -            | -                | -                | -         |     1.22 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4209 | 2024-02-17 | Corinthians       | W   | 0.064      | -            | -                | -                | -         |     0.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4230 | 2024-02-16 | Flamengo          | W   | 0.059      | -            | -                | -                | -         |     0.17 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4233 | 2024-02-16 | Imperial          | L   | 0.058      | -            | -                | -                | -         |    -0.22 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4238 | 2024-02-16 | Imperial          | L   | 0.058      | -            | -                | -                | -         |    -0.21 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4264 | 2024-02-15 | 9z Academy        | W   | 0.052      | -            | -                | -                | -         |     0.16 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4291 | 2024-02-14 | Solid             | L   | 0.046      | -            | -                | -                | -         |    -0.74 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4305 | 2024-02-14 | Sharks            | L   | 0.044      | -            | -                | -                | -         |    -0.57 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4340 | 2024-02-13 | Case              | L   | 0.038      | -            | -                | -                | -         |    -0.54 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4350 | 2024-02-12 | inSanitY          | W   | 0.032      | -            | -                | -                | -         |     0.06 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,568.06)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.885 | $1,075.00      | $951.67         |
| 2024-06-09 |      0.819 | $1,500.00      | $1,228.19       |
| 2024-04-15 |      0.452 | $5,000.00      | $2,259.72       |
| 2024-04-11 |      0.426 | $592.00        | $252.09         |
| 2024-02-22 |      0.099 | $1,417.00      | $140.13         |
| 2024-02-21 |      0.091 | $1,500.00      | $136.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
