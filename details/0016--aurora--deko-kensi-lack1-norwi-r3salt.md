### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1437.8<br />
<br />
Final Rank Value (1437.8) = Starting Rank Value (1695.8) + Head To Head Adjustments (-258.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.733[<sup>1</sup>](#table2)
- Bounty Collected: 0.508[<sup>2</sup>](#table1)
- Opponent Network: 0.276[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1695.8
- 400 + ( ( 0.629 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1695.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           85 |      165 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.72 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      213 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      218 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.128 (0.083)    | 0.513 (0.334)    | 1 (1.000) |    10.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      244 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      256 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.174 (0.113)    | 0.403 (0.262)    | 1 (1.000) |    11.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      291 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.451 (0.294)    | 1 (1.000) |     3.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      489 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.878 (0.439)    | -         |     5.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      619 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.452 (0.226)    | -         |     2.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |      905 | 2024-06-16 | Complexity         | L   | 0.892      | -            | -                | -                | -         |    -8.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |      962 | 2024-06-14 | The MongolZ        | W   | 0.881      | 0.500        | 1.000 (0.440)    | 0.719 (0.317)    | 1 (0.881) |    25.78 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |      972 | 2024-06-14 | Falcons            | W   | 0.879      | 0.500        | 0.206 (0.091)    | -                | 1 (0.879) |    14.85 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1074 | 2024-06-10 | 9 Pandas           | W   | 0.854      | -            | -                | -                | -         |     3.70 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1079 | 2024-06-10 | Monte              | W   | 0.853      | -            | -                | -                | -         |     2.86 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1083 | 2024-06-10 | SAW                | L   | 0.853      | -            | -                | -                | -         |   -21.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1108 | 2024-06-09 | Monte              | L   | 0.848      | -            | -                | -                | -         |   -24.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1115 | 2024-06-09 | PARIVISION         | W   | 0.847      | -            | -                | -                | -         |     3.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1123 | 2024-06-09 | RUSH B             | L   | 0.847      | -            | -                | -                | -         |   -25.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1131 | 2024-06-09 | 3DMAX              | L   | 0.847      | -            | -                | -                | -         |   -13.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1140 | 2024-06-09 | SINNERS            | L   | 0.846      | -            | -                | -                | -         |   -24.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1235 | 2024-06-07 | Sangal             | L   | 0.835      | -            | -                | -                | -         |   -23.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1250 | 2024-06-07 | Verdant            | W   | 0.834      | -            | -                | -                | -         |     0.87 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1254 | 2024-06-07 | PERA               | W   | 0.834      | -            | -                | -                | -         |     1.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1303 | 2024-06-06 | RUSH B             | W   | 0.828      | -            | -                | -                | -         |     0.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1368 | 2024-06-05 | PARIVISION         | W   | 0.821      | 0.500        | -                | 0.451 (0.185)    | -         |     2.15 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1416 | 2024-06-04 | 3DMAX              | L   | 0.815      | -            | -                | -                | -         |   -12.73 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1482 | 2024-06-01 | BLEED              | L   | 0.798      | -            | -                | -                | -         |   -17.78 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1507 | 2024-06-01 | Lynn Vision        | W   | 0.794      | 0.500        | 0.080 (0.032)    | -                | 1 (0.794) |     1.16 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1516 | 2024-05-31 | Chinggis Warriors  | W   | 0.792      | -            | -                | -                | 1 (0.792) |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1591 | 2024-05-29 | The MongolZ        | L   | 0.773      | -            | -                | -                | -         |    -3.03 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1614 | 2024-05-28 | Lynn Vision        | W   | 0.765      | -            | -                | -                | 1 (0.765) |     0.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1802 | 2024-05-21 | Astralis           | L   | 0.720      | -            | -                | -                | -         |    -6.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     1944 | 2024-05-17 | SAW                | W   | 0.693      | 0.769        | 0.108 (0.057)    | 0.544 (0.290)    | -         |     3.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     1959 | 2024-05-16 | PARIVISION         | W   | 0.689      | 0.769        | -                | 0.451 (0.239)    | -         |     1.45 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     1967 | 2024-05-16 | MIBR               | L   | 0.688      | -            | -                | -                | -         |   -14.11 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     1981 | 2024-05-16 | SAW                | L   | 0.686      | -            | -                | -                | -         |   -19.08 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2035 | 2024-05-15 | Spirit             | L   | 0.679      | -            | -                | -                | -         |    -2.93 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2183 | 2024-05-10 | MOUZ NXT           | L   | 0.648      | -            | -                | -                | -         |   -19.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2445 | 2024-04-28 | MIBR               | L   | 0.566      | -            | -                | -                | -         |   -12.93 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2447 | 2024-04-27 | Rebels             | W   | 0.565      | 0.500        | -                | 0.635 (0.179)    | 1 (0.565) |     0.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2474 | 2024-04-27 | Party Astronauts   | W   | 0.559      | -            | -                | -                | -         |     0.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2498 | 2024-04-25 | Apeks              | L   | 0.552      | -            | -                | -                | -         |   -16.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2502 | 2024-04-25 | Party Astronauts   | W   | 0.550      | -            | -                | -                | -         |     0.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2714 | 2024-04-18 | RUBY               | L   | 0.501      | -            | -                | -                | -         |   -15.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2828 | 2024-04-14 | OG                 | W   | 0.474      | 0.684        | 0.143 (0.046)    | -                | -         |     0.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2841 | 2024-04-13 | BetBoom            | W   | 0.468      | 0.684        | 0.257 (0.082)    | -                | -         |     3.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2853 | 2024-04-12 | AMKAL              | W   | 0.462      | -            | -                | -                | -         |     0.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2877 | 2024-04-11 | BetBoom            | W   | 0.455      | -            | -                | -                | -         |     3.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2884 | 2024-04-11 | Apeks              | W   | 0.454      | -            | -                | -                | -         |     0.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2889 | 2024-04-11 | FORZE              | W   | 0.454      | -            | -                | -                | -         |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2918 | 2024-04-10 | PARIVISION         | W   | 0.448      | -            | -                | -                | -         |     0.60 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     2930 | 2024-04-10 | BetBoom            | L   | 0.448      | -            | -                | -                | -         |   -11.01 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     2979 | 2024-04-09 | KOI                | L   | 0.442      | -            | -                | -                | -         |   -13.67 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     2987 | 2024-04-09 | 1WIN               | W   | 0.441      | -            | -                | -                | -         |     0.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     2995 | 2024-04-09 | 9 Pandas           | W   | 0.440      | -            | -                | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3005 | 2024-04-08 | Metizport          | W   | 0.435      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3010 | 2024-04-08 | OG                 | W   | 0.435      | 0.684        | 0.143 (0.043)    | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3020 | 2024-04-08 | 1WIN               | L   | 0.434      | -            | -                | -                | -         |   -13.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3113 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.408      | -            | -                | -                | -         |     3.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3155 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.402      | -            | -                | -                | -         |     3.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3199 | 2024-04-02 | Apeks              | W   | 0.395      | -            | -                | -                | -         |     0.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3208 | 2024-04-02 | Metizport          | W   | 0.394      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3220 | 2024-04-01 | SINNERS            | L   | 0.388      | -            | -                | -                | -         |   -11.89 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3259 | 2024-03-28 | brazylijski luz    | W   | 0.361      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3291 | 2024-03-27 | Metizport          | W   | 0.355      | -            | -                | -                | -         |     0.16 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3298 | 2024-03-27 | AURA               | W   | 0.355      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3336 | 2024-03-25 | Rebels             | W   | 0.341      | -            | -                | -                | -         |     0.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3352 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.329      | -            | -                | -                | -         |     0.20 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3366 | 2024-03-22 | ex-Sprout          | W   | 0.321      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3490 | 2024-03-16 | Gods Reign         | W   | 0.280      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3511 | 2024-03-15 | Gods Reign         | W   | 0.273      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3550 | 2024-03-14 | Bad News Kangaroos | W   | 0.265      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3816 | 2024-03-04 | Young Ninjas       | L   | 0.201      | -            | -                | -                | -         |    -6.30 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3863 | 2024-03-02 | Rebels             | W   | 0.188      | -            | -                | -                | -         |     0.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3887 | 2024-03-01 | FORZE              | W   | 0.182      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3889 | 2024-03-01 | 9 Pandas           | W   | 0.181      | -            | -                | -                | -         |     0.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3895 | 2024-02-29 | KOI                | W   | 0.175      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3898 | 2024-02-29 | Spirit Academy     | W   | 0.174      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3904 | 2024-02-29 | HAVU               | W   | 0.173      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3907 | 2024-02-28 | kONO               | W   | 0.168      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3914 | 2024-02-28 | FORZE              | L   | 0.167      | -            | -                | -                | -         |    -5.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4143 | 2024-02-18 | Monte              | L   | 0.102      | -            | -                | -                | -         |    -3.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4152 | 2024-02-18 | B8                 | W   | 0.100      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4169 | 2024-02-17 | kONO               | W   | 0.095      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4173 | 2024-02-17 | Monte              | L   | 0.094      | -            | -                | -                | -         |    -2.91 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4176 | 2024-02-17 | kONO               | W   | 0.094      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($141,380.20)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.43) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.894 | $10,000.00     | $8,938.89       |
| 2024-06-09 |      0.848 | $8,500.00      | $7,205.52       |
| 2024-06-02 |      0.800 | $15,000.00     | $11,993.40      |
| 2024-05-23 |      0.734 | $12,500.00     | $9,171.88       |
| 2024-04-28 |      0.566 | $20,000.00     | $11,317.59      |
| 2024-04-14 |      0.474 | $105,000.00    | $49,772.92      |
| 2024-03-16 |      0.280 | $28,500.00     | $7,980.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
