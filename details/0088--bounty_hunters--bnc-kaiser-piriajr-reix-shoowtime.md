### Roster Details<br />
Team Name: Bounty Hunters<br />
Roster: bnc, KAISER, piriajr, reix, SHOOWTiME<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [22]( ../standings_americas.md)<br />
<br />
Final Rank Value:  917.5<br />
<br />
Final Rank Value (917.5) = Starting Rank Value (900.6) + Head To Head Adjustments (16.9)<br />

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
|           44 |      121 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -19.94 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           43 |      126 | 2024-08-01 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           42 |      143 | 2024-08-01 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -15.76 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           41 |      174 | 2024-07-31 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.58 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           40 |      224 | 2024-07-30 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.50 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           39 |      290 | 2024-07-28 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -16.25 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           38 |      296 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.61 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           37 |      379 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.14 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           36 |      386 | 2024-07-25 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.27 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           35 |      390 | 2024-07-25 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.34 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           34 |      491 | 2024-07-22 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.500 (0.185)    | 0 (0.000) |    10.79 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           33 |      552 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.09 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           32 |      567 | 2024-07-19 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.37 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           31 |      611 | 2024-07-18 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -23.18 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           30 |      689 | 2024-07-17 | Solid             | W   | 1.000      | 0.384        | 0.025 (0.009)    | 0.825 (0.317)    | 0 (0.000) |    10.27 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           29 |      808 | 2024-07-15 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.39 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           28 |      853 | 2024-07-12 | Legacy            | L   | 1.000      | -            | -                | -                | -         |   -12.15 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           27 |      868 | 2024-07-11 | Sharks            | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.558 (0.207)    | 0 (0.000) |    16.69 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           26 |      897 | 2024-07-10 | Solid             | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.825 (0.306)    | -         |    11.07 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           25 |      904 | 2024-07-09 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.71 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           24 |      934 | 2024-07-08 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.792 (0.294)    | -         |    19.15 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           23 |      956 | 2024-07-03 | inSanitY          | L   | 0.978      | -            | -                | -                | -         |   -11.47 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           22 |      957 | 2024-07-02 | Vikings KR        | W   | 0.972      | 0.333        | -                | 0.500 (0.162)    | -         |    10.63 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           21 |      959 | 2024-07-01 | inSanitY          | L   | 0.965      | -            | -                | -                | -         |   -11.83 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           20 |      971 | 2024-06-29 | Patins da Ferrari | W   | 0.951      | 0.333        | 0.012 (0.004)    | -                | -         |    10.42 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           19 |      976 | 2024-06-28 | Sharks            | W   | 0.945      | 0.278        | 0.030 (0.008)    | -                | -         |    18.39 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           18 |      981 | 2024-06-27 | W7M               | W   | 0.939      | -            | -                | -                | -         |     9.51 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           17 |      987 | 2024-06-26 | Vikings KR        | W   | 0.932      | -            | -                | -                | -         |    10.20 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           16 |     1186 | 2024-06-11 | KRÜ               | L   | 0.830      | -            | -                | -                | -         |   -14.47 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           15 |     1202 | 2024-06-10 | BESTIA            | L   | 0.825      | -            | -                | -                | -         |    -8.82 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           14 |     1234 | 2024-06-09 | inSanitY          | W   | 0.819      | 0.371        | 0.048 (0.015)    | -                | -         |    15.10 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           13 |     1240 | 2024-06-09 | inSanitY          | L   | 0.818      | -            | -                | -                | -         |   -10.70 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           12 |     1300 | 2024-06-08 | W7M               | W   | 0.812      | 0.450        | -                | 0.531 (0.194)    | -         |     8.55 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           11 |     1349 | 2024-06-07 | MIBR              | W   | 0.806      | 0.371        | 0.208 (0.062)    | 0.648 (0.194)    | -         |    24.11 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           10 |     1372 | 2024-06-07 | Fluxo             | L   | 0.804      | -            | -                | -                | -         |    -6.71 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            9 |     1405 | 2024-06-06 | Case              | W   | 0.800      | 0.371        | 0.029 (0.009)    | 0.795 (0.236)    | -         |    12.45 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            8 |     1445 | 2024-06-06 | Case              | W   | 0.797      | 0.450        | 0.029 (0.010)    | 0.795 (0.285)    | -         |    13.31 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            7 |     1589 | 2024-06-02 | Hawks             | W   | 0.771      | -            | -                | -                | -         |     3.37 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            6 |     1644 | 2024-05-31 | Intense           | L   | 0.760      | -            | -                | -                | -         |   -16.34 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            5 |     1708 | 2024-05-29 | FURIA Academy     | W   | 0.745      | -            | -                | -                | -         |     2.81 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            4 |     1747 | 2024-05-27 | inSanitY          | L   | 0.732      | -            | -                | -                | -         |   -10.07 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            3 |     2862 | 2024-04-16 | MIBR              | L   | 0.460      | -            | -                | -                | -         |    -0.69 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            2 |     3081 | 2024-04-08 | RED Canids        | L   | 0.404      | -            | -                | -                | -         |    -3.39 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            1 |     3125 | 2024-04-06 | MIBR              | L   | 0.393      | -            | -                | -                | -         |    -0.70 | bnc, KAISER, reix, SHOOWTiME, Tomate  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,063.30)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-03 |      0.978 | $3,000.00      | $2,935.00       |
| 2024-06-28 |      0.945 | $2,000.00      | $1,889.31       |
| 2024-06-10 |      0.826 | $1,500.00      | $1,238.99       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
