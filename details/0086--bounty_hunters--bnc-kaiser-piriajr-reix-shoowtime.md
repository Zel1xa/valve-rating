### Roster Details<br />
Team Name: Bounty Hunters<br />
Roster: bnc, KAISER, piriajr, reix, SHOOWTiME<br />
Global Rank: [86](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [22]( ../standings_americas.md)<br />
<br />
Final Rank Value:  918.7<br />
<br />
Final Rank Value (918.7) = Starting Rank Value (901.6) + Head To Head Adjustments (17.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.376[<sup>1</sup>](#table2)
- Bounty Collected: 0.363[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.6
- 400 + ( ( 0.245 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 901.6


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
|           44 |       93 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -19.98 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           43 |       98 | 2024-08-01 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.45 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           42 |      115 | 2024-08-01 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -15.77 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           41 |      146 | 2024-07-31 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.54 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           40 |      196 | 2024-07-30 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.47 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           39 |      262 | 2024-07-28 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -16.27 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           38 |      268 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.59 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           37 |      351 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.18 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           36 |      358 | 2024-07-25 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.26 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           35 |      362 | 2024-07-25 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.32 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           34 |      463 | 2024-07-22 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.506 (0.187)    | 0 (0.000) |    10.76 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           33 |      524 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.07 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           32 |      539 | 2024-07-19 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.35 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           31 |      583 | 2024-07-18 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -23.22 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           30 |      661 | 2024-07-17 | Solid             | W   | 1.000      | 0.384        | 0.025 (0.010)    | 0.836 (0.321)    | 0 (0.000) |    10.24 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           29 |      780 | 2024-07-15 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.37 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           28 |      825 | 2024-07-12 | Legacy            | L   | 1.000      | -            | -                | -                | -         |   -12.12 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           27 |      840 | 2024-07-11 | Sharks            | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.565 (0.209)    | 0 (0.000) |    16.70 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           26 |      869 | 2024-07-10 | Solid             | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.836 (0.310)    | -         |    11.04 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           25 |      876 | 2024-07-09 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.67 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           24 |      906 | 2024-07-08 | BESTIA            | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.801 (0.297)    | -         |    19.17 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           23 |      928 | 2024-07-03 | inSanitY          | L   | 0.987      | -            | -                | -                | -         |   -11.54 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           22 |      929 | 2024-07-02 | Vikings KR        | W   | 0.981      | 0.333        | -                | 0.506 (0.165)    | -         |    10.70 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           21 |      931 | 2024-07-01 | inSanitY          | L   | 0.974      | -            | -                | -                | -         |   -11.90 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           20 |      943 | 2024-06-29 | Patins da Ferrari | W   | 0.960      | 0.333        | 0.012 (0.004)    | -                | -         |    10.49 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           19 |      948 | 2024-06-28 | Sharks            | W   | 0.954      | 0.278        | 0.030 (0.008)    | -                | -         |    18.59 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           18 |      953 | 2024-06-27 | W7M               | W   | 0.948      | -            | -                | -                | -         |     9.56 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           17 |      959 | 2024-06-26 | Vikings KR        | W   | 0.941      | -            | -                | -                | -         |    10.27 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           16 |     1158 | 2024-06-11 | KRÜ               | L   | 0.839      | -            | -                | -                | -         |   -14.64 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           15 |     1174 | 2024-06-10 | BESTIA            | L   | 0.834      | -            | -                | -                | -         |    -8.90 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           14 |     1206 | 2024-06-09 | inSanitY          | W   | 0.828      | 0.371        | 0.048 (0.015)    | -                | -         |    15.29 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           13 |     1212 | 2024-06-09 | inSanitY          | L   | 0.827      | -            | -                | -                | -         |   -10.78 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           12 |     1272 | 2024-06-08 | W7M               | W   | 0.821      | 0.450        | -                | 0.537 (0.199)    | -         |     8.62 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           11 |     1321 | 2024-06-07 | MIBR              | W   | 0.815      | 0.371        | 0.209 (0.063)    | 0.659 (0.199)    | -         |    24.40 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           10 |     1344 | 2024-06-07 | Fluxo             | L   | 0.813      | -            | -                | -                | -         |    -6.75 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            9 |     1377 | 2024-06-06 | Case              | W   | 0.809      | 0.371        | 0.029 (0.009)    | 0.805 (0.241)    | -         |    12.57 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            8 |     1417 | 2024-06-06 | Case              | W   | 0.806      | 0.450        | 0.029 (0.011)    | 0.805 (0.292)    | -         |    13.46 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            7 |     1561 | 2024-06-02 | Hawks             | W   | 0.780      | -            | -                | -                | -         |     3.41 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            6 |     1616 | 2024-05-31 | Intense           | L   | 0.769      | -            | -                | -                | -         |   -16.56 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            5 |     1680 | 2024-05-29 | FURIA Academy     | W   | 0.754      | -            | -                | -                | -         |     2.83 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            4 |     1719 | 2024-05-27 | inSanitY          | L   | 0.741      | -            | -                | -                | -         |   -10.16 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            3 |     2834 | 2024-04-16 | MIBR              | L   | 0.469      | -            | -                | -                | -         |    -0.69 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            2 |     3053 | 2024-04-08 | RED Canids        | L   | 0.413      | -            | -                | -                | -         |    -3.44 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            1 |     3097 | 2024-04-06 | MIBR              | L   | 0.402      | -            | -                | -                | -         |    -0.71 | bnc, KAISER, reix, SHOOWTiME, Tomate  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,122.13)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-03 |      0.987 | $3,000.00      | $2,962.15       |
| 2024-06-28 |      0.954 | $2,000.00      | $1,907.41       |
| 2024-06-10 |      0.835 | $1,500.00      | $1,252.57       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
