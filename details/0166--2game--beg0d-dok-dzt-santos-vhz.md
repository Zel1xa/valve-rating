### Roster Details<br />
Team Name: 2GAME<br />
Roster: beg0d, dok, dzt, santos, vhz<br />
Global Rank: [166](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [45]( ../standings_americas.md)<br />
<br />
Final Rank Value:  669.6<br />
<br />
Final Rank Value (669.6) = Starting Rank Value (674.2) + Head To Head Adjustments (-4.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.2
- 400 + ( ( 0.134 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 674.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |     2987 | 2024-04-10 | RED Canids  | L   | 0.417      | -            | -                | -                | -         |    -1.14 | beg0d, dok, dzt, santos, vhz |
|           20 |     2990 | 2024-04-10 | RED Canids  | L   | 0.417      | -            | -                | -                | -         |    -1.16 | beg0d, dok, dzt, santos, vhz |
|           19 |     3148 | 2024-04-05 | adalYamigos | W   | 0.383      | 0.450        | 0.000 (0.000)    | 0.061 (0.011)    | 0 (0.000) |     5.21 | beg0d, dok, dzt, santos, vhz |
|           18 |     3149 | 2024-04-05 | adalYamigos | L   | 0.383      | -            | -                | -                | -         |    -7.01 | beg0d, dok, dzt, santos, vhz |
|           17 |     3215 | 2024-04-03 | Sharks      | L   | 0.370      | -            | -                | -                | -         |    -1.82 | beg0d, dok, dzt, santos, vhz |
|           16 |     3218 | 2024-04-03 | Sharks      | L   | 0.370      | -            | -                | -                | -         |    -1.85 | beg0d, dok, dzt, santos, vhz |
|           15 |     3350 | 2024-03-27 | Corinthians | W   | 0.324      | 0.450        | 0.000 (0.000)    | 0.046 (0.007)    | 0 (0.000) |     2.93 | beg0d, dok, dzt, santos, vhz |
|           14 |     3354 | 2024-03-27 | Corinthians | L   | 0.324      | -            | -                | -                | -         |    -7.40 | beg0d, dok, dzt, santos, vhz |
|           13 |     3392 | 2024-03-26 | Galorys     | L   | 0.317      | -            | -                | -                | -         |    -2.32 | beg0d, dok, dzt, santos, vhz |
|           12 |     3394 | 2024-03-26 | Galorys     | L   | 0.317      | -            | -                | -                | -         |    -2.36 | beg0d, dok, dzt, santos, vhz |
|           11 |     3473 | 2024-03-20 | Solid       | W   | 0.277      | 0.450        | 0.024 (0.003)    | 0.825 (0.103)    | 0 (0.000) |     6.76 | beg0d, dok, dzt, santos, vhz |
|           10 |     3476 | 2024-03-20 | Solid       | L   | 0.276      | -            | -                | -                | -         |    -1.97 | beg0d, dok, dzt, santos, vhz |
|            9 |     3560 | 2024-03-15 | ODDIK       | L   | 0.244      | -            | -                | -                | -         |    -1.15 | beg0d, dok, dzt, santos, vhz |
|            8 |     3561 | 2024-03-15 | ODDIK       | L   | 0.244      | -            | -                | -                | -         |    -1.17 | beg0d, dok, dzt, santos, vhz |
|            7 |     3834 | 2024-03-05 | W7M         | W   | 0.177      | 0.450        | 0.007 (0.001)    | 0.531 (0.042)    | 0 (0.000) |     3.96 | beg0d, dok, dzt, santos, vhz |
|            6 |     3836 | 2024-03-05 | W7M         | W   | 0.177      | 0.450        | 0.007 (0.001)    | 0.531 (0.042)    | 0 (0.000) |     4.00 | beg0d, dok, dzt, santos, vhz |
|            5 |     4040 | 2024-02-24 | Case        | L   | 0.111      | -            | -                | -                | -         |    -0.66 | beg0d, dok, dzt, santos, vhz |
|            4 |     4045 | 2024-02-24 | Case        | W   | 0.110      | 0.450        | 0.029 (0.001)    | 0.795 (0.039)    | 0 (0.000) |     2.83 | beg0d, dok, dzt, santos, vhz |
|            3 |     4105 | 2024-02-21 | Imperial    | L   | 0.091      | -            | -                | -                | -         |    -0.10 | beg0d, dok, dzt, santos, vhz |
|            2 |     4108 | 2024-02-21 | Imperial    | L   | 0.090      | -            | -                | -                | -         |    -0.10 | beg0d, dok, dzt, santos, vhz |
|            1 |     4290 | 2024-02-14 | 9z          | L   | 0.044      | -            | -                | -                | -         |    -0.01 | beg0d, dok, dzt, santos, vhz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($734.67)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
