### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn<br />
Global Rank: [123](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  797.1<br />
<br />
Final Rank Value (797.1) = Starting Rank Value (770.3) + Head To Head Adjustments (26.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.419[<sup>1</sup>](#table2)
- Bounty Collected: 0.237[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
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
|           21 |      465 | 2024-07-21 | Carnival           | W   | 1.000      | 0.262        | 0.002 (0.001)    | -                | 0 (0.000) |     5.17 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |      902 | 2024-06-30 | True Rippers       | W   | 0.969      | 0.262        | 0.006 (0.001)    | 0.171 (0.043)    | 0 (0.000) |    13.10 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           19 |      904 | 2024-06-29 | LOT                | W   | 0.969      | -            | -                | -                | 0 (0.000) |     3.27 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |      908 | 2024-06-29 | True Rippers       | L   | 0.964      | -            | -                | -                | -         |   -17.59 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |      909 | 2024-06-29 | Marcos             | W   | 0.963      | 0.143        | -                | 0.037 (0.005)    | 0 (0.000) |     4.89 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |      915 | 2024-06-28 | Carnival           | W   | 0.956      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.28 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |      920 | 2024-06-27 | True Rippers       | L   | 0.950      | -            | -                | -                | -         |   -18.69 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     1715 | 2024-05-26 | True Rippers       | W   | 0.736      | 0.262        | 0.006 (0.001)    | 0.171 (0.033)    | 0 (0.000) |     8.51 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           13 |     1718 | 2024-05-25 | Marcos             | W   | 0.735      | 0.262        | -                | 0.037 (0.007)    | 0 (0.000) |     3.65 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     2934 | 2024-04-10 | BIG                | L   | 0.432      | -            | -                | -                | -         |    -0.73 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           11 |     2988 | 2024-04-09 | Ninjas in Pyjamas  | L   | 0.425      | -            | -                | -                | -         |    -0.10 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           10 |     3232 | 2024-03-31 | True Rippers       | W   | 0.363      | 0.143        | 0.006 (0.000)    | 0.171 (0.009)    | 0 (0.000) |     4.26 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     3247 | 2024-03-29 | Marcos             | W   | 0.350      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     3.12 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     3340 | 2024-03-24 | Marcos             | W   | 0.316      | 0.262        | 0.000 (0.000)    | 0.012 (0.001)    | -         |     2.88 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     3342 | 2024-03-23 | Grayfox            | W   | 0.315      | 0.262        | 0.000 (0.000)    | 0.005 (0.000)    | -         |     2.60 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     3484 | 2024-03-16 | Aurora             | L   | 0.264      | -            | -                | -                | -         |    -0.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     3486 | 2024-03-15 | Bad News Kangaroos | W   | 0.262      | 0.432        | 0.017 (0.002)    | 0.108 (0.012)    | 1 (0.262) |     4.02 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            4 |     3505 | 2024-03-15 | Aurora             | L   | 0.256      | -            | -                | -                | -         |    -0.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            3 |     3537 | 2024-03-14 | GRDX               | W   | 0.250      | 0.432        | 0.002 (0.000)    | -                | 1 (0.250) |     1.67 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     3963 | 2024-02-25 | Grayfox            | W   | 0.129      | 0.262        | -                | 0.005 (0.000)    | -         |     1.10 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     3964 | 2024-02-24 | 2ez                | W   | 0.129      | -            | -                | -                | -         |     0.45 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,309.72)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-30 |      0.969 | $1,000.00      | $968.98         |
| 2024-05-26 |      0.736 | $1,000.00      | $736.09         |
| 2024-04-14 |      0.458 | $15,000.00     | $6,864.58       |
| 2024-03-24 |      0.316 | $1,000.00      | $315.76         |
| 2024-03-16 |      0.264 | $12,500.00     | $3,295.14       |
| 2024-02-25 |      0.129 | $1,000.00      | $129.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
