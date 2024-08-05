### Roster Details<br />
Team Name: Limitless<br />
Roster: DJF, Seb, Tender, wiz, Wolffe<br />
Global Rank: [167](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  668.3<br />
<br />
Final Rank Value (668.3) = Starting Rank Value (747.4) + Head To Head Adjustments (-79.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.169<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.4
- 400 + ( ( 0.169 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 747.4


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
|           28 |      159 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.05 | DJF, Seb, Tender, wiz, Wolffe |
|           27 |      165 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.06 | DJF, Seb, Tender, wiz, Wolffe |
|           26 |      405 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.57 | DJF, Seb, Tender, wiz, Wolffe |
|           25 |      408 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -10.33 | DJF, Seb, Tender, wiz, Wolffe |
|           24 |      438 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.25 | DJF, Seb, Tender, wiz, Wolffe |
|           23 |      440 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.52 | DJF, Seb, Tender, wiz, Wolffe |
|           22 |      671 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -10.33 | DJF, Seb, Tender, wiz, Wolffe |
|           21 |      674 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -11.18 | DJF, Seb, Tender, wiz, Wolffe |
|           20 |      729 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.13 | DJF, Seb, Tender, wiz, Wolffe |
|           19 |      735 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.49 | DJF, Seb, Tender, wiz, Wolffe |
|           18 |      779 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.52 | DJF, Seb, Tender, wiz, Wolffe |
|           17 |      782 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.03 | DJF, Seb, Tender, wiz, Wolffe |
|           16 |     1126 | 2024-06-13 | E-Xolos LAZER    | L   | 0.846      | -            | -                | -                | -         |   -11.88 | Lake, micro, Seb, Tender, wiz |
|           15 |     1479 | 2024-06-05 | LAG              | L   | 0.794      | -            | -                | -                | -         |   -10.44 | Lake, micro, Seb, Tender, wiz |
|           14 |     1521 | 2024-06-04 | LAG              | L   | 0.789      | -            | -                | -                | -         |   -11.11 | Lake, micro, Seb, Tender, wiz |
|           13 |     1835 | 2024-05-22 | MIGHT            | W   | 0.702      | 0.477        | 0.000 (0.000)    | 0.058 (0.019)    | 0 (0.000) |     4.05 | Lake, micro, Seb, Tender, wiz |
|           12 |     1840 | 2024-05-22 | MIGHT            | W   | 0.702      | 0.477        | 0.000 (0.000)    | 0.058 (0.019)    | 0 (0.000) |     4.21 | Lake, micro, Seb, Tender, wiz |
|           11 |     1888 | 2024-05-21 | Legacy           | L   | 0.695      | -            | -                | -                | -         |    -4.69 | Lake, micro, Seb, Tender, wiz |
|           10 |     1890 | 2024-05-21 | Wildcard         | L   | 0.694      | -            | -                | -                | -         |    -7.17 | Lake, micro, Seb, Tender, wiz |
|            9 |     1894 | 2024-05-21 | Wildcard         | L   | 0.694      | -            | -                | -                | -         |    -7.58 | Lake, micro, Seb, Tender, wiz |
|            8 |     1919 | 2024-05-20 | BOSS             | W   | 0.688      | 0.477        | 0.014 (0.005)    | 0.327 (0.107)    | 0 (0.000) |    10.82 | Lake, micro, Seb, Tender, wiz |
|            7 |     1923 | 2024-05-20 | BOSS             | L   | 0.688      | -            | -                | -                | -         |   -11.07 | Lake, micro, Seb, Tender, wiz |
|            6 |     2046 | 2024-05-16 | Take Flyte       | W   | 0.662      | 0.477        | 0.002 (0.001)    | 0.236 (0.075)    | 0 (0.000) |     7.48 | Lake, micro, Seb, Tender, wiz |
|            5 |     2047 | 2024-05-16 | Take Flyte       | W   | 0.662      | 0.477        | 0.002 (0.001)    | 0.236 (0.075)    | 0 (0.000) |     7.89 | Lake, micro, Seb, Tender, wiz |
|            4 |     2084 | 2024-05-15 | Nouns            | W   | 0.655      | 0.477        | 0.057 (0.018)    | 0.553 (0.173)    | 0 (0.000) |    14.21 | Lake, micro, Seb, Tender, wiz |
|            3 |     2089 | 2024-05-15 | Nouns            | W   | 0.655      | 0.477        | 0.057 (0.018)    | 0.553 (0.173)    | 0 (0.000) |    14.91 | Lake, micro, Seb, Tender, wiz |
|            2 |     2140 | 2024-05-14 | LAG              | L   | 0.649      | -            | -                | -                | -         |    -8.52 | Lake, micro, Seb, Tender, wiz |
|            1 |     2146 | 2024-05-14 | LAG              | W   | 0.648      | 0.477        | 0.012 (0.004)    | 0.347 (0.107)    | 0 (0.000) |    12.21 | Lake, micro, Seb, Tender, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,643.06)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
