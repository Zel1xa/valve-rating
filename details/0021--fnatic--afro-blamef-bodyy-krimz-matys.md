### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1403.9<br />
<br />
Final Rank Value (1403.9) = Starting Rank Value (1556.6) + Head To Head Adjustments (-152.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.699[<sup>1</sup>](#table2)
- Bounty Collected: 0.548[<sup>2</sup>](#table1)
- Opponent Network: 0.363[<sup>2</sup>](#table1)
- LAN Wins: 0.639[<sup>2</sup>](#table1)

The average of these factors is 0.562<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1556.6
- 400 + ( ( 0.562 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1556.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           63 |       70 | 2024-08-03 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -14.13 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           62 |      121 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.94 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           61 |      151 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | -         |     0.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           60 |      216 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -24.26 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           59 |      308 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -23.62 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           58 |      320 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.516 (0.224)    | -         |     5.74 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           57 |      336 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | -                | 0.962 (0.418)    | -         |     4.20 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |      370 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     1.40 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      500 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.087)    | 1.000 (0.500)    | -         |     4.49 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      531 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.069)    | 0.962 (0.481)    | -         |     4.30 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      575 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.109)    | 0.846 (0.423)    | -         |     7.03 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      596 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.57 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      648 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -27.14 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      773 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.28 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |     1025 | 2024-06-16 | 9z                | L   | 0.863      | -            | -                | -                | -         |   -13.54 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |     1029 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.862      | 0.548        | 0.254 (0.120)    | 0.531 (0.251)    | 1 (0.862) |    18.93 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |     1053 | 2024-06-15 | RED Canids        | W   | 0.856      | 0.548        | -                | 0.732 (0.344)    | 1 (0.856) |     4.36 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |     1067 | 2024-06-15 | Imperial          | W   | 0.854      | 0.548        | 0.233 (0.109)    | 0.658 (0.308)    | 1 (0.854) |     7.26 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1092 | 2024-06-14 | RED Canids        | L   | 0.849      | -            | -                | -                | -         |   -22.42 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1375 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.802      | -            | -                | -                | -         |    -8.46 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1431 | 2024-06-06 | BIG               | W   | 0.795      | 0.715        | 0.154 (0.088)    | -                | 1 (0.795) |     7.51 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1457 | 2024-06-06 | FURIA             | L   | 0.794      | -            | -                | -                | -         |    -8.63 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1472 | 2024-06-06 | Complexity        | W   | 0.793      | 0.715        | 0.341 (0.193)    | -                | 1 (0.793) |    18.83 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1502 | 2024-06-05 | Eternal Fire      | W   | 0.788      | 0.715        | 0.739 (0.416)    | 0.438 (0.247)    | 1 (0.788) |    19.34 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1518 | 2024-06-05 | BetBoom           | L   | 0.787      | -            | -                | -                | -         |   -14.95 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1608 | 2024-06-02 | DMS               | L   | 0.767      | -            | -                | -                | -         |   -22.58 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1673 | 2024-05-31 | SAW               | W   | 0.754      | -            | -                | -                | -         |     4.35 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1674 | 2024-05-31 | Sangal            | W   | 0.754      | -            | -                | -                | -         |     3.22 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     2010 | 2024-05-18 | ENCE              | L   | 0.667      | -            | -                | -                | -         |   -12.82 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     2018 | 2024-05-18 | GamerLegion       | L   | 0.666      | -            | -                | -                | -         |   -18.17 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     2044 | 2024-05-17 | ENCE              | W   | 0.660      | 0.769        | 0.173 (0.088)    | -                | -         |     7.60 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2410 | 2024-05-03 | 9 Pandas          | L   | 0.568      | -            | -                | -                | -         |   -16.98 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2438 | 2024-05-02 | Sashi             | L   | 0.561      | -            | -                | -                | -         |   -15.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2466 | 2024-05-01 | AMKAL             | W   | 0.554      | -            | -                | -                | -         |     1.93 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2479 | 2024-05-01 | PARIVISION        | W   | 0.552      | -            | -                | -                | -         |     1.52 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2502 | 2024-04-30 | Nexus             | W   | 0.545      | -            | -                | -                | -         |     0.36 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2561 | 2024-04-27 | Virtus.pro        | L   | 0.526      | -            | -                | -                | -         |    -4.98 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2602 | 2024-04-25 | Eternal Fire      | L   | 0.515      | -            | -                | -                | -         |    -4.56 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2626 | 2024-04-24 | 3DMAX             | L   | 0.507      | -            | -                | -                | -         |    -5.79 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2650 | 2024-04-23 | Virtus.pro        | W   | 0.500      | 0.889        | 0.498 (0.221)    | -                | 1 (0.500) |    11.21 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2801 | 2024-04-18 | KOI               | L   | 0.468      | -            | -                | -                | -         |   -13.68 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     3055 | 2024-04-09 | Apeks             | L   | 0.408      | -            | -                | -                | -         |   -12.50 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3089 | 2024-04-08 | Apeks             | W   | 0.402      | -            | -                | -                | -         |     0.34 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3095 | 2024-04-08 | KOI               | W   | 0.401      | -            | -                | -                | -         |     0.83 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3428 | 2024-03-23 | BetBoom           | L   | 0.293      | -            | -                | -                | -         |    -6.38 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3464 | 2024-03-21 | 3DMAX             | W   | 0.281      | -            | -                | -                | -         |     5.86 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3818 | 2024-03-06 | BLEED             | W   | 0.181      | -            | -                | -                | -         |     0.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3861 | 2024-03-05 | Young Ninjas      | W   | 0.174      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3878 | 2024-03-04 | 3DMAX             | W   | 0.167      | -            | -                | -                | -         |     3.62 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3895 | 2024-03-03 | Gaimin Gladiators | L   | 0.162      | -            | -                | -                | -         |    -4.90 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3900 | 2024-03-03 | AURA              | W   | 0.161      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3910 | 2024-03-03 | ex-Preasy         | W   | 0.160      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3947 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.147      | -            | -                | -                | -         |     0.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3963 | 2024-02-28 | ex-Preasy         | L   | 0.135      | -            | -                | -                | -         |    -4.20 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4079 | 2024-02-23 | GamerLegion       | L   | 0.101      | -            | -                | -                | -         |    -3.14 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4224 | 2024-02-17 | SAW               | L   | 0.061      | -            | -                | -                | -         |    -1.72 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4260 | 2024-02-16 | KOI               | L   | 0.053      | -            | -                | -                | -         |    -1.56 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4283 | 2024-02-15 | AMKAL             | W   | 0.047      | -            | -                | -                | 1 (0.047) |     0.13 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4310 | 2024-02-14 | Virtus.pro        | L   | 0.042      | -            | -                | -                | -         |    -0.41 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4320 | 2024-02-14 | BetBoom           | W   | 0.041      | -            | -                | -                | 1 (0.041) |     0.40 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4391 | 2024-02-09 | 3DMAX             | L   | 0.008      | -            | -                | -                | -         |    -0.08 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4394 | 2024-02-09 | ex-Sprout         | L   | 0.007      | -            | -                | -                | -         |    -0.23 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4398 | 2024-02-09 | Endpoint          | W   | 0.007      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($118,730.97)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-16 |      0.863 | $30,000.00     | $25,894.44      |
| 2024-06-09 |      0.814 | $20,000.00     | $16,281.48      |
| 2024-05-12 |      0.627 | $7,000.00      | $4,391.85       |
| 2024-05-04 |      0.574 | $2,000.00      | $1,148.70       |
| 2024-05-02 |      0.561 | $3,500.00      | $1,963.56       |
| 2024-03-06 |      0.181 | $50,000.00     | $9,050.93       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
