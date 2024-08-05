### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [112](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [79]( ../standings_europe.md)<br />
<br />
Final Rank Value:  834.9<br />
<br />
Final Rank Value (834.9) = Starting Rank Value (870.1) + Head To Head Adjustments (-35.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.378[<sup>2</sup>](#table1)
- Opponent Network: 0.156[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.230<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 870.1
- 400 + ( ( 0.230 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 870.1


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
|           34 |      575 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.62 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      692 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      777 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.26 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     1046 | 2024-06-15 | ARCRED            | L   | 0.863      | -            | -                | -                | -         |   -12.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     1113 | 2024-06-13 | HOTU              | W   | 0.850      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.67 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1122 | 2024-06-13 | 3DMAX             | L   | 0.849      | -            | -                | -                | -         |    -1.32 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1259 | 2024-06-09 | Illuminar         | L   | 0.822      | -            | -                | -                | -         |   -13.75 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1314 | 2024-06-08 | EYEBALLERS        | L   | 0.816      | -            | -                | -                | -         |   -13.17 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1412 | 2024-06-06 | Space             | L   | 0.804      | -            | -                | -                | -         |   -14.61 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1534 | 2024-06-04 | SINNERS           | W   | 0.789      | 0.435        | 0.037 (0.013)    | 0.797 (0.273)    | 0 (0.000) |    16.29 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1581 | 2024-06-02 | GUN5              | L   | 0.776      | -            | -                | -                | -         |   -11.07 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1602 | 2024-06-01 | 3DMAX             | W   | 0.771      | 0.435        | 0.507 (0.170)    | 1.000 (0.335)    | 0 (0.000) |    23.55 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1612 | 2024-06-01 | 777               | W   | 0.769      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.56 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1629 | 2024-05-31 | LEON              | L   | 0.765      | -            | -                | -                | -         |   -18.87 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1645 | 2024-05-31 | Alliance          | W   | 0.762      | 0.435        | 0.017 (0.006)    | 0.298 (0.099)    | 0 (0.000) |     9.87 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1656 | 2024-05-30 | Insilio           | L   | 0.758      | -            | -                | -                | -         |   -11.71 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1702 | 2024-05-28 | CYBERSHOKE        | W   | 0.745      | 0.372        | 0.039 (0.011)    | 0.351 (0.097)    | 0 (0.000) |    10.51 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1732 | 2024-05-27 | Permitta          | W   | 0.737      | 0.435        | 0.024 (0.008)    | 0.876 (0.281)    | 0 (0.000) |    11.87 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1783 | 2024-05-24 | DMS               | W   | 0.717      | 0.435        | -                | 0.446 (0.139)    | 0 (0.000) |    12.09 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1834 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.705      | 0.435        | 0.031 (0.010)    | 0.560 (0.171)    | 0 (0.000) |    11.85 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1923 | 2024-05-20 | SINNERS           | L   | 0.690      | -            | -                | -                | -         |    -5.59 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     1980 | 2024-05-18 | CPH Wolves        | W   | 0.676      | 0.143        | -                | 0.365 (0.035)    | 0 (0.000) |     8.06 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2145 | 2024-05-14 | LEON              | W   | 0.651      | -            | -                | -                | -         |     5.44 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2176 | 2024-05-13 | WOPA              | W   | 0.644      | -            | -                | -                | -         |     4.03 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2345 | 2024-05-05 | Nemiga            | L   | 0.591      | -            | -                | -                | -         |    -2.74 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2477 | 2024-04-29 | Nexus             | W   | 0.550      | 0.396        | 0.014 (0.003)    | 0.465 (0.101)    | -         |     8.09 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2495 | 2024-04-28 | brazylijski luz   | L   | 0.544      | -            | -                | -                | -         |    -9.31 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2498 | 2024-04-28 | LEON              | W   | 0.543      | 0.396        | 0.007 (0.001)    | 0.130 (0.028)    | -         |     4.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3391 | 2024-03-23 | FORZE             | L   | 0.304      | -            | -                | -                | -         |    -4.25 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3410 | 2024-03-22 | ex-Guild Eagles   | W   | 0.296      | -            | -                | -                | -         |     3.94 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3455 | 2024-03-20 | TSM               | W   | 0.283      | -            | -                | -                | -         |     2.29 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3682 | 2024-03-10 | 1WIN              | L   | 0.217      | -            | -                | -                | -         |    -2.96 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3750 | 2024-03-07 | Permitta          | L   | 0.198      | -            | -                | -                | -         |    -2.38 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3820 | 2024-03-05 | FORZE YNG         | W   | 0.184      | -            | -                | -                | -         |     0.39 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,234.72)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.870 | $5,000.00      | $4,348.61       |
| 2024-06-02 |      0.777 | $5,000.00      | $3,886.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
