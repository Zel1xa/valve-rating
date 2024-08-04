### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [112](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [79]( ../standings_europe.md)<br />
<br />
Final Rank Value:  835.1<br />
<br />
Final Rank Value (835.1) = Starting Rank Value (870.3) + Head To Head Adjustments (-35.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.378[<sup>2</sup>](#table1)
- Opponent Network: 0.157[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.230<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 870.3
- 400 + ( ( 0.230 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 870.3


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
|           34 |      571 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.62 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      688 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      773 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.26 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     1042 | 2024-06-15 | ARCRED            | L   | 0.865      | -            | -                | -                | -         |   -12.05 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     1109 | 2024-06-13 | HOTU              | W   | 0.853      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.67 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1118 | 2024-06-13 | 3DMAX             | L   | 0.852      | -            | -                | -                | -         |    -1.34 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1255 | 2024-06-09 | Illuminar         | L   | 0.824      | -            | -                | -                | -         |   -13.80 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1310 | 2024-06-08 | EYEBALLERS        | L   | 0.818      | -            | -                | -                | -         |   -13.21 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1408 | 2024-06-06 | Space             | L   | 0.807      | -            | -                | -                | -         |   -14.64 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1530 | 2024-06-04 | SINNERS           | W   | 0.792      | 0.435        | 0.037 (0.013)    | 0.797 (0.274)    | 0 (0.000) |    16.33 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1577 | 2024-06-02 | GUN5              | L   | 0.778      | -            | -                | -                | -         |   -11.10 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1598 | 2024-06-01 | 3DMAX             | W   | 0.773      | 0.435        | 0.506 (0.170)    | 1.000 (0.336)    | 0 (0.000) |    23.61 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1608 | 2024-06-01 | 777               | W   | 0.772      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.57 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1625 | 2024-05-31 | LEON              | L   | 0.767      | -            | -                | -                | -         |   -18.93 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1641 | 2024-05-31 | Alliance          | W   | 0.765      | 0.435        | 0.017 (0.006)    | 0.299 (0.100)    | 0 (0.000) |     9.90 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1652 | 2024-05-30 | Insilio           | L   | 0.760      | -            | -                | -                | -         |   -11.74 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1698 | 2024-05-28 | CYBERSHOKE        | W   | 0.748      | 0.372        | 0.039 (0.011)    | 0.351 (0.098)    | 0 (0.000) |    10.53 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1728 | 2024-05-27 | Permitta          | W   | 0.740      | 0.435        | 0.024 (0.008)    | 0.876 (0.282)    | 0 (0.000) |    11.90 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1779 | 2024-05-24 | DMS               | W   | 0.720      | 0.435        | -                | 0.446 (0.139)    | 0 (0.000) |    12.13 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1830 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.707      | 0.435        | 0.031 (0.010)    | 0.560 (0.172)    | 0 (0.000) |    11.89 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1919 | 2024-05-20 | SINNERS           | L   | 0.692      | -            | -                | -                | -         |    -5.61 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     1976 | 2024-05-18 | CPH Wolves        | W   | 0.679      | 0.143        | -                | 0.365 (0.035)    | 0 (0.000) |     8.08 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2141 | 2024-05-14 | LEON              | W   | 0.654      | -            | -                | -                | -         |     5.46 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2172 | 2024-05-13 | WOPA              | W   | 0.647      | -            | -                | -                | -         |     4.04 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2341 | 2024-05-05 | Nemiga            | L   | 0.593      | -            | -                | -                | -         |    -2.74 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2473 | 2024-04-29 | Nexus             | W   | 0.552      | 0.396        | 0.014 (0.003)    | 0.465 (0.102)    | -         |     8.13 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2491 | 2024-04-28 | brazylijski luz   | L   | 0.546      | -            | -                | -                | -         |    -9.34 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2494 | 2024-04-28 | LEON              | W   | 0.546      | 0.396        | 0.007 (0.001)    | 0.130 (0.028)    | -         |     4.74 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3387 | 2024-03-23 | FORZE             | L   | 0.306      | -            | -                | -                | -         |    -4.28 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3406 | 2024-03-22 | ex-Guild Eagles   | W   | 0.298      | -            | -                | -                | -         |     3.98 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3451 | 2024-03-20 | TSM               | W   | 0.285      | -            | -                | -                | -         |     2.31 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3678 | 2024-03-10 | 1WIN              | L   | 0.220      | -            | -                | -                | -         |    -2.99 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3746 | 2024-03-07 | Permitta          | L   | 0.200      | -            | -                | -                | -         |    -2.41 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3816 | 2024-03-05 | FORZE YNG         | W   | 0.187      | -            | -                | -                | -         |     0.39 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,258.56)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.872 | $5,000.00      | $4,360.53       |
| 2024-06-02 |      0.780 | $5,000.00      | $3,898.03       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
