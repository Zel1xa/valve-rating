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
Final Rank Value (669.6) = Starting Rank Value (674.3) + Head To Head Adjustments (-4.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.3
- 400 + ( ( 0.133 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 674.3


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
|           21 |     3005 | 2024-04-10 | RED Canids  | L   | 0.415      | -            | -                | -                | -         |    -1.15 | beg0d, dok, dzt, santos, vhz |
|           20 |     3008 | 2024-04-10 | RED Canids  | L   | 0.415      | -            | -                | -                | -         |    -1.16 | beg0d, dok, dzt, santos, vhz |
|           19 |     3166 | 2024-04-05 | adalYamigos | W   | 0.382      | 0.450        | 0.000 (0.000)    | 0.059 (0.010)    | 0 (0.000) |     5.17 | beg0d, dok, dzt, santos, vhz |
|           18 |     3167 | 2024-04-05 | adalYamigos | L   | 0.381      | -            | -                | -                | -         |    -6.99 | beg0d, dok, dzt, santos, vhz |
|           17 |     3233 | 2024-04-03 | Sharks      | L   | 0.368      | -            | -                | -                | -         |    -1.82 | beg0d, dok, dzt, santos, vhz |
|           16 |     3236 | 2024-04-03 | Sharks      | L   | 0.368      | -            | -                | -                | -         |    -1.86 | beg0d, dok, dzt, santos, vhz |
|           15 |     3368 | 2024-03-27 | Corinthians | W   | 0.322      | 0.450        | 0.000 (0.000)    | 0.045 (0.006)    | 0 (0.000) |     2.91 | beg0d, dok, dzt, santos, vhz |
|           14 |     3372 | 2024-03-27 | Corinthians | L   | 0.322      | -            | -                | -                | -         |    -7.36 | beg0d, dok, dzt, santos, vhz |
|           13 |     3410 | 2024-03-26 | Galorys     | L   | 0.316      | -            | -                | -                | -         |    -2.32 | beg0d, dok, dzt, santos, vhz |
|           12 |     3412 | 2024-03-26 | Galorys     | L   | 0.315      | -            | -                | -                | -         |    -2.36 | beg0d, dok, dzt, santos, vhz |
|           11 |     3491 | 2024-03-20 | Solid       | W   | 0.275      | 0.450        | 0.024 (0.003)    | 0.807 (0.100)    | 0 (0.000) |     6.70 | beg0d, dok, dzt, santos, vhz |
|           10 |     3494 | 2024-03-20 | Solid       | L   | 0.275      | -            | -                | -                | -         |    -1.97 | beg0d, dok, dzt, santos, vhz |
|            9 |     3578 | 2024-03-15 | ODDIK       | L   | 0.242      | -            | -                | -                | -         |    -1.15 | beg0d, dok, dzt, santos, vhz |
|            8 |     3579 | 2024-03-15 | ODDIK       | L   | 0.242      | -            | -                | -                | -         |    -1.16 | beg0d, dok, dzt, santos, vhz |
|            7 |     3852 | 2024-03-05 | W7M         | W   | 0.175      | 0.450        | 0.007 (0.001)    | 0.520 (0.041)    | 0 (0.000) |     3.91 | beg0d, dok, dzt, santos, vhz |
|            6 |     3854 | 2024-03-05 | W7M         | W   | 0.175      | 0.450        | 0.007 (0.001)    | 0.520 (0.041)    | 0 (0.000) |     3.95 | beg0d, dok, dzt, santos, vhz |
|            5 |     4058 | 2024-02-24 | Case        | L   | 0.109      | -            | -                | -                | -         |    -0.65 | beg0d, dok, dzt, santos, vhz |
|            4 |     4063 | 2024-02-24 | Case        | W   | 0.108      | 0.450        | 0.029 (0.001)    | 0.778 (0.038)    | 0 (0.000) |     2.78 | beg0d, dok, dzt, santos, vhz |
|            3 |     4123 | 2024-02-21 | Imperial    | L   | 0.089      | -            | -                | -                | -         |    -0.10 | beg0d, dok, dzt, santos, vhz |
|            2 |     4126 | 2024-02-21 | Imperial    | L   | 0.088      | -            | -                | -                | -         |    -0.10 | beg0d, dok, dzt, santos, vhz |
|            1 |     4308 | 2024-02-14 | 9z          | L   | 0.042      | -            | -                | -                | -         |    -0.01 | beg0d, dok, dzt, santos, vhz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($733.04)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
