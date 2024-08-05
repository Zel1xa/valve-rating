### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [112](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [80]( ../standings_europe.md)<br />
<br />
Final Rank Value:  837.4<br />
<br />
Final Rank Value (837.4) = Starting Rank Value (869.9) + Head To Head Adjustments (-32.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.154[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 869.9
- 400 + ( ( 0.229 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 869.9


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
|           34 |      596 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.67 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      713 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.58 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      798 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.54 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     1067 | 2024-06-15 | ARCRED            | L   | 0.858      | -            | -                | -                | -         |   -10.77 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     1134 | 2024-06-13 | HOTU              | W   | 0.846      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.64 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1143 | 2024-06-13 | 3DMAX             | L   | 0.845      | -            | -                | -                | -         |    -1.29 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1280 | 2024-06-09 | Illuminar         | L   | 0.818      | -            | -                | -                | -         |   -13.61 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1335 | 2024-06-08 | EYEBALLERS        | L   | 0.812      | -            | -                | -                | -         |   -13.09 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1433 | 2024-06-06 | Space             | L   | 0.800      | -            | -                | -                | -         |   -14.54 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1555 | 2024-06-04 | SINNERS           | W   | 0.785      | 0.435        | 0.037 (0.013)    | 0.809 (0.276)    | 0 (0.000) |    16.32 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1602 | 2024-06-02 | GUN5              | L   | 0.771      | -            | -                | -                | -         |   -10.99 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1623 | 2024-06-01 | 3DMAX             | W   | 0.766      | 0.435        | 0.508 (0.169)    | 1.000 (0.333)    | 0 (0.000) |    23.42 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1633 | 2024-06-01 | 777               | W   | 0.765      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.49 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1650 | 2024-05-31 | LEON              | L   | 0.760      | -            | -                | -                | -         |   -18.75 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1666 | 2024-05-31 | Alliance          | W   | 0.758      | 0.435        | 0.017 (0.006)    | 0.292 (0.096)    | 0 (0.000) |     9.82 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1677 | 2024-05-30 | Insilio           | L   | 0.754      | -            | -                | -                | -         |   -11.61 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1723 | 2024-05-28 | CYBERSHOKE        | W   | 0.741      | 0.372        | 0.039 (0.011)    | 0.346 (0.096)    | 0 (0.000) |    10.46 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1753 | 2024-05-27 | Permitta          | W   | 0.733      | 0.435        | 0.024 (0.007)    | 0.863 (0.275)    | 0 (0.000) |    11.85 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1804 | 2024-05-24 | DMS               | W   | 0.713      | 0.435        | -                | 0.438 (0.136)    | 0 (0.000) |    12.11 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1855 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.700      | 0.435        | 0.031 (0.010)    | 0.550 (0.168)    | 0 (0.000) |    11.82 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1944 | 2024-05-20 | SINNERS           | L   | 0.685      | -            | -                | -                | -         |    -5.44 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     2001 | 2024-05-18 | CPH Wolves        | W   | 0.672      | 0.143        | -                | 0.361 (0.035)    | 0 (0.000) |     8.04 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2166 | 2024-05-14 | LEON              | W   | 0.647      | -            | -                | -                | -         |     5.42 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2197 | 2024-05-13 | WOPA              | W   | 0.640      | -            | -                | -                | -         |     4.01 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2366 | 2024-05-05 | Nemiga            | L   | 0.586      | -            | -                | -                | -         |    -2.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2498 | 2024-04-29 | Nexus             | W   | 0.545      | 0.396        | 0.014 (0.003)    | 0.458 (0.099)    | -         |     8.04 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2516 | 2024-04-28 | brazylijski luz   | L   | 0.539      | -            | -                | -                | -         |    -9.25 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2519 | 2024-04-28 | LEON              | W   | 0.539      | 0.396        | 0.007 (0.001)    | 0.127 (0.027)    | -         |     4.69 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3412 | 2024-03-23 | FORZE             | L   | 0.299      | -            | -                | -                | -         |    -4.20 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3431 | 2024-03-22 | ex-Guild Eagles   | W   | 0.292      | -            | -                | -                | -         |     3.88 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3476 | 2024-03-20 | TSM               | W   | 0.278      | -            | -                | -                | -         |     2.26 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3703 | 2024-03-10 | 1WIN              | L   | 0.213      | -            | -                | -                | -         |    -2.82 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3771 | 2024-03-07 | Permitta          | L   | 0.194      | -            | -                | -                | -         |    -2.33 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3841 | 2024-03-05 | FORZE YNG         | W   | 0.180      | -            | -                | -                | -         |     0.38 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,190.28)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.865 | $5,000.00      | $4,326.39       |
| 2024-06-02 |      0.773 | $5,000.00      | $3,863.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
