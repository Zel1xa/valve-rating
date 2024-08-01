### Roster Details<br />
Team Name: ARCRED<br />
Roster: 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  943.0<br />
<br />
Final Rank Value (943.0) = Starting Rank Value (861.3) + Head To Head Adjustments (81.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.414[<sup>1</sup>](#table2)
- Bounty Collected: 0.336[<sup>2</sup>](#table1)
- Opponent Network: 0.147[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.224<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 861.3
- 400 + ( ( 0.224 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 861.3


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
|           24 |       91 | 2024-07-30 | B8              | L   | 1.000      | -            | -                | -                | -         |    -7.86 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           23 |      123 | 2024-07-29 | PERA            | W   | 1.000      | 0.500        | 0.048 (0.024)    | 0.452 (0.226)    | 0 (0.000) |    16.67 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           22 |      624 | 2024-07-16 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -6.76 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           21 |      905 | 2024-06-16 | RUBY            | L   | 0.892      | -            | -                | -                | -         |   -16.15 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           20 |      926 | 2024-06-15 | EYEBALLERS      | W   | 0.886      | 0.143        | -                | 0.512 (0.065)    | 0 (0.000) |    11.55 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           19 |      940 | 2024-06-15 | VP.Prodigy      | W   | 0.885      | 0.450        | 0.026 (0.010)    | 0.405 (0.161)    | 0 (0.000) |    12.53 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           18 |      956 | 2024-06-14 | FAVBET          | W   | 0.880      | -            | -                | -                | 0 (0.000) |    10.67 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           17 |     1008 | 2024-06-13 | CYBERSHOKE      | W   | 0.871      | 0.450        | 0.040 (0.016)    | 0.348 (0.137)    | 0 (0.000) |    12.79 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           16 |     1064 | 2024-06-10 | Insilio         | L   | 0.853      | -            | -                | -                | -         |   -10.89 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           15 |     1385 | 2024-06-05 | RUBY            | W   | 0.819      | 0.372        | 0.097 (0.029)    | 0.544 (0.166)    | 0 (0.000) |    13.70 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           14 |     1457 | 2024-06-03 | DMS             | W   | 0.806      | 0.372        | 0.003 (0.001)    | 0.447 (0.134)    | 0 (0.000) |    15.82 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           13 |     1504 | 2024-06-01 | Enterprise      | W   | 0.793      | 0.372        | 0.040 (0.012)    | 0.622 (0.184)    | 0 (0.000) |    13.54 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           12 |     1562 | 2024-05-30 | FAVBET          | W   | 0.780      | 0.372        | 0.003 (0.001)    | 0.343 (0.100)    | 0 (0.000) |     9.83 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           11 |     2305 | 2024-05-05 | 9 Pandas        | L   | 0.611      | -            | -                | -                | -         |    -6.30 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           10 |     2490 | 2024-04-26 | Insilio         | W   | 0.552      | 0.396        | 0.023 (0.005)    | 0.554 (0.121)    | 0 (0.000) |    10.25 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            9 |     2499 | 2024-04-26 | Permitta        | W   | 0.551      | 0.396        | 0.024 (0.005)    | 0.801 (0.175)    | -         |    11.09 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            8 |     3615 | 2024-03-12 | The Chosen Few  | L   | 0.253      | -            | -                | -                | -         |    -5.79 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            7 |     3674 | 2024-03-09 | FORZE YNG       | W   | 0.233      | -            | -                | -                | -         |     0.52 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            6 |     3699 | 2024-03-08 | RUBY            | L   | 0.226      | -            | -                | -                | -         |    -2.76 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            5 |     3787 | 2024-03-05 | 1WIN            | W   | 0.207      | 0.372        | 0.027 (0.002)    | -                | -         |     3.59 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            4 |     3941 | 2024-02-27 | FORZE           | L   | 0.160      | -            | -                | -                | -         |    -2.25 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            3 |     4156 | 2024-02-18 | brazylijski luz | L   | 0.099      | -            | -                | -                | -         |    -1.80 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            2 |     4338 | 2024-02-11 | Sashi           | L   | 0.052      | -            | -                | -                | -         |    -0.25 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            1 |     4428 | 2024-02-04 | Portugal        | L   | 0.005      | -            | -                | -                | -         |    -0.11 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,586.60)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.892 | $10,000.00     | $8,916.67       |
| 2024-06-10 |      0.853 | $4,300.00      | $3,669.93       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
