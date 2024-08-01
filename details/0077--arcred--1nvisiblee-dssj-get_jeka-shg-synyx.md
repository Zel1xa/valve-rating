### Roster Details<br />
Team Name: ARCRED<br />
Roster: 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  942.9<br />
<br />
Final Rank Value (942.9) = Starting Rank Value (861.4) + Head To Head Adjustments (81.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.414[<sup>1</sup>](#table2)
- Bounty Collected: 0.336[<sup>2</sup>](#table1)
- Opponent Network: 0.147[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.224<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 861.4
- 400 + ( ( 0.224 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 861.4


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
|           24 |       88 | 2024-07-30 | B8              | L   | 1.000      | -            | -                | -                | -         |    -7.87 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           23 |      120 | 2024-07-29 | PERA            | W   | 1.000      | 0.500        | 0.048 (0.024)    | 0.452 (0.226)    | 0 (0.000) |    16.57 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           22 |      621 | 2024-07-16 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -6.76 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           21 |      903 | 2024-06-16 | RUBY            | L   | 0.892      | -            | -                | -                | -         |   -16.16 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           20 |      924 | 2024-06-15 | EYEBALLERS      | W   | 0.887      | 0.143        | -                | 0.512 (0.065)    | 0 (0.000) |    11.55 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           19 |      938 | 2024-06-15 | VP.Prodigy      | W   | 0.885      | 0.450        | 0.026 (0.010)    | 0.405 (0.161)    | 0 (0.000) |    12.53 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           18 |      954 | 2024-06-14 | FAVBET          | W   | 0.880      | -            | -                | -                | 0 (0.000) |    10.67 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           17 |     1006 | 2024-06-13 | CYBERSHOKE      | W   | 0.872      | 0.450        | 0.040 (0.016)    | 0.348 (0.137)    | 0 (0.000) |    12.79 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           16 |     1062 | 2024-06-10 | Insilio         | L   | 0.854      | -            | -                | -                | -         |   -10.89 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           15 |     1383 | 2024-06-05 | RUBY            | W   | 0.819      | 0.372        | 0.097 (0.029)    | 0.544 (0.166)    | 0 (0.000) |    13.71 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           14 |     1455 | 2024-06-03 | DMS             | W   | 0.806      | 0.372        | 0.003 (0.001)    | 0.447 (0.134)    | 0 (0.000) |    15.82 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           13 |     1502 | 2024-06-01 | Enterprise      | W   | 0.793      | 0.372        | 0.040 (0.012)    | 0.622 (0.184)    | 0 (0.000) |    13.55 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           12 |     1560 | 2024-05-30 | FAVBET          | W   | 0.780      | 0.372        | 0.003 (0.001)    | 0.343 (0.100)    | 0 (0.000) |     9.83 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           11 |     2303 | 2024-05-05 | 9 Pandas        | L   | 0.611      | -            | -                | -                | -         |    -6.31 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           10 |     2488 | 2024-04-26 | Insilio         | W   | 0.553      | 0.396        | 0.023 (0.005)    | 0.554 (0.121)    | 0 (0.000) |    10.25 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            9 |     2497 | 2024-04-26 | Permitta        | W   | 0.551      | 0.396        | 0.024 (0.005)    | 0.801 (0.175)    | -         |    11.13 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            8 |     3613 | 2024-03-12 | The Chosen Few  | L   | 0.253      | -            | -                | -                | -         |    -5.79 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            7 |     3672 | 2024-03-09 | FORZE YNG       | W   | 0.233      | -            | -                | -                | -         |     0.52 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            6 |     3697 | 2024-03-08 | RUBY            | L   | 0.227      | -            | -                | -                | -         |    -2.77 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            5 |     3785 | 2024-03-05 | 1WIN            | W   | 0.207      | 0.372        | 0.027 (0.002)    | -                | -         |     3.60 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            4 |     3939 | 2024-02-27 | FORZE           | L   | 0.160      | -            | -                | -                | -         |    -2.26 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            3 |     4154 | 2024-02-18 | brazylijski luz | L   | 0.100      | -            | -                | -                | -         |    -1.81 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            2 |     4336 | 2024-02-11 | Sashi           | L   | 0.052      | -            | -                | -                | -         |    -0.25 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            1 |     4426 | 2024-02-04 | Portugal        | L   | 0.005      | -            | -                | -                | -         |    -0.12 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,590.57)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.892 | $10,000.00     | $8,919.44       |
| 2024-06-10 |      0.854 | $4,300.00      | $3,671.13       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
