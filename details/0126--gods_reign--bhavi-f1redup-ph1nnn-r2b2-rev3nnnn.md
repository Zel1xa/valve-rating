### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn<br />
Global Rank: [126](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  795.6<br />
<br />
Final Rank Value (795.6) = Starting Rank Value (769.4) + Head To Head Adjustments (26.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.417[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 769.4
- 400 + ( ( 0.180 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 769.4


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
|           21 |      525 | 2024-07-21 | Carnival           | W   | 1.000      | 0.262        | 0.002 (0.001)    | -                | 0 (0.000) |     5.23 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |      963 | 2024-06-30 | True Rippers       | W   | 0.957      | 0.262        | 0.005 (0.001)    | 0.167 (0.042)    | 0 (0.000) |    12.93 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           19 |      965 | 2024-06-29 | LOT                | W   | 0.957      | -            | -                | -                | 0 (0.000) |     3.25 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |      969 | 2024-06-29 | True Rippers       | L   | 0.952      | -            | -                | -                | -         |   -17.41 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |      970 | 2024-06-29 | Marcos             | W   | 0.951      | 0.143        | -                | 0.037 (0.005)    | 0 (0.000) |     4.87 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |      976 | 2024-06-28 | Carnival           | W   | 0.945      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.28 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |      981 | 2024-06-27 | True Rippers       | L   | 0.939      | -            | -                | -                | -         |   -18.47 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     1776 | 2024-05-26 | True Rippers       | W   | 0.724      | 0.262        | 0.005 (0.001)    | 0.167 (0.032)    | 0 (0.000) |     8.37 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           13 |     1779 | 2024-05-25 | Marcos             | W   | 0.724      | 0.262        | -                | 0.037 (0.007)    | 0 (0.000) |     3.63 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     2996 | 2024-04-10 | BIG                | L   | 0.420      | -            | -                | -                | -         |    -0.71 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           11 |     3050 | 2024-04-09 | Ninjas in Pyjamas  | L   | 0.413      | -            | -                | -                | -         |    -0.09 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           10 |     3294 | 2024-03-31 | True Rippers       | W   | 0.351      | 0.143        | 0.005 (0.000)    | 0.167 (0.008)    | 0 (0.000) |     4.11 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     3309 | 2024-03-29 | Marcos             | W   | 0.338      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     3.02 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     3402 | 2024-03-24 | Marcos             | W   | 0.304      | 0.262        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     2.78 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     3404 | 2024-03-23 | Grayfox            | W   | 0.303      | 0.262        | 0.000 (0.000)    | 0.005 (0.000)    | -         |     2.51 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     3546 | 2024-03-16 | Aurora             | L   | 0.252      | -            | -                | -                | -         |    -0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     3548 | 2024-03-15 | Bad News Kangaroos | W   | 0.250      | 0.432        | 0.017 (0.002)    | 0.222 (0.024)    | 1 (0.250) |     4.03 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            4 |     3567 | 2024-03-15 | Aurora             | L   | 0.244      | -            | -                | -                | -         |    -0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            3 |     3599 | 2024-03-14 | GRDX               | W   | 0.238      | 0.432        | 0.002 (0.000)    | -                | 1 (0.238) |     1.60 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     4026 | 2024-02-25 | Grayfox            | W   | 0.117      | 0.262        | -                | 0.005 (0.000)    | -         |     1.00 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     4027 | 2024-02-24 | 2ez                | W   | 0.117      | -            | -                | -                | -         |     0.41 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,942.22)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-30 |      0.957 | $1,000.00      | $957.31         |
| 2024-05-26 |      0.724 | $1,000.00      | $724.42         |
| 2024-04-14 |      0.446 | $15,000.00     | $6,689.58       |
| 2024-03-24 |      0.304 | $1,000.00      | $304.10         |
| 2024-03-16 |      0.252 | $12,500.00     | $3,149.31       |
| 2024-02-25 |      0.117 | $1,000.00      | $117.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
