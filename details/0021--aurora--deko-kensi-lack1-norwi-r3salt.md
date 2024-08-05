### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1415.1<br />
<br />
Final Rank Value (1415.1) = Starting Rank Value (1679.3) + Head To Head Adjustments (-264.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.728[<sup>1</sup>](#table2)
- Bounty Collected: 0.504[<sup>2</sup>](#table1)
- Opponent Network: 0.291[<sup>2</sup>](#table1)
- LAN Wins: 0.978[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1679.3
- 400 + ( ( 0.625 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1679.3


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
|           86 |       11 | 2024-08-04 | Nemiga             | L   | 1.000      | -            | -                | -                | -         |   -26.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           85 |      289 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      337 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      342 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.518 (0.337)    | 1 (1.000) |     9.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      368 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      380 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.168 (0.110)    | 0.439 (0.286)    | 1 (1.000) |    12.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      415 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.534 (0.347)    | 1 (1.000) |     3.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      604 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.165 (0.082)    | 0.951 (0.475)    | -         |     5.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      732 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.453 (0.226)    | -         |     2.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |     1014 | 2024-06-16 | Complexity         | L   | 0.869      | -            | -                | -                | -         |    -7.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1080 | 2024-06-14 | The MongolZ        | W   | 0.857      | 0.500        | 1.000 (0.428)    | 0.721 (0.309)    | 1 (0.857) |    25.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1090 | 2024-06-14 | Falcons            | W   | 0.856      | 0.500        | 0.223 (0.095)    | -                | 1 (0.856) |    13.77 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1190 | 2024-06-10 | 9 Pandas           | W   | 0.830      | -            | -                | -                | -         |     3.45 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1195 | 2024-06-10 | Monte              | W   | 0.830      | -            | -                | -                | -         |     2.77 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1199 | 2024-06-10 | SAW                | L   | 0.829      | -            | -                | -                | -         |   -20.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1224 | 2024-06-09 | Monte              | L   | 0.824      | -            | -                | -                | -         |   -23.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1231 | 2024-06-09 | PARIVISION         | W   | 0.824      | -            | -                | -                | -         |     3.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1239 | 2024-06-09 | RUSH B             | L   | 0.823      | -            | -                | -                | -         |   -24.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1247 | 2024-06-09 | 3DMAX              | L   | 0.823      | -            | -                | -                | -         |   -12.70 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1255 | 2024-06-09 | SINNERS            | L   | 0.823      | -            | -                | -                | -         |   -24.09 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1342 | 2024-06-07 | Sangal             | L   | 0.811      | -            | -                | -                | -         |   -22.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1357 | 2024-06-07 | Verdant            | W   | 0.810      | -            | -                | -                | -         |     0.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1361 | 2024-06-07 | PERA               | W   | 0.810      | -            | -                | -                | -         |     1.03 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1408 | 2024-06-06 | RUSH B             | W   | 0.804      | -            | -                | -                | -         |     0.67 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1470 | 2024-06-05 | PARIVISION         | W   | 0.798      | 0.500        | -                | 0.534 (0.213)    | -         |     2.07 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1518 | 2024-06-04 | 3DMAX              | L   | 0.791      | -            | -                | -                | -         |   -12.16 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1583 | 2024-06-01 | BLEED              | L   | 0.774      | -            | -                | -                | -         |   -17.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1608 | 2024-06-01 | Lynn Vision        | W   | 0.770      | 0.500        | 0.078 (0.030)    | -                | 1 (0.770) |     1.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1617 | 2024-05-31 | Chinggis Warriors  | W   | 0.768      | -            | -                | -                | 1 (0.768) |     0.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1692 | 2024-05-29 | The MongolZ        | L   | 0.749      | -            | -                | -                | -         |    -2.93 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1715 | 2024-05-28 | Lynn Vision        | W   | 0.742      | -            | -                | -                | 1 (0.742) |     1.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1886 | 2024-05-21 | Astralis           | L   | 0.697      | -            | -                | -                | -         |    -5.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2017 | 2024-05-17 | SAW                | W   | 0.669      | 0.769        | 0.105 (0.054)    | 0.539 (0.277)    | -         |     2.73 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2032 | 2024-05-16 | PARIVISION         | W   | 0.665      | 0.769        | -                | 0.534 (0.273)    | -         |     1.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2040 | 2024-05-16 | MIBR               | L   | 0.665      | -            | -                | -                | -         |   -13.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2054 | 2024-05-16 | SAW                | L   | 0.662      | -            | -                | -                | -         |   -18.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2104 | 2024-05-15 | Spirit             | L   | 0.656      | -            | -                | -                | -         |    -2.90 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2247 | 2024-05-10 | MOUZ NXT           | L   | 0.625      | -            | -                | -                | -         |   -18.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2504 | 2024-04-28 | MIBR               | L   | 0.542      | -            | -                | -                | -         |   -12.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2506 | 2024-04-27 | Rebels             | W   | 0.542      | -            | -                | -                | 1 (0.542) |     0.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2532 | 2024-04-27 | Party Astronauts   | W   | 0.535      | -            | -                | -                | -         |     0.39 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2557 | 2024-04-25 | Apeks              | L   | 0.528      | -            | -                | -                | -         |   -16.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2561 | 2024-04-25 | Party Astronauts   | W   | 0.527      | -            | -                | -                | -         |     0.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2765 | 2024-04-18 | RUBY               | L   | 0.477      | -            | -                | -                | -         |   -14.76 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2877 | 2024-04-14 | OG                 | W   | 0.450      | 0.684        | 0.138 (0.043)    | -                | -         |     0.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2890 | 2024-04-13 | BetBoom            | W   | 0.444      | 0.684        | 0.250 (0.076)    | 0.540 (0.164)    | -         |     3.07 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2902 | 2024-04-12 | AMKAL              | W   | 0.438      | -            | -                | -                | -         |     0.78 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2925 | 2024-04-11 | BetBoom            | W   | 0.432      | -            | -                | -                | -         |     3.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2932 | 2024-04-11 | Apeks              | W   | 0.431      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2937 | 2024-04-11 | FORZE              | W   | 0.430      | -            | -                | -                | -         |     0.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2966 | 2024-04-10 | PARIVISION         | W   | 0.425      | -            | -                | -                | -         |     0.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     2978 | 2024-04-10 | BetBoom            | L   | 0.424      | -            | -                | -                | -         |   -10.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3027 | 2024-04-09 | KOI                | L   | 0.418      | -            | -                | -                | -         |   -12.69 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3035 | 2024-04-09 | 1WIN               | W   | 0.417      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3043 | 2024-04-09 | 9 Pandas           | W   | 0.416      | -            | -                | -                | -         |     0.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3053 | 2024-04-08 | Metizport          | W   | 0.412      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3058 | 2024-04-08 | OG                 | W   | 0.411      | 0.684        | 0.138 (0.039)    | -                | -         |     0.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3068 | 2024-04-08 | 1WIN               | L   | 0.410      | -            | -                | -                | -         |   -12.72 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3161 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.385      | -            | -                | -                | -         |     6.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3201 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.378      | -            | -                | -                | -         |     6.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3239 | 2024-04-02 | Apeks              | W   | 0.371      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3248 | 2024-04-02 | Metizport          | W   | 0.370      | -            | -                | -                | -         |     0.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3260 | 2024-04-01 | SINNERS            | L   | 0.365      | -            | -                | -                | -         |   -10.94 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3299 | 2024-03-28 | brazylijski luz    | W   | 0.338      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3330 | 2024-03-27 | Metizport          | W   | 0.332      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3337 | 2024-03-27 | AURA               | W   | 0.332      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3371 | 2024-03-25 | Rebels             | W   | 0.318      | -            | -                | -                | -         |     0.22 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3387 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.305      | -            | -                | -                | -         |     0.20 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3401 | 2024-03-22 | ex-Sprout          | W   | 0.298      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3525 | 2024-03-16 | Gods Reign         | W   | 0.256      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3546 | 2024-03-15 | Gods Reign         | W   | 0.249      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3581 | 2024-03-14 | Bad News Kangaroos | W   | 0.242      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3840 | 2024-03-04 | Young Ninjas       | L   | 0.177      | -            | -                | -                | -         |    -5.56 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3887 | 2024-03-02 | Rebels             | W   | 0.164      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3910 | 2024-03-01 | FORZE              | W   | 0.158      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3912 | 2024-03-01 | 9 Pandas           | W   | 0.157      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3918 | 2024-02-29 | KOI                | W   | 0.152      | -            | -                | -                | -         |     0.17 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3921 | 2024-02-29 | Spirit Academy     | W   | 0.150      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3927 | 2024-02-29 | HAVU               | W   | 0.149      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3930 | 2024-02-28 | kONO               | W   | 0.145      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3936 | 2024-02-28 | FORZE              | L   | 0.144      | -            | -                | -                | -         |    -4.47 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4157 | 2024-02-18 | Monte              | L   | 0.078      | -            | -                | -                | -         |    -2.42 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4166 | 2024-02-18 | B8                 | W   | 0.077      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4184 | 2024-02-17 | kONO               | W   | 0.071      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4188 | 2024-02-17 | Monte              | L   | 0.071      | -            | -                | -                | -         |    -2.18 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4191 | 2024-02-17 | kONO               | W   | 0.070      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($136,669.78)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.870 | $10,000.00     | $8,702.78       |
| 2024-06-09 |      0.824 | $8,500.00      | $7,004.83       |
| 2024-06-02 |      0.776 | $15,000.00     | $11,639.24      |
| 2024-05-23 |      0.710 | $12,500.00     | $8,876.74       |
| 2024-04-28 |      0.542 | $20,000.00     | $10,845.37      |
| 2024-04-14 |      0.450 | $105,000.00    | $47,293.75      |
| 2024-03-16 |      0.256 | $28,500.00     | $7,307.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
