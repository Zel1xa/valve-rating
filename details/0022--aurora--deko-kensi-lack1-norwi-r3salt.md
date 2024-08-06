### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1392.8<br />
<br />
Final Rank Value (1392.8) = Starting Rank Value (1686.0) + Head To Head Adjustments (-293.1)<br />

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
|           87 |       14 | 2024-08-05 | ARCRED             | L   | 1.000      | -            | -                | -                | -         |   -28.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           86 |       46 | 2024-08-04 | Nemiga             | L   | 1.000      | -            | -                | -                | -         |   -26.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           85 |      324 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      372 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      377 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.538 (0.350)    | 1 (1.000) |     9.89 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      403 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      415 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.173 (0.113)    | 0.422 (0.274)    | 1 (1.000) |    12.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      450 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.590 (0.384)    | 1 (1.000) |     3.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      639 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | -         |     5.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      767 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.435 (0.218)    | -         |     2.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |     1049 | 2024-06-16 | Complexity         | L   | 0.859      | -            | -                | -                | -         |    -7.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1115 | 2024-06-14 | The MongolZ        | W   | 0.847      | 0.500        | 1.000 (0.424)    | 0.694 (0.294)    | 1 (0.847) |    24.77 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1125 | 2024-06-14 | Falcons            | W   | 0.846      | 0.500        | 0.220 (0.093)    | -                | 1 (0.846) |    13.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1225 | 2024-06-10 | 9 Pandas           | W   | 0.820      | -            | -                | -                | -         |     3.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1230 | 2024-06-10 | Monte              | W   | 0.820      | -            | -                | -                | -         |     2.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1234 | 2024-06-10 | SAW                | L   | 0.819      | -            | -                | -                | -         |   -21.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1259 | 2024-06-09 | Monte              | L   | 0.814      | -            | -                | -                | -         |   -23.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1266 | 2024-06-09 | PARIVISION         | W   | 0.814      | -            | -                | -                | -         |     3.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1274 | 2024-06-09 | RUSH B             | L   | 0.814      | -            | -                | -                | -         |   -24.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1282 | 2024-06-09 | 3DMAX              | L   | 0.813      | -            | -                | -                | -         |   -12.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1290 | 2024-06-09 | SINNERS            | L   | 0.813      | -            | -                | -                | -         |   -23.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1377 | 2024-06-07 | Sangal             | L   | 0.801      | -            | -                | -                | -         |   -21.96 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1392 | 2024-06-07 | Verdant            | W   | 0.801      | -            | -                | -                | -         |     0.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1396 | 2024-06-07 | PERA               | W   | 0.800      | -            | -                | -                | -         |     0.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1443 | 2024-06-06 | RUSH B             | W   | 0.795      | -            | -                | -                | -         |     0.64 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1505 | 2024-06-05 | PARIVISION         | W   | 0.788      | 0.500        | -                | 0.590 (0.233)    | -         |     2.03 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1553 | 2024-06-04 | 3DMAX              | L   | 0.781      | -            | -                | -                | -         |   -12.04 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1618 | 2024-06-01 | BLEED              | L   | 0.764      | -            | -                | -                | -         |   -17.39 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1643 | 2024-06-01 | Lynn Vision        | W   | 0.760      | 0.500        | 0.086 (0.033)    | -                | 1 (0.760) |     1.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1652 | 2024-05-31 | Chinggis Warriors  | W   | 0.758      | -            | -                | -                | 1 (0.758) |     0.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1727 | 2024-05-29 | The MongolZ        | L   | 0.740      | -            | -                | -                | -         |    -3.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1750 | 2024-05-28 | Lynn Vision        | W   | 0.732      | -            | -                | -                | 1 (0.732) |     1.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1921 | 2024-05-21 | Astralis           | L   | 0.687      | -            | -                | -                | -         |    -5.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2052 | 2024-05-17 | SAW                | W   | 0.659      | 0.769        | 0.104 (0.053)    | 0.516 (0.262)    | -         |     2.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2067 | 2024-05-16 | PARIVISION         | W   | 0.656      | 0.769        | -                | 0.590 (0.297)    | -         |     1.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2075 | 2024-05-16 | MIBR               | L   | 0.655      | -            | -                | -                | -         |   -13.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2089 | 2024-05-16 | SAW                | L   | 0.653      | -            | -                | -                | -         |   -18.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2139 | 2024-05-15 | Spirit             | L   | 0.646      | -            | -                | -                | -         |    -2.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2282 | 2024-05-10 | MOUZ NXT           | L   | 0.615      | -            | -                | -                | -         |   -18.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2539 | 2024-04-28 | MIBR               | L   | 0.532      | -            | -                | -                | -         |   -12.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2541 | 2024-04-27 | Rebels             | W   | 0.532      | 0.500        | -                | 0.578 (0.154)    | 1 (0.532) |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2567 | 2024-04-27 | Party Astronauts   | W   | 0.525      | -            | -                | -                | -         |     0.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2592 | 2024-04-25 | Apeks              | L   | 0.518      | -            | -                | -                | -         |   -15.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2596 | 2024-04-25 | Party Astronauts   | W   | 0.517      | -            | -                | -                | -         |     0.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2800 | 2024-04-18 | RUBY               | L   | 0.468      | -            | -                | -                | -         |   -14.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2912 | 2024-04-14 | OG                 | W   | 0.441      | 0.684        | 0.137 (0.041)    | -                | -         |     0.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2925 | 2024-04-13 | BetBoom            | W   | 0.434      | 0.684        | 0.248 (0.074)    | -                | -         |     2.85 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2937 | 2024-04-12 | AMKAL              | W   | 0.428      | -            | -                | -                | -         |     0.73 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2960 | 2024-04-11 | BetBoom            | W   | 0.422      | -            | -                | -                | -         |     2.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2967 | 2024-04-11 | Apeks              | W   | 0.421      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2972 | 2024-04-11 | FORZE              | W   | 0.420      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     3001 | 2024-04-10 | PARIVISION         | W   | 0.415      | -            | -                | -                | -         |     0.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     3013 | 2024-04-10 | BetBoom            | L   | 0.414      | -            | -                | -                | -         |   -10.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3062 | 2024-04-09 | KOI                | L   | 0.408      | -            | -                | -                | -         |   -12.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3070 | 2024-04-09 | 1WIN               | W   | 0.407      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3078 | 2024-04-09 | 9 Pandas           | W   | 0.406      | -            | -                | -                | -         |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3088 | 2024-04-08 | Metizport          | W   | 0.402      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3093 | 2024-04-08 | OG                 | W   | 0.401      | 0.684        | 0.137 (0.038)    | -                | -         |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3103 | 2024-04-08 | 1WIN               | L   | 0.400      | -            | -                | -                | -         |   -12.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3196 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.375      | -            | -                | -                | -         |     5.90 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3236 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.368      | -            | -                | -                | -         |     5.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3274 | 2024-04-02 | Apeks              | W   | 0.361      | -            | -                | -                | -         |     0.16 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3283 | 2024-04-02 | Metizport          | W   | 0.360      | -            | -                | -                | -         |     0.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3295 | 2024-04-01 | SINNERS            | L   | 0.355      | -            | -                | -                | -         |   -10.64 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3334 | 2024-03-28 | brazylijski luz    | W   | 0.328      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3365 | 2024-03-27 | Metizport          | W   | 0.322      | -            | -                | -                | -         |     0.14 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3372 | 2024-03-27 | AURA               | W   | 0.322      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3406 | 2024-03-25 | Rebels             | W   | 0.308      | -            | -                | -                | -         |     0.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3422 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.295      | -            | -                | -                | -         |     0.18 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3436 | 2024-03-22 | ex-Sprout          | W   | 0.288      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3560 | 2024-03-16 | Gods Reign         | W   | 0.247      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3581 | 2024-03-15 | Gods Reign         | W   | 0.239      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3616 | 2024-03-14 | Bad News Kangaroos | W   | 0.232      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3875 | 2024-03-04 | Young Ninjas       | L   | 0.168      | -            | -                | -                | -         |    -5.25 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3922 | 2024-03-02 | Rebels             | W   | 0.154      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3945 | 2024-03-01 | FORZE              | W   | 0.148      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3947 | 2024-03-01 | 9 Pandas           | W   | 0.147      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3953 | 2024-02-29 | KOI                | W   | 0.142      | -            | -                | -                | -         |     0.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3956 | 2024-02-29 | Spirit Academy     | W   | 0.141      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3962 | 2024-02-29 | HAVU               | W   | 0.139      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3965 | 2024-02-28 | kONO               | W   | 0.135      | -            | -                | -                | -         |     0.03 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3971 | 2024-02-28 | FORZE              | L   | 0.134      | -            | -                | -                | -         |    -4.17 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4192 | 2024-02-18 | Monte              | L   | 0.069      | -            | -                | -                | -         |    -2.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4201 | 2024-02-18 | B8                 | W   | 0.067      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4219 | 2024-02-17 | kONO               | W   | 0.061      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4223 | 2024-02-17 | Monte              | L   | 0.061      | -            | -                | -                | -         |    -1.88 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4226 | 2024-02-17 | kONO               | W   | 0.061      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($134,711.72)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.860 | $10,000.00     | $8,604.63       |
| 2024-06-09 |      0.814 | $8,500.00      | $6,921.40       |
| 2024-06-02 |      0.766 | $15,000.00     | $11,492.01      |
| 2024-05-23 |      0.700 | $12,500.00     | $8,754.05       |
| 2024-04-28 |      0.532 | $20,000.00     | $10,649.07      |
| 2024-04-14 |      0.441 | $105,000.00    | $46,263.19      |
| 2024-03-16 |      0.247 | $28,500.00     | $7,027.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
