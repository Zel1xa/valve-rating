### Roster Details<br />
Team Name: Limitless<br />
Roster: DJF, Seb, Tender, wiz, Wolffe<br />
Global Rank: [162](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [44]( ../standings_americas.md)<br />
<br />
Final Rank Value:  687.9<br />
<br />
Final Rank Value (687.9) = Starting Rank Value (752.6) + Head To Head Adjustments (-64.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.080[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 752.6
- 400 + ( ( 0.171 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 752.6


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
|           28 |       19 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.05 | DJF, Seb, Tender, wiz, Wolffe |
|           27 |       25 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.07 | DJF, Seb, Tender, wiz, Wolffe |
|           26 |      265 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.14 | DJF, Seb, Tender, wiz, Wolffe |
|           25 |      269 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.84 | DJF, Seb, Tender, wiz, Wolffe |
|           24 |      298 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.32 | DJF, Seb, Tender, wiz, Wolffe |
|           23 |      300 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.59 | DJF, Seb, Tender, wiz, Wolffe |
|           22 |      540 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -6.06 | DJF, Seb, Tender, wiz, Wolffe |
|           21 |      543 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -6.41 | DJF, Seb, Tender, wiz, Wolffe |
|           20 |      598 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.01 | DJF, Seb, Tender, wiz, Wolffe |
|           19 |      604 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.36 | DJF, Seb, Tender, wiz, Wolffe |
|           18 |      653 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.33 | DJF, Seb, Tender, wiz, Wolffe |
|           17 |      657 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.82 | DJF, Seb, Tender, wiz, Wolffe |
|           16 |      992 | 2024-06-13 | E-Xolos LAZER    | L   | 0.873      | -            | -                | -                | -         |   -12.41 | Lake, micro, Seb, Tender, wiz |
|           15 |     1360 | 2024-06-05 | LAG              | L   | 0.821      | -            | -                | -                | -         |   -10.17 | Lake, micro, Seb, Tender, wiz |
|           14 |     1403 | 2024-06-04 | LAG              | L   | 0.816      | -            | -                | -                | -         |   -10.83 | Lake, micro, Seb, Tender, wiz |
|           13 |     1720 | 2024-05-22 | MIGHT            | W   | 0.729      | 0.477        | 0.000 (0.000)    | 0.061 (0.021)    | 0 (0.000) |     4.10 | Lake, micro, Seb, Tender, wiz |
|           12 |     1725 | 2024-05-22 | MIGHT            | W   | 0.729      | 0.477        | 0.000 (0.000)    | 0.061 (0.021)    | 0 (0.000) |     4.26 | Lake, micro, Seb, Tender, wiz |
|           11 |     1785 | 2024-05-21 | Legacy           | L   | 0.721      | -            | -                | -                | -         |    -4.83 | Lake, micro, Seb, Tender, wiz |
|           10 |     1787 | 2024-05-21 | Wildcard         | L   | 0.721      | -            | -                | -                | -         |    -6.57 | Lake, micro, Seb, Tender, wiz |
|            9 |     1791 | 2024-05-21 | Wildcard         | L   | 0.721      | -            | -                | -                | -         |    -6.93 | Lake, micro, Seb, Tender, wiz |
|            8 |     1820 | 2024-05-20 | BOSS             | W   | 0.715      | 0.477        | 0.014 (0.005)    | 0.334 (0.114)    | 0 (0.000) |    11.33 | Lake, micro, Seb, Tender, wiz |
|            7 |     1824 | 2024-05-20 | BOSS             | L   | 0.715      | -            | -                | -                | -         |   -11.40 | Lake, micro, Seb, Tender, wiz |
|            6 |     1957 | 2024-05-16 | Take Flyte       | W   | 0.689      | 0.477        | 0.002 (0.001)    | 0.241 (0.079)    | 0 (0.000) |     7.63 | Lake, micro, Seb, Tender, wiz |
|            5 |     1958 | 2024-05-16 | Take Flyte       | W   | 0.689      | 0.477        | 0.002 (0.001)    | 0.241 (0.079)    | 0 (0.000) |     8.07 | Lake, micro, Seb, Tender, wiz |
|            4 |     1995 | 2024-05-15 | Nouns            | W   | 0.682      | 0.477        | 0.058 (0.019)    | 0.557 (0.181)    | 0 (0.000) |    14.84 | Lake, micro, Seb, Tender, wiz |
|            3 |     2000 | 2024-05-15 | Nouns            | W   | 0.682      | 0.477        | 0.058 (0.019)    | 0.557 (0.181)    | 0 (0.000) |    15.60 | Lake, micro, Seb, Tender, wiz |
|            2 |     2057 | 2024-05-14 | LAG              | L   | 0.675      | -            | -                | -                | -         |    -8.48 | Lake, micro, Seb, Tender, wiz |
|            1 |     2063 | 2024-05-14 | LAG              | W   | 0.675      | 0.477        | 0.013 (0.004)    | 0.371 (0.119)    | 0 (0.000) |    13.12 | Lake, micro, Seb, Tender, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,696.67)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
