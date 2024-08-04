### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1413.8<br />
<br />
Final Rank Value (1413.8) = Starting Rank Value (1678.1) + Head To Head Adjustments (-264.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.728[<sup>1</sup>](#table2)
- Bounty Collected: 0.505[<sup>2</sup>](#table1)
- Opponent Network: 0.289[<sup>2</sup>](#table1)
- LAN Wins: 0.979[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1678.1
- 400 + ( ( 0.625 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1678.1


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
|           86 |        6 | 2024-08-04 | Nemiga             | L   | 1.000      | -            | -                | -                | -         |   -26.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           85 |      285 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      333 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      338 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.517 (0.336)    | 1 (1.000) |    10.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      364 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      376 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.169 (0.110)    | 0.400 (0.260)    | 1 (1.000) |    12.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      411 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.534 (0.347)    | 1 (1.000) |     3.39 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      600 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.951 (0.476)    | -         |     5.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      728 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.453 (0.226)    | -         |     2.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |     1010 | 2024-06-16 | Complexity         | L   | 0.871      | -            | -                | -                | -         |    -7.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1076 | 2024-06-14 | The MongolZ        | W   | 0.859      | 0.500        | 1.000 (0.430)    | 0.721 (0.310)    | 1 (0.859) |    25.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1086 | 2024-06-14 | Falcons            | W   | 0.858      | 0.500        | 0.223 (0.096)    | -                | 1 (0.858) |    13.87 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1186 | 2024-06-10 | 9 Pandas           | W   | 0.832      | -            | -                | -                | -         |     3.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1191 | 2024-06-10 | Monte              | W   | 0.832      | -            | -                | -                | -         |     2.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1195 | 2024-06-10 | SAW                | L   | 0.832      | -            | -                | -                | -         |   -20.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1220 | 2024-06-09 | Monte              | L   | 0.826      | -            | -                | -                | -         |   -23.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1227 | 2024-06-09 | PARIVISION         | W   | 0.826      | -            | -                | -                | -         |     3.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1235 | 2024-06-09 | RUSH B             | L   | 0.826      | -            | -                | -                | -         |   -24.86 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1243 | 2024-06-09 | 3DMAX              | L   | 0.825      | -            | -                | -                | -         |   -12.72 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1251 | 2024-06-09 | SINNERS            | L   | 0.825      | -            | -                | -                | -         |   -24.15 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1338 | 2024-06-07 | Sangal             | L   | 0.814      | -            | -                | -                | -         |   -22.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1353 | 2024-06-07 | Verdant            | W   | 0.813      | -            | -                | -                | -         |     0.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1357 | 2024-06-07 | PERA               | W   | 0.812      | -            | -                | -                | -         |     1.04 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1404 | 2024-06-06 | RUSH B             | W   | 0.807      | -            | -                | -                | -         |     0.68 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1466 | 2024-06-05 | PARIVISION         | W   | 0.800      | 0.500        | -                | 0.534 (0.214)    | -         |     2.09 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1514 | 2024-06-04 | 3DMAX              | L   | 0.793      | -            | -                | -                | -         |   -12.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1579 | 2024-06-01 | BLEED              | L   | 0.777      | -            | -                | -                | -         |   -17.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1604 | 2024-06-01 | Lynn Vision        | W   | 0.772      | 0.500        | 0.078 (0.030)    | -                | 1 (0.772) |     1.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1613 | 2024-05-31 | Chinggis Warriors  | W   | 0.770      | -            | -                | -                | 1 (0.770) |     0.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1688 | 2024-05-29 | The MongolZ        | L   | 0.752      | -            | -                | -                | -         |    -2.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1711 | 2024-05-28 | Lynn Vision        | W   | 0.744      | -            | -                | -                | 1 (0.744) |     1.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1882 | 2024-05-21 | Astralis           | L   | 0.699      | -            | -                | -                | -         |    -5.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2013 | 2024-05-17 | SAW                | W   | 0.671      | 0.769        | 0.105 (0.054)    | 0.540 (0.279)    | -         |     2.78 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2028 | 2024-05-16 | PARIVISION         | W   | 0.668      | 0.769        | -                | 0.534 (0.274)    | -         |     1.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2036 | 2024-05-16 | MIBR               | L   | 0.667      | -            | -                | -                | -         |   -13.48 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2050 | 2024-05-16 | SAW                | L   | 0.665      | -            | -                | -                | -         |   -18.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2100 | 2024-05-15 | Spirit             | L   | 0.658      | -            | -                | -                | -         |    -2.89 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2243 | 2024-05-10 | MOUZ NXT           | L   | 0.627      | -            | -                | -                | -         |   -18.91 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2500 | 2024-04-28 | MIBR               | L   | 0.545      | -            | -                | -                | -         |   -12.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2502 | 2024-04-27 | Rebels             | W   | 0.544      | -            | -                | -                | 1 (0.544) |     0.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2528 | 2024-04-27 | Party Astronauts   | W   | 0.538      | -            | -                | -                | -         |     0.39 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2553 | 2024-04-25 | Apeks              | L   | 0.530      | -            | -                | -                | -         |   -16.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2557 | 2024-04-25 | Party Astronauts   | W   | 0.529      | -            | -                | -                | -         |     0.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2761 | 2024-04-18 | RUBY               | L   | 0.480      | -            | -                | -                | -         |   -14.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2873 | 2024-04-14 | OG                 | W   | 0.453      | 0.684        | 0.139 (0.043)    | -                | -         |     0.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2886 | 2024-04-13 | BetBoom            | W   | 0.446      | 0.684        | 0.251 (0.076)    | 0.541 (0.165)    | -         |     3.12 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2898 | 2024-04-12 | AMKAL              | W   | 0.440      | -            | -                | -                | -         |     0.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2921 | 2024-04-11 | BetBoom            | W   | 0.434      | -            | -                | -                | -         |     3.11 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2928 | 2024-04-11 | Apeks              | W   | 0.433      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2933 | 2024-04-11 | FORZE              | W   | 0.432      | -            | -                | -                | -         |     0.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2962 | 2024-04-10 | PARIVISION         | W   | 0.427      | -            | -                | -                | -         |     0.60 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     2974 | 2024-04-10 | BetBoom            | L   | 0.426      | -            | -                | -                | -         |   -10.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3023 | 2024-04-09 | KOI                | L   | 0.420      | -            | -                | -                | -         |   -12.76 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3031 | 2024-04-09 | 1WIN               | W   | 0.419      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3039 | 2024-04-09 | 9 Pandas           | W   | 0.418      | -            | -                | -                | -         |     0.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3049 | 2024-04-08 | Metizport          | W   | 0.414      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3054 | 2024-04-08 | OG                 | W   | 0.413      | 0.684        | 0.139 (0.039)    | -                | -         |     0.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3064 | 2024-04-08 | 1WIN               | L   | 0.412      | -            | -                | -                | -         |   -12.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3157 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.387      | -            | -                | -                | -         |     6.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3197 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.380      | -            | -                | -                | -         |     6.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3235 | 2024-04-02 | Apeks              | W   | 0.374      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3244 | 2024-04-02 | Metizport          | W   | 0.373      | -            | -                | -                | -         |     0.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3256 | 2024-04-01 | SINNERS            | L   | 0.367      | -            | -                | -                | -         |   -11.00 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3295 | 2024-03-28 | brazylijski luz    | W   | 0.340      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3326 | 2024-03-27 | Metizport          | W   | 0.334      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3333 | 2024-03-27 | AURA               | W   | 0.334      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3367 | 2024-03-25 | Rebels             | W   | 0.320      | -            | -                | -                | -         |     0.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3383 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.307      | -            | -                | -                | -         |     0.20 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3397 | 2024-03-22 | ex-Sprout          | W   | 0.300      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3521 | 2024-03-16 | Gods Reign         | W   | 0.259      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3542 | 2024-03-15 | Gods Reign         | W   | 0.251      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3577 | 2024-03-14 | Bad News Kangaroos | W   | 0.244      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3836 | 2024-03-04 | Young Ninjas       | L   | 0.180      | -            | -                | -                | -         |    -5.63 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3883 | 2024-03-02 | Rebels             | W   | 0.167      | -            | -                | -                | -         |     0.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3906 | 2024-03-01 | FORZE              | W   | 0.161      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3908 | 2024-03-01 | 9 Pandas           | W   | 0.159      | -            | -                | -                | -         |     0.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3914 | 2024-02-29 | KOI                | W   | 0.154      | -            | -                | -                | -         |     0.18 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3917 | 2024-02-29 | Spirit Academy     | W   | 0.153      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3923 | 2024-02-29 | HAVU               | W   | 0.152      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3926 | 2024-02-28 | kONO               | W   | 0.147      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3932 | 2024-02-28 | FORZE              | L   | 0.146      | -            | -                | -                | -         |    -4.55 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4153 | 2024-02-18 | Monte              | L   | 0.081      | -            | -                | -                | -         |    -2.49 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4162 | 2024-02-18 | B8                 | W   | 0.079      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4180 | 2024-02-17 | kONO               | W   | 0.074      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4184 | 2024-02-17 | Monte              | L   | 0.073      | -            | -                | -                | -         |    -2.25 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4187 | 2024-02-17 | kONO               | W   | 0.073      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($137,145.44)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.873 | $10,000.00     | $8,726.62       |
| 2024-06-09 |      0.826 | $8,500.00      | $7,025.09       |
| 2024-06-02 |      0.778 | $15,000.00     | $11,675.00      |
| 2024-05-23 |      0.713 | $12,500.00     | $8,906.54       |
| 2024-04-28 |      0.545 | $20,000.00     | $10,893.06      |
| 2024-04-14 |      0.453 | $105,000.00    | $47,544.10      |
| 2024-03-16 |      0.259 | $28,500.00     | $7,375.03       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
