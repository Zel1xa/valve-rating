### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1067.7<br />
<br />
Final Rank Value (1067.7) = Starting Rank Value (998.3) + Head To Head Adjustments (69.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.479[<sup>1</sup>](#table2)
- Bounty Collected: 0.412[<sup>2</sup>](#table1)
- Opponent Network: 0.238[<sup>2</sup>](#table1)
- LAN Wins: 0.042[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 998.3
- 400 + ( ( 0.293 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 998.3


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
|           59 |       11 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.09 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |       39 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.535 (0.228)    | 0 (0.000) |    10.32 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |       53 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.77 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |       72 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.57 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      163 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.59 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      173 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.99 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      232 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.76 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      396 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.18 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |      634 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.27 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1150 | 2024-06-10 | Aurora            | L   | 0.837      | -            | -                | -                | -         |    -3.61 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1153 | 2024-06-10 | SINNERS           | W   | 0.837      | -            | -                | -                | -         |    12.15 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1158 | 2024-06-10 | 3DMAX             | L   | 0.836      | -            | -                | -                | -         |    -3.25 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1190 | 2024-06-09 | RUSH B            | L   | 0.831      | -            | -                | -                | -         |   -18.48 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1197 | 2024-06-09 | PARIVISION        | L   | 0.831      | -            | -                | -                | -         |   -12.92 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1205 | 2024-06-09 | SAW               | W   | 0.830      | 0.143        | 0.106 (0.013)    | -                | -         |    16.22 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1216 | 2024-06-09 | Monte             | W   | 0.830      | -            | -                | -                | -         |    11.26 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1480 | 2024-06-04 | Sangal            | L   | 0.798      | -            | -                | -                | -         |   -10.70 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           42 |     1704 | 2024-05-26 | MOUZ NXT          | W   | 0.738      | 0.435        | 0.139 (0.045)    | 1.000 (0.321)    | -         |    11.69 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1708 | 2024-05-26 | 1WIN              | W   | 0.737      | 0.435        | -                | 0.629 (0.201)    | -         |     9.98 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1722 | 2024-05-25 | Space             | W   | 0.732      | -            | -                | -                | -         |     6.37 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1748 | 2024-05-24 | SINNERS           | W   | 0.723      | 0.435        | 0.037 (0.012)    | 0.758 (0.238)    | -         |    11.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1877 | 2024-05-20 | BLEED             | L   | 0.698      | -            | -                | -                | -         |    -2.79 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     1932 | 2024-05-18 | Passion UA        | W   | 0.684      | 0.500        | 0.172 (0.059)    | 1.000 (0.342)    | -         |    10.47 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2003 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.671      | 0.500        | 0.032 (0.011)    | 0.561 (0.188)    | -         |     8.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2163 | 2024-05-12 | BetBoom           | L   | 0.644      | -            | -                | -                | -         |    -2.27 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2189 | 2024-05-11 | RUBY              | W   | 0.638      | 0.435        | 0.095 (0.026)    | -                | -         |     8.26 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2236 | 2024-05-09 | Zero Tenacity     | W   | 0.624      | 0.435        | 0.137 (0.037)    | 1.000 (0.271)    | -         |    11.05 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2276 | 2024-05-07 | Sashi             | L   | 0.611      | -            | -                | -                | -         |    -4.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2321 | 2024-05-05 | ARCRED            | W   | 0.596      | -            | -                | -                | -         |     6.31 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2329 | 2024-05-04 | BetBoom           | L   | 0.591      | -            | -                | -                | -         |    -1.67 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2336 | 2024-05-03 | fnatic            | W   | 0.585      | 0.435        | 0.371 (0.094)    | 0.709 (0.180)    | -         |    17.45 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2380 | 2024-05-02 | MOUZ NXT          | W   | 0.576      | 0.435        | 0.139 (0.035)    | 1.000 (0.250)    | -         |    11.09 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2426 | 2024-04-30 | Passion UA        | L   | 0.563      | -            | -                | -                | -         |    -8.05 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2465 | 2024-04-28 | Gaimin Gladiators | W   | 0.549      | -            | -                | -                | -         |     9.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2503 | 2024-04-26 | Passion UA        | L   | 0.538      | -            | -                | -                | -         |    -7.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2693 | 2024-04-19 | Alliance          | L   | 0.489      | -            | -                | -                | -         |   -10.40 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2786 | 2024-04-17 | Sangal            | L   | 0.476      | -            | -                | -                | -         |    -4.63 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2926 | 2024-04-10 | SAW               | L   | 0.432      | -            | -                | -                | -         |    -3.57 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     2982 | 2024-04-09 | SINNERS           | L   | 0.425      | -            | -                | -                | -         |    -4.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3002 | 2024-04-09 | Aurora            | L   | 0.423      | -            | -                | -                | -         |    -0.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3015 | 2024-04-08 | 1WIN              | L   | 0.418      | -            | -                | -                | -         |    -8.48 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3023 | 2024-04-08 | Metizport         | W   | 0.417      | -            | -                | -                | -         |     5.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3086 | 2024-04-05 | Secret            | L   | 0.397      | -            | -                | -                | -         |   -11.69 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3116 | 2024-04-04 | TSM               | W   | 0.392      | -            | -                | -                | -         |     1.63 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3162 | 2024-04-03 | EYEBALLERS        | W   | 0.385      | -            | -                | -                | -         |     4.30 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3169 | 2024-04-03 | 9INE              | W   | 0.384      | -            | -                | -                | -         |     0.74 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3200 | 2024-04-02 | Sangal            | W   | 0.378      | 0.500        | 0.219 (0.041)    | 0.862 (0.163)    | -         |     8.05 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3731 | 2024-03-06 | KOI               | L   | 0.199      | -            | -                | -                | -         |    -2.38 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3870 | 2024-03-01 | Aurora            | L   | 0.164      | -            | -                | -                | -         |    -0.12 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3877 | 2024-02-29 | FORZE             | L   | 0.159      | -            | -                | -                | -         |    -3.23 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3890 | 2024-02-28 | Spirit Academy    | W   | 0.152      | -            | -                | -                | -         |     0.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3895 | 2024-02-28 | Croatia           | W   | 0.151      | -            | -                | -                | -         |     0.26 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     3988 | 2024-02-24 | GamerLegion       | W   | 0.124      | -            | -                | -                | 1 (0.124) |     0.90 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4005 | 2024-02-23 | Astralis          | W   | 0.117      | -            | -                | -                | 1 (0.117) |     3.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4153 | 2024-02-17 | AMKAL             | L   | 0.077      | -            | -                | -                | -         |    -0.74 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4176 | 2024-02-16 | 3DMAX             | W   | 0.071      | -            | -                | -                | 1 (0.071) |     2.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4207 | 2024-02-15 | KOI               | L   | 0.063      | -            | -                | -                | -         |    -0.76 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4241 | 2024-02-14 | SAW               | W   | 0.058      | -            | -                | -                | 1 (0.058) |     1.31 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4253 | 2024-02-14 | FaZe              | L   | 0.057      | -            | -                | -                | -         |    -0.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,575.42)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.831 | $5,000.00      | $4,156.60       |
| 2024-05-26 |      0.738 | $22,000.00     | $16,237.22      |
| 2024-05-12 |      0.645 | $5,000.00      | $3,224.65       |
| 2024-05-04 |      0.591 | $5,000.00      | $2,956.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
