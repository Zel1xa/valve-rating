### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1425.6<br />
<br />
Final Rank Value (1425.6) = Starting Rank Value (1409.8) + Head To Head Adjustments (15.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.673[<sup>1</sup>](#table2)
- Bounty Collected: 0.493[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.485[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1409.8
- 400 + ( ( 0.494 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1409.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          103 |       25 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.83 | biguzera, kauez, lux, nqz, snow   |
|          102 |       37 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.06 | biguzera, kauez, lux, nqz, snow   |
|          101 |       59 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.209 (0.077)    | -                | -         |    11.97 | biguzera, kauez, lux, nqz, snow   |
|          100 |       63 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.80 | biguzera, kauez, lux, nqz, snow   |
|           99 |       78 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.50 | biguzera, kauez, lux, nqz, snow   |
|           98 |      116 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.46 | biguzera, kauez, lux, nqz, snow   |
|           97 |      145 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.09 | biguzera, kauez, lux, nqz, snow   |
|           96 |      166 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.23 | biguzera, kauez, lux, nqz, snow   |
|           95 |      190 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           94 |      194 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           93 |      209 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.25 | biguzera, kauez, lux, nqz, snow   |
|           92 |      229 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.61 | biguzera, kauez, lux, nqz, snow   |
|           91 |      257 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.52 | biguzera, kauez, lux, nqz, snow   |
|           90 |      263 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.04 | biguzera, kauez, lux, nqz, snow   |
|           89 |      478 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.55 | biguzera, kauez, lux, nqz, snow   |
|           88 |      485 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.47 | biguzera, kauez, lux, nqz, snow   |
|           87 |      511 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.94 | biguzera, kauez, lux, nqz, snow   |
|           86 |      524 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.07 | biguzera, kauez, lux, nqz, snow   |
|           85 |      544 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.77 | biguzera, kauez, lux, nqz, snow   |
|           84 |      554 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.61 | biguzera, kauez, lux, nqz, snow   |
|           83 |      585 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.28 | biguzera, kauez, lux, nqz, snow   |
|           82 |      587 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.29 | biguzera, kauez, lux, nqz, snow   |
|           81 |      653 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.805 (0.362)    | -         |     2.33 | biguzera, kauez, lux, nqz, snow   |
|           80 |      656 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.805 (0.362)    | -         |     2.39 | biguzera, kauez, lux, nqz, snow   |
|           79 |      679 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.47 | biguzera, kauez, lux, nqz, snow   |
|           78 |      715 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.61 | biguzera, kauez, lux, nqz, snow   |
|           77 |      758 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.836 (0.376)    | -         |     1.92 | biguzera, kauez, lux, nqz, snow   |
|           76 |      762 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.836 (0.376)    | -         |     1.96 | biguzera, kauez, lux, nqz, snow   |
|           75 |      992 | 2024-06-16 | Fluxo             | L   | 0.874      | -            | -                | -                | -         |   -21.40 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1019 | 2024-06-15 | 9z                | L   | 0.868      | -            | -                | -                | -         |   -10.20 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1034 | 2024-06-15 | ODDIK             | W   | 0.866      | 0.450        | -                | 0.832 (0.324)    | -         |     2.62 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1051 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.862      | -            | -                | -                | -         |    -5.45 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1069 | 2024-06-14 | BESTIA            | W   | 0.860      | 0.548        | -                | 0.801 (0.378)    | 1 (0.860) |     3.90 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1094 | 2024-06-13 | KRÜ               | W   | 0.854      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1168 | 2024-06-10 | BESTIA            | W   | 0.835      | 0.371        | -                | 0.801 (0.248)    | -         |     3.97 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1181 | 2024-06-10 | Imperial          | W   | 0.833      | 0.371        | 0.236 (0.073)    | -                | -         |    11.27 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1211 | 2024-06-09 | Sharks            | W   | 0.827      | -            | -                | -                | -         |     4.17 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1265 | 2024-06-08 | Hype              | W   | 0.822      | -            | -                | -                | -         |     2.07 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1295 | 2024-06-08 | Dusty Roots       | W   | 0.819      | -            | -                | -                | -         |     1.56 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1322 | 2024-06-07 | Patins da Ferrari | W   | 0.815      | -            | -                | -                | -         |     1.24 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1373 | 2024-06-06 | Galorys           | W   | 0.809      | -            | -                | -                | -         |     1.85 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1383 | 2024-06-06 | Sharks            | L   | 0.808      | -            | -                | -                | -         |   -21.67 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1449 | 2024-06-05 | Fluxo             | W   | 0.802      | 0.450        | -                | 0.724 (0.261)    | -         |     4.42 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1503 | 2024-06-04 | ODDIK             | W   | 0.795      | 0.450        | -                | 0.832 (0.298)    | -         |     2.48 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1828 | 2024-05-22 | MIBR              | L   | 0.707      | -            | -                | -                | -         |    -8.51 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1832 | 2024-05-22 | MIBR              | L   | 0.707      | -            | -                | -                | -         |    -9.03 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1938 | 2024-05-19 | AMKAL             | L   | 0.686      | -            | -                | -                | -         |   -15.96 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1949 | 2024-05-19 | OG                | W   | 0.685      | 0.769        | 0.139 (0.073)    | -                | -         |     2.89 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1963 | 2024-05-18 | AMKAL             | L   | 0.680      | -            | -                | -                | -         |   -16.43 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2187 | 2024-05-12 | 9z                | W   | 0.641      | 0.435        | 0.405 (0.113)    | -                | -         |    13.77 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2220 | 2024-05-11 | BESTIA            | W   | 0.633      | -            | -                | -                | -         |     1.80 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2248 | 2024-05-10 | RED Canids        | W   | 0.626      | -            | -                | -                | -         |     3.46 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2257 | 2024-05-09 | Fluxo             | L   | 0.622      | -            | -                | -                | -         |   -16.70 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2262 | 2024-05-09 | Fluxo             | W   | 0.622      | -            | -                | -                | -         |     2.82 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2282 | 2024-05-08 | RED Canids        | W   | 0.615      | -            | -                | -                | -         |     3.25 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2284 | 2024-05-08 | RED Canids        | L   | 0.615      | -            | -                | -                | -         |   -16.43 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2286 | 2024-05-08 | Galorys           | W   | 0.614      | -            | -                | -                | -         |     1.01 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2289 | 2024-05-08 | Galorys           | W   | 0.614      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2303 | 2024-05-07 | W7M               | W   | 0.608      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2323 | 2024-05-06 | W7M               | W   | 0.601      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2324 | 2024-05-06 | W7M               | W   | 0.600      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2336 | 2024-05-05 | KRÜ               | W   | 0.594      | -            | -                | -                | -         |     1.09 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2561 | 2024-04-25 | Solid             | W   | 0.528      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2563 | 2024-04-25 | Solid             | W   | 0.528      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2582 | 2024-04-24 | ODDIK             | W   | 0.522      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2583 | 2024-04-24 | ODDIK             | L   | 0.522      | -            | -                | -                | -         |   -15.21 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2656 | 2024-04-20 | Imperial          | W   | 0.495      | 0.589        | 0.236 (0.069)    | -                | 1 (0.495) |     5.54 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2665 | 2024-04-20 | MIBR              | W   | 0.494      | 0.589        | 0.209 (0.061)    | -                | 1 (0.494) |     9.06 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2686 | 2024-04-19 | Imperial          | L   | 0.490      | -            | -                | -                | -         |   -10.01 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2687 | 2024-04-19 | MIBR              | L   | 0.489      | -            | -                | -                | -         |    -6.80 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2699 | 2024-04-19 | Imperial          | W   | 0.487      | -            | -                | -                | -         |     5.33 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2713 | 2024-04-19 | MIBR              | W   | 0.487      | 0.589        | 0.209 (0.060)    | -                | 1 (0.487) |     8.63 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2736 | 2024-04-18 | Fluxo             | W   | 0.483      | -            | -                | -                | -         |     2.16 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2740 | 2024-04-18 | MIBR              | L   | 0.482      | -            | -                | -                | -         |    -6.81 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2766 | 2024-04-18 | Monte             | W   | 0.480      | -            | -                | -                | 1 (0.480) |     1.42 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2870 | 2024-04-14 | Imperial          | L   | 0.453      | -            | -                | -                | -         |    -9.59 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2881 | 2024-04-13 | ODDIK             | W   | 0.448      | -            | -                | -                | -         |     0.99 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2914 | 2024-04-11 | MIBR              | L   | 0.435      | -            | -                | -                | -         |    -6.77 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2920 | 2024-04-11 | Sharks            | W   | 0.434      | -            | -                | -                | -         |     1.08 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2926 | 2024-04-11 | Imperial          | W   | 0.433      | -            | -                | -                | -         |     4.38 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2961 | 2024-04-10 | RED Canids        | W   | 0.427      | -            | -                | -                | -         |     1.92 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     3005 | 2024-04-09 | Case              | W   | 0.422      | -            | -                | -                | -         |     0.74 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     3010 | 2024-04-09 | Case              | W   | 0.422      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3028 | 2024-04-09 | Imperial          | L   | 0.420      | -            | -                | -                | -         |    -8.97 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3050 | 2024-04-08 | Sharks            | W   | 0.414      | -            | -                | -                | -         |     0.34 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3080 | 2024-04-07 | MIBR              | L   | 0.409      | -            | -                | -                | -         |    -6.75 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3084 | 2024-04-07 | Galorys           | W   | 0.408      | -            | -                | -                | -         |     0.66 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3120 | 2024-04-05 | Sharks            | W   | 0.393      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3140 | 2024-04-04 | Sharks            | W   | 0.389      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3147 | 2024-04-04 | Sharks            | W   | 0.388      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3373 | 2024-03-24 | Natus Vincere     | L   | 0.314      | -            | -                | -                | -         |    -0.46 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3384 | 2024-03-23 | HEROIC            | W   | 0.307      | 1.000        | 0.229 (0.070)    | -                | 1 (0.307) |     6.71 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3399 | 2024-03-22 | The MongolZ       | W   | 0.299      | 1.000        | 1.000 (0.299)    | -                | 1 (0.299) |     8.93 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3419 | 2024-03-21 | Virtus.pro        | L   | 0.294      | -            | -                | -                | -         |    -1.53 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3427 | 2024-03-21 | Complexity        | L   | 0.293      | -            | -                | -                | -         |    -1.95 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3464 | 2024-03-19 | SAW               | W   | 0.280      | -            | -                | -                | 1 (0.280) |     1.86 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3479 | 2024-03-18 | ENCE              | W   | 0.272      | -            | -                | -                | 1 (0.272) |     4.85 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3497 | 2024-03-17 | Eternal Fire      | L   | 0.267      | -            | -                | -                | -         |    -1.35 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3507 | 2024-03-17 | Apeks             | W   | 0.266      | -            | -                | -                | 1 (0.266) |     0.48 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3837 | 2024-03-04 | ODDIK             | W   | 0.180      | -            | -                | -                | -         |     0.53 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3858 | 2024-03-03 | Imperial          | L   | 0.174      | -            | -                | -                | -         |    -3.79 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3885 | 2024-03-02 | RED Canids        | W   | 0.167      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3899 | 2024-03-01 | Legacy            | W   | 0.161      | -            | -                | -                | -         |     0.49 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($105,874.80)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.33) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.875 | $1,500.00      | $1,313.02       |
| 2024-06-16 |      0.874 | $10,000.00     | $8,737.73       |
| 2024-06-10 |      0.835 | $10,000.00     | $8,350.46       |
| 2024-06-09 |      0.828 | $3,000.00      | $2,483.54       |
| 2024-05-12 |      0.641 | $25,000.00     | $16,024.88      |
| 2024-04-20 |      0.495 | $100,000.00    | $49,451.39      |
| 2024-04-15 |      0.461 | $5,000.00      | $2,304.98       |
| 2024-03-31 |      0.360 | $20,000.00     | $7,208.80       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
