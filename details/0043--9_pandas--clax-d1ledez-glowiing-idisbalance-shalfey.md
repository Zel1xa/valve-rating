### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1111.2<br />
<br />
Final Rank Value (1111.2) = Starting Rank Value (1003.1) + Head To Head Adjustments (108.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.478[<sup>1</sup>](#table2)
- Bounty Collected: 0.416[<sup>2</sup>](#table1)
- Opponent Network: 0.244[<sup>2</sup>](#table1)
- LAN Wins: 0.034[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1003.1
- 400 + ( ( 0.293 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1003.1


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
|           63 |        0 | 2024-08-06 | GUN5              | W   | 1.000      | 0.500        | 0.072 (0.036)    | 0.550 (0.275)    | 0 (0.000) |     6.72 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           62 |       35 | 2024-08-05 | Johnny Speeds     | W   | 1.000      | 0.143        | 0.122 (0.017)    | -                | 0 (0.000) |    22.29 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           61 |       62 | 2024-08-04 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.83 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           60 |       90 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.39 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           59 |      118 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.523 (0.223)    | 0 (0.000) |    10.52 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |      132 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.93 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |      152 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.25 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |      244 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.13 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      254 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.20 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      313 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | -         |     0.75 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      478 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | -         |     2.29 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      718 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.04 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1232 | 2024-06-10 | Aurora            | L   | 0.819      | -            | -                | -                | -         |    -3.33 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1235 | 2024-06-10 | SINNERS           | W   | 0.819      | -            | -                | -                | -         |    12.75 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1240 | 2024-06-10 | 3DMAX             | L   | 0.819      | -            | -                | -                | -         |    -2.99 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1272 | 2024-06-09 | RUSH B            | L   | 0.813      | -            | -                | -                | -         |   -17.80 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1279 | 2024-06-09 | PARIVISION        | L   | 0.813      | -            | -                | -                | -         |   -12.39 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1287 | 2024-06-09 | SAW               | W   | 0.812      | 0.143        | 0.104 (0.012)    | -                | -         |    15.72 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1298 | 2024-06-09 | Monte             | W   | 0.812      | -            | -                | -                | -         |    11.05 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1562 | 2024-06-04 | Sangal            | L   | 0.781      | -            | -                | -                | -         |   -10.12 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1786 | 2024-05-26 | MOUZ NXT          | W   | 0.720      | 0.435        | 0.139 (0.043)    | 0.962 (0.301)    | -         |    11.56 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1790 | 2024-05-26 | 1WIN              | W   | 0.719      | 0.435        | -                | 0.718 (0.225)    | -         |    10.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1804 | 2024-05-25 | Space             | W   | 0.714      | -            | -                | -                | -         |     6.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1830 | 2024-05-24 | SINNERS           | W   | 0.706      | 0.435        | -                | 0.800 (0.245)    | -         |    12.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1959 | 2024-05-20 | BLEED             | L   | 0.680      | -            | -                | -                | -         |    -2.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     2014 | 2024-05-18 | Passion UA        | W   | 0.667      | 0.500        | 0.173 (0.058)    | 1.000 (0.333)    | -         |    10.72 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     2085 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.653      | 0.500        | -                | 0.537 (0.175)    | -         |     8.66 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2245 | 2024-05-12 | BetBoom           | L   | 0.626      | -            | -                | -                | -         |    -2.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2271 | 2024-05-11 | RUBY              | W   | 0.620      | 0.435        | 0.095 (0.026)    | -                | -         |     8.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2318 | 2024-05-09 | Zero Tenacity     | W   | 0.606      | 0.435        | 0.143 (0.038)    | 1.000 (0.263)    | -         |    10.92 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2358 | 2024-05-07 | Sashi             | L   | 0.593      | -            | -                | -                | -         |    -4.54 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2403 | 2024-05-05 | ARCRED            | W   | 0.578      | -            | -                | -                | -         |     7.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2411 | 2024-05-04 | BetBoom           | L   | 0.573      | -            | -                | -                | -         |    -1.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2418 | 2024-05-03 | fnatic            | W   | 0.568      | 0.435        | 0.371 (0.091)    | 0.680 (0.168)    | -         |    16.93 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2462 | 2024-05-02 | MOUZ NXT          | W   | 0.558      | 0.435        | 0.139 (0.034)    | 0.962 (0.233)    | -         |    10.86 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2508 | 2024-04-30 | Passion UA        | L   | 0.545      | -            | -                | -                | -         |    -7.33 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2547 | 2024-04-28 | Gaimin Gladiators | W   | 0.532      | -            | -                | -                | -         |     9.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2585 | 2024-04-26 | Passion UA        | L   | 0.520      | -            | -                | -                | -         |    -7.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2586 | 2024-04-26 | Passion UA        | L   | 0.520      | -            | -                | -                | -         |    -6.88 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2776 | 2024-04-19 | Alliance          | L   | 0.472      | -            | -                | -                | -         |   -10.12 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2869 | 2024-04-17 | Sangal            | L   | 0.458      | -            | -                | -                | -         |    -4.33 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     3009 | 2024-04-10 | SAW               | L   | 0.414      | -            | -                | -                | -         |    -3.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     3065 | 2024-04-09 | SINNERS           | L   | 0.407      | -            | -                | -                | -         |    -3.82 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3085 | 2024-04-09 | Aurora            | L   | 0.406      | -            | -                | -                | -         |    -0.31 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3098 | 2024-04-08 | 1WIN              | L   | 0.401      | -            | -                | -                | -         |    -7.54 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3106 | 2024-04-08 | Metizport         | W   | 0.400      | -            | -                | -                | -         |     5.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3169 | 2024-04-05 | Secret            | L   | 0.379      | -            | -                | -                | -         |   -11.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3199 | 2024-04-04 | TSM               | W   | 0.374      | -            | -                | -                | -         |     1.52 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3245 | 2024-04-03 | EYEBALLERS        | W   | 0.367      | -            | -                | -                | -         |     4.06 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3252 | 2024-04-03 | 9INE              | W   | 0.366      | -            | -                | -                | -         |     0.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3283 | 2024-04-02 | Sangal            | W   | 0.361      | 0.500        | 0.219 (0.039)    | -                | -         |     7.80 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3815 | 2024-03-06 | KOI               | L   | 0.181      | -            | -                | -                | -         |    -2.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3954 | 2024-03-01 | Aurora            | L   | 0.147      | -            | -                | -                | -         |    -0.10 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3961 | 2024-02-29 | FORZE             | L   | 0.141      | -            | -                | -                | -         |    -2.91 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3974 | 2024-02-28 | Spirit Academy    | W   | 0.134      | -            | -                | -                | -         |     0.30 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3979 | 2024-02-28 | Croatia           | W   | 0.133      | -            | -                | -                | -         |     0.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4072 | 2024-02-24 | GamerLegion       | W   | 0.106      | -            | -                | -                | 1 (0.106) |     0.72 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4089 | 2024-02-23 | Astralis          | W   | 0.099      | -            | -                | -                | 1 (0.099) |     3.06 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4238 | 2024-02-17 | AMKAL             | L   | 0.059      | -            | -                | -                | -         |    -0.58 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4261 | 2024-02-16 | 3DMAX             | W   | 0.053      | -            | -                | -                | 1 (0.053) |     1.64 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4292 | 2024-02-15 | KOI               | L   | 0.046      | -            | -                | -                | -         |    -0.56 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4326 | 2024-02-14 | SAW               | W   | 0.040      | -            | -                | -                | 1 (0.040) |     0.90 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4338 | 2024-02-14 | FaZe              | L   | 0.039      | -            | -                | -                | -         |    -0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,917.64)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.814 | $5,000.00      | $4,067.71       |
| 2024-05-26 |      0.720 | $22,000.00     | $15,846.11      |
| 2024-05-12 |      0.627 | $5,000.00      | $3,135.76       |
| 2024-05-04 |      0.574 | $5,000.00      | $2,868.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
