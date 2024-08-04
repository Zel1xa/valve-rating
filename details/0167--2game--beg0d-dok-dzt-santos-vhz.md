### Roster Details<br />
Team Name: 2GAME<br />
Roster: beg0d, dok, dzt, santos, vhz<br />
Global Rank: [167](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  671.0<br />
<br />
Final Rank Value (671.0) = Starting Rank Value (675.2) + Head To Head Adjustments (-4.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.237[<sup>2</sup>](#table1)
- Opponent Network: 0.026[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 675.2
- 400 + ( ( 0.135 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 675.2


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
|           21 |     2954 | 2024-04-10 | RED Canids  | L   | 0.429      | -            | -                | -                | -         |    -1.17 | beg0d, dok, dzt, santos, vhz |
|           20 |     2957 | 2024-04-10 | RED Canids  | L   | 0.429      | -            | -                | -                | -         |    -1.18 | beg0d, dok, dzt, santos, vhz |
|           19 |     3115 | 2024-04-05 | adalYamigos | W   | 0.395      | 0.450        | 0.000 (0.000)    | 0.065 (0.012)    | 0 (0.000) |     5.45 | beg0d, dok, dzt, santos, vhz |
|           18 |     3116 | 2024-04-05 | adalYamigos | L   | 0.395      | -            | -                | -                | -         |    -7.16 | beg0d, dok, dzt, santos, vhz |
|           17 |     3182 | 2024-04-03 | Sharks      | L   | 0.382      | -            | -                | -                | -         |    -1.87 | beg0d, dok, dzt, santos, vhz |
|           16 |     3185 | 2024-04-03 | Sharks      | L   | 0.382      | -            | -                | -                | -         |    -1.90 | beg0d, dok, dzt, santos, vhz |
|           15 |     3317 | 2024-03-27 | Corinthians | W   | 0.336      | 0.450        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     3.02 | beg0d, dok, dzt, santos, vhz |
|           14 |     3321 | 2024-03-27 | Corinthians | L   | 0.335      | -            | -                | -                | -         |    -7.68 | beg0d, dok, dzt, santos, vhz |
|           13 |     3359 | 2024-03-26 | Galorys     | L   | 0.329      | -            | -                | -                | -         |    -2.42 | beg0d, dok, dzt, santos, vhz |
|           12 |     3361 | 2024-03-26 | Galorys     | L   | 0.329      | -            | -                | -                | -         |    -2.47 | beg0d, dok, dzt, santos, vhz |
|           11 |     3440 | 2024-03-20 | Solid       | W   | 0.289      | 0.450        | 0.025 (0.003)    | 0.836 (0.109)    | 0 (0.000) |     7.05 | beg0d, dok, dzt, santos, vhz |
|           10 |     3443 | 2024-03-20 | Solid       | L   | 0.288      | -            | -                | -                | -         |    -2.05 | beg0d, dok, dzt, santos, vhz |
|            9 |     3527 | 2024-03-15 | ODDIK       | L   | 0.256      | -            | -                | -                | -         |    -1.21 | beg0d, dok, dzt, santos, vhz |
|            8 |     3528 | 2024-03-15 | ODDIK       | L   | 0.255      | -            | -                | -                | -         |    -1.22 | beg0d, dok, dzt, santos, vhz |
|            7 |     3801 | 2024-03-05 | W7M         | W   | 0.189      | 0.450        | 0.007 (0.001)    | 0.537 (0.046)    | 0 (0.000) |     4.21 | beg0d, dok, dzt, santos, vhz |
|            6 |     3803 | 2024-03-05 | W7M         | W   | 0.189      | 0.450        | 0.007 (0.001)    | 0.537 (0.046)    | 0 (0.000) |     4.26 | beg0d, dok, dzt, santos, vhz |
|            5 |     4007 | 2024-02-24 | Case        | L   | 0.122      | -            | -                | -                | -         |    -0.73 | beg0d, dok, dzt, santos, vhz |
|            4 |     4012 | 2024-02-24 | Case        | W   | 0.122      | 0.450        | 0.029 (0.002)    | 0.805 (0.044)    | 0 (0.000) |     3.14 | beg0d, dok, dzt, santos, vhz |
|            3 |     4072 | 2024-02-21 | Imperial    | L   | 0.102      | -            | -                | -                | -         |    -0.11 | beg0d, dok, dzt, santos, vhz |
|            2 |     4075 | 2024-02-21 | Imperial    | L   | 0.102      | -            | -                | -                | -         |    -0.11 | beg0d, dok, dzt, santos, vhz |
|            1 |     4257 | 2024-02-14 | 9z          | L   | 0.056      | -            | -                | -                | -         |    -0.01 | beg0d, dok, dzt, santos, vhz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($745.33)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
