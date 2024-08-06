### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1422.4<br />
<br />
Final Rank Value (1422.4) = Starting Rank Value (1402.9) + Head To Head Adjustments (19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.671[<sup>1</sup>](#table2)
- Bounty Collected: 0.490[<sup>2</sup>](#table1)
- Opponent Network: 0.317[<sup>2</sup>](#table1)
- LAN Wins: 0.476[<sup>2</sup>](#table1)

The average of these factors is 0.489<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1402.9
- 400 + ( ( 0.489 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1402.9


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
|          103 |       57 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.84 | biguzera, kauez, lux, nqz, snow   |
|          102 |       69 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.09 | biguzera, kauez, lux, nqz, snow   |
|          101 |       91 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.208 (0.077)    | -                | -         |    11.98 | biguzera, kauez, lux, nqz, snow   |
|          100 |       95 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.81 | biguzera, kauez, lux, nqz, snow   |
|           99 |      110 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.52 | biguzera, kauez, lux, nqz, snow   |
|           98 |      148 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.49 | biguzera, kauez, lux, nqz, snow   |
|           97 |      177 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.13 | biguzera, kauez, lux, nqz, snow   |
|           96 |      198 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.25 | biguzera, kauez, lux, nqz, snow   |
|           95 |      222 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, snow   |
|           94 |      226 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.73 | biguzera, kauez, lux, nqz, snow   |
|           93 |      241 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.28 | biguzera, kauez, lux, nqz, snow   |
|           92 |      261 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.60 | biguzera, kauez, lux, nqz, snow   |
|           91 |      289 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.50 | biguzera, kauez, lux, nqz, snow   |
|           90 |      295 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.06 | biguzera, kauez, lux, nqz, snow   |
|           89 |      510 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.53 | biguzera, kauez, lux, nqz, snow   |
|           88 |      517 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.50 | biguzera, kauez, lux, nqz, snow   |
|           87 |      543 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.90 | biguzera, kauez, lux, nqz, snow   |
|           86 |      556 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.10 | biguzera, kauez, lux, nqz, snow   |
|           85 |      576 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.79 | biguzera, kauez, lux, nqz, snow   |
|           84 |      586 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.63 | biguzera, kauez, lux, nqz, snow   |
|           83 |      617 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.30 | biguzera, kauez, lux, nqz, snow   |
|           82 |      619 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.32 | biguzera, kauez, lux, nqz, snow   |
|           81 |      685 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.795 (0.358)    | -         |     2.37 | biguzera, kauez, lux, nqz, snow   |
|           80 |      688 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.795 (0.358)    | -         |     2.42 | biguzera, kauez, lux, nqz, snow   |
|           79 |      711 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.50 | biguzera, kauez, lux, nqz, snow   |
|           78 |      747 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.542 (0.244)    | -         |     1.64 | biguzera, kauez, lux, nqz, snow   |
|           77 |      790 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.825 (0.371)    | -         |     1.95 | biguzera, kauez, lux, nqz, snow   |
|           76 |      794 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.825 (0.371)    | -         |     1.99 | biguzera, kauez, lux, nqz, snow   |
|           75 |     1024 | 2024-06-16 | Fluxo             | L   | 0.862      | -            | -                | -                | -         |   -21.10 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1051 | 2024-06-15 | 9z                | L   | 0.856      | -            | -                | -                | -         |    -9.99 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1066 | 2024-06-15 | ODDIK             | W   | 0.855      | 0.450        | -                | 0.823 (0.316)    | -         |     2.63 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1083 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.851      | -            | -                | -                | -         |    -5.26 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1101 | 2024-06-14 | BESTIA            | W   | 0.849      | 0.548        | -                | 0.793 (0.369)    | 1 (0.849) |     3.89 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1126 | 2024-06-13 | KRÜ               | W   | 0.843      | -            | -                | -                | -         |     1.76 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1200 | 2024-06-10 | BESTIA            | W   | 0.823      | 0.371        | -                | 0.793 (0.242)    | -         |     3.96 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1213 | 2024-06-10 | Imperial          | W   | 0.821      | 0.371        | 0.233 (0.071)    | -                | -         |    11.07 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1243 | 2024-06-09 | Sharks            | W   | 0.816      | -            | -                | -                | -         |     4.14 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1297 | 2024-06-08 | Hype              | W   | 0.810      | -            | -                | -                | -         |     2.08 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1327 | 2024-06-08 | Dusty Roots       | W   | 0.808      | -            | -                | -                | -         |     1.57 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1354 | 2024-06-07 | Patins da Ferrari | W   | 0.804      | -            | -                | -                | -         |     1.25 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1405 | 2024-06-06 | Galorys           | W   | 0.797      | -            | -                | -                | -         |     1.86 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1415 | 2024-06-06 | Sharks            | L   | 0.797      | -            | -                | -                | -         |   -21.34 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1481 | 2024-06-05 | Fluxo             | W   | 0.790      | 0.450        | -                | 0.716 (0.255)    | -         |     4.39 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1535 | 2024-06-04 | ODDIK             | W   | 0.783      | 0.450        | -                | 0.823 (0.290)    | -         |     2.49 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1860 | 2024-05-22 | MIBR              | L   | 0.696      | -            | -                | -                | -         |    -8.37 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1864 | 2024-05-22 | MIBR              | L   | 0.696      | -            | -                | -                | -         |    -8.87 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1970 | 2024-05-19 | AMKAL             | L   | 0.675      | -            | -                | -                | -         |   -15.61 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1981 | 2024-05-19 | OG                | W   | 0.673      | 0.769        | 0.137 (0.071)    | -                | -         |     2.86 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1995 | 2024-05-18 | AMKAL             | L   | 0.669      | -            | -                | -                | -         |   -16.07 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2219 | 2024-05-12 | 9z                | W   | 0.629      | 0.435        | 0.404 (0.110)    | -                | -         |    13.60 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2252 | 2024-05-11 | BESTIA            | W   | 0.622      | -            | -                | -                | -         |     1.81 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2280 | 2024-05-10 | RED Canids        | W   | 0.614      | -            | -                | -                | -         |     3.43 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2289 | 2024-05-09 | Fluxo             | L   | 0.611      | -            | -                | -                | -         |   -16.35 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2294 | 2024-05-09 | Fluxo             | W   | 0.611      | -            | -                | -                | -         |     2.81 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2314 | 2024-05-08 | RED Canids        | W   | 0.604      | -            | -                | -                | -         |     3.23 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2316 | 2024-05-08 | RED Canids        | L   | 0.604      | -            | -                | -                | -         |   -16.08 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2318 | 2024-05-08 | Galorys           | W   | 0.603      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2321 | 2024-05-08 | Galorys           | W   | 0.602      | -            | -                | -                | -         |     1.03 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2335 | 2024-05-07 | W7M               | W   | 0.596      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2355 | 2024-05-06 | W7M               | W   | 0.589      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2356 | 2024-05-06 | W7M               | W   | 0.589      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2368 | 2024-05-05 | KRÜ               | W   | 0.583      | -            | -                | -                | -         |     1.10 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2593 | 2024-04-25 | Solid             | W   | 0.517      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2595 | 2024-04-25 | Solid             | W   | 0.517      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2614 | 2024-04-24 | ODDIK             | W   | 0.510      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2615 | 2024-04-24 | ODDIK             | L   | 0.510      | -            | -                | -                | -         |   -14.84 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2688 | 2024-04-20 | Imperial          | W   | 0.483      | 0.589        | 0.233 (0.066)    | -                | 1 (0.483) |     5.39 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2697 | 2024-04-20 | MIBR              | W   | 0.482      | 0.589        | 0.208 (0.059)    | -                | 1 (0.482) |     8.86 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2718 | 2024-04-19 | Imperial          | L   | 0.478      | -            | -                | -                | -         |    -9.79 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2719 | 2024-04-19 | MIBR              | L   | 0.478      | -            | -                | -                | -         |    -6.62 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2731 | 2024-04-19 | Imperial          | W   | 0.476      | -            | -                | -                | -         |     5.18 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2745 | 2024-04-19 | MIBR              | W   | 0.475      | 0.589        | 0.208 (0.058)    | -                | 1 (0.475) |     8.45 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2768 | 2024-04-18 | Fluxo             | W   | 0.471      | -            | -                | -                | -         |     2.14 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2772 | 2024-04-18 | MIBR              | L   | 0.470      | -            | -                | -                | -         |    -6.63 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2798 | 2024-04-18 | Monte             | W   | 0.468      | -            | -                | -                | 1 (0.468) |     1.40 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2902 | 2024-04-14 | Imperial          | L   | 0.442      | -            | -                | -                | -         |    -9.37 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2913 | 2024-04-13 | ODDIK             | W   | 0.436      | -            | -                | -                | -         |     1.00 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2946 | 2024-04-11 | MIBR              | L   | 0.424      | -            | -                | -                | -         |    -6.55 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2952 | 2024-04-11 | Sharks            | W   | 0.423      | -            | -                | -                | -         |     1.07 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2958 | 2024-04-11 | Imperial          | W   | 0.422      | -            | -                | -                | -         |     4.25 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2993 | 2024-04-10 | RED Canids        | W   | 0.416      | -            | -                | -                | -         |     1.90 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     3037 | 2024-04-09 | Case              | W   | 0.410      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     3042 | 2024-04-09 | Case              | W   | 0.410      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3060 | 2024-04-09 | Imperial          | L   | 0.408      | -            | -                | -                | -         |    -8.74 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3082 | 2024-04-08 | Sharks            | W   | 0.402      | -            | -                | -                | -         |     0.34 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3112 | 2024-04-07 | MIBR              | L   | 0.397      | -            | -                | -                | -         |    -6.52 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3116 | 2024-04-07 | Galorys           | W   | 0.396      | -            | -                | -                | -         |     0.66 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3152 | 2024-04-05 | Sharks            | W   | 0.382      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3172 | 2024-04-04 | Sharks            | W   | 0.377      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3179 | 2024-04-04 | Sharks            | W   | 0.377      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3405 | 2024-03-24 | Natus Vincere     | L   | 0.302      | -            | -                | -                | -         |    -0.43 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3416 | 2024-03-23 | HEROIC            | W   | 0.296      | 1.000        | 0.225 (0.066)    | -                | 1 (0.296) |     6.49 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3431 | 2024-03-22 | The MongolZ       | W   | 0.288      | 1.000        | 1.000 (0.288)    | -                | 1 (0.288) |     8.60 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3451 | 2024-03-21 | Virtus.pro        | L   | 0.282      | -            | -                | -                | -         |    -1.45 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3459 | 2024-03-21 | Complexity        | L   | 0.281      | -            | -                | -                | -         |    -1.84 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3496 | 2024-03-19 | SAW               | W   | 0.268      | -            | -                | -                | 1 (0.268) |     1.79 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3511 | 2024-03-18 | ENCE              | W   | 0.261      | -            | -                | -                | 1 (0.261) |     4.83 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3529 | 2024-03-17 | Eternal Fire      | L   | 0.256      | -            | -                | -                | -         |    -1.27 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3539 | 2024-03-17 | Apeks             | W   | 0.254      | -            | -                | -                | 1 (0.254) |     0.46 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3869 | 2024-03-04 | ODDIK             | W   | 0.168      | -            | -                | -                | -         |     0.51 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3890 | 2024-03-03 | Imperial          | L   | 0.162      | -            | -                | -                | -         |    -3.54 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3917 | 2024-03-02 | RED Canids        | W   | 0.155      | -            | -                | -                | -         |     0.67 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3931 | 2024-03-01 | Legacy            | W   | 0.150      | -            | -                | -                | -         |     0.47 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($103,859.17)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.864 | $1,500.00      | $1,295.69       |
| 2024-06-16 |      0.862 | $10,000.00     | $8,622.22       |
| 2024-06-10 |      0.823 | $10,000.00     | $8,234.95       |
| 2024-06-09 |      0.816 | $3,000.00      | $2,448.89       |
| 2024-05-12 |      0.629 | $25,000.00     | $15,736.11      |
| 2024-04-20 |      0.483 | $100,000.00    | $48,296.30      |
| 2024-04-15 |      0.449 | $5,000.00      | $2,247.22       |
| 2024-03-31 |      0.349 | $20,000.00     | $6,977.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
