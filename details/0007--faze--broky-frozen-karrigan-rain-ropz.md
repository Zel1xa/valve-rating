### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1684.0<br />
<br />
Final Rank Value (1684.0) = Starting Rank Value (1685.5) + Head To Head Adjustments (-1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.839[<sup>1</sup>](#table2)
- Bounty Collected: 0.628[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.818[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1685.5
- 400 + ( ( 0.629 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1685.5


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
|           42 |       41 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -21.15 | broky, frozen, karrigan, rain, ropz |
|           41 |       91 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.34 | broky, frozen, karrigan, rain, ropz |
|           40 |      140 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.13 | broky, frozen, karrigan, rain, ropz |
|           39 |      508 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.53 | broky, frozen, karrigan, rain, ropz |
|           38 |      656 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.291 (0.291)    | 1 (1.000) |     1.51 | broky, frozen, karrigan, rain, ropz |
|           37 |     1035 | 2024-06-14 | Vitality          | L   | 0.864      | -            | -                | -                | -         |    -8.65 | broky, frozen, karrigan, rain, ropz |
|           36 |     1075 | 2024-06-13 | Natus Vincere     | L   | 0.857      | -            | -                | -                | -         |    -6.98 | broky, frozen, karrigan, rain, ropz |
|           35 |     1107 | 2024-06-12 | SAW               | W   | 0.850      | 0.729        | -                | 0.541 (0.335)    | 1 (0.850) |     1.09 | broky, frozen, karrigan, rain, ropz |
|           34 |     1583 | 2024-05-31 | G2                | L   | 0.773      | -            | -                | -                | -         |    -5.95 | broky, frozen, karrigan, rain, ropz |
|           33 |     1637 | 2024-05-29 | Spirit            | L   | 0.759      | -            | -                | -                | -         |    -6.63 | broky, frozen, karrigan, rain, ropz |
|           32 |     1660 | 2024-05-28 | Virtus.pro        | W   | 0.752      | 0.624        | 0.496 (0.233)    | -                | 1 (0.752) |     9.52 | broky, frozen, karrigan, rain, ropz |
|           31 |     1684 | 2024-05-27 | M80               | W   | 0.746      | 0.624        | -                | 0.587 (0.273)    | 1 (0.746) |     1.43 | broky, frozen, karrigan, rain, ropz |
|           30 |     2209 | 2024-05-10 | Vitality          | L   | 0.632      | -            | -                | -                | -         |    -6.79 | broky, frozen, karrigan, rain, ropz |
|           29 |     2251 | 2024-05-08 | Natus Vincere     | W   | 0.619      | 0.889        | 1.000 (0.550)    | 0.331 (0.182)    | 1 (0.619) |    15.15 | broky, frozen, karrigan, rain, ropz |
|           28 |     2269 | 2024-05-07 | Monte             | W   | 0.612      | -            | -                | -                | 1 (0.612) |     0.38 | broky, frozen, karrigan, rain, ropz |
|           27 |     2501 | 2024-04-26 | Eternal Fire      | W   | 0.538      | 0.889        | 0.743 (0.356)    | 0.458 (0.219)    | 1 (0.538) |     7.87 | broky, frozen, karrigan, rain, ropz |
|           26 |     2529 | 2024-04-25 | Virtus.pro        | W   | 0.532      | 0.889        | 0.496 (0.235)    | 0.324 (0.153)    | 1 (0.532) |     7.53 | broky, frozen, karrigan, rain, ropz |
|           25 |     2548 | 2024-04-24 | Astralis          | L   | 0.525      | -            | -                | -                | -         |    -8.73 | broky, frozen, karrigan, rain, ropz |
|           24 |     2566 | 2024-04-23 | Imperial          | W   | 0.518      | 0.889        | 0.238 (0.109)    | 0.685 (0.316)    | 1 (0.518) |     1.45 | broky, frozen, karrigan, rain, ropz |
|           23 |     2841 | 2024-04-14 | MOUZ              | W   | 0.457      | 0.624        | 1.000 (0.285)    | -                | -         |    10.07 | broky, frozen, karrigan, rain, ropz |
|           22 |     2855 | 2024-04-13 | Astralis          | W   | 0.450      | 0.624        | 0.353 (0.099)    | -                | -         |     6.88 | broky, frozen, karrigan, rain, ropz |
|           21 |     2869 | 2024-04-12 | Liquid            | W   | 0.443      | -            | -                | -                | -         |     3.58 | broky, frozen, karrigan, rain, ropz |
|           20 |     2942 | 2024-04-10 | FlyQuest          | W   | 0.430      | -            | -                | -                | -         |     0.69 | broky, frozen, karrigan, rain, ropz |
|           19 |     2958 | 2024-04-09 | Cloud9            | W   | 0.428      | -            | -                | -                | -         |     0.39 | broky, frozen, karrigan, rain, ropz |
|           18 |     3003 | 2024-04-09 | Astralis          | L   | 0.423      | -            | -                | -                | -         |    -7.05 | broky, frozen, karrigan, rain, ropz |
|           17 |     3034 | 2024-04-08 | Nemiga            | W   | 0.416      | 0.624        | -                | 0.695 (0.180)    | -         |     0.57 | broky, frozen, karrigan, rain, ropz |
|           16 |     3228 | 2024-03-31 | Natus Vincere     | L   | 0.365      | -            | -                | -                | -         |    -2.09 | broky, frozen, karrigan, rain, ropz |
|           15 |     3234 | 2024-03-30 | Vitality          | W   | 0.358      | 1.000        | 0.649 (0.233)    | -                | -         |     7.90 | broky, frozen, karrigan, rain, ropz |
|           14 |     3254 | 2024-03-28 | Spirit            | W   | 0.346      | 1.000        | 1.000 (0.346)    | 0.461 (0.159)    | -         |     8.42 | broky, frozen, karrigan, rain, ropz |
|           13 |     3338 | 2024-03-24 | Complexity        | W   | 0.317      | -            | -                | -                | -         |     4.37 | broky, frozen, karrigan, rain, ropz |
|           12 |     3352 | 2024-03-23 | Imperial          | W   | 0.310      | 1.000        | -                | 0.685 (0.213)    | -         |     0.90 | broky, frozen, karrigan, rain, ropz |
|           11 |     3366 | 2024-03-22 | Eternal Fire      | L   | 0.304      | -            | -                | -                | -         |    -4.56 | broky, frozen, karrigan, rain, ropz |
|           10 |     3376 | 2024-03-21 | FURIA             | W   | 0.299      | -            | -                | -                | -         |     5.01 | broky, frozen, karrigan, rain, ropz |
|            9 |     3388 | 2024-03-21 | HEROIC            | L   | 0.298      | -            | -                | -                | -         |    -6.19 | broky, frozen, karrigan, rain, ropz |
|            8 |     4178 | 2024-02-16 | Eternal Fire      | W   | 0.071      | -            | -                | -                | -         |     1.15 | broky, frozen, karrigan, rain, ropz |
|            7 |     4204 | 2024-02-15 | G2                | L   | 0.064      | -            | -                | -                | -         |    -0.30 | broky, frozen, karrigan, rain, ropz |
|            6 |     4237 | 2024-02-14 | Falcons           | W   | 0.059      | -            | -                | -                | -         |     0.35 | broky, frozen, karrigan, rain, ropz |
|            5 |     4253 | 2024-02-14 | 9 Pandas          | W   | 0.057      | -            | -                | -                | -         |     0.04 | broky, frozen, karrigan, rain, ropz |
|            4 |     4291 | 2024-02-11 | Spirit            | L   | 0.038      | -            | -                | -                | -         |    -0.28 | broky, frozen, karrigan, rain, ropz |
|            3 |     4302 | 2024-02-10 | MOUZ              | W   | 0.031      | -            | -                | -                | -         |     0.70 | broky, frozen, karrigan, rain, ropz |
|            2 |     4316 | 2024-02-09 | G2                | W   | 0.025      | -            | -                | -                | -         |     0.66 | broky, frozen, karrigan, rain, ropz |
|            1 |     4347 | 2024-02-06 | Spirit            | L   | 0.005      | -            | -                | -                | -         |    -0.03 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($209,127.31)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.64) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.877 | $20,000.00     | $17,550.00      |
| 2024-06-02 |      0.785 | $10,000.00     | $7,852.78       |
| 2024-05-12 |      0.644 | $32,000.00     | $20,622.22      |
| 2024-04-14 |      0.457 | $100,000.00    | $45,655.09      |
| 2024-03-31 |      0.365 | $170,000.00    | $62,097.22      |
| 2024-02-11 |      0.038 | $180,000.00    | $6,850.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
