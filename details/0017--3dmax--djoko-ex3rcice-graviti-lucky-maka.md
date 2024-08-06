### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1431.2<br />
<br />
Final Rank Value (1431.2) = Starting Rank Value (1687.6) + Head To Head Adjustments (-256.4)<br />

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
|           83 |       44 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       68 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |      110 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      143 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      185 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      305 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    26.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      319 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.420 (0.273)    | 0.759 (0.493)    | 1 (1.000) |    18.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      333 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.173 (0.113)    | -                | 1 (1.000) |    15.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      359 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      399 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      411 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      439 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.452 (0.294)    | 1 (1.000) |     9.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      706 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.700 (0.350)    | -         |     4.96 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      809 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      935 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |     1017 | 2024-06-17 | 5W                | L   | 0.866      | -            | -                | -                | -         |   -24.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |     1031 | 2024-06-16 | B8                | L   | 0.861      | -            | -                | -                | -         |   -22.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1036 | 2024-06-16 | Permitta          | W   | 0.860      | 0.435        | -                | 0.919 (0.343)    | -         |     1.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1042 | 2024-06-16 | Enterprise        | W   | 0.859      | -            | -                | -                | -         |     1.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1057 | 2024-06-15 | GUN5              | W   | 0.855      | -            | -                | -                | -         |     1.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1077 | 2024-06-15 | BLEED             | W   | 0.852      | -            | -                | -                | -         |    10.02 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1111 | 2024-06-14 | Sashi             | W   | 0.847      | -            | -                | -                | -         |     5.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1122 | 2024-06-14 | Passion UA        | W   | 0.845      | 0.435        | 0.173 (0.064)    | 1.000 (0.367)    | -         |     3.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1140 | 2024-06-13 | 9INE              | W   | 0.841      | -            | -                | -                | -         |     1.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1152 | 2024-06-13 | VP.Prodigy        | W   | 0.839      | -            | -                | -                | -         |     1.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1183 | 2024-06-11 | SINNERS           | W   | 0.828      | -            | -                | -                | -         |     2.38 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1194 | 2024-06-11 | BUHAWI            | W   | 0.827      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1210 | 2024-06-10 | EYEBALLERS        | W   | 0.821      | -            | -                | -                | -         |     1.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1217 | 2024-06-10 | SAW               | W   | 0.820      | -            | -                | -                | -         |     4.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1224 | 2024-06-10 | PARIVISION        | W   | 0.819      | -            | -                | -                | -         |     3.35 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1228 | 2024-06-10 | 9 Pandas          | W   | 0.819      | -            | -                | -                | -         |     2.93 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1250 | 2024-06-09 | 9INE              | L   | 0.814      | -            | -                | -                | -         |   -24.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1263 | 2024-06-09 | Monte             | L   | 0.814      | -            | -                | -                | -         |   -23.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1270 | 2024-06-09 | SINNERS           | L   | 0.813      | -            | -                | -                | -         |   -23.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1277 | 2024-06-09 | Aurora            | W   | 0.813      | 0.143        | 0.420 (0.049)    | -                | -         |    12.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1287 | 2024-06-09 | RUSH B            | W   | 0.812      | -            | -                | -                | -         |     0.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1325 | 2024-06-08 | Illuminar         | L   | 0.807      | -            | -                | -                | -         |   -24.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1383 | 2024-06-07 | Gaimin Gladiators | W   | 0.800      | -            | -                | -                | -         |     1.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1422 | 2024-06-06 | Nexus             | W   | 0.795      | -            | -                | -                | -         |     0.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1439 | 2024-06-06 | Sangal            | L   | 0.794      | -            | -                | -                | -         |   -22.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1502 | 2024-06-05 | KOI               | L   | 0.788      | -            | -                | -                | -         |   -23.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1548 | 2024-06-04 | Aurora            | W   | 0.781      | 0.500        | 0.420 (0.164)    | 0.759 (0.296)    | -         |    11.99 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1632 | 2024-06-01 | VP.Prodigy        | L   | 0.761      | -            | -                | -                | -         |   -23.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1685 | 2024-05-30 | Sampi             | W   | 0.748      | 0.435        | -                | 1.000 (0.325)    | -         |     0.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1807 | 2024-05-25 | MOUZ NXT          | L   | 0.712      | -            | -                | -                | -         |   -21.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1830 | 2024-05-23 | Zero Tenacity     | W   | 0.700      | 0.435        | -                | 1.000 (0.304)    | -         |     1.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2044 | 2024-05-17 | B8                | L   | 0.660      | -            | -                | -                | -         |   -19.39 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2130 | 2024-05-15 | Zero Tenacity     | L   | 0.646      | -            | -                | -                | -         |   -19.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2326 | 2024-05-08 | G2                | L   | 0.600      | -            | -                | -                | -         |    -2.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2469 | 2024-05-01 | Sashi             | L   | 0.553      | -            | -                | -                | -         |   -16.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2493 | 2024-04-30 | BetBoom           | W   | 0.546      | 0.384        | 0.248 (0.052)    | -                | -         |     3.82 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2501 | 2024-04-29 | PARIVISION        | W   | 0.541      | -            | -                | -                | -         |     0.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2548 | 2024-04-27 | Astralis          | L   | 0.527      | -            | -                | -                | -         |    -5.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2622 | 2024-04-24 | fnatic            | W   | 0.507      | 0.889        | 0.371 (0.167)    | 0.680 (0.307)    | 1 (0.507) |     5.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2647 | 2024-04-23 | SAW               | W   | 0.499      | -            | -                | -                | 1 (0.499) |     1.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2656 | 2024-04-22 | ex-Guild Eagles   | W   | 0.494      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2852 | 2024-04-17 | BLEED             | W   | 0.459      | -            | -                | -                | -         |     0.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2910 | 2024-04-14 | BetBoom           | L   | 0.440      | -            | -                | -                | -         |   -10.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2924 | 2024-04-13 | ex-Preasy         | W   | 0.433      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2966 | 2024-04-11 | Passion UA        | L   | 0.420      | -            | -                | -                | -         |   -12.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     3000 | 2024-04-10 | SINNERS           | L   | 0.415      | -            | -                | -                | -         |   -12.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3052 | 2024-04-09 | SAW               | W   | 0.408      | -            | -                | -                | -         |     0.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3126 | 2024-04-07 | Young Ninjas      | W   | 0.393      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3198 | 2024-04-04 | Space             | W   | 0.374      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3226 | 2024-04-03 | GUN5              | W   | 0.368      | -            | -                | -                | -         |     0.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3279 | 2024-04-02 | Permitta          | W   | 0.360      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3334 | 2024-03-28 | Apeks             | W   | 0.327      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3460 | 2024-03-21 | fnatic            | L   | 0.280      | -            | -                | -                | -         |    -5.85 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3500 | 2024-03-19 | GUN5              | W   | 0.267      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3570 | 2024-03-15 | B8                | W   | 0.241      | -            | -                | -                | -         |     0.29 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3640 | 2024-03-13 | PARIVISION        | L   | 0.227      | -            | -                | -                | -         |    -6.86 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3851 | 2024-03-05 | FORZE             | L   | 0.174      | -            | -                | -                | -         |    -5.42 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3874 | 2024-03-04 | fnatic            | L   | 0.167      | -            | -                | -                | -         |    -3.61 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3912 | 2024-03-02 | Monte             | W   | 0.155      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3947 | 2024-02-29 | Gaimin Gladiators | W   | 0.142      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4249 | 2024-02-16 | 9 Pandas          | L   | 0.054      | -            | -                | -                | -         |    -1.65 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4273 | 2024-02-15 | Into the Breach   | W   | 0.047      | -            | -                | -                | 1 (0.047) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4309 | 2024-02-14 | KOI               | L   | 0.041      | -            | -                | -                | -         |    -1.26 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4315 | 2024-02-14 | Falcons           | L   | 0.040      | -            | -                | -                | -         |    -1.04 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4363 | 2024-02-11 | Apeks             | L   | 0.021      | -            | -                | -                | -         |    -0.65 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4387 | 2024-02-09 | fnatic            | W   | 0.008      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4388 | 2024-02-09 | Endpoint          | W   | 0.007      | -            | -                | -                | -         |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4393 | 2024-02-09 | ex-Sprout         | L   | 0.007      | -            | -                | -                | -         |    -0.21 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,279.65)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.866 | $10,000.00     | $8,660.19       |
| 2024-06-16 |      0.861 | $10,000.00     | $8,607.41       |
| 2024-06-09 |      0.814 | $7,000.00      | $5,698.03       |
| 2024-06-02 |      0.767 | $2,000.00      | $1,534.26       |
| 2024-05-26 |      0.721 | $2,000.00      | $1,441.48       |
| 2024-05-12 |      0.627 | $23,500.00     | $14,737.55      |
| 2024-05-02 |      0.561 | $1,500.00      | $841.11         |
| 2024-04-14 |      0.440 | $4,000.00      | $1,759.63       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
