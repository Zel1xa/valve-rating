### Roster Details<br />
Team Name: Bounty Hunters<br />
Roster: bnc, KAISER, piriajr, reix, SHOOWTiME<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [22]( ../standings_americas.md)<br />
<br />
Final Rank Value:  917.6<br />
<br />
Final Rank Value (917.6) = Starting Rank Value (900.6) + Head To Head Adjustments (17.0)<br />

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
|           44 |      118 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -19.95 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           43 |      123 | 2024-08-01 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           42 |      140 | 2024-08-01 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -15.76 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           41 |      171 | 2024-07-31 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.58 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           40 |      221 | 2024-07-30 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.49 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           39 |      287 | 2024-07-28 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -16.26 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           38 |      293 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.61 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           37 |      376 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.15 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           36 |      383 | 2024-07-25 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.27 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           35 |      387 | 2024-07-25 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.33 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           34 |      488 | 2024-07-22 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.500 (0.185)    | 0 (0.000) |    10.78 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           33 |      549 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.09 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           32 |      564 | 2024-07-19 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.37 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           31 |      608 | 2024-07-18 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -23.18 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           30 |      686 | 2024-07-17 | Solid             | W   | 1.000      | 0.384        | 0.025 (0.010)    | 0.825 (0.317)    | 0 (0.000) |    10.26 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           29 |      805 | 2024-07-15 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.39 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           28 |      850 | 2024-07-12 | Legacy            | L   | 1.000      | -            | -                | -                | -         |   -12.14 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           27 |      865 | 2024-07-11 | Sharks            | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.558 (0.207)    | 0 (0.000) |    16.70 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           26 |      894 | 2024-07-10 | Solid             | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.825 (0.306)    | -         |    11.06 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           25 |      901 | 2024-07-09 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.70 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           24 |      931 | 2024-07-08 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.792 (0.293)    | -         |    19.16 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           23 |      953 | 2024-07-03 | inSanitY          | L   | 0.981      | -            | -                | -                | -         |   -11.49 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           22 |      954 | 2024-07-02 | Vikings KR        | W   | 0.974      | 0.333        | -                | 0.500 (0.162)    | -         |    10.65 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           21 |      956 | 2024-07-01 | inSanitY          | L   | 0.967      | -            | -                | -                | -         |   -11.84 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           20 |      968 | 2024-06-29 | Patins da Ferrari | W   | 0.953      | 0.333        | 0.012 (0.004)    | -                | -         |    10.45 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           19 |      973 | 2024-06-28 | Sharks            | W   | 0.947      | 0.278        | 0.030 (0.008)    | -                | -         |    18.44 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           18 |      978 | 2024-06-27 | W7M               | W   | 0.941      | -            | -                | -                | -         |     9.52 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           17 |      984 | 2024-06-26 | Vikings KR        | W   | 0.934      | -            | -                | -                | -         |    10.22 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           16 |     1183 | 2024-06-11 | KRÜ               | L   | 0.833      | -            | -                | -                | -         |   -14.51 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           15 |     1199 | 2024-06-10 | BESTIA            | L   | 0.827      | -            | -                | -                | -         |    -8.84 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           14 |     1231 | 2024-06-09 | inSanitY          | W   | 0.821      | 0.371        | 0.048 (0.015)    | -                | -         |    15.14 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           13 |     1237 | 2024-06-09 | inSanitY          | L   | 0.820      | -            | -                | -                | -         |   -10.72 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           12 |     1297 | 2024-06-08 | W7M               | W   | 0.814      | 0.450        | -                | 0.531 (0.194)    | -         |     8.57 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           11 |     1346 | 2024-06-07 | MIBR              | W   | 0.808      | 0.371        | 0.208 (0.062)    | 0.649 (0.194)    | -         |    24.18 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           10 |     1369 | 2024-06-07 | Fluxo             | L   | 0.807      | -            | -                | -                | -         |    -6.72 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            9 |     1402 | 2024-06-06 | Case              | W   | 0.802      | 0.371        | 0.029 (0.009)    | 0.795 (0.236)    | -         |    12.48 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            8 |     1442 | 2024-06-06 | Case              | W   | 0.799      | 0.450        | 0.029 (0.011)    | 0.795 (0.286)    | -         |    13.35 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            7 |     1586 | 2024-06-02 | Hawks             | W   | 0.773      | -            | -                | -                | -         |     3.38 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            6 |     1641 | 2024-05-31 | Intense           | L   | 0.762      | -            | -                | -                | -         |   -16.39 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            5 |     1705 | 2024-05-29 | FURIA Academy     | W   | 0.747      | -            | -                | -                | -         |     2.82 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            4 |     1744 | 2024-05-27 | inSanitY          | L   | 0.734      | -            | -                | -                | -         |   -10.09 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            3 |     2859 | 2024-04-16 | MIBR              | L   | 0.462      | -            | -                | -                | -         |    -0.69 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            2 |     3078 | 2024-04-08 | RED Canids        | L   | 0.407      | -            | -                | -                | -         |    -3.40 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            1 |     3122 | 2024-04-06 | MIBR              | L   | 0.395      | -            | -                | -                | -         |    -0.70 | bnc, KAISER, reix, SHOOWTiME, Tomate  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,077.74)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-03 |      0.981 | $3,000.00      | $2,941.67       |
| 2024-06-28 |      0.947 | $2,000.00      | $1,893.75       |
| 2024-06-10 |      0.828 | $1,500.00      | $1,242.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
