### Roster Details<br />
Team Name: Bounty Hunters<br />
Roster: bnc, KAISER, piriajr, reix, SHOOWTiME<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [22]( ../standings_americas.md)<br />
<br />
Final Rank Value:  917.4<br />
<br />
Final Rank Value (917.4) = Starting Rank Value (900.6) + Head To Head Adjustments (16.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.376[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.238[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 900.6
- 400 + ( ( 0.244 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 900.6


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
|           44 |      125 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -19.93 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           43 |      130 | 2024-08-01 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.47 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           42 |      147 | 2024-08-01 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -15.76 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           41 |      178 | 2024-07-31 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.59 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           40 |      228 | 2024-07-30 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.50 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           39 |      294 | 2024-07-28 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -16.25 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           38 |      300 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.61 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           37 |      383 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.14 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           36 |      390 | 2024-07-25 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.27 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           35 |      394 | 2024-07-25 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.34 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           34 |      495 | 2024-07-22 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.501 (0.186)    | 0 (0.000) |    10.79 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           33 |      556 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.10 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           32 |      571 | 2024-07-19 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.37 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           31 |      615 | 2024-07-18 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -23.17 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           30 |      693 | 2024-07-17 | Solid             | W   | 1.000      | 0.384        | 0.024 (0.009)    | 0.825 (0.317)    | 0 (0.000) |    10.28 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           29 |      812 | 2024-07-15 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.39 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           28 |      857 | 2024-07-12 | Legacy            | L   | 1.000      | -            | -                | -                | -         |   -12.17 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           27 |      872 | 2024-07-11 | Sharks            | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.558 (0.207)    | 0 (0.000) |    16.69 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           26 |      901 | 2024-07-10 | Solid             | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.825 (0.306)    | -         |    11.08 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           25 |      908 | 2024-07-09 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.72 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           24 |      938 | 2024-07-08 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.793 (0.294)    | -         |    19.15 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           23 |      960 | 2024-07-03 | inSanitY          | L   | 0.976      | -            | -                | -                | -         |   -11.45 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           22 |      961 | 2024-07-02 | Vikings KR        | W   | 0.969      | 0.333        | -                | 0.501 (0.162)    | -         |    10.61 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           21 |      963 | 2024-07-01 | inSanitY          | L   | 0.962      | -            | -                | -                | -         |   -11.80 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           20 |      975 | 2024-06-29 | Patins da Ferrari | W   | 0.948      | 0.333        | 0.012 (0.004)    | -                | -         |    10.40 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           19 |      980 | 2024-06-28 | Sharks            | W   | 0.942      | 0.278        | 0.030 (0.008)    | -                | -         |    18.33 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           18 |      985 | 2024-06-27 | W7M               | W   | 0.936      | -            | -                | -                | -         |     9.49 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           17 |      991 | 2024-06-26 | Vikings KR        | W   | 0.929      | -            | -                | -                | -         |    10.18 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           16 |     1190 | 2024-06-11 | KRÜ               | L   | 0.828      | -            | -                | -                | -         |   -14.42 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           15 |     1206 | 2024-06-10 | BESTIA            | L   | 0.822      | -            | -                | -                | -         |    -8.80 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           14 |     1238 | 2024-06-09 | inSanitY          | W   | 0.816      | 0.371        | 0.048 (0.015)    | -                | -         |    15.05 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           13 |     1244 | 2024-06-09 | inSanitY          | L   | 0.815      | -            | -                | -                | -         |   -10.67 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           12 |     1304 | 2024-06-08 | W7M               | W   | 0.809      | 0.450        | -                | 0.531 (0.193)    | -         |     8.53 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           11 |     1353 | 2024-06-07 | MIBR              | W   | 0.804      | 0.371        | 0.208 (0.062)    | 0.647 (0.193)    | -         |    24.03 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           10 |     1376 | 2024-06-07 | Fluxo             | L   | 0.802      | -            | -                | -                | -         |    -6.70 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            9 |     1409 | 2024-06-06 | Case              | W   | 0.797      | 0.371        | 0.029 (0.009)    | 0.795 (0.235)    | -         |    12.41 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            8 |     1449 | 2024-06-06 | Case              | W   | 0.794      | 0.450        | 0.029 (0.010)    | 0.795 (0.284)    | -         |    13.27 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            7 |     1593 | 2024-06-02 | Hawks             | W   | 0.769      | -            | -                | -                | -         |     3.36 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            6 |     1648 | 2024-05-31 | Intense           | L   | 0.757      | -            | -                | -                | -         |   -16.29 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            5 |     1712 | 2024-05-29 | FURIA Academy     | W   | 0.742      | -            | -                | -                | -         |     2.80 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            4 |     1751 | 2024-05-27 | inSanitY          | L   | 0.730      | -            | -                | -                | -         |   -10.04 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            3 |     2866 | 2024-04-16 | MIBR              | L   | 0.457      | -            | -                | -                | -         |    -0.69 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            2 |     3085 | 2024-04-08 | RED Canids        | L   | 0.402      | -            | -                | -                | -         |    -3.37 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            1 |     3129 | 2024-04-06 | MIBR              | L   | 0.390      | -            | -                | -                | -         |    -0.70 | bnc, KAISER, reix, SHOOWTiME, Tomate  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,047.05)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-03 |      0.976 | $3,000.00      | $2,927.50       |
| 2024-06-28 |      0.942 | $2,000.00      | $1,884.31       |
| 2024-06-10 |      0.823 | $1,500.00      | $1,235.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
