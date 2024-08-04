### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1429.8<br />
<br />
Final Rank Value (1429.8) = Starting Rank Value (1682.0) + Head To Head Adjustments (-252.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.771[<sup>1</sup>](#table2)
- Bounty Collected: 0.564[<sup>2</sup>](#table1)
- Opponent Network: 0.364[<sup>2</sup>](#table1)
- LAN Wins: 0.811[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1682.0
- 400 + ( ( 0.627 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1682.0


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
|           81 |       42 | 2024-08-02 | BLEED             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           80 |       76 | 2024-08-01 | Betera            | W   | 1.000      | -            | -                | -                | -         |     0.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           79 |      116 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | -         |     0.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      236 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.720 (0.469)    | 1 (1.000) |    26.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      250 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.424 (0.276)    | 0.794 (0.516)    | 1 (1.000) |    18.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      264 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.170 (0.110)    | -                | 1 (1.000) |    15.33 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      290 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      330 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      342 | 2024-07-25 | DMS               | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      370 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.130 (0.085)    | 0.477 (0.310)    | 1 (1.000) |     9.70 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      634 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.691 (0.345)    | -         |     5.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      738 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.90 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      865 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -29.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |      947 | 2024-06-17 | 5W                | L   | 0.883      | -            | -                | -                | -         |   -25.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |      961 | 2024-06-16 | B8                | L   | 0.878      | -            | -                | -                | -         |   -22.82 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |      966 | 2024-06-16 | Permitta          | W   | 0.877      | 0.435        | -                | 0.876 (0.334)    | -         |     1.63 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |      972 | 2024-06-16 | Enterprise        | W   | 0.876      | -            | -                | -                | -         |     1.55 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |      987 | 2024-06-15 | GUN5              | W   | 0.872      | -            | -                | -                | -         |     2.02 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |     1007 | 2024-06-15 | BLEED             | W   | 0.870      | -            | -                | -                | -         |    10.44 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |     1041 | 2024-06-14 | Sashi             | W   | 0.864      | -            | -                | -                | -         |     5.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |     1052 | 2024-06-14 | Passion UA        | W   | 0.863      | 0.435        | 0.172 (0.064)    | 1.000 (0.375)    | -         |     3.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |     1070 | 2024-06-13 | 9INE              | W   | 0.858      | -            | -                | -                | -         |     1.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1082 | 2024-06-13 | VP.Prodigy        | W   | 0.856      | -            | -                | -                | -         |     1.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1113 | 2024-06-11 | SINNERS           | W   | 0.845      | -            | -                | -                | -         |     2.35 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1124 | 2024-06-11 | BUHAWI            | W   | 0.844      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1140 | 2024-06-10 | EYEBALLERS        | W   | 0.838      | -            | -                | -                | -         |     1.34 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1147 | 2024-06-10 | SAW               | W   | 0.837      | -            | -                | -                | -         |     5.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1154 | 2024-06-10 | PARIVISION        | W   | 0.837      | -            | -                | -                | -         |     3.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1158 | 2024-06-10 | 9 Pandas          | W   | 0.836      | -            | -                | -                | -         |     3.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1180 | 2024-06-09 | 9INE              | L   | 0.831      | -            | -                | -                | -         |   -24.72 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1193 | 2024-06-09 | Monte             | L   | 0.831      | -            | -                | -                | -         |   -24.15 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1200 | 2024-06-09 | SINNERS           | L   | 0.831      | -            | -                | -                | -         |   -24.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1207 | 2024-06-09 | Aurora            | W   | 0.830      | 0.143        | 0.424 (0.050)    | -                | -         |    12.79 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1217 | 2024-06-09 | RUSH B            | W   | 0.830      | -            | -                | -                | -         |     0.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1255 | 2024-06-08 | Illuminar         | L   | 0.824      | -            | -                | -                | -         |   -25.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1313 | 2024-06-07 | Gaimin Gladiators | W   | 0.818      | -            | -                | -                | -         |     1.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1352 | 2024-06-06 | Nexus             | W   | 0.813      | -            | -                | -                | -         |     0.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1369 | 2024-06-06 | Sangal            | L   | 0.812      | -            | -                | -                | -         |   -22.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1432 | 2024-06-05 | KOI               | L   | 0.805      | -            | -                | -                | -         |   -23.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1478 | 2024-06-04 | Aurora            | W   | 0.798      | 0.500        | 0.424 (0.169)    | 0.794 (0.317)    | -         |    12.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1562 | 2024-06-01 | VP.Prodigy        | L   | 0.778      | -            | -                | -                | -         |   -23.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1615 | 2024-05-30 | Sampi             | W   | 0.765      | 0.435        | -                | 1.000 (0.333)    | -         |     0.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1737 | 2024-05-25 | MOUZ NXT          | L   | 0.729      | -            | -                | -                | -         |   -21.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1760 | 2024-05-23 | Zero Tenacity     | W   | 0.718      | 0.435        | -                | 1.000 (0.312)    | -         |     1.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     1974 | 2024-05-17 | B8                | L   | 0.677      | -            | -                | -                | -         |   -19.82 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2060 | 2024-05-15 | Zero Tenacity     | L   | 0.664      | -            | -                | -                | -         |   -19.91 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2256 | 2024-05-08 | G2                | L   | 0.618      | -            | -                | -                | -         |    -2.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2399 | 2024-05-01 | Sashi             | L   | 0.570      | -            | -                | -                | -         |   -16.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2423 | 2024-04-30 | BetBoom           | W   | 0.563      | 0.384        | 0.252 (0.054)    | -                | -         |     4.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2431 | 2024-04-29 | PARIVISION        | W   | 0.558      | -            | -                | -                | -         |     0.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2478 | 2024-04-27 | Astralis          | L   | 0.544      | -            | -                | -                | -         |    -6.65 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2551 | 2024-04-24 | fnatic            | W   | 0.524      | 0.889        | 0.371 (0.173)    | 0.709 (0.330)    | 1 (0.524) |     6.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2576 | 2024-04-23 | SAW               | W   | 0.517      | 0.889        | 0.106 (0.048)    | -                | 1 (0.517) |     1.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2585 | 2024-04-22 | ex-Guild Eagles   | W   | 0.511      | -            | -                | -                | -         |     0.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2781 | 2024-04-17 | BLEED             | W   | 0.476      | -            | -                | -                | -         |     0.48 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2839 | 2024-04-14 | BetBoom           | L   | 0.457      | -            | -                | -                | -         |   -11.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2853 | 2024-04-13 | ex-Preasy         | W   | 0.451      | -            | -                | -                | -         |     0.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2895 | 2024-04-11 | Passion UA        | L   | 0.437      | -            | -                | -                | -         |   -13.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2929 | 2024-04-10 | SINNERS           | L   | 0.432      | -            | -                | -                | -         |   -12.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     2981 | 2024-04-09 | SAW               | W   | 0.425      | -            | -                | -                | -         |     0.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3055 | 2024-04-07 | Young Ninjas      | W   | 0.411      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3127 | 2024-04-04 | Space             | W   | 0.391      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3155 | 2024-04-03 | GUN5              | W   | 0.385      | -            | -                | -                | -         |     0.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3208 | 2024-04-02 | Permitta          | W   | 0.377      | -            | -                | -                | -         |     0.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3263 | 2024-03-28 | Apeks             | W   | 0.344      | -            | -                | -                | -         |     0.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3389 | 2024-03-21 | fnatic            | L   | 0.298      | -            | -                | -                | -         |    -6.09 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3429 | 2024-03-19 | GUN5              | W   | 0.284      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3499 | 2024-03-15 | B8                | W   | 0.258      | -            | -                | -                | -         |     0.32 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3568 | 2024-03-13 | PARIVISION        | L   | 0.244      | -            | -                | -                | -         |    -7.38 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3779 | 2024-03-05 | FORZE             | L   | 0.192      | -            | -                | -                | -         |    -5.96 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3802 | 2024-03-04 | fnatic            | L   | 0.184      | -            | -                | -                | -         |    -3.93 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3840 | 2024-03-02 | Monte             | W   | 0.172      | -            | -                | -                | -         |     0.12 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3875 | 2024-02-29 | Gaimin Gladiators | W   | 0.159      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4176 | 2024-02-16 | 9 Pandas          | L   | 0.071      | -            | -                | -                | -         |    -2.18 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4200 | 2024-02-15 | Into the Breach   | W   | 0.065      | -            | -                | -                | 1 (0.065) |     0.00 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4236 | 2024-02-14 | KOI               | L   | 0.059      | -            | -                | -                | -         |    -1.78 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4242 | 2024-02-14 | Falcons           | L   | 0.058      | -            | -                | -                | -         |    -1.47 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4290 | 2024-02-11 | Apeks             | L   | 0.038      | -            | -                | -                | -         |    -1.19 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4314 | 2024-02-09 | fnatic            | W   | 0.025      | -            | -                | -                | -         |     0.27 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4315 | 2024-02-09 | Endpoint          | W   | 0.025      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4320 | 2024-02-09 | ex-Sprout         | L   | 0.024      | -            | -                | -                | -         |    -0.76 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($164,318.54)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.883 | $10,000.00     | $8,833.33       |
| 2024-06-16 |      0.878 | $10,000.00     | $8,780.56       |
| 2024-06-09 |      0.831 | $7,000.00      | $5,819.24       |
| 2024-06-02 |      0.784 | $2,000.00      | $1,568.89       |
| 2024-05-26 |      0.738 | $2,000.00      | $1,476.11       |
| 2024-05-12 |      0.644 | $23,500.00     | $15,144.44      |
| 2024-05-02 |      0.578 | $1,500.00      | $867.08         |
| 2024-04-14 |      0.457 | $4,000.00      | $1,828.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
