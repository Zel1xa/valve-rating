### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1425.7<br />
<br />
Final Rank Value (1425.7) = Starting Rank Value (1410.3) + Head To Head Adjustments (15.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.673[<sup>1</sup>](#table2)
- Bounty Collected: 0.494[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.486[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1410.3
- 400 + ( ( 0.494 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1410.3


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
|          103 |        8 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.82 | biguzera, kauez, lux, nqz, snow   |
|          102 |       15 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.05 | biguzera, kauez, lux, nqz, snow   |
|          101 |       37 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.209 (0.078)    | -                | -         |    11.96 | biguzera, kauez, lux, nqz, snow   |
|          100 |       42 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.79 | biguzera, kauez, lux, nqz, snow   |
|           99 |       56 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.50 | biguzera, kauez, lux, nqz, snow   |
|           98 |       93 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.46 | biguzera, kauez, lux, nqz, snow   |
|           97 |      121 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.08 | biguzera, kauez, lux, nqz, snow   |
|           96 |      143 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.23 | biguzera, kauez, lux, nqz, snow   |
|           95 |      166 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           94 |      170 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           93 |      185 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.25 | biguzera, kauez, lux, nqz, snow   |
|           92 |      205 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.61 | biguzera, kauez, lux, nqz, snow   |
|           91 |      233 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.52 | biguzera, kauez, lux, nqz, snow   |
|           90 |      239 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.04 | biguzera, kauez, lux, nqz, snow   |
|           89 |      454 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.55 | biguzera, kauez, lux, nqz, snow   |
|           88 |      461 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.47 | biguzera, kauez, lux, nqz, snow   |
|           87 |      487 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.94 | biguzera, kauez, lux, nqz, snow   |
|           86 |      500 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.07 | biguzera, kauez, lux, nqz, snow   |
|           85 |      520 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.76 | biguzera, kauez, lux, nqz, snow   |
|           84 |      531 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.61 | biguzera, kauez, lux, nqz, snow   |
|           83 |      561 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.27 | biguzera, kauez, lux, nqz, snow   |
|           82 |      563 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.29 | biguzera, kauez, lux, nqz, snow   |
|           81 |      629 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.805 (0.362)    | -         |     2.33 | biguzera, kauez, lux, nqz, snow   |
|           80 |      632 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.805 (0.362)    | -         |     2.38 | biguzera, kauez, lux, nqz, snow   |
|           79 |      655 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.47 | biguzera, kauez, lux, nqz, snow   |
|           78 |      691 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.61 | biguzera, kauez, lux, nqz, snow   |
|           77 |      734 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.835 (0.376)    | -         |     1.92 | biguzera, kauez, lux, nqz, snow   |
|           76 |      738 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.835 (0.376)    | -         |     1.96 | biguzera, kauez, lux, nqz, snow   |
|           75 |      968 | 2024-06-16 | Fluxo             | L   | 0.875      | -            | -                | -                | -         |   -21.43 | biguzera, kauez, lux, nqz, snow   |
|           74 |      995 | 2024-06-15 | 9z                | L   | 0.869      | -            | -                | -                | -         |   -10.22 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1010 | 2024-06-15 | ODDIK             | W   | 0.867      | 0.450        | -                | 0.831 (0.324)    | -         |     2.62 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1027 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.863      | -            | -                | -                | -         |    -5.46 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1045 | 2024-06-14 | BESTIA            | W   | 0.861      | 0.548        | -                | 0.801 (0.378)    | 1 (0.861) |     3.90 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1070 | 2024-06-13 | KRÜ               | W   | 0.855      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1144 | 2024-06-10 | BESTIA            | W   | 0.836      | 0.371        | -                | 0.801 (0.248)    | -         |     3.97 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1157 | 2024-06-10 | Imperial          | W   | 0.834      | 0.371        | 0.237 (0.073)    | -                | -         |    11.29 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1187 | 2024-06-09 | Sharks            | W   | 0.828      | -            | -                | -                | -         |     4.17 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1241 | 2024-06-08 | Hype              | W   | 0.823      | -            | -                | -                | -         |     2.07 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1271 | 2024-06-08 | Dusty Roots       | W   | 0.821      | -            | -                | -                | -         |     1.56 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1298 | 2024-06-07 | Patins da Ferrari | W   | 0.816      | -            | -                | -                | -         |     1.24 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1349 | 2024-06-06 | Galorys           | W   | 0.810      | -            | -                | -                | -         |     1.85 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1359 | 2024-06-06 | Sharks            | L   | 0.809      | -            | -                | -                | -         |   -21.70 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1425 | 2024-06-05 | Fluxo             | W   | 0.803      | 0.450        | -                | 0.723 (0.261)    | -         |     4.42 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1479 | 2024-06-04 | ODDIK             | W   | 0.796      | 0.450        | -                | 0.831 (0.298)    | -         |     2.48 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1804 | 2024-05-22 | MIBR              | L   | 0.708      | -            | -                | -                | -         |    -8.52 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1808 | 2024-05-22 | MIBR              | L   | 0.708      | -            | -                | -                | -         |    -9.04 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1914 | 2024-05-19 | AMKAL             | L   | 0.687      | -            | -                | -                | -         |   -15.97 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1925 | 2024-05-19 | OG                | W   | 0.686      | 0.769        | 0.139 (0.073)    | -                | -         |     2.90 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1939 | 2024-05-18 | AMKAL             | L   | 0.681      | -            | -                | -                | -         |   -16.45 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2163 | 2024-05-12 | 9z                | W   | 0.642      | 0.435        | 0.405 (0.113)    | -                | -         |    13.79 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2196 | 2024-05-11 | BESTIA            | W   | 0.635      | -            | -                | -                | -         |     1.80 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2224 | 2024-05-10 | RED Canids        | W   | 0.627      | -            | -                | -                | -         |     3.46 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2233 | 2024-05-09 | Fluxo             | L   | 0.623      | -            | -                | -                | -         |   -16.73 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2238 | 2024-05-09 | Fluxo             | W   | 0.623      | -            | -                | -                | -         |     2.82 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2258 | 2024-05-08 | RED Canids        | W   | 0.617      | -            | -                | -                | -         |     3.26 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2260 | 2024-05-08 | RED Canids        | L   | 0.616      | -            | -                | -                | -         |   -16.46 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2262 | 2024-05-08 | Galorys           | W   | 0.615      | -            | -                | -                | -         |     1.01 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2265 | 2024-05-08 | Galorys           | W   | 0.615      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2279 | 2024-05-07 | W7M               | W   | 0.609      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2299 | 2024-05-06 | W7M               | W   | 0.602      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2300 | 2024-05-06 | W7M               | W   | 0.602      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2312 | 2024-05-05 | KRÜ               | W   | 0.595      | -            | -                | -                | -         |     1.09 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2537 | 2024-04-25 | Solid             | W   | 0.529      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2539 | 2024-04-25 | Solid             | W   | 0.529      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2558 | 2024-04-24 | ODDIK             | W   | 0.523      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2559 | 2024-04-24 | ODDIK             | L   | 0.523      | -            | -                | -                | -         |   -15.24 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2632 | 2024-04-20 | Imperial          | W   | 0.496      | 0.589        | 0.237 (0.069)    | -                | 1 (0.496) |     5.57 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2641 | 2024-04-20 | MIBR              | W   | 0.495      | 0.589        | 0.209 (0.061)    | -                | 1 (0.495) |     9.08 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2662 | 2024-04-19 | Imperial          | L   | 0.491      | -            | -                | -                | -         |   -10.02 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2663 | 2024-04-19 | MIBR              | L   | 0.490      | -            | -                | -                | -         |    -6.81 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2675 | 2024-04-19 | Imperial          | W   | 0.489      | -            | -                | -                | -         |     5.35 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2689 | 2024-04-19 | MIBR              | W   | 0.488      | 0.589        | 0.209 (0.060)    | -                | 1 (0.488) |     8.65 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2712 | 2024-04-18 | Fluxo             | W   | 0.484      | -            | -                | -                | -         |     2.16 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2716 | 2024-04-18 | MIBR              | L   | 0.483      | -            | -                | -                | -         |    -6.82 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2742 | 2024-04-18 | Monte             | W   | 0.481      | -            | -                | -                | 1 (0.481) |     1.43 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2846 | 2024-04-14 | Imperial          | L   | 0.455      | -            | -                | -                | -         |    -9.62 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2857 | 2024-04-13 | ODDIK             | W   | 0.449      | -            | -                | -                | -         |     0.99 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2890 | 2024-04-11 | MIBR              | L   | 0.436      | -            | -                | -                | -         |    -6.78 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2896 | 2024-04-11 | Sharks            | W   | 0.435      | -            | -                | -                | -         |     1.08 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2902 | 2024-04-11 | Imperial          | W   | 0.434      | -            | -                | -                | -         |     4.39 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2937 | 2024-04-10 | RED Canids        | W   | 0.428      | -            | -                | -                | -         |     1.93 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     2981 | 2024-04-09 | Case              | W   | 0.423      | -            | -                | -                | -         |     0.74 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     2986 | 2024-04-09 | Case              | W   | 0.423      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3004 | 2024-04-09 | Imperial          | L   | 0.421      | -            | -                | -                | -         |    -9.00 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3026 | 2024-04-08 | Sharks            | W   | 0.415      | -            | -                | -                | -         |     0.34 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3056 | 2024-04-07 | MIBR              | L   | 0.410      | -            | -                | -                | -         |    -6.77 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3060 | 2024-04-07 | Galorys           | W   | 0.409      | -            | -                | -                | -         |     0.66 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3096 | 2024-04-05 | Sharks            | W   | 0.394      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3116 | 2024-04-04 | Sharks            | W   | 0.390      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3123 | 2024-04-04 | Sharks            | W   | 0.389      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3349 | 2024-03-24 | Natus Vincere     | L   | 0.315      | -            | -                | -                | -         |    -0.47 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3360 | 2024-03-23 | HEROIC            | W   | 0.308      | 1.000        | 0.229 (0.071)    | -                | 1 (0.308) |     6.72 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3375 | 2024-03-22 | The MongolZ       | W   | 0.300      | 1.000        | 1.000 (0.300)    | -                | 1 (0.300) |     8.96 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3395 | 2024-03-21 | Virtus.pro        | L   | 0.295      | -            | -                | -                | -         |    -1.55 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3403 | 2024-03-21 | Complexity        | L   | 0.294      | -            | -                | -                | -         |    -2.05 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3440 | 2024-03-19 | SAW               | W   | 0.281      | -            | -                | -                | 1 (0.281) |     1.86 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3455 | 2024-03-18 | ENCE              | W   | 0.273      | -            | -                | -                | 1 (0.273) |     4.86 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3473 | 2024-03-17 | Eternal Fire      | L   | 0.268      | -            | -                | -                | -         |    -1.36 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3483 | 2024-03-17 | Apeks             | W   | 0.267      | -            | -                | -                | 1 (0.267) |     0.48 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3813 | 2024-03-04 | ODDIK             | W   | 0.181      | -            | -                | -                | -         |     0.53 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3834 | 2024-03-03 | Imperial          | L   | 0.175      | -            | -                | -                | -         |    -3.81 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3861 | 2024-03-02 | RED Canids        | W   | 0.168      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3875 | 2024-03-01 | Legacy            | W   | 0.162      | -            | -                | -                | -         |     0.49 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($106,060.61)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.33) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.876 | $1,500.00      | $1,314.62       |
| 2024-06-16 |      0.875 | $10,000.00     | $8,748.38       |
| 2024-06-10 |      0.836 | $10,000.00     | $8,361.11       |
| 2024-06-09 |      0.829 | $3,000.00      | $2,486.74       |
| 2024-05-12 |      0.642 | $25,000.00     | $16,051.50      |
| 2024-04-20 |      0.496 | $100,000.00    | $49,557.87      |
| 2024-04-15 |      0.462 | $5,000.00      | $2,310.30       |
| 2024-03-31 |      0.362 | $20,000.00     | $7,230.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
