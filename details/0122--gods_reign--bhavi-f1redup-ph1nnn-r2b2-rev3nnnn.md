### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn<br />
Global Rank: [122](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
<br />
Final Rank Value:  803.8<br />
<br />
Final Rank Value (803.8) = Starting Rank Value (777.5) + Head To Head Adjustments (26.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.421[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.063[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.5
- 400 + ( ( 0.184 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 777.5


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
|           21 |      386 | 2024-07-21 | Carnival           | W   | 1.000      | 0.262        | 0.002 (0.001)    | -                | 0 (0.000) |     5.02 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |      840 | 2024-06-30 | True Rippers       | W   | 0.984      | 0.262        | 0.006 (0.002)    | 0.172 (0.044)    | 0 (0.000) |    13.27 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           19 |      842 | 2024-06-29 | LOT                | W   | 0.984      | -            | -                | -                | 0 (0.000) |     3.21 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |      846 | 2024-06-29 | True Rippers       | L   | 0.979      | -            | -                | -                | -         |   -17.89 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |      847 | 2024-06-29 | Marcos             | W   | 0.978      | 0.143        | -                | 0.037 (0.005)    | 0 (0.000) |     4.82 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |      853 | 2024-06-28 | Carnival           | W   | 0.971      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.20 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |      858 | 2024-06-27 | True Rippers       | L   | 0.965      | -            | -                | -                | -         |   -19.04 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     1660 | 2024-05-26 | True Rippers       | W   | 0.751      | 0.262        | 0.006 (0.001)    | 0.172 (0.034)    | 0 (0.000) |     8.62 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           13 |     1663 | 2024-05-25 | Marcos             | W   | 0.750      | 0.262        | -                | 0.037 (0.007)    | 0 (0.000) |     3.61 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     2931 | 2024-04-10 | BIG                | L   | 0.447      | -            | -                | -                | -         |    -1.16 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           11 |     2985 | 2024-04-09 | Ninjas in Pyjamas  | L   | 0.440      | -            | -                | -                | -         |    -0.22 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           10 |     3237 | 2024-03-31 | True Rippers       | W   | 0.378      | 0.143        | 0.006 (0.000)    | 0.172 (0.009)    | 0 (0.000) |     4.40 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     3252 | 2024-03-29 | Marcos             | W   | 0.365      | 0.143        | 0.001 (0.000)    | 0.013 (0.001)    | -         |     3.20 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     3350 | 2024-03-24 | Marcos             | W   | 0.331      | 0.262        | 0.001 (0.000)    | 0.013 (0.001)    | -         |     2.97 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     3352 | 2024-03-23 | Grayfox            | W   | 0.330      | 0.262        | 0.000 (0.000)    | 0.006 (0.000)    | -         |     2.67 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     3494 | 2024-03-16 | Aurora             | L   | 0.279      | -            | -                | -                | -         |    -0.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     3496 | 2024-03-15 | Bad News Kangaroos | W   | 0.277      | 0.432        | 0.017 (0.002)    | 0.111 (0.013)    | 1 (0.277) |     4.26 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            4 |     3515 | 2024-03-15 | Aurora             | L   | 0.271      | -            | -                | -                | -         |    -0.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            3 |     3551 | 2024-03-14 | GRDX               | W   | 0.265      | 0.432        | 0.002 (0.000)    | -                | 1 (0.265) |     1.73 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     3989 | 2024-02-25 | Grayfox            | W   | 0.144      | 0.262        | -                | 0.006 (0.000)    | -         |     1.21 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     3990 | 2024-02-24 | 2ez                | W   | 0.144      | -            | -                | -                | -         |     0.49 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,782.22)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-30 |      0.984 | $1,000.00      | $983.98         |
| 2024-05-26 |      0.751 | $1,000.00      | $751.09         |
| 2024-04-14 |      0.473 | $15,000.00     | $7,089.58       |
| 2024-03-24 |      0.331 | $1,000.00      | $330.76         |
| 2024-03-16 |      0.279 | $12,500.00     | $3,482.64       |
| 2024-02-25 |      0.144 | $1,000.00      | $144.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
