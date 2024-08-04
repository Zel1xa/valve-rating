### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1413.3<br />
<br />
Final Rank Value (1413.3) = Starting Rank Value (1677.1) + Head To Head Adjustments (-263.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.728[<sup>1</sup>](#table2)
- Bounty Collected: 0.505[<sup>2</sup>](#table1)
- Opponent Network: 0.287[<sup>2</sup>](#table1)
- LAN Wins: 0.979[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1677.1
- 400 + ( ( 0.625 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1677.1


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
|           86 |        5 | 2024-08-04 | Nemiga             | L   | 1.000      | -            | -                | -                | -         |   -26.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           85 |      284 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      332 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.39 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      337 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.517 (0.336)    | 1 (1.000) |    10.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      363 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      375 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.169 (0.110)    | 0.400 (0.260)    | 1 (1.000) |    12.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      410 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.534 (0.347)    | 1 (1.000) |     3.39 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      599 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.912 (0.456)    | -         |     5.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      727 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.453 (0.226)    | -         |     2.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |     1009 | 2024-06-16 | Complexity         | L   | 0.871      | -            | -                | -                | -         |    -7.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1075 | 2024-06-14 | The MongolZ        | W   | 0.860      | 0.500        | 1.000 (0.430)    | 0.721 (0.310)    | 1 (0.860) |    25.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1085 | 2024-06-14 | Falcons            | W   | 0.858      | 0.500        | 0.223 (0.096)    | -                | 1 (0.858) |    13.90 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1185 | 2024-06-10 | 9 Pandas           | W   | 0.833      | -            | -                | -                | -         |     3.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1190 | 2024-06-10 | Monte              | W   | 0.832      | -            | -                | -                | -         |     2.81 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1194 | 2024-06-10 | SAW                | L   | 0.832      | -            | -                | -                | -         |   -20.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1219 | 2024-06-09 | Monte              | L   | 0.827      | -            | -                | -                | -         |   -23.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1226 | 2024-06-09 | PARIVISION         | W   | 0.826      | -            | -                | -                | -         |     3.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1234 | 2024-06-09 | RUSH B             | L   | 0.826      | -            | -                | -                | -         |   -24.87 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1242 | 2024-06-09 | 3DMAX              | L   | 0.826      | -            | -                | -                | -         |   -12.71 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1250 | 2024-06-09 | SINNERS            | L   | 0.825      | -            | -                | -                | -         |   -24.15 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1337 | 2024-06-07 | Sangal             | L   | 0.814      | -            | -                | -                | -         |   -22.22 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1352 | 2024-06-07 | Verdant            | W   | 0.813      | -            | -                | -                | -         |     0.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1356 | 2024-06-07 | PERA               | W   | 0.813      | -            | -                | -                | -         |     1.05 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1403 | 2024-06-06 | RUSH B             | W   | 0.807      | -            | -                | -                | -         |     0.68 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1465 | 2024-06-05 | PARIVISION         | W   | 0.800      | 0.500        | -                | 0.534 (0.214)    | -         |     2.09 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1513 | 2024-06-04 | 3DMAX              | L   | 0.794      | -            | -                | -                | -         |   -12.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1578 | 2024-06-01 | BLEED              | L   | 0.777      | -            | -                | -                | -         |   -17.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1603 | 2024-06-01 | Lynn Vision        | W   | 0.773      | 0.500        | 0.078 (0.030)    | -                | 1 (0.773) |     1.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1612 | 2024-05-31 | Chinggis Warriors  | W   | 0.771      | -            | -                | -                | 1 (0.771) |     0.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1687 | 2024-05-29 | The MongolZ        | L   | 0.752      | -            | -                | -                | -         |    -2.93 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1710 | 2024-05-28 | Lynn Vision        | W   | 0.744      | -            | -                | -                | 1 (0.744) |     1.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1881 | 2024-05-21 | Astralis           | L   | 0.699      | -            | -                | -                | -         |    -5.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2012 | 2024-05-17 | SAW                | W   | 0.672      | 0.769        | 0.105 (0.054)    | 0.540 (0.279)    | -         |     2.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2027 | 2024-05-16 | PARIVISION         | W   | 0.668      | 0.769        | -                | 0.534 (0.274)    | -         |     1.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2035 | 2024-05-16 | MIBR               | L   | 0.667      | -            | -                | -                | -         |   -13.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2049 | 2024-05-16 | SAW                | L   | 0.665      | -            | -                | -                | -         |   -18.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2099 | 2024-05-15 | Spirit             | L   | 0.659      | -            | -                | -                | -         |    -2.87 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2242 | 2024-05-10 | MOUZ NXT           | L   | 0.627      | -            | -                | -                | -         |   -18.91 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2499 | 2024-04-28 | MIBR               | L   | 0.545      | -            | -                | -                | -         |   -12.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2501 | 2024-04-27 | Rebels             | W   | 0.544      | -            | -                | -                | 1 (0.544) |     0.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2527 | 2024-04-27 | Party Astronauts   | W   | 0.538      | -            | -                | -                | -         |     0.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2552 | 2024-04-25 | Apeks              | L   | 0.531      | -            | -                | -                | -         |   -16.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2556 | 2024-04-25 | Party Astronauts   | W   | 0.529      | -            | -                | -                | -         |     0.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2760 | 2024-04-18 | RUBY               | L   | 0.480      | -            | -                | -                | -         |   -14.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2872 | 2024-04-14 | OG                 | W   | 0.453      | 0.684        | 0.139 (0.043)    | -                | -         |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2885 | 2024-04-13 | BetBoom            | W   | 0.447      | 0.684        | 0.251 (0.077)    | 0.541 (0.165)    | -         |     3.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2897 | 2024-04-12 | AMKAL              | W   | 0.441      | -            | -                | -                | -         |     0.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2920 | 2024-04-11 | BetBoom            | W   | 0.434      | -            | -                | -                | -         |     3.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2927 | 2024-04-11 | Apeks              | W   | 0.433      | -            | -                | -                | -         |     0.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2932 | 2024-04-11 | FORZE              | W   | 0.433      | -            | -                | -                | -         |     0.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2961 | 2024-04-10 | PARIVISION         | W   | 0.427      | -            | -                | -                | -         |     0.60 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     2973 | 2024-04-10 | BetBoom            | L   | 0.427      | -            | -                | -                | -         |   -10.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3022 | 2024-04-09 | KOI                | L   | 0.421      | -            | -                | -                | -         |   -12.77 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3030 | 2024-04-09 | 1WIN               | W   | 0.420      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3038 | 2024-04-09 | 9 Pandas           | W   | 0.419      | -            | -                | -                | -         |     0.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3048 | 2024-04-08 | Metizport          | W   | 0.414      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3053 | 2024-04-08 | OG                 | W   | 0.414      | 0.684        | 0.139 (0.039)    | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3063 | 2024-04-08 | 1WIN               | L   | 0.413      | -            | -                | -                | -         |   -12.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3156 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.387      | -            | -                | -                | -         |     6.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3196 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.381      | -            | -                | -                | -         |     6.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3234 | 2024-04-02 | Apeks              | W   | 0.374      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3243 | 2024-04-02 | Metizport          | W   | 0.373      | -            | -                | -                | -         |     0.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3255 | 2024-04-01 | SINNERS            | L   | 0.367      | -            | -                | -                | -         |   -11.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3294 | 2024-03-28 | brazylijski luz    | W   | 0.340      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3325 | 2024-03-27 | Metizport          | W   | 0.335      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3332 | 2024-03-27 | AURA               | W   | 0.334      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3366 | 2024-03-25 | Rebels             | W   | 0.320      | -            | -                | -                | -         |     0.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3382 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.308      | -            | -                | -                | -         |     0.20 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3396 | 2024-03-22 | ex-Sprout          | W   | 0.300      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3520 | 2024-03-16 | Gods Reign         | W   | 0.259      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3541 | 2024-03-15 | Gods Reign         | W   | 0.252      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3576 | 2024-03-14 | Bad News Kangaroos | W   | 0.244      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3835 | 2024-03-04 | Young Ninjas       | L   | 0.180      | -            | -                | -                | -         |    -5.64 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3882 | 2024-03-02 | Rebels             | W   | 0.167      | -            | -                | -                | -         |     0.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3905 | 2024-03-01 | FORZE              | W   | 0.161      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3907 | 2024-03-01 | 9 Pandas           | W   | 0.160      | -            | -                | -                | -         |     0.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3913 | 2024-02-29 | KOI                | W   | 0.154      | -            | -                | -                | -         |     0.18 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3916 | 2024-02-29 | Spirit Academy     | W   | 0.153      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3922 | 2024-02-29 | HAVU               | W   | 0.152      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3925 | 2024-02-28 | kONO               | W   | 0.148      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3931 | 2024-02-28 | FORZE              | L   | 0.146      | -            | -                | -                | -         |    -4.56 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4152 | 2024-02-18 | Monte              | L   | 0.081      | -            | -                | -                | -         |    -2.50 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4161 | 2024-02-18 | B8                 | W   | 0.079      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4179 | 2024-02-17 | kONO               | W   | 0.074      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4183 | 2024-02-17 | Monte              | L   | 0.073      | -            | -                | -                | -         |    -2.26 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4186 | 2024-02-17 | kONO               | W   | 0.073      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($137,205.47)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.873 | $10,000.00     | $8,729.63       |
| 2024-06-09 |      0.827 | $8,500.00      | $7,027.65       |
| 2024-06-02 |      0.779 | $15,000.00     | $11,679.51      |
| 2024-05-23 |      0.713 | $12,500.00     | $8,910.30       |
| 2024-04-28 |      0.545 | $20,000.00     | $10,899.07      |
| 2024-04-14 |      0.453 | $105,000.00    | $47,575.69      |
| 2024-03-16 |      0.259 | $28,500.00     | $7,383.61       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
