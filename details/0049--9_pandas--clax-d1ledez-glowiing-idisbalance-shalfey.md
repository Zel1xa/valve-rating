### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1065.8<br />
<br />
Final Rank Value (1065.8) = Starting Rank Value (997.8) + Head To Head Adjustments (68.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.479[<sup>1</sup>](#table2)
- Bounty Collected: 0.408[<sup>2</sup>](#table1)
- Opponent Network: 0.239[<sup>2</sup>](#table1)
- LAN Wins: 0.043[<sup>2</sup>](#table1)

The average of these factors is 0.292<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 997.8
- 400 + ( ( 0.292 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 997.8


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
|           59 |        9 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.20 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |       32 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.553 (0.235)    | 0 (0.000) |    10.38 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |       45 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.93 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |       53 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.55 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      140 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.41 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      150 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.92 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      209 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.77 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      374 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.24 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |      613 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.31 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1096 | 2024-06-10 | Aurora            | L   | 0.839      | -            | -                | -                | -         |    -3.56 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1099 | 2024-06-10 | SINNERS           | W   | 0.839      | -            | -                | -                | -         |    12.17 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1104 | 2024-06-10 | 3DMAX             | L   | 0.838      | -            | -                | -                | -         |    -3.30 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1135 | 2024-06-09 | RUSH B            | L   | 0.833      | -            | -                | -                | -         |   -18.42 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1142 | 2024-06-09 | PARIVISION        | L   | 0.832      | -            | -                | -                | -         |   -12.89 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1150 | 2024-06-09 | SAW               | W   | 0.832      | 0.143        | 0.106 (0.013)    | -                | -         |    16.20 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1161 | 2024-06-09 | Monte             | W   | 0.831      | -            | -                | -                | -         |    11.06 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1419 | 2024-06-04 | Sangal            | L   | 0.800      | -            | -                | -                | -         |   -11.39 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           42 |     1641 | 2024-05-26 | MOUZ NXT          | W   | 0.740      | 0.435        | 0.139 (0.045)    | 1.000 (0.321)    | -         |    11.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1644 | 2024-05-26 | 1WIN              | W   | 0.739      | 0.435        | -                | 0.650 (0.209)    | -         |    10.14 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1658 | 2024-05-25 | Space             | W   | 0.734      | -            | -                | -                | -         |     6.50 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1684 | 2024-05-24 | SINNERS           | W   | 0.725      | 0.435        | 0.037 (0.012)    | 0.784 (0.247)    | -         |    11.51 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1813 | 2024-05-20 | BLEED             | L   | 0.699      | -            | -                | -                | -         |    -2.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     1867 | 2024-05-18 | Passion UA        | W   | 0.686      | 0.500        | 0.172 (0.059)    | 1.000 (0.343)    | -         |    10.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     1938 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.673      | 0.500        | 0.032 (0.011)    | 0.580 (0.195)    | -         |     8.86 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2098 | 2024-05-12 | BetBoom           | L   | 0.646      | -            | -                | -                | -         |    -2.26 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2124 | 2024-05-11 | RUBY              | W   | 0.640      | 0.435        | 0.095 (0.026)    | -                | -         |     8.42 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2171 | 2024-05-09 | Zero Tenacity     | W   | 0.625      | 0.435        | 0.137 (0.037)    | 1.000 (0.272)    | -         |    11.08 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2210 | 2024-05-07 | Sashi             | L   | 0.612      | -            | -                | -                | -         |    -4.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2255 | 2024-05-05 | ARCRED            | W   | 0.598      | -            | -                | -                | -         |     6.45 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2263 | 2024-05-04 | BetBoom           | L   | 0.592      | -            | -                | -                | -         |    -1.66 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2270 | 2024-05-03 | fnatic            | W   | 0.587      | 0.435        | 0.290 (0.074)    | 0.627 (0.160)    | -         |    16.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2314 | 2024-05-02 | MOUZ NXT          | W   | 0.578      | 0.435        | 0.139 (0.035)    | 1.000 (0.251)    | -         |    11.08 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2360 | 2024-04-30 | Passion UA        | L   | 0.564      | -            | -                | -                | -         |    -8.00 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2399 | 2024-04-28 | Gaimin Gladiators | W   | 0.551      | -            | -                | -                | -         |     9.79 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2437 | 2024-04-26 | Passion UA        | L   | 0.539      | -            | -                | -                | -         |    -7.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2627 | 2024-04-19 | Alliance          | L   | 0.491      | -            | -                | -                | -         |   -10.36 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2720 | 2024-04-17 | Sangal            | L   | 0.478      | -            | -                | -                | -         |    -4.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2860 | 2024-04-10 | SAW               | L   | 0.434      | -            | -                | -                | -         |    -3.54 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     2916 | 2024-04-09 | SINNERS           | L   | 0.427      | -            | -                | -                | -         |    -4.80 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     2936 | 2024-04-09 | Aurora            | L   | 0.425      | -            | -                | -                | -         |    -0.33 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     2949 | 2024-04-08 | 1WIN              | L   | 0.420      | -            | -                | -                | -         |    -8.43 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     2957 | 2024-04-08 | Metizport         | W   | 0.419      | -            | -                | -                | -         |     5.72 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3020 | 2024-04-05 | Secret            | L   | 0.399      | -            | -                | -                | -         |   -11.72 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3050 | 2024-04-04 | TSM               | W   | 0.394      | -            | -                | -                | -         |     1.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3096 | 2024-04-03 | EYEBALLERS        | W   | 0.387      | -            | -                | -                | -         |     4.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3103 | 2024-04-03 | 9INE              | W   | 0.386      | -            | -                | -                | -         |     0.76 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3134 | 2024-04-02 | Sangal            | W   | 0.380      | 0.500        | 0.219 (0.042)    | 0.823 (0.156)    | -         |     8.08 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3658 | 2024-03-06 | KOI               | L   | 0.201      | -            | -                | -                | -         |    -3.72 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3797 | 2024-03-01 | Aurora            | L   | 0.166      | -            | -                | -                | -         |    -0.12 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3804 | 2024-02-29 | FORZE             | L   | 0.160      | -            | -                | -                | -         |    -3.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3817 | 2024-02-28 | Spirit Academy    | W   | 0.154      | -            | -                | -                | -         |     0.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3822 | 2024-02-28 | Croatia           | W   | 0.153      | -            | -                | -                | -         |     0.26 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     3915 | 2024-02-24 | GamerLegion       | W   | 0.126      | -            | -                | -                | 1 (0.126) |     0.92 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     3932 | 2024-02-23 | Astralis          | W   | 0.118      | -            | -                | -                | 1 (0.118) |     3.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4080 | 2024-02-17 | AMKAL             | L   | 0.078      | -            | -                | -                | -         |    -0.74 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4103 | 2024-02-16 | 3DMAX             | W   | 0.073      | -            | -                | -                | 1 (0.073) |     2.24 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4134 | 2024-02-15 | KOI               | L   | 0.065      | -            | -                | -                | -         |    -1.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4168 | 2024-02-14 | SAW               | W   | 0.060      | -            | -                | -                | 1 (0.060) |     1.36 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4180 | 2024-02-14 | FaZe              | L   | 0.058      | -            | -                | -                | -         |    -0.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,638.80)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.833 | $5,000.00      | $4,165.16       |
| 2024-05-26 |      0.740 | $22,000.00     | $16,274.91      |
| 2024-05-12 |      0.647 | $5,000.00      | $3,233.22       |
| 2024-05-04 |      0.593 | $5,000.00      | $2,965.51       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
