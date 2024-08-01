### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [51](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1041.2<br />
<br />
Final Rank Value (1041.2) = Starting Rank Value (1002.8) + Head To Head Adjustments (38.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.480[<sup>1</sup>](#table2)
- Bounty Collected: 0.410[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.049[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1002.8
- 400 + ( ( 0.293 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1002.8


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
|           56 |        0 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.40 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |       84 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.58 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |       94 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.81 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      153 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.75 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      318 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.20 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |      567 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.36 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1080 | 2024-06-10 | Aurora            | L   | 0.852      | -            | -                | -                | -         |    -3.66 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1083 | 2024-06-10 | SINNERS           | W   | 0.852      | -            | -                | -                | 0 (0.000) |    12.21 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1088 | 2024-06-10 | 3DMAX             | L   | 0.851      | -            | -                | -                | -         |    -3.39 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1120 | 2024-06-09 | RUSH B            | L   | 0.846      | -            | -                | -                | -         |   -18.86 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1127 | 2024-06-09 | PARIVISION        | L   | 0.845      | -            | -                | -                | -         |   -12.94 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1135 | 2024-06-09 | SAW               | W   | 0.845      | 0.143        | 0.108 (0.013)    | -                | 0 (0.000) |    16.60 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1147 | 2024-06-09 | Monte             | W   | 0.844      | -            | -                | -                | 0 (0.000) |    11.24 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1424 | 2024-06-04 | Sangal            | L   | 0.813      | -            | -                | -                | -         |   -11.68 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           42 |     1651 | 2024-05-26 | MOUZ NXT          | W   | 0.753      | 0.435        | 0.141 (0.046)    | 1.000 (0.327)    | -         |    11.81 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1655 | 2024-05-26 | 1WIN              | W   | 0.752      | 0.435        | -                | 0.629 (0.206)    | -         |    10.26 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1669 | 2024-05-25 | Space             | W   | 0.747      | -            | -                | -                | -         |     6.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1695 | 2024-05-24 | SINNERS           | W   | 0.738      | 0.435        | 0.038 (0.012)    | 0.768 (0.246)    | -         |    11.54 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1842 | 2024-05-20 | BLEED             | L   | 0.713      | -            | -                | -                | -         |    -2.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     1904 | 2024-05-18 | Passion UA        | W   | 0.699      | 0.500        | 0.173 (0.060)    | 1.000 (0.350)    | -         |    10.80 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     1976 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.686      | 0.500        | -                | 0.563 (0.193)    | -         |     8.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2145 | 2024-05-12 | BetBoom           | L   | 0.659      | -            | -                | -                | -         |    -2.26 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2171 | 2024-05-11 | RUBY              | W   | 0.653      | 0.435        | 0.097 (0.027)    | 0.544 (0.154)    | -         |     8.70 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2218 | 2024-05-09 | Zero Tenacity     | W   | 0.638      | 0.435        | 0.139 (0.038)    | 1.000 (0.277)    | -         |    11.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2260 | 2024-05-07 | Sashi             | L   | 0.625      | -            | -                | -                | -         |    -4.74 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2305 | 2024-05-05 | ARCRED            | W   | 0.611      | -            | -                | -                | -         |     6.30 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2313 | 2024-05-04 | BetBoom           | L   | 0.605      | -            | -                | -                | -         |    -1.66 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2320 | 2024-05-03 | fnatic            | W   | 0.600      | 0.435        | 0.292 (0.076)    | 0.568 (0.148)    | -         |    16.54 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2365 | 2024-05-02 | MOUZ NXT          | W   | 0.591      | 0.435        | 0.141 (0.036)    | 1.000 (0.257)    | -         |    11.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2413 | 2024-04-30 | Passion UA        | L   | 0.578      | -            | -                | -                | -         |    -8.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2452 | 2024-04-28 | Gaimin Gladiators | W   | 0.564      | 0.500        | 0.040 (0.011)    | -                | -         |    10.23 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2491 | 2024-04-26 | Passion UA        | L   | 0.552      | -            | -                | -                | -         |    -7.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2688 | 2024-04-19 | Alliance          | L   | 0.504      | -            | -                | -                | -         |   -10.70 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2783 | 2024-04-17 | Sangal            | L   | 0.491      | -            | -                | -                | -         |    -4.95 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2925 | 2024-04-10 | SAW               | L   | 0.447      | -            | -                | -                | -         |    -3.54 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     2981 | 2024-04-09 | SINNERS           | L   | 0.440      | -            | -                | -                | -         |    -5.63 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3001 | 2024-04-09 | Aurora            | L   | 0.438      | -            | -                | -                | -         |    -0.33 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3014 | 2024-04-08 | 1WIN              | L   | 0.433      | -            | -                | -                | -         |    -8.76 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3022 | 2024-04-08 | Metizport         | W   | 0.432      | -            | -                | -                | -         |     5.85 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3085 | 2024-04-05 | Secret            | L   | 0.412      | -            | -                | -                | -         |   -12.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3115 | 2024-04-04 | TSM               | W   | 0.407      | -            | -                | -                | -         |     1.69 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3163 | 2024-04-03 | EYEBALLERS        | W   | 0.400      | -            | -                | -                | -         |     4.47 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3174 | 2024-04-03 | 9INE              | W   | 0.399      | -            | -                | -                | -         |     0.76 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3207 | 2024-04-02 | Sangal            | W   | 0.393      | 0.500        | 0.221 (0.043)    | 0.823 (0.162)    | -         |     8.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3750 | 2024-03-06 | KOI               | L   | 0.214      | -            | -                | -                | -         |    -3.95 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3895 | 2024-03-01 | Aurora            | L   | 0.179      | -            | -                | -                | -         |    -0.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3902 | 2024-02-29 | FORZE             | L   | 0.173      | -            | -                | -                | -         |    -3.50 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3915 | 2024-02-28 | Spirit Academy    | W   | 0.167      | -            | -                | -                | -         |     0.38 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3921 | 2024-02-28 | Croatia           | W   | 0.166      | -            | -                | -                | -         |     0.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4018 | 2024-02-24 | GamerLegion       | W   | 0.139      | -            | -                | -                | 1 (0.139) |     1.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4037 | 2024-02-23 | Astralis          | W   | 0.131      | -            | -                | -                | 1 (0.131) |     4.05 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4187 | 2024-02-17 | AMKAL             | L   | 0.091      | -            | -                | -                | -         |    -0.88 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4211 | 2024-02-16 | 3DMAX             | W   | 0.086      | -            | -                | -                | 1 (0.086) |     2.64 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4242 | 2024-02-15 | KOI               | L   | 0.078      | -            | -                | -                | -         |    -1.46 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4276 | 2024-02-14 | SAW               | W   | 0.073      | -            | -                | -                | 1 (0.073) |     1.67 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4288 | 2024-02-14 | FaZe              | L   | 0.071      | -            | -                | -                | -         |    -0.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,120.14)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $5,000.00      | $4,230.21       |
| 2024-05-26 |      0.753 | $22,000.00     | $16,561.11      |
| 2024-05-12 |      0.660 | $5,000.00      | $3,298.26       |
| 2024-05-04 |      0.606 | $5,000.00      | $3,030.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
