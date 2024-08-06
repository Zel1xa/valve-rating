### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1390.0<br />
<br />
Final Rank Value (1390.0) = Starting Rank Value (1682.1) + Head To Head Adjustments (-292.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.727[<sup>1</sup>](#table2)
- Bounty Collected: 0.504[<sup>2</sup>](#table1)
- Opponent Network: 0.291[<sup>2</sup>](#table1)
- LAN Wins: 0.978[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1682.1
- 400 + ( ( 0.625 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1682.1


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
|           87 |        3 | 2024-08-05 | ARCRED             | L   | 1.000      | -            | -                | -                | -         |   -28.81 | deko, KENSI, Lack1, Norwi, r3salt     |
|           86 |       35 | 2024-08-04 | Nemiga             | L   | 1.000      | -            | -                | -                | -         |   -26.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           85 |      313 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      361 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      366 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.511 (0.332)    | 1 (1.000) |     9.96 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      392 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      404 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.174 (0.113)    | 0.432 (0.281)    | 1 (1.000) |    12.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      439 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.565 (0.367)    | 1 (1.000) |     3.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      628 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.164 (0.082)    | 0.934 (0.467)    | -         |     5.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      756 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.445 (0.223)    | -         |     2.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |     1038 | 2024-06-16 | Complexity         | L   | 0.862      | -            | -                | -                | -         |    -7.73 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1104 | 2024-06-14 | The MongolZ        | W   | 0.850      | 0.500        | 1.000 (0.425)    | 0.710 (0.302)    | 1 (0.850) |    24.90 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1114 | 2024-06-14 | Falcons            | W   | 0.849      | 0.500        | 0.221 (0.094)    | -                | 1 (0.849) |    13.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1214 | 2024-06-10 | 9 Pandas           | W   | 0.823      | -            | -                | -                | -         |     3.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1219 | 2024-06-10 | Monte              | W   | 0.823      | -            | -                | -                | -         |     2.69 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1223 | 2024-06-10 | SAW                | L   | 0.823      | -            | -                | -                | -         |   -20.96 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1248 | 2024-06-09 | Monte              | L   | 0.817      | -            | -                | -                | -         |   -23.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1255 | 2024-06-09 | PARIVISION         | W   | 0.817      | -            | -                | -                | -         |     3.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1263 | 2024-06-09 | RUSH B             | L   | 0.817      | -            | -                | -                | -         |   -24.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1271 | 2024-06-09 | 3DMAX              | L   | 0.816      | -            | -                | -                | -         |   -12.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1279 | 2024-06-09 | SINNERS            | L   | 0.816      | -            | -                | -                | -         |   -23.91 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1366 | 2024-06-07 | Sangal             | L   | 0.805      | -            | -                | -                | -         |   -22.01 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1381 | 2024-06-07 | Verdant            | W   | 0.804      | -            | -                | -                | -         |     0.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1385 | 2024-06-07 | PERA               | W   | 0.803      | -            | -                | -                | -         |     1.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1432 | 2024-06-06 | RUSH B             | W   | 0.798      | -            | -                | -                | -         |     0.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1494 | 2024-06-05 | PARIVISION         | W   | 0.791      | 0.500        | -                | 0.565 (0.223)    | -         |     2.05 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1542 | 2024-06-04 | 3DMAX              | L   | 0.784      | -            | -                | -                | -         |   -12.03 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1607 | 2024-06-01 | BLEED              | L   | 0.768      | -            | -                | -                | -         |   -17.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1632 | 2024-06-01 | Lynn Vision        | W   | 0.763      | 0.500        | 0.086 (0.033)    | -                | 1 (0.763) |     1.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1641 | 2024-05-31 | Chinggis Warriors  | W   | 0.761      | -            | -                | -                | 1 (0.761) |     0.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1716 | 2024-05-29 | The MongolZ        | L   | 0.743      | -            | -                | -                | -         |    -2.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1739 | 2024-05-28 | Lynn Vision        | W   | 0.735      | -            | -                | -                | 1 (0.735) |     1.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1910 | 2024-05-21 | Astralis           | L   | 0.690      | -            | -                | -                | -         |    -5.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2041 | 2024-05-17 | SAW                | W   | 0.662      | 0.769        | 0.104 (0.053)    | 0.529 (0.269)    | -         |     2.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2056 | 2024-05-16 | PARIVISION         | W   | 0.659      | 0.769        | -                | 0.565 (0.286)    | -         |     1.39 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2064 | 2024-05-16 | MIBR               | L   | 0.658      | -            | -                | -                | -         |   -13.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2078 | 2024-05-16 | SAW                | L   | 0.656      | -            | -                | -                | -         |   -18.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2128 | 2024-05-15 | Spirit             | L   | 0.649      | -            | -                | -                | -         |    -2.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2271 | 2024-05-10 | MOUZ NXT           | L   | 0.618      | -            | -                | -                | -         |   -18.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2528 | 2024-04-28 | MIBR               | L   | 0.536      | -            | -                | -                | -         |   -12.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2530 | 2024-04-27 | Rebels             | W   | 0.535      | 0.500        | -                | 0.591 (0.158)    | 1 (0.535) |     0.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2556 | 2024-04-27 | Party Astronauts   | W   | 0.529      | -            | -                | -                | -         |     0.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2581 | 2024-04-25 | Apeks              | L   | 0.521      | -            | -                | -                | -         |   -16.07 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2585 | 2024-04-25 | Party Astronauts   | W   | 0.520      | -            | -                | -                | -         |     0.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2789 | 2024-04-18 | RUBY               | L   | 0.471      | -            | -                | -                | -         |   -14.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2901 | 2024-04-14 | OG                 | W   | 0.444      | 0.684        | 0.137 (0.042)    | -                | -         |     0.48 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2914 | 2024-04-13 | BetBoom            | W   | 0.437      | 0.684        | 0.249 (0.074)    | -                | -         |     2.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2926 | 2024-04-12 | AMKAL              | W   | 0.431      | -            | -                | -                | -         |     0.75 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2949 | 2024-04-11 | BetBoom            | W   | 0.425      | -            | -                | -                | -         |     2.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2956 | 2024-04-11 | Apeks              | W   | 0.424      | -            | -                | -                | -         |     0.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2961 | 2024-04-11 | FORZE              | W   | 0.423      | -            | -                | -                | -         |     0.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2990 | 2024-04-10 | PARIVISION         | W   | 0.418      | -            | -                | -                | -         |     0.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     3002 | 2024-04-10 | BetBoom            | L   | 0.417      | -            | -                | -                | -         |   -10.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3051 | 2024-04-09 | KOI                | L   | 0.411      | -            | -                | -                | -         |   -12.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3059 | 2024-04-09 | 1WIN               | W   | 0.410      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3067 | 2024-04-09 | 9 Pandas           | W   | 0.409      | -            | -                | -                | -         |     0.31 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3077 | 2024-04-08 | Metizport          | W   | 0.405      | -            | -                | -                | -         |     0.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3082 | 2024-04-08 | OG                 | W   | 0.404      | 0.684        | 0.137 (0.038)    | -                | -         |     0.31 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3092 | 2024-04-08 | 1WIN               | L   | 0.403      | -            | -                | -                | -         |   -12.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3185 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.378      | -            | -                | -                | -         |     6.04 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3225 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.371      | -            | -                | -                | -         |     6.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3263 | 2024-04-02 | Apeks              | W   | 0.365      | -            | -                | -                | -         |     0.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3272 | 2024-04-02 | Metizport          | W   | 0.363      | -            | -                | -                | -         |     0.12 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3284 | 2024-04-01 | SINNERS            | L   | 0.358      | -            | -                | -                | -         |   -10.73 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3323 | 2024-03-28 | brazylijski luz    | W   | 0.331      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3354 | 2024-03-27 | Metizport          | W   | 0.325      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3361 | 2024-03-27 | AURA               | W   | 0.325      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3395 | 2024-03-25 | Rebels             | W   | 0.311      | -            | -                | -                | -         |     0.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3411 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.298      | -            | -                | -                | -         |     0.19 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3425 | 2024-03-22 | ex-Sprout          | W   | 0.291      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3549 | 2024-03-16 | Gods Reign         | W   | 0.250      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3570 | 2024-03-15 | Gods Reign         | W   | 0.242      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3605 | 2024-03-14 | Bad News Kangaroos | W   | 0.235      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3864 | 2024-03-04 | Young Ninjas       | L   | 0.171      | -            | -                | -                | -         |    -5.35 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3911 | 2024-03-02 | Rebels             | W   | 0.158      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3934 | 2024-03-01 | FORZE              | W   | 0.152      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3936 | 2024-03-01 | 9 Pandas           | W   | 0.150      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3942 | 2024-02-29 | KOI                | W   | 0.145      | -            | -                | -                | -         |     0.16 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3945 | 2024-02-29 | Spirit Academy     | W   | 0.144      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3951 | 2024-02-29 | HAVU               | W   | 0.142      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3954 | 2024-02-28 | kONO               | W   | 0.138      | -            | -                | -                | -         |     0.03 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3960 | 2024-02-28 | FORZE              | L   | 0.137      | -            | -                | -                | -         |    -4.27 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4181 | 2024-02-18 | Monte              | L   | 0.072      | -            | -                | -                | -         |    -2.22 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4190 | 2024-02-18 | B8                 | W   | 0.070      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4208 | 2024-02-17 | kONO               | W   | 0.065      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4212 | 2024-02-17 | Monte              | L   | 0.064      | -            | -                | -                | -         |    -1.98 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4215 | 2024-02-17 | kONO               | W   | 0.064      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($135,339.78)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.864 | $10,000.00     | $8,636.11       |
| 2024-06-09 |      0.817 | $8,500.00      | $6,948.16       |
| 2024-06-02 |      0.769 | $15,000.00     | $11,539.24      |
| 2024-05-23 |      0.703 | $12,500.00     | $8,793.40       |
| 2024-04-28 |      0.536 | $20,000.00     | $10,712.04      |
| 2024-04-14 |      0.444 | $105,000.00    | $46,593.75      |
| 2024-03-16 |      0.250 | $28,500.00     | $7,117.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
