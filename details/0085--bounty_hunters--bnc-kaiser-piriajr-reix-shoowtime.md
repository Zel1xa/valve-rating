### Roster Details<br />
Team Name: Bounty Hunters<br />
Roster: bnc, KAISER, piriajr, reix, SHOOWTiME<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [21]( ../standings_americas.md)<br />
<br />
Final Rank Value:  918.7<br />
<br />
Final Rank Value (918.7) = Starting Rank Value (901.5) + Head To Head Adjustments (17.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.376[<sup>1</sup>](#table2)
- Bounty Collected: 0.363[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.5
- 400 + ( ( 0.245 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 901.5


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
|           44 |       71 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -19.98 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           43 |       76 | 2024-08-01 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.45 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           42 |       92 | 2024-08-01 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -15.77 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           41 |      122 | 2024-07-31 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.54 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           40 |      172 | 2024-07-30 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.47 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           39 |      238 | 2024-07-28 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -16.27 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           38 |      244 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.59 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           37 |      327 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.18 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           36 |      334 | 2024-07-25 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.26 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           35 |      338 | 2024-07-25 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.31 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           34 |      439 | 2024-07-22 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.505 (0.187)    | 0 (0.000) |    10.76 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           33 |      500 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.07 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           32 |      515 | 2024-07-19 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.35 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           31 |      559 | 2024-07-18 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -23.22 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           30 |      637 | 2024-07-17 | Solid             | W   | 1.000      | 0.384        | 0.025 (0.010)    | 0.835 (0.321)    | 0 (0.000) |    10.23 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           29 |      756 | 2024-07-15 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.37 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           28 |      801 | 2024-07-12 | Legacy            | L   | 1.000      | -            | -                | -                | -         |   -12.12 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           27 |      816 | 2024-07-11 | Sharks            | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.565 (0.209)    | 0 (0.000) |    16.70 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           26 |      845 | 2024-07-10 | Solid             | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.835 (0.310)    | -         |    11.03 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           25 |      852 | 2024-07-09 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.66 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           24 |      882 | 2024-07-08 | BESTIA            | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.801 (0.297)    | -         |    19.17 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           23 |      904 | 2024-07-03 | inSanitY          | L   | 0.988      | -            | -                | -                | -         |   -11.55 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           22 |      905 | 2024-07-02 | Vikings KR        | W   | 0.982      | 0.333        | -                | 0.505 (0.165)    | -         |    10.71 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           21 |      907 | 2024-07-01 | inSanitY          | L   | 0.975      | -            | -                | -                | -         |   -11.91 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           20 |      919 | 2024-06-29 | Patins da Ferrari | W   | 0.961      | 0.333        | 0.012 (0.004)    | -                | -         |    10.50 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           19 |      924 | 2024-06-28 | Sharks            | W   | 0.955      | 0.278        | 0.030 (0.008)    | -                | -         |    18.61 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           18 |      929 | 2024-06-27 | W7M               | W   | 0.949      | -            | -                | -                | -         |     9.57 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           17 |      935 | 2024-06-26 | Vikings KR        | W   | 0.942      | -            | -                | -                | -         |    10.28 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           16 |     1134 | 2024-06-11 | KRÜ               | L   | 0.841      | -            | -                | -                | -         |   -14.66 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           15 |     1150 | 2024-06-10 | BESTIA            | L   | 0.835      | -            | -                | -                | -         |    -8.91 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           14 |     1182 | 2024-06-09 | inSanitY          | W   | 0.829      | 0.371        | 0.048 (0.015)    | -                | -         |    15.31 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           13 |     1188 | 2024-06-09 | inSanitY          | L   | 0.828      | -            | -                | -                | -         |   -10.79 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           12 |     1248 | 2024-06-08 | W7M               | W   | 0.822      | 0.450        | -                | 0.537 (0.199)    | -         |     8.62 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           11 |     1297 | 2024-06-07 | MIBR              | W   | 0.816      | 0.371        | 0.209 (0.063)    | 0.659 (0.199)    | -         |    24.43 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           10 |     1320 | 2024-06-07 | Fluxo             | L   | 0.815      | -            | -                | -                | -         |    -6.75 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            9 |     1353 | 2024-06-06 | Case              | W   | 0.810      | 0.371        | 0.029 (0.009)    | 0.805 (0.242)    | -         |    12.59 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            8 |     1393 | 2024-06-06 | Case              | W   | 0.807      | 0.450        | 0.029 (0.011)    | 0.805 (0.292)    | -         |    13.48 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            7 |     1537 | 2024-06-02 | Hawks             | W   | 0.781      | -            | -                | -                | -         |     3.41 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            6 |     1592 | 2024-05-31 | Intense           | L   | 0.770      | -            | -                | -                | -         |   -16.59 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            5 |     1656 | 2024-05-29 | FURIA Academy     | W   | 0.755      | -            | -                | -                | -         |     2.84 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            4 |     1695 | 2024-05-27 | inSanitY          | L   | 0.742      | -            | -                | -                | -         |   -10.17 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            3 |     2810 | 2024-04-16 | MIBR              | L   | 0.470      | -            | -                | -                | -         |    -0.69 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            2 |     3029 | 2024-04-08 | RED Canids        | L   | 0.415      | -            | -                | -                | -         |    -3.44 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            1 |     3073 | 2024-04-06 | MIBR              | L   | 0.403      | -            | -                | -                | -         |    -0.71 | bnc, KAISER, reix, SHOOWTiME, Tomate  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,129.05)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-03 |      0.988 | $3,000.00      | $2,965.35       |
| 2024-06-28 |      0.955 | $2,000.00      | $1,909.54       |
| 2024-06-10 |      0.836 | $1,500.00      | $1,254.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
