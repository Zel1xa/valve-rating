### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1392.7<br />
<br />
Final Rank Value (1392.7) = Starting Rank Value (1686.0) + Head To Head Adjustments (-293.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.727[<sup>1</sup>](#table2)
- Bounty Collected: 0.504[<sup>2</sup>](#table1)
- Opponent Network: 0.292[<sup>2</sup>](#table1)
- LAN Wins: 0.978[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1686.0
- 400 + ( ( 0.625 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1686.0


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
|           87 |       11 | 2024-08-05 | ARCRED             | L   | 1.000      | -            | -                | -                | -         |   -28.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           86 |       43 | 2024-08-04 | Nemiga             | L   | 1.000      | -            | -                | -                | -         |   -26.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           85 |      321 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      369 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      374 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.538 (0.350)    | 1 (1.000) |     9.87 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      400 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      412 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.173 (0.113)    | 0.422 (0.274)    | 1 (1.000) |    12.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      447 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.590 (0.384)    | 1 (1.000) |     3.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      636 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | -         |     5.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      764 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.435 (0.218)    | -         |     2.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |     1046 | 2024-06-16 | Complexity         | L   | 0.859      | -            | -                | -                | -         |    -7.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1112 | 2024-06-14 | The MongolZ        | W   | 0.848      | 0.500        | 1.000 (0.424)    | 0.694 (0.294)    | 1 (0.848) |    24.78 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1122 | 2024-06-14 | Falcons            | W   | 0.846      | 0.500        | 0.220 (0.093)    | -                | 1 (0.846) |    13.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1222 | 2024-06-10 | 9 Pandas           | W   | 0.821      | -            | -                | -                | -         |     3.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1227 | 2024-06-10 | Monte              | W   | 0.820      | -            | -                | -                | -         |     2.64 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1231 | 2024-06-10 | SAW                | L   | 0.820      | -            | -                | -                | -         |   -21.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1256 | 2024-06-09 | Monte              | L   | 0.815      | -            | -                | -                | -         |   -23.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1263 | 2024-06-09 | PARIVISION         | W   | 0.814      | -            | -                | -                | -         |     3.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1271 | 2024-06-09 | RUSH B             | L   | 0.814      | -            | -                | -                | -         |   -24.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1279 | 2024-06-09 | 3DMAX              | L   | 0.813      | -            | -                | -                | -         |   -12.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1287 | 2024-06-09 | SINNERS            | L   | 0.813      | -            | -                | -                | -         |   -23.85 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1374 | 2024-06-07 | Sangal             | L   | 0.802      | -            | -                | -                | -         |   -21.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1389 | 2024-06-07 | Verdant            | W   | 0.801      | -            | -                | -                | -         |     0.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1393 | 2024-06-07 | PERA               | W   | 0.801      | -            | -                | -                | -         |     0.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1440 | 2024-06-06 | RUSH B             | W   | 0.795      | -            | -                | -                | -         |     0.64 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1502 | 2024-06-05 | PARIVISION         | W   | 0.788      | 0.500        | -                | 0.590 (0.233)    | -         |     2.03 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1550 | 2024-06-04 | 3DMAX              | L   | 0.782      | -            | -                | -                | -         |   -12.04 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1615 | 2024-06-01 | BLEED              | L   | 0.765      | -            | -                | -                | -         |   -17.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1640 | 2024-06-01 | Lynn Vision        | W   | 0.760      | 0.500        | 0.086 (0.033)    | -                | 1 (0.760) |     1.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1649 | 2024-05-31 | Chinggis Warriors  | W   | 0.759      | -            | -                | -                | 1 (0.759) |     0.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1724 | 2024-05-29 | The MongolZ        | L   | 0.740      | -            | -                | -                | -         |    -3.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1747 | 2024-05-28 | Lynn Vision        | W   | 0.732      | -            | -                | -                | 1 (0.732) |     1.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1918 | 2024-05-21 | Astralis           | L   | 0.687      | -            | -                | -                | -         |    -5.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2049 | 2024-05-17 | SAW                | W   | 0.660      | 0.769        | 0.104 (0.053)    | 0.516 (0.262)    | -         |     2.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2064 | 2024-05-16 | PARIVISION         | W   | 0.656      | 0.769        | -                | 0.590 (0.298)    | -         |     1.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2072 | 2024-05-16 | MIBR               | L   | 0.655      | -            | -                | -                | -         |   -13.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2086 | 2024-05-16 | SAW                | L   | 0.653      | -            | -                | -                | -         |   -18.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2136 | 2024-05-15 | Spirit             | L   | 0.646      | -            | -                | -                | -         |    -2.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2279 | 2024-05-10 | MOUZ NXT           | L   | 0.615      | -            | -                | -                | -         |   -18.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2536 | 2024-04-28 | MIBR               | L   | 0.533      | -            | -                | -                | -         |   -12.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2538 | 2024-04-27 | Rebels             | W   | 0.532      | 0.500        | -                | 0.578 (0.154)    | 1 (0.532) |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2564 | 2024-04-27 | Party Astronauts   | W   | 0.526      | -            | -                | -                | -         |     0.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2589 | 2024-04-25 | Apeks              | L   | 0.519      | -            | -                | -                | -         |   -15.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2593 | 2024-04-25 | Party Astronauts   | W   | 0.517      | -            | -                | -                | -         |     0.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2797 | 2024-04-18 | RUBY               | L   | 0.468      | -            | -                | -                | -         |   -14.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2909 | 2024-04-14 | OG                 | W   | 0.441      | 0.684        | 0.137 (0.041)    | -                | -         |     0.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2922 | 2024-04-13 | BetBoom            | W   | 0.435      | 0.684        | 0.248 (0.074)    | -                | -         |     2.86 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2934 | 2024-04-12 | AMKAL              | W   | 0.429      | -            | -                | -                | -         |     0.73 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2957 | 2024-04-11 | BetBoom            | W   | 0.422      | -            | -                | -                | -         |     2.85 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2964 | 2024-04-11 | Apeks              | W   | 0.421      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2969 | 2024-04-11 | FORZE              | W   | 0.421      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2998 | 2024-04-10 | PARIVISION         | W   | 0.415      | -            | -                | -                | -         |     0.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     3010 | 2024-04-10 | BetBoom            | L   | 0.414      | -            | -                | -                | -         |   -10.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3059 | 2024-04-09 | KOI                | L   | 0.409      | -            | -                | -                | -         |   -12.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3067 | 2024-04-09 | 1WIN               | W   | 0.407      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3075 | 2024-04-09 | 9 Pandas           | W   | 0.407      | -            | -                | -                | -         |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3085 | 2024-04-08 | Metizport          | W   | 0.402      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3090 | 2024-04-08 | OG                 | W   | 0.402      | 0.684        | 0.137 (0.038)    | -                | -         |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3100 | 2024-04-08 | 1WIN               | L   | 0.401      | -            | -                | -                | -         |   -12.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3193 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.375      | -            | -                | -                | -         |     5.90 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3233 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.368      | -            | -                | -                | -         |     5.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3271 | 2024-04-02 | Apeks              | W   | 0.362      | -            | -                | -                | -         |     0.16 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3280 | 2024-04-02 | Metizport          | W   | 0.361      | -            | -                | -                | -         |     0.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3292 | 2024-04-01 | SINNERS            | L   | 0.355      | -            | -                | -                | -         |   -10.66 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3331 | 2024-03-28 | brazylijski luz    | W   | 0.328      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3362 | 2024-03-27 | Metizport          | W   | 0.322      | -            | -                | -                | -         |     0.14 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3369 | 2024-03-27 | AURA               | W   | 0.322      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3403 | 2024-03-25 | Rebels             | W   | 0.308      | -            | -                | -                | -         |     0.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3419 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.296      | -            | -                | -                | -         |     0.19 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3433 | 2024-03-22 | ex-Sprout          | W   | 0.288      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3557 | 2024-03-16 | Gods Reign         | W   | 0.247      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3578 | 2024-03-15 | Gods Reign         | W   | 0.239      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3613 | 2024-03-14 | Bad News Kangaroos | W   | 0.232      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3872 | 2024-03-04 | Young Ninjas       | L   | 0.168      | -            | -                | -                | -         |    -5.26 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3919 | 2024-03-02 | Rebels             | W   | 0.155      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3942 | 2024-03-01 | FORZE              | W   | 0.149      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3944 | 2024-03-01 | 9 Pandas           | W   | 0.148      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3950 | 2024-02-29 | KOI                | W   | 0.142      | -            | -                | -                | -         |     0.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3953 | 2024-02-29 | Spirit Academy     | W   | 0.141      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3959 | 2024-02-29 | HAVU               | W   | 0.140      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3962 | 2024-02-28 | kONO               | W   | 0.135      | -            | -                | -                | -         |     0.03 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3968 | 2024-02-28 | FORZE              | L   | 0.134      | -            | -                | -                | -         |    -4.18 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4189 | 2024-02-18 | Monte              | L   | 0.069      | -            | -                | -                | -         |    -2.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4198 | 2024-02-18 | B8                 | W   | 0.067      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4216 | 2024-02-17 | kONO               | W   | 0.062      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4220 | 2024-02-17 | Monte              | L   | 0.061      | -            | -                | -                | -         |    -1.89 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4223 | 2024-02-17 | kONO               | W   | 0.061      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($134,785.61)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.861 | $10,000.00     | $8,608.33       |
| 2024-06-09 |      0.815 | $8,500.00      | $6,924.55       |
| 2024-06-02 |      0.767 | $15,000.00     | $11,497.57      |
| 2024-05-23 |      0.701 | $12,500.00     | $8,758.68       |
| 2024-04-28 |      0.533 | $20,000.00     | $10,656.48      |
| 2024-04-14 |      0.441 | $105,000.00    | $46,302.08      |
| 2024-03-16 |      0.247 | $28,500.00     | $7,037.92       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
