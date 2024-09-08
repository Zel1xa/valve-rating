### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Mcg!LLzZz, Ph1NNN, reV3nnnn<br />
Global Rank: [144](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
<br />
Final Rank Value:  713.0<br />
<br />
Final Rank Value (713.0) = Starting Rank Value (697.0) + Head To Head Adjustments (16.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.219[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.004[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 697.0
- 400 + ( ( 0.153 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 697.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      236 | 2024-08-30 | Alter Ego          | L   | 1.000      | -            | -                | -                | -         |   -18.98 | Bhavi, f1redup, Mcg!LLzZz, Ph1NNN, reV3nnnn |
|           24 |      244 | 2024-08-30 | True Rippers       | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.223 (0.032)    | 0 (0.000) |    13.42 | Bhavi, f1redup, Mcg!LLzZz, Ph1NNN, reV3nnnn |
|           23 |      287 | 2024-08-29 | Alter Ego          | L   | 1.000      | -            | -                | -                | -         |   -20.04 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|           22 |      341 | 2024-08-28 | Forward            | W   | 1.000      | 0.143        | -                | 0.038 (0.005)    | 0 (0.000) |     6.30 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|           21 |      357 | 2024-08-28 | ONi                | W   | 1.000      | 0.143        | -                | 0.113 (0.016)    | 0 (0.000) |     6.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|           20 |      749 | 2024-08-18 | Victores Sumus     | W   | 1.000      | 0.262        | 0.002 (0.000)    | -                | 0 (0.000) |     7.80 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|           19 |     1664 | 2024-07-21 | Carnival           | W   | 0.872      | 0.262        | 0.002 (0.000)    | -                | 0 (0.000) |     6.38 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|           18 |     2105 | 2024-06-30 | True Rippers       | W   | 0.732      | 0.262        | 0.003 (0.001)    | 0.223 (0.043)    | 0 (0.000) |    11.01 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn      |
|           17 |     2107 | 2024-06-29 | LOT                | W   | 0.731      | -            | -                | -                | 0 (0.000) |     3.62 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|           16 |     2111 | 2024-06-29 | True Rippers       | L   | 0.727      | -            | -                | -                | -         |   -12.27 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|           15 |     2112 | 2024-06-29 | Marcos             | W   | 0.726      | 0.143        | -                | 0.027 (0.003)    | 0 (0.000) |     5.14 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|           14 |     2118 | 2024-06-28 | Carnival           | W   | 0.719      | 0.143        | 0.002 (0.000)    | -                | -         |     5.74 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|           13 |     2123 | 2024-06-27 | True Rippers       | L   | 0.713      | -            | -                | -                | -         |   -12.68 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|           12 |     2918 | 2024-05-26 | True Rippers       | W   | 0.499      | 0.262        | 0.003 (0.000)    | 0.223 (0.029)    | -         |     6.87 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn      |
|           11 |     2921 | 2024-05-25 | Marcos             | W   | 0.498      | 0.262        | -                | 0.027 (0.003)    | -         |     3.57 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|           10 |     4138 | 2024-04-10 | BIG                | L   | 0.195      | -            | -                | -                | -         |    -0.36 | Bhavi, f1redup, Ph1NNN, R2B2, yoom          |
|            9 |     4192 | 2024-04-09 | Ninjas in Pyjamas  | L   | 0.188      | -            | -                | -                | -         |    -0.09 | Bhavi, f1redup, Ph1NNN, R2B2, yoom          |
|            8 |     4436 | 2024-03-31 | True Rippers       | W   | 0.125      | 0.143        | 0.003 (0.000)    | 0.223 (0.004)    | -         |     1.74 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|            7 |     4451 | 2024-03-29 | Marcos             | W   | 0.113      | 0.143        | 0.000 (0.000)    | -                | -         |     1.20 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|            6 |     4544 | 2024-03-24 | Marcos             | W   | 0.079      | 0.262        | 0.000 (0.000)    | 0.003 (0.000)    | -         |     0.84 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|            5 |     4546 | 2024-03-23 | Grayfox            | W   | 0.078      | -            | -                | -                | -         |     0.39 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|            4 |     4688 | 2024-03-16 | Aurora             | L   | 0.026      | -            | -                | -                | -         |    -0.01 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|            3 |     4690 | 2024-03-15 | Bad News Kangaroos | W   | 0.025      | 0.432        | 0.008 (0.000)    | 0.034 (0.000)    | 1 (0.025) |     0.35 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|            2 |     4709 | 2024-03-15 | Aurora             | L   | 0.019      | -            | -                | -                | -         |    -0.01 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |
|            1 |     4741 | 2024-03-14 | GRDX               | W   | 0.013      | -            | -                | -                | 1 (0.013) |     0.10 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,817.08)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-18 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-21 |      0.872 | $1,000.00      | $871.81         |
| 2024-06-30 |      0.732 | $1,000.00      | $731.76         |
| 2024-05-26 |      0.499 | $1,000.00      | $498.87         |
| 2024-04-14 |      0.220 | $15,000.00     | $3,306.25       |
| 2024-03-24 |      0.079 | $1,000.00      | $78.54          |
| 2024-03-16 |      0.026 | $12,500.00     | $329.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
