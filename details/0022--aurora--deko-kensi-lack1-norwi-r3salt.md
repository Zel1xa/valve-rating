### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1393.7<br />
<br />
Final Rank Value (1393.7) = Starting Rank Value (1685.9) + Head To Head Adjustments (-292.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.726[<sup>1</sup>](#table2)
- Bounty Collected: 0.503[<sup>2</sup>](#table1)
- Opponent Network: 0.292[<sup>2</sup>](#table1)
- LAN Wins: 0.978[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1685.9
- 400 + ( ( 0.625 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1685.9


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
|           87 |       21 | 2024-08-05 | ARCRED             | L   | 1.000      | -            | -                | -                | -         |   -28.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           86 |       53 | 2024-08-04 | Nemiga             | L   | 1.000      | -            | -                | -                | -         |   -26.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           85 |      331 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      379 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      384 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.538 (0.350)    | 1 (1.000) |     9.91 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      410 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      422 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.173 (0.112)    | 0.422 (0.274)    | 1 (1.000) |    12.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      457 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.590 (0.384)    | 1 (1.000) |     3.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      646 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | -         |     5.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      774 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.435 (0.218)    | -         |     2.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |     1056 | 2024-06-16 | Complexity         | L   | 0.858      | -            | -                | -                | -         |    -7.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1122 | 2024-06-14 | The MongolZ        | W   | 0.846      | 0.500        | 1.000 (0.423)    | 0.694 (0.294)    | 1 (0.846) |    24.74 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1132 | 2024-06-14 | Falcons            | W   | 0.845      | 0.500        | 0.219 (0.093)    | -                | 1 (0.845) |    13.14 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1232 | 2024-06-10 | 9 Pandas           | W   | 0.819      | -            | -                | -                | -         |     3.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1237 | 2024-06-10 | Monte              | W   | 0.819      | -            | -                | -                | -         |     2.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1241 | 2024-06-10 | SAW                | L   | 0.819      | -            | -                | -                | -         |   -20.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1266 | 2024-06-09 | Monte              | L   | 0.813      | -            | -                | -                | -         |   -23.31 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1273 | 2024-06-09 | PARIVISION         | W   | 0.813      | -            | -                | -                | -         |     3.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1281 | 2024-06-09 | RUSH B             | L   | 0.813      | -            | -                | -                | -         |   -24.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1289 | 2024-06-09 | 3DMAX              | L   | 0.812      | -            | -                | -                | -         |   -12.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1297 | 2024-06-09 | SINNERS            | L   | 0.812      | -            | -                | -                | -         |   -23.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1384 | 2024-06-07 | Sangal             | L   | 0.801      | -            | -                | -                | -         |   -21.91 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1399 | 2024-06-07 | Verdant            | W   | 0.800      | -            | -                | -                | -         |     0.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1403 | 2024-06-07 | PERA               | W   | 0.799      | -            | -                | -                | -         |     0.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1450 | 2024-06-06 | RUSH B             | W   | 0.794      | -            | -                | -                | -         |     0.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1512 | 2024-06-05 | PARIVISION         | W   | 0.787      | 0.500        | -                | 0.590 (0.232)    | -         |     2.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1560 | 2024-06-04 | 3DMAX              | L   | 0.781      | -            | -                | -                | -         |   -12.04 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1625 | 2024-06-01 | BLEED              | L   | 0.764      | -            | -                | -                | -         |   -17.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1650 | 2024-06-01 | Lynn Vision        | W   | 0.759      | 0.500        | 0.086 (0.033)    | -                | 1 (0.759) |     1.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1659 | 2024-05-31 | Chinggis Warriors  | W   | 0.757      | -            | -                | -                | 1 (0.757) |     1.01 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1734 | 2024-05-29 | The MongolZ        | L   | 0.739      | -            | -                | -                | -         |    -2.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1757 | 2024-05-28 | Lynn Vision        | W   | 0.731      | -            | -                | -                | 1 (0.731) |     1.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1928 | 2024-05-21 | Astralis           | L   | 0.686      | -            | -                | -                | -         |    -5.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2059 | 2024-05-17 | SAW                | W   | 0.658      | 0.769        | 0.104 (0.053)    | 0.516 (0.261)    | -         |     2.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2074 | 2024-05-16 | PARIVISION         | W   | 0.655      | 0.769        | -                | 0.590 (0.297)    | -         |     1.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2082 | 2024-05-16 | MIBR               | L   | 0.654      | -            | -                | -                | -         |   -13.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2096 | 2024-05-16 | SAW                | L   | 0.652      | -            | -                | -                | -         |   -18.44 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2146 | 2024-05-15 | Spirit             | L   | 0.645      | -            | -                | -                | -         |    -2.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2289 | 2024-05-10 | MOUZ NXT           | L   | 0.614      | -            | -                | -                | -         |   -18.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2546 | 2024-04-28 | MIBR               | L   | 0.532      | -            | -                | -                | -         |   -12.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2548 | 2024-04-27 | Rebels             | W   | 0.531      | 0.500        | -                | 0.578 (0.153)    | 1 (0.531) |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2574 | 2024-04-27 | Party Astronauts   | W   | 0.525      | -            | -                | -                | -         |     0.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2599 | 2024-04-25 | Apeks              | L   | 0.517      | -            | -                | -                | -         |   -15.96 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2603 | 2024-04-25 | Party Astronauts   | W   | 0.516      | -            | -                | -                | -         |     0.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2807 | 2024-04-18 | RUBY               | L   | 0.467      | -            | -                | -                | -         |   -14.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2919 | 2024-04-14 | OG                 | W   | 0.440      | 0.684        | 0.137 (0.041)    | -                | -         |     0.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2932 | 2024-04-13 | BetBoom            | W   | 0.433      | 0.684        | 0.248 (0.073)    | -                | -         |     2.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2944 | 2024-04-12 | AMKAL              | W   | 0.427      | -            | -                | -                | -         |     0.74 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2967 | 2024-04-11 | BetBoom            | W   | 0.421      | -            | -                | -                | -         |     2.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2974 | 2024-04-11 | Apeks              | W   | 0.420      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2979 | 2024-04-11 | FORZE              | W   | 0.419      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     3008 | 2024-04-10 | PARIVISION         | W   | 0.414      | -            | -                | -                | -         |     0.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     3020 | 2024-04-10 | BetBoom            | L   | 0.413      | -            | -                | -                | -         |   -10.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3069 | 2024-04-09 | KOI                | L   | 0.407      | -            | -                | -                | -         |   -12.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3077 | 2024-04-09 | 1WIN               | W   | 0.406      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3085 | 2024-04-09 | 9 Pandas           | W   | 0.406      | -            | -                | -                | -         |     0.31 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3095 | 2024-04-08 | Metizport          | W   | 0.401      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3100 | 2024-04-08 | OG                 | W   | 0.400      | 0.684        | 0.137 (0.037)    | -                | -         |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3110 | 2024-04-08 | 1WIN               | L   | 0.399      | -            | -                | -                | -         |   -12.39 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3203 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.374      | -            | -                | -                | -         |     5.88 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3243 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.367      | -            | -                | -                | -         |     5.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3281 | 2024-04-02 | Apeks              | W   | 0.361      | -            | -                | -                | -         |     0.16 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3290 | 2024-04-02 | Metizport          | W   | 0.360      | -            | -                | -                | -         |     0.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3302 | 2024-04-01 | SINNERS            | L   | 0.354      | -            | -                | -                | -         |   -10.62 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3341 | 2024-03-28 | brazylijski luz    | W   | 0.327      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3372 | 2024-03-27 | Metizport          | W   | 0.321      | -            | -                | -                | -         |     0.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3379 | 2024-03-27 | AURA               | W   | 0.321      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3413 | 2024-03-25 | Rebels             | W   | 0.307      | -            | -                | -                | -         |     0.20 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3429 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.294      | -            | -                | -                | -         |     0.18 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3443 | 2024-03-22 | ex-Sprout          | W   | 0.287      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3567 | 2024-03-16 | Gods Reign         | W   | 0.246      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3588 | 2024-03-15 | Gods Reign         | W   | 0.238      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3623 | 2024-03-14 | Bad News Kangaroos | W   | 0.231      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3882 | 2024-03-04 | Young Ninjas       | L   | 0.167      | -            | -                | -                | -         |    -5.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3929 | 2024-03-02 | Rebels             | W   | 0.154      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3952 | 2024-03-01 | FORZE              | W   | 0.148      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3954 | 2024-03-01 | 9 Pandas           | W   | 0.147      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3960 | 2024-02-29 | KOI                | W   | 0.141      | -            | -                | -                | -         |     0.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3963 | 2024-02-29 | Spirit Academy     | W   | 0.140      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3969 | 2024-02-29 | HAVU               | W   | 0.139      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3972 | 2024-02-28 | kONO               | W   | 0.134      | -            | -                | -                | -         |     0.03 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3978 | 2024-02-28 | FORZE              | L   | 0.133      | -            | -                | -                | -         |    -4.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4199 | 2024-02-18 | Monte              | L   | 0.068      | -            | -                | -                | -         |    -2.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4208 | 2024-02-18 | B8                 | W   | 0.066      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4226 | 2024-02-17 | kONO               | W   | 0.061      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4230 | 2024-02-17 | Monte              | L   | 0.060      | -            | -                | -                | -         |    -1.86 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4233 | 2024-02-17 | kONO               | W   | 0.060      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($134,563.95)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.860 | $10,000.00     | $8,597.22       |
| 2024-06-09 |      0.814 | $8,500.00      | $6,915.10       |
| 2024-06-02 |      0.765 | $15,000.00     | $11,480.90      |
| 2024-05-23 |      0.700 | $12,500.00     | $8,744.79       |
| 2024-04-28 |      0.532 | $20,000.00     | $10,634.26      |
| 2024-04-14 |      0.440 | $105,000.00    | $46,185.42      |
| 2024-03-16 |      0.246 | $28,500.00     | $7,006.25       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
