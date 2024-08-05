### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1424.3<br />
<br />
Final Rank Value (1424.3) = Starting Rank Value (1406.7) + Head To Head Adjustments (17.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.672[<sup>1</sup>](#table2)
- Bounty Collected: 0.492[<sup>2</sup>](#table1)
- Opponent Network: 0.322[<sup>2</sup>](#table1)
- LAN Wins: 0.481[<sup>2</sup>](#table1)

The average of these factors is 0.492<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1406.7
- 400 + ( ( 0.492 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1406.7


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
|          103 |       42 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.83 | biguzera, kauez, lux, nqz, snow   |
|          102 |       54 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.07 | biguzera, kauez, lux, nqz, snow   |
|          101 |       76 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.208 (0.077)    | -                | -         |    11.98 | biguzera, kauez, lux, nqz, snow   |
|          100 |       80 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.80 | biguzera, kauez, lux, nqz, snow   |
|           99 |       95 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.51 | biguzera, kauez, lux, nqz, snow   |
|           98 |      133 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.47 | biguzera, kauez, lux, nqz, snow   |
|           97 |      162 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.11 | biguzera, kauez, lux, nqz, snow   |
|           96 |      183 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.24 | biguzera, kauez, lux, nqz, snow   |
|           95 |      207 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           94 |      211 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, snow   |
|           93 |      226 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.26 | biguzera, kauez, lux, nqz, snow   |
|           92 |      246 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.60 | biguzera, kauez, lux, nqz, snow   |
|           91 |      274 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.51 | biguzera, kauez, lux, nqz, snow   |
|           90 |      280 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.05 | biguzera, kauez, lux, nqz, snow   |
|           89 |      495 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.54 | biguzera, kauez, lux, nqz, snow   |
|           88 |      502 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.49 | biguzera, kauez, lux, nqz, snow   |
|           87 |      528 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.92 | biguzera, kauez, lux, nqz, snow   |
|           86 |      541 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.08 | biguzera, kauez, lux, nqz, snow   |
|           85 |      561 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.78 | biguzera, kauez, lux, nqz, snow   |
|           84 |      571 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.62 | biguzera, kauez, lux, nqz, snow   |
|           83 |      602 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.29 | biguzera, kauez, lux, nqz, snow   |
|           82 |      604 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.31 | biguzera, kauez, lux, nqz, snow   |
|           81 |      670 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.805 (0.362)    | -         |     2.35 | biguzera, kauez, lux, nqz, snow   |
|           80 |      673 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.805 (0.362)    | -         |     2.40 | biguzera, kauez, lux, nqz, snow   |
|           79 |      696 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.48 | biguzera, kauez, lux, nqz, snow   |
|           78 |      732 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.550 (0.247)    | -         |     1.63 | biguzera, kauez, lux, nqz, snow   |
|           77 |      775 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.835 (0.376)    | -         |     1.93 | biguzera, kauez, lux, nqz, snow   |
|           76 |      779 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.835 (0.376)    | -         |     1.97 | biguzera, kauez, lux, nqz, snow   |
|           75 |     1009 | 2024-06-16 | Fluxo             | L   | 0.868      | -            | -                | -                | -         |   -21.25 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1036 | 2024-06-15 | 9z                | L   | 0.862      | -            | -                | -                | -         |   -10.10 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1051 | 2024-06-15 | ODDIK             | W   | 0.861      | 0.450        | -                | 0.832 (0.322)    | -         |     2.62 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1068 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.857      | -            | -                | -                | -         |    -5.33 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1086 | 2024-06-14 | BESTIA            | W   | 0.854      | 0.548        | -                | 0.801 (0.375)    | 1 (0.854) |     3.90 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1111 | 2024-06-13 | KRÜ               | W   | 0.849      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1185 | 2024-06-10 | BESTIA            | W   | 0.829      | 0.371        | -                | 0.801 (0.246)    | -         |     3.96 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1198 | 2024-06-10 | Imperial          | W   | 0.827      | 0.371        | 0.235 (0.072)    | -                | -         |    11.17 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1228 | 2024-06-09 | Sharks            | W   | 0.821      | -            | -                | -                | -         |     4.15 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1282 | 2024-06-08 | Hype              | W   | 0.816      | -            | -                | -                | -         |     2.08 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1312 | 2024-06-08 | Dusty Roots       | W   | 0.814      | -            | -                | -                | -         |     1.56 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1339 | 2024-06-07 | Patins da Ferrari | W   | 0.809      | -            | -                | -                | -         |     1.24 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1390 | 2024-06-06 | Galorys           | W   | 0.803      | -            | -                | -                | -         |     1.85 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1400 | 2024-06-06 | Sharks            | L   | 0.802      | -            | -                | -                | -         |   -21.50 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1466 | 2024-06-05 | Fluxo             | W   | 0.796      | 0.450        | -                | 0.724 (0.259)    | -         |     4.41 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1520 | 2024-06-04 | ODDIK             | W   | 0.789      | 0.450        | -                | 0.832 (0.295)    | -         |     2.48 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1845 | 2024-05-22 | MIBR              | L   | 0.702      | -            | -                | -                | -         |    -8.44 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1849 | 2024-05-22 | MIBR              | L   | 0.701      | -            | -                | -                | -         |    -8.95 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1955 | 2024-05-19 | AMKAL             | L   | 0.681      | -            | -                | -                | -         |   -15.81 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1966 | 2024-05-19 | OG                | W   | 0.679      | 0.769        | 0.138 (0.072)    | -                | -         |     2.87 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1980 | 2024-05-18 | AMKAL             | L   | 0.675      | -            | -                | -                | -         |   -16.28 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2204 | 2024-05-12 | 9z                | W   | 0.635      | 0.435        | 0.405 (0.112)    | -                | -         |    13.68 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2237 | 2024-05-11 | BESTIA            | W   | 0.628      | -            | -                | -                | -         |     1.80 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2265 | 2024-05-10 | RED Canids        | W   | 0.620      | -            | -                | -                | -         |     3.44 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2274 | 2024-05-09 | Fluxo             | L   | 0.617      | -            | -                | -                | -         |   -16.52 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2279 | 2024-05-09 | Fluxo             | W   | 0.616      | -            | -                | -                | -         |     2.82 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2299 | 2024-05-08 | RED Canids        | W   | 0.610      | -            | -                | -                | -         |     3.24 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2301 | 2024-05-08 | RED Canids        | L   | 0.609      | -            | -                | -                | -         |   -16.26 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2303 | 2024-05-08 | Galorys           | W   | 0.608      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2306 | 2024-05-08 | Galorys           | W   | 0.608      | -            | -                | -                | -         |     1.03 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2320 | 2024-05-07 | W7M               | W   | 0.602      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2340 | 2024-05-06 | W7M               | W   | 0.595      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2341 | 2024-05-06 | W7M               | W   | 0.595      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2353 | 2024-05-05 | KRÜ               | W   | 0.589      | -            | -                | -                | -         |     1.09 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2578 | 2024-04-25 | Solid             | W   | 0.523      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2580 | 2024-04-25 | Solid             | W   | 0.522      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2599 | 2024-04-24 | ODDIK             | W   | 0.516      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2600 | 2024-04-24 | ODDIK             | L   | 0.516      | -            | -                | -                | -         |   -15.03 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2673 | 2024-04-20 | Imperial          | W   | 0.489      | 0.589        | 0.235 (0.068)    | -                | 1 (0.489) |     5.47 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2682 | 2024-04-20 | MIBR              | W   | 0.488      | 0.589        | 0.208 (0.060)    | -                | 1 (0.488) |     8.96 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2703 | 2024-04-19 | Imperial          | L   | 0.484      | -            | -                | -                | -         |    -9.90 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2704 | 2024-04-19 | MIBR              | L   | 0.484      | -            | -                | -                | -         |    -6.71 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2716 | 2024-04-19 | Imperial          | W   | 0.482      | -            | -                | -                | -         |     5.25 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2730 | 2024-04-19 | MIBR              | W   | 0.481      | 0.589        | 0.208 (0.059)    | -                | 1 (0.481) |     8.54 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2753 | 2024-04-18 | Fluxo             | W   | 0.477      | -            | -                | -                | -         |     2.15 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2757 | 2024-04-18 | MIBR              | L   | 0.476      | -            | -                | -                | -         |    -6.72 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2783 | 2024-04-18 | Monte             | W   | 0.474      | -            | -                | -                | 1 (0.474) |     1.41 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2887 | 2024-04-14 | Imperial          | L   | 0.448      | -            | -                | -                | -         |    -9.48 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2898 | 2024-04-13 | ODDIK             | W   | 0.442      | -            | -                | -                | -         |     0.99 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2931 | 2024-04-11 | MIBR              | L   | 0.430      | -            | -                | -                | -         |    -6.66 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2937 | 2024-04-11 | Sharks            | W   | 0.429      | -            | -                | -                | -         |     1.08 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2943 | 2024-04-11 | Imperial          | W   | 0.428      | -            | -                | -                | -         |     4.31 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2978 | 2024-04-10 | RED Canids        | W   | 0.422      | -            | -                | -                | -         |     1.91 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     3022 | 2024-04-09 | Case              | W   | 0.416      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     3027 | 2024-04-09 | Case              | W   | 0.416      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3045 | 2024-04-09 | Imperial          | L   | 0.414      | -            | -                | -                | -         |    -8.86 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3067 | 2024-04-08 | Sharks            | W   | 0.408      | -            | -                | -                | -         |     0.34 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3097 | 2024-04-07 | MIBR              | L   | 0.403      | -            | -                | -                | -         |    -6.64 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3101 | 2024-04-07 | Galorys           | W   | 0.402      | -            | -                | -                | -         |     0.66 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3137 | 2024-04-05 | Sharks            | W   | 0.388      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3157 | 2024-04-04 | Sharks            | W   | 0.383      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3164 | 2024-04-04 | Sharks            | W   | 0.383      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3390 | 2024-03-24 | Natus Vincere     | L   | 0.308      | -            | -                | -                | -         |    -0.44 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3401 | 2024-03-23 | HEROIC            | W   | 0.302      | 1.000        | 0.225 (0.068)    | -                | 1 (0.302) |     6.61 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3416 | 2024-03-22 | The MongolZ       | W   | 0.294      | 1.000        | 1.000 (0.294)    | -                | 1 (0.294) |     8.77 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3436 | 2024-03-21 | Virtus.pro        | L   | 0.288      | -            | -                | -                | -         |    -1.50 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3444 | 2024-03-21 | Complexity        | L   | 0.287      | -            | -                | -                | -         |    -1.90 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3481 | 2024-03-19 | SAW               | W   | 0.274      | -            | -                | -                | 1 (0.274) |     1.83 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3496 | 2024-03-18 | ENCE              | W   | 0.266      | -            | -                | -                | 1 (0.266) |     4.86 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3514 | 2024-03-17 | Eternal Fire      | L   | 0.261      | -            | -                | -                | -         |    -1.31 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3524 | 2024-03-17 | Apeks             | W   | 0.260      | -            | -                | -                | 1 (0.260) |     0.47 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3854 | 2024-03-04 | ODDIK             | W   | 0.174      | -            | -                | -                | -         |     0.52 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3875 | 2024-03-03 | Imperial          | L   | 0.168      | -            | -                | -                | -         |    -3.67 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3902 | 2024-03-02 | RED Canids        | W   | 0.161      | -            | -                | -                | -         |     0.69 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3916 | 2024-03-01 | Legacy            | W   | 0.156      | -            | -                | -                | -         |     0.48 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($104,877.08)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.33) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.870 | $1,500.00      | $1,304.44       |
| 2024-06-16 |      0.868 | $10,000.00     | $8,680.56       |
| 2024-06-10 |      0.829 | $10,000.00     | $8,293.29       |
| 2024-06-09 |      0.822 | $3,000.00      | $2,466.39       |
| 2024-05-12 |      0.635 | $25,000.00     | $15,881.94      |
| 2024-04-20 |      0.489 | $100,000.00    | $48,879.63      |
| 2024-04-15 |      0.455 | $5,000.00      | $2,276.39       |
| 2024-03-31 |      0.355 | $20,000.00     | $7,094.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
