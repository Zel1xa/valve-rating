### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1422.5<br />
<br />
Final Rank Value (1422.5) = Starting Rank Value (1697.3) + Head To Head Adjustments (-274.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.768[<sup>1</sup>](#table2)
- Bounty Collected: 0.566[<sup>2</sup>](#table1)
- Opponent Network: 0.359[<sup>2</sup>](#table1)
- LAN Wins: 0.824[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1697.3
- 400 + ( ( 0.629 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1697.3


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
|           79 |        2 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.28 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      122 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.719 (0.467)    | 1 (1.000) |    26.71 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      136 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.429 (0.279)    | 0.800 (0.520)    | 1 (1.000) |    18.72 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      150 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.173 (0.112)    | -                | 1 (1.000) |    15.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      176 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.33 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      216 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      228 | 2024-07-25 | DMS               | W   | 1.000      | 0.650        | -                | 0.447 (0.291)    | 1 (1.000) |     2.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      256 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.131 (0.085)    | 0.484 (0.315)    | 1 (1.000) |     9.94 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      523 | 2024-07-17 | 9 Pandas          | W   | 1.000      | -            | -                | -                | -         |     5.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      626 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -27.00 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      752 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -29.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |      834 | 2024-06-17 | 5W                | L   | 0.904      | -            | -                | -                | -         |   -25.70 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |      848 | 2024-06-16 | B8                | L   | 0.899      | -            | -                | -                | -         |   -23.28 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |      853 | 2024-06-16 | Permitta          | W   | 0.898      | 0.435        | -                | 0.799 (0.312)    | -         |     1.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |      859 | 2024-06-16 | Enterprise        | W   | 0.897      | -            | -                | -                | -         |     1.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |      874 | 2024-06-15 | GUN5              | W   | 0.893      | -            | -                | -                | -         |     2.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |      894 | 2024-06-15 | BLEED             | W   | 0.890      | -            | -                | -                | -         |    10.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |      928 | 2024-06-14 | Sashi             | W   | 0.885      | -            | -                | -                | -         |     6.28 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |      939 | 2024-06-14 | Passion UA        | W   | 0.883      | 0.435        | 0.171 (0.066)    | 1.000 (0.384)    | -         |     3.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |      957 | 2024-06-13 | 9INE              | W   | 0.879      | -            | -                | -                | -         |     1.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |      969 | 2024-06-13 | VP.Prodigy        | W   | 0.877      | -            | -                | -                | -         |     1.39 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1000 | 2024-06-11 | SINNERS           | W   | 0.866      | -            | -                | -                | -         |     2.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1011 | 2024-06-11 | BUHAWI            | W   | 0.865      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1027 | 2024-06-10 | EYEBALLERS        | W   | 0.859      | -            | -                | -                | -         |     1.38 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1034 | 2024-06-10 | SAW               | W   | 0.858      | -            | -                | -                | -         |     5.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1041 | 2024-06-10 | PARIVISION        | W   | 0.858      | -            | -                | -                | -         |     3.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1045 | 2024-06-10 | 9 Pandas          | W   | 0.857      | -            | -                | -                | -         |     3.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1067 | 2024-06-09 | 9INE              | L   | 0.852      | -            | -                | -                | -         |   -25.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1080 | 2024-06-09 | Monte             | L   | 0.852      | -            | -                | -                | -         |   -24.73 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1087 | 2024-06-09 | SINNERS           | L   | 0.851      | -            | -                | -                | -         |   -25.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1094 | 2024-06-09 | Aurora            | W   | 0.851      | 0.143        | 0.429 (0.052)    | -                | -         |    13.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1104 | 2024-06-09 | RUSH B            | W   | 0.850      | -            | -                | -                | -         |     0.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1142 | 2024-06-08 | Illuminar         | L   | 0.845      | -            | -                | -                | -         |   -25.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1200 | 2024-06-07 | Gaimin Gladiators | W   | 0.839      | -            | -                | -                | -         |     1.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1239 | 2024-06-06 | Nexus             | W   | 0.833      | -            | -                | -                | -         |     0.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1256 | 2024-06-06 | Sangal            | L   | 0.832      | -            | -                | -                | -         |   -23.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1319 | 2024-06-05 | KOI               | L   | 0.826      | -            | -                | -                | -         |   -24.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1365 | 2024-06-04 | Aurora            | W   | 0.819      | 0.500        | 0.429 (0.176)    | 0.800 (0.327)    | -         |    12.73 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1449 | 2024-06-01 | VP.Prodigy        | L   | 0.799      | -            | -                | -                | -         |   -24.39 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1502 | 2024-05-30 | Sampi             | W   | 0.786      | 0.435        | -                | 1.000 (0.342)    | -         |     0.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1624 | 2024-05-25 | MOUZ NXT          | L   | 0.750      | -            | -                | -                | -         |   -22.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1647 | 2024-05-23 | Zero Tenacity     | W   | 0.738      | 0.435        | -                | 1.000 (0.321)    | -         |     1.63 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     1861 | 2024-05-17 | B8                | L   | 0.698      | -            | -                | -                | -         |   -20.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     1947 | 2024-05-15 | Zero Tenacity     | L   | 0.684      | -            | -                | -                | -         |   -20.56 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2143 | 2024-05-08 | G2                | L   | 0.638      | -            | -                | -                | -         |    -2.74 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2286 | 2024-05-01 | Sashi             | L   | 0.591      | -            | -                | -                | -         |   -17.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2310 | 2024-04-30 | BetBoom           | W   | 0.584      | 0.384        | 0.256 (0.057)    | -                | -         |     4.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2318 | 2024-04-29 | PARIVISION        | W   | 0.579      | -            | -                | -                | -         |     0.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2365 | 2024-04-27 | Astralis          | L   | 0.565      | -            | -                | -                | -         |    -6.63 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2439 | 2024-04-24 | fnatic            | W   | 0.545      | 0.889        | 0.371 (0.180)    | 0.633 (0.307)    | 1 (0.545) |     6.74 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2464 | 2024-04-23 | SAW               | W   | 0.538      | 0.889        | 0.107 (0.051)    | -                | 1 (0.538) |     1.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2473 | 2024-04-22 | ex-Guild Eagles   | W   | 0.532      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2669 | 2024-04-17 | BLEED             | W   | 0.497      | -            | -                | -                | -         |     0.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2727 | 2024-04-14 | BetBoom           | L   | 0.478      | -            | -                | -                | -         |   -11.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2741 | 2024-04-13 | ex-Preasy         | W   | 0.471      | -            | -                | -                | -         |     0.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2783 | 2024-04-11 | Passion UA        | L   | 0.458      | -            | -                | -                | -         |   -13.96 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2817 | 2024-04-10 | SINNERS           | L   | 0.453      | -            | -                | -                | -         |   -13.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     2869 | 2024-04-09 | SAW               | W   | 0.446      | -            | -                | -                | -         |     0.95 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     2943 | 2024-04-07 | Young Ninjas      | W   | 0.431      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3015 | 2024-04-04 | Space             | W   | 0.412      | -            | -                | -                | -         |     0.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3043 | 2024-04-03 | GUN5              | W   | 0.406      | -            | -                | -                | -         |     0.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3096 | 2024-04-02 | Permitta          | W   | 0.398      | -            | -                | -                | -         |     0.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3151 | 2024-03-28 | Apeks             | W   | 0.365      | -            | -                | -                | -         |     0.18 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3277 | 2024-03-21 | fnatic            | L   | 0.318      | -            | -                | -                | -         |    -6.36 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3317 | 2024-03-19 | GUN5              | W   | 0.305      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3387 | 2024-03-15 | B8                | W   | 0.279      | -            | -                | -                | -         |     0.35 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3457 | 2024-03-13 | PARIVISION        | L   | 0.265      | -            | -                | -                | -         |    -8.04 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3668 | 2024-03-05 | FORZE             | L   | 0.212      | -            | -                | -                | -         |    -6.60 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3691 | 2024-03-04 | fnatic            | L   | 0.205      | -            | -                | -                | -         |    -4.29 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3729 | 2024-03-02 | Monte             | W   | 0.193      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3764 | 2024-02-29 | Gaimin Gladiators | W   | 0.180      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4066 | 2024-02-16 | 9 Pandas          | L   | 0.092      | -            | -                | -                | -         |    -2.82 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4090 | 2024-02-15 | Into the Breach   | W   | 0.085      | -            | -                | -                | 1 (0.085) |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4126 | 2024-02-14 | KOI               | L   | 0.079      | -            | -                | -                | -         |    -2.41 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4132 | 2024-02-14 | Falcons           | L   | 0.078      | -            | -                | -                | -         |    -1.95 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4180 | 2024-02-11 | Apeks             | L   | 0.059      | -            | -                | -                | -         |    -1.83 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4204 | 2024-02-09 | fnatic            | W   | 0.046      | -            | -                | -                | -         |     0.51 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4205 | 2024-02-09 | Endpoint          | W   | 0.046      | -            | -                | -                | -         |     0.02 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4210 | 2024-02-09 | ex-Sprout         | L   | 0.045      | -            | -                | -                | -         |    -1.41 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($165,562.15)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.904 | $10,000.00     | $9,040.60       |
| 2024-06-16 |      0.899 | $10,000.00     | $8,987.82       |
| 2024-06-09 |      0.852 | $7,000.00      | $5,964.32       |
| 2024-06-02 |      0.805 | $2,000.00      | $1,610.34       |
| 2024-05-26 |      0.759 | $2,000.00      | $1,517.56       |
| 2024-05-12 |      0.665 | $23,500.00     | $15,631.53      |
| 2024-05-02 |      0.599 | $1,500.00      | $898.17         |
| 2024-04-14 |      0.478 | $4,000.00      | $1,911.80       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
