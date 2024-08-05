### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1423.5<br />
<br />
Final Rank Value (1423.5) = Starting Rank Value (1405.4) + Head To Head Adjustments (18.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.672[<sup>1</sup>](#table2)
- Bounty Collected: 0.491[<sup>2</sup>](#table1)
- Opponent Network: 0.318[<sup>2</sup>](#table1)
- LAN Wins: 0.480[<sup>2</sup>](#table1)

The average of these factors is 0.490<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1405.4
- 400 + ( ( 0.490 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1405.4


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
|          103 |       50 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.84 | biguzera, kauez, lux, nqz, snow   |
|          102 |       62 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.08 | biguzera, kauez, lux, nqz, snow   |
|          101 |       84 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.208 (0.077)    | -                | -         |    11.98 | biguzera, kauez, lux, nqz, snow   |
|          100 |       88 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.81 | biguzera, kauez, lux, nqz, snow   |
|           99 |      103 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.51 | biguzera, kauez, lux, nqz, snow   |
|           98 |      141 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.48 | biguzera, kauez, lux, nqz, snow   |
|           97 |      170 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.11 | biguzera, kauez, lux, nqz, snow   |
|           96 |      191 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.24 | biguzera, kauez, lux, nqz, snow   |
|           95 |      215 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, snow   |
|           94 |      219 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, snow   |
|           93 |      234 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.27 | biguzera, kauez, lux, nqz, snow   |
|           92 |      254 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.60 | biguzera, kauez, lux, nqz, snow   |
|           91 |      282 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.51 | biguzera, kauez, lux, nqz, snow   |
|           90 |      288 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.05 | biguzera, kauez, lux, nqz, snow   |
|           89 |      503 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.54 | biguzera, kauez, lux, nqz, snow   |
|           88 |      510 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.48 | biguzera, kauez, lux, nqz, snow   |
|           87 |      536 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.92 | biguzera, kauez, lux, nqz, snow   |
|           86 |      549 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.09 | biguzera, kauez, lux, nqz, snow   |
|           85 |      569 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.78 | biguzera, kauez, lux, nqz, snow   |
|           84 |      579 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.62 | biguzera, kauez, lux, nqz, snow   |
|           83 |      610 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.29 | biguzera, kauez, lux, nqz, snow   |
|           82 |      612 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.31 | biguzera, kauez, lux, nqz, snow   |
|           81 |      678 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.795 (0.358)    | -         |     2.35 | biguzera, kauez, lux, nqz, snow   |
|           80 |      681 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.795 (0.358)    | -         |     2.41 | biguzera, kauez, lux, nqz, snow   |
|           79 |      704 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.49 | biguzera, kauez, lux, nqz, snow   |
|           78 |      740 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.543 (0.244)    | -         |     1.63 | biguzera, kauez, lux, nqz, snow   |
|           77 |      783 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.825 (0.371)    | -         |     1.94 | biguzera, kauez, lux, nqz, snow   |
|           76 |      787 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.825 (0.371)    | -         |     1.98 | biguzera, kauez, lux, nqz, snow   |
|           75 |     1017 | 2024-06-16 | Fluxo             | L   | 0.867      | -            | -                | -                | -         |   -21.22 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1044 | 2024-06-15 | 9z                | L   | 0.861      | -            | -                | -                | -         |   -10.07 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1059 | 2024-06-15 | ODDIK             | W   | 0.859      | 0.450        | -                | 0.822 (0.318)    | -         |     2.62 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1076 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.856      | -            | -                | -                | -         |    -5.31 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1094 | 2024-06-14 | BESTIA            | W   | 0.853      | 0.548        | -                | 0.792 (0.371)    | 1 (0.853) |     3.90 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1119 | 2024-06-13 | KRÜ               | W   | 0.848      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1193 | 2024-06-10 | BESTIA            | W   | 0.828      | 0.371        | -                | 0.792 (0.243)    | -         |     3.96 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1206 | 2024-06-10 | Imperial          | W   | 0.826      | 0.371        | 0.235 (0.072)    | -                | -         |    11.15 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1236 | 2024-06-09 | Sharks            | W   | 0.820      | -            | -                | -                | -         |     4.15 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1290 | 2024-06-08 | Hype              | W   | 0.815      | -            | -                | -                | -         |     2.08 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1320 | 2024-06-08 | Dusty Roots       | W   | 0.813      | -            | -                | -                | -         |     1.57 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1347 | 2024-06-07 | Patins da Ferrari | W   | 0.808      | -            | -                | -                | -         |     1.25 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1398 | 2024-06-06 | Galorys           | W   | 0.802      | -            | -                | -                | -         |     1.85 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1408 | 2024-06-06 | Sharks            | L   | 0.801      | -            | -                | -                | -         |   -21.48 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1474 | 2024-06-05 | Fluxo             | W   | 0.795      | 0.450        | -                | 0.716 (0.256)    | -         |     4.40 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1528 | 2024-06-04 | ODDIK             | W   | 0.788      | 0.450        | -                | 0.822 (0.292)    | -         |     2.48 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1853 | 2024-05-22 | MIBR              | L   | 0.701      | -            | -                | -                | -         |    -8.42 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1857 | 2024-05-22 | MIBR              | L   | 0.700      | -            | -                | -                | -         |    -8.93 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1963 | 2024-05-19 | AMKAL             | L   | 0.680      | -            | -                | -                | -         |   -15.77 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1974 | 2024-05-19 | OG                | W   | 0.678      | 0.769        | 0.138 (0.072)    | -                | -         |     2.88 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1988 | 2024-05-18 | AMKAL             | L   | 0.673      | -            | -                | -                | -         |   -16.23 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2212 | 2024-05-12 | 9z                | W   | 0.634      | 0.435        | 0.404 (0.111)    | -                | -         |    13.67 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2245 | 2024-05-11 | BESTIA            | W   | 0.627      | -            | -                | -                | -         |     1.80 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2273 | 2024-05-10 | RED Canids        | W   | 0.619      | -            | -                | -                | -         |     3.44 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2282 | 2024-05-09 | Fluxo             | L   | 0.616      | -            | -                | -                | -         |   -16.49 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2287 | 2024-05-09 | Fluxo             | W   | 0.615      | -            | -                | -                | -         |     2.81 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2307 | 2024-05-08 | RED Canids        | W   | 0.609      | -            | -                | -                | -         |     3.24 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2309 | 2024-05-08 | RED Canids        | L   | 0.608      | -            | -                | -                | -         |   -16.23 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2311 | 2024-05-08 | Galorys           | W   | 0.607      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2314 | 2024-05-08 | Galorys           | W   | 0.607      | -            | -                | -                | -         |     1.03 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2328 | 2024-05-07 | W7M               | W   | 0.601      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2348 | 2024-05-06 | W7M               | W   | 0.594      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2349 | 2024-05-06 | W7M               | W   | 0.594      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2361 | 2024-05-05 | KRÜ               | W   | 0.588      | -            | -                | -                | -         |     1.09 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2586 | 2024-04-25 | Solid             | W   | 0.522      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2588 | 2024-04-25 | Solid             | W   | 0.521      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2607 | 2024-04-24 | ODDIK             | W   | 0.515      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2608 | 2024-04-24 | ODDIK             | L   | 0.515      | -            | -                | -                | -         |   -14.99 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2681 | 2024-04-20 | Imperial          | W   | 0.488      | 0.589        | 0.235 (0.067)    | -                | 1 (0.488) |     5.46 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2690 | 2024-04-20 | MIBR              | W   | 0.487      | 0.589        | 0.208 (0.060)    | -                | 1 (0.487) |     8.94 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2711 | 2024-04-19 | Imperial          | L   | 0.483      | -            | -                | -                | -         |    -9.88 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2712 | 2024-04-19 | MIBR              | L   | 0.482      | -            | -                | -                | -         |    -6.70 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2724 | 2024-04-19 | Imperial          | W   | 0.481      | -            | -                | -                | -         |     5.25 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2738 | 2024-04-19 | MIBR              | W   | 0.480      | 0.589        | 0.208 (0.059)    | -                | 1 (0.480) |     8.52 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2761 | 2024-04-18 | Fluxo             | W   | 0.476      | -            | -                | -                | -         |     2.15 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2765 | 2024-04-18 | MIBR              | L   | 0.475      | -            | -                | -                | -         |    -6.70 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2791 | 2024-04-18 | Monte             | W   | 0.473      | -            | -                | -                | 1 (0.473) |     1.41 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2895 | 2024-04-14 | Imperial          | L   | 0.447      | -            | -                | -                | -         |    -9.46 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2906 | 2024-04-13 | ODDIK             | W   | 0.441      | -            | -                | -                | -         |     0.99 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2939 | 2024-04-11 | MIBR              | L   | 0.428      | -            | -                | -                | -         |    -6.64 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2945 | 2024-04-11 | Sharks            | W   | 0.427      | -            | -                | -                | -         |     1.07 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2951 | 2024-04-11 | Imperial          | W   | 0.427      | -            | -                | -                | -         |     4.30 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2986 | 2024-04-10 | RED Canids        | W   | 0.420      | -            | -                | -                | -         |     1.91 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     3030 | 2024-04-09 | Case              | W   | 0.415      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     3035 | 2024-04-09 | Case              | W   | 0.415      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3053 | 2024-04-09 | Imperial          | L   | 0.413      | -            | -                | -                | -         |    -8.84 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3075 | 2024-04-08 | Sharks            | W   | 0.407      | -            | -                | -                | -         |     0.34 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3105 | 2024-04-07 | MIBR              | L   | 0.402      | -            | -                | -                | -         |    -6.61 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3109 | 2024-04-07 | Galorys           | W   | 0.401      | -            | -                | -                | -         |     0.66 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3145 | 2024-04-05 | Sharks            | W   | 0.386      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3165 | 2024-04-04 | Sharks            | W   | 0.382      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3172 | 2024-04-04 | Sharks            | W   | 0.381      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3398 | 2024-03-24 | Natus Vincere     | L   | 0.307      | -            | -                | -                | -         |    -0.44 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3409 | 2024-03-23 | HEROIC            | W   | 0.301      | 1.000        | 0.225 (0.068)    | -                | 1 (0.301) |     6.59 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3424 | 2024-03-22 | The MongolZ       | W   | 0.293      | 1.000        | 1.000 (0.293)    | -                | 1 (0.293) |     8.74 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3444 | 2024-03-21 | Virtus.pro        | L   | 0.287      | -            | -                | -                | -         |    -1.48 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3452 | 2024-03-21 | Complexity        | L   | 0.286      | -            | -                | -                | -         |    -1.88 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3489 | 2024-03-19 | SAW               | W   | 0.273      | -            | -                | -                | 1 (0.273) |     1.82 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3504 | 2024-03-18 | ENCE              | W   | 0.265      | -            | -                | -                | 1 (0.265) |     4.89 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3522 | 2024-03-17 | Eternal Fire      | L   | 0.260      | -            | -                | -                | -         |    -1.29 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3532 | 2024-03-17 | Apeks             | W   | 0.259      | -            | -                | -                | 1 (0.259) |     0.47 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3862 | 2024-03-04 | ODDIK             | W   | 0.173      | -            | -                | -                | -         |     0.52 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3883 | 2024-03-03 | Imperial          | L   | 0.167      | -            | -                | -                | -         |    -3.64 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3910 | 2024-03-02 | RED Canids        | W   | 0.160      | -            | -                | -                | -         |     0.69 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3924 | 2024-03-01 | Legacy            | W   | 0.155      | -            | -                | -                | -         |     0.48 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($104,683.19)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.33) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.869 | $1,500.00      | $1,302.78       |
| 2024-06-16 |      0.867 | $10,000.00     | $8,669.44       |
| 2024-06-10 |      0.828 | $10,000.00     | $8,282.18       |
| 2024-06-09 |      0.821 | $3,000.00      | $2,463.06       |
| 2024-05-12 |      0.634 | $25,000.00     | $15,854.17      |
| 2024-04-20 |      0.488 | $100,000.00    | $48,768.52      |
| 2024-04-15 |      0.454 | $5,000.00      | $2,270.83       |
| 2024-03-31 |      0.354 | $20,000.00     | $7,072.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
