### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [111](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [80]( ../standings_europe.md)<br />
<br />
Final Rank Value:  838.4<br />
<br />
Final Rank Value (838.4) = Starting Rank Value (870.4) + Head To Head Adjustments (-32.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 870.4
- 400 + ( ( 0.229 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 870.4


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
|           34 |      607 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.69 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      724 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.47 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      809 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.57 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     1078 | 2024-06-15 | ARCRED            | L   | 0.853      | -            | -                | -                | -         |   -10.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     1145 | 2024-06-13 | HOTU              | W   | 0.841      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.60 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1154 | 2024-06-13 | 3DMAX             | L   | 0.840      | -            | -                | -                | -         |    -1.26 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1291 | 2024-06-09 | Illuminar         | L   | 0.813      | -            | -                | -                | -         |   -13.53 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1346 | 2024-06-08 | EYEBALLERS        | L   | 0.807      | -            | -                | -                | -         |   -12.88 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1444 | 2024-06-06 | Space             | L   | 0.795      | -            | -                | -                | -         |   -14.25 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1566 | 2024-06-04 | SINNERS           | W   | 0.780      | 0.435        | 0.037 (0.013)    | 0.790 (0.268)    | 0 (0.000) |    16.23 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1613 | 2024-06-02 | GUN5              | L   | 0.766      | -            | -                | -                | -         |   -10.94 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1634 | 2024-06-01 | 3DMAX             | W   | 0.761      | 0.435        | 0.510 (0.169)    | 1.000 (0.331)    | 0 (0.000) |    23.28 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1644 | 2024-06-01 | 777               | W   | 0.760      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.44 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1661 | 2024-05-31 | LEON              | L   | 0.755      | -            | -                | -                | -         |   -18.63 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1677 | 2024-05-31 | Alliance          | W   | 0.753      | 0.435        | 0.017 (0.006)    | 0.283 (0.093)    | 0 (0.000) |     9.77 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1688 | 2024-05-30 | Insilio           | L   | 0.749      | -            | -                | -                | -         |   -11.49 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1734 | 2024-05-28 | CYBERSHOKE        | W   | 0.736      | 0.372        | 0.039 (0.011)    | 0.339 (0.093)    | 0 (0.000) |    10.36 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1764 | 2024-05-27 | Permitta          | W   | 0.728      | 0.435        | 0.023 (0.007)    | 0.919 (0.291)    | 0 (0.000) |    11.98 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1815 | 2024-05-24 | DMS               | W   | 0.708      | 0.435        | -                | 0.428 (0.132)    | 0 (0.000) |    12.00 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1866 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.695      | 0.435        | 0.031 (0.009)    | 0.537 (0.162)    | 0 (0.000) |    11.77 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1955 | 2024-05-20 | SINNERS           | L   | 0.680      | -            | -                | -                | -         |    -5.40 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     2012 | 2024-05-18 | CPH Wolves        | W   | 0.667      | 0.143        | -                | 0.353 (0.034)    | 0 (0.000) |     7.99 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2177 | 2024-05-14 | LEON              | W   | 0.642      | -            | -                | -                | -         |     5.38 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2208 | 2024-05-13 | WOPA              | W   | 0.635      | -            | -                | -                | -         |     3.98 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2377 | 2024-05-05 | Nemiga            | L   | 0.581      | -            | -                | -                | -         |    -2.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2509 | 2024-04-29 | Nexus             | W   | 0.540      | 0.396        | 0.014 (0.003)    | 0.447 (0.096)    | -         |     8.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2527 | 2024-04-28 | brazylijski luz   | L   | 0.534      | -            | -                | -                | -         |    -9.20 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2530 | 2024-04-28 | LEON              | W   | 0.534      | 0.396        | 0.007 (0.001)    | 0.124 (0.026)    | -         |     4.64 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3423 | 2024-03-23 | FORZE             | L   | 0.294      | -            | -                | -                | -         |    -4.15 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3442 | 2024-03-22 | ex-Guild Eagles   | W   | 0.287      | -            | -                | -                | -         |     3.82 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3487 | 2024-03-20 | TSM               | W   | 0.273      | -            | -                | -                | -         |     2.21 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3714 | 2024-03-10 | 1WIN              | L   | 0.208      | -            | -                | -                | -         |    -2.75 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3782 | 2024-03-07 | Permitta          | L   | 0.189      | -            | -                | -                | -         |    -2.16 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3852 | 2024-03-05 | FORZE YNG         | W   | 0.175      | -            | -                | -                | -         |     0.37 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,140.28)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.860 | $5,000.00      | $4,301.39       |
| 2024-06-02 |      0.768 | $5,000.00      | $3,838.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
