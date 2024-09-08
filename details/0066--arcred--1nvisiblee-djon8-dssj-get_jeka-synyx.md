### Roster Details<br />
Team Name: ARCRED<br />
Roster: 1NVISIBLEE, Djon8, DSSj, Get_Jeka, synyx<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  953.3<br />
<br />
Final Rank Value (953.3) = Starting Rank Value (886.7) + Head To Head Adjustments (66.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.409[<sup>1</sup>](#table2)
- Bounty Collected: 0.384[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.251<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 886.7
- 400 + ( ( 0.251 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 886.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      216 | 2024-08-31 | Revenant       | W   | 1.000      | 0.384        | 0.042 (0.016)    | 0.666 (0.256)    | 0 (0.000) |    15.09 | 1NVISIBLEE, Djon8, DSSj, Get_Jeka, synyx |
|           29 |      564 | 2024-08-23 | Sashi          | L   | 1.000      | -            | -                | -                | -         |   -10.22 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           28 |      595 | 2024-08-22 | Passion UA     | L   | 1.000      | -            | -                | -                | -         |   -10.41 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           27 |      629 | 2024-08-21 | Johnny Speeds  | W   | 1.000      | 0.143        | 0.102 (0.015)    | 0.956 (0.137)    | 0 (0.000) |    21.22 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           26 |      664 | 2024-08-21 | Nemiga         | L   | 1.000      | -            | -                | -                | -         |    -5.16 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           25 |      685 | 2024-08-20 | SINNERS        | L   | 1.000      | -            | -                | -                | -         |   -10.22 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           24 |      819 | 2024-08-15 | OG             | L   | 1.000      | -            | -                | -                | -         |   -16.12 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           23 |      876 | 2024-08-13 | Monte          | W   | 1.000      | 0.500        | 0.023 (0.012)    | 0.697 (0.349)    | 0 (0.000) |    17.10 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           22 |      923 | 2024-08-12 | RUSH B         | L   | 1.000      | -            | -                | -                | -         |   -17.24 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           21 |     1112 | 2024-08-06 | Space          | W   | 0.981      | 0.500        | -                | 0.463 (0.227)    | 0 (0.000) |     9.07 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           20 |     1139 | 2024-08-05 | Aurora         | W   | 0.974      | 0.500        | 0.290 (0.141)    | 0.603 (0.294)    | 0 (0.000) |    27.27 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           19 |     1206 | 2024-08-03 | BC.Game        | L   | 0.960      | -            | -                | -                | -         |   -15.86 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           18 |     1248 | 2024-08-02 | Insilio        | W   | 0.953      | 0.342        | 0.023 (0.008)    | 0.654 (0.213)    | 0 (0.000) |    13.83 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           17 |     1369 | 2024-07-30 | B8             | L   | 0.934      | -            | -                | -                | -         |    -8.16 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           16 |     1401 | 2024-07-29 | Qiang          | W   | 0.928      | 0.500        | 0.036 (0.017)    | 0.389 (0.180)    | 0 (0.000) |    13.31 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           15 |     1893 | 2024-07-16 | Nemiga         | L   | 0.841      | -            | -                | -                | -         |    -5.64 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           14 |     2171 | 2024-06-16 | RUBY           | L   | 0.640      | -            | -                | -                | -         |   -12.34 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           13 |     2193 | 2024-06-15 | EYEBALLERS     | W   | 0.634      | -            | -                | -                | 0 (0.000) |     6.99 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           12 |     2209 | 2024-06-15 | VP.Prodigy     | W   | 0.633      | 0.450        | 0.020 (0.006)    | -                | 0 (0.000) |     7.85 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           11 |     2230 | 2024-06-14 | FAVBET         | W   | 0.628      | -            | -                | -                | 0 (0.000) |     7.34 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           10 |     2283 | 2024-06-13 | CYBERSHOKE     | W   | 0.619      | 0.450        | 0.043 (0.012)    | 0.702 (0.196)    | -         |     9.80 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|            9 |     2337 | 2024-06-10 | Insilio        | L   | 0.602      | -            | -                | -                | -         |    -8.96 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|            8 |     2644 | 2024-06-05 | RUBY           | W   | 0.567      | 0.372        | 0.073 (0.015)    | -                | -         |     8.09 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|            7 |     2716 | 2024-06-03 | DMS            | W   | 0.554      | -            | -                | -                | -         |     9.16 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|            6 |     2763 | 2024-06-01 | Enterprise     | W   | 0.541      | 0.372        | 0.039 (0.008)    | 0.697 (0.140)    | -         |     8.10 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|            5 |     2820 | 2024-05-30 | FAVBET         | W   | 0.528      | 0.372        | -                | 0.655 (0.129)    | -         |     6.20 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|            4 |     3524 | 2024-05-05 | 9 Pandas       | L   | 0.359      | -            | -                | -                | -         |    -3.83 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|            3 |     3705 | 2024-04-26 | Insilio        | W   | 0.301      | -            | -                | -                | -         |     4.95 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|            2 |     3715 | 2024-04-26 | Permitta       | W   | 0.299      | -            | -                | -                | -         |     5.41 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|            1 |     4802 | 2024-03-12 | The Chosen Few | L   | 0.001      | -            | -                | -                | -         |    -0.02 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,950.18)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-06 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-08-04 |      0.966 | $1,000.00      | $966.39         |
| 2024-06-16 |      0.640 | $10,000.00     | $6,397.22       |
| 2024-06-10 |      0.602 | $4,300.00      | $2,586.57       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
