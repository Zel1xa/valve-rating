### Roster Details<br />
Team Name: ARCRED<br />
Roster: 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  944.5<br />
<br />
Final Rank Value (944.5) = Starting Rank Value (862.0) + Head To Head Adjustments (82.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.414[<sup>1</sup>](#table2)
- Bounty Collected: 0.336[<sup>2</sup>](#table1)
- Opponent Network: 0.147[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.224<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 862.0
- 400 + ( ( 0.224 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 862.0


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
|           24 |       56 | 2024-07-30 | B8              | L   | 1.000      | -            | -                | -                | -         |    -7.42 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           23 |       88 | 2024-07-29 | PERA            | W   | 1.000      | 0.500        | 0.048 (0.024)    | 0.452 (0.226)    | 0 (0.000) |    16.68 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           22 |      578 | 2024-07-16 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -6.44 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           21 |      855 | 2024-06-16 | RUBY            | L   | 0.898      | -            | -                | -                | -         |   -16.28 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           20 |      877 | 2024-06-15 | EYEBALLERS      | W   | 0.892      | 0.143        | -                | 0.513 (0.065)    | 0 (0.000) |    11.66 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           19 |      893 | 2024-06-15 | VP.Prodigy      | W   | 0.891      | 0.450        | 0.026 (0.010)    | 0.406 (0.163)    | 0 (0.000) |    12.50 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           18 |      914 | 2024-06-14 | FAVBET          | W   | 0.886      | -            | -                | -                | 0 (0.000) |    10.73 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           17 |      967 | 2024-06-13 | CYBERSHOKE      | W   | 0.877      | 0.450        | 0.039 (0.016)    | 0.347 (0.137)    | 0 (0.000) |    12.85 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           16 |     1021 | 2024-06-10 | Insilio         | L   | 0.859      | -            | -                | -                | -         |   -10.91 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           15 |     1328 | 2024-06-05 | RUBY            | W   | 0.825      | 0.372        | 0.096 (0.029)    | 0.506 (0.156)    | 0 (0.000) |    13.72 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           14 |     1400 | 2024-06-03 | DMS             | W   | 0.812      | 0.372        | 0.003 (0.001)    | 0.447 (0.135)    | 0 (0.000) |    16.13 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           13 |     1447 | 2024-06-01 | Enterprise      | W   | 0.799      | 0.372        | 0.040 (0.012)    | 0.622 (0.185)    | 0 (0.000) |    13.82 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           12 |     1504 | 2024-05-30 | FAVBET          | W   | 0.786      | 0.372        | 0.003 (0.001)    | 0.344 (0.101)    | 0 (0.000) |     9.90 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           11 |     2208 | 2024-05-05 | 9 Pandas        | L   | 0.617      | -            | -                | -                | -         |    -6.36 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           10 |     2389 | 2024-04-26 | Insilio         | W   | 0.559      | 0.396        | 0.023 (0.005)    | 0.554 (0.123)    | 0 (0.000) |    10.38 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            9 |     2399 | 2024-04-26 | Permitta        | W   | 0.557      | 0.396        | 0.024 (0.005)    | 0.799 (0.176)    | -         |    10.95 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            8 |     3486 | 2024-03-12 | The Chosen Few  | L   | 0.259      | -            | -                | -                | -         |    -5.91 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            7 |     3544 | 2024-03-09 | FORZE YNG       | W   | 0.239      | -            | -                | -                | -         |     0.54 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            6 |     3569 | 2024-03-08 | RUBY            | L   | 0.232      | -            | -                | -                | -         |    -2.89 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            5 |     3657 | 2024-03-05 | 1WIN            | W   | 0.213      | 0.372        | 0.027 (0.002)    | -                | -         |     3.68 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            4 |     3804 | 2024-02-27 | FORZE           | L   | 0.166      | -            | -                | -                | -         |    -2.33 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            3 |     4011 | 2024-02-18 | brazylijski luz | L   | 0.105      | -            | -                | -                | -         |    -1.95 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            2 |     4184 | 2024-02-11 | Sashi           | L   | 0.058      | -            | -                | -                | -         |    -0.27 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            1 |     4273 | 2024-02-04 | Portugal        | L   | 0.011      | -            | -                | -                | -         |    -0.25 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,672.46)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.898 | $10,000.00     | $8,976.71       |
| 2024-06-10 |      0.859 | $4,300.00      | $3,695.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
