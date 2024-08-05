### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [51](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1054.1<br />
<br />
Final Rank Value (1054.1) = Starting Rank Value (1008.2) + Head To Head Adjustments (46.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.480[<sup>1</sup>](#table2)
- Bounty Collected: 0.414[<sup>2</sup>](#table1)
- Opponent Network: 0.233[<sup>2</sup>](#table1)
- LAN Wins: 0.052[<sup>2</sup>](#table1)

The average of these factors is 0.295<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1008.2
- 400 + ( ( 0.295 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1008.2


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
|           56 |       49 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.65 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |       59 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.19 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      118 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.75 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      283 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.08 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      523 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.25 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1037 | 2024-06-10 | Aurora            | L   | 0.858      | -            | -                | -                | -         |    -3.63 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1040 | 2024-06-10 | SINNERS           | W   | 0.858      | -            | -                | -                | 0 (0.000) |    11.90 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1045 | 2024-06-10 | 3DMAX             | L   | 0.857      | -            | -                | -                | -         |    -3.32 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1077 | 2024-06-09 | RUSH B            | L   | 0.852      | -            | -                | -                | -         |   -18.99 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1084 | 2024-06-09 | PARIVISION        | L   | 0.851      | -            | -                | -                | -         |   -13.44 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1092 | 2024-06-09 | SAW               | W   | 0.851      | 0.143        | 0.107 (0.013)    | -                | 0 (0.000) |    16.98 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1103 | 2024-06-09 | Monte             | W   | 0.850      | -            | -                | -                | 0 (0.000) |    11.68 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1367 | 2024-06-04 | Sangal            | L   | 0.819      | -            | -                | -                | -         |   -11.16 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1591 | 2024-05-26 | MOUZ NXT          | W   | 0.759      | 0.435        | 0.140 (0.046)    | 1.000 (0.330)    | -         |    12.01 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1595 | 2024-05-26 | 1WIN              | W   | 0.758      | 0.435        | -                | 0.630 (0.207)    | -         |    10.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1609 | 2024-05-25 | Space             | W   | 0.753      | -            | -                | -                | -         |     6.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1635 | 2024-05-24 | SINNERS           | W   | 0.744      | 0.435        | 0.038 (0.012)    | 0.721 (0.233)    | -         |    10.82 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1764 | 2024-05-20 | BLEED             | L   | 0.719      | -            | -                | -                | -         |    -2.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1819 | 2024-05-18 | Passion UA        | W   | 0.705      | 0.500        | 0.171 (0.060)    | 1.000 (0.353)    | -         |    10.86 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     1890 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.692      | 0.500        | -                | 0.564 (0.195)    | -         |     9.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2050 | 2024-05-12 | BetBoom           | L   | 0.665      | -            | -                | -                | -         |    -2.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2076 | 2024-05-11 | RUBY              | W   | 0.659      | 0.435        | 0.096 (0.027)    | 0.506 (0.145)    | -         |     8.66 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2123 | 2024-05-09 | Zero Tenacity     | W   | 0.644      | 0.435        | 0.138 (0.039)    | 1.000 (0.280)    | -         |    11.40 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2163 | 2024-05-07 | Sashi             | L   | 0.631      | -            | -                | -                | -         |    -4.67 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2208 | 2024-05-05 | ARCRED            | W   | 0.617      | -            | -                | -                | -         |     6.36 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2216 | 2024-05-04 | BetBoom           | L   | 0.611      | -            | -                | -                | -         |    -1.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2223 | 2024-05-03 | fnatic            | W   | 0.606      | 0.435        | 0.371 (0.098)    | 0.633 (0.167)    | -         |    18.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2267 | 2024-05-02 | MOUZ NXT          | W   | 0.597      | 0.435        | 0.140 (0.036)    | 1.000 (0.259)    | -         |    11.52 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2313 | 2024-04-30 | Passion UA        | L   | 0.584      | -            | -                | -                | -         |    -8.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2352 | 2024-04-28 | Gaimin Gladiators | W   | 0.570      | 0.500        | 0.040 (0.011)    | -                | -         |    10.48 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2390 | 2024-04-26 | Passion UA        | L   | 0.559      | -            | -                | -                | -         |    -8.11 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2391 | 2024-04-26 | Passion UA        | L   | 0.559      | -            | -                | -                | -         |    -7.72 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2581 | 2024-04-19 | Alliance          | L   | 0.510      | -            | -                | -                | -         |   -10.99 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2674 | 2024-04-17 | Sangal            | L   | 0.497      | -            | -                | -                | -         |    -5.10 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2814 | 2024-04-10 | SAW               | L   | 0.453      | -            | -                | -                | -         |    -3.62 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     2870 | 2024-04-09 | SINNERS           | L   | 0.446      | -            | -                | -                | -         |    -6.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     2890 | 2024-04-09 | Aurora            | L   | 0.444      | -            | -                | -                | -         |    -0.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     2903 | 2024-04-08 | 1WIN              | L   | 0.439      | -            | -                | -                | -         |    -9.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     2911 | 2024-04-08 | Metizport         | W   | 0.438      | -            | -                | -                | -         |     5.92 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     2974 | 2024-04-05 | Secret            | L   | 0.418      | -            | -                | -                | -         |   -12.33 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3004 | 2024-04-04 | TSM               | W   | 0.413      | -            | -                | -                | -         |     1.68 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3050 | 2024-04-03 | EYEBALLERS        | W   | 0.406      | -            | -                | -                | -         |     4.45 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3057 | 2024-04-03 | 9INE              | W   | 0.405      | -            | -                | -                | -         |     0.74 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3088 | 2024-04-02 | Sangal            | W   | 0.399      | 0.500        | 0.219 (0.044)    | 0.824 (0.164)    | -         |     8.21 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3620 | 2024-03-06 | KOI               | L   | 0.220      | -            | -                | -                | -         |    -2.58 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3759 | 2024-03-01 | Aurora            | L   | 0.185      | -            | -                | -                | -         |    -0.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3766 | 2024-02-29 | FORZE             | L   | 0.179      | -            | -                | -                | -         |    -3.64 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3779 | 2024-02-28 | Spirit Academy    | W   | 0.173      | -            | -                | -                | -         |     0.38 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3784 | 2024-02-28 | Croatia           | W   | 0.172      | -            | -                | -                | -         |     0.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     3877 | 2024-02-24 | GamerLegion       | W   | 0.145      | -            | -                | -                | 1 (0.145) |     1.09 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     3894 | 2024-02-23 | Astralis          | W   | 0.137      | -            | -                | -                | 1 (0.137) |     4.24 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4043 | 2024-02-17 | AMKAL             | L   | 0.097      | -            | -                | -                | -         |    -0.94 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4066 | 2024-02-16 | 3DMAX             | W   | 0.092      | -            | -                | -                | 1 (0.092) |     2.82 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4097 | 2024-02-15 | KOI               | L   | 0.084      | -            | -                | -                | -         |    -0.98 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4131 | 2024-02-14 | SAW               | W   | 0.079      | -            | -                | -                | 1 (0.079) |     1.80 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4143 | 2024-02-14 | FaZe              | L   | 0.077      | -            | -                | -                | -         |    -0.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,342.31)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.852 | $5,000.00      | $4,260.23       |
| 2024-05-26 |      0.759 | $22,000.00     | $16,693.21      |
| 2024-05-12 |      0.666 | $5,000.00      | $3,328.29       |
| 2024-05-04 |      0.612 | $5,000.00      | $3,060.58       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
