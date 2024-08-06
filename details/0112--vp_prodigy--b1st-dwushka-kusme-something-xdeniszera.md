### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [112](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [80]( ../standings_europe.md)<br />
<br />
Final Rank Value:  838.6<br />
<br />
Final Rank Value (838.6) = Starting Rank Value (870.8) + Head To Head Adjustments (-32.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.155[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 870.8
- 400 + ( ( 0.229 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 870.8


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
|           34 |      603 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.70 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      720 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.47 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      805 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.58 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     1074 | 2024-06-15 | ARCRED            | L   | 0.854      | -            | -                | -                | -         |   -10.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     1141 | 2024-06-13 | HOTU              | W   | 0.841      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.58 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1150 | 2024-06-13 | 3DMAX             | L   | 0.840      | -            | -                | -                | -         |    -1.27 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1287 | 2024-06-09 | Illuminar         | L   | 0.813      | -            | -                | -                | -         |   -13.56 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1342 | 2024-06-08 | EYEBALLERS        | L   | 0.807      | -            | -                | -                | -         |   -12.89 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1440 | 2024-06-06 | Space             | L   | 0.795      | -            | -                | -                | -         |   -14.24 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1562 | 2024-06-04 | SINNERS           | W   | 0.780      | 0.435        | 0.037 (0.013)    | 0.808 (0.274)    | 0 (0.000) |    16.22 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1609 | 2024-06-02 | GUN5              | L   | 0.766      | -            | -                | -                | -         |   -10.95 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1630 | 2024-06-01 | 3DMAX             | W   | 0.761      | 0.435        | 0.509 (0.169)    | 1.000 (0.331)    | 0 (0.000) |    23.29 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1640 | 2024-06-01 | 777               | W   | 0.760      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.43 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1657 | 2024-05-31 | LEON              | L   | 0.756      | -            | -                | -                | -         |   -18.65 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1673 | 2024-05-31 | Alliance          | W   | 0.753      | 0.435        | 0.017 (0.006)    | 0.289 (0.095)    | 0 (0.000) |     9.75 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1684 | 2024-05-30 | Insilio           | L   | 0.749      | -            | -                | -                | -         |   -11.48 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1730 | 2024-05-28 | CYBERSHOKE        | W   | 0.736      | 0.372        | 0.039 (0.011)    | 0.347 (0.095)    | 0 (0.000) |    10.37 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1760 | 2024-05-27 | Permitta          | W   | 0.728      | 0.435        | 0.023 (0.007)    | 0.940 (0.297)    | 0 (0.000) |    11.98 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1811 | 2024-05-24 | DMS               | W   | 0.708      | 0.435        | -                | 0.437 (0.135)    | 0 (0.000) |    12.01 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1862 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.696      | 0.435        | 0.031 (0.009)    | 0.549 (0.166)    | 0 (0.000) |    11.75 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1951 | 2024-05-20 | SINNERS           | L   | 0.681      | -            | -                | -                | -         |    -5.41 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     2008 | 2024-05-18 | CPH Wolves        | W   | 0.667      | 0.143        | -                | 0.361 (0.034)    | 0 (0.000) |     7.98 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2173 | 2024-05-14 | LEON              | W   | 0.642      | -            | -                | -                | -         |     5.36 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2204 | 2024-05-13 | WOPA              | W   | 0.635      | -            | -                | -                | -         |     3.97 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2373 | 2024-05-05 | Nemiga            | L   | 0.582      | -            | -                | -                | -         |    -2.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2505 | 2024-04-29 | Nexus             | W   | 0.541      | 0.396        | 0.014 (0.003)    | 0.457 (0.098)    | -         |     8.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2523 | 2024-04-28 | brazylijski luz   | L   | 0.535      | -            | -                | -                | -         |    -9.21 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2526 | 2024-04-28 | LEON              | W   | 0.534      | 0.396        | 0.007 (0.001)    | 0.127 (0.027)    | -         |     4.63 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3419 | 2024-03-23 | FORZE             | L   | 0.294      | -            | -                | -                | -         |    -4.16 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3438 | 2024-03-22 | ex-Guild Eagles   | W   | 0.287      | -            | -                | -                | -         |     3.81 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3483 | 2024-03-20 | TSM               | W   | 0.274      | -            | -                | -                | -         |     2.20 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3710 | 2024-03-10 | 1WIN              | L   | 0.208      | -            | -                | -                | -         |    -2.74 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3778 | 2024-03-07 | Permitta          | L   | 0.189      | -            | -                | -                | -         |    -2.17 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3848 | 2024-03-05 | FORZE YNG         | W   | 0.175      | -            | -                | -                | -         |     0.37 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,143.06)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.861 | $5,000.00      | $4,302.78       |
| 2024-06-02 |      0.768 | $5,000.00      | $3,840.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
