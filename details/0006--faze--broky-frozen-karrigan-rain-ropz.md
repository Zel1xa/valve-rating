### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1742.7<br />
<br />
Final Rank Value (1742.7) = Starting Rank Value (1723.2) + Head To Head Adjustments (19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.848[<sup>1</sup>](#table2)
- Bounty Collected: 0.636[<sup>2</sup>](#table1)
- Opponent Network: 0.239[<sup>2</sup>](#table1)
- LAN Wins: 0.843[<sup>2</sup>](#table1)

The average of these factors is 0.642<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1723.2
- 400 + ( ( 0.642 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1723.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |       28 | 2024-07-31 | Cloud9        | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.05 | broky, frozen, karrigan, rain, ropz |
|           41 |      394 | 2024-07-19 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -7.98 | broky, frozen, karrigan, rain, ropz |
|           40 |      542 | 2024-07-17 | FlyQuest      | W   | 1.000      | 1.000        | -                | 0.298 (0.298)    | 1 (1.000) |     1.42 | broky, frozen, karrigan, rain, ropz |
|           39 |      922 | 2024-06-14 | Vitality      | L   | 0.885      | -            | -                | -                | -         |    -9.52 | broky, frozen, karrigan, rain, ropz |
|           38 |      962 | 2024-06-13 | Natus Vincere | L   | 0.878      | -            | -                | -                | -         |    -7.62 | broky, frozen, karrigan, rain, ropz |
|           37 |      994 | 2024-06-12 | SAW           | W   | 0.871      | 0.729        | -                | 0.545 (0.346)    | 1 (0.871) |     0.99 | broky, frozen, karrigan, rain, ropz |
|           36 |     1470 | 2024-05-31 | G2            | L   | 0.794      | -            | -                | -                | -         |    -6.97 | broky, frozen, karrigan, rain, ropz |
|           35 |     1524 | 2024-05-29 | Spirit        | L   | 0.780      | -            | -                | -                | -         |    -7.33 | broky, frozen, karrigan, rain, ropz |
|           34 |     1547 | 2024-05-28 | Virtus.pro    | W   | 0.773      | 0.624        | 0.494 (0.238)    | -                | 1 (0.773) |     9.50 | broky, frozen, karrigan, rain, ropz |
|           33 |     1571 | 2024-05-27 | M80           | W   | 0.767      | 0.624        | -                | 0.551 (0.264)    | 1 (0.767) |     1.31 | broky, frozen, karrigan, rain, ropz |
|           32 |     2096 | 2024-05-10 | Vitality      | L   | 0.653      | -            | -                | -                | -         |    -7.64 | broky, frozen, karrigan, rain, ropz |
|           31 |     2138 | 2024-05-08 | Natus Vincere | W   | 0.639      | 0.889        | 1.000 (0.568)    | 0.331 (0.188)    | 1 (0.639) |    15.30 | broky, frozen, karrigan, rain, ropz |
|           30 |     2156 | 2024-05-07 | Monte         | W   | 0.633      | -            | -                | -                | 1 (0.633) |     0.36 | broky, frozen, karrigan, rain, ropz |
|           29 |     2388 | 2024-04-26 | Eternal Fire  | W   | 0.559      | 0.889        | 0.752 (0.373)    | 0.462 (0.229)    | 1 (0.559) |     7.94 | broky, frozen, karrigan, rain, ropz |
|           28 |     2417 | 2024-04-25 | Virtus.pro    | W   | 0.553      | 0.889        | 0.494 (0.243)    | 0.327 (0.161)    | 1 (0.553) |     7.63 | broky, frozen, karrigan, rain, ropz |
|           27 |     2436 | 2024-04-24 | Astralis      | L   | 0.546      | -            | -                | -                | -         |    -9.45 | broky, frozen, karrigan, rain, ropz |
|           26 |     2454 | 2024-04-23 | Imperial      | W   | 0.539      | 0.889        | 0.243 (0.116)    | 0.685 (0.328)    | 1 (0.539) |     1.40 | broky, frozen, karrigan, rain, ropz |
|           25 |     2729 | 2024-04-14 | MOUZ          | W   | 0.477      | 0.624        | 1.000 (0.298)    | -                | -         |    10.44 | broky, frozen, karrigan, rain, ropz |
|           24 |     2743 | 2024-04-13 | Astralis      | W   | 0.471      | 0.624        | 0.394 (0.116)    | -                | -         |     6.85 | broky, frozen, karrigan, rain, ropz |
|           23 |     2757 | 2024-04-12 | Liquid        | W   | 0.464      | -            | -                | -                | -         |     2.91 | broky, frozen, karrigan, rain, ropz |
|           22 |     2830 | 2024-04-10 | FlyQuest      | W   | 0.451      | -            | -                | -                | -         |     0.68 | broky, frozen, karrigan, rain, ropz |
|           21 |     2846 | 2024-04-09 | Cloud9        | W   | 0.449      | -            | -                | -                | -         |     0.39 | broky, frozen, karrigan, rain, ropz |
|           20 |     2891 | 2024-04-09 | Astralis      | L   | 0.444      | -            | -                | -                | -         |    -7.76 | broky, frozen, karrigan, rain, ropz |
|           19 |     2922 | 2024-04-08 | Nemiga        | W   | 0.437      | 0.624        | -                | 0.698 (0.190)    | -         |     0.53 | broky, frozen, karrigan, rain, ropz |
|           18 |     3116 | 2024-03-31 | Natus Vincere | L   | 0.386      | -            | -                | -                | -         |    -2.41 | broky, frozen, karrigan, rain, ropz |
|           17 |     3122 | 2024-03-30 | Vitality      | W   | 0.379      | 1.000        | 0.654 (0.248)    | -                | -         |     7.96 | broky, frozen, karrigan, rain, ropz |
|           16 |     3142 | 2024-03-28 | Spirit        | W   | 0.366      | 1.000        | 1.000 (0.366)    | -                | -         |     8.66 | broky, frozen, karrigan, rain, ropz |
|           15 |     3226 | 2024-03-24 | Complexity    | W   | 0.338      | 1.000        | 0.348 (0.117)    | -                | -         |     4.25 | broky, frozen, karrigan, rain, ropz |
|           14 |     3240 | 2024-03-23 | Imperial      | W   | 0.331      | 1.000        | -                | 0.685 (0.227)    | -         |     0.90 | broky, frozen, karrigan, rain, ropz |
|           13 |     3254 | 2024-03-22 | Eternal Fire  | L   | 0.325      | -            | -                | -                | -         |    -5.02 | broky, frozen, karrigan, rain, ropz |
|           12 |     3264 | 2024-03-21 | FURIA         | W   | 0.320      | 1.000        | -                | 0.495 (0.159)    | -         |     5.16 | broky, frozen, karrigan, rain, ropz |
|           11 |     3276 | 2024-03-21 | HEROIC        | L   | 0.318      | -            | -                | -                | -         |    -6.72 | broky, frozen, karrigan, rain, ropz |
|           10 |     4068 | 2024-02-16 | Eternal Fire  | W   | 0.091      | -            | -                | -                | -         |     1.44 | broky, frozen, karrigan, rain, ropz |
|            9 |     4094 | 2024-02-15 | G2            | L   | 0.085      | -            | -                | -                | -         |    -0.47 | broky, frozen, karrigan, rain, ropz |
|            8 |     4127 | 2024-02-14 | Falcons       | W   | 0.079      | -            | -                | -                | -         |     0.46 | broky, frozen, karrigan, rain, ropz |
|            7 |     4143 | 2024-02-14 | 9 Pandas      | W   | 0.077      | -            | -                | -                | -         |     0.04 | broky, frozen, karrigan, rain, ropz |
|            6 |     4181 | 2024-02-11 | Spirit        | L   | 0.059      | -            | -                | -                | -         |    -0.47 | broky, frozen, karrigan, rain, ropz |
|            5 |     4192 | 2024-02-10 | MOUZ          | W   | 0.052      | -            | -                | -                | -         |     1.15 | broky, frozen, karrigan, rain, ropz |
|            4 |     4206 | 2024-02-09 | G2            | W   | 0.045      | -            | -                | -                | -         |     1.18 | broky, frozen, karrigan, rain, ropz |
|            3 |     4237 | 2024-02-06 | Spirit        | L   | 0.025      | -            | -                | -                | -         |    -0.20 | broky, frozen, karrigan, rain, ropz |
|            2 |     4257 | 2024-02-04 | Eternal Fire  | W   | 0.013      | -            | -                | -                | -         |     0.21 | broky, frozen, karrigan, rain, ropz |
|            1 |     4295 | 2024-02-03 | Rebels        | W   | 0.005      | -            | -                | -                | -         |     0.00 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($219,739.46)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.66) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.898 | $20,000.00     | $17,964.54      |
| 2024-06-02 |      0.806 | $10,000.00     | $8,060.05       |
| 2024-05-12 |      0.665 | $32,000.00     | $21,285.48      |
| 2024-04-14 |      0.477 | $100,000.00    | $47,727.78      |
| 2024-03-31 |      0.386 | $170,000.00    | $65,620.79      |
| 2024-02-11 |      0.059 | $180,000.00    | $10,580.83      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
