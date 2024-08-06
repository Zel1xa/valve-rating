### Roster Details<br />
Team Name: Imperial<br />
Roster: decenty, felps, noway, try, VINI<br />
Global Rank: [30](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [8]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1222.5<br />
<br />
Final Rank Value (1222.5) = Starting Rank Value (1256.6) + Head To Head Adjustments (-34.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.613[<sup>1</sup>](#table2)
- Bounty Collected: 0.496[<sup>2</sup>](#table1)
- Opponent Network: 0.217[<sup>2</sup>](#table1)
- LAN Wins: 0.340[<sup>2</sup>](#table1)

The average of these factors is 0.416<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1256.6
- 400 + ( ( 0.416 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1256.6


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
|          100 |      275 | 2024-07-29 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -9.60 | decenty, felps, noway, try, VINI  |
|           99 |      279 | 2024-07-29 | MIBR              | W   | 1.000      | -            | -                | -                | -         |    21.67 | decenty, felps, noway, try, VINI  |
|           98 |      303 | 2024-07-28 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -9.51 | decenty, felps, noway, try, VINI  |
|           97 |      310 | 2024-07-28 | MIBR              | W   | 1.000      | -            | -                | -                | -         |    22.68 | decenty, felps, noway, try, VINI  |
|           96 |      357 | 2024-07-26 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |    13.96 | decenty, felps, noway, try, VINI  |
|           95 |      360 | 2024-07-26 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     8.58 | decenty, felps, noway, try, VINI  |
|           94 |      389 | 2024-07-25 | Solid             | W   | 1.000      | -            | -                | -                | -         |     6.65 | decenty, felps, noway, try, VINI  |
|           93 |      392 | 2024-07-25 | Yawara            | W   | 1.000      | -            | -                | -                | -         |     0.72 | decenty, felps, noway, try, VINI  |
|           92 |      462 | 2024-07-23 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -25.25 | decenty, felps, noway, try, VINI  |
|           91 |      470 | 2024-07-23 | Atrix             | W   | 1.000      | -            | -                | -                | -         |     1.41 | decenty, felps, noway, try, VINI  |
|           90 |      557 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -8.91 | decenty, felps, noway, try, VINI  |
|           89 |      637 | 2024-07-18 | BESTIA            | W   | 1.000      | -            | -                | -                | -         |     7.28 | decenty, felps, noway, try, VINI  |
|           88 |      647 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -22.42 | decenty, felps, noway, try, VINI  |
|           87 |      653 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     0.32 | decenty, felps, noway, try, VINI  |
|           86 |      697 | 2024-07-17 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.479 (0.216)    | -         |     4.14 | decenty, felps, noway, try, VINI  |
|           85 |      704 | 2024-07-17 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.479 (0.216)    | -         |     4.32 | decenty, felps, noway, try, VINI  |
|           84 |      817 | 2024-07-15 | Case              | L   | 1.000      | -            | -                | -                | -         |   -26.68 | decenty, felps, noway, VINI, zakk |
|           83 |      823 | 2024-07-15 | Case              | L   | 1.000      | -            | -                | -                | -         |   -27.81 | decenty, felps, noway, VINI, zakk |
|           82 |     1075 | 2024-06-15 | fnatic            | L   | 0.854      | -            | -                | -                | -         |    -7.24 | decenty, felps, HEN1, noway, VINI |
|           81 |     1099 | 2024-06-14 | KOI               | L   | 0.849      | -            | -                | -                | -         |   -20.33 | decenty, felps, HEN1, noway, VINI |
|           80 |     1227 | 2024-06-10 | paiN              | L   | 0.820      | -            | -                | -                | -         |   -11.06 | decenty, felps, HEN1, noway, VINI |
|           79 |     1253 | 2024-06-09 | RED Canids        | W   | 0.815      | 0.450        | -                | 0.732 (0.268)    | -         |     8.62 | decenty, felps, HEN1, noway, VINI |
|           78 |     1270 | 2024-06-09 | ODDIK             | W   | 0.813      | 0.371        | 0.099 (0.030)    | 0.805 (0.243)    | -         |     3.10 | decenty, felps, HEN1, noway, VINI |
|           77 |     1313 | 2024-06-08 | 9z                | W   | 0.809      | 0.450        | 0.404 (0.147)    | 0.591 (0.215)    | -         |    18.86 | decenty, felps, HEN1, noway, VINI |
|           76 |     1373 | 2024-06-07 | Galorys           | W   | 0.802      | -            | -                | -                | -         |     2.38 | decenty, felps, HEN1, noway, VINI |
|           75 |     1426 | 2024-06-06 | RED Canids        | L   | 0.795      | -            | -                | -                | -         |   -16.35 | decenty, felps, HEN1, noway, VINI |
|           74 |     1498 | 2024-06-05 | Sharks            | W   | 0.789      | 0.450        | -                | 0.546 (0.194)    | -         |     4.88 | decenty, felps, HEN1, noway, VINI |
|           73 |     1863 | 2024-05-22 | 9z                | W   | 0.696      | 0.450        | 0.404 (0.126)    | 0.591 (0.185)    | -         |    15.60 | decenty, felps, HEN1, noway, VINI |
|           72 |     1867 | 2024-05-22 | 9z                | W   | 0.695      | 0.450        | 0.404 (0.126)    | -                | -         |    16.37 | decenty, felps, HEN1, noway, VINI |
|           71 |     1875 | 2024-05-22 | Sharks            | L   | 0.694      | -            | -                | -                | -         |   -17.60 | decenty, felps, HEN1, noway, VINI |
|           70 |     1879 | 2024-05-22 | Sharks            | W   | 0.694      | -            | -                | -                | -         |     4.15 | decenty, felps, HEN1, noway, VINI |
|           69 |     1915 | 2024-05-21 | BESTIA            | L   | 0.688      | -            | -                | -                | -         |   -17.51 | decenty, felps, HEN1, noway, VINI |
|           68 |     1916 | 2024-05-21 | BESTIA            | L   | 0.688      | -            | -                | -                | -         |   -18.14 | decenty, felps, HEN1, noway, VINI |
|           67 |     2078 | 2024-05-16 | 9z                | W   | 0.654      | 0.384        | 0.404 (0.101)    | -                | -         |    15.76 | decenty, felps, HEN1, noway, VINI |
|           66 |     2133 | 2024-05-15 | Fluxo             | W   | 0.647      | 0.384        | 0.123 (0.031)    | -                | -         |     5.70 | decenty, felps, HEN1, noway, VINI |
|           65 |     2168 | 2024-05-14 | W7M               | W   | 0.643      | -            | -                | -                | -         |     1.37 | decenty, felps, HEN1, noway, VINI |
|           64 |     2171 | 2024-05-14 | W7M               | W   | 0.642      | -            | -                | -                | -         |     1.39 | decenty, felps, HEN1, noway, VINI |
|           63 |     2182 | 2024-05-14 | BESTIA            | W   | 0.642      | 0.384        | -                | 0.776 (0.191)    | -         |     3.18 | decenty, felps, HEN1, noway, VINI |
|           62 |     2219 | 2024-05-13 | KRÜ               | W   | 0.633      | -            | -                | -                | -         |     2.44 | decenty, felps, HEN1, noway, VINI |
|           61 |     2290 | 2024-05-10 | BESTIA            | L   | 0.614      | -            | -                | -                | -         |   -16.57 | decenty, felps, HEN1, noway, VINI |
|           60 |     2348 | 2024-05-07 | ODDIK             | W   | 0.596      | 0.435        | -                | 0.805 (0.208)    | -         |     2.95 | decenty, felps, HEN1, noway, VINI |
|           59 |     2385 | 2024-05-05 | inSanitY          | W   | 0.581      | -            | -                | -                | -         |     2.13 | decenty, felps, HEN1, noway, VINI |
|           58 |     2587 | 2024-04-26 | SAW               | L   | 0.520      | -            | -                | -                | -         |   -10.87 | decenty, felps, HEN1, noway, VINI |
|           57 |     2630 | 2024-04-24 | Eternal Fire      | L   | 0.507      | -            | -                | -                | -         |    -1.54 | decenty, felps, HEN1, noway, VINI |
|           56 |     2649 | 2024-04-23 | FaZe              | L   | 0.501      | -            | -                | -                | -         |    -1.37 | decenty, felps, HEN1, noway, VINI |
|           55 |     2702 | 2024-04-20 | paiN              | L   | 0.482      | -            | -                | -                | -         |    -5.39 | decenty, felps, HEN1, noway, VINI |
|           54 |     2732 | 2024-04-19 | paiN              | W   | 0.477      | 0.589        | 0.324 (0.091)    | 0.839 (0.235)    | 1 (0.477) |     9.75 | decenty, felps, HEN1, noway, VINI |
|           53 |     2745 | 2024-04-19 | paiN              | L   | 0.475      | -            | -                | -                | -         |    -5.18 | decenty, felps, HEN1, noway, VINI |
|           52 |     2781 | 2024-04-18 | MIBR              | L   | 0.470      | -            | -                | -                | -         |    -4.54 | decenty, felps, HEN1, noway, VINI |
|           51 |     2785 | 2024-04-18 | 9z                | W   | 0.469      | 0.589        | 0.404 (0.111)    | -                | 1 (0.469) |    11.97 | decenty, felps, HEN1, noway, VINI |
|           50 |     2789 | 2024-04-18 | Fluxo             | W   | 0.468      | -            | -                | -                | -         |     3.57 | decenty, felps, HEN1, noway, VINI |
|           49 |     2800 | 2024-04-18 | Metizport         | W   | 0.467      | -            | -                | -                | 1 (0.467) |     1.92 | decenty, felps, HEN1, noway, VINI |
|           48 |     2901 | 2024-04-15 | MIBR              | L   | 0.448      | -            | -                | -                | -         |    -4.38 | decenty, felps, HEN1, noway, VINI |
|           47 |     2916 | 2024-04-14 | paiN              | W   | 0.441      | 0.435        | 0.324 (0.062)    | -                | -         |     9.33 | decenty, felps, HEN1, noway, VINI |
|           46 |     2926 | 2024-04-13 | RED Canids        | W   | 0.436      | -            | -                | -                | -         |     3.68 | decenty, felps, HEN1, noway, VINI |
|           45 |     2962 | 2024-04-11 | adalYamigos       | W   | 0.422      | -            | -                | -                | -         |     0.35 | decenty, felps, HEN1, noway, VINI |
|           44 |     2972 | 2024-04-11 | paiN              | L   | 0.420      | -            | -                | -                | -         |    -4.24 | decenty, felps, HEN1, noway, VINI |
|           43 |     3000 | 2024-04-10 | Fluxo             | L   | 0.416      | -            | -                | -                | -         |   -10.06 | decenty, felps, HEN1, noway, VINI |
|           42 |     3003 | 2024-04-10 | Fluxo             | W   | 0.415      | -            | -                | -                | -         |     3.04 | decenty, felps, HEN1, noway, VINI |
|           41 |     3019 | 2024-04-10 | MIBR              | L   | 0.413      | -            | -                | -                | -         |    -4.30 | decenty, felps, HEN1, noway, VINI |
|           40 |     3060 | 2024-04-09 | Solid             | W   | 0.408      | -            | -                | -                | -         |     1.28 | decenty, felps, HEN1, noway, VINI |
|           39 |     3061 | 2024-04-09 | Solid             | W   | 0.408      | -            | -                | -                | -         |     1.29 | decenty, felps, HEN1, noway, VINI |
|           38 |     3074 | 2024-04-09 | paiN              | W   | 0.407      | -            | -                | -                | -         |     8.71 | decenty, felps, HEN1, noway, VINI |
|           37 |     3129 | 2024-04-07 | RED Canids        | W   | 0.395      | -            | -                | -                | -         |     3.18 | decenty, felps, HEN1, noway, VINI |
|           36 |     3132 | 2024-04-07 | FURIA Academy     | W   | 0.394      | -            | -                | -                | -         |     0.18 | decenty, felps, HEN1, noway, VINI |
|           35 |     3189 | 2024-04-04 | ODDIK             | W   | 0.376      | -            | -                | -                | -         |     1.93 | decenty, felps, HEN1, noway, VINI |
|           34 |     3195 | 2024-04-04 | ODDIK             | W   | 0.375      | -            | -                | -                | -         |     1.96 | decenty, felps, HEN1, noway, VINI |
|           33 |     3198 | 2024-04-04 | BESTIA            | W   | 0.374      | -            | -                | -                | -         |     2.14 | decenty, felps, HEN1, noway, VINI |
|           32 |     3227 | 2024-04-03 | Case              | W   | 0.369      | -            | -                | -                | -         |     1.43 | decenty, felps, HEN1, noway, VINI |
|           31 |     3230 | 2024-04-03 | Case              | W   | 0.369      | -            | -                | -                | -         |     1.45 | decenty, felps, HEN1, noway, VINI |
|           30 |     3435 | 2024-03-23 | FaZe              | L   | 0.292      | -            | -                | -                | -         |    -0.84 | decenty, felps, HEN1, noway, VINI |
|           29 |     3448 | 2024-03-22 | Vitality          | L   | 0.286      | -            | -                | -                | -         |    -0.33 | decenty, felps, HEN1, noway, VINI |
|           28 |     3458 | 2024-03-21 | Spirit            | L   | 0.282      | -            | -                | -                | -         |    -0.24 | decenty, felps, HEN1, noway, VINI |
|           27 |     3475 | 2024-03-21 | Virtus.pro        | W   | 0.279      | 1.000        | 0.499 (0.139)    | -                | 1 (0.279) |     8.13 | decenty, felps, HEN1, noway, VINI |
|           26 |     3495 | 2024-03-20 | GamerLegion       | W   | 0.273      | -            | -                | -                | 1 (0.273) |     0.59 | decenty, felps, HEN1, noway, VINI |
|           25 |     3508 | 2024-03-19 | Gaimin Gladiators | L   | 0.267      | -            | -                | -                | -         |    -6.97 | decenty, felps, HEN1, noway, VINI |
|           24 |     3524 | 2024-03-18 | Apeks             | W   | 0.259      | -            | -                | -                | 1 (0.259) |     1.00 | decenty, felps, HEN1, noway, VINI |
|           23 |     3540 | 2024-03-17 | HEROIC            | L   | 0.254      | -            | -                | -                | -         |    -1.29 | decenty, felps, HEN1, noway, VINI |
|           22 |     3552 | 2024-03-17 | ENCE              | W   | 0.253      | -            | -                | -                | 1 (0.253) |     6.13 | decenty, felps, HEN1, noway, VINI |
|           21 |     3782 | 2024-03-07 | Monte             | L   | 0.189      | -            | -                | -                | -         |    -4.88 | decenty, felps, HEN1, noway, VINI |
|           20 |     3904 | 2024-03-03 | paiN              | W   | 0.161      | -            | -                | -                | 1 (0.161) |     3.51 | decenty, felps, HEN1, noway, VINI |
|           19 |     3927 | 2024-03-02 | M80               | W   | 0.154      | -            | -                | -                | 1 (0.154) |     2.22 | decenty, felps, HEN1, noway, VINI |
|           18 |     3944 | 2024-03-01 | NRG               | W   | 0.149      | -            | -                | -                | 1 (0.149) |     0.45 | decenty, felps, HEN1, noway, VINI |
|           17 |     4035 | 2024-02-25 | Fluxo             | L   | 0.115      | -            | -                | -                | -         |    -2.77 | decenty, felps, HEN1, noway, VINI |
|           16 |     4067 | 2024-02-24 | BESTIA            | W   | 0.107      | -            | -                | -                | -         |     0.71 | decenty, felps, HEN1, noway, VINI |
|           15 |     4096 | 2024-02-22 | BESTIA            | L   | 0.096      | -            | -                | -                | -         |    -2.39 | decenty, felps, HEN1, noway, VINI |
|           14 |     4104 | 2024-02-22 | FURIA             | L   | 0.095      | -            | -                | -                | -         |    -0.21 | decenty, felps, HEN1, noway, VINI |
|           13 |     4119 | 2024-02-21 | 2GAME             | W   | 0.089      | -            | -                | -                | -         |     0.10 | decenty, felps, HEN1, noway, VINI |
|           12 |     4122 | 2024-02-21 | 2GAME             | W   | 0.089      | -            | -                | -                | -         |     0.10 | decenty, felps, HEN1, noway, VINI |
|           11 |     4132 | 2024-02-21 | LA RUGONETA       | W   | 0.086      | -            | -                | -                | -         |     0.05 | decenty, felps, HEN1, noway, VINI |
|           10 |     4223 | 2024-02-17 | adalYamigos       | W   | 0.061      | -            | -                | -                | -         |     0.04 | decenty, felps, HEN1, noway, VINI |
|            9 |     4251 | 2024-02-16 | Galorys           | W   | 0.054      | -            | -                | -                | -         |     0.20 | decenty, felps, HEN1, noway, VINI |
|            8 |     4256 | 2024-02-16 | Galorys           | W   | 0.054      | -            | -                | -                | -         |     0.20 | decenty, felps, HEN1, noway, VINI |
|            7 |     4274 | 2024-02-15 | 9z                | W   | 0.049      | -            | -                | -                | -         |     1.29 | decenty, felps, HEN1, noway, VINI |
|            6 |     4276 | 2024-02-15 | Fluxo             | W   | 0.049      | -            | -                | -                | -         |     0.36 | decenty, felps, HEN1, noway, VINI |
|            5 |     4280 | 2024-02-15 | Solid             | W   | 0.048      | -            | -                | -                | -         |     0.18 | decenty, felps, HEN1, noway, VINI |
|            4 |     4310 | 2024-02-14 | Yawara            | W   | 0.042      | -            | -                | -                | -         |     0.02 | decenty, felps, HEN1, noway, VINI |
|            3 |     4347 | 2024-02-13 | RED Canids        | W   | 0.036      | -            | -                | -                | -         |     0.30 | decenty, felps, HEN1, noway, VINI |
|            2 |     4350 | 2024-02-13 | RED Canids        | L   | 0.036      | -            | -                | -                | -         |    -0.83 | decenty, felps, HEN1, noway, VINI |
|            1 |     4357 | 2024-02-13 | Solid             | W   | 0.035      | -            | -                | -                | -         |     0.13 | decenty, felps, HEN1, noway, VINI |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($74,611.19)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.23) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.862 | $1,500.00      | $1,293.61       |
| 2024-06-10 |      0.822 | $1,500.00      | $1,233.16       |
| 2024-06-09 |      0.815 | $20,000.00     | $16,298.15      |
| 2024-05-16 |      0.654 | $20,000.00     | $13,083.33      |
| 2024-05-12 |      0.627 | $3,500.00      | $2,193.33       |
| 2024-04-20 |      0.482 | $50,000.00     | $24,078.70      |
| 2024-04-15 |      0.448 | $15,000.00     | $6,720.83       |
| 2024-03-31 |      0.347 | $20,000.00     | $6,950.00       |
| 2024-03-10 |      0.208 | $5,000.00      | $1,039.24       |
| 2024-02-25 |      0.115 | $15,000.00     | $1,720.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
