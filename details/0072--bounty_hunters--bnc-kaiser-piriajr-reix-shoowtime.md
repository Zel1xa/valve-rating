### Roster Details<br />
Team Name: Bounty Hunters<br />
Roster: bnc, KAISER, piriajr, reix, SHOOWTiME<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [20]( ../standings_americas.md)<br />
<br />
Final Rank Value:  951.0<br />
<br />
Final Rank Value (951.0) = Starting Rank Value (902.6) + Head To Head Adjustments (48.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.238[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 902.6
- 400 + ( ( 0.244 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 902.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |       31 | 2024-07-31 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.79 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           40 |       82 | 2024-07-30 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.66 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           39 |      148 | 2024-07-28 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -15.92 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           38 |      154 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.29 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           37 |      237 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -20.50 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           36 |      244 | 2024-07-25 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.29 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           35 |      248 | 2024-07-25 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.05 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           34 |      350 | 2024-07-22 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.459 (0.170)    | 0 (0.000) |    10.59 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           33 |      413 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.97 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           32 |      428 | 2024-07-19 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.41 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           31 |      476 | 2024-07-18 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -26.20 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           30 |      556 | 2024-07-17 | Solid             | W   | 1.000      | 0.384        | 0.027 (0.010)    | 0.844 (0.324)    | 0 (0.000) |    10.42 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           29 |      681 | 2024-07-15 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.37 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           28 |      728 | 2024-07-12 | Legacy            | L   | 1.000      | -            | -                | -                | -         |   -11.00 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           27 |      743 | 2024-07-11 | Sharks            | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.572 (0.212)    | 0 (0.000) |    16.61 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           26 |      772 | 2024-07-10 | Solid             | W   | 1.000      | 0.371        | 0.027 (0.010)    | 0.844 (0.313)    | 0 (0.000) |    11.40 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           25 |      779 | 2024-07-09 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |   -10.56 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           24 |      809 | 2024-07-08 | BESTIA            | W   | 1.000      | 0.371        | 0.089 (0.033)    | 0.738 (0.274)    | -         |    19.13 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           23 |      832 | 2024-07-03 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |   -12.05 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           22 |      833 | 2024-07-02 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |    11.07 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           21 |      835 | 2024-07-01 | inSanitY          | L   | 0.993      | -            | -                | -                | -         |   -12.54 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           20 |      847 | 2024-06-29 | Patins da Ferrari | W   | 0.979      | 0.333        | 0.012 (0.004)    | -                | -         |    10.71 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           19 |      852 | 2024-06-28 | Sharks            | W   | 0.973      | 0.278        | 0.029 (0.008)    | -                | -         |    18.62 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           18 |      857 | 2024-06-27 | W7M               | W   | 0.967      | 0.278        | -                | 0.626 (0.168)    | -         |    11.63 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           17 |      863 | 2024-06-26 | Vikings KR        | W   | 0.961      | -            | -                | -                | -         |    10.71 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           16 |     1051 | 2024-06-11 | KRÜ               | L   | 0.859      | -            | -                | -                | -         |   -13.75 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           15 |     1068 | 2024-06-10 | BESTIA            | L   | 0.853      | -            | -                | -                | -         |    -9.21 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           14 |     1100 | 2024-06-09 | inSanitY          | W   | 0.847      | 0.371        | 0.049 (0.015)    | -                | -         |    15.22 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           13 |     1106 | 2024-06-09 | inSanitY          | L   | 0.847      | -            | -                | -                | -         |   -11.47 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           12 |     1168 | 2024-06-08 | W7M               | W   | 0.841      | 0.450        | -                | 0.626 (0.237)    | -         |    10.76 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           11 |     1220 | 2024-06-07 | MIBR              | W   | 0.835      | 0.371        | 0.201 (0.062)    | 0.637 (0.197)    | -         |    24.53 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           10 |     1247 | 2024-06-07 | Fluxo             | L   | 0.833      | -            | -                | -                | -         |    -7.03 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            9 |     1281 | 2024-06-06 | Case              | W   | 0.828      | 0.371        | 0.030 (0.009)    | 0.722 (0.222)    | -         |    13.09 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            8 |     1322 | 2024-06-06 | Case              | W   | 0.826      | 0.450        | 0.030 (0.011)    | 0.722 (0.268)    | -         |    14.04 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            7 |     1470 | 2024-06-02 | Hawks             | W   | 0.800      | -            | -                | -                | -         |     3.57 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            6 |     1525 | 2024-05-31 | Intense           | L   | 0.788      | -            | -                | -                | -         |   -20.10 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            5 |     1589 | 2024-05-29 | FURIA Academy     | W   | 0.773      | -            | -                | -                | -         |     2.89 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            4 |     1628 | 2024-05-27 | inSanitY          | L   | 0.761      | -            | -                | -                | -         |   -11.02 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            3 |     2794 | 2024-04-16 | MIBR              | L   | 0.488      | -            | -                | -                | -         |    -0.74 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            2 |     3015 | 2024-04-08 | RED Canids        | L   | 0.433      | -            | -                | -                | -         |    -4.26 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            1 |     3059 | 2024-04-06 | MIBR              | L   | 0.421      | -            | -                | -                | -         |    -0.77 | bnc, KAISER, reix, SHOOWTiME, Tomate  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,228.44)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-03 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-28 |      0.973 | $2,000.00      | $1,946.53       |
| 2024-06-10 |      0.855 | $1,500.00      | $1,281.91       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
