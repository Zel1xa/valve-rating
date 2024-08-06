### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, kRaSnaL, STYKO<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1103.2<br />
<br />
Final Rank Value (1103.2) = Starting Rank Value (994.8) + Head To Head Adjustments (108.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.477[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.243[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 994.8
- 400 + ( ( 0.290 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 994.8


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
|           36 |      187 | 2024-07-31 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.499 (0.249)    | 0 (0.000) |     4.80 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           35 |      270 | 2024-07-29 | 9INE            | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.534 (0.232)    | 0 (0.000) |    11.07 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           34 |      318 | 2024-07-28 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -9.73 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           33 |      326 | 2024-07-27 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.46 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           32 |      334 | 2024-07-27 | 9z              | W   | 1.000      | 0.435        | 0.404 (0.176)    | 0.604 (0.263)    | 0 (0.000) |    28.22 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           31 |      369 | 2024-07-26 | Space           | W   | 1.000      | 0.435        | -                | 0.439 (0.191)    | 0 (0.000) |     9.50 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           30 |      404 | 2024-07-25 | Endpoint        | W   | 1.000      | 0.435        | -                | 0.513 (0.223)    | 0 (0.000) |     7.54 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           29 |      424 | 2024-07-24 | Sashi           | L   | 1.000      | -            | -                | -                | -         |   -10.35 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           28 |      630 | 2024-07-18 | KOI             | W   | 1.000      | 0.500        | 0.058 (0.029)    | 0.365 (0.182)    | 0 (0.000) |    17.98 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           27 |      758 | 2024-07-16 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -13.50 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           26 |     1039 | 2024-06-16 | B8              | L   | 0.860      | -            | -                | -                | -         |   -10.29 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           25 |     1064 | 2024-06-15 | BLEED           | W   | 0.855      | 0.435        | 0.126 (0.047)    | 0.550 (0.204)    | 0 (0.000) |    22.51 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           24 |     1117 | 2024-06-14 | BLEED           | L   | 0.847      | -            | -                | -                | -         |    -3.90 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           23 |     1140 | 2024-06-13 | Zero Tenacity   | W   | 0.841      | 0.435        | 0.143 (0.052)    | 1.000 (0.366)    | 0 (0.000) |    15.27 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           22 |     1176 | 2024-06-12 | FORZE Reload    | W   | 0.833      | -            | -                | -                | 0 (0.000) |     1.61 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           21 |     1217 | 2024-06-10 | SINNERS         | W   | 0.821      | -            | -                | -                | -         |    13.72 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           20 |     1223 | 2024-06-10 | Aurora          | L   | 0.820      | -            | -                | -                | -         |    -2.67 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           19 |     1229 | 2024-06-10 | RUSH B          | L   | 0.820      | -            | -                | -                | -         |   -16.02 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           18 |     1241 | 2024-06-09 | AMKAL           | L   | 0.816      | -            | -                | -                | -         |    -7.12 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           17 |     1252 | 2024-06-09 | Aurora          | W   | 0.815      | 0.143        | 0.421 (0.049)    | -                | -         |    23.32 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           16 |     1261 | 2024-06-09 | 3DMAX           | W   | 0.815      | 0.143        | 0.509 (0.059)    | -                | -         |    23.79 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           15 |     1266 | 2024-06-09 | SAW             | L   | 0.814      | -            | -                | -                | -         |    -7.47 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           14 |     1276 | 2024-06-09 | PARIVISION      | L   | 0.814      | -            | -                | -                | -         |   -10.12 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           13 |     1284 | 2024-06-09 | 9 Pandas        | L   | 0.813      | -            | -                | -                | -         |   -11.23 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           12 |     1321 | 2024-06-08 | 1WIN            | W   | 0.808      | -            | -                | -                | -         |    11.53 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           11 |     1328 | 2024-06-08 | AMKAL           | L   | 0.808      | -            | -                | -                | -         |    -6.91 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           10 |     1340 | 2024-06-08 | Quixal          | W   | 0.807      | -            | -                | -                | -         |     0.77 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            9 |     1545 | 2024-06-04 | PARIVISION      | L   | 0.782      | -            | -                | -                | -         |   -10.21 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            8 |     1747 | 2024-05-27 | Falcons         | L   | 0.730      | -            | -                | -                | -         |    -2.29 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            7 |     1758 | 2024-05-27 | Vitality        | L   | 0.729      | -            | -                | -                | -         |    -0.22 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            6 |     1915 | 2024-05-21 | Sangal          | L   | 0.687      | -            | -                | -                | -         |    -7.92 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            5 |     1956 | 2024-05-20 | Sashi           | W   | 0.680      | 0.500        | 0.184 (0.062)    | 0.980 (0.333)    | -         |    15.53 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            4 |     2005 | 2024-05-18 | Sashi           | L   | 0.667      | -            | -                | -                | -         |    -5.55 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            3 |     2036 | 2024-05-17 | BLEED           | W   | 0.661      | 0.500        | 0.126 (0.042)    | 0.550 (0.182)    | -         |    18.58 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            2 |     2075 | 2024-05-16 | kONO            | W   | 0.654      | 0.384        | 0.028 (0.007)    | -                | -         |     6.50 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            1 |     2121 | 2024-05-15 | DMS             | W   | 0.648      | -            | -                | -                | -         |     8.17 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,664.86)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.862 | $5,000.00      | $4,308.33       |
| 2024-06-09 |      0.815 | $4,000.00      | $3,259.72       |
| 2024-06-02 |      0.769 | $4,000.00      | $3,075.56       |
| 2024-05-22 |      0.695 | $12,500.00     | $8,684.03       |
| 2024-05-18 |      0.669 | $2,000.00      | $1,337.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
