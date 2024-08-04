### Roster Details<br />
Team Name: Limitless<br />
Roster: DJF, Seb, Tender, wiz, Wolffe<br />
Global Rank: [161](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [44]( ../standings_americas.md)<br />
<br />
Final Rank Value:  679.6<br />
<br />
Final Rank Value (679.6) = Starting Rank Value (747.3) + Head To Head Adjustments (-67.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.076[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.3
- 400 + ( ( 0.170 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 747.3


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
|           28 |      109 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.09 | DJF, Seb, Tender, wiz, Wolffe |
|           27 |      115 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.10 | DJF, Seb, Tender, wiz, Wolffe |
|           26 |      355 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.35 | DJF, Seb, Tender, wiz, Wolffe |
|           25 |      358 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -10.08 | DJF, Seb, Tender, wiz, Wolffe |
|           24 |      388 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.51 | DJF, Seb, Tender, wiz, Wolffe |
|           23 |      390 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.81 | DJF, Seb, Tender, wiz, Wolffe |
|           22 |      621 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -6.12 | DJF, Seb, Tender, wiz, Wolffe |
|           21 |      624 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -6.48 | DJF, Seb, Tender, wiz, Wolffe |
|           20 |      679 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.10 | DJF, Seb, Tender, wiz, Wolffe |
|           19 |      685 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.45 | DJF, Seb, Tender, wiz, Wolffe |
|           18 |      729 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.49 | DJF, Seb, Tender, wiz, Wolffe |
|           17 |      732 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.00 | DJF, Seb, Tender, wiz, Wolffe |
|           16 |     1076 | 2024-06-13 | E-Xolos LAZER    | L   | 0.855      | -            | -                | -                | -         |   -12.13 | Lake, micro, Seb, Tender, wiz |
|           15 |     1429 | 2024-06-05 | LAG              | L   | 0.803      | -            | -                | -                | -         |   -10.30 | Lake, micro, Seb, Tender, wiz |
|           14 |     1471 | 2024-06-04 | LAG              | L   | 0.797      | -            | -                | -                | -         |   -10.97 | Lake, micro, Seb, Tender, wiz |
|           13 |     1785 | 2024-05-22 | MIGHT            | W   | 0.710      | 0.477        | 0.000 (0.000)    | 0.060 (0.020)    | 0 (0.000) |     4.07 | Lake, micro, Seb, Tender, wiz |
|           12 |     1790 | 2024-05-22 | MIGHT            | W   | 0.710      | 0.477        | 0.000 (0.000)    | 0.060 (0.020)    | 0 (0.000) |     4.22 | Lake, micro, Seb, Tender, wiz |
|           11 |     1838 | 2024-05-21 | Legacy           | L   | 0.703      | -            | -                | -                | -         |    -4.76 | Lake, micro, Seb, Tender, wiz |
|           10 |     1840 | 2024-05-21 | Wildcard         | L   | 0.703      | -            | -                | -                | -         |    -6.45 | Lake, micro, Seb, Tender, wiz |
|            9 |     1844 | 2024-05-21 | Wildcard         | L   | 0.702      | -            | -                | -                | -         |    -6.79 | Lake, micro, Seb, Tender, wiz |
|            8 |     1869 | 2024-05-20 | BOSS             | W   | 0.697      | 0.477        | 0.014 (0.005)    | 0.333 (0.110)    | 0 (0.000) |    10.97 | Lake, micro, Seb, Tender, wiz |
|            7 |     1873 | 2024-05-20 | BOSS             | L   | 0.697      | -            | -                | -                | -         |   -11.19 | Lake, micro, Seb, Tender, wiz |
|            6 |     1996 | 2024-05-16 | Take Flyte       | W   | 0.670      | 0.477        | 0.002 (0.001)    | 0.240 (0.077)    | 0 (0.000) |     7.50 | Lake, micro, Seb, Tender, wiz |
|            5 |     1997 | 2024-05-16 | Take Flyte       | W   | 0.670      | 0.477        | 0.002 (0.001)    | 0.240 (0.077)    | 0 (0.000) |     7.93 | Lake, micro, Seb, Tender, wiz |
|            4 |     2034 | 2024-05-15 | Nouns            | W   | 0.664      | 0.477        | 0.057 (0.018)    | 0.548 (0.173)    | 0 (0.000) |    14.43 | Lake, micro, Seb, Tender, wiz |
|            3 |     2039 | 2024-05-15 | Nouns            | W   | 0.663      | 0.477        | 0.057 (0.018)    | 0.548 (0.173)    | 0 (0.000) |    15.14 | Lake, micro, Seb, Tender, wiz |
|            2 |     2090 | 2024-05-14 | LAG              | L   | 0.657      | -            | -                | -                | -         |    -8.35 | Lake, micro, Seb, Tender, wiz |
|            1 |     2096 | 2024-05-14 | LAG              | W   | 0.657      | 0.477        | 0.012 (0.004)    | 0.340 (0.107)    | 0 (0.000) |    12.66 | Lake, micro, Seb, Tender, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,659.68)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
