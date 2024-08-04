### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1445.2<br />
<br />
Final Rank Value (1445.2) = Starting Rank Value (1682.7) + Head To Head Adjustments (-237.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.772[<sup>1</sup>](#table2)
- Bounty Collected: 0.564[<sup>2</sup>](#table1)
- Opponent Network: 0.363[<sup>2</sup>](#table1)
- LAN Wins: 0.811[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1682.7
- 400 + ( ( 0.627 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1682.7


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
|           82 |        4 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |       46 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.52 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |       79 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      119 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      239 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    26.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      253 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.424 (0.276)    | 0.793 (0.516)    | 1 (1.000) |    18.54 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      267 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.169 (0.110)    | -                | 1 (1.000) |    15.28 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      293 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      333 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      345 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.18 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      373 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.085)    | 0.476 (0.309)    | 1 (1.000) |     9.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      637 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.690 (0.345)    | -         |     5.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      741 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      869 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -29.99 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |      951 | 2024-06-17 | 5W                | L   | 0.880      | -            | -                | -                | -         |   -25.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |      965 | 2024-06-16 | B8                | L   | 0.875      | -            | -                | -                | -         |   -22.79 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |      970 | 2024-06-16 | Permitta          | W   | 0.874      | 0.435        | -                | 0.876 (0.333)    | -         |     1.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |      976 | 2024-06-16 | Enterprise        | W   | 0.873      | -            | -                | -                | -         |     1.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |      991 | 2024-06-15 | GUN5              | W   | 0.869      | -            | -                | -                | -         |     2.00 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1011 | 2024-06-15 | BLEED             | W   | 0.867      | -            | -                | -                | -         |    10.35 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1045 | 2024-06-14 | Sashi             | W   | 0.861      | -            | -                | -                | -         |     5.91 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1056 | 2024-06-14 | Passion UA        | W   | 0.859      | 0.435        | 0.172 (0.064)    | 1.000 (0.374)    | -         |     3.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1074 | 2024-06-13 | 9INE              | W   | 0.855      | -            | -                | -                | -         |     1.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1086 | 2024-06-13 | VP.Prodigy        | W   | 0.853      | -            | -                | -                | -         |     1.35 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1117 | 2024-06-11 | SINNERS           | W   | 0.842      | -            | -                | -                | -         |     2.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1128 | 2024-06-11 | BUHAWI            | W   | 0.841      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1144 | 2024-06-10 | EYEBALLERS        | W   | 0.835      | -            | -                | -                | -         |     1.33 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1151 | 2024-06-10 | SAW               | W   | 0.834      | -            | -                | -                | -         |     5.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1158 | 2024-06-10 | PARIVISION        | W   | 0.834      | -            | -                | -                | -         |     3.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1162 | 2024-06-10 | 9 Pandas          | W   | 0.833      | -            | -                | -                | -         |     3.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1184 | 2024-06-09 | 9INE              | L   | 0.828      | -            | -                | -                | -         |   -24.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1197 | 2024-06-09 | Monte             | L   | 0.828      | -            | -                | -                | -         |   -24.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1204 | 2024-06-09 | SINNERS           | L   | 0.828      | -            | -                | -                | -         |   -24.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1211 | 2024-06-09 | Aurora            | W   | 0.827      | 0.143        | 0.424 (0.050)    | -                | -         |    12.71 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1221 | 2024-06-09 | RUSH B            | W   | 0.827      | -            | -                | -                | -         |     0.85 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1259 | 2024-06-08 | Illuminar         | L   | 0.821      | -            | -                | -                | -         |   -25.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1317 | 2024-06-07 | Gaimin Gladiators | W   | 0.815      | -            | -                | -                | -         |     1.44 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1356 | 2024-06-06 | Nexus             | W   | 0.810      | -            | -                | -                | -         |     0.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1373 | 2024-06-06 | Sangal            | L   | 0.809      | -            | -                | -                | -         |   -22.37 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1436 | 2024-06-05 | KOI               | L   | 0.802      | -            | -                | -                | -         |   -23.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1482 | 2024-06-04 | Aurora            | W   | 0.795      | 0.500        | 0.424 (0.168)    | 0.793 (0.315)    | -         |    12.18 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1566 | 2024-06-01 | VP.Prodigy        | L   | 0.775      | -            | -                | -                | -         |   -23.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1619 | 2024-05-30 | Sampi             | W   | 0.762      | 0.435        | -                | 1.000 (0.331)    | -         |     0.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1741 | 2024-05-25 | MOUZ NXT          | L   | 0.726      | -            | -                | -                | -         |   -21.69 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1764 | 2024-05-23 | Zero Tenacity     | W   | 0.714      | 0.435        | -                | 1.000 (0.310)    | -         |     1.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     1978 | 2024-05-17 | B8                | L   | 0.674      | -            | -                | -                | -         |   -19.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2064 | 2024-05-15 | Zero Tenacity     | L   | 0.661      | -            | -                | -                | -         |   -19.82 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2260 | 2024-05-08 | G2                | L   | 0.615      | -            | -                | -                | -         |    -2.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2403 | 2024-05-01 | Sashi             | L   | 0.567      | -            | -                | -                | -         |   -16.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2427 | 2024-04-30 | BetBoom           | W   | 0.560      | 0.384        | 0.251 (0.054)    | -                | -         |     4.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2435 | 2024-04-29 | PARIVISION        | W   | 0.555      | -            | -                | -                | -         |     0.85 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2482 | 2024-04-27 | Astralis          | L   | 0.541      | -            | -                | -                | -         |    -6.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2556 | 2024-04-24 | fnatic            | W   | 0.521      | 0.889        | 0.371 (0.172)    | 0.708 (0.328)    | 1 (0.521) |     6.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2581 | 2024-04-23 | SAW               | W   | 0.514      | -            | -                | -                | 1 (0.514) |     1.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2590 | 2024-04-22 | ex-Guild Eagles   | W   | 0.508      | -            | -                | -                | -         |     0.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2786 | 2024-04-17 | BLEED             | W   | 0.473      | -            | -                | -                | -         |     0.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2844 | 2024-04-14 | BetBoom           | L   | 0.454      | -            | -                | -                | -         |   -11.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2858 | 2024-04-13 | ex-Preasy         | W   | 0.448      | -            | -                | -                | -         |     0.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2900 | 2024-04-11 | Passion UA        | L   | 0.434      | -            | -                | -                | -         |   -13.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2934 | 2024-04-10 | SINNERS           | L   | 0.429      | -            | -                | -                | -         |   -12.90 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     2986 | 2024-04-09 | SAW               | W   | 0.422      | -            | -                | -                | -         |     0.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3060 | 2024-04-07 | Young Ninjas      | W   | 0.407      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3132 | 2024-04-04 | Space             | W   | 0.388      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3160 | 2024-04-03 | GUN5              | W   | 0.382      | -            | -                | -                | -         |     0.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3213 | 2024-04-02 | Permitta          | W   | 0.374      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3268 | 2024-03-28 | Apeks             | W   | 0.341      | -            | -                | -                | -         |     0.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3394 | 2024-03-21 | fnatic            | L   | 0.295      | -            | -                | -                | -         |    -6.05 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3434 | 2024-03-19 | GUN5              | W   | 0.281      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3504 | 2024-03-15 | B8                | W   | 0.255      | -            | -                | -                | -         |     0.32 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3574 | 2024-03-13 | PARIVISION        | L   | 0.241      | -            | -                | -                | -         |    -7.29 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3785 | 2024-03-05 | FORZE             | L   | 0.189      | -            | -                | -                | -         |    -5.86 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3808 | 2024-03-04 | fnatic            | L   | 0.181      | -            | -                | -                | -         |    -3.87 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3846 | 2024-03-02 | Monte             | W   | 0.169      | -            | -                | -                | -         |     0.12 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3881 | 2024-02-29 | Gaimin Gladiators | W   | 0.156      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4183 | 2024-02-16 | 9 Pandas          | L   | 0.068      | -            | -                | -                | -         |    -2.09 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4207 | 2024-02-15 | Into the Breach   | W   | 0.062      | -            | -                | -                | 1 (0.062) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4243 | 2024-02-14 | KOI               | L   | 0.056      | -            | -                | -                | -         |    -1.69 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4249 | 2024-02-14 | Falcons           | L   | 0.055      | -            | -                | -                | -         |    -1.39 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4297 | 2024-02-11 | Apeks             | L   | 0.035      | -            | -                | -                | -         |    -1.09 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4321 | 2024-02-09 | fnatic            | W   | 0.022      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4322 | 2024-02-09 | Endpoint          | W   | 0.022      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4327 | 2024-02-09 | ex-Sprout         | L   | 0.021      | -            | -                | -                | -         |    -0.66 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($164,135.21)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.880 | $10,000.00     | $8,802.78       |
| 2024-06-16 |      0.875 | $10,000.00     | $8,750.00       |
| 2024-06-09 |      0.828 | $7,000.00      | $5,797.85       |
| 2024-06-02 |      0.781 | $2,000.00      | $1,562.78       |
| 2024-05-26 |      0.735 | $2,000.00      | $1,470.00       |
| 2024-05-12 |      0.641 | $23,500.00     | $15,072.64      |
| 2024-05-02 |      0.575 | $1,500.00      | $862.50         |
| 2024-04-14 |      0.454 | $4,000.00      | $1,816.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
