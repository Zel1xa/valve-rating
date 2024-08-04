### Roster Details<br />
Team Name: Bounty Hunters<br />
Roster: bnc, KAISER, piriajr, reix, SHOOWTiME<br />
Global Rank: [84](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [21]( ../standings_americas.md)<br />
<br />
Final Rank Value:  918.8<br />
<br />
Final Rank Value (918.8) = Starting Rank Value (901.4) + Head To Head Adjustments (17.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.376[<sup>1</sup>](#table2)
- Bounty Collected: 0.363[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.4
- 400 + ( ( 0.245 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 901.4


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
|           44 |       60 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -19.99 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           43 |       65 | 2024-08-01 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.45 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           42 |       81 | 2024-08-01 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -15.76 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           41 |      111 | 2024-07-31 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.53 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           40 |      161 | 2024-07-30 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.47 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           39 |      227 | 2024-07-28 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -16.26 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           38 |      233 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.58 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           37 |      316 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.19 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           36 |      323 | 2024-07-25 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.26 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           35 |      327 | 2024-07-25 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.31 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           34 |      428 | 2024-07-22 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.504 (0.187)    | 0 (0.000) |    10.75 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           33 |      489 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.06 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           32 |      504 | 2024-07-19 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.34 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           31 |      548 | 2024-07-18 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -23.23 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           30 |      626 | 2024-07-17 | Solid             | W   | 1.000      | 0.384        | 0.025 (0.010)    | 0.835 (0.321)    | 0 (0.000) |    10.22 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           29 |      745 | 2024-07-15 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.37 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           28 |      789 | 2024-07-12 | Legacy            | L   | 1.000      | -            | -                | -                | -         |   -12.10 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           27 |      804 | 2024-07-11 | Sharks            | W   | 1.000      | 0.371        | 0.031 (0.011)    | 0.564 (0.209)    | 0 (0.000) |    16.70 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           26 |      833 | 2024-07-10 | Solid             | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.835 (0.309)    | -         |    11.02 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           25 |      840 | 2024-07-09 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.65 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           24 |      870 | 2024-07-08 | BESTIA            | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.799 (0.296)    | -         |    19.17 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           23 |      892 | 2024-07-03 | inSanitY          | L   | 0.992      | -            | -                | -                | -         |   -11.58 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           22 |      893 | 2024-07-02 | Vikings KR        | W   | 0.986      | 0.333        | -                | 0.504 (0.166)    | -         |    10.74 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           21 |      895 | 2024-07-01 | inSanitY          | L   | 0.979      | -            | -                | -                | -         |   -11.94 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           20 |      907 | 2024-06-29 | Patins da Ferrari | W   | 0.965      | 0.333        | 0.012 (0.004)    | -                | -         |    10.54 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           19 |      912 | 2024-06-28 | Sharks            | W   | 0.959      | 0.278        | 0.031 (0.008)    | -                | -         |    18.68 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           18 |      917 | 2024-06-27 | W7M               | W   | 0.953      | -            | -                | -                | -         |     9.59 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           17 |      923 | 2024-06-26 | Vikings KR        | W   | 0.946      | -            | -                | -                | -         |    10.31 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           16 |     1122 | 2024-06-11 | KRÜ               | L   | 0.844      | -            | -                | -                | -         |   -14.73 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           15 |     1138 | 2024-06-10 | BESTIA            | L   | 0.839      | -            | -                | -                | -         |    -8.95 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           14 |     1170 | 2024-06-09 | inSanitY          | W   | 0.833      | 0.371        | 0.049 (0.015)    | -                | -         |    15.39 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           13 |     1176 | 2024-06-09 | inSanitY          | L   | 0.832      | -            | -                | -                | -         |   -10.82 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           12 |     1236 | 2024-06-08 | W7M               | W   | 0.826      | 0.450        | -                | 0.536 (0.199)    | -         |     8.65 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           11 |     1285 | 2024-06-07 | MIBR              | W   | 0.820      | 0.371        | 0.210 (0.064)    | 0.659 (0.200)    | -         |    24.55 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           10 |     1308 | 2024-06-07 | Fluxo             | L   | 0.818      | -            | -                | -                | -         |    -6.77 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            9 |     1341 | 2024-06-06 | Case              | W   | 0.814      | 0.371        | 0.029 (0.009)    | 0.804 (0.242)    | -         |    12.64 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            8 |     1381 | 2024-06-06 | Case              | W   | 0.811      | 0.450        | 0.029 (0.011)    | 0.804 (0.293)    | -         |    13.54 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            7 |     1525 | 2024-06-02 | Hawks             | W   | 0.785      | -            | -                | -                | -         |     3.43 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            6 |     1580 | 2024-05-31 | Intense           | L   | 0.773      | -            | -                | -                | -         |   -16.67 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            5 |     1644 | 2024-05-29 | FURIA Academy     | W   | 0.759      | -            | -                | -                | -         |     2.85 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            4 |     1683 | 2024-05-27 | inSanitY          | L   | 0.746      | -            | -                | -                | -         |   -10.21 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            3 |     2797 | 2024-04-16 | MIBR              | L   | 0.473      | -            | -                | -                | -         |    -0.69 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            2 |     3016 | 2024-04-08 | RED Canids        | L   | 0.418      | -            | -                | -                | -         |    -3.47 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            1 |     3060 | 2024-04-06 | MIBR              | L   | 0.407      | -            | -                | -                | -         |    -0.71 | bnc, KAISER, reix, SHOOWTiME, Tomate  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,153.58)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-03 |      0.992 | $3,000.00      | $2,976.67       |
| 2024-06-28 |      0.959 | $2,000.00      | $1,917.08       |
| 2024-06-10 |      0.840 | $1,500.00      | $1,259.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
