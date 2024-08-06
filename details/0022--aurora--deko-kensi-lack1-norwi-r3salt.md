### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1393.6<br />
<br />
Final Rank Value (1393.6) = Starting Rank Value (1685.9) + Head To Head Adjustments (-292.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.727[<sup>1</sup>](#table2)
- Bounty Collected: 0.504[<sup>2</sup>](#table1)
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
|           87 |       19 | 2024-08-05 | ARCRED             | L   | 1.000      | -            | -                | -                | -         |   -28.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           86 |       51 | 2024-08-04 | Nemiga             | L   | 1.000      | -            | -                | -                | -         |   -26.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           85 |      329 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      377 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      382 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.538 (0.350)    | 1 (1.000) |     9.91 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      408 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      420 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.173 (0.113)    | 0.422 (0.274)    | 1 (1.000) |    12.14 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      455 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.590 (0.384)    | 1 (1.000) |     3.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      644 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | -         |     5.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      772 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.435 (0.218)    | -         |     2.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |     1054 | 2024-06-16 | Complexity         | L   | 0.858      | -            | -                | -                | -         |    -7.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1120 | 2024-06-14 | The MongolZ        | W   | 0.847      | 0.500        | 1.000 (0.423)    | 0.694 (0.294)    | 1 (0.847) |    24.75 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1130 | 2024-06-14 | Falcons            | W   | 0.845      | 0.500        | 0.219 (0.093)    | -                | 1 (0.845) |    13.15 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1230 | 2024-06-10 | 9 Pandas           | W   | 0.820      | -            | -                | -                | -         |     3.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1235 | 2024-06-10 | Monte              | W   | 0.819      | -            | -                | -                | -         |     2.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1239 | 2024-06-10 | SAW                | L   | 0.819      | -            | -                | -                | -         |   -21.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1264 | 2024-06-09 | Monte              | L   | 0.814      | -            | -                | -                | -         |   -23.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1271 | 2024-06-09 | PARIVISION         | W   | 0.813      | -            | -                | -                | -         |     3.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1279 | 2024-06-09 | RUSH B             | L   | 0.813      | -            | -                | -                | -         |   -24.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1287 | 2024-06-09 | 3DMAX              | L   | 0.813      | -            | -                | -                | -         |   -12.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1295 | 2024-06-09 | SINNERS            | L   | 0.812      | -            | -                | -                | -         |   -23.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1382 | 2024-06-07 | Sangal             | L   | 0.801      | -            | -                | -                | -         |   -21.92 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1397 | 2024-06-07 | Verdant            | W   | 0.800      | -            | -                | -                | -         |     0.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1401 | 2024-06-07 | PERA               | W   | 0.800      | -            | -                | -                | -         |     0.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1448 | 2024-06-06 | RUSH B             | W   | 0.794      | -            | -                | -                | -         |     0.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1510 | 2024-06-05 | PARIVISION         | W   | 0.787      | 0.500        | -                | 0.590 (0.232)    | -         |     2.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1558 | 2024-06-04 | 3DMAX              | L   | 0.781      | -            | -                | -                | -         |   -12.04 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1623 | 2024-06-01 | BLEED              | L   | 0.764      | -            | -                | -                | -         |   -17.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1648 | 2024-06-01 | Lynn Vision        | W   | 0.760      | 0.500        | 0.086 (0.033)    | -                | 1 (0.760) |     1.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1657 | 2024-05-31 | Chinggis Warriors  | W   | 0.758      | -            | -                | -                | 1 (0.758) |     1.01 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1732 | 2024-05-29 | The MongolZ        | L   | 0.739      | -            | -                | -                | -         |    -2.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1755 | 2024-05-28 | Lynn Vision        | W   | 0.731      | -            | -                | -                | 1 (0.731) |     1.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1926 | 2024-05-21 | Astralis           | L   | 0.686      | -            | -                | -                | -         |    -5.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2057 | 2024-05-17 | SAW                | W   | 0.659      | 0.769        | 0.104 (0.053)    | 0.516 (0.261)    | -         |     2.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2072 | 2024-05-16 | PARIVISION         | W   | 0.655      | 0.769        | -                | 0.590 (0.297)    | -         |     1.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2080 | 2024-05-16 | MIBR               | L   | 0.654      | -            | -                | -                | -         |   -13.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2094 | 2024-05-16 | SAW                | L   | 0.652      | -            | -                | -                | -         |   -18.44 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2144 | 2024-05-15 | Spirit             | L   | 0.645      | -            | -                | -                | -         |    -2.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2287 | 2024-05-10 | MOUZ NXT           | L   | 0.614      | -            | -                | -                | -         |   -18.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2544 | 2024-04-28 | MIBR               | L   | 0.532      | -            | -                | -                | -         |   -12.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2546 | 2024-04-27 | Rebels             | W   | 0.531      | 0.500        | -                | 0.578 (0.154)    | 1 (0.531) |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2572 | 2024-04-27 | Party Astronauts   | W   | 0.525      | -            | -                | -                | -         |     0.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2597 | 2024-04-25 | Apeks              | L   | 0.518      | -            | -                | -                | -         |   -15.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2601 | 2024-04-25 | Party Astronauts   | W   | 0.516      | -            | -                | -                | -         |     0.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2805 | 2024-04-18 | RUBY               | L   | 0.467      | -            | -                | -                | -         |   -14.44 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2917 | 2024-04-14 | OG                 | W   | 0.440      | 0.684        | 0.137 (0.041)    | -                | -         |     0.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2930 | 2024-04-13 | BetBoom            | W   | 0.434      | 0.684        | 0.248 (0.073)    | -                | -         |     2.85 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2942 | 2024-04-12 | AMKAL              | W   | 0.428      | -            | -                | -                | -         |     0.74 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2965 | 2024-04-11 | BetBoom            | W   | 0.421      | -            | -                | -                | -         |     2.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2972 | 2024-04-11 | Apeks              | W   | 0.420      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2977 | 2024-04-11 | FORZE              | W   | 0.420      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     3006 | 2024-04-10 | PARIVISION         | W   | 0.414      | -            | -                | -                | -         |     0.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     3018 | 2024-04-10 | BetBoom            | L   | 0.414      | -            | -                | -                | -         |   -10.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3067 | 2024-04-09 | KOI                | L   | 0.408      | -            | -                | -                | -         |   -12.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3075 | 2024-04-09 | 1WIN               | W   | 0.407      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3083 | 2024-04-09 | 9 Pandas           | W   | 0.406      | -            | -                | -                | -         |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3093 | 2024-04-08 | Metizport          | W   | 0.401      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3098 | 2024-04-08 | OG                 | W   | 0.401      | 0.684        | 0.137 (0.037)    | -                | -         |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3108 | 2024-04-08 | 1WIN               | L   | 0.400      | -            | -                | -                | -         |   -12.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3201 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.374      | -            | -                | -                | -         |     5.88 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3241 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.368      | -            | -                | -                | -         |     5.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3279 | 2024-04-02 | Apeks              | W   | 0.361      | -            | -                | -                | -         |     0.16 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3288 | 2024-04-02 | Metizport          | W   | 0.360      | -            | -                | -                | -         |     0.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3300 | 2024-04-01 | SINNERS            | L   | 0.354      | -            | -                | -                | -         |   -10.63 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3339 | 2024-03-28 | brazylijski luz    | W   | 0.327      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3370 | 2024-03-27 | Metizport          | W   | 0.322      | -            | -                | -                | -         |     0.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3377 | 2024-03-27 | AURA               | W   | 0.321      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3411 | 2024-03-25 | Rebels             | W   | 0.307      | -            | -                | -                | -         |     0.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3427 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.295      | -            | -                | -                | -         |     0.19 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3441 | 2024-03-22 | ex-Sprout          | W   | 0.287      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3565 | 2024-03-16 | Gods Reign         | W   | 0.246      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3586 | 2024-03-15 | Gods Reign         | W   | 0.239      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3621 | 2024-03-14 | Bad News Kangaroos | W   | 0.231      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3880 | 2024-03-04 | Young Ninjas       | L   | 0.167      | -            | -                | -                | -         |    -5.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3927 | 2024-03-02 | Rebels             | W   | 0.154      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3950 | 2024-03-01 | FORZE              | W   | 0.148      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3952 | 2024-03-01 | 9 Pandas           | W   | 0.147      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3958 | 2024-02-29 | KOI                | W   | 0.141      | -            | -                | -                | -         |     0.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3961 | 2024-02-29 | Spirit Academy     | W   | 0.140      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3967 | 2024-02-29 | HAVU               | W   | 0.139      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3970 | 2024-02-28 | kONO               | W   | 0.134      | -            | -                | -                | -         |     0.03 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3976 | 2024-02-28 | FORZE              | L   | 0.133      | -            | -                | -                | -         |    -4.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4197 | 2024-02-18 | Monte              | L   | 0.068      | -            | -                | -                | -         |    -2.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4206 | 2024-02-18 | B8                 | W   | 0.066      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4224 | 2024-02-17 | kONO               | W   | 0.061      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4228 | 2024-02-17 | Monte              | L   | 0.060      | -            | -                | -                | -         |    -1.86 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4231 | 2024-02-17 | kONO               | W   | 0.060      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($134,600.89)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.860 | $10,000.00     | $8,599.07       |
| 2024-06-09 |      0.814 | $8,500.00      | $6,916.68       |
| 2024-06-02 |      0.766 | $15,000.00     | $11,483.68      |
| 2024-05-23 |      0.700 | $12,500.00     | $8,747.11       |
| 2024-04-28 |      0.532 | $20,000.00     | $10,637.96      |
| 2024-04-14 |      0.440 | $105,000.00    | $46,204.86      |
| 2024-03-16 |      0.246 | $28,500.00     | $7,011.53       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
