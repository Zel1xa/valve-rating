### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1349.9<br />
<br />
Final Rank Value (1349.9) = Starting Rank Value (1368.1) + Head To Head Adjustments (-18.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.657[<sup>1</sup>](#table2)
- Bounty Collected: 0.484[<sup>2</sup>](#table1)
- Opponent Network: 0.305[<sup>2</sup>](#table1)
- LAN Wins: 0.435[<sup>2</sup>](#table1)

The average of these factors is 0.470<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1368.1
- 400 + ( ( 0.470 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1368.1


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
|          103 |       23 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     5.09 | biguzera, kauez, lux, nqz, snow   |
|          102 |       46 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.67 | biguzera, kauez, lux, nqz, snow   |
|          101 |       69 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     1.31 | biguzera, kauez, lux, nqz, snow   |
|          100 |       73 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     1.33 | biguzera, kauez, lux, nqz, snow   |
|           99 |       88 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.82 | biguzera, kauez, lux, nqz, snow   |
|           98 |      109 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |    10.46 | biguzera, kauez, lux, nqz, snow   |
|           97 |      137 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |    10.48 | biguzera, kauez, lux, nqz, snow   |
|           96 |      143 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     9.36 | biguzera, kauez, lux, nqz, snow   |
|           95 |      359 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -20.96 | biguzera, kauez, lux, nqz, snow   |
|           94 |      367 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |    10.13 | biguzera, kauez, lux, nqz, snow   |
|           93 |      394 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |    10.02 | biguzera, kauez, lux, nqz, snow   |
|           92 |      407 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.96 | biguzera, kauez, lux, nqz, snow   |
|           91 |      428 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |    10.62 | biguzera, kauez, lux, nqz, snow   |
|           90 |      439 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     2.24 | biguzera, kauez, lux, nqz, snow   |
|           89 |      472 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.88 | biguzera, kauez, lux, nqz, snow   |
|           88 |      474 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.92 | biguzera, kauez, lux, nqz, snow   |
|           87 |      543 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.721 (0.325)    | -         |     3.07 | biguzera, kauez, lux, nqz, snow   |
|           86 |      545 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.721 (0.325)    | -         |     3.17 | biguzera, kauez, lux, nqz, snow   |
|           85 |      568 | 2024-07-17 | W7M               | W   | 1.000      | 0.384        | -                | 0.625 (0.240)    | -         |     2.63 | biguzera, kauez, lux, nqz, snow   |
|           84 |      604 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.568 (0.256)    | -         |     2.17 | biguzera, kauez, lux, nqz, snow   |
|           83 |      611 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.568 (0.256)    | -         |     2.23 | biguzera, kauez, lux, nqz, snow   |
|           82 |      653 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.843 (0.380)    | -         |     2.76 | biguzera, kauez, lux, nqz, snow   |
|           81 |      658 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.843 (0.380)    | -         |     2.84 | biguzera, kauez, lux, nqz, snow   |
|           80 |      888 | 2024-06-16 | Fluxo             | L   | 0.895      | -            | -                | -                | -         |   -20.08 | biguzera, kauez, lux, nqz, snow   |
|           79 |      926 | 2024-06-15 | ODDIK             | W   | 0.887      | 0.450        | 0.096 (0.038)    | 0.822 (0.328)    | -         |     4.46 | biguzera, kauez, lux, nqz, snow   |
|           78 |      980 | 2024-06-13 | KRÜ               | W   | 0.876      | -            | -                | -                | -         |     3.16 | biguzera, kauez, lux, nqz, snow   |
|           77 |     1056 | 2024-06-10 | BESTIA            | W   | 0.856      | -            | -                | -                | -         |     5.82 | biguzera, kauez, lux, nqz, snow   |
|           76 |     1069 | 2024-06-10 | Imperial          | W   | 0.854      | 0.371        | 0.240 (0.076)    | -                | -         |    14.30 | biguzera, kauez, lux, nqz, snow   |
|           75 |     1099 | 2024-06-09 | Sharks            | W   | 0.848      | -            | -                | -                | -         |     6.21 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1155 | 2024-06-08 | Hype              | W   | 0.843      | -            | -                | -                | -         |     3.75 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1185 | 2024-06-08 | Dusty Roots       | W   | 0.841      | -            | -                | -                | -         |     2.66 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1215 | 2024-06-07 | Patins da Ferrari | W   | 0.836      | -            | -                | -                | -         |     2.09 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1271 | 2024-06-06 | Galorys           | W   | 0.830      | -            | -                | -                | -         |     3.13 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1281 | 2024-06-06 | Sharks            | L   | 0.829      | -            | -                | -                | -         |   -20.56 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1350 | 2024-06-05 | Fluxo             | W   | 0.823      | 0.450        | 0.122 (0.045)    | 0.701 (0.260)    | -         |     6.71 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1405 | 2024-06-04 | ODDIK             | W   | 0.816      | 0.450        | -                | 0.822 (0.302)    | -         |     4.28 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1733 | 2024-05-22 | MIBR              | L   | 0.729      | -            | -                | -                | -         |    -7.33 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1737 | 2024-05-22 | MIBR              | L   | 0.728      | -            | -                | -                | -         |    -7.76 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1748 | 2024-05-22 | Smoke             | L   | 0.727      | -            | -                | -                | -         |   -21.37 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1749 | 2024-05-22 | Smoke             | L   | 0.727      | -            | -                | -                | -         |   -21.68 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1868 | 2024-05-19 | AMKAL             | L   | 0.708      | -            | -                | -                | -         |   -14.85 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1879 | 2024-05-19 | OG                | W   | 0.706      | 0.769        | 0.143 (0.078)    | -                | -         |     3.92 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1893 | 2024-05-18 | AMKAL             | L   | 0.701      | -            | -                | -                | -         |   -15.33 | biguzera, kauez, lux, nqz, snow   |
|           60 |     2026 | 2024-05-15 | Imperial          | L   | 0.680      | -            | -                | -                | -         |   -12.07 | biguzera, kauez, lux, nqz, snow   |
|           59 |     2027 | 2024-05-15 | Imperial          | L   | 0.680      | -            | -                | -                | -         |   -12.81 | biguzera, kauez, lux, nqz, snow   |
|           58 |     2127 | 2024-05-12 | 9z                | W   | 0.662      | 0.435        | 0.138 (0.040)    | -                | -         |     5.67 | biguzera, kauez, lux, nqz, snow   |
|           57 |     2160 | 2024-05-11 | BESTIA            | W   | 0.655      | -            | -                | -                | -         |     2.13 | biguzera, kauez, lux, nqz, snow   |
|           56 |     2188 | 2024-05-10 | RED Canids        | W   | 0.647      | -            | -                | -                | -         |     3.50 | biguzera, kauez, lux, nqz, snow   |
|           55 |     2197 | 2024-05-09 | Fluxo             | L   | 0.644      | -            | -                | -                | -         |   -16.69 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2202 | 2024-05-09 | Fluxo             | W   | 0.643      | -            | -                | -                | -         |     3.49 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2222 | 2024-05-08 | RED Canids        | W   | 0.637      | -            | -                | -                | -         |     3.32 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2226 | 2024-05-08 | RED Canids        | L   | 0.636      | -            | -                | -                | -         |   -17.04 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2228 | 2024-05-08 | Galorys           | W   | 0.635      | -            | -                | -                | -         |     1.33 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2231 | 2024-05-08 | Galorys           | W   | 0.635      | -            | -                | -                | -         |     1.35 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2245 | 2024-05-07 | W7M               | W   | 0.629      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2265 | 2024-05-06 | W7M               | W   | 0.622      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2266 | 2024-05-06 | W7M               | W   | 0.622      | -            | -                | -                | -         |     1.03 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2278 | 2024-05-05 | KRÜ               | W   | 0.616      | -            | -                | -                | -         |     1.41 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2506 | 2024-04-25 | Solid             | W   | 0.550      | -            | -                | -                | -         |     1.07 | biguzera, kauez, lux, nqz, nyezin |
|           44 |     2508 | 2024-04-25 | Solid             | W   | 0.549      | -            | -                | -                | -         |     1.08 | biguzera, kauez, lux, nqz, nyezin |
|           43 |     2527 | 2024-04-24 | ODDIK             | W   | 0.543      | -            | -                | -                | -         |     1.83 | biguzera, kauez, lux, nqz, nyezin |
|           42 |     2528 | 2024-04-24 | ODDIK             | L   | 0.543      | -            | -                | -                | -         |   -15.46 | biguzera, kauez, lux, nqz, nyezin |
|           41 |     2607 | 2024-04-20 | Imperial          | W   | 0.516      | 0.589        | 0.240 (0.073)    | -                | 1 (0.516) |     6.51 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2616 | 2024-04-20 | MIBR              | W   | 0.515      | 0.589        | 0.201 (0.061)    | -                | 1 (0.515) |    10.09 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2637 | 2024-04-19 | Imperial          | L   | 0.511      | -            | -                | -                | -         |    -9.68 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2638 | 2024-04-19 | MIBR              | L   | 0.511      | -            | -                | -                | -         |    -6.42 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2651 | 2024-04-19 | Imperial          | W   | 0.509      | -            | -                | -                | -         |     6.36 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2665 | 2024-04-19 | MIBR              | W   | 0.508      | 0.589        | 0.201 (0.060)    | -                | 1 (0.508) |     9.72 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2688 | 2024-04-18 | Fluxo             | W   | 0.504      | -            | -                | -                | -         |     2.80 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2692 | 2024-04-18 | MIBR              | L   | 0.503      | -            | -                | -                | -         |    -6.36 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2719 | 2024-04-18 | Monte             | W   | 0.501      | -            | -                | -                | 1 (0.501) |     1.97 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2825 | 2024-04-14 | Imperial          | L   | 0.475      | -            | -                | -                | -         |    -9.09 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2836 | 2024-04-13 | ODDIK             | W   | 0.469      | -            | -                | -                | -         |     1.39 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2870 | 2024-04-11 | MIBR              | L   | 0.457      | -            | -                | -                | -         |    -6.37 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2876 | 2024-04-11 | Sharks            | W   | 0.456      | -            | -                | -                | -         |     1.44 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2882 | 2024-04-11 | Imperial          | W   | 0.455      | -            | -                | -                | -         |     5.56 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2917 | 2024-04-10 | RED Canids        | W   | 0.448      | -            | -                | -                | -         |     2.06 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2961 | 2024-04-09 | Case              | W   | 0.443      | -            | -                | -                | -         |     0.99 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2966 | 2024-04-09 | Case              | W   | 0.443      | -            | -                | -                | -         |     1.00 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2984 | 2024-04-09 | Imperial          | L   | 0.441      | -            | -                | -                | -         |    -8.43 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     3006 | 2024-04-08 | Sharks            | W   | 0.435      | -            | -                | -                | -         |     0.47 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     3036 | 2024-04-07 | MIBR              | L   | 0.430      | -            | -                | -                | -         |    -6.36 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     3040 | 2024-04-07 | Galorys           | W   | 0.429      | -            | -                | -                | -         |     0.97 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3076 | 2024-04-05 | Sharks            | W   | 0.414      | -            | -                | -                | -         |     0.39 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3096 | 2024-04-04 | Sharks            | W   | 0.410      | -            | -                | -                | -         |     0.38 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3103 | 2024-04-04 | Sharks            | W   | 0.409      | -            | -                | -                | -         |     0.38 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3342 | 2024-03-24 | Natus Vincere     | L   | 0.335      | -            | -                | -                | -         |    -0.36 | biguzera, kauez, lux, n1ssim, nqz |
|           16 |     3353 | 2024-03-23 | HEROIC            | W   | 0.329      | 1.000        | 0.209 (0.069)    | -                | 1 (0.329) |     7.84 | biguzera, kauez, lux, n1ssim, nqz |
|           15 |     3368 | 2024-03-22 | The MongolZ       | W   | 0.321      | 1.000        | 1.000 (0.321)    | -                | 1 (0.321) |     9.68 | biguzera, kauez, lux, n1ssim, nqz |
|           14 |     3388 | 2024-03-21 | Virtus.pro        | L   | 0.315      | -            | -                | -                | -         |    -1.25 | biguzera, kauez, lux, n1ssim, nqz |
|           13 |     3396 | 2024-03-21 | Complexity        | L   | 0.314      | -            | -                | -                | -         |    -1.82 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3433 | 2024-03-19 | SAW               | W   | 0.301      | -            | -                | -                | 1 (0.301) |     2.59 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3448 | 2024-03-18 | ENCE              | W   | 0.293      | -            | -                | -                | 1 (0.293) |     5.95 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3466 | 2024-03-17 | Eternal Fire      | L   | 0.288      | -            | -                | -                | -         |    -1.06 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3476 | 2024-03-17 | Apeks             | W   | 0.287      | -            | -                | -                | 1 (0.287) |     0.73 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3817 | 2024-03-04 | ODDIK             | W   | 0.201      | -            | -                | -                | 1 (0.201) |     0.81 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3838 | 2024-03-03 | Imperial          | L   | 0.195      | -            | -                | -                | -         |    -3.77 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3865 | 2024-03-02 | RED Canids        | W   | 0.188      | -            | -                | -                | -         |     0.79 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3880 | 2024-03-01 | Legacy            | W   | 0.183      | -            | -                | -                | -         |     0.74 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     4300 | 2024-02-13 | 9z                | L   | 0.070      | -            | -                | -                | -         |    -1.48 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     4301 | 2024-02-13 | 9z                | L   | 0.070      | -            | -                | -                | -         |    -1.49 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     4304 | 2024-02-13 | BESTIA            | L   | 0.070      | -            | -                | -                | -         |    -1.92 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     4305 | 2024-02-13 | BESTIA            | L   | 0.070      | -            | -                | -                | -         |    -1.92 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($98,234.03)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.30) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.895 | $10,000.00     | $8,950.00       |
| 2024-06-10 |      0.856 | $10,000.00     | $8,562.73       |
| 2024-06-09 |      0.849 | $3,000.00      | $2,547.22       |
| 2024-05-12 |      0.662 | $25,000.00     | $16,555.56      |
| 2024-04-20 |      0.516 | $100,000.00    | $51,574.07      |
| 2024-04-15 |      0.482 | $5,000.00      | $2,411.11       |
| 2024-03-31 |      0.382 | $20,000.00     | $7,633.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
