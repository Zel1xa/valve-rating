### Roster Details<br />
Team Name: inSanitY<br />
Roster: cass1n, f4stzin, iDk, pesadelo, shz<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [17]( ../standings_americas.md)<br />
<br />
Final Rank Value:  967.5<br />
<br />
Final Rank Value (967.5) = Starting Rank Value (917.3) + Head To Head Adjustments (50.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.432[<sup>1</sup>](#table2)
- Bounty Collected: 0.348[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 917.3
- 400 + ( ( 0.252 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 917.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |       94 | 2024-08-02 | Case              | L   | 1.000      | -            | -                | -                | -         |   -19.23 | cass1n, f4stzin, iDk, pesadelo, shz |
|           35 |      127 | 2024-08-01 | SPORT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.45 | cass1n, f4stzin, iDk, pesadelo, shz |
|           34 |      224 | 2024-07-30 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -12.78 | cass1n, f4stzin, iDk, pesadelo, shz |
|           33 |      377 | 2024-07-25 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.14 | cass1n, f4stzin, iDk, pesadelo, shz |
|           32 |      453 | 2024-07-23 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -20.73 | cass1n, f4stzin, iDk, pesadelo, shz |
|           31 |      539 | 2024-07-20 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.56 | cass1n, f4stzin, iDk, pesadelo, shz |
|           30 |      643 | 2024-07-18 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -22.22 | cass1n, f4stzin, iDk, pesadelo, shz |
|           29 |      708 | 2024-07-17 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.78 | cass1n, f4stzin, iDk, pesadelo, shz |
|           28 |      744 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.10 | cass1n, f4stzin, iDk, pesadelo, shz |
|           27 |      749 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.45 | cass1n, f4stzin, iDk, pesadelo, shz |
|           26 |      793 | 2024-07-15 | Galorys           | W   | 1.000      | 0.450        | 0.030 (0.013)    | 0.542 (0.244)    | 0 (0.000) |     8.09 | cass1n, f4stzin, iDk, pesadelo, shz |
|           25 |      799 | 2024-07-15 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -23.95 | cass1n, f4stzin, iDk, pesadelo, shz |
|           24 |      815 | 2024-07-15 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.32 | cass1n, f4stzin, iDk, pesadelo, shz |
|           23 |      960 | 2024-07-03 | Bounty Hunters    | W   | 0.976      | 0.333        | -                | 0.552 (0.180)    | 0 (0.000) |    11.45 | cass1n, f4stzin, iDk, pesadelo, shz |
|           22 |      963 | 2024-07-01 | Bounty Hunters    | W   | 0.962      | 0.333        | -                | 0.552 (0.177)    | 0 (0.000) |    11.80 | cass1n, f4stzin, iDk, pesadelo, shz |
|           21 |      973 | 2024-06-29 | Galorys           | W   | 0.949      | 0.333        | 0.030 (0.009)    | -                | 0 (0.000) |     8.59 | cass1n, f4stzin, iDk, pesadelo, shz |
|           20 |      987 | 2024-06-27 | Sharks            | W   | 0.935      | 0.333        | 0.030 (0.009)    | -                | -         |    15.63 | cass1n, f4stzin, iDk, pesadelo, shz |
|           19 |     1008 | 2024-06-19 | Case              | W   | 0.883      | 0.337        | 0.029 (0.009)    | 0.795 (0.236)    | -         |     8.97 | cass1n, f4stzin, iDk, pesadelo, shz |
|           18 |     1009 | 2024-06-18 | Galorys           | W   | 0.877      | 0.337        | 0.030 (0.009)    | -                | -         |     9.13 | cass1n, f4stzin, iDk, pesadelo, shz |
|           17 |     1012 | 2024-06-17 | Dusty Roots       | W   | 0.870      | -            | -                | -                | -         |     8.85 | cass1n, f4stzin, iDk, pesadelo, shz |
|           16 |     1052 | 2024-06-15 | Fluxo             | L   | 0.856      | -            | -                | -                | -         |    -8.89 | cass1n, f4stzin, iDk, pesadelo, shz |
|           15 |     1096 | 2024-06-14 | Patins da Ferrari | W   | 0.849      | -            | -                | -                | -         |     8.24 | cass1n, f4stzin, iDk, pesadelo, shz |
|           14 |     1238 | 2024-06-09 | Bounty Hunters    | L   | 0.816      | -            | -                | -                | -         |   -15.05 | cass1n, f4stzin, iDk, pesadelo, shz |
|           13 |     1244 | 2024-06-09 | Bounty Hunters    | W   | 0.815      | 0.450        | 0.022 (0.008)    | 0.552 (0.203)    | -         |    10.67 | cass1n, f4stzin, iDk, pesadelo, shz |
|           12 |     1320 | 2024-06-08 | Solid             | W   | 0.809      | 0.450        | 0.024 (0.009)    | 0.825 (0.300)    | -         |    10.06 | cass1n, f4stzin, iDk, pesadelo, shz |
|           11 |     1355 | 2024-06-07 | Hype              | L   | 0.803      | -            | -                | -                | -         |   -15.18 | cass1n, f4stzin, iDk, pesadelo, shz |
|           10 |     1384 | 2024-06-07 | KRÜ               | W   | 0.801      | -            | -                | -                | -         |     9.31 | cass1n, f4stzin, iDk, pesadelo, shz |
|            9 |     1422 | 2024-06-06 | BESTIA            | W   | 0.796      | 0.450        | 0.096 (0.034)    | 0.793 (0.284)    | -         |    15.47 | cass1n, f4stzin, iDk, pesadelo, shz |
|            8 |     1613 | 2024-06-01 | Solid             | W   | 0.764      | 0.371        | -                | 0.825 (0.233)    | -         |    10.24 | cass1n, f4stzin, iDk, pesadelo, shz |
|            7 |     1690 | 2024-05-30 | Intense           | W   | 0.748      | -            | -                | -                | -         |     5.72 | cass1n, f4stzin, iDk, pesadelo, shz |
|            6 |     1751 | 2024-05-27 | Bounty Hunters    | W   | 0.730      | -            | -                | -                | -         |    10.04 | cass1n, f4stzin, iDk, pesadelo, shz |
|            5 |     2214 | 2024-05-12 | 9z                | L   | 0.630      | -            | -                | -                | -         |    -0.74 | cass1n, f4stzin, pesadelo, shz, vsm |
|            4 |     2273 | 2024-05-10 | 9z                | L   | 0.617      | -            | -                | -                | -         |    -0.68 | cass1n, f4stzin, iDk, pesadelo, shz |
|            3 |     2299 | 2024-05-09 | ODDIK             | W   | 0.609      | 0.435        | 0.099 (0.026)    | 0.823 (0.218)    | -         |    10.88 | cass1n, f4stzin, iDk, pesadelo, shz |
|            2 |     2338 | 2024-05-07 | Case              | W   | 0.595      | 0.435        | 0.029 (0.008)    | 0.795 (0.206)    | -         |     9.13 | cass1n, f4stzin, iDk, pesadelo, shz |
|            1 |     2371 | 2024-05-05 | Imperial          | L   | 0.582      | -            | -                | -                | -         |    -2.13 | cass1n, f4stzin, iDk, pesadelo, shz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,506.59)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-03 |      0.976 | $6,000.00      | $5,855.00       |
| 2024-06-19 |      0.883 | $5,350.00      | $4,722.86       |
| 2024-06-16 |      0.862 | $5,000.00      | $4,311.11       |
| 2024-06-10 |      0.823 | $750.00        | $617.62         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
