### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1438.5<br />
<br />
Final Rank Value (1438.5) = Starting Rank Value (1694.5) + Head To Head Adjustments (-256.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.733[<sup>1</sup>](#table2)
- Bounty Collected: 0.507[<sup>2</sup>](#table1)
- Opponent Network: 0.277[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1694.5
- 400 + ( ( 0.629 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1694.5


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
|           85 |      171 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.76 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      219 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      224 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.128 (0.083)    | 0.513 (0.334)    | 1 (1.000) |    10.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      250 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      262 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.173 (0.113)    | 0.403 (0.262)    | 1 (1.000) |    11.85 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      297 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.457 (0.297)    | 1 (1.000) |     3.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      495 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.878 (0.439)    | -         |     5.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      625 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.452 (0.226)    | -         |     2.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |      911 | 2024-06-16 | Complexity         | L   | 0.891      | -            | -                | -                | -         |    -8.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |      968 | 2024-06-14 | The MongolZ        | W   | 0.879      | 0.500        | 1.000 (0.439)    | 0.719 (0.316)    | 1 (0.879) |    25.74 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |      978 | 2024-06-14 | Falcons            | W   | 0.878      | 0.500        | 0.205 (0.090)    | -                | 1 (0.878) |    14.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1080 | 2024-06-10 | 9 Pandas           | W   | 0.852      | -            | -                | -                | -         |     3.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1085 | 2024-06-10 | Monte              | W   | 0.852      | -            | -                | -                | -         |     2.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1089 | 2024-06-10 | SAW                | L   | 0.851      | -            | -                | -                | -         |   -21.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1114 | 2024-06-09 | Monte              | L   | 0.846      | -            | -                | -                | -         |   -24.15 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1121 | 2024-06-09 | PARIVISION         | W   | 0.846      | -            | -                | -                | -         |     3.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1129 | 2024-06-09 | RUSH B             | L   | 0.845      | -            | -                | -                | -         |   -25.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1137 | 2024-06-09 | 3DMAX              | L   | 0.845      | -            | -                | -                | -         |   -13.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1146 | 2024-06-09 | SINNERS            | L   | 0.844      | -            | -                | -                | -         |   -24.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1241 | 2024-06-07 | Sangal             | L   | 0.833      | -            | -                | -                | -         |   -23.09 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1256 | 2024-06-07 | Verdant            | W   | 0.832      | -            | -                | -                | -         |     0.86 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1260 | 2024-06-07 | PERA               | W   | 0.832      | -            | -                | -                | -         |     1.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1309 | 2024-06-06 | RUSH B             | W   | 0.826      | -            | -                | -                | -         |     0.64 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1374 | 2024-06-05 | PARIVISION         | W   | 0.820      | 0.500        | -                | 0.457 (0.187)    | -         |     2.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1422 | 2024-06-04 | 3DMAX              | L   | 0.813      | -            | -                | -                | -         |   -12.74 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1488 | 2024-06-01 | BLEED              | L   | 0.796      | -            | -                | -                | -         |   -17.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1513 | 2024-06-01 | Lynn Vision        | W   | 0.792      | 0.500        | 0.080 (0.032)    | -                | 1 (0.792) |     1.14 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1522 | 2024-05-31 | Chinggis Warriors  | W   | 0.790      | -            | -                | -                | 1 (0.790) |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1597 | 2024-05-29 | The MongolZ        | L   | 0.771      | -            | -                | -                | -         |    -3.03 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1620 | 2024-05-28 | Lynn Vision        | W   | 0.764      | -            | -                | -                | 1 (0.764) |     0.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1808 | 2024-05-21 | Astralis           | L   | 0.718      | -            | -                | -                | -         |    -6.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     1950 | 2024-05-17 | SAW                | W   | 0.691      | 0.769        | 0.108 (0.057)    | 0.544 (0.289)    | -         |     2.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     1965 | 2024-05-16 | PARIVISION         | W   | 0.687      | 0.769        | -                | 0.457 (0.242)    | -         |     1.48 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     1973 | 2024-05-16 | MIBR               | L   | 0.687      | -            | -                | -                | -         |   -14.14 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     1987 | 2024-05-16 | SAW                | L   | 0.684      | -            | -                | -                | -         |   -19.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2041 | 2024-05-15 | Spirit             | L   | 0.678      | -            | -                | -                | -         |    -2.96 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2189 | 2024-05-10 | MOUZ NXT           | L   | 0.647      | -            | -                | -                | -         |   -19.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2451 | 2024-04-28 | MIBR               | L   | 0.564      | -            | -                | -                | -         |   -12.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2453 | 2024-04-27 | Rebels             | W   | 0.563      | 0.500        | -                | 0.635 (0.179)    | 1 (0.563) |     0.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2480 | 2024-04-27 | Party Astronauts   | W   | 0.557      | -            | -                | -                | -         |     0.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2504 | 2024-04-25 | Apeks              | L   | 0.550      | -            | -                | -                | -         |   -16.92 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2508 | 2024-04-25 | Party Astronauts   | W   | 0.549      | -            | -                | -                | -         |     0.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2720 | 2024-04-18 | RUBY               | L   | 0.499      | -            | -                | -                | -         |   -15.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2834 | 2024-04-14 | OG                 | W   | 0.472      | 0.684        | 0.143 (0.046)    | -                | -         |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2847 | 2024-04-13 | BetBoom            | W   | 0.466      | 0.684        | 0.257 (0.082)    | -                | -         |     3.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2859 | 2024-04-12 | AMKAL              | W   | 0.460      | -            | -                | -                | -         |     0.81 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2883 | 2024-04-11 | BetBoom            | W   | 0.453      | -            | -                | -                | -         |     3.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2890 | 2024-04-11 | Apeks              | W   | 0.453      | -            | -                | -                | -         |     0.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2895 | 2024-04-11 | FORZE              | W   | 0.452      | -            | -                | -                | -         |     0.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2924 | 2024-04-10 | PARIVISION         | W   | 0.447      | -            | -                | -                | -         |     0.62 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     2936 | 2024-04-10 | BetBoom            | L   | 0.446      | -            | -                | -                | -         |   -10.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     2985 | 2024-04-09 | KOI                | L   | 0.440      | -            | -                | -                | -         |   -13.62 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     2993 | 2024-04-09 | 1WIN               | W   | 0.439      | -            | -                | -                | -         |     0.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3001 | 2024-04-09 | 9 Pandas           | W   | 0.438      | -            | -                | -                | -         |     0.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3011 | 2024-04-08 | Metizport          | W   | 0.434      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3016 | 2024-04-08 | OG                 | W   | 0.433      | 0.684        | 0.143 (0.042)    | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3026 | 2024-04-08 | 1WIN               | L   | 0.432      | -            | -                | -                | -         |   -13.44 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3119 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.407      | -            | -                | -                | -         |     4.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3161 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.400      | -            | -                | -                | -         |     4.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3205 | 2024-04-02 | Apeks              | W   | 0.393      | -            | -                | -                | -         |     0.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3214 | 2024-04-02 | Metizport          | W   | 0.392      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3226 | 2024-04-01 | SINNERS            | L   | 0.387      | -            | -                | -                | -         |   -11.84 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3265 | 2024-03-28 | brazylijski luz    | W   | 0.360      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3297 | 2024-03-27 | Metizport          | W   | 0.354      | -            | -                | -                | -         |     0.16 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3304 | 2024-03-27 | AURA               | W   | 0.353      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3342 | 2024-03-25 | Rebels             | W   | 0.340      | -            | -                | -                | -         |     0.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3358 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.327      | -            | -                | -                | -         |     0.20 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3372 | 2024-03-22 | ex-Sprout          | W   | 0.320      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3496 | 2024-03-16 | Gods Reign         | W   | 0.278      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3517 | 2024-03-15 | Gods Reign         | W   | 0.271      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3556 | 2024-03-14 | Bad News Kangaroos | W   | 0.264      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3822 | 2024-03-04 | Young Ninjas       | L   | 0.199      | -            | -                | -                | -         |    -6.25 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3869 | 2024-03-02 | Rebels             | W   | 0.186      | -            | -                | -                | -         |     0.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3893 | 2024-03-01 | FORZE              | W   | 0.180      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3895 | 2024-03-01 | 9 Pandas           | W   | 0.179      | -            | -                | -                | -         |     0.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3901 | 2024-02-29 | KOI                | W   | 0.173      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3904 | 2024-02-29 | Spirit Academy     | W   | 0.172      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3910 | 2024-02-29 | HAVU               | W   | 0.171      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3913 | 2024-02-28 | kONO               | W   | 0.167      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3920 | 2024-02-28 | FORZE              | L   | 0.166      | -            | -                | -                | -         |    -5.16 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4149 | 2024-02-18 | Monte              | L   | 0.100      | -            | -                | -                | -         |    -3.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4158 | 2024-02-18 | B8                 | W   | 0.099      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4175 | 2024-02-17 | kONO               | W   | 0.093      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4179 | 2024-02-17 | Monte              | L   | 0.093      | -            | -                | -                | -         |    -2.86 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4182 | 2024-02-17 | kONO               | W   | 0.092      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($141,047.70)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.43) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.892 | $10,000.00     | $8,922.22       |
| 2024-06-09 |      0.846 | $8,500.00      | $7,191.35       |
| 2024-06-02 |      0.798 | $15,000.00     | $11,968.40      |
| 2024-05-23 |      0.732 | $12,500.00     | $9,151.04       |
| 2024-04-28 |      0.564 | $20,000.00     | $11,284.26      |
| 2024-04-14 |      0.472 | $105,000.00    | $49,597.92      |
| 2024-03-16 |      0.278 | $28,500.00     | $7,932.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
