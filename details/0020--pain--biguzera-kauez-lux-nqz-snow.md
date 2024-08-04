### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1425.5<br />
<br />
Final Rank Value (1425.5) = Starting Rank Value (1410.7) + Head To Head Adjustments (14.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.673[<sup>1</sup>](#table2)
- Bounty Collected: 0.494[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.487[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1410.7
- 400 + ( ( 0.494 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1410.7


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
|          103 |        2 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.83 | biguzera, kauez, lux, nqz, snow   |
|          102 |        7 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.06 | biguzera, kauez, lux, nqz, snow   |
|          101 |       29 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.209 (0.078)    | -                | -         |    11.96 | biguzera, kauez, lux, nqz, snow   |
|          100 |       34 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.80 | biguzera, kauez, lux, nqz, snow   |
|           99 |       48 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.50 | biguzera, kauez, lux, nqz, snow   |
|           98 |       85 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.46 | biguzera, kauez, lux, nqz, snow   |
|           97 |      113 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.09 | biguzera, kauez, lux, nqz, snow   |
|           96 |      135 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.23 | biguzera, kauez, lux, nqz, snow   |
|           95 |      158 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           94 |      162 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           93 |      177 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.25 | biguzera, kauez, lux, nqz, snow   |
|           92 |      197 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.62 | biguzera, kauez, lux, nqz, snow   |
|           91 |      225 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.53 | biguzera, kauez, lux, nqz, snow   |
|           90 |      231 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.04 | biguzera, kauez, lux, nqz, snow   |
|           89 |      446 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.55 | biguzera, kauez, lux, nqz, snow   |
|           88 |      453 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.48 | biguzera, kauez, lux, nqz, snow   |
|           87 |      479 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.95 | biguzera, kauez, lux, nqz, snow   |
|           86 |      492 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.07 | biguzera, kauez, lux, nqz, snow   |
|           85 |      512 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.77 | biguzera, kauez, lux, nqz, snow   |
|           84 |      523 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.61 | biguzera, kauez, lux, nqz, snow   |
|           83 |      553 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.28 | biguzera, kauez, lux, nqz, snow   |
|           82 |      555 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.29 | biguzera, kauez, lux, nqz, snow   |
|           81 |      621 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.805 (0.362)    | -         |     2.33 | biguzera, kauez, lux, nqz, snow   |
|           80 |      624 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.805 (0.362)    | -         |     2.39 | biguzera, kauez, lux, nqz, snow   |
|           79 |      647 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.47 | biguzera, kauez, lux, nqz, snow   |
|           78 |      683 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.61 | biguzera, kauez, lux, nqz, snow   |
|           77 |      726 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.835 (0.376)    | -         |     1.92 | biguzera, kauez, lux, nqz, snow   |
|           76 |      730 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.835 (0.376)    | -         |     1.96 | biguzera, kauez, lux, nqz, snow   |
|           75 |      960 | 2024-06-16 | Fluxo             | L   | 0.876      | -            | -                | -                | -         |   -21.43 | biguzera, kauez, lux, nqz, snow   |
|           74 |      987 | 2024-06-15 | 9z                | L   | 0.870      | -            | -                | -                | -         |   -10.33 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1002 | 2024-06-15 | ODDIK             | W   | 0.868      | 0.450        | -                | 0.831 (0.325)    | -         |     2.62 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1019 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.864      | -            | -                | -                | -         |    -5.72 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1037 | 2024-06-14 | BESTIA            | W   | 0.862      | 0.548        | -                | 0.801 (0.378)    | 1 (0.862) |     3.90 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1062 | 2024-06-13 | KRÜ               | W   | 0.856      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1136 | 2024-06-10 | BESTIA            | W   | 0.837      | 0.371        | -                | 0.801 (0.248)    | -         |     3.97 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1149 | 2024-06-10 | Imperial          | W   | 0.835      | 0.371        | 0.237 (0.073)    | -                | -         |    11.30 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1179 | 2024-06-09 | Sharks            | W   | 0.829      | -            | -                | -                | -         |     4.17 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1233 | 2024-06-08 | Hype              | W   | 0.824      | -            | -                | -                | -         |     2.07 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1263 | 2024-06-08 | Dusty Roots       | W   | 0.821      | -            | -                | -                | -         |     1.56 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1290 | 2024-06-07 | Patins da Ferrari | W   | 0.817      | -            | -                | -                | -         |     1.24 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1341 | 2024-06-06 | Galorys           | W   | 0.811      | -            | -                | -                | -         |     1.85 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1351 | 2024-06-06 | Sharks            | L   | 0.810      | -            | -                | -                | -         |   -21.72 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1417 | 2024-06-05 | Fluxo             | W   | 0.803      | 0.450        | -                | 0.723 (0.261)    | -         |     4.42 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1471 | 2024-06-04 | ODDIK             | W   | 0.797      | 0.450        | -                | 0.831 (0.298)    | -         |     2.48 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1796 | 2024-05-22 | MIBR              | L   | 0.709      | -            | -                | -                | -         |    -8.53 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1800 | 2024-05-22 | MIBR              | L   | 0.709      | -            | -                | -                | -         |    -9.06 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1906 | 2024-05-19 | AMKAL             | L   | 0.688      | -            | -                | -                | -         |   -16.02 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1917 | 2024-05-19 | OG                | W   | 0.687      | 0.769        | 0.139 (0.073)    | -                | -         |     2.88 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1931 | 2024-05-18 | AMKAL             | L   | 0.682      | -            | -                | -                | -         |   -16.47 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2155 | 2024-05-12 | 9z                | W   | 0.643      | 0.435        | 0.406 (0.113)    | -                | -         |    13.77 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2188 | 2024-05-11 | BESTIA            | W   | 0.635      | -            | -                | -                | -         |     1.79 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2216 | 2024-05-10 | RED Canids        | W   | 0.628      | -            | -                | -                | -         |     3.47 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2225 | 2024-05-09 | Fluxo             | L   | 0.624      | -            | -                | -                | -         |   -16.75 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2230 | 2024-05-09 | Fluxo             | W   | 0.624      | -            | -                | -                | -         |     2.82 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2250 | 2024-05-08 | RED Canids        | W   | 0.617      | -            | -                | -                | -         |     3.26 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2252 | 2024-05-08 | RED Canids        | L   | 0.617      | -            | -                | -                | -         |   -16.48 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2254 | 2024-05-08 | Galorys           | W   | 0.616      | -            | -                | -                | -         |     1.01 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2257 | 2024-05-08 | Galorys           | W   | 0.616      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2271 | 2024-05-07 | W7M               | W   | 0.609      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2291 | 2024-05-06 | W7M               | W   | 0.603      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2292 | 2024-05-06 | W7M               | W   | 0.602      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2304 | 2024-05-05 | KRÜ               | W   | 0.596      | -            | -                | -                | -         |     1.09 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2529 | 2024-04-25 | Solid             | W   | 0.530      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2531 | 2024-04-25 | Solid             | W   | 0.530      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2550 | 2024-04-24 | ODDIK             | W   | 0.524      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2551 | 2024-04-24 | ODDIK             | L   | 0.523      | -            | -                | -                | -         |   -15.27 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2624 | 2024-04-20 | Imperial          | W   | 0.496      | 0.589        | 0.237 (0.069)    | -                | 1 (0.496) |     5.57 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2633 | 2024-04-20 | MIBR              | W   | 0.495      | 0.589        | 0.209 (0.061)    | -                | 1 (0.495) |     9.09 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2654 | 2024-04-19 | Imperial          | L   | 0.492      | -            | -                | -                | -         |   -10.03 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2655 | 2024-04-19 | MIBR              | L   | 0.491      | -            | -                | -                | -         |    -6.82 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2667 | 2024-04-19 | Imperial          | W   | 0.489      | -            | -                | -                | -         |     5.36 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2681 | 2024-04-19 | MIBR              | W   | 0.489      | 0.589        | 0.209 (0.060)    | -                | 1 (0.489) |     8.67 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2704 | 2024-04-18 | Fluxo             | W   | 0.484      | -            | -                | -                | -         |     2.16 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2708 | 2024-04-18 | MIBR              | L   | 0.483      | -            | -                | -                | -         |    -6.83 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2734 | 2024-04-18 | Monte             | W   | 0.481      | -            | -                | -                | 1 (0.481) |     1.44 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2838 | 2024-04-14 | Imperial          | L   | 0.455      | -            | -                | -                | -         |    -9.63 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2849 | 2024-04-13 | ODDIK             | W   | 0.449      | -            | -                | -                | -         |     0.99 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2882 | 2024-04-11 | MIBR              | L   | 0.437      | -            | -                | -                | -         |    -6.80 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2888 | 2024-04-11 | Sharks            | W   | 0.436      | -            | -                | -                | -         |     1.08 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2894 | 2024-04-11 | Imperial          | W   | 0.435      | -            | -                | -                | -         |     4.40 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2929 | 2024-04-10 | RED Canids        | W   | 0.429      | -            | -                | -                | -         |     1.93 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     2973 | 2024-04-09 | Case              | W   | 0.424      | -            | -                | -                | -         |     0.74 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     2978 | 2024-04-09 | Case              | W   | 0.423      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     2996 | 2024-04-09 | Imperial          | L   | 0.422      | -            | -                | -                | -         |    -9.01 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3018 | 2024-04-08 | Sharks            | W   | 0.416      | -            | -                | -                | -         |     0.34 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3048 | 2024-04-07 | MIBR              | L   | 0.411      | -            | -                | -                | -         |    -6.79 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3052 | 2024-04-07 | Galorys           | W   | 0.409      | -            | -                | -                | -         |     0.66 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3088 | 2024-04-05 | Sharks            | W   | 0.395      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3108 | 2024-04-04 | Sharks            | W   | 0.390      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3115 | 2024-04-04 | Sharks            | W   | 0.390      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3341 | 2024-03-24 | Natus Vincere     | L   | 0.316      | -            | -                | -                | -         |    -0.47 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3352 | 2024-03-23 | HEROIC            | W   | 0.309      | 1.000        | 0.229 (0.071)    | -                | 1 (0.309) |     6.72 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3367 | 2024-03-22 | The MongolZ       | W   | 0.301      | 1.000        | 1.000 (0.301)    | -                | 1 (0.301) |     8.97 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3387 | 2024-03-21 | Virtus.pro        | L   | 0.296      | -            | -                | -                | -         |    -1.57 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3395 | 2024-03-21 | Complexity        | L   | 0.294      | -            | -                | -                | -         |    -2.06 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3432 | 2024-03-19 | SAW               | W   | 0.281      | -            | -                | -                | 1 (0.281) |     1.85 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3447 | 2024-03-18 | ENCE              | W   | 0.274      | -            | -                | -                | 1 (0.274) |     4.85 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3465 | 2024-03-17 | Eternal Fire      | L   | 0.269      | -            | -                | -                | -         |    -1.37 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3475 | 2024-03-17 | Apeks             | W   | 0.268      | -            | -                | -                | 1 (0.268) |     0.48 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3805 | 2024-03-04 | ODDIK             | W   | 0.182      | -            | -                | -                | -         |     0.53 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3826 | 2024-03-03 | Imperial          | L   | 0.176      | -            | -                | -                | -         |    -3.83 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3853 | 2024-03-02 | RED Canids        | W   | 0.168      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3867 | 2024-03-01 | Legacy            | W   | 0.163      | -            | -                | -                | -         |     0.49 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($106,185.83)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.33) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.877 | $1,500.00      | $1,315.69       |
| 2024-06-16 |      0.876 | $10,000.00     | $8,755.56       |
| 2024-06-10 |      0.837 | $10,000.00     | $8,368.29       |
| 2024-06-09 |      0.830 | $3,000.00      | $2,488.89       |
| 2024-05-12 |      0.643 | $25,000.00     | $16,069.44      |
| 2024-04-20 |      0.496 | $100,000.00    | $49,629.63      |
| 2024-04-15 |      0.463 | $5,000.00      | $2,313.89       |
| 2024-03-31 |      0.362 | $20,000.00     | $7,244.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
