### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1099.8<br />
<br />
Final Rank Value (1099.8) = Starting Rank Value (994.8) + Head To Head Adjustments (105.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.478[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.235[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 994.8
- 400 + ( ( 0.290 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 994.8


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
|           62 |       21 | 2024-08-05 | Johnny Speeds     | W   | 1.000      | 0.143        | 0.122 (0.017)    | -                | 0 (0.000) |    22.37 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           61 |       48 | 2024-08-04 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.59 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           60 |       76 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.44 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           59 |      104 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.534 (0.228)    | 0 (0.000) |    10.55 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |      118 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.96 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |      138 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.16 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |      230 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.97 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      240 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.10 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      299 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | -         |     0.77 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      464 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | -         |     2.33 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      704 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -4.96 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1218 | 2024-06-10 | Aurora            | L   | 0.821      | -            | -                | -                | -         |    -3.31 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1221 | 2024-06-10 | SINNERS           | W   | 0.820      | -            | -                | -                | -         |    12.89 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1226 | 2024-06-10 | 3DMAX             | L   | 0.820      | -            | -                | -                | -         |    -2.94 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1258 | 2024-06-09 | RUSH B            | L   | 0.815      | -            | -                | -                | -         |   -17.69 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1265 | 2024-06-09 | PARIVISION        | L   | 0.814      | -            | -                | -                | -         |   -12.29 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1273 | 2024-06-09 | SAW               | W   | 0.814      | 0.143        | 0.104 (0.012)    | -                | -         |    15.94 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1284 | 2024-06-09 | Monte             | W   | 0.813      | -            | -                | -                | -         |    11.26 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1548 | 2024-06-04 | Sangal            | L   | 0.782      | -            | -                | -                | -         |   -10.09 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1772 | 2024-05-26 | MOUZ NXT          | W   | 0.722      | 0.435        | 0.139 (0.043)    | 0.984 (0.309)    | -         |    11.74 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1776 | 2024-05-26 | 1WIN              | W   | 0.721      | 0.435        | -                | 0.695 (0.218)    | -         |    10.79 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1790 | 2024-05-25 | Space             | W   | 0.716      | -            | -                | -                | -         |     6.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1816 | 2024-05-24 | SINNERS           | W   | 0.707      | 0.435        | 0.037 (0.011)    | 0.808 (0.248)    | -         |    12.46 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1945 | 2024-05-20 | BLEED             | L   | 0.681      | -            | -                | -                | -         |    -2.57 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     2000 | 2024-05-18 | Passion UA        | W   | 0.668      | 0.500        | 0.173 (0.058)    | 1.000 (0.334)    | -         |    10.88 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     2071 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.655      | 0.500        | -                | 0.549 (0.180)    | -         |     8.80 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2231 | 2024-05-12 | BetBoom           | L   | 0.628      | -            | -                | -                | -         |    -2.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2257 | 2024-05-11 | RUBY              | W   | 0.621      | 0.435        | 0.095 (0.026)    | -                | -         |     8.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2304 | 2024-05-09 | Zero Tenacity     | W   | 0.607      | 0.435        | 0.143 (0.038)    | 1.000 (0.264)    | -         |    11.09 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2344 | 2024-05-07 | Sashi             | L   | 0.594      | -            | -                | -                | -         |    -4.43 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2389 | 2024-05-05 | ARCRED            | W   | 0.579      | -            | -                | -                | -         |     7.37 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2397 | 2024-05-04 | BetBoom           | L   | 0.574      | -            | -                | -                | -         |    -1.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2404 | 2024-05-03 | fnatic            | W   | 0.569      | 0.435        | 0.371 (0.092)    | 0.695 (0.172)    | -         |    17.01 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2448 | 2024-05-02 | MOUZ NXT          | W   | 0.559      | 0.435        | 0.139 (0.034)    | 0.984 (0.239)    | -         |    11.05 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2494 | 2024-04-30 | Passion UA        | L   | 0.546      | -            | -                | -                | -         |    -7.21 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2533 | 2024-04-28 | Gaimin Gladiators | W   | 0.533      | -            | -                | -                | -         |     9.43 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2571 | 2024-04-26 | Passion UA        | L   | 0.521      | -            | -                | -                | -         |    -7.06 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2572 | 2024-04-26 | Passion UA        | L   | 0.521      | -            | -                | -                | -         |    -6.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2762 | 2024-04-19 | Alliance          | L   | 0.473      | -            | -                | -                | -         |   -10.01 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2855 | 2024-04-17 | Sangal            | L   | 0.460      | -            | -                | -                | -         |    -4.30 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2995 | 2024-04-10 | SAW               | L   | 0.416      | -            | -                | -                | -         |    -3.47 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     3051 | 2024-04-09 | SINNERS           | L   | 0.409      | -            | -                | -                | -         |    -3.72 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3071 | 2024-04-09 | Aurora            | L   | 0.407      | -            | -                | -                | -         |    -0.30 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3084 | 2024-04-08 | 1WIN              | L   | 0.402      | -            | -                | -                | -         |    -7.41 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3092 | 2024-04-08 | Metizport         | W   | 0.401      | -            | -                | -                | -         |     4.50 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3155 | 2024-04-05 | Secret            | L   | 0.381      | -            | -                | -                | -         |   -11.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3185 | 2024-04-04 | TSM               | W   | 0.376      | -            | -                | -                | -         |     1.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3231 | 2024-04-03 | EYEBALLERS        | W   | 0.369      | -            | -                | -                | -         |     4.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3238 | 2024-04-03 | 9INE              | W   | 0.367      | -            | -                | -                | -         |     0.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3269 | 2024-04-02 | Sangal            | W   | 0.362      | 0.500        | 0.219 (0.040)    | 0.865 (0.157)    | -         |     7.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3801 | 2024-03-06 | KOI               | L   | 0.182      | -            | -                | -                | -         |    -2.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3940 | 2024-03-01 | Aurora            | L   | 0.148      | -            | -                | -                | -         |    -0.10 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3947 | 2024-02-29 | FORZE             | L   | 0.142      | -            | -                | -                | -         |    -2.89 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3960 | 2024-02-28 | Spirit Academy    | W   | 0.136      | -            | -                | -                | -         |     0.32 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3965 | 2024-02-28 | Croatia           | W   | 0.135      | -            | -                | -                | -         |     0.23 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4058 | 2024-02-24 | GamerLegion       | W   | 0.108      | -            | -                | -                | 1 (0.108) |     0.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4075 | 2024-02-23 | Astralis          | W   | 0.100      | -            | -                | -                | 1 (0.100) |     3.11 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4224 | 2024-02-17 | AMKAL             | L   | 0.060      | -            | -                | -                | -         |    -0.57 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4247 | 2024-02-16 | 3DMAX             | W   | 0.054      | -            | -                | -                | 1 (0.054) |     1.68 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4278 | 2024-02-15 | KOI               | L   | 0.047      | -            | -                | -                | -         |    -0.56 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4312 | 2024-02-14 | SAW               | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.94 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4324 | 2024-02-14 | FaZe              | L   | 0.040      | -            | -                | -                | -         |    -0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,969.03)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.815 | $5,000.00      | $4,074.65       |
| 2024-05-26 |      0.722 | $22,000.00     | $15,876.67      |
| 2024-05-12 |      0.629 | $5,000.00      | $3,142.71       |
| 2024-05-04 |      0.575 | $5,000.00      | $2,875.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
