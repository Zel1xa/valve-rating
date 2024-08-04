### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1424.6<br />
<br />
Final Rank Value (1424.6) = Starting Rank Value (1683.0) + Head To Head Adjustments (-258.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.772[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.362[<sup>2</sup>](#table1)
- LAN Wins: 0.812[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1683.0
- 400 + ( ( 0.627 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1683.0


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
|           83 |        7 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       32 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |       76 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      109 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      151 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      271 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.721 (0.469)    | 1 (1.000) |    26.63 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      285 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.423 (0.275)    | 0.793 (0.515)    | 1 (1.000) |    18.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      299 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.169 (0.110)    | -                | 1 (1.000) |    15.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      325 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.76 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      365 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      377 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      405 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.475 (0.309)    | 1 (1.000) |     9.55 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      672 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.690 (0.345)    | -         |     5.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      775 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.95 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      901 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.02 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |      983 | 2024-06-17 | 5W                | L   | 0.878      | -            | -                | -                | -         |   -25.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |      997 | 2024-06-16 | B8                | L   | 0.873      | -            | -                | -                | -         |   -22.76 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1002 | 2024-06-16 | Permitta          | W   | 0.872      | 0.435        | -                | 0.876 (0.332)    | -         |     1.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1008 | 2024-06-16 | Enterprise        | W   | 0.872      | -            | -                | -                | -         |     1.52 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1023 | 2024-06-15 | GUN5              | W   | 0.867      | -            | -                | -                | -         |     1.99 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1043 | 2024-06-15 | BLEED             | W   | 0.865      | -            | -                | -                | -         |    10.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1077 | 2024-06-14 | Sashi             | W   | 0.859      | -            | -                | -                | -         |     5.91 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1088 | 2024-06-14 | Passion UA        | W   | 0.858      | 0.435        | 0.172 (0.064)    | 1.000 (0.373)    | -         |     3.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1106 | 2024-06-13 | 9INE              | W   | 0.853      | -            | -                | -                | -         |     1.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1118 | 2024-06-13 | VP.Prodigy        | W   | 0.852      | -            | -                | -                | -         |     1.34 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1149 | 2024-06-11 | SINNERS           | W   | 0.840      | -            | -                | -                | -         |     2.49 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1160 | 2024-06-11 | BUHAWI            | W   | 0.839      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1176 | 2024-06-10 | EYEBALLERS        | W   | 0.833      | -            | -                | -                | -         |     1.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1183 | 2024-06-10 | SAW               | W   | 0.832      | -            | -                | -                | -         |     5.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1190 | 2024-06-10 | PARIVISION        | W   | 0.832      | -            | -                | -                | -         |     3.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1194 | 2024-06-10 | 9 Pandas          | W   | 0.832      | -            | -                | -                | -         |     3.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1216 | 2024-06-09 | 9INE              | L   | 0.827      | -            | -                | -                | -         |   -24.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1229 | 2024-06-09 | Monte             | L   | 0.826      | -            | -                | -                | -         |   -24.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1236 | 2024-06-09 | SINNERS           | L   | 0.826      | -            | -                | -                | -         |   -23.97 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1243 | 2024-06-09 | Aurora            | W   | 0.825      | 0.143        | 0.423 (0.050)    | -                | -         |    12.72 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1253 | 2024-06-09 | RUSH B            | W   | 0.825      | -            | -                | -                | -         |     0.89 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1291 | 2024-06-08 | Illuminar         | L   | 0.820      | -            | -                | -                | -         |   -25.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1349 | 2024-06-07 | Gaimin Gladiators | W   | 0.813      | -            | -                | -                | -         |     1.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1388 | 2024-06-06 | Nexus             | W   | 0.808      | -            | -                | -                | -         |     0.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1405 | 2024-06-06 | Sangal            | L   | 0.807      | -            | -                | -                | -         |   -22.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1468 | 2024-06-05 | KOI               | L   | 0.800      | -            | -                | -                | -         |   -23.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1514 | 2024-06-04 | Aurora            | W   | 0.793      | 0.500        | 0.423 (0.168)    | 0.793 (0.314)    | -         |    12.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1598 | 2024-06-01 | VP.Prodigy        | L   | 0.773      | -            | -                | -                | -         |   -23.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1651 | 2024-05-30 | Sampi             | W   | 0.760      | 0.435        | -                | 1.000 (0.330)    | -         |     0.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1773 | 2024-05-25 | MOUZ NXT          | L   | 0.724      | -            | -                | -                | -         |   -21.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1796 | 2024-05-23 | Zero Tenacity     | W   | 0.713      | 0.435        | -                | 1.000 (0.310)    | -         |     1.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2010 | 2024-05-17 | B8                | L   | 0.672      | -            | -                | -                | -         |   -19.70 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2096 | 2024-05-15 | Zero Tenacity     | L   | 0.659      | -            | -                | -                | -         |   -19.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2292 | 2024-05-08 | G2                | L   | 0.613      | -            | -                | -                | -         |    -2.54 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2435 | 2024-05-01 | Sashi             | L   | 0.565      | -            | -                | -                | -         |   -16.38 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2459 | 2024-04-30 | BetBoom           | W   | 0.558      | 0.384        | 0.251 (0.054)    | -                | -         |     4.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2467 | 2024-04-29 | PARIVISION        | W   | 0.554      | -            | -                | -                | -         |     0.85 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2514 | 2024-04-27 | Astralis          | L   | 0.540      | -            | -                | -                | -         |    -5.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2588 | 2024-04-24 | fnatic            | W   | 0.520      | 0.889        | 0.371 (0.171)    | 0.708 (0.327)    | 1 (0.520) |     6.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2613 | 2024-04-23 | SAW               | W   | 0.512      | -            | -                | -                | 1 (0.512) |     1.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2622 | 2024-04-22 | ex-Guild Eagles   | W   | 0.507      | -            | -                | -                | -         |     0.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2818 | 2024-04-17 | BLEED             | W   | 0.472      | -            | -                | -                | -         |     0.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2876 | 2024-04-14 | BetBoom           | L   | 0.452      | -            | -                | -                | -         |   -11.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2890 | 2024-04-13 | ex-Preasy         | W   | 0.446      | -            | -                | -                | -         |     0.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2932 | 2024-04-11 | Passion UA        | L   | 0.432      | -            | -                | -                | -         |   -13.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2966 | 2024-04-10 | SINNERS           | L   | 0.427      | -            | -                | -                | -         |   -12.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3018 | 2024-04-09 | SAW               | W   | 0.420      | -            | -                | -                | -         |     0.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3092 | 2024-04-07 | Young Ninjas      | W   | 0.406      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3164 | 2024-04-04 | Space             | W   | 0.386      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3192 | 2024-04-03 | GUN5              | W   | 0.380      | -            | -                | -                | -         |     0.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3245 | 2024-04-02 | Permitta          | W   | 0.372      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3300 | 2024-03-28 | Apeks             | W   | 0.339      | -            | -                | -                | -         |     0.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3426 | 2024-03-21 | fnatic            | L   | 0.293      | -            | -                | -                | -         |    -6.00 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3466 | 2024-03-19 | GUN5              | W   | 0.279      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3536 | 2024-03-15 | B8                | W   | 0.253      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3606 | 2024-03-13 | PARIVISION        | L   | 0.240      | -            | -                | -                | -         |    -7.24 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3817 | 2024-03-05 | FORZE             | L   | 0.187      | -            | -                | -                | -         |    -5.81 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3840 | 2024-03-04 | fnatic            | L   | 0.179      | -            | -                | -                | -         |    -3.83 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3878 | 2024-03-02 | Monte             | W   | 0.167      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3913 | 2024-02-29 | Gaimin Gladiators | W   | 0.154      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4215 | 2024-02-16 | 9 Pandas          | L   | 0.066      | -            | -                | -                | -         |    -2.03 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4239 | 2024-02-15 | Into the Breach   | W   | 0.060      | -            | -                | -                | 1 (0.060) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4275 | 2024-02-14 | KOI               | L   | 0.054      | -            | -                | -                | -         |    -1.64 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4281 | 2024-02-14 | Falcons           | L   | 0.053      | -            | -                | -                | -         |    -1.35 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4329 | 2024-02-11 | Apeks             | L   | 0.033      | -            | -                | -                | -         |    -1.04 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4353 | 2024-02-09 | fnatic            | W   | 0.020      | -            | -                | -                | -         |     0.21 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4354 | 2024-02-09 | Endpoint          | W   | 0.020      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4359 | 2024-02-09 | ex-Sprout         | L   | 0.019      | -            | -                | -                | -         |    -0.61 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($164,028.26)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.878 | $10,000.00     | $8,784.95       |
| 2024-06-16 |      0.873 | $10,000.00     | $8,732.18       |
| 2024-06-09 |      0.826 | $7,000.00      | $5,785.37       |
| 2024-06-02 |      0.780 | $2,000.00      | $1,559.21       |
| 2024-05-26 |      0.733 | $2,000.00      | $1,466.44       |
| 2024-05-12 |      0.640 | $23,500.00     | $15,030.75      |
| 2024-05-02 |      0.573 | $1,500.00      | $859.83         |
| 2024-04-14 |      0.452 | $4,000.00      | $1,809.54       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
