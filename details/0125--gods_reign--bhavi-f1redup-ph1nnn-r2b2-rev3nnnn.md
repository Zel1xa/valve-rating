### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn<br />
Global Rank: [125](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  795.1<br />
<br />
Final Rank Value (795.1) = Starting Rank Value (769.1) + Head To Head Adjustments (26.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.417[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.055[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 769.1
- 400 + ( ( 0.179 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 769.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      536 | 2024-07-21 | Carnival           | W   | 1.000      | 0.262        | 0.002 (0.001)    | -                | 0 (0.000) |     5.25 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |      974 | 2024-06-30 | True Rippers       | W   | 0.952      | 0.262        | 0.005 (0.001)    | 0.163 (0.041)    | 0 (0.000) |    12.86 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           19 |      976 | 2024-06-29 | LOT                | W   | 0.952      | -            | -                | -                | 0 (0.000) |     3.24 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |      980 | 2024-06-29 | True Rippers       | L   | 0.947      | -            | -                | -                | -         |   -17.32 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |      981 | 2024-06-29 | Marcos             | W   | 0.946      | 0.143        | -                | 0.036 (0.005)    | 0 (0.000) |     4.86 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |      987 | 2024-06-28 | Carnival           | W   | 0.940      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.28 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |      992 | 2024-06-27 | True Rippers       | L   | 0.934      | -            | -                | -                | -         |   -18.37 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     1787 | 2024-05-26 | True Rippers       | W   | 0.719      | 0.262        | 0.005 (0.001)    | 0.163 (0.031)    | 0 (0.000) |     8.32 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           13 |     1790 | 2024-05-25 | Marcos             | W   | 0.719      | 0.262        | -                | 0.036 (0.007)    | 0 (0.000) |     3.62 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     3007 | 2024-04-10 | BIG                | L   | 0.415      | -            | -                | -                | -         |    -0.70 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           11 |     3061 | 2024-04-09 | Ninjas in Pyjamas  | L   | 0.408      | -            | -                | -                | -         |    -0.09 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           10 |     3305 | 2024-03-31 | True Rippers       | W   | 0.346      | 0.143        | 0.005 (0.000)    | 0.163 (0.008)    | 0 (0.000) |     4.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     3320 | 2024-03-29 | Marcos             | W   | 0.333      | 0.143        | 0.000 (0.000)    | 0.011 (0.001)    | -         |     2.99 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     3413 | 2024-03-24 | Marcos             | W   | 0.299      | 0.262        | 0.000 (0.000)    | 0.011 (0.001)    | -         |     2.74 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     3415 | 2024-03-23 | Grayfox            | W   | 0.298      | 0.262        | 0.000 (0.000)    | 0.004 (0.000)    | -         |     2.47 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     3557 | 2024-03-16 | Aurora             | L   | 0.247      | -            | -                | -                | -         |    -0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     3559 | 2024-03-15 | Bad News Kangaroos | W   | 0.245      | 0.432        | 0.016 (0.002)    | 0.217 (0.023)    | 1 (0.245) |     3.95 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            4 |     3578 | 2024-03-15 | Aurora             | L   | 0.239      | -            | -                | -                | -         |    -0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            3 |     3610 | 2024-03-14 | GRDX               | W   | 0.233      | 0.432        | 0.002 (0.000)    | -                | 1 (0.233) |     1.57 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     4037 | 2024-02-25 | Grayfox            | W   | 0.113      | 0.262        | -                | 0.004 (0.000)    | -         |     0.96 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     4038 | 2024-02-24 | 2ez                | W   | 0.112      | -            | -                | -                | -         |     0.40 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,784.72)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-30 |      0.952 | $1,000.00      | $952.31         |
| 2024-05-26 |      0.719 | $1,000.00      | $719.42         |
| 2024-04-14 |      0.441 | $15,000.00     | $6,614.58       |
| 2024-03-24 |      0.299 | $1,000.00      | $299.10         |
| 2024-03-16 |      0.247 | $12,500.00     | $3,086.81       |
| 2024-02-25 |      0.113 | $1,000.00      | $112.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
