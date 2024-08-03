### Roster Details<br />
Team Name: 2GAME<br />
Roster: beg0d, dok, dzt, santos, vhz<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  677.9<br />
<br />
Final Rank Value (677.9) = Starting Rank Value (676.4) + Head To Head Adjustments (1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.238[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 676.4
- 400 + ( ( 0.135 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 676.4


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
|           20 |     2852 | 2024-04-10 | RED Canids  | L   | 0.435      | -            | -                | -                | -         |    -1.71 | beg0d, dok, dzt, santos, vhz |
|           19 |     2855 | 2024-04-10 | RED Canids  | L   | 0.435      | -            | -                | -                | -         |    -1.74 | beg0d, dok, dzt, santos, vhz |
|           18 |     3013 | 2024-04-05 | adalYamigos | W   | 0.401      | 0.450        | 0.000 (0.000)    | 0.069 (0.012)    | 0 (0.000) |     5.41 | beg0d, dok, dzt, santos, vhz |
|           17 |     3014 | 2024-04-05 | adalYamigos | L   | 0.401      | -            | -                | -                | -         |    -7.39 | beg0d, dok, dzt, santos, vhz |
|           16 |     3080 | 2024-04-03 | Sharks      | L   | 0.388      | -            | -                | -                | -         |    -1.99 | beg0d, dok, dzt, santos, vhz |
|           15 |     3083 | 2024-04-03 | Sharks      | L   | 0.388      | -            | -                | -                | -         |    -2.03 | beg0d, dok, dzt, santos, vhz |
|           14 |     3215 | 2024-03-27 | Corinthians | W   | 0.342      | 0.450        | 0.000 (0.000)    | 0.036 (0.005)    | 0 (0.000) |     2.86 | beg0d, dok, dzt, santos, vhz |
|           13 |     3254 | 2024-03-26 | Galorys     | L   | 0.335      | -            | -                | -                | -         |    -2.62 | beg0d, dok, dzt, santos, vhz |
|           12 |     3256 | 2024-03-26 | Galorys     | L   | 0.335      | -            | -                | -                | -         |    -2.68 | beg0d, dok, dzt, santos, vhz |
|           11 |     3333 | 2024-03-20 | Solid       | W   | 0.295      | 0.450        | 0.026 (0.003)    | 0.863 (0.114)    | 0 (0.000) |     7.20 | beg0d, dok, dzt, santos, vhz |
|           10 |     3336 | 2024-03-20 | Solid       | L   | 0.294      | -            | -                | -                | -         |    -2.09 | beg0d, dok, dzt, santos, vhz |
|            9 |     3419 | 2024-03-15 | ODDIK       | L   | 0.262      | -            | -                | -                | -         |    -1.29 | beg0d, dok, dzt, santos, vhz |
|            8 |     3420 | 2024-03-15 | ODDIK       | L   | 0.262      | -            | -                | -                | -         |    -1.30 | beg0d, dok, dzt, santos, vhz |
|            7 |     3691 | 2024-03-05 | W7M         | W   | 0.195      | 0.450        | 0.007 (0.001)    | 0.554 (0.049)    | 0 (0.000) |     4.33 | beg0d, dok, dzt, santos, vhz |
|            6 |     3693 | 2024-03-05 | W7M         | W   | 0.195      | 0.450        | 0.007 (0.001)    | 0.554 (0.049)    | 0 (0.000) |     4.38 | beg0d, dok, dzt, santos, vhz |
|            5 |     3897 | 2024-02-24 | Case        | L   | 0.129      | -            | -                | -                | -         |    -0.76 | beg0d, dok, dzt, santos, vhz |
|            4 |     3902 | 2024-02-24 | Case        | W   | 0.128      | 0.450        | 0.029 (0.002)    | 0.750 (0.043)    | 0 (0.000) |     3.31 | beg0d, dok, dzt, santos, vhz |
|            3 |     3962 | 2024-02-21 | Imperial    | L   | 0.109      | -            | -                | -                | -         |    -0.14 | beg0d, dok, dzt, santos, vhz |
|            2 |     3965 | 2024-02-21 | Imperial    | L   | 0.108      | -            | -                | -                | -         |    -0.14 | beg0d, dok, dzt, santos, vhz |
|            1 |     4146 | 2024-02-14 | 9z          | L   | 0.062      | -            | -                | -                | -         |    -0.09 | beg0d, dok, dzt, santos, vhz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($750.96)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
