### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1100.8<br />
<br />
Final Rank Value (1100.8) = Starting Rank Value (994.4) + Head To Head Adjustments (106.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.478[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 994.4
- 400 + ( ( 0.289 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 994.4


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
|           62 |       28 | 2024-08-05 | Johnny Speeds     | W   | 1.000      | 0.143        | 0.122 (0.017)    | -                | 0 (0.000) |    22.38 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           61 |       53 | 2024-08-04 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.90 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           60 |       80 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.45 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           59 |      106 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.523 (0.223)    | 0 (0.000) |    10.61 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |      120 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.06 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |      140 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.13 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |      232 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.98 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      242 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.31 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      301 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | -         |     0.77 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      466 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | -         |     2.34 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      706 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -4.96 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1220 | 2024-06-10 | Aurora            | L   | 0.820      | -            | -                | -                | -         |    -3.29 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1223 | 2024-06-10 | SINNERS           | W   | 0.819      | -            | -                | -                | -         |    12.76 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1228 | 2024-06-10 | 3DMAX             | L   | 0.819      | -            | -                | -                | -         |    -2.93 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1260 | 2024-06-09 | RUSH B            | L   | 0.814      | -            | -                | -                | -         |   -17.68 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1267 | 2024-06-09 | PARIVISION        | L   | 0.813      | -            | -                | -                | -         |   -12.24 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1275 | 2024-06-09 | SAW               | W   | 0.813      | 0.143        | 0.104 (0.012)    | -                | -         |    15.88 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1286 | 2024-06-09 | Monte             | W   | 0.812      | -            | -                | -                | -         |    11.20 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1550 | 2024-06-04 | Sangal            | L   | 0.781      | -            | -                | -                | -         |   -10.12 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1774 | 2024-05-26 | MOUZ NXT          | W   | 0.721      | 0.435        | 0.139 (0.043)    | 0.962 (0.301)    | -         |    11.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1778 | 2024-05-26 | 1WIN              | W   | 0.720      | 0.435        | -                | 0.718 (0.225)    | -         |    10.74 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1792 | 2024-05-25 | Space             | W   | 0.715      | -            | -                | -                | -         |     6.29 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1818 | 2024-05-24 | SINNERS           | W   | 0.706      | 0.435        | 0.037 (0.011)    | 0.790 (0.242)    | -         |    12.44 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1947 | 2024-05-20 | BLEED             | L   | 0.680      | -            | -                | -                | -         |    -2.58 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     2002 | 2024-05-18 | Passion UA        | W   | 0.667      | 0.500        | 0.173 (0.058)    | 1.000 (0.334)    | -         |    10.86 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     2073 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.654      | 0.500        | -                | 0.537 (0.175)    | -         |     8.81 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2233 | 2024-05-12 | BetBoom           | L   | 0.627      | -            | -                | -                | -         |    -2.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2259 | 2024-05-11 | RUBY              | W   | 0.620      | 0.435        | 0.095 (0.026)    | -                | -         |     8.26 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2306 | 2024-05-09 | Zero Tenacity     | W   | 0.606      | 0.435        | 0.143 (0.038)    | 1.000 (0.263)    | -         |    11.09 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2346 | 2024-05-07 | Sashi             | L   | 0.593      | -            | -                | -                | -         |    -4.43 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2391 | 2024-05-05 | ARCRED            | W   | 0.579      | -            | -                | -                | -         |     7.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2399 | 2024-05-04 | BetBoom           | L   | 0.573      | -            | -                | -                | -         |    -1.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2406 | 2024-05-03 | fnatic            | W   | 0.568      | 0.435        | 0.371 (0.091)    | 0.680 (0.168)    | -         |    16.97 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2450 | 2024-05-02 | MOUZ NXT          | W   | 0.559      | 0.435        | 0.139 (0.034)    | 0.962 (0.233)    | -         |    11.02 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2496 | 2024-04-30 | Passion UA        | L   | 0.545      | -            | -                | -                | -         |    -7.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2535 | 2024-04-28 | Gaimin Gladiators | W   | 0.532      | -            | -                | -                | -         |     9.37 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2573 | 2024-04-26 | Passion UA        | L   | 0.520      | -            | -                | -                | -         |    -7.06 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2574 | 2024-04-26 | Passion UA        | L   | 0.520      | -            | -                | -                | -         |    -6.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2764 | 2024-04-19 | Alliance          | L   | 0.472      | -            | -                | -                | -         |   -10.00 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2857 | 2024-04-17 | Sangal            | L   | 0.459      | -            | -                | -                | -         |    -4.29 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2997 | 2024-04-10 | SAW               | L   | 0.415      | -            | -                | -                | -         |    -3.49 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     3053 | 2024-04-09 | SINNERS           | L   | 0.408      | -            | -                | -                | -         |    -3.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3073 | 2024-04-09 | Aurora            | L   | 0.406      | -            | -                | -                | -         |    -0.30 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3086 | 2024-04-08 | 1WIN              | L   | 0.401      | -            | -                | -                | -         |    -7.42 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3094 | 2024-04-08 | Metizport         | W   | 0.400      | -            | -                | -                | -         |     5.45 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3157 | 2024-04-05 | Secret            | L   | 0.380      | -            | -                | -                | -         |   -11.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3187 | 2024-04-04 | TSM               | W   | 0.375      | -            | -                | -                | -         |     1.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3233 | 2024-04-03 | EYEBALLERS        | W   | 0.368      | -            | -                | -                | -         |     4.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3240 | 2024-04-03 | 9INE              | W   | 0.367      | -            | -                | -                | -         |     0.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3271 | 2024-04-02 | Sangal            | W   | 0.361      | 0.500        | 0.219 (0.040)    | 0.846 (0.153)    | -         |     7.85 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3803 | 2024-03-06 | KOI               | L   | 0.182      | -            | -                | -                | -         |    -2.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3942 | 2024-03-01 | Aurora            | L   | 0.147      | -            | -                | -                | -         |    -0.10 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3949 | 2024-02-29 | FORZE             | L   | 0.141      | -            | -                | -                | -         |    -2.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3962 | 2024-02-28 | Spirit Academy    | W   | 0.135      | -            | -                | -                | -         |     0.31 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3967 | 2024-02-28 | Croatia           | W   | 0.134      | -            | -                | -                | -         |     0.23 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4060 | 2024-02-24 | GamerLegion       | W   | 0.107      | -            | -                | -                | 1 (0.107) |     0.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4077 | 2024-02-23 | Astralis          | W   | 0.099      | -            | -                | -                | 1 (0.099) |     3.08 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4226 | 2024-02-17 | AMKAL             | L   | 0.059      | -            | -                | -                | -         |    -0.56 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4249 | 2024-02-16 | 3DMAX             | W   | 0.054      | -            | -                | -                | 1 (0.054) |     1.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4280 | 2024-02-15 | KOI               | L   | 0.046      | -            | -                | -                | -         |    -0.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4314 | 2024-02-14 | SAW               | W   | 0.041      | -            | -                | -                | 1 (0.041) |     0.92 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4326 | 2024-02-14 | FaZe              | L   | 0.039      | -            | -                | -                | -         |    -0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,934.77)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.814 | $5,000.00      | $4,070.02       |
| 2024-05-26 |      0.721 | $22,000.00     | $15,856.30      |
| 2024-05-12 |      0.628 | $5,000.00      | $3,138.08       |
| 2024-05-04 |      0.574 | $5,000.00      | $2,870.37       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
