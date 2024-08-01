### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1348.8<br />
<br />
Final Rank Value (1348.8) = Starting Rank Value (1366.2) + Head To Head Adjustments (-17.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.656[<sup>1</sup>](#table2)
- Bounty Collected: 0.484[<sup>2</sup>](#table1)
- Opponent Network: 0.305[<sup>2</sup>](#table1)
- LAN Wins: 0.433[<sup>2</sup>](#table1)

The average of these factors is 0.470<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1366.2
- 400 + ( ( 0.470 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1366.2


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
|          103 |       27 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     5.10 | biguzera, kauez, lux, nqz, snow   |
|          102 |       50 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.67 | biguzera, kauez, lux, nqz, snow   |
|          101 |       73 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     1.32 | biguzera, kauez, lux, nqz, snow   |
|          100 |       77 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     1.34 | biguzera, kauez, lux, nqz, snow   |
|           99 |       92 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.82 | biguzera, kauez, lux, nqz, snow   |
|           98 |      113 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |    10.46 | biguzera, kauez, lux, nqz, snow   |
|           97 |      141 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |    10.48 | biguzera, kauez, lux, nqz, snow   |
|           96 |      147 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     9.37 | biguzera, kauez, lux, nqz, snow   |
|           95 |      363 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -20.96 | biguzera, kauez, lux, nqz, snow   |
|           94 |      371 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |    10.14 | biguzera, kauez, lux, nqz, snow   |
|           93 |      398 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |    10.02 | biguzera, kauez, lux, nqz, snow   |
|           92 |      411 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.96 | biguzera, kauez, lux, nqz, snow   |
|           91 |      432 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |    10.62 | biguzera, kauez, lux, nqz, snow   |
|           90 |      443 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     2.25 | biguzera, kauez, lux, nqz, snow   |
|           89 |      476 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.89 | biguzera, kauez, lux, nqz, snow   |
|           88 |      478 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.93 | biguzera, kauez, lux, nqz, snow   |
|           87 |      547 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.722 (0.325)    | -         |     3.08 | biguzera, kauez, lux, nqz, snow   |
|           86 |      549 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.722 (0.325)    | -         |     3.17 | biguzera, kauez, lux, nqz, snow   |
|           85 |      572 | 2024-07-17 | W7M               | W   | 1.000      | 0.384        | -                | 0.626 (0.240)    | -         |     2.64 | biguzera, kauez, lux, nqz, snow   |
|           84 |      608 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.568 (0.256)    | -         |     2.18 | biguzera, kauez, lux, nqz, snow   |
|           83 |      615 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.568 (0.256)    | -         |     2.23 | biguzera, kauez, lux, nqz, snow   |
|           82 |      657 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.844 (0.380)    | -         |     2.77 | biguzera, kauez, lux, nqz, snow   |
|           81 |      662 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.844 (0.380)    | -         |     2.85 | biguzera, kauez, lux, nqz, snow   |
|           80 |      892 | 2024-06-16 | Fluxo             | L   | 0.894      | -            | -                | -                | -         |   -20.04 | biguzera, kauez, lux, nqz, snow   |
|           79 |      930 | 2024-06-15 | ODDIK             | W   | 0.886      | 0.450        | 0.096 (0.038)    | 0.822 (0.328)    | -         |     4.47 | biguzera, kauez, lux, nqz, snow   |
|           78 |      984 | 2024-06-13 | KRÜ               | W   | 0.874      | -            | -                | -                | -         |     3.17 | biguzera, kauez, lux, nqz, snow   |
|           77 |     1060 | 2024-06-10 | BESTIA            | W   | 0.855      | -            | -                | -                | -         |     5.82 | biguzera, kauez, lux, nqz, snow   |
|           76 |     1073 | 2024-06-10 | Imperial          | W   | 0.853      | 0.371        | 0.239 (0.076)    | -                | -         |    14.27 | biguzera, kauez, lux, nqz, snow   |
|           75 |     1103 | 2024-06-09 | Sharks            | W   | 0.847      | -            | -                | -                | -         |     6.21 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1159 | 2024-06-08 | Hype              | W   | 0.842      | -            | -                | -                | -         |     3.76 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1189 | 2024-06-08 | Dusty Roots       | W   | 0.839      | -            | -                | -                | -         |     2.67 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1219 | 2024-06-07 | Patins da Ferrari | W   | 0.835      | -            | -                | -                | -         |     2.10 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1275 | 2024-06-06 | Galorys           | W   | 0.829      | -            | -                | -                | -         |     3.14 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1285 | 2024-06-06 | Sharks            | L   | 0.828      | -            | -                | -                | -         |   -20.52 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1354 | 2024-06-05 | Fluxo             | W   | 0.821      | 0.450        | 0.122 (0.045)    | 0.702 (0.259)    | -         |     6.71 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1409 | 2024-06-04 | ODDIK             | W   | 0.815      | 0.450        | -                | 0.822 (0.301)    | -         |     4.29 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1737 | 2024-05-22 | MIBR              | L   | 0.727      | -            | -                | -                | -         |    -7.32 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1741 | 2024-05-22 | MIBR              | L   | 0.727      | -            | -                | -                | -         |    -7.75 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1752 | 2024-05-22 | Smoke             | L   | 0.726      | -            | -                | -                | -         |   -21.32 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1753 | 2024-05-22 | Smoke             | L   | 0.726      | -            | -                | -                | -         |   -21.64 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1872 | 2024-05-19 | AMKAL             | L   | 0.706      | -            | -                | -                | -         |   -14.79 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1883 | 2024-05-19 | OG                | W   | 0.705      | 0.769        | 0.143 (0.078)    | -                | -         |     3.94 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1897 | 2024-05-18 | AMKAL             | L   | 0.700      | -            | -                | -                | -         |   -15.29 | biguzera, kauez, lux, nqz, snow   |
|           60 |     2030 | 2024-05-15 | Imperial          | L   | 0.679      | -            | -                | -                | -         |   -12.05 | biguzera, kauez, lux, nqz, snow   |
|           59 |     2031 | 2024-05-15 | Imperial          | L   | 0.679      | -            | -                | -                | -         |   -12.79 | biguzera, kauez, lux, nqz, snow   |
|           58 |     2131 | 2024-05-12 | 9z                | W   | 0.661      | 0.435        | 0.138 (0.040)    | -                | -         |     5.69 | biguzera, kauez, lux, nqz, snow   |
|           57 |     2164 | 2024-05-11 | BESTIA            | W   | 0.653      | -            | -                | -                | -         |     2.14 | biguzera, kauez, lux, nqz, snow   |
|           56 |     2192 | 2024-05-10 | RED Canids        | W   | 0.646      | -            | -                | -                | -         |     3.51 | biguzera, kauez, lux, nqz, snow   |
|           55 |     2201 | 2024-05-09 | Fluxo             | L   | 0.642      | -            | -                | -                | -         |   -16.64 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2206 | 2024-05-09 | Fluxo             | W   | 0.642      | -            | -                | -                | -         |     3.49 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2226 | 2024-05-08 | RED Canids        | W   | 0.635      | -            | -                | -                | -         |     3.33 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2230 | 2024-05-08 | RED Canids        | L   | 0.635      | -            | -                | -                | -         |   -17.00 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2232 | 2024-05-08 | Galorys           | W   | 0.634      | -            | -                | -                | -         |     1.34 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2235 | 2024-05-08 | Galorys           | W   | 0.634      | -            | -                | -                | -         |     1.36 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2249 | 2024-05-07 | W7M               | W   | 0.627      | -            | -                | -                | -         |     1.03 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2269 | 2024-05-06 | W7M               | W   | 0.621      | -            | -                | -                | -         |     1.03 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2270 | 2024-05-06 | W7M               | W   | 0.620      | -            | -                | -                | -         |     1.04 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2282 | 2024-05-05 | KRÜ               | W   | 0.614      | -            | -                | -                | -         |     1.41 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2510 | 2024-04-25 | Solid             | W   | 0.548      | -            | -                | -                | -         |     1.07 | biguzera, kauez, lux, nqz, nyezin |
|           44 |     2512 | 2024-04-25 | Solid             | W   | 0.548      | -            | -                | -                | -         |     1.09 | biguzera, kauez, lux, nqz, nyezin |
|           43 |     2531 | 2024-04-24 | ODDIK             | W   | 0.542      | -            | -                | -                | -         |     1.83 | biguzera, kauez, lux, nqz, nyezin |
|           42 |     2532 | 2024-04-24 | ODDIK             | L   | 0.541      | -            | -                | -                | -         |   -15.41 | biguzera, kauez, lux, nqz, nyezin |
|           41 |     2611 | 2024-04-20 | Imperial          | W   | 0.514      | 0.589        | 0.239 (0.072)    | -                | 1 (0.514) |     6.49 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2620 | 2024-04-20 | MIBR              | W   | 0.513      | 0.589        | 0.201 (0.061)    | -                | 1 (0.513) |    10.06 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2641 | 2024-04-19 | Imperial          | L   | 0.510      | -            | -                | -                | -         |    -9.65 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2642 | 2024-04-19 | MIBR              | L   | 0.509      | -            | -                | -                | -         |    -6.39 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2655 | 2024-04-19 | Imperial          | W   | 0.507      | -            | -                | -                | -         |     6.34 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2669 | 2024-04-19 | MIBR              | W   | 0.507      | 0.589        | 0.201 (0.060)    | -                | 1 (0.507) |     9.70 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2692 | 2024-04-18 | Fluxo             | W   | 0.502      | -            | -                | -                | -         |     2.80 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2696 | 2024-04-18 | MIBR              | L   | 0.501      | -            | -                | -                | -         |    -6.34 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2723 | 2024-04-18 | Monte             | W   | 0.500      | -            | -                | -                | 1 (0.500) |     1.97 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2829 | 2024-04-14 | Imperial          | L   | 0.473      | -            | -                | -                | -         |    -9.06 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2840 | 2024-04-13 | ODDIK             | W   | 0.468      | -            | -                | -                | -         |     1.40 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2874 | 2024-04-11 | MIBR              | L   | 0.455      | -            | -                | -                | -         |    -6.35 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2880 | 2024-04-11 | Sharks            | W   | 0.454      | -            | -                | -                | -         |     1.44 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2886 | 2024-04-11 | Imperial          | W   | 0.453      | -            | -                | -                | -         |     5.54 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2921 | 2024-04-10 | RED Canids        | W   | 0.447      | -            | -                | -                | -         |     2.06 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2965 | 2024-04-09 | Case              | W   | 0.442      | -            | -                | -                | -         |     0.99 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2970 | 2024-04-09 | Case              | W   | 0.441      | -            | -                | -                | -         |     1.00 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2988 | 2024-04-09 | Imperial          | L   | 0.440      | -            | -                | -                | -         |    -8.40 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     3010 | 2024-04-08 | Sharks            | W   | 0.434      | -            | -                | -                | -         |     0.47 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     3040 | 2024-04-07 | MIBR              | L   | 0.429      | -            | -                | -                | -         |    -6.33 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     3044 | 2024-04-07 | Galorys           | W   | 0.427      | -            | -                | -                | -         |     0.97 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3080 | 2024-04-05 | Sharks            | W   | 0.413      | -            | -                | -                | -         |     0.39 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3100 | 2024-04-04 | Sharks            | W   | 0.408      | -            | -                | -                | -         |     0.39 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3107 | 2024-04-04 | Sharks            | W   | 0.408      | -            | -                | -                | -         |     0.39 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3346 | 2024-03-24 | Natus Vincere     | L   | 0.334      | -            | -                | -                | -         |    -0.36 | biguzera, kauez, lux, n1ssim, nqz |
|           16 |     3357 | 2024-03-23 | HEROIC            | W   | 0.327      | 1.000        | 0.208 (0.068)    | -                | 1 (0.327) |     7.81 | biguzera, kauez, lux, n1ssim, nqz |
|           15 |     3372 | 2024-03-22 | The MongolZ       | W   | 0.319      | 1.000        | 1.000 (0.319)    | -                | 1 (0.319) |     9.64 | biguzera, kauez, lux, n1ssim, nqz |
|           14 |     3392 | 2024-03-21 | Virtus.pro        | L   | 0.314      | -            | -                | -                | -         |    -1.25 | biguzera, kauez, lux, n1ssim, nqz |
|           13 |     3400 | 2024-03-21 | Complexity        | L   | 0.313      | -            | -                | -                | -         |    -1.81 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3437 | 2024-03-19 | SAW               | W   | 0.299      | -            | -                | -                | 1 (0.299) |     2.58 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3452 | 2024-03-18 | ENCE              | W   | 0.292      | -            | -                | -                | 1 (0.292) |     5.92 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3470 | 2024-03-17 | Eternal Fire      | L   | 0.287      | -            | -                | -                | -         |    -1.05 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3480 | 2024-03-17 | Apeks             | W   | 0.286      | -            | -                | -                | 1 (0.286) |     0.72 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3821 | 2024-03-04 | ODDIK             | W   | 0.200      | -            | -                | -                | 1 (0.200) |     0.81 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3842 | 2024-03-03 | Imperial          | L   | 0.194      | -            | -                | -                | -         |    -3.74 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3869 | 2024-03-02 | RED Canids        | W   | 0.186      | -            | -                | -                | -         |     0.79 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3884 | 2024-03-01 | Legacy            | W   | 0.181      | -            | -                | -                | -         |     0.74 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     4304 | 2024-02-13 | 9z                | L   | 0.068      | -            | -                | -                | -         |    -1.45 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     4305 | 2024-02-13 | 9z                | L   | 0.068      | -            | -                | -                | -         |    -1.45 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     4308 | 2024-02-13 | BESTIA            | L   | 0.068      | -            | -                | -                | -         |    -1.88 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     4309 | 2024-02-13 | BESTIA            | L   | 0.068      | -            | -                | -                | -         |    -1.88 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($97,993.75)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.30) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.894 | $10,000.00     | $8,936.11       |
| 2024-06-10 |      0.855 | $10,000.00     | $8,548.84       |
| 2024-06-09 |      0.848 | $3,000.00      | $2,543.06       |
| 2024-05-12 |      0.661 | $25,000.00     | $16,520.83      |
| 2024-04-20 |      0.514 | $100,000.00    | $51,435.19      |
| 2024-04-15 |      0.481 | $5,000.00      | $2,404.17       |
| 2024-03-31 |      0.380 | $20,000.00     | $7,605.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
