### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn<br />
Global Rank: [126](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  795.1<br />
<br />
Final Rank Value (795.1) = Starting Rank Value (769.0) + Head To Head Adjustments (26.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.417[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 769.0
- 400 + ( ( 0.180 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 769.0


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
|           21 |      528 | 2024-07-21 | Carnival           | W   | 1.000      | 0.262        | 0.002 (0.001)    | -                | 0 (0.000) |     5.24 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |      966 | 2024-06-30 | True Rippers       | W   | 0.955      | 0.262        | 0.005 (0.001)    | 0.167 (0.042)    | 0 (0.000) |    12.90 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           19 |      968 | 2024-06-29 | LOT                | W   | 0.955      | -            | -                | -                | 0 (0.000) |     3.25 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |      972 | 2024-06-29 | True Rippers       | L   | 0.950      | -            | -                | -                | -         |   -17.37 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |      973 | 2024-06-29 | Marcos             | W   | 0.949      | 0.143        | -                | 0.037 (0.005)    | 0 (0.000) |     4.87 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |      979 | 2024-06-28 | Carnival           | W   | 0.942      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.28 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |      984 | 2024-06-27 | True Rippers       | L   | 0.937      | -            | -                | -                | -         |   -18.43 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     1779 | 2024-05-26 | True Rippers       | W   | 0.722      | 0.262        | 0.005 (0.001)    | 0.167 (0.032)    | 0 (0.000) |     8.35 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           13 |     1782 | 2024-05-25 | Marcos             | W   | 0.721      | 0.262        | -                | 0.037 (0.007)    | 0 (0.000) |     3.63 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     2999 | 2024-04-10 | BIG                | L   | 0.418      | -            | -                | -                | -         |    -0.71 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           11 |     3053 | 2024-04-09 | Ninjas in Pyjamas  | L   | 0.411      | -            | -                | -                | -         |    -0.09 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           10 |     3297 | 2024-03-31 | True Rippers       | W   | 0.349      | 0.143        | 0.005 (0.000)    | 0.167 (0.008)    | 0 (0.000) |     4.09 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     3312 | 2024-03-29 | Marcos             | W   | 0.336      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     3.01 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     3405 | 2024-03-24 | Marcos             | W   | 0.302      | 0.262        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     2.77 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     3407 | 2024-03-23 | Grayfox            | W   | 0.301      | 0.262        | 0.000 (0.000)    | 0.004 (0.000)    | -         |     2.49 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     3549 | 2024-03-16 | Aurora             | L   | 0.250      | -            | -                | -                | -         |    -0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     3551 | 2024-03-15 | Bad News Kangaroos | W   | 0.248      | 0.432        | 0.016 (0.002)    | 0.222 (0.024)    | 1 (0.248) |     3.99 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            4 |     3570 | 2024-03-15 | Aurora             | L   | 0.242      | -            | -                | -                | -         |    -0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            3 |     3602 | 2024-03-14 | GRDX               | W   | 0.236      | 0.432        | 0.002 (0.000)    | -                | 1 (0.236) |     1.59 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     4029 | 2024-02-25 | Grayfox            | W   | 0.115      | 0.262        | -                | 0.004 (0.000)    | -         |     0.98 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     4030 | 2024-02-24 | 2ez                | W   | 0.115      | -            | -                | -                | -         |     0.41 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,872.22)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-30 |      0.955 | $1,000.00      | $955.09         |
| 2024-05-26 |      0.722 | $1,000.00      | $722.20         |
| 2024-04-14 |      0.444 | $15,000.00     | $6,656.25       |
| 2024-03-24 |      0.302 | $1,000.00      | $301.88         |
| 2024-03-16 |      0.250 | $12,500.00     | $3,121.53       |
| 2024-02-25 |      0.115 | $1,000.00      | $115.28         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
