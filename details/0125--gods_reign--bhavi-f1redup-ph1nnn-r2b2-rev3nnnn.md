### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn<br />
Global Rank: [125](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  796.7<br />
<br />
Final Rank Value (796.7) = Starting Rank Value (770.2) + Head To Head Adjustments (26.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.418[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.058[<sup>2</sup>](#table1)

The average of these factors is 0.181<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 770.2
- 400 + ( ( 0.181 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 770.2


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
|           21 |      499 | 2024-07-21 | Carnival           | W   | 1.000      | 0.262        | 0.002 (0.001)    | -                | 0 (0.000) |     5.18 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |      937 | 2024-06-30 | True Rippers       | W   | 0.964      | 0.262        | 0.005 (0.001)    | 0.170 (0.043)    | 0 (0.000) |    13.02 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           19 |      939 | 2024-06-29 | LOT                | W   | 0.964      | -            | -                | -                | 0 (0.000) |     3.26 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |      943 | 2024-06-29 | True Rippers       | L   | 0.959      | -            | -                | -                | -         |   -17.53 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |      944 | 2024-06-29 | Marcos             | W   | 0.958      | 0.143        | -                | 0.037 (0.005)    | 0 (0.000) |     4.87 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |      950 | 2024-06-28 | Carnival           | W   | 0.952      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.27 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |      955 | 2024-06-27 | True Rippers       | L   | 0.946      | -            | -                | -                | -         |   -18.62 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     1750 | 2024-05-26 | True Rippers       | W   | 0.732      | 0.262        | 0.005 (0.001)    | 0.170 (0.033)    | 0 (0.000) |     8.44 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           13 |     1753 | 2024-05-25 | Marcos             | W   | 0.731      | 0.262        | -                | 0.037 (0.007)    | 0 (0.000) |     3.64 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     2970 | 2024-04-10 | BIG                | L   | 0.427      | -            | -                | -                | -         |    -0.72 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           11 |     3024 | 2024-04-09 | Ninjas in Pyjamas  | L   | 0.420      | -            | -                | -                | -         |    -0.10 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           10 |     3268 | 2024-03-31 | True Rippers       | W   | 0.358      | 0.143        | 0.005 (0.000)    | 0.170 (0.009)    | 0 (0.000) |     4.19 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     3283 | 2024-03-29 | Marcos             | W   | 0.345      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     3.08 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     3376 | 2024-03-24 | Marcos             | W   | 0.311      | 0.262        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     2.84 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     3378 | 2024-03-23 | Grayfox            | W   | 0.311      | 0.262        | 0.000 (0.000)    | 0.005 (0.000)    | -         |     2.56 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     3520 | 2024-03-16 | Aurora             | L   | 0.259      | -            | -                | -                | -         |    -0.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     3522 | 2024-03-15 | Bad News Kangaroos | W   | 0.257      | 0.432        | 0.017 (0.002)    | 0.226 (0.025)    | 1 (0.257) |     4.15 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            4 |     3541 | 2024-03-15 | Aurora             | L   | 0.252      | -            | -                | -                | -         |    -0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            3 |     3573 | 2024-03-14 | GRDX               | W   | 0.245      | 0.432        | 0.002 (0.000)    | -                | 1 (0.245) |     1.64 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     4000 | 2024-02-25 | Grayfox            | W   | 0.125      | 0.262        | -                | 0.005 (0.000)    | -         |     1.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     4001 | 2024-02-24 | 2ez                | W   | 0.124      | -            | -                | -                | -         |     0.44 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,166.81)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-30 |      0.964 | $1,000.00      | $964.44         |
| 2024-05-26 |      0.732 | $1,000.00      | $731.55         |
| 2024-04-14 |      0.453 | $15,000.00     | $6,796.53       |
| 2024-03-24 |      0.311 | $1,000.00      | $311.23         |
| 2024-03-16 |      0.259 | $12,500.00     | $3,238.43       |
| 2024-02-25 |      0.125 | $1,000.00      | $124.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
