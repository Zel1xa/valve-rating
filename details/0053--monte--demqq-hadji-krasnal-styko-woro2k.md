### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, hAdji, kRaSnaL, STYKO, Woro2k<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1005.0<br />
<br />
Final Rank Value (1005.0) = Starting Rank Value (943.3) + Head To Head Adjustments (61.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.472[<sup>1</sup>](#table2)
- Bounty Collected: 0.406[<sup>2</sup>](#table1)
- Opponent Network: 0.136[<sup>2</sup>](#table1)
- LAN Wins: 0.108[<sup>2</sup>](#table1)

The average of these factors is 0.281<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 943.3
- 400 + ( ( 0.281 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 943.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |     2174 | 2024-06-16 | B8                | L   | 0.639      | -            | -                | -                | -         |    -7.76 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           43 |     2199 | 2024-06-15 | BLEED             | W   | 0.634      | 0.435        | 0.101 (0.028)    | 0.541 (0.149)    | 0 (0.000) |    15.18 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           42 |     2252 | 2024-06-14 | BLEED             | L   | 0.626      | -            | -                | -                | -         |    -4.61 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           41 |     2275 | 2024-06-13 | Zero Tenacity     | W   | 0.620      | 0.435        | 0.163 (0.044)    | 1.000 (0.270)    | 0 (0.000) |    11.65 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           40 |     2311 | 2024-06-12 | FORZE Reload      | W   | 0.613      | -            | -                | -                | 0 (0.000) |     1.38 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           39 |     2352 | 2024-06-10 | SINNERS           | W   | 0.600      | 0.143        | -                | 1.000 (0.086)    | 0 (0.000) |    11.44 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           38 |     2358 | 2024-06-10 | Aurora            | L   | 0.600      | -            | -                | -                | -         |    -2.67 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           37 |     2364 | 2024-06-10 | RUSH B            | L   | 0.599      | -            | -                | -                | -         |   -11.76 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           36 |     2376 | 2024-06-09 | AMKAL             | L   | 0.595      | -            | -                | -                | -         |    -5.75 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           35 |     2387 | 2024-06-09 | Aurora            | W   | 0.594      | 0.143        | 0.290 (0.025)    | -                | 0 (0.000) |    16.19 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           34 |     2396 | 2024-06-09 | 3DMAX             | W   | 0.594      | 0.143        | 0.509 (0.043)    | 0.951 (0.081)    | 0 (0.000) |    18.06 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           33 |     2401 | 2024-06-09 | SAW               | L   | 0.593      | -            | -                | -                | -         |    -1.26 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           32 |     2411 | 2024-06-09 | PARIVISION        | L   | 0.593      | -            | -                | -                | -         |    -6.70 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           31 |     2419 | 2024-06-09 | 9 Pandas          | L   | 0.593      | -            | -                | -                | -         |    -7.33 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           30 |     2456 | 2024-06-08 | 1WIN              | W   | 0.588      | -            | -                | -                | 0 (0.000) |     7.82 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           29 |     2463 | 2024-06-08 | AMKAL             | L   | 0.587      | -            | -                | -                | -         |    -5.51 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           28 |     2475 | 2024-06-08 | Quixal            | W   | 0.586      | -            | -                | -                | -         |     0.70 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           27 |     2680 | 2024-06-04 | PARIVISION        | L   | 0.561      | -            | -                | -                | -         |    -6.63 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           26 |     2882 | 2024-05-27 | Falcons           | L   | 0.509      | -            | -                | -                | -         |    -0.82 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           25 |     2893 | 2024-05-27 | Vitality          | L   | 0.508      | -            | -                | -                | -         |    -0.09 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           24 |     3050 | 2024-05-21 | Sangal            | L   | 0.466      | -            | -                | -                | -         |    -2.53 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           23 |     3091 | 2024-05-20 | Sashi             | W   | 0.459      | 0.500        | 0.151 (0.035)    | 0.926 (0.212)    | -         |     9.87 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           22 |     3140 | 2024-05-18 | Sashi             | L   | 0.447      | -            | -                | -                | -         |    -4.46 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           21 |     3171 | 2024-05-17 | BLEED             | W   | 0.441      | 0.500        | 0.101 (0.022)    | 0.541 (0.119)    | -         |    11.04 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           20 |     3210 | 2024-05-16 | kONO              | W   | 0.433      | 0.384        | -                | 0.532 (0.089)    | -         |     4.75 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           19 |     3256 | 2024-05-15 | DMS               | W   | 0.427      | 0.500        | -                | 0.486 (0.104)    | -         |     5.28 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           18 |     3472 | 2024-05-07 | FaZe              | L   | 0.375      | -            | -                | -                | -         |    -0.14 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           17 |     3511 | 2024-05-05 | FURIA             | W   | 0.360      | 0.889        | 0.319 (0.102)    | 0.513 (0.164)    | 1 (0.360) |    11.06 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           16 |     3535 | 2024-05-04 | FORZE             | W   | 0.353      | 0.889        | 0.034 (0.011)    | -                | 1 (0.353) |     3.48 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           15 |     3565 | 2024-05-02 | ENCE              | L   | 0.341      | -            | -                | -                | -         |    -1.92 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           14 |     3588 | 2024-05-01 | Liquid            | L   | 0.335      | -            | -                | -                | -         |    -0.31 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           13 |     3612 | 2024-04-30 | FORZE             | W   | 0.328      | 0.889        | 0.034 (0.010)    | -                | 1 (0.328) |     3.18 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           12 |     3867 | 2024-04-19 | OG                | L   | 0.255      | -            | -                | -                | -         |    -3.78 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           11 |     3933 | 2024-04-18 | paiN              | L   | 0.247      | -            | -                | -                | -         |    -0.14 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           10 |     4054 | 2024-04-13 | Rebels            | W   | 0.214      | -            | -                | -                | -         |     3.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|            9 |     4068 | 2024-04-12 | Sangal            | W   | 0.207      | 0.500        | 0.248 (0.026)    | 0.878 (0.091)    | -         |     5.81 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|            8 |     4362 | 2024-04-03 | Metizport         | L   | 0.148      | -            | -                | -                | -         |    -3.47 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|            7 |     4372 | 2024-04-03 | Apeks             | W   | 0.147      | -            | -                | -                | -         |     1.23 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|            6 |     4400 | 2024-04-02 | GamerLegion       | W   | 0.141      | -            | -                | -                | -         |     2.96 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|            5 |     4409 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.140      | -            | -                | -                | -         |    -0.24 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|            4 |     4433 | 2024-03-31 | RUSH B            | L   | 0.128      | -            | -                | -                | -         |    -2.53 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|            3 |     4463 | 2024-03-28 | Betera            | L   | 0.108      | -            | -                | -                | -         |    -2.83 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|            2 |     4531 | 2024-03-26 | System5           | W   | 0.095      | -            | -                | -                | -         |     0.46 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|            1 |     4760 | 2024-03-13 | Qiang             | W   | 0.008      | -            | -                | -                | -         |     0.10 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,028.98)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.641 | $5,000.00      | $3,204.17       |
| 2024-06-09 |      0.594 | $4,000.00      | $2,376.39       |
| 2024-06-02 |      0.548 | $4,000.00      | $2,192.22       |
| 2024-05-22 |      0.474 | $12,500.00     | $5,923.61       |
| 2024-05-18 |      0.448 | $2,000.00      | $895.56         |
| 2024-05-12 |      0.407 | $17,500.00     | $7,126.39       |
| 2024-04-20 |      0.262 | $5,000.00      | $1,310.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
