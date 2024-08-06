### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, kRaSnaL, STYKO<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1103.9<br />
<br />
Final Rank Value (1103.9) = Starting Rank Value (994.6) + Head To Head Adjustments (109.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.477[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.239[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 994.6
- 400 + ( ( 0.289 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 994.6


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
|           36 |      201 | 2024-07-31 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |     4.82 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           35 |      284 | 2024-07-29 | 9INE            | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.523 (0.227)    | 0 (0.000) |    11.17 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           34 |      332 | 2024-07-28 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -9.65 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           33 |      340 | 2024-07-27 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.48 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           32 |      348 | 2024-07-27 | 9z              | W   | 1.000      | 0.435        | 0.404 (0.175)    | 0.591 (0.257)    | 0 (0.000) |    28.19 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           31 |      383 | 2024-07-26 | Space           | W   | 1.000      | 0.435        | -                | 0.429 (0.187)    | 0 (0.000) |     9.55 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           30 |      418 | 2024-07-25 | Endpoint        | W   | 1.000      | 0.435        | -                | 0.540 (0.235)    | 0 (0.000) |     7.66 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           29 |      438 | 2024-07-24 | Sashi           | L   | 1.000      | -            | -                | -                | -         |   -10.33 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           28 |      644 | 2024-07-18 | KOI             | W   | 1.000      | 0.500        | 0.058 (0.029)    | 0.356 (0.178)    | 0 (0.000) |    17.95 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           27 |      772 | 2024-07-16 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -13.45 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           26 |     1053 | 2024-06-16 | B8              | L   | 0.859      | -            | -                | -                | -         |   -10.24 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           25 |     1078 | 2024-06-15 | BLEED           | W   | 0.853      | 0.435        | 0.126 (0.047)    | 0.538 (0.200)    | 0 (0.000) |    22.50 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           24 |     1131 | 2024-06-14 | BLEED           | L   | 0.845      | -            | -                | -                | -         |    -3.87 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           23 |     1154 | 2024-06-13 | Zero Tenacity   | W   | 0.840      | 0.435        | 0.143 (0.052)    | 1.000 (0.365)    | 0 (0.000) |    15.29 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           22 |     1190 | 2024-06-12 | FORZE Reload    | W   | 0.832      | -            | -                | -                | 0 (0.000) |     1.61 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           21 |     1231 | 2024-06-10 | SINNERS         | W   | 0.819      | -            | -                | -                | -         |    13.74 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           20 |     1237 | 2024-06-10 | Aurora          | L   | 0.819      | -            | -                | -                | -         |    -2.63 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           19 |     1243 | 2024-06-10 | RUSH B          | L   | 0.819      | -            | -                | -                | -         |   -15.99 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           18 |     1255 | 2024-06-09 | AMKAL           | L   | 0.814      | -            | -                | -                | -         |    -7.10 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           17 |     1266 | 2024-06-09 | Aurora          | W   | 0.813      | 0.143        | 0.420 (0.049)    | -                | -         |    23.31 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           16 |     1275 | 2024-06-09 | 3DMAX           | W   | 0.813      | 0.143        | 0.510 (0.059)    | -                | -         |    23.75 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           15 |     1280 | 2024-06-09 | SAW             | L   | 0.813      | -            | -                | -                | -         |    -7.47 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           14 |     1290 | 2024-06-09 | PARIVISION      | L   | 0.812      | -            | -                | -                | -         |   -10.06 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           13 |     1298 | 2024-06-09 | 9 Pandas        | L   | 0.812      | -            | -                | -                | -         |   -11.05 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           12 |     1335 | 2024-06-08 | 1WIN            | W   | 0.807      | -            | -                | -                | -         |    11.53 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           11 |     1342 | 2024-06-08 | AMKAL           | L   | 0.806      | -            | -                | -                | -         |    -6.88 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           10 |     1354 | 2024-06-08 | Quixal          | W   | 0.806      | -            | -                | -                | -         |     0.77 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            9 |     1559 | 2024-06-04 | PARIVISION      | L   | 0.781      | -            | -                | -                | -         |   -10.13 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            8 |     1761 | 2024-05-27 | Falcons         | L   | 0.729      | -            | -                | -                | -         |    -2.29 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            7 |     1772 | 2024-05-27 | Vitality        | L   | 0.727      | -            | -                | -                | -         |    -0.22 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            6 |     1929 | 2024-05-21 | Sangal          | L   | 0.686      | -            | -                | -                | -         |    -7.79 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            5 |     1970 | 2024-05-20 | Sashi           | W   | 0.678      | 0.500        | 0.184 (0.062)    | 0.958 (0.325)    | -         |    15.52 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            4 |     2019 | 2024-05-18 | Sashi           | L   | 0.666      | -            | -                | -                | -         |    -5.52 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            3 |     2050 | 2024-05-17 | BLEED           | W   | 0.660      | 0.500        | 0.126 (0.041)    | 0.538 (0.178)    | -         |    18.55 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            2 |     2089 | 2024-05-16 | kONO            | W   | 0.653      | 0.384        | 0.028 (0.007)    | -                | -         |     6.50 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            1 |     2135 | 2024-05-15 | DMS             | W   | 0.647      | -            | -                | -                | -         |     8.15 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,626.67)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.860 | $5,000.00      | $4,301.39       |
| 2024-06-09 |      0.814 | $4,000.00      | $3,254.17       |
| 2024-06-02 |      0.767 | $4,000.00      | $3,070.00       |
| 2024-05-22 |      0.693 | $12,500.00     | $8,666.67       |
| 2024-05-18 |      0.667 | $2,000.00      | $1,334.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
