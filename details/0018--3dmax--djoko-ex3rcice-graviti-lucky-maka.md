### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1428.3<br />
<br />
Final Rank Value (1428.3) = Starting Rank Value (1685.3) + Head To Head Adjustments (-257.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.773[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.358[<sup>2</sup>](#table1)
- LAN Wins: 0.813[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1685.3
- 400 + ( ( 0.627 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1685.3


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
|           83 |       31 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       57 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |      101 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.52 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      134 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      176 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      296 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.710 (0.462)    | 1 (1.000) |    26.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      310 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.422 (0.274)    | 0.779 (0.506)    | 1 (1.000) |    18.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      324 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.174 (0.113)    | -                | 1 (1.000) |    15.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      350 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      390 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      402 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      430 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.465 (0.303)    | 1 (1.000) |     9.33 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      697 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.718 (0.359)    | -         |     5.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      800 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      926 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |     1008 | 2024-06-17 | 5W                | L   | 0.872      | -            | -                | -                | -         |   -24.95 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |     1022 | 2024-06-16 | B8                | L   | 0.866      | -            | -                | -                | -         |   -22.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1027 | 2024-06-16 | Permitta          | W   | 0.866      | 0.435        | -                | 0.863 (0.324)    | -         |     1.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1033 | 2024-06-16 | Enterprise        | W   | 0.865      | -            | -                | -                | -         |     1.49 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1048 | 2024-06-15 | GUN5              | W   | 0.860      | -            | -                | -                | -         |     1.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1068 | 2024-06-15 | BLEED             | W   | 0.858      | -            | -                | -                | -         |    10.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1102 | 2024-06-14 | Sashi             | W   | 0.852      | -            | -                | -                | -         |     5.74 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1113 | 2024-06-14 | Passion UA        | W   | 0.851      | 0.435        | 0.173 (0.064)    | 1.000 (0.370)    | -         |     3.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1131 | 2024-06-13 | 9INE              | W   | 0.846      | -            | -                | -                | -         |     1.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1143 | 2024-06-13 | VP.Prodigy        | W   | 0.845      | -            | -                | -                | -         |     1.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1174 | 2024-06-11 | SINNERS           | W   | 0.834      | -            | -                | -                | -         |     2.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1185 | 2024-06-11 | BUHAWI            | W   | 0.833      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1201 | 2024-06-10 | EYEBALLERS        | W   | 0.826      | -            | -                | -                | -         |     1.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1208 | 2024-06-10 | SAW               | W   | 0.826      | -            | -                | -                | -         |     5.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1215 | 2024-06-10 | PARIVISION        | W   | 0.825      | -            | -                | -                | -         |     3.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1219 | 2024-06-10 | 9 Pandas          | W   | 0.825      | -            | -                | -                | -         |     3.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1241 | 2024-06-09 | 9INE              | L   | 0.820      | -            | -                | -                | -         |   -24.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1254 | 2024-06-09 | Monte             | L   | 0.819      | -            | -                | -                | -         |   -23.90 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1261 | 2024-06-09 | SINNERS           | L   | 0.819      | -            | -                | -                | -         |   -23.79 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1268 | 2024-06-09 | Aurora            | W   | 0.818      | 0.143        | 0.422 (0.049)    | -                | -         |    12.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1278 | 2024-06-09 | RUSH B            | W   | 0.818      | -            | -                | -                | -         |     0.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1316 | 2024-06-08 | Illuminar         | L   | 0.813      | -            | -                | -                | -         |   -24.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1374 | 2024-06-07 | Gaimin Gladiators | W   | 0.806      | -            | -                | -                | -         |     1.39 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1413 | 2024-06-06 | Nexus             | W   | 0.801      | -            | -                | -                | -         |     0.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1430 | 2024-06-06 | Sangal            | L   | 0.800      | -            | -                | -                | -         |   -22.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1493 | 2024-06-05 | KOI               | L   | 0.793      | -            | -                | -                | -         |   -23.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1539 | 2024-06-04 | Aurora            | W   | 0.787      | 0.500        | 0.422 (0.166)    | 0.779 (0.306)    | -         |    12.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1623 | 2024-06-01 | VP.Prodigy        | L   | 0.766      | -            | -                | -                | -         |   -23.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1676 | 2024-05-30 | Sampi             | W   | 0.754      | 0.435        | -                | 1.000 (0.328)    | -         |     0.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1798 | 2024-05-25 | MOUZ NXT          | L   | 0.718      | -            | -                | -                | -         |   -21.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1821 | 2024-05-23 | Zero Tenacity     | W   | 0.706      | 0.435        | -                | 1.000 (0.307)    | -         |     1.52 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2035 | 2024-05-17 | B8                | L   | 0.665      | -            | -                | -                | -         |   -19.54 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2121 | 2024-05-15 | Zero Tenacity     | L   | 0.652      | -            | -                | -                | -         |   -19.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2317 | 2024-05-08 | G2                | L   | 0.606      | -            | -                | -                | -         |    -2.54 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2460 | 2024-05-01 | Sashi             | L   | 0.558      | -            | -                | -                | -         |   -16.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2484 | 2024-04-30 | BetBoom           | W   | 0.552      | 0.384        | 0.249 (0.053)    | -                | -         |     3.96 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2492 | 2024-04-29 | PARIVISION        | W   | 0.547      | -            | -                | -                | -         |     0.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2539 | 2024-04-27 | Astralis          | L   | 0.533      | -            | -                | -                | -         |    -5.82 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2613 | 2024-04-24 | fnatic            | W   | 0.513      | 0.889        | 0.371 (0.169)    | 0.697 (0.318)    | 1 (0.513) |     5.95 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2638 | 2024-04-23 | SAW               | W   | 0.505      | -            | -                | -                | 1 (0.505) |     1.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2647 | 2024-04-22 | ex-Guild Eagles   | W   | 0.500      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2843 | 2024-04-17 | BLEED             | W   | 0.465      | -            | -                | -                | -         |     0.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2901 | 2024-04-14 | BetBoom           | L   | 0.446      | -            | -                | -                | -         |   -11.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2915 | 2024-04-13 | ex-Preasy         | W   | 0.439      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2957 | 2024-04-11 | Passion UA        | L   | 0.426      | -            | -                | -                | -         |   -12.95 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2991 | 2024-04-10 | SINNERS           | L   | 0.420      | -            | -                | -                | -         |   -12.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3043 | 2024-04-09 | SAW               | W   | 0.414      | -            | -                | -                | -         |     0.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3117 | 2024-04-07 | Young Ninjas      | W   | 0.399      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3189 | 2024-04-04 | Space             | W   | 0.379      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3217 | 2024-04-03 | GUN5              | W   | 0.374      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3270 | 2024-04-02 | Permitta          | W   | 0.366      | -            | -                | -                | -         |     0.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3325 | 2024-03-28 | Apeks             | W   | 0.333      | -            | -                | -                | -         |     0.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3451 | 2024-03-21 | fnatic            | L   | 0.286      | -            | -                | -                | -         |    -5.91 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3491 | 2024-03-19 | GUN5              | W   | 0.272      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3561 | 2024-03-15 | B8                | W   | 0.246      | -            | -                | -                | -         |     0.30 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3631 | 2024-03-13 | PARIVISION        | L   | 0.233      | -            | -                | -                | -         |    -7.03 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3842 | 2024-03-05 | FORZE             | L   | 0.180      | -            | -                | -                | -         |    -5.60 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3865 | 2024-03-04 | fnatic            | L   | 0.172      | -            | -                | -                | -         |    -3.70 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3903 | 2024-03-02 | Monte             | W   | 0.161      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3938 | 2024-02-29 | Gaimin Gladiators | W   | 0.147      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4240 | 2024-02-16 | 9 Pandas          | L   | 0.059      | -            | -                | -                | -         |    -1.82 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4264 | 2024-02-15 | Into the Breach   | W   | 0.053      | -            | -                | -                | 1 (0.053) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4300 | 2024-02-14 | KOI               | L   | 0.047      | -            | -                | -                | -         |    -1.43 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4306 | 2024-02-14 | Falcons           | L   | 0.046      | -            | -                | -                | -         |    -1.18 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4354 | 2024-02-11 | Apeks             | L   | 0.027      | -            | -                | -                | -         |    -0.83 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4378 | 2024-02-09 | fnatic            | W   | 0.013      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4379 | 2024-02-09 | Endpoint          | W   | 0.013      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4384 | 2024-02-09 | ex-Sprout         | L   | 0.012      | -            | -                | -                | -         |    -0.39 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,618.54)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.872 | $10,000.00     | $8,716.67       |
| 2024-06-16 |      0.866 | $10,000.00     | $8,663.89       |
| 2024-06-09 |      0.820 | $7,000.00      | $5,737.57       |
| 2024-06-02 |      0.773 | $2,000.00      | $1,545.56       |
| 2024-05-26 |      0.726 | $2,000.00      | $1,452.78       |
| 2024-05-12 |      0.633 | $23,500.00     | $14,870.28      |
| 2024-05-02 |      0.566 | $1,500.00      | $849.58         |
| 2024-04-14 |      0.446 | $4,000.00      | $1,782.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
