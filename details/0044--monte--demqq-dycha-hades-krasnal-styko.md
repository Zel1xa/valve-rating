### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, kRaSnaL, STYKO<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1102.0<br />
<br />
Final Rank Value (1102.0) = Starting Rank Value (993.6) + Head To Head Adjustments (108.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.477[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.241[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 993.6
- 400 + ( ( 0.290 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 993.6


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
|           36 |      180 | 2024-07-31 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |     4.75 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           35 |      263 | 2024-07-29 | 9INE            | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.533 (0.231)    | 0 (0.000) |    11.07 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           34 |      311 | 2024-07-28 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -9.73 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           33 |      319 | 2024-07-27 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.44 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           32 |      327 | 2024-07-27 | 9z              | W   | 1.000      | 0.435        | 0.404 (0.176)    | 0.607 (0.264)    | 0 (0.000) |    28.25 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           31 |      362 | 2024-07-26 | Space           | W   | 1.000      | 0.435        | -                | 0.439 (0.191)    | 0 (0.000) |     9.33 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           30 |      397 | 2024-07-25 | Endpoint        | W   | 1.000      | 0.435        | -                | 0.514 (0.223)    | 0 (0.000) |     7.37 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           29 |      417 | 2024-07-24 | Sashi           | L   | 1.000      | -            | -                | -                | -         |   -10.33 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           28 |      623 | 2024-07-18 | KOI             | W   | 1.000      | 0.500        | 0.058 (0.029)    | 0.367 (0.183)    | 0 (0.000) |    18.07 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           27 |      751 | 2024-07-16 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -13.57 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           26 |     1032 | 2024-06-16 | B8              | L   | 0.865      | -            | -                | -                | -         |   -10.33 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           25 |     1057 | 2024-06-15 | BLEED           | W   | 0.859      | 0.435        | 0.126 (0.047)    | 0.511 (0.191)    | 0 (0.000) |    22.64 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           24 |     1110 | 2024-06-14 | BLEED           | L   | 0.851      | -            | -                | -                | -         |    -3.91 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           23 |     1133 | 2024-06-13 | Zero Tenacity   | W   | 0.846      | 0.435        | 0.143 (0.053)    | 1.000 (0.368)    | 0 (0.000) |    15.28 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           22 |     1169 | 2024-06-12 | FORZE Reload    | W   | 0.838      | -            | -                | -                | 0 (0.000) |     1.62 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           21 |     1210 | 2024-06-10 | SINNERS         | W   | 0.826      | -            | -                | -                | -         |    13.81 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           20 |     1216 | 2024-06-10 | Aurora          | L   | 0.825      | -            | -                | -                | -         |    -2.71 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           19 |     1222 | 2024-06-10 | RUSH B          | L   | 0.825      | -            | -                | -                | -         |   -16.07 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           18 |     1234 | 2024-06-09 | AMKAL           | L   | 0.820      | -            | -                | -                | -         |    -7.18 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           17 |     1245 | 2024-06-09 | Aurora          | W   | 0.820      | 0.143        | 0.422 (0.049)    | -                | -         |    23.43 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           16 |     1254 | 2024-06-09 | 3DMAX           | W   | 0.819      | 0.143        | 0.508 (0.059)    | -                | -         |    23.90 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           15 |     1259 | 2024-06-09 | SAW             | L   | 0.819      | -            | -                | -                | -         |    -7.43 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           14 |     1269 | 2024-06-09 | PARIVISION      | L   | 0.818      | -            | -                | -                | -         |   -10.20 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           13 |     1277 | 2024-06-09 | 9 Pandas        | L   | 0.818      | -            | -                | -                | -         |   -11.25 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           12 |     1314 | 2024-06-08 | 1WIN            | W   | 0.813      | -            | -                | -                | -         |    11.57 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           11 |     1321 | 2024-06-08 | AMKAL           | L   | 0.813      | -            | -                | -                | -         |    -6.97 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           10 |     1333 | 2024-06-08 | Quixal          | W   | 0.812      | -            | -                | -                | -         |     0.78 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            9 |     1538 | 2024-06-04 | PARIVISION      | L   | 0.787      | -            | -                | -                | -         |   -10.30 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            8 |     1740 | 2024-05-27 | Falcons         | L   | 0.735      | -            | -                | -                | -         |    -2.28 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            7 |     1751 | 2024-05-27 | Vitality        | L   | 0.733      | -            | -                | -                | -         |    -0.22 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            6 |     1908 | 2024-05-21 | Sangal          | L   | 0.692      | -            | -                | -                | -         |    -8.02 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            5 |     1949 | 2024-05-20 | Sashi           | W   | 0.684      | 0.500        | 0.184 (0.063)    | 0.983 (0.336)    | -         |    15.65 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            4 |     1998 | 2024-05-18 | Sashi           | L   | 0.672      | -            | -                | -                | -         |    -5.57 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            3 |     2029 | 2024-05-17 | BLEED           | W   | 0.666      | 0.500        | 0.126 (0.042)    | 0.511 (0.170)    | -         |    18.73 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            2 |     2068 | 2024-05-16 | kONO            | W   | 0.659      | 0.384        | 0.028 (0.007)    | -                | -         |     6.49 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            1 |     2114 | 2024-05-15 | DMS             | W   | 0.653      | -            | -                | -                | -         |     8.27 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,794.72)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.866 | $5,000.00      | $4,331.94       |
| 2024-06-09 |      0.820 | $4,000.00      | $3,278.61       |
| 2024-06-02 |      0.774 | $4,000.00      | $3,094.44       |
| 2024-05-22 |      0.699 | $12,500.00     | $8,743.06       |
| 2024-05-18 |      0.673 | $2,000.00      | $1,346.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
