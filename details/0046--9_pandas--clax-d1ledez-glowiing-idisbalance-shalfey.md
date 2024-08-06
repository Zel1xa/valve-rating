### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1101.7<br />
<br />
Final Rank Value (1101.7) = Starting Rank Value (994.2) + Head To Head Adjustments (107.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.478[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 994.2
- 400 + ( ( 0.289 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 994.2


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
|           62 |       33 | 2024-08-05 | Johnny Speeds     | W   | 1.000      | 0.143        | 0.122 (0.017)    | -                | 0 (0.000) |    22.39 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           61 |       60 | 2024-08-04 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.94 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           60 |       88 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.49 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           59 |      116 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.523 (0.223)    | 0 (0.000) |    10.64 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |      130 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.06 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |      150 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.12 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |      242 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.99 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      252 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.35 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      311 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | -         |     0.76 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      476 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | -         |     2.33 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      716 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -4.96 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1230 | 2024-06-10 | Aurora            | L   | 0.820      | -            | -                | -                | -         |    -3.27 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1233 | 2024-06-10 | SINNERS           | W   | 0.819      | -            | -                | -                | -         |    12.89 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1238 | 2024-06-10 | 3DMAX             | L   | 0.819      | -            | -                | -                | -         |    -2.93 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1270 | 2024-06-09 | RUSH B            | L   | 0.813      | -            | -                | -                | -         |   -17.68 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1277 | 2024-06-09 | PARIVISION        | L   | 0.813      | -            | -                | -                | -         |   -12.23 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1285 | 2024-06-09 | SAW               | W   | 0.813      | 0.143        | 0.104 (0.012)    | -                | -         |    15.87 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1296 | 2024-06-09 | Monte             | W   | 0.812      | -            | -                | -                | -         |    11.21 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1560 | 2024-06-04 | Sangal            | L   | 0.781      | -            | -                | -                | -         |    -9.97 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1784 | 2024-05-26 | MOUZ NXT          | W   | 0.720      | 0.435        | 0.139 (0.043)    | 0.962 (0.301)    | -         |    11.72 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1788 | 2024-05-26 | 1WIN              | W   | 0.720      | 0.435        | -                | 0.718 (0.225)    | -         |    10.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1802 | 2024-05-25 | Space             | W   | 0.714      | -            | -                | -                | -         |     6.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1828 | 2024-05-24 | SINNERS           | W   | 0.706      | 0.435        | 0.037 (0.011)    | 0.790 (0.242)    | -         |    12.45 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1957 | 2024-05-20 | BLEED             | L   | 0.680      | -            | -                | -                | -         |    -2.58 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     2012 | 2024-05-18 | Passion UA        | W   | 0.667      | 0.500        | 0.173 (0.058)    | 1.000 (0.333)    | -         |    10.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     2083 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.654      | 0.500        | -                | 0.537 (0.175)    | -         |     8.83 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2243 | 2024-05-12 | BetBoom           | L   | 0.626      | -            | -                | -                | -         |    -2.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2269 | 2024-05-11 | RUBY              | W   | 0.620      | 0.435        | 0.095 (0.026)    | -                | -         |     8.29 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2316 | 2024-05-09 | Zero Tenacity     | W   | 0.606      | 0.435        | 0.143 (0.038)    | 1.000 (0.263)    | -         |    11.09 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2356 | 2024-05-07 | Sashi             | L   | 0.593      | -            | -                | -                | -         |    -4.42 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2401 | 2024-05-05 | ARCRED            | W   | 0.578      | -            | -                | -                | -         |     7.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2409 | 2024-05-04 | BetBoom           | L   | 0.573      | -            | -                | -                | -         |    -1.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2416 | 2024-05-03 | fnatic            | W   | 0.568      | 0.435        | 0.371 (0.091)    | 0.680 (0.168)    | -         |    16.96 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2460 | 2024-05-02 | MOUZ NXT          | W   | 0.558      | 0.435        | 0.139 (0.034)    | 0.962 (0.233)    | -         |    11.02 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2506 | 2024-04-30 | Passion UA        | L   | 0.545      | -            | -                | -                | -         |    -7.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2545 | 2024-04-28 | Gaimin Gladiators | W   | 0.532      | -            | -                | -                | -         |     9.38 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2583 | 2024-04-26 | Passion UA        | L   | 0.520      | -            | -                | -                | -         |    -7.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2584 | 2024-04-26 | Passion UA        | L   | 0.520      | -            | -                | -                | -         |    -6.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2774 | 2024-04-19 | Alliance          | L   | 0.472      | -            | -                | -                | -         |    -9.99 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2867 | 2024-04-17 | Sangal            | L   | 0.459      | -            | -                | -                | -         |    -4.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     3007 | 2024-04-10 | SAW               | L   | 0.414      | -            | -                | -                | -         |    -3.49 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     3063 | 2024-04-09 | SINNERS           | L   | 0.408      | -            | -                | -                | -         |    -3.70 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3083 | 2024-04-09 | Aurora            | L   | 0.406      | -            | -                | -                | -         |    -0.30 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3096 | 2024-04-08 | 1WIN              | L   | 0.401      | -            | -                | -                | -         |    -7.41 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3104 | 2024-04-08 | Metizport         | W   | 0.400      | -            | -                | -                | -         |     5.50 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3167 | 2024-04-05 | Secret            | L   | 0.379      | -            | -                | -                | -         |   -11.15 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3197 | 2024-04-04 | TSM               | W   | 0.374      | -            | -                | -                | -         |     1.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3243 | 2024-04-03 | EYEBALLERS        | W   | 0.367      | -            | -                | -                | -         |     4.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3250 | 2024-04-03 | 9INE              | W   | 0.366      | -            | -                | -                | -         |     0.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3281 | 2024-04-02 | Sangal            | W   | 0.361      | 0.500        | 0.219 (0.039)    | 0.846 (0.153)    | -         |     7.91 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3813 | 2024-03-06 | KOI               | L   | 0.181      | -            | -                | -                | -         |    -2.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3952 | 2024-03-01 | Aurora            | L   | 0.147      | -            | -                | -                | -         |    -0.10 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3959 | 2024-02-29 | FORZE             | L   | 0.141      | -            | -                | -                | -         |    -2.86 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3972 | 2024-02-28 | Spirit Academy    | W   | 0.134      | -            | -                | -                | -         |     0.31 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3977 | 2024-02-28 | Croatia           | W   | 0.133      | -            | -                | -                | -         |     0.23 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4070 | 2024-02-24 | GamerLegion       | W   | 0.107      | -            | -                | -                | 1 (0.107) |     0.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4087 | 2024-02-23 | Astralis          | W   | 0.099      | -            | -                | -                | 1 (0.099) |     3.07 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4236 | 2024-02-17 | AMKAL             | L   | 0.059      | -            | -                | -                | -         |    -0.56 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4259 | 2024-02-16 | 3DMAX             | W   | 0.053      | -            | -                | -                | 1 (0.053) |     1.64 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4290 | 2024-02-15 | KOI               | L   | 0.046      | -            | -                | -                | -         |    -0.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4324 | 2024-02-14 | SAW               | W   | 0.040      | -            | -                | -                | 1 (0.040) |     0.91 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4336 | 2024-02-14 | FaZe              | L   | 0.039      | -            | -                | -                | -         |    -0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,924.49)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.814 | $5,000.00      | $4,068.63       |
| 2024-05-26 |      0.720 | $22,000.00     | $15,850.19      |
| 2024-05-12 |      0.627 | $5,000.00      | $3,136.69       |
| 2024-05-04 |      0.574 | $5,000.00      | $2,868.98       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
