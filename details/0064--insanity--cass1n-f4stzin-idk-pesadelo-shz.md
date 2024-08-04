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
|           36 |       61 | 2024-08-02 | Case              | L   | 1.000      | -            | -                | -                | -         |   -19.28 | cass1n, f4stzin, iDk, pesadelo, shz |
|           35 |       94 | 2024-08-01 | SPORT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.39 | cass1n, f4stzin, iDk, pesadelo, shz |
|           34 |      191 | 2024-07-30 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.81 | cass1n, f4stzin, iDk, pesadelo, shz |
|           33 |      344 | 2024-07-25 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.19 | cass1n, f4stzin, iDk, pesadelo, shz |
|           32 |      420 | 2024-07-23 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -20.79 | cass1n, f4stzin, iDk, pesadelo, shz |
|           31 |      506 | 2024-07-20 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.50 | cass1n, f4stzin, iDk, pesadelo, shz |
|           30 |      610 | 2024-07-18 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -22.27 | cass1n, f4stzin, iDk, pesadelo, shz |
|           29 |      675 | 2024-07-17 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.71 | cass1n, f4stzin, iDk, pesadelo, shz |
|           28 |      711 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.02 | cass1n, f4stzin, iDk, pesadelo, shz |
|           27 |      716 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.37 | cass1n, f4stzin, iDk, pesadelo, shz |
|           26 |      760 | 2024-07-15 | Galorys           | W   | 1.000      | 0.450        | 0.030 (0.013)    | 0.552 (0.248)    | 0 (0.000) |     8.01 | cass1n, f4stzin, iDk, pesadelo, shz |
|           25 |      766 | 2024-07-15 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -24.04 | cass1n, f4stzin, iDk, pesadelo, shz |
|           24 |      782 | 2024-07-15 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.30 | cass1n, f4stzin, iDk, pesadelo, shz |
|           23 |      927 | 2024-07-03 | Bounty Hunters    | W   | 0.988      | 0.333        | -                | 0.557 (0.183)    | 0 (0.000) |    11.54 | cass1n, f4stzin, iDk, pesadelo, shz |
|           22 |      930 | 2024-07-01 | Bounty Hunters    | W   | 0.974      | 0.333        | -                | 0.557 (0.181)    | 0 (0.000) |    11.90 | cass1n, f4stzin, iDk, pesadelo, shz |
|           21 |      940 | 2024-06-29 | Galorys           | W   | 0.961      | 0.333        | 0.030 (0.010)    | -                | 0 (0.000) |     8.62 | cass1n, f4stzin, iDk, pesadelo, shz |
|           20 |      954 | 2024-06-27 | Sharks            | W   | 0.947      | 0.333        | 0.030 (0.010)    | -                | -         |    15.83 | cass1n, f4stzin, iDk, pesadelo, shz |
|           19 |      975 | 2024-06-19 | Case              | W   | 0.895      | 0.337        | 0.029 (0.009)    | 0.805 (0.243)    | -         |     9.02 | cass1n, f4stzin, iDk, pesadelo, shz |
|           18 |      976 | 2024-06-18 | Galorys           | W   | 0.889      | 0.337        | 0.030 (0.009)    | -                | -         |     9.18 | cass1n, f4stzin, iDk, pesadelo, shz |
|           17 |      979 | 2024-06-17 | Dusty Roots       | W   | 0.882      | -            | -                | -                | -         |     8.88 | cass1n, f4stzin, iDk, pesadelo, shz |
|           16 |     1019 | 2024-06-15 | Fluxo             | L   | 0.868      | -            | -                | -                | -         |    -8.99 | cass1n, f4stzin, iDk, pesadelo, shz |
|           15 |     1063 | 2024-06-14 | Patins da Ferrari | W   | 0.860      | -            | -                | -                | -         |     8.31 | cass1n, f4stzin, iDk, pesadelo, shz |
|           14 |     1205 | 2024-06-09 | Bounty Hunters    | L   | 0.828      | -            | -                | -                | -         |   -15.29 | cass1n, f4stzin, iDk, pesadelo, shz |
|           13 |     1211 | 2024-06-09 | Bounty Hunters    | W   | 0.827      | 0.450        | 0.022 (0.008)    | 0.557 (0.207)    | -         |    10.78 | cass1n, f4stzin, iDk, pesadelo, shz |
|           12 |     1287 | 2024-06-08 | Solid             | W   | 0.820      | 0.450        | 0.025 (0.009)    | 0.836 (0.309)    | -         |    10.17 | cass1n, f4stzin, iDk, pesadelo, shz |
|           11 |     1322 | 2024-06-07 | Hype              | L   | 0.815      | -            | -                | -                | -         |   -15.47 | cass1n, f4stzin, iDk, pesadelo, shz |
|           10 |     1351 | 2024-06-07 | KRÜ               | W   | 0.813      | -            | -                | -                | -         |     9.38 | cass1n, f4stzin, iDk, pesadelo, shz |
|            9 |     1389 | 2024-06-06 | BESTIA            | W   | 0.808      | 0.450        | 0.095 (0.035)    | 0.801 (0.291)    | -         |    15.68 | cass1n, f4stzin, iDk, pesadelo, shz |
|            8 |     1580 | 2024-06-01 | Solid             | W   | 0.776      | 0.371        | -                | 0.836 (0.240)    | -         |    10.36 | cass1n, f4stzin, iDk, pesadelo, shz |
|            7 |     1657 | 2024-05-30 | Intense           | W   | 0.760      | -            | -                | -                | -         |     5.75 | cass1n, f4stzin, iDk, pesadelo, shz |
|            6 |     1718 | 2024-05-27 | Bounty Hunters    | W   | 0.741      | -            | -                | -                | -         |    10.16 | cass1n, f4stzin, iDk, pesadelo, shz |
|            5 |     2181 | 2024-05-12 | 9z                | L   | 0.642      | -            | -                | -                | -         |    -0.76 | cass1n, f4stzin, pesadelo, shz, vsm |
|            4 |     2240 | 2024-05-10 | 9z                | L   | 0.629      | -            | -                | -                | -         |    -0.69 | cass1n, f4stzin, iDk, pesadelo, shz |
|            3 |     2266 | 2024-05-09 | ODDIK             | W   | 0.620      | 0.435        | 0.099 (0.027)    | 0.831 (0.224)    | -         |    11.07 | cass1n, f4stzin, iDk, pesadelo, shz |
|            2 |     2305 | 2024-05-07 | Case              | W   | 0.607      | 0.435        | 0.029 (0.008)    | 0.805 (0.212)    | -         |     9.27 | cass1n, f4stzin, iDk, pesadelo, shz |
|            1 |     2338 | 2024-05-05 | Imperial          | L   | 0.594      | -            | -                | -                | -         |    -2.12 | cass1n, f4stzin, iDk, pesadelo, shz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,709.26)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-03 |      0.988 | $6,000.00      | $5,926.11       |
| 2024-06-19 |      0.895 | $5,350.00      | $4,786.27       |
| 2024-06-16 |      0.874 | $5,000.00      | $4,370.37       |
| 2024-06-10 |      0.835 | $750.00        | $626.51         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
