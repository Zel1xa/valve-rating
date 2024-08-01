### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1052.3<br />
<br />
Final Rank Value (1052.3) = Starting Rank Value (1002.4) + Head To Head Adjustments (49.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.481[<sup>1</sup>](#table2)
- Bounty Collected: 0.410[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.050[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1002.4
- 400 + ( ( 0.293 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1002.4


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
|           55 |       81 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.50 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |       91 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.90 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      151 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.76 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      316 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.11 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |      562 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.36 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1078 | 2024-06-10 | Aurora            | L   | 0.852      | -            | -                | -                | -         |    -3.67 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1081 | 2024-06-10 | SINNERS           | W   | 0.852      | -            | -                | -                | 0 (0.000) |    12.22 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1086 | 2024-06-10 | 3DMAX             | L   | 0.851      | -            | -                | -                | -         |    -3.39 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1118 | 2024-06-09 | RUSH B            | L   | 0.846      | -            | -                | -                | -         |   -18.86 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1125 | 2024-06-09 | PARIVISION        | L   | 0.846      | -            | -                | -                | -         |   -13.11 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1133 | 2024-06-09 | SAW               | W   | 0.845      | 0.143        | 0.108 (0.013)    | -                | 0 (0.000) |    16.61 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1145 | 2024-06-09 | Monte             | W   | 0.845      | -            | -                | -                | 0 (0.000) |    11.24 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1422 | 2024-06-04 | Sangal            | L   | 0.813      | -            | -                | -                | -         |   -11.69 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           42 |     1649 | 2024-05-26 | MOUZ NXT          | W   | 0.753      | 0.435        | 0.141 (0.046)    | 1.000 (0.327)    | -         |    11.82 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1653 | 2024-05-26 | 1WIN              | W   | 0.752      | 0.435        | -                | 0.629 (0.206)    | -         |    10.27 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1667 | 2024-05-25 | Space             | W   | 0.747      | -            | -                | -                | -         |     6.56 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1693 | 2024-05-24 | SINNERS           | W   | 0.738      | 0.435        | 0.038 (0.012)    | 0.768 (0.246)    | -         |    11.54 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1840 | 2024-05-20 | BLEED             | L   | 0.713      | -            | -                | -                | -         |    -2.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     1902 | 2024-05-18 | Passion UA        | W   | 0.699      | 0.500        | 0.173 (0.060)    | 1.000 (0.350)    | -         |    10.81 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     1974 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.686      | 0.500        | -                | 0.563 (0.193)    | -         |     8.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2143 | 2024-05-12 | BetBoom           | L   | 0.659      | -            | -                | -                | -         |    -2.27 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2169 | 2024-05-11 | RUBY              | W   | 0.653      | 0.435        | 0.097 (0.027)    | 0.544 (0.154)    | -         |     8.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2216 | 2024-05-09 | Zero Tenacity     | W   | 0.639      | 0.435        | 0.139 (0.038)    | 1.000 (0.278)    | -         |    11.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2258 | 2024-05-07 | Sashi             | L   | 0.626      | -            | -                | -                | -         |    -4.74 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2303 | 2024-05-05 | ARCRED            | W   | 0.611      | -            | -                | -                | -         |     6.31 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2311 | 2024-05-04 | BetBoom           | L   | 0.606      | -            | -                | -                | -         |    -1.66 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2318 | 2024-05-03 | fnatic            | W   | 0.600      | 0.435        | 0.292 (0.076)    | 0.529 (0.138)    | -         |    16.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2363 | 2024-05-02 | MOUZ NXT          | W   | 0.591      | 0.435        | 0.141 (0.036)    | 1.000 (0.257)    | -         |    11.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2411 | 2024-04-30 | Passion UA        | L   | 0.578      | -            | -                | -                | -         |    -8.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2450 | 2024-04-28 | Gaimin Gladiators | W   | 0.564      | 0.500        | 0.040 (0.011)    | -                | -         |    10.24 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2489 | 2024-04-26 | Passion UA        | L   | 0.553      | -            | -                | -                | -         |    -7.70 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2686 | 2024-04-19 | Alliance          | L   | 0.504      | -            | -                | -                | -         |   -10.69 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2781 | 2024-04-17 | Sangal            | L   | 0.491      | -            | -                | -                | -         |    -4.94 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2923 | 2024-04-10 | SAW               | L   | 0.447      | -            | -                | -                | -         |    -3.54 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     2979 | 2024-04-09 | SINNERS           | L   | 0.440      | -            | -                | -                | -         |    -5.63 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     2999 | 2024-04-09 | Aurora            | L   | 0.438      | -            | -                | -                | -         |    -0.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3012 | 2024-04-08 | 1WIN              | L   | 0.433      | -            | -                | -                | -         |    -8.76 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3020 | 2024-04-08 | Metizport         | W   | 0.432      | -            | -                | -                | -         |     5.86 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3083 | 2024-04-05 | Secret            | L   | 0.412      | -            | -                | -                | -         |   -12.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3113 | 2024-04-04 | TSM               | W   | 0.407      | -            | -                | -                | -         |     1.70 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3161 | 2024-04-03 | EYEBALLERS        | W   | 0.400      | -            | -                | -                | -         |     4.48 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3172 | 2024-04-03 | 9INE              | W   | 0.399      | -            | -                | -                | -         |     0.76 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3205 | 2024-04-02 | Sangal            | W   | 0.393      | 0.500        | 0.221 (0.043)    | 0.823 (0.162)    | -         |     8.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3748 | 2024-03-06 | KOI               | L   | 0.214      | -            | -                | -                | -         |    -3.95 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3893 | 2024-03-01 | Aurora            | L   | 0.179      | -            | -                | -                | -         |    -0.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3900 | 2024-02-29 | FORZE             | L   | 0.174      | -            | -                | -                | -         |    -3.50 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3913 | 2024-02-28 | Spirit Academy    | W   | 0.167      | -            | -                | -                | -         |     0.38 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3919 | 2024-02-28 | Croatia           | W   | 0.166      | -            | -                | -                | -         |     0.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4016 | 2024-02-24 | GamerLegion       | W   | 0.139      | -            | -                | -                | 1 (0.139) |     1.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4035 | 2024-02-23 | Astralis          | W   | 0.132      | -            | -                | -                | 1 (0.132) |     4.06 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4185 | 2024-02-17 | AMKAL             | L   | 0.092      | -            | -                | -                | -         |    -0.88 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4209 | 2024-02-16 | 3DMAX             | W   | 0.086      | -            | -                | -                | 1 (0.086) |     2.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4240 | 2024-02-15 | KOI               | L   | 0.078      | -            | -                | -                | -         |    -1.47 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4274 | 2024-02-14 | SAW               | W   | 0.073      | -            | -                | -                | 1 (0.073) |     1.68 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4286 | 2024-02-14 | FaZe              | L   | 0.072      | -            | -                | -                | -         |    -0.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,130.42)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $5,000.00      | $4,231.60       |
| 2024-05-26 |      0.753 | $22,000.00     | $16,567.22      |
| 2024-05-12 |      0.660 | $5,000.00      | $3,299.65       |
| 2024-05-04 |      0.606 | $5,000.00      | $3,031.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
