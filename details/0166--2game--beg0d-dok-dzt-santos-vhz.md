### Roster Details<br />
Team Name: 2GAME<br />
Roster: beg0d, dok, dzt, santos, vhz<br />
Global Rank: [166](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [45]( ../standings_americas.md)<br />
<br />
Final Rank Value:  670.3<br />
<br />
Final Rank Value (670.3) = Starting Rank Value (674.6) + Head To Head Adjustments (-4.3)<br />

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
- 400 + ( ( 0.134 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 674.6


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
|           21 |     2972 | 2024-04-10 | RED Canids  | L   | 0.423      | -            | -                | -                | -         |    -1.15 | beg0d, dok, dzt, santos, vhz |
|           20 |     2975 | 2024-04-10 | RED Canids  | L   | 0.422      | -            | -                | -                | -         |    -1.16 | beg0d, dok, dzt, santos, vhz |
|           19 |     3133 | 2024-04-05 | adalYamigos | W   | 0.389      | 0.450        | 0.000 (0.000)    | 0.063 (0.011)    | 0 (0.000) |     5.33 | beg0d, dok, dzt, santos, vhz |
|           18 |     3134 | 2024-04-05 | adalYamigos | L   | 0.389      | -            | -                | -                | -         |    -7.08 | beg0d, dok, dzt, santos, vhz |
|           17 |     3200 | 2024-04-03 | Sharks      | L   | 0.376      | -            | -                | -                | -         |    -1.84 | beg0d, dok, dzt, santos, vhz |
|           16 |     3203 | 2024-04-03 | Sharks      | L   | 0.376      | -            | -                | -                | -         |    -1.87 | beg0d, dok, dzt, santos, vhz |
|           15 |     3335 | 2024-03-27 | Corinthians | W   | 0.330      | 0.450        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     2.98 | beg0d, dok, dzt, santos, vhz |
|           14 |     3339 | 2024-03-27 | Corinthians | L   | 0.329      | -            | -                | -                | -         |    -7.54 | beg0d, dok, dzt, santos, vhz |
|           13 |     3377 | 2024-03-26 | Galorys     | L   | 0.323      | -            | -                | -                | -         |    -2.36 | beg0d, dok, dzt, santos, vhz |
|           12 |     3379 | 2024-03-26 | Galorys     | L   | 0.323      | -            | -                | -                | -         |    -2.41 | beg0d, dok, dzt, santos, vhz |
|           11 |     3458 | 2024-03-20 | Solid       | W   | 0.282      | 0.450        | 0.025 (0.003)    | 0.835 (0.106)    | 0 (0.000) |     6.91 | beg0d, dok, dzt, santos, vhz |
|           10 |     3461 | 2024-03-20 | Solid       | L   | 0.282      | -            | -                | -                | -         |    -2.00 | beg0d, dok, dzt, santos, vhz |
|            9 |     3545 | 2024-03-15 | ODDIK       | L   | 0.250      | -            | -                | -                | -         |    -1.18 | beg0d, dok, dzt, santos, vhz |
|            8 |     3546 | 2024-03-15 | ODDIK       | L   | 0.249      | -            | -                | -                | -         |    -1.19 | beg0d, dok, dzt, santos, vhz |
|            7 |     3819 | 2024-03-05 | W7M         | W   | 0.183      | 0.450        | 0.007 (0.001)    | 0.537 (0.044)    | 0 (0.000) |     4.08 | beg0d, dok, dzt, santos, vhz |
|            6 |     3821 | 2024-03-05 | W7M         | W   | 0.183      | 0.450        | 0.007 (0.001)    | 0.537 (0.044)    | 0 (0.000) |     4.13 | beg0d, dok, dzt, santos, vhz |
|            5 |     4025 | 2024-02-24 | Case        | L   | 0.116      | -            | -                | -                | -         |    -0.69 | beg0d, dok, dzt, santos, vhz |
|            4 |     4030 | 2024-02-24 | Case        | W   | 0.116      | 0.450        | 0.029 (0.002)    | 0.805 (0.042)    | 0 (0.000) |     2.99 | beg0d, dok, dzt, santos, vhz |
|            3 |     4090 | 2024-02-21 | Imperial    | L   | 0.096      | -            | -                | -                | -         |    -0.11 | beg0d, dok, dzt, santos, vhz |
|            2 |     4093 | 2024-02-21 | Imperial    | L   | 0.096      | -            | -                | -                | -         |    -0.11 | beg0d, dok, dzt, santos, vhz |
|            1 |     4275 | 2024-02-14 | 9z          | L   | 0.050      | -            | -                | -                | -         |    -0.01 | beg0d, dok, dzt, santos, vhz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($739.92)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
