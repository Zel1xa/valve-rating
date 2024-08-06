### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1432.3<br />
<br />
Final Rank Value (1432.3) = Starting Rank Value (1687.8) + Head To Head Adjustments (-255.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.774[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.353[<sup>2</sup>](#table1)
- LAN Wins: 0.815[<sup>2</sup>](#table1)

The average of these factors is 0.626<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1687.8
- 400 + ( ( 0.626 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1687.8


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
|           83 |       55 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       81 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |      125 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      159 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      200 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      320 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    26.49 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      334 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.420 (0.273)    | 0.758 (0.493)    | 1 (1.000) |    18.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      348 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.173 (0.112)    | -                | 1 (1.000) |    15.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      374 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -6.01 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      414 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      426 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      454 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.452 (0.294)    | 1 (1.000) |     9.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      721 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.700 (0.350)    | -         |     5.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      824 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      950 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |     1032 | 2024-06-17 | 5W                | L   | 0.865      | -            | -                | -                | -         |   -24.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |     1046 | 2024-06-16 | B8                | L   | 0.860      | -            | -                | -                | -         |   -22.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1051 | 2024-06-16 | Permitta          | W   | 0.859      | 0.435        | -                | 0.919 (0.343)    | -         |     1.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1057 | 2024-06-16 | Enterprise        | W   | 0.858      | -            | -                | -                | -         |     1.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1072 | 2024-06-15 | GUN5              | W   | 0.854      | -            | -                | -                | -         |     1.89 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1092 | 2024-06-15 | BLEED             | W   | 0.852      | -            | -                | -                | -         |    10.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1126 | 2024-06-14 | Sashi             | W   | 0.846      | -            | -                | -                | -         |     5.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1137 | 2024-06-14 | Passion UA        | W   | 0.844      | 0.435        | 0.173 (0.064)    | 1.000 (0.367)    | -         |     3.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1155 | 2024-06-13 | 9INE              | W   | 0.840      | -            | -                | -                | -         |     1.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1167 | 2024-06-13 | VP.Prodigy        | W   | 0.838      | -            | -                | -                | -         |     1.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1198 | 2024-06-11 | SINNERS           | W   | 0.827      | -            | -                | -                | -         |     2.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1209 | 2024-06-11 | BUHAWI            | W   | 0.826      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1225 | 2024-06-10 | EYEBALLERS        | W   | 0.820      | -            | -                | -                | -         |     1.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1232 | 2024-06-10 | SAW               | W   | 0.819      | -            | -                | -                | -         |     4.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1239 | 2024-06-10 | PARIVISION        | W   | 0.819      | -            | -                | -                | -         |     3.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1243 | 2024-06-10 | 9 Pandas          | W   | 0.818      | -            | -                | -                | -         |     2.99 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1265 | 2024-06-09 | 9INE              | L   | 0.813      | -            | -                | -                | -         |   -24.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1278 | 2024-06-09 | Monte             | L   | 0.813      | -            | -                | -                | -         |   -23.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1285 | 2024-06-09 | SINNERS           | L   | 0.813      | -            | -                | -                | -         |   -23.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1292 | 2024-06-09 | Aurora            | W   | 0.812      | 0.143        | 0.420 (0.049)    | -                | -         |    12.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1302 | 2024-06-09 | RUSH B            | W   | 0.812      | -            | -                | -                | -         |     0.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1340 | 2024-06-08 | Illuminar         | L   | 0.806      | -            | -                | -                | -         |   -24.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1398 | 2024-06-07 | Gaimin Gladiators | W   | 0.800      | -            | -                | -                | -         |     1.33 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1437 | 2024-06-06 | Nexus             | W   | 0.795      | -            | -                | -                | -         |     0.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1454 | 2024-06-06 | Sangal            | L   | 0.794      | -            | -                | -                | -         |   -21.97 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1517 | 2024-06-05 | KOI               | L   | 0.787      | -            | -                | -                | -         |   -23.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1563 | 2024-06-04 | Aurora            | W   | 0.780      | 0.500        | 0.420 (0.164)    | 0.758 (0.296)    | -         |    12.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1647 | 2024-06-01 | VP.Prodigy        | L   | 0.760      | -            | -                | -                | -         |   -23.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1700 | 2024-05-30 | Sampi             | W   | 0.747      | 0.435        | -                | 1.000 (0.325)    | -         |     0.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1822 | 2024-05-25 | MOUZ NXT          | L   | 0.711      | -            | -                | -                | -         |   -21.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1845 | 2024-05-23 | Zero Tenacity     | W   | 0.699      | 0.435        | -                | 1.000 (0.304)    | -         |     1.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2059 | 2024-05-17 | B8                | L   | 0.659      | -            | -                | -                | -         |   -19.37 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2145 | 2024-05-15 | Zero Tenacity     | L   | 0.646      | -            | -                | -                | -         |   -19.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2341 | 2024-05-08 | G2                | L   | 0.600      | -            | -                | -                | -         |    -2.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2484 | 2024-05-01 | Sashi             | L   | 0.552      | -            | -                | -                | -         |   -16.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2508 | 2024-04-30 | BetBoom           | W   | 0.545      | 0.384        | 0.248 (0.052)    | -                | -         |     3.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2516 | 2024-04-29 | PARIVISION        | W   | 0.540      | -            | -                | -                | -         |     0.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2563 | 2024-04-27 | Astralis          | L   | 0.526      | -            | -                | -                | -         |    -5.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2637 | 2024-04-24 | fnatic            | W   | 0.506      | 0.889        | 0.371 (0.167)    | 0.680 (0.306)    | 1 (0.506) |     5.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2662 | 2024-04-23 | SAW               | W   | 0.499      | -            | -                | -                | 1 (0.499) |     1.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2671 | 2024-04-22 | ex-Guild Eagles   | W   | 0.493      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2867 | 2024-04-17 | BLEED             | W   | 0.458      | -            | -                | -                | -         |     0.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2925 | 2024-04-14 | BetBoom           | L   | 0.439      | -            | -                | -                | -         |   -10.97 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2939 | 2024-04-13 | ex-Preasy         | W   | 0.432      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2981 | 2024-04-11 | Passion UA        | L   | 0.419      | -            | -                | -                | -         |   -12.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     3015 | 2024-04-10 | SINNERS           | L   | 0.414      | -            | -                | -                | -         |   -12.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3067 | 2024-04-09 | SAW               | W   | 0.407      | -            | -                | -                | -         |     0.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3141 | 2024-04-07 | Young Ninjas      | W   | 0.393      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3213 | 2024-04-04 | Space             | W   | 0.373      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3241 | 2024-04-03 | GUN5              | W   | 0.367      | -            | -                | -                | -         |     0.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3294 | 2024-04-02 | Permitta          | W   | 0.359      | -            | -                | -                | -         |     0.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3349 | 2024-03-28 | Apeks             | W   | 0.326      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3475 | 2024-03-21 | fnatic            | L   | 0.280      | -            | -                | -                | -         |    -5.84 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3515 | 2024-03-19 | GUN5              | W   | 0.266      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3585 | 2024-03-15 | B8                | W   | 0.240      | -            | -                | -                | -         |     0.29 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3655 | 2024-03-13 | PARIVISION        | L   | 0.226      | -            | -                | -                | -         |    -6.84 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3866 | 2024-03-05 | FORZE             | L   | 0.174      | -            | -                | -                | -         |    -5.40 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3889 | 2024-03-04 | fnatic            | L   | 0.166      | -            | -                | -                | -         |    -3.60 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3927 | 2024-03-02 | Monte             | W   | 0.154      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3962 | 2024-02-29 | Gaimin Gladiators | W   | 0.141      | -            | -                | -                | -         |     0.07 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4264 | 2024-02-16 | 9 Pandas          | L   | 0.053      | -            | -                | -                | -         |    -1.63 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4288 | 2024-02-15 | Into the Breach   | W   | 0.047      | -            | -                | -                | 1 (0.047) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4324 | 2024-02-14 | KOI               | L   | 0.041      | -            | -                | -                | -         |    -1.24 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4330 | 2024-02-14 | Falcons           | L   | 0.040      | -            | -                | -                | -         |    -1.02 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4378 | 2024-02-11 | Apeks             | L   | 0.020      | -            | -                | -                | -         |    -0.63 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4402 | 2024-02-09 | fnatic            | W   | 0.007      | -            | -                | -                | -         |     0.07 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4403 | 2024-02-09 | Endpoint          | W   | 0.007      | -            | -                | -                | -         |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4408 | 2024-02-09 | ex-Sprout         | L   | 0.006      | -            | -                | -                | -         |    -0.19 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,235.21)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.865 | $10,000.00     | $8,652.78       |
| 2024-06-16 |      0.860 | $10,000.00     | $8,600.00       |
| 2024-06-09 |      0.813 | $7,000.00      | $5,692.85       |
| 2024-06-02 |      0.766 | $2,000.00      | $1,532.78       |
| 2024-05-26 |      0.720 | $2,000.00      | $1,440.00       |
| 2024-05-12 |      0.626 | $23,500.00     | $14,720.14      |
| 2024-05-02 |      0.560 | $1,500.00      | $840.00         |
| 2024-04-14 |      0.439 | $4,000.00      | $1,756.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
