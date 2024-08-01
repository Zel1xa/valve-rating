### Roster Details<br />
Team Name: Limitless<br />
Roster: DJF, Seb, Tender, wiz, Wolffe<br />
Global Rank: [162](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [44]( ../standings_americas.md)<br />
<br />
Final Rank Value:  688.5<br />
<br />
Final Rank Value (688.5) = Starting Rank Value (753.1) + Head To Head Adjustments (-64.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.080[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.1
- 400 + ( ( 0.171 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 753.1


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
|           28 |       12 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.06 | DJF, Seb, Tender, wiz, Wolffe |
|           27 |       18 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.07 | DJF, Seb, Tender, wiz, Wolffe |
|           26 |      259 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.14 | DJF, Seb, Tender, wiz, Wolffe |
|           25 |      263 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.84 | DJF, Seb, Tender, wiz, Wolffe |
|           24 |      292 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.32 | DJF, Seb, Tender, wiz, Wolffe |
|           23 |      294 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.59 | DJF, Seb, Tender, wiz, Wolffe |
|           22 |      534 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -6.06 | DJF, Seb, Tender, wiz, Wolffe |
|           21 |      537 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -6.41 | DJF, Seb, Tender, wiz, Wolffe |
|           20 |      592 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.01 | DJF, Seb, Tender, wiz, Wolffe |
|           19 |      598 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.35 | DJF, Seb, Tender, wiz, Wolffe |
|           18 |      647 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.33 | DJF, Seb, Tender, wiz, Wolffe |
|           17 |      651 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.82 | DJF, Seb, Tender, wiz, Wolffe |
|           16 |      986 | 2024-06-13 | E-Xolos LAZER    | L   | 0.875      | -            | -                | -                | -         |   -12.43 | Lake, micro, Seb, Tender, wiz |
|           15 |     1354 | 2024-06-05 | LAG              | L   | 0.823      | -            | -                | -                | -         |   -10.18 | Lake, micro, Seb, Tender, wiz |
|           14 |     1397 | 2024-06-04 | LAG              | L   | 0.817      | -            | -                | -                | -         |   -10.85 | Lake, micro, Seb, Tender, wiz |
|           13 |     1714 | 2024-05-22 | MIGHT            | W   | 0.731      | 0.477        | 0.000 (0.000)    | 0.061 (0.021)    | 0 (0.000) |     4.11 | Lake, micro, Seb, Tender, wiz |
|           12 |     1719 | 2024-05-22 | MIGHT            | W   | 0.730      | 0.477        | 0.000 (0.000)    | 0.061 (0.021)    | 0 (0.000) |     4.27 | Lake, micro, Seb, Tender, wiz |
|           11 |     1779 | 2024-05-21 | Legacy           | L   | 0.723      | -            | -                | -                | -         |    -4.84 | Lake, micro, Seb, Tender, wiz |
|           10 |     1781 | 2024-05-21 | Wildcard         | L   | 0.723      | -            | -                | -                | -         |    -6.58 | Lake, micro, Seb, Tender, wiz |
|            9 |     1785 | 2024-05-21 | Wildcard         | L   | 0.723      | -            | -                | -                | -         |    -6.94 | Lake, micro, Seb, Tender, wiz |
|            8 |     1814 | 2024-05-20 | BOSS             | W   | 0.717      | 0.477        | 0.014 (0.005)    | 0.334 (0.114)    | 0 (0.000) |    11.35 | Lake, micro, Seb, Tender, wiz |
|            7 |     1818 | 2024-05-20 | BOSS             | L   | 0.717      | -            | -                | -                | -         |   -11.44 | Lake, micro, Seb, Tender, wiz |
|            6 |     1951 | 2024-05-16 | Take Flyte       | W   | 0.691      | 0.477        | 0.002 (0.001)    | 0.241 (0.079)    | 0 (0.000) |     7.64 | Lake, micro, Seb, Tender, wiz |
|            5 |     1952 | 2024-05-16 | Take Flyte       | W   | 0.690      | 0.477        | 0.002 (0.001)    | 0.241 (0.079)    | 0 (0.000) |     8.09 | Lake, micro, Seb, Tender, wiz |
|            4 |     1989 | 2024-05-15 | Nouns            | W   | 0.684      | 0.477        | 0.058 (0.019)    | 0.557 (0.182)    | 0 (0.000) |    14.88 | Lake, micro, Seb, Tender, wiz |
|            3 |     1994 | 2024-05-15 | Nouns            | W   | 0.684      | 0.477        | 0.058 (0.019)    | 0.557 (0.181)    | 0 (0.000) |    15.64 | Lake, micro, Seb, Tender, wiz |
|            2 |     2051 | 2024-05-14 | LAG              | L   | 0.677      | -            | -                | -                | -         |    -8.50 | Lake, micro, Seb, Tender, wiz |
|            1 |     2057 | 2024-05-14 | LAG              | W   | 0.677      | 0.477        | 0.013 (0.004)    | 0.371 (0.120)    | 0 (0.000) |    13.16 | Lake, micro, Seb, Tender, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,700.00)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
