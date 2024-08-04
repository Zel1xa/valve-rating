### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1436.5<br />
<br />
Final Rank Value (1436.5) = Starting Rank Value (1677.2) + Head To Head Adjustments (-240.7)<br />

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
|           85 |      253 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      301 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      306 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.517 (0.336)    | 1 (1.000) |    10.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      332 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      344 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.169 (0.110)    | 0.400 (0.260)    | 1 (1.000) |    12.14 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      379 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.534 (0.347)    | 1 (1.000) |     3.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      565 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.912 (0.456)    | -         |     5.70 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      695 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.453 (0.226)    | -         |     2.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |      978 | 2024-06-16 | Complexity         | L   | 0.873      | -            | -                | -                | -         |    -7.81 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1044 | 2024-06-14 | The MongolZ        | W   | 0.861      | 0.500        | 1.000 (0.431)    | 0.721 (0.310)    | 1 (0.861) |    25.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1054 | 2024-06-14 | Falcons            | W   | 0.860      | 0.500        | 0.224 (0.096)    | -                | 1 (0.860) |    13.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1154 | 2024-06-10 | 9 Pandas           | W   | 0.834      | -            | -                | -                | -         |     3.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1159 | 2024-06-10 | Monte              | W   | 0.834      | -            | -                | -                | -         |     2.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1163 | 2024-06-10 | SAW                | L   | 0.833      | -            | -                | -                | -         |   -21.01 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1188 | 2024-06-09 | Monte              | L   | 0.828      | -            | -                | -                | -         |   -23.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1195 | 2024-06-09 | PARIVISION         | W   | 0.828      | -            | -                | -                | -         |     3.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1203 | 2024-06-09 | RUSH B             | L   | 0.828      | -            | -                | -                | -         |   -24.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1211 | 2024-06-09 | 3DMAX              | L   | 0.827      | -            | -                | -                | -         |   -12.71 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1219 | 2024-06-09 | SINNERS            | L   | 0.827      | -            | -                | -                | -         |   -24.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1306 | 2024-06-07 | Sangal             | L   | 0.815      | -            | -                | -                | -         |   -22.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1321 | 2024-06-07 | Verdant            | W   | 0.815      | -            | -                | -                | -         |     0.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1325 | 2024-06-07 | PERA               | W   | 0.814      | -            | -                | -                | -         |     1.05 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1372 | 2024-06-06 | RUSH B             | W   | 0.809      | -            | -                | -                | -         |     0.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1434 | 2024-06-05 | PARIVISION         | W   | 0.802      | 0.500        | -                | 0.534 (0.214)    | -         |     2.10 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1482 | 2024-06-04 | 3DMAX              | L   | 0.795      | -            | -                | -                | -         |   -12.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1547 | 2024-06-01 | BLEED              | L   | 0.778      | -            | -                | -                | -         |   -17.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1572 | 2024-06-01 | Lynn Vision        | W   | 0.774      | 0.500        | 0.078 (0.030)    | -                | 1 (0.774) |     1.08 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1581 | 2024-05-31 | Chinggis Warriors  | W   | 0.772      | -            | -                | -                | 1 (0.772) |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1656 | 2024-05-29 | The MongolZ        | L   | 0.754      | -            | -                | -                | -         |    -2.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1679 | 2024-05-28 | Lynn Vision        | W   | 0.746      | -            | -                | -                | 1 (0.746) |     0.92 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1850 | 2024-05-21 | Astralis           | L   | 0.701      | -            | -                | -                | -         |    -6.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     1981 | 2024-05-17 | SAW                | W   | 0.673      | 0.769        | 0.105 (0.054)    | 0.540 (0.279)    | -         |     2.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     1996 | 2024-05-16 | PARIVISION         | W   | 0.670      | 0.769        | -                | 0.534 (0.275)    | -         |     1.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2004 | 2024-05-16 | MIBR               | L   | 0.669      | -            | -                | -                | -         |   -13.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2018 | 2024-05-16 | SAW                | L   | 0.667      | -            | -                | -                | -         |   -18.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2068 | 2024-05-15 | Spirit             | L   | 0.660      | -            | -                | -                | -         |    -2.90 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2211 | 2024-05-10 | MOUZ NXT           | L   | 0.629      | -            | -                | -                | -         |   -18.96 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2468 | 2024-04-28 | MIBR               | L   | 0.546      | -            | -                | -                | -         |   -12.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2470 | 2024-04-27 | Rebels             | W   | 0.546      | -            | -                | -                | 1 (0.546) |     0.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2496 | 2024-04-27 | Party Astronauts   | W   | 0.539      | -            | -                | -                | -         |     0.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2521 | 2024-04-25 | Apeks              | L   | 0.532      | -            | -                | -                | -         |   -16.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2525 | 2024-04-25 | Party Astronauts   | W   | 0.531      | -            | -                | -                | -         |     0.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2729 | 2024-04-18 | RUBY               | L   | 0.482      | -            | -                | -                | -         |   -14.87 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2841 | 2024-04-14 | OG                 | W   | 0.455      | 0.684        | 0.139 (0.043)    | -                | -         |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2854 | 2024-04-13 | BetBoom            | W   | 0.448      | 0.684        | 0.251 (0.077)    | 0.542 (0.166)    | -         |     3.15 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2866 | 2024-04-12 | AMKAL              | W   | 0.442      | -            | -                | -                | -         |     0.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2889 | 2024-04-11 | BetBoom            | W   | 0.436      | -            | -                | -                | -         |     3.14 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2896 | 2024-04-11 | Apeks              | W   | 0.435      | -            | -                | -                | -         |     0.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2901 | 2024-04-11 | FORZE              | W   | 0.434      | -            | -                | -                | -         |     0.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2930 | 2024-04-10 | PARIVISION         | W   | 0.429      | -            | -                | -                | -         |     0.60 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     2942 | 2024-04-10 | BetBoom            | L   | 0.428      | -            | -                | -                | -         |   -10.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     2991 | 2024-04-09 | KOI                | L   | 0.422      | -            | -                | -                | -         |   -12.81 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     2999 | 2024-04-09 | 1WIN               | W   | 0.421      | -            | -                | -                | -         |     0.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3007 | 2024-04-09 | 9 Pandas           | W   | 0.420      | -            | -                | -                | -         |     0.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3017 | 2024-04-08 | Metizport          | W   | 0.416      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3022 | 2024-04-08 | OG                 | W   | 0.415      | 0.684        | 0.139 (0.039)    | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3032 | 2024-04-08 | 1WIN               | L   | 0.414      | -            | -                | -                | -         |   -12.88 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3125 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.389      | -            | -                | -                | -         |     6.11 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3165 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.382      | -            | -                | -                | -         |     6.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3203 | 2024-04-02 | Apeks              | W   | 0.375      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3212 | 2024-04-02 | Metizport          | W   | 0.374      | -            | -                | -                | -         |     0.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3224 | 2024-04-01 | SINNERS            | L   | 0.369      | -            | -                | -                | -         |   -11.20 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3263 | 2024-03-28 | brazylijski luz    | W   | 0.342      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3294 | 2024-03-27 | Metizport          | W   | 0.336      | -            | -                | -                | -         |     0.16 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3301 | 2024-03-27 | AURA               | W   | 0.336      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3335 | 2024-03-25 | Rebels             | W   | 0.322      | -            | -                | -                | -         |     0.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3351 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.309      | -            | -                | -                | -         |     0.20 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3365 | 2024-03-22 | ex-Sprout          | W   | 0.302      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3489 | 2024-03-16 | Gods Reign         | W   | 0.261      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3510 | 2024-03-15 | Gods Reign         | W   | 0.253      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3545 | 2024-03-14 | Bad News Kangaroos | W   | 0.246      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3804 | 2024-03-04 | Young Ninjas       | L   | 0.182      | -            | -                | -                | -         |    -5.69 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3851 | 2024-03-02 | Rebels             | W   | 0.168      | -            | -                | -                | -         |     0.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3874 | 2024-03-01 | FORZE              | W   | 0.162      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3876 | 2024-03-01 | 9 Pandas           | W   | 0.161      | -            | -                | -                | -         |     0.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3882 | 2024-02-29 | KOI                | W   | 0.156      | -            | -                | -                | -         |     0.18 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3885 | 2024-02-29 | Spirit Academy     | W   | 0.155      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3891 | 2024-02-29 | HAVU               | W   | 0.153      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3894 | 2024-02-28 | kONO               | W   | 0.149      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3900 | 2024-02-28 | FORZE              | L   | 0.148      | -            | -                | -                | -         |    -4.60 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4121 | 2024-02-18 | Monte              | L   | 0.083      | -            | -                | -                | -         |    -2.55 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4130 | 2024-02-18 | B8                 | W   | 0.081      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4148 | 2024-02-17 | kONO               | W   | 0.075      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4152 | 2024-02-17 | Monte              | L   | 0.075      | -            | -                | -                | -         |    -2.31 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4155 | 2024-02-17 | kONO               | W   | 0.075      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($137,501.03)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.874 | $10,000.00     | $8,744.44       |
| 2024-06-09 |      0.828 | $8,500.00      | $7,040.24       |
| 2024-06-02 |      0.780 | $15,000.00     | $11,701.74      |
| 2024-05-23 |      0.714 | $12,500.00     | $8,928.82       |
| 2024-04-28 |      0.546 | $20,000.00     | $10,928.70      |
| 2024-04-14 |      0.455 | $105,000.00    | $47,731.25      |
| 2024-03-16 |      0.261 | $28,500.00     | $7,425.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
