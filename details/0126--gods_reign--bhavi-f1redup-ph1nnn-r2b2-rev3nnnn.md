### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn<br />
Global Rank: [126](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  795.5<br />
<br />
Final Rank Value (795.5) = Starting Rank Value (769.2) + Head To Head Adjustments (26.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.418[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 769.2
- 400 + ( ( 0.180 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 769.2


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
|           21 |      517 | 2024-07-21 | Carnival           | W   | 1.000      | 0.262        | 0.002 (0.001)    | -                | 0 (0.000) |     5.22 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |      955 | 2024-06-30 | True Rippers       | W   | 0.958      | 0.262        | 0.005 (0.001)    | 0.169 (0.042)    | 0 (0.000) |    12.95 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           19 |      957 | 2024-06-29 | LOT                | W   | 0.958      | -            | -                | -                | 0 (0.000) |     3.26 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |      961 | 2024-06-29 | True Rippers       | L   | 0.953      | -            | -                | -                | -         |   -17.43 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |      962 | 2024-06-29 | Marcos             | W   | 0.952      | 0.143        | -                | 0.037 (0.005)    | 0 (0.000) |     4.87 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |      968 | 2024-06-28 | Carnival           | W   | 0.946      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.28 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |      973 | 2024-06-27 | True Rippers       | L   | 0.940      | -            | -                | -                | -         |   -18.50 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     1768 | 2024-05-26 | True Rippers       | W   | 0.726      | 0.262        | 0.005 (0.001)    | 0.169 (0.032)    | 0 (0.000) |     8.38 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           13 |     1771 | 2024-05-25 | Marcos             | W   | 0.725      | 0.262        | -                | 0.037 (0.007)    | 0 (0.000) |     3.63 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     2988 | 2024-04-10 | BIG                | L   | 0.421      | -            | -                | -                | -         |    -0.71 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           11 |     3042 | 2024-04-09 | Ninjas in Pyjamas  | L   | 0.414      | -            | -                | -                | -         |    -0.09 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           10 |     3286 | 2024-03-31 | True Rippers       | W   | 0.352      | 0.143        | 0.005 (0.000)    | 0.169 (0.009)    | 0 (0.000) |     4.13 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     3301 | 2024-03-29 | Marcos             | W   | 0.339      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     3.03 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     3394 | 2024-03-24 | Marcos             | W   | 0.305      | 0.262        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     2.79 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     3396 | 2024-03-23 | Grayfox            | W   | 0.305      | 0.262        | 0.000 (0.000)    | 0.005 (0.000)    | -         |     2.52 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     3538 | 2024-03-16 | Aurora             | L   | 0.253      | -            | -                | -                | -         |    -0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     3540 | 2024-03-15 | Bad News Kangaroos | W   | 0.251      | 0.432        | 0.017 (0.002)    | 0.225 (0.024)    | 1 (0.251) |     4.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            4 |     3559 | 2024-03-15 | Aurora             | L   | 0.246      | -            | -                | -                | -         |    -0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            3 |     3591 | 2024-03-14 | GRDX               | W   | 0.239      | 0.432        | 0.002 (0.000)    | -                | 1 (0.239) |     1.61 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     4018 | 2024-02-25 | Grayfox            | W   | 0.119      | 0.262        | -                | 0.005 (0.000)    | -         |     1.01 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     4019 | 2024-02-24 | 2ez                | W   | 0.118      | -            | -                | -                | -         |     0.42 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,977.22)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-30 |      0.958 | $1,000.00      | $958.43         |
| 2024-05-26 |      0.726 | $1,000.00      | $725.53         |
| 2024-04-14 |      0.447 | $15,000.00     | $6,706.25       |
| 2024-03-24 |      0.305 | $1,000.00      | $305.21         |
| 2024-03-16 |      0.253 | $12,500.00     | $3,163.19       |
| 2024-02-25 |      0.119 | $1,000.00      | $118.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
