### Roster Details<br />
Team Name: Limitless<br />
Roster: DJF, Seb, Tender, wiz, Wolffe<br />
Global Rank: [168](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
<br />
Final Rank Value:  668.9<br />
<br />
Final Rank Value (668.9) = Starting Rank Value (747.8) + Head To Head Adjustments (-79.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.077[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.8
- 400 + ( ( 0.170 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 747.8


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
|           28 |      133 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.04 | DJF, Seb, Tender, wiz, Wolffe |
|           27 |      139 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.05 | DJF, Seb, Tender, wiz, Wolffe |
|           26 |      379 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.57 | DJF, Seb, Tender, wiz, Wolffe |
|           25 |      382 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -10.33 | DJF, Seb, Tender, wiz, Wolffe |
|           24 |      412 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.24 | DJF, Seb, Tender, wiz, Wolffe |
|           23 |      414 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.50 | DJF, Seb, Tender, wiz, Wolffe |
|           22 |      645 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -10.35 | DJF, Seb, Tender, wiz, Wolffe |
|           21 |      648 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -11.20 | DJF, Seb, Tender, wiz, Wolffe |
|           20 |      703 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.12 | DJF, Seb, Tender, wiz, Wolffe |
|           19 |      709 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.47 | DJF, Seb, Tender, wiz, Wolffe |
|           18 |      753 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.51 | DJF, Seb, Tender, wiz, Wolffe |
|           17 |      756 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.02 | DJF, Seb, Tender, wiz, Wolffe |
|           16 |     1100 | 2024-06-13 | E-Xolos LAZER    | L   | 0.854      | -            | -                | -                | -         |   -12.03 | Lake, micro, Seb, Tender, wiz |
|           15 |     1453 | 2024-06-05 | LAG              | L   | 0.802      | -            | -                | -                | -         |   -10.52 | Lake, micro, Seb, Tender, wiz |
|           14 |     1495 | 2024-06-04 | LAG              | L   | 0.796      | -            | -                | -                | -         |   -11.21 | Lake, micro, Seb, Tender, wiz |
|           13 |     1809 | 2024-05-22 | MIGHT            | W   | 0.709      | 0.477        | 0.000 (0.000)    | 0.060 (0.020)    | 0 (0.000) |     4.08 | Lake, micro, Seb, Tender, wiz |
|           12 |     1814 | 2024-05-22 | MIGHT            | W   | 0.709      | 0.477        | 0.000 (0.000)    | 0.060 (0.020)    | 0 (0.000) |     4.24 | Lake, micro, Seb, Tender, wiz |
|           11 |     1862 | 2024-05-21 | Legacy           | L   | 0.702      | -            | -                | -                | -         |    -4.71 | Lake, micro, Seb, Tender, wiz |
|           10 |     1864 | 2024-05-21 | Wildcard         | L   | 0.702      | -            | -                | -                | -         |    -7.23 | Lake, micro, Seb, Tender, wiz |
|            9 |     1868 | 2024-05-21 | Wildcard         | L   | 0.701      | -            | -                | -                | -         |    -7.64 | Lake, micro, Seb, Tender, wiz |
|            8 |     1893 | 2024-05-20 | BOSS             | W   | 0.696      | 0.477        | 0.014 (0.005)    | 0.332 (0.110)    | 0 (0.000) |    10.94 | Lake, micro, Seb, Tender, wiz |
|            7 |     1897 | 2024-05-20 | BOSS             | L   | 0.695      | -            | -                | -                | -         |   -11.19 | Lake, micro, Seb, Tender, wiz |
|            6 |     2020 | 2024-05-16 | Take Flyte       | W   | 0.669      | 0.477        | 0.002 (0.001)    | 0.240 (0.077)    | 0 (0.000) |     7.53 | Lake, micro, Seb, Tender, wiz |
|            5 |     2021 | 2024-05-16 | Take Flyte       | W   | 0.669      | 0.477        | 0.002 (0.001)    | 0.240 (0.077)    | 0 (0.000) |     7.96 | Lake, micro, Seb, Tender, wiz |
|            4 |     2058 | 2024-05-15 | Nouns            | W   | 0.663      | 0.477        | 0.057 (0.018)    | 0.561 (0.177)    | 0 (0.000) |    14.37 | Lake, micro, Seb, Tender, wiz |
|            3 |     2063 | 2024-05-15 | Nouns            | W   | 0.662      | 0.477        | 0.057 (0.018)    | 0.561 (0.177)    | 0 (0.000) |    15.08 | Lake, micro, Seb, Tender, wiz |
|            2 |     2114 | 2024-05-14 | LAG              | L   | 0.656      | -            | -                | -                | -         |    -8.60 | Lake, micro, Seb, Tender, wiz |
|            1 |     2120 | 2024-05-14 | LAG              | W   | 0.656      | 0.477        | 0.012 (0.004)    | 0.353 (0.110)    | 0 (0.000) |    12.36 | Lake, micro, Seb, Tender, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,657.55)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
