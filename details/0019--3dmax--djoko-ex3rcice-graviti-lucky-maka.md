### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1416.4<br />
<br />
Final Rank Value (1416.4) = Starting Rank Value (1693.2) + Head To Head Adjustments (-276.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.771[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.355[<sup>2</sup>](#table1)
- LAN Wins: 0.825[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1693.2
- 400 + ( ( 0.629 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1693.2


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
|           80 |        3 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |       37 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      157 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.719 (0.468)    | 1 (1.000) |    26.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      171 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.431 (0.281)    | 0.798 (0.519)    | 1 (1.000) |    18.76 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      185 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.173 (0.113)    | -                | 1 (1.000) |    15.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      211 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.49 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      251 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      263 | 2024-07-25 | DMS               | W   | 1.000      | 0.650        | -                | 0.447 (0.291)    | 1 (1.000) |     2.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      291 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.132 (0.086)    | 0.482 (0.313)    | 1 (1.000) |     9.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      567 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.577 (0.289)    | -         |     5.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      676 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      804 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -29.89 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |      887 | 2024-06-17 | 5W                | L   | 0.898      | -            | -                | -                | -         |   -25.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |      899 | 2024-06-16 | B8                | L   | 0.893      | -            | -                | -                | -         |   -23.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |      903 | 2024-06-16 | Permitta          | W   | 0.892      | 0.435        | -                | 0.801 (0.311)    | -         |     1.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |      909 | 2024-06-16 | Enterprise        | W   | 0.891      | -            | -                | -                | -         |     1.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |      922 | 2024-06-15 | GUN5              | W   | 0.887      | -            | -                | -                | -         |     2.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |      941 | 2024-06-15 | BLEED             | W   | 0.884      | -            | -                | -                | -         |    11.01 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |      969 | 2024-06-14 | Sashi             | W   | 0.879      | -            | -                | -                | -         |     6.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |      980 | 2024-06-14 | Passion UA        | W   | 0.877      | 0.435        | 0.173 (0.066)    | 1.000 (0.381)    | -         |     3.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |      998 | 2024-06-13 | 9INE              | W   | 0.873      | -            | -                | -                | -         |     2.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1010 | 2024-06-13 | VP.Prodigy        | W   | 0.871      | -            | -                | -                | -         |     1.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1042 | 2024-06-11 | SINNERS           | W   | 0.860      | -            | -                | -                | -         |     2.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1053 | 2024-06-11 | BUHAWI            | W   | 0.859      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1070 | 2024-06-10 | EYEBALLERS        | W   | 0.853      | -            | -                | -                | -         |     1.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1077 | 2024-06-10 | SAW               | W   | 0.852      | -            | -                | -                | -         |     5.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1084 | 2024-06-10 | PARIVISION        | W   | 0.852      | -            | -                | -                | -         |     3.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1088 | 2024-06-10 | 9 Pandas          | W   | 0.851      | -            | -                | -                | -         |     3.39 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1110 | 2024-06-09 | 9INE              | L   | 0.846      | -            | -                | -                | -         |   -24.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1123 | 2024-06-09 | Monte             | L   | 0.846      | -            | -                | -                | -         |   -24.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1130 | 2024-06-09 | SINNERS           | L   | 0.845      | -            | -                | -                | -         |   -24.70 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1137 | 2024-06-09 | Aurora            | W   | 0.845      | 0.143        | 0.431 (0.052)    | -                | -         |    13.28 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1148 | 2024-06-09 | RUSH B            | W   | 0.844      | -            | -                | -                | -         |     0.89 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1187 | 2024-06-08 | Illuminar         | L   | 0.839      | -            | -                | -                | -         |   -25.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1252 | 2024-06-07 | Gaimin Gladiators | W   | 0.833      | -            | -                | -                | -         |     1.63 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1293 | 2024-06-06 | Nexus             | W   | 0.827      | -            | -                | -                | -         |     0.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1310 | 2024-06-06 | Sangal            | L   | 0.826      | -            | -                | -                | -         |   -23.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1376 | 2024-06-05 | KOI               | L   | 0.820      | -            | -                | -                | -         |   -24.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1422 | 2024-06-04 | Aurora            | W   | 0.813      | 0.500        | 0.431 (0.175)    | 0.798 (0.324)    | -         |    12.74 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1507 | 2024-06-01 | VP.Prodigy        | L   | 0.793      | -            | -                | -                | -         |   -24.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1560 | 2024-05-30 | Sampi             | W   | 0.780      | 0.435        | -                | 1.000 (0.339)    | -         |     0.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1684 | 2024-05-25 | MOUZ NXT          | L   | 0.744      | -            | -                | -                | -         |   -22.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1707 | 2024-05-23 | Zero Tenacity     | W   | 0.732      | 0.435        | -                | 1.000 (0.318)    | -         |     1.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     1947 | 2024-05-17 | B8                | L   | 0.692      | -            | -                | -                | -         |   -20.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2037 | 2024-05-15 | Zero Tenacity     | L   | 0.678      | -            | -                | -                | -         |   -20.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2240 | 2024-05-08 | G2                | L   | 0.632      | -            | -                | -                | -         |    -2.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2385 | 2024-05-01 | Sashi             | L   | 0.585      | -            | -                | -                | -         |   -16.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2410 | 2024-04-30 | BetBoom           | W   | 0.578      | 0.384        | 0.257 (0.057)    | -                | -         |     4.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2418 | 2024-04-29 | PARIVISION        | W   | 0.573      | -            | -                | -                | -         |     0.94 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2465 | 2024-04-27 | Astralis          | L   | 0.559      | -            | -                | -                | -         |    -6.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2539 | 2024-04-24 | fnatic            | W   | 0.539      | 0.889        | 0.292 (0.140)    | -                | 1 (0.539) |     3.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2566 | 2024-04-23 | SAW               | W   | 0.532      | 0.889        | 0.108 (0.051)    | -                | 1 (0.532) |     1.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2576 | 2024-04-22 | ex-Guild Eagles   | W   | 0.526      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2778 | 2024-04-17 | BLEED             | W   | 0.491      | -            | -                | -                | -         |     0.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2837 | 2024-04-14 | BetBoom           | L   | 0.472      | -            | -                | -                | -         |   -11.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2851 | 2024-04-13 | ex-Preasy         | W   | 0.465      | -            | -                | -                | -         |     0.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2894 | 2024-04-11 | Passion UA        | L   | 0.452      | -            | -                | -                | -         |   -13.74 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2928 | 2024-04-10 | SINNERS           | L   | 0.447      | -            | -                | -                | -         |   -13.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     2980 | 2024-04-09 | SAW               | W   | 0.440      | -            | -                | -                | -         |     0.94 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3054 | 2024-04-07 | Young Ninjas      | W   | 0.425      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3127 | 2024-04-04 | Space             | W   | 0.406      | -            | -                | -                | -         |     0.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3156 | 2024-04-03 | GUN5              | W   | 0.400      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3215 | 2024-04-02 | Permitta          | W   | 0.392      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3270 | 2024-03-28 | Apeks             | W   | 0.359      | -            | -                | -                | -         |     0.18 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3401 | 2024-03-21 | fnatic            | L   | 0.312      | -            | -                | -                | -         |    -8.32 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3441 | 2024-03-19 | GUN5              | W   | 0.299      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3511 | 2024-03-15 | B8                | W   | 0.273      | -            | -                | -                | -         |     0.35 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3585 | 2024-03-13 | PARIVISION        | L   | 0.259      | -            | -                | -                | -         |    -7.83 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3803 | 2024-03-05 | FORZE             | L   | 0.206      | -            | -                | -                | -         |    -6.41 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3826 | 2024-03-04 | fnatic            | L   | 0.199      | -            | -                | -                | -         |    -5.39 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3864 | 2024-03-02 | Monte             | W   | 0.187      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3900 | 2024-02-29 | Gaimin Gladiators | W   | 0.174      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4211 | 2024-02-16 | 9 Pandas          | L   | 0.086      | -            | -                | -                | -         |    -2.64 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4235 | 2024-02-15 | Into the Breach   | W   | 0.079      | -            | -                | -                | 1 (0.079) |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4271 | 2024-02-14 | KOI               | L   | 0.073      | -            | -                | -                | -         |    -2.28 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4277 | 2024-02-14 | Falcons           | L   | 0.072      | -            | -                | -                | -         |    -1.83 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4334 | 2024-02-11 | Apeks             | L   | 0.053      | -            | -                | -                | -         |    -1.65 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4359 | 2024-02-09 | fnatic            | W   | 0.040      | -            | -                | -                | -         |     0.18 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4360 | 2024-02-09 | Endpoint          | W   | 0.040      | -            | -                | -                | -         |     0.02 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4365 | 2024-02-09 | ex-Sprout         | L   | 0.039      | -            | -                | -                | -         |    -1.22 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($165,201.88)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.898 | $10,000.00     | $8,980.56       |
| 2024-06-16 |      0.893 | $10,000.00     | $8,927.78       |
| 2024-06-09 |      0.846 | $7,000.00      | $5,922.29       |
| 2024-06-02 |      0.799 | $2,000.00      | $1,598.33       |
| 2024-05-26 |      0.753 | $2,000.00      | $1,505.56       |
| 2024-05-12 |      0.659 | $23,500.00     | $15,490.42      |
| 2024-05-02 |      0.593 | $1,500.00      | $889.17         |
| 2024-04-14 |      0.472 | $4,000.00      | $1,887.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
