### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, kRaSnaL, STYKO<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1102.7<br />
<br />
Final Rank Value (1102.7) = Starting Rank Value (993.8) + Head To Head Adjustments (108.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.477[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.238[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 993.8
- 400 + ( ( 0.289 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 993.8


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
|           36 |      191 | 2024-07-31 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |     4.80 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           35 |      274 | 2024-07-29 | 9INE            | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.523 (0.227)    | 0 (0.000) |    11.09 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           34 |      322 | 2024-07-28 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -9.72 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           33 |      330 | 2024-07-27 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.47 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           32 |      338 | 2024-07-27 | 9z              | W   | 1.000      | 0.435        | 0.404 (0.175)    | 0.591 (0.257)    | 0 (0.000) |    28.21 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           31 |      373 | 2024-07-26 | Space           | W   | 1.000      | 0.435        | -                | 0.429 (0.187)    | 0 (0.000) |     9.51 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           30 |      408 | 2024-07-25 | Endpoint        | W   | 1.000      | 0.435        | -                | 0.502 (0.218)    | 0 (0.000) |     7.55 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           29 |      428 | 2024-07-24 | Sashi           | L   | 1.000      | -            | -                | -                | -         |   -10.33 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           28 |      634 | 2024-07-18 | KOI             | W   | 1.000      | 0.500        | 0.058 (0.029)    | 0.357 (0.178)    | 0 (0.000) |    17.98 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           27 |      762 | 2024-07-16 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -13.48 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           26 |     1043 | 2024-06-16 | B8              | L   | 0.860      | -            | -                | -                | -         |   -10.24 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           25 |     1068 | 2024-06-15 | BLEED           | W   | 0.854      | 0.435        | 0.126 (0.047)    | 0.538 (0.200)    | 0 (0.000) |    22.51 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           24 |     1121 | 2024-06-14 | BLEED           | L   | 0.846      | -            | -                | -                | -         |    -3.89 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           23 |     1144 | 2024-06-13 | Zero Tenacity   | W   | 0.841      | 0.435        | 0.143 (0.052)    | 1.000 (0.365)    | 0 (0.000) |    15.28 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           22 |     1180 | 2024-06-12 | FORZE Reload    | W   | 0.833      | -            | -                | -                | 0 (0.000) |     1.62 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           21 |     1221 | 2024-06-10 | SINNERS         | W   | 0.821      | -            | -                | -                | -         |    13.74 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           20 |     1227 | 2024-06-10 | Aurora          | L   | 0.820      | -            | -                | -                | -         |    -2.64 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           19 |     1233 | 2024-06-10 | RUSH B          | L   | 0.820      | -            | -                | -                | -         |   -15.99 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           18 |     1245 | 2024-06-09 | AMKAL           | L   | 0.815      | -            | -                | -                | -         |    -7.12 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           17 |     1256 | 2024-06-09 | Aurora          | W   | 0.815      | 0.143        | 0.421 (0.049)    | -                | -         |    23.34 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           16 |     1265 | 2024-06-09 | 3DMAX           | W   | 0.814      | 0.143        | 0.510 (0.059)    | -                | -         |    23.79 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           15 |     1270 | 2024-06-09 | SAW             | L   | 0.814      | -            | -                | -                | -         |    -7.46 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           14 |     1280 | 2024-06-09 | PARIVISION      | L   | 0.813      | -            | -                | -                | -         |   -10.07 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           13 |     1288 | 2024-06-09 | 9 Pandas        | L   | 0.813      | -            | -                | -                | -         |   -11.22 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           12 |     1325 | 2024-06-08 | 1WIN            | W   | 0.808      | -            | -                | -                | -         |    11.53 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           11 |     1332 | 2024-06-08 | AMKAL           | L   | 0.808      | -            | -                | -                | -         |    -6.90 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           10 |     1344 | 2024-06-08 | Quixal          | W   | 0.807      | -            | -                | -                | -         |     0.78 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            9 |     1549 | 2024-06-04 | PARIVISION      | L   | 0.782      | -            | -                | -                | -         |   -10.15 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            8 |     1751 | 2024-05-27 | Falcons         | L   | 0.730      | -            | -                | -                | -         |    -2.28 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            7 |     1762 | 2024-05-27 | Vitality        | L   | 0.728      | -            | -                | -                | -         |    -0.22 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            6 |     1919 | 2024-05-21 | Sangal          | L   | 0.687      | -            | -                | -                | -         |    -7.90 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            5 |     1960 | 2024-05-20 | Sashi           | W   | 0.679      | 0.500        | 0.184 (0.062)    | 0.958 (0.326)    | -         |    15.54 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            4 |     2009 | 2024-05-18 | Sashi           | L   | 0.667      | -            | -                | -                | -         |    -5.53 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            3 |     2040 | 2024-05-17 | BLEED           | W   | 0.661      | 0.500        | 0.126 (0.042)    | 0.538 (0.178)    | -         |    18.59 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            2 |     2079 | 2024-05-16 | kONO            | W   | 0.654      | 0.384        | 0.028 (0.007)    | -                | -         |     6.52 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            1 |     2125 | 2024-05-15 | DMS             | W   | 0.648      | -            | -                | -                | -         |     8.18 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,657.22)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.861 | $5,000.00      | $4,306.94       |
| 2024-06-09 |      0.815 | $4,000.00      | $3,258.61       |
| 2024-06-02 |      0.769 | $4,000.00      | $3,074.44       |
| 2024-05-22 |      0.694 | $12,500.00     | $8,680.56       |
| 2024-05-18 |      0.668 | $2,000.00      | $1,336.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
