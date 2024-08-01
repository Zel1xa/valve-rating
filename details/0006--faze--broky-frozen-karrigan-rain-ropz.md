### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1725.2<br />
<br />
Final Rank Value (1725.2) = Starting Rank Value (1713.4) + Head To Head Adjustments (11.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.836[<sup>1</sup>](#table2)
- Bounty Collected: 0.631[<sup>2</sup>](#table1)
- Opponent Network: 0.246[<sup>2</sup>](#table1)
- LAN Wins: 0.841[<sup>2</sup>](#table1)

The average of these factors is 0.638<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1713.4
- 400 + ( ( 0.638 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1713.4


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
|           42 |       11 | 2024-08-01 | G2            | L   | 1.000      | -            | -                | -                | -         |    -6.96 | broky, frozen, karrigan, rain, ropz |
|           41 |       62 | 2024-07-31 | Cloud9        | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.11 | broky, frozen, karrigan, rain, ropz |
|           40 |      433 | 2024-07-19 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -7.86 | broky, frozen, karrigan, rain, ropz |
|           39 |      586 | 2024-07-17 | FlyQuest      | W   | 1.000      | 1.000        | 0.106 (0.106)    | 0.322 (0.322)    | 1 (1.000) |     1.46 | broky, frozen, karrigan, rain, ropz |
|           38 |      965 | 2024-06-14 | Vitality      | L   | 0.879      | -            | -                | -                | -         |    -9.68 | broky, frozen, karrigan, rain, ropz |
|           37 |     1003 | 2024-06-13 | Natus Vincere | L   | 0.872      | -            | -                | -                | -         |    -7.43 | broky, frozen, karrigan, rain, ropz |
|           36 |     1035 | 2024-06-12 | SAW           | W   | 0.865      | 0.729        | -                | 0.544 (0.343)    | 1 (0.865) |     1.00 | broky, frozen, karrigan, rain, ropz |
|           35 |     1528 | 2024-05-31 | G2            | L   | 0.788      | -            | -                | -                | -         |    -6.67 | broky, frozen, karrigan, rain, ropz |
|           34 |     1582 | 2024-05-29 | Spirit        | L   | 0.774      | -            | -                | -                | -         |    -7.19 | broky, frozen, karrigan, rain, ropz |
|           33 |     1605 | 2024-05-28 | Virtus.pro    | W   | 0.767      | 0.624        | 0.484 (0.232)    | 0.326 (0.156)    | 1 (0.767) |     9.09 | broky, frozen, karrigan, rain, ropz |
|           32 |     1629 | 2024-05-27 | M80           | W   | 0.761      | 0.624        | -                | 0.641 (0.304)    | 1 (0.761) |     1.41 | broky, frozen, karrigan, rain, ropz |
|           31 |     2191 | 2024-05-10 | Vitality      | L   | 0.647      | -            | -                | -                | -         |    -7.75 | broky, frozen, karrigan, rain, ropz |
|           30 |     2235 | 2024-05-08 | Natus Vincere | W   | 0.633      | 0.889        | 1.000 (0.563)    | 0.331 (0.187)    | 1 (0.633) |    15.25 | broky, frozen, karrigan, rain, ropz |
|           29 |     2253 | 2024-05-07 | Monte         | W   | 0.627      | -            | -                | -                | 1 (0.627) |     0.36 | broky, frozen, karrigan, rain, ropz |
|           28 |     2489 | 2024-04-26 | Eternal Fire  | W   | 0.553      | 0.889        | 0.757 (0.372)    | 0.461 (0.226)    | 1 (0.553) |     7.82 | broky, frozen, karrigan, rain, ropz |
|           27 |     2517 | 2024-04-25 | Virtus.pro    | W   | 0.547      | 0.889        | 0.484 (0.235)    | 0.326 (0.158)    | 1 (0.547) |     7.31 | broky, frozen, karrigan, rain, ropz |
|           26 |     2536 | 2024-04-24 | Astralis      | L   | 0.540      | -            | -                | -                | -         |    -9.52 | broky, frozen, karrigan, rain, ropz |
|           25 |     2555 | 2024-04-23 | Imperial      | W   | 0.533      | 0.889        | 0.239 (0.113)    | 0.719 (0.341)    | 1 (0.533) |     1.28 | broky, frozen, karrigan, rain, ropz |
|           24 |     2839 | 2024-04-14 | MOUZ          | W   | 0.471      | 0.624        | 1.000 (0.294)    | -                | -         |    10.35 | broky, frozen, karrigan, rain, ropz |
|           23 |     2853 | 2024-04-13 | Astralis      | W   | 0.465      | -            | -                | -                | -         |     6.60 | broky, frozen, karrigan, rain, ropz |
|           22 |     2868 | 2024-04-12 | Liquid        | W   | 0.458      | -            | -                | -                | -         |     3.64 | broky, frozen, karrigan, rain, ropz |
|           21 |     2941 | 2024-04-10 | FlyQuest      | W   | 0.445      | -            | -                | -                | -         |     0.68 | broky, frozen, karrigan, rain, ropz |
|           20 |     2957 | 2024-04-09 | Cloud9        | W   | 0.443      | -            | -                | -                | -         |     0.40 | broky, frozen, karrigan, rain, ropz |
|           19 |     3002 | 2024-04-09 | Astralis      | L   | 0.438      | -            | -                | -                | -         |    -7.79 | broky, frozen, karrigan, rain, ropz |
|           18 |     3033 | 2024-04-08 | Nemiga        | W   | 0.431      | 0.624        | -                | 0.697 (0.187)    | -         |     0.54 | broky, frozen, karrigan, rain, ropz |
|           17 |     3235 | 2024-03-31 | Natus Vincere | L   | 0.380      | -            | -                | -                | -         |    -2.33 | broky, frozen, karrigan, rain, ropz |
|           16 |     3241 | 2024-03-30 | Vitality      | W   | 0.373      | 1.000        | 0.590 (0.220)    | -                | -         |     7.73 | broky, frozen, karrigan, rain, ropz |
|           15 |     3261 | 2024-03-28 | Spirit        | W   | 0.360      | 1.000        | 1.000 (0.360)    | -                | -         |     8.54 | broky, frozen, karrigan, rain, ropz |
|           14 |     3350 | 2024-03-24 | Complexity    | W   | 0.332      | 1.000        | 0.318 (0.105)    | -                | -         |     4.10 | broky, frozen, karrigan, rain, ropz |
|           13 |     3364 | 2024-03-23 | Imperial      | W   | 0.325      | 1.000        | -                | 0.719 (0.234)    | -         |     0.86 | broky, frozen, karrigan, rain, ropz |
|           12 |     3378 | 2024-03-22 | Eternal Fire  | L   | 0.319      | -            | -                | -                | -         |    -4.92 | broky, frozen, karrigan, rain, ropz |
|           11 |     3388 | 2024-03-21 | FURIA         | W   | 0.314      | -            | -                | -                | -         |     5.10 | broky, frozen, karrigan, rain, ropz |
|           10 |     3400 | 2024-03-21 | HEROIC        | L   | 0.312      | -            | -                | -                | -         |    -6.69 | broky, frozen, karrigan, rain, ropz |
|            9 |     4213 | 2024-02-16 | Eternal Fire  | W   | 0.085      | -            | -                | -                | -         |     1.35 | broky, frozen, karrigan, rain, ropz |
|            8 |     4239 | 2024-02-15 | G2            | L   | 0.079      | -            | -                | -                | -         |    -0.42 | broky, frozen, karrigan, rain, ropz |
|            7 |     4272 | 2024-02-14 | Falcons       | W   | 0.073      | -            | -                | -                | -         |     0.41 | broky, frozen, karrigan, rain, ropz |
|            6 |     4288 | 2024-02-14 | 9 Pandas      | W   | 0.071      | -            | -                | -                | -         |     0.04 | broky, frozen, karrigan, rain, ropz |
|            5 |     4335 | 2024-02-11 | Spirit        | L   | 0.053      | -            | -                | -                | -         |    -0.42 | broky, frozen, karrigan, rain, ropz |
|            4 |     4346 | 2024-02-10 | MOUZ          | W   | 0.046      | -            | -                | -                | -         |     1.02 | broky, frozen, karrigan, rain, ropz |
|            3 |     4361 | 2024-02-09 | G2            | W   | 0.039      | -            | -                | -                | -         |     1.03 | broky, frozen, karrigan, rain, ropz |
|            2 |     4392 | 2024-02-06 | Spirit        | L   | 0.019      | -            | -                | -                | -         |    -0.15 | broky, frozen, karrigan, rain, ropz |
|            1 |     4412 | 2024-02-04 | Eternal Fire  | W   | 0.007      | -            | -                | -                | -         |     0.12 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($208,165.09)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.64) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.892 | $20,000.00     | $17,844.44      |
| 2024-06-02 |      0.800 | $10,000.00     | $8,000.00       |
| 2024-05-12 |      0.659 | $32,000.00     | $21,093.33      |
| 2024-04-14 |      0.471 | $100,000.00    | $47,127.31      |
| 2024-03-31 |      0.380 | $170,000.00    | $64,600.00      |
| 2024-02-11 |      0.053 | $180,000.00    | $9,500.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
