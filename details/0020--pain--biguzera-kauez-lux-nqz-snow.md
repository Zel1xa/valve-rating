### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1426.0<br />
<br />
Final Rank Value (1426.0) = Starting Rank Value (1412.2) + Head To Head Adjustments (13.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.674[<sup>1</sup>](#table2)
- Bounty Collected: 0.495[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.489[<sup>2</sup>](#table1)

The average of these factors is 0.495<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1412.2
- 400 + ( ( 0.495 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1412.2


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
|          103 |        0 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.82 | biguzera, kauez, lux, nqz, snow   |
|          102 |        4 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     3.98 | biguzera, kauez, lux, nqz, snow   |
|          101 |       26 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.210 (0.078)    | -                | -         |    11.95 | biguzera, kauez, lux, nqz, snow   |
|          100 |       32 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.79 | biguzera, kauez, lux, nqz, snow   |
|           99 |       45 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.49 | biguzera, kauez, lux, nqz, snow   |
|           98 |       82 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.45 | biguzera, kauez, lux, nqz, snow   |
|           97 |      110 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.00 | biguzera, kauez, lux, nqz, snow   |
|           96 |      132 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.23 | biguzera, kauez, lux, nqz, snow   |
|           95 |      155 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.70 | biguzera, kauez, lux, nqz, snow   |
|           94 |      159 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           93 |      174 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.24 | biguzera, kauez, lux, nqz, snow   |
|           92 |      194 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.63 | biguzera, kauez, lux, nqz, snow   |
|           91 |      222 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.53 | biguzera, kauez, lux, nqz, snow   |
|           90 |      228 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.03 | biguzera, kauez, lux, nqz, snow   |
|           89 |      443 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.56 | biguzera, kauez, lux, nqz, snow   |
|           88 |      450 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.46 | biguzera, kauez, lux, nqz, snow   |
|           87 |      476 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.96 | biguzera, kauez, lux, nqz, snow   |
|           86 |      489 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.06 | biguzera, kauez, lux, nqz, snow   |
|           85 |      509 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.76 | biguzera, kauez, lux, nqz, snow   |
|           84 |      520 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.60 | biguzera, kauez, lux, nqz, snow   |
|           83 |      550 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.27 | biguzera, kauez, lux, nqz, snow   |
|           82 |      552 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.29 | biguzera, kauez, lux, nqz, snow   |
|           81 |      618 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.804 (0.362)    | -         |     2.31 | biguzera, kauez, lux, nqz, snow   |
|           80 |      621 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.804 (0.362)    | -         |     2.37 | biguzera, kauez, lux, nqz, snow   |
|           79 |      644 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.46 | biguzera, kauez, lux, nqz, snow   |
|           78 |      680 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.61 | biguzera, kauez, lux, nqz, snow   |
|           77 |      723 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.835 (0.376)    | -         |     1.91 | biguzera, kauez, lux, nqz, snow   |
|           76 |      727 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.835 (0.376)    | -         |     1.95 | biguzera, kauez, lux, nqz, snow   |
|           75 |      956 | 2024-06-16 | Fluxo             | L   | 0.879      | -            | -                | -                | -         |   -21.52 | biguzera, kauez, lux, nqz, snow   |
|           74 |      983 | 2024-06-15 | 9z                | L   | 0.873      | -            | -                | -                | -         |   -10.38 | biguzera, kauez, lux, nqz, snow   |
|           73 |      998 | 2024-06-15 | ODDIK             | W   | 0.871      | 0.450        | -                | 0.829 (0.325)    | -         |     2.62 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1015 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.867      | -            | -                | -                | -         |    -5.76 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1033 | 2024-06-14 | BESTIA            | W   | 0.865      | 0.548        | -                | 0.799 (0.379)    | 1 (0.865) |     3.90 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1058 | 2024-06-13 | KRÜ               | W   | 0.859      | -            | -                | -                | -         |     1.74 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1132 | 2024-06-10 | BESTIA            | W   | 0.840      | 0.371        | -                | 0.799 (0.249)    | -         |     3.97 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1145 | 2024-06-10 | Imperial          | W   | 0.838      | 0.371        | 0.238 (0.074)    | -                | -         |    11.35 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1175 | 2024-06-09 | Sharks            | W   | 0.832      | -            | -                | -                | -         |     4.18 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1229 | 2024-06-08 | Hype              | W   | 0.827      | -            | -                | -                | -         |     2.07 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1259 | 2024-06-08 | Dusty Roots       | W   | 0.824      | -            | -                | -                | -         |     1.55 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1286 | 2024-06-07 | Patins da Ferrari | W   | 0.820      | -            | -                | -                | -         |     1.24 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1337 | 2024-06-06 | Galorys           | W   | 0.814      | -            | -                | -                | -         |     1.84 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1347 | 2024-06-06 | Sharks            | L   | 0.813      | -            | -                | -                | -         |   -21.81 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1413 | 2024-06-05 | Fluxo             | W   | 0.806      | 0.450        | -                | 0.722 (0.262)    | -         |     4.42 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1467 | 2024-06-04 | ODDIK             | W   | 0.800      | 0.450        | -                | 0.829 (0.299)    | -         |     2.47 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1792 | 2024-05-22 | MIBR              | L   | 0.712      | -            | -                | -                | -         |    -8.56 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1796 | 2024-05-22 | MIBR              | L   | 0.712      | -            | -                | -                | -         |    -9.10 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1902 | 2024-05-19 | AMKAL             | L   | 0.691      | -            | -                | -                | -         |   -16.09 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1913 | 2024-05-19 | OG                | W   | 0.690      | 0.769        | 0.140 (0.074)    | -                | -         |     2.90 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1927 | 2024-05-18 | AMKAL             | L   | 0.685      | -            | -                | -                | -         |   -16.55 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2151 | 2024-05-12 | 9z                | W   | 0.646      | 0.435        | 0.406 (0.114)    | -                | -         |    13.81 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2184 | 2024-05-11 | BESTIA            | W   | 0.638      | -            | -                | -                | -         |     1.79 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2212 | 2024-05-10 | RED Canids        | W   | 0.631      | -            | -                | -                | -         |     3.48 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2221 | 2024-05-09 | Fluxo             | L   | 0.627      | -            | -                | -                | -         |   -16.84 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2226 | 2024-05-09 | Fluxo             | W   | 0.627      | -            | -                | -                | -         |     2.83 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2246 | 2024-05-08 | RED Canids        | W   | 0.620      | -            | -                | -                | -         |     3.27 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2248 | 2024-05-08 | RED Canids        | L   | 0.620      | -            | -                | -                | -         |   -16.57 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2250 | 2024-05-08 | Galorys           | W   | 0.619      | -            | -                | -                | -         |     1.01 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2253 | 2024-05-08 | Galorys           | W   | 0.619      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2267 | 2024-05-07 | W7M               | W   | 0.613      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2287 | 2024-05-06 | W7M               | W   | 0.606      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2288 | 2024-05-06 | W7M               | W   | 0.605      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2300 | 2024-05-05 | KRÜ               | W   | 0.599      | -            | -                | -                | -         |     1.08 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2524 | 2024-04-25 | Solid             | W   | 0.533      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2526 | 2024-04-25 | Solid             | W   | 0.533      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2545 | 2024-04-24 | ODDIK             | W   | 0.527      | -            | -                | -                | -         |     1.36 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2546 | 2024-04-24 | ODDIK             | L   | 0.526      | -            | -                | -                | -         |   -15.36 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2619 | 2024-04-20 | Imperial          | W   | 0.499      | 0.589        | 0.238 (0.070)    | -                | 1 (0.499) |     5.62 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2628 | 2024-04-20 | MIBR              | W   | 0.498      | 0.589        | 0.210 (0.062)    | -                | 1 (0.498) |     9.15 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2649 | 2024-04-19 | Imperial          | L   | 0.495      | -            | -                | -                | -         |   -10.09 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2650 | 2024-04-19 | MIBR              | L   | 0.494      | -            | -                | -                | -         |    -6.87 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2662 | 2024-04-19 | Imperial          | W   | 0.492      | -            | -                | -                | -         |     5.40 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2676 | 2024-04-19 | MIBR              | W   | 0.492      | 0.589        | 0.210 (0.061)    | -                | 1 (0.492) |     8.72 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2699 | 2024-04-18 | Fluxo             | W   | 0.487      | -            | -                | -                | -         |     2.16 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2703 | 2024-04-18 | MIBR              | L   | 0.486      | -            | -                | -                | -         |    -6.88 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2729 | 2024-04-18 | Monte             | W   | 0.485      | -            | -                | -                | 1 (0.485) |     1.45 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2833 | 2024-04-14 | Imperial          | L   | 0.458      | -            | -                | -                | -         |    -9.69 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2844 | 2024-04-13 | ODDIK             | W   | 0.453      | -            | -                | -                | -         |     0.99 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2877 | 2024-04-11 | MIBR              | L   | 0.440      | -            | -                | -                | -         |    -6.85 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2883 | 2024-04-11 | Sharks            | W   | 0.439      | -            | -                | -                | -         |     1.08 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2889 | 2024-04-11 | Imperial          | W   | 0.438      | -            | -                | -                | -         |     4.43 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2924 | 2024-04-10 | RED Canids        | W   | 0.432      | -            | -                | -                | -         |     1.93 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     2968 | 2024-04-09 | Case              | W   | 0.427      | -            | -                | -                | -         |     0.74 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     2973 | 2024-04-09 | Case              | W   | 0.426      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     2991 | 2024-04-09 | Imperial          | L   | 0.425      | -            | -                | -                | -         |    -9.07 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3013 | 2024-04-08 | Sharks            | W   | 0.419      | -            | -                | -                | -         |     0.34 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3043 | 2024-04-07 | MIBR              | L   | 0.414      | -            | -                | -                | -         |    -6.85 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3047 | 2024-04-07 | Galorys           | W   | 0.412      | -            | -                | -                | -         |     0.65 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3083 | 2024-04-05 | Sharks            | W   | 0.398      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3103 | 2024-04-04 | Sharks            | W   | 0.393      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3110 | 2024-04-04 | Sharks            | W   | 0.393      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3336 | 2024-03-24 | Natus Vincere     | L   | 0.319      | -            | -                | -                | -         |    -0.48 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3347 | 2024-03-23 | HEROIC            | W   | 0.312      | 1.000        | 0.229 (0.072)    | -                | 1 (0.312) |     6.78 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3362 | 2024-03-22 | The MongolZ       | W   | 0.304      | 1.000        | 1.000 (0.304)    | -                | 1 (0.304) |     9.06 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3382 | 2024-03-21 | Virtus.pro        | L   | 0.299      | -            | -                | -                | -         |    -1.59 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3390 | 2024-03-21 | Complexity        | L   | 0.298      | -            | -                | -                | -         |    -2.09 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3427 | 2024-03-19 | SAW               | W   | 0.284      | -            | -                | -                | 1 (0.284) |     1.87 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3442 | 2024-03-18 | ENCE              | W   | 0.277      | -            | -                | -                | 1 (0.277) |     4.89 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3460 | 2024-03-17 | Eternal Fire      | L   | 0.272      | -            | -                | -                | -         |    -1.39 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3470 | 2024-03-17 | Apeks             | W   | 0.271      | -            | -                | -                | 1 (0.271) |     0.49 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3799 | 2024-03-04 | ODDIK             | W   | 0.185      | -            | -                | -                | -         |     0.54 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3820 | 2024-03-03 | Imperial          | L   | 0.179      | -            | -                | -                | -         |    -3.89 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3847 | 2024-03-02 | RED Canids        | W   | 0.171      | -            | -                | -                | -         |     0.73 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3861 | 2024-03-01 | Legacy            | W   | 0.166      | -            | -                | -                | -         |     0.50 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($106,719.03)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.33) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.880 | $1,500.00      | $1,320.28       |
| 2024-06-16 |      0.879 | $10,000.00     | $8,786.11       |
| 2024-06-10 |      0.840 | $10,000.00     | $8,398.84       |
| 2024-06-09 |      0.833 | $3,000.00      | $2,498.06       |
| 2024-05-12 |      0.646 | $25,000.00     | $16,145.83      |
| 2024-04-20 |      0.499 | $100,000.00    | $49,935.19      |
| 2024-04-15 |      0.466 | $5,000.00      | $2,329.17       |
| 2024-03-31 |      0.365 | $20,000.00     | $7,305.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
