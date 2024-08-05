### Roster Details<br />
Team Name: ARCRED<br />
Roster: 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
<br />
Final Rank Value:  996.9<br />
<br />
Final Rank Value (996.9) = Starting Rank Value (913.7) + Head To Head Adjustments (83.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.419[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.183[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.251<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 913.7
- 400 + ( ( 0.251 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 913.7


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
|           26 |        0 | 2024-08-05 | Aurora          | W   | 1.000      | 0.500        | 0.422 (0.211)    | 0.779 (0.389)    | 0 (0.000) |    28.81 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           25 |       67 | 2024-08-03 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -17.77 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           24 |      109 | 2024-08-02 | Insilio         | W   | 1.000      | 0.342        | 0.023 (0.008)    | 0.553 (0.189)    | 0 (0.000) |    14.27 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           23 |      230 | 2024-07-30 | B8              | L   | 1.000      | -            | -                | -                | -         |    -8.47 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           22 |      262 | 2024-07-29 | PERA            | W   | 1.000      | 0.500        | 0.048 (0.024)    | 0.446 (0.223)    | 0 (0.000) |    15.28 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           21 |      752 | 2024-07-16 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -7.25 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           20 |     1029 | 2024-06-16 | RUBY            | L   | 0.865      | -            | -                | -                | -         |   -16.83 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           19 |     1051 | 2024-06-15 | EYEBALLERS      | W   | 0.860      | -            | -                | -                | 0 (0.000) |     9.93 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           18 |     1067 | 2024-06-15 | VP.Prodigy      | W   | 0.858      | 0.450        | 0.025 (0.010)    | 0.393 (0.152)    | 0 (0.000) |    10.77 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           17 |     1088 | 2024-06-14 | FAVBET          | W   | 0.853      | -            | -                | -                | 0 (0.000) |     9.01 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           16 |     1141 | 2024-06-13 | CYBERSHOKE      | W   | 0.845      | 0.450        | 0.039 (0.015)    | 0.346 (0.132)    | 0 (0.000) |    10.94 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           15 |     1195 | 2024-06-10 | Insilio         | L   | 0.827      | -            | -                | -                | -         |   -12.03 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           14 |     1502 | 2024-06-05 | RUBY            | W   | 0.792      | 0.372        | 0.095 (0.028)    | 0.492 (0.145)    | 0 (0.000) |    11.67 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           13 |     1574 | 2024-06-03 | DMS             | W   | 0.779      | 0.372        | -                | 0.438 (0.127)    | 0 (0.000) |    13.93 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           12 |     1621 | 2024-06-01 | Enterprise      | W   | 0.766      | 0.372        | 0.039 (0.011)    | 0.616 (0.176)    | 0 (0.000) |    11.71 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           11 |     1678 | 2024-05-30 | FAVBET          | W   | 0.754      | -            | -                | -                | -         |     7.93 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           10 |     2382 | 2024-05-05 | 9 Pandas        | L   | 0.584      | -            | -                | -                | -         |    -7.37 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            9 |     2563 | 2024-04-26 | Insilio         | W   | 0.526      | 0.396        | 0.023 (0.005)    | 0.553 (0.115)    | -         |     8.52 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            8 |     2573 | 2024-04-26 | Permitta        | W   | 0.525      | 0.396        | 0.024 (0.005)    | 0.863 (0.179)    | -         |     9.39 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            7 |     3660 | 2024-03-12 | The Chosen Few  | L   | 0.226      | -            | -                | -                | -         |    -5.60 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            6 |     3718 | 2024-03-09 | FORZE YNG       | W   | 0.207      | -            | -                | -                | -         |     0.35 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            5 |     3743 | 2024-03-08 | RUBY            | L   | 0.200      | -            | -                | -                | -         |    -3.05 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            4 |     3831 | 2024-03-05 | 1WIN            | W   | 0.181      | 0.372        | 0.033 (0.002)    | -                | -         |     2.98 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            3 |     3978 | 2024-02-27 | FORZE           | L   | 0.133      | -            | -                | -                | -         |    -2.26 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            2 |     4185 | 2024-02-18 | brazylijski luz | L   | 0.073      | -            | -                | -                | -         |    -1.52 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            1 |     4358 | 2024-02-11 | Sashi           | L   | 0.025      | -            | -                | -                | -         |    -0.16 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,209.24)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.865 | $10,000.00     | $8,652.78       |
| 2024-06-10 |      0.827 | $4,300.00      | $3,556.46       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
