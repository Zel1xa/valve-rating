### Roster Details<br />
Team Name: inSanitY<br />
Roster: cass1n, f4stzin, iDk, pesadelo, shz<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [18]( ../standings_americas.md)<br />
<br />
Final Rank Value:  986.0<br />
<br />
Final Rank Value (986.0) = Starting Rank Value (920.1) + Head To Head Adjustments (65.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.432[<sup>1</sup>](#table2)
- Bounty Collected: 0.351[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 920.1
- 400 + ( ( 0.252 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 920.1


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
|           34 |       43 | 2024-07-30 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.87 | cass1n, f4stzin, iDk, pesadelo, shz |
|           33 |      196 | 2024-07-25 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.28 | cass1n, f4stzin, iDk, pesadelo, shz |
|           32 |      272 | 2024-07-23 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -20.99 | cass1n, f4stzin, iDk, pesadelo, shz |
|           31 |      358 | 2024-07-20 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.45 | cass1n, f4stzin, iDk, pesadelo, shz |
|           30 |      462 | 2024-07-18 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -22.44 | cass1n, f4stzin, iDk, pesadelo, shz |
|           29 |      527 | 2024-07-17 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.53 | cass1n, f4stzin, iDk, pesadelo, shz |
|           28 |      563 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.82 | cass1n, f4stzin, iDk, pesadelo, shz |
|           27 |      568 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.15 | cass1n, f4stzin, iDk, pesadelo, shz |
|           26 |      612 | 2024-07-15 | Galorys           | W   | 1.000      | 0.450        | 0.030 (0.014)    | 0.553 (0.249)    | 0 (0.000) |     7.75 | cass1n, f4stzin, iDk, pesadelo, shz |
|           25 |      618 | 2024-07-15 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -24.30 | cass1n, f4stzin, iDk, pesadelo, shz |
|           24 |      634 | 2024-07-15 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.28 | cass1n, f4stzin, iDk, pesadelo, shz |
|           23 |      779 | 2024-07-03 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.58 | cass1n, f4stzin, iDk, pesadelo, shz |
|           22 |      782 | 2024-07-01 | Bounty Hunters    | W   | 0.999      | -            | -                | -                | 0 (0.000) |    12.10 | cass1n, f4stzin, iDk, pesadelo, shz |
|           21 |      792 | 2024-06-29 | Galorys           | W   | 0.986      | 0.333        | 0.030 (0.010)    | 0.553 (0.182)    | 0 (0.000) |     8.64 | cass1n, f4stzin, iDk, pesadelo, shz |
|           20 |      806 | 2024-06-27 | Sharks            | W   | 0.972      | 0.333        | 0.031 (0.010)    | 0.558 (0.181)    | 0 (0.000) |    16.28 | cass1n, f4stzin, iDk, pesadelo, shz |
|           19 |      827 | 2024-06-19 | Case              | W   | 0.920      | 0.337        | 0.030 (0.009)    | 0.720 (0.223)    | -         |     9.15 | cass1n, f4stzin, iDk, pesadelo, shz |
|           18 |      828 | 2024-06-18 | Galorys           | W   | 0.914      | 0.337        | 0.030 (0.009)    | -                | -         |     9.25 | cass1n, f4stzin, iDk, pesadelo, shz |
|           17 |      831 | 2024-06-17 | Dusty Roots       | W   | 0.908      | -            | -                | -                | -         |     8.84 | cass1n, f4stzin, iDk, pesadelo, shz |
|           16 |      871 | 2024-06-15 | Fluxo             | L   | 0.893      | -            | -                | -                | -         |    -9.20 | cass1n, f4stzin, iDk, pesadelo, shz |
|           15 |      915 | 2024-06-14 | Patins da Ferrari | W   | 0.886      | -            | -                | -                | -         |     8.56 | cass1n, f4stzin, iDk, pesadelo, shz |
|           14 |     1057 | 2024-06-09 | Bounty Hunters    | L   | 0.853      | -            | -                | -                | -         |   -15.84 | cass1n, f4stzin, iDk, pesadelo, shz |
|           13 |     1063 | 2024-06-09 | Bounty Hunters    | W   | 0.853      | 0.450        | 0.022 (0.008)    | 0.471 (0.181)    | -         |    11.00 | cass1n, f4stzin, iDk, pesadelo, shz |
|           12 |     1139 | 2024-06-08 | Solid             | W   | 0.846      | 0.450        | 0.027 (0.010)    | 0.817 (0.311)    | -         |    10.35 | cass1n, f4stzin, iDk, pesadelo, shz |
|           11 |     1174 | 2024-06-07 | Hype              | L   | 0.840      | -            | -                | -                | -         |   -16.06 | cass1n, f4stzin, iDk, pesadelo, shz |
|           10 |     1203 | 2024-06-07 | KRÜ               | W   | 0.838      | -            | -                | -                | -         |     9.31 | cass1n, f4stzin, iDk, pesadelo, shz |
|            9 |     1241 | 2024-06-06 | BESTIA            | W   | 0.833      | 0.450        | 0.095 (0.035)    | 0.731 (0.274)    | -         |    16.19 | cass1n, f4stzin, iDk, pesadelo, shz |
|            8 |     1432 | 2024-06-01 | Solid             | W   | 0.801      | 0.371        | -                | 0.817 (0.243)    | -         |    10.58 | cass1n, f4stzin, iDk, pesadelo, shz |
|            7 |     1509 | 2024-05-30 | Intense           | W   | 0.785      | -            | -                | -                | -         |     5.85 | cass1n, f4stzin, iDk, pesadelo, shz |
|            6 |     1570 | 2024-05-27 | Bounty Hunters    | W   | 0.767      | -            | -                | -                | -         |    10.38 | cass1n, f4stzin, iDk, pesadelo, shz |
|            5 |     2033 | 2024-05-12 | 9z                | L   | 0.668      | -            | -                | -                | -         |    -0.72 | cass1n, f4stzin, pesadelo, shz, vsm |
|            4 |     2092 | 2024-05-10 | 9z                | L   | 0.654      | -            | -                | -                | -         |    -0.66 | cass1n, f4stzin, iDk, pesadelo, shz |
|            3 |     2118 | 2024-05-09 | ODDIK             | W   | 0.646      | 0.435        | 0.097 (0.027)    | 0.781 (0.219)    | -         |    11.48 | cass1n, f4stzin, iDk, pesadelo, shz |
|            2 |     2157 | 2024-05-07 | Case              | W   | 0.632      | 0.435        | 0.030 (0.008)    | 0.720 (0.198)    | -         |     9.68 | cass1n, f4stzin, iDk, pesadelo, shz |
|            1 |     2190 | 2024-05-05 | Imperial          | L   | 0.619      | -            | -                | -                | -         |    -1.98 | cass1n, f4stzin, iDk, pesadelo, shz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($16,063.58)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-03 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-06-19 |      0.920 | $5,350.00      | $4,921.43       |
| 2024-06-16 |      0.899 | $5,000.00      | $4,496.69       |
| 2024-06-10 |      0.861 | $750.00        | $645.46         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
