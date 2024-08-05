### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1100.4<br />
<br />
Final Rank Value (1100.4) = Starting Rank Value (996.6) + Head To Head Adjustments (103.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.478[<sup>1</sup>](#table2)
- Bounty Collected: 0.412[<sup>2</sup>](#table1)
- Opponent Network: 0.237[<sup>2</sup>](#table1)
- LAN Wins: 0.037[<sup>2</sup>](#table1)

The average of these factors is 0.291<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 996.6
- 400 + ( ( 0.291 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 996.6


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
|           62 |       15 | 2024-08-05 | Johnny Speeds     | W   | 1.000      | 0.143        | 0.122 (0.017)    | -                | 0 (0.000) |    22.33 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           61 |       42 | 2024-08-04 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.57 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           60 |       70 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.42 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           59 |       98 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.533 (0.227)    | 0 (0.000) |    10.51 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |      112 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.93 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |      132 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.23 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |      224 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.02 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      234 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.06 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      293 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | -         |     0.76 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      458 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | -         |     2.32 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      698 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.04 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1212 | 2024-06-10 | Aurora            | L   | 0.825      | -            | -                | -                | -         |    -3.38 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1215 | 2024-06-10 | SINNERS           | W   | 0.825      | -            | -                | -                | -         |    12.91 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1220 | 2024-06-10 | 3DMAX             | L   | 0.824      | -            | -                | -                | -         |    -3.02 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1252 | 2024-06-09 | RUSH B            | L   | 0.819      | -            | -                | -                | -         |   -17.80 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1259 | 2024-06-09 | PARIVISION        | L   | 0.818      | -            | -                | -                | -         |   -12.43 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1267 | 2024-06-09 | SAW               | W   | 0.818      | 0.143        | 0.104 (0.012)    | -                | -         |    16.04 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1278 | 2024-06-09 | Monte             | W   | 0.818      | -            | -                | -                | -         |    11.24 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1542 | 2024-06-04 | Sangal            | L   | 0.786      | -            | -                | -                | -         |   -10.21 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1766 | 2024-05-26 | MOUZ NXT          | W   | 0.726      | 0.435        | 0.139 (0.044)    | 0.987 (0.311)    | -         |    11.77 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1770 | 2024-05-26 | 1WIN              | W   | 0.725      | 0.435        | -                | 0.696 (0.219)    | -         |    10.80 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1784 | 2024-05-25 | Space             | W   | 0.720      | -            | -                | -                | -         |     6.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1810 | 2024-05-24 | SINNERS           | W   | 0.711      | 0.435        | 0.037 (0.012)    | 0.809 (0.250)    | -         |    12.48 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1939 | 2024-05-20 | BLEED             | L   | 0.686      | -            | -                | -                | -         |    -2.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1994 | 2024-05-18 | Passion UA        | W   | 0.672      | 0.500        | 0.173 (0.058)    | 1.000 (0.336)    | -         |    10.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     2065 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.659      | 0.500        | -                | 0.550 (0.181)    | -         |     8.82 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2225 | 2024-05-12 | BetBoom           | L   | 0.632      | -            | -                | -                | -         |    -2.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2251 | 2024-05-11 | RUBY              | W   | 0.626      | 0.435        | 0.095 (0.026)    | -                | -         |     8.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2298 | 2024-05-09 | Zero Tenacity     | W   | 0.612      | 0.435        | 0.143 (0.038)    | 1.000 (0.266)    | -         |    11.12 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2338 | 2024-05-07 | Sashi             | L   | 0.598      | -            | -                | -                | -         |    -4.48 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2383 | 2024-05-05 | ARCRED            | W   | 0.584      | -            | -                | -                | -         |     7.38 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2391 | 2024-05-04 | BetBoom           | L   | 0.578      | -            | -                | -                | -         |    -1.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2398 | 2024-05-03 | fnatic            | W   | 0.573      | 0.435        | 0.371 (0.092)    | 0.697 (0.174)    | -         |    17.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2442 | 2024-05-02 | MOUZ NXT          | W   | 0.564      | 0.435        | 0.139 (0.034)    | 0.987 (0.242)    | -         |    11.10 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2488 | 2024-04-30 | Passion UA        | L   | 0.551      | -            | -                | -                | -         |    -7.33 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2527 | 2024-04-28 | Gaimin Gladiators | W   | 0.537      | -            | -                | -                | -         |     9.53 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2565 | 2024-04-26 | Passion UA        | L   | 0.526      | -            | -                | -                | -         |    -7.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2566 | 2024-04-26 | Passion UA        | L   | 0.526      | -            | -                | -                | -         |    -6.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2756 | 2024-04-19 | Alliance          | L   | 0.477      | -            | -                | -                | -         |   -10.12 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2849 | 2024-04-17 | Sangal            | L   | 0.464      | -            | -                | -                | -         |    -4.38 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2989 | 2024-04-10 | SAW               | L   | 0.420      | -            | -                | -                | -         |    -3.50 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     3045 | 2024-04-09 | SINNERS           | L   | 0.413      | -            | -                | -                | -         |    -3.78 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3065 | 2024-04-09 | Aurora            | L   | 0.411      | -            | -                | -                | -         |    -0.31 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3078 | 2024-04-08 | 1WIN              | L   | 0.406      | -            | -                | -                | -         |    -7.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3086 | 2024-04-08 | Metizport         | W   | 0.405      | -            | -                | -                | -         |     4.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3149 | 2024-04-05 | Secret            | L   | 0.385      | -            | -                | -                | -         |   -11.32 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3179 | 2024-04-04 | TSM               | W   | 0.380      | -            | -                | -                | -         |     1.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3225 | 2024-04-03 | EYEBALLERS        | W   | 0.373      | -            | -                | -                | -         |     4.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3232 | 2024-04-03 | 9INE              | W   | 0.372      | -            | -                | -                | -         |     0.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3263 | 2024-04-02 | Sangal            | W   | 0.366      | 0.500        | 0.219 (0.040)    | 0.866 (0.159)    | -         |     7.92 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3795 | 2024-03-06 | KOI               | L   | 0.187      | -            | -                | -                | -         |    -2.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3934 | 2024-03-01 | Aurora            | L   | 0.152      | -            | -                | -                | -         |    -0.11 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3941 | 2024-02-29 | FORZE             | L   | 0.147      | -            | -                | -                | -         |    -2.98 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3954 | 2024-02-28 | Spirit Academy    | W   | 0.140      | -            | -                | -                | -         |     0.32 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3959 | 2024-02-28 | Croatia           | W   | 0.139      | -            | -                | -                | -         |     0.24 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4052 | 2024-02-24 | GamerLegion       | W   | 0.112      | -            | -                | -                | 1 (0.112) |     0.79 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4069 | 2024-02-23 | Astralis          | W   | 0.105      | -            | -                | -                | 1 (0.105) |     3.24 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4218 | 2024-02-17 | AMKAL             | L   | 0.065      | -            | -                | -                | -         |    -0.62 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4241 | 2024-02-16 | 3DMAX             | W   | 0.059      | -            | -                | -                | 1 (0.059) |     1.81 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4272 | 2024-02-15 | KOI               | L   | 0.051      | -            | -                | -                | -         |    -0.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4306 | 2024-02-14 | SAW               | W   | 0.046      | -            | -                | -                | 1 (0.046) |     1.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4318 | 2024-02-14 | FaZe              | L   | 0.045      | -            | -                | -                | -         |    -0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,128.33)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.819 | $5,000.00      | $4,096.18       |
| 2024-05-26 |      0.726 | $22,000.00     | $15,971.39      |
| 2024-05-12 |      0.633 | $5,000.00      | $3,164.24       |
| 2024-05-04 |      0.579 | $5,000.00      | $2,896.53       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
