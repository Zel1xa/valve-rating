### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1680.9<br />
<br />
Final Rank Value (1680.9) = Starting Rank Value (1677.1) + Head To Head Adjustments (3.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.831[<sup>1</sup>](#table2)
- Bounty Collected: 0.622[<sup>2</sup>](#table1)
- Opponent Network: 0.219[<sup>2</sup>](#table1)
- LAN Wins: 0.812[<sup>2</sup>](#table1)

The average of these factors is 0.621<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1677.1
- 400 + ( ( 0.621 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1677.1


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
|           41 |      113 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -20.63 | broky, frozen, karrigan, rain, ropz |
|           40 |      165 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.14 | broky, frozen, karrigan, rain, ropz |
|           39 |      213 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.14 | broky, frozen, karrigan, rain, ropz |
|           38 |      582 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.30 | broky, frozen, karrigan, rain, ropz |
|           37 |      730 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.278 (0.278)    | 1 (1.000) |     1.51 | broky, frozen, karrigan, rain, ropz |
|           36 |     1110 | 2024-06-14 | Vitality          | L   | 0.847      | -            | -                | -                | -         |    -8.29 | broky, frozen, karrigan, rain, ropz |
|           35 |     1150 | 2024-06-13 | Natus Vincere     | L   | 0.840      | -            | -                | -                | -         |    -6.61 | broky, frozen, karrigan, rain, ropz |
|           34 |     1182 | 2024-06-12 | SAW               | W   | 0.833      | 0.729        | -                | 0.516 (0.314)    | 1 (0.833) |     1.08 | broky, frozen, karrigan, rain, ropz |
|           33 |     1658 | 2024-05-31 | G2                | L   | 0.756      | -            | -                | -                | -         |    -5.61 | broky, frozen, karrigan, rain, ropz |
|           32 |     1712 | 2024-05-29 | Spirit            | L   | 0.742      | -            | -                | -                | -         |    -6.34 | broky, frozen, karrigan, rain, ropz |
|           31 |     1735 | 2024-05-28 | Virtus.pro        | W   | 0.735      | 0.624        | 0.498 (0.229)    | 0.309 (0.142)    | 1 (0.735) |     9.45 | broky, frozen, karrigan, rain, ropz |
|           30 |     1759 | 2024-05-27 | M80               | W   | 0.729      | 0.624        | -                | 0.563 (0.256)    | 1 (0.729) |     1.41 | broky, frozen, karrigan, rain, ropz |
|           29 |     2284 | 2024-05-10 | Vitality          | L   | 0.615      | -            | -                | -                | -         |    -6.44 | broky, frozen, karrigan, rain, ropz |
|           28 |     2326 | 2024-05-08 | Natus Vincere     | W   | 0.602      | 0.889        | 1.000 (0.535)    | 0.357 (0.191)    | 1 (0.602) |    14.88 | broky, frozen, karrigan, rain, ropz |
|           27 |     2344 | 2024-05-07 | Monte             | W   | 0.595      | -            | -                | -                | 1 (0.595) |     0.37 | broky, frozen, karrigan, rain, ropz |
|           26 |     2576 | 2024-04-26 | Eternal Fire      | W   | 0.521      | 0.889        | 0.739 (0.342)    | 0.438 (0.203)    | 1 (0.521) |     7.73 | broky, frozen, karrigan, rain, ropz |
|           25 |     2605 | 2024-04-25 | Virtus.pro        | W   | 0.515      | 0.889        | 0.498 (0.228)    | -                | 1 (0.515) |     7.39 | broky, frozen, karrigan, rain, ropz |
|           24 |     2624 | 2024-04-24 | Astralis          | L   | 0.508      | -            | -                | -                | -         |    -7.47 | broky, frozen, karrigan, rain, ropz |
|           23 |     2642 | 2024-04-23 | Imperial          | W   | 0.501      | 0.889        | 0.233 (0.104)    | 0.658 (0.293)    | 1 (0.501) |     1.37 | broky, frozen, karrigan, rain, ropz |
|           22 |     2917 | 2024-04-14 | MOUZ              | W   | 0.440      | 0.624        | 1.000 (0.274)    | -                | -         |     9.76 | broky, frozen, karrigan, rain, ropz |
|           21 |     2931 | 2024-04-13 | Astralis          | W   | 0.433      | 0.624        | 0.389 (0.105)    | -                | -         |     7.50 | broky, frozen, karrigan, rain, ropz |
|           20 |     2945 | 2024-04-12 | Liquid            | W   | 0.426      | -            | -                | -                | -         |     5.00 | broky, frozen, karrigan, rain, ropz |
|           19 |     3018 | 2024-04-10 | FlyQuest          | W   | 0.413      | -            | -                | -                | -         |     0.67 | broky, frozen, karrigan, rain, ropz |
|           18 |     3034 | 2024-04-09 | Cloud9            | W   | 0.411      | -            | -                | -                | -         |     0.38 | broky, frozen, karrigan, rain, ropz |
|           17 |     3079 | 2024-04-09 | Astralis          | L   | 0.406      | -            | -                | -                | -         |    -5.86 | broky, frozen, karrigan, rain, ropz |
|           16 |     3110 | 2024-04-08 | Nemiga            | W   | 0.399      | 0.624        | -                | 0.704 (0.175)    | -         |     0.63 | broky, frozen, karrigan, rain, ropz |
|           15 |     3304 | 2024-03-31 | Natus Vincere     | L   | 0.348      | -            | -                | -                | -         |    -1.89 | broky, frozen, karrigan, rain, ropz |
|           14 |     3310 | 2024-03-30 | Vitality          | W   | 0.341      | 1.000        | 0.647 (0.221)    | -                | -         |     7.66 | broky, frozen, karrigan, rain, ropz |
|           13 |     3330 | 2024-03-28 | Spirit            | W   | 0.328      | 1.000        | 1.000 (0.328)    | 0.441 (0.145)    | -         |     8.10 | broky, frozen, karrigan, rain, ropz |
|           12 |     3414 | 2024-03-24 | Complexity        | W   | 0.300      | -            | -                | -                | -         |     4.33 | broky, frozen, karrigan, rain, ropz |
|           11 |     3428 | 2024-03-23 | Imperial          | W   | 0.293      | 1.000        | -                | 0.658 (0.193)    | -         |     0.84 | broky, frozen, karrigan, rain, ropz |
|           10 |     3442 | 2024-03-22 | Eternal Fire      | L   | 0.287      | -            | -                | -                | -         |    -4.21 | broky, frozen, karrigan, rain, ropz |
|            9 |     3452 | 2024-03-21 | FURIA             | W   | 0.282      | -            | -                | -                | -         |     4.86 | broky, frozen, karrigan, rain, ropz |
|            8 |     3464 | 2024-03-21 | HEROIC            | L   | 0.281      | -            | -                | -                | -         |    -5.79 | broky, frozen, karrigan, rain, ropz |
|            7 |     4256 | 2024-02-16 | Eternal Fire      | W   | 0.054      | -            | -                | -                | -         |     0.89 | broky, frozen, karrigan, rain, ropz |
|            6 |     4282 | 2024-02-15 | G2                | L   | 0.047      | -            | -                | -                | -         |    -0.21 | broky, frozen, karrigan, rain, ropz |
|            5 |     4315 | 2024-02-14 | Falcons           | W   | 0.041      | -            | -                | -                | -         |     0.25 | broky, frozen, karrigan, rain, ropz |
|            4 |     4331 | 2024-02-14 | 9 Pandas          | W   | 0.040      | -            | -                | -                | -         |     0.03 | broky, frozen, karrigan, rain, ropz |
|            3 |     4369 | 2024-02-11 | Spirit            | L   | 0.021      | -            | -                | -                | -         |    -0.14 | broky, frozen, karrigan, rain, ropz |
|            2 |     4380 | 2024-02-10 | MOUZ              | W   | 0.014      | -            | -                | -                | -         |     0.32 | broky, frozen, karrigan, rain, ropz |
|            1 |     4394 | 2024-02-09 | G2                | W   | 0.007      | -            | -                | -                | -         |     0.20 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($200,404.35)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.63) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.860 | $20,000.00     | $17,209.26      |
| 2024-06-02 |      0.768 | $10,000.00     | $7,682.41       |
| 2024-05-12 |      0.627 | $32,000.00     | $20,077.04      |
| 2024-04-14 |      0.440 | $100,000.00    | $43,951.39      |
| 2024-03-31 |      0.348 | $170,000.00    | $59,200.93      |
| 2024-02-11 |      0.021 | $180,000.00    | $3,783.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
