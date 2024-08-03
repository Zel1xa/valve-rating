### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1400.1<br />
<br />
Final Rank Value (1400.1) = Starting Rank Value (1363.7) + Head To Head Adjustments (36.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.672[<sup>1</sup>](#table2)
- Bounty Collected: 0.487[<sup>2</sup>](#table1)
- Opponent Network: 0.312[<sup>2</sup>](#table1)
- LAN Wins: 0.413[<sup>2</sup>](#table1)

The average of these factors is 0.471<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1363.7
- 400 + ( ( 0.471 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1363.7


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
|           98 |        2 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     3.97 | biguzera, kauez, lux, nqz, snow   |
|           97 |       22 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.210 (0.078)    | 0.682 (0.253)    | -         |    12.24 | biguzera, kauez, lux, nqz, snow   |
|           96 |       24 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.663 (0.246)    | -         |     5.43 | biguzera, kauez, lux, nqz, snow   |
|           95 |       38 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.60 | biguzera, kauez, lux, nqz, snow   |
|           94 |       61 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.57 | biguzera, kauez, lux, nqz, snow   |
|           93 |       88 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.00 | biguzera, kauez, lux, nqz, snow   |
|           92 |      109 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.31 | biguzera, kauez, lux, nqz, snow   |
|           91 |      132 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.78 | biguzera, kauez, lux, nqz, snow   |
|           90 |      136 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.79 | biguzera, kauez, lux, nqz, snow   |
|           89 |      151 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.42 | biguzera, kauez, lux, nqz, snow   |
|           88 |      171 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.82 | biguzera, kauez, lux, nqz, snow   |
|           87 |      199 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.73 | biguzera, kauez, lux, nqz, snow   |
|           86 |      205 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     7.26 | biguzera, kauez, lux, nqz, snow   |
|           85 |      420 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.41 | biguzera, kauez, lux, nqz, snow   |
|           84 |      427 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.61 | biguzera, kauez, lux, nqz, snow   |
|           83 |      453 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.09 | biguzera, kauez, lux, nqz, snow   |
|           82 |      466 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.30 | biguzera, kauez, lux, nqz, snow   |
|           81 |      486 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.94 | biguzera, kauez, lux, nqz, snow   |
|           80 |      496 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           79 |      527 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.38 | biguzera, kauez, lux, nqz, snow   |
|           78 |      529 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.40 | biguzera, kauez, lux, nqz, snow   |
|           77 |      595 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.750 (0.337)    | -         |     2.60 | biguzera, kauez, lux, nqz, snow   |
|           76 |      598 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.750 (0.337)    | -         |     2.67 | biguzera, kauez, lux, nqz, snow   |
|           75 |      620 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.59 | biguzera, kauez, lux, nqz, snow   |
|           74 |      654 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.571 (0.257)    | -         |     1.69 | biguzera, kauez, lux, nqz, snow   |
|           73 |      697 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.863 (0.388)    | -         |     2.19 | biguzera, kauez, lux, nqz, snow   |
|           72 |      701 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.863 (0.388)    | -         |     2.25 | biguzera, kauez, lux, nqz, snow   |
|           71 |      920 | 2024-06-16 | Fluxo             | L   | 0.880      | -            | -                | -                | -         |   -21.39 | biguzera, kauez, lux, nqz, snow   |
|           70 |      955 | 2024-06-15 | ODDIK             | W   | 0.873      | 0.450        | -                | 0.857 (0.337)    | -         |     2.94 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1008 | 2024-06-13 | KRÜ               | W   | 0.861      | -            | -                | -                | -         |     2.21 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1078 | 2024-06-10 | BESTIA            | W   | 0.842      | -            | -                | -                | -         |     4.24 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1091 | 2024-06-10 | Imperial          | W   | 0.839      | 0.371        | 0.234 (0.073)    | -                | -         |    10.97 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1120 | 2024-06-09 | Sharks            | W   | 0.834      | -            | -                | -                | -         |     4.61 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1200 | 2024-06-08 | Dusty Roots       | W   | 0.826      | -            | -                | -                | -         |     1.81 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1226 | 2024-06-07 | Patins da Ferrari | W   | 0.822      | -            | -                | -                | -         |     1.51 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1277 | 2024-06-06 | Galorys           | W   | 0.816      | -            | -                | -                | -         |     2.23 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1287 | 2024-06-06 | Sharks            | L   | 0.815      | -            | -                | -                | -         |   -21.41 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1353 | 2024-06-05 | Fluxo             | W   | 0.808      | 0.450        | 0.125 (0.045)    | 0.746 (0.271)    | -         |     4.80 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1407 | 2024-06-04 | ODDIK             | W   | 0.802      | 0.450        | -                | 0.857 (0.309)    | -         |     2.82 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1728 | 2024-05-22 | MIBR              | L   | 0.714      | -            | -                | -                | -         |    -7.59 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1732 | 2024-05-22 | MIBR              | L   | 0.714      | -            | -                | -                | -         |    -8.04 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1837 | 2024-05-19 | AMKAL             | L   | 0.693      | -            | -                | -                | -         |   -15.15 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1848 | 2024-05-19 | OG                | W   | 0.691      | 0.769        | 0.140 (0.074)    | -                | -         |     3.38 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1862 | 2024-05-18 | AMKAL             | L   | 0.687      | -            | -                | -                | -         |   -15.63 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2086 | 2024-05-12 | 9z                | W   | 0.648      | -            | -                | -                | -         |     6.80 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2119 | 2024-05-11 | BESTIA            | W   | 0.640      | -            | -                | -                | -         |     2.02 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2147 | 2024-05-10 | RED Canids        | W   | 0.633      | -            | -                | -                | -         |     3.13 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2156 | 2024-05-09 | Fluxo             | L   | 0.629      | -            | -                | -                | -         |   -16.45 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2161 | 2024-05-09 | Fluxo             | W   | 0.629      | -            | -                | -                | -         |     3.27 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2180 | 2024-05-08 | RED Canids        | W   | 0.622      | -            | -                | -                | -         |     2.93 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2182 | 2024-05-08 | RED Canids        | L   | 0.622      | -            | -                | -                | -         |   -16.95 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2184 | 2024-05-08 | Galorys           | W   | 0.621      | -            | -                | -                | -         |     1.15 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2187 | 2024-05-08 | Galorys           | W   | 0.620      | -            | -                | -                | -         |     1.17 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2201 | 2024-05-07 | W7M               | W   | 0.614      | -            | -                | -                | -         |     0.89 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2221 | 2024-05-06 | W7M               | W   | 0.607      | -            | -                | -                | -         |     0.89 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2222 | 2024-05-06 | W7M               | W   | 0.607      | -            | -                | -                | -         |     0.90 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2234 | 2024-05-05 | KRÜ               | W   | 0.601      | -            | -                | -                | -         |     1.32 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2458 | 2024-04-25 | Solid             | W   | 0.535      | -            | -                | -                | -         |     1.05 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2460 | 2024-04-25 | Solid             | W   | 0.535      | -            | -                | -                | -         |     1.07 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2479 | 2024-04-24 | ODDIK             | W   | 0.528      | -            | -                | -                | -         |     1.57 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2480 | 2024-04-24 | ODDIK             | L   | 0.528      | -            | -                | -                | -         |   -15.23 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2553 | 2024-04-20 | Imperial          | W   | 0.501      | 0.589        | 0.234 (0.069)    | -                | 1 (0.501) |     5.75 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2562 | 2024-04-20 | MIBR              | W   | 0.500      | 0.589        | 0.210 (0.062)    | -                | 1 (0.500) |     9.91 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2583 | 2024-04-19 | Imperial          | L   | 0.497      | -            | -                | -                | -         |    -9.98 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2584 | 2024-04-19 | MIBR              | L   | 0.496      | -            | -                | -                | -         |    -6.12 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2596 | 2024-04-19 | Imperial          | W   | 0.494      | -            | -                | -                | -         |     5.58 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2610 | 2024-04-19 | MIBR              | W   | 0.493      | 0.589        | 0.210 (0.061)    | -                | 1 (0.493) |     9.55 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2633 | 2024-04-18 | Fluxo             | W   | 0.489      | -            | -                | -                | -         |     2.56 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2637 | 2024-04-18 | MIBR              | L   | 0.488      | -            | -                | -                | -         |    -6.05 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2663 | 2024-04-18 | Monte             | W   | 0.486      | -            | -                | -                | 1 (0.486) |     1.81 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2767 | 2024-04-14 | Imperial          | L   | 0.460      | -            | -                | -                | -         |    -9.46 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2778 | 2024-04-13 | ODDIK             | W   | 0.454      | -            | -                | -                | -         |     1.17 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2811 | 2024-04-11 | MIBR              | L   | 0.442      | -            | -                | -                | -         |    -6.02 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2817 | 2024-04-11 | Sharks            | W   | 0.441      | -            | -                | -                | -         |     1.34 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2823 | 2024-04-11 | Imperial          | W   | 0.440      | -            | -                | -                | -         |     4.74 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2858 | 2024-04-10 | RED Canids        | W   | 0.434      | -            | -                | -                | -         |     1.72 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     2902 | 2024-04-09 | Case              | W   | 0.428      | -            | -                | -                | -         |     0.93 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     2907 | 2024-04-09 | Case              | W   | 0.428      | -            | -                | -                | -         |     0.94 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     2925 | 2024-04-09 | Imperial          | L   | 0.426      | -            | -                | -                | -         |    -8.84 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     2947 | 2024-04-08 | Sharks            | W   | 0.420      | -            | -                | -                | -         |     0.43 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     2977 | 2024-04-07 | MIBR              | L   | 0.415      | -            | -                | -                | -         |    -5.99 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     2981 | 2024-04-07 | Galorys           | W   | 0.414      | -            | -                | -                | -         |     0.78 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3017 | 2024-04-05 | Sharks            | W   | 0.400      | -            | -                | -                | -         |     0.36 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3037 | 2024-04-04 | Sharks            | W   | 0.395      | -            | -                | -                | -         |     0.36 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3044 | 2024-04-04 | Sharks            | W   | 0.395      | -            | -                | -                | -         |     0.36 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3267 | 2024-03-24 | Natus Vincere     | L   | 0.320      | -            | -                | -                | -         |    -0.37 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3277 | 2024-03-23 | HEROIC            | W   | 0.314      | 1.000        | 0.230 (0.072)    | -                | 1 (0.314) |     7.37 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3291 | 2024-03-22 | The MongolZ       | W   | 0.306      | 1.000        | 1.000 (0.306)    | -                | 1 (0.306) |     9.23 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3311 | 2024-03-21 | Virtus.pro        | L   | 0.300      | -            | -                | -                | -         |    -1.26 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3319 | 2024-03-21 | Complexity        | L   | 0.299      | -            | -                | -                | -         |    -1.66 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3356 | 2024-03-19 | SAW               | W   | 0.286      | -            | -                | -                | 1 (0.286) |     2.33 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3371 | 2024-03-18 | ENCE              | W   | 0.279      | -            | -                | -                | 1 (0.279) |     5.49 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3389 | 2024-03-17 | Eternal Fire      | L   | 0.274      | -            | -                | -                | -         |    -1.09 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3399 | 2024-03-17 | Apeks             | W   | 0.272      | -            | -                | -                | 1 (0.272) |     0.63 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3726 | 2024-03-04 | ODDIK             | W   | 0.186      | -            | -                | -                | 1 (0.186) |     0.67 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3747 | 2024-03-03 | Imperial          | L   | 0.180      | -            | -                | -                | -         |    -3.79 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3774 | 2024-03-02 | RED Canids        | W   | 0.173      | -            | -                | -                | -         |     0.61 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3788 | 2024-03-01 | Legacy            | W   | 0.168      | -            | -                | -                | -         |     0.64 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($105,695.09)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.880 | $10,000.00     | $8,803.24       |
| 2024-06-10 |      0.842 | $10,000.00     | $8,415.97       |
| 2024-06-09 |      0.834 | $3,000.00      | $2,503.19       |
| 2024-05-12 |      0.648 | $25,000.00     | $16,188.66      |
| 2024-04-20 |      0.501 | $100,000.00    | $50,106.48      |
| 2024-04-15 |      0.468 | $5,000.00      | $2,337.73       |
| 2024-03-31 |      0.367 | $20,000.00     | $7,339.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
