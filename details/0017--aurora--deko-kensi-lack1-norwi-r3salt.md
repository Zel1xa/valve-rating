### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1436.0<br />
<br />
Final Rank Value (1436.0) = Starting Rank Value (1677.4) + Head To Head Adjustments (-241.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.729[<sup>1</sup>](#table2)
- Bounty Collected: 0.505[<sup>2</sup>](#table1)
- Opponent Network: 0.288[<sup>2</sup>](#table1)
- LAN Wins: 0.979[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1677.4
- 400 + ( ( 0.625 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1677.4


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
|           85 |      250 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      298 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      303 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.516 (0.336)    | 1 (1.000) |    10.04 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      329 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      341 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.170 (0.110)    | 0.401 (0.261)    | 1 (1.000) |    12.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      376 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.534 (0.347)    | 1 (1.000) |     3.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      562 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.913 (0.456)    | -         |     5.73 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      692 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.453 (0.226)    | -         |     2.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |      974 | 2024-06-16 | Complexity         | L   | 0.876      | -            | -                | -                | -         |    -7.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1040 | 2024-06-14 | The MongolZ        | W   | 0.864      | 0.500        | 1.000 (0.432)    | 0.720 (0.311)    | 1 (0.864) |    25.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1050 | 2024-06-14 | Falcons            | W   | 0.863      | 0.500        | 0.225 (0.097)    | -                | 1 (0.863) |    14.10 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1150 | 2024-06-10 | 9 Pandas           | W   | 0.837      | -            | -                | -                | -         |     3.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1155 | 2024-06-10 | Monte              | W   | 0.837      | -            | -                | -                | -         |     2.87 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1159 | 2024-06-10 | SAW                | L   | 0.836      | -            | -                | -                | -         |   -21.03 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1184 | 2024-06-09 | Monte              | L   | 0.831      | -            | -                | -                | -         |   -23.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1191 | 2024-06-09 | PARIVISION         | W   | 0.831      | -            | -                | -                | -         |     3.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1199 | 2024-06-09 | RUSH B             | L   | 0.831      | -            | -                | -                | -         |   -25.05 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1207 | 2024-06-09 | 3DMAX              | L   | 0.830      | -            | -                | -                | -         |   -12.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1215 | 2024-06-09 | SINNERS            | L   | 0.830      | -            | -                | -                | -         |   -24.45 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1302 | 2024-06-07 | Sangal             | L   | 0.818      | -            | -                | -                | -         |   -22.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1317 | 2024-06-07 | Verdant            | W   | 0.818      | -            | -                | -                | -         |     0.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1321 | 2024-06-07 | PERA               | W   | 0.817      | -            | -                | -                | -         |     1.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1368 | 2024-06-06 | RUSH B             | W   | 0.812      | -            | -                | -                | -         |     0.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1430 | 2024-06-05 | PARIVISION         | W   | 0.805      | 0.500        | -                | 0.534 (0.215)    | -         |     2.12 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1478 | 2024-06-04 | 3DMAX              | L   | 0.798      | -            | -                | -                | -         |   -12.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1543 | 2024-06-01 | BLEED              | L   | 0.781      | -            | -                | -                | -         |   -17.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1568 | 2024-06-01 | Lynn Vision        | W   | 0.777      | 0.500        | 0.078 (0.030)    | -                | 1 (0.777) |     1.09 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1577 | 2024-05-31 | Chinggis Warriors  | W   | 0.775      | -            | -                | -                | 1 (0.775) |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1652 | 2024-05-29 | The MongolZ        | L   | 0.757      | -            | -                | -                | -         |    -2.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1675 | 2024-05-28 | Lynn Vision        | W   | 0.749      | -            | -                | -                | 1 (0.749) |     0.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1846 | 2024-05-21 | Astralis           | L   | 0.704      | -            | -                | -                | -         |    -6.15 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     1977 | 2024-05-17 | SAW                | W   | 0.676      | 0.769        | 0.106 (0.055)    | 0.541 (0.281)    | -         |     2.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     1992 | 2024-05-16 | PARIVISION         | W   | 0.673      | 0.769        | -                | 0.534 (0.276)    | -         |     1.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2000 | 2024-05-16 | MIBR               | L   | 0.672      | -            | -                | -                | -         |   -13.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2014 | 2024-05-16 | SAW                | L   | 0.670      | -            | -                | -                | -         |   -18.72 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2064 | 2024-05-15 | Spirit             | L   | 0.663      | -            | -                | -                | -         |    -2.90 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2207 | 2024-05-10 | MOUZ NXT           | L   | 0.632      | -            | -                | -                | -         |   -19.05 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2464 | 2024-04-28 | MIBR               | L   | 0.549      | -            | -                | -                | -         |   -12.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2466 | 2024-04-27 | Rebels             | W   | 0.549      | -            | -                | -                | 1 (0.549) |     0.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2492 | 2024-04-27 | Party Astronauts   | W   | 0.542      | -            | -                | -                | -         |     0.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2516 | 2024-04-25 | Apeks              | L   | 0.535      | -            | -                | -                | -         |   -16.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2520 | 2024-04-25 | Party Astronauts   | W   | 0.534      | -            | -                | -                | -         |     0.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2724 | 2024-04-18 | RUBY               | L   | 0.485      | -            | -                | -                | -         |   -14.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2836 | 2024-04-14 | OG                 | W   | 0.458      | 0.684        | 0.140 (0.044)    | -                | -         |     0.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2849 | 2024-04-13 | BetBoom            | W   | 0.451      | 0.684        | 0.252 (0.078)    | 0.543 (0.168)    | -         |     3.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2861 | 2024-04-12 | AMKAL              | W   | 0.445      | -            | -                | -                | -         |     0.81 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2884 | 2024-04-11 | BetBoom            | W   | 0.439      | -            | -                | -                | -         |     3.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2891 | 2024-04-11 | Apeks              | W   | 0.438      | -            | -                | -                | -         |     0.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2896 | 2024-04-11 | FORZE              | W   | 0.437      | -            | -                | -                | -         |     0.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2925 | 2024-04-10 | PARIVISION         | W   | 0.432      | -            | -                | -                | -         |     0.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     2937 | 2024-04-10 | BetBoom            | L   | 0.431      | -            | -                | -                | -         |   -10.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     2986 | 2024-04-09 | KOI                | L   | 0.425      | -            | -                | -                | -         |   -12.90 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     2994 | 2024-04-09 | 1WIN               | W   | 0.424      | -            | -                | -                | -         |     0.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3002 | 2024-04-09 | 9 Pandas           | W   | 0.423      | -            | -                | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3012 | 2024-04-08 | Metizport          | W   | 0.419      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3017 | 2024-04-08 | OG                 | W   | 0.418      | 0.684        | 0.140 (0.040)    | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3027 | 2024-04-08 | 1WIN               | L   | 0.417      | -            | -                | -                | -         |   -12.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3120 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.392      | -            | -                | -                | -         |     6.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3160 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.385      | -            | -                | -                | -         |     6.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3198 | 2024-04-02 | Apeks              | W   | 0.378      | -            | -                | -                | -         |     0.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3207 | 2024-04-02 | Metizport          | W   | 0.377      | -            | -                | -                | -         |     0.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3219 | 2024-04-01 | SINNERS            | L   | 0.372      | -            | -                | -                | -         |   -11.29 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3258 | 2024-03-28 | brazylijski luz    | W   | 0.345      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3289 | 2024-03-27 | Metizport          | W   | 0.339      | -            | -                | -                | -         |     0.16 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3296 | 2024-03-27 | AURA               | W   | 0.339      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3330 | 2024-03-25 | Rebels             | W   | 0.325      | -            | -                | -                | -         |     0.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3346 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.312      | -            | -                | -                | -         |     0.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3360 | 2024-03-22 | ex-Sprout          | W   | 0.305      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3484 | 2024-03-16 | Gods Reign         | W   | 0.264      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3505 | 2024-03-15 | Gods Reign         | W   | 0.256      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3540 | 2024-03-14 | Bad News Kangaroos | W   | 0.249      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3798 | 2024-03-04 | Young Ninjas       | L   | 0.185      | -            | -                | -                | -         |    -5.78 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3845 | 2024-03-02 | Rebels             | W   | 0.171      | -            | -                | -                | -         |     0.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3868 | 2024-03-01 | FORZE              | W   | 0.165      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3870 | 2024-03-01 | 9 Pandas           | W   | 0.164      | -            | -                | -                | -         |     0.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3876 | 2024-02-29 | KOI                | W   | 0.159      | -            | -                | -                | -         |     0.19 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3879 | 2024-02-29 | Spirit Academy     | W   | 0.158      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3885 | 2024-02-29 | HAVU               | W   | 0.156      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3888 | 2024-02-28 | kONO               | W   | 0.152      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3894 | 2024-02-28 | FORZE              | L   | 0.151      | -            | -                | -                | -         |    -4.70 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4115 | 2024-02-18 | Monte              | L   | 0.086      | -            | -                | -                | -         |    -2.64 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4124 | 2024-02-18 | B8                 | W   | 0.084      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4141 | 2024-02-17 | kONO               | W   | 0.078      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4145 | 2024-02-17 | Monte              | L   | 0.078      | -            | -                | -                | -         |    -2.40 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4148 | 2024-02-17 | kONO               | W   | 0.078      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($138,110.61)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.877 | $10,000.00     | $8,775.00       |
| 2024-06-09 |      0.831 | $8,500.00      | $7,066.22       |
| 2024-06-02 |      0.783 | $15,000.00     | $11,747.57      |
| 2024-05-23 |      0.717 | $12,500.00     | $8,967.01       |
| 2024-04-28 |      0.549 | $20,000.00     | $10,989.81      |
| 2024-04-14 |      0.458 | $105,000.00    | $48,052.08      |
| 2024-03-16 |      0.264 | $28,500.00     | $7,512.92       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
