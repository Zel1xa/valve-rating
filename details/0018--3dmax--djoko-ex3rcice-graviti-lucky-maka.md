### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1426.3<br />
<br />
Final Rank Value (1426.3) = Starting Rank Value (1683.5) + Head To Head Adjustments (-257.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.771[<sup>1</sup>](#table2)
- Bounty Collected: 0.561[<sup>2</sup>](#table1)
- Opponent Network: 0.367[<sup>2</sup>](#table1)
- LAN Wins: 0.810[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1683.5
- 400 + ( ( 0.627 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1683.5


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
|           81 |       36 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |       57 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |       94 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.70 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      213 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.745 (0.485)    | 1 (1.000) |    26.71 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      227 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.425 (0.276)    | 0.809 (0.526)    | 1 (1.000) |    18.76 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      241 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.170 (0.110)    | -                | 1 (1.000) |    15.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      267 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.73 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      307 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      319 | 2024-07-25 | DMS               | W   | 1.000      | 0.650        | -                | 0.462 (0.300)    | 1 (1.000) |     2.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      347 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.085)    | 0.494 (0.321)    | 1 (1.000) |     9.76 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      613 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.715 (0.357)    | -         |     5.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      714 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      835 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -29.94 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |      913 | 2024-06-17 | 5W                | L   | 0.885      | -            | -                | -                | -         |   -25.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |      925 | 2024-06-16 | B8                | L   | 0.880      | -            | -                | -                | -         |   -22.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |      929 | 2024-06-16 | Permitta          | W   | 0.879      | 0.435        | -                | 0.887 (0.339)    | -         |     1.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |      935 | 2024-06-16 | Enterprise        | W   | 0.878      | -            | -                | -                | -         |     1.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |      946 | 2024-06-15 | GUN5              | W   | 0.874      | -            | -                | -                | -         |     2.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |      964 | 2024-06-15 | BLEED             | W   | 0.871      | -            | -                | -                | -         |    10.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |      991 | 2024-06-14 | Sashi             | W   | 0.866      | -            | -                | -                | -         |     6.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1002 | 2024-06-14 | Passion UA        | W   | 0.864      | 0.435        | 0.172 (0.065)    | 1.000 (0.376)    | -         |     3.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1020 | 2024-06-13 | 9INE              | W   | 0.860      | -            | -                | -                | -         |     1.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1032 | 2024-06-13 | VP.Prodigy        | W   | 0.858      | -            | -                | -                | -         |     1.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1061 | 2024-06-11 | SINNERS           | W   | 0.847      | -            | -                | -                | -         |     2.38 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1070 | 2024-06-11 | BUHAWI            | W   | 0.846      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1086 | 2024-06-10 | EYEBALLERS        | W   | 0.840      | -            | -                | -                | -         |     1.39 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1093 | 2024-06-10 | SAW               | W   | 0.839      | -            | -                | -                | -         |     5.44 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1100 | 2024-06-10 | PARIVISION        | W   | 0.839      | -            | -                | -                | -         |     3.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1104 | 2024-06-10 | 9 Pandas          | W   | 0.838      | -            | -                | -                | -         |     3.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1125 | 2024-06-09 | 9INE              | L   | 0.833      | -            | -                | -                | -         |   -24.71 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1138 | 2024-06-09 | Monte             | L   | 0.833      | -            | -                | -                | -         |   -24.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1145 | 2024-06-09 | SINNERS           | L   | 0.832      | -            | -                | -                | -         |   -24.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1152 | 2024-06-09 | Aurora            | W   | 0.832      | 0.143        | 0.425 (0.050)    | -                | -         |    13.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1162 | 2024-06-09 | RUSH B            | W   | 0.831      | -            | -                | -                | -         |     0.90 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1197 | 2024-06-08 | Illuminar         | L   | 0.826      | -            | -                | -                | -         |   -25.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1253 | 2024-06-07 | Gaimin Gladiators | W   | 0.819      | -            | -                | -                | -         |     1.54 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1292 | 2024-06-06 | Nexus             | W   | 0.814      | -            | -                | -                | -         |     0.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1309 | 2024-06-06 | Sangal            | L   | 0.813      | -            | -                | -                | -         |   -22.69 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1372 | 2024-06-05 | KOI               | L   | 0.807      | -            | -                | -                | -         |   -24.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1417 | 2024-06-04 | Aurora            | W   | 0.800      | 0.500        | 0.425 (0.170)    | 0.809 (0.324)    | -         |    12.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1499 | 2024-06-01 | VP.Prodigy        | L   | 0.780      | -            | -                | -                | -         |   -23.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1552 | 2024-05-30 | Sampi             | W   | 0.767      | 0.435        | -                | 1.000 (0.333)    | -         |     0.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1673 | 2024-05-25 | MOUZ NXT          | L   | 0.731      | -            | -                | -                | -         |   -21.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1696 | 2024-05-23 | Zero Tenacity     | W   | 0.719      | 0.435        | -                | 1.000 (0.313)    | -         |     1.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     1909 | 2024-05-17 | B8                | L   | 0.679      | -            | -                | -                | -         |   -19.85 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     1995 | 2024-05-15 | Zero Tenacity     | L   | 0.665      | -            | -                | -                | -         |   -19.95 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2190 | 2024-05-08 | G2                | L   | 0.619      | -            | -                | -                | -         |    -2.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2333 | 2024-05-01 | Sashi             | L   | 0.572      | -            | -                | -                | -         |   -16.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2357 | 2024-04-30 | BetBoom           | W   | 0.565      | 0.384        | 0.252 (0.055)    | -                | -         |     4.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2365 | 2024-04-29 | PARIVISION        | W   | 0.560      | -            | -                | -                | -         |     0.90 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2412 | 2024-04-27 | Astralis          | L   | 0.546      | -            | -                | -                | -         |    -6.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2485 | 2024-04-24 | fnatic            | W   | 0.526      | 0.889        | 0.290 (0.135)    | -                | 1 (0.526) |     2.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2510 | 2024-04-23 | SAW               | W   | 0.519      | 0.889        | 0.106 (0.049)    | -                | 1 (0.519) |     1.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2519 | 2024-04-22 | ex-Guild Eagles   | W   | 0.513      | -            | -                | -                | -         |     0.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2715 | 2024-04-17 | BLEED             | W   | 0.478      | -            | -                | -                | -         |     0.48 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2773 | 2024-04-14 | BetBoom           | L   | 0.459      | -            | -                | -                | -         |   -11.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2787 | 2024-04-13 | ex-Preasy         | W   | 0.452      | -            | -                | -                | -         |     0.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2829 | 2024-04-11 | Passion UA        | L   | 0.439      | -            | -                | -                | -         |   -13.35 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2863 | 2024-04-10 | SINNERS           | L   | 0.434      | -            | -                | -                | -         |   -13.02 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     2915 | 2024-04-09 | SAW               | W   | 0.427      | -            | -                | -                | -         |     0.90 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     2989 | 2024-04-07 | Young Ninjas      | W   | 0.412      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3061 | 2024-04-04 | Space             | W   | 0.393      | -            | -                | -                | -         |     0.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3089 | 2024-04-03 | GUN5              | W   | 0.387      | -            | -                | -                | -         |     0.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3142 | 2024-04-02 | Permitta          | W   | 0.379      | -            | -                | -                | -         |     0.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3197 | 2024-03-28 | Apeks             | W   | 0.346      | -            | -                | -                | -         |     0.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3318 | 2024-03-21 | fnatic            | L   | 0.299      | -            | -                | -                | -         |    -7.97 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3358 | 2024-03-19 | GUN5              | W   | 0.286      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3427 | 2024-03-15 | B8                | W   | 0.260      | -            | -                | -                | -         |     0.33 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3496 | 2024-03-13 | PARIVISION        | L   | 0.246      | -            | -                | -                | -         |    -7.43 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3706 | 2024-03-05 | FORZE             | L   | 0.193      | -            | -                | -                | -         |    -6.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3729 | 2024-03-04 | fnatic            | L   | 0.186      | -            | -                | -                | -         |    -5.04 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3767 | 2024-03-02 | Monte             | W   | 0.174      | -            | -                | -                | -         |     0.12 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3802 | 2024-02-29 | Gaimin Gladiators | W   | 0.161      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4103 | 2024-02-16 | 9 Pandas          | L   | 0.073      | -            | -                | -                | -         |    -2.24 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4127 | 2024-02-15 | Into the Breach   | W   | 0.066      | -            | -                | -                | 1 (0.066) |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4163 | 2024-02-14 | KOI               | L   | 0.060      | -            | -                | -                | -         |    -1.87 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4169 | 2024-02-14 | Falcons           | L   | 0.059      | -            | -                | -                | -         |    -1.50 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4217 | 2024-02-11 | Apeks             | L   | 0.040      | -            | -                | -                | -         |    -1.24 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4241 | 2024-02-09 | fnatic            | W   | 0.027      | -            | -                | -                | -         |     0.12 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4242 | 2024-02-09 | Endpoint          | W   | 0.027      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4247 | 2024-02-09 | ex-Sprout         | L   | 0.026      | -            | -                | -                | -         |    -0.81 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($164,421.32)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.885 | $10,000.00     | $8,850.46       |
| 2024-06-16 |      0.880 | $10,000.00     | $8,797.69       |
| 2024-06-09 |      0.833 | $7,000.00      | $5,831.23       |
| 2024-06-02 |      0.786 | $2,000.00      | $1,572.31       |
| 2024-05-26 |      0.740 | $2,000.00      | $1,479.54       |
| 2024-05-12 |      0.646 | $23,500.00     | $15,184.70      |
| 2024-05-02 |      0.580 | $1,500.00      | $869.65         |
| 2024-04-14 |      0.459 | $4,000.00      | $1,835.74       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
