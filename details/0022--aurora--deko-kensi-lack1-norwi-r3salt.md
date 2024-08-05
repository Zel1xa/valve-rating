### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1389.7<br />
<br />
Final Rank Value (1389.7) = Starting Rank Value (1682.2) + Head To Head Adjustments (-292.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.727[<sup>1</sup>](#table2)
- Bounty Collected: 0.504[<sup>2</sup>](#table1)
- Opponent Network: 0.291[<sup>2</sup>](#table1)
- LAN Wins: 0.978[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1682.2
- 400 + ( ( 0.625 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1682.2


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
|           87 |        1 | 2024-08-05 | ARCRED             | L   | 1.000      | -            | -                | -                | -         |   -28.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           86 |       33 | 2024-08-04 | Nemiga             | L   | 1.000      | -            | -                | -                | -         |   -26.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           85 |      311 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      359 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      364 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.511 (0.332)    | 1 (1.000) |     9.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      390 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      402 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.174 (0.113)    | 0.432 (0.281)    | 1 (1.000) |    12.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      437 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.565 (0.367)    | 1 (1.000) |     3.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      626 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.165 (0.082)    | 0.935 (0.468)    | -         |     5.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      754 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.446 (0.223)    | -         |     2.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |     1036 | 2024-06-16 | Complexity         | L   | 0.864      | -            | -                | -                | -         |    -7.72 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1102 | 2024-06-14 | The MongolZ        | W   | 0.852      | 0.500        | 1.000 (0.426)    | 0.710 (0.303)    | 1 (0.852) |    24.96 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1112 | 2024-06-14 | Falcons            | W   | 0.851      | 0.500        | 0.221 (0.094)    | -                | 1 (0.851) |    13.48 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1212 | 2024-06-10 | 9 Pandas           | W   | 0.825      | -            | -                | -                | -         |     3.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1217 | 2024-06-10 | Monte              | W   | 0.825      | -            | -                | -                | -         |     2.71 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1221 | 2024-06-10 | SAW                | L   | 0.824      | -            | -                | -                | -         |   -20.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1246 | 2024-06-09 | Monte              | L   | 0.819      | -            | -                | -                | -         |   -23.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1253 | 2024-06-09 | PARIVISION         | W   | 0.819      | -            | -                | -                | -         |     3.31 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1261 | 2024-06-09 | RUSH B             | L   | 0.818      | -            | -                | -                | -         |   -24.68 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1269 | 2024-06-09 | 3DMAX              | L   | 0.818      | -            | -                | -                | -         |   -12.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1277 | 2024-06-09 | SINNERS            | L   | 0.818      | -            | -                | -                | -         |   -23.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1364 | 2024-06-07 | Sangal             | L   | 0.806      | -            | -                | -                | -         |   -22.05 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1379 | 2024-06-07 | Verdant            | W   | 0.805      | -            | -                | -                | -         |     0.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1383 | 2024-06-07 | PERA               | W   | 0.805      | -            | -                | -                | -         |     1.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1430 | 2024-06-06 | RUSH B             | W   | 0.800      | -            | -                | -                | -         |     0.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1492 | 2024-06-05 | PARIVISION         | W   | 0.793      | 0.500        | -                | 0.565 (0.224)    | -         |     2.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1540 | 2024-06-04 | 3DMAX              | L   | 0.786      | -            | -                | -                | -         |   -12.08 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1605 | 2024-06-01 | BLEED              | L   | 0.769      | -            | -                | -                | -         |   -17.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1630 | 2024-06-01 | Lynn Vision        | W   | 0.765      | 0.500        | 0.086 (0.033)    | -                | 1 (0.765) |     1.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1639 | 2024-05-31 | Chinggis Warriors  | W   | 0.763      | -            | -                | -                | 1 (0.763) |     0.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1714 | 2024-05-29 | The MongolZ        | L   | 0.745      | -            | -                | -                | -         |    -2.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1737 | 2024-05-28 | Lynn Vision        | W   | 0.737      | -            | -                | -                | 1 (0.737) |     1.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1908 | 2024-05-21 | Astralis           | L   | 0.692      | -            | -                | -                | -         |    -5.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2039 | 2024-05-17 | SAW                | W   | 0.664      | 0.769        | 0.104 (0.053)    | 0.530 (0.270)    | -         |     2.64 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2054 | 2024-05-16 | PARIVISION         | W   | 0.661      | 0.769        | -                | 0.565 (0.287)    | -         |     1.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2062 | 2024-05-16 | MIBR               | L   | 0.660      | -            | -                | -                | -         |   -13.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2076 | 2024-05-16 | SAW                | L   | 0.658      | -            | -                | -                | -         |   -18.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2126 | 2024-05-15 | Spirit             | L   | 0.651      | -            | -                | -                | -         |    -2.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2269 | 2024-05-10 | MOUZ NXT           | L   | 0.620      | -            | -                | -                | -         |   -18.70 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2526 | 2024-04-28 | MIBR               | L   | 0.537      | -            | -                | -                | -         |   -12.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2528 | 2024-04-27 | Rebels             | W   | 0.537      | -            | -                | -                | 1 (0.537) |     0.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2554 | 2024-04-27 | Party Astronauts   | W   | 0.530      | -            | -                | -                | -         |     0.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2579 | 2024-04-25 | Apeks              | L   | 0.523      | -            | -                | -                | -         |   -16.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2583 | 2024-04-25 | Party Astronauts   | W   | 0.522      | -            | -                | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2787 | 2024-04-18 | RUBY               | L   | 0.473      | -            | -                | -                | -         |   -14.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2899 | 2024-04-14 | OG                 | W   | 0.446      | 0.684        | 0.138 (0.042)    | -                | -         |     0.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2912 | 2024-04-13 | BetBoom            | W   | 0.439      | 0.684        | 0.249 (0.075)    | 0.529 (0.159)    | -         |     2.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2924 | 2024-04-12 | AMKAL              | W   | 0.433      | -            | -                | -                | -         |     0.76 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2947 | 2024-04-11 | BetBoom            | W   | 0.427      | -            | -                | -                | -         |     2.96 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2954 | 2024-04-11 | Apeks              | W   | 0.426      | -            | -                | -                | -         |     0.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2959 | 2024-04-11 | FORZE              | W   | 0.425      | -            | -                | -                | -         |     0.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2988 | 2024-04-10 | PARIVISION         | W   | 0.420      | -            | -                | -                | -         |     0.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     3000 | 2024-04-10 | BetBoom            | L   | 0.419      | -            | -                | -                | -         |   -10.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3049 | 2024-04-09 | KOI                | L   | 0.413      | -            | -                | -                | -         |   -12.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3057 | 2024-04-09 | 1WIN               | W   | 0.412      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3065 | 2024-04-09 | 9 Pandas           | W   | 0.411      | -            | -                | -                | -         |     0.31 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3075 | 2024-04-08 | Metizport          | W   | 0.407      | -            | -                | -                | -         |     0.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3080 | 2024-04-08 | OG                 | W   | 0.406      | 0.684        | 0.138 (0.038)    | -                | -         |     0.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3090 | 2024-04-08 | 1WIN               | L   | 0.405      | -            | -                | -                | -         |   -12.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3183 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.380      | -            | -                | -                | -         |     6.08 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3223 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.373      | -            | -                | -                | -         |     6.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3261 | 2024-04-02 | Apeks              | W   | 0.366      | -            | -                | -                | -         |     0.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3270 | 2024-04-02 | Metizport          | W   | 0.365      | -            | -                | -                | -         |     0.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3282 | 2024-04-01 | SINNERS            | L   | 0.360      | -            | -                | -                | -         |   -10.78 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3321 | 2024-03-28 | brazylijski luz    | W   | 0.333      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3352 | 2024-03-27 | Metizport          | W   | 0.327      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3359 | 2024-03-27 | AURA               | W   | 0.327      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3393 | 2024-03-25 | Rebels             | W   | 0.313      | -            | -                | -                | -         |     0.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3409 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.300      | -            | -                | -                | -         |     0.19 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3423 | 2024-03-22 | ex-Sprout          | W   | 0.293      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3547 | 2024-03-16 | Gods Reign         | W   | 0.252      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3568 | 2024-03-15 | Gods Reign         | W   | 0.244      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3603 | 2024-03-14 | Bad News Kangaroos | W   | 0.237      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3862 | 2024-03-04 | Young Ninjas       | L   | 0.173      | -            | -                | -                | -         |    -5.41 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3909 | 2024-03-02 | Rebels             | W   | 0.159      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3932 | 2024-03-01 | FORZE              | W   | 0.153      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3934 | 2024-03-01 | 9 Pandas           | W   | 0.152      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3940 | 2024-02-29 | KOI                | W   | 0.147      | -            | -                | -                | -         |     0.17 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3943 | 2024-02-29 | Spirit Academy     | W   | 0.146      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3949 | 2024-02-29 | HAVU               | W   | 0.144      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3952 | 2024-02-28 | kONO               | W   | 0.140      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3958 | 2024-02-28 | FORZE              | L   | 0.139      | -            | -                | -                | -         |    -4.32 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4179 | 2024-02-18 | Monte              | L   | 0.074      | -            | -                | -                | -         |    -2.27 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4188 | 2024-02-18 | B8                 | W   | 0.072      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4206 | 2024-02-17 | kONO               | W   | 0.066      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4210 | 2024-02-17 | Monte              | L   | 0.066      | -            | -                | -                | -         |    -2.03 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4213 | 2024-02-17 | kONO               | W   | 0.065      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($135,699.99)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.865 | $10,000.00     | $8,654.17       |
| 2024-06-09 |      0.819 | $8,500.00      | $6,963.51       |
| 2024-06-02 |      0.771 | $15,000.00     | $11,566.32      |
| 2024-05-23 |      0.705 | $12,500.00     | $8,815.97       |
| 2024-04-28 |      0.537 | $20,000.00     | $10,748.15      |
| 2024-04-14 |      0.446 | $105,000.00    | $46,783.33      |
| 2024-03-16 |      0.252 | $28,500.00     | $7,168.54       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
