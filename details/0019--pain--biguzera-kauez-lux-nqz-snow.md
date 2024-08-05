### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1423.4<br />
<br />
Final Rank Value (1423.4) = Starting Rank Value (1405.2) + Head To Head Adjustments (18.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.672[<sup>1</sup>](#table2)
- Bounty Collected: 0.491[<sup>2</sup>](#table1)
- Opponent Network: 0.318[<sup>2</sup>](#table1)
- LAN Wins: 0.479[<sup>2</sup>](#table1)

The average of these factors is 0.490<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1405.2
- 400 + ( ( 0.490 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1405.2


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
|          103 |       51 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.84 | biguzera, kauez, lux, nqz, snow   |
|          102 |       63 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.08 | biguzera, kauez, lux, nqz, snow   |
|          101 |       85 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.208 (0.077)    | -                | -         |    11.98 | biguzera, kauez, lux, nqz, snow   |
|          100 |       89 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.81 | biguzera, kauez, lux, nqz, snow   |
|           99 |      104 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.51 | biguzera, kauez, lux, nqz, snow   |
|           98 |      142 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.48 | biguzera, kauez, lux, nqz, snow   |
|           97 |      171 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.11 | biguzera, kauez, lux, nqz, snow   |
|           96 |      192 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.24 | biguzera, kauez, lux, nqz, snow   |
|           95 |      216 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, snow   |
|           94 |      220 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, snow   |
|           93 |      235 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.27 | biguzera, kauez, lux, nqz, snow   |
|           92 |      255 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.60 | biguzera, kauez, lux, nqz, snow   |
|           91 |      283 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.51 | biguzera, kauez, lux, nqz, snow   |
|           90 |      289 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.05 | biguzera, kauez, lux, nqz, snow   |
|           89 |      504 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.54 | biguzera, kauez, lux, nqz, snow   |
|           88 |      511 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.48 | biguzera, kauez, lux, nqz, snow   |
|           87 |      537 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.92 | biguzera, kauez, lux, nqz, snow   |
|           86 |      550 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.09 | biguzera, kauez, lux, nqz, snow   |
|           85 |      570 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.78 | biguzera, kauez, lux, nqz, snow   |
|           84 |      580 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.62 | biguzera, kauez, lux, nqz, snow   |
|           83 |      611 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.29 | biguzera, kauez, lux, nqz, snow   |
|           82 |      613 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.31 | biguzera, kauez, lux, nqz, snow   |
|           81 |      679 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.795 (0.358)    | -         |     2.35 | biguzera, kauez, lux, nqz, snow   |
|           80 |      682 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.795 (0.358)    | -         |     2.41 | biguzera, kauez, lux, nqz, snow   |
|           79 |      705 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.49 | biguzera, kauez, lux, nqz, snow   |
|           78 |      741 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.543 (0.244)    | -         |     1.63 | biguzera, kauez, lux, nqz, snow   |
|           77 |      784 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.825 (0.371)    | -         |     1.94 | biguzera, kauez, lux, nqz, snow   |
|           76 |      788 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.825 (0.371)    | -         |     1.98 | biguzera, kauez, lux, nqz, snow   |
|           75 |     1018 | 2024-06-16 | Fluxo             | L   | 0.867      | -            | -                | -                | -         |   -21.21 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1045 | 2024-06-15 | 9z                | L   | 0.861      | -            | -                | -                | -         |   -10.06 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1060 | 2024-06-15 | ODDIK             | W   | 0.859      | 0.450        | -                | 0.822 (0.318)    | -         |     2.62 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1077 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.855      | -            | -                | -                | -         |    -5.31 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1095 | 2024-06-14 | BESTIA            | W   | 0.853      | 0.548        | -                | 0.792 (0.370)    | 1 (0.853) |     3.89 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1120 | 2024-06-13 | KRÜ               | W   | 0.847      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1194 | 2024-06-10 | BESTIA            | W   | 0.828      | 0.371        | -                | 0.792 (0.243)    | -         |     3.96 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1207 | 2024-06-10 | Imperial          | W   | 0.826      | 0.371        | 0.234 (0.072)    | -                | -         |    11.14 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1237 | 2024-06-09 | Sharks            | W   | 0.820      | -            | -                | -                | -         |     4.15 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1291 | 2024-06-08 | Hype              | W   | 0.815      | -            | -                | -                | -         |     2.08 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1321 | 2024-06-08 | Dusty Roots       | W   | 0.812      | -            | -                | -                | -         |     1.57 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1348 | 2024-06-07 | Patins da Ferrari | W   | 0.808      | -            | -                | -                | -         |     1.25 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1399 | 2024-06-06 | Galorys           | W   | 0.802      | -            | -                | -                | -         |     1.85 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1409 | 2024-06-06 | Sharks            | L   | 0.801      | -            | -                | -                | -         |   -21.46 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1475 | 2024-06-05 | Fluxo             | W   | 0.794      | 0.450        | -                | 0.716 (0.256)    | -         |     4.40 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1529 | 2024-06-04 | ODDIK             | W   | 0.788      | 0.450        | -                | 0.822 (0.291)    | -         |     2.48 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1854 | 2024-05-22 | MIBR              | L   | 0.700      | -            | -                | -                | -         |    -8.41 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1858 | 2024-05-22 | MIBR              | L   | 0.700      | -            | -                | -                | -         |    -8.93 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1964 | 2024-05-19 | AMKAL             | L   | 0.679      | -            | -                | -                | -         |   -15.74 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1975 | 2024-05-19 | OG                | W   | 0.677      | 0.769        | 0.138 (0.072)    | -                | -         |     2.88 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1989 | 2024-05-18 | AMKAL             | L   | 0.673      | -            | -                | -                | -         |   -16.20 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2213 | 2024-05-12 | 9z                | W   | 0.634      | 0.435        | 0.404 (0.111)    | -                | -         |    13.66 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2246 | 2024-05-11 | BESTIA            | W   | 0.626      | -            | -                | -                | -         |     1.80 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2274 | 2024-05-10 | RED Canids        | W   | 0.619      | -            | -                | -                | -         |     3.44 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2283 | 2024-05-09 | Fluxo             | L   | 0.615      | -            | -                | -                | -         |   -16.48 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2288 | 2024-05-09 | Fluxo             | W   | 0.615      | -            | -                | -                | -         |     2.81 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2308 | 2024-05-08 | RED Canids        | W   | 0.608      | -            | -                | -                | -         |     3.24 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2310 | 2024-05-08 | RED Canids        | L   | 0.608      | -            | -                | -                | -         |   -16.21 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2312 | 2024-05-08 | Galorys           | W   | 0.607      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2315 | 2024-05-08 | Galorys           | W   | 0.607      | -            | -                | -                | -         |     1.03 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2329 | 2024-05-07 | W7M               | W   | 0.600      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2349 | 2024-05-06 | W7M               | W   | 0.593      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2350 | 2024-05-06 | W7M               | W   | 0.593      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2362 | 2024-05-05 | KRÜ               | W   | 0.587      | -            | -                | -                | -         |     1.09 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2587 | 2024-04-25 | Solid             | W   | 0.521      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2589 | 2024-04-25 | Solid             | W   | 0.521      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2608 | 2024-04-24 | ODDIK             | W   | 0.515      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2609 | 2024-04-24 | ODDIK             | L   | 0.514      | -            | -                | -                | -         |   -14.98 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2682 | 2024-04-20 | Imperial          | W   | 0.487      | 0.589        | 0.234 (0.067)    | -                | 1 (0.487) |     5.45 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2691 | 2024-04-20 | MIBR              | W   | 0.486      | 0.589        | 0.208 (0.060)    | -                | 1 (0.486) |     8.94 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2712 | 2024-04-19 | Imperial          | L   | 0.483      | -            | -                | -                | -         |    -9.87 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2713 | 2024-04-19 | MIBR              | L   | 0.482      | -            | -                | -                | -         |    -6.69 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2725 | 2024-04-19 | Imperial          | W   | 0.480      | -            | -                | -                | -         |     5.24 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2739 | 2024-04-19 | MIBR              | W   | 0.480      | 0.589        | 0.208 (0.059)    | -                | 1 (0.480) |     8.52 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2762 | 2024-04-18 | Fluxo             | W   | 0.475      | -            | -                | -                | -         |     2.15 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2766 | 2024-04-18 | MIBR              | L   | 0.474      | -            | -                | -                | -         |    -6.70 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2792 | 2024-04-18 | Monte             | W   | 0.472      | -            | -                | -                | 1 (0.472) |     1.41 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2896 | 2024-04-14 | Imperial          | L   | 0.446      | -            | -                | -                | -         |    -9.45 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2907 | 2024-04-13 | ODDIK             | W   | 0.440      | -            | -                | -                | -         |     0.99 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2940 | 2024-04-11 | MIBR              | L   | 0.428      | -            | -                | -                | -         |    -6.63 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2946 | 2024-04-11 | Sharks            | W   | 0.427      | -            | -                | -                | -         |     1.07 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2952 | 2024-04-11 | Imperial          | W   | 0.426      | -            | -                | -                | -         |     4.30 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2987 | 2024-04-10 | RED Canids        | W   | 0.420      | -            | -                | -                | -         |     1.91 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     3031 | 2024-04-09 | Case              | W   | 0.415      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     3036 | 2024-04-09 | Case              | W   | 0.414      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3054 | 2024-04-09 | Imperial          | L   | 0.412      | -            | -                | -                | -         |    -8.83 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3076 | 2024-04-08 | Sharks            | W   | 0.407      | -            | -                | -                | -         |     0.34 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3106 | 2024-04-07 | MIBR              | L   | 0.402      | -            | -                | -                | -         |    -6.61 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3110 | 2024-04-07 | Galorys           | W   | 0.400      | -            | -                | -                | -         |     0.66 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3146 | 2024-04-05 | Sharks            | W   | 0.386      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3166 | 2024-04-04 | Sharks            | W   | 0.381      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3173 | 2024-04-04 | Sharks            | W   | 0.381      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3399 | 2024-03-24 | Natus Vincere     | L   | 0.307      | -            | -                | -                | -         |    -0.44 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3410 | 2024-03-23 | HEROIC            | W   | 0.300      | 1.000        | 0.225 (0.068)    | -                | 1 (0.300) |     6.58 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3425 | 2024-03-22 | The MongolZ       | W   | 0.292      | 1.000        | 1.000 (0.292)    | -                | 1 (0.292) |     8.73 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3445 | 2024-03-21 | Virtus.pro        | L   | 0.287      | -            | -                | -                | -         |    -1.48 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3453 | 2024-03-21 | Complexity        | L   | 0.285      | -            | -                | -                | -         |    -1.88 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3490 | 2024-03-19 | SAW               | W   | 0.272      | -            | -                | -                | 1 (0.272) |     1.82 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3505 | 2024-03-18 | ENCE              | W   | 0.265      | -            | -                | -                | 1 (0.265) |     4.88 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3523 | 2024-03-17 | Eternal Fire      | L   | 0.260      | -            | -                | -                | -         |    -1.29 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3533 | 2024-03-17 | Apeks             | W   | 0.258      | -            | -                | -                | 1 (0.258) |     0.47 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3863 | 2024-03-04 | ODDIK             | W   | 0.173      | -            | -                | -                | -         |     0.52 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3884 | 2024-03-03 | Imperial          | L   | 0.167      | -            | -                | -                | -         |    -3.63 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3911 | 2024-03-02 | RED Canids        | W   | 0.159      | -            | -                | -                | -         |     0.69 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3925 | 2024-03-01 | Legacy            | W   | 0.154      | -            | -                | -                | -         |     0.48 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($104,610.49)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.868 | $1,500.00      | $1,302.15       |
| 2024-06-16 |      0.867 | $10,000.00     | $8,665.28       |
| 2024-06-10 |      0.828 | $10,000.00     | $8,278.01       |
| 2024-06-09 |      0.821 | $3,000.00      | $2,461.81       |
| 2024-05-12 |      0.634 | $25,000.00     | $15,843.75      |
| 2024-04-20 |      0.487 | $100,000.00    | $48,726.85      |
| 2024-04-15 |      0.454 | $5,000.00      | $2,268.75       |
| 2024-03-31 |      0.353 | $20,000.00     | $7,063.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
