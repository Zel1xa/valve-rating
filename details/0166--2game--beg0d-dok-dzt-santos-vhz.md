### Roster Details<br />
Team Name: 2GAME<br />
Roster: beg0d, dok, dzt, santos, vhz<br />
Global Rank: [166](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
<br />
Final Rank Value:  671.5<br />
<br />
Final Rank Value (671.5) = Starting Rank Value (675.6) + Head To Head Adjustments (-4.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.238[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 675.6
- 400 + ( ( 0.135 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 675.6


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
|           21 |     2918 | 2024-04-10 | RED Canids  | L   | 0.433      | -            | -                | -                | -         |    -1.18 | beg0d, dok, dzt, santos, vhz |
|           20 |     2921 | 2024-04-10 | RED Canids  | L   | 0.433      | -            | -                | -                | -         |    -1.19 | beg0d, dok, dzt, santos, vhz |
|           19 |     3079 | 2024-04-05 | adalYamigos | W   | 0.400      | 0.450        | 0.000 (0.000)    | 0.066 (0.012)    | 0 (0.000) |     5.54 | beg0d, dok, dzt, santos, vhz |
|           18 |     3080 | 2024-04-05 | adalYamigos | L   | 0.399      | -            | -                | -                | -         |    -7.21 | beg0d, dok, dzt, santos, vhz |
|           17 |     3146 | 2024-04-03 | Sharks      | L   | 0.387      | -            | -                | -                | -         |    -1.90 | beg0d, dok, dzt, santos, vhz |
|           16 |     3149 | 2024-04-03 | Sharks      | L   | 0.386      | -            | -                | -                | -         |    -1.93 | beg0d, dok, dzt, santos, vhz |
|           15 |     3281 | 2024-03-27 | Corinthians | W   | 0.340      | 0.450        | 0.000 (0.000)    | 0.048 (0.007)    | 0 (0.000) |     3.06 | beg0d, dok, dzt, santos, vhz |
|           14 |     3285 | 2024-03-27 | Corinthians | L   | 0.340      | -            | -                | -                | -         |    -7.79 | beg0d, dok, dzt, santos, vhz |
|           13 |     3323 | 2024-03-26 | Galorys     | L   | 0.334      | -            | -                | -                | -         |    -2.46 | beg0d, dok, dzt, santos, vhz |
|           12 |     3325 | 2024-03-26 | Galorys     | L   | 0.333      | -            | -                | -                | -         |    -2.52 | beg0d, dok, dzt, santos, vhz |
|           11 |     3404 | 2024-03-20 | Solid       | W   | 0.293      | 0.450        | 0.025 (0.003)    | 0.835 (0.110)    | 0 (0.000) |     7.15 | beg0d, dok, dzt, santos, vhz |
|           10 |     3407 | 2024-03-20 | Solid       | L   | 0.293      | -            | -                | -                | -         |    -2.09 | beg0d, dok, dzt, santos, vhz |
|            9 |     3491 | 2024-03-15 | ODDIK       | L   | 0.260      | -            | -                | -                | -         |    -1.24 | beg0d, dok, dzt, santos, vhz |
|            8 |     3492 | 2024-03-15 | ODDIK       | L   | 0.260      | -            | -                | -                | -         |    -1.25 | beg0d, dok, dzt, santos, vhz |
|            7 |     3764 | 2024-03-05 | W7M         | W   | 0.194      | 0.450        | 0.007 (0.001)    | 0.536 (0.047)    | 0 (0.000) |     4.31 | beg0d, dok, dzt, santos, vhz |
|            6 |     3766 | 2024-03-05 | W7M         | W   | 0.193      | 0.450        | 0.007 (0.001)    | 0.536 (0.047)    | 0 (0.000) |     4.36 | beg0d, dok, dzt, santos, vhz |
|            5 |     3970 | 2024-02-24 | Case        | L   | 0.127      | -            | -                | -                | -         |    -0.76 | beg0d, dok, dzt, santos, vhz |
|            4 |     3975 | 2024-02-24 | Case        | W   | 0.127      | 0.450        | 0.029 (0.002)    | 0.804 (0.046)    | 0 (0.000) |     3.25 | beg0d, dok, dzt, santos, vhz |
|            3 |     4035 | 2024-02-21 | Imperial    | L   | 0.107      | -            | -                | -                | -         |    -0.12 | beg0d, dok, dzt, santos, vhz |
|            2 |     4038 | 2024-02-21 | Imperial    | L   | 0.107      | -            | -                | -                | -         |    -0.12 | beg0d, dok, dzt, santos, vhz |
|            1 |     4219 | 2024-02-14 | 9z          | L   | 0.060      | -            | -                | -                | -         |    -0.01 | beg0d, dok, dzt, santos, vhz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($749.42)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
