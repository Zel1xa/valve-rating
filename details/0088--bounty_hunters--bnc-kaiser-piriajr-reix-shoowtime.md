### Roster Details<br />
Team Name: Bounty Hunters<br />
Roster: bnc, KAISER, piriajr, reix, SHOOWTiME<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [22]( ../standings_americas.md)<br />
<br />
Final Rank Value:  918.3<br />
<br />
Final Rank Value (918.3) = Starting Rank Value (901.5) + Head To Head Adjustments (16.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.376[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.241[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.5
- 400 + ( ( 0.245 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 901.5


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
|           44 |      110 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -19.96 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           43 |      115 | 2024-08-01 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.45 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           42 |      132 | 2024-08-01 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -15.77 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           41 |      163 | 2024-07-31 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.56 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           40 |      213 | 2024-07-30 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.49 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           39 |      279 | 2024-07-28 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -16.26 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           38 |      285 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.60 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           37 |      368 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.16 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           36 |      375 | 2024-07-25 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.26 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           35 |      379 | 2024-07-25 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.33 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           34 |      480 | 2024-07-22 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.506 (0.187)    | 0 (0.000) |    10.77 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           33 |      541 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.08 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           32 |      556 | 2024-07-19 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.35 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           31 |      600 | 2024-07-18 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -23.20 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           30 |      678 | 2024-07-17 | Solid             | W   | 1.000      | 0.384        | 0.025 (0.010)    | 0.835 (0.321)    | 0 (0.000) |    10.26 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           29 |      797 | 2024-07-15 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.38 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           28 |      842 | 2024-07-12 | Legacy            | L   | 1.000      | -            | -                | -                | -         |   -12.15 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           27 |      857 | 2024-07-11 | Sharks            | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.565 (0.209)    | 0 (0.000) |    16.70 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           26 |      886 | 2024-07-10 | Solid             | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.835 (0.309)    | -         |    11.05 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           25 |      893 | 2024-07-09 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.69 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           24 |      923 | 2024-07-08 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.801 (0.297)    | -         |    19.16 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           23 |      945 | 2024-07-03 | inSanitY          | L   | 0.982      | -            | -                | -                | -         |   -11.50 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           22 |      946 | 2024-07-02 | Vikings KR        | W   | 0.975      | 0.333        | -                | 0.506 (0.164)    | -         |    10.65 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           21 |      948 | 2024-07-01 | inSanitY          | L   | 0.968      | -            | -                | -                | -         |   -11.86 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           20 |      960 | 2024-06-29 | Patins da Ferrari | W   | 0.954      | 0.333        | 0.012 (0.004)    | -                | -         |    10.44 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           19 |      965 | 2024-06-28 | Sharks            | W   | 0.948      | 0.278        | 0.030 (0.008)    | -                | -         |    18.46 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           18 |      970 | 2024-06-27 | W7M               | W   | 0.942      | -            | -                | -                | -         |     9.52 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           17 |      976 | 2024-06-26 | Vikings KR        | W   | 0.935      | -            | -                | -                | -         |    10.22 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           16 |     1175 | 2024-06-11 | KRÜ               | L   | 0.834      | -            | -                | -                | -         |   -14.53 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           15 |     1191 | 2024-06-10 | BESTIA            | L   | 0.828      | -            | -                | -                | -         |    -8.85 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           14 |     1223 | 2024-06-09 | inSanitY          | W   | 0.822      | 0.371        | 0.048 (0.015)    | -                | -         |    15.17 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           13 |     1229 | 2024-06-09 | inSanitY          | L   | 0.821      | -            | -                | -                | -         |   -10.73 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           12 |     1289 | 2024-06-08 | W7M               | W   | 0.815      | 0.450        | -                | 0.537 (0.197)    | -         |     8.57 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           11 |     1338 | 2024-06-07 | MIBR              | W   | 0.810      | 0.371        | 0.208 (0.063)    | 0.657 (0.197)    | -         |    24.21 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           10 |     1361 | 2024-06-07 | Fluxo             | L   | 0.808      | -            | -                | -                | -         |    -6.72 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            9 |     1394 | 2024-06-06 | Case              | W   | 0.803      | 0.371        | 0.029 (0.009)    | 0.805 (0.239)    | -         |    12.49 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            8 |     1434 | 2024-06-06 | Case              | W   | 0.800      | 0.450        | 0.029 (0.011)    | 0.805 (0.290)    | -         |    13.37 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            7 |     1578 | 2024-06-02 | Hawks             | W   | 0.775      | -            | -                | -                | -         |     3.38 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            6 |     1633 | 2024-05-31 | Intense           | L   | 0.763      | -            | -                | -                | -         |   -16.43 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            5 |     1697 | 2024-05-29 | FURIA Academy     | W   | 0.748      | -            | -                | -                | -         |     2.81 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            4 |     1736 | 2024-05-27 | inSanitY          | L   | 0.735      | -            | -                | -                | -         |   -10.10 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            3 |     2851 | 2024-04-16 | MIBR              | L   | 0.463      | -            | -                | -                | -         |    -0.69 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            2 |     3070 | 2024-04-08 | RED Canids        | L   | 0.408      | -            | -                | -                | -         |    -3.41 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            1 |     3114 | 2024-04-06 | MIBR              | L   | 0.396      | -            | -                | -                | -         |    -0.70 | bnc, KAISER, reix, SHOOWTiME, Tomate  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,084.97)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-03 |      0.982 | $3,000.00      | $2,945.00       |
| 2024-06-28 |      0.948 | $2,000.00      | $1,895.97       |
| 2024-06-10 |      0.829 | $1,500.00      | $1,243.99       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
