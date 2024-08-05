### Roster Details<br />
Team Name: Bounty Hunters<br />
Roster: bnc, KAISER, piriajr, reix, SHOOWTiME<br />
Global Rank: [86](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [22]( ../standings_americas.md)<br />
<br />
Final Rank Value:  918.6<br />
<br />
Final Rank Value (918.6) = Starting Rank Value (901.6) + Head To Head Adjustments (17.0)<br />

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
|           44 |       97 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -19.97 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           43 |      102 | 2024-08-01 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.45 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           42 |      119 | 2024-08-01 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -15.77 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           41 |      150 | 2024-07-31 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.55 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           40 |      200 | 2024-07-30 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.48 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           39 |      266 | 2024-07-28 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -16.27 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           38 |      272 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.60 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           37 |      355 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -22.17 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           36 |      362 | 2024-07-25 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.26 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           35 |      366 | 2024-07-25 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.32 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           34 |      467 | 2024-07-22 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.507 (0.188)    | 0 (0.000) |    10.77 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           33 |      528 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.08 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           32 |      543 | 2024-07-19 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.35 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           31 |      587 | 2024-07-18 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -23.21 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           30 |      665 | 2024-07-17 | Solid             | W   | 1.000      | 0.384        | 0.025 (0.010)    | 0.836 (0.321)    | 0 (0.000) |    10.24 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           29 |      784 | 2024-07-15 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.37 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           28 |      829 | 2024-07-12 | Legacy            | L   | 1.000      | -            | -                | -                | -         |   -12.13 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           27 |      844 | 2024-07-11 | Sharks            | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.566 (0.210)    | 0 (0.000) |    16.70 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           26 |      873 | 2024-07-10 | Solid             | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.836 (0.310)    | -         |    11.04 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           25 |      880 | 2024-07-09 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.68 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           24 |      910 | 2024-07-08 | BESTIA            | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.802 (0.297)    | -         |    19.16 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           23 |      932 | 2024-07-03 | inSanitY          | L   | 0.985      | -            | -                | -                | -         |   -11.52 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           22 |      933 | 2024-07-02 | Vikings KR        | W   | 0.978      | 0.333        | -                | 0.507 (0.165)    | -         |    10.68 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           21 |      935 | 2024-07-01 | inSanitY          | L   | 0.971      | -            | -                | -                | -         |   -11.88 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           20 |      947 | 2024-06-29 | Patins da Ferrari | W   | 0.958      | 0.333        | 0.012 (0.004)    | -                | -         |    10.47 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           19 |      952 | 2024-06-28 | Sharks            | W   | 0.951      | 0.278        | 0.030 (0.008)    | -                | -         |    18.54 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           18 |      957 | 2024-06-27 | W7M               | W   | 0.945      | -            | -                | -                | -         |     9.55 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           17 |      963 | 2024-06-26 | Vikings KR        | W   | 0.939      | -            | -                | -                | -         |    10.25 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           16 |     1162 | 2024-06-11 | KRÜ               | L   | 0.837      | -            | -                | -                | -         |   -14.59 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           15 |     1178 | 2024-06-10 | BESTIA            | L   | 0.831      | -            | -                | -                | -         |    -8.88 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           14 |     1210 | 2024-06-09 | inSanitY          | W   | 0.826      | 0.371        | 0.048 (0.015)    | -                | -         |    15.24 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           13 |     1216 | 2024-06-09 | inSanitY          | L   | 0.825      | -            | -                | -                | -         |   -10.76 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           12 |     1276 | 2024-06-08 | W7M               | W   | 0.819      | 0.450        | -                | 0.538 (0.198)    | -         |     8.60 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           11 |     1325 | 2024-06-07 | MIBR              | W   | 0.813      | 0.371        | 0.209 (0.063)    | 0.659 (0.198)    | -         |    24.32 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           10 |     1348 | 2024-06-07 | Fluxo             | L   | 0.811      | -            | -                | -                | -         |    -6.74 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            9 |     1381 | 2024-06-06 | Case              | W   | 0.807      | 0.371        | 0.029 (0.009)    | 0.806 (0.241)    | -         |    12.54 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            8 |     1421 | 2024-06-06 | Case              | W   | 0.804      | 0.450        | 0.029 (0.011)    | 0.806 (0.292)    | -         |    13.42 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            7 |     1565 | 2024-06-02 | Hawks             | W   | 0.778      | -            | -                | -                | -         |     3.39 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            6 |     1620 | 2024-05-31 | Intense           | L   | 0.766      | -            | -                | -                | -         |   -16.51 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            5 |     1684 | 2024-05-29 | FURIA Academy     | W   | 0.751      | -            | -                | -                | -         |     2.82 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            4 |     1723 | 2024-05-27 | inSanitY          | L   | 0.739      | -            | -                | -                | -         |   -10.14 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            3 |     2838 | 2024-04-16 | MIBR              | L   | 0.466      | -            | -                | -                | -         |    -0.69 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            2 |     3057 | 2024-04-08 | RED Canids        | L   | 0.411      | -            | -                | -                | -         |    -3.43 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            1 |     3101 | 2024-04-06 | MIBR              | L   | 0.399      | -            | -                | -                | -         |    -0.71 | bnc, KAISER, reix, SHOOWTiME, Tomate  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,106.63)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-03 |      0.985 | $3,000.00      | $2,955.00       |
| 2024-06-28 |      0.951 | $2,000.00      | $1,902.64       |
| 2024-06-10 |      0.833 | $1,500.00      | $1,248.99       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
