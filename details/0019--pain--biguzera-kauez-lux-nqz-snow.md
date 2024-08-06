### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1423.0<br />
<br />
Final Rank Value (1423.0) = Starting Rank Value (1404.3) + Head To Head Adjustments (18.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.672[<sup>1</sup>](#table2)
- Bounty Collected: 0.491[<sup>2</sup>](#table1)
- Opponent Network: 0.318[<sup>2</sup>](#table1)
- LAN Wins: 0.478[<sup>2</sup>](#table1)

The average of these factors is 0.490<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1404.3
- 400 + ( ( 0.490 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1404.3


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
|          103 |       53 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.84 | biguzera, kauez, lux, nqz, snow   |
|          102 |       65 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.08 | biguzera, kauez, lux, nqz, snow   |
|          101 |       87 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.208 (0.077)    | -                | -         |    11.98 | biguzera, kauez, lux, nqz, snow   |
|          100 |       91 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.81 | biguzera, kauez, lux, nqz, snow   |
|           99 |      106 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.52 | biguzera, kauez, lux, nqz, snow   |
|           98 |      144 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.48 | biguzera, kauez, lux, nqz, snow   |
|           97 |      173 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.12 | biguzera, kauez, lux, nqz, snow   |
|           96 |      194 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.25 | biguzera, kauez, lux, nqz, snow   |
|           95 |      218 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, snow   |
|           94 |      222 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.72 | biguzera, kauez, lux, nqz, snow   |
|           93 |      237 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.27 | biguzera, kauez, lux, nqz, snow   |
|           92 |      257 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.60 | biguzera, kauez, lux, nqz, snow   |
|           91 |      285 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.50 | biguzera, kauez, lux, nqz, snow   |
|           90 |      291 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.06 | biguzera, kauez, lux, nqz, snow   |
|           89 |      506 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.53 | biguzera, kauez, lux, nqz, snow   |
|           88 |      513 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.49 | biguzera, kauez, lux, nqz, snow   |
|           87 |      539 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.91 | biguzera, kauez, lux, nqz, snow   |
|           86 |      552 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.09 | biguzera, kauez, lux, nqz, snow   |
|           85 |      572 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.78 | biguzera, kauez, lux, nqz, snow   |
|           84 |      582 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.63 | biguzera, kauez, lux, nqz, snow   |
|           83 |      613 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.30 | biguzera, kauez, lux, nqz, snow   |
|           82 |      615 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.31 | biguzera, kauez, lux, nqz, snow   |
|           81 |      681 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.795 (0.358)    | -         |     2.36 | biguzera, kauez, lux, nqz, snow   |
|           80 |      684 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.795 (0.358)    | -         |     2.42 | biguzera, kauez, lux, nqz, snow   |
|           79 |      707 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.49 | biguzera, kauez, lux, nqz, snow   |
|           78 |      743 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.543 (0.244)    | -         |     1.64 | biguzera, kauez, lux, nqz, snow   |
|           77 |      786 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.825 (0.371)    | -         |     1.94 | biguzera, kauez, lux, nqz, snow   |
|           76 |      790 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.825 (0.371)    | -         |     1.98 | biguzera, kauez, lux, nqz, snow   |
|           75 |     1020 | 2024-06-16 | Fluxo             | L   | 0.865      | -            | -                | -                | -         |   -21.16 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1047 | 2024-06-15 | 9z                | L   | 0.859      | -            | -                | -                | -         |   -10.03 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1062 | 2024-06-15 | ODDIK             | W   | 0.857      | 0.450        | -                | 0.822 (0.317)    | -         |     2.63 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1079 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.853      | -            | -                | -                | -         |    -5.29 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1097 | 2024-06-14 | BESTIA            | W   | 0.851      | 0.548        | -                | 0.792 (0.370)    | 1 (0.851) |     3.89 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1122 | 2024-06-13 | KRÜ               | W   | 0.845      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1196 | 2024-06-10 | BESTIA            | W   | 0.826      | 0.371        | -                | 0.792 (0.242)    | -         |     3.96 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1209 | 2024-06-10 | Imperial          | W   | 0.824      | 0.371        | 0.234 (0.071)    | -                | -         |    11.11 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1239 | 2024-06-09 | Sharks            | W   | 0.818      | -            | -                | -                | -         |     4.14 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1293 | 2024-06-08 | Hype              | W   | 0.813      | -            | -                | -                | -         |     2.08 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1323 | 2024-06-08 | Dusty Roots       | W   | 0.810      | -            | -                | -                | -         |     1.57 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1350 | 2024-06-07 | Patins da Ferrari | W   | 0.806      | -            | -                | -                | -         |     1.25 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1401 | 2024-06-06 | Galorys           | W   | 0.800      | -            | -                | -                | -         |     1.86 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1411 | 2024-06-06 | Sharks            | L   | 0.799      | -            | -                | -                | -         |   -21.41 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1477 | 2024-06-05 | Fluxo             | W   | 0.793      | 0.450        | -                | 0.716 (0.255)    | -         |     4.40 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1531 | 2024-06-04 | ODDIK             | W   | 0.786      | 0.450        | -                | 0.822 (0.291)    | -         |     2.48 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1856 | 2024-05-22 | MIBR              | L   | 0.698      | -            | -                | -                | -         |    -8.39 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1860 | 2024-05-22 | MIBR              | L   | 0.698      | -            | -                | -                | -         |    -8.90 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1966 | 2024-05-19 | AMKAL             | L   | 0.677      | -            | -                | -                | -         |   -15.70 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1977 | 2024-05-19 | OG                | W   | 0.676      | 0.769        | 0.137 (0.071)    | -                | -         |     2.87 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1991 | 2024-05-18 | AMKAL             | L   | 0.671      | -            | -                | -                | -         |   -16.16 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2215 | 2024-05-12 | 9z                | W   | 0.632      | 0.435        | 0.404 (0.111)    | -                | -         |    13.64 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2248 | 2024-05-11 | BESTIA            | W   | 0.624      | -            | -                | -                | -         |     1.81 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2276 | 2024-05-10 | RED Canids        | W   | 0.617      | -            | -                | -                | -         |     3.44 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2285 | 2024-05-09 | Fluxo             | L   | 0.613      | -            | -                | -                | -         |   -16.43 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2290 | 2024-05-09 | Fluxo             | W   | 0.613      | -            | -                | -                | -         |     2.81 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2310 | 2024-05-08 | RED Canids        | W   | 0.606      | -            | -                | -                | -         |     3.23 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2312 | 2024-05-08 | RED Canids        | L   | 0.606      | -            | -                | -                | -         |   -16.16 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2314 | 2024-05-08 | Galorys           | W   | 0.605      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2317 | 2024-05-08 | Galorys           | W   | 0.605      | -            | -                | -                | -         |     1.03 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2331 | 2024-05-07 | W7M               | W   | 0.599      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2351 | 2024-05-06 | W7M               | W   | 0.592      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2352 | 2024-05-06 | W7M               | W   | 0.591      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2364 | 2024-05-05 | KRÜ               | W   | 0.585      | -            | -                | -                | -         |     1.09 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2589 | 2024-04-25 | Solid             | W   | 0.519      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2591 | 2024-04-25 | Solid             | W   | 0.519      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2610 | 2024-04-24 | ODDIK             | W   | 0.513      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2611 | 2024-04-24 | ODDIK             | L   | 0.512      | -            | -                | -                | -         |   -14.92 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2684 | 2024-04-20 | Imperial          | W   | 0.485      | 0.589        | 0.234 (0.067)    | -                | 1 (0.485) |     5.43 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2693 | 2024-04-20 | MIBR              | W   | 0.485      | 0.589        | 0.208 (0.059)    | -                | 1 (0.485) |     8.90 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2714 | 2024-04-19 | Imperial          | L   | 0.481      | -            | -                | -                | -         |    -9.84 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2715 | 2024-04-19 | MIBR              | L   | 0.480      | -            | -                | -                | -         |    -6.66 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2727 | 2024-04-19 | Imperial          | W   | 0.478      | -            | -                | -                | -         |     5.22 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2741 | 2024-04-19 | MIBR              | W   | 0.478      | 0.589        | 0.208 (0.058)    | -                | 1 (0.478) |     8.49 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2764 | 2024-04-18 | Fluxo             | W   | 0.474      | -            | -                | -                | -         |     2.14 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2768 | 2024-04-18 | MIBR              | L   | 0.472      | -            | -                | -                | -         |    -6.67 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2794 | 2024-04-18 | Monte             | W   | 0.471      | -            | -                | -                | 1 (0.471) |     1.41 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2898 | 2024-04-14 | Imperial          | L   | 0.444      | -            | -                | -                | -         |    -9.41 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2909 | 2024-04-13 | ODDIK             | W   | 0.439      | -            | -                | -                | -         |     0.99 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2942 | 2024-04-11 | MIBR              | L   | 0.426      | -            | -                | -                | -         |    -6.60 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2948 | 2024-04-11 | Sharks            | W   | 0.425      | -            | -                | -                | -         |     1.07 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2954 | 2024-04-11 | Imperial          | W   | 0.424      | -            | -                | -                | -         |     4.28 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2989 | 2024-04-10 | RED Canids        | W   | 0.418      | -            | -                | -                | -         |     1.91 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     3033 | 2024-04-09 | Case              | W   | 0.413      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     3038 | 2024-04-09 | Case              | W   | 0.412      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3056 | 2024-04-09 | Imperial          | L   | 0.411      | -            | -                | -                | -         |    -8.79 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3078 | 2024-04-08 | Sharks            | W   | 0.405      | -            | -                | -                | -         |     0.34 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3108 | 2024-04-07 | MIBR              | L   | 0.400      | -            | -                | -                | -         |    -6.57 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3112 | 2024-04-07 | Galorys           | W   | 0.399      | -            | -                | -                | -         |     0.66 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3148 | 2024-04-05 | Sharks            | W   | 0.384      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3168 | 2024-04-04 | Sharks            | W   | 0.380      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3175 | 2024-04-04 | Sharks            | W   | 0.379      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3401 | 2024-03-24 | Natus Vincere     | L   | 0.305      | -            | -                | -                | -         |    -0.43 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3412 | 2024-03-23 | HEROIC            | W   | 0.298      | 1.000        | 0.225 (0.067)    | -                | 1 (0.298) |     6.54 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3427 | 2024-03-22 | The MongolZ       | W   | 0.290      | 1.000        | 1.000 (0.290)    | -                | 1 (0.290) |     8.68 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3447 | 2024-03-21 | Virtus.pro        | L   | 0.285      | -            | -                | -                | -         |    -1.47 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3455 | 2024-03-21 | Complexity        | L   | 0.284      | -            | -                | -                | -         |    -1.86 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3492 | 2024-03-19 | SAW               | W   | 0.271      | -            | -                | -                | 1 (0.271) |     1.81 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3507 | 2024-03-18 | ENCE              | W   | 0.263      | -            | -                | -                | 1 (0.263) |     4.86 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3525 | 2024-03-17 | Eternal Fire      | L   | 0.258      | -            | -                | -                | -         |    -1.28 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3535 | 2024-03-17 | Apeks             | W   | 0.257      | -            | -                | -                | 1 (0.257) |     0.47 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3865 | 2024-03-04 | ODDIK             | W   | 0.171      | -            | -                | -                | -         |     0.51 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3886 | 2024-03-03 | Imperial          | L   | 0.165      | -            | -                | -                | -         |    -3.59 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3913 | 2024-03-02 | RED Canids        | W   | 0.158      | -            | -                | -                | -         |     0.68 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3927 | 2024-03-01 | Legacy            | W   | 0.152      | -            | -                | -                | -         |     0.47 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($104,295.42)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.866 | $1,500.00      | $1,299.44       |
| 2024-06-16 |      0.865 | $10,000.00     | $8,647.22       |
| 2024-06-10 |      0.826 | $10,000.00     | $8,259.95       |
| 2024-06-09 |      0.819 | $3,000.00      | $2,456.39       |
| 2024-05-12 |      0.632 | $25,000.00     | $15,798.61      |
| 2024-04-20 |      0.485 | $100,000.00    | $48,546.30      |
| 2024-04-15 |      0.452 | $5,000.00      | $2,259.72       |
| 2024-03-31 |      0.351 | $20,000.00     | $7,027.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
