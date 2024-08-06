### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1682.5<br />
<br />
Final Rank Value (1682.5) = Starting Rank Value (1678.9) + Head To Head Adjustments (3.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.832[<sup>1</sup>](#table2)
- Bounty Collected: 0.623[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.813[<sup>2</sup>](#table1)

The average of these factors is 0.623<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1678.9
- 400 + ( ( 0.623 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1678.9


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
|           41 |      102 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -20.67 | broky, frozen, karrigan, rain, ropz |
|           40 |      154 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.19 | broky, frozen, karrigan, rain, ropz |
|           39 |      202 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.14 | broky, frozen, karrigan, rain, ropz |
|           38 |      571 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.35 | broky, frozen, karrigan, rain, ropz |
|           37 |      719 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.285 (0.285)    | 1 (1.000) |     1.51 | broky, frozen, karrigan, rain, ropz |
|           36 |     1099 | 2024-06-14 | Vitality          | L   | 0.851      | -            | -                | -                | -         |    -8.35 | broky, frozen, karrigan, rain, ropz |
|           35 |     1139 | 2024-06-13 | Natus Vincere     | L   | 0.843      | -            | -                | -                | -         |    -6.68 | broky, frozen, karrigan, rain, ropz |
|           34 |     1171 | 2024-06-12 | SAW               | W   | 0.836      | 0.729        | -                | 0.529 (0.323)    | 1 (0.836) |     1.08 | broky, frozen, karrigan, rain, ropz |
|           33 |     1647 | 2024-05-31 | G2                | L   | 0.759      | -            | -                | -                | -         |    -5.69 | broky, frozen, karrigan, rain, ropz |
|           32 |     1701 | 2024-05-29 | Spirit            | L   | 0.745      | -            | -                | -                | -         |    -6.41 | broky, frozen, karrigan, rain, ropz |
|           31 |     1724 | 2024-05-28 | Virtus.pro        | W   | 0.739      | 0.624        | 0.498 (0.230)    | 0.316 (0.146)    | 1 (0.739) |     9.46 | broky, frozen, karrigan, rain, ropz |
|           30 |     1748 | 2024-05-27 | M80               | W   | 0.732      | 0.624        | -                | 0.576 (0.263)    | 1 (0.732) |     1.41 | broky, frozen, karrigan, rain, ropz |
|           29 |     2273 | 2024-05-10 | Vitality          | L   | 0.618      | -            | -                | -                | -         |    -6.50 | broky, frozen, karrigan, rain, ropz |
|           28 |     2315 | 2024-05-08 | Natus Vincere     | W   | 0.605      | 0.889        | 1.000 (0.538)    | 0.365 (0.196)    | 1 (0.605) |    14.93 | broky, frozen, karrigan, rain, ropz |
|           27 |     2333 | 2024-05-07 | Monte             | W   | 0.598      | -            | -                | -                | 1 (0.598) |     0.36 | broky, frozen, karrigan, rain, ropz |
|           26 |     2565 | 2024-04-26 | Eternal Fire      | W   | 0.524      | 0.889        | 0.739 (0.345)    | 0.449 (0.209)    | 1 (0.524) |     7.73 | broky, frozen, karrigan, rain, ropz |
|           25 |     2594 | 2024-04-25 | Virtus.pro        | W   | 0.518      | 0.889        | 0.498 (0.229)    | -                | 1 (0.518) |     7.41 | broky, frozen, karrigan, rain, ropz |
|           24 |     2613 | 2024-04-24 | Astralis          | L   | 0.511      | -            | -                | -                | -         |    -7.54 | broky, frozen, karrigan, rain, ropz |
|           23 |     2631 | 2024-04-23 | Imperial          | W   | 0.505      | 0.889        | 0.234 (0.105)    | 0.674 (0.302)    | 1 (0.505) |     1.38 | broky, frozen, karrigan, rain, ropz |
|           22 |     2906 | 2024-04-14 | MOUZ              | W   | 0.443      | 0.624        | 1.000 (0.276)    | -                | -         |     9.82 | broky, frozen, karrigan, rain, ropz |
|           21 |     2920 | 2024-04-13 | Astralis          | W   | 0.436      | 0.624        | 0.389 (0.106)    | -                | -         |     7.53 | broky, frozen, karrigan, rain, ropz |
|           20 |     2934 | 2024-04-12 | Liquid            | W   | 0.429      | -            | -                | -                | -         |     5.01 | broky, frozen, karrigan, rain, ropz |
|           19 |     3007 | 2024-04-10 | FlyQuest          | W   | 0.416      | -            | -                | -                | -         |     0.67 | broky, frozen, karrigan, rain, ropz |
|           18 |     3023 | 2024-04-09 | Cloud9            | W   | 0.415      | -            | -                | -                | -         |     0.39 | broky, frozen, karrigan, rain, ropz |
|           17 |     3068 | 2024-04-09 | Astralis          | L   | 0.409      | -            | -                | -                | -         |    -5.92 | broky, frozen, karrigan, rain, ropz |
|           16 |     3099 | 2024-04-08 | Nemiga            | W   | 0.402      | 0.624        | -                | 0.721 (0.181)    | -         |     0.63 | broky, frozen, karrigan, rain, ropz |
|           15 |     3293 | 2024-03-31 | Natus Vincere     | L   | 0.351      | -            | -                | -                | -         |    -1.93 | broky, frozen, karrigan, rain, ropz |
|           14 |     3299 | 2024-03-30 | Vitality          | W   | 0.344      | 1.000        | 0.647 (0.223)    | -                | -         |     7.71 | broky, frozen, karrigan, rain, ropz |
|           13 |     3319 | 2024-03-28 | Spirit            | W   | 0.332      | 1.000        | 1.000 (0.332)    | 0.452 (0.150)    | -         |     8.16 | broky, frozen, karrigan, rain, ropz |
|           12 |     3403 | 2024-03-24 | Complexity        | W   | 0.303      | -            | -                | -                | -         |     4.36 | broky, frozen, karrigan, rain, ropz |
|           11 |     3417 | 2024-03-23 | Imperial          | W   | 0.296      | 1.000        | -                | 0.674 (0.200)    | -         |     0.85 | broky, frozen, karrigan, rain, ropz |
|           10 |     3431 | 2024-03-22 | Eternal Fire      | L   | 0.290      | -            | -                | -                | -         |    -4.28 | broky, frozen, karrigan, rain, ropz |
|            9 |     3441 | 2024-03-21 | FURIA             | W   | 0.285      | -            | -                | -                | -         |     4.90 | broky, frozen, karrigan, rain, ropz |
|            8 |     3453 | 2024-03-21 | HEROIC            | L   | 0.284      | -            | -                | -                | -         |    -5.85 | broky, frozen, karrigan, rain, ropz |
|            7 |     4245 | 2024-02-16 | Eternal Fire      | W   | 0.057      | -            | -                | -                | -         |     0.94 | broky, frozen, karrigan, rain, ropz |
|            6 |     4271 | 2024-02-15 | G2                | L   | 0.050      | -            | -                | -                | -         |    -0.23 | broky, frozen, karrigan, rain, ropz |
|            5 |     4304 | 2024-02-14 | Falcons           | W   | 0.045      | -            | -                | -                | -         |     0.27 | broky, frozen, karrigan, rain, ropz |
|            4 |     4320 | 2024-02-14 | 9 Pandas          | W   | 0.043      | -            | -                | -                | -         |     0.03 | broky, frozen, karrigan, rain, ropz |
|            3 |     4358 | 2024-02-11 | Spirit            | L   | 0.024      | -            | -                | -                | -         |    -0.17 | broky, frozen, karrigan, rain, ropz |
|            2 |     4369 | 2024-02-10 | MOUZ              | W   | 0.017      | -            | -                | -                | -         |     0.39 | broky, frozen, karrigan, rain, ropz |
|            1 |     4383 | 2024-02-09 | G2                | W   | 0.011      | -            | -                | -                | -         |     0.29 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($202,016.20)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.63) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.864 | $20,000.00     | $17,272.22      |
| 2024-06-02 |      0.771 | $10,000.00     | $7,713.89       |
| 2024-05-12 |      0.631 | $32,000.00     | $20,177.78      |
| 2024-04-14 |      0.443 | $100,000.00    | $44,266.20      |
| 2024-03-31 |      0.351 | $170,000.00    | $59,736.11      |
| 2024-02-11 |      0.024 | $180,000.00    | $4,350.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
