### Roster Details<br />
Team Name: 2GAME<br />
Roster: beg0d, dok, dzt, santos, vhz<br />
Global Rank: [163](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
<br />
Final Rank Value:  676.6<br />
<br />
Final Rank Value (676.6) = Starting Rank Value (680.8) + Head To Head Adjustments (-4.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.029[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 680.8
- 400 + ( ( 0.136 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 680.8


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
|           21 |     2806 | 2024-04-10 | RED Canids  | L   | 0.454      | -            | -                | -                | -         |    -1.22 | beg0d, dok, dzt, santos, vhz |
|           20 |     2809 | 2024-04-10 | RED Canids  | L   | 0.454      | -            | -                | -                | -         |    -1.23 | beg0d, dok, dzt, santos, vhz |
|           19 |     2967 | 2024-04-05 | adalYamigos | W   | 0.420      | 0.450        | 0.000 (0.000)    | 0.071 (0.013)    | 0 (0.000) |     5.89 | beg0d, dok, dzt, santos, vhz |
|           18 |     2968 | 2024-04-05 | adalYamigos | L   | 0.420      | -            | -                | -                | -         |    -7.52 | beg0d, dok, dzt, santos, vhz |
|           17 |     3034 | 2024-04-03 | Sharks      | L   | 0.407      | -            | -                | -                | -         |    -2.04 | beg0d, dok, dzt, santos, vhz |
|           16 |     3037 | 2024-04-03 | Sharks      | L   | 0.407      | -            | -                | -                | -         |    -2.08 | beg0d, dok, dzt, santos, vhz |
|           15 |     3169 | 2024-03-27 | Corinthians | W   | 0.361      | 0.450        | 0.000 (0.000)    | 0.049 (0.008)    | 0 (0.000) |     3.21 | beg0d, dok, dzt, santos, vhz |
|           14 |     3173 | 2024-03-27 | Corinthians | L   | 0.361      | -            | -                | -                | -         |    -8.31 | beg0d, dok, dzt, santos, vhz |
|           13 |     3211 | 2024-03-26 | Galorys     | L   | 0.354      | -            | -                | -                | -         |    -2.73 | beg0d, dok, dzt, santos, vhz |
|           12 |     3213 | 2024-03-26 | Galorys     | L   | 0.354      | -            | -                | -                | -         |    -2.79 | beg0d, dok, dzt, santos, vhz |
|           11 |     3292 | 2024-03-20 | Solid       | W   | 0.314      | 0.450        | 0.027 (0.004)    | 0.817 (0.115)    | 0 (0.000) |     7.59 | beg0d, dok, dzt, santos, vhz |
|           10 |     3295 | 2024-03-20 | Solid       | L   | 0.314      | -            | -                | -                | -         |    -2.31 | beg0d, dok, dzt, santos, vhz |
|            9 |     3379 | 2024-03-15 | ODDIK       | L   | 0.281      | -            | -                | -                | -         |    -1.38 | beg0d, dok, dzt, santos, vhz |
|            8 |     3380 | 2024-03-15 | ODDIK       | L   | 0.281      | -            | -                | -                | -         |    -1.39 | beg0d, dok, dzt, santos, vhz |
|            7 |     3653 | 2024-03-05 | W7M         | W   | 0.214      | 0.450        | 0.007 (0.001)    | 0.532 (0.051)    | 0 (0.000) |     4.72 | beg0d, dok, dzt, santos, vhz |
|            6 |     3655 | 2024-03-05 | W7M         | W   | 0.214      | 0.450        | 0.007 (0.001)    | 0.532 (0.051)    | 0 (0.000) |     4.79 | beg0d, dok, dzt, santos, vhz |
|            5 |     3859 | 2024-02-24 | Case        | L   | 0.148      | -            | -                | -                | -         |    -0.89 | beg0d, dok, dzt, santos, vhz |
|            4 |     3864 | 2024-02-24 | Case        | W   | 0.147      | 0.450        | 0.030 (0.002)    | 0.720 (0.048)    | 0 (0.000) |     3.79 | beg0d, dok, dzt, santos, vhz |
|            3 |     3924 | 2024-02-21 | Imperial    | L   | 0.128      | -            | -                | -                | -         |    -0.12 | beg0d, dok, dzt, santos, vhz |
|            2 |     3927 | 2024-02-21 | Imperial    | L   | 0.127      | -            | -                | -                | -         |    -0.12 | beg0d, dok, dzt, santos, vhz |
|            1 |     4109 | 2024-02-14 | 9z          | L   | 0.081      | -            | -                | -                | -         |    -0.02 | beg0d, dok, dzt, santos, vhz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($768.07)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
