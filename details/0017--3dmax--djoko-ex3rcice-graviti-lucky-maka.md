### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1433.4<br />
<br />
Final Rank Value (1433.4) = Starting Rank Value (1687.8) + Head To Head Adjustments (-254.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.774[<sup>1</sup>](#table2)
- Bounty Collected: 0.562[<sup>2</sup>](#table1)
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
|           83 |       57 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       83 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |      127 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.48 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      160 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      202 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      322 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.694 (0.451)    | 1 (1.000) |    26.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      336 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.420 (0.273)    | 0.758 (0.493)    | 1 (1.000) |    18.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      350 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.173 (0.112)    | -                | 1 (1.000) |    15.34 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      376 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -6.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      416 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.79 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      428 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      456 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.452 (0.294)    | 1 (1.000) |     9.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      723 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.700 (0.350)    | -         |     5.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      826 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.89 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      952 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |     1034 | 2024-06-17 | 5W                | L   | 0.865      | -            | -                | -                | -         |   -24.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |     1048 | 2024-06-16 | B8                | L   | 0.860      | -            | -                | -                | -         |   -22.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1053 | 2024-06-16 | Permitta          | W   | 0.859      | 0.435        | -                | 0.919 (0.343)    | -         |     1.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1059 | 2024-06-16 | Enterprise        | W   | 0.858      | -            | -                | -                | -         |     1.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1074 | 2024-06-15 | GUN5              | W   | 0.854      | -            | -                | -                | -         |     1.89 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1094 | 2024-06-15 | BLEED             | W   | 0.852      | -            | -                | -                | -         |    10.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1128 | 2024-06-14 | Sashi             | W   | 0.846      | -            | -                | -                | -         |     5.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1139 | 2024-06-14 | Passion UA        | W   | 0.844      | 0.435        | 0.173 (0.064)    | 1.000 (0.367)    | -         |     3.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1157 | 2024-06-13 | 9INE              | W   | 0.840      | -            | -                | -                | -         |     1.49 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1169 | 2024-06-13 | VP.Prodigy        | W   | 0.838      | -            | -                | -                | -         |     1.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1200 | 2024-06-11 | SINNERS           | W   | 0.827      | -            | -                | -                | -         |     2.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1211 | 2024-06-11 | BUHAWI            | W   | 0.826      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1227 | 2024-06-10 | EYEBALLERS        | W   | 0.820      | -            | -                | -                | -         |     1.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1234 | 2024-06-10 | SAW               | W   | 0.819      | -            | -                | -                | -         |     4.96 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1241 | 2024-06-10 | PARIVISION        | W   | 0.819      | -            | -                | -                | -         |     3.69 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1245 | 2024-06-10 | 9 Pandas          | W   | 0.818      | -            | -                | -                | -         |     3.01 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1267 | 2024-06-09 | 9INE              | L   | 0.813      | -            | -                | -                | -         |   -24.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1280 | 2024-06-09 | Monte             | L   | 0.813      | -            | -                | -                | -         |   -23.73 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1287 | 2024-06-09 | SINNERS           | L   | 0.812      | -            | -                | -                | -         |   -23.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1294 | 2024-06-09 | Aurora            | W   | 0.812      | 0.143        | 0.420 (0.049)    | -                | -         |    12.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1304 | 2024-06-09 | RUSH B            | W   | 0.812      | -            | -                | -                | -         |     0.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1342 | 2024-06-08 | Illuminar         | L   | 0.806      | -            | -                | -                | -         |   -24.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1400 | 2024-06-07 | Gaimin Gladiators | W   | 0.800      | -            | -                | -                | -         |     1.33 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1439 | 2024-06-06 | Nexus             | W   | 0.794      | -            | -                | -                | -         |     0.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1456 | 2024-06-06 | Sangal            | L   | 0.793      | -            | -                | -                | -         |   -21.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1519 | 2024-06-05 | KOI               | L   | 0.787      | -            | -                | -                | -         |   -23.28 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1565 | 2024-06-04 | Aurora            | W   | 0.780      | 0.500        | 0.420 (0.164)    | 0.758 (0.296)    | -         |    12.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1649 | 2024-06-01 | VP.Prodigy        | L   | 0.760      | -            | -                | -                | -         |   -23.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1702 | 2024-05-30 | Sampi             | W   | 0.747      | 0.435        | -                | 1.000 (0.325)    | -         |     0.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1824 | 2024-05-25 | MOUZ NXT          | L   | 0.711      | -            | -                | -                | -         |   -21.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1847 | 2024-05-23 | Zero Tenacity     | W   | 0.699      | 0.435        | -                | 1.000 (0.304)    | -         |     1.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2061 | 2024-05-17 | B8                | L   | 0.659      | -            | -                | -                | -         |   -19.35 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2147 | 2024-05-15 | Zero Tenacity     | L   | 0.645      | -            | -                | -                | -         |   -19.39 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2343 | 2024-05-08 | G2                | L   | 0.599      | -            | -                | -                | -         |    -2.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2486 | 2024-05-01 | Sashi             | L   | 0.552      | -            | -                | -                | -         |   -16.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2510 | 2024-04-30 | BetBoom           | W   | 0.545      | 0.384        | 0.248 (0.052)    | -                | -         |     3.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2518 | 2024-04-29 | PARIVISION        | W   | 0.540      | -            | -                | -                | -         |     0.96 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2565 | 2024-04-27 | Astralis          | L   | 0.526      | -            | -                | -                | -         |    -5.89 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2639 | 2024-04-24 | fnatic            | W   | 0.506      | 0.889        | 0.371 (0.167)    | 0.680 (0.306)    | 1 (0.506) |     5.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2664 | 2024-04-23 | SAW               | W   | 0.499      | -            | -                | -                | 1 (0.499) |     1.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2673 | 2024-04-22 | ex-Guild Eagles   | W   | 0.493      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2869 | 2024-04-17 | BLEED             | W   | 0.458      | -            | -                | -                | -         |     0.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2927 | 2024-04-14 | BetBoom           | L   | 0.439      | -            | -                | -                | -         |   -10.97 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2941 | 2024-04-13 | ex-Preasy         | W   | 0.432      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2983 | 2024-04-11 | Passion UA        | L   | 0.419      | -            | -                | -                | -         |   -12.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     3017 | 2024-04-10 | SINNERS           | L   | 0.414      | -            | -                | -                | -         |   -12.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3069 | 2024-04-09 | SAW               | W   | 0.407      | -            | -                | -                | -         |     0.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3143 | 2024-04-07 | Young Ninjas      | W   | 0.392      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3215 | 2024-04-04 | Space             | W   | 0.373      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3243 | 2024-04-03 | GUN5              | W   | 0.367      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3296 | 2024-04-02 | Permitta          | W   | 0.359      | -            | -                | -                | -         |     0.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3351 | 2024-03-28 | Apeks             | W   | 0.326      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3477 | 2024-03-21 | fnatic            | L   | 0.279      | -            | -                | -                | -         |    -5.82 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3517 | 2024-03-19 | GUN5              | W   | 0.266      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3587 | 2024-03-15 | B8                | W   | 0.240      | -            | -                | -                | -         |     0.29 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3657 | 2024-03-13 | PARIVISION        | L   | 0.226      | -            | -                | -                | -         |    -6.77 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3868 | 2024-03-05 | FORZE             | L   | 0.173      | -            | -                | -                | -         |    -5.40 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3891 | 2024-03-04 | fnatic            | L   | 0.166      | -            | -                | -                | -         |    -3.58 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3929 | 2024-03-02 | Monte             | W   | 0.154      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3964 | 2024-02-29 | Gaimin Gladiators | W   | 0.141      | -            | -                | -                | -         |     0.07 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4266 | 2024-02-16 | 9 Pandas          | L   | 0.053      | -            | -                | -                | -         |    -1.62 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4290 | 2024-02-15 | Into the Breach   | W   | 0.047      | -            | -                | -                | 1 (0.047) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4326 | 2024-02-14 | KOI               | L   | 0.040      | -            | -                | -                | -         |    -1.23 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4332 | 2024-02-14 | Falcons           | L   | 0.039      | -            | -                | -                | -         |    -1.02 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4380 | 2024-02-11 | Apeks             | L   | 0.020      | -            | -                | -                | -         |    -0.62 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4404 | 2024-02-09 | fnatic            | W   | 0.007      | -            | -                | -                | -         |     0.07 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4405 | 2024-02-09 | Endpoint          | W   | 0.007      | -            | -                | -                | -         |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4410 | 2024-02-09 | ex-Sprout         | L   | 0.006      | -            | -                | -                | -         |    -0.19 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,226.88)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.865 | $10,000.00     | $8,651.39       |
| 2024-06-16 |      0.860 | $10,000.00     | $8,598.61       |
| 2024-06-09 |      0.813 | $7,000.00      | $5,691.88       |
| 2024-06-02 |      0.766 | $2,000.00      | $1,532.50       |
| 2024-05-26 |      0.720 | $2,000.00      | $1,439.72       |
| 2024-05-12 |      0.626 | $23,500.00     | $14,716.88      |
| 2024-05-02 |      0.560 | $1,500.00      | $839.79         |
| 2024-04-14 |      0.439 | $4,000.00      | $1,756.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
