### Roster Details<br />
Team Name: ARCRED<br />
Roster: 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
<br />
Final Rank Value:  998.3<br />
<br />
Final Rank Value (998.3) = Starting Rank Value (913.9) + Head To Head Adjustments (84.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.419[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.180[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 913.9
- 400 + ( ( 0.250 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 913.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |       11 | 2024-08-05 | Aurora          | W   | 1.000      | 0.500        | 0.421 (0.210)    | 0.759 (0.379)    | 0 (0.000) |    28.83 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           25 |       78 | 2024-08-03 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -17.42 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           24 |      120 | 2024-08-02 | Insilio         | W   | 1.000      | 0.342        | 0.023 (0.008)    | 0.539 (0.185)    | 0 (0.000) |    14.66 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           23 |      241 | 2024-07-30 | B8              | L   | 1.000      | -            | -                | -                | -         |    -8.46 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           22 |      273 | 2024-07-29 | PERA            | W   | 1.000      | 0.500        | 0.048 (0.024)    | 0.435 (0.218)    | 0 (0.000) |    15.25 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           21 |      763 | 2024-07-16 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -7.28 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           20 |     1040 | 2024-06-16 | RUBY            | L   | 0.860      | -            | -                | -                | -         |   -16.62 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           19 |     1062 | 2024-06-15 | EYEBALLERS      | W   | 0.855      | -            | -                | -                | 0 (0.000) |     9.99 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           18 |     1078 | 2024-06-15 | VP.Prodigy      | W   | 0.853      | 0.450        | 0.025 (0.010)    | 0.383 (0.147)    | 0 (0.000) |    10.73 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           17 |     1099 | 2024-06-14 | FAVBET          | W   | 0.848      | -            | -                | -                | 0 (0.000) |     8.97 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           16 |     1152 | 2024-06-13 | CYBERSHOKE      | W   | 0.840      | 0.450        | 0.039 (0.015)    | 0.339 (0.128)    | 0 (0.000) |    10.85 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           15 |     1206 | 2024-06-10 | Insilio         | L   | 0.822      | -            | -                | -                | -         |   -11.92 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           14 |     1513 | 2024-06-05 | RUBY            | W   | 0.787      | 0.372        | 0.095 (0.028)    | 0.480 (0.141)    | 0 (0.000) |    11.73 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           13 |     1585 | 2024-06-03 | DMS             | W   | 0.774      | 0.372        | -                | 0.428 (0.123)    | 0 (0.000) |    13.81 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           12 |     1632 | 2024-06-01 | Enterprise      | W   | 0.761      | 0.372        | 0.039 (0.011)    | 0.641 (0.182)    | 0 (0.000) |    11.67 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           11 |     1689 | 2024-05-30 | FAVBET          | W   | 0.749      | -            | -                | -                | -         |     7.89 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           10 |     2393 | 2024-05-05 | 9 Pandas        | L   | 0.579      | -            | -                | -                | -         |    -7.35 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            9 |     2574 | 2024-04-26 | Insilio         | W   | 0.521      | 0.396        | 0.023 (0.005)    | 0.539 (0.111)    | -         |     8.46 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            8 |     2584 | 2024-04-26 | Permitta        | W   | 0.520      | 0.396        | 0.023 (0.005)    | 0.919 (0.189)    | -         |     9.51 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            7 |     3671 | 2024-03-12 | The Chosen Few  | L   | 0.221      | -            | -                | -                | -         |    -5.48 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            6 |     3729 | 2024-03-09 | FORZE YNG       | W   | 0.202      | -            | -                | -                | -         |     0.34 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            5 |     3754 | 2024-03-08 | RUBY            | L   | 0.195      | -            | -                | -                | -         |    -2.92 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            4 |     3842 | 2024-03-05 | 1WIN            | W   | 0.176      | 0.372        | 0.033 (0.002)    | -                | -         |     2.91 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            3 |     3989 | 2024-02-27 | FORZE           | L   | 0.128      | -            | -                | -                | -         |    -2.18 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            2 |     4196 | 2024-02-18 | brazylijski luz | L   | 0.068      | -            | -                | -                | -         |    -1.42 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            1 |     4369 | 2024-02-11 | Sashi           | L   | 0.020      | -            | -                | -                | -         |    -0.13 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,137.74)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.860 | $10,000.00     | $8,602.78       |
| 2024-06-10 |      0.822 | $4,300.00      | $3,534.96       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />