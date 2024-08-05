### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1427.4<br />
<br />
Final Rank Value (1427.4) = Starting Rank Value (1685.0) + Head To Head Adjustments (-257.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.773[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.362[<sup>2</sup>](#table1)
- LAN Wins: 0.813[<sup>2</sup>](#table1)

The average of these factors is 0.628<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1685.0
- 400 + ( ( 0.628 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1685.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           83 |       24 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.52 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       49 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |       93 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      126 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      168 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      288 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.719 (0.468)    | 1 (1.000) |    26.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      302 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.422 (0.274)    | 0.788 (0.513)    | 1 (1.000) |    18.54 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      316 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.168 (0.109)    | -                | 1 (1.000) |    15.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      342 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      382 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      394 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      422 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.472 (0.307)    | 1 (1.000) |     9.37 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      689 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.727 (0.363)    | -         |     5.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      792 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      918 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |     1000 | 2024-06-17 | 5W                | L   | 0.873      | -            | -                | -                | -         |   -24.97 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |     1014 | 2024-06-16 | B8                | L   | 0.868      | -            | -                | -                | -         |   -22.70 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1019 | 2024-06-16 | Permitta          | W   | 0.867      | 0.435        | -                | 0.873 (0.329)    | -         |     1.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1025 | 2024-06-16 | Enterprise        | W   | 0.866      | -            | -                | -                | -         |     1.48 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1040 | 2024-06-15 | GUN5              | W   | 0.861      | -            | -                | -                | -         |     1.93 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1060 | 2024-06-15 | BLEED             | W   | 0.859      | -            | -                | -                | -         |    10.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1094 | 2024-06-14 | Sashi             | W   | 0.853      | -            | -                | -                | -         |     5.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1105 | 2024-06-14 | Passion UA        | W   | 0.852      | 0.435        | 0.173 (0.064)    | 1.000 (0.370)    | -         |     3.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1123 | 2024-06-13 | 9INE              | W   | 0.847      | -            | -                | -                | -         |     1.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1135 | 2024-06-13 | VP.Prodigy        | W   | 0.846      | -            | -                | -                | -         |     1.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1166 | 2024-06-11 | SINNERS           | W   | 0.835      | -            | -                | -                | -         |     2.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1177 | 2024-06-11 | BUHAWI            | W   | 0.834      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1193 | 2024-06-10 | EYEBALLERS        | W   | 0.828      | -            | -                | -                | -         |     1.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1200 | 2024-06-10 | SAW               | W   | 0.827      | -            | -                | -                | -         |     5.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1207 | 2024-06-10 | PARIVISION        | W   | 0.826      | -            | -                | -                | -         |     3.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1211 | 2024-06-10 | 9 Pandas          | W   | 0.826      | -            | -                | -                | -         |     3.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1233 | 2024-06-09 | 9INE              | L   | 0.821      | -            | -                | -                | -         |   -24.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1246 | 2024-06-09 | Monte             | L   | 0.820      | -            | -                | -                | -         |   -23.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1253 | 2024-06-09 | SINNERS           | L   | 0.820      | -            | -                | -                | -         |   -23.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1260 | 2024-06-09 | Aurora            | W   | 0.820      | 0.143        | 0.422 (0.049)    | -                | -         |    12.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1270 | 2024-06-09 | RUSH B            | W   | 0.819      | -            | -                | -                | -         |     0.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1308 | 2024-06-08 | Illuminar         | L   | 0.814      | -            | -                | -                | -         |   -24.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1366 | 2024-06-07 | Gaimin Gladiators | W   | 0.807      | -            | -                | -                | -         |     1.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1405 | 2024-06-06 | Nexus             | W   | 0.802      | -            | -                | -                | -         |     0.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1422 | 2024-06-06 | Sangal            | L   | 0.801      | -            | -                | -                | -         |   -22.18 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1485 | 2024-06-05 | KOI               | L   | 0.794      | -            | -                | -                | -         |   -23.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1531 | 2024-06-04 | Aurora            | W   | 0.788      | 0.500        | 0.422 (0.166)    | 0.788 (0.311)    | -         |    12.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1615 | 2024-06-01 | VP.Prodigy        | L   | 0.767      | -            | -                | -                | -         |   -23.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1668 | 2024-05-30 | Sampi             | W   | 0.755      | 0.435        | -                | 1.000 (0.328)    | -         |     0.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1790 | 2024-05-25 | MOUZ NXT          | L   | 0.719      | -            | -                | -                | -         |   -21.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1813 | 2024-05-23 | Zero Tenacity     | W   | 0.707      | 0.435        | -                | 1.000 (0.307)    | -         |     1.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2027 | 2024-05-17 | B8                | L   | 0.666      | -            | -                | -                | -         |   -19.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2113 | 2024-05-15 | Zero Tenacity     | L   | 0.653      | -            | -                | -                | -         |   -19.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2309 | 2024-05-08 | G2                | L   | 0.607      | -            | -                | -                | -         |    -2.54 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2452 | 2024-05-01 | Sashi             | L   | 0.559      | -            | -                | -                | -         |   -16.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2476 | 2024-04-30 | BetBoom           | W   | 0.553      | 0.384        | 0.249 (0.053)    | -                | -         |     3.99 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2484 | 2024-04-29 | PARIVISION        | W   | 0.548      | -            | -                | -                | -         |     0.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2531 | 2024-04-27 | Astralis          | L   | 0.534      | -            | -                | -                | -         |    -5.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2605 | 2024-04-24 | fnatic            | W   | 0.514      | 0.889        | 0.371 (0.169)    | 0.706 (0.322)    | 1 (0.514) |     5.99 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2630 | 2024-04-23 | SAW               | W   | 0.506      | -            | -                | -                | 1 (0.506) |     1.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2639 | 2024-04-22 | ex-Guild Eagles   | W   | 0.501      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2835 | 2024-04-17 | BLEED             | W   | 0.466      | -            | -                | -                | -         |     0.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2893 | 2024-04-14 | BetBoom           | L   | 0.447      | -            | -                | -                | -         |   -11.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2907 | 2024-04-13 | ex-Preasy         | W   | 0.440      | -            | -                | -                | -         |     0.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2949 | 2024-04-11 | Passion UA        | L   | 0.427      | -            | -                | -                | -         |   -12.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2983 | 2024-04-10 | SINNERS           | L   | 0.421      | -            | -                | -                | -         |   -12.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3035 | 2024-04-09 | SAW               | W   | 0.415      | -            | -                | -                | -         |     0.82 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3109 | 2024-04-07 | Young Ninjas      | W   | 0.400      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3181 | 2024-04-04 | Space             | W   | 0.380      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3209 | 2024-04-03 | GUN5              | W   | 0.375      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3262 | 2024-04-02 | Permitta          | W   | 0.367      | -            | -                | -                | -         |     0.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3317 | 2024-03-28 | Apeks             | W   | 0.334      | -            | -                | -                | -         |     0.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3443 | 2024-03-21 | fnatic            | L   | 0.287      | -            | -                | -                | -         |    -5.93 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3483 | 2024-03-19 | GUN5              | W   | 0.273      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3553 | 2024-03-15 | B8                | W   | 0.247      | -            | -                | -                | -         |     0.30 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3623 | 2024-03-13 | PARIVISION        | L   | 0.234      | -            | -                | -                | -         |    -7.07 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3834 | 2024-03-05 | FORZE             | L   | 0.181      | -            | -                | -                | -         |    -5.63 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3857 | 2024-03-04 | fnatic            | L   | 0.173      | -            | -                | -                | -         |    -3.72 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3895 | 2024-03-02 | Monte             | W   | 0.162      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3930 | 2024-02-29 | Gaimin Gladiators | W   | 0.148      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4232 | 2024-02-16 | 9 Pandas          | L   | 0.060      | -            | -                | -                | -         |    -1.86 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4256 | 2024-02-15 | Into the Breach   | W   | 0.054      | -            | -                | -                | 1 (0.054) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4292 | 2024-02-14 | KOI               | L   | 0.048      | -            | -                | -                | -         |    -1.46 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4298 | 2024-02-14 | Falcons           | L   | 0.047      | -            | -                | -                | -         |    -1.21 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4346 | 2024-02-11 | Apeks             | L   | 0.028      | -            | -                | -                | -         |    -0.86 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4370 | 2024-02-09 | fnatic            | W   | 0.015      | -            | -                | -                | -         |     0.15 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4371 | 2024-02-09 | Endpoint          | W   | 0.014      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4376 | 2024-02-09 | ex-Sprout         | L   | 0.014      | -            | -                | -                | -         |    -0.43 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,685.21)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.873 | $10,000.00     | $8,727.78       |
| 2024-06-16 |      0.868 | $10,000.00     | $8,675.00       |
| 2024-06-09 |      0.821 | $7,000.00      | $5,745.35       |
| 2024-06-02 |      0.774 | $2,000.00      | $1,547.78       |
| 2024-05-26 |      0.728 | $2,000.00      | $1,455.00       |
| 2024-05-12 |      0.634 | $23,500.00     | $14,896.39      |
| 2024-05-02 |      0.568 | $1,500.00      | $851.25         |
| 2024-04-14 |      0.447 | $4,000.00      | $1,786.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
