### Roster Details<br />
Team Name: Gaimin Gladiators<br />
Roster: kraghen, nicoodoz, Nodios, Queenix, roeJ<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  943.9<br />
<br />
Final Rank Value (943.9) = Starting Rank Value (962.8) + Head To Head Adjustments (-18.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.395[<sup>2</sup>](#table1)
- Opponent Network: 0.132[<sup>2</sup>](#table1)
- LAN Wins: 0.162[<sup>2</sup>](#table1)

The average of these factors is 0.275<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 962.8
- 400 + ( ( 0.275 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 962.8


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
|           53 |      285 | 2024-07-26 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -9.04 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           52 |     1035 | 2024-06-14 | GUN5             | L   | 0.862      | -            | -                | -                | -         |   -12.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           51 |     1161 | 2024-06-10 | Enterprise       | L   | 0.833      | -            | -                | -                | -         |   -15.62 | kraghen, Nodios, Patti, Queenix, salazar |
|           50 |     1217 | 2024-06-09 | 5W               | L   | 0.827      | -            | -                | -                | -         |   -14.25 | kraghen, Nodios, Patti, Queenix, salazar |
|           49 |     1261 | 2024-06-08 | EYEBALLERS       | W   | 0.821      | 0.450        | -                | 0.510 (0.188)    | 0 (0.000) |    10.38 | kraghen, Nodios, Patti, Queenix, salazar |
|           48 |     1317 | 2024-06-07 | 3DMAX            | L   | 0.815      | -            | -                | -                | -         |    -1.44 | kraghen, Nodios, Patti, Queenix, salazar |
|           47 |     1382 | 2024-06-06 | Astralis Talent  | W   | 0.808      | 0.450        | -                | 0.162 (0.059)    | 0 (0.000) |     5.96 | kraghen, Nodios, Patti, Queenix, salazar |
|           46 |     1634 | 2024-05-30 | Lynn Vision      | L   | 0.759      | -            | -                | -                | -         |   -12.42 | kraghen, Nodios, Patti, Queenix, salazar |
|           45 |     1677 | 2024-05-28 | The MongolZ      | L   | 0.747      | -            | -                | -                | -         |    -0.15 | kraghen, Nodios, Patti, Queenix, salazar |
|           44 |     1963 | 2024-05-17 | ENCE             | L   | 0.676      | -            | -                | -                | -         |    -2.29 | kraghen, Nodios, Patti, Queenix, salazar |
|           43 |     1969 | 2024-05-17 | GamerLegion      | L   | 0.675      | -            | -                | -                | -         |    -6.45 | kraghen, Nodios, Patti, Queenix, salazar |
|           42 |     1975 | 2024-05-17 | Rebels           | L   | 0.674      | -            | -                | -                | -         |   -10.68 | kraghen, Nodios, Patti, Queenix, salazar |
|           41 |     2061 | 2024-05-15 | BLEED            | W   | 0.661      | 0.384        | 0.126 (0.032)    | 0.517 (0.131)    | 0 (0.000) |    18.87 | kraghen, Nodios, Patti, Queenix, salazar |
|           40 |     2286 | 2024-05-07 | Grannys Knockers | L   | 0.606      | -            | -                | -                | -         |   -14.89 | kraghen, Nodios, Patti, Queenix, salazar |
|           39 |     2297 | 2024-05-06 | 500              | W   | 0.601      | -            | -                | -                | -         |     0.64 | kraghen, Nodios, Patti, Queenix, salazar |
|           38 |     2308 | 2024-05-05 | Sashi            | W   | 0.595      | 0.143        | 0.184 (0.016)    | 0.962 (0.082)    | -         |    14.31 | kraghen, Nodios, Patti, Queenix, salazar |
|           37 |     2317 | 2024-05-05 | Kronjyllands     | W   | 0.594      | -            | -                | -                | -         |     0.65 | kraghen, Nodios, Patti, Queenix, salazar |
|           36 |     2348 | 2024-05-03 | AMKAL            | L   | 0.581      | -            | -                | -                | -         |    -5.39 | kraghen, Nodios, Patti, Queenix, salazar |
|           35 |     2369 | 2024-05-02 | HAVU             | W   | 0.575      | -            | -                | -                | -         |     3.03 | kraghen, Nodios, Patti, Queenix, salazar |
|           34 |     2381 | 2024-05-02 | SINNERS          | W   | 0.574      | 0.435        | 0.037 (0.009)    | 0.758 (0.189)    | -         |    10.22 | kraghen, Nodios, Patti, Queenix, salazar |
|           33 |     2414 | 2024-04-30 | AMKAL            | L   | 0.562      | -            | -                | -                | -         |    -5.27 | kraghen, Nodios, Patti, Queenix, salazar |
|           32 |     2443 | 2024-04-29 | kONO             | L   | 0.554      | -            | -                | -                | -         |   -12.94 | kraghen, Nodios, Patti, Queenix, salazar |
|           31 |     2469 | 2024-04-28 | 9 Pandas         | L   | 0.546      | -            | -                | -                | -         |    -9.74 | kraghen, Nodios, Patti, Queenix, salazar |
|           30 |     2517 | 2024-04-26 | ALTERNATE aTTaX  | L   | 0.533      | -            | -                | -                | -         |   -10.14 | kraghen, Nodios, Patti, Queenix, salazar |
|           29 |     2578 | 2024-04-23 | Sashi            | L   | 0.514      | -            | -                | -                | -         |    -5.21 | kraghen, Nodios, Patti, Queenix, salazar |
|           28 |     2593 | 2024-04-22 | BLEED            | L   | 0.507      | -            | -                | -                | -         |    -7.80 | kraghen, Nodios, Patti, Queenix, salazar |
|           27 |     2611 | 2024-04-21 | AMKAL            | W   | 0.501      | 0.384        | 0.130 (0.025)    | 0.476 (0.092)    | -         |    10.30 | kraghen, Nodios, Patti, Queenix, salazar |
|           26 |     2648 | 2024-04-20 | Nemiga           | W   | 0.493      | 0.384        | 0.317 (0.060)    | 0.695 (0.132)    | -         |    10.52 | kraghen, Nodios, Patti, Queenix, salazar |
|           25 |     2790 | 2024-04-17 | SINNERS          | W   | 0.473      | 0.384        | 0.037 (0.007)    | 0.758 (0.138)    | -         |     9.57 | kraghen, Nodios, Patti, Queenix, salazar |
|           24 |     2811 | 2024-04-16 | Permitta         | W   | 0.467      | 0.384        | -                | 0.876 (0.157)    | -         |     6.62 | kraghen, Nodios, Patti, Queenix, salazar |
|           23 |     3139 | 2024-04-04 | JANO             | W   | 0.387      | -            | -                | -                | -         |     1.72 | kraghen, Nodios, Patti, Queenix, salazar |
|           22 |     3354 | 2024-03-23 | G2               | L   | 0.308      | -            | -                | -                | -         |    -0.04 | kraghen, Nodios, Patti, Queenix, salazar |
|           21 |     3363 | 2024-03-22 | FURIA            | W   | 0.302      | 1.000        | 0.284 (0.086)    | 0.491 (0.148)    | 1 (0.302) |     9.35 | kraghen, Nodios, Patti, Queenix, salazar |
|           20 |     3383 | 2024-03-21 | Cloud9           | L   | 0.296      | -            | -                | -                | -         |    -3.93 | kraghen, Nodios, Patti, Queenix, salazar |
|           19 |     3398 | 2024-03-21 | MOUZ             | L   | 0.294      | -            | -                | -                | -         |    -0.08 | kraghen, Nodios, Patti, Queenix, salazar |
|           18 |     3430 | 2024-03-19 | Imperial         | W   | 0.282      | 0.143        | 0.237 (0.010)    | -                | 1 (0.282) |     7.38 | kraghen, Nodios, Patti, Queenix, salazar |
|           17 |     3445 | 2024-03-18 | Lynn Vision      | W   | 0.274      | -            | -                | -                | 1 (0.274) |     4.43 | kraghen, Nodios, Patti, Queenix, salazar |
|           16 |     3464 | 2024-03-17 | The MongolZ      | W   | 0.269      | 0.143        | 1.000 (0.038)    | -                | 1 (0.269) |     8.43 | kraghen, Nodios, Patti, Queenix, salazar |
|           15 |     3476 | 2024-03-17 | Cloud9           | L   | 0.267      | -            | -                | -                | -         |    -3.52 | kraghen, Nodios, Patti, Queenix, salazar |
|           14 |     3812 | 2024-03-04 | BetBoom          | L   | 0.180      | -            | -                | -                | -         |    -0.45 | kraghen, Nodios, Patti, Queenix, salazar |
|           13 |     3818 | 2024-03-03 | ex-Preasy        | L   | 0.176      | -            | -                | -                | -         |    -4.12 | kraghen, Nodios, Patti, Queenix, salazar |
|           12 |     3825 | 2024-03-03 | fnatic           | W   | 0.176      | 0.143        | 0.371 (0.009)    | -                | -         |     5.31 | kraghen, Nodios, Patti, Queenix, salazar |
|           11 |     3834 | 2024-03-03 | SINNERS          | W   | 0.175      | -            | -                | -                | -         |     3.60 | kraghen, Nodios, Patti, Queenix, salazar |
|           10 |     3841 | 2024-03-03 | Monte            | W   | 0.173      | -            | -                | -                | -         |     2.95 | kraghen, Nodios, Patti, Queenix, salazar |
|            9 |     3857 | 2024-03-02 | PARIVISION       | W   | 0.168      | -            | -                | -                | -         |     3.58 | kraghen, Nodios, Patti, Queenix, salazar |
|            8 |     3881 | 2024-02-29 | 3DMAX            | L   | 0.156      | -            | -                | -                | -         |    -0.09 | kraghen, Nodios, Patti, Queenix, salazar |
|            7 |     4028 | 2024-02-22 | ex-Guild Eagles  | W   | 0.108      | -            | -                | -                | 1 (0.108) |     1.03 | kraghen, Nodios, Patti, Queenix, salazar |
|            6 |     4056 | 2024-02-21 | Apeks            | L   | 0.100      | -            | -                | -                | -         |    -1.84 | kraghen, Nodios, Patti, Queenix, salazar |
|            5 |     4086 | 2024-02-20 | OG               | W   | 0.094      | -            | -                | -                | 1 (0.094) |     1.61 | kraghen, Nodios, Patti, Queenix, salazar |
|            4 |     4101 | 2024-02-19 | MOUZ             | L   | 0.089      | -            | -                | -                | -         |    -0.02 | kraghen, Nodios, Patti, Queenix, salazar |
|            3 |     4111 | 2024-02-19 | Monte            | W   | 0.087      | -            | -                | -                | 1 (0.087) |     1.51 | kraghen, Nodios, Patti, Queenix, salazar |
|            2 |     4330 | 2024-02-09 | ex-Preasy        | L   | 0.020      | -            | -                | -                | -         |    -0.46 | kraghen, Nodios, Patti, Queenix, salazar |
|            1 |     4348 | 2024-02-07 | TSM              | W   | 0.007      | -            | -                | -                | -         |     0.04 | kraghen, Nodios, Patti, Queenix, salazar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,313.47)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.682 | $1,000.00      | $681.94         |
| 2024-05-04 |      0.588 | $2,000.00      | $1,176.67       |
| 2024-05-02 |      0.575 | $1,000.00      | $575.00         |
| 2024-04-22 |      0.507 | $5,000.00      | $2,536.81       |
| 2024-03-31 |      0.362 | $20,000.00     | $7,244.44       |
| 2024-02-09 |      0.020 | $5,000.00      | $98.61          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
