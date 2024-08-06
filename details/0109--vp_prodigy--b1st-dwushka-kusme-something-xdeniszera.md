### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [109](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [80]( ../standings_europe.md)<br />
<br />
Final Rank Value:  839.3<br />
<br />
Final Rank Value (839.3) = Starting Rank Value (870.3) + Head To Head Adjustments (-31.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 870.3
- 400 + ( ( 0.229 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 870.3


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
|           34 |      605 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.71 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      722 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.64 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      807 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -13.50 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     1076 | 2024-06-15 | ARCRED            | L   | 0.853      | -            | -                | -                | -         |   -10.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     1143 | 2024-06-13 | HOTU              | W   | 0.840      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.60 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1152 | 2024-06-13 | 3DMAX             | L   | 0.839      | -            | -                | -                | -         |    -1.26 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1289 | 2024-06-09 | Illuminar         | L   | 0.812      | -            | -                | -                | -         |   -13.40 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1344 | 2024-06-08 | EYEBALLERS        | L   | 0.806      | -            | -                | -                | -         |   -12.87 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1442 | 2024-06-06 | Space             | L   | 0.794      | -            | -                | -                | -         |   -14.26 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1564 | 2024-06-04 | SINNERS           | W   | 0.779      | 0.435        | 0.037 (0.013)    | 0.790 (0.268)    | 0 (0.000) |    16.22 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1611 | 2024-06-02 | GUN5              | L   | 0.765      | -            | -                | -                | -         |   -10.94 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1632 | 2024-06-01 | 3DMAX             | W   | 0.761      | 0.435        | 0.510 (0.168)    | 1.000 (0.331)    | 0 (0.000) |    23.26 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1642 | 2024-06-01 | 777               | W   | 0.759      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.44 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1659 | 2024-05-31 | LEON              | L   | 0.755      | -            | -                | -                | -         |   -18.61 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1675 | 2024-05-31 | Alliance          | W   | 0.752      | 0.435        | 0.017 (0.006)    | 0.283 (0.092)    | 0 (0.000) |     9.76 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1686 | 2024-05-30 | Insilio           | L   | 0.748      | -            | -                | -                | -         |   -11.46 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1732 | 2024-05-28 | CYBERSHOKE        | W   | 0.735      | 0.372        | 0.039 (0.011)    | 0.339 (0.093)    | 0 (0.000) |    10.38 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1762 | 2024-05-27 | Permitta          | W   | 0.727      | 0.435        | 0.023 (0.007)    | 0.919 (0.290)    | 0 (0.000) |    11.98 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1813 | 2024-05-24 | DMS               | W   | 0.707      | 0.435        | -                | 0.428 (0.131)    | 0 (0.000) |    11.87 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1864 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.695      | 0.435        | 0.031 (0.009)    | 0.537 (0.162)    | 0 (0.000) |    11.78 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1953 | 2024-05-20 | SINNERS           | L   | 0.680      | -            | -                | -                | -         |    -5.39 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     2010 | 2024-05-18 | CPH Wolves        | W   | 0.666      | 0.143        | -                | 0.353 (0.034)    | 0 (0.000) |     7.98 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2175 | 2024-05-14 | LEON              | W   | 0.641      | -            | -                | -                | -         |     5.37 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2206 | 2024-05-13 | WOPA              | W   | 0.634      | -            | -                | -                | -         |     3.98 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2375 | 2024-05-05 | Nemiga            | L   | 0.581      | -            | -                | -                | -         |    -2.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2507 | 2024-04-29 | Nexus             | W   | 0.540      | 0.396        | 0.014 (0.003)    | 0.447 (0.096)    | -         |     8.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2525 | 2024-04-28 | brazylijski luz   | L   | 0.534      | -            | -                | -                | -         |    -9.19 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2528 | 2024-04-28 | LEON              | W   | 0.533      | 0.396        | 0.007 (0.001)    | 0.124 (0.026)    | -         |     4.64 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3421 | 2024-03-23 | FORZE             | L   | 0.294      | -            | -                | -                | -         |    -4.13 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3440 | 2024-03-22 | ex-Guild Eagles   | W   | 0.286      | -            | -                | -                | -         |     3.81 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3485 | 2024-03-20 | TSM               | W   | 0.273      | -            | -                | -                | -         |     2.20 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3712 | 2024-03-10 | 1WIN              | L   | 0.207      | -            | -                | -                | -         |    -2.74 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3780 | 2024-03-07 | Permitta          | L   | 0.188      | -            | -                | -                | -         |    -2.15 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3850 | 2024-03-05 | FORZE YNG         | W   | 0.174      | -            | -                | -                | -         |     0.37 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,133.80)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.860 | $5,000.00      | $4,298.15       |
| 2024-06-02 |      0.767 | $5,000.00      | $3,835.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
