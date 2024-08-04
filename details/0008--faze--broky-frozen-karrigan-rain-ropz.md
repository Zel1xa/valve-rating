### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1686.2<br />
<br />
Final Rank Value (1686.2) = Starting Rank Value (1683.7) + Head To Head Adjustments (2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.837[<sup>1</sup>](#table2)
- Bounty Collected: 0.627[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.816[<sup>2</sup>](#table1)

The average of these factors is 0.628<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1683.7
- 400 + ( ( 0.628 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1683.7


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
|           42 |       52 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -20.86 | broky, frozen, karrigan, rain, ropz |
|           41 |      102 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.32 | broky, frozen, karrigan, rain, ropz |
|           40 |      153 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.13 | broky, frozen, karrigan, rain, ropz |
|           39 |      519 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.53 | broky, frozen, karrigan, rain, ropz |
|           38 |      667 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | -                | 0.294 (0.294)    | 1 (1.000) |     1.51 | broky, frozen, karrigan, rain, ropz |
|           37 |     1047 | 2024-06-14 | Vitality          | L   | 0.861      | -            | -                | -                | -         |    -8.54 | broky, frozen, karrigan, rain, ropz |
|           36 |     1087 | 2024-06-13 | Natus Vincere     | L   | 0.853      | -            | -                | -                | -         |    -6.94 | broky, frozen, karrigan, rain, ropz |
|           35 |     1119 | 2024-06-12 | SAW               | W   | 0.846      | 0.729        | -                | 0.540 (0.333)    | 1 (0.846) |     1.07 | broky, frozen, karrigan, rain, ropz |
|           34 |     1595 | 2024-05-31 | G2                | L   | 0.769      | -            | -                | -                | -         |    -5.91 | broky, frozen, karrigan, rain, ropz |
|           33 |     1649 | 2024-05-29 | Spirit            | L   | 0.755      | -            | -                | -                | -         |    -6.65 | broky, frozen, karrigan, rain, ropz |
|           32 |     1672 | 2024-05-28 | Virtus.pro        | W   | 0.749      | 0.624        | 0.497 (0.232)    | -                | 1 (0.749) |     9.46 | broky, frozen, karrigan, rain, ropz |
|           31 |     1696 | 2024-05-27 | M80               | W   | 0.742      | 0.624        | -                | 0.587 (0.272)    | 1 (0.742) |     1.42 | broky, frozen, karrigan, rain, ropz |
|           30 |     2221 | 2024-05-10 | Vitality          | L   | 0.628      | -            | -                | -                | -         |    -6.70 | broky, frozen, karrigan, rain, ropz |
|           29 |     2263 | 2024-05-08 | Natus Vincere     | W   | 0.615      | 0.889        | 1.000 (0.547)    | 0.331 (0.181)    | 1 (0.615) |    15.05 | broky, frozen, karrigan, rain, ropz |
|           28 |     2281 | 2024-05-07 | Monte             | W   | 0.608      | -            | -                | -                | 1 (0.608) |     0.37 | broky, frozen, karrigan, rain, ropz |
|           27 |     2513 | 2024-04-26 | Eternal Fire      | W   | 0.534      | 0.889        | 0.742 (0.353)    | 0.458 (0.217)    | 1 (0.534) |     7.80 | broky, frozen, karrigan, rain, ropz |
|           26 |     2542 | 2024-04-25 | Virtus.pro        | W   | 0.528      | 0.889        | 0.497 (0.233)    | 0.323 (0.152)    | 1 (0.528) |     7.47 | broky, frozen, karrigan, rain, ropz |
|           25 |     2561 | 2024-04-24 | Astralis          | L   | 0.521      | -            | -                | -                | -         |    -7.76 | broky, frozen, karrigan, rain, ropz |
|           24 |     2579 | 2024-04-23 | Imperial          | W   | 0.515      | 0.889        | 0.237 (0.108)    | 0.685 (0.313)    | 1 (0.515) |     1.42 | broky, frozen, karrigan, rain, ropz |
|           23 |     2854 | 2024-04-14 | MOUZ              | W   | 0.453      | 0.624        | 1.000 (0.283)    | -                | -         |     9.98 | broky, frozen, karrigan, rain, ropz |
|           22 |     2868 | 2024-04-13 | Astralis          | W   | 0.446      | 0.624        | 0.391 (0.109)    | -                | -         |     7.65 | broky, frozen, karrigan, rain, ropz |
|           21 |     2882 | 2024-04-12 | Liquid            | W   | 0.439      | 0.624        | 0.384 (0.105)    | -                | -         |     4.99 | broky, frozen, karrigan, rain, ropz |
|           20 |     2955 | 2024-04-10 | FlyQuest          | W   | 0.426      | -            | -                | -                | -         |     0.69 | broky, frozen, karrigan, rain, ropz |
|           19 |     2971 | 2024-04-09 | Cloud9            | W   | 0.425      | -            | -                | -                | -         |     0.38 | broky, frozen, karrigan, rain, ropz |
|           18 |     3016 | 2024-04-09 | Astralis          | L   | 0.419      | -            | -                | -                | -         |    -6.13 | broky, frozen, karrigan, rain, ropz |
|           17 |     3047 | 2024-04-08 | Nemiga            | W   | 0.412      | 0.624        | -                | 0.695 (0.179)    | -         |     0.57 | broky, frozen, karrigan, rain, ropz |
|           16 |     3241 | 2024-03-31 | Natus Vincere     | L   | 0.362      | -            | -                | -                | -         |    -2.04 | broky, frozen, karrigan, rain, ropz |
|           15 |     3247 | 2024-03-30 | Vitality          | W   | 0.354      | 1.000        | 0.649 (0.230)    | -                | -         |     7.89 | broky, frozen, karrigan, rain, ropz |
|           14 |     3267 | 2024-03-28 | Spirit            | W   | 0.342      | 1.000        | 1.000 (0.342)    | 0.460 (0.157)    | -         |     8.35 | broky, frozen, karrigan, rain, ropz |
|           13 |     3351 | 2024-03-24 | Complexity        | W   | 0.313      | -            | -                | -                | -         |     4.34 | broky, frozen, karrigan, rain, ropz |
|           12 |     3365 | 2024-03-23 | Imperial          | W   | 0.307      | 1.000        | -                | 0.685 (0.210)    | -         |     0.89 | broky, frozen, karrigan, rain, ropz |
|           11 |     3379 | 2024-03-22 | Eternal Fire      | L   | 0.300      | -            | -                | -                | -         |    -4.47 | broky, frozen, karrigan, rain, ropz |
|           10 |     3389 | 2024-03-21 | FURIA             | W   | 0.296      | -            | -                | -                | -         |     4.98 | broky, frozen, karrigan, rain, ropz |
|            9 |     3401 | 2024-03-21 | HEROIC            | L   | 0.294      | -            | -                | -                | -         |    -6.10 | broky, frozen, karrigan, rain, ropz |
|            8 |     4193 | 2024-02-16 | Eternal Fire      | W   | 0.067      | -            | -                | -                | -         |     1.09 | broky, frozen, karrigan, rain, ropz |
|            7 |     4219 | 2024-02-15 | G2                | L   | 0.060      | -            | -                | -                | -         |    -0.28 | broky, frozen, karrigan, rain, ropz |
|            6 |     4252 | 2024-02-14 | Falcons           | W   | 0.055      | -            | -                | -                | -         |     0.32 | broky, frozen, karrigan, rain, ropz |
|            5 |     4268 | 2024-02-14 | 9 Pandas          | W   | 0.053      | -            | -                | -                | -         |     0.04 | broky, frozen, karrigan, rain, ropz |
|            4 |     4306 | 2024-02-11 | Spirit            | L   | 0.034      | -            | -                | -                | -         |    -0.25 | broky, frozen, karrigan, rain, ropz |
|            3 |     4317 | 2024-02-10 | MOUZ              | W   | 0.027      | -            | -                | -                | -         |     0.61 | broky, frozen, karrigan, rain, ropz |
|            2 |     4331 | 2024-02-09 | G2                | W   | 0.021      | -            | -                | -                | -         |     0.56 | broky, frozen, karrigan, rain, ropz |
|            1 |     4362 | 2024-02-06 | Spirit            | L   | 0.001      | -            | -                | -                | -         |    -0.01 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($207,195.46)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.64) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.874 | $20,000.00     | $17,474.54      |
| 2024-06-02 |      0.782 | $10,000.00     | $7,815.05       |
| 2024-05-12 |      0.641 | $32,000.00     | $20,501.48      |
| 2024-04-14 |      0.453 | $100,000.00    | $45,277.78      |
| 2024-03-31 |      0.362 | $170,000.00    | $61,455.79      |
| 2024-02-11 |      0.034 | $180,000.00    | $6,170.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
