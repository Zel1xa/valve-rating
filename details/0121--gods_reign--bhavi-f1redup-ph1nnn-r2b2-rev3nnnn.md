### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn<br />
Global Rank: [121](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  798.1<br />
<br />
Final Rank Value (798.1) = Starting Rank Value (771.4) + Head To Head Adjustments (26.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.419[<sup>1</sup>](#table2)
- Bounty Collected: 0.237[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.059[<sup>2</sup>](#table1)

The average of these factors is 0.182<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 771.4
- 400 + ( ( 0.182 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 771.4


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
|           21 |      442 | 2024-07-21 | Carnival           | W   | 1.000      | 0.262        | 0.002 (0.001)    | -                | 0 (0.000) |     5.15 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |      872 | 2024-06-30 | True Rippers       | W   | 0.971      | 0.262        | 0.006 (0.001)    | 0.177 (0.045)    | 0 (0.000) |    13.12 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           19 |      874 | 2024-06-29 | LOT                | W   | 0.970      | -            | -                | -                | 0 (0.000) |     3.26 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |      878 | 2024-06-29 | True Rippers       | L   | 0.966      | -            | -                | -                | -         |   -17.63 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |      879 | 2024-06-29 | Marcos             | W   | 0.965      | 0.143        | -                | 0.039 (0.005)    | 0 (0.000) |     4.87 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |      885 | 2024-06-28 | Carnival           | W   | 0.958      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.27 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |      890 | 2024-06-27 | True Rippers       | L   | 0.952      | -            | -                | -                | -         |   -18.73 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     1651 | 2024-05-26 | True Rippers       | W   | 0.738      | 0.262        | 0.006 (0.001)    | 0.177 (0.034)    | 0 (0.000) |     8.52 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           13 |     1654 | 2024-05-25 | Marcos             | W   | 0.737      | 0.262        | -                | 0.039 (0.007)    | 0 (0.000) |     3.64 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     2868 | 2024-04-10 | BIG                | L   | 0.433      | -            | -                | -                | -         |    -0.72 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           11 |     2922 | 2024-04-09 | Ninjas in Pyjamas  | L   | 0.427      | -            | -                | -                | -         |    -0.15 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           10 |     3166 | 2024-03-31 | True Rippers       | W   | 0.364      | 0.143        | 0.006 (0.000)    | 0.177 (0.009)    | 0 (0.000) |     4.27 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     3181 | 2024-03-29 | Marcos             | W   | 0.352      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | -         |     3.13 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     3271 | 2024-03-24 | Marcos             | W   | 0.317      | 0.262        | 0.000 (0.000)    | 0.013 (0.001)    | -         |     2.89 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     3273 | 2024-03-23 | Grayfox            | W   | 0.317      | 0.262        | 0.000 (0.000)    | 0.005 (0.000)    | -         |     2.60 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     3413 | 2024-03-16 | Aurora             | L   | 0.265      | -            | -                | -                | -         |    -0.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     3415 | 2024-03-15 | Bad News Kangaroos | W   | 0.264      | 0.432        | 0.017 (0.002)    | 0.112 (0.013)    | 1 (0.264) |     4.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            4 |     3433 | 2024-03-15 | Aurora             | L   | 0.258      | -            | -                | -                | -         |    -0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            3 |     3465 | 2024-03-14 | GRDX               | W   | 0.252      | 0.432        | 0.002 (0.000)    | -                | 1 (0.252) |     1.68 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     3890 | 2024-02-25 | Grayfox            | W   | 0.131      | 0.262        | -                | 0.005 (0.000)    | -         |     1.11 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     3891 | 2024-02-24 | 2ez                | W   | 0.130      | -            | -                | -                | -         |     0.46 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,363.68)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-30 |      0.971 | $1,000.00      | $970.69         |
| 2024-05-26 |      0.738 | $1,000.00      | $737.80         |
| 2024-04-14 |      0.459 | $15,000.00     | $6,890.28       |
| 2024-03-24 |      0.317 | $1,000.00      | $317.48         |
| 2024-03-16 |      0.265 | $12,500.00     | $3,316.55       |
| 2024-02-25 |      0.131 | $1,000.00      | $130.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
