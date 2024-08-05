### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn<br />
Global Rank: [125](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  796.2<br />
<br />
Final Rank Value (796.2) = Starting Rank Value (769.7) + Head To Head Adjustments (26.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.418[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.057[<sup>2</sup>](#table1)

The average of these factors is 0.181<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 769.7
- 400 + ( ( 0.181 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 769.7


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
|           21 |      504 | 2024-07-21 | Carnival           | W   | 1.000      | 0.262        | 0.002 (0.001)    | -                | 0 (0.000) |     5.20 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |      942 | 2024-06-30 | True Rippers       | W   | 0.962      | 0.262        | 0.005 (0.001)    | 0.170 (0.043)    | 0 (0.000) |    12.99 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           19 |      944 | 2024-06-29 | LOT                | W   | 0.961      | -            | -                | -                | 0 (0.000) |     3.26 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |      948 | 2024-06-29 | True Rippers       | L   | 0.957      | -            | -                | -                | -         |   -17.49 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |      949 | 2024-06-29 | Marcos             | W   | 0.956      | 0.143        | -                | 0.037 (0.005)    | 0 (0.000) |     4.87 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |      955 | 2024-06-28 | Carnival           | W   | 0.949      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.28 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |      960 | 2024-06-27 | True Rippers       | L   | 0.943      | -            | -                | -                | -         |   -18.56 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     1755 | 2024-05-26 | True Rippers       | W   | 0.729      | 0.262        | 0.005 (0.001)    | 0.170 (0.032)    | 0 (0.000) |     8.42 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           13 |     1758 | 2024-05-25 | Marcos             | W   | 0.728      | 0.262        | -                | 0.037 (0.007)    | 0 (0.000) |     3.63 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     2975 | 2024-04-10 | BIG                | L   | 0.425      | -            | -                | -                | -         |    -0.72 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           11 |     3029 | 2024-04-09 | Ninjas in Pyjamas  | L   | 0.418      | -            | -                | -                | -         |    -0.10 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           10 |     3273 | 2024-03-31 | True Rippers       | W   | 0.355      | 0.143        | 0.005 (0.000)    | 0.170 (0.009)    | 0 (0.000) |     4.16 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     3288 | 2024-03-29 | Marcos             | W   | 0.343      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     3.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     3381 | 2024-03-24 | Marcos             | W   | 0.309      | 0.262        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     2.82 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     3383 | 2024-03-23 | Grayfox            | W   | 0.308      | 0.262        | 0.000 (0.000)    | 0.005 (0.000)    | -         |     2.54 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     3525 | 2024-03-16 | Aurora             | L   | 0.256      | -            | -                | -                | -         |    -0.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     3527 | 2024-03-15 | Bad News Kangaroos | W   | 0.255      | 0.432        | 0.017 (0.002)    | 0.226 (0.025)    | 1 (0.255) |     4.10 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            4 |     3546 | 2024-03-15 | Aurora             | L   | 0.249      | -            | -                | -                | -         |    -0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            3 |     3578 | 2024-03-14 | GRDX               | W   | 0.243      | 0.432        | 0.002 (0.000)    | -                | 1 (0.243) |     1.63 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     4005 | 2024-02-25 | Grayfox            | W   | 0.122      | 0.262        | -                | 0.005 (0.000)    | -         |     1.04 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     4006 | 2024-02-24 | 2ez                | W   | 0.121      | -            | -                | -                | -         |     0.43 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,082.22)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-30 |      0.962 | $1,000.00      | $961.76         |
| 2024-05-26 |      0.729 | $1,000.00      | $728.87         |
| 2024-04-14 |      0.450 | $15,000.00     | $6,756.25       |
| 2024-03-24 |      0.309 | $1,000.00      | $308.54         |
| 2024-03-16 |      0.256 | $12,500.00     | $3,204.86       |
| 2024-02-25 |      0.122 | $1,000.00      | $121.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
