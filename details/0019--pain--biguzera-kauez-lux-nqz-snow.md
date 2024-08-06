### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1421.0<br />
<br />
Final Rank Value (1421.0) = Starting Rank Value (1400.7) + Head To Head Adjustments (20.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.671[<sup>1</sup>](#table2)
- Bounty Collected: 0.490[<sup>2</sup>](#table1)
- Opponent Network: 0.310[<sup>2</sup>](#table1)
- LAN Wins: 0.474[<sup>2</sup>](#table1)

The average of these factors is 0.486<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1400.7
- 400 + ( ( 0.486 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1400.7


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
|          103 |       74 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.85 | biguzera, kauez, lux, nqz, snow   |
|          102 |       86 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.09 | biguzera, kauez, lux, nqz, snow   |
|          101 |      108 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.207 (0.077)    | -                | -         |    11.99 | biguzera, kauez, lux, nqz, snow   |
|          100 |      112 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.82 | biguzera, kauez, lux, nqz, snow   |
|           99 |      127 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.52 | biguzera, kauez, lux, nqz, snow   |
|           98 |      165 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.49 | biguzera, kauez, lux, nqz, snow   |
|           97 |      194 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.13 | biguzera, kauez, lux, nqz, snow   |
|           96 |      215 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.26 | biguzera, kauez, lux, nqz, snow   |
|           95 |      239 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, snow   |
|           94 |      243 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.73 | biguzera, kauez, lux, nqz, snow   |
|           93 |      258 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.29 | biguzera, kauez, lux, nqz, snow   |
|           92 |      278 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.60 | biguzera, kauez, lux, nqz, snow   |
|           91 |      306 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.51 | biguzera, kauez, lux, nqz, snow   |
|           90 |      312 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.06 | biguzera, kauez, lux, nqz, snow   |
|           89 |      527 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.53 | biguzera, kauez, lux, nqz, snow   |
|           88 |      534 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.49 | biguzera, kauez, lux, nqz, snow   |
|           87 |      560 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.91 | biguzera, kauez, lux, nqz, snow   |
|           86 |      573 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.10 | biguzera, kauez, lux, nqz, snow   |
|           85 |      593 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.78 | biguzera, kauez, lux, nqz, snow   |
|           84 |      603 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.64 | biguzera, kauez, lux, nqz, snow   |
|           83 |      634 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.31 | biguzera, kauez, lux, nqz, snow   |
|           82 |      636 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.33 | biguzera, kauez, lux, nqz, snow   |
|           81 |      702 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.778 (0.350)    | -         |     2.37 | biguzera, kauez, lux, nqz, snow   |
|           80 |      705 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.778 (0.350)    | -         |     2.43 | biguzera, kauez, lux, nqz, snow   |
|           79 |      728 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.50 | biguzera, kauez, lux, nqz, snow   |
|           78 |      764 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | -         |     1.65 | biguzera, kauez, lux, nqz, snow   |
|           77 |      807 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.807 (0.363)    | -         |     1.95 | biguzera, kauez, lux, nqz, snow   |
|           76 |      811 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.807 (0.363)    | -         |     1.99 | biguzera, kauez, lux, nqz, snow   |
|           75 |     1041 | 2024-06-16 | Fluxo             | L   | 0.861      | -            | -                | -                | -         |   -21.07 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1068 | 2024-06-15 | 9z                | L   | 0.855      | -            | -                | -                | -         |    -9.94 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1083 | 2024-06-15 | ODDIK             | W   | 0.853      | 0.450        | -                | 0.805 (0.309)    | -         |     2.63 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1100 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.849      | -            | -                | -                | -         |    -5.22 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1118 | 2024-06-14 | BESTIA            | W   | 0.847      | 0.548        | -                | 0.776 (0.360)    | 1 (0.847) |     3.89 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1143 | 2024-06-13 | KRÜ               | W   | 0.841      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1217 | 2024-06-10 | BESTIA            | W   | 0.822      | 0.371        | -                | 0.776 (0.236)    | -         |     3.95 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1230 | 2024-06-10 | Imperial          | W   | 0.820      | 0.371        | 0.233 (0.071)    | -                | -         |    11.05 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1260 | 2024-06-09 | Sharks            | W   | 0.814      | -            | -                | -                | -         |     4.12 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1314 | 2024-06-08 | Hype              | W   | 0.809      | -            | -                | -                | -         |     2.08 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1344 | 2024-06-08 | Dusty Roots       | W   | 0.806      | -            | -                | -                | -         |     1.58 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1371 | 2024-06-07 | Patins da Ferrari | W   | 0.802      | -            | -                | -                | -         |     1.25 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1422 | 2024-06-06 | Galorys           | W   | 0.796      | -            | -                | -                | -         |     1.86 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1432 | 2024-06-06 | Sharks            | L   | 0.795      | -            | -                | -                | -         |   -21.30 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1498 | 2024-06-05 | Fluxo             | W   | 0.788      | 0.450        | -                | 0.701 (0.249)    | -         |     4.38 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1552 | 2024-06-04 | ODDIK             | W   | 0.782      | 0.450        | -                | 0.805 (0.283)    | -         |     2.48 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1877 | 2024-05-22 | MIBR              | L   | 0.694      | -            | -                | -                | -         |    -8.34 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1881 | 2024-05-22 | MIBR              | L   | 0.694      | -            | -                | -                | -         |    -8.84 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1987 | 2024-05-19 | AMKAL             | L   | 0.673      | -            | -                | -                | -         |   -15.50 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1998 | 2024-05-19 | OG                | W   | 0.672      | 0.769        | 0.137 (0.071)    | -                | -         |     2.87 | biguzera, kauez, lux, nqz, snow   |
|           55 |     2012 | 2024-05-18 | AMKAL             | L   | 0.667      | -            | -                | -                | -         |   -15.95 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2236 | 2024-05-12 | 9z                | W   | 0.628      | 0.435        | 0.404 (0.110)    | -                | -         |    13.58 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2269 | 2024-05-11 | BESTIA            | W   | 0.620      | -            | -                | -                | -         |     1.81 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2297 | 2024-05-10 | RED Canids        | W   | 0.613      | -            | -                | -                | -         |     3.43 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2306 | 2024-05-09 | Fluxo             | L   | 0.609      | -            | -                | -                | -         |   -16.30 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2311 | 2024-05-09 | Fluxo             | W   | 0.609      | -            | -                | -                | -         |     2.80 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2331 | 2024-05-08 | RED Canids        | W   | 0.602      | -            | -                | -                | -         |     3.23 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2333 | 2024-05-08 | RED Canids        | L   | 0.602      | -            | -                | -                | -         |   -16.04 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2335 | 2024-05-08 | Galorys           | W   | 0.601      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2338 | 2024-05-08 | Galorys           | W   | 0.601      | -            | -                | -                | -         |     1.03 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2352 | 2024-05-07 | W7M               | W   | 0.594      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2372 | 2024-05-06 | W7M               | W   | 0.588      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2373 | 2024-05-06 | W7M               | W   | 0.587      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2385 | 2024-05-05 | KRÜ               | W   | 0.581      | -            | -                | -                | -         |     1.09 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2610 | 2024-04-25 | Solid             | W   | 0.515      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2612 | 2024-04-25 | Solid             | W   | 0.515      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2631 | 2024-04-24 | ODDIK             | W   | 0.509      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2632 | 2024-04-24 | ODDIK             | L   | 0.508      | -            | -                | -                | -         |   -14.79 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2705 | 2024-04-20 | Imperial          | W   | 0.481      | 0.589        | 0.233 (0.066)    | -                | 1 (0.481) |     5.39 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2714 | 2024-04-20 | MIBR              | W   | 0.480      | 0.589        | 0.207 (0.059)    | -                | 1 (0.480) |     8.83 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2735 | 2024-04-19 | Imperial          | L   | 0.477      | -            | -                | -                | -         |    -9.75 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2736 | 2024-04-19 | MIBR              | L   | 0.476      | -            | -                | -                | -         |    -6.60 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2748 | 2024-04-19 | Imperial          | W   | 0.474      | -            | -                | -                | -         |     5.18 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2762 | 2024-04-19 | MIBR              | W   | 0.474      | 0.589        | 0.207 (0.058)    | -                | 1 (0.474) |     8.42 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2785 | 2024-04-18 | Fluxo             | W   | 0.469      | -            | -                | -                | -         |     2.13 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2789 | 2024-04-18 | MIBR              | L   | 0.468      | -            | -                | -                | -         |    -6.60 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2815 | 2024-04-18 | Monte             | W   | 0.466      | -            | -                | -                | 1 (0.466) |     1.42 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2919 | 2024-04-14 | Imperial          | L   | 0.440      | -            | -                | -                | -         |    -9.32 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2930 | 2024-04-13 | ODDIK             | W   | 0.434      | -            | -                | -                | -         |     1.00 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2963 | 2024-04-11 | MIBR              | L   | 0.422      | -            | -                | -                | -         |    -6.52 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2969 | 2024-04-11 | Sharks            | W   | 0.421      | -            | -                | -                | -         |     1.07 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2975 | 2024-04-11 | Imperial          | W   | 0.420      | -            | -                | -                | -         |     4.24 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     3010 | 2024-04-10 | RED Canids        | W   | 0.414      | -            | -                | -                | -         |     1.90 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     3054 | 2024-04-09 | Case              | W   | 0.409      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     3059 | 2024-04-09 | Case              | W   | 0.408      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3077 | 2024-04-09 | Imperial          | L   | 0.407      | -            | -                | -                | -         |    -8.70 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3099 | 2024-04-08 | Sharks            | W   | 0.401      | -            | -                | -                | -         |     0.35 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3129 | 2024-04-07 | MIBR              | L   | 0.396      | -            | -                | -                | -         |    -6.48 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3133 | 2024-04-07 | Galorys           | W   | 0.394      | -            | -                | -                | -         |     0.66 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3169 | 2024-04-05 | Sharks            | W   | 0.380      | -            | -                | -                | -         |     0.29 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3189 | 2024-04-04 | Sharks            | W   | 0.375      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3196 | 2024-04-04 | Sharks            | W   | 0.375      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3422 | 2024-03-24 | Natus Vincere     | L   | 0.301      | -            | -                | -                | -         |    -0.42 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3433 | 2024-03-23 | HEROIC            | W   | 0.294      | 1.000        | 0.224 (0.066)    | -                | 1 (0.294) |     6.47 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3448 | 2024-03-22 | The MongolZ       | W   | 0.286      | 1.000        | 1.000 (0.286)    | -                | 1 (0.286) |     8.56 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3468 | 2024-03-21 | Virtus.pro        | L   | 0.281      | -            | -                | -                | -         |    -1.44 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3476 | 2024-03-21 | Complexity        | L   | 0.279      | -            | -                | -                | -         |    -1.81 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3513 | 2024-03-19 | SAW               | W   | 0.266      | -            | -                | -                | 1 (0.266) |     1.79 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3528 | 2024-03-18 | ENCE              | W   | 0.259      | -            | -                | -                | 1 (0.259) |     4.83 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3546 | 2024-03-17 | Eternal Fire      | L   | 0.254      | -            | -                | -                | -         |    -1.24 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3556 | 2024-03-17 | Apeks             | W   | 0.253      | -            | -                | -                | 1 (0.253) |     0.47 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3886 | 2024-03-04 | ODDIK             | W   | 0.167      | -            | -                | -                | -         |     0.50 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3907 | 2024-03-03 | Imperial          | L   | 0.161      | -            | -                | -                | -         |    -3.50 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3934 | 2024-03-02 | RED Canids        | W   | 0.153      | -            | -                | -                | -         |     0.67 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3948 | 2024-03-01 | Legacy            | W   | 0.148      | -            | -                | -                | -         |     0.46 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($103,568.33)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.862 | $1,500.00      | $1,293.19       |
| 2024-06-16 |      0.861 | $10,000.00     | $8,605.56       |
| 2024-06-10 |      0.822 | $10,000.00     | $8,218.29       |
| 2024-06-09 |      0.815 | $3,000.00      | $2,443.89       |
| 2024-05-12 |      0.628 | $25,000.00     | $15,694.44      |
| 2024-04-20 |      0.481 | $100,000.00    | $48,129.63      |
| 2024-04-15 |      0.448 | $5,000.00      | $2,238.89       |
| 2024-03-31 |      0.347 | $20,000.00     | $6,944.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
