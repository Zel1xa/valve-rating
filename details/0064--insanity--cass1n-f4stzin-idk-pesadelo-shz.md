### Roster Details<br />
Team Name: inSanitY<br />
Roster: cass1n, f4stzin, iDk, pesadelo, shz<br />
Global Rank: [64](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [17]( ../standings_americas.md)<br />
<br />
Final Rank Value:  969.5<br />
<br />
Final Rank Value (969.5) = Starting Rank Value (919.0) + Head To Head Adjustments (50.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.432[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.254<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 919.0
- 400 + ( ( 0.254 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 919.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |       62 | 2024-08-02 | Case              | L   | 1.000      | -            | -                | -                | -         |   -19.28 | cass1n, f4stzin, iDk, pesadelo, shz |
|           35 |       95 | 2024-08-01 | SPORT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.39 | cass1n, f4stzin, iDk, pesadelo, shz |
|           34 |      192 | 2024-07-30 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.81 | cass1n, f4stzin, iDk, pesadelo, shz |
|           33 |      345 | 2024-07-25 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.19 | cass1n, f4stzin, iDk, pesadelo, shz |
|           32 |      421 | 2024-07-23 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -20.79 | cass1n, f4stzin, iDk, pesadelo, shz |
|           31 |      507 | 2024-07-20 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.50 | cass1n, f4stzin, iDk, pesadelo, shz |
|           30 |      611 | 2024-07-18 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -22.27 | cass1n, f4stzin, iDk, pesadelo, shz |
|           29 |      676 | 2024-07-17 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.71 | cass1n, f4stzin, iDk, pesadelo, shz |
|           28 |      712 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.03 | cass1n, f4stzin, iDk, pesadelo, shz |
|           27 |      717 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.37 | cass1n, f4stzin, iDk, pesadelo, shz |
|           26 |      761 | 2024-07-15 | Galorys           | W   | 1.000      | 0.450        | 0.030 (0.013)    | 0.552 (0.248)    | 0 (0.000) |     8.02 | cass1n, f4stzin, iDk, pesadelo, shz |
|           25 |      767 | 2024-07-15 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -24.03 | cass1n, f4stzin, iDk, pesadelo, shz |
|           24 |      783 | 2024-07-15 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.30 | cass1n, f4stzin, iDk, pesadelo, shz |
|           23 |      928 | 2024-07-03 | Bounty Hunters    | W   | 0.987      | 0.333        | -                | 0.557 (0.183)    | 0 (0.000) |    11.54 | cass1n, f4stzin, iDk, pesadelo, shz |
|           22 |      931 | 2024-07-01 | Bounty Hunters    | W   | 0.974      | 0.333        | -                | 0.557 (0.181)    | 0 (0.000) |    11.90 | cass1n, f4stzin, iDk, pesadelo, shz |
|           21 |      941 | 2024-06-29 | Galorys           | W   | 0.961      | 0.333        | 0.030 (0.010)    | -                | 0 (0.000) |     8.61 | cass1n, f4stzin, iDk, pesadelo, shz |
|           20 |      955 | 2024-06-27 | Sharks            | W   | 0.947      | 0.333        | 0.030 (0.010)    | -                | -         |    15.82 | cass1n, f4stzin, iDk, pesadelo, shz |
|           19 |      976 | 2024-06-19 | Case              | W   | 0.894      | 0.337        | 0.029 (0.009)    | 0.805 (0.243)    | -         |     9.02 | cass1n, f4stzin, iDk, pesadelo, shz |
|           18 |      977 | 2024-06-18 | Galorys           | W   | 0.888      | 0.337        | 0.030 (0.009)    | -                | -         |     9.18 | cass1n, f4stzin, iDk, pesadelo, shz |
|           17 |      980 | 2024-06-17 | Dusty Roots       | W   | 0.882      | -            | -                | -                | -         |     8.88 | cass1n, f4stzin, iDk, pesadelo, shz |
|           16 |     1020 | 2024-06-15 | Fluxo             | L   | 0.868      | -            | -                | -                | -         |    -8.98 | cass1n, f4stzin, iDk, pesadelo, shz |
|           15 |     1064 | 2024-06-14 | Patins da Ferrari | W   | 0.860      | -            | -                | -                | -         |     8.31 | cass1n, f4stzin, iDk, pesadelo, shz |
|           14 |     1206 | 2024-06-09 | Bounty Hunters    | L   | 0.828      | -            | -                | -                | -         |   -15.29 | cass1n, f4stzin, iDk, pesadelo, shz |
|           13 |     1212 | 2024-06-09 | Bounty Hunters    | W   | 0.827      | 0.450        | 0.022 (0.008)    | 0.557 (0.207)    | -         |    10.78 | cass1n, f4stzin, iDk, pesadelo, shz |
|           12 |     1288 | 2024-06-08 | Solid             | W   | 0.820      | 0.450        | 0.025 (0.009)    | 0.836 (0.309)    | -         |    10.16 | cass1n, f4stzin, iDk, pesadelo, shz |
|           11 |     1323 | 2024-06-07 | Hype              | L   | 0.815      | -            | -                | -                | -         |   -15.46 | cass1n, f4stzin, iDk, pesadelo, shz |
|           10 |     1352 | 2024-06-07 | KRÜ               | W   | 0.813      | -            | -                | -                | -         |     9.38 | cass1n, f4stzin, iDk, pesadelo, shz |
|            9 |     1390 | 2024-06-06 | BESTIA            | W   | 0.808      | 0.450        | 0.095 (0.035)    | 0.801 (0.291)    | -         |    15.68 | cass1n, f4stzin, iDk, pesadelo, shz |
|            8 |     1581 | 2024-06-01 | Solid             | W   | 0.775      | 0.371        | -                | 0.836 (0.240)    | -         |    10.36 | cass1n, f4stzin, iDk, pesadelo, shz |
|            7 |     1658 | 2024-05-30 | Intense           | W   | 0.759      | -            | -                | -                | -         |     5.75 | cass1n, f4stzin, iDk, pesadelo, shz |
|            6 |     1719 | 2024-05-27 | Bounty Hunters    | W   | 0.741      | -            | -                | -                | -         |    10.16 | cass1n, f4stzin, iDk, pesadelo, shz |
|            5 |     2182 | 2024-05-12 | 9z                | L   | 0.642      | -            | -                | -                | -         |    -0.76 | cass1n, f4stzin, pesadelo, shz, vsm |
|            4 |     2241 | 2024-05-10 | 9z                | L   | 0.629      | -            | -                | -                | -         |    -0.69 | cass1n, f4stzin, iDk, pesadelo, shz |
|            3 |     2267 | 2024-05-09 | ODDIK             | W   | 0.620      | 0.435        | 0.099 (0.027)    | 0.832 (0.224)    | -         |    11.07 | cass1n, f4stzin, iDk, pesadelo, shz |
|            2 |     2306 | 2024-05-07 | Case              | W   | 0.607      | 0.435        | 0.029 (0.008)    | 0.805 (0.212)    | -         |     9.27 | cass1n, f4stzin, iDk, pesadelo, shz |
|            1 |     2339 | 2024-05-05 | Imperial          | L   | 0.593      | -            | -                | -                | -         |    -2.12 | cass1n, f4stzin, iDk, pesadelo, shz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,704.11)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-03 |      0.987 | $6,000.00      | $5,924.31       |
| 2024-06-19 |      0.894 | $5,350.00      | $4,784.66       |
| 2024-06-16 |      0.874 | $5,000.00      | $4,368.87       |
| 2024-06-10 |      0.835 | $750.00        | $626.28         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
