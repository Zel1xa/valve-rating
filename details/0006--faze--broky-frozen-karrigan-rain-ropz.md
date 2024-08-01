### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1726.7<br />
<br />
Final Rank Value (1726.7) = Starting Rank Value (1716.1) + Head To Head Adjustments (10.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.837[<sup>1</sup>](#table2)
- Bounty Collected: 0.632[<sup>2</sup>](#table1)
- Opponent Network: 0.247[<sup>2</sup>](#table1)
- LAN Wins: 0.841[<sup>2</sup>](#table1)

The average of these factors is 0.639<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1716.1
- 400 + ( ( 0.639 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1716.1


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
|           43 |        3 | 2024-08-01 | G2            | L   | 1.000      | -            | -                | -                | -         |    -7.03 | broky, frozen, karrigan, rain, ropz |
|           42 |       56 | 2024-07-31 | Cloud9        | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.05 | broky, frozen, karrigan, rain, ropz |
|           41 |      427 | 2024-07-19 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -7.86 | broky, frozen, karrigan, rain, ropz |
|           40 |      580 | 2024-07-17 | FlyQuest      | W   | 1.000      | 1.000        | 0.106 (0.106)    | 0.323 (0.323)    | 1 (1.000) |     1.44 | broky, frozen, karrigan, rain, ropz |
|           39 |      959 | 2024-06-14 | Vitality      | L   | 0.881      | -            | -                | -                | -         |    -9.69 | broky, frozen, karrigan, rain, ropz |
|           38 |      997 | 2024-06-13 | Natus Vincere | L   | 0.874      | -            | -                | -                | -         |    -7.44 | broky, frozen, karrigan, rain, ropz |
|           37 |     1029 | 2024-06-12 | SAW           | W   | 0.866      | 0.729        | -                | 0.544 (0.344)    | 1 (0.866) |     1.00 | broky, frozen, karrigan, rain, ropz |
|           36 |     1522 | 2024-05-31 | G2            | L   | 0.789      | -            | -                | -                | -         |    -6.75 | broky, frozen, karrigan, rain, ropz |
|           35 |     1576 | 2024-05-29 | Spirit        | L   | 0.776      | -            | -                | -                | -         |    -7.20 | broky, frozen, karrigan, rain, ropz |
|           34 |     1599 | 2024-05-28 | Virtus.pro    | W   | 0.769      | 0.624        | 0.483 (0.232)    | 0.326 (0.157)    | 1 (0.769) |     9.09 | broky, frozen, karrigan, rain, ropz |
|           33 |     1623 | 2024-05-27 | M80           | W   | 0.762      | 0.624        | -                | 0.641 (0.305)    | 1 (0.762) |     1.39 | broky, frozen, karrigan, rain, ropz |
|           32 |     2185 | 2024-05-10 | Vitality      | L   | 0.648      | -            | -                | -                | -         |    -7.75 | broky, frozen, karrigan, rain, ropz |
|           31 |     2229 | 2024-05-08 | Natus Vincere | W   | 0.635      | 0.889        | 1.000 (0.565)    | 0.331 (0.187)    | 1 (0.635) |    15.30 | broky, frozen, karrigan, rain, ropz |
|           30 |     2247 | 2024-05-07 | Monte         | W   | 0.628      | -            | -                | -                | 1 (0.628) |     0.36 | broky, frozen, karrigan, rain, ropz |
|           29 |     2483 | 2024-04-26 | Eternal Fire  | W   | 0.554      | 0.889        | 0.757 (0.373)    | 0.461 (0.227)    | 1 (0.554) |     7.80 | broky, frozen, karrigan, rain, ropz |
|           28 |     2511 | 2024-04-25 | Virtus.pro    | W   | 0.548      | 0.889        | 0.483 (0.236)    | 0.326 (0.159)    | 1 (0.548) |     7.32 | broky, frozen, karrigan, rain, ropz |
|           27 |     2530 | 2024-04-24 | Astralis      | L   | 0.542      | -            | -                | -                | -         |    -9.55 | broky, frozen, karrigan, rain, ropz |
|           26 |     2549 | 2024-04-23 | Imperial      | W   | 0.535      | 0.889        | 0.240 (0.114)    | 0.719 (0.342)    | 1 (0.535) |     1.28 | broky, frozen, karrigan, rain, ropz |
|           25 |     2833 | 2024-04-14 | MOUZ          | W   | 0.473      | 0.624        | 1.000 (0.295)    | -                | -         |    10.37 | broky, frozen, karrigan, rain, ropz |
|           24 |     2847 | 2024-04-13 | Astralis      | W   | 0.466      | -            | -                | -                | -         |     6.62 | broky, frozen, karrigan, rain, ropz |
|           23 |     2862 | 2024-04-12 | Liquid        | W   | 0.460      | -            | -                | -                | -         |     2.67 | broky, frozen, karrigan, rain, ropz |
|           22 |     2935 | 2024-04-10 | FlyQuest      | W   | 0.447      | -            | -                | -                | -         |     0.67 | broky, frozen, karrigan, rain, ropz |
|           21 |     2951 | 2024-04-09 | Cloud9        | W   | 0.445      | -            | -                | -                | -         |     0.40 | broky, frozen, karrigan, rain, ropz |
|           20 |     2996 | 2024-04-09 | Astralis      | L   | 0.439      | -            | -                | -                | -         |    -7.85 | broky, frozen, karrigan, rain, ropz |
|           19 |     3027 | 2024-04-08 | Nemiga        | W   | 0.432      | 0.624        | -                | 0.697 (0.188)    | -         |     0.54 | broky, frozen, karrigan, rain, ropz |
|           18 |     3229 | 2024-03-31 | Natus Vincere | L   | 0.382      | -            | -                | -                | -         |    -2.34 | broky, frozen, karrigan, rain, ropz |
|           17 |     3235 | 2024-03-30 | Vitality      | W   | 0.374      | 1.000        | 0.591 (0.221)    | -                | -         |     7.76 | broky, frozen, karrigan, rain, ropz |
|           16 |     3255 | 2024-03-28 | Spirit        | W   | 0.362      | 1.000        | 1.000 (0.362)    | -                | -         |     8.58 | broky, frozen, karrigan, rain, ropz |
|           15 |     3344 | 2024-03-24 | Complexity    | W   | 0.333      | 1.000        | 0.318 (0.106)    | -                | -         |     4.10 | broky, frozen, karrigan, rain, ropz |
|           14 |     3358 | 2024-03-23 | Imperial      | W   | 0.327      | 1.000        | -                | 0.719 (0.235)    | -         |     0.86 | broky, frozen, karrigan, rain, ropz |
|           13 |     3372 | 2024-03-22 | Eternal Fire  | L   | 0.320      | -            | -                | -                | -         |    -4.98 | broky, frozen, karrigan, rain, ropz |
|           12 |     3382 | 2024-03-21 | FURIA         | W   | 0.316      | -            | -                | -                | -         |     5.09 | broky, frozen, karrigan, rain, ropz |
|           11 |     3394 | 2024-03-21 | HEROIC        | L   | 0.314      | -            | -                | -                | -         |    -6.74 | broky, frozen, karrigan, rain, ropz |
|           10 |     4207 | 2024-02-16 | Eternal Fire  | W   | 0.087      | -            | -                | -                | -         |     1.36 | broky, frozen, karrigan, rain, ropz |
|            9 |     4233 | 2024-02-15 | G2            | L   | 0.080      | -            | -                | -                | -         |    -0.43 | broky, frozen, karrigan, rain, ropz |
|            8 |     4266 | 2024-02-14 | Falcons       | W   | 0.075      | -            | -                | -                | -         |     0.42 | broky, frozen, karrigan, rain, ropz |
|            7 |     4282 | 2024-02-14 | 9 Pandas      | W   | 0.073      | -            | -                | -                | -         |     0.04 | broky, frozen, karrigan, rain, ropz |
|            6 |     4329 | 2024-02-11 | Spirit        | L   | 0.054      | -            | -                | -                | -         |    -0.43 | broky, frozen, karrigan, rain, ropz |
|            5 |     4340 | 2024-02-10 | MOUZ          | W   | 0.048      | -            | -                | -                | -         |     1.05 | broky, frozen, karrigan, rain, ropz |
|            4 |     4355 | 2024-02-09 | G2            | W   | 0.041      | -            | -                | -                | -         |     1.07 | broky, frozen, karrigan, rain, ropz |
|            3 |     4386 | 2024-02-06 | Spirit        | L   | 0.021      | -            | -                | -                | -         |    -0.17 | broky, frozen, karrigan, rain, ropz |
|            2 |     4406 | 2024-02-04 | Eternal Fire  | W   | 0.009      | -            | -                | -                | -         |     0.14 | broky, frozen, karrigan, rain, ropz |
|            1 |     4444 | 2024-02-03 | Rebels        | W   | 0.001      | -            | -                | -                | -         |     0.00 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($209,018.43)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.64) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.894 | $20,000.00     | $17,877.78      |
| 2024-06-02 |      0.802 | $10,000.00     | $8,016.67       |
| 2024-05-12 |      0.661 | $32,000.00     | $21,146.67      |
| 2024-04-14 |      0.473 | $100,000.00    | $47,293.98      |
| 2024-03-31 |      0.382 | $170,000.00    | $64,883.33      |
| 2024-02-11 |      0.054 | $180,000.00    | $9,800.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
