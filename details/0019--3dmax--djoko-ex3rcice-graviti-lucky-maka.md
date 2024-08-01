### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1415.4<br />
<br />
Final Rank Value (1415.4) = Starting Rank Value (1694.6) + Head To Head Adjustments (-279.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.771[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.356[<sup>2</sup>](#table1)
- LAN Wins: 0.825[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1694.6
- 400 + ( ( 0.629 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1694.6


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
|           79 |       30 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           78 |      151 | 2024-07-28 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.719 (0.468)    | 1 (1.000) |    26.63 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           77 |      165 | 2024-07-28 | Aurora            | W   | 1.000      | 0.650        | 0.432 (0.281)    | 0.798 (0.519)    | 1 (1.000) |    18.72 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           76 |      179 | 2024-07-27 | ENCE              | W   | 1.000      | 0.650        | 0.174 (0.113)    | -                | 1 (1.000) |    15.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           75 |      205 | 2024-07-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -5.53 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           74 |      245 | 2024-07-25 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           73 |      257 | 2024-07-25 | DMS               | W   | 1.000      | 0.650        | -                | 0.447 (0.291)    | 1 (1.000) |     2.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           72 |      285 | 2024-07-24 | AMKAL             | W   | 1.000      | 0.650        | 0.132 (0.086)    | 0.482 (0.314)    | 1 (1.000) |     9.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           71 |      558 | 2024-07-17 | 9 Pandas          | W   | 1.000      | 0.500        | -                | 0.578 (0.289)    | -         |     5.38 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           70 |      669 | 2024-07-15 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -26.87 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           69 |      798 | 2024-07-08 | Latvia            | L   | 1.000      | -            | -                | -                | -         |   -29.88 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           68 |      881 | 2024-06-17 | 5W                | L   | 0.900      | -            | -                | -                | -         |   -25.51 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           67 |      893 | 2024-06-16 | B8                | L   | 0.894      | -            | -                | -                | -         |   -23.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           66 |      897 | 2024-06-16 | Permitta          | W   | 0.894      | 0.435        | -                | 0.801 (0.311)    | -         |     1.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           65 |      903 | 2024-06-16 | Enterprise        | W   | 0.893      | -            | -                | -                | -         |     1.59 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           64 |      916 | 2024-06-15 | GUN5              | W   | 0.888      | -            | -                | -                | -         |     2.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           63 |      935 | 2024-06-15 | BLEED             | W   | 0.886      | -            | -                | -                | -         |    11.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           62 |      963 | 2024-06-14 | Sashi             | W   | 0.880      | -            | -                | -                | -         |     6.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           61 |      974 | 2024-06-14 | Passion UA        | W   | 0.879      | 0.435        | 0.172 (0.066)    | 1.000 (0.382)    | -         |     3.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           60 |      992 | 2024-06-13 | 9INE              | W   | 0.874      | -            | -                | -                | -         |     2.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           59 |     1004 | 2024-06-13 | VP.Prodigy        | W   | 0.873      | -            | -                | -                | -         |     1.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           58 |     1036 | 2024-06-11 | SINNERS           | W   | 0.862      | -            | -                | -                | -         |     2.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           57 |     1047 | 2024-06-11 | BUHAWI            | W   | 0.861      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           56 |     1064 | 2024-06-10 | EYEBALLERS        | W   | 0.854      | -            | -                | -                | -         |     1.43 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           55 |     1071 | 2024-06-10 | SAW               | W   | 0.854      | -            | -                | -                | -         |     5.71 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           54 |     1078 | 2024-06-10 | PARIVISION        | W   | 0.853      | -            | -                | -                | -         |     3.69 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           53 |     1082 | 2024-06-10 | 9 Pandas          | W   | 0.853      | -            | -                | -                | -         |     3.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           52 |     1104 | 2024-06-09 | 9INE              | L   | 0.848      | -            | -                | -                | -         |   -24.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           51 |     1117 | 2024-06-09 | Monte             | L   | 0.847      | -            | -                | -                | -         |   -24.63 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           50 |     1124 | 2024-06-09 | SINNERS           | L   | 0.847      | -            | -                | -                | -         |   -24.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           49 |     1131 | 2024-06-09 | Aurora            | W   | 0.847      | 0.143        | 0.432 (0.052)    | -                | -         |    13.26 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           48 |     1142 | 2024-06-09 | RUSH B            | W   | 0.846      | -            | -                | -                | -         |     0.89 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           47 |     1181 | 2024-06-08 | Illuminar         | L   | 0.841      | -            | -                | -                | -         |   -25.55 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           46 |     1246 | 2024-06-07 | Gaimin Gladiators | W   | 0.834      | -            | -                | -                | -         |     1.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           45 |     1287 | 2024-06-06 | Nexus             | W   | 0.829      | -            | -                | -                | -         |     0.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           44 |     1304 | 2024-06-06 | Sangal            | L   | 0.828      | -            | -                | -                | -         |   -23.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           43 |     1370 | 2024-06-05 | KOI               | L   | 0.821      | -            | -                | -                | -         |   -24.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           42 |     1416 | 2024-06-04 | Aurora            | W   | 0.815      | 0.500        | 0.432 (0.176)    | 0.798 (0.325)    | -         |    12.73 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           41 |     1501 | 2024-06-01 | VP.Prodigy        | L   | 0.794      | -            | -                | -                | -         |   -24.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           40 |     1554 | 2024-05-30 | Sampi             | W   | 0.782      | 0.435        | -                | 1.000 (0.340)    | -         |     0.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           39 |     1678 | 2024-05-25 | MOUZ NXT          | L   | 0.746      | -            | -                | -                | -         |   -22.25 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           38 |     1701 | 2024-05-23 | Zero Tenacity     | W   | 0.734      | 0.435        | -                | 1.000 (0.319)    | -         |     1.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           37 |     1941 | 2024-05-17 | B8                | L   | 0.693      | -            | -                | -                | -         |   -20.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           36 |     2031 | 2024-05-15 | Zero Tenacity     | L   | 0.680      | -            | -                | -                | -         |   -20.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           35 |     2234 | 2024-05-08 | G2                | L   | 0.634      | -            | -                | -                | -         |    -2.63 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           34 |     2379 | 2024-05-01 | Sashi             | L   | 0.586      | -            | -                | -                | -         |   -16.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           33 |     2404 | 2024-04-30 | BetBoom           | W   | 0.580      | 0.384        | 0.257 (0.057)    | -                | -         |     4.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           32 |     2412 | 2024-04-29 | PARIVISION        | W   | 0.575      | -            | -                | -                | -         |     0.92 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           31 |     2459 | 2024-04-27 | Astralis          | L   | 0.561      | -            | -                | -                | -         |    -6.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           30 |     2533 | 2024-04-24 | fnatic            | W   | 0.541      | 0.889        | 0.292 (0.140)    | -                | 1 (0.541) |     3.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           29 |     2560 | 2024-04-23 | SAW               | W   | 0.533      | 0.889        | 0.108 (0.051)    | -                | 1 (0.533) |     1.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           28 |     2570 | 2024-04-22 | ex-Guild Eagles   | W   | 0.528      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           27 |     2772 | 2024-04-17 | BLEED             | W   | 0.493      | -            | -                | -                | -         |     0.50 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           26 |     2831 | 2024-04-14 | BetBoom           | L   | 0.474      | -            | -                | -                | -         |   -11.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           25 |     2845 | 2024-04-13 | ex-Preasy         | W   | 0.467      | -            | -                | -                | -         |     0.17 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           24 |     2888 | 2024-04-11 | Passion UA        | L   | 0.454      | -            | -                | -                | -         |   -13.79 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           23 |     2922 | 2024-04-10 | SINNERS           | L   | 0.448      | -            | -                | -                | -         |   -13.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           22 |     2974 | 2024-04-09 | SAW               | W   | 0.442      | -            | -                | -                | -         |     0.95 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           21 |     3048 | 2024-04-07 | Young Ninjas      | W   | 0.427      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           20 |     3121 | 2024-04-04 | Space             | W   | 0.407      | -            | -                | -                | -         |     0.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           19 |     3150 | 2024-04-03 | GUN5              | W   | 0.402      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           18 |     3209 | 2024-04-02 | Permitta          | W   | 0.394      | -            | -                | -                | -         |     0.23 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           17 |     3264 | 2024-03-28 | Apeks             | W   | 0.361      | -            | -                | -                | -         |     0.18 | Djoko, Ex3rcice, Graviti, Lucky, Maka  |
|           16 |     3395 | 2024-03-21 | fnatic            | L   | 0.314      | -            | -                | -                | -         |    -8.37 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           15 |     3435 | 2024-03-19 | GUN5              | W   | 0.300      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Lucky, Maka, NBK-     |
|           14 |     3505 | 2024-03-15 | B8                | W   | 0.274      | -            | -                | -                | -         |     0.35 | Djoko, Ex3rcice, Lucky, Maka, misutaaa |
|           13 |     3579 | 2024-03-13 | PARIVISION        | L   | 0.261      | -            | -                | -                | -         |    -7.90 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           12 |     3797 | 2024-03-05 | FORZE             | L   | 0.208      | -            | -                | -                | -         |    -6.46 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           11 |     3820 | 2024-03-04 | fnatic            | L   | 0.200      | -            | -                | -                | -         |    -5.43 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|           10 |     3858 | 2024-03-02 | Monte             | W   | 0.189      | -            | -                | -                | -         |     0.14 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            9 |     3894 | 2024-02-29 | Gaimin Gladiators | W   | 0.175      | -            | -                | -                | -         |     0.11 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            8 |     4205 | 2024-02-16 | 9 Pandas          | L   | 0.087      | -            | -                | -                | -         |    -2.69 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            7 |     4229 | 2024-02-15 | Into the Breach   | W   | 0.081      | -            | -                | -                | 1 (0.081) |     0.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            6 |     4265 | 2024-02-14 | KOI               | L   | 0.075      | -            | -                | -                | -         |    -2.33 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            5 |     4271 | 2024-02-14 | Falcons           | L   | 0.074      | -            | -                | -                | -         |    -1.87 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            4 |     4328 | 2024-02-11 | Apeks             | L   | 0.055      | -            | -                | -                | -         |    -1.70 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            3 |     4353 | 2024-02-09 | fnatic            | W   | 0.042      | -            | -                | -                | -         |     0.19 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            2 |     4354 | 2024-02-09 | Endpoint          | W   | 0.041      | -            | -                | -                | -         |     0.02 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |
|            1 |     4359 | 2024-02-09 | ex-Sprout         | L   | 0.041      | -            | -                | -                | -         |    -1.27 | Djoko, Ex3rcice, hAdji, Lucky, Maka    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($165,301.87)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $120,000.00    | $120,000.00     |
| 2024-06-17 |      0.900 | $10,000.00     | $8,997.22       |
| 2024-06-16 |      0.894 | $10,000.00     | $8,944.44       |
| 2024-06-09 |      0.848 | $7,000.00      | $5,933.96       |
| 2024-06-02 |      0.801 | $2,000.00      | $1,601.67       |
| 2024-05-26 |      0.754 | $2,000.00      | $1,508.89       |
| 2024-05-12 |      0.661 | $23,500.00     | $15,529.58      |
| 2024-05-02 |      0.594 | $1,500.00      | $891.67         |
| 2024-04-14 |      0.474 | $4,000.00      | $1,894.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
