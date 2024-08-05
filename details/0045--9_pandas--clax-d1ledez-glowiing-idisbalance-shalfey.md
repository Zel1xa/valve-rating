### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1099.1<br />
<br />
Final Rank Value (1099.1) = Starting Rank Value (997.0) + Head To Head Adjustments (102.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.478[<sup>1</sup>](#table2)
- Bounty Collected: 0.412[<sup>2</sup>](#table1)
- Opponent Network: 0.238[<sup>2</sup>](#table1)
- LAN Wins: 0.038[<sup>2</sup>](#table1)

The average of these factors is 0.292<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 997.0
- 400 + ( ( 0.292 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 997.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           62 |        7 | 2024-08-05 | Johnny Speeds     | W   | 1.000      | 0.143        | 0.122 (0.017)    | -                | 0 (0.000) |    22.38 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           61 |       33 | 2024-08-04 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.47 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           60 |       61 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.43 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           59 |       89 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.539 (0.230)    | 0 (0.000) |    10.51 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |      103 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.92 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |      122 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.27 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |      215 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.03 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      225 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.98 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      284 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | -         |     0.77 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      449 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | -         |     2.33 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      689 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.05 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1203 | 2024-06-10 | Aurora            | L   | 0.827      | -            | -                | -                | -         |    -3.41 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1206 | 2024-06-10 | SINNERS           | W   | 0.826      | -            | -                | -                | -         |    12.87 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1211 | 2024-06-10 | 3DMAX             | L   | 0.826      | -            | -                | -                | -         |    -3.03 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1243 | 2024-06-09 | RUSH B            | L   | 0.820      | -            | -                | -                | -         |   -17.82 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1250 | 2024-06-09 | PARIVISION        | L   | 0.820      | -            | -                | -                | -         |   -12.50 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1258 | 2024-06-09 | SAW               | W   | 0.820      | 0.143        | 0.105 (0.012)    | -                | -         |    16.11 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1269 | 2024-06-09 | Monte             | W   | 0.819      | -            | -                | -                | -         |    11.30 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1533 | 2024-06-04 | Sangal            | L   | 0.788      | -            | -                | -                | -         |   -10.24 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1757 | 2024-05-26 | MOUZ NXT          | W   | 0.728      | 0.435        | 0.139 (0.044)    | 1.000 (0.316)    | -         |    11.80 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1761 | 2024-05-26 | 1WIN              | W   | 0.727      | 0.435        | -                | 0.705 (0.223)    | -         |    10.79 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1775 | 2024-05-25 | Space             | W   | 0.721      | -            | -                | -                | -         |     6.21 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1801 | 2024-05-24 | SINNERS           | W   | 0.713      | 0.435        | 0.037 (0.012)    | 0.794 (0.246)    | -         |    12.40 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1930 | 2024-05-20 | BLEED             | L   | 0.687      | -            | -                | -                | -         |    -2.62 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1985 | 2024-05-18 | Passion UA        | W   | 0.674      | 0.500        | 0.173 (0.058)    | 1.000 (0.337)    | -         |    10.84 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     2056 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.661      | 0.500        | -                | 0.557 (0.184)    | -         |     8.84 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2216 | 2024-05-12 | BetBoom           | L   | 0.633      | -            | -                | -                | -         |    -2.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2242 | 2024-05-11 | RUBY              | W   | 0.627      | 0.435        | 0.095 (0.026)    | -                | -         |     8.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2289 | 2024-05-09 | Zero Tenacity     | W   | 0.613      | 0.435        | 0.137 (0.036)    | 1.000 (0.266)    | -         |    11.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2329 | 2024-05-07 | Sashi             | L   | 0.600      | -            | -                | -                | -         |    -4.48 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2374 | 2024-05-05 | ARCRED            | W   | 0.585      | -            | -                | -                | -         |     6.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2382 | 2024-05-04 | BetBoom           | L   | 0.580      | -            | -                | -                | -         |    -1.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2389 | 2024-05-03 | fnatic            | W   | 0.575      | 0.435        | 0.371 (0.093)    | 0.706 (0.176)    | -         |    17.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2433 | 2024-05-02 | MOUZ NXT          | W   | 0.565      | 0.435        | 0.139 (0.034)    | 1.000 (0.246)    | -         |    11.11 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2479 | 2024-04-30 | Passion UA        | L   | 0.552      | -            | -                | -                | -         |    -7.43 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2518 | 2024-04-28 | Gaimin Gladiators | W   | 0.539      | -            | -                | -                | -         |     9.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2556 | 2024-04-26 | Passion UA        | L   | 0.527      | -            | -                | -                | -         |    -7.30 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2557 | 2024-04-26 | Passion UA        | L   | 0.527      | -            | -                | -                | -         |    -6.98 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2747 | 2024-04-19 | Alliance          | L   | 0.479      | -            | -                | -                | -         |   -10.16 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2840 | 2024-04-17 | Sangal            | L   | 0.466      | -            | -                | -                | -         |    -4.43 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2980 | 2024-04-10 | SAW               | L   | 0.421      | -            | -                | -                | -         |    -3.51 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     3036 | 2024-04-09 | SINNERS           | L   | 0.415      | -            | -                | -                | -         |    -3.89 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3056 | 2024-04-09 | Aurora            | L   | 0.413      | -            | -                | -                | -         |    -0.32 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3069 | 2024-04-08 | 1WIN              | L   | 0.408      | -            | -                | -                | -         |    -7.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3077 | 2024-04-08 | Metizport         | W   | 0.407      | -            | -                | -                | -         |     4.56 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3140 | 2024-04-05 | Secret            | L   | 0.387      | -            | -                | -                | -         |   -11.37 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3170 | 2024-04-04 | TSM               | W   | 0.381      | -            | -                | -                | -         |     1.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3216 | 2024-04-03 | EYEBALLERS        | W   | 0.374      | -            | -                | -                | -         |     4.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3223 | 2024-04-03 | 9INE              | W   | 0.373      | -            | -                | -                | -         |     0.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3254 | 2024-04-02 | Sangal            | W   | 0.368      | 0.500        | 0.219 (0.040)    | 0.877 (0.161)    | -         |     7.92 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3786 | 2024-03-06 | KOI               | L   | 0.188      | -            | -                | -                | -         |    -2.26 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3925 | 2024-03-01 | Aurora            | L   | 0.154      | -            | -                | -                | -         |    -0.11 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3932 | 2024-02-29 | FORZE             | L   | 0.148      | -            | -                | -                | -         |    -3.02 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3945 | 2024-02-28 | Spirit Academy    | W   | 0.142      | -            | -                | -                | -         |     0.33 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3950 | 2024-02-28 | Croatia           | W   | 0.140      | -            | -                | -                | -         |     0.24 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4043 | 2024-02-24 | GamerLegion       | W   | 0.114      | -            | -                | -                | 1 (0.114) |     0.80 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4060 | 2024-02-23 | Astralis          | W   | 0.106      | -            | -                | -                | 1 (0.106) |     3.29 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4209 | 2024-02-17 | AMKAL             | L   | 0.066      | -            | -                | -                | -         |    -0.64 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4232 | 2024-02-16 | 3DMAX             | W   | 0.060      | -            | -                | -                | 1 (0.060) |     1.86 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4263 | 2024-02-15 | KOI               | L   | 0.053      | -            | -                | -                | -         |    -0.63 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4297 | 2024-02-14 | SAW               | W   | 0.048      | -            | -                | -                | 1 (0.048) |     1.07 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4309 | 2024-02-14 | FaZe              | L   | 0.046      | -            | -                | -                | -         |    -0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,184.86)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.821 | $5,000.00      | $4,103.82       |
| 2024-05-26 |      0.728 | $22,000.00     | $16,005.00      |
| 2024-05-12 |      0.634 | $5,000.00      | $3,171.88       |
| 2024-05-04 |      0.581 | $5,000.00      | $2,904.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
