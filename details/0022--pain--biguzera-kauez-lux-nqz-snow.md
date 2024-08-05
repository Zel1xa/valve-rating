### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1398.2<br />
<br />
Final Rank Value (1398.2) = Starting Rank Value (1429.6) + Head To Head Adjustments (-31.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.677[<sup>1</sup>](#table2)
- Bounty Collected: 0.496[<sup>2</sup>](#table1)
- Opponent Network: 0.308[<sup>2</sup>](#table1)
- LAN Wins: 0.517[<sup>2</sup>](#table1)

The average of these factors is 0.499<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1429.6
- 400 + ( ( 0.499 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1429.6


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
|           96 |       17 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.15 | biguzera, kauez, lux, nqz, snow   |
|           95 |       41 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.68 | biguzera, kauez, lux, nqz, snow   |
|           94 |       45 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.68 | biguzera, kauez, lux, nqz, snow   |
|           93 |       60 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.12 | biguzera, kauez, lux, nqz, snow   |
|           92 |       80 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.71 | biguzera, kauez, lux, nqz, snow   |
|           91 |      108 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.63 | biguzera, kauez, lux, nqz, snow   |
|           90 |      114 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     7.94 | biguzera, kauez, lux, nqz, snow   |
|           89 |      329 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.74 | biguzera, kauez, lux, nqz, snow   |
|           88 |      336 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.27 | biguzera, kauez, lux, nqz, snow   |
|           87 |      362 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.10 | biguzera, kauez, lux, nqz, snow   |
|           86 |      375 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     2.94 | biguzera, kauez, lux, nqz, snow   |
|           85 |      395 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.56 | biguzera, kauez, lux, nqz, snow   |
|           84 |      405 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.52 | biguzera, kauez, lux, nqz, snow   |
|           83 |      436 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.18 | biguzera, kauez, lux, nqz, snow   |
|           82 |      438 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.19 | biguzera, kauez, lux, nqz, snow   |
|           81 |      504 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.720 (0.324)    | -         |     2.20 | biguzera, kauez, lux, nqz, snow   |
|           80 |      507 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.720 (0.324)    | -         |     2.25 | biguzera, kauez, lux, nqz, snow   |
|           79 |      530 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.38 | biguzera, kauez, lux, nqz, snow   |
|           78 |      566 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.553 (0.249)    | -         |     1.49 | biguzera, kauez, lux, nqz, snow   |
|           77 |      609 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.817 (0.368)    | -         |     1.80 | biguzera, kauez, lux, nqz, snow   |
|           76 |      613 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.817 (0.368)    | -         |     1.83 | biguzera, kauez, lux, nqz, snow   |
|           75 |      843 | 2024-06-16 | Fluxo             | L   | 0.899      | -            | -                | -                | -         |   -22.20 | biguzera, kauez, lux, nqz, snow   |
|           74 |      870 | 2024-06-15 | 9z                | L   | 0.893      | -            | -                | -                | -         |   -10.54 | biguzera, kauez, lux, nqz, snow   |
|           73 |      885 | 2024-06-15 | ODDIK             | W   | 0.892      | 0.450        | -                | 0.781 (0.314)    | -         |     2.54 | biguzera, kauez, lux, nqz, snow   |
|           72 |      902 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.888      | -            | -                | -                | -         |    -6.48 | biguzera, kauez, lux, nqz, snow   |
|           71 |      920 | 2024-06-14 | BESTIA            | W   | 0.886      | 0.548        | 0.095 (0.046)    | 0.731 (0.355)    | 1 (0.886) |     3.83 | biguzera, kauez, lux, nqz, snow   |
|           70 |      945 | 2024-06-13 | KRÜ               | W   | 0.880      | -            | -                | -                | -         |     1.63 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1019 | 2024-06-10 | BESTIA            | W   | 0.861      | -            | -                | -                | -         |     3.90 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1032 | 2024-06-10 | Imperial          | W   | 0.858      | 0.371        | 0.243 (0.077)    | -                | -         |    11.79 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1062 | 2024-06-09 | Sharks            | W   | 0.853      | -            | -                | -                | -         |     4.12 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1116 | 2024-06-08 | Hype              | W   | 0.847      | -            | -                | -                | -         |     1.99 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1146 | 2024-06-08 | Dusty Roots       | W   | 0.845      | -            | -                | -                | -         |     1.45 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1173 | 2024-06-07 | Patins da Ferrari | W   | 0.841      | -            | -                | -                | -         |     1.21 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1224 | 2024-06-06 | Galorys           | W   | 0.835      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1234 | 2024-06-06 | Sharks            | L   | 0.834      | -            | -                | -                | -         |   -22.53 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1300 | 2024-06-05 | Fluxo             | W   | 0.827      | 0.450        | 0.126 (0.047)    | 0.685 (0.255)    | -         |     4.33 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1354 | 2024-06-04 | ODDIK             | W   | 0.821      | 0.450        | -                | 0.781 (0.289)    | -         |     2.38 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1679 | 2024-05-22 | MIBR              | L   | 0.733      | -            | -                | -                | -         |    -8.87 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1683 | 2024-05-22 | MIBR              | L   | 0.733      | -            | -                | -                | -         |    -9.44 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1789 | 2024-05-19 | AMKAL             | L   | 0.712      | -            | -                | -                | -         |   -16.64 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1800 | 2024-05-19 | OG                | W   | 0.710      | 0.769        | 0.143 (0.078)    | -                | -         |     3.02 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1814 | 2024-05-18 | AMKAL             | L   | 0.706      | -            | -                | -                | -         |   -17.12 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2038 | 2024-05-12 | 9z                | W   | 0.667      | 0.435        | 0.408 (0.118)    | -                | -         |    14.37 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2071 | 2024-05-11 | BESTIA            | W   | 0.659      | -            | -                | -                | -         |     1.72 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2099 | 2024-05-10 | RED Canids        | W   | 0.652      | -            | -                | -                | -         |     3.48 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2108 | 2024-05-09 | Fluxo             | L   | 0.648      | -            | -                | -                | -         |   -17.58 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2113 | 2024-05-09 | Fluxo             | W   | 0.648      | -            | -                | -                | -         |     2.73 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2133 | 2024-05-08 | RED Canids        | W   | 0.641      | -            | -                | -                | -         |     3.26 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2135 | 2024-05-08 | RED Canids        | L   | 0.641      | -            | -                | -                | -         |   -17.24 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2137 | 2024-05-08 | Galorys           | W   | 0.640      | -            | -                | -                | -         |     0.94 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2140 | 2024-05-08 | Galorys           | W   | 0.639      | -            | -                | -                | -         |     0.95 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2154 | 2024-05-07 | W7M               | W   | 0.633      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2174 | 2024-05-06 | W7M               | W   | 0.626      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2175 | 2024-05-06 | W7M               | W   | 0.626      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2187 | 2024-05-05 | KRÜ               | W   | 0.620      | -            | -                | -                | -         |     0.98 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2412 | 2024-04-25 | Solid             | W   | 0.554      | -            | -                | -                | -         |     0.82 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2414 | 2024-04-25 | Solid             | W   | 0.554      | -            | -                | -                | -         |     0.83 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2433 | 2024-04-24 | ODDIK             | W   | 0.547      | -            | -                | -                | -         |     1.30 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2434 | 2024-04-24 | ODDIK             | L   | 0.547      | -            | -                | -                | -         |   -16.08 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2507 | 2024-04-20 | Imperial          | W   | 0.520      | 0.589        | 0.243 (0.074)    | -                | 1 (0.520) |     5.95 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2516 | 2024-04-20 | MIBR              | W   | 0.519      | 0.589        | 0.200 (0.061)    | -                | 1 (0.519) |     9.43 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2537 | 2024-04-19 | Imperial          | L   | 0.516      | -            | -                | -                | -         |   -10.40 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2538 | 2024-04-19 | MIBR              | L   | 0.515      | -            | -                | -                | -         |    -7.27 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2550 | 2024-04-19 | Imperial          | W   | 0.513      | -            | -                | -                | -         |     5.72 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2564 | 2024-04-19 | MIBR              | W   | 0.512      | 0.589        | 0.200 (0.060)    | -                | 1 (0.512) |     8.96 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2587 | 2024-04-18 | Fluxo             | W   | 0.508      | -            | -                | -                | -         |     2.09 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2591 | 2024-04-18 | MIBR              | L   | 0.507      | -            | -                | -                | -         |    -7.31 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2617 | 2024-04-18 | Monte             | W   | 0.505      | -            | -                | -                | 1 (0.505) |     1.52 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2721 | 2024-04-14 | Imperial          | L   | 0.479      | -            | -                | -                | -         |   -10.03 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2732 | 2024-04-13 | ODDIK             | W   | 0.473      | -            | -                | -                | -         |     0.94 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2765 | 2024-04-11 | MIBR              | L   | 0.461      | -            | -                | -                | -         |    -7.34 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2771 | 2024-04-11 | Sharks            | W   | 0.460      | -            | -                | -                | -         |     1.03 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2777 | 2024-04-11 | Imperial          | W   | 0.459      | -            | -                | -                | -         |     4.72 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2812 | 2024-04-10 | RED Canids        | W   | 0.453      | -            | -                | -                | -         |     1.93 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     2856 | 2024-04-09 | Case              | W   | 0.447      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     2861 | 2024-04-09 | Case              | W   | 0.447      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     2879 | 2024-04-09 | Imperial          | L   | 0.445      | -            | -                | -                | -         |    -9.41 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     2901 | 2024-04-08 | Sharks            | W   | 0.439      | -            | -                | -                | -         |     0.33 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     2931 | 2024-04-07 | MIBR              | L   | 0.434      | -            | -                | -                | -         |    -7.38 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     2935 | 2024-04-07 | Galorys           | W   | 0.433      | -            | -                | -                | -         |     0.61 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     2971 | 2024-04-05 | Sharks            | W   | 0.419      | -            | -                | -                | -         |     0.27 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     2991 | 2024-04-04 | Sharks            | W   | 0.414      | -            | -                | -                | -         |     0.27 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     2998 | 2024-04-04 | Sharks            | W   | 0.414      | -            | -                | -                | -         |     0.27 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3224 | 2024-03-24 | Natus Vincere     | L   | 0.339      | -            | -                | -                | -         |    -0.51 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3235 | 2024-03-23 | HEROIC            | W   | 0.333      | 1.000        | 0.234 (0.078)    | -                | 1 (0.333) |     7.38 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3250 | 2024-03-22 | The MongolZ       | W   | 0.325      | 1.000        | 1.000 (0.325)    | 0.719 (0.234)    | 1 (0.325) |     9.65 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3270 | 2024-03-21 | Virtus.pro        | L   | 0.319      | -            | -                | -                | -         |    -1.60 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3278 | 2024-03-21 | Complexity        | L   | 0.318      | -            | -                | -                | -         |    -2.32 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3315 | 2024-03-19 | SAW               | W   | 0.305      | -            | -                | -                | 1 (0.305) |     2.01 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3330 | 2024-03-18 | ENCE              | W   | 0.298      | -            | -                | -                | 1 (0.298) |     5.33 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3348 | 2024-03-17 | Eternal Fire      | L   | 0.293      | -            | -                | -                | -         |    -1.42 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3358 | 2024-03-17 | Apeks             | W   | 0.291      | -            | -                | -                | 1 (0.291) |     0.54 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3688 | 2024-03-04 | ODDIK             | W   | 0.205      | -            | -                | -                | -         |     0.55 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3709 | 2024-03-03 | Imperial          | L   | 0.199      | -            | -                | -                | -         |    -4.29 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3736 | 2024-03-02 | RED Canids        | W   | 0.192      | -            | -                | -                | -         |     0.78 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3750 | 2024-03-01 | Legacy            | W   | 0.187      | -            | -                | -                | -         |     0.50 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($110,335.86)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.33) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.901 | $1,500.00      | $1,351.37       |
| 2024-06-16 |      0.899 | $10,000.00     | $8,993.38       |
| 2024-06-10 |      0.861 | $10,000.00     | $8,606.11       |
| 2024-06-09 |      0.853 | $3,000.00      | $2,560.24       |
| 2024-05-12 |      0.667 | $25,000.00     | $16,664.00      |
| 2024-04-20 |      0.520 | $100,000.00    | $52,007.87      |
| 2024-04-15 |      0.487 | $5,000.00      | $2,432.80       |
| 2024-03-31 |      0.386 | $20,000.00     | $7,720.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
