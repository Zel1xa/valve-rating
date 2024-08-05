### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, kRaSnaL, STYKO<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1102.2<br />
<br />
Final Rank Value (1102.2) = Starting Rank Value (993.6) + Head To Head Adjustments (108.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.477[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.241[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 993.6
- 400 + ( ( 0.289 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 993.6


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
|           36 |      181 | 2024-07-31 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |     4.76 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           35 |      264 | 2024-07-29 | 9INE            | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.533 (0.232)    | 0 (0.000) |    11.08 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           34 |      312 | 2024-07-28 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -9.72 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           33 |      320 | 2024-07-27 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.46 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           32 |      328 | 2024-07-27 | 9z              | W   | 1.000      | 0.435        | 0.404 (0.176)    | 0.607 (0.264)    | 0 (0.000) |    28.24 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           31 |      363 | 2024-07-26 | Space           | W   | 1.000      | 0.435        | -                | 0.439 (0.191)    | 0 (0.000) |     9.35 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           30 |      398 | 2024-07-25 | Endpoint        | W   | 1.000      | 0.435        | -                | 0.514 (0.223)    | 0 (0.000) |     7.38 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           29 |      418 | 2024-07-24 | Sashi           | L   | 1.000      | -            | -                | -                | -         |   -10.32 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           28 |      624 | 2024-07-18 | KOI             | W   | 1.000      | 0.500        | 0.058 (0.029)    | 0.367 (0.183)    | 0 (0.000) |    18.06 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           27 |      752 | 2024-07-16 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -13.56 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           26 |     1033 | 2024-06-16 | B8              | L   | 0.864      | -            | -                | -                | -         |   -10.32 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           25 |     1058 | 2024-06-15 | BLEED           | W   | 0.859      | 0.435        | 0.126 (0.047)    | 0.511 (0.191)    | 0 (0.000) |    22.63 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           24 |     1111 | 2024-06-14 | BLEED           | L   | 0.851      | -            | -                | -                | -         |    -3.91 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           23 |     1134 | 2024-06-13 | Zero Tenacity   | W   | 0.845      | 0.435        | 0.143 (0.053)    | 1.000 (0.367)    | 0 (0.000) |    15.29 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           22 |     1170 | 2024-06-12 | FORZE Reload    | W   | 0.838      | -            | -                | -                | 0 (0.000) |     1.62 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           21 |     1211 | 2024-06-10 | SINNERS         | W   | 0.825      | -            | -                | -                | -         |    13.80 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           20 |     1217 | 2024-06-10 | Aurora          | L   | 0.825      | -            | -                | -                | -         |    -2.71 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           19 |     1223 | 2024-06-10 | RUSH B          | L   | 0.824      | -            | -                | -                | -         |   -16.06 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           18 |     1235 | 2024-06-09 | AMKAL           | L   | 0.820      | -            | -                | -                | -         |    -7.16 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           17 |     1246 | 2024-06-09 | Aurora          | W   | 0.819      | 0.143        | 0.422 (0.049)    | -                | -         |    23.42 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           16 |     1255 | 2024-06-09 | 3DMAX           | W   | 0.819      | 0.143        | 0.508 (0.059)    | -                | -         |    23.89 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           15 |     1260 | 2024-06-09 | SAW             | L   | 0.818      | -            | -                | -                | -         |    -7.43 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           14 |     1270 | 2024-06-09 | PARIVISION      | L   | 0.818      | -            | -                | -                | -         |   -10.19 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           13 |     1278 | 2024-06-09 | 9 Pandas        | L   | 0.818      | -            | -                | -                | -         |   -11.24 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           12 |     1315 | 2024-06-08 | 1WIN            | W   | 0.813      | -            | -                | -                | -         |    11.60 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           11 |     1322 | 2024-06-08 | AMKAL           | L   | 0.812      | -            | -                | -                | -         |    -6.94 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           10 |     1334 | 2024-06-08 | Quixal          | W   | 0.812      | -            | -                | -                | -         |     0.78 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            9 |     1539 | 2024-06-04 | PARIVISION      | L   | 0.786      | -            | -                | -                | -         |   -10.28 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            8 |     1741 | 2024-05-27 | Falcons         | L   | 0.734      | -            | -                | -                | -         |    -2.28 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            7 |     1752 | 2024-05-27 | Vitality        | L   | 0.733      | -            | -                | -                | -         |    -0.22 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            6 |     1909 | 2024-05-21 | Sangal          | L   | 0.692      | -            | -                | -                | -         |    -7.99 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            5 |     1950 | 2024-05-20 | Sashi           | W   | 0.684      | 0.500        | 0.184 (0.063)    | 0.983 (0.336)    | -         |    15.65 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            4 |     1999 | 2024-05-18 | Sashi           | L   | 0.672      | -            | -                | -                | -         |    -5.56 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            3 |     2030 | 2024-05-17 | BLEED           | W   | 0.666      | 0.500        | 0.126 (0.042)    | 0.511 (0.170)    | -         |    18.71 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            2 |     2069 | 2024-05-16 | kONO            | W   | 0.658      | 0.384        | 0.028 (0.007)    | -                | -         |     6.49 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            1 |     2115 | 2024-05-15 | DMS             | W   | 0.652      | -            | -                | -                | -         |     8.26 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,783.26)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.866 | $5,000.00      | $4,329.86       |
| 2024-06-09 |      0.819 | $4,000.00      | $3,276.94       |
| 2024-06-02 |      0.773 | $4,000.00      | $3,092.78       |
| 2024-05-22 |      0.699 | $12,500.00     | $8,737.85       |
| 2024-05-18 |      0.673 | $2,000.00      | $1,345.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
