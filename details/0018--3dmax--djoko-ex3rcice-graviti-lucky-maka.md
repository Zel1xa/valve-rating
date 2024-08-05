### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1425.3<br />
<br />
Final Rank Value (1425.3) = Starting Rank Value (1683.4) + Head To Head Adjustments (-258.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.772[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.362[<sup>2</sup>](#table1)
- LAN Wins: 0.812[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1683.4
- 400 + ( ( 0.627 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1683.4


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
|           83 |       10 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.49 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       36 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.37 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |       80 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      113 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      155 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      275 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    26.63 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      289 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.423 (0.275)    | 0.792 (0.515)    | 1 (1.000) |    18.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      303 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.168 (0.110)    | -                | 1 (1.000) |    15.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      329 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.79 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      369 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.85 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      381 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      409 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.474 (0.308)    | 1 (1.000) |     9.49 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      676 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.690 (0.345)    | -         |     5.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      779 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.97 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      905 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |      987 | 2024-06-17 | 5W                | L   | 0.876      | -            | -                | -                | -         |   -25.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |     1001 | 2024-06-16 | B8                | L   | 0.871      | -            | -                | -                | -         |   -22.74 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1006 | 2024-06-16 | Permitta          | W   | 0.870      | 0.435        | -                | 0.876 (0.331)    | -         |     1.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1012 | 2024-06-16 | Enterprise        | W   | 0.869      | -            | -                | -                | -         |     1.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1027 | 2024-06-15 | GUN5              | W   | 0.865      | -            | -                | -                | -         |     1.97 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1047 | 2024-06-15 | BLEED             | W   | 0.863      | -            | -                | -                | -         |    10.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1081 | 2024-06-14 | Sashi             | W   | 0.857      | -            | -                | -                | -         |     5.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1092 | 2024-06-14 | Passion UA        | W   | 0.855      | 0.435        | 0.172 (0.064)    | 1.000 (0.372)    | -         |     3.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1110 | 2024-06-13 | 9INE              | W   | 0.851      | -            | -                | -                | -         |     1.55 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1122 | 2024-06-13 | VP.Prodigy        | W   | 0.849      | -            | -                | -                | -         |     1.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1153 | 2024-06-11 | SINNERS           | W   | 0.838      | -            | -                | -                | -         |     2.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1164 | 2024-06-11 | BUHAWI            | W   | 0.837      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1180 | 2024-06-10 | EYEBALLERS        | W   | 0.831      | -            | -                | -                | -         |     1.28 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1187 | 2024-06-10 | SAW               | W   | 0.830      | -            | -                | -                | -         |     5.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1194 | 2024-06-10 | PARIVISION        | W   | 0.830      | -            | -                | -                | -         |     3.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1198 | 2024-06-10 | 9 Pandas          | W   | 0.829      | -            | -                | -                | -         |     3.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1220 | 2024-06-09 | 9INE              | L   | 0.824      | -            | -                | -                | -         |   -24.55 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1233 | 2024-06-09 | Monte             | L   | 0.824      | -            | -                | -                | -         |   -24.00 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1240 | 2024-06-09 | SINNERS           | L   | 0.823      | -            | -                | -                | -         |   -23.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1247 | 2024-06-09 | Aurora            | W   | 0.823      | 0.143        | 0.423 (0.050)    | -                | -         |    12.70 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1257 | 2024-06-09 | RUSH B            | W   | 0.823      | -            | -                | -                | -         |     0.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1295 | 2024-06-08 | Illuminar         | L   | 0.817      | -            | -                | -                | -         |   -24.97 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1353 | 2024-06-07 | Gaimin Gladiators | W   | 0.811      | -            | -                | -                | -         |     1.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1392 | 2024-06-06 | Nexus             | W   | 0.805      | -            | -                | -                | -         |     0.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1409 | 2024-06-06 | Sangal            | L   | 0.804      | -            | -                | -                | -         |   -22.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1472 | 2024-06-05 | KOI               | L   | 0.798      | -            | -                | -                | -         |   -23.52 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1518 | 2024-06-04 | Aurora            | W   | 0.791      | 0.500        | 0.423 (0.167)    | 0.792 (0.313)    | -         |    12.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1602 | 2024-06-01 | VP.Prodigy        | L   | 0.771      | -            | -                | -                | -         |   -23.55 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1655 | 2024-05-30 | Sampi             | W   | 0.758      | 0.435        | -                | 1.000 (0.329)    | -         |     0.63 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1777 | 2024-05-25 | MOUZ NXT          | L   | 0.722      | -            | -                | -                | -         |   -21.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1800 | 2024-05-23 | Zero Tenacity     | W   | 0.710      | 0.435        | -                | 1.000 (0.309)    | -         |     1.55 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2014 | 2024-05-17 | B8                | L   | 0.670      | -            | -                | -                | -         |   -19.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2100 | 2024-05-15 | Zero Tenacity     | L   | 0.656      | -            | -                | -                | -         |   -19.70 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2296 | 2024-05-08 | G2                | L   | 0.610      | -            | -                | -                | -         |    -2.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2439 | 2024-05-01 | Sashi             | L   | 0.563      | -            | -                | -                | -         |   -16.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2463 | 2024-04-30 | BetBoom           | W   | 0.556      | 0.384        | 0.250 (0.053)    | -                | -         |     4.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2471 | 2024-04-29 | PARIVISION        | W   | 0.551      | -            | -                | -                | -         |     0.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2518 | 2024-04-27 | Astralis          | L   | 0.537      | -            | -                | -                | -         |    -5.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2592 | 2024-04-24 | fnatic            | W   | 0.517      | 0.889        | 0.371 (0.170)    | 0.708 (0.325)    | 1 (0.517) |     6.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2617 | 2024-04-23 | SAW               | W   | 0.510      | -            | -                | -                | 1 (0.510) |     1.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2626 | 2024-04-22 | ex-Guild Eagles   | W   | 0.504      | -            | -                | -                | -         |     0.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2822 | 2024-04-17 | BLEED             | W   | 0.469      | -            | -                | -                | -         |     0.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2880 | 2024-04-14 | BetBoom           | L   | 0.450      | -            | -                | -                | -         |   -11.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2894 | 2024-04-13 | ex-Preasy         | W   | 0.443      | -            | -                | -                | -         |     0.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2936 | 2024-04-11 | Passion UA        | L   | 0.430      | -            | -                | -                | -         |   -13.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2970 | 2024-04-10 | SINNERS           | L   | 0.425      | -            | -                | -                | -         |   -12.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3022 | 2024-04-09 | SAW               | W   | 0.418      | -            | -                | -                | -         |     0.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3096 | 2024-04-07 | Young Ninjas      | W   | 0.403      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3168 | 2024-04-04 | Space             | W   | 0.384      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3196 | 2024-04-03 | GUN5              | W   | 0.378      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3249 | 2024-04-02 | Permitta          | W   | 0.370      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3304 | 2024-03-28 | Apeks             | W   | 0.337      | -            | -                | -                | -         |     0.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3430 | 2024-03-21 | fnatic            | L   | 0.290      | -            | -                | -                | -         |    -5.97 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3470 | 2024-03-19 | GUN5              | W   | 0.277      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3540 | 2024-03-15 | B8                | W   | 0.251      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3610 | 2024-03-13 | PARIVISION        | L   | 0.237      | -            | -                | -                | -         |    -7.17 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3821 | 2024-03-05 | FORZE             | L   | 0.184      | -            | -                | -                | -         |    -5.74 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3844 | 2024-03-04 | fnatic            | L   | 0.177      | -            | -                | -                | -         |    -3.78 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3882 | 2024-03-02 | Monte             | W   | 0.165      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3917 | 2024-02-29 | Gaimin Gladiators | W   | 0.152      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4219 | 2024-02-16 | 9 Pandas          | L   | 0.064      | -            | -                | -                | -         |    -1.96 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4243 | 2024-02-15 | Into the Breach   | W   | 0.057      | -            | -                | -                | 1 (0.057) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4279 | 2024-02-14 | KOI               | L   | 0.051      | -            | -                | -                | -         |    -1.56 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4285 | 2024-02-14 | Falcons           | L   | 0.050      | -            | -                | -                | -         |    -1.29 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4333 | 2024-02-11 | Apeks             | L   | 0.031      | -            | -                | -                | -         |    -0.96 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4357 | 2024-02-09 | fnatic            | W   | 0.018      | -            | -                | -                | -         |     0.19 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4358 | 2024-02-09 | Endpoint          | W   | 0.018      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4363 | 2024-02-09 | ex-Sprout         | L   | 0.017      | -            | -                | -                | -         |    -0.53 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,885.21)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.876 | $10,000.00     | $8,761.11       |
| 2024-06-16 |      0.871 | $10,000.00     | $8,708.33       |
| 2024-06-09 |      0.824 | $7,000.00      | $5,768.68       |
| 2024-06-02 |      0.777 | $2,000.00      | $1,554.44       |
| 2024-05-26 |      0.731 | $2,000.00      | $1,461.67       |
| 2024-05-12 |      0.637 | $23,500.00     | $14,974.72      |
| 2024-05-02 |      0.571 | $1,500.00      | $856.25         |
| 2024-04-14 |      0.450 | $4,000.00      | $1,800.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
