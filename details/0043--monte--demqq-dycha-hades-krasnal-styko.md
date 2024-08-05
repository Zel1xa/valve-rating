### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, kRaSnaL, STYKO<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1100.8<br />
<br />
Final Rank Value (1100.8) = Starting Rank Value (992.7) + Head To Head Adjustments (108.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.477[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 992.7
- 400 + ( ( 0.290 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 992.7


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
|           36 |      159 | 2024-07-31 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.509 (0.254)    | 0 (0.000) |     4.73 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           35 |      242 | 2024-07-29 | 9INE            | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.539 (0.234)    | 0 (0.000) |    11.04 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           34 |      290 | 2024-07-28 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -9.76 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           33 |      298 | 2024-07-27 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.45 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           32 |      306 | 2024-07-27 | 9z              | W   | 1.000      | 0.435        | 0.405 (0.176)    | 0.617 (0.268)    | 0 (0.000) |    28.28 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           31 |      341 | 2024-07-26 | Space           | W   | 1.000      | 0.435        | -                | 0.406 (0.177)    | 0 (0.000) |     9.23 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           30 |      376 | 2024-07-25 | Endpoint        | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |     7.37 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           29 |      396 | 2024-07-24 | Sashi           | L   | 1.000      | -            | -                | -                | -         |   -10.32 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           28 |      602 | 2024-07-18 | KOI             | W   | 1.000      | 0.500        | 0.058 (0.029)    | 0.374 (0.187)    | 0 (0.000) |    18.14 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           27 |      730 | 2024-07-16 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -13.59 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           26 |     1011 | 2024-06-16 | B8              | L   | 0.869      | -            | -                | -                | -         |   -10.37 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           25 |     1036 | 2024-06-15 | BLEED           | W   | 0.864      | 0.435        | 0.126 (0.047)    | 0.518 (0.194)    | 0 (0.000) |    22.70 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           24 |     1089 | 2024-06-14 | BLEED           | L   | 0.856      | -            | -                | -                | -         |    -3.98 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           23 |     1112 | 2024-06-13 | Zero Tenacity   | W   | 0.850      | 0.435        | 0.137 (0.051)    | 1.000 (0.370)    | 0 (0.000) |    15.36 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           22 |     1148 | 2024-06-12 | FORZE Reload    | W   | 0.843      | -            | -                | -                | 0 (0.000) |     1.64 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           21 |     1189 | 2024-06-10 | SINNERS         | W   | 0.830      | -            | -                | -                | -         |    13.72 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           20 |     1195 | 2024-06-10 | Aurora          | L   | 0.830      | -            | -                | -                | -         |    -2.77 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           19 |     1201 | 2024-06-10 | RUSH B          | L   | 0.829      | -            | -                | -                | -         |   -16.14 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           18 |     1213 | 2024-06-09 | AMKAL           | L   | 0.825      | -            | -                | -                | -         |    -7.17 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           17 |     1224 | 2024-06-09 | Aurora          | W   | 0.824      | 0.143        | 0.423 (0.050)    | -                | -         |    23.52 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           16 |     1233 | 2024-06-09 | 3DMAX           | W   | 0.824      | 0.143        | 0.507 (0.060)    | -                | -         |    24.00 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           15 |     1238 | 2024-06-09 | SAW             | L   | 0.823      | -            | -                | -                | -         |    -7.42 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           14 |     1248 | 2024-06-09 | PARIVISION      | L   | 0.823      | -            | -                | -                | -         |   -10.35 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           13 |     1256 | 2024-06-09 | 9 Pandas        | L   | 0.823      | -            | -                | -                | -         |   -11.30 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           12 |     1293 | 2024-06-08 | 1WIN            | W   | 0.818      | -            | -                | -                | -         |    11.47 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           11 |     1300 | 2024-06-08 | AMKAL           | L   | 0.817      | -            | -                | -                | -         |    -6.95 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           10 |     1312 | 2024-06-08 | Quixal          | W   | 0.816      | -            | -                | -                | -         |     0.79 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            9 |     1517 | 2024-06-04 | PARIVISION      | L   | 0.791      | -            | -                | -                | -         |   -10.46 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            8 |     1719 | 2024-05-27 | Falcons         | L   | 0.739      | -            | -                | -                | -         |    -2.26 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            7 |     1730 | 2024-05-27 | Vitality        | L   | 0.738      | -            | -                | -                | -         |    -0.22 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            6 |     1887 | 2024-05-21 | Sangal          | L   | 0.696      | -            | -                | -                | -         |    -8.14 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            5 |     1928 | 2024-05-20 | Sashi           | W   | 0.689      | 0.500        | 0.184 (0.063)    | 0.961 (0.331)    | -         |    15.77 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            4 |     1977 | 2024-05-18 | Sashi           | L   | 0.677      | -            | -                | -                | -         |    -5.59 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            3 |     2008 | 2024-05-17 | BLEED           | W   | 0.671      | 0.500        | 0.126 (0.042)    | 0.518 (0.174)    | -         |    18.82 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            2 |     2047 | 2024-05-16 | kONO            | W   | 0.663      | 0.384        | 0.028 (0.007)    | -                | -         |     6.56 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            1 |     2093 | 2024-05-15 | DMS             | W   | 0.657      | -            | -                | -                | -         |     8.25 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,916.94)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.871 | $5,000.00      | $4,354.17       |
| 2024-06-09 |      0.824 | $4,000.00      | $3,296.39       |
| 2024-06-02 |      0.778 | $4,000.00      | $3,112.22       |
| 2024-05-22 |      0.704 | $12,500.00     | $8,798.61       |
| 2024-05-18 |      0.678 | $2,000.00      | $1,355.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
