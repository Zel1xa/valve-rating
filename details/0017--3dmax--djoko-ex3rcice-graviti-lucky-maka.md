### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1446.7<br />
<br />
Final Rank Value (1446.7) = Starting Rank Value (1682.8) + Head To Head Adjustments (-236.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.772[<sup>1</sup>](#table2)
- Bounty Collected: 0.564[<sup>2</sup>](#table1)
- Opponent Network: 0.363[<sup>2</sup>](#table1)
- LAN Wins: 0.812[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1682.8
- 400 + ( ( 0.627 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1682.8


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
|           82 |       10 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |       54 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.52 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |       87 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      127 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      247 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    26.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      261 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.423 (0.275)    | 0.793 (0.516)    | 1 (1.000) |    18.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      275 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.169 (0.110)    | -                | 1 (1.000) |    15.37 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      301 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.73 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      341 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      353 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      381 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.085)    | 0.475 (0.309)    | 1 (1.000) |     9.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      645 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.690 (0.345)    | -         |     5.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      749 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.95 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      877 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.01 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |      959 | 2024-06-17 | 5W                | L   | 0.880      | -            | -                | -                | -         |   -25.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |      973 | 2024-06-16 | B8                | L   | 0.874      | -            | -                | -                | -         |   -22.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |      978 | 2024-06-16 | Permitta          | W   | 0.874      | 0.435        | -                | 0.876 (0.333)    | -         |     1.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |      984 | 2024-06-16 | Enterprise        | W   | 0.873      | -            | -                | -                | -         |     1.52 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |      999 | 2024-06-15 | GUN5              | W   | 0.868      | -            | -                | -                | -         |     1.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1019 | 2024-06-15 | BLEED             | W   | 0.866      | -            | -                | -                | -         |    10.34 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1053 | 2024-06-14 | Sashi             | W   | 0.860      | -            | -                | -                | -         |     5.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1064 | 2024-06-14 | Passion UA        | W   | 0.859      | 0.435        | 0.172 (0.064)    | 1.000 (0.373)    | -         |     3.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1082 | 2024-06-13 | 9INE              | W   | 0.854      | -            | -                | -                | -         |     1.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1094 | 2024-06-13 | VP.Prodigy        | W   | 0.853      | -            | -                | -                | -         |     1.34 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1125 | 2024-06-11 | SINNERS           | W   | 0.842      | -            | -                | -                | -         |     2.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1136 | 2024-06-11 | BUHAWI            | W   | 0.841      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1152 | 2024-06-10 | EYEBALLERS        | W   | 0.834      | -            | -                | -                | -         |     1.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1159 | 2024-06-10 | SAW               | W   | 0.833      | -            | -                | -                | -         |     5.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1166 | 2024-06-10 | PARIVISION        | W   | 0.833      | -            | -                | -                | -         |     3.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1170 | 2024-06-10 | 9 Pandas          | W   | 0.833      | -            | -                | -                | -         |     3.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1192 | 2024-06-09 | 9INE              | L   | 0.828      | -            | -                | -                | -         |   -24.63 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1205 | 2024-06-09 | Monte             | L   | 0.827      | -            | -                | -                | -         |   -24.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1212 | 2024-06-09 | SINNERS           | L   | 0.827      | -            | -                | -                | -         |   -24.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1219 | 2024-06-09 | Aurora            | W   | 0.826      | 0.143        | 0.423 (0.050)    | -                | -         |    12.72 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1229 | 2024-06-09 | RUSH B            | W   | 0.826      | -            | -                | -                | -         |     0.89 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1267 | 2024-06-08 | Illuminar         | L   | 0.821      | -            | -                | -                | -         |   -25.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1325 | 2024-06-07 | Gaimin Gladiators | W   | 0.814      | -            | -                | -                | -         |     1.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1364 | 2024-06-06 | Nexus             | W   | 0.809      | -            | -                | -                | -         |     0.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1381 | 2024-06-06 | Sangal            | L   | 0.808      | -            | -                | -                | -         |   -22.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1444 | 2024-06-05 | KOI               | L   | 0.801      | -            | -                | -                | -         |   -23.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1490 | 2024-06-04 | Aurora            | W   | 0.795      | 0.500        | 0.423 (0.168)    | 0.793 (0.315)    | -         |    12.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1574 | 2024-06-01 | VP.Prodigy        | L   | 0.774      | -            | -                | -                | -         |   -23.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1627 | 2024-05-30 | Sampi             | W   | 0.762      | 0.435        | -                | 1.000 (0.331)    | -         |     0.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1749 | 2024-05-25 | MOUZ NXT          | L   | 0.725      | -            | -                | -                | -         |   -21.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1772 | 2024-05-23 | Zero Tenacity     | W   | 0.714      | 0.435        | -                | 1.000 (0.310)    | -         |     1.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     1986 | 2024-05-17 | B8                | L   | 0.673      | -            | -                | -                | -         |   -19.74 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2072 | 2024-05-15 | Zero Tenacity     | L   | 0.660      | -            | -                | -                | -         |   -19.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2268 | 2024-05-08 | G2                | L   | 0.614      | -            | -                | -                | -         |    -2.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2411 | 2024-05-01 | Sashi             | L   | 0.566      | -            | -                | -                | -         |   -16.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2435 | 2024-04-30 | BetBoom           | W   | 0.560      | 0.384        | 0.251 (0.054)    | -                | -         |     4.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2443 | 2024-04-29 | PARIVISION        | W   | 0.555      | -            | -                | -                | -         |     0.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2490 | 2024-04-27 | Astralis          | L   | 0.541      | -            | -                | -                | -         |    -5.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2564 | 2024-04-24 | fnatic            | W   | 0.521      | 0.889        | 0.371 (0.172)    | 0.708 (0.328)    | 1 (0.521) |     6.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2589 | 2024-04-23 | SAW               | W   | 0.513      | -            | -                | -                | 1 (0.513) |     1.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2598 | 2024-04-22 | ex-Guild Eagles   | W   | 0.508      | -            | -                | -                | -         |     0.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2794 | 2024-04-17 | BLEED             | W   | 0.473      | -            | -                | -                | -         |     0.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2852 | 2024-04-14 | BetBoom           | L   | 0.453      | -            | -                | -                | -         |   -11.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2866 | 2024-04-13 | ex-Preasy         | W   | 0.447      | -            | -                | -                | -         |     0.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2908 | 2024-04-11 | Passion UA        | L   | 0.433      | -            | -                | -                | -         |   -13.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2942 | 2024-04-10 | SINNERS           | L   | 0.428      | -            | -                | -                | -         |   -12.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     2994 | 2024-04-09 | SAW               | W   | 0.422      | -            | -                | -                | -         |     0.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3068 | 2024-04-07 | Young Ninjas      | W   | 0.407      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3140 | 2024-04-04 | Space             | W   | 0.387      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3168 | 2024-04-03 | GUN5              | W   | 0.382      | -            | -                | -                | -         |     0.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3221 | 2024-04-02 | Permitta          | W   | 0.373      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3276 | 2024-03-28 | Apeks             | W   | 0.340      | -            | -                | -                | -         |     0.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3402 | 2024-03-21 | fnatic            | L   | 0.294      | -            | -                | -                | -         |    -6.03 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3442 | 2024-03-19 | GUN5              | W   | 0.280      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3512 | 2024-03-15 | B8                | W   | 0.254      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3582 | 2024-03-13 | PARIVISION        | L   | 0.241      | -            | -                | -                | -         |    -7.27 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3793 | 2024-03-05 | FORZE             | L   | 0.188      | -            | -                | -                | -         |    -5.84 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3816 | 2024-03-04 | fnatic            | L   | 0.180      | -            | -                | -                | -         |    -3.85 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3854 | 2024-03-02 | Monte             | W   | 0.168      | -            | -                | -                | -         |     0.12 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3889 | 2024-02-29 | Gaimin Gladiators | W   | 0.155      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4191 | 2024-02-16 | 9 Pandas          | L   | 0.067      | -            | -                | -                | -         |    -2.07 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4215 | 2024-02-15 | Into the Breach   | W   | 0.061      | -            | -                | -                | 1 (0.061) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4251 | 2024-02-14 | KOI               | L   | 0.055      | -            | -                | -                | -         |    -1.67 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4257 | 2024-02-14 | Falcons           | L   | 0.054      | -            | -                | -                | -         |    -1.37 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4305 | 2024-02-11 | Apeks             | L   | 0.034      | -            | -                | -                | -         |    -1.07 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4329 | 2024-02-09 | fnatic            | W   | 0.021      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4330 | 2024-02-09 | Endpoint          | W   | 0.021      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4335 | 2024-02-09 | ex-Sprout         | L   | 0.020      | -            | -                | -                | -         |    -0.64 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($164,092.15)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.880 | $10,000.00     | $8,795.60       |
| 2024-06-16 |      0.874 | $10,000.00     | $8,742.82       |
| 2024-06-09 |      0.828 | $7,000.00      | $5,792.82       |
| 2024-06-02 |      0.781 | $2,000.00      | $1,561.34       |
| 2024-05-26 |      0.734 | $2,000.00      | $1,468.56       |
| 2024-05-12 |      0.641 | $23,500.00     | $15,055.78      |
| 2024-05-02 |      0.574 | $1,500.00      | $861.42         |
| 2024-04-14 |      0.453 | $4,000.00      | $1,813.80       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
