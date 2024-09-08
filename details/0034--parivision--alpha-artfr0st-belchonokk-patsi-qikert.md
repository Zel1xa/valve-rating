### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1116.2<br />
<br />
Final Rank Value (1116.2) = Starting Rank Value (1084.2) + Head To Head Adjustments (32.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.427[<sup>1</sup>](#table2)
- Bounty Collected: 0.480[<sup>2</sup>](#table1)
- Opponent Network: 0.319[<sup>2</sup>](#table1)
- LAN Wins: 0.187[<sup>2</sup>](#table1)

The average of these factors is 0.353<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1084.2
- 400 + ( ( 0.353 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1084.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           70 |      128 | 2024-09-04 | Monte             | W   | 1.000      | 0.384        | -                | 0.697 (0.268)    | 0 (0.000) |    13.02 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           69 |      286 | 2024-08-29 | AMKAL             | W   | 1.000      | 0.384        | 0.123 (0.047)    | -                | 0 (0.000) |    11.80 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           68 |      398 | 2024-08-27 | Gaimin Gladiators | L   | 1.000      | -            | -                | -                | -         |   -25.24 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           67 |      499 | 2024-08-25 | Monte Gen         | L   | 1.000      | -            | -                | -                | -         |   -25.50 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           66 |      559 | 2024-08-23 | GamerLegion       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.95 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           65 |      594 | 2024-08-22 | B8                | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.69 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           64 |      627 | 2024-08-21 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |   -16.25 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           63 |      648 | 2024-08-21 | Enterprise        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.06 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           62 |      689 | 2024-08-20 | 9 Pandas          | W   | 1.000      | 0.500        | 0.059 (0.029)    | 0.732 (0.366)    | 0 (0.000) |    15.80 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           61 |      720 | 2024-08-19 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -4.42 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           60 |      815 | 2024-08-15 | OG                | L   | 1.000      | -            | -                | -                | -         |   -22.00 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           59 |      820 | 2024-08-15 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.97 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           58 |      833 | 2024-08-15 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           57 |      871 | 2024-08-13 | RUSH B            | W   | 1.000      | -            | -                | -                | -         |     8.44 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           56 |      917 | 2024-08-12 | Monte             | W   | 1.000      | 0.500        | -                | 0.697 (0.349)    | -         |    11.65 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           55 |     1003 | 2024-08-09 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -3.63 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           54 |     1082 | 2024-08-07 | SINNERS           | W   | 0.986      | -            | -                | -                | -         |    11.76 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           53 |     1113 | 2024-08-06 | Sangal            | L   | 0.981      | -            | -                | -                | -         |    -6.08 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |     1127 | 2024-08-06 | Aurora Young Blud | W   | 0.979      | 0.435        | -                | 0.711 (0.302)    | -         |    11.32 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |     1147 | 2024-08-05 | ENCE              | W   | 0.973      | 0.435        | 0.130 (0.055)    | -                | -         |    21.21 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |     1164 | 2024-08-04 | Betera            | L   | 0.968      | -            | -                | -                | -         |   -28.20 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |     1203 | 2024-08-03 | GUN5              | L   | 0.961      | -            | -                | -                | -         |   -23.30 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |     1218 | 2024-08-03 | CYBERSHOKE        | W   | 0.959      | 0.435        | -                | 0.702 (0.293)    | -         |     8.49 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |     1229 | 2024-08-02 | TSM               | W   | 0.955      | 0.500        | 0.058 (0.028)    | 0.900 (0.430)    | -         |    10.98 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |     1270 | 2024-08-01 | 9 Pandas          | W   | 0.948      | 0.500        | 0.059 (0.028)    | 0.732 (0.347)    | -         |    13.23 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |     1385 | 2024-07-30 | Permitta          | W   | 0.932      | -            | -                | -                | -         |     8.52 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |     1485 | 2024-07-26 | BLEED             | L   | 0.907      | -            | -                | -                | -         |    -9.31 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1498 | 2024-07-26 | True Rippers      | W   | 0.906      | -            | -                | -                | 1 (0.906) |     2.75 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1530 | 2024-07-25 | ENCE              | L   | 0.900      | -            | -                | -                | -         |    -8.97 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1568 | 2024-07-24 | The MongolZ       | W   | 0.893      | 0.650        | 0.864 (0.502)    | 0.695 (0.403)    | 1 (0.893) |    27.48 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1575 | 2024-07-24 | Aurora            | L   | 0.892      | -            | -                | -                | -         |    -4.76 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     2250 | 2024-06-14 | Permitta          | L   | 0.626      | -            | -                | -                | -         |   -14.11 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     2351 | 2024-06-10 | RUSH B            | W   | 0.600      | -            | -                | -                | -         |     5.28 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     2357 | 2024-06-10 | 3DMAX             | L   | 0.600      | -            | -                | -                | -         |    -1.32 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     2363 | 2024-06-10 | SINNERS           | L   | 0.599      | -            | -                | -                | -         |    -9.88 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     2394 | 2024-06-09 | Aurora            | L   | 0.594      | -            | -                | -                | -         |    -3.97 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     2400 | 2024-06-09 | 9 Pandas          | W   | 0.593      | -            | -                | -                | -         |     9.15 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     2411 | 2024-06-09 | Monte             | W   | 0.593      | -            | -                | -                | -         |     6.70 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           32 |     2413 | 2024-06-09 | SAW               | L   | 0.593      | -            | -                | -                | -         |    -2.03 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           31 |     2633 | 2024-06-05 | Aurora            | L   | 0.568      | -            | -                | -                | -         |    -3.00 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           30 |     2680 | 2024-06-04 | Monte             | W   | 0.561      | -            | -                | -                | -         |     6.63 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           29 |     3085 | 2024-05-20 | Sangal            | L   | 0.460      | -            | -                | -                | -         |    -3.72 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     3164 | 2024-05-17 | Zero Tenacity     | W   | 0.441      | 0.500        | 0.163 (0.036)    | 1.000 (0.221)    | -         |     6.68 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     3195 | 2024-05-16 | Aurora            | L   | 0.435      | -            | -                | -                | -         |    -2.17 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     3211 | 2024-05-16 | Eternal Fire      | L   | 0.433      | -            | -                | -                | -         |    -0.18 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     3250 | 2024-05-15 | B8                | W   | 0.428      | 0.500        | 0.176 (0.038)    | 1.000 (0.214)    | -         |     6.90 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     3435 | 2024-05-09 | Endpoint          | L   | 0.387      | -            | -                | -                | -         |    -6.84 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     3592 | 2024-05-01 | Passion UA        | L   | 0.334      | -            | -                | -                | -         |    -6.17 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     3608 | 2024-05-01 | fnatic            | L   | 0.332      | -            | -                | -                | -         |    -2.17 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     3634 | 2024-04-29 | 3DMAX             | L   | 0.321      | -            | -                | -                | -         |    -0.30 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     3643 | 2024-04-29 | Zero Tenacity     | W   | 0.320      | 0.500        | 0.163 (0.026)    | -                | -         |     4.71 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     3679 | 2024-04-27 | Sangal            | W   | 0.307      | 0.500        | 0.248 (0.038)    | -                | -         |     7.55 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     3709 | 2024-04-26 | SINNERS           | W   | 0.300      | -            | -                | -                | -         |     5.60 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     3738 | 2024-04-25 | ex-Guild Eagles   | W   | 0.294      | -            | -                | -                | -         |     1.47 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     3757 | 2024-04-24 | MOUZ NXT          | W   | 0.287      | -            | -                | -                | -         |     3.58 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     3809 | 2024-04-21 | Nexus             | W   | 0.267      | -            | -                | -                | -         |     1.68 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           14 |     3812 | 2024-04-21 | B8                | L   | 0.266      | -            | -                | -                | -         |    -4.37 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           13 |     3868 | 2024-04-19 | Zero Tenacity     | L   | 0.255      | -            | -                | -                | -         |    -4.16 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           12 |     3967 | 2024-04-17 | HAVU              | W   | 0.241      | -            | -                | -                | -         |     0.43 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           11 |     3970 | 2024-04-17 | Permitta          | L   | 0.240      | -            | -                | -                | -         |    -5.02 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           10 |     4094 | 2024-04-11 | 500               | L   | 0.201      | -            | -                | -                | -         |    -5.77 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|            9 |     4129 | 2024-04-10 | Aurora            | L   | 0.195      | -            | -                | -                | -         |    -0.84 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     4189 | 2024-04-09 | RUSH B            | L   | 0.188      | -            | -                | -                | -         |    -4.64 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     4358 | 2024-04-03 | MOUZ NXT          | L   | 0.148      | -            | -                | -                | -         |    -3.01 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     4370 | 2024-04-03 | Space             | W   | 0.147      | -            | -                | -                | -         |     0.82 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     4406 | 2024-04-02 | AMKAL             | L   | 0.141      | -            | -                | -                | -         |    -2.16 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     4413 | 2024-04-02 | Insilio           | L   | 0.140      | -            | -                | -                | -         |    -3.27 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     4425 | 2024-04-01 | Metizport         | W   | 0.134      | -            | -                | -                | -         |     0.55 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     4591 | 2024-03-21 | FORZE             | W   | 0.061      | -            | -                | -                | -         |     0.31 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     4773 | 2024-03-13 | 3DMAX             | W   | 0.007      | -            | -                | -                | -         |     0.22 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,841.77)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      0.981 | $10,000.00     | $9,809.72       |
| 2024-06-09 |      0.594 | $6,500.00      | $3,861.63       |
| 2024-05-02 |      0.341 | $500.00        | $170.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
