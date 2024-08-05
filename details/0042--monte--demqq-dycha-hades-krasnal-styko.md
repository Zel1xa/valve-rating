### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, kRaSnaL, STYKO<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1106.3<br />
<br />
Final Rank Value (1106.3) = Starting Rank Value (1000.2) + Head To Head Adjustments (106.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.477[<sup>1</sup>](#table2)
- Bounty Collected: 0.443[<sup>2</sup>](#table1)
- Opponent Network: 0.244[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.291<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1000.2
- 400 + ( ( 0.291 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1000.2


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
|           36 |        6 | 2024-07-31 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.513 (0.257)    | 0 (0.000) |     4.56 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           35 |       89 | 2024-07-29 | 9INE            | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.487 (0.211)    | 0 (0.000) |    10.94 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           34 |      137 | 2024-07-28 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -9.99 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           33 |      145 | 2024-07-27 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.06 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           32 |      153 | 2024-07-27 | 9z              | W   | 1.000      | 0.435        | 0.408 (0.177)    | 0.625 (0.272)    | 0 (0.000) |    28.36 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           31 |      188 | 2024-07-26 | Space           | W   | 1.000      | 0.435        | -                | 0.406 (0.176)    | 0 (0.000) |     9.30 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           30 |      223 | 2024-07-25 | Endpoint        | W   | 1.000      | 0.435        | -                | 0.523 (0.227)    | 0 (0.000) |     7.37 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           29 |      243 | 2024-07-24 | Sashi           | L   | 1.000      | -            | -                | -                | -         |   -10.30 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           28 |      449 | 2024-07-18 | KOI             | W   | 1.000      | 0.500        | 0.059 (0.030)    | 0.382 (0.191)    | 0 (0.000) |    18.44 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           27 |      577 | 2024-07-16 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -13.67 | DemQQ, dycha, hades, kRaSnaL, STYKO  |
|           26 |      858 | 2024-06-16 | B8              | L   | 0.897      | -            | -                | -                | -         |   -10.68 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           25 |      883 | 2024-06-15 | BLEED           | W   | 0.892      | 0.435        | 0.127 (0.049)    | 0.512 (0.198)    | 0 (0.000) |    23.44 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           24 |      936 | 2024-06-14 | BLEED           | L   | 0.884      | -            | -                | -                | -         |    -4.07 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           23 |      959 | 2024-06-13 | Zero Tenacity   | W   | 0.878      | 0.435        | 0.138 (0.052)    | 1.000 (0.382)    | 0 (0.000) |    15.80 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           22 |      995 | 2024-06-12 | FORZE Reload    | W   | 0.870      | -            | -                | -                | 0 (0.000) |     1.66 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           21 |     1036 | 2024-06-10 | SINNERS         | W   | 0.858      | -            | -                | -                | -         |    12.84 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           20 |     1042 | 2024-06-10 | Aurora          | L   | 0.858      | -            | -                | -                | -         |    -2.94 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           19 |     1048 | 2024-06-10 | RUSH B          | L   | 0.857      | -            | -                | -                | -         |   -17.21 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           18 |     1060 | 2024-06-09 | AMKAL           | L   | 0.853      | -            | -                | -                | -         |    -7.29 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           17 |     1071 | 2024-06-09 | Aurora          | W   | 0.852      | 0.143        | 0.429 (0.052)    | -                | -         |    24.24 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           16 |     1080 | 2024-06-09 | 3DMAX           | W   | 0.852      | 0.143        | 0.499 (0.061)    | -                | -         |    24.73 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           15 |     1085 | 2024-06-09 | SAW             | L   | 0.851      | -            | -                | -                | -         |    -7.41 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           14 |     1095 | 2024-06-09 | PARIVISION      | L   | 0.851      | -            | -                | -                | -         |   -11.09 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           13 |     1103 | 2024-06-09 | 9 Pandas        | L   | 0.850      | -            | -                | -                | -         |   -11.68 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           12 |     1140 | 2024-06-08 | 1WIN            | W   | 0.846      | -            | -                | -                | -         |    11.02 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           11 |     1147 | 2024-06-08 | AMKAL           | L   | 0.845      | -            | -                | -                | -         |    -7.09 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           10 |     1159 | 2024-06-08 | Quixal          | W   | 0.844      | -            | -                | -                | -         |     0.78 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            9 |     1364 | 2024-06-04 | PARIVISION      | L   | 0.819      | -            | -                | -                | -         |   -11.32 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            8 |     1566 | 2024-05-27 | Falcons         | L   | 0.767      | -            | -                | -                | -         |    -2.08 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            7 |     1577 | 2024-05-27 | Vitality        | L   | 0.766      | -            | -                | -                | -         |    -0.23 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            6 |     1734 | 2024-05-21 | Sangal          | L   | 0.724      | -            | -                | -                | -         |    -8.97 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            5 |     1775 | 2024-05-20 | Sashi           | W   | 0.717      | 0.500        | 0.185 (0.066)    | 0.973 (0.349)    | -         |    16.39 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            4 |     1824 | 2024-05-18 | Sashi           | L   | 0.705      | -            | -                | -                | -         |    -5.80 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            3 |     1855 | 2024-05-17 | BLEED           | W   | 0.699      | 0.500        | 0.127 (0.044)    | 0.512 (0.179)    | -         |    19.62 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            2 |     1894 | 2024-05-16 | kONO            | W   | 0.691      | 0.384        | 0.029 (0.008)    | -                | -         |     6.83 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|            1 |     1940 | 2024-05-15 | DMS             | W   | 0.685      | -            | -                | -                | -         |     8.56 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,685.54)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.899 | $5,000.00      | $4,493.91       |
| 2024-06-09 |      0.852 | $4,000.00      | $3,408.19       |
| 2024-06-02 |      0.806 | $4,000.00      | $3,224.02       |
| 2024-05-22 |      0.732 | $12,500.00     | $9,147.97       |
| 2024-05-18 |      0.706 | $2,000.00      | $1,411.45       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
