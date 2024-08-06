### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1431.4<br />
<br />
Final Rank Value (1431.4) = Starting Rank Value (1687.6) + Head To Head Adjustments (-256.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.774[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.353[<sup>2</sup>](#table1)
- LAN Wins: 0.814[<sup>2</sup>](#table1)

The average of these factors is 0.626<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1687.6
- 400 + ( ( 0.626 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1687.6


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
|           83 |       45 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       71 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |      115 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      148 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      190 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      310 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    26.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      324 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.420 (0.273)    | 0.759 (0.493)    | 1 (1.000) |    18.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      338 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.173 (0.113)    | -                | 1 (1.000) |    15.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      364 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      404 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      416 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      444 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.453 (0.294)    | 1 (1.000) |     9.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      711 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.700 (0.350)    | -         |     4.96 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      814 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      940 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |     1022 | 2024-06-17 | 5W                | L   | 0.866      | -            | -                | -                | -         |   -24.85 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |     1036 | 2024-06-16 | B8                | L   | 0.861      | -            | -                | -                | -         |   -22.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1041 | 2024-06-16 | Permitta          | W   | 0.860      | 0.435        | -                | 0.919 (0.344)    | -         |     1.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1047 | 2024-06-16 | Enterprise        | W   | 0.859      | -            | -                | -                | -         |     1.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1062 | 2024-06-15 | GUN5              | W   | 0.855      | -            | -                | -                | -         |     1.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1082 | 2024-06-15 | BLEED             | W   | 0.853      | -            | -                | -                | -         |    10.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1116 | 2024-06-14 | Sashi             | W   | 0.847      | -            | -                | -                | -         |     5.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1127 | 2024-06-14 | Passion UA        | W   | 0.845      | 0.435        | 0.173 (0.064)    | 1.000 (0.367)    | -         |     3.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1145 | 2024-06-13 | 9INE              | W   | 0.841      | -            | -                | -                | -         |     1.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1157 | 2024-06-13 | VP.Prodigy        | W   | 0.839      | -            | -                | -                | -         |     1.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1188 | 2024-06-11 | SINNERS           | W   | 0.828      | -            | -                | -                | -         |     2.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1199 | 2024-06-11 | BUHAWI            | W   | 0.827      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1215 | 2024-06-10 | EYEBALLERS        | W   | 0.821      | -            | -                | -                | -         |     1.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1222 | 2024-06-10 | SAW               | W   | 0.820      | -            | -                | -                | -         |     4.93 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1229 | 2024-06-10 | PARIVISION        | W   | 0.820      | -            | -                | -                | -         |     3.35 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1233 | 2024-06-10 | 9 Pandas          | W   | 0.819      | -            | -                | -                | -         |     2.94 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1255 | 2024-06-09 | 9INE              | L   | 0.814      | -            | -                | -                | -         |   -24.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1268 | 2024-06-09 | Monte             | L   | 0.814      | -            | -                | -                | -         |   -23.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1275 | 2024-06-09 | SINNERS           | L   | 0.814      | -            | -                | -                | -         |   -23.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1282 | 2024-06-09 | Aurora            | W   | 0.813      | 0.143        | 0.420 (0.049)    | -                | -         |    12.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1292 | 2024-06-09 | RUSH B            | W   | 0.813      | -            | -                | -                | -         |     0.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1330 | 2024-06-08 | Illuminar         | L   | 0.807      | -            | -                | -                | -         |   -24.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1388 | 2024-06-07 | Gaimin Gladiators | W   | 0.801      | -            | -                | -                | -         |     1.34 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1427 | 2024-06-06 | Nexus             | W   | 0.796      | -            | -                | -                | -         |     0.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1444 | 2024-06-06 | Sangal            | L   | 0.795      | -            | -                | -                | -         |   -22.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1507 | 2024-06-05 | KOI               | L   | 0.788      | -            | -                | -                | -         |   -23.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1553 | 2024-06-04 | Aurora            | W   | 0.781      | 0.500        | 0.420 (0.164)    | 0.759 (0.296)    | -         |    12.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1637 | 2024-06-01 | VP.Prodigy        | L   | 0.761      | -            | -                | -                | -         |   -23.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1690 | 2024-05-30 | Sampi             | W   | 0.748      | 0.435        | -                | 1.000 (0.325)    | -         |     0.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1812 | 2024-05-25 | MOUZ NXT          | L   | 0.712      | -            | -                | -                | -         |   -21.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1835 | 2024-05-23 | Zero Tenacity     | W   | 0.700      | 0.435        | -                | 1.000 (0.304)    | -         |     1.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2049 | 2024-05-17 | B8                | L   | 0.660      | -            | -                | -                | -         |   -19.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2135 | 2024-05-15 | Zero Tenacity     | L   | 0.647      | -            | -                | -                | -         |   -19.44 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2331 | 2024-05-08 | G2                | L   | 0.601      | -            | -                | -                | -         |    -2.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2474 | 2024-05-01 | Sashi             | L   | 0.553      | -            | -                | -                | -         |   -16.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2498 | 2024-04-30 | BetBoom           | W   | 0.546      | 0.384        | 0.248 (0.052)    | -                | -         |     3.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2506 | 2024-04-29 | PARIVISION        | W   | 0.541      | -            | -                | -                | -         |     0.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2553 | 2024-04-27 | Astralis          | L   | 0.527      | -            | -                | -                | -         |    -5.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2627 | 2024-04-24 | fnatic            | W   | 0.507      | 0.889        | 0.371 (0.167)    | 0.680 (0.307)    | 1 (0.507) |     5.79 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2652 | 2024-04-23 | SAW               | W   | 0.500      | -            | -                | -                | 1 (0.500) |     1.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2661 | 2024-04-22 | ex-Guild Eagles   | W   | 0.494      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2857 | 2024-04-17 | BLEED             | W   | 0.459      | -            | -                | -                | -         |     0.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2915 | 2024-04-14 | BetBoom           | L   | 0.440      | -            | -                | -                | -         |   -10.99 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2929 | 2024-04-13 | ex-Preasy         | W   | 0.434      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2971 | 2024-04-11 | Passion UA        | L   | 0.420      | -            | -                | -                | -         |   -12.79 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     3005 | 2024-04-10 | SINNERS           | L   | 0.415      | -            | -                | -                | -         |   -12.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3057 | 2024-04-09 | SAW               | W   | 0.408      | -            | -                | -                | -         |     0.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3131 | 2024-04-07 | Young Ninjas      | W   | 0.394      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3203 | 2024-04-04 | Space             | W   | 0.374      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3231 | 2024-04-03 | GUN5              | W   | 0.368      | -            | -                | -                | -         |     0.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3284 | 2024-04-02 | Permitta          | W   | 0.360      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3339 | 2024-03-28 | Apeks             | W   | 0.327      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3465 | 2024-03-21 | fnatic            | L   | 0.281      | -            | -                | -                | -         |    -5.86 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3505 | 2024-03-19 | GUN5              | W   | 0.267      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3575 | 2024-03-15 | B8                | W   | 0.241      | -            | -                | -                | -         |     0.29 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3645 | 2024-03-13 | PARIVISION        | L   | 0.227      | -            | -                | -                | -         |    -6.87 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3856 | 2024-03-05 | FORZE             | L   | 0.175      | -            | -                | -                | -         |    -5.43 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3879 | 2024-03-04 | fnatic            | L   | 0.167      | -            | -                | -                | -         |    -3.62 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3917 | 2024-03-02 | Monte             | W   | 0.155      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3952 | 2024-02-29 | Gaimin Gladiators | W   | 0.142      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4254 | 2024-02-16 | 9 Pandas          | L   | 0.054      | -            | -                | -                | -         |    -1.66 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4278 | 2024-02-15 | Into the Breach   | W   | 0.048      | -            | -                | -                | 1 (0.048) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4314 | 2024-02-14 | KOI               | L   | 0.042      | -            | -                | -                | -         |    -1.27 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4320 | 2024-02-14 | Falcons           | L   | 0.041      | -            | -                | -                | -         |    -1.05 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4368 | 2024-02-11 | Apeks             | L   | 0.021      | -            | -                | -                | -         |    -0.66 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4392 | 2024-02-09 | fnatic            | W   | 0.008      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4393 | 2024-02-09 | Endpoint          | W   | 0.008      | -            | -                | -                | -         |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4398 | 2024-02-09 | ex-Sprout         | L   | 0.007      | -            | -                | -                | -         |    -0.22 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,296.32)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.866 | $10,000.00     | $8,662.96       |
| 2024-06-16 |      0.861 | $10,000.00     | $8,610.19       |
| 2024-06-09 |      0.814 | $7,000.00      | $5,699.98       |
| 2024-06-02 |      0.767 | $2,000.00      | $1,534.81       |
| 2024-05-26 |      0.721 | $2,000.00      | $1,442.04       |
| 2024-05-12 |      0.627 | $23,500.00     | $14,744.07      |
| 2024-05-02 |      0.561 | $1,500.00      | $841.53         |
| 2024-04-14 |      0.440 | $4,000.00      | $1,760.74       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
