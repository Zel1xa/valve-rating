### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, kRaSnaL, STYKO<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1101.1<br />
<br />
Final Rank Value (1101.1) = Starting Rank Value (992.8) + Head To Head Adjustments (108.3)<br />

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
- 400 + ( ( 0.290 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 992.8


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
|           36 |      155 | 2024-07-31 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.509 (0.255)    | 0 (0.000) |     4.73 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           35 |      238 | 2024-07-29 | 9INE            | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.537 (0.234)    | 0 (0.000) |    11.04 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           34 |      286 | 2024-07-28 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -9.76 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           33 |      294 | 2024-07-27 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.45 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           32 |      302 | 2024-07-27 | 9z              | W   | 1.000      | 0.435        | 0.405 (0.176)    | 0.618 (0.269)    | 0 (0.000) |    28.28 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           31 |      337 | 2024-07-26 | Space           | W   | 1.000      | 0.435        | -                | 0.406 (0.177)    | 0 (0.000) |     9.24 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           30 |      372 | 2024-07-25 | Endpoint        | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |     7.36 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           29 |      392 | 2024-07-24 | Sashi           | L   | 1.000      | -            | -                | -                | -         |   -10.32 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           28 |      598 | 2024-07-18 | KOI             | W   | 1.000      | 0.500        | 0.058 (0.029)    | 0.375 (0.187)    | 0 (0.000) |    18.16 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           27 |      726 | 2024-07-16 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -13.59 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           26 |     1007 | 2024-06-16 | B8              | L   | 0.872      | -            | -                | -                | -         |   -10.39 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           25 |     1032 | 2024-06-15 | BLEED           | W   | 0.866      | 0.435        | 0.126 (0.047)    | 0.517 (0.195)    | 0 (0.000) |    22.75 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           24 |     1085 | 2024-06-14 | BLEED           | L   | 0.858      | -            | -                | -                | -         |    -4.00 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           23 |     1108 | 2024-06-13 | Zero Tenacity   | W   | 0.853      | 0.435        | 0.137 (0.051)    | 1.000 (0.371)    | 0 (0.000) |    15.40 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           22 |     1144 | 2024-06-12 | FORZE Reload    | W   | 0.845      | -            | -                | -                | 0 (0.000) |     1.64 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           21 |     1185 | 2024-06-10 | SINNERS         | W   | 0.832      | -            | -                | -                | -         |    13.75 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           20 |     1191 | 2024-06-10 | Aurora          | L   | 0.832      | -            | -                | -                | -         |    -2.80 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           19 |     1197 | 2024-06-10 | RUSH B          | L   | 0.832      | -            | -                | -                | -         |   -16.18 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           18 |     1209 | 2024-06-09 | AMKAL           | L   | 0.827      | -            | -                | -                | -         |    -7.18 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           17 |     1220 | 2024-06-09 | Aurora          | W   | 0.826      | 0.143        | 0.423 (0.050)    | -                | -         |    23.57 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           16 |     1229 | 2024-06-09 | 3DMAX           | W   | 0.826      | 0.143        | 0.506 (0.060)    | -                | -         |    24.05 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           15 |     1234 | 2024-06-09 | SAW             | L   | 0.826      | -            | -                | -                | -         |    -7.41 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           14 |     1244 | 2024-06-09 | PARIVISION      | L   | 0.825      | -            | -                | -                | -         |   -10.38 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           13 |     1252 | 2024-06-09 | 9 Pandas        | L   | 0.825      | -            | -                | -                | -         |   -11.31 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           12 |     1289 | 2024-06-08 | 1WIN            | W   | 0.820      | -            | -                | -                | -         |    11.52 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           11 |     1296 | 2024-06-08 | AMKAL           | L   | 0.819      | -            | -                | -                | -         |    -6.96 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           10 |     1308 | 2024-06-08 | Quixal          | W   | 0.819      | -            | -                | -                | -         |     0.79 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            9 |     1513 | 2024-06-04 | PARIVISION      | L   | 0.793      | -            | -                | -                | -         |   -10.50 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            8 |     1715 | 2024-05-27 | Falcons         | L   | 0.742      | -            | -                | -                | -         |    -2.27 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            7 |     1726 | 2024-05-27 | Vitality        | L   | 0.740      | -            | -                | -                | -         |    -0.22 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            6 |     1883 | 2024-05-21 | Sangal          | L   | 0.699      | -            | -                | -                | -         |    -8.17 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            5 |     1924 | 2024-05-20 | Sashi           | W   | 0.691      | 0.500        | 0.184 (0.064)    | 0.962 (0.332)    | -         |    15.83 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            4 |     1973 | 2024-05-18 | Sashi           | L   | 0.679      | -            | -                | -                | -         |    -5.60 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            3 |     2004 | 2024-05-17 | BLEED           | W   | 0.673      | 0.500        | 0.126 (0.042)    | 0.517 (0.174)    | -         |    18.89 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            2 |     2043 | 2024-05-16 | kONO            | W   | 0.666      | 0.384        | 0.028 (0.007)    | -                | -         |     6.59 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            1 |     2089 | 2024-05-15 | DMS             | W   | 0.660      | -            | -                | -                | -         |     8.28 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,982.51)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.873 | $5,000.00      | $4,366.09       |
| 2024-06-09 |      0.826 | $4,000.00      | $3,305.93       |
| 2024-06-02 |      0.780 | $4,000.00      | $3,121.76       |
| 2024-05-22 |      0.706 | $12,500.00     | $8,828.41       |
| 2024-05-18 |      0.680 | $2,000.00      | $1,360.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
