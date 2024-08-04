### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1682.3<br />
<br />
Final Rank Value (1682.3) = Starting Rank Value (1683.5) + Head To Head Adjustments (-1.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.837[<sup>1</sup>](#table2)
- Bounty Collected: 0.626[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.817[<sup>2</sup>](#table1)

The average of these factors is 0.628<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1683.5
- 400 + ( ( 0.628 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1683.5


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
|           42 |       44 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -21.09 | broky, frozen, karrigan, rain, ropz |
|           41 |       94 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.29 | broky, frozen, karrigan, rain, ropz |
|           40 |      143 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.14 | broky, frozen, karrigan, rain, ropz |
|           39 |      511 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.48 | broky, frozen, karrigan, rain, ropz |
|           38 |      659 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.290 (0.290)    | 1 (1.000) |     1.52 | broky, frozen, karrigan, rain, ropz |
|           37 |     1039 | 2024-06-14 | Vitality          | L   | 0.861      | -            | -                | -                | -         |    -8.58 | broky, frozen, karrigan, rain, ropz |
|           36 |     1079 | 2024-06-13 | Natus Vincere     | L   | 0.854      | -            | -                | -                | -         |    -6.91 | broky, frozen, karrigan, rain, ropz |
|           35 |     1111 | 2024-06-12 | SAW               | W   | 0.847      | 0.729        | -                | 0.540 (0.333)    | 1 (0.847) |     1.09 | broky, frozen, karrigan, rain, ropz |
|           34 |     1587 | 2024-05-31 | G2                | L   | 0.770      | -            | -                | -                | -         |    -5.87 | broky, frozen, karrigan, rain, ropz |
|           33 |     1641 | 2024-05-29 | Spirit            | L   | 0.756      | -            | -                | -                | -         |    -6.56 | broky, frozen, karrigan, rain, ropz |
|           32 |     1664 | 2024-05-28 | Virtus.pro        | W   | 0.749      | 0.624        | 0.497 (0.232)    | -                | 1 (0.749) |     9.52 | broky, frozen, karrigan, rain, ropz |
|           31 |     1688 | 2024-05-27 | M80               | W   | 0.743      | 0.624        | -                | 0.587 (0.272)    | 1 (0.743) |     1.44 | broky, frozen, karrigan, rain, ropz |
|           30 |     2213 | 2024-05-10 | Vitality          | L   | 0.629      | -            | -                | -                | -         |    -6.72 | broky, frozen, karrigan, rain, ropz |
|           29 |     2255 | 2024-05-08 | Natus Vincere     | W   | 0.616      | 0.889        | 1.000 (0.547)    | 0.331 (0.181)    | 1 (0.616) |    15.12 | broky, frozen, karrigan, rain, ropz |
|           28 |     2273 | 2024-05-07 | Monte             | W   | 0.609      | -            | -                | -                | 1 (0.609) |     0.38 | broky, frozen, karrigan, rain, ropz |
|           27 |     2505 | 2024-04-26 | Eternal Fire      | W   | 0.535      | 0.889        | 0.743 (0.353)    | 0.458 (0.218)    | 1 (0.535) |     7.85 | broky, frozen, karrigan, rain, ropz |
|           26 |     2534 | 2024-04-25 | Virtus.pro        | W   | 0.529      | 0.889        | 0.497 (0.233)    | 0.323 (0.152)    | 1 (0.529) |     7.52 | broky, frozen, karrigan, rain, ropz |
|           25 |     2553 | 2024-04-24 | Astralis          | L   | 0.522      | -            | -                | -                | -         |    -8.66 | broky, frozen, karrigan, rain, ropz |
|           24 |     2571 | 2024-04-23 | Imperial          | W   | 0.515      | 0.889        | 0.237 (0.108)    | 0.685 (0.314)    | 1 (0.515) |     1.45 | broky, frozen, karrigan, rain, ropz |
|           23 |     2846 | 2024-04-14 | MOUZ              | W   | 0.453      | 0.624        | 1.000 (0.283)    | -                | -         |    10.02 | broky, frozen, karrigan, rain, ropz |
|           22 |     2860 | 2024-04-13 | Astralis          | W   | 0.447      | 0.624        | 0.352 (0.098)    | -                | -         |     6.84 | broky, frozen, karrigan, rain, ropz |
|           21 |     2874 | 2024-04-12 | Liquid            | W   | 0.440      | -            | -                | -                | -         |     3.57 | broky, frozen, karrigan, rain, ropz |
|           20 |     2947 | 2024-04-10 | FlyQuest          | W   | 0.427      | -            | -                | -                | -         |     0.69 | broky, frozen, karrigan, rain, ropz |
|           19 |     2963 | 2024-04-09 | Cloud9            | W   | 0.425      | -            | -                | -                | -         |     0.39 | broky, frozen, karrigan, rain, ropz |
|           18 |     3008 | 2024-04-09 | Astralis          | L   | 0.420      | -            | -                | -                | -         |    -6.99 | broky, frozen, karrigan, rain, ropz |
|           17 |     3039 | 2024-04-08 | Nemiga            | W   | 0.413      | 0.624        | -                | 0.695 (0.179)    | -         |     0.57 | broky, frozen, karrigan, rain, ropz |
|           16 |     3233 | 2024-03-31 | Natus Vincere     | L   | 0.362      | -            | -                | -                | -         |    -2.06 | broky, frozen, karrigan, rain, ropz |
|           15 |     3239 | 2024-03-30 | Vitality          | W   | 0.355      | 1.000        | 0.649 (0.230)    | -                | -         |     7.85 | broky, frozen, karrigan, rain, ropz |
|           14 |     3259 | 2024-03-28 | Spirit            | W   | 0.342      | 1.000        | 1.000 (0.342)    | 0.460 (0.158)    | -         |     8.36 | broky, frozen, karrigan, rain, ropz |
|           13 |     3343 | 2024-03-24 | Complexity        | W   | 0.314      | -            | -                | -                | -         |     4.34 | broky, frozen, karrigan, rain, ropz |
|           12 |     3357 | 2024-03-23 | Imperial          | W   | 0.307      | 1.000        | -                | 0.685 (0.210)    | -         |     0.90 | broky, frozen, karrigan, rain, ropz |
|           11 |     3371 | 2024-03-22 | Eternal Fire      | L   | 0.301      | -            | -                | -                | -         |    -4.50 | broky, frozen, karrigan, rain, ropz |
|           10 |     3381 | 2024-03-21 | FURIA             | W   | 0.296      | -            | -                | -                | -         |     4.98 | broky, frozen, karrigan, rain, ropz |
|            9 |     3393 | 2024-03-21 | HEROIC            | L   | 0.295      | -            | -                | -                | -         |    -6.12 | broky, frozen, karrigan, rain, ropz |
|            8 |     4185 | 2024-02-16 | Eternal Fire      | W   | 0.068      | -            | -                | -                | -         |     1.10 | broky, frozen, karrigan, rain, ropz |
|            7 |     4211 | 2024-02-15 | G2                | L   | 0.061      | -            | -                | -                | -         |    -0.28 | broky, frozen, karrigan, rain, ropz |
|            6 |     4244 | 2024-02-14 | Falcons           | W   | 0.055      | -            | -                | -                | -         |     0.33 | broky, frozen, karrigan, rain, ropz |
|            5 |     4260 | 2024-02-14 | 9 Pandas          | W   | 0.054      | -            | -                | -                | -         |     0.04 | broky, frozen, karrigan, rain, ropz |
|            4 |     4298 | 2024-02-11 | Spirit            | L   | 0.035      | -            | -                | -                | -         |    -0.25 | broky, frozen, karrigan, rain, ropz |
|            3 |     4309 | 2024-02-10 | MOUZ              | W   | 0.028      | -            | -                | -                | -         |     0.63 | broky, frozen, karrigan, rain, ropz |
|            2 |     4323 | 2024-02-09 | G2                | W   | 0.021      | -            | -                | -                | -         |     0.58 | broky, frozen, karrigan, rain, ropz |
|            1 |     4354 | 2024-02-06 | Spirit            | L   | 0.002      | -            | -                | -                | -         |    -0.01 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($207,562.87)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.64) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.874 | $20,000.00     | $17,488.89      |
| 2024-06-02 |      0.782 | $10,000.00     | $7,822.22       |
| 2024-05-12 |      0.641 | $32,000.00     | $20,524.44      |
| 2024-04-14 |      0.453 | $100,000.00    | $45,349.54      |
| 2024-03-31 |      0.362 | $170,000.00    | $61,577.78      |
| 2024-02-11 |      0.035 | $180,000.00    | $6,300.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
