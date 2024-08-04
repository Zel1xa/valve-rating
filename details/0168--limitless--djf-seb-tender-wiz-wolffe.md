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
|           28 |      132 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.04 | DJF, Seb, Tender, wiz, Wolffe |
|           27 |      138 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.05 | DJF, Seb, Tender, wiz, Wolffe |
|           26 |      378 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.57 | DJF, Seb, Tender, wiz, Wolffe |
|           25 |      381 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -10.33 | DJF, Seb, Tender, wiz, Wolffe |
|           24 |      411 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.24 | DJF, Seb, Tender, wiz, Wolffe |
|           23 |      413 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.50 | DJF, Seb, Tender, wiz, Wolffe |
|           22 |      644 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -10.35 | DJF, Seb, Tender, wiz, Wolffe |
|           21 |      647 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -11.20 | DJF, Seb, Tender, wiz, Wolffe |
|           20 |      702 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.12 | DJF, Seb, Tender, wiz, Wolffe |
|           19 |      708 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.47 | DJF, Seb, Tender, wiz, Wolffe |
|           18 |      752 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.51 | DJF, Seb, Tender, wiz, Wolffe |
|           17 |      755 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.02 | DJF, Seb, Tender, wiz, Wolffe |
|           16 |     1099 | 2024-06-13 | E-Xolos LAZER    | L   | 0.854      | -            | -                | -                | -         |   -12.03 | Lake, micro, Seb, Tender, wiz |
|           15 |     1452 | 2024-06-05 | LAG              | L   | 0.802      | -            | -                | -                | -         |   -10.53 | Lake, micro, Seb, Tender, wiz |
|           14 |     1494 | 2024-06-04 | LAG              | L   | 0.796      | -            | -                | -                | -         |   -11.21 | Lake, micro, Seb, Tender, wiz |
|           13 |     1808 | 2024-05-22 | MIGHT            | W   | 0.710      | 0.477        | 0.000 (0.000)    | 0.060 (0.020)    | 0 (0.000) |     4.09 | Lake, micro, Seb, Tender, wiz |
|           12 |     1813 | 2024-05-22 | MIGHT            | W   | 0.709      | 0.477        | 0.000 (0.000)    | 0.060 (0.020)    | 0 (0.000) |     4.24 | Lake, micro, Seb, Tender, wiz |
|           11 |     1861 | 2024-05-21 | Legacy           | L   | 0.702      | -            | -                | -                | -         |    -4.71 | Lake, micro, Seb, Tender, wiz |
|           10 |     1863 | 2024-05-21 | Wildcard         | L   | 0.702      | -            | -                | -                | -         |    -7.23 | Lake, micro, Seb, Tender, wiz |
|            9 |     1867 | 2024-05-21 | Wildcard         | L   | 0.702      | -            | -                | -                | -         |    -7.64 | Lake, micro, Seb, Tender, wiz |
|            8 |     1892 | 2024-05-20 | BOSS             | W   | 0.696      | 0.477        | 0.014 (0.005)    | 0.332 (0.110)    | 0 (0.000) |    10.94 | Lake, micro, Seb, Tender, wiz |
|            7 |     1896 | 2024-05-20 | BOSS             | L   | 0.696      | -            | -                | -                | -         |   -11.19 | Lake, micro, Seb, Tender, wiz |
|            6 |     2019 | 2024-05-16 | Take Flyte       | W   | 0.670      | 0.477        | 0.002 (0.001)    | 0.240 (0.077)    | 0 (0.000) |     7.53 | Lake, micro, Seb, Tender, wiz |
|            5 |     2020 | 2024-05-16 | Take Flyte       | W   | 0.669      | 0.477        | 0.002 (0.001)    | 0.240 (0.077)    | 0 (0.000) |     7.96 | Lake, micro, Seb, Tender, wiz |
|            4 |     2057 | 2024-05-15 | Nouns            | W   | 0.663      | 0.477        | 0.057 (0.018)    | 0.561 (0.177)    | 0 (0.000) |    14.38 | Lake, micro, Seb, Tender, wiz |
|            3 |     2062 | 2024-05-15 | Nouns            | W   | 0.663      | 0.477        | 0.057 (0.018)    | 0.561 (0.177)    | 0 (0.000) |    15.09 | Lake, micro, Seb, Tender, wiz |
|            2 |     2113 | 2024-05-14 | LAG              | L   | 0.656      | -            | -                | -                | -         |    -8.61 | Lake, micro, Seb, Tender, wiz |
|            1 |     2119 | 2024-05-14 | LAG              | W   | 0.656      | 0.477        | 0.012 (0.004)    | 0.353 (0.111)    | 0 (0.000) |    12.37 | Lake, micro, Seb, Tender, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,658.15)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
