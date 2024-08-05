### Roster Details<br />
Team Name: Limitless<br />
Roster: DJF, Seb, Tender, wiz, Wolffe<br />
Global Rank: [167](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  668.8<br />
<br />
Final Rank Value (668.8) = Starting Rank Value (747.7) + Head To Head Adjustments (-78.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.077[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.7
- 400 + ( ( 0.170 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 747.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |      137 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.04 | DJF, Seb, Tender, wiz, Wolffe |
|           27 |      143 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.05 | DJF, Seb, Tender, wiz, Wolffe |
|           26 |      383 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.57 | DJF, Seb, Tender, wiz, Wolffe |
|           25 |      386 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -10.33 | DJF, Seb, Tender, wiz, Wolffe |
|           24 |      416 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.23 | DJF, Seb, Tender, wiz, Wolffe |
|           23 |      418 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.50 | DJF, Seb, Tender, wiz, Wolffe |
|           22 |      649 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -10.34 | DJF, Seb, Tender, wiz, Wolffe |
|           21 |      652 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -11.19 | DJF, Seb, Tender, wiz, Wolffe |
|           20 |      707 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.11 | DJF, Seb, Tender, wiz, Wolffe |
|           19 |      713 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.47 | DJF, Seb, Tender, wiz, Wolffe |
|           18 |      757 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.50 | DJF, Seb, Tender, wiz, Wolffe |
|           17 |      760 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.01 | DJF, Seb, Tender, wiz, Wolffe |
|           16 |     1104 | 2024-06-13 | E-Xolos LAZER    | L   | 0.851      | -            | -                | -                | -         |   -11.96 | Lake, micro, Seb, Tender, wiz |
|           15 |     1457 | 2024-06-05 | LAG              | L   | 0.799      | -            | -                | -                | -         |   -10.49 | Lake, micro, Seb, Tender, wiz |
|           14 |     1499 | 2024-06-04 | LAG              | L   | 0.794      | -            | -                | -                | -         |   -11.17 | Lake, micro, Seb, Tender, wiz |
|           13 |     1813 | 2024-05-22 | MIGHT            | W   | 0.707      | 0.477        | 0.000 (0.000)    | 0.059 (0.020)    | 0 (0.000) |     4.08 | Lake, micro, Seb, Tender, wiz |
|           12 |     1818 | 2024-05-22 | MIGHT            | W   | 0.707      | 0.477        | 0.000 (0.000)    | 0.059 (0.020)    | 0 (0.000) |     4.23 | Lake, micro, Seb, Tender, wiz |
|           11 |     1866 | 2024-05-21 | Legacy           | L   | 0.699      | -            | -                | -                | -         |    -4.70 | Lake, micro, Seb, Tender, wiz |
|           10 |     1868 | 2024-05-21 | Wildcard         | L   | 0.699      | -            | -                | -                | -         |    -7.21 | Lake, micro, Seb, Tender, wiz |
|            9 |     1872 | 2024-05-21 | Wildcard         | L   | 0.699      | -            | -                | -                | -         |    -7.61 | Lake, micro, Seb, Tender, wiz |
|            8 |     1897 | 2024-05-20 | BOSS             | W   | 0.693      | 0.477        | 0.014 (0.005)    | 0.332 (0.110)    | 0 (0.000) |    10.90 | Lake, micro, Seb, Tender, wiz |
|            7 |     1901 | 2024-05-20 | BOSS             | L   | 0.693      | -            | -                | -                | -         |   -11.14 | Lake, micro, Seb, Tender, wiz |
|            6 |     2024 | 2024-05-16 | Take Flyte       | W   | 0.667      | 0.477        | 0.002 (0.001)    | 0.240 (0.076)    | 0 (0.000) |     7.51 | Lake, micro, Seb, Tender, wiz |
|            5 |     2025 | 2024-05-16 | Take Flyte       | W   | 0.667      | 0.477        | 0.002 (0.001)    | 0.240 (0.076)    | 0 (0.000) |     7.94 | Lake, micro, Seb, Tender, wiz |
|            4 |     2062 | 2024-05-15 | Nouns            | W   | 0.660      | 0.477        | 0.057 (0.018)    | 0.561 (0.177)    | 0 (0.000) |    14.32 | Lake, micro, Seb, Tender, wiz |
|            3 |     2067 | 2024-05-15 | Nouns            | W   | 0.660      | 0.477        | 0.057 (0.018)    | 0.561 (0.177)    | 0 (0.000) |    15.03 | Lake, micro, Seb, Tender, wiz |
|            2 |     2118 | 2024-05-14 | LAG              | L   | 0.654      | -            | -                | -                | -         |    -8.57 | Lake, micro, Seb, Tender, wiz |
|            1 |     2124 | 2024-05-14 | LAG              | W   | 0.653      | 0.477        | 0.012 (0.004)    | 0.353 (0.110)    | 0 (0.000) |    12.31 | Lake, micro, Seb, Tender, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,652.78)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
