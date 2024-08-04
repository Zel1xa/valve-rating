### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1687.1<br />
<br />
Final Rank Value (1687.1) = Starting Rank Value (1684.7) + Head To Head Adjustments (2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.837[<sup>1</sup>](#table2)
- Bounty Collected: 0.627[<sup>2</sup>](#table1)
- Opponent Network: 0.233[<sup>2</sup>](#table1)
- LAN Wins: 0.816[<sup>2</sup>](#table1)

The average of these factors is 0.628<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1684.7
- 400 + ( ( 0.628 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1684.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |       74 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -20.90 | broky, frozen, karrigan, rain, ropz |
|           40 |      126 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.34 | broky, frozen, karrigan, rain, ropz |
|           39 |      177 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.13 | broky, frozen, karrigan, rain, ropz |
|           38 |      543 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.50 | broky, frozen, karrigan, rain, ropz |
|           37 |      691 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | -                | 0.294 (0.294)    | 1 (1.000) |     1.50 | broky, frozen, karrigan, rain, ropz |
|           36 |     1071 | 2024-06-14 | Vitality          | L   | 0.860      | -            | -                | -                | -         |    -8.56 | broky, frozen, karrigan, rain, ropz |
|           35 |     1111 | 2024-06-13 | Natus Vincere     | L   | 0.852      | -            | -                | -                | -         |    -6.90 | broky, frozen, karrigan, rain, ropz |
|           34 |     1143 | 2024-06-12 | SAW               | W   | 0.845      | 0.729        | -                | 0.540 (0.333)    | 1 (0.845) |     1.07 | broky, frozen, karrigan, rain, ropz |
|           33 |     1619 | 2024-05-31 | G2                | L   | 0.768      | -            | -                | -                | -         |    -5.92 | broky, frozen, karrigan, rain, ropz |
|           32 |     1673 | 2024-05-29 | Spirit            | L   | 0.754      | -            | -                | -                | -         |    -6.62 | broky, frozen, karrigan, rain, ropz |
|           31 |     1696 | 2024-05-28 | Virtus.pro        | W   | 0.748      | 0.624        | 0.497 (0.232)    | -                | 1 (0.748) |     9.46 | broky, frozen, karrigan, rain, ropz |
|           30 |     1720 | 2024-05-27 | M80               | W   | 0.741      | 0.624        | -                | 0.587 (0.271)    | 1 (0.741) |     1.40 | broky, frozen, karrigan, rain, ropz |
|           29 |     2245 | 2024-05-10 | Vitality          | L   | 0.627      | -            | -                | -                | -         |    -6.71 | broky, frozen, karrigan, rain, ropz |
|           28 |     2287 | 2024-05-08 | Natus Vincere     | W   | 0.614      | 0.889        | 1.000 (0.546)    | 0.371 (0.202)    | 1 (0.614) |    15.04 | broky, frozen, karrigan, rain, ropz |
|           27 |     2305 | 2024-05-07 | Monte             | W   | 0.607      | -            | -                | -                | 1 (0.607) |     0.36 | broky, frozen, karrigan, rain, ropz |
|           26 |     2537 | 2024-04-26 | Eternal Fire      | W   | 0.533      | 0.889        | 0.742 (0.352)    | 0.458 (0.217)    | 1 (0.533) |     7.76 | broky, frozen, karrigan, rain, ropz |
|           25 |     2566 | 2024-04-25 | Virtus.pro        | W   | 0.527      | 0.889        | 0.497 (0.233)    | 0.323 (0.151)    | 1 (0.527) |     7.46 | broky, frozen, karrigan, rain, ropz |
|           24 |     2585 | 2024-04-24 | Astralis          | L   | 0.520      | -            | -                | -                | -         |    -7.77 | broky, frozen, karrigan, rain, ropz |
|           23 |     2603 | 2024-04-23 | Imperial          | W   | 0.514      | 0.889        | 0.236 (0.108)    | 0.685 (0.313)    | 1 (0.514) |     1.40 | broky, frozen, karrigan, rain, ropz |
|           22 |     2878 | 2024-04-14 | MOUZ              | W   | 0.452      | 0.624        | 1.000 (0.282)    | -                | -         |     9.95 | broky, frozen, karrigan, rain, ropz |
|           21 |     2892 | 2024-04-13 | Astralis          | W   | 0.445      | 0.624        | 0.390 (0.108)    | -                | -         |     7.61 | broky, frozen, karrigan, rain, ropz |
|           20 |     2906 | 2024-04-12 | Liquid            | W   | 0.438      | -            | -                | -                | -         |     5.00 | broky, frozen, karrigan, rain, ropz |
|           19 |     2979 | 2024-04-10 | FlyQuest          | W   | 0.425      | -            | -                | -                | -         |     0.68 | broky, frozen, karrigan, rain, ropz |
|           18 |     2995 | 2024-04-09 | Cloud9            | W   | 0.424      | -            | -                | -                | -         |     0.40 | broky, frozen, karrigan, rain, ropz |
|           17 |     3040 | 2024-04-09 | Astralis          | L   | 0.418      | -            | -                | -                | -         |    -6.14 | broky, frozen, karrigan, rain, ropz |
|           16 |     3071 | 2024-04-08 | Nemiga            | W   | 0.411      | 0.624        | -                | 0.734 (0.188)    | -         |     0.63 | broky, frozen, karrigan, rain, ropz |
|           15 |     3265 | 2024-03-31 | Natus Vincere     | L   | 0.360      | -            | -                | -                | -         |    -2.03 | broky, frozen, karrigan, rain, ropz |
|           14 |     3271 | 2024-03-30 | Vitality          | W   | 0.353      | 1.000        | 0.649 (0.229)    | -                | -         |     7.85 | broky, frozen, karrigan, rain, ropz |
|           13 |     3291 | 2024-03-28 | Spirit            | W   | 0.341      | 1.000        | 1.000 (0.341)    | 0.460 (0.157)    | -         |     8.33 | broky, frozen, karrigan, rain, ropz |
|           12 |     3375 | 2024-03-24 | Complexity        | W   | 0.312      | 1.000        | 0.342 (0.107)    | -                | -         |     4.45 | broky, frozen, karrigan, rain, ropz |
|           11 |     3389 | 2024-03-23 | Imperial          | W   | 0.305      | 1.000        | -                | 0.685 (0.209)    | -         |     0.88 | broky, frozen, karrigan, rain, ropz |
|           10 |     3403 | 2024-03-22 | Eternal Fire      | L   | 0.299      | -            | -                | -                | -         |    -4.47 | broky, frozen, karrigan, rain, ropz |
|            9 |     3413 | 2024-03-21 | FURIA             | W   | 0.294      | -            | -                | -                | -         |     4.96 | broky, frozen, karrigan, rain, ropz |
|            8 |     3425 | 2024-03-21 | HEROIC            | L   | 0.293      | -            | -                | -                | -         |    -6.08 | broky, frozen, karrigan, rain, ropz |
|            7 |     4217 | 2024-02-16 | Eternal Fire      | W   | 0.066      | -            | -                | -                | -         |     1.07 | broky, frozen, karrigan, rain, ropz |
|            6 |     4243 | 2024-02-15 | G2                | L   | 0.059      | -            | -                | -                | -         |    -0.27 | broky, frozen, karrigan, rain, ropz |
|            5 |     4276 | 2024-02-14 | Falcons           | W   | 0.054      | -            | -                | -                | -         |     0.32 | broky, frozen, karrigan, rain, ropz |
|            4 |     4292 | 2024-02-14 | 9 Pandas          | W   | 0.052      | -            | -                | -                | -         |     0.03 | broky, frozen, karrigan, rain, ropz |
|            3 |     4330 | 2024-02-11 | Spirit            | L   | 0.033      | -            | -                | -                | -         |    -0.24 | broky, frozen, karrigan, rain, ropz |
|            2 |     4341 | 2024-02-10 | MOUZ              | W   | 0.026      | -            | -                | -                | -         |     0.59 | broky, frozen, karrigan, rain, ropz |
|            1 |     4355 | 2024-02-09 | G2                | W   | 0.020      | -            | -                | -                | -         |     0.53 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($206,650.28)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.64) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.873 | $20,000.00     | $17,453.24      |
| 2024-06-02 |      0.780 | $10,000.00     | $7,804.40       |
| 2024-05-12 |      0.640 | $32,000.00     | $20,467.41      |
| 2024-04-14 |      0.452 | $100,000.00    | $45,171.30      |
| 2024-03-31 |      0.360 | $170,000.00    | $61,274.77      |
| 2024-02-11 |      0.033 | $180,000.00    | $5,979.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
