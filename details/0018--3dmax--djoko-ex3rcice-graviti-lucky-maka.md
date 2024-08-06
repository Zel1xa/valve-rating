### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1429.5<br />
<br />
Final Rank Value (1429.5) = Starting Rank Value (1686.4) + Head To Head Adjustments (-257.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.773[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.359[<sup>2</sup>](#table1)
- LAN Wins: 0.814[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1686.4
- 400 + ( ( 0.627 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1686.4


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
|           83 |       34 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       60 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |      104 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.48 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      137 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      179 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      299 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.710 (0.462)    | 1 (1.000) |    26.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      313 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.421 (0.274)    | 0.777 (0.506)    | 1 (1.000) |    18.55 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      327 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.174 (0.113)    | -                | 1 (1.000) |    15.39 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      353 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      393 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.82 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      405 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      433 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.464 (0.302)    | 1 (1.000) |     9.28 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      700 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.717 (0.358)    | -         |     5.01 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      803 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      929 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |     1011 | 2024-06-17 | 5W                | L   | 0.869      | -            | -                | -                | -         |   -24.91 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |     1025 | 2024-06-16 | B8                | L   | 0.864      | -            | -                | -                | -         |   -22.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1030 | 2024-06-16 | Permitta          | W   | 0.863      | 0.435        | -                | 0.901 (0.338)    | -         |     1.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1036 | 2024-06-16 | Enterprise        | W   | 0.863      | -            | -                | -                | -         |     1.48 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1051 | 2024-06-15 | GUN5              | W   | 0.858      | -            | -                | -                | -         |     1.90 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1071 | 2024-06-15 | BLEED             | W   | 0.856      | -            | -                | -                | -         |    10.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1105 | 2024-06-14 | Sashi             | W   | 0.850      | -            | -                | -                | -         |     5.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1116 | 2024-06-14 | Passion UA        | W   | 0.849      | 0.435        | 0.173 (0.064)    | 1.000 (0.369)    | -         |     3.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1134 | 2024-06-13 | 9INE              | W   | 0.844      | -            | -                | -                | -         |     1.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1146 | 2024-06-13 | VP.Prodigy        | W   | 0.843      | -            | -                | -                | -         |     1.28 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1177 | 2024-06-11 | SINNERS           | W   | 0.831      | -            | -                | -                | -         |     2.44 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1188 | 2024-06-11 | BUHAWI            | W   | 0.830      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1204 | 2024-06-10 | EYEBALLERS        | W   | 0.824      | -            | -                | -                | -         |     1.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1211 | 2024-06-10 | SAW               | W   | 0.823      | -            | -                | -                | -         |     5.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1218 | 2024-06-10 | PARIVISION        | W   | 0.823      | -            | -                | -                | -         |     3.38 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1222 | 2024-06-10 | 9 Pandas          | W   | 0.823      | -            | -                | -                | -         |     2.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1244 | 2024-06-09 | 9INE              | L   | 0.818      | -            | -                | -                | -         |   -24.38 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1257 | 2024-06-09 | Monte             | L   | 0.817      | -            | -                | -                | -         |   -23.85 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1264 | 2024-06-09 | SINNERS           | L   | 0.817      | -            | -                | -                | -         |   -23.74 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1271 | 2024-06-09 | Aurora            | W   | 0.816      | 0.143        | 0.421 (0.049)    | -                | -         |    12.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1281 | 2024-06-09 | RUSH B            | W   | 0.816      | -            | -                | -                | -         |     0.85 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1319 | 2024-06-08 | Illuminar         | L   | 0.811      | -            | -                | -                | -         |   -24.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1377 | 2024-06-07 | Gaimin Gladiators | W   | 0.804      | -            | -                | -                | -         |     1.37 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1416 | 2024-06-06 | Nexus             | W   | 0.799      | -            | -                | -                | -         |     0.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1433 | 2024-06-06 | Sangal            | L   | 0.798      | -            | -                | -                | -         |   -22.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1496 | 2024-06-05 | KOI               | L   | 0.791      | -            | -                | -                | -         |   -23.38 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1542 | 2024-06-04 | Aurora            | W   | 0.784      | 0.500        | 0.421 (0.165)    | 0.777 (0.305)    | -         |    12.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1626 | 2024-06-01 | VP.Prodigy        | L   | 0.764      | -            | -                | -                | -         |   -23.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1679 | 2024-05-30 | Sampi             | W   | 0.751      | 0.435        | -                | 1.000 (0.327)    | -         |     0.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1801 | 2024-05-25 | MOUZ NXT          | L   | 0.715      | -            | -                | -                | -         |   -21.38 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1824 | 2024-05-23 | Zero Tenacity     | W   | 0.704      | 0.435        | -                | 1.000 (0.306)    | -         |     1.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2038 | 2024-05-17 | B8                | L   | 0.663      | -            | -                | -                | -         |   -19.48 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2124 | 2024-05-15 | Zero Tenacity     | L   | 0.650      | -            | -                | -                | -         |   -19.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2320 | 2024-05-08 | G2                | L   | 0.604      | -            | -                | -                | -         |    -2.55 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2463 | 2024-05-01 | Sashi             | L   | 0.556      | -            | -                | -                | -         |   -16.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2487 | 2024-04-30 | BetBoom           | W   | 0.549      | 0.384        | 0.249 (0.052)    | -                | -         |     3.90 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2495 | 2024-04-29 | PARIVISION        | W   | 0.544      | -            | -                | -                | -         |     0.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2542 | 2024-04-27 | Astralis          | L   | 0.530      | -            | -                | -                | -         |    -5.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2616 | 2024-04-24 | fnatic            | W   | 0.511      | 0.889        | 0.371 (0.168)    | 0.696 (0.316)    | 1 (0.511) |     5.89 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2641 | 2024-04-23 | SAW               | W   | 0.503      | -            | -                | -                | 1 (0.503) |     1.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2650 | 2024-04-22 | ex-Guild Eagles   | W   | 0.497      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2846 | 2024-04-17 | BLEED             | W   | 0.463      | -            | -                | -                | -         |     0.44 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2904 | 2024-04-14 | BetBoom           | L   | 0.443      | -            | -                | -                | -         |   -11.02 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2918 | 2024-04-13 | ex-Preasy         | W   | 0.437      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2960 | 2024-04-11 | Passion UA        | L   | 0.423      | -            | -                | -                | -         |   -12.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2994 | 2024-04-10 | SINNERS           | L   | 0.418      | -            | -                | -                | -         |   -12.39 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3046 | 2024-04-09 | SAW               | W   | 0.411      | -            | -                | -                | -         |     0.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3120 | 2024-04-07 | Young Ninjas      | W   | 0.397      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3192 | 2024-04-04 | Space             | W   | 0.377      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3220 | 2024-04-03 | GUN5              | W   | 0.371      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3273 | 2024-04-02 | Permitta          | W   | 0.363      | -            | -                | -                | -         |     0.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3328 | 2024-03-28 | Apeks             | W   | 0.330      | -            | -                | -                | -         |     0.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3454 | 2024-03-21 | fnatic            | L   | 0.284      | -            | -                | -                | -         |    -5.89 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3494 | 2024-03-19 | GUN5              | W   | 0.270      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3564 | 2024-03-15 | B8                | W   | 0.244      | -            | -                | -                | -         |     0.29 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3634 | 2024-03-13 | PARIVISION        | L   | 0.231      | -            | -                | -                | -         |    -6.96 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3845 | 2024-03-05 | FORZE             | L   | 0.178      | -            | -                | -                | -         |    -5.53 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3868 | 2024-03-04 | fnatic            | L   | 0.170      | -            | -                | -                | -         |    -3.67 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3906 | 2024-03-02 | Monte             | W   | 0.158      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3941 | 2024-02-29 | Gaimin Gladiators | W   | 0.145      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4243 | 2024-02-16 | 9 Pandas          | L   | 0.057      | -            | -                | -                | -         |    -1.76 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4267 | 2024-02-15 | Into the Breach   | W   | 0.051      | -            | -                | -                | 1 (0.051) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4303 | 2024-02-14 | KOI               | L   | 0.045      | -            | -                | -                | -         |    -1.36 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4309 | 2024-02-14 | Falcons           | L   | 0.044      | -            | -                | -                | -         |    -1.13 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4357 | 2024-02-11 | Apeks             | L   | 0.024      | -            | -                | -                | -         |    -0.76 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4381 | 2024-02-09 | fnatic            | W   | 0.011      | -            | -                | -                | -         |     0.12 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4382 | 2024-02-09 | Endpoint          | W   | 0.011      | -            | -                | -                | -         |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4387 | 2024-02-09 | ex-Sprout         | L   | 0.010      | -            | -                | -                | -         |    -0.32 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,485.21)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.869 | $10,000.00     | $8,694.44       |
| 2024-06-16 |      0.864 | $10,000.00     | $8,641.67       |
| 2024-06-09 |      0.817 | $7,000.00      | $5,722.01       |
| 2024-06-02 |      0.771 | $2,000.00      | $1,541.11       |
| 2024-05-26 |      0.724 | $2,000.00      | $1,448.33       |
| 2024-05-12 |      0.631 | $23,500.00     | $14,818.06      |
| 2024-05-02 |      0.564 | $1,500.00      | $846.25         |
| 2024-04-14 |      0.443 | $4,000.00      | $1,773.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
