### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, kRaSnaL, STYKO<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1101.8<br />
<br />
Final Rank Value (1101.8) = Starting Rank Value (994.0) + Head To Head Adjustments (107.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.477[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.243[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 994.0
- 400 + ( ( 0.290 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 994.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |      172 | 2024-07-31 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.507 (0.253)    | 0 (0.000) |     4.72 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           35 |      255 | 2024-07-29 | 9INE            | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.539 (0.234)    | 0 (0.000) |    11.04 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           34 |      303 | 2024-07-28 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -9.75 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           33 |      311 | 2024-07-27 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.44 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           32 |      319 | 2024-07-27 | 9z              | W   | 1.000      | 0.435        | 0.405 (0.176)    | 0.615 (0.267)    | 0 (0.000) |    28.26 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           31 |      354 | 2024-07-26 | Space           | W   | 1.000      | 0.435        | -                | 0.445 (0.193)    | 0 (0.000) |     9.34 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           30 |      389 | 2024-07-25 | Endpoint        | W   | 1.000      | 0.435        | -                | 0.520 (0.226)    | 0 (0.000) |     7.36 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           29 |      409 | 2024-07-24 | Sashi           | L   | 1.000      | -            | -                | -                | -         |   -10.33 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           28 |      615 | 2024-07-18 | KOI             | W   | 1.000      | 0.500        | 0.058 (0.029)    | 0.372 (0.186)    | 0 (0.000) |    18.07 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           27 |      743 | 2024-07-16 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -13.59 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           26 |     1024 | 2024-06-16 | B8              | L   | 0.866      | -            | -                | -                | -         |   -10.35 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           25 |     1049 | 2024-06-15 | BLEED           | W   | 0.861      | 0.435        | 0.126 (0.047)    | 0.517 (0.193)    | 0 (0.000) |    22.64 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           24 |     1102 | 2024-06-14 | BLEED           | L   | 0.853      | -            | -                | -                | -         |    -3.94 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           23 |     1125 | 2024-06-13 | Zero Tenacity   | W   | 0.847      | 0.435        | 0.137 (0.050)    | 1.000 (0.368)    | 0 (0.000) |    15.29 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           22 |     1161 | 2024-06-12 | FORZE Reload    | W   | 0.839      | -            | -                | -                | 0 (0.000) |     1.62 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           21 |     1202 | 2024-06-10 | SINNERS         | W   | 0.827      | -            | -                | -                | -         |    13.73 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           20 |     1208 | 2024-06-10 | Aurora          | L   | 0.826      | -            | -                | -                | -         |    -2.75 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           19 |     1214 | 2024-06-10 | RUSH B          | L   | 0.826      | -            | -                | -                | -         |   -16.12 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           18 |     1226 | 2024-06-09 | AMKAL           | L   | 0.821      | -            | -                | -                | -         |    -7.19 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           17 |     1237 | 2024-06-09 | Aurora          | W   | 0.821      | 0.143        | 0.422 (0.049)    | -                | -         |    23.43 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           16 |     1246 | 2024-06-09 | 3DMAX           | W   | 0.820      | 0.143        | 0.508 (0.060)    | -                | -         |    23.92 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           15 |     1251 | 2024-06-09 | SAW             | L   | 0.820      | -            | -                | -                | -         |    -7.44 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           14 |     1261 | 2024-06-09 | PARIVISION      | L   | 0.820      | -            | -                | -                | -         |   -10.29 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           13 |     1269 | 2024-06-09 | 9 Pandas        | L   | 0.819      | -            | -                | -                | -         |   -11.30 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           12 |     1306 | 2024-06-08 | 1WIN            | W   | 0.814      | -            | -                | -                | -         |    11.54 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           11 |     1313 | 2024-06-08 | AMKAL           | L   | 0.814      | -            | -                | -                | -         |    -6.98 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           10 |     1325 | 2024-06-08 | Quixal          | W   | 0.813      | -            | -                | -                | -         |     0.78 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            9 |     1530 | 2024-06-04 | PARIVISION      | L   | 0.788      | -            | -                | -                | -         |   -10.40 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            8 |     1732 | 2024-05-27 | Falcons         | L   | 0.736      | -            | -                | -                | -         |    -2.28 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            7 |     1743 | 2024-05-27 | Vitality        | L   | 0.735      | -            | -                | -                | -         |    -0.22 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            6 |     1900 | 2024-05-21 | Sangal          | L   | 0.693      | -            | -                | -                | -         |    -8.06 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            5 |     1941 | 2024-05-20 | Sashi           | W   | 0.686      | 0.500        | 0.184 (0.063)    | 0.996 (0.341)    | -         |    15.66 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            4 |     1990 | 2024-05-18 | Sashi           | L   | 0.673      | -            | -                | -                | -         |    -5.59 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            3 |     2021 | 2024-05-17 | BLEED           | W   | 0.667      | 0.500        | 0.126 (0.042)    | 0.517 (0.172)    | -         |    18.74 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            2 |     2060 | 2024-05-16 | kONO            | W   | 0.660      | 0.384        | 0.028 (0.007)    | -                | -         |     6.48 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            1 |     2106 | 2024-05-15 | DMS             | W   | 0.654      | -            | -                | -                | -         |     8.28 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,825.28)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.868 | $5,000.00      | $4,337.50       |
| 2024-06-09 |      0.821 | $4,000.00      | $3,283.06       |
| 2024-06-02 |      0.775 | $4,000.00      | $3,098.89       |
| 2024-05-22 |      0.701 | $12,500.00     | $8,756.94       |
| 2024-05-18 |      0.674 | $2,000.00      | $1,348.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
