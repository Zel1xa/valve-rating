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
Final Rank Value (1425.6) = Starting Rank Value (1410.0) + Head To Head Adjustments (15.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.673[<sup>1</sup>](#table2)
- Bounty Collected: 0.494[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.485[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1410.0
- 400 + ( ( 0.494 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1410.0


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
|          103 |       24 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.83 | biguzera, kauez, lux, nqz, snow   |
|          102 |       36 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.06 | biguzera, kauez, lux, nqz, snow   |
|          101 |       58 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.209 (0.077)    | -                | -         |    11.97 | biguzera, kauez, lux, nqz, snow   |
|          100 |       62 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.80 | biguzera, kauez, lux, nqz, snow   |
|           99 |       77 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.50 | biguzera, kauez, lux, nqz, snow   |
|           98 |      115 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.46 | biguzera, kauez, lux, nqz, snow   |
|           97 |      144 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.09 | biguzera, kauez, lux, nqz, snow   |
|           96 |      165 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.23 | biguzera, kauez, lux, nqz, snow   |
|           95 |      189 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           94 |      193 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           93 |      208 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.25 | biguzera, kauez, lux, nqz, snow   |
|           92 |      228 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.61 | biguzera, kauez, lux, nqz, snow   |
|           91 |      256 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.52 | biguzera, kauez, lux, nqz, snow   |
|           90 |      262 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.04 | biguzera, kauez, lux, nqz, snow   |
|           89 |      477 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.55 | biguzera, kauez, lux, nqz, snow   |
|           88 |      484 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.47 | biguzera, kauez, lux, nqz, snow   |
|           87 |      510 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.94 | biguzera, kauez, lux, nqz, snow   |
|           86 |      523 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.07 | biguzera, kauez, lux, nqz, snow   |
|           85 |      543 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.77 | biguzera, kauez, lux, nqz, snow   |
|           84 |      553 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.61 | biguzera, kauez, lux, nqz, snow   |
|           83 |      584 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.28 | biguzera, kauez, lux, nqz, snow   |
|           82 |      586 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.29 | biguzera, kauez, lux, nqz, snow   |
|           81 |      652 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.805 (0.362)    | -         |     2.33 | biguzera, kauez, lux, nqz, snow   |
|           80 |      655 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.805 (0.362)    | -         |     2.39 | biguzera, kauez, lux, nqz, snow   |
|           79 |      678 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.47 | biguzera, kauez, lux, nqz, snow   |
|           78 |      714 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.61 | biguzera, kauez, lux, nqz, snow   |
|           77 |      757 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.836 (0.376)    | -         |     1.92 | biguzera, kauez, lux, nqz, snow   |
|           76 |      761 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.836 (0.376)    | -         |     1.96 | biguzera, kauez, lux, nqz, snow   |
|           75 |      991 | 2024-06-16 | Fluxo             | L   | 0.874      | -            | -                | -                | -         |   -21.41 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1018 | 2024-06-15 | 9z                | L   | 0.868      | -            | -                | -                | -         |   -10.20 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1033 | 2024-06-15 | ODDIK             | W   | 0.867      | 0.450        | -                | 0.831 (0.324)    | -         |     2.62 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1050 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.863      | -            | -                | -                | -         |    -5.45 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1068 | 2024-06-14 | BESTIA            | W   | 0.860      | 0.548        | -                | 0.801 (0.378)    | 1 (0.860) |     3.90 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1093 | 2024-06-13 | KRÜ               | W   | 0.855      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1167 | 2024-06-10 | BESTIA            | W   | 0.835      | 0.371        | -                | 0.801 (0.248)    | -         |     3.97 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1180 | 2024-06-10 | Imperial          | W   | 0.833      | 0.371        | 0.236 (0.073)    | -                | -         |    11.27 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1210 | 2024-06-09 | Sharks            | W   | 0.827      | -            | -                | -                | -         |     4.17 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1264 | 2024-06-08 | Hype              | W   | 0.822      | -            | -                | -                | -         |     2.07 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1294 | 2024-06-08 | Dusty Roots       | W   | 0.820      | -            | -                | -                | -         |     1.56 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1321 | 2024-06-07 | Patins da Ferrari | W   | 0.815      | -            | -                | -                | -         |     1.24 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1372 | 2024-06-06 | Galorys           | W   | 0.809      | -            | -                | -                | -         |     1.85 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1382 | 2024-06-06 | Sharks            | L   | 0.809      | -            | -                | -                | -         |   -21.68 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1448 | 2024-06-05 | Fluxo             | W   | 0.802      | 0.450        | -                | 0.724 (0.261)    | -         |     4.42 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1502 | 2024-06-04 | ODDIK             | W   | 0.795      | 0.450        | -                | 0.831 (0.298)    | -         |     2.48 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1827 | 2024-05-22 | MIBR              | L   | 0.708      | -            | -                | -                | -         |    -8.51 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1831 | 2024-05-22 | MIBR              | L   | 0.707      | -            | -                | -                | -         |    -9.03 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1937 | 2024-05-19 | AMKAL             | L   | 0.687      | -            | -                | -                | -         |   -15.98 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1948 | 2024-05-19 | OG                | W   | 0.685      | 0.769        | 0.139 (0.073)    | -                | -         |     2.89 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1962 | 2024-05-18 | AMKAL             | L   | 0.681      | -            | -                | -                | -         |   -16.45 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2186 | 2024-05-12 | 9z                | W   | 0.641      | 0.435        | 0.405 (0.113)    | -                | -         |    13.78 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2219 | 2024-05-11 | BESTIA            | W   | 0.634      | -            | -                | -                | -         |     1.80 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2247 | 2024-05-10 | RED Canids        | W   | 0.626      | -            | -                | -                | -         |     3.46 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2256 | 2024-05-09 | Fluxo             | L   | 0.623      | -            | -                | -                | -         |   -16.70 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2261 | 2024-05-09 | Fluxo             | W   | 0.622      | -            | -                | -                | -         |     2.82 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2281 | 2024-05-08 | RED Canids        | W   | 0.616      | -            | -                | -                | -         |     3.25 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2283 | 2024-05-08 | RED Canids        | L   | 0.615      | -            | -                | -                | -         |   -16.44 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2285 | 2024-05-08 | Galorys           | W   | 0.614      | -            | -                | -                | -         |     1.01 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2288 | 2024-05-08 | Galorys           | W   | 0.614      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2302 | 2024-05-07 | W7M               | W   | 0.608      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2322 | 2024-05-06 | W7M               | W   | 0.601      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2323 | 2024-05-06 | W7M               | W   | 0.601      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2335 | 2024-05-05 | KRÜ               | W   | 0.595      | -            | -                | -                | -         |     1.09 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2560 | 2024-04-25 | Solid             | W   | 0.529      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2562 | 2024-04-25 | Solid             | W   | 0.529      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2581 | 2024-04-24 | ODDIK             | W   | 0.522      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2582 | 2024-04-24 | ODDIK             | L   | 0.522      | -            | -                | -                | -         |   -15.22 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2655 | 2024-04-20 | Imperial          | W   | 0.495      | 0.589        | 0.236 (0.069)    | -                | 1 (0.495) |     5.55 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2664 | 2024-04-20 | MIBR              | W   | 0.494      | 0.589        | 0.209 (0.061)    | -                | 1 (0.494) |     9.07 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2685 | 2024-04-19 | Imperial          | L   | 0.490      | -            | -                | -                | -         |   -10.01 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2686 | 2024-04-19 | MIBR              | L   | 0.490      | -            | -                | -                | -         |    -6.80 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2698 | 2024-04-19 | Imperial          | W   | 0.488      | -            | -                | -                | -         |     5.33 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2712 | 2024-04-19 | MIBR              | W   | 0.487      | 0.589        | 0.209 (0.060)    | -                | 1 (0.487) |     8.64 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2735 | 2024-04-18 | Fluxo             | W   | 0.483      | -            | -                | -                | -         |     2.16 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2739 | 2024-04-18 | MIBR              | L   | 0.482      | -            | -                | -                | -         |    -6.81 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2765 | 2024-04-18 | Monte             | W   | 0.480      | -            | -                | -                | 1 (0.480) |     1.42 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2869 | 2024-04-14 | Imperial          | L   | 0.454      | -            | -                | -                | -         |    -9.60 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2880 | 2024-04-13 | ODDIK             | W   | 0.448      | -            | -                | -                | -         |     0.99 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2913 | 2024-04-11 | MIBR              | L   | 0.436      | -            | -                | -                | -         |    -6.77 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2919 | 2024-04-11 | Sharks            | W   | 0.435      | -            | -                | -                | -         |     1.08 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2925 | 2024-04-11 | Imperial          | W   | 0.434      | -            | -                | -                | -         |     4.38 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2960 | 2024-04-10 | RED Canids        | W   | 0.428      | -            | -                | -                | -         |     1.92 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     3004 | 2024-04-09 | Case              | W   | 0.422      | -            | -                | -                | -         |     0.74 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     3009 | 2024-04-09 | Case              | W   | 0.422      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3027 | 2024-04-09 | Imperial          | L   | 0.420      | -            | -                | -                | -         |    -8.98 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3049 | 2024-04-08 | Sharks            | W   | 0.414      | -            | -                | -                | -         |     0.34 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3079 | 2024-04-07 | MIBR              | L   | 0.409      | -            | -                | -                | -         |    -6.76 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3083 | 2024-04-07 | Galorys           | W   | 0.408      | -            | -                | -                | -         |     0.66 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3119 | 2024-04-05 | Sharks            | W   | 0.394      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3139 | 2024-04-04 | Sharks            | W   | 0.389      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3146 | 2024-04-04 | Sharks            | W   | 0.389      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3372 | 2024-03-24 | Natus Vincere     | L   | 0.314      | -            | -                | -                | -         |    -0.46 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3383 | 2024-03-23 | HEROIC            | W   | 0.308      | 1.000        | 0.229 (0.070)    | -                | 1 (0.308) |     6.72 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3398 | 2024-03-22 | The MongolZ       | W   | 0.300      | 1.000        | 1.000 (0.300)    | -                | 1 (0.300) |     8.93 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3418 | 2024-03-21 | Virtus.pro        | L   | 0.294      | -            | -                | -                | -         |    -1.53 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3426 | 2024-03-21 | Complexity        | L   | 0.293      | -            | -                | -                | -         |    -1.95 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3463 | 2024-03-19 | SAW               | W   | 0.280      | -            | -                | -                | 1 (0.280) |     1.86 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3478 | 2024-03-18 | ENCE              | W   | 0.272      | -            | -                | -                | 1 (0.272) |     4.86 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3496 | 2024-03-17 | Eternal Fire      | L   | 0.267      | -            | -                | -                | -         |    -1.35 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3506 | 2024-03-17 | Apeks             | W   | 0.266      | -            | -                | -                | 1 (0.266) |     0.48 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3836 | 2024-03-04 | ODDIK             | W   | 0.180      | -            | -                | -                | -         |     0.53 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3857 | 2024-03-03 | Imperial          | L   | 0.174      | -            | -                | -                | -         |    -3.79 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3884 | 2024-03-02 | RED Canids        | W   | 0.167      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3898 | 2024-03-01 | Legacy            | W   | 0.162      | -            | -                | -                | -         |     0.49 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($105,927.31)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.33) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.876 | $1,500.00      | $1,313.47       |
| 2024-06-16 |      0.874 | $10,000.00     | $8,740.74       |
| 2024-06-10 |      0.835 | $10,000.00     | $8,353.47       |
| 2024-06-09 |      0.828 | $3,000.00      | $2,484.44       |
| 2024-05-12 |      0.641 | $25,000.00     | $16,032.41      |
| 2024-04-20 |      0.495 | $100,000.00    | $49,481.48      |
| 2024-04-15 |      0.461 | $5,000.00      | $2,306.48       |
| 2024-03-31 |      0.361 | $20,000.00     | $7,214.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
