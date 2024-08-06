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
Final Rank Value (669.6) = Starting Rank Value (674.4) + Head To Head Adjustments (-4.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.4
- 400 + ( ( 0.133 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 674.4


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
|           21 |     2999 | 2024-04-10 | RED Canids  | L   | 0.416      | -            | -                | -                | -         |    -1.15 | beg0d, dok, dzt, santos, vhz |
|           20 |     3002 | 2024-04-10 | RED Canids  | L   | 0.415      | -            | -                | -                | -         |    -1.16 | beg0d, dok, dzt, santos, vhz |
|           19 |     3160 | 2024-04-05 | adalYamigos | W   | 0.382      | 0.450        | 0.000 (0.000)    | 0.060 (0.010)    | 0 (0.000) |     5.18 | beg0d, dok, dzt, santos, vhz |
|           18 |     3161 | 2024-04-05 | adalYamigos | L   | 0.382      | -            | -                | -                | -         |    -7.00 | beg0d, dok, dzt, santos, vhz |
|           17 |     3227 | 2024-04-03 | Sharks      | L   | 0.369      | -            | -                | -                | -         |    -1.83 | beg0d, dok, dzt, santos, vhz |
|           16 |     3230 | 2024-04-03 | Sharks      | L   | 0.369      | -            | -                | -                | -         |    -1.86 | beg0d, dok, dzt, santos, vhz |
|           15 |     3362 | 2024-03-27 | Corinthians | W   | 0.323      | 0.450        | 0.000 (0.000)    | 0.045 (0.007)    | 0 (0.000) |     2.92 | beg0d, dok, dzt, santos, vhz |
|           14 |     3366 | 2024-03-27 | Corinthians | L   | 0.322      | -            | -                | -                | -         |    -7.37 | beg0d, dok, dzt, santos, vhz |
|           13 |     3404 | 2024-03-26 | Galorys     | L   | 0.316      | -            | -                | -                | -         |    -2.32 | beg0d, dok, dzt, santos, vhz |
|           12 |     3406 | 2024-03-26 | Galorys     | L   | 0.316      | -            | -                | -                | -         |    -2.37 | beg0d, dok, dzt, santos, vhz |
|           11 |     3485 | 2024-03-20 | Solid       | W   | 0.275      | 0.450        | 0.024 (0.003)    | 0.807 (0.100)    | 0 (0.000) |     6.72 | beg0d, dok, dzt, santos, vhz |
|           10 |     3488 | 2024-03-20 | Solid       | L   | 0.275      | -            | -                | -                | -         |    -1.97 | beg0d, dok, dzt, santos, vhz |
|            9 |     3572 | 2024-03-15 | ODDIK       | L   | 0.243      | -            | -                | -                | -         |    -1.16 | beg0d, dok, dzt, santos, vhz |
|            8 |     3573 | 2024-03-15 | ODDIK       | L   | 0.242      | -            | -                | -                | -         |    -1.17 | beg0d, dok, dzt, santos, vhz |
|            7 |     3846 | 2024-03-05 | W7M         | W   | 0.176      | 0.450        | 0.007 (0.001)    | 0.519 (0.041)    | 0 (0.000) |     3.92 | beg0d, dok, dzt, santos, vhz |
|            6 |     3848 | 2024-03-05 | W7M         | W   | 0.176      | 0.450        | 0.007 (0.001)    | 0.519 (0.041)    | 0 (0.000) |     3.96 | beg0d, dok, dzt, santos, vhz |
|            5 |     4052 | 2024-02-24 | Case        | L   | 0.109      | -            | -                | -                | -         |    -0.66 | beg0d, dok, dzt, santos, vhz |
|            4 |     4057 | 2024-02-24 | Case        | W   | 0.109      | 0.450        | 0.029 (0.001)    | 0.778 (0.038)    | 0 (0.000) |     2.80 | beg0d, dok, dzt, santos, vhz |
|            3 |     4117 | 2024-02-21 | Imperial    | L   | 0.089      | -            | -                | -                | -         |    -0.10 | beg0d, dok, dzt, santos, vhz |
|            2 |     4120 | 2024-02-21 | Imperial    | L   | 0.089      | -            | -                | -                | -         |    -0.10 | beg0d, dok, dzt, santos, vhz |
|            1 |     4302 | 2024-02-14 | 9z          | L   | 0.043      | -            | -                | -                | -         |    -0.01 | beg0d, dok, dzt, santos, vhz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($733.58)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
