### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1076.1<br />
<br />
Final Rank Value (1076.1) = Starting Rank Value (997.4) + Head To Head Adjustments (78.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.479[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.240[<sup>2</sup>](#table1)
- LAN Wins: 0.039[<sup>2</sup>](#table1)

The average of these factors is 0.292<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 997.4
- 400 + ( ( 0.292 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 997.4


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
|           61 |       19 | 2024-08-04 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.47 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           60 |       48 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.42 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           59 |       76 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.539 (0.230)    | 0 (0.000) |    10.50 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |       90 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.92 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |      110 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.31 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |      202 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.34 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      212 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.97 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      271 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.77 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      436 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | -         |     2.33 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      676 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.11 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1190 | 2024-06-10 | Aurora            | L   | 0.830      | -            | -                | -                | -         |    -3.45 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1193 | 2024-06-10 | SINNERS           | W   | 0.830      | -            | -                | -                | -         |    12.82 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1198 | 2024-06-10 | 3DMAX             | L   | 0.829      | -            | -                | -                | -         |    -3.09 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1230 | 2024-06-09 | RUSH B            | L   | 0.824      | -            | -                | -                | -         |   -17.89 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1237 | 2024-06-09 | PARIVISION        | L   | 0.823      | -            | -                | -                | -         |   -12.60 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1245 | 2024-06-09 | SAW               | W   | 0.823      | 0.143        | 0.105 (0.012)    | -                | -         |    16.19 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1256 | 2024-06-09 | Monte             | W   | 0.823      | -            | -                | -                | -         |    11.30 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1520 | 2024-06-04 | Sangal            | L   | 0.791      | -            | -                | -                | -         |   -10.36 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1744 | 2024-05-26 | MOUZ NXT          | W   | 0.731      | 0.435        | 0.139 (0.044)    | 1.000 (0.318)    | -         |    11.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1748 | 2024-05-26 | 1WIN              | W   | 0.730      | 0.435        | -                | 0.707 (0.224)    | -         |    10.68 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1762 | 2024-05-25 | Space             | W   | 0.725      | -            | -                | -                | -         |     6.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1788 | 2024-05-24 | SINNERS           | W   | 0.716      | 0.435        | 0.037 (0.012)    | 0.797 (0.248)    | -         |    12.44 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1917 | 2024-05-20 | BLEED             | L   | 0.691      | -            | -                | -                | -         |    -2.66 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1972 | 2024-05-18 | Passion UA        | W   | 0.677      | 0.500        | 0.172 (0.058)    | 1.000 (0.339)    | -         |    10.85 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     2043 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.664      | 0.500        | 0.031 (0.010)    | 0.560 (0.186)    | -         |     8.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2203 | 2024-05-12 | BetBoom           | L   | 0.637      | -            | -                | -                | -         |    -2.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2229 | 2024-05-11 | RUBY              | W   | 0.631      | 0.435        | 0.095 (0.026)    | -                | -         |     8.21 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2276 | 2024-05-09 | Zero Tenacity     | W   | 0.616      | 0.435        | 0.137 (0.037)    | 1.000 (0.268)    | -         |    11.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2316 | 2024-05-07 | Sashi             | L   | 0.603      | -            | -                | -                | -         |    -4.50 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2361 | 2024-05-05 | ARCRED            | W   | 0.589      | -            | -                | -                | -         |     6.38 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2369 | 2024-05-04 | BetBoom           | L   | 0.583      | -            | -                | -                | -         |    -1.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2376 | 2024-05-03 | fnatic            | W   | 0.578      | 0.435        | 0.371 (0.093)    | 0.708 (0.178)    | -         |    17.27 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2420 | 2024-05-02 | MOUZ NXT          | W   | 0.569      | 0.435        | 0.139 (0.034)    | 1.000 (0.247)    | -         |    11.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2466 | 2024-04-30 | Passion UA        | L   | 0.556      | -            | -                | -                | -         |    -7.51 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2505 | 2024-04-28 | Gaimin Gladiators | W   | 0.542      | -            | -                | -                | -         |     9.66 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2543 | 2024-04-26 | Passion UA        | L   | 0.531      | -            | -                | -                | -         |    -7.39 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2544 | 2024-04-26 | Passion UA        | L   | 0.531      | -            | -                | -                | -         |    -7.05 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2734 | 2024-04-19 | Alliance          | L   | 0.482      | -            | -                | -                | -         |   -10.24 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2827 | 2024-04-17 | Sangal            | L   | 0.469      | -            | -                | -                | -         |    -4.47 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2967 | 2024-04-10 | SAW               | L   | 0.425      | -            | -                | -                | -         |    -3.52 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     3023 | 2024-04-09 | SINNERS           | L   | 0.418      | -            | -                | -                | -         |    -3.92 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3043 | 2024-04-09 | Aurora            | L   | 0.416      | -            | -                | -                | -         |    -0.32 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3056 | 2024-04-08 | 1WIN              | L   | 0.411      | -            | -                | -                | -         |    -7.81 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3064 | 2024-04-08 | Metizport         | W   | 0.410      | -            | -                | -                | -         |     4.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3127 | 2024-04-05 | Secret            | L   | 0.390      | -            | -                | -                | -         |   -11.47 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3157 | 2024-04-04 | TSM               | W   | 0.385      | -            | -                | -                | -         |     1.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3203 | 2024-04-03 | EYEBALLERS        | W   | 0.378      | -            | -                | -                | -         |     4.23 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3210 | 2024-04-03 | 9INE              | W   | 0.377      | -            | -                | -                | -         |     0.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3241 | 2024-04-02 | Sangal            | W   | 0.371      | 0.500        | 0.219 (0.041)    | 0.861 (0.160)    | -         |     7.98 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3773 | 2024-03-06 | KOI               | L   | 0.192      | -            | -                | -                | -         |    -2.30 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3912 | 2024-03-01 | Aurora            | L   | 0.157      | -            | -                | -                | -         |    -0.11 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3919 | 2024-02-29 | FORZE             | L   | 0.152      | -            | -                | -                | -         |    -3.08 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3932 | 2024-02-28 | Spirit Academy    | W   | 0.145      | -            | -                | -                | -         |     0.33 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3937 | 2024-02-28 | Croatia           | W   | 0.144      | -            | -                | -                | -         |     0.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4030 | 2024-02-24 | GamerLegion       | W   | 0.117      | -            | -                | -                | 1 (0.117) |     0.82 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4047 | 2024-02-23 | Astralis          | W   | 0.109      | -            | -                | -                | 1 (0.109) |     3.39 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4196 | 2024-02-17 | AMKAL             | L   | 0.069      | -            | -                | -                | -         |    -0.67 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4219 | 2024-02-16 | 3DMAX             | W   | 0.064      | -            | -                | -                | 1 (0.064) |     1.96 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4250 | 2024-02-15 | KOI               | L   | 0.056      | -            | -                | -                | -         |    -0.67 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4284 | 2024-02-14 | SAW               | W   | 0.051      | -            | -                | -                | 1 (0.051) |     1.15 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4296 | 2024-02-14 | FaZe              | L   | 0.049      | -            | -                | -                | -         |    -0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,308.19)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.824 | $5,000.00      | $4,120.49       |
| 2024-05-26 |      0.731 | $22,000.00     | $16,078.33      |
| 2024-05-12 |      0.638 | $5,000.00      | $3,188.54       |
| 2024-05-04 |      0.584 | $5,000.00      | $2,920.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
