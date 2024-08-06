### Roster Details<br />
Team Name: Bounty Hunters<br />
Roster: bnc, KAISER, piriajr, reix, SHOOWTiME<br />
Global Rank: [89](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [22]( ../standings_americas.md)<br />
<br />
Final Rank Value:  916.1<br />
<br />
Final Rank Value (916.1) = Starting Rank Value (899.0) + Head To Head Adjustments (17.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.376[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.243<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 899.0
- 400 + ( ( 0.243 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 899.0


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
|           44 |      137 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -19.91 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           43 |      142 | 2024-08-01 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.48 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           42 |      159 | 2024-08-01 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -15.75 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           41 |      190 | 2024-07-31 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.61 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           40 |      240 | 2024-07-30 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.51 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           39 |      306 | 2024-07-28 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -16.24 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           38 |      312 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.62 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           37 |      395 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.13 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           36 |      402 | 2024-07-25 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.28 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           35 |      406 | 2024-07-25 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.35 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           34 |      507 | 2024-07-22 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.490 (0.182)    | 0 (0.000) |    10.80 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           33 |      568 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.10 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           32 |      583 | 2024-07-19 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.39 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           31 |      627 | 2024-07-18 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -23.14 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           30 |      705 | 2024-07-17 | Solid             | W   | 1.000      | 0.384        | 0.024 (0.009)    | 0.807 (0.310)    | 0 (0.000) |    10.28 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           29 |      824 | 2024-07-15 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.41 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           28 |      869 | 2024-07-12 | Legacy            | L   | 1.000      | -            | -                | -                | -         |   -12.15 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           27 |      884 | 2024-07-11 | Sharks            | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.546 (0.202)    | 0 (0.000) |    16.69 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           26 |      913 | 2024-07-10 | Solid             | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.807 (0.299)    | -         |    11.09 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           25 |      920 | 2024-07-09 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.72 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           24 |      950 | 2024-07-08 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.776 (0.287)    | -         |    19.15 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           23 |      972 | 2024-07-03 | inSanitY          | L   | 0.975      | -            | -                | -                | -         |   -11.44 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           22 |      973 | 2024-07-02 | Vikings KR        | W   | 0.968      | 0.333        | -                | 0.490 (0.158)    | -         |    10.61 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           21 |      975 | 2024-07-01 | inSanitY          | L   | 0.961      | -            | -                | -                | -         |   -11.79 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           20 |      987 | 2024-06-29 | Patins da Ferrari | W   | 0.947      | 0.333        | 0.012 (0.004)    | -                | -         |    10.42 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           19 |      992 | 2024-06-28 | Sharks            | W   | 0.941      | 0.278        | 0.030 (0.008)    | -                | -         |    18.30 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           18 |      997 | 2024-06-27 | W7M               | W   | 0.935      | -            | -                | -                | -         |     9.49 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           17 |     1003 | 2024-06-26 | Vikings KR        | W   | 0.928      | -            | -                | -                | -         |    10.18 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           16 |     1202 | 2024-06-11 | KRÜ               | L   | 0.827      | -            | -                | -                | -         |   -14.41 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           15 |     1218 | 2024-06-10 | BESTIA            | L   | 0.821      | -            | -                | -                | -         |    -8.79 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           14 |     1250 | 2024-06-09 | inSanitY          | W   | 0.815      | 0.371        | 0.048 (0.015)    | -                | -         |    15.02 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           13 |     1256 | 2024-06-09 | inSanitY          | L   | 0.814      | -            | -                | -                | -         |   -10.66 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           12 |     1316 | 2024-06-08 | W7M               | W   | 0.808      | 0.450        | -                | 0.519 (0.189)    | -         |     8.53 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           11 |     1365 | 2024-06-07 | MIBR              | W   | 0.802      | 0.371        | 0.208 (0.062)    | 0.633 (0.188)    | -         |    24.00 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           10 |     1388 | 2024-06-07 | Fluxo             | L   | 0.801      | -            | -                | -                | -         |    -6.70 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            9 |     1421 | 2024-06-06 | Case              | W   | 0.796      | 0.371        | 0.029 (0.009)    | 0.778 (0.230)    | -         |    12.40 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            8 |     1461 | 2024-06-06 | Case              | W   | 0.793      | 0.450        | 0.029 (0.010)    | 0.778 (0.278)    | -         |    13.26 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            7 |     1605 | 2024-06-02 | Hawks             | W   | 0.768      | -            | -                | -                | -         |     3.38 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            6 |     1660 | 2024-05-31 | Intense           | L   | 0.756      | -            | -                | -                | -         |   -16.23 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            5 |     1724 | 2024-05-29 | FURIA Academy     | W   | 0.741      | -            | -                | -                | -         |     2.82 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            4 |     1763 | 2024-05-27 | inSanitY          | L   | 0.728      | -            | -                | -                | -         |   -10.03 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            3 |     2878 | 2024-04-16 | MIBR              | L   | 0.456      | -            | -                | -                | -         |    -0.69 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            2 |     3097 | 2024-04-08 | RED Canids        | L   | 0.401      | -            | -                | -                | -         |    -3.36 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            1 |     3141 | 2024-04-06 | MIBR              | L   | 0.389      | -            | -                | -                | -         |    -0.70 | bnc, KAISER, reix, SHOOWTiME, Tomate  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,039.22)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-03 |      0.975 | $3,000.00      | $2,923.89       |
| 2024-06-28 |      0.941 | $2,000.00      | $1,881.90       |
| 2024-06-10 |      0.822 | $1,500.00      | $1,233.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />