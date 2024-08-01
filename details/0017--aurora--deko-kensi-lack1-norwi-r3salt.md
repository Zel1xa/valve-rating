### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1437.9<br />
<br />
Final Rank Value (1437.9) = Starting Rank Value (1694.1) + Head To Head Adjustments (-256.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.733[<sup>1</sup>](#table2)
- Bounty Collected: 0.507[<sup>2</sup>](#table1)
- Opponent Network: 0.276[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1694.1
- 400 + ( ( 0.629 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1694.1


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
|           85 |      169 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.75 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      217 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      222 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.128 (0.083)    | 0.513 (0.334)    | 1 (1.000) |    10.22 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      248 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      260 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.174 (0.113)    | 0.403 (0.262)    | 1 (1.000) |    11.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      295 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.451 (0.293)    | 1 (1.000) |     3.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      493 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.878 (0.439)    | -         |     5.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      623 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.452 (0.226)    | -         |     2.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |      909 | 2024-06-16 | Complexity         | L   | 0.891      | -            | -                | -                | -         |    -8.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |      966 | 2024-06-14 | The MongolZ        | W   | 0.879      | 0.500        | 1.000 (0.440)    | 0.719 (0.316)    | 1 (0.879) |    25.75 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |      976 | 2024-06-14 | Falcons            | W   | 0.878      | 0.500        | 0.205 (0.090)    | -                | 1 (0.878) |    14.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1078 | 2024-06-10 | 9 Pandas           | W   | 0.852      | -            | -                | -                | -         |     3.67 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1083 | 2024-06-10 | Monte              | W   | 0.852      | -            | -                | -                | -         |     2.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1087 | 2024-06-10 | SAW                | L   | 0.851      | -            | -                | -                | -         |   -21.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1112 | 2024-06-09 | Monte              | L   | 0.846      | -            | -                | -                | -         |   -24.15 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1119 | 2024-06-09 | PARIVISION         | W   | 0.846      | -            | -                | -                | -         |     3.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1127 | 2024-06-09 | RUSH B             | L   | 0.846      | -            | -                | -                | -         |   -25.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1135 | 2024-06-09 | 3DMAX              | L   | 0.845      | -            | -                | -                | -         |   -13.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1144 | 2024-06-09 | SINNERS            | L   | 0.845      | -            | -                | -                | -         |   -24.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1239 | 2024-06-07 | Sangal             | L   | 0.833      | -            | -                | -                | -         |   -23.09 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1254 | 2024-06-07 | Verdant            | W   | 0.833      | -            | -                | -                | -         |     0.87 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1258 | 2024-06-07 | PERA               | W   | 0.832      | -            | -                | -                | -         |     1.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1307 | 2024-06-06 | RUSH B             | W   | 0.827      | -            | -                | -                | -         |     0.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1372 | 2024-06-05 | PARIVISION         | W   | 0.820      | 0.500        | -                | 0.451 (0.185)    | -         |     2.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1420 | 2024-06-04 | 3DMAX              | L   | 0.813      | -            | -                | -                | -         |   -12.74 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1486 | 2024-06-01 | BLEED              | L   | 0.796      | -            | -                | -                | -         |   -17.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1511 | 2024-06-01 | Lynn Vision        | W   | 0.792      | 0.500        | 0.080 (0.032)    | -                | 1 (0.792) |     1.14 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1520 | 2024-05-31 | Chinggis Warriors  | W   | 0.790      | -            | -                | -                | 1 (0.790) |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1595 | 2024-05-29 | The MongolZ        | L   | 0.772      | -            | -                | -                | -         |    -3.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1618 | 2024-05-28 | Lynn Vision        | W   | 0.764      | -            | -                | -                | 1 (0.764) |     0.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1806 | 2024-05-21 | Astralis           | L   | 0.719      | -            | -                | -                | -         |    -6.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     1948 | 2024-05-17 | SAW                | W   | 0.691      | 0.769        | 0.108 (0.057)    | 0.544 (0.289)    | -         |     2.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     1963 | 2024-05-16 | PARIVISION         | W   | 0.688      | 0.769        | -                | 0.451 (0.239)    | -         |     1.44 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     1971 | 2024-05-16 | MIBR               | L   | 0.687      | -            | -                | -                | -         |   -14.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     1985 | 2024-05-16 | SAW                | L   | 0.685      | -            | -                | -                | -         |   -19.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2039 | 2024-05-15 | Spirit             | L   | 0.678      | -            | -                | -                | -         |    -2.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2187 | 2024-05-10 | MOUZ NXT           | L   | 0.647      | -            | -                | -                | -         |   -19.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2449 | 2024-04-28 | MIBR               | L   | 0.564      | -            | -                | -                | -         |   -12.93 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2451 | 2024-04-27 | Rebels             | W   | 0.564      | 0.500        | -                | 0.635 (0.179)    | 1 (0.564) |     0.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2478 | 2024-04-27 | Party Astronauts   | W   | 0.557      | -            | -                | -                | -         |     0.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2502 | 2024-04-25 | Apeks              | L   | 0.550      | -            | -                | -                | -         |   -16.93 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2506 | 2024-04-25 | Party Astronauts   | W   | 0.549      | -            | -                | -                | -         |     0.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2718 | 2024-04-18 | RUBY               | L   | 0.500      | -            | -                | -                | -         |   -15.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2832 | 2024-04-14 | OG                 | W   | 0.473      | 0.684        | 0.143 (0.046)    | -                | -         |     0.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2845 | 2024-04-13 | BetBoom            | W   | 0.466      | 0.684        | 0.257 (0.082)    | -                | -         |     3.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2857 | 2024-04-12 | AMKAL              | W   | 0.460      | -            | -                | -                | -         |     0.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2881 | 2024-04-11 | BetBoom            | W   | 0.454      | -            | -                | -                | -         |     3.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2888 | 2024-04-11 | Apeks              | W   | 0.453      | -            | -                | -                | -         |     0.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2893 | 2024-04-11 | FORZE              | W   | 0.452      | -            | -                | -                | -         |     0.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2922 | 2024-04-10 | PARIVISION         | W   | 0.447      | -            | -                | -                | -         |     0.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     2934 | 2024-04-10 | BetBoom            | L   | 0.446      | -            | -                | -                | -         |   -11.01 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     2983 | 2024-04-09 | KOI                | L   | 0.440      | -            | -                | -                | -         |   -13.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     2991 | 2024-04-09 | 1WIN               | W   | 0.439      | -            | -                | -                | -         |     0.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     2999 | 2024-04-09 | 9 Pandas           | W   | 0.438      | -            | -                | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3009 | 2024-04-08 | Metizport          | W   | 0.434      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3014 | 2024-04-08 | OG                 | W   | 0.433      | 0.684        | 0.143 (0.042)    | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3024 | 2024-04-08 | 1WIN               | L   | 0.432      | -            | -                | -                | -         |   -13.44 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3117 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.407      | -            | -                | -                | -         |     4.16 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3159 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.400      | -            | -                | -                | -         |     4.22 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3203 | 2024-04-02 | Apeks              | W   | 0.393      | -            | -                | -                | -         |     0.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3212 | 2024-04-02 | Metizport          | W   | 0.392      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3224 | 2024-04-01 | SINNERS            | L   | 0.387      | -            | -                | -                | -         |   -11.84 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3263 | 2024-03-28 | brazylijski luz    | W   | 0.360      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3295 | 2024-03-27 | Metizport          | W   | 0.354      | -            | -                | -                | -         |     0.16 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3302 | 2024-03-27 | AURA               | W   | 0.354      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3340 | 2024-03-25 | Rebels             | W   | 0.340      | -            | -                | -                | -         |     0.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3356 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.327      | -            | -                | -                | -         |     0.20 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3370 | 2024-03-22 | ex-Sprout          | W   | 0.320      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3494 | 2024-03-16 | Gods Reign         | W   | 0.279      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3515 | 2024-03-15 | Gods Reign         | W   | 0.271      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3554 | 2024-03-14 | Bad News Kangaroos | W   | 0.264      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3820 | 2024-03-04 | Young Ninjas       | L   | 0.200      | -            | -                | -                | -         |    -6.25 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3867 | 2024-03-02 | Rebels             | W   | 0.186      | -            | -                | -                | -         |     0.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3891 | 2024-03-01 | FORZE              | W   | 0.180      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3893 | 2024-03-01 | 9 Pandas           | W   | 0.179      | -            | -                | -                | -         |     0.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3899 | 2024-02-29 | KOI                | W   | 0.174      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3902 | 2024-02-29 | Spirit Academy     | W   | 0.173      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3908 | 2024-02-29 | HAVU               | W   | 0.171      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3911 | 2024-02-28 | kONO               | W   | 0.167      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3918 | 2024-02-28 | FORZE              | L   | 0.166      | -            | -                | -                | -         |    -5.17 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4147 | 2024-02-18 | Monte              | L   | 0.101      | -            | -                | -                | -         |    -3.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4156 | 2024-02-18 | B8                 | W   | 0.099      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4173 | 2024-02-17 | kONO               | W   | 0.093      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4177 | 2024-02-17 | Monte              | L   | 0.093      | -            | -                | -                | -         |    -2.87 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4180 | 2024-02-17 | kONO               | W   | 0.093      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($141,103.11)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.43) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.892 | $10,000.00     | $8,925.00       |
| 2024-06-09 |      0.846 | $8,500.00      | $7,193.72       |
| 2024-06-02 |      0.798 | $15,000.00     | $11,972.57      |
| 2024-05-23 |      0.732 | $12,500.00     | $9,154.51       |
| 2024-04-28 |      0.564 | $20,000.00     | $11,289.81      |
| 2024-04-14 |      0.473 | $105,000.00    | $49,627.08      |
| 2024-03-16 |      0.279 | $28,500.00     | $7,940.42       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
