### Roster Details<br />
Team Name: ARCRED<br />
Roster: 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  943.6<br />
<br />
Final Rank Value (943.6) = Starting Rank Value (862.0) + Head To Head Adjustments (81.6)<br />

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
- 400 + ( ( 0.224 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 862.0


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
|           24 |       84 | 2024-07-30 | B8              | L   | 1.000      | -            | -                | -                | -         |    -7.86 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           23 |      116 | 2024-07-29 | PERA            | W   | 1.000      | 0.500        | 0.048 (0.024)    | 0.452 (0.226)    | 0 (0.000) |    16.54 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           22 |      617 | 2024-07-16 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -6.75 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           21 |      899 | 2024-06-16 | RUBY            | L   | 0.893      | -            | -                | -                | -         |   -16.18 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           20 |      920 | 2024-06-15 | EYEBALLERS      | W   | 0.888      | 0.143        | -                | 0.513 (0.065)    | 0 (0.000) |    11.57 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           19 |      934 | 2024-06-15 | VP.Prodigy      | W   | 0.886      | 0.450        | 0.026 (0.010)    | 0.405 (0.161)    | 0 (0.000) |    12.55 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           18 |      950 | 2024-06-14 | FAVBET          | W   | 0.881      | -            | -                | -                | 0 (0.000) |    10.69 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           17 |     1002 | 2024-06-13 | CYBERSHOKE      | W   | 0.873      | 0.450        | 0.040 (0.016)    | 0.348 (0.137)    | 0 (0.000) |    12.81 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           16 |     1058 | 2024-06-10 | Insilio         | L   | 0.855      | -            | -                | -                | -         |   -10.90 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           15 |     1379 | 2024-06-05 | RUBY            | W   | 0.821      | 0.372        | 0.097 (0.030)    | 0.544 (0.166)    | 0 (0.000) |    13.73 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           14 |     1451 | 2024-06-03 | DMS             | W   | 0.807      | 0.372        | 0.003 (0.001)    | 0.447 (0.134)    | 0 (0.000) |    15.85 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           13 |     1498 | 2024-06-01 | Enterprise      | W   | 0.794      | 0.372        | 0.040 (0.012)    | 0.622 (0.184)    | 0 (0.000) |    13.57 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           12 |     1556 | 2024-05-30 | FAVBET          | W   | 0.782      | 0.372        | 0.003 (0.001)    | 0.343 (0.100)    | 0 (0.000) |     9.85 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           11 |     2299 | 2024-05-05 | 9 Pandas        | L   | 0.612      | -            | -                | -                | -         |    -6.31 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           10 |     2484 | 2024-04-26 | Insilio         | W   | 0.554      | 0.396        | 0.023 (0.005)    | 0.554 (0.122)    | 0 (0.000) |    10.28 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            9 |     2493 | 2024-04-26 | Permitta        | W   | 0.553      | 0.396        | 0.024 (0.005)    | 0.801 (0.176)    | -         |    11.17 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            8 |     3609 | 2024-03-12 | The Chosen Few  | L   | 0.254      | -            | -                | -                | -         |    -5.83 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            7 |     3668 | 2024-03-09 | FORZE YNG       | W   | 0.235      | -            | -                | -                | -         |     0.53 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            6 |     3693 | 2024-03-08 | RUBY            | L   | 0.228      | -            | -                | -                | -         |    -2.78 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            5 |     3781 | 2024-03-05 | 1WIN            | W   | 0.209      | 0.372        | 0.027 (0.002)    | -                | -         |     3.61 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            4 |     3935 | 2024-02-27 | FORZE           | L   | 0.161      | -            | -                | -                | -         |    -2.27 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            3 |     4150 | 2024-02-18 | brazylijski luz | L   | 0.101      | -            | -                | -                | -         |    -1.83 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            2 |     4332 | 2024-02-11 | Sashi           | L   | 0.053      | -            | -                | -                | -         |    -0.26 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            1 |     4422 | 2024-02-04 | Portugal        | L   | 0.007      | -            | -                | -                | -         |    -0.15 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,610.43)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.893 | $10,000.00     | $8,933.33       |
| 2024-06-10 |      0.855 | $4,300.00      | $3,677.10       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
