### Roster Details<br />
Team Name: 2GAME<br />
Roster: beg0d, dok, dzt, santos, vhz<br />
Global Rank: [166](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [45]( ../standings_americas.md)<br />
<br />
Final Rank Value:  670.2<br />
<br />
Final Rank Value (670.2) = Starting Rank Value (674.6) + Head To Head Adjustments (-4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.6
- 400 + ( ( 0.134 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 674.6


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
|           21 |     2981 | 2024-04-10 | RED Canids  | L   | 0.421      | -            | -                | -                | -         |    -1.15 | beg0d, dok, dzt, santos, vhz |
|           20 |     2984 | 2024-04-10 | RED Canids  | L   | 0.421      | -            | -                | -                | -         |    -1.17 | beg0d, dok, dzt, santos, vhz |
|           19 |     3142 | 2024-04-05 | adalYamigos | W   | 0.388      | 0.450        | 0.000 (0.000)    | 0.062 (0.011)    | 0 (0.000) |     5.30 | beg0d, dok, dzt, santos, vhz |
|           18 |     3143 | 2024-04-05 | adalYamigos | L   | 0.387      | -            | -                | -                | -         |    -7.07 | beg0d, dok, dzt, santos, vhz |
|           17 |     3209 | 2024-04-03 | Sharks      | L   | 0.375      | -            | -                | -                | -         |    -1.84 | beg0d, dok, dzt, santos, vhz |
|           16 |     3212 | 2024-04-03 | Sharks      | L   | 0.374      | -            | -                | -                | -         |    -1.87 | beg0d, dok, dzt, santos, vhz |
|           15 |     3344 | 2024-03-27 | Corinthians | W   | 0.328      | 0.450        | 0.000 (0.000)    | 0.046 (0.007)    | 0 (0.000) |     2.96 | beg0d, dok, dzt, santos, vhz |
|           14 |     3348 | 2024-03-27 | Corinthians | L   | 0.328      | -            | -                | -                | -         |    -7.50 | beg0d, dok, dzt, santos, vhz |
|           13 |     3386 | 2024-03-26 | Galorys     | L   | 0.322      | -            | -                | -                | -         |    -2.36 | beg0d, dok, dzt, santos, vhz |
|           12 |     3388 | 2024-03-26 | Galorys     | L   | 0.321      | -            | -                | -                | -         |    -2.40 | beg0d, dok, dzt, santos, vhz |
|           11 |     3467 | 2024-03-20 | Solid       | W   | 0.281      | 0.450        | 0.025 (0.003)    | 0.825 (0.104)    | 0 (0.000) |     6.86 | beg0d, dok, dzt, santos, vhz |
|           10 |     3470 | 2024-03-20 | Solid       | L   | 0.281      | -            | -                | -                | -         |    -2.00 | beg0d, dok, dzt, santos, vhz |
|            9 |     3554 | 2024-03-15 | ODDIK       | L   | 0.248      | -            | -                | -                | -         |    -1.18 | beg0d, dok, dzt, santos, vhz |
|            8 |     3555 | 2024-03-15 | ODDIK       | L   | 0.248      | -            | -                | -                | -         |    -1.19 | beg0d, dok, dzt, santos, vhz |
|            7 |     3828 | 2024-03-05 | W7M         | W   | 0.182      | 0.450        | 0.007 (0.001)    | 0.531 (0.043)    | 0 (0.000) |     4.05 | beg0d, dok, dzt, santos, vhz |
|            6 |     3830 | 2024-03-05 | W7M         | W   | 0.181      | 0.450        | 0.007 (0.001)    | 0.531 (0.043)    | 0 (0.000) |     4.09 | beg0d, dok, dzt, santos, vhz |
|            5 |     4034 | 2024-02-24 | Case        | L   | 0.115      | -            | -                | -                | -         |    -0.68 | beg0d, dok, dzt, santos, vhz |
|            4 |     4039 | 2024-02-24 | Case        | W   | 0.115      | 0.450        | 0.029 (0.002)    | 0.795 (0.041)    | 0 (0.000) |     2.94 | beg0d, dok, dzt, santos, vhz |
|            3 |     4099 | 2024-02-21 | Imperial    | L   | 0.095      | -            | -                | -                | -         |    -0.11 | beg0d, dok, dzt, santos, vhz |
|            2 |     4102 | 2024-02-21 | Imperial    | L   | 0.095      | -            | -                | -                | -         |    -0.11 | beg0d, dok, dzt, santos, vhz |
|            1 |     4284 | 2024-02-14 | 9z          | L   | 0.048      | -            | -                | -                | -         |    -0.01 | beg0d, dok, dzt, santos, vhz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($738.54)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
