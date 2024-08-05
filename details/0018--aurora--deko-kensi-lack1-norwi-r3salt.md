### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1444.6<br />
<br />
Final Rank Value (1444.6) = Starting Rank Value (1697.8) + Head To Head Adjustments (-253.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.731[<sup>1</sup>](#table2)
- Bounty Collected: 0.509[<sup>2</sup>](#table1)
- Opponent Network: 0.277[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1697.8
- 400 + ( ( 0.629 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1697.8


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
|           85 |      136 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.72 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      184 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      189 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.127 (0.083)    | 0.512 (0.333)    | 1 (1.000) |    10.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      215 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      227 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.173 (0.112)    | 0.404 (0.263)    | 1 (1.000) |    12.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      262 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.452 (0.294)    | 1 (1.000) |     3.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      451 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.167 (0.083)    | 0.879 (0.440)    | -         |     5.70 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      579 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.452 (0.226)    | -         |     2.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |      861 | 2024-06-16 | Complexity         | L   | 0.897      | -            | -                | -                | -         |    -7.92 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |      927 | 2024-06-14 | The MongolZ        | W   | 0.885      | 0.500        | 1.000 (0.442)    | 0.719 (0.318)    | 1 (0.885) |    25.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |      937 | 2024-06-14 | Falcons            | W   | 0.884      | 0.500        | 0.231 (0.102)    | -                | 1 (0.884) |    15.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1037 | 2024-06-10 | 9 Pandas           | W   | 0.858      | -            | -                | -                | -         |     3.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1042 | 2024-06-10 | Monte              | W   | 0.858      | -            | -                | -                | -         |     2.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1046 | 2024-06-10 | SAW                | L   | 0.857      | -            | -                | -                | -         |   -21.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1071 | 2024-06-09 | Monte              | L   | 0.852      | -            | -                | -                | -         |   -24.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1078 | 2024-06-09 | PARIVISION         | W   | 0.852      | -            | -                | -                | -         |     3.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1086 | 2024-06-09 | RUSH B             | L   | 0.851      | -            | -                | -                | -         |   -25.72 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1094 | 2024-06-09 | 3DMAX              | L   | 0.851      | -            | -                | -                | -         |   -13.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1102 | 2024-06-09 | SINNERS            | L   | 0.850      | -            | -                | -                | -         |   -25.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1189 | 2024-06-07 | Sangal             | L   | 0.839      | -            | -                | -                | -         |   -23.05 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1204 | 2024-06-07 | Verdant            | W   | 0.838      | -            | -                | -                | -         |     0.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1208 | 2024-06-07 | PERA               | W   | 0.838      | -            | -                | -                | -         |     1.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1255 | 2024-06-06 | RUSH B             | W   | 0.832      | -            | -                | -                | -         |     0.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1317 | 2024-06-05 | PARIVISION         | W   | 0.826      | 0.500        | -                | 0.452 (0.187)    | -         |     2.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1365 | 2024-06-04 | 3DMAX              | L   | 0.819      | -            | -                | -                | -         |   -12.73 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1430 | 2024-06-01 | BLEED              | L   | 0.802      | -            | -                | -                | -         |   -18.04 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1455 | 2024-06-01 | Lynn Vision        | W   | 0.798      | 0.500        | 0.079 (0.032)    | -                | 1 (0.798) |     1.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1464 | 2024-05-31 | Chinggis Warriors  | W   | 0.796      | -            | -                | -                | 1 (0.796) |     0.22 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1539 | 2024-05-29 | The MongolZ        | L   | 0.777      | -            | -                | -                | -         |    -3.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1562 | 2024-05-28 | Lynn Vision        | W   | 0.770      | -            | -                | -                | 1 (0.770) |     0.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1733 | 2024-05-21 | Astralis           | L   | 0.724      | -            | -                | -                | -         |    -6.14 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     1864 | 2024-05-17 | SAW                | W   | 0.697      | 0.769        | 0.107 (0.057)    | 0.545 (0.292)    | -         |     3.01 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     1879 | 2024-05-16 | PARIVISION         | W   | 0.693      | 0.769        | -                | 0.452 (0.241)    | -         |     1.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     1887 | 2024-05-16 | MIBR               | L   | 0.693      | -            | -                | -                | -         |   -13.87 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     1901 | 2024-05-16 | SAW                | L   | 0.690      | -            | -                | -                | -         |   -19.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     1951 | 2024-05-15 | Spirit             | L   | 0.684      | -            | -                | -                | -         |    -2.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2094 | 2024-05-10 | MOUZ NXT           | L   | 0.653      | -            | -                | -                | -         |   -19.73 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2351 | 2024-04-28 | MIBR               | L   | 0.570      | -            | -                | -                | -         |   -12.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2353 | 2024-04-27 | Rebels             | W   | 0.569      | -            | -                | -                | 1 (0.569) |     0.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2379 | 2024-04-27 | Party Astronauts   | W   | 0.563      | -            | -                | -                | -         |     0.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2404 | 2024-04-25 | Apeks              | L   | 0.556      | -            | -                | -                | -         |   -17.09 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2408 | 2024-04-25 | Party Astronauts   | W   | 0.555      | -            | -                | -                | -         |     0.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2612 | 2024-04-18 | RUBY               | L   | 0.505      | -            | -                | -                | -         |   -15.62 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2724 | 2024-04-14 | OG                 | W   | 0.478      | 0.684        | 0.143 (0.047)    | -                | -         |     0.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2737 | 2024-04-13 | BetBoom            | W   | 0.472      | 0.684        | 0.256 (0.083)    | 0.554 (0.179)    | -         |     3.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2749 | 2024-04-12 | AMKAL              | W   | 0.466      | -            | -                | -                | -         |     0.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2772 | 2024-04-11 | BetBoom            | W   | 0.460      | -            | -                | -                | -         |     3.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2779 | 2024-04-11 | Apeks              | W   | 0.459      | -            | -                | -                | -         |     0.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2784 | 2024-04-11 | FORZE              | W   | 0.458      | -            | -                | -                | -         |     0.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2813 | 2024-04-10 | PARIVISION         | W   | 0.453      | -            | -                | -                | -         |     0.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     2825 | 2024-04-10 | BetBoom            | L   | 0.452      | -            | -                | -                | -         |   -11.09 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     2874 | 2024-04-09 | KOI                | L   | 0.446      | -            | -                | -                | -         |   -13.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     2882 | 2024-04-09 | 1WIN               | W   | 0.445      | -            | -                | -                | -         |     0.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     2890 | 2024-04-09 | 9 Pandas           | W   | 0.444      | -            | -                | -                | -         |     0.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     2900 | 2024-04-08 | Metizport          | W   | 0.440      | -            | -                | -                | -         |     0.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     2905 | 2024-04-08 | OG                 | W   | 0.439      | 0.684        | 0.143 (0.043)    | -                | -         |     0.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     2915 | 2024-04-08 | 1WIN               | L   | 0.438      | -            | -                | -                | -         |   -13.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3008 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.413      | -            | -                | -                | -         |     5.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3048 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.406      | -            | -                | -                | -         |     5.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3086 | 2024-04-02 | Apeks              | W   | 0.399      | -            | -                | -                | -         |     0.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3095 | 2024-04-02 | Metizport          | W   | 0.398      | -            | -                | -                | -         |     0.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3107 | 2024-04-01 | SINNERS            | L   | 0.393      | -            | -                | -                | -         |   -12.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3146 | 2024-03-28 | brazylijski luz    | W   | 0.366      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3177 | 2024-03-27 | Metizport          | W   | 0.360      | -            | -                | -                | -         |     0.16 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3184 | 2024-03-27 | AURA               | W   | 0.359      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3218 | 2024-03-25 | Rebels             | W   | 0.346      | -            | -                | -                | -         |     0.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3234 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.333      | -            | -                | -                | -         |     0.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3248 | 2024-03-22 | ex-Sprout          | W   | 0.326      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3372 | 2024-03-16 | Gods Reign         | W   | 0.284      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3393 | 2024-03-15 | Gods Reign         | W   | 0.277      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3428 | 2024-03-14 | Bad News Kangaroos | W   | 0.270      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3687 | 2024-03-04 | Young Ninjas       | L   | 0.205      | -            | -                | -                | -         |    -6.43 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3734 | 2024-03-02 | Rebels             | W   | 0.192      | -            | -                | -                | -         |     0.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3757 | 2024-03-01 | FORZE              | W   | 0.186      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3759 | 2024-03-01 | 9 Pandas           | W   | 0.185      | -            | -                | -                | -         |     0.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3765 | 2024-02-29 | KOI                | W   | 0.179      | -            | -                | -                | -         |     0.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3768 | 2024-02-29 | Spirit Academy     | W   | 0.178      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3774 | 2024-02-29 | HAVU               | W   | 0.177      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3777 | 2024-02-28 | kONO               | W   | 0.173      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3783 | 2024-02-28 | FORZE              | L   | 0.172      | -            | -                | -                | -         |    -5.34 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4004 | 2024-02-18 | Monte              | L   | 0.106      | -            | -                | -                | -         |    -3.28 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4013 | 2024-02-18 | B8                 | W   | 0.105      | -            | -                | -                | -         |     0.11 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4031 | 2024-02-17 | kONO               | W   | 0.099      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4035 | 2024-02-17 | Monte              | L   | 0.099      | -            | -                | -                | -         |    -3.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4038 | 2024-02-17 | kONO               | W   | 0.098      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($142,245.62)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.43) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.898 | $10,000.00     | $8,982.27       |
| 2024-06-09 |      0.852 | $8,500.00      | $7,242.39       |
| 2024-06-02 |      0.804 | $15,000.00     | $12,058.47      |
| 2024-05-23 |      0.738 | $12,500.00     | $9,226.10       |
| 2024-04-28 |      0.570 | $20,000.00     | $11,404.35      |
| 2024-04-14 |      0.478 | $105,000.00    | $50,228.40      |
| 2024-03-16 |      0.284 | $28,500.00     | $8,103.63       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
