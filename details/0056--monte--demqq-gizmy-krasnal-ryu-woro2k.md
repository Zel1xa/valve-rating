### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1020.2<br />
<br />
Final Rank Value (1020.2) = Starting Rank Value (985.7) + Head To Head Adjustments (34.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.446[<sup>1</sup>](#table2)
- Bounty Collected: 0.398[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.286<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 985.7
- 400 + ( ( 0.286 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 985.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |     2333 | 2024-05-07 | FaZe              | L   | 0.598      | -            | -                | -                | -         |    -0.36 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2372 | 2024-05-05 | FURIA             | W   | 0.584      | 0.889        | 0.284 (0.147)    | 0.480 (0.249)    | 1 (0.584) |    17.85 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2396 | 2024-05-04 | FORZE             | W   | 0.576      | 0.889        | 0.058 (0.030)    | 0.169 (0.087)    | 1 (0.576) |     7.54 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2426 | 2024-05-02 | ENCE              | L   | 0.565      | -            | -                | -                | -         |    -1.61 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2449 | 2024-05-01 | Liquid            | L   | 0.558      | -            | -                | -                | -         |    -0.61 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2473 | 2024-04-30 | FORZE             | W   | 0.551      | 0.889        | 0.058 (0.028)    | 0.169 (0.083)    | 1 (0.551) |     7.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2728 | 2024-04-19 | OG                | L   | 0.478      | -            | -                | -                | -         |    -6.40 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     2794 | 2024-04-18 | paiN              | L   | 0.471      | -            | -                | -                | -         |    -1.41 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     2915 | 2024-04-13 | Rebels            | W   | 0.437      | 0.500        | 0.038 (0.008)    | 0.591 (0.129)    | 0 (0.000) |     7.03 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     2929 | 2024-04-12 | Sangal            | W   | 0.431      | 0.500        | 0.219 (0.047)    | 0.866 (0.186)    | 0 (0.000) |     9.46 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3223 | 2024-04-03 | Metizport         | L   | 0.371      | -            | -                | -                | -         |    -7.73 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3233 | 2024-04-03 | Apeks             | W   | 0.370      | -            | -                | -                | 0 (0.000) |     4.54 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3261 | 2024-04-02 | GamerLegion       | W   | 0.365      | 0.143        | 0.173 (0.009)    | 0.266 (0.014)    | 0 (0.000) |     7.97 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3270 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.363      | -            | -                | -                | -         |    -0.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3294 | 2024-03-31 | RUSH B            | L   | 0.351      | -            | -                | -                | -         |    -7.30 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3324 | 2024-03-28 | Betera            | L   | 0.331      | -            | -                | -                | -         |    -8.73 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           16 |     3392 | 2024-03-26 | System5           | W   | 0.318      | 0.500        | -                | 0.083 (0.013)    | 0 (0.000) |     1.47 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           15 |     3621 | 2024-03-13 | PERA              | W   | 0.232      | 0.500        | 0.048 (0.006)    | 0.445 (0.052)    | 0 (0.000) |     2.97 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           14 |     3724 | 2024-03-09 | Metizport         | L   | 0.204      | -            | -                | -                | -         |    -4.49 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           13 |     3764 | 2024-03-07 | Imperial          | W   | 0.192      | 0.535        | 0.234 (0.024)    | 0.674 (0.069)    | -         |     4.99 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           12 |     3836 | 2024-03-05 | SAW               | L   | 0.178      | -            | -                | -                | -         |    -1.54 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           11 |     3901 | 2024-03-03 | Gaimin Gladiators | L   | 0.163      | -            | -                | -                | -         |    -2.76 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           10 |     3906 | 2024-03-02 | 3DMAX             | L   | 0.158      | -            | -                | -                | -         |    -0.10 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            9 |     3949 | 2024-02-29 | PARIVISION        | W   | 0.143      | 0.500        | -                | 0.565 (0.040)    | -         |     2.99 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            8 |     4117 | 2024-02-21 | Astralis          | L   | 0.089      | -            | -                | -                | -         |    -0.04 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            7 |     4147 | 2024-02-20 | Apeks             | L   | 0.083      | -            | -                | -                | -         |    -1.63 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            6 |     4162 | 2024-02-19 | Nexus             | W   | 0.078      | -            | -                | -                | 1 (0.078) |     0.73 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            5 |     4171 | 2024-02-19 | Gaimin Gladiators | L   | 0.076      | -            | -                | -                | -         |    -1.32 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            4 |     4181 | 2024-02-18 | Aurora            | W   | 0.072      | 0.143        | 0.421 (0.004)    | -                | -         |     2.22 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4187 | 2024-02-18 | SINNERS           | W   | 0.071      | -            | -                | -                | -         |     1.59 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4212 | 2024-02-17 | Aurora            | W   | 0.064      | 0.143        | 0.421 (0.004)    | -                | -         |     1.98 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4217 | 2024-02-17 | The Chosen Few    | W   | 0.063      | -            | -                | -                | -         |     0.29 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,319.78)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.817 | $4,000.00      | $3,269.72       |
| 2024-05-12 |      0.631 | $17,500.00     | $11,034.72      |
| 2024-04-20 |      0.485 | $5,000.00      | $2,427.31       |
| 2024-03-10 |      0.212 | $7,500.00      | $1,588.02       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
