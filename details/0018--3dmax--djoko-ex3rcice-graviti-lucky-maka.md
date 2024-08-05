### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1428.9<br />
<br />
Final Rank Value (1428.9) = Starting Rank Value (1686.1) + Head To Head Adjustments (-257.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.773[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.359[<sup>2</sup>](#table1)
- LAN Wins: 0.813[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1686.1
- 400 + ( ( 0.627 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1686.1


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
|           83 |       32 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       58 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |      102 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      135 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      177 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      297 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.710 (0.462)    | 1 (1.000) |    26.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      311 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.422 (0.274)    | 0.778 (0.506)    | 1 (1.000) |    18.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      325 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.174 (0.113)    | -                | 1 (1.000) |    15.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      351 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.90 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      391 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.82 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      403 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      431 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.465 (0.303)    | 1 (1.000) |     9.33 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      698 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.717 (0.359)    | -         |     5.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      801 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.82 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      927 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |     1009 | 2024-06-17 | 5W                | L   | 0.871      | -            | -                | -                | -         |   -24.95 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |     1023 | 2024-06-16 | B8                | L   | 0.866      | -            | -                | -                | -         |   -22.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1028 | 2024-06-16 | Permitta          | W   | 0.865      | 0.435        | -                | 0.902 (0.339)    | -         |     1.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1034 | 2024-06-16 | Enterprise        | W   | 0.864      | -            | -                | -                | -         |     1.49 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1049 | 2024-06-15 | GUN5              | W   | 0.860      | -            | -                | -                | -         |     1.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1069 | 2024-06-15 | BLEED             | W   | 0.858      | -            | -                | -                | -         |    10.18 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1103 | 2024-06-14 | Sashi             | W   | 0.852      | -            | -                | -                | -         |     5.73 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1114 | 2024-06-14 | Passion UA        | W   | 0.850      | 0.435        | 0.173 (0.064)    | 1.000 (0.370)    | -         |     3.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1132 | 2024-06-13 | 9INE              | W   | 0.846      | -            | -                | -                | -         |     1.52 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1144 | 2024-06-13 | VP.Prodigy        | W   | 0.844      | -            | -                | -                | -         |     1.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1175 | 2024-06-11 | SINNERS           | W   | 0.833      | -            | -                | -                | -         |     2.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1186 | 2024-06-11 | BUHAWI            | W   | 0.832      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1202 | 2024-06-10 | EYEBALLERS        | W   | 0.826      | -            | -                | -                | -         |     1.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1209 | 2024-06-10 | SAW               | W   | 0.825      | -            | -                | -                | -         |     5.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1216 | 2024-06-10 | PARIVISION        | W   | 0.825      | -            | -                | -                | -         |     3.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1220 | 2024-06-10 | 9 Pandas          | W   | 0.824      | -            | -                | -                | -         |     3.02 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1242 | 2024-06-09 | 9INE              | L   | 0.819      | -            | -                | -                | -         |   -24.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1255 | 2024-06-09 | Monte             | L   | 0.819      | -            | -                | -                | -         |   -23.89 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1262 | 2024-06-09 | SINNERS           | L   | 0.818      | -            | -                | -                | -         |   -23.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1269 | 2024-06-09 | Aurora            | W   | 0.818      | 0.143        | 0.422 (0.049)    | -                | -         |    12.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1279 | 2024-06-09 | RUSH B            | W   | 0.818      | -            | -                | -                | -         |     0.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1317 | 2024-06-08 | Illuminar         | L   | 0.812      | -            | -                | -                | -         |   -24.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1375 | 2024-06-07 | Gaimin Gladiators | W   | 0.806      | -            | -                | -                | -         |     1.38 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1414 | 2024-06-06 | Nexus             | W   | 0.801      | -            | -                | -                | -         |     0.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1431 | 2024-06-06 | Sangal            | L   | 0.800      | -            | -                | -                | -         |   -22.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1494 | 2024-06-05 | KOI               | L   | 0.793      | -            | -                | -                | -         |   -23.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1540 | 2024-06-04 | Aurora            | W   | 0.786      | 0.500        | 0.422 (0.166)    | 0.778 (0.306)    | -         |    12.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1624 | 2024-06-01 | VP.Prodigy        | L   | 0.766      | -            | -                | -                | -         |   -23.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1677 | 2024-05-30 | Sampi             | W   | 0.753      | 0.435        | -                | 1.000 (0.327)    | -         |     0.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1799 | 2024-05-25 | MOUZ NXT          | L   | 0.717      | -            | -                | -                | -         |   -21.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1822 | 2024-05-23 | Zero Tenacity     | W   | 0.705      | 0.435        | -                | 1.000 (0.307)    | -         |     1.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2036 | 2024-05-17 | B8                | L   | 0.665      | -            | -                | -                | -         |   -19.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2122 | 2024-05-15 | Zero Tenacity     | L   | 0.652      | -            | -                | -                | -         |   -19.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2318 | 2024-05-08 | G2                | L   | 0.605      | -            | -                | -                | -         |    -2.55 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2461 | 2024-05-01 | Sashi             | L   | 0.558      | -            | -                | -                | -         |   -16.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2485 | 2024-04-30 | BetBoom           | W   | 0.551      | 0.384        | 0.249 (0.053)    | -                | -         |     3.94 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2493 | 2024-04-29 | PARIVISION        | W   | 0.546      | -            | -                | -                | -         |     0.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2540 | 2024-04-27 | Astralis          | L   | 0.532      | -            | -                | -                | -         |    -5.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2614 | 2024-04-24 | fnatic            | W   | 0.512      | 0.889        | 0.371 (0.169)    | 0.697 (0.317)    | 1 (0.512) |     5.93 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2639 | 2024-04-23 | SAW               | W   | 0.505      | -            | -                | -                | 1 (0.505) |     1.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2648 | 2024-04-22 | ex-Guild Eagles   | W   | 0.499      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2844 | 2024-04-17 | BLEED             | W   | 0.464      | -            | -                | -                | -         |     0.44 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2902 | 2024-04-14 | BetBoom           | L   | 0.445      | -            | -                | -                | -         |   -11.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2916 | 2024-04-13 | ex-Preasy         | W   | 0.438      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2958 | 2024-04-11 | Passion UA        | L   | 0.425      | -            | -                | -                | -         |   -12.93 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2992 | 2024-04-10 | SINNERS           | L   | 0.420      | -            | -                | -                | -         |   -12.44 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3044 | 2024-04-09 | SAW               | W   | 0.413      | -            | -                | -                | -         |     0.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3118 | 2024-04-07 | Young Ninjas      | W   | 0.398      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3190 | 2024-04-04 | Space             | W   | 0.379      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3218 | 2024-04-03 | GUN5              | W   | 0.373      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3271 | 2024-04-02 | Permitta          | W   | 0.365      | -            | -                | -                | -         |     0.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3326 | 2024-03-28 | Apeks             | W   | 0.332      | -            | -                | -                | -         |     0.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3452 | 2024-03-21 | fnatic            | L   | 0.286      | -            | -                | -                | -         |    -5.92 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3492 | 2024-03-19 | GUN5              | W   | 0.272      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3562 | 2024-03-15 | B8                | W   | 0.246      | -            | -                | -                | -         |     0.30 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3632 | 2024-03-13 | PARIVISION        | L   | 0.232      | -            | -                | -                | -         |    -7.02 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3843 | 2024-03-05 | FORZE             | L   | 0.180      | -            | -                | -                | -         |    -5.58 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3866 | 2024-03-04 | fnatic            | L   | 0.172      | -            | -                | -                | -         |    -3.70 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3904 | 2024-03-02 | Monte             | W   | 0.160      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3939 | 2024-02-29 | Gaimin Gladiators | W   | 0.147      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4241 | 2024-02-16 | 9 Pandas          | L   | 0.059      | -            | -                | -                | -         |    -1.81 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4265 | 2024-02-15 | Into the Breach   | W   | 0.053      | -            | -                | -                | 1 (0.053) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4301 | 2024-02-14 | KOI               | L   | 0.047      | -            | -                | -                | -         |    -1.42 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4307 | 2024-02-14 | Falcons           | L   | 0.046      | -            | -                | -                | -         |    -1.17 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4355 | 2024-02-11 | Apeks             | L   | 0.026      | -            | -                | -                | -         |    -0.81 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4379 | 2024-02-09 | fnatic            | W   | 0.013      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4380 | 2024-02-09 | Endpoint          | W   | 0.013      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4385 | 2024-02-09 | ex-Sprout         | L   | 0.012      | -            | -                | -                | -         |    -0.38 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,593.54)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.871 | $10,000.00     | $8,712.50       |
| 2024-06-16 |      0.866 | $10,000.00     | $8,659.72       |
| 2024-06-09 |      0.819 | $7,000.00      | $5,734.65       |
| 2024-06-02 |      0.772 | $2,000.00      | $1,544.72       |
| 2024-05-26 |      0.726 | $2,000.00      | $1,451.94       |
| 2024-05-12 |      0.632 | $23,500.00     | $14,860.49      |
| 2024-05-02 |      0.566 | $1,500.00      | $848.96         |
| 2024-04-14 |      0.445 | $4,000.00      | $1,780.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
