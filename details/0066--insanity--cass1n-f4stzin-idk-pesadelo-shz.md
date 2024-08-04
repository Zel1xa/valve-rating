### Roster Details<br />
Team Name: inSanitY<br />
Roster: cass1n, f4stzin, iDk, pesadelo, shz<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [19]( ../standings_americas.md)<br />
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
- 400 + ( ( 0.254 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 919.0


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
|           36 |       40 | 2024-08-02 | Case              | L   | 1.000      | -            | -                | -                | -         |   -19.28 | cass1n, f4stzin, iDk, pesadelo, shz |
|           35 |       73 | 2024-08-01 | SPORT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.39 | cass1n, f4stzin, iDk, pesadelo, shz |
|           34 |      168 | 2024-07-30 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.82 | cass1n, f4stzin, iDk, pesadelo, shz |
|           33 |      321 | 2024-07-25 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.20 | cass1n, f4stzin, iDk, pesadelo, shz |
|           32 |      397 | 2024-07-23 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -20.80 | cass1n, f4stzin, iDk, pesadelo, shz |
|           31 |      483 | 2024-07-20 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.50 | cass1n, f4stzin, iDk, pesadelo, shz |
|           30 |      588 | 2024-07-18 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -22.28 | cass1n, f4stzin, iDk, pesadelo, shz |
|           29 |      652 | 2024-07-17 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.71 | cass1n, f4stzin, iDk, pesadelo, shz |
|           28 |      688 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.02 | cass1n, f4stzin, iDk, pesadelo, shz |
|           27 |      693 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.36 | cass1n, f4stzin, iDk, pesadelo, shz |
|           26 |      737 | 2024-07-15 | Galorys           | W   | 1.000      | 0.450        | 0.030 (0.013)    | 0.552 (0.248)    | 0 (0.000) |     8.01 | cass1n, f4stzin, iDk, pesadelo, shz |
|           25 |      743 | 2024-07-15 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -24.04 | cass1n, f4stzin, iDk, pesadelo, shz |
|           24 |      760 | 2024-07-15 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.30 | cass1n, f4stzin, iDk, pesadelo, shz |
|           23 |      904 | 2024-07-03 | Bounty Hunters    | W   | 0.988      | 0.333        | -                | 0.557 (0.183)    | 0 (0.000) |    11.55 | cass1n, f4stzin, iDk, pesadelo, shz |
|           22 |      907 | 2024-07-01 | Bounty Hunters    | W   | 0.975      | 0.333        | -                | 0.557 (0.181)    | 0 (0.000) |    11.91 | cass1n, f4stzin, iDk, pesadelo, shz |
|           21 |      917 | 2024-06-29 | Galorys           | W   | 0.962      | 0.333        | 0.030 (0.010)    | -                | 0 (0.000) |     8.62 | cass1n, f4stzin, iDk, pesadelo, shz |
|           20 |      931 | 2024-06-27 | Sharks            | W   | 0.948      | 0.333        | 0.030 (0.010)    | -                | -         |    15.84 | cass1n, f4stzin, iDk, pesadelo, shz |
|           19 |      952 | 2024-06-19 | Case              | W   | 0.895      | 0.337        | 0.029 (0.009)    | 0.805 (0.243)    | -         |     9.02 | cass1n, f4stzin, iDk, pesadelo, shz |
|           18 |      953 | 2024-06-18 | Galorys           | W   | 0.889      | 0.337        | 0.030 (0.009)    | -                | -         |     9.18 | cass1n, f4stzin, iDk, pesadelo, shz |
|           17 |      956 | 2024-06-17 | Dusty Roots       | W   | 0.883      | -            | -                | -                | -         |     8.88 | cass1n, f4stzin, iDk, pesadelo, shz |
|           16 |      996 | 2024-06-15 | Fluxo             | L   | 0.869      | -            | -                | -                | -         |    -9.00 | cass1n, f4stzin, iDk, pesadelo, shz |
|           15 |     1040 | 2024-06-14 | Patins da Ferrari | W   | 0.861      | -            | -                | -                | -         |     8.32 | cass1n, f4stzin, iDk, pesadelo, shz |
|           14 |     1182 | 2024-06-09 | Bounty Hunters    | L   | 0.829      | -            | -                | -                | -         |   -15.31 | cass1n, f4stzin, iDk, pesadelo, shz |
|           13 |     1188 | 2024-06-09 | Bounty Hunters    | W   | 0.828      | 0.450        | 0.022 (0.008)    | 0.557 (0.208)    | -         |    10.79 | cass1n, f4stzin, iDk, pesadelo, shz |
|           12 |     1264 | 2024-06-08 | Solid             | W   | 0.821      | 0.450        | 0.025 (0.009)    | 0.835 (0.309)    | -         |    10.17 | cass1n, f4stzin, iDk, pesadelo, shz |
|           11 |     1299 | 2024-06-07 | Hype              | L   | 0.816      | -            | -                | -                | -         |   -15.49 | cass1n, f4stzin, iDk, pesadelo, shz |
|           10 |     1328 | 2024-06-07 | KRÜ               | W   | 0.814      | -            | -                | -                | -         |     9.38 | cass1n, f4stzin, iDk, pesadelo, shz |
|            9 |     1366 | 2024-06-06 | BESTIA            | W   | 0.809      | 0.450        | 0.095 (0.035)    | 0.801 (0.292)    | -         |    15.70 | cass1n, f4stzin, iDk, pesadelo, shz |
|            8 |     1557 | 2024-06-01 | Solid             | W   | 0.776      | 0.371        | -                | 0.835 (0.240)    | -         |    10.36 | cass1n, f4stzin, iDk, pesadelo, shz |
|            7 |     1634 | 2024-05-30 | Intense           | W   | 0.761      | -            | -                | -                | -         |     5.75 | cass1n, f4stzin, iDk, pesadelo, shz |
|            6 |     1695 | 2024-05-27 | Bounty Hunters    | W   | 0.742      | -            | -                | -                | -         |    10.17 | cass1n, f4stzin, iDk, pesadelo, shz |
|            5 |     2158 | 2024-05-12 | 9z                | L   | 0.643      | -            | -                | -                | -         |    -0.76 | cass1n, f4stzin, pesadelo, shz, vsm |
|            4 |     2217 | 2024-05-10 | 9z                | L   | 0.630      | -            | -                | -                | -         |    -0.70 | cass1n, f4stzin, iDk, pesadelo, shz |
|            3 |     2243 | 2024-05-09 | ODDIK             | W   | 0.621      | 0.435        | 0.098 (0.027)    | 0.831 (0.224)    | -         |    11.08 | cass1n, f4stzin, iDk, pesadelo, shz |
|            2 |     2282 | 2024-05-07 | Case              | W   | 0.608      | 0.435        | 0.029 (0.008)    | 0.805 (0.213)    | -         |     9.28 | cass1n, f4stzin, iDk, pesadelo, shz |
|            1 |     2315 | 2024-05-05 | Imperial          | L   | 0.595      | -            | -                | -                | -         |    -2.12 | cass1n, f4stzin, iDk, pesadelo, shz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,722.32)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-03 |      0.988 | $6,000.00      | $5,930.69       |
| 2024-06-19 |      0.895 | $5,350.00      | $4,790.36       |
| 2024-06-16 |      0.875 | $5,000.00      | $4,374.19       |
| 2024-06-10 |      0.836 | $750.00        | $627.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
