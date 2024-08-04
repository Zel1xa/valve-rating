### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, kRaSnaL, STYKO<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1100.4<br />
<br />
Final Rank Value (1100.4) = Starting Rank Value (992.8) + Head To Head Adjustments (107.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.477[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 992.8
- 400 + ( ( 0.290 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 992.8


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
|           36 |      131 | 2024-07-31 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.510 (0.255)    | 0 (0.000) |     4.77 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           35 |      214 | 2024-07-29 | 9INE            | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.537 (0.233)    | 0 (0.000) |    11.06 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           34 |      262 | 2024-07-28 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -9.82 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           33 |      270 | 2024-07-27 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.46 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           32 |      278 | 2024-07-27 | 9z              | W   | 1.000      | 0.435        | 0.405 (0.176)    | 0.618 (0.269)    | 0 (0.000) |    28.29 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           31 |      313 | 2024-07-26 | Space           | W   | 1.000      | 0.435        | -                | 0.406 (0.177)    | 0 (0.000) |     9.43 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           30 |      348 | 2024-07-25 | Endpoint        | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |     7.50 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           29 |      368 | 2024-07-24 | Sashi           | L   | 1.000      | -            | -                | -                | -         |   -10.33 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           28 |      571 | 2024-07-18 | KOI             | W   | 1.000      | 0.500        | 0.058 (0.029)    | 0.375 (0.188)    | 0 (0.000) |    18.14 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           27 |      701 | 2024-07-16 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -13.56 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           26 |      983 | 2024-06-16 | B8              | L   | 0.873      | -            | -                | -                | -         |   -10.42 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           25 |     1008 | 2024-06-15 | BLEED           | W   | 0.867      | 0.435        | 0.126 (0.048)    | 0.517 (0.195)    | 0 (0.000) |    22.77 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           24 |     1061 | 2024-06-14 | BLEED           | L   | 0.859      | -            | -                | -                | -         |    -4.01 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           23 |     1084 | 2024-06-13 | Zero Tenacity   | W   | 0.854      | 0.435        | 0.137 (0.051)    | 1.000 (0.371)    | 0 (0.000) |    15.45 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           22 |     1120 | 2024-06-12 | FORZE Reload    | W   | 0.846      | -            | -                | -                | 0 (0.000) |     1.65 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           21 |     1161 | 2024-06-10 | SINNERS         | W   | 0.833      | -            | -                | -                | -         |    13.15 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           20 |     1167 | 2024-06-10 | Aurora          | L   | 0.833      | -            | -                | -                | -         |    -2.81 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           19 |     1173 | 2024-06-10 | RUSH B          | L   | 0.833      | -            | -                | -                | -         |   -16.25 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           18 |     1185 | 2024-06-09 | AMKAL           | L   | 0.828      | -            | -                | -                | -         |    -7.16 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           17 |     1196 | 2024-06-09 | Aurora          | W   | 0.827      | 0.143        | 0.423 (0.050)    | -                | -         |    23.58 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           16 |     1205 | 2024-06-09 | 3DMAX           | W   | 0.827      | 0.143        | 0.506 (0.060)    | -                | -         |    24.08 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           15 |     1210 | 2024-06-09 | SAW             | L   | 0.827      | -            | -                | -                | -         |    -7.43 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           14 |     1220 | 2024-06-09 | PARIVISION      | L   | 0.826      | -            | -                | -                | -         |   -10.45 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           13 |     1228 | 2024-06-09 | 9 Pandas        | L   | 0.826      | -            | -                | -                | -         |   -11.37 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           12 |     1265 | 2024-06-08 | 1WIN            | W   | 0.821      | -            | -                | -                | -         |    11.35 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           11 |     1272 | 2024-06-08 | AMKAL           | L   | 0.820      | -            | -                | -                | -         |    -6.96 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           10 |     1284 | 2024-06-08 | Quixal          | W   | 0.820      | -            | -                | -                | -         |     0.79 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            9 |     1489 | 2024-06-04 | PARIVISION      | L   | 0.795      | -            | -                | -                | -         |   -10.58 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            8 |     1691 | 2024-05-27 | Falcons         | L   | 0.743      | -            | -                | -                | -         |    -2.27 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            7 |     1702 | 2024-05-27 | Vitality        | L   | 0.741      | -            | -                | -                | -         |    -0.22 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            6 |     1859 | 2024-05-21 | Sangal          | L   | 0.700      | -            | -                | -                | -         |    -8.28 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            5 |     1900 | 2024-05-20 | Sashi           | W   | 0.692      | 0.500        | 0.184 (0.064)    | 0.962 (0.333)    | -         |    15.83 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            4 |     1949 | 2024-05-18 | Sashi           | L   | 0.680      | -            | -                | -                | -         |    -5.63 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            3 |     1980 | 2024-05-17 | BLEED           | W   | 0.674      | 0.500        | 0.126 (0.043)    | 0.517 (0.174)    | -         |    18.90 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            2 |     2019 | 2024-05-16 | kONO            | W   | 0.667      | 0.384        | 0.028 (0.007)    | -                | -         |     6.60 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            1 |     2065 | 2024-05-15 | DMS             | W   | 0.661      | -            | -                | -                | -         |     8.28 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,011.79)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.874 | $5,000.00      | $4,371.41       |
| 2024-06-09 |      0.828 | $4,000.00      | $3,310.19       |
| 2024-06-02 |      0.782 | $4,000.00      | $3,126.02       |
| 2024-05-22 |      0.707 | $12,500.00     | $8,841.72       |
| 2024-05-18 |      0.681 | $2,000.00      | $1,362.45       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
