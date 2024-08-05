### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1685.9<br />
<br />
Final Rank Value (1685.9) = Starting Rank Value (1683.1) + Head To Head Adjustments (2.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.835[<sup>1</sup>](#table2)
- Bounty Collected: 0.626[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.815[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1683.1
- 400 + ( ( 0.627 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1683.1


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
|           41 |       78 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -20.83 | broky, frozen, karrigan, rain, ropz |
|           40 |      130 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.30 | broky, frozen, karrigan, rain, ropz |
|           39 |      178 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.13 | broky, frozen, karrigan, rain, ropz |
|           38 |      547 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.46 | broky, frozen, karrigan, rain, ropz |
|           37 |      695 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | -                | 0.293 (0.293)    | 1 (1.000) |     1.50 | broky, frozen, karrigan, rain, ropz |
|           36 |     1075 | 2024-06-14 | Vitality          | L   | 0.857      | -            | -                | -                | -         |    -8.50 | broky, frozen, karrigan, rain, ropz |
|           35 |     1115 | 2024-06-13 | Natus Vincere     | L   | 0.850      | -            | -                | -                | -         |    -6.84 | broky, frozen, karrigan, rain, ropz |
|           34 |     1147 | 2024-06-12 | SAW               | W   | 0.843      | 0.729        | -                | 0.539 (0.331)    | 1 (0.843) |     1.07 | broky, frozen, karrigan, rain, ropz |
|           33 |     1623 | 2024-05-31 | G2                | L   | 0.766      | -            | -                | -                | -         |    -5.86 | broky, frozen, karrigan, rain, ropz |
|           32 |     1677 | 2024-05-29 | Spirit            | L   | 0.752      | -            | -                | -                | -         |    -6.57 | broky, frozen, karrigan, rain, ropz |
|           31 |     1700 | 2024-05-28 | Virtus.pro        | W   | 0.745      | 0.624        | 0.497 (0.231)    | -                | 1 (0.745) |     9.46 | broky, frozen, karrigan, rain, ropz |
|           30 |     1724 | 2024-05-27 | M80               | W   | 0.739      | 0.624        | -                | 0.587 (0.270)    | 1 (0.739) |     1.40 | broky, frozen, karrigan, rain, ropz |
|           29 |     2249 | 2024-05-10 | Vitality          | L   | 0.625      | -            | -                | -                | -         |    -6.65 | broky, frozen, karrigan, rain, ropz |
|           28 |     2291 | 2024-05-08 | Natus Vincere     | W   | 0.611      | 0.889        | 1.000 (0.544)    | 0.371 (0.202)    | 1 (0.611) |    15.01 | broky, frozen, karrigan, rain, ropz |
|           27 |     2309 | 2024-05-07 | Monte             | W   | 0.605      | -            | -                | -                | 1 (0.605) |     0.36 | broky, frozen, karrigan, rain, ropz |
|           26 |     2541 | 2024-04-26 | Eternal Fire      | W   | 0.531      | 0.889        | 0.741 (0.350)    | 0.457 (0.216)    | 1 (0.531) |     7.74 | broky, frozen, karrigan, rain, ropz |
|           25 |     2570 | 2024-04-25 | Virtus.pro        | W   | 0.525      | 0.889        | 0.497 (0.232)    | 0.323 (0.150)    | 1 (0.525) |     7.45 | broky, frozen, karrigan, rain, ropz |
|           24 |     2589 | 2024-04-24 | Astralis          | L   | 0.518      | -            | -                | -                | -         |    -7.69 | broky, frozen, karrigan, rain, ropz |
|           23 |     2607 | 2024-04-23 | Imperial          | W   | 0.511      | 0.889        | 0.236 (0.107)    | 0.685 (0.311)    | 1 (0.511) |     1.40 | broky, frozen, karrigan, rain, ropz |
|           22 |     2882 | 2024-04-14 | MOUZ              | W   | 0.449      | 0.624        | 1.000 (0.280)    | -                | -         |     9.91 | broky, frozen, karrigan, rain, ropz |
|           21 |     2896 | 2024-04-13 | Astralis          | W   | 0.443      | 0.624        | 0.390 (0.108)    | -                | -         |     7.60 | broky, frozen, karrigan, rain, ropz |
|           20 |     2910 | 2024-04-12 | Liquid            | W   | 0.436      | -            | -                | -                | -         |     5.02 | broky, frozen, karrigan, rain, ropz |
|           19 |     2983 | 2024-04-10 | FlyQuest          | W   | 0.423      | -            | -                | -                | -         |     0.68 | broky, frozen, karrigan, rain, ropz |
|           18 |     2999 | 2024-04-09 | Cloud9            | W   | 0.421      | -            | -                | -                | -         |     0.40 | broky, frozen, karrigan, rain, ropz |
|           17 |     3044 | 2024-04-09 | Astralis          | L   | 0.416      | -            | -                | -                | -         |    -6.07 | broky, frozen, karrigan, rain, ropz |
|           16 |     3075 | 2024-04-08 | Nemiga            | W   | 0.409      | 0.624        | -                | 0.733 (0.187)    | -         |     0.63 | broky, frozen, karrigan, rain, ropz |
|           15 |     3269 | 2024-03-31 | Natus Vincere     | L   | 0.358      | -            | -                | -                | -         |    -2.00 | broky, frozen, karrigan, rain, ropz |
|           14 |     3275 | 2024-03-30 | Vitality          | W   | 0.351      | 1.000        | 0.648 (0.227)    | -                | -         |     7.82 | broky, frozen, karrigan, rain, ropz |
|           13 |     3295 | 2024-03-28 | Spirit            | W   | 0.338      | 1.000        | 1.000 (0.338)    | 0.460 (0.156)    | -         |     8.28 | broky, frozen, karrigan, rain, ropz |
|           12 |     3379 | 2024-03-24 | Complexity        | W   | 0.310      | 1.000        | 0.342 (0.106)    | -                | -         |     4.42 | broky, frozen, karrigan, rain, ropz |
|           11 |     3393 | 2024-03-23 | Imperial          | W   | 0.303      | 1.000        | -                | 0.685 (0.208)    | -         |     0.88 | broky, frozen, karrigan, rain, ropz |
|           10 |     3407 | 2024-03-22 | Eternal Fire      | L   | 0.297      | -            | -                | -                | -         |    -4.42 | broky, frozen, karrigan, rain, ropz |
|            9 |     3417 | 2024-03-21 | FURIA             | W   | 0.292      | -            | -                | -                | -         |     4.95 | broky, frozen, karrigan, rain, ropz |
|            8 |     3429 | 2024-03-21 | HEROIC            | L   | 0.290      | -            | -                | -                | -         |    -6.02 | broky, frozen, karrigan, rain, ropz |
|            7 |     4221 | 2024-02-16 | Eternal Fire      | W   | 0.064      | -            | -                | -                | -         |     1.04 | broky, frozen, karrigan, rain, ropz |
|            6 |     4247 | 2024-02-15 | G2                | L   | 0.057      | -            | -                | -                | -         |    -0.26 | broky, frozen, karrigan, rain, ropz |
|            5 |     4280 | 2024-02-14 | Falcons           | W   | 0.051      | -            | -                | -                | -         |     0.30 | broky, frozen, karrigan, rain, ropz |
|            4 |     4296 | 2024-02-14 | 9 Pandas          | W   | 0.049      | -            | -                | -                | -         |     0.03 | broky, frozen, karrigan, rain, ropz |
|            3 |     4334 | 2024-02-11 | Spirit            | L   | 0.031      | -            | -                | -                | -         |    -0.22 | broky, frozen, karrigan, rain, ropz |
|            2 |     4345 | 2024-02-10 | MOUZ              | W   | 0.024      | -            | -                | -                | -         |     0.54 | broky, frozen, karrigan, rain, ropz |
|            1 |     4359 | 2024-02-09 | G2                | W   | 0.017      | -            | -                | -                | -         |     0.47 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($205,429.54)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.64) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.870 | $20,000.00     | $17,405.56      |
| 2024-06-02 |      0.778 | $10,000.00     | $7,780.56       |
| 2024-05-12 |      0.637 | $32,000.00     | $20,391.11      |
| 2024-04-14 |      0.449 | $100,000.00    | $44,932.87      |
| 2024-03-31 |      0.358 | $170,000.00    | $60,869.44      |
| 2024-02-11 |      0.031 | $180,000.00    | $5,550.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
