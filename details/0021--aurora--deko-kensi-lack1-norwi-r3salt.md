### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1416.4<br />
<br />
Final Rank Value (1416.4) = Starting Rank Value (1679.2) + Head To Head Adjustments (-262.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.727[<sup>1</sup>](#table2)
- Bounty Collected: 0.504[<sup>2</sup>](#table1)
- Opponent Network: 0.289[<sup>2</sup>](#table1)
- LAN Wins: 0.978[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1679.2
- 400 + ( ( 0.625 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1679.2


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
|           86 |       23 | 2024-08-04 | Nemiga             | L   | 1.000      | -            | -                | -                | -         |   -26.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           85 |      302 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      350 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      355 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.517 (0.336)    | 1 (1.000) |     9.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      381 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      393 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.168 (0.109)    | 0.438 (0.285)    | 1 (1.000) |    12.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      428 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.532 (0.346)    | 1 (1.000) |     3.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      617 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.165 (0.082)    | 0.947 (0.474)    | -         |     5.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      745 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.451 (0.226)    | -         |     2.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |     1027 | 2024-06-16 | Complexity         | L   | 0.865      | -            | -                | -                | -         |    -7.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1093 | 2024-06-14 | The MongolZ        | W   | 0.854      | 0.500        | 1.000 (0.427)    | 0.719 (0.307)    | 1 (0.854) |    25.03 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1103 | 2024-06-14 | Falcons            | W   | 0.852      | 0.500        | 0.222 (0.094)    | -                | 1 (0.852) |    13.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1203 | 2024-06-10 | 9 Pandas           | W   | 0.827      | -            | -                | -                | -         |     3.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1208 | 2024-06-10 | Monte              | W   | 0.826      | -            | -                | -                | -         |     2.75 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1212 | 2024-06-10 | SAW                | L   | 0.826      | -            | -                | -                | -         |   -20.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1237 | 2024-06-09 | Monte              | L   | 0.821      | -            | -                | -                | -         |   -23.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1244 | 2024-06-09 | PARIVISION         | W   | 0.820      | -            | -                | -                | -         |     3.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1252 | 2024-06-09 | RUSH B             | L   | 0.820      | -            | -                | -                | -         |   -24.71 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1260 | 2024-06-09 | 3DMAX              | L   | 0.820      | -            | -                | -                | -         |   -12.60 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1268 | 2024-06-09 | SINNERS            | L   | 0.819      | -            | -                | -                | -         |   -24.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1355 | 2024-06-07 | Sangal             | L   | 0.808      | -            | -                | -                | -         |   -22.07 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1370 | 2024-06-07 | Verdant            | W   | 0.807      | -            | -                | -                | -         |     0.81 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1374 | 2024-06-07 | PERA               | W   | 0.807      | -            | -                | -                | -         |     1.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1421 | 2024-06-06 | RUSH B             | W   | 0.801      | -            | -                | -                | -         |     0.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1483 | 2024-06-05 | PARIVISION         | W   | 0.794      | 0.500        | -                | 0.532 (0.211)    | -         |     2.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1531 | 2024-06-04 | 3DMAX              | L   | 0.788      | -            | -                | -                | -         |   -12.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1596 | 2024-06-01 | BLEED              | L   | 0.771      | -            | -                | -                | -         |   -17.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1621 | 2024-06-01 | Lynn Vision        | W   | 0.767      | 0.500        | 0.086 (0.033)    | -                | 1 (0.767) |     1.44 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1630 | 2024-05-31 | Chinggis Warriors  | W   | 0.765      | -            | -                | -                | 1 (0.765) |     0.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1705 | 2024-05-29 | The MongolZ        | L   | 0.746      | -            | -                | -                | -         |    -2.91 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1728 | 2024-05-28 | Lynn Vision        | W   | 0.738      | -            | -                | -                | 1 (0.738) |     1.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1899 | 2024-05-21 | Astralis           | L   | 0.693      | -            | -                | -                | -         |    -5.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2030 | 2024-05-17 | SAW                | W   | 0.666      | 0.769        | 0.105 (0.054)    | 0.537 (0.275)    | -         |     2.69 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2045 | 2024-05-16 | PARIVISION         | W   | 0.662      | 0.769        | -                | 0.532 (0.271)    | -         |     1.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2053 | 2024-05-16 | MIBR               | L   | 0.661      | -            | -                | -                | -         |   -13.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2067 | 2024-05-16 | SAW                | L   | 0.659      | -            | -                | -                | -         |   -18.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2117 | 2024-05-15 | Spirit             | L   | 0.652      | -            | -                | -                | -         |    -2.90 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2260 | 2024-05-10 | MOUZ NXT           | L   | 0.621      | -            | -                | -                | -         |   -18.74 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2517 | 2024-04-28 | MIBR               | L   | 0.539      | -            | -                | -                | -         |   -12.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2519 | 2024-04-27 | Rebels             | W   | 0.538      | -            | -                | -                | 1 (0.538) |     0.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2545 | 2024-04-27 | Party Astronauts   | W   | 0.532      | -            | -                | -                | -         |     0.39 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2570 | 2024-04-25 | Apeks              | L   | 0.525      | -            | -                | -                | -         |   -16.16 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2574 | 2024-04-25 | Party Astronauts   | W   | 0.523      | -            | -                | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2778 | 2024-04-18 | RUBY               | L   | 0.474      | -            | -                | -                | -         |   -14.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2890 | 2024-04-14 | OG                 | W   | 0.447      | 0.684        | 0.138 (0.042)    | -                | -         |     0.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2903 | 2024-04-13 | BetBoom            | W   | 0.441      | 0.684        | 0.249 (0.075)    | 0.536 (0.162)    | -         |     3.03 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2915 | 2024-04-12 | AMKAL              | W   | 0.435      | -            | -                | -                | -         |     0.77 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2938 | 2024-04-11 | BetBoom            | W   | 0.428      | -            | -                | -                | -         |     3.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2945 | 2024-04-11 | Apeks              | W   | 0.427      | -            | -                | -                | -         |     0.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2950 | 2024-04-11 | FORZE              | W   | 0.427      | -            | -                | -                | -         |     0.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2979 | 2024-04-10 | PARIVISION         | W   | 0.421      | -            | -                | -                | -         |     0.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     2991 | 2024-04-10 | BetBoom            | L   | 0.421      | -            | -                | -                | -         |   -10.45 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3040 | 2024-04-09 | KOI                | L   | 0.415      | -            | -                | -                | -         |   -12.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3048 | 2024-04-09 | 1WIN               | W   | 0.414      | -            | -                | -                | -         |     0.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3056 | 2024-04-09 | 9 Pandas           | W   | 0.413      | -            | -                | -                | -         |     0.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3066 | 2024-04-08 | Metizport          | W   | 0.408      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3071 | 2024-04-08 | OG                 | W   | 0.408      | 0.684        | 0.138 (0.038)    | -                | -         |     0.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3081 | 2024-04-08 | 1WIN               | L   | 0.407      | -            | -                | -                | -         |   -12.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3174 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.381      | -            | -                | -                | -         |     6.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3214 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.375      | -            | -                | -                | -         |     6.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3252 | 2024-04-02 | Apeks              | W   | 0.368      | -            | -                | -                | -         |     0.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3261 | 2024-04-02 | Metizport          | W   | 0.367      | -            | -                | -                | -         |     0.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3273 | 2024-04-01 | SINNERS            | L   | 0.361      | -            | -                | -                | -         |   -10.84 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3312 | 2024-03-28 | brazylijski luz    | W   | 0.334      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3343 | 2024-03-27 | Metizport          | W   | 0.329      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3350 | 2024-03-27 | AURA               | W   | 0.328      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3384 | 2024-03-25 | Rebels             | W   | 0.314      | -            | -                | -                | -         |     0.22 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3400 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.302      | -            | -                | -                | -         |     0.20 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3414 | 2024-03-22 | ex-Sprout          | W   | 0.294      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3538 | 2024-03-16 | Gods Reign         | W   | 0.253      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3559 | 2024-03-15 | Gods Reign         | W   | 0.246      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3594 | 2024-03-14 | Bad News Kangaroos | W   | 0.238      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3853 | 2024-03-04 | Young Ninjas       | L   | 0.174      | -            | -                | -                | -         |    -5.45 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3900 | 2024-03-02 | Rebels             | W   | 0.161      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3923 | 2024-03-01 | FORZE              | W   | 0.155      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3925 | 2024-03-01 | 9 Pandas           | W   | 0.154      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3931 | 2024-02-29 | KOI                | W   | 0.148      | -            | -                | -                | -         |     0.17 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3934 | 2024-02-29 | Spirit Academy     | W   | 0.147      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3940 | 2024-02-29 | HAVU               | W   | 0.146      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3943 | 2024-02-28 | kONO               | W   | 0.142      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3949 | 2024-02-28 | FORZE              | L   | 0.140      | -            | -                | -                | -         |    -4.37 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4170 | 2024-02-18 | Monte              | L   | 0.075      | -            | -                | -                | -         |    -2.32 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4179 | 2024-02-18 | B8                 | W   | 0.073      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4197 | 2024-02-17 | kONO               | W   | 0.068      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4201 | 2024-02-17 | Monte              | L   | 0.067      | -            | -                | -                | -         |    -2.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4204 | 2024-02-17 | kONO               | W   | 0.067      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($136,004.78)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.867 | $10,000.00     | $8,669.44       |
| 2024-06-09 |      0.821 | $8,500.00      | $6,976.49       |
| 2024-06-02 |      0.773 | $15,000.00     | $11,589.24      |
| 2024-05-23 |      0.707 | $12,500.00     | $8,835.07       |
| 2024-04-28 |      0.539 | $20,000.00     | $10,778.70      |
| 2024-04-14 |      0.447 | $105,000.00    | $46,943.75      |
| 2024-03-16 |      0.253 | $28,500.00     | $7,212.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
