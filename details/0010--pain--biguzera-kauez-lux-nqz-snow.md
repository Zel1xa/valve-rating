### Roster Details<br />
Team Name: paiN<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1588.0<br />
<br />
Final Rank Value (1588.0) = Starting Rank Value (1690.2) + Head To Head Adjustments (-102.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.726[<sup>1</sup>](#table2)
- Bounty Collected: 0.597[<sup>2</sup>](#table1)
- Opponent Network: 0.342[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.666<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1690.2
- 400 + ( ( 0.666 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1690.2


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
|          116 |      219 | 2024-08-31 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -9.98 | biguzera, kauez, lux, nqz, snow   |
|          115 |      230 | 2024-08-30 | Virtus.pro        | W   | 1.000      | 0.769        | 0.520 (0.399)    | -                | 1 (1.000) |    11.06 | biguzera, kauez, lux, nqz, snow   |
|          114 |      260 | 2024-08-29 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -5.30 | biguzera, kauez, lux, nqz, snow   |
|          113 |      317 | 2024-08-28 | HEROIC            | W   | 1.000      | 0.769        | 0.205 (0.158)    | 0.412 (0.317)    | 1 (1.000) |     8.21 | biguzera, kauez, lux, nqz, snow   |
|          112 |      397 | 2024-08-27 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |    13.54 | biguzera, kauez, lux, nqz, snow   |
|          111 |      508 | 2024-08-25 | 9z                | W   | 1.000      | 0.143        | 0.362 (0.052)    | -                | 1 (1.000) |    10.11 | biguzera, kauez, lux, nqz, snow   |
|          110 |      525 | 2024-08-24 | FaZe              | L   | 1.000      | -            | -                | -                | -         |    -9.48 | biguzera, kauez, lux, nqz, snow   |
|          109 |      529 | 2024-08-24 | BetBoom           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.50 | biguzera, kauez, lux, nqz, snow   |
|          108 |      552 | 2024-08-23 | Cloud9            | W   | 1.000      | 0.535        | 0.098 (0.053)    | 0.488 (0.261)    | -         |     1.91 | biguzera, kauez, lux, nqz, snow   |
|          107 |      879 | 2024-08-13 | G2                | L   | 1.000      | -            | -                | -                | -         |    -3.11 | biguzera, kauez, lux, nqz, snow   |
|          106 |      925 | 2024-08-12 | The MongolZ       | W   | 1.000      | 1.000        | 0.864 (0.864)    | 0.695 (0.695)    | 1 (1.000) |    21.14 | biguzera, kauez, lux, nqz, snow   |
|          105 |      949 | 2024-08-11 | 9z                | W   | 1.000      | 1.000        | 0.362 (0.362)    | 0.530 (0.530)    | 1 (1.000) |    10.86 | biguzera, kauez, lux, nqz, snow   |
|          104 |      971 | 2024-08-10 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -2.96 | biguzera, kauez, lux, nqz, snow   |
|          103 |      995 | 2024-08-09 | MIBR              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.68 | biguzera, kauez, lux, nqz, snow   |
|          102 |     1007 | 2024-08-09 | Imperial          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.20 | biguzera, kauez, lux, nqz, snow   |
|          101 |     1056 | 2024-08-07 | Liquid            | L   | 0.988      | -            | -                | -                | -         |   -10.90 | biguzera, kauez, lux, nqz, snow   |
|          100 |     1189 | 2024-08-03 | Legacy            | W   | 0.963      | -            | -                | -                | -         |     1.71 | biguzera, kauez, lux, nqz, snow   |
|           99 |     1201 | 2024-08-03 | ODDIK             | W   | 0.961      | -            | -                | -                | -         |     2.15 | biguzera, kauez, lux, nqz, snow   |
|           98 |     1223 | 2024-08-02 | MIBR              | W   | 0.956      | 0.371        | 0.156 (0.055)    | -                | -         |     6.39 | biguzera, kauez, lux, nqz, snow   |
|           97 |     1227 | 2024-08-02 | Legacy            | W   | 0.955      | 0.371        | -                | 0.730 (0.258)    | -         |     1.55 | biguzera, kauez, lux, nqz, snow   |
|           96 |     1242 | 2024-08-02 | Sharks            | W   | 0.954      | -            | -                | -                | -         |     1.63 | biguzera, kauez, lux, nqz, snow   |
|           95 |     1280 | 2024-08-01 | Sharks            | W   | 0.947      | -            | -                | -                | -         |     1.57 | biguzera, kauez, lux, nqz, snow   |
|           94 |     1308 | 2024-07-31 | ODDIK             | W   | 0.943      | -            | -                | -                | -         |     1.99 | biguzera, kauez, lux, nqz, snow   |
|           93 |     1330 | 2024-07-31 | Dusty Roots       | W   | 0.940      | -            | -                | -                | -         |     0.45 | biguzera, kauez, lux, nqz, snow   |
|           92 |     1354 | 2024-07-30 | Players           | W   | 0.936      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, snow   |
|           91 |     1358 | 2024-07-30 | Players           | W   | 0.936      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, snow   |
|           90 |     1373 | 2024-07-30 | Case              | W   | 0.934      | -            | -                | -                | -         |     0.93 | biguzera, kauez, lux, nqz, snow   |
|           89 |     1393 | 2024-07-29 | Imperial          | W   | 0.930      | -            | -                | -                | -         |     3.24 | biguzera, kauez, lux, nqz, snow   |
|           88 |     1421 | 2024-07-28 | Imperial          | W   | 0.923      | -            | -                | -                | -         |     2.98 | biguzera, kauez, lux, nqz, snow   |
|           87 |     1427 | 2024-07-28 | RED Canids        | W   | 0.922      | -            | -                | -                | -         |     2.51 | biguzera, kauez, lux, nqz, snow   |
|           86 |     1642 | 2024-07-21 | Fluxo             | L   | 0.875      | -            | -                | -                | -         |   -24.62 | biguzera, kauez, lux, nqz, snow   |
|           85 |     1649 | 2024-07-21 | Fluxo             | W   | 0.874      | -            | -                | -                | -         |     2.70 | biguzera, kauez, lux, nqz, snow   |
|           84 |     1675 | 2024-07-20 | Imperial          | W   | 0.868      | -            | -                | -                | -         |     2.14 | biguzera, kauez, lux, nqz, snow   |
|           83 |     1688 | 2024-07-20 | Bounty Hunters    | W   | 0.867      | -            | -                | -                | -         |     0.78 | biguzera, kauez, lux, nqz, snow   |
|           82 |     1708 | 2024-07-19 | Fluxo             | W   | 0.862      | -            | -                | -                | -         |     2.47 | biguzera, kauez, lux, nqz, snow   |
|           81 |     1718 | 2024-07-19 | Vikings KR        | W   | 0.861      | -            | -                | -                | -         |     0.40 | biguzera, kauez, lux, nqz, snow   |
|           80 |     1749 | 2024-07-18 | Dusty Roots       | W   | 0.856      | -            | -                | -                | -         |     0.33 | biguzera, kauez, lux, nqz, snow   |
|           79 |     1751 | 2024-07-18 | Dusty Roots       | W   | 0.856      | -            | -                | -                | -         |     0.33 | biguzera, kauez, lux, nqz, snow   |
|           78 |     1818 | 2024-07-17 | Case              | W   | 0.849      | 0.450        | -                | 0.727 (0.278)    | -         |     0.73 | biguzera, kauez, lux, nqz, snow   |
|           77 |     1820 | 2024-07-17 | Case              | W   | 0.849      | 0.450        | -                | 0.727 (0.278)    | -         |     0.74 | biguzera, kauez, lux, nqz, snow   |
|           76 |     1843 | 2024-07-17 | W7M               | W   | 0.847      | -            | -                | -                | -         |     0.40 | biguzera, kauez, lux, nqz, snow   |
|           75 |     1879 | 2024-07-16 | Galorys           | W   | 0.843      | -            | -                | -                | -         |     0.41 | biguzera, kauez, lux, nqz, snow   |
|           74 |     1886 | 2024-07-16 | Galorys           | W   | 0.843      | -            | -                | -                | -         |     0.41 | biguzera, kauez, lux, nqz, snow   |
|           73 |     1925 | 2024-07-15 | Solid             | W   | 0.837      | 0.450        | -                | 0.692 (0.261)    | -         |     0.51 | biguzera, kauez, lux, nqz, snow   |
|           72 |     1930 | 2024-07-15 | Solid             | W   | 0.836      | 0.450        | -                | 0.692 (0.261)    | -         |     0.51 | biguzera, kauez, lux, nqz, snow   |
|           71 |     2159 | 2024-06-16 | Fluxo             | L   | 0.641      | -            | -                | -                | -         |   -18.95 | biguzera, kauez, lux, nqz, snow   |
|           70 |     2186 | 2024-06-15 | 9z                | L   | 0.635      | -            | -                | -                | -         |   -13.52 | biguzera, kauez, lux, nqz, snow   |
|           69 |     2201 | 2024-06-15 | ODDIK             | W   | 0.634      | 0.450        | 0.190 (0.054)    | -                | -         |     1.03 | biguzera, kauez, lux, nqz, snow   |
|           68 |     2218 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.630      | -            | -                | -                | -         |   -13.15 | biguzera, kauez, lux, nqz, snow   |
|           67 |     2236 | 2024-06-14 | BESTIA            | W   | 0.628      | 0.548        | -                | 0.807 (0.278)    | 1 (0.628) |     0.79 | biguzera, kauez, lux, nqz, snow   |
|           66 |     2261 | 2024-06-13 | KRÜ               | W   | 0.622      | -            | -                | -                | -         |     0.36 | biguzera, kauez, lux, nqz, snow   |
|           65 |     2335 | 2024-06-10 | BESTIA            | W   | 0.603      | -            | -                | -                | -         |     0.77 | biguzera, kauez, lux, nqz, snow   |
|           64 |     2348 | 2024-06-10 | Imperial          | W   | 0.600      | -            | -                | -                | -         |     1.68 | biguzera, kauez, lux, nqz, snow   |
|           63 |     2378 | 2024-06-09 | Sharks            | W   | 0.595      | -            | -                | -                | -         |     1.05 | biguzera, kauez, lux, nqz, snow   |
|           62 |     2432 | 2024-06-08 | Hype              | W   | 0.589      | -            | -                | -                | -         |     0.35 | biguzera, kauez, lux, nqz, snow   |
|           61 |     2462 | 2024-06-08 | Dusty Roots       | W   | 0.587      | -            | -                | -                | -         |     0.25 | biguzera, kauez, lux, nqz, snow   |
|           60 |     2489 | 2024-06-07 | Patins da Ferrari | W   | 0.583      | -            | -                | -                | -         |     0.18 | biguzera, kauez, lux, nqz, snow   |
|           59 |     2540 | 2024-06-06 | Galorys           | W   | 0.577      | -            | -                | -                | -         |     0.29 | biguzera, kauez, lux, nqz, snow   |
|           58 |     2550 | 2024-06-06 | Sharks            | L   | 0.576      | -            | -                | -                | -         |   -17.21 | biguzera, kauez, lux, nqz, snow   |
|           57 |     2616 | 2024-06-05 | Fluxo             | W   | 0.569      | -            | -                | -                | -         |     0.73 | biguzera, kauez, lux, nqz, snow   |
|           56 |     2670 | 2024-06-04 | ODDIK             | W   | 0.563      | -            | -                | -                | -         |     0.88 | biguzera, kauez, lux, nqz, snow   |
|           55 |     2995 | 2024-05-22 | MIBR              | L   | 0.475      | -            | -                | -                | -         |   -11.09 | biguzera, kauez, lux, nqz, snow   |
|           54 |     2999 | 2024-05-22 | MIBR              | L   | 0.475      | -            | -                | -                | -         |   -11.44 | biguzera, kauez, lux, nqz, snow   |
|           53 |     3105 | 2024-05-19 | AMKAL             | L   | 0.454      | -            | -                | -                | -         |   -13.40 | biguzera, kauez, lux, nqz, snow   |
|           52 |     3116 | 2024-05-19 | OG                | W   | 0.452      | -            | -                | -                | -         |     0.38 | biguzera, kauez, lux, nqz, snow   |
|           51 |     3130 | 2024-05-18 | AMKAL             | L   | 0.448      | -            | -                | -                | -         |   -13.33 | biguzera, kauez, lux, nqz, snow   |
|           50 |     3354 | 2024-05-12 | 9z                | W   | 0.409      | 0.435        | 0.362 (0.064)    | -                | -         |     3.92 | biguzera, kauez, lux, nqz, snow   |
|           49 |     3387 | 2024-05-11 | BESTIA            | W   | 0.401      | -            | -                | -                | -         |     0.27 | biguzera, kauez, lux, nqz, snow   |
|           48 |     3415 | 2024-05-10 | RED Canids        | W   | 0.394      | -            | -                | -                | -         |     0.36 | biguzera, kauez, lux, nqz, snow   |
|           47 |     3424 | 2024-05-09 | Fluxo             | L   | 0.390      | -            | -                | -                | -         |   -11.93 | biguzera, kauez, lux, nqz, snow   |
|           46 |     3429 | 2024-05-09 | Fluxo             | W   | 0.390      | -            | -                | -                | -         |     0.35 | biguzera, kauez, lux, nqz, snow   |
|           45 |     3449 | 2024-05-08 | RED Canids        | W   | 0.383      | -            | -                | -                | -         |     0.33 | biguzera, kauez, lux, nqz, snow   |
|           44 |     3451 | 2024-05-08 | RED Canids        | L   | 0.383      | -            | -                | -                | -         |   -11.76 | biguzera, kauez, lux, nqz, snow   |
|           43 |     3453 | 2024-05-08 | Galorys           | W   | 0.382      | -            | -                | -                | -         |     0.07 | biguzera, kauez, lux, nqz, snow   |
|           42 |     3456 | 2024-05-08 | Galorys           | W   | 0.381      | -            | -                | -                | -         |     0.07 | biguzera, kauez, lux, nqz, snow   |
|           41 |     3470 | 2024-05-07 | W7M               | W   | 0.375      | -            | -                | -                | -         |     0.10 | biguzera, kauez, lux, nqz, snow   |
|           40 |     3490 | 2024-05-06 | W7M               | W   | 0.368      | -            | -                | -                | -         |     0.10 | biguzera, kauez, lux, nqz, snow   |
|           39 |     3491 | 2024-05-06 | W7M               | W   | 0.368      | -            | -                | -                | -         |     0.10 | biguzera, kauez, lux, nqz, snow   |
|           38 |     3503 | 2024-05-05 | KRÜ               | W   | 0.362      | -            | -                | -                | -         |     0.15 | biguzera, kauez, lux, nqz, snow   |
|           37 |     3728 | 2024-04-25 | Solid             | W   | 0.296      | -            | -                | -                | -         |     0.10 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     3730 | 2024-04-25 | Solid             | W   | 0.296      | -            | -                | -                | -         |     0.10 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     3749 | 2024-04-24 | ODDIK             | W   | 0.290      | -            | -                | -                | -         |     0.43 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     3750 | 2024-04-24 | ODDIK             | L   | 0.289      | -            | -                | -                | -         |    -8.71 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     3823 | 2024-04-20 | Imperial          | W   | 0.262      | -            | -                | -                | -         |     0.34 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     3832 | 2024-04-20 | MIBR              | W   | 0.261      | -            | -                | -                | -         |     1.73 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     3853 | 2024-04-19 | Imperial          | L   | 0.258      | -            | -                | -                | -         |    -7.80 | biguzera, kauez, lux, nqz, nyezin |
|           30 |     3854 | 2024-04-19 | MIBR              | L   | 0.257      | -            | -                | -                | -         |    -6.54 | biguzera, kauez, lux, nqz, nyezin |
|           29 |     3866 | 2024-04-19 | Imperial          | W   | 0.255      | -            | -                | -                | -         |     0.30 | biguzera, kauez, lux, nqz, nyezin |
|           28 |     3880 | 2024-04-19 | MIBR              | W   | 0.254      | -            | -                | -                | -         |     1.51 | biguzera, kauez, lux, nqz, nyezin |
|           27 |     3903 | 2024-04-18 | Fluxo             | W   | 0.250      | -            | -                | -                | -         |     0.05 | biguzera, kauez, lux, nqz, nyezin |
|           26 |     3907 | 2024-04-18 | MIBR              | L   | 0.249      | -            | -                | -                | -         |    -6.45 | biguzera, kauez, lux, nqz, nyezin |
|           25 |     3933 | 2024-04-18 | Monte             | W   | 0.247      | -            | -                | -                | -         |     0.14 | biguzera, kauez, lux, nqz, nyezin |
|           24 |     4037 | 2024-04-14 | Imperial          | L   | 0.221      | -            | -                | -                | -         |    -6.74 | biguzera, kauez, lux, nqz, nyezin |
|           23 |     4048 | 2024-04-13 | ODDIK             | W   | 0.215      | -            | -                | -                | -         |     0.27 | biguzera, kauez, lux, nqz, nyezin |
|           22 |     4081 | 2024-04-11 | MIBR              | L   | 0.203      | -            | -                | -                | -         |    -5.36 | biguzera, kauez, lux, nqz, nyezin |
|           21 |     4087 | 2024-04-11 | Sharks            | W   | 0.202      | -            | -                | -                | -         |     0.18 | biguzera, kauez, lux, nqz, nyezin |
|           20 |     4093 | 2024-04-11 | Imperial          | W   | 0.201      | -            | -                | -                | -         |     0.20 | biguzera, kauez, lux, nqz, nyezin |
|           19 |     4128 | 2024-04-10 | RED Canids        | W   | 0.195      | -            | -                | -                | -         |     0.12 | biguzera, kauez, lux, nqz, nyezin |
|           18 |     4172 | 2024-04-09 | Case              | W   | 0.190      | -            | -                | -                | -         |     0.10 | biguzera, kauez, lux, nqz, nyezin |
|           17 |     4177 | 2024-04-09 | Case              | W   | 0.189      | -            | -                | -                | -         |     0.10 | biguzera, kauez, lux, nqz, nyezin |
|           16 |     4195 | 2024-04-09 | Imperial          | L   | 0.187      | -            | -                | -                | -         |    -5.73 | biguzera, kauez, lux, nqz, nyezin |
|           15 |     4217 | 2024-04-08 | Sharks            | W   | 0.182      | -            | -                | -                | -         |     0.03 | biguzera, kauez, lux, nqz, nyezin |
|           14 |     4247 | 2024-04-07 | MIBR              | L   | 0.176      | -            | -                | -                | -         |    -4.73 | biguzera, kauez, lux, nqz, nyezin |
|           13 |     4251 | 2024-04-07 | Galorys           | W   | 0.175      | -            | -                | -                | -         |     0.03 | biguzera, kauez, lux, nqz, nyezin |
|           12 |     4287 | 2024-04-05 | Sharks            | W   | 0.161      | -            | -                | -                | -         |     0.02 | biguzera, kauez, lux, nqz, nyezin |
|           11 |     4307 | 2024-04-04 | Sharks            | W   | 0.156      | -            | -                | -                | -         |     0.02 | biguzera, kauez, lux, nqz, nyezin |
|           10 |     4314 | 2024-04-04 | Sharks            | W   | 0.156      | -            | -                | -                | -         |     0.02 | biguzera, kauez, lux, nqz, nyezin |
|            9 |     4540 | 2024-03-24 | Natus Vincere     | L   | 0.081      | -            | -                | -                | -         |    -0.39 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     4551 | 2024-03-23 | HEROIC            | W   | 0.075      | -            | -                | -                | -         |     0.38 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     4566 | 2024-03-22 | The MongolZ       | W   | 0.067      | 1.000        | 0.864 (0.058)    | -                | -         |     1.58 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     4586 | 2024-03-21 | Virtus.pro        | L   | 0.062      | -            | -                | -                | -         |    -1.41 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     4594 | 2024-03-21 | Complexity        | L   | 0.060      | -            | -                | -                | -         |    -1.38 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     4631 | 2024-03-19 | SAW               | W   | 0.047      | -            | -                | -                | -         |     0.42 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     4646 | 2024-03-18 | ENCE              | W   | 0.040      | -            | -                | -                | -         |     0.09 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     4664 | 2024-03-17 | Eternal Fire      | L   | 0.035      | -            | -                | -                | -         |    -0.29 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     4674 | 2024-03-17 | Apeks             | W   | 0.033      | -            | -                | -                | -         |     0.01 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($127,489.12)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-01 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-08-27 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-08-25 |      1.000 | $7,500.00      | $7,500.00       |
| 2024-08-18 |      1.000 | $24,000.00     | $24,000.00      |
| 2024-08-02 |      0.956 | $10,000.00     | $9,559.26       |
| 2024-06-16 |      0.641 | $10,000.00     | $6,413.89       |
| 2024-06-10 |      0.603 | $10,000.00     | $6,026.62       |
| 2024-05-12 |      0.409 | $25,000.00     | $10,215.28      |
| 2024-04-20 |      0.262 | $100,000.00    | $26,212.96      |
| 2024-03-31 |      0.128 | $20,000.00     | $2,561.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
