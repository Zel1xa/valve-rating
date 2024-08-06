### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1431.1<br />
<br />
Final Rank Value (1431.1) = Starting Rank Value (1687.5) + Head To Head Adjustments (-256.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.774[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.353[<sup>2</sup>](#table1)
- LAN Wins: 0.814[<sup>2</sup>](#table1)

The average of these factors is 0.626<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1687.5
- 400 + ( ( 0.626 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1687.5


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
|           83 |       42 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       68 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |      112 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      145 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      187 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      307 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    26.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      321 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.421 (0.273)    | 0.759 (0.493)    | 1 (1.000) |    18.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      335 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.173 (0.113)    | -                | 1 (1.000) |    15.37 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      361 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.97 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      401 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      413 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      441 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.453 (0.294)    | 1 (1.000) |     9.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      708 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.700 (0.350)    | -         |     4.96 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      811 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      937 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |     1019 | 2024-06-17 | 5W                | L   | 0.867      | -            | -                | -                | -         |   -24.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |     1033 | 2024-06-16 | B8                | L   | 0.861      | -            | -                | -                | -         |   -22.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1038 | 2024-06-16 | Permitta          | W   | 0.861      | 0.435        | -                | 0.919 (0.344)    | -         |     1.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1044 | 2024-06-16 | Enterprise        | W   | 0.860      | -            | -                | -                | -         |     1.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1059 | 2024-06-15 | GUN5              | W   | 0.855      | -            | -                | -                | -         |     1.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1079 | 2024-06-15 | BLEED             | W   | 0.853      | -            | -                | -                | -         |    10.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1113 | 2024-06-14 | Sashi             | W   | 0.847      | -            | -                | -                | -         |     5.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1124 | 2024-06-14 | Passion UA        | W   | 0.846      | 0.435        | 0.173 (0.064)    | 1.000 (0.368)    | -         |     3.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1142 | 2024-06-13 | 9INE              | W   | 0.841      | -            | -                | -                | -         |     1.49 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1154 | 2024-06-13 | VP.Prodigy        | W   | 0.840      | -            | -                | -                | -         |     1.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1185 | 2024-06-11 | SINNERS           | W   | 0.829      | -            | -                | -                | -         |     2.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1196 | 2024-06-11 | BUHAWI            | W   | 0.828      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1212 | 2024-06-10 | EYEBALLERS        | W   | 0.821      | -            | -                | -                | -         |     1.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1219 | 2024-06-10 | SAW               | W   | 0.821      | -            | -                | -                | -         |     4.94 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1226 | 2024-06-10 | PARIVISION        | W   | 0.820      | -            | -                | -                | -         |     3.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1230 | 2024-06-10 | 9 Pandas          | W   | 0.820      | -            | -                | -                | -         |     2.94 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1252 | 2024-06-09 | 9INE              | L   | 0.815      | -            | -                | -                | -         |   -24.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1265 | 2024-06-09 | Monte             | L   | 0.814      | -            | -                | -                | -         |   -23.79 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1272 | 2024-06-09 | SINNERS           | L   | 0.814      | -            | -                | -                | -         |   -23.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1279 | 2024-06-09 | Aurora            | W   | 0.813      | 0.143        | 0.421 (0.049)    | -                | -         |    12.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1289 | 2024-06-09 | RUSH B            | W   | 0.813      | -            | -                | -                | -         |     0.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1327 | 2024-06-08 | Illuminar         | L   | 0.808      | -            | -                | -                | -         |   -24.70 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1385 | 2024-06-07 | Gaimin Gladiators | W   | 0.801      | -            | -                | -                | -         |     1.34 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1424 | 2024-06-06 | Nexus             | W   | 0.796      | -            | -                | -                | -         |     0.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1441 | 2024-06-06 | Sangal            | L   | 0.795      | -            | -                | -                | -         |   -22.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1504 | 2024-06-05 | KOI               | L   | 0.788      | -            | -                | -                | -         |   -23.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1550 | 2024-06-04 | Aurora            | W   | 0.782      | 0.500        | 0.421 (0.164)    | 0.759 (0.297)    | -         |    12.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1634 | 2024-06-01 | VP.Prodigy        | L   | 0.761      | -            | -                | -                | -         |   -23.28 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1687 | 2024-05-30 | Sampi             | W   | 0.749      | 0.435        | -                | 1.000 (0.325)    | -         |     0.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1809 | 2024-05-25 | MOUZ NXT          | L   | 0.713      | -            | -                | -                | -         |   -21.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1832 | 2024-05-23 | Zero Tenacity     | W   | 0.701      | 0.435        | -                | 1.000 (0.305)    | -         |     1.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2046 | 2024-05-17 | B8                | L   | 0.660      | -            | -                | -                | -         |   -19.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2132 | 2024-05-15 | Zero Tenacity     | L   | 0.647      | -            | -                | -                | -         |   -19.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2328 | 2024-05-08 | G2                | L   | 0.601      | -            | -                | -                | -         |    -2.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2471 | 2024-05-01 | Sashi             | L   | 0.553      | -            | -                | -                | -         |   -16.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2495 | 2024-04-30 | BetBoom           | W   | 0.547      | 0.384        | 0.248 (0.052)    | -                | -         |     3.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2503 | 2024-04-29 | PARIVISION        | W   | 0.542      | -            | -                | -                | -         |     0.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2550 | 2024-04-27 | Astralis          | L   | 0.528      | -            | -                | -                | -         |    -5.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2624 | 2024-04-24 | fnatic            | W   | 0.508      | 0.889        | 0.371 (0.167)    | 0.680 (0.307)    | 1 (0.508) |     5.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2649 | 2024-04-23 | SAW               | W   | 0.500      | -            | -                | -                | 1 (0.500) |     1.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2658 | 2024-04-22 | ex-Guild Eagles   | W   | 0.495      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2854 | 2024-04-17 | BLEED             | W   | 0.460      | -            | -                | -                | -         |     0.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2912 | 2024-04-14 | BetBoom           | L   | 0.441      | -            | -                | -                | -         |   -10.99 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2926 | 2024-04-13 | ex-Preasy         | W   | 0.434      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2968 | 2024-04-11 | Passion UA        | L   | 0.421      | -            | -                | -                | -         |   -12.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     3002 | 2024-04-10 | SINNERS           | L   | 0.415      | -            | -                | -                | -         |   -12.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3054 | 2024-04-09 | SAW               | W   | 0.409      | -            | -                | -                | -         |     0.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3128 | 2024-04-07 | Young Ninjas      | W   | 0.394      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3200 | 2024-04-04 | Space             | W   | 0.374      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3228 | 2024-04-03 | GUN5              | W   | 0.369      | -            | -                | -                | -         |     0.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3281 | 2024-04-02 | Permitta          | W   | 0.361      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3336 | 2024-03-28 | Apeks             | W   | 0.328      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3462 | 2024-03-21 | fnatic            | L   | 0.281      | -            | -                | -                | -         |    -5.86 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3502 | 2024-03-19 | GUN5              | W   | 0.267      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3572 | 2024-03-15 | B8                | W   | 0.241      | -            | -                | -                | -         |     0.29 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3642 | 2024-03-13 | PARIVISION        | L   | 0.228      | -            | -                | -                | -         |    -6.88 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3853 | 2024-03-05 | FORZE             | L   | 0.175      | -            | -                | -                | -         |    -5.44 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3876 | 2024-03-04 | fnatic            | L   | 0.167      | -            | -                | -                | -         |    -3.62 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3914 | 2024-03-02 | Monte             | W   | 0.156      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3949 | 2024-02-29 | Gaimin Gladiators | W   | 0.142      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4251 | 2024-02-16 | 9 Pandas          | L   | 0.054      | -            | -                | -                | -         |    -1.67 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4275 | 2024-02-15 | Into the Breach   | W   | 0.048      | -            | -                | -                | 1 (0.048) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4311 | 2024-02-14 | KOI               | L   | 0.042      | -            | -                | -                | -         |    -1.28 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4317 | 2024-02-14 | Falcons           | L   | 0.041      | -            | -                | -                | -         |    -1.06 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4365 | 2024-02-11 | Apeks             | L   | 0.022      | -            | -                | -                | -         |    -0.67 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4389 | 2024-02-09 | fnatic            | W   | 0.008      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4390 | 2024-02-09 | Endpoint          | W   | 0.008      | -            | -                | -                | -         |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4395 | 2024-02-09 | ex-Sprout         | L   | 0.007      | -            | -                | -                | -         |    -0.23 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,318.54)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.867 | $10,000.00     | $8,666.67       |
| 2024-06-16 |      0.861 | $10,000.00     | $8,613.89       |
| 2024-06-09 |      0.815 | $7,000.00      | $5,702.57       |
| 2024-06-02 |      0.768 | $2,000.00      | $1,535.56       |
| 2024-05-26 |      0.721 | $2,000.00      | $1,442.78       |
| 2024-05-12 |      0.628 | $23,500.00     | $14,752.78      |
| 2024-05-02 |      0.561 | $1,500.00      | $842.08         |
| 2024-04-14 |      0.441 | $4,000.00      | $1,762.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
