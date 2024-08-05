### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [112](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [80]( ../standings_europe.md)<br />
<br />
Final Rank Value:  837.9<br />
<br />
Final Rank Value (837.9) = Starting Rank Value (870.5) + Head To Head Adjustments (-32.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.155[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 870.5
- 400 + ( ( 0.229 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 870.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |      597 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.68 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      714 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.58 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      799 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.56 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     1068 | 2024-06-15 | ARCRED            | L   | 0.858      | -            | -                | -                | -         |   -10.77 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     1135 | 2024-06-13 | HOTU              | W   | 0.845      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.62 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1144 | 2024-06-13 | 3DMAX             | L   | 0.844      | -            | -                | -                | -         |    -1.29 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1281 | 2024-06-09 | Illuminar         | L   | 0.817      | -            | -                | -                | -         |   -13.62 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1336 | 2024-06-08 | EYEBALLERS        | L   | 0.811      | -            | -                | -                | -         |   -13.08 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1434 | 2024-06-06 | Space             | L   | 0.800      | -            | -                | -                | -         |   -14.54 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1556 | 2024-06-04 | SINNERS           | W   | 0.785      | 0.435        | 0.037 (0.013)    | 0.809 (0.276)    | 0 (0.000) |    16.30 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1603 | 2024-06-02 | GUN5              | L   | 0.771      | -            | -                | -                | -         |   -11.00 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1624 | 2024-06-01 | 3DMAX             | W   | 0.766      | 0.435        | 0.508 (0.169)    | 1.000 (0.333)    | 0 (0.000) |    23.41 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1634 | 2024-06-01 | 777               | W   | 0.765      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.47 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1651 | 2024-05-31 | LEON              | L   | 0.760      | -            | -                | -                | -         |   -18.76 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1667 | 2024-05-31 | Alliance          | W   | 0.757      | 0.435        | 0.017 (0.006)    | 0.292 (0.096)    | 0 (0.000) |     9.79 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1678 | 2024-05-30 | Insilio           | L   | 0.753      | -            | -                | -                | -         |   -11.57 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1724 | 2024-05-28 | CYBERSHOKE        | W   | 0.740      | 0.372        | 0.039 (0.011)    | 0.346 (0.095)    | 0 (0.000) |    10.43 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1754 | 2024-05-27 | Permitta          | W   | 0.732      | 0.435        | 0.024 (0.007)    | 0.902 (0.287)    | 0 (0.000) |    12.03 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1805 | 2024-05-24 | DMS               | W   | 0.712      | 0.435        | -                | 0.438 (0.136)    | 0 (0.000) |    12.09 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1856 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.700      | 0.435        | 0.031 (0.010)    | 0.550 (0.167)    | 0 (0.000) |    11.81 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1945 | 2024-05-20 | SINNERS           | L   | 0.685      | -            | -                | -                | -         |    -5.45 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     2002 | 2024-05-18 | CPH Wolves        | W   | 0.672      | 0.143        | -                | 0.361 (0.035)    | 0 (0.000) |     8.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2167 | 2024-05-14 | LEON              | W   | 0.647      | -            | -                | -                | -         |     5.40 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2198 | 2024-05-13 | WOPA              | W   | 0.639      | -            | -                | -                | -         |     4.00 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2367 | 2024-05-05 | Nemiga            | L   | 0.586      | -            | -                | -                | -         |    -2.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2499 | 2024-04-29 | Nexus             | W   | 0.545      | 0.396        | 0.014 (0.003)    | 0.458 (0.099)    | -         |     8.03 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2517 | 2024-04-28 | brazylijski luz   | L   | 0.539      | -            | -                | -                | -         |    -9.26 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2520 | 2024-04-28 | LEON              | W   | 0.538      | 0.396        | 0.007 (0.001)    | 0.127 (0.027)    | -         |     4.67 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3413 | 2024-03-23 | FORZE             | L   | 0.299      | -            | -                | -                | -         |    -4.20 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3432 | 2024-03-22 | ex-Guild Eagles   | W   | 0.291      | -            | -                | -                | -         |     3.86 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3477 | 2024-03-20 | TSM               | W   | 0.278      | -            | -                | -                | -         |     2.25 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3704 | 2024-03-10 | 1WIN              | L   | 0.212      | -            | -                | -                | -         |    -2.81 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3772 | 2024-03-07 | Permitta          | L   | 0.193      | -            | -                | -                | -         |    -2.21 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3842 | 2024-03-05 | FORZE YNG         | W   | 0.180      | -            | -                | -                | -         |     0.38 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,186.11)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.865 | $5,000.00      | $4,324.31       |
| 2024-06-02 |      0.772 | $5,000.00      | $3,861.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
