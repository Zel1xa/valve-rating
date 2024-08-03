### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1436.6<br />
<br />
Final Rank Value (1436.6) = Starting Rank Value (1684.6) + Head To Head Adjustments (-248.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.729[<sup>1</sup>](#table2)
- Bounty Collected: 0.506[<sup>2</sup>](#table1)
- Opponent Network: 0.298[<sup>2</sup>](#table1)
- LAN Wins: 0.979[<sup>2</sup>](#table1)

The average of these factors is 0.628<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1684.6
- 400 + ( ( 0.628 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1684.6


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
|           84 |      227 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.76 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      275 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      280 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.534 (0.347)    | 1 (1.000) |    10.08 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      306 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      318 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.170 (0.110)    | 0.415 (0.270)    | 1 (1.000) |    11.76 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      353 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.553 (0.359)    | 1 (1.000) |     3.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      542 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.166 (0.083)    | 0.945 (0.472)    | -         |     5.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |      667 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.468 (0.234)    | -         |     2.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |      937 | 2024-06-16 | Complexity         | L   | 0.878      | -            | -                | -                | -         |    -7.91 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |      990 | 2024-06-14 | The MongolZ        | W   | 0.866      | 0.500        | 1.000 (0.433)    | 0.745 (0.323)    | 1 (0.866) |    25.39 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1000 | 2024-06-14 | Falcons            | W   | 0.865      | 0.500        | 0.225 (0.097)    | -                | 1 (0.865) |    14.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1096 | 2024-06-10 | 9 Pandas           | W   | 0.839      | -            | -                | -                | -         |     3.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1101 | 2024-06-10 | Monte              | W   | 0.839      | -            | -                | -                | -         |     2.75 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1105 | 2024-06-10 | SAW                | L   | 0.838      | -            | -                | -                | -         |   -21.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1129 | 2024-06-09 | Monte              | L   | 0.833      | -            | -                | -                | -         |   -23.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1136 | 2024-06-09 | PARIVISION         | W   | 0.833      | -            | -                | -                | -         |     3.39 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1144 | 2024-06-09 | RUSH B             | L   | 0.832      | -            | -                | -                | -         |   -25.11 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1152 | 2024-06-09 | 3DMAX              | L   | 0.832      | -            | -                | -                | -         |   -13.09 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1160 | 2024-06-09 | SINNERS            | L   | 0.831      | -            | -                | -                | -         |   -24.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1242 | 2024-06-07 | Sangal             | L   | 0.820      | -            | -                | -                | -         |   -22.73 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1257 | 2024-06-07 | Verdant            | W   | 0.819      | -            | -                | -                | -         |     0.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1261 | 2024-06-07 | PERA               | W   | 0.819      | -            | -                | -                | -         |     1.05 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1308 | 2024-06-06 | RUSH B             | W   | 0.813      | -            | -                | -                | -         |     0.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1370 | 2024-06-05 | PARIVISION         | W   | 0.807      | 0.500        | -                | 0.553 (0.223)    | -         |     2.08 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1417 | 2024-06-04 | 3DMAX              | L   | 0.800      | -            | -                | -                | -         |   -12.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1481 | 2024-06-01 | BLEED              | L   | 0.783      | -            | -                | -                | -         |   -17.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1505 | 2024-06-01 | Lynn Vision        | W   | 0.779      | 0.500        | 0.078 (0.031)    | -                | 1 (0.779) |     1.07 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1514 | 2024-05-31 | Chinggis Warriors  | W   | 0.777      | -            | -                | -                | 1 (0.777) |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1589 | 2024-05-29 | The MongolZ        | L   | 0.758      | -            | -                | -                | -         |    -2.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1612 | 2024-05-28 | Lynn Vision        | W   | 0.751      | -            | -                | -                | 1 (0.751) |     0.92 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     1782 | 2024-05-21 | Astralis           | L   | 0.705      | -            | -                | -                | -         |    -6.08 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     1912 | 2024-05-17 | SAW                | W   | 0.678      | 0.769        | 0.106 (0.055)    | 0.560 (0.292)    | -         |     2.81 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     1927 | 2024-05-16 | PARIVISION         | W   | 0.674      | 0.769        | -                | 0.553 (0.286)    | -         |     1.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     1935 | 2024-05-16 | MIBR               | L   | 0.673      | -            | -                | -                | -         |   -13.69 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     1949 | 2024-05-16 | SAW                | L   | 0.671      | -            | -                | -                | -         |   -18.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     1999 | 2024-05-15 | Spirit             | L   | 0.665      | -            | -                | -                | -         |    -2.86 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2142 | 2024-05-10 | MOUZ NXT           | L   | 0.634      | -            | -                | -                | -         |   -19.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2398 | 2024-04-28 | MIBR               | L   | 0.551      | -            | -                | -                | -         |   -12.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2400 | 2024-04-27 | Rebels             | W   | 0.550      | -            | -                | -                | 1 (0.550) |     0.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2426 | 2024-04-27 | Party Astronauts   | W   | 0.544      | -            | -                | -                | -         |     0.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2450 | 2024-04-25 | Apeks              | L   | 0.537      | -            | -                | -                | -         |   -16.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2454 | 2024-04-25 | Party Astronauts   | W   | 0.536      | -            | -                | -                | -         |     0.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2658 | 2024-04-18 | RUBY               | L   | 0.486      | -            | -                | -                | -         |   -15.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2770 | 2024-04-14 | OG                 | W   | 0.459      | 0.684        | 0.140 (0.044)    | -                | -         |     0.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2783 | 2024-04-13 | BetBoom            | W   | 0.453      | 0.684        | 0.252 (0.078)    | 0.563 (0.174)    | -         |     3.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2795 | 2024-04-12 | AMKAL              | W   | 0.447      | -            | -                | -                | -         |     0.81 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2818 | 2024-04-11 | BetBoom            | W   | 0.440      | -            | -                | -                | -         |     3.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2825 | 2024-04-11 | Apeks              | W   | 0.440      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     2830 | 2024-04-11 | FORZE              | W   | 0.439      | -            | -                | -                | -         |     0.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     2859 | 2024-04-10 | PARIVISION         | W   | 0.434      | -            | -                | -                | -         |     0.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     2871 | 2024-04-10 | BetBoom            | L   | 0.433      | -            | -                | -                | -         |   -10.73 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     2920 | 2024-04-09 | KOI                | L   | 0.427      | -            | -                | -                | -         |   -13.22 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     2928 | 2024-04-09 | 1WIN               | W   | 0.426      | -            | -                | -                | -         |     0.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     2936 | 2024-04-09 | 9 Pandas           | W   | 0.425      | -            | -                | -                | -         |     0.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     2946 | 2024-04-08 | Metizport          | W   | 0.421      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     2951 | 2024-04-08 | OG                 | W   | 0.420      | 0.684        | 0.140 (0.040)    | -                | -         |     0.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     2961 | 2024-04-08 | 1WIN               | L   | 0.419      | -            | -                | -                | -         |   -13.03 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3054 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.394      | -            | -                | -                | -         |     5.07 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3094 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.387      | -            | -                | -                | -         |     5.15 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3132 | 2024-04-02 | Apeks              | W   | 0.380      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3141 | 2024-04-02 | Metizport          | W   | 0.379      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           23 |     3153 | 2024-04-01 | SINNERS            | L   | 0.374      | -            | -                | -                | -         |   -11.35 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3192 | 2024-03-28 | brazylijski luz    | W   | 0.347      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3222 | 2024-03-27 | Metizport          | W   | 0.341      | -            | -                | -                | -         |     0.16 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3229 | 2024-03-27 | AURA               | W   | 0.340      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3261 | 2024-03-25 | Rebels             | W   | 0.327      | -            | -                | -                | -         |     0.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3289 | 2024-03-22 | ex-Sprout          | W   | 0.307      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3413 | 2024-03-16 | Gods Reign         | W   | 0.265      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3433 | 2024-03-15 | Gods Reign         | W   | 0.258      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3468 | 2024-03-14 | Bad News Kangaroos | W   | 0.251      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3725 | 2024-03-04 | Young Ninjas       | L   | 0.186      | -            | -                | -                | -         |    -5.84 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3772 | 2024-03-02 | Rebels             | W   | 0.173      | -            | -                | -                | -         |     0.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3795 | 2024-03-01 | FORZE              | W   | 0.167      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3797 | 2024-03-01 | 9 Pandas           | W   | 0.166      | -            | -                | -                | -         |     0.12 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3803 | 2024-02-29 | KOI                | W   | 0.160      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3806 | 2024-02-29 | Spirit Academy     | W   | 0.159      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3812 | 2024-02-29 | HAVU               | W   | 0.158      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3815 | 2024-02-28 | kONO               | W   | 0.154      | -            | -                | -                | -         |     0.04 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3821 | 2024-02-28 | FORZE              | L   | 0.153      | -            | -                | -                | -         |    -4.75 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4042 | 2024-02-18 | Monte              | L   | 0.087      | -            | -                | -                | -         |    -2.69 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4051 | 2024-02-18 | B8                 | W   | 0.086      | -            | -                | -                | -         |     0.09 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4068 | 2024-02-17 | kONO               | W   | 0.080      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4072 | 2024-02-17 | Monte              | L   | 0.080      | -            | -                | -                | -         |    -2.46 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4075 | 2024-02-17 | kONO               | W   | 0.079      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($138,452.35)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.879 | $10,000.00     | $8,792.13       |
| 2024-06-09 |      0.833 | $8,500.00      | $7,080.78       |
| 2024-06-02 |      0.785 | $15,000.00     | $11,773.26      |
| 2024-05-23 |      0.719 | $12,500.00     | $8,988.43       |
| 2024-04-28 |      0.551 | $20,000.00     | $11,024.07      |
| 2024-04-14 |      0.459 | $105,000.00    | $48,231.94      |
| 2024-03-16 |      0.265 | $28,500.00     | $7,561.74       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
