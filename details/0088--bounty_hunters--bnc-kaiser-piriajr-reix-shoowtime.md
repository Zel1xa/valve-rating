### Roster Details<br />
Team Name: Bounty Hunters<br />
Roster: bnc, KAISER, piriajr, reix, SHOOWTiME<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [22]( ../standings_americas.md)<br />
<br />
Final Rank Value:  916.2<br />
<br />
Final Rank Value (916.2) = Starting Rank Value (899.0) + Head To Head Adjustments (17.2)<br />

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
|           44 |      129 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -19.91 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           43 |      134 | 2024-08-01 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.48 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           42 |      151 | 2024-08-01 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -15.75 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           41 |      182 | 2024-07-31 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.61 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           40 |      232 | 2024-07-30 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.51 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           39 |      298 | 2024-07-28 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -16.24 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           38 |      304 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.62 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           37 |      387 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.13 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           36 |      394 | 2024-07-25 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.28 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           35 |      398 | 2024-07-25 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.35 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           34 |      499 | 2024-07-22 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.490 (0.182)    | 0 (0.000) |    10.80 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           33 |      560 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.10 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           32 |      575 | 2024-07-19 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.39 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           31 |      619 | 2024-07-18 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -23.15 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           30 |      697 | 2024-07-17 | Solid             | W   | 1.000      | 0.384        | 0.024 (0.009)    | 0.807 (0.310)    | 0 (0.000) |    10.28 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           29 |      816 | 2024-07-15 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.41 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           28 |      861 | 2024-07-12 | Legacy            | L   | 1.000      | -            | -                | -                | -         |   -12.15 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           27 |      876 | 2024-07-11 | Sharks            | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.546 (0.202)    | 0 (0.000) |    16.69 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           26 |      905 | 2024-07-10 | Solid             | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.807 (0.299)    | -         |    11.08 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           25 |      912 | 2024-07-09 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.71 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           24 |      942 | 2024-07-08 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.775 (0.287)    | -         |    19.15 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           23 |      964 | 2024-07-03 | inSanitY          | L   | 0.976      | -            | -                | -                | -         |   -11.45 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           22 |      965 | 2024-07-02 | Vikings KR        | W   | 0.969      | 0.333        | -                | 0.490 (0.158)    | -         |    10.62 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           21 |      967 | 2024-07-01 | inSanitY          | L   | 0.962      | -            | -                | -                | -         |   -11.80 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           20 |      979 | 2024-06-29 | Patins da Ferrari | W   | 0.948      | 0.333        | 0.012 (0.004)    | -                | -         |    10.43 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           19 |      984 | 2024-06-28 | Sharks            | W   | 0.942      | 0.278        | 0.030 (0.008)    | -                | -         |    18.32 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           18 |      989 | 2024-06-27 | W7M               | W   | 0.936      | -            | -                | -                | -         |     9.49 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           17 |      995 | 2024-06-26 | Vikings KR        | W   | 0.929      | -            | -                | -                | -         |    10.19 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           16 |     1194 | 2024-06-11 | KRÜ               | L   | 0.828      | -            | -                | -                | -         |   -14.42 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           15 |     1210 | 2024-06-10 | BESTIA            | L   | 0.822      | -            | -                | -                | -         |    -8.79 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           14 |     1242 | 2024-06-09 | inSanitY          | W   | 0.816      | 0.371        | 0.048 (0.015)    | -                | -         |    15.04 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           13 |     1248 | 2024-06-09 | inSanitY          | L   | 0.815      | -            | -                | -                | -         |   -10.67 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           12 |     1308 | 2024-06-08 | W7M               | W   | 0.809      | 0.450        | -                | 0.519 (0.189)    | -         |     8.54 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           11 |     1357 | 2024-06-07 | MIBR              | W   | 0.803      | 0.371        | 0.208 (0.062)    | 0.633 (0.188)    | -         |    24.02 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           10 |     1380 | 2024-06-07 | Fluxo             | L   | 0.802      | -            | -                | -                | -         |    -6.70 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            9 |     1413 | 2024-06-06 | Case              | W   | 0.797      | 0.371        | 0.029 (0.009)    | 0.778 (0.230)    | -         |    12.41 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            8 |     1453 | 2024-06-06 | Case              | W   | 0.794      | 0.450        | 0.029 (0.010)    | 0.778 (0.278)    | -         |    13.27 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            7 |     1597 | 2024-06-02 | Hawks             | W   | 0.768      | -            | -                | -                | -         |     3.38 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            6 |     1652 | 2024-05-31 | Intense           | L   | 0.757      | -            | -                | -                | -         |   -16.25 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            5 |     1716 | 2024-05-29 | FURIA Academy     | W   | 0.742      | -            | -                | -                | -         |     2.82 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            4 |     1755 | 2024-05-27 | inSanitY          | L   | 0.729      | -            | -                | -                | -         |   -10.03 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            3 |     2870 | 2024-04-16 | MIBR              | L   | 0.457      | -            | -                | -                | -         |    -0.69 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            2 |     3089 | 2024-04-08 | RED Canids        | L   | 0.402      | -            | -                | -                | -         |    -3.37 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            1 |     3133 | 2024-04-06 | MIBR              | L   | 0.390      | -            | -                | -                | -         |    -0.70 | bnc, KAISER, reix, SHOOWTiME, Tomate  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,045.24)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-03 |      0.976 | $3,000.00      | $2,926.67       |
| 2024-06-28 |      0.942 | $2,000.00      | $1,883.75       |
| 2024-06-10 |      0.823 | $1,500.00      | $1,234.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
