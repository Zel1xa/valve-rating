### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1415.1<br />
<br />
Final Rank Value (1415.1) = Starting Rank Value (1693.2) + Head To Head Adjustments (-278.1)<br />

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
|           79 |       34 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      155 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.719 (0.468)    | 1 (1.000) |    26.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      169 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.431 (0.281)    | 0.798 (0.519)    | 1 (1.000) |    18.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      183 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.174 (0.113)    | -                | 1 (1.000) |    15.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      209 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      249 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      261 | 2024-07-25 | DMS               | W   | 1.000      | 0.650        | -                | 0.447 (0.291)    | 1 (1.000) |     2.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      289 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.132 (0.086)    | 0.482 (0.313)    | 1 (1.000) |     9.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      562 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.577 (0.289)    | -         |     5.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      673 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      802 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -29.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |      885 | 2024-06-17 | 5W                | L   | 0.898      | -            | -                | -                | -         |   -25.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |      897 | 2024-06-16 | B8                | L   | 0.893      | -            | -                | -                | -         |   -23.33 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |      901 | 2024-06-16 | Permitta          | W   | 0.892      | 0.435        | -                | 0.801 (0.311)    | -         |     1.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |      907 | 2024-06-16 | Enterprise        | W   | 0.891      | -            | -                | -                | -         |     1.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |      920 | 2024-06-15 | GUN5              | W   | 0.887      | -            | -                | -                | -         |     2.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |      939 | 2024-06-15 | BLEED             | W   | 0.885      | -            | -                | -                | -         |    11.02 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |      967 | 2024-06-14 | Sashi             | W   | 0.879      | -            | -                | -                | -         |     6.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |      978 | 2024-06-14 | Passion UA        | W   | 0.877      | 0.435        | 0.173 (0.066)    | 1.000 (0.381)    | -         |     3.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |      996 | 2024-06-13 | 9INE              | W   | 0.873      | -            | -                | -                | -         |     2.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1008 | 2024-06-13 | VP.Prodigy        | W   | 0.871      | -            | -                | -                | -         |     1.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1040 | 2024-06-11 | SINNERS           | W   | 0.860      | -            | -                | -                | -         |     2.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1051 | 2024-06-11 | BUHAWI            | W   | 0.859      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1068 | 2024-06-10 | EYEBALLERS        | W   | 0.853      | -            | -                | -                | -         |     1.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1075 | 2024-06-10 | SAW               | W   | 0.852      | -            | -                | -                | -         |     5.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1082 | 2024-06-10 | PARIVISION        | W   | 0.852      | -            | -                | -                | -         |     3.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1086 | 2024-06-10 | 9 Pandas          | W   | 0.851      | -            | -                | -                | -         |     3.39 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1108 | 2024-06-09 | 9INE              | L   | 0.846      | -            | -                | -                | -         |   -24.76 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1121 | 2024-06-09 | Monte             | L   | 0.846      | -            | -                | -                | -         |   -24.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1128 | 2024-06-09 | SINNERS           | L   | 0.846      | -            | -                | -                | -         |   -24.71 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1135 | 2024-06-09 | Aurora            | W   | 0.845      | 0.143        | 0.431 (0.052)    | -                | -         |    13.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1146 | 2024-06-09 | RUSH B            | W   | 0.845      | -            | -                | -                | -         |     0.89 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1185 | 2024-06-08 | Illuminar         | L   | 0.839      | -            | -                | -                | -         |   -25.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1250 | 2024-06-07 | Gaimin Gladiators | W   | 0.833      | -            | -                | -                | -         |     1.63 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1291 | 2024-06-06 | Nexus             | W   | 0.828      | -            | -                | -                | -         |     0.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1308 | 2024-06-06 | Sangal            | L   | 0.827      | -            | -                | -                | -         |   -23.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1374 | 2024-06-05 | KOI               | L   | 0.820      | -            | -                | -                | -         |   -24.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1420 | 2024-06-04 | Aurora            | W   | 0.813      | 0.500        | 0.431 (0.175)    | 0.798 (0.325)    | -         |    12.74 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1505 | 2024-06-01 | VP.Prodigy        | L   | 0.793      | -            | -                | -                | -         |   -24.18 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1558 | 2024-05-30 | Sampi             | W   | 0.780      | 0.435        | -                | 1.000 (0.339)    | -         |     0.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1682 | 2024-05-25 | MOUZ NXT          | L   | 0.744      | -            | -                | -                | -         |   -22.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1705 | 2024-05-23 | Zero Tenacity     | W   | 0.733      | 0.435        | -                | 1.000 (0.318)    | -         |     1.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     1945 | 2024-05-17 | B8                | L   | 0.692      | -            | -                | -                | -         |   -20.28 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2035 | 2024-05-15 | Zero Tenacity     | L   | 0.679      | -            | -                | -                | -         |   -20.37 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2238 | 2024-05-08 | G2                | L   | 0.633      | -            | -                | -                | -         |    -2.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2383 | 2024-05-01 | Sashi             | L   | 0.585      | -            | -                | -                | -         |   -16.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2408 | 2024-04-30 | BetBoom           | W   | 0.578      | 0.384        | 0.257 (0.057)    | -                | -         |     4.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2416 | 2024-04-29 | PARIVISION        | W   | 0.573      | -            | -                | -                | -         |     0.91 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2463 | 2024-04-27 | Astralis          | L   | 0.559      | -            | -                | -                | -         |    -6.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2537 | 2024-04-24 | fnatic            | W   | 0.539      | 0.889        | 0.292 (0.140)    | -                | 1 (0.539) |     3.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2564 | 2024-04-23 | SAW               | W   | 0.532      | 0.889        | 0.108 (0.051)    | -                | 1 (0.532) |     1.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2574 | 2024-04-22 | ex-Guild Eagles   | W   | 0.526      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2776 | 2024-04-17 | BLEED             | W   | 0.491      | -            | -                | -                | -         |     0.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2835 | 2024-04-14 | BetBoom           | L   | 0.472      | -            | -                | -                | -         |   -11.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2849 | 2024-04-13 | ex-Preasy         | W   | 0.466      | -            | -                | -                | -         |     0.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2892 | 2024-04-11 | Passion UA        | L   | 0.452      | -            | -                | -                | -         |   -13.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2926 | 2024-04-10 | SINNERS           | L   | 0.447      | -            | -                | -                | -         |   -13.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     2978 | 2024-04-09 | SAW               | W   | 0.440      | -            | -                | -                | -         |     0.95 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3052 | 2024-04-07 | Young Ninjas      | W   | 0.426      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3125 | 2024-04-04 | Space             | W   | 0.406      | -            | -                | -                | -         |     0.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3154 | 2024-04-03 | GUN5              | W   | 0.400      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3213 | 2024-04-02 | Permitta          | W   | 0.392      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3268 | 2024-03-28 | Apeks             | W   | 0.359      | -            | -                | -                | -         |     0.18 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3399 | 2024-03-21 | fnatic            | L   | 0.313      | -            | -                | -                | -         |    -8.33 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3439 | 2024-03-19 | GUN5              | W   | 0.299      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3509 | 2024-03-15 | B8                | W   | 0.273      | -            | -                | -                | -         |     0.35 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3583 | 2024-03-13 | PARIVISION        | L   | 0.259      | -            | -                | -                | -         |    -7.86 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3801 | 2024-03-05 | FORZE             | L   | 0.207      | -            | -                | -                | -         |    -6.42 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3824 | 2024-03-04 | fnatic            | L   | 0.199      | -            | -                | -                | -         |    -5.40 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3862 | 2024-03-02 | Monte             | W   | 0.187      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3898 | 2024-02-29 | Gaimin Gladiators | W   | 0.174      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4209 | 2024-02-16 | 9 Pandas          | L   | 0.086      | -            | -                | -                | -         |    -2.65 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4233 | 2024-02-15 | Into the Breach   | W   | 0.080      | -            | -                | -                | 1 (0.080) |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4269 | 2024-02-14 | KOI               | L   | 0.074      | -            | -                | -                | -         |    -2.29 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4275 | 2024-02-14 | Falcons           | L   | 0.073      | -            | -                | -                | -         |    -1.83 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4332 | 2024-02-11 | Apeks             | L   | 0.053      | -            | -                | -                | -         |    -1.65 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4357 | 2024-02-09 | fnatic            | W   | 0.040      | -            | -                | -                | -         |     0.18 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4358 | 2024-02-09 | Endpoint          | W   | 0.040      | -            | -                | -                | -         |     0.02 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4363 | 2024-02-09 | ex-Sprout         | L   | 0.039      | -            | -                | -                | -         |    -1.23 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($165,218.54)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.898 | $10,000.00     | $8,983.33       |
| 2024-06-16 |      0.893 | $10,000.00     | $8,930.56       |
| 2024-06-09 |      0.846 | $7,000.00      | $5,924.24       |
| 2024-06-02 |      0.799 | $2,000.00      | $1,598.89       |
| 2024-05-26 |      0.753 | $2,000.00      | $1,506.11       |
| 2024-05-12 |      0.659 | $23,500.00     | $15,496.94      |
| 2024-05-02 |      0.593 | $1,500.00      | $889.58         |
| 2024-04-14 |      0.472 | $4,000.00      | $1,888.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
