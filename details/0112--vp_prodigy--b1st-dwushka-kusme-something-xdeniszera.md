### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [112](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [80]( ../standings_europe.md)<br />
<br />
Final Rank Value:  837.8<br />
<br />
Final Rank Value (837.8) = Starting Rank Value (870.3) + Head To Head Adjustments (-32.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.155[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 870.3
- 400 + ( ( 0.229 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 870.3


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
|           34 |      599 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.68 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      716 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.58 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      801 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.56 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     1070 | 2024-06-15 | ARCRED            | L   | 0.856      | -            | -                | -                | -         |   -10.75 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     1137 | 2024-06-13 | HOTU              | W   | 0.844      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.62 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1146 | 2024-06-13 | 3DMAX             | L   | 0.843      | -            | -                | -                | -         |    -1.28 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1283 | 2024-06-09 | Illuminar         | L   | 0.815      | -            | -                | -                | -         |   -13.58 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1338 | 2024-06-08 | EYEBALLERS        | L   | 0.809      | -            | -                | -                | -         |   -13.05 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1436 | 2024-06-06 | Space             | L   | 0.798      | -            | -                | -                | -         |   -14.51 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1558 | 2024-06-04 | SINNERS           | W   | 0.783      | 0.435        | 0.037 (0.013)    | 0.808 (0.275)    | 0 (0.000) |    16.27 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1605 | 2024-06-02 | GUN5              | L   | 0.769      | -            | -                | -                | -         |   -10.97 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1626 | 2024-06-01 | 3DMAX             | W   | 0.764      | 0.435        | 0.509 (0.169)    | 1.000 (0.332)    | 0 (0.000) |    23.36 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1636 | 2024-06-01 | 777               | W   | 0.763      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.46 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1653 | 2024-05-31 | LEON              | L   | 0.758      | -            | -                | -                | -         |   -18.71 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1669 | 2024-05-31 | Alliance          | W   | 0.756      | 0.435        | 0.017 (0.006)    | 0.291 (0.095)    | 0 (0.000) |     9.77 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1680 | 2024-05-30 | Insilio           | L   | 0.751      | -            | -                | -                | -         |   -11.54 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1726 | 2024-05-28 | CYBERSHOKE        | W   | 0.738      | 0.372        | 0.039 (0.011)    | 0.346 (0.095)    | 0 (0.000) |    10.41 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1756 | 2024-05-27 | Permitta          | W   | 0.731      | 0.435        | 0.023 (0.007)    | 0.901 (0.286)    | 0 (0.000) |    12.00 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1807 | 2024-05-24 | DMS               | W   | 0.711      | 0.435        | -                | 0.438 (0.135)    | 0 (0.000) |    12.06 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1858 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.698      | 0.435        | 0.031 (0.009)    | 0.550 (0.167)    | 0 (0.000) |    11.78 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1947 | 2024-05-20 | SINNERS           | L   | 0.683      | -            | -                | -                | -         |    -5.43 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     2004 | 2024-05-18 | CPH Wolves        | W   | 0.670      | 0.143        | -                | 0.361 (0.035)    | 0 (0.000) |     8.01 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2169 | 2024-05-14 | LEON              | W   | 0.645      | -            | -                | -                | -         |     5.39 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2200 | 2024-05-13 | WOPA              | W   | 0.638      | -            | -                | -                | -         |     3.99 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2369 | 2024-05-05 | Nemiga            | L   | 0.584      | -            | -                | -                | -         |    -2.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2501 | 2024-04-29 | Nexus             | W   | 0.543      | 0.396        | 0.014 (0.003)    | 0.457 (0.098)    | -         |     8.00 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2519 | 2024-04-28 | brazylijski luz   | L   | 0.537      | -            | -                | -                | -         |    -9.24 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2522 | 2024-04-28 | LEON              | W   | 0.537      | 0.396        | 0.007 (0.001)    | 0.127 (0.027)    | -         |     4.66 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3415 | 2024-03-23 | FORZE             | L   | 0.297      | -            | -                | -                | -         |    -4.18 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3434 | 2024-03-22 | ex-Guild Eagles   | W   | 0.289      | -            | -                | -                | -         |     3.83 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3479 | 2024-03-20 | TSM               | W   | 0.276      | -            | -                | -                | -         |     2.23 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3706 | 2024-03-10 | 1WIN              | L   | 0.211      | -            | -                | -                | -         |    -2.79 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3774 | 2024-03-07 | Permitta          | L   | 0.191      | -            | -                | -                | -         |    -2.19 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3844 | 2024-03-05 | FORZE YNG         | W   | 0.178      | -            | -                | -                | -         |     0.38 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,168.06)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.863 | $5,000.00      | $4,315.28       |
| 2024-06-02 |      0.771 | $5,000.00      | $3,852.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
