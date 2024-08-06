### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1680.6<br />
<br />
Final Rank Value (1680.6) = Starting Rank Value (1676.8) + Head To Head Adjustments (3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.830[<sup>1</sup>](#table2)
- Bounty Collected: 0.622[<sup>2</sup>](#table1)
- Opponent Network: 0.219[<sup>2</sup>](#table1)
- LAN Wins: 0.811[<sup>2</sup>](#table1)

The average of these factors is 0.621<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1676.8
- 400 + ( ( 0.621 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1676.8


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
|           41 |      118 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -20.62 | broky, frozen, karrigan, rain, ropz |
|           40 |      170 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.13 | broky, frozen, karrigan, rain, ropz |
|           39 |      218 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.14 | broky, frozen, karrigan, rain, ropz |
|           38 |      587 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.29 | broky, frozen, karrigan, rain, ropz |
|           37 |      735 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.277 (0.277)    | 1 (1.000) |     1.51 | broky, frozen, karrigan, rain, ropz |
|           36 |     1115 | 2024-06-14 | Vitality          | L   | 0.847      | -            | -                | -                | -         |    -8.27 | broky, frozen, karrigan, rain, ropz |
|           35 |     1155 | 2024-06-13 | Natus Vincere     | L   | 0.840      | -            | -                | -                | -         |    -6.60 | broky, frozen, karrigan, rain, ropz |
|           34 |     1187 | 2024-06-12 | SAW               | W   | 0.832      | 0.729        | -                | 0.516 (0.313)    | 1 (0.832) |     1.08 | broky, frozen, karrigan, rain, ropz |
|           33 |     1663 | 2024-05-31 | G2                | L   | 0.755      | -            | -                | -                | -         |    -5.60 | broky, frozen, karrigan, rain, ropz |
|           32 |     1717 | 2024-05-29 | Spirit            | L   | 0.742      | -            | -                | -                | -         |    -6.32 | broky, frozen, karrigan, rain, ropz |
|           31 |     1740 | 2024-05-28 | Virtus.pro        | W   | 0.735      | 0.624        | 0.498 (0.229)    | 0.308 (0.142)    | 1 (0.735) |     9.45 | broky, frozen, karrigan, rain, ropz |
|           30 |     1764 | 2024-05-27 | M80               | W   | 0.728      | 0.624        | -                | 0.563 (0.256)    | 1 (0.728) |     1.41 | broky, frozen, karrigan, rain, ropz |
|           29 |     2289 | 2024-05-10 | Vitality          | L   | 0.614      | -            | -                | -                | -         |    -6.42 | broky, frozen, karrigan, rain, ropz |
|           28 |     2331 | 2024-05-08 | Natus Vincere     | W   | 0.601      | 0.889        | 1.000 (0.534)    | 0.357 (0.191)    | 1 (0.601) |    14.88 | broky, frozen, karrigan, rain, ropz |
|           27 |     2349 | 2024-05-07 | Monte             | W   | 0.594      | -            | -                | -                | 1 (0.594) |     0.37 | broky, frozen, karrigan, rain, ropz |
|           26 |     2581 | 2024-04-26 | Eternal Fire      | W   | 0.520      | 0.889        | 0.738 (0.342)    | 0.438 (0.202)    | 1 (0.520) |     7.72 | broky, frozen, karrigan, rain, ropz |
|           25 |     2610 | 2024-04-25 | Virtus.pro        | W   | 0.514      | 0.889        | 0.498 (0.228)    | -                | 1 (0.514) |     7.38 | broky, frozen, karrigan, rain, ropz |
|           24 |     2629 | 2024-04-24 | Astralis          | L   | 0.508      | -            | -                | -                | -         |    -7.46 | broky, frozen, karrigan, rain, ropz |
|           23 |     2647 | 2024-04-23 | Imperial          | W   | 0.501      | 0.889        | 0.233 (0.104)    | 0.658 (0.293)    | 1 (0.501) |     1.37 | broky, frozen, karrigan, rain, ropz |
|           22 |     2922 | 2024-04-14 | MOUZ              | W   | 0.439      | 0.624        | 1.000 (0.274)    | -                | -         |     9.75 | broky, frozen, karrigan, rain, ropz |
|           21 |     2936 | 2024-04-13 | Astralis          | W   | 0.432      | 0.624        | 0.389 (0.105)    | -                | -         |     7.49 | broky, frozen, karrigan, rain, ropz |
|           20 |     2950 | 2024-04-12 | Liquid            | W   | 0.426      | -            | -                | -                | -         |     5.00 | broky, frozen, karrigan, rain, ropz |
|           19 |     3023 | 2024-04-10 | FlyQuest          | W   | 0.413      | -            | -                | -                | -         |     0.67 | broky, frozen, karrigan, rain, ropz |
|           18 |     3039 | 2024-04-09 | Cloud9            | W   | 0.411      | -            | -                | -                | -         |     0.38 | broky, frozen, karrigan, rain, ropz |
|           17 |     3084 | 2024-04-09 | Astralis          | L   | 0.405      | -            | -                | -                | -         |    -5.85 | broky, frozen, karrigan, rain, ropz |
|           16 |     3115 | 2024-04-08 | Nemiga            | W   | 0.398      | 0.624        | -                | 0.704 (0.175)    | -         |     0.63 | broky, frozen, karrigan, rain, ropz |
|           15 |     3309 | 2024-03-31 | Natus Vincere     | L   | 0.348      | -            | -                | -                | -         |    -1.89 | broky, frozen, karrigan, rain, ropz |
|           14 |     3315 | 2024-03-30 | Vitality          | W   | 0.340      | 1.000        | 0.647 (0.220)    | -                | -         |     7.65 | broky, frozen, karrigan, rain, ropz |
|           13 |     3335 | 2024-03-28 | Spirit            | W   | 0.328      | 1.000        | 1.000 (0.328)    | 0.441 (0.145)    | -         |     8.09 | broky, frozen, karrigan, rain, ropz |
|           12 |     3419 | 2024-03-24 | Complexity        | W   | 0.299      | -            | -                | -                | -         |     4.33 | broky, frozen, karrigan, rain, ropz |
|           11 |     3433 | 2024-03-23 | Imperial          | W   | 0.293      | 1.000        | -                | 0.658 (0.193)    | -         |     0.84 | broky, frozen, karrigan, rain, ropz |
|           10 |     3447 | 2024-03-22 | Eternal Fire      | L   | 0.286      | -            | -                | -                | -         |    -4.20 | broky, frozen, karrigan, rain, ropz |
|            9 |     3457 | 2024-03-21 | FURIA             | W   | 0.282      | -            | -                | -                | -         |     4.85 | broky, frozen, karrigan, rain, ropz |
|            8 |     3469 | 2024-03-21 | HEROIC            | L   | 0.280      | -            | -                | -                | -         |    -5.77 | broky, frozen, karrigan, rain, ropz |
|            7 |     4261 | 2024-02-16 | Eternal Fire      | W   | 0.053      | -            | -                | -                | -         |     0.88 | broky, frozen, karrigan, rain, ropz |
|            6 |     4287 | 2024-02-15 | G2                | L   | 0.046      | -            | -                | -                | -         |    -0.21 | broky, frozen, karrigan, rain, ropz |
|            5 |     4320 | 2024-02-14 | Falcons           | W   | 0.041      | -            | -                | -                | -         |     0.24 | broky, frozen, karrigan, rain, ropz |
|            4 |     4336 | 2024-02-14 | 9 Pandas          | W   | 0.039      | -            | -                | -                | -         |     0.03 | broky, frozen, karrigan, rain, ropz |
|            3 |     4374 | 2024-02-11 | Spirit            | L   | 0.020      | -            | -                | -                | -         |    -0.14 | broky, frozen, karrigan, rain, ropz |
|            2 |     4385 | 2024-02-10 | MOUZ              | W   | 0.014      | -            | -                | -                | -         |     0.31 | broky, frozen, karrigan, rain, ropz |
|            1 |     4399 | 2024-02-09 | G2                | W   | 0.007      | -            | -                | -                | -         |     0.19 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($200,119.91)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.62) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.860 | $20,000.00     | $17,198.15      |
| 2024-06-02 |      0.768 | $10,000.00     | $7,676.85       |
| 2024-05-12 |      0.627 | $32,000.00     | $20,059.26      |
| 2024-04-14 |      0.439 | $100,000.00    | $43,895.83      |
| 2024-03-31 |      0.348 | $170,000.00    | $59,106.48      |
| 2024-02-11 |      0.020 | $180,000.00    | $3,683.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
