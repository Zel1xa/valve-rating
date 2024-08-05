### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1684.2<br />
<br />
Final Rank Value (1684.2) = Starting Rank Value (1680.9) + Head To Head Adjustments (3.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.834[<sup>1</sup>](#table2)
- Bounty Collected: 0.625[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.814[<sup>2</sup>](#table1)

The average of these factors is 0.626<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1680.9
- 400 + ( ( 0.626 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1680.9


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
|           41 |       91 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -20.73 | broky, frozen, karrigan, rain, ropz |
|           40 |      143 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.24 | broky, frozen, karrigan, rain, ropz |
|           39 |      191 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.14 | broky, frozen, karrigan, rain, ropz |
|           38 |      560 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.40 | broky, frozen, karrigan, rain, ropz |
|           37 |      708 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | -                | 0.290 (0.290)    | 1 (1.000) |     1.50 | broky, frozen, karrigan, rain, ropz |
|           36 |     1088 | 2024-06-14 | Vitality          | L   | 0.854      | -            | -                | -                | -         |    -8.42 | broky, frozen, karrigan, rain, ropz |
|           35 |     1128 | 2024-06-13 | Natus Vincere     | L   | 0.847      | -            | -                | -                | -         |    -6.76 | broky, frozen, karrigan, rain, ropz |
|           34 |     1160 | 2024-06-12 | SAW               | W   | 0.839      | 0.729        | -                | 0.537 (0.329)    | 1 (0.839) |     1.08 | broky, frozen, karrigan, rain, ropz |
|           33 |     1636 | 2024-05-31 | G2                | L   | 0.762      | -            | -                | -                | -         |    -5.77 | broky, frozen, karrigan, rain, ropz |
|           32 |     1690 | 2024-05-29 | Spirit            | L   | 0.749      | -            | -                | -                | -         |    -6.49 | broky, frozen, karrigan, rain, ropz |
|           31 |     1713 | 2024-05-28 | Virtus.pro        | W   | 0.742      | 0.624        | 0.498 (0.230)    | -                | 1 (0.742) |     9.46 | broky, frozen, karrigan, rain, ropz |
|           30 |     1737 | 2024-05-27 | M80               | W   | 0.735      | 0.624        | -                | 0.584 (0.268)    | 1 (0.735) |     1.41 | broky, frozen, karrigan, rain, ropz |
|           29 |     2262 | 2024-05-10 | Vitality          | L   | 0.621      | -            | -                | -                | -         |    -6.58 | broky, frozen, karrigan, rain, ropz |
|           28 |     2304 | 2024-05-08 | Natus Vincere     | W   | 0.608      | 0.889        | 1.000 (0.541)    | 0.370 (0.200)    | 1 (0.608) |    14.97 | broky, frozen, karrigan, rain, ropz |
|           27 |     2322 | 2024-05-07 | Monte             | W   | 0.601      | -            | -                | -                | 1 (0.601) |     0.36 | broky, frozen, karrigan, rain, ropz |
|           26 |     2554 | 2024-04-26 | Eternal Fire      | W   | 0.527      | 0.889        | 0.740 (0.347)    | 0.455 (0.213)    | 1 (0.527) |     7.73 | broky, frozen, karrigan, rain, ropz |
|           25 |     2583 | 2024-04-25 | Virtus.pro        | W   | 0.521      | 0.889        | 0.498 (0.231)    | 0.321 (0.149)    | 1 (0.521) |     7.43 | broky, frozen, karrigan, rain, ropz |
|           24 |     2602 | 2024-04-24 | Astralis          | L   | 0.515      | -            | -                | -                | -         |    -7.61 | broky, frozen, karrigan, rain, ropz |
|           23 |     2620 | 2024-04-23 | Imperial          | W   | 0.508      | 0.889        | 0.235 (0.106)    | 0.683 (0.308)    | 1 (0.508) |     1.39 | broky, frozen, karrigan, rain, ropz |
|           22 |     2895 | 2024-04-14 | MOUZ              | W   | 0.446      | 0.624        | 1.000 (0.278)    | -                | -         |     9.88 | broky, frozen, karrigan, rain, ropz |
|           21 |     2909 | 2024-04-13 | Astralis          | W   | 0.439      | 0.624        | 0.390 (0.107)    | -                | -         |     7.57 | broky, frozen, karrigan, rain, ropz |
|           20 |     2923 | 2024-04-12 | Liquid            | W   | 0.433      | -            | -                | -                | -         |     5.01 | broky, frozen, karrigan, rain, ropz |
|           19 |     2996 | 2024-04-10 | FlyQuest          | W   | 0.420      | -            | -                | -                | -         |     0.67 | broky, frozen, karrigan, rain, ropz |
|           18 |     3012 | 2024-04-09 | Cloud9            | W   | 0.418      | -            | -                | -                | -         |     0.39 | broky, frozen, karrigan, rain, ropz |
|           17 |     3057 | 2024-04-09 | Astralis          | L   | 0.412      | -            | -                | -                | -         |    -5.99 | broky, frozen, karrigan, rain, ropz |
|           16 |     3088 | 2024-04-08 | Nemiga            | W   | 0.405      | 0.624        | -                | 0.731 (0.185)    | -         |     0.63 | broky, frozen, karrigan, rain, ropz |
|           15 |     3282 | 2024-03-31 | Natus Vincere     | L   | 0.355      | -            | -                | -                | -         |    -1.96 | broky, frozen, karrigan, rain, ropz |
|           14 |     3288 | 2024-03-30 | Vitality          | W   | 0.347      | 1.000        | 0.648 (0.225)    | -                | -         |     7.77 | broky, frozen, karrigan, rain, ropz |
|           13 |     3308 | 2024-03-28 | Spirit            | W   | 0.335      | 1.000        | 1.000 (0.335)    | 0.458 (0.153)    | -         |     8.22 | broky, frozen, karrigan, rain, ropz |
|           12 |     3392 | 2024-03-24 | Complexity        | W   | 0.306      | 1.000        | 0.342 (0.105)    | -                | -         |     4.39 | broky, frozen, karrigan, rain, ropz |
|           11 |     3406 | 2024-03-23 | Imperial          | W   | 0.300      | 1.000        | -                | 0.683 (0.205)    | -         |     0.86 | broky, frozen, karrigan, rain, ropz |
|           10 |     3420 | 2024-03-22 | Eternal Fire      | L   | 0.293      | -            | -                | -                | -         |    -4.36 | broky, frozen, karrigan, rain, ropz |
|            9 |     3430 | 2024-03-21 | FURIA             | W   | 0.289      | -            | -                | -                | -         |     4.94 | broky, frozen, karrigan, rain, ropz |
|            8 |     3442 | 2024-03-21 | HEROIC            | L   | 0.287      | -            | -                | -                | -         |    -5.93 | broky, frozen, karrigan, rain, ropz |
|            7 |     4234 | 2024-02-16 | Eternal Fire      | W   | 0.060      | -            | -                | -                | -         |     0.98 | broky, frozen, karrigan, rain, ropz |
|            6 |     4260 | 2024-02-15 | G2                | L   | 0.053      | -            | -                | -                | -         |    -0.24 | broky, frozen, karrigan, rain, ropz |
|            5 |     4293 | 2024-02-14 | Falcons           | W   | 0.048      | -            | -                | -                | -         |     0.28 | broky, frozen, karrigan, rain, ropz |
|            4 |     4309 | 2024-02-14 | 9 Pandas          | W   | 0.046      | -            | -                | -                | -         |     0.03 | broky, frozen, karrigan, rain, ropz |
|            3 |     4347 | 2024-02-11 | Spirit            | L   | 0.028      | -            | -                | -                | -         |    -0.19 | broky, frozen, karrigan, rain, ropz |
|            2 |     4358 | 2024-02-10 | MOUZ              | W   | 0.021      | -            | -                | -                | -         |     0.46 | broky, frozen, karrigan, rain, ropz |
|            1 |     4372 | 2024-02-09 | G2                | W   | 0.014      | -            | -                | -                | -         |     0.38 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($203,722.87)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.63) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.867 | $20,000.00     | $17,338.89      |
| 2024-06-02 |      0.775 | $10,000.00     | $7,747.22       |
| 2024-05-12 |      0.634 | $32,000.00     | $20,284.44      |
| 2024-04-14 |      0.446 | $100,000.00    | $44,599.54      |
| 2024-03-31 |      0.355 | $170,000.00    | $60,302.78      |
| 2024-02-11 |      0.028 | $180,000.00    | $4,950.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
