### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1438.7<br />
<br />
Final Rank Value (1438.7) = Starting Rank Value (1677.2) + Head To Head Adjustments (-238.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.728[<sup>1</sup>](#table2)
- Bounty Collected: 0.505[<sup>2</sup>](#table1)
- Opponent Network: 0.287[<sup>2</sup>](#table1)
- LAN Wins: 0.979[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1677.2
- 400 + ( ( 0.625 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1677.2


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
|           85 |      261 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      309 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      314 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.517 (0.336)    | 1 (1.000) |    10.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      340 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      352 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.169 (0.110)    | 0.400 (0.260)    | 1 (1.000) |    12.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      387 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.534 (0.347)    | 1 (1.000) |     3.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      573 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.912 (0.456)    | -         |     5.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      703 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.453 (0.226)    | -         |     2.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |      986 | 2024-06-16 | Complexity         | L   | 0.872      | -            | -                | -                | -         |    -7.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1052 | 2024-06-14 | The MongolZ        | W   | 0.860      | 0.500        | 1.000 (0.430)    | 0.721 (0.310)    | 1 (0.860) |    25.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1062 | 2024-06-14 | Falcons            | W   | 0.859      | 0.500        | 0.224 (0.096)    | -                | 1 (0.859) |    13.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1162 | 2024-06-10 | 9 Pandas           | W   | 0.833      | -            | -                | -                | -         |     3.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1167 | 2024-06-10 | Monte              | W   | 0.833      | -            | -                | -                | -         |     2.81 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1171 | 2024-06-10 | SAW                | L   | 0.833      | -            | -                | -                | -         |   -21.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1196 | 2024-06-09 | Monte              | L   | 0.827      | -            | -                | -                | -         |   -23.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1203 | 2024-06-09 | PARIVISION         | W   | 0.827      | -            | -                | -                | -         |     3.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1211 | 2024-06-09 | RUSH B             | L   | 0.827      | -            | -                | -                | -         |   -24.90 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1219 | 2024-06-09 | 3DMAX              | L   | 0.826      | -            | -                | -                | -         |   -12.72 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1227 | 2024-06-09 | SINNERS            | L   | 0.826      | -            | -                | -                | -         |   -24.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1314 | 2024-06-07 | Sangal             | L   | 0.815      | -            | -                | -                | -         |   -22.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1329 | 2024-06-07 | Verdant            | W   | 0.814      | -            | -                | -                | -         |     0.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1333 | 2024-06-07 | PERA               | W   | 0.813      | -            | -                | -                | -         |     1.05 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1380 | 2024-06-06 | RUSH B             | W   | 0.808      | -            | -                | -                | -         |     0.68 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1442 | 2024-06-05 | PARIVISION         | W   | 0.801      | 0.500        | -                | 0.534 (0.214)    | -         |     2.08 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1490 | 2024-06-04 | 3DMAX              | L   | 0.795      | -            | -                | -                | -         |   -12.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1555 | 2024-06-01 | BLEED              | L   | 0.778      | -            | -                | -                | -         |   -17.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1580 | 2024-06-01 | Lynn Vision        | W   | 0.773      | 0.500        | 0.078 (0.030)    | -                | 1 (0.773) |     1.44 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1589 | 2024-05-31 | Chinggis Warriors  | W   | 0.771      | -            | -                | -                | 1 (0.771) |     0.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1664 | 2024-05-29 | The MongolZ        | L   | 0.753      | -            | -                | -                | -         |    -2.93 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1687 | 2024-05-28 | Lynn Vision        | W   | 0.745      | -            | -                | -                | 1 (0.745) |     1.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1858 | 2024-05-21 | Astralis           | L   | 0.700      | -            | -                | -                | -         |    -5.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     1989 | 2024-05-17 | SAW                | W   | 0.672      | 0.769        | 0.105 (0.054)    | 0.540 (0.279)    | -         |     2.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2004 | 2024-05-16 | PARIVISION         | W   | 0.669      | 0.769        | -                | 0.534 (0.275)    | -         |     1.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2012 | 2024-05-16 | MIBR               | L   | 0.668      | -            | -                | -                | -         |   -13.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2026 | 2024-05-16 | SAW                | L   | 0.666      | -            | -                | -                | -         |   -18.64 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2076 | 2024-05-15 | Spirit             | L   | 0.659      | -            | -                | -                | -         |    -2.90 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2219 | 2024-05-10 | MOUZ NXT           | L   | 0.628      | -            | -                | -                | -         |   -18.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2476 | 2024-04-28 | MIBR               | L   | 0.546      | -            | -                | -                | -         |   -12.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2478 | 2024-04-27 | Rebels             | W   | 0.545      | -            | -                | -                | 1 (0.545) |     0.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2504 | 2024-04-27 | Party Astronauts   | W   | 0.539      | -            | -                | -                | -         |     0.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2529 | 2024-04-25 | Apeks              | L   | 0.531      | -            | -                | -                | -         |   -16.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2533 | 2024-04-25 | Party Astronauts   | W   | 0.530      | -            | -                | -                | -         |     0.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2737 | 2024-04-18 | RUBY               | L   | 0.481      | -            | -                | -                | -         |   -14.85 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2849 | 2024-04-14 | OG                 | W   | 0.454      | 0.684        | 0.139 (0.043)    | -                | -         |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2862 | 2024-04-13 | BetBoom            | W   | 0.447      | 0.684        | 0.251 (0.077)    | 0.541 (0.166)    | -         |     3.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2874 | 2024-04-12 | AMKAL              | W   | 0.442      | -            | -                | -                | -         |     0.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2897 | 2024-04-11 | BetBoom            | W   | 0.435      | -            | -                | -                | -         |     3.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2904 | 2024-04-11 | Apeks              | W   | 0.434      | -            | -                | -                | -         |     0.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2909 | 2024-04-11 | FORZE              | W   | 0.433      | -            | -                | -                | -         |     0.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2938 | 2024-04-10 | PARIVISION         | W   | 0.428      | -            | -                | -                | -         |     0.60 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     2950 | 2024-04-10 | BetBoom            | L   | 0.427      | -            | -                | -                | -         |   -10.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     2999 | 2024-04-09 | KOI                | L   | 0.422      | -            | -                | -                | -         |   -12.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3007 | 2024-04-09 | 1WIN               | W   | 0.420      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3015 | 2024-04-09 | 9 Pandas           | W   | 0.420      | -            | -                | -                | -         |     0.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3025 | 2024-04-08 | Metizport          | W   | 0.415      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3030 | 2024-04-08 | OG                 | W   | 0.414      | 0.684        | 0.139 (0.039)    | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3040 | 2024-04-08 | 1WIN               | L   | 0.413      | -            | -                | -                | -         |   -12.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3133 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.388      | -            | -                | -                | -         |     6.31 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3173 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.381      | -            | -                | -                | -         |     6.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3211 | 2024-04-02 | Apeks              | W   | 0.375      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3220 | 2024-04-02 | Metizport          | W   | 0.374      | -            | -                | -                | -         |     0.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3232 | 2024-04-01 | SINNERS            | L   | 0.368      | -            | -                | -                | -         |   -11.18 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3271 | 2024-03-28 | brazylijski luz    | W   | 0.341      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3302 | 2024-03-27 | Metizport          | W   | 0.335      | -            | -                | -                | -         |     0.16 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3309 | 2024-03-27 | AURA               | W   | 0.335      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3343 | 2024-03-25 | Rebels             | W   | 0.321      | -            | -                | -                | -         |     0.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3359 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.308      | -            | -                | -                | -         |     0.20 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3373 | 2024-03-22 | ex-Sprout          | W   | 0.301      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3497 | 2024-03-16 | Gods Reign         | W   | 0.260      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3518 | 2024-03-15 | Gods Reign         | W   | 0.252      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3553 | 2024-03-14 | Bad News Kangaroos | W   | 0.245      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3812 | 2024-03-04 | Young Ninjas       | L   | 0.181      | -            | -                | -                | -         |    -5.67 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3859 | 2024-03-02 | Rebels             | W   | 0.168      | -            | -                | -                | -         |     0.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3882 | 2024-03-01 | FORZE              | W   | 0.162      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3884 | 2024-03-01 | 9 Pandas           | W   | 0.161      | -            | -                | -                | -         |     0.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3890 | 2024-02-29 | KOI                | W   | 0.155      | -            | -                | -                | -         |     0.18 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3893 | 2024-02-29 | Spirit Academy     | W   | 0.154      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3899 | 2024-02-29 | HAVU               | W   | 0.153      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3902 | 2024-02-28 | kONO               | W   | 0.148      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3908 | 2024-02-28 | FORZE              | L   | 0.147      | -            | -                | -                | -         |    -4.58 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4129 | 2024-02-18 | Monte              | L   | 0.082      | -            | -                | -                | -         |    -2.52 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4138 | 2024-02-18 | B8                 | W   | 0.080      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4156 | 2024-02-17 | kONO               | W   | 0.075      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4160 | 2024-02-17 | Monte              | L   | 0.074      | -            | -                | -                | -         |    -2.29 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4163 | 2024-02-17 | kONO               | W   | 0.074      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($137,357.87)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.874 | $10,000.00     | $8,737.27       |
| 2024-06-09 |      0.828 | $8,500.00      | $7,034.14       |
| 2024-06-02 |      0.779 | $15,000.00     | $11,690.97      |
| 2024-05-23 |      0.714 | $12,500.00     | $8,919.85       |
| 2024-04-28 |      0.546 | $20,000.00     | $10,914.35      |
| 2024-04-14 |      0.454 | $105,000.00    | $47,655.90      |
| 2024-03-16 |      0.260 | $28,500.00     | $7,405.38       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
