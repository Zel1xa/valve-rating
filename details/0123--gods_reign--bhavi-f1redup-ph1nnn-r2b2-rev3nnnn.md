### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn<br />
Global Rank: [123](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  796.9<br />
<br />
Final Rank Value (796.9) = Starting Rank Value (770.3) + Head To Head Adjustments (26.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.418[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.058[<sup>2</sup>](#table1)

The average of these factors is 0.181<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 770.3
- 400 + ( ( 0.181 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 770.3


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
|           21 |      476 | 2024-07-21 | Carnival           | W   | 1.000      | 0.262        | 0.002 (0.001)    | -                | 0 (0.000) |     5.18 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |      914 | 2024-06-30 | True Rippers       | W   | 0.965      | 0.262        | 0.005 (0.001)    | 0.171 (0.043)    | 0 (0.000) |    13.03 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           19 |      916 | 2024-06-29 | LOT                | W   | 0.965      | -            | -                | -                | 0 (0.000) |     3.26 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |      920 | 2024-06-29 | True Rippers       | L   | 0.960      | -            | -                | -                | -         |   -17.55 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |      921 | 2024-06-29 | Marcos             | W   | 0.959      | 0.143        | -                | 0.037 (0.005)    | 0 (0.000) |     4.87 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |      927 | 2024-06-28 | Carnival           | W   | 0.952      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.27 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |      932 | 2024-06-27 | True Rippers       | L   | 0.947      | -            | -                | -                | -         |   -18.64 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     1727 | 2024-05-26 | True Rippers       | W   | 0.732      | 0.262        | 0.005 (0.001)    | 0.171 (0.033)    | 0 (0.000) |     8.45 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           13 |     1730 | 2024-05-25 | Marcos             | W   | 0.731      | 0.262        | -                | 0.037 (0.007)    | 0 (0.000) |     3.64 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     2947 | 2024-04-10 | BIG                | L   | 0.428      | -            | -                | -                | -         |    -0.73 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           11 |     3001 | 2024-04-09 | Ninjas in Pyjamas  | L   | 0.421      | -            | -                | -                | -         |    -0.10 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           10 |     3245 | 2024-03-31 | True Rippers       | W   | 0.359      | 0.143        | 0.005 (0.000)    | 0.171 (0.009)    | 0 (0.000) |     4.20 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     3260 | 2024-03-29 | Marcos             | W   | 0.346      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     3.08 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     3353 | 2024-03-24 | Marcos             | W   | 0.312      | 0.262        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     2.84 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     3355 | 2024-03-23 | Grayfox            | W   | 0.311      | 0.262        | 0.000 (0.000)    | 0.005 (0.000)    | -         |     2.56 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     3497 | 2024-03-16 | Aurora             | L   | 0.260      | -            | -                | -                | -         |    -0.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     3499 | 2024-03-15 | Bad News Kangaroos | W   | 0.258      | 0.432        | 0.017 (0.002)    | 0.226 (0.025)    | 1 (0.258) |     4.16 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            4 |     3518 | 2024-03-15 | Aurora             | L   | 0.252      | -            | -                | -                | -         |    -0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            3 |     3550 | 2024-03-14 | GRDX               | W   | 0.246      | 0.432        | 0.002 (0.000)    | -                | 1 (0.246) |     1.65 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     3977 | 2024-02-25 | Grayfox            | W   | 0.125      | 0.262        | -                | 0.005 (0.000)    | -         |     1.07 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     3978 | 2024-02-24 | 2ez                | W   | 0.125      | -            | -                | -                | -         |     0.44 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,190.87)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-30 |      0.965 | $1,000.00      | $965.21         |
| 2024-05-26 |      0.732 | $1,000.00      | $732.31         |
| 2024-04-14 |      0.454 | $15,000.00     | $6,807.99       |
| 2024-03-24 |      0.312 | $1,000.00      | $311.99         |
| 2024-03-16 |      0.260 | $12,500.00     | $3,247.97       |
| 2024-02-25 |      0.125 | $1,000.00      | $125.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
