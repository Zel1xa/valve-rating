### Roster Details<br />
Team Name: Gaimin Gladiators<br />
Roster: kraghen, nicoodoz, Nodios, Queenix, roeJ<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  943.2<br />
<br />
Final Rank Value (943.2) = Starting Rank Value (957.2) + Head To Head Adjustments (-13.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.411[<sup>1</sup>](#table2)
- Bounty Collected: 0.392[<sup>2</sup>](#table1)
- Opponent Network: 0.129[<sup>2</sup>](#table1)
- LAN Wins: 0.152[<sup>2</sup>](#table1)

The average of these factors is 0.271<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 957.2
- 400 + ( ( 0.271 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 957.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           52 |      351 | 2024-07-26 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -8.64 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           51 |     1101 | 2024-06-14 | GUN5             | L   | 0.848      | -            | -                | -                | -         |   -12.32 | kraghen, Nodios, Patti, Queenix, salazar |
|           50 |     1227 | 2024-06-10 | Enterprise       | L   | 0.819      | -            | -                | -                | -         |   -15.11 | kraghen, Nodios, Patti, Queenix, salazar |
|           49 |     1283 | 2024-06-09 | 5W               | L   | 0.812      | -            | -                | -                | -         |   -13.94 | kraghen, Nodios, Patti, Queenix, salazar |
|           48 |     1327 | 2024-06-08 | EYEBALLERS       | W   | 0.807      | 0.450        | -                | 0.488 (0.177)    | 0 (0.000) |    10.36 | kraghen, Nodios, Patti, Queenix, salazar |
|           47 |     1383 | 2024-06-07 | 3DMAX            | L   | 0.800      | -            | -                | -                | -         |    -1.32 | kraghen, Nodios, Patti, Queenix, salazar |
|           46 |     1448 | 2024-06-06 | Astralis Talent  | W   | 0.794      | 0.450        | -                | 0.156 (0.056)    | 0 (0.000) |     5.87 | kraghen, Nodios, Patti, Queenix, salazar |
|           45 |     1700 | 2024-05-30 | Lynn Vision      | L   | 0.745      | -            | -                | -                | -         |   -12.25 | kraghen, Nodios, Patti, Queenix, salazar |
|           44 |     1743 | 2024-05-28 | The MongolZ      | L   | 0.732      | -            | -                | -                | -         |    -0.15 | kraghen, Nodios, Patti, Queenix, salazar |
|           43 |     2029 | 2024-05-17 | ENCE             | L   | 0.662      | -            | -                | -                | -         |    -2.06 | kraghen, Nodios, Patti, Queenix, salazar |
|           42 |     2035 | 2024-05-17 | GamerLegion      | L   | 0.661      | -            | -                | -                | -         |    -6.32 | kraghen, Nodios, Patti, Queenix, salazar |
|           41 |     2041 | 2024-05-17 | Rebels           | L   | 0.660      | -            | -                | -                | -         |   -10.36 | kraghen, Nodios, Patti, Queenix, salazar |
|           40 |     2127 | 2024-05-15 | BLEED            | W   | 0.647      | 0.384        | 0.126 (0.031)    | 0.538 (0.134)    | 0 (0.000) |    18.54 | kraghen, Nodios, Patti, Queenix, salazar |
|           39 |     2352 | 2024-05-07 | Grannys Knockers | L   | 0.592      | -            | -                | -                | -         |   -14.49 | kraghen, Nodios, Patti, Queenix, salazar |
|           38 |     2363 | 2024-05-06 | 500              | W   | 0.587      | -            | -                | -                | -         |     0.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           37 |     2374 | 2024-05-05 | Sashi            | W   | 0.581      | 0.143        | 0.184 (0.015)    | 0.958 (0.079)    | -         |    14.05 | kraghen, Nodios, Patti, Queenix, salazar |
|           36 |     2383 | 2024-05-05 | Kronjyllands     | W   | 0.580      | -            | -                | -                | -         |     0.64 | kraghen, Nodios, Patti, Queenix, salazar |
|           35 |     2414 | 2024-05-03 | AMKAL            | L   | 0.567      | -            | -                | -                | -         |    -5.20 | kraghen, Nodios, Patti, Queenix, salazar |
|           34 |     2435 | 2024-05-02 | HAVU             | W   | 0.561      | -            | -                | -                | -         |     2.99 | kraghen, Nodios, Patti, Queenix, salazar |
|           33 |     2447 | 2024-05-02 | SINNERS          | W   | 0.559      | 0.435        | 0.037 (0.009)    | 0.790 (0.192)    | -         |    11.17 | kraghen, Nodios, Patti, Queenix, salazar |
|           32 |     2480 | 2024-04-30 | AMKAL            | L   | 0.548      | -            | -                | -                | -         |    -5.05 | kraghen, Nodios, Patti, Queenix, salazar |
|           31 |     2509 | 2024-04-29 | kONO             | L   | 0.540      | -            | -                | -                | -         |   -12.44 | kraghen, Nodios, Patti, Queenix, salazar |
|           30 |     2535 | 2024-04-28 | 9 Pandas         | L   | 0.532      | -            | -                | -                | -         |    -9.37 | kraghen, Nodios, Patti, Queenix, salazar |
|           29 |     2583 | 2024-04-26 | ALTERNATE aTTaX  | L   | 0.519      | -            | -                | -                | -         |    -9.66 | kraghen, Nodios, Patti, Queenix, salazar |
|           28 |     2644 | 2024-04-23 | Sashi            | L   | 0.500      | -            | -                | -                | -         |    -4.91 | kraghen, Nodios, Patti, Queenix, salazar |
|           27 |     2659 | 2024-04-22 | BLEED            | L   | 0.493      | -            | -                | -                | -         |    -7.52 | kraghen, Nodios, Patti, Queenix, salazar |
|           26 |     2677 | 2024-04-21 | AMKAL            | W   | 0.487      | 0.384        | 0.130 (0.024)    | 0.452 (0.085)    | -         |    10.13 | kraghen, Nodios, Patti, Queenix, salazar |
|           25 |     2714 | 2024-04-20 | Nemiga           | W   | 0.479      | 0.384        | 0.314 (0.058)    | 0.704 (0.130)    | -         |    10.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           24 |     2856 | 2024-04-17 | SINNERS          | W   | 0.459      | 0.384        | 0.037 (0.007)    | 0.790 (0.139)    | -         |    10.35 | kraghen, Nodios, Patti, Queenix, salazar |
|           23 |     2877 | 2024-04-16 | Permitta         | W   | 0.453      | 0.384        | -                | 0.919 (0.160)    | -         |     6.82 | kraghen, Nodios, Patti, Queenix, salazar |
|           22 |     3205 | 2024-04-04 | JANO             | W   | 0.372      | -            | -                | -                | -         |     1.73 | kraghen, Nodios, Patti, Queenix, salazar |
|           21 |     3420 | 2024-03-23 | G2               | L   | 0.294      | -            | -                | -                | -         |    -0.04 | kraghen, Nodios, Patti, Queenix, salazar |
|           20 |     3429 | 2024-03-22 | FURIA            | W   | 0.288      | 1.000        | 0.284 (0.082)    | 0.469 (0.135)    | 1 (0.288) |     8.91 | kraghen, Nodios, Patti, Queenix, salazar |
|           19 |     3449 | 2024-03-21 | Cloud9           | L   | 0.282      | -            | -                | -                | -         |    -3.71 | kraghen, Nodios, Patti, Queenix, salazar |
|           18 |     3464 | 2024-03-21 | MOUZ             | L   | 0.280      | -            | -                | -                | -         |    -0.07 | kraghen, Nodios, Patti, Queenix, salazar |
|           17 |     3496 | 2024-03-19 | Imperial         | W   | 0.268      | 0.143        | 0.233 (0.009)    | -                | 1 (0.268) |     6.99 | kraghen, Nodios, Patti, Queenix, salazar |
|           16 |     3511 | 2024-03-18 | Lynn Vision      | W   | 0.260      | -            | -                | -                | 1 (0.260) |     4.22 | kraghen, Nodios, Patti, Queenix, salazar |
|           15 |     3530 | 2024-03-17 | The MongolZ      | W   | 0.255      | 0.143        | 1.000 (0.036)    | -                | 1 (0.255) |     7.99 | kraghen, Nodios, Patti, Queenix, salazar |
|           14 |     3542 | 2024-03-17 | Cloud9           | L   | 0.253      | -            | -                | -                | -         |    -3.30 | kraghen, Nodios, Patti, Queenix, salazar |
|           13 |     3878 | 2024-03-04 | BetBoom          | L   | 0.166      | -            | -                | -                | -         |    -0.41 | kraghen, Nodios, Patti, Queenix, salazar |
|           12 |     3884 | 2024-03-03 | ex-Preasy        | L   | 0.162      | -            | -                | -                | -         |    -3.78 | kraghen, Nodios, Patti, Queenix, salazar |
|           11 |     3891 | 2024-03-03 | fnatic           | W   | 0.161      | 0.143        | 0.371 (0.009)    | -                | -         |     4.89 | kraghen, Nodios, Patti, Queenix, salazar |
|           10 |     3900 | 2024-03-03 | SINNERS          | W   | 0.161      | -            | -                | -                | -         |     3.73 | kraghen, Nodios, Patti, Queenix, salazar |
|            9 |     3907 | 2024-03-03 | Monte            | W   | 0.159      | -            | -                | -                | -         |     2.71 | kraghen, Nodios, Patti, Queenix, salazar |
|            8 |     3923 | 2024-03-02 | PARIVISION       | W   | 0.153      | -            | -                | -                | -         |     3.37 | kraghen, Nodios, Patti, Queenix, salazar |
|            7 |     3947 | 2024-02-29 | 3DMAX            | L   | 0.142      | -            | -                | -                | -         |    -0.08 | kraghen, Nodios, Patti, Queenix, salazar |
|            6 |     4094 | 2024-02-22 | ex-Guild Eagles  | W   | 0.093      | -            | -                | -                | 1 (0.093) |     0.91 | kraghen, Nodios, Patti, Queenix, salazar |
|            5 |     4122 | 2024-02-21 | Apeks            | L   | 0.086      | -            | -                | -                | -         |    -1.58 | kraghen, Nodios, Patti, Queenix, salazar |
|            4 |     4152 | 2024-02-20 | OG               | W   | 0.079      | -            | -                | -                | 1 (0.079) |     1.37 | kraghen, Nodios, Patti, Queenix, salazar |
|            3 |     4167 | 2024-02-19 | MOUZ             | L   | 0.075      | -            | -                | -                | -         |    -0.02 | kraghen, Nodios, Patti, Queenix, salazar |
|            2 |     4177 | 2024-02-19 | Monte            | W   | 0.073      | -            | -                | -                | 1 (0.073) |     1.26 | kraghen, Nodios, Patti, Queenix, salazar |
|            1 |     4396 | 2024-02-09 | ex-Preasy        | L   | 0.005      | -            | -                | -                | -         |    -0.13 | kraghen, Nodios, Patti, Queenix, salazar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,828.66)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.668 | $1,000.00      | $667.69         |
| 2024-05-04 |      0.574 | $2,000.00      | $1,148.15       |
| 2024-05-02 |      0.561 | $1,000.00      | $560.74         |
| 2024-04-22 |      0.493 | $5,000.00      | $2,465.51       |
| 2024-03-31 |      0.348 | $20,000.00     | $6,959.26       |
| 2024-02-09 |      0.005 | $5,000.00      | $27.31          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
