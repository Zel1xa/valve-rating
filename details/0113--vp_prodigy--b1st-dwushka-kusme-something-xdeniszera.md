### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [113](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
<br />
Final Rank Value:  833.2<br />
<br />
Final Rank Value (833.2) = Starting Rank Value (870.0) + Head To Head Adjustments (-36.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.378[<sup>2</sup>](#table1)
- Opponent Network: 0.156[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.230<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 870.0
- 400 + ( ( 0.230 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 870.0


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
|           34 |      536 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.58 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      654 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.58 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      741 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.83 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     1006 | 2024-06-15 | ARCRED            | L   | 0.870      | -            | -                | -                | -         |   -12.05 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     1073 | 2024-06-13 | HOTU              | W   | 0.858      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.74 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1082 | 2024-06-13 | 3DMAX             | L   | 0.856      | -            | -                | -                | -         |    -1.36 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1219 | 2024-06-09 | Illuminar         | L   | 0.829      | -            | -                | -                | -         |   -13.87 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1274 | 2024-06-08 | EYEBALLERS        | L   | 0.823      | -            | -                | -                | -         |   -13.14 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1372 | 2024-06-06 | Space             | L   | 0.812      | -            | -                | -                | -         |   -14.42 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1494 | 2024-06-04 | SINNERS           | W   | 0.797      | 0.435        | 0.037 (0.013)    | 0.758 (0.262)    | 0 (0.000) |    15.63 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1541 | 2024-06-02 | GUN5              | L   | 0.783      | -            | -                | -                | -         |   -11.19 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1562 | 2024-06-01 | 3DMAX             | W   | 0.778      | 0.435        | 0.505 (0.171)    | 1.000 (0.338)    | 0 (0.000) |    23.75 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1572 | 2024-06-01 | 777               | W   | 0.777      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.65 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1589 | 2024-05-31 | LEON              | L   | 0.772      | -            | -                | -                | -         |   -19.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1605 | 2024-05-31 | Alliance          | W   | 0.769      | 0.435        | 0.017 (0.006)    | 0.302 (0.101)    | 0 (0.000) |    10.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1616 | 2024-05-30 | Insilio           | L   | 0.765      | -            | -                | -                | -         |   -11.79 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1662 | 2024-05-28 | CYBERSHOKE        | W   | 0.752      | 0.372        | 0.039 (0.011)    | 0.350 (0.098)    | 0 (0.000) |    10.58 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1692 | 2024-05-27 | Permitta          | W   | 0.744      | 0.435        | 0.024 (0.008)    | 0.876 (0.283)    | 0 (0.000) |    11.96 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1743 | 2024-05-24 | DMS               | W   | 0.724      | 0.435        | -                | 0.446 (0.140)    | 0 (0.000) |    12.25 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1794 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.712      | 0.435        | 0.032 (0.010)    | 0.561 (0.174)    | 0 (0.000) |    11.94 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1883 | 2024-05-20 | SINNERS           | L   | 0.697      | -            | -                | -                | -         |    -6.51 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     1940 | 2024-05-18 | CPH Wolves        | W   | 0.684      | 0.143        | -                | 0.363 (0.035)    | 0 (0.000) |     8.14 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2105 | 2024-05-14 | LEON              | W   | 0.659      | -            | -                | -                | -         |     5.51 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2136 | 2024-05-13 | WOPA              | W   | 0.651      | -            | -                | -                | -         |     4.08 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2305 | 2024-05-05 | Nemiga            | L   | 0.598      | -            | -                | -                | -         |    -2.98 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2437 | 2024-04-29 | Nexus             | W   | 0.557      | 0.396        | 0.014 (0.003)    | 0.465 (0.103)    | -         |     8.22 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2455 | 2024-04-28 | brazylijski luz   | L   | 0.551      | -            | -                | -                | -         |    -9.45 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2458 | 2024-04-28 | LEON              | W   | 0.550      | 0.396        | 0.007 (0.001)    | 0.130 (0.028)    | -         |     4.79 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3350 | 2024-03-23 | FORZE             | L   | 0.311      | -            | -                | -                | -         |    -4.32 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3369 | 2024-03-22 | ex-Guild Eagles   | W   | 0.303      | -            | -                | -                | -         |     4.09 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3414 | 2024-03-20 | TSM               | W   | 0.290      | -            | -                | -                | -         |     2.36 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3640 | 2024-03-10 | 1WIN              | L   | 0.224      | -            | -                | -                | -         |    -3.34 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3708 | 2024-03-07 | Permitta          | L   | 0.205      | -            | -                | -                | -         |    -2.47 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3778 | 2024-03-05 | FORZE YNG         | W   | 0.192      | -            | -                | -                | -         |     0.41 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,306.94)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.877 | $5,000.00      | $4,384.72       |
| 2024-06-02 |      0.784 | $5,000.00      | $3,922.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
