### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1681.1<br />
<br />
Final Rank Value (1681.1) = Starting Rank Value (1677.3) + Head To Head Adjustments (3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.831[<sup>1</sup>](#table2)
- Bounty Collected: 0.622[<sup>2</sup>](#table1)
- Opponent Network: 0.224[<sup>2</sup>](#table1)
- LAN Wins: 0.812[<sup>2</sup>](#table1)

The average of these factors is 0.622<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1677.3
- 400 + ( ( 0.622 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1677.3


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
|           41 |      106 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -20.63 | broky, frozen, karrigan, rain, ropz |
|           40 |      158 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.14 | broky, frozen, karrigan, rain, ropz |
|           39 |      206 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.14 | broky, frozen, karrigan, rain, ropz |
|           38 |      575 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.31 | broky, frozen, karrigan, rain, ropz |
|           37 |      723 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.284 (0.284)    | 1 (1.000) |     1.51 | broky, frozen, karrigan, rain, ropz |
|           36 |     1103 | 2024-06-14 | Vitality          | L   | 0.848      | -            | -                | -                | -         |    -8.29 | broky, frozen, karrigan, rain, ropz |
|           35 |     1143 | 2024-06-13 | Natus Vincere     | L   | 0.841      | -            | -                | -                | -         |    -6.62 | broky, frozen, karrigan, rain, ropz |
|           34 |     1175 | 2024-06-12 | SAW               | W   | 0.834      | 0.729        | -                | 0.528 (0.321)    | 1 (0.834) |     1.09 | broky, frozen, karrigan, rain, ropz |
|           33 |     1651 | 2024-05-31 | G2                | L   | 0.756      | -            | -                | -                | -         |    -5.62 | broky, frozen, karrigan, rain, ropz |
|           32 |     1705 | 2024-05-29 | Spirit            | L   | 0.743      | -            | -                | -                | -         |    -6.35 | broky, frozen, karrigan, rain, ropz |
|           31 |     1728 | 2024-05-28 | Virtus.pro        | W   | 0.736      | 0.624        | 0.498 (0.229)    | 0.316 (0.145)    | 1 (0.736) |     9.46 | broky, frozen, karrigan, rain, ropz |
|           30 |     1752 | 2024-05-27 | M80               | W   | 0.730      | 0.624        | -                | 0.576 (0.262)    | 1 (0.730) |     1.41 | broky, frozen, karrigan, rain, ropz |
|           29 |     2277 | 2024-05-10 | Vitality          | L   | 0.615      | -            | -                | -                | -         |    -6.45 | broky, frozen, karrigan, rain, ropz |
|           28 |     2319 | 2024-05-08 | Natus Vincere     | W   | 0.602      | 0.889        | 1.000 (0.535)    | 0.365 (0.195)    | 1 (0.602) |    14.90 | broky, frozen, karrigan, rain, ropz |
|           27 |     2337 | 2024-05-07 | Monte             | W   | 0.595      | -            | -                | -                | 1 (0.595) |     0.36 | broky, frozen, karrigan, rain, ropz |
|           26 |     2569 | 2024-04-26 | Eternal Fire      | W   | 0.522      | 0.889        | 0.739 (0.343)    | 0.448 (0.208)    | 1 (0.522) |     7.71 | broky, frozen, karrigan, rain, ropz |
|           25 |     2598 | 2024-04-25 | Virtus.pro        | W   | 0.515      | 0.889        | 0.498 (0.228)    | -                | 1 (0.515) |     7.40 | broky, frozen, karrigan, rain, ropz |
|           24 |     2617 | 2024-04-24 | Astralis          | L   | 0.509      | -            | -                | -                | -         |    -7.48 | broky, frozen, karrigan, rain, ropz |
|           23 |     2635 | 2024-04-23 | Imperial          | W   | 0.502      | 0.889        | 0.233 (0.104)    | 0.673 (0.300)    | 1 (0.502) |     1.38 | broky, frozen, karrigan, rain, ropz |
|           22 |     2910 | 2024-04-14 | MOUZ              | W   | 0.440      | 0.624        | 1.000 (0.275)    | -                | -         |     9.78 | broky, frozen, karrigan, rain, ropz |
|           21 |     2924 | 2024-04-13 | Astralis          | W   | 0.434      | 0.624        | 0.389 (0.105)    | -                | -         |     7.51 | broky, frozen, karrigan, rain, ropz |
|           20 |     2938 | 2024-04-12 | Liquid            | W   | 0.427      | -            | -                | -                | -         |     5.00 | broky, frozen, karrigan, rain, ropz |
|           19 |     3011 | 2024-04-10 | FlyQuest          | W   | 0.414      | -            | -                | -                | -         |     0.67 | broky, frozen, karrigan, rain, ropz |
|           18 |     3027 | 2024-04-09 | Cloud9            | W   | 0.412      | -            | -                | -                | -         |     0.38 | broky, frozen, karrigan, rain, ropz |
|           17 |     3072 | 2024-04-09 | Astralis          | L   | 0.406      | -            | -                | -                | -         |    -5.87 | broky, frozen, karrigan, rain, ropz |
|           16 |     3103 | 2024-04-08 | Nemiga            | W   | 0.400      | 0.624        | -                | 0.720 (0.180)    | -         |     0.63 | broky, frozen, karrigan, rain, ropz |
|           15 |     3297 | 2024-03-31 | Natus Vincere     | L   | 0.349      | -            | -                | -                | -         |    -1.90 | broky, frozen, karrigan, rain, ropz |
|           14 |     3303 | 2024-03-30 | Vitality          | W   | 0.342      | 1.000        | 0.647 (0.221)    | -                | -         |     7.67 | broky, frozen, karrigan, rain, ropz |
|           13 |     3323 | 2024-03-28 | Spirit            | W   | 0.329      | 1.000        | 1.000 (0.329)    | 0.451 (0.149)    | -         |     8.11 | broky, frozen, karrigan, rain, ropz |
|           12 |     3407 | 2024-03-24 | Complexity        | W   | 0.301      | -            | -                | -                | -         |     4.34 | broky, frozen, karrigan, rain, ropz |
|           11 |     3421 | 2024-03-23 | Imperial          | W   | 0.294      | 1.000        | -                | 0.673 (0.198)    | -         |     0.85 | broky, frozen, karrigan, rain, ropz |
|           10 |     3435 | 2024-03-22 | Eternal Fire      | L   | 0.288      | -            | -                | -                | -         |    -4.23 | broky, frozen, karrigan, rain, ropz |
|            9 |     3445 | 2024-03-21 | FURIA             | W   | 0.283      | -            | -                | -                | -         |     4.88 | broky, frozen, karrigan, rain, ropz |
|            8 |     3457 | 2024-03-21 | HEROIC            | L   | 0.281      | -            | -                | -                | -         |    -5.79 | broky, frozen, karrigan, rain, ropz |
|            7 |     4249 | 2024-02-16 | Eternal Fire      | W   | 0.054      | -            | -                | -                | -         |     0.90 | broky, frozen, karrigan, rain, ropz |
|            6 |     4275 | 2024-02-15 | G2                | L   | 0.048      | -            | -                | -                | -         |    -0.21 | broky, frozen, karrigan, rain, ropz |
|            5 |     4308 | 2024-02-14 | Falcons           | W   | 0.042      | -            | -                | -                | -         |     0.25 | broky, frozen, karrigan, rain, ropz |
|            4 |     4324 | 2024-02-14 | 9 Pandas          | W   | 0.040      | -            | -                | -                | -         |     0.03 | broky, frozen, karrigan, rain, ropz |
|            3 |     4362 | 2024-02-11 | Spirit            | L   | 0.022      | -            | -                | -                | -         |    -0.15 | broky, frozen, karrigan, rain, ropz |
|            2 |     4373 | 2024-02-10 | MOUZ              | W   | 0.015      | -            | -                | -                | -         |     0.33 | broky, frozen, karrigan, rain, ropz |
|            1 |     4387 | 2024-02-09 | G2                | W   | 0.008      | -            | -                | -                | -         |     0.22 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($200,736.20)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.63) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.861 | $20,000.00     | $17,222.22      |
| 2024-06-02 |      0.769 | $10,000.00     | $7,688.89       |
| 2024-05-12 |      0.628 | $32,000.00     | $20,097.78      |
| 2024-04-14 |      0.440 | $100,000.00    | $44,016.20      |
| 2024-03-31 |      0.349 | $170,000.00    | $59,311.11      |
| 2024-02-11 |      0.022 | $180,000.00    | $3,900.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
