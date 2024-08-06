### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1421.2<br />
<br />
Final Rank Value (1421.2) = Starting Rank Value (1401.2) + Head To Head Adjustments (20.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.671[<sup>1</sup>](#table2)
- Bounty Collected: 0.490[<sup>2</sup>](#table1)
- Opponent Network: 0.310[<sup>2</sup>](#table1)
- LAN Wins: 0.475[<sup>2</sup>](#table1)

The average of these factors is 0.487<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1401.2
- 400 + ( ( 0.487 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1401.2


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
|          103 |       63 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.85 | biguzera, kauez, lux, nqz, snow   |
|          102 |       75 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.09 | biguzera, kauez, lux, nqz, snow   |
|          101 |       97 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.208 (0.077)    | -                | -         |    11.99 | biguzera, kauez, lux, nqz, snow   |
|          100 |      101 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.82 | biguzera, kauez, lux, nqz, snow   |
|           99 |      116 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.52 | biguzera, kauez, lux, nqz, snow   |
|           98 |      154 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.49 | biguzera, kauez, lux, nqz, snow   |
|           97 |      183 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.13 | biguzera, kauez, lux, nqz, snow   |
|           96 |      204 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.25 | biguzera, kauez, lux, nqz, snow   |
|           95 |      228 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, snow   |
|           94 |      232 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.73 | biguzera, kauez, lux, nqz, snow   |
|           93 |      247 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.28 | biguzera, kauez, lux, nqz, snow   |
|           92 |      267 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.60 | biguzera, kauez, lux, nqz, snow   |
|           91 |      295 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.51 | biguzera, kauez, lux, nqz, snow   |
|           90 |      301 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.06 | biguzera, kauez, lux, nqz, snow   |
|           89 |      516 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.53 | biguzera, kauez, lux, nqz, snow   |
|           88 |      523 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.49 | biguzera, kauez, lux, nqz, snow   |
|           87 |      549 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.91 | biguzera, kauez, lux, nqz, snow   |
|           86 |      562 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.10 | biguzera, kauez, lux, nqz, snow   |
|           85 |      582 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.78 | biguzera, kauez, lux, nqz, snow   |
|           84 |      592 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.63 | biguzera, kauez, lux, nqz, snow   |
|           83 |      623 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.30 | biguzera, kauez, lux, nqz, snow   |
|           82 |      625 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.32 | biguzera, kauez, lux, nqz, snow   |
|           81 |      691 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.778 (0.350)    | -         |     2.37 | biguzera, kauez, lux, nqz, snow   |
|           80 |      694 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.778 (0.350)    | -         |     2.43 | biguzera, kauez, lux, nqz, snow   |
|           79 |      717 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.50 | biguzera, kauez, lux, nqz, snow   |
|           78 |      753 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | -         |     1.65 | biguzera, kauez, lux, nqz, snow   |
|           77 |      796 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.807 (0.363)    | -         |     1.95 | biguzera, kauez, lux, nqz, snow   |
|           76 |      800 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.807 (0.363)    | -         |     1.99 | biguzera, kauez, lux, nqz, snow   |
|           75 |     1030 | 2024-06-16 | Fluxo             | L   | 0.862      | -            | -                | -                | -         |   -21.09 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1057 | 2024-06-15 | 9z                | L   | 0.856      | -            | -                | -                | -         |    -9.96 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1072 | 2024-06-15 | ODDIK             | W   | 0.854      | 0.450        | -                | 0.805 (0.309)    | -         |     2.63 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1089 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.850      | -            | -                | -                | -         |    -5.23 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1107 | 2024-06-14 | BESTIA            | W   | 0.848      | 0.548        | -                | 0.776 (0.361)    | 1 (0.848) |     3.89 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1132 | 2024-06-13 | KRÜ               | W   | 0.842      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1206 | 2024-06-10 | BESTIA            | W   | 0.823      | 0.371        | -                | 0.776 (0.236)    | -         |     3.95 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1219 | 2024-06-10 | Imperial          | W   | 0.821      | 0.371        | 0.233 (0.071)    | -                | -         |    11.07 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1249 | 2024-06-09 | Sharks            | W   | 0.815      | -            | -                | -                | -         |     4.13 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1303 | 2024-06-08 | Hype              | W   | 0.810      | -            | -                | -                | -         |     2.08 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1333 | 2024-06-08 | Dusty Roots       | W   | 0.807      | -            | -                | -                | -         |     1.58 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1360 | 2024-06-07 | Patins da Ferrari | W   | 0.803      | -            | -                | -                | -         |     1.25 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1411 | 2024-06-06 | Galorys           | W   | 0.797      | -            | -                | -                | -         |     1.86 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1421 | 2024-06-06 | Sharks            | L   | 0.796      | -            | -                | -                | -         |   -21.33 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1487 | 2024-06-05 | Fluxo             | W   | 0.789      | 0.450        | -                | 0.701 (0.249)    | -         |     4.38 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1541 | 2024-06-04 | ODDIK             | W   | 0.783      | 0.450        | -                | 0.805 (0.284)    | -         |     2.48 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1866 | 2024-05-22 | MIBR              | L   | 0.695      | -            | -                | -                | -         |    -8.35 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1870 | 2024-05-22 | MIBR              | L   | 0.695      | -            | -                | -                | -         |    -8.86 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1976 | 2024-05-19 | AMKAL             | L   | 0.674      | -            | -                | -                | -         |   -15.55 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1987 | 2024-05-19 | OG                | W   | 0.673      | 0.769        | 0.137 (0.071)    | -                | -         |     2.88 | biguzera, kauez, lux, nqz, snow   |
|           55 |     2001 | 2024-05-18 | AMKAL             | L   | 0.668      | -            | -                | -                | -         |   -16.01 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2225 | 2024-05-12 | 9z                | W   | 0.629      | 0.435        | 0.404 (0.110)    | -                | -         |    13.60 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2258 | 2024-05-11 | BESTIA            | W   | 0.621      | -            | -                | -                | -         |     1.81 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2286 | 2024-05-10 | RED Canids        | W   | 0.614      | -            | -                | -                | -         |     3.43 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2295 | 2024-05-09 | Fluxo             | L   | 0.610      | -            | -                | -                | -         |   -16.34 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2300 | 2024-05-09 | Fluxo             | W   | 0.610      | -            | -                | -                | -         |     2.81 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2320 | 2024-05-08 | RED Canids        | W   | 0.603      | -            | -                | -                | -         |     3.23 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2322 | 2024-05-08 | RED Canids        | L   | 0.603      | -            | -                | -                | -         |   -16.07 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2324 | 2024-05-08 | Galorys           | W   | 0.602      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2327 | 2024-05-08 | Galorys           | W   | 0.602      | -            | -                | -                | -         |     1.03 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2341 | 2024-05-07 | W7M               | W   | 0.595      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2361 | 2024-05-06 | W7M               | W   | 0.589      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2362 | 2024-05-06 | W7M               | W   | 0.588      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2374 | 2024-05-05 | KRÜ               | W   | 0.582      | -            | -                | -                | -         |     1.09 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2599 | 2024-04-25 | Solid             | W   | 0.516      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2601 | 2024-04-25 | Solid             | W   | 0.516      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2620 | 2024-04-24 | ODDIK             | W   | 0.510      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2621 | 2024-04-24 | ODDIK             | L   | 0.509      | -            | -                | -                | -         |   -14.82 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2694 | 2024-04-20 | Imperial          | W   | 0.482      | 0.589        | 0.233 (0.066)    | -                | 1 (0.482) |     5.40 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2703 | 2024-04-20 | MIBR              | W   | 0.481      | 0.589        | 0.208 (0.059)    | -                | 1 (0.481) |     8.85 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2724 | 2024-04-19 | Imperial          | L   | 0.478      | -            | -                | -                | -         |    -9.77 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2725 | 2024-04-19 | MIBR              | L   | 0.477      | -            | -                | -                | -         |    -6.61 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2737 | 2024-04-19 | Imperial          | W   | 0.475      | -            | -                | -                | -         |     5.19 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2751 | 2024-04-19 | MIBR              | W   | 0.475      | 0.589        | 0.208 (0.058)    | -                | 1 (0.475) |     8.44 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2774 | 2024-04-18 | Fluxo             | W   | 0.470      | -            | -                | -                | -         |     2.14 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2778 | 2024-04-18 | MIBR              | L   | 0.469      | -            | -                | -                | -         |    -6.62 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2804 | 2024-04-18 | Monte             | W   | 0.467      | -            | -                | -                | 1 (0.467) |     1.42 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2908 | 2024-04-14 | Imperial          | L   | 0.441      | -            | -                | -                | -         |    -9.35 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2919 | 2024-04-13 | ODDIK             | W   | 0.435      | -            | -                | -                | -         |     1.00 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2952 | 2024-04-11 | MIBR              | L   | 0.423      | -            | -                | -                | -         |    -6.54 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2958 | 2024-04-11 | Sharks            | W   | 0.422      | -            | -                | -                | -         |     1.07 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2964 | 2024-04-11 | Imperial          | W   | 0.421      | -            | -                | -                | -         |     4.25 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2999 | 2024-04-10 | RED Canids        | W   | 0.415      | -            | -                | -                | -         |     1.90 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     3043 | 2024-04-09 | Case              | W   | 0.410      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     3048 | 2024-04-09 | Case              | W   | 0.409      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3066 | 2024-04-09 | Imperial          | L   | 0.408      | -            | -                | -                | -         |    -8.72 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3088 | 2024-04-08 | Sharks            | W   | 0.402      | -            | -                | -                | -         |     0.35 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3118 | 2024-04-07 | MIBR              | L   | 0.397      | -            | -                | -                | -         |    -6.50 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3122 | 2024-04-07 | Galorys           | W   | 0.395      | -            | -                | -                | -         |     0.66 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3158 | 2024-04-05 | Sharks            | W   | 0.381      | -            | -                | -                | -         |     0.29 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3178 | 2024-04-04 | Sharks            | W   | 0.376      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3185 | 2024-04-04 | Sharks            | W   | 0.376      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3411 | 2024-03-24 | Natus Vincere     | L   | 0.302      | -            | -                | -                | -         |    -0.42 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3422 | 2024-03-23 | HEROIC            | W   | 0.295      | 1.000        | 0.224 (0.066)    | -                | 1 (0.295) |     6.49 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3437 | 2024-03-22 | The MongolZ       | W   | 0.287      | 1.000        | 1.000 (0.287)    | -                | 1 (0.287) |     8.59 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3457 | 2024-03-21 | Virtus.pro        | L   | 0.282      | -            | -                | -                | -         |    -1.44 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3465 | 2024-03-21 | Complexity        | L   | 0.280      | -            | -                | -                | -         |    -1.82 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3502 | 2024-03-19 | SAW               | W   | 0.267      | -            | -                | -                | 1 (0.267) |     1.79 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3517 | 2024-03-18 | ENCE              | W   | 0.260      | -            | -                | -                | 1 (0.260) |     4.85 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3535 | 2024-03-17 | Eternal Fire      | L   | 0.255      | -            | -                | -                | -         |    -1.25 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3545 | 2024-03-17 | Apeks             | W   | 0.254      | -            | -                | -                | 1 (0.254) |     0.47 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3875 | 2024-03-04 | ODDIK             | W   | 0.168      | -            | -                | -                | -         |     0.51 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3896 | 2024-03-03 | Imperial          | L   | 0.162      | -            | -                | -                | -         |    -3.52 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3923 | 2024-03-02 | RED Canids        | W   | 0.154      | -            | -                | -                | -         |     0.67 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3937 | 2024-03-01 | Legacy            | W   | 0.149      | -            | -                | -                | -         |     0.47 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($103,746.06)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.863 | $1,500.00      | $1,294.72       |
| 2024-06-16 |      0.862 | $10,000.00     | $8,615.74       |
| 2024-06-10 |      0.823 | $10,000.00     | $8,228.47       |
| 2024-06-09 |      0.816 | $3,000.00      | $2,446.94       |
| 2024-05-12 |      0.629 | $25,000.00     | $15,719.91      |
| 2024-04-20 |      0.482 | $100,000.00    | $48,231.48      |
| 2024-04-15 |      0.449 | $5,000.00      | $2,243.98       |
| 2024-03-31 |      0.348 | $20,000.00     | $6,964.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
