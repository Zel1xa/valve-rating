### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1432.0<br />
<br />
Final Rank Value (1432.0) = Starting Rank Value (1687.7) + Head To Head Adjustments (-255.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.774[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.353[<sup>2</sup>](#table1)
- LAN Wins: 0.815[<sup>2</sup>](#table1)

The average of these factors is 0.626<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1687.7
- 400 + ( ( 0.626 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1687.7


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
|           83 |       51 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       77 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |      121 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      155 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      196 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      316 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    26.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      330 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.420 (0.273)    | 0.758 (0.493)    | 1 (1.000) |    18.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      344 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.173 (0.112)    | -                | 1 (1.000) |    15.34 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      370 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -6.00 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      410 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      422 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      450 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.452 (0.294)    | 1 (1.000) |     9.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      717 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.700 (0.350)    | -         |     4.96 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      820 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      946 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |     1028 | 2024-06-17 | 5W                | L   | 0.866      | -            | -                | -                | -         |   -24.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |     1042 | 2024-06-16 | B8                | L   | 0.860      | -            | -                | -                | -         |   -22.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1047 | 2024-06-16 | Permitta          | W   | 0.860      | 0.435        | -                | 0.919 (0.343)    | -         |     1.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1053 | 2024-06-16 | Enterprise        | W   | 0.859      | -            | -                | -                | -         |     1.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1068 | 2024-06-15 | GUN5              | W   | 0.854      | -            | -                | -                | -         |     1.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1088 | 2024-06-15 | BLEED             | W   | 0.852      | -            | -                | -                | -         |    10.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1122 | 2024-06-14 | Sashi             | W   | 0.846      | -            | -                | -                | -         |     5.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1133 | 2024-06-14 | Passion UA        | W   | 0.845      | 0.435        | 0.173 (0.064)    | 1.000 (0.367)    | -         |     3.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1151 | 2024-06-13 | 9INE              | W   | 0.840      | -            | -                | -                | -         |     1.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1163 | 2024-06-13 | VP.Prodigy        | W   | 0.839      | -            | -                | -                | -         |     1.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1194 | 2024-06-11 | SINNERS           | W   | 0.828      | -            | -                | -                | -         |     2.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1205 | 2024-06-11 | BUHAWI            | W   | 0.827      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1221 | 2024-06-10 | EYEBALLERS        | W   | 0.820      | -            | -                | -                | -         |     1.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1228 | 2024-06-10 | SAW               | W   | 0.819      | -            | -                | -                | -         |     4.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1235 | 2024-06-10 | PARIVISION        | W   | 0.819      | -            | -                | -                | -         |     3.35 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1239 | 2024-06-10 | 9 Pandas          | W   | 0.819      | -            | -                | -                | -         |     2.93 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1261 | 2024-06-09 | 9INE              | L   | 0.814      | -            | -                | -                | -         |   -24.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1274 | 2024-06-09 | Monte             | L   | 0.813      | -            | -                | -                | -         |   -23.76 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1281 | 2024-06-09 | SINNERS           | L   | 0.813      | -            | -                | -                | -         |   -23.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1288 | 2024-06-09 | Aurora            | W   | 0.812      | 0.143        | 0.420 (0.049)    | -                | -         |    12.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1298 | 2024-06-09 | RUSH B            | W   | 0.812      | -            | -                | -                | -         |     0.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1336 | 2024-06-08 | Illuminar         | L   | 0.807      | -            | -                | -                | -         |   -24.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1394 | 2024-06-07 | Gaimin Gladiators | W   | 0.800      | -            | -                | -                | -         |     1.34 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1433 | 2024-06-06 | Nexus             | W   | 0.795      | -            | -                | -                | -         |     0.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1450 | 2024-06-06 | Sangal            | L   | 0.794      | -            | -                | -                | -         |   -21.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1513 | 2024-06-05 | KOI               | L   | 0.787      | -            | -                | -                | -         |   -23.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1559 | 2024-06-04 | Aurora            | W   | 0.781      | 0.500        | 0.420 (0.164)    | 0.758 (0.296)    | -         |    12.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1643 | 2024-06-01 | VP.Prodigy        | L   | 0.760      | -            | -                | -                | -         |   -23.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1696 | 2024-05-30 | Sampi             | W   | 0.748      | 0.435        | -                | 1.000 (0.325)    | -         |     0.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1818 | 2024-05-25 | MOUZ NXT          | L   | 0.711      | -            | -                | -                | -         |   -21.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1841 | 2024-05-23 | Zero Tenacity     | W   | 0.700      | 0.435        | -                | 1.000 (0.304)    | -         |     1.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2055 | 2024-05-17 | B8                | L   | 0.659      | -            | -                | -                | -         |   -19.37 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2141 | 2024-05-15 | Zero Tenacity     | L   | 0.646      | -            | -                | -                | -         |   -19.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2337 | 2024-05-08 | G2                | L   | 0.600      | -            | -                | -                | -         |    -2.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2480 | 2024-05-01 | Sashi             | L   | 0.552      | -            | -                | -                | -         |   -16.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2504 | 2024-04-30 | BetBoom           | W   | 0.546      | 0.384        | 0.248 (0.052)    | -                | -         |     3.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2512 | 2024-04-29 | PARIVISION        | W   | 0.541      | -            | -                | -                | -         |     0.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2559 | 2024-04-27 | Astralis          | L   | 0.527      | -            | -                | -                | -         |    -5.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2633 | 2024-04-24 | fnatic            | W   | 0.507      | 0.889        | 0.371 (0.167)    | 0.680 (0.306)    | 1 (0.507) |     5.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2658 | 2024-04-23 | SAW               | W   | 0.499      | -            | -                | -                | 1 (0.499) |     1.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2667 | 2024-04-22 | ex-Guild Eagles   | W   | 0.494      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2863 | 2024-04-17 | BLEED             | W   | 0.459      | -            | -                | -                | -         |     0.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2921 | 2024-04-14 | BetBoom           | L   | 0.439      | -            | -                | -                | -         |   -10.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2935 | 2024-04-13 | ex-Preasy         | W   | 0.433      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2977 | 2024-04-11 | Passion UA        | L   | 0.419      | -            | -                | -                | -         |   -12.76 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     3011 | 2024-04-10 | SINNERS           | L   | 0.414      | -            | -                | -                | -         |   -12.28 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3063 | 2024-04-09 | SAW               | W   | 0.407      | -            | -                | -                | -         |     0.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3137 | 2024-04-07 | Young Ninjas      | W   | 0.393      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3209 | 2024-04-04 | Space             | W   | 0.373      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3237 | 2024-04-03 | GUN5              | W   | 0.367      | -            | -                | -                | -         |     0.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3290 | 2024-04-02 | Permitta          | W   | 0.359      | -            | -                | -                | -         |     0.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3345 | 2024-03-28 | Apeks             | W   | 0.326      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3471 | 2024-03-21 | fnatic            | L   | 0.280      | -            | -                | -                | -         |    -5.85 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3511 | 2024-03-19 | GUN5              | W   | 0.266      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3581 | 2024-03-15 | B8                | W   | 0.240      | -            | -                | -                | -         |     0.29 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3651 | 2024-03-13 | PARIVISION        | L   | 0.227      | -            | -                | -                | -         |    -6.85 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3862 | 2024-03-05 | FORZE             | L   | 0.174      | -            | -                | -                | -         |    -5.41 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3885 | 2024-03-04 | fnatic            | L   | 0.166      | -            | -                | -                | -         |    -3.60 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3923 | 2024-03-02 | Monte             | W   | 0.154      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3958 | 2024-02-29 | Gaimin Gladiators | W   | 0.141      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4260 | 2024-02-16 | 9 Pandas          | L   | 0.053      | -            | -                | -                | -         |    -1.64 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4284 | 2024-02-15 | Into the Breach   | W   | 0.047      | -            | -                | -                | 1 (0.047) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4320 | 2024-02-14 | KOI               | L   | 0.041      | -            | -                | -                | -         |    -1.24 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4326 | 2024-02-14 | Falcons           | L   | 0.040      | -            | -                | -                | -         |    -1.03 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4374 | 2024-02-11 | Apeks             | L   | 0.020      | -            | -                | -                | -         |    -0.64 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4398 | 2024-02-09 | fnatic            | W   | 0.007      | -            | -                | -                | -         |     0.07 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4399 | 2024-02-09 | Endpoint          | W   | 0.007      | -            | -                | -                | -         |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4404 | 2024-02-09 | ex-Sprout         | L   | 0.006      | -            | -                | -                | -         |    -0.20 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,251.88)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.866 | $10,000.00     | $8,655.56       |
| 2024-06-16 |      0.860 | $10,000.00     | $8,602.78       |
| 2024-06-09 |      0.814 | $7,000.00      | $5,694.79       |
| 2024-06-02 |      0.767 | $2,000.00      | $1,533.33       |
| 2024-05-26 |      0.720 | $2,000.00      | $1,440.56       |
| 2024-05-12 |      0.627 | $23,500.00     | $14,726.67      |
| 2024-05-02 |      0.560 | $1,500.00      | $840.42         |
| 2024-04-14 |      0.439 | $4,000.00      | $1,757.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
