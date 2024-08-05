### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1425.1<br />
<br />
Final Rank Value (1425.1) = Starting Rank Value (1408.6) + Head To Head Adjustments (16.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.673[<sup>1</sup>](#table2)
- Bounty Collected: 0.493[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.483[<sup>2</sup>](#table1)

The average of these factors is 0.493<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1408.6
- 400 + ( ( 0.493 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1408.6


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
|          103 |       29 | 2024-08-03 | Legacy            | W   | 1.000      | -            | -                | -                | -         |     4.83 | biguzera, kauez, lux, nqz, snow   |
|          102 |       41 | 2024-08-03 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.06 | biguzera, kauez, lux, nqz, snow   |
|          101 |       63 | 2024-08-02 | MIBR              | W   | 1.000      | 0.371        | 0.209 (0.077)    | -                | -         |    11.97 | biguzera, kauez, lux, nqz, snow   |
|          100 |       67 | 2024-08-02 | Legacy            | W   | 1.000      | 0.371        | 0.122 (0.045)    | -                | -         |     4.80 | biguzera, kauez, lux, nqz, snow   |
|           99 |       82 | 2024-08-02 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.50 | biguzera, kauez, lux, nqz, snow   |
|           98 |      120 | 2024-08-01 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     3.47 | biguzera, kauez, lux, nqz, snow   |
|           97 |      149 | 2024-07-31 | ODDIK             | W   | 1.000      | -            | -                | -                | -         |     4.10 | biguzera, kauez, lux, nqz, snow   |
|           96 |      170 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.23 | biguzera, kauez, lux, nqz, snow   |
|           95 |      194 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           94 |      198 | 2024-07-30 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     0.71 | biguzera, kauez, lux, nqz, snow   |
|           93 |      213 | 2024-07-30 | Case              | W   | 1.000      | -            | -                | -                | -         |     2.25 | biguzera, kauez, lux, nqz, snow   |
|           92 |      233 | 2024-07-29 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.61 | biguzera, kauez, lux, nqz, snow   |
|           91 |      261 | 2024-07-28 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     9.51 | biguzera, kauez, lux, nqz, snow   |
|           90 |      267 | 2024-07-28 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     8.04 | biguzera, kauez, lux, nqz, snow   |
|           89 |      482 | 2024-07-21 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -22.54 | biguzera, kauez, lux, nqz, snow   |
|           88 |      489 | 2024-07-21 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.48 | biguzera, kauez, lux, nqz, snow   |
|           87 |      515 | 2024-07-20 | Imperial          | W   | 1.000      | -            | -                | -                | -         |     8.93 | biguzera, kauez, lux, nqz, snow   |
|           86 |      528 | 2024-07-20 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | -         |     3.08 | biguzera, kauez, lux, nqz, snow   |
|           85 |      548 | 2024-07-19 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     8.77 | biguzera, kauez, lux, nqz, snow   |
|           84 |      558 | 2024-07-19 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |     1.61 | biguzera, kauez, lux, nqz, snow   |
|           83 |      589 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.28 | biguzera, kauez, lux, nqz, snow   |
|           82 |      591 | 2024-07-18 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |     1.30 | biguzera, kauez, lux, nqz, snow   |
|           81 |      657 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.806 (0.363)    | -         |     2.34 | biguzera, kauez, lux, nqz, snow   |
|           80 |      660 | 2024-07-17 | Case              | W   | 1.000      | 0.450        | -                | 0.806 (0.363)    | -         |     2.39 | biguzera, kauez, lux, nqz, snow   |
|           79 |      683 | 2024-07-17 | W7M               | W   | 1.000      | -            | -                | -                | -         |     1.48 | biguzera, kauez, lux, nqz, snow   |
|           78 |      719 | 2024-07-16 | Galorys           | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.62 | biguzera, kauez, lux, nqz, snow   |
|           77 |      762 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.836 (0.376)    | -         |     1.93 | biguzera, kauez, lux, nqz, snow   |
|           76 |      766 | 2024-07-15 | Solid             | W   | 1.000      | 0.450        | -                | 0.836 (0.376)    | -         |     1.97 | biguzera, kauez, lux, nqz, snow   |
|           75 |      996 | 2024-06-16 | Fluxo             | L   | 0.871      | -            | -                | -                | -         |   -21.34 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1023 | 2024-06-15 | 9z                | L   | 0.865      | -            | -                | -                | -         |   -10.16 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1038 | 2024-06-15 | ODDIK             | W   | 0.864      | 0.450        | -                | 0.833 (0.324)    | -         |     2.62 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1055 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.860      | -            | -                | -                | -         |    -5.40 | biguzera, kauez, lux, nqz, snow   |
|           71 |     1073 | 2024-06-14 | BESTIA            | W   | 0.858      | 0.548        | -                | 0.802 (0.377)    | 1 (0.858) |     3.90 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1098 | 2024-06-13 | KRÜ               | W   | 0.852      | -            | -                | -                | -         |     1.75 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1172 | 2024-06-10 | BESTIA            | W   | 0.833      | 0.371        | -                | 0.802 (0.248)    | -         |     3.96 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1185 | 2024-06-10 | Imperial          | W   | 0.830      | 0.371        | 0.236 (0.073)    | -                | -         |    11.23 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1215 | 2024-06-09 | Sharks            | W   | 0.825      | -            | -                | -                | -         |     4.16 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1269 | 2024-06-08 | Hype              | W   | 0.819      | -            | -                | -                | -         |     2.07 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1299 | 2024-06-08 | Dusty Roots       | W   | 0.817      | -            | -                | -                | -         |     1.56 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1326 | 2024-06-07 | Patins da Ferrari | W   | 0.813      | -            | -                | -                | -         |     1.24 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1377 | 2024-06-06 | Galorys           | W   | 0.807      | -            | -                | -                | -         |     1.85 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1387 | 2024-06-06 | Sharks            | L   | 0.806      | -            | -                | -                | -         |   -21.60 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1453 | 2024-06-05 | Fluxo             | W   | 0.799      | 0.450        | -                | 0.725 (0.261)    | -         |     4.41 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1507 | 2024-06-04 | ODDIK             | W   | 0.793      | 0.450        | -                | 0.833 (0.297)    | -         |     2.48 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1832 | 2024-05-22 | MIBR              | L   | 0.705      | -            | -                | -                | -         |    -8.48 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1836 | 2024-05-22 | MIBR              | L   | 0.705      | -            | -                | -                | -         |    -9.00 | biguzera, kauez, lux, nqz, snow   |
|           57 |     1942 | 2024-05-19 | AMKAL             | L   | 0.684      | -            | -                | -                | -         |   -15.90 | biguzera, kauez, lux, nqz, snow   |
|           56 |     1953 | 2024-05-19 | OG                | W   | 0.682      | 0.769        | 0.138 (0.073)    | -                | -         |     2.89 | biguzera, kauez, lux, nqz, snow   |
|           55 |     1967 | 2024-05-18 | AMKAL             | L   | 0.678      | -            | -                | -                | -         |   -16.37 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2191 | 2024-05-12 | 9z                | W   | 0.639      | 0.435        | 0.405 (0.112)    | -                | -         |    13.73 | biguzera, kauez, lux, nqz, snow   |
|           53 |     2224 | 2024-05-11 | BESTIA            | W   | 0.631      | -            | -                | -                | -         |     1.80 | biguzera, kauez, lux, nqz, snow   |
|           52 |     2252 | 2024-05-10 | RED Canids        | W   | 0.624      | -            | -                | -                | -         |     3.45 | biguzera, kauez, lux, nqz, snow   |
|           51 |     2261 | 2024-05-09 | Fluxo             | L   | 0.620      | -            | -                | -                | -         |   -16.62 | biguzera, kauez, lux, nqz, snow   |
|           50 |     2266 | 2024-05-09 | Fluxo             | W   | 0.620      | -            | -                | -                | -         |     2.82 | biguzera, kauez, lux, nqz, snow   |
|           49 |     2286 | 2024-05-08 | RED Canids        | W   | 0.613      | -            | -                | -                | -         |     3.25 | biguzera, kauez, lux, nqz, snow   |
|           48 |     2288 | 2024-05-08 | RED Canids        | L   | 0.613      | -            | -                | -                | -         |   -16.36 | biguzera, kauez, lux, nqz, snow   |
|           47 |     2290 | 2024-05-08 | Galorys           | W   | 0.612      | -            | -                | -                | -         |     1.01 | biguzera, kauez, lux, nqz, snow   |
|           46 |     2293 | 2024-05-08 | Galorys           | W   | 0.611      | -            | -                | -                | -         |     1.02 | biguzera, kauez, lux, nqz, snow   |
|           45 |     2307 | 2024-05-07 | W7M               | W   | 0.605      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           44 |     2327 | 2024-05-06 | W7M               | W   | 0.598      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, nqz, snow   |
|           43 |     2328 | 2024-05-06 | W7M               | W   | 0.598      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           42 |     2340 | 2024-05-05 | KRÜ               | W   | 0.592      | -            | -                | -                | -         |     1.09 | biguzera, kauez, lux, nqz, snow   |
|           41 |     2565 | 2024-04-25 | Solid             | W   | 0.526      | -            | -                | -                | -         |     0.87 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     2567 | 2024-04-25 | Solid             | W   | 0.526      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     2586 | 2024-04-24 | ODDIK             | W   | 0.520      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     2587 | 2024-04-24 | ODDIK             | L   | 0.519      | -            | -                | -                | -         |   -15.13 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     2660 | 2024-04-20 | Imperial          | W   | 0.492      | 0.589        | 0.236 (0.068)    | -                | 1 (0.492) |     5.51 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     2669 | 2024-04-20 | MIBR              | W   | 0.491      | 0.589        | 0.209 (0.060)    | -                | 1 (0.491) |     9.02 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     2690 | 2024-04-19 | Imperial          | L   | 0.488      | -            | -                | -                | -         |    -9.96 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     2691 | 2024-04-19 | MIBR              | L   | 0.487      | -            | -                | -                | -         |    -6.76 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     2703 | 2024-04-19 | Imperial          | W   | 0.485      | -            | -                | -                | -         |     5.30 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     2717 | 2024-04-19 | MIBR              | W   | 0.484      | 0.589        | 0.209 (0.060)    | -                | 1 (0.484) |     8.60 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     2740 | 2024-04-18 | Fluxo             | W   | 0.480      | -            | -                | -                | -         |     2.15 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     2744 | 2024-04-18 | MIBR              | L   | 0.479      | -            | -                | -                | -         |    -6.77 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     2770 | 2024-04-18 | Monte             | W   | 0.477      | -            | -                | -                | 1 (0.477) |     1.42 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     2874 | 2024-04-14 | Imperial          | L   | 0.451      | -            | -                | -                | -         |    -9.55 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     2885 | 2024-04-13 | ODDIK             | W   | 0.445      | -            | -                | -                | -         |     0.99 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     2918 | 2024-04-11 | MIBR              | L   | 0.433      | -            | -                | -                | -         |    -6.72 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     2924 | 2024-04-11 | Sharks            | W   | 0.432      | -            | -                | -                | -         |     1.08 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     2930 | 2024-04-11 | Imperial          | W   | 0.431      | -            | -                | -                | -         |     4.35 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     2965 | 2024-04-10 | RED Canids        | W   | 0.425      | -            | -                | -                | -         |     1.92 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     3009 | 2024-04-09 | Case              | W   | 0.420      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     3014 | 2024-04-09 | Case              | W   | 0.419      | -            | -                | -                | -         |     0.75 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     3032 | 2024-04-09 | Imperial          | L   | 0.417      | -            | -                | -                | -         |    -8.93 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     3054 | 2024-04-08 | Sharks            | W   | 0.412      | -            | -                | -                | -         |     0.34 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     3084 | 2024-04-07 | MIBR              | L   | 0.406      | -            | -                | -                | -         |    -6.70 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     3088 | 2024-04-07 | Galorys           | W   | 0.405      | -            | -                | -                | -         |     0.66 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     3124 | 2024-04-05 | Sharks            | W   | 0.391      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     3144 | 2024-04-04 | Sharks            | W   | 0.386      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     3151 | 2024-04-04 | Sharks            | W   | 0.386      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     3377 | 2024-03-24 | Natus Vincere     | L   | 0.311      | -            | -                | -                | -         |    -0.45 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     3388 | 2024-03-23 | HEROIC            | W   | 0.305      | 1.000        | 0.226 (0.069)    | -                | 1 (0.305) |     6.67 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     3403 | 2024-03-22 | The MongolZ       | W   | 0.297      | 1.000        | 1.000 (0.297)    | -                | 1 (0.297) |     8.86 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     3423 | 2024-03-21 | Virtus.pro        | L   | 0.292      | -            | -                | -                | -         |    -1.52 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     3431 | 2024-03-21 | Complexity        | L   | 0.290      | -            | -                | -                | -         |    -1.93 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     3468 | 2024-03-19 | SAW               | W   | 0.277      | -            | -                | -                | 1 (0.277) |     1.84 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     3483 | 2024-03-18 | ENCE              | W   | 0.270      | -            | -                | -                | 1 (0.270) |     4.89 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     3501 | 2024-03-17 | Eternal Fire      | L   | 0.265      | -            | -                | -                | -         |    -1.33 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     3511 | 2024-03-17 | Apeks             | W   | 0.263      | -            | -                | -                | 1 (0.263) |     0.47 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     3841 | 2024-03-04 | ODDIK             | W   | 0.177      | -            | -                | -                | -         |     0.53 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     3862 | 2024-03-03 | Imperial          | L   | 0.171      | -            | -                | -                | -         |    -3.74 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     3889 | 2024-03-02 | RED Canids        | W   | 0.164      | -            | -                | -                | -         |     0.70 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     3903 | 2024-03-01 | Legacy            | W   | 0.159      | -            | -                | -                | -         |     0.49 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($105,458.75)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.33) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.873 | $1,500.00      | $1,309.44       |
| 2024-06-16 |      0.871 | $10,000.00     | $8,713.89       |
| 2024-06-10 |      0.833 | $10,000.00     | $8,326.62       |
| 2024-06-09 |      0.825 | $3,000.00      | $2,476.39       |
| 2024-05-12 |      0.639 | $25,000.00     | $15,965.28      |
| 2024-04-20 |      0.492 | $100,000.00    | $49,212.96      |
| 2024-04-15 |      0.459 | $5,000.00      | $2,293.06       |
| 2024-03-31 |      0.358 | $20,000.00     | $7,161.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
