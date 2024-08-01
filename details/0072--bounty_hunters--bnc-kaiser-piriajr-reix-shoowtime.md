### Roster Details<br />
Team Name: Bounty Hunters<br />
Roster: bnc, KAISER, piriajr, reix, SHOOWTiME<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [20]( ../standings_americas.md)<br />
<br />
Final Rank Value:  951.7<br />
<br />
Final Rank Value (951.7) = Starting Rank Value (903.2) + Head To Head Adjustments (48.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.239[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 903.2
- 400 + ( ( 0.244 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 903.2


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
|           41 |       24 | 2024-07-31 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.78 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           40 |       75 | 2024-07-30 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.65 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           39 |      142 | 2024-07-28 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -15.92 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           38 |      148 | 2024-07-28 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.29 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           37 |      231 | 2024-07-25 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -20.51 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           36 |      238 | 2024-07-25 | SENSEI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.29 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           35 |      242 | 2024-07-25 | Vikings KR        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.05 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           34 |      344 | 2024-07-22 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.459 (0.170)    | 0 (0.000) |    10.59 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           33 |      407 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.96 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           32 |      422 | 2024-07-19 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.40 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           31 |      470 | 2024-07-18 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -26.21 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           30 |      550 | 2024-07-17 | Solid             | W   | 1.000      | 0.384        | 0.027 (0.010)    | 0.843 (0.324)    | 0 (0.000) |    10.42 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           29 |      675 | 2024-07-15 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.36 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           28 |      722 | 2024-07-12 | Legacy            | L   | 1.000      | -            | -                | -                | -         |   -11.00 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           27 |      737 | 2024-07-11 | Sharks            | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.572 (0.212)    | 0 (0.000) |    16.61 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           26 |      766 | 2024-07-10 | Solid             | W   | 1.000      | 0.371        | 0.027 (0.010)    | 0.843 (0.312)    | 0 (0.000) |    11.39 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           25 |      773 | 2024-07-09 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |   -10.56 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           24 |      803 | 2024-07-08 | BESTIA            | W   | 1.000      | 0.371        | 0.089 (0.033)    | 0.738 (0.273)    | -         |    19.13 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           23 |      826 | 2024-07-03 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |   -12.05 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           22 |      827 | 2024-07-02 | Vikings KR        | W   | 1.000      | -            | -                | -                | -         |    11.07 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           21 |      829 | 2024-07-01 | inSanitY          | L   | 0.995      | -            | -                | -                | -         |   -12.56 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           20 |      841 | 2024-06-29 | Patins da Ferrari | W   | 0.981      | 0.333        | 0.012 (0.004)    | -                | -         |    10.72 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           19 |      846 | 2024-06-28 | Sharks            | W   | 0.975      | 0.278        | 0.029 (0.008)    | -                | -         |    18.66 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           18 |      851 | 2024-06-27 | W7M               | W   | 0.969      | 0.278        | -                | 0.625 (0.168)    | -         |    11.64 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           17 |      857 | 2024-06-26 | Vikings KR        | W   | 0.962      | -            | -                | -                | -         |    10.72 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           16 |     1045 | 2024-06-11 | KRÜ               | L   | 0.861      | -            | -                | -                | -         |   -13.77 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           15 |     1062 | 2024-06-10 | BESTIA            | L   | 0.855      | -            | -                | -                | -         |    -9.22 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           14 |     1094 | 2024-06-09 | inSanitY          | W   | 0.849      | 0.371        | 0.049 (0.015)    | -                | -         |    15.26 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           13 |     1100 | 2024-06-09 | inSanitY          | L   | 0.848      | -            | -                | -                | -         |   -11.49 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           12 |     1162 | 2024-06-08 | W7M               | W   | 0.842      | 0.450        | -                | 0.625 (0.237)    | -         |    10.78 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           11 |     1214 | 2024-06-07 | MIBR              | W   | 0.836      | 0.371        | 0.201 (0.062)    | 0.637 (0.197)    | -         |    24.59 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|           10 |     1241 | 2024-06-07 | Fluxo             | L   | 0.835      | -            | -                | -                | -         |    -7.03 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            9 |     1275 | 2024-06-06 | Case              | W   | 0.830      | 0.371        | 0.030 (0.009)    | 0.721 (0.222)    | -         |    13.12 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            8 |     1316 | 2024-06-06 | Case              | W   | 0.827      | 0.450        | 0.030 (0.011)    | 0.721 (0.269)    | -         |    14.07 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            7 |     1464 | 2024-06-02 | Hawks             | W   | 0.802      | -            | -                | -                | -         |     3.58 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            6 |     1519 | 2024-05-31 | Intense           | L   | 0.790      | -            | -                | -                | -         |   -20.15 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            5 |     1583 | 2024-05-29 | FURIA Academy     | W   | 0.775      | -            | -                | -                | -         |     2.89 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            4 |     1622 | 2024-05-27 | inSanitY          | L   | 0.762      | -            | -                | -                | -         |   -11.04 | bnc, KAISER, piriajr, reix, SHOOWTiME |
|            3 |     2788 | 2024-04-16 | MIBR              | L   | 0.490      | -            | -                | -                | -         |    -0.74 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            2 |     3009 | 2024-04-08 | RED Canids        | L   | 0.435      | -            | -                | -                | -         |    -4.27 | bnc, KAISER, reix, SHOOWTiME, Tomate  |
|            1 |     3053 | 2024-04-06 | MIBR              | L   | 0.423      | -            | -                | -                | -         |    -0.77 | bnc, KAISER, reix, SHOOWTiME, Tomate  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,234.27)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-03 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-28 |      0.975 | $2,000.00      | $1,949.86       |
| 2024-06-10 |      0.856 | $1,500.00      | $1,284.41       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
