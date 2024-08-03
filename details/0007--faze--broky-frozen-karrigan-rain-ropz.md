### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1687.2<br />
<br />
Final Rank Value (1687.2) = Starting Rank Value (1692.6) + Head To Head Adjustments (-5.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.840[<sup>1</sup>](#table2)
- Bounty Collected: 0.628[<sup>2</sup>](#table1)
- Opponent Network: 0.241[<sup>2</sup>](#table1)
- LAN Wins: 0.818[<sup>2</sup>](#table1)

The average of these factors is 0.632<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1692.6
- 400 + ( ( 0.632 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1692.6


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
|           42 |       34 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -22.26 | broky, frozen, karrigan, rain, ropz |
|           41 |       69 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.58 | broky, frozen, karrigan, rain, ropz |
|           40 |      118 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.13 | broky, frozen, karrigan, rain, ropz |
|           39 |      485 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.54 | broky, frozen, karrigan, rain, ropz |
|           38 |      631 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.302 (0.302)    | 1 (1.000) |     1.48 | broky, frozen, karrigan, rain, ropz |
|           37 |      987 | 2024-06-14 | Vitality          | L   | 0.866      | -            | -                | -                | -         |    -8.72 | broky, frozen, karrigan, rain, ropz |
|           36 |     1025 | 2024-06-13 | Natus Vincere     | L   | 0.859      | -            | -                | -                | -         |    -6.99 | broky, frozen, karrigan, rain, ropz |
|           35 |     1055 | 2024-06-12 | SAW               | W   | 0.852      | 0.729        | -                | 0.560 (0.347)    | 1 (0.852) |     1.04 | broky, frozen, karrigan, rain, ropz |
|           34 |     1520 | 2024-05-31 | G2                | L   | 0.775      | -            | -                | -                | -         |    -6.20 | broky, frozen, karrigan, rain, ropz |
|           33 |     1574 | 2024-05-29 | Spirit            | L   | 0.761      | -            | -                | -                | -         |    -6.65 | broky, frozen, karrigan, rain, ropz |
|           32 |     1597 | 2024-05-28 | Virtus.pro        | W   | 0.754      | 0.624        | 0.496 (0.234)    | -                | 1 (0.754) |     9.27 | broky, frozen, karrigan, rain, ropz |
|           31 |     1621 | 2024-05-27 | M80               | W   | 0.748      | 0.624        | -                | 0.608 (0.284)    | 1 (0.748) |     1.41 | broky, frozen, karrigan, rain, ropz |
|           30 |     2144 | 2024-05-10 | Vitality          | L   | 0.634      | -            | -                | -                | -         |    -6.75 | broky, frozen, karrigan, rain, ropz |
|           29 |     2185 | 2024-05-08 | Natus Vincere     | W   | 0.620      | 0.889        | 1.000 (0.552)    | 0.343 (0.189)    | 1 (0.620) |    15.19 | broky, frozen, karrigan, rain, ropz |
|           28 |     2203 | 2024-05-07 | Monte             | W   | 0.614      | -            | -                | -                | 1 (0.614) |     0.37 | broky, frozen, karrigan, rain, ropz |
|           27 |     2435 | 2024-04-26 | Eternal Fire      | W   | 0.540      | 0.889        | 0.746 (0.358)    | 0.474 (0.228)    | 1 (0.540) |     7.75 | broky, frozen, karrigan, rain, ropz |
|           26 |     2463 | 2024-04-25 | Virtus.pro        | W   | 0.534      | 0.889        | 0.496 (0.235)    | 0.335 (0.159)    | 1 (0.534) |     7.42 | broky, frozen, karrigan, rain, ropz |
|           25 |     2482 | 2024-04-24 | Astralis          | L   | 0.527      | -            | -                | -                | -         |    -8.73 | broky, frozen, karrigan, rain, ropz |
|           24 |     2500 | 2024-04-23 | Imperial          | W   | 0.520      | 0.889        | 0.234 (0.108)    | 0.708 (0.328)    | 1 (0.520) |     1.21 | broky, frozen, karrigan, rain, ropz |
|           23 |     2775 | 2024-04-14 | MOUZ              | W   | 0.458      | 0.624        | 1.000 (0.286)    | -                | -         |     9.03 | broky, frozen, karrigan, rain, ropz |
|           22 |     2789 | 2024-04-13 | Astralis          | W   | 0.452      | -            | -                | -                | -         |     6.91 | broky, frozen, karrigan, rain, ropz |
|           21 |     2803 | 2024-04-12 | Liquid            | W   | 0.445      | -            | -                | -                | -         |     3.56 | broky, frozen, karrigan, rain, ropz |
|           20 |     2876 | 2024-04-10 | FlyQuest          | W   | 0.432      | -            | -                | -                | -         |     0.67 | broky, frozen, karrigan, rain, ropz |
|           19 |     2892 | 2024-04-09 | Cloud9            | W   | 0.430      | -            | -                | -                | -         |     0.39 | broky, frozen, karrigan, rain, ropz |
|           18 |     2937 | 2024-04-09 | Astralis          | L   | 0.425      | -            | -                | -                | -         |    -7.07 | broky, frozen, karrigan, rain, ropz |
|           17 |     2968 | 2024-04-08 | Nemiga            | W   | 0.418      | 0.624        | -                | 0.719 (0.188)    | -         |     0.55 | broky, frozen, karrigan, rain, ropz |
|           16 |     3162 | 2024-03-31 | Natus Vincere     | L   | 0.367      | -            | -                | -                | -         |    -2.12 | broky, frozen, karrigan, rain, ropz |
|           15 |     3168 | 2024-03-30 | Vitality          | W   | 0.360      | 1.000        | 0.650 (0.234)    | -                | -         |     7.94 | broky, frozen, karrigan, rain, ropz |
|           14 |     3188 | 2024-03-28 | Spirit            | W   | 0.347      | 1.000        | 1.000 (0.347)    | 0.477 (0.165)    | -         |     8.46 | broky, frozen, karrigan, rain, ropz |
|           13 |     3269 | 2024-03-24 | Complexity        | W   | 0.319      | 1.000        | 0.313 (0.100)    | -                | -         |     4.37 | broky, frozen, karrigan, rain, ropz |
|           12 |     3282 | 2024-03-23 | Imperial          | W   | 0.312      | 1.000        | -                | 0.708 (0.221)    | -         |     0.76 | broky, frozen, karrigan, rain, ropz |
|           11 |     3295 | 2024-03-22 | Eternal Fire      | L   | 0.306      | -            | -                | -                | -         |    -4.65 | broky, frozen, karrigan, rain, ropz |
|           10 |     3305 | 2024-03-21 | FURIA             | W   | 0.301      | -            | -                | -                | -         |     4.96 | broky, frozen, karrigan, rain, ropz |
|            9 |     3317 | 2024-03-21 | HEROIC            | L   | 0.299      | -            | -                | -                | -         |    -6.28 | broky, frozen, karrigan, rain, ropz |
|            8 |     4105 | 2024-02-16 | Eternal Fire      | W   | 0.072      | -            | -                | -                | -         |     1.16 | broky, frozen, karrigan, rain, ropz |
|            7 |     4131 | 2024-02-15 | G2                | L   | 0.066      | -            | -                | -                | -         |    -0.32 | broky, frozen, karrigan, rain, ropz |
|            6 |     4164 | 2024-02-14 | Falcons           | W   | 0.060      | -            | -                | -                | -         |     0.35 | broky, frozen, karrigan, rain, ropz |
|            5 |     4180 | 2024-02-14 | 9 Pandas          | W   | 0.058      | -            | -                | -                | -         |     0.04 | broky, frozen, karrigan, rain, ropz |
|            4 |     4218 | 2024-02-11 | Spirit            | L   | 0.040      | -            | -                | -                | -         |    -0.29 | broky, frozen, karrigan, rain, ropz |
|            3 |     4229 | 2024-02-10 | MOUZ              | W   | 0.033      | -            | -                | -                | -         |     0.65 | broky, frozen, karrigan, rain, ropz |
|            2 |     4243 | 2024-02-09 | G2                | W   | 0.026      | -            | -                | -                | -         |     0.70 | broky, frozen, karrigan, rain, ropz |
|            1 |     4274 | 2024-02-06 | Spirit            | L   | 0.006      | -            | -                | -                | -         |    -0.04 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($210,004.35)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.64) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.879 | $20,000.00     | $17,584.26      |
| 2024-06-02 |      0.787 | $10,000.00     | $7,869.91       |
| 2024-05-12 |      0.646 | $32,000.00     | $20,677.04      |
| 2024-04-14 |      0.458 | $100,000.00    | $45,826.39      |
| 2024-03-31 |      0.367 | $170,000.00    | $62,388.43      |
| 2024-02-11 |      0.040 | $180,000.00    | $7,158.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
