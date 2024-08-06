### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1391.5<br />
<br />
Final Rank Value (1391.5) = Starting Rank Value (1683.2) + Head To Head Adjustments (-291.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.727[<sup>1</sup>](#table2)
- Bounty Collected: 0.503[<sup>2</sup>](#table1)
- Opponent Network: 0.293[<sup>2</sup>](#table1)
- LAN Wins: 0.978[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1683.2
- 400 + ( ( 0.625 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1683.2


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
|           87 |        7 | 2024-08-05 | ARCRED             | L   | 1.000      | -            | -                | -                | -         |   -28.81 | deko, KENSI, Lack1, Norwi, r3salt     |
|           86 |       39 | 2024-08-04 | Nemiga             | L   | 1.000      | -            | -                | -                | -         |   -26.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           85 |      317 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      365 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      370 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.550 (0.358)    | 1 (1.000) |     9.93 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      396 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      408 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.173 (0.113)    | 0.431 (0.280)    | 1 (1.000) |    12.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      443 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.564 (0.367)    | 1 (1.000) |     3.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      632 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.164 (0.082)    | 0.933 (0.466)    | -         |     5.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      760 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.445 (0.223)    | -         |     2.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |     1042 | 2024-06-16 | Complexity         | L   | 0.859      | -            | -                | -                | -         |    -7.77 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1108 | 2024-06-14 | The MongolZ        | W   | 0.848      | 0.500        | 1.000 (0.424)    | 0.709 (0.301)    | 1 (0.848) |    24.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1118 | 2024-06-14 | Falcons            | W   | 0.847      | 0.500        | 0.220 (0.093)    | -                | 1 (0.847) |    13.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1218 | 2024-06-10 | 9 Pandas           | W   | 0.821      | -            | -                | -                | -         |     3.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1223 | 2024-06-10 | Monte              | W   | 0.820      | -            | -                | -                | -         |     2.67 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1227 | 2024-06-10 | SAW                | L   | 0.820      | -            | -                | -                | -         |   -20.96 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1252 | 2024-06-09 | Monte              | L   | 0.815      | -            | -                | -                | -         |   -23.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1259 | 2024-06-09 | PARIVISION         | W   | 0.815      | -            | -                | -                | -         |     3.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1267 | 2024-06-09 | RUSH B             | L   | 0.814      | -            | -                | -                | -         |   -24.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1275 | 2024-06-09 | 3DMAX              | L   | 0.814      | -            | -                | -                | -         |   -12.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1283 | 2024-06-09 | SINNERS            | L   | 0.813      | -            | -                | -                | -         |   -23.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1370 | 2024-06-07 | Sangal             | L   | 0.802      | -            | -                | -                | -         |   -21.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1385 | 2024-06-07 | Verdant            | W   | 0.801      | -            | -                | -                | -         |     0.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1389 | 2024-06-07 | PERA               | W   | 0.801      | -            | -                | -                | -         |     0.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1436 | 2024-06-06 | RUSH B             | W   | 0.795      | -            | -                | -                | -         |     0.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1498 | 2024-06-05 | PARIVISION         | W   | 0.789      | 0.500        | -                | 0.564 (0.222)    | -         |     2.04 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1546 | 2024-06-04 | 3DMAX              | L   | 0.782      | -            | -                | -                | -         |   -11.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1611 | 2024-06-01 | BLEED              | L   | 0.765      | -            | -                | -                | -         |   -17.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1636 | 2024-06-01 | Lynn Vision        | W   | 0.761      | 0.500        | 0.086 (0.033)    | -                | 1 (0.761) |     1.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1645 | 2024-05-31 | Chinggis Warriors  | W   | 0.759      | -            | -                | -                | 1 (0.759) |     0.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1720 | 2024-05-29 | The MongolZ        | L   | 0.740      | -            | -                | -                | -         |    -2.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1743 | 2024-05-28 | Lynn Vision        | W   | 0.733      | -            | -                | -                | 1 (0.733) |     1.22 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1914 | 2024-05-21 | Astralis           | L   | 0.687      | -            | -                | -                | -         |    -5.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2045 | 2024-05-17 | SAW                | W   | 0.660      | 0.769        | 0.104 (0.053)    | 0.528 (0.268)    | -         |     2.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2060 | 2024-05-16 | PARIVISION         | W   | 0.656      | 0.769        | -                | 0.564 (0.285)    | -         |     1.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2068 | 2024-05-16 | MIBR               | L   | 0.655      | -            | -                | -                | -         |   -13.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2082 | 2024-05-16 | SAW                | L   | 0.653      | -            | -                | -                | -         |   -18.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2132 | 2024-05-15 | Spirit             | L   | 0.647      | -            | -                | -                | -         |    -2.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2275 | 2024-05-10 | MOUZ NXT           | L   | 0.616      | -            | -                | -                | -         |   -18.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2532 | 2024-04-28 | MIBR               | L   | 0.533      | -            | -                | -                | -         |   -12.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2534 | 2024-04-27 | Rebels             | W   | 0.532      | 0.500        | -                | 0.591 (0.157)    | 1 (0.532) |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2560 | 2024-04-27 | Party Astronauts   | W   | 0.526      | -            | -                | -                | -         |     0.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2585 | 2024-04-25 | Apeks              | L   | 0.519      | -            | -                | -                | -         |   -16.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2589 | 2024-04-25 | Party Astronauts   | W   | 0.518      | -            | -                | -                | -         |     0.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2793 | 2024-04-18 | RUBY               | L   | 0.468      | -            | -                | -                | -         |   -14.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2905 | 2024-04-14 | OG                 | W   | 0.441      | 0.684        | 0.137 (0.041)    | -                | -         |     0.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2918 | 2024-04-13 | BetBoom            | W   | 0.435      | 0.684        | 0.248 (0.074)    | -                | -         |     2.90 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2930 | 2024-04-12 | AMKAL              | W   | 0.429      | -            | -                | -                | -         |     0.75 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2953 | 2024-04-11 | BetBoom            | W   | 0.422      | -            | -                | -                | -         |     2.88 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2960 | 2024-04-11 | Apeks              | W   | 0.422      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2965 | 2024-04-11 | FORZE              | W   | 0.421      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2994 | 2024-04-10 | PARIVISION         | W   | 0.416      | -            | -                | -                | -         |     0.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     3006 | 2024-04-10 | BetBoom            | L   | 0.415      | -            | -                | -                | -         |   -10.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3055 | 2024-04-09 | KOI                | L   | 0.409      | -            | -                | -                | -         |   -12.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3063 | 2024-04-09 | 1WIN               | W   | 0.408      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3071 | 2024-04-09 | 9 Pandas           | W   | 0.407      | -            | -                | -                | -         |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3081 | 2024-04-08 | Metizport          | W   | 0.402      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3086 | 2024-04-08 | OG                 | W   | 0.402      | 0.684        | 0.137 (0.038)    | -                | -         |     0.31 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3096 | 2024-04-08 | 1WIN               | L   | 0.401      | -            | -                | -                | -         |   -12.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3189 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.375      | -            | -                | -                | -         |     5.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3229 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.369      | -            | -                | -                | -         |     6.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3267 | 2024-04-02 | Apeks              | W   | 0.362      | -            | -                | -                | -         |     0.16 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3276 | 2024-04-02 | Metizport          | W   | 0.361      | -            | -                | -                | -         |     0.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3288 | 2024-04-01 | SINNERS            | L   | 0.356      | -            | -                | -                | -         |   -10.66 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3327 | 2024-03-28 | brazylijski luz    | W   | 0.329      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3358 | 2024-03-27 | Metizport          | W   | 0.323      | -            | -                | -                | -         |     0.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3365 | 2024-03-27 | AURA               | W   | 0.322      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3399 | 2024-03-25 | Rebels             | W   | 0.309      | -            | -                | -                | -         |     0.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3415 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.296      | -            | -                | -                | -         |     0.19 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3429 | 2024-03-22 | ex-Sprout          | W   | 0.289      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3553 | 2024-03-16 | Gods Reign         | W   | 0.247      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3574 | 2024-03-15 | Gods Reign         | W   | 0.240      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3609 | 2024-03-14 | Bad News Kangaroos | W   | 0.233      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3868 | 2024-03-04 | Young Ninjas       | L   | 0.168      | -            | -                | -                | -         |    -5.27 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3915 | 2024-03-02 | Rebels             | W   | 0.155      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3938 | 2024-03-01 | FORZE              | W   | 0.149      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3940 | 2024-03-01 | 9 Pandas           | W   | 0.148      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3946 | 2024-02-29 | KOI                | W   | 0.142      | -            | -                | -                | -         |     0.16 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3949 | 2024-02-29 | Spirit Academy     | W   | 0.141      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3955 | 2024-02-29 | HAVU               | W   | 0.140      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3958 | 2024-02-28 | kONO               | W   | 0.136      | -            | -                | -                | -         |     0.03 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3964 | 2024-02-28 | FORZE              | L   | 0.135      | -            | -                | -                | -         |    -4.19 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4185 | 2024-02-18 | Monte              | L   | 0.069      | -            | -                | -                | -         |    -2.14 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4194 | 2024-02-18 | B8                 | W   | 0.068      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4212 | 2024-02-17 | kONO               | W   | 0.062      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4216 | 2024-02-17 | Monte              | L   | 0.062      | -            | -                | -                | -         |    -1.90 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4219 | 2024-02-17 | kONO               | W   | 0.061      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($134,841.03)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.861 | $10,000.00     | $8,611.11       |
| 2024-06-09 |      0.815 | $8,500.00      | $6,926.91       |
| 2024-06-02 |      0.767 | $15,000.00     | $11,501.74      |
| 2024-05-23 |      0.701 | $12,500.00     | $8,762.15       |
| 2024-04-28 |      0.533 | $20,000.00     | $10,662.04      |
| 2024-04-14 |      0.441 | $105,000.00    | $46,331.25      |
| 2024-03-16 |      0.247 | $28,500.00     | $7,045.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
