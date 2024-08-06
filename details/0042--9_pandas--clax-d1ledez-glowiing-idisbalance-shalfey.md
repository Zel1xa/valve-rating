### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1113.7<br />
<br />
Final Rank Value (1113.7) = Starting Rank Value (1004.2) + Head To Head Adjustments (109.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.478[<sup>1</sup>](#table2)
- Bounty Collected: 0.418[<sup>2</sup>](#table1)
- Opponent Network: 0.244[<sup>2</sup>](#table1)
- LAN Wins: 0.034[<sup>2</sup>](#table1)

The average of these factors is 0.294<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1004.2
- 400 + ( ( 0.294 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1004.2


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
|           63 |        4 | 2024-08-06 | GUN5              | W   | 1.000      | 0.500        | 0.072 (0.036)    | 0.550 (0.275)    | 0 (0.000) |     6.71 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           62 |       40 | 2024-08-05 | Johnny Speeds     | W   | 1.000      | 0.143        | 0.122 (0.017)    | -                | 0 (0.000) |    22.21 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           61 |       67 | 2024-08-04 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.76 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           60 |       95 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.36 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           59 |      123 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.523 (0.223)    | 0 (0.000) |    10.44 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |      137 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.85 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |      157 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -12.64 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |      249 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.20 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      259 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.14 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      318 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | -         |     0.74 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      483 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | -         |     2.33 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      723 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.07 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1237 | 2024-06-10 | Aurora            | L   | 0.819      | -            | -                | -                | -         |    -3.35 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1240 | 2024-06-10 | SINNERS           | W   | 0.819      | -            | -                | -                | -         |    12.73 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1245 | 2024-06-10 | 3DMAX             | L   | 0.818      | -            | -                | -                | -         |    -3.01 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1277 | 2024-06-09 | RUSH B            | L   | 0.813      | -            | -                | -                | -         |   -17.83 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1284 | 2024-06-09 | PARIVISION        | L   | 0.812      | -            | -                | -                | -         |   -11.66 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1292 | 2024-06-09 | SAW               | W   | 0.812      | 0.143        | 0.104 (0.012)    | -                | -         |    15.77 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1303 | 2024-06-09 | Monte             | W   | 0.812      | -            | -                | -                | -         |    11.02 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1567 | 2024-06-04 | Sangal            | L   | 0.780      | -            | -                | -                | -         |    -9.71 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1791 | 2024-05-26 | MOUZ NXT          | W   | 0.720      | 0.435        | 0.139 (0.043)    | 0.961 (0.301)    | -         |    11.57 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1795 | 2024-05-26 | 1WIN              | W   | 0.719      | 0.435        | -                | 0.718 (0.224)    | -         |    10.58 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1809 | 2024-05-25 | Space             | W   | 0.714      | -            | -                | -                | -         |     6.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1835 | 2024-05-24 | SINNERS           | W   | 0.705      | 0.435        | -                | 0.800 (0.245)    | -         |    12.27 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1964 | 2024-05-20 | BLEED             | L   | 0.680      | -            | -                | -                | -         |    -2.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     2019 | 2024-05-18 | Passion UA        | W   | 0.666      | 0.500        | 0.173 (0.058)    | 1.000 (0.333)    | -         |    10.70 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     2090 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.653      | 0.500        | -                | 0.537 (0.175)    | -         |     8.68 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2250 | 2024-05-12 | BetBoom           | L   | 0.626      | -            | -                | -                | -         |    -2.26 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2276 | 2024-05-11 | RUBY              | W   | 0.620      | 0.435        | 0.095 (0.026)    | -                | -         |     8.08 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2323 | 2024-05-09 | Zero Tenacity     | W   | 0.605      | 0.435        | 0.143 (0.038)    | 1.000 (0.263)    | -         |    10.94 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2363 | 2024-05-07 | Sashi             | L   | 0.592      | -            | -                | -                | -         |    -4.56 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2408 | 2024-05-05 | ARCRED            | W   | 0.578      | -            | -                | -                | -         |     7.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2416 | 2024-05-04 | BetBoom           | L   | 0.572      | -            | -                | -                | -         |    -1.67 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2423 | 2024-05-03 | fnatic            | W   | 0.567      | 0.435        | 0.371 (0.091)    | 0.680 (0.168)    | -         |    16.92 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2467 | 2024-05-02 | MOUZ NXT          | W   | 0.558      | 0.435        | 0.139 (0.034)    | 0.961 (0.233)    | -         |    10.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2513 | 2024-04-30 | Passion UA        | L   | 0.545      | -            | -                | -                | -         |    -7.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2552 | 2024-04-28 | Gaimin Gladiators | W   | 0.531      | -            | -                | -                | -         |     9.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2590 | 2024-04-26 | Passion UA        | L   | 0.520      | -            | -                | -                | -         |    -7.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2591 | 2024-04-26 | Passion UA        | L   | 0.520      | -            | -                | -                | -         |    -6.90 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2781 | 2024-04-19 | Alliance          | L   | 0.471      | -            | -                | -                | -         |   -10.13 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2874 | 2024-04-17 | Sangal            | L   | 0.458      | -            | -                | -                | -         |    -4.01 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     3014 | 2024-04-10 | SAW               | L   | 0.414      | -            | -                | -                | -         |    -3.58 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     3070 | 2024-04-09 | SINNERS           | L   | 0.407      | -            | -                | -                | -         |    -3.83 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3090 | 2024-04-09 | Aurora            | L   | 0.405      | -            | -                | -                | -         |    -0.31 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3103 | 2024-04-08 | 1WIN              | L   | 0.400      | -            | -                | -                | -         |    -7.54 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3111 | 2024-04-08 | Metizport         | W   | 0.399      | -            | -                | -                | -         |     5.36 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3174 | 2024-04-05 | Secret            | L   | 0.379      | -            | -                | -                | -         |   -11.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3204 | 2024-04-04 | TSM               | W   | 0.374      | -            | -                | -                | -         |     1.51 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3250 | 2024-04-03 | EYEBALLERS        | W   | 0.367      | -            | -                | -                | -         |     4.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3257 | 2024-04-03 | 9INE              | W   | 0.366      | -            | -                | -                | -         |     0.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3288 | 2024-04-02 | Sangal            | W   | 0.360      | 0.500        | 0.288 (0.052)    | -                | -         |     8.08 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3820 | 2024-03-06 | KOI               | L   | 0.181      | -            | -                | -                | -         |    -2.24 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3959 | 2024-03-01 | Aurora            | L   | 0.146      | -            | -                | -                | -         |    -0.10 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3966 | 2024-02-29 | FORZE             | L   | 0.141      | -            | -                | -                | -         |    -2.90 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3979 | 2024-02-28 | Spirit Academy    | W   | 0.134      | -            | -                | -                | -         |     0.30 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3984 | 2024-02-28 | Croatia           | W   | 0.133      | -            | -                | -                | -         |     0.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4077 | 2024-02-24 | GamerLegion       | W   | 0.106      | -            | -                | -                | 1 (0.106) |     0.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4094 | 2024-02-23 | Astralis          | W   | 0.098      | -            | -                | -                | 1 (0.098) |     3.05 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4243 | 2024-02-17 | AMKAL             | L   | 0.058      | -            | -                | -                | -         |    -0.58 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4266 | 2024-02-16 | 3DMAX             | W   | 0.053      | -            | -                | -                | 1 (0.053) |     1.62 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4297 | 2024-02-15 | KOI               | L   | 0.045      | -            | -                | -                | -         |    -0.56 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4331 | 2024-02-14 | SAW               | W   | 0.040      | -            | -                | -                | 1 (0.040) |     0.89 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4343 | 2024-02-14 | FaZe              | L   | 0.038      | -            | -                | -                | -         |    -0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,902.22)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.813 | $5,000.00      | $4,065.63       |
| 2024-05-26 |      0.720 | $22,000.00     | $15,836.94      |
| 2024-05-12 |      0.627 | $5,000.00      | $3,133.68       |
| 2024-05-04 |      0.573 | $5,000.00      | $2,865.97       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
