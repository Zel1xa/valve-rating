### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1431.0<br />
<br />
Final Rank Value (1431.0) = Starting Rank Value (1687.6) + Head To Head Adjustments (-256.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.773[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.359[<sup>2</sup>](#table1)
- LAN Wins: 0.814[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1687.6
- 400 + ( ( 0.627 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1687.6


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
|           83 |       38 | 2024-08-04 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -23.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           82 |       64 | 2024-08-03 | fnatic            | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    14.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           81 |      108 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    11.44 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |      141 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      183 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      303 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.709 (0.461)    | 1 (1.000) |    26.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      317 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.421 (0.274)    | 0.776 (0.505)    | 1 (1.000) |    18.54 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      331 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.173 (0.113)    | -                | 1 (1.000) |    15.35 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      357 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      397 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      409 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      437 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.084)    | 0.463 (0.301)    | 1 (1.000) |     9.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      704 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.716 (0.358)    | -         |     4.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      807 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      933 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -30.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |     1015 | 2024-06-17 | 5W                | L   | 0.867      | -            | -                | -                | -         |   -24.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |     1029 | 2024-06-16 | B8                | L   | 0.862      | -            | -                | -                | -         |   -22.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |     1034 | 2024-06-16 | Permitta          | W   | 0.861      | 0.435        | -                | 0.940 (0.352)    | -         |     1.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |     1040 | 2024-06-16 | Enterprise        | W   | 0.860      | -            | -                | -                | -         |     1.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |     1055 | 2024-06-15 | GUN5              | W   | 0.856      | -            | -                | -                | -         |     1.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1075 | 2024-06-15 | BLEED             | W   | 0.853      | -            | -                | -                | -         |    10.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1109 | 2024-06-14 | Sashi             | W   | 0.848      | -            | -                | -                | -         |     5.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1120 | 2024-06-14 | Passion UA        | W   | 0.846      | 0.435        | 0.173 (0.064)    | 1.000 (0.368)    | -         |     3.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1138 | 2024-06-13 | 9INE              | W   | 0.842      | -            | -                | -                | -         |     1.49 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1150 | 2024-06-13 | VP.Prodigy        | W   | 0.840      | -            | -                | -                | -         |     1.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1181 | 2024-06-11 | SINNERS           | W   | 0.829      | -            | -                | -                | -         |     2.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1192 | 2024-06-11 | BUHAWI            | W   | 0.828      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1208 | 2024-06-10 | EYEBALLERS        | W   | 0.822      | -            | -                | -                | -         |     1.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1215 | 2024-06-10 | SAW               | W   | 0.821      | -            | -                | -                | -         |     4.96 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1222 | 2024-06-10 | PARIVISION        | W   | 0.820      | -            | -                | -                | -         |     3.35 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1226 | 2024-06-10 | 9 Pandas          | W   | 0.820      | -            | -                | -                | -         |     2.95 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1248 | 2024-06-09 | 9INE              | L   | 0.815      | -            | -                | -                | -         |   -24.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1261 | 2024-06-09 | Monte             | L   | 0.815      | -            | -                | -                | -         |   -23.79 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1268 | 2024-06-09 | SINNERS           | L   | 0.814      | -            | -                | -                | -         |   -23.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1275 | 2024-06-09 | Aurora            | W   | 0.814      | 0.143        | 0.421 (0.049)    | -                | -         |    12.52 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1285 | 2024-06-09 | RUSH B            | W   | 0.813      | -            | -                | -                | -         |     0.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1323 | 2024-06-08 | Illuminar         | L   | 0.808      | -            | -                | -                | -         |   -24.71 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1381 | 2024-06-07 | Gaimin Gladiators | W   | 0.801      | -            | -                | -                | -         |     1.34 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1420 | 2024-06-06 | Nexus             | W   | 0.796      | -            | -                | -                | -         |     0.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1437 | 2024-06-06 | Sangal            | L   | 0.795      | -            | -                | -                | -         |   -22.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1500 | 2024-06-05 | KOI               | L   | 0.789      | -            | -                | -                | -         |   -23.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1546 | 2024-06-04 | Aurora            | W   | 0.782      | 0.500        | 0.421 (0.164)    | 0.776 (0.303)    | -         |    11.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1630 | 2024-06-01 | VP.Prodigy        | L   | 0.761      | -            | -                | -                | -         |   -23.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1683 | 2024-05-30 | Sampi             | W   | 0.749      | 0.435        | -                | 1.000 (0.325)    | -         |     0.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1805 | 2024-05-25 | MOUZ NXT          | L   | 0.713      | -            | -                | -                | -         |   -21.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1828 | 2024-05-23 | Zero Tenacity     | W   | 0.701      | 0.435        | -                | 1.000 (0.305)    | -         |     1.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     2042 | 2024-05-17 | B8                | L   | 0.661      | -            | -                | -                | -         |   -19.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2128 | 2024-05-15 | Zero Tenacity     | L   | 0.647      | -            | -                | -                | -         |   -19.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2324 | 2024-05-08 | G2                | L   | 0.601      | -            | -                | -                | -         |    -2.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2467 | 2024-05-01 | Sashi             | L   | 0.554      | -            | -                | -                | -         |   -16.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2491 | 2024-04-30 | BetBoom           | W   | 0.547      | 0.384        | 0.248 (0.052)    | -                | -         |     3.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2499 | 2024-04-29 | PARIVISION        | W   | 0.542      | -            | -                | -                | -         |     0.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2546 | 2024-04-27 | Astralis          | L   | 0.528      | -            | -                | -                | -         |    -5.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2620 | 2024-04-24 | fnatic            | W   | 0.508      | 0.889        | 0.371 (0.167)    | 0.695 (0.314)    | 1 (0.508) |     5.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2645 | 2024-04-23 | SAW               | W   | 0.500      | -            | -                | -                | 1 (0.500) |     1.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2654 | 2024-04-22 | ex-Guild Eagles   | W   | 0.495      | -            | -                | -                | -         |     0.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2850 | 2024-04-17 | BLEED             | W   | 0.460      | -            | -                | -                | -         |     0.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2908 | 2024-04-14 | BetBoom           | L   | 0.441      | -            | -                | -                | -         |   -11.00 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2922 | 2024-04-13 | ex-Preasy         | W   | 0.434      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2964 | 2024-04-11 | Passion UA        | L   | 0.421      | -            | -                | -                | -         |   -12.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2998 | 2024-04-10 | SINNERS           | L   | 0.416      | -            | -                | -                | -         |   -12.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     3050 | 2024-04-09 | SAW               | W   | 0.409      | -            | -                | -                | -         |     0.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3124 | 2024-04-07 | Young Ninjas      | W   | 0.394      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3196 | 2024-04-04 | Space             | W   | 0.374      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3224 | 2024-04-03 | GUN5              | W   | 0.369      | -            | -                | -                | -         |     0.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3277 | 2024-04-02 | Permitta          | W   | 0.361      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3332 | 2024-03-28 | Apeks             | W   | 0.328      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3458 | 2024-03-21 | fnatic            | L   | 0.281      | -            | -                | -                | -         |    -5.86 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3498 | 2024-03-19 | GUN5              | W   | 0.268      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3568 | 2024-03-15 | B8                | W   | 0.242      | -            | -                | -                | -         |     0.29 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3638 | 2024-03-13 | PARIVISION        | L   | 0.228      | -            | -                | -                | -         |    -6.89 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3849 | 2024-03-05 | FORZE             | L   | 0.175      | -            | -                | -                | -         |    -5.45 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3872 | 2024-03-04 | fnatic            | L   | 0.168      | -            | -                | -                | -         |    -3.63 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3910 | 2024-03-02 | Monte             | W   | 0.156      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3945 | 2024-02-29 | Gaimin Gladiators | W   | 0.142      | -            | -                | -                | -         |     0.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4247 | 2024-02-16 | 9 Pandas          | L   | 0.054      | -            | -                | -                | -         |    -1.68 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4271 | 2024-02-15 | Into the Breach   | W   | 0.048      | -            | -                | -                | 1 (0.048) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4307 | 2024-02-14 | KOI               | L   | 0.042      | -            | -                | -                | -         |    -1.29 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4313 | 2024-02-14 | Falcons           | L   | 0.041      | -            | -                | -                | -         |    -1.06 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4361 | 2024-02-11 | Apeks             | L   | 0.022      | -            | -                | -                | -         |    -0.68 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4385 | 2024-02-09 | fnatic            | W   | 0.009      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4386 | 2024-02-09 | Endpoint          | W   | 0.008      | -            | -                | -                | -         |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4391 | 2024-02-09 | ex-Sprout         | L   | 0.008      | -            | -                | -                | -         |    -0.24 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163,335.21)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.867 | $10,000.00     | $8,669.44       |
| 2024-06-16 |      0.862 | $10,000.00     | $8,616.67       |
| 2024-06-09 |      0.815 | $7,000.00      | $5,704.51       |
| 2024-06-02 |      0.768 | $2,000.00      | $1,536.11       |
| 2024-05-26 |      0.722 | $2,000.00      | $1,443.33       |
| 2024-05-12 |      0.628 | $23,500.00     | $14,759.31      |
| 2024-05-02 |      0.562 | $1,500.00      | $842.50         |
| 2024-04-14 |      0.441 | $4,000.00      | $1,763.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
