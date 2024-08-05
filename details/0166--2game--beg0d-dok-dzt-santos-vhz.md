### Roster Details<br />
Team Name: 2GAME<br />
Roster: beg0d, dok, dzt, santos, vhz<br />
Global Rank: [166](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [45]( ../standings_americas.md)<br />
<br />
Final Rank Value:  670.7<br />
<br />
Final Rank Value (670.7) = Starting Rank Value (674.9) + Head To Head Adjustments (-4.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.237[<sup>2</sup>](#table1)
- Opponent Network: 0.026[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.9
- 400 + ( ( 0.134 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 674.9


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
|           21 |     2959 | 2024-04-10 | RED Canids  | L   | 0.426      | -            | -                | -                | -         |    -1.16 | beg0d, dok, dzt, santos, vhz |
|           20 |     2962 | 2024-04-10 | RED Canids  | L   | 0.426      | -            | -                | -                | -         |    -1.17 | beg0d, dok, dzt, santos, vhz |
|           19 |     3120 | 2024-04-05 | adalYamigos | W   | 0.393      | 0.450        | 0.000 (0.000)    | 0.064 (0.011)    | 0 (0.000) |     5.40 | beg0d, dok, dzt, santos, vhz |
|           18 |     3121 | 2024-04-05 | adalYamigos | L   | 0.392      | -            | -                | -                | -         |    -7.12 | beg0d, dok, dzt, santos, vhz |
|           17 |     3187 | 2024-04-03 | Sharks      | L   | 0.379      | -            | -                | -                | -         |    -1.85 | beg0d, dok, dzt, santos, vhz |
|           16 |     3190 | 2024-04-03 | Sharks      | L   | 0.379      | -            | -                | -                | -         |    -1.89 | beg0d, dok, dzt, santos, vhz |
|           15 |     3322 | 2024-03-27 | Corinthians | W   | 0.333      | 0.450        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     3.00 | beg0d, dok, dzt, santos, vhz |
|           14 |     3326 | 2024-03-27 | Corinthians | L   | 0.333      | -            | -                | -                | -         |    -7.62 | beg0d, dok, dzt, santos, vhz |
|           13 |     3364 | 2024-03-26 | Galorys     | L   | 0.327      | -            | -                | -                | -         |    -2.39 | beg0d, dok, dzt, santos, vhz |
|           12 |     3366 | 2024-03-26 | Galorys     | L   | 0.326      | -            | -                | -                | -         |    -2.44 | beg0d, dok, dzt, santos, vhz |
|           11 |     3445 | 2024-03-20 | Solid       | W   | 0.286      | 0.450        | 0.025 (0.003)    | 0.836 (0.108)    | 0 (0.000) |     6.99 | beg0d, dok, dzt, santos, vhz |
|           10 |     3448 | 2024-03-20 | Solid       | L   | 0.286      | -            | -                | -                | -         |    -2.03 | beg0d, dok, dzt, santos, vhz |
|            9 |     3532 | 2024-03-15 | ODDIK       | L   | 0.253      | -            | -                | -                | -         |    -1.20 | beg0d, dok, dzt, santos, vhz |
|            8 |     3533 | 2024-03-15 | ODDIK       | L   | 0.253      | -            | -                | -                | -         |    -1.21 | beg0d, dok, dzt, santos, vhz |
|            7 |     3806 | 2024-03-05 | W7M         | W   | 0.186      | 0.450        | 0.007 (0.001)    | 0.538 (0.045)    | 0 (0.000) |     4.16 | beg0d, dok, dzt, santos, vhz |
|            6 |     3808 | 2024-03-05 | W7M         | W   | 0.186      | 0.450        | 0.007 (0.001)    | 0.538 (0.045)    | 0 (0.000) |     4.21 | beg0d, dok, dzt, santos, vhz |
|            5 |     4012 | 2024-02-24 | Case        | L   | 0.120      | -            | -                | -                | -         |    -0.71 | beg0d, dok, dzt, santos, vhz |
|            4 |     4017 | 2024-02-24 | Case        | W   | 0.119      | 0.450        | 0.029 (0.002)    | 0.806 (0.043)    | 0 (0.000) |     3.07 | beg0d, dok, dzt, santos, vhz |
|            3 |     4077 | 2024-02-21 | Imperial    | L   | 0.100      | -            | -                | -                | -         |    -0.11 | beg0d, dok, dzt, santos, vhz |
|            2 |     4080 | 2024-02-21 | Imperial    | L   | 0.099      | -            | -                | -                | -         |    -0.11 | beg0d, dok, dzt, santos, vhz |
|            1 |     4262 | 2024-02-14 | 9z          | L   | 0.053      | -            | -                | -                | -         |    -0.01 | beg0d, dok, dzt, santos, vhz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($742.92)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />