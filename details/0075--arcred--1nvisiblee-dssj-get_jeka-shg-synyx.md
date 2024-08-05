### Roster Details<br />
Team Name: ARCRED<br />
Roster: 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  942.9<br />
<br />
Final Rank Value (942.9) = Starting Rank Value (866.6) + Head To Head Adjustments (76.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.419[<sup>1</sup>](#table2)
- Bounty Collected: 0.337[<sup>2</sup>](#table1)
- Opponent Network: 0.155[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.228<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 866.6
- 400 + ( ( 0.228 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 866.6


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
|           25 |       59 | 2024-08-03 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -16.73 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           24 |      101 | 2024-08-02 | Insilio         | W   | 1.000      | 0.342        | 0.023 (0.008)    | 0.559 (0.192)    | 0 (0.000) |    15.33 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           23 |      222 | 2024-07-30 | B8              | L   | 1.000      | -            | -                | -                | -         |    -7.58 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           22 |      254 | 2024-07-29 | PERA            | W   | 1.000      | 0.500        | 0.048 (0.024)    | 0.451 (0.226)    | 0 (0.000) |    16.53 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           21 |      744 | 2024-07-16 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -6.38 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           20 |     1021 | 2024-06-16 | RUBY            | L   | 0.866      | -            | -                | -                | -         |   -15.80 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           19 |     1043 | 2024-06-15 | EYEBALLERS      | W   | 0.861      | -            | -                | -                | 0 (0.000) |    11.05 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           18 |     1059 | 2024-06-15 | VP.Prodigy      | W   | 0.859      | 0.450        | 0.025 (0.010)    | 0.398 (0.154)    | 0 (0.000) |    11.98 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           17 |     1080 | 2024-06-14 | FAVBET          | W   | 0.854      | -            | -                | -                | 0 (0.000) |    10.12 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           16 |     1133 | 2024-06-13 | CYBERSHOKE      | W   | 0.846      | 0.450        | 0.039 (0.015)    | 0.351 (0.133)    | 0 (0.000) |    12.24 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           15 |     1187 | 2024-06-10 | Insilio         | L   | 0.828      | -            | -                | -                | -         |   -10.80 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           14 |     1494 | 2024-06-05 | RUBY            | W   | 0.794      | 0.372        | 0.095 (0.028)    | 0.499 (0.147)    | 0 (0.000) |    12.97 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           13 |     1566 | 2024-06-03 | DMS             | W   | 0.781      | 0.372        | -                | 0.444 (0.129)    | 0 (0.000) |    15.24 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           12 |     1613 | 2024-06-01 | Enterprise      | W   | 0.767      | 0.372        | 0.039 (0.011)    | 0.624 (0.178)    | 0 (0.000) |    13.02 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           11 |     1670 | 2024-05-30 | FAVBET          | W   | 0.755      | 0.372        | 0.003 (0.001)    | 0.338 (0.095)    | 0 (0.000) |     9.18 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|           10 |     2374 | 2024-05-05 | 9 Pandas        | L   | 0.585      | -            | -                | -                | -         |    -6.35 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            9 |     2555 | 2024-04-26 | Insilio         | W   | 0.527      | 0.396        | 0.023 (0.005)    | 0.559 (0.117)    | -         |     9.55 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            8 |     2565 | 2024-04-26 | Permitta        | W   | 0.526      | 0.396        | 0.024 (0.005)    | 0.873 (0.182)    | -         |    10.40 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            7 |     3652 | 2024-03-12 | The Chosen Few  | L   | 0.228      | -            | -                | -                | -         |    -5.30 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            6 |     3710 | 2024-03-09 | FORZE YNG       | W   | 0.208      | -            | -                | -                | -         |     0.45 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            5 |     3735 | 2024-03-08 | RUBY            | L   | 0.201      | -            | -                | -                | -         |    -2.67 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            4 |     3823 | 2024-03-05 | 1WIN            | W   | 0.182      | 0.372        | 0.033 (0.002)    | -                | -         |     3.37 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            3 |     3970 | 2024-02-27 | FORZE           | L   | 0.134      | -            | -                | -                | -         |    -2.00 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            2 |     4177 | 2024-02-18 | brazylijski luz | L   | 0.074      | -            | -                | -                | -         |    -1.40 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |
|            1 |     4350 | 2024-02-11 | Sashi           | L   | 0.026      | -            | -                | -                | -         |    -0.13 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,225.13)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.866 | $10,000.00     | $8,663.89       |
| 2024-06-10 |      0.828 | $4,300.00      | $3,561.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
