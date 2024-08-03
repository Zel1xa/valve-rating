### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, kRaSnaL, STYKO<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1084.5<br />
<br />
Final Rank Value (1084.5) = Starting Rank Value (982.2) + Head To Head Adjustments (102.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.477[<sup>1</sup>](#table2)
- Bounty Collected: 0.419[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.285<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 982.2
- 400 + ( ( 0.285 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 982.2


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
|           36 |       98 | 2024-07-31 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.528 (0.264)    | 0 (0.000) |     4.89 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           35 |      180 | 2024-07-29 | 9INE            | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.553 (0.240)    | 0 (0.000) |    11.69 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           34 |      228 | 2024-07-28 | Sangal          | L   | 1.000      | -            | -                | -                | -         |   -10.27 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           33 |      236 | 2024-07-27 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.75 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           32 |      244 | 2024-07-27 | 9z              | W   | 1.000      | 0.435        | 0.136 (0.059)    | 0.528 (0.229)    | 0 (0.000) |    23.15 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           31 |      279 | 2024-07-26 | Space           | W   | 1.000      | 0.435        | -                | 0.420 (0.183)    | 0 (0.000) |    10.29 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           30 |      314 | 2024-07-25 | Endpoint        | W   | 1.000      | 0.435        | -                | 0.540 (0.235)    | 0 (0.000) |     7.94 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           29 |      334 | 2024-07-24 | Sashi           | L   | 1.000      | -            | -                | -                | -         |    -9.83 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           28 |      540 | 2024-07-18 | KOI             | W   | 1.000      | 0.500        | 0.040 (0.020)    | 0.319 (0.160)    | 0 (0.000) |    12.64 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           27 |      665 | 2024-07-16 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -14.11 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           26 |      934 | 2024-06-16 | B8              | L   | 0.878      | -            | -                | -                | -         |   -10.26 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           25 |      953 | 2024-06-15 | BLEED           | W   | 0.873      | 0.435        | 0.126 (0.048)    | 0.534 (0.202)    | 0 (0.000) |    23.11 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           24 |      999 | 2024-06-14 | BLEED           | L   | 0.865      | -            | -                | -                | -         |    -3.85 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           23 |     1022 | 2024-06-13 | Zero Tenacity   | W   | 0.859      | 0.435        | 0.137 (0.051)    | 1.000 (0.373)    | 0 (0.000) |    15.27 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           22 |     1056 | 2024-06-12 | FORZE Reload    | W   | 0.851      | -            | -                | -                | 0 (0.000) |     1.74 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           21 |     1095 | 2024-06-10 | SINNERS         | W   | 0.839      | -            | -                | -                | -         |    13.39 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           20 |     1101 | 2024-06-10 | Aurora          | L   | 0.839      | -            | -                | -                | -         |    -2.75 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           19 |     1107 | 2024-06-10 | RUSH B          | L   | 0.838      | -            | -                | -                | -         |   -16.38 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           18 |     1118 | 2024-06-09 | AMKAL           | L   | 0.834      | -            | -                | -                | -         |    -7.05 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           17 |     1129 | 2024-06-09 | Aurora          | W   | 0.833      | 0.143        | 0.425 (0.051)    | -                | -         |    23.82 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           16 |     1138 | 2024-06-09 | 3DMAX           | W   | 0.833      | 0.143        | 0.504 (0.060)    | -                | -         |    24.23 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           15 |     1143 | 2024-06-09 | SAW             | L   | 0.832      | -            | -                | -                | -         |    -7.35 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           14 |     1153 | 2024-06-09 | PARIVISION      | L   | 0.832      | -            | -                | -                | -         |   -10.26 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           13 |     1161 | 2024-06-09 | 9 Pandas        | L   | 0.831      | -            | -                | -                | -         |   -11.06 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           12 |     1195 | 2024-06-08 | 1WIN            | W   | 0.827      | -            | -                | -                | -         |    11.33 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           11 |     1201 | 2024-06-08 | AMKAL           | L   | 0.826      | -            | -                | -                | -         |    -6.81 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           10 |     1212 | 2024-06-08 | Quixal          | W   | 0.825      | -            | -                | -                | -         |     0.84 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            9 |     1416 | 2024-06-04 | PARIVISION      | L   | 0.800      | -            | -                | -                | -         |   -10.37 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            8 |     1616 | 2024-05-27 | Falcons         | L   | 0.748      | -            | -                | -                | -         |    -2.11 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            7 |     1627 | 2024-05-27 | Vitality        | L   | 0.747      | -            | -                | -                | -         |    -0.21 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            6 |     1783 | 2024-05-21 | Sangal          | L   | 0.705      | -            | -                | -                | -         |    -8.72 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            5 |     1824 | 2024-05-20 | Sashi           | W   | 0.698      | 0.500        | 0.184 (0.064)    | 0.998 (0.348)    | -         |    16.22 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            4 |     1872 | 2024-05-18 | Sashi           | L   | 0.686      | -            | -                | -                | -         |    -5.41 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            3 |     1903 | 2024-05-17 | BLEED           | W   | 0.679      | 0.500        | 0.126 (0.043)    | 0.534 (0.181)    | -         |    19.21 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            2 |     1942 | 2024-05-16 | kONO            | W   | 0.672      | 0.384        | 0.028 (0.007)    | -                | -         |     6.94 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            1 |     1988 | 2024-05-15 | DMS             | W   | 0.666      | -            | -                | -                | -         |     8.66 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,162.66)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.880 | $5,000.00      | $4,398.84       |
| 2024-06-09 |      0.833 | $4,000.00      | $3,332.13       |
| 2024-06-02 |      0.787 | $4,000.00      | $3,147.96       |
| 2024-05-22 |      0.713 | $12,500.00     | $8,910.30       |
| 2024-05-18 |      0.687 | $2,000.00      | $1,373.43       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
