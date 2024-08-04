### Roster Details<br />
Team Name: inSanitY<br />
Roster: cass1n, f4stzin, iDk, pesadelo, shz<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [19]( ../standings_americas.md)<br />
<br />
Final Rank Value:  969.6<br />
<br />
Final Rank Value (969.6) = Starting Rank Value (919.1) + Head To Head Adjustments (50.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.432[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.254<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 919.1
- 400 + ( ( 0.254 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 919.1


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
|           36 |       32 | 2024-08-02 | Case              | L   | 1.000      | -            | -                | -                | -         |   -19.29 | cass1n, f4stzin, iDk, pesadelo, shz |
|           35 |       65 | 2024-08-01 | SPORT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.39 | cass1n, f4stzin, iDk, pesadelo, shz |
|           34 |      160 | 2024-07-30 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.82 | cass1n, f4stzin, iDk, pesadelo, shz |
|           33 |      313 | 2024-07-25 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.20 | cass1n, f4stzin, iDk, pesadelo, shz |
|           32 |      389 | 2024-07-23 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -20.80 | cass1n, f4stzin, iDk, pesadelo, shz |
|           31 |      475 | 2024-07-20 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.50 | cass1n, f4stzin, iDk, pesadelo, shz |
|           30 |      580 | 2024-07-18 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -22.28 | cass1n, f4stzin, iDk, pesadelo, shz |
|           29 |      644 | 2024-07-17 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.70 | cass1n, f4stzin, iDk, pesadelo, shz |
|           28 |      680 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.02 | cass1n, f4stzin, iDk, pesadelo, shz |
|           27 |      685 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.36 | cass1n, f4stzin, iDk, pesadelo, shz |
|           26 |      729 | 2024-07-15 | Galorys           | W   | 1.000      | 0.450        | 0.030 (0.013)    | 0.552 (0.248)    | 0 (0.000) |     8.00 | cass1n, f4stzin, iDk, pesadelo, shz |
|           25 |      735 | 2024-07-15 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -24.05 | cass1n, f4stzin, iDk, pesadelo, shz |
|           24 |      752 | 2024-07-15 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.30 | cass1n, f4stzin, iDk, pesadelo, shz |
|           23 |      896 | 2024-07-03 | Bounty Hunters    | W   | 0.989      | 0.333        | -                | 0.557 (0.184)    | 0 (0.000) |    11.55 | cass1n, f4stzin, iDk, pesadelo, shz |
|           22 |      899 | 2024-07-01 | Bounty Hunters    | W   | 0.976      | 0.333        | -                | 0.557 (0.181)    | 0 (0.000) |    11.92 | cass1n, f4stzin, iDk, pesadelo, shz |
|           21 |      909 | 2024-06-29 | Galorys           | W   | 0.963      | 0.333        | 0.030 (0.010)    | -                | 0 (0.000) |     8.62 | cass1n, f4stzin, iDk, pesadelo, shz |
|           20 |      923 | 2024-06-27 | Sharks            | W   | 0.949      | 0.333        | 0.030 (0.010)    | -                | -         |    15.85 | cass1n, f4stzin, iDk, pesadelo, shz |
|           19 |      944 | 2024-06-19 | Case              | W   | 0.896      | 0.337        | 0.029 (0.009)    | 0.805 (0.243)    | -         |     9.02 | cass1n, f4stzin, iDk, pesadelo, shz |
|           18 |      945 | 2024-06-18 | Galorys           | W   | 0.890      | 0.337        | 0.030 (0.009)    | -                | -         |     9.18 | cass1n, f4stzin, iDk, pesadelo, shz |
|           17 |      948 | 2024-06-17 | Dusty Roots       | W   | 0.884      | -            | -                | -                | -         |     8.89 | cass1n, f4stzin, iDk, pesadelo, shz |
|           16 |      988 | 2024-06-15 | Fluxo             | L   | 0.869      | -            | -                | -                | -         |    -9.01 | cass1n, f4stzin, iDk, pesadelo, shz |
|           15 |     1032 | 2024-06-14 | Patins da Ferrari | W   | 0.862      | -            | -                | -                | -         |     8.32 | cass1n, f4stzin, iDk, pesadelo, shz |
|           14 |     1174 | 2024-06-09 | Bounty Hunters    | L   | 0.830      | -            | -                | -                | -         |   -15.33 | cass1n, f4stzin, iDk, pesadelo, shz |
|           13 |     1180 | 2024-06-09 | Bounty Hunters    | W   | 0.829      | 0.450        | 0.022 (0.008)    | 0.557 (0.208)    | -         |    10.80 | cass1n, f4stzin, iDk, pesadelo, shz |
|           12 |     1256 | 2024-06-08 | Solid             | W   | 0.822      | 0.450        | 0.025 (0.009)    | 0.835 (0.309)    | -         |    10.18 | cass1n, f4stzin, iDk, pesadelo, shz |
|           11 |     1291 | 2024-06-07 | Hype              | L   | 0.817      | -            | -                | -                | -         |   -15.50 | cass1n, f4stzin, iDk, pesadelo, shz |
|           10 |     1320 | 2024-06-07 | KRÜ               | W   | 0.815      | -            | -                | -                | -         |     9.38 | cass1n, f4stzin, iDk, pesadelo, shz |
|            9 |     1358 | 2024-06-06 | BESTIA            | W   | 0.809      | 0.450        | 0.095 (0.035)    | 0.801 (0.292)    | -         |    15.71 | cass1n, f4stzin, iDk, pesadelo, shz |
|            8 |     1549 | 2024-06-01 | Solid             | W   | 0.777      | 0.371        | -                | 0.835 (0.240)    | -         |    10.37 | cass1n, f4stzin, iDk, pesadelo, shz |
|            7 |     1626 | 2024-05-30 | Intense           | W   | 0.761      | -            | -                | -                | -         |     5.75 | cass1n, f4stzin, iDk, pesadelo, shz |
|            6 |     1687 | 2024-05-27 | Bounty Hunters    | W   | 0.743      | -            | -                | -                | -         |    10.18 | cass1n, f4stzin, iDk, pesadelo, shz |
|            5 |     2150 | 2024-05-12 | 9z                | L   | 0.644      | -            | -                | -                | -         |    -0.76 | cass1n, f4stzin, pesadelo, shz, vsm |
|            4 |     2209 | 2024-05-10 | 9z                | L   | 0.631      | -            | -                | -                | -         |    -0.70 | cass1n, f4stzin, iDk, pesadelo, shz |
|            3 |     2235 | 2024-05-09 | ODDIK             | W   | 0.622      | 0.435        | 0.098 (0.027)    | 0.831 (0.225)    | -         |    11.09 | cass1n, f4stzin, iDk, pesadelo, shz |
|            2 |     2274 | 2024-05-07 | Case              | W   | 0.609      | 0.435        | 0.029 (0.008)    | 0.805 (0.213)    | -         |     9.29 | cass1n, f4stzin, iDk, pesadelo, shz |
|            1 |     2307 | 2024-05-05 | Imperial          | L   | 0.595      | -            | -                | -                | -         |    -2.12 | cass1n, f4stzin, iDk, pesadelo, shz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,734.59)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-03 |      0.989 | $6,000.00      | $5,935.00       |
| 2024-06-19 |      0.896 | $5,350.00      | $4,794.19       |
| 2024-06-16 |      0.876 | $5,000.00      | $4,377.78       |
| 2024-06-10 |      0.837 | $750.00        | $627.62         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
