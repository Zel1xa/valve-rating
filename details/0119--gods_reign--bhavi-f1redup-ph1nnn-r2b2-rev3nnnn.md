### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
<br />
Final Rank Value:  805.8<br />
<br />
Final Rank Value (805.8) = Starting Rank Value (779.3) + Head To Head Adjustments (26.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.421[<sup>1</sup>](#table2)
- Bounty Collected: 0.240[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 779.3
- 400 + ( ( 0.184 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 779.3


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
|           21 |      351 | 2024-07-21 | Carnival           | W   | 1.000      | 0.262        | 0.002 (0.001)    | -                | 0 (0.000) |     4.98 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |      789 | 2024-06-30 | True Rippers       | W   | 0.990      | 0.262        | 0.006 (0.002)    | 0.173 (0.045)    | 0 (0.000) |    13.33 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           19 |      791 | 2024-06-29 | LOT                | W   | 0.989      | -            | -                | -                | 0 (0.000) |     3.19 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |      795 | 2024-06-29 | True Rippers       | L   | 0.985      | -            | -                | -                | -         |   -18.00 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |      796 | 2024-06-29 | Marcos             | W   | 0.984      | 0.143        | -                | 0.037 (0.005)    | 0 (0.000) |     4.81 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |      802 | 2024-06-28 | Carnival           | W   | 0.977      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.18 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |      807 | 2024-06-27 | True Rippers       | L   | 0.971      | -            | -                | -                | -         |   -19.17 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     1602 | 2024-05-26 | True Rippers       | W   | 0.757      | 0.262        | 0.006 (0.001)    | 0.173 (0.034)    | 0 (0.000) |     8.67 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|           13 |     1605 | 2024-05-25 | Marcos             | W   | 0.756      | 0.262        | -                | 0.037 (0.007)    | 0 (0.000) |     3.60 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     2822 | 2024-04-10 | BIG                | L   | 0.452      | -            | -                | -                | -         |    -1.09 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           11 |     2876 | 2024-04-09 | Ninjas in Pyjamas  | L   | 0.446      | -            | -                | -                | -         |    -0.13 | Bhavi, f1redup, Ph1NNN, R2B2, yoom     |
|           10 |     3120 | 2024-03-31 | True Rippers       | W   | 0.383      | 0.143        | 0.006 (0.000)    | 0.173 (0.009)    | 0 (0.000) |     4.46 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     3135 | 2024-03-29 | Marcos             | W   | 0.371      | 0.143        | 0.001 (0.000)    | 0.013 (0.001)    | -         |     3.23 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     3228 | 2024-03-24 | Marcos             | W   | 0.336      | 0.262        | 0.001 (0.000)    | 0.013 (0.001)    | -         |     3.01 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     3230 | 2024-03-23 | Grayfox            | W   | 0.336      | 0.262        | 0.000 (0.000)    | 0.006 (0.001)    | -         |     2.71 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     3372 | 2024-03-16 | Aurora             | L   | 0.284      | -            | -                | -                | -         |    -0.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     3374 | 2024-03-15 | Bad News Kangaroos | W   | 0.283      | 0.432        | 0.017 (0.002)    | 0.112 (0.014)    | 1 (0.283) |     4.35 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            4 |     3393 | 2024-03-15 | Aurora             | L   | 0.277      | -            | -                | -                | -         |    -0.06 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            3 |     3425 | 2024-03-14 | GRDX               | W   | 0.271      | 0.432        | 0.002 (0.000)    | -                | 1 (0.271) |     1.75 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     3852 | 2024-02-25 | Grayfox            | W   | 0.150      | 0.262        | -                | 0.006 (0.000)    | -         |     1.25 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     3853 | 2024-02-24 | 2ez                | W   | 0.149      | -            | -                | -                | -         |     0.50 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,962.62)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-30 |      0.990 | $1,000.00      | $989.71         |
| 2024-05-26 |      0.757 | $1,000.00      | $756.81         |
| 2024-04-14 |      0.478 | $15,000.00     | $7,175.49       |
| 2024-03-24 |      0.336 | $1,000.00      | $336.49         |
| 2024-03-16 |      0.284 | $12,500.00     | $3,554.22       |
| 2024-02-25 |      0.150 | $1,000.00      | $149.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
