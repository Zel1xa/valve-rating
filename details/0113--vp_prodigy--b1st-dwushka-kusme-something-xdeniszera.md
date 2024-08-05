### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [113](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [80]( ../standings_europe.md)<br />
<br />
Final Rank Value:  835.1<br />
<br />
Final Rank Value (835.1) = Starting Rank Value (869.8) + Head To Head Adjustments (-34.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.155[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 869.8
- 400 + ( ( 0.229 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 869.8


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
|           34 |      588 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.62 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      705 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.61 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      790 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.21 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     1059 | 2024-06-15 | ARCRED            | L   | 0.859      | -            | -                | -                | -         |   -11.98 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     1126 | 2024-06-13 | HOTU              | W   | 0.847      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.65 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1135 | 2024-06-13 | 3DMAX             | L   | 0.846      | -            | -                | -                | -         |    -1.30 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1272 | 2024-06-09 | Illuminar         | L   | 0.819      | -            | -                | -                | -         |   -13.67 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1327 | 2024-06-08 | EYEBALLERS        | L   | 0.813      | -            | -                | -                | -         |   -13.12 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1425 | 2024-06-06 | Space             | L   | 0.801      | -            | -                | -                | -         |   -14.54 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1547 | 2024-06-04 | SINNERS           | W   | 0.786      | 0.435        | 0.037 (0.013)    | 0.794 (0.271)    | 0 (0.000) |    16.24 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1594 | 2024-06-02 | GUN5              | L   | 0.772      | -            | -                | -                | -         |   -11.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1615 | 2024-06-01 | 3DMAX             | W   | 0.767      | 0.435        | 0.508 (0.169)    | 1.000 (0.333)    | 0 (0.000) |    23.45 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1625 | 2024-06-01 | 777               | W   | 0.766      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.54 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1642 | 2024-05-31 | LEON              | L   | 0.761      | -            | -                | -                | -         |   -18.78 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1658 | 2024-05-31 | Alliance          | W   | 0.759      | 0.435        | 0.017 (0.006)    | 0.296 (0.098)    | 0 (0.000) |     9.83 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1669 | 2024-05-30 | Insilio           | L   | 0.755      | -            | -                | -                | -         |   -11.65 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1715 | 2024-05-28 | CYBERSHOKE        | W   | 0.742      | 0.372        | 0.039 (0.011)    | 0.351 (0.097)    | 0 (0.000) |    10.49 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1745 | 2024-05-27 | Permitta          | W   | 0.734      | 0.435        | 0.024 (0.008)    | 0.873 (0.278)    | 0 (0.000) |    11.84 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1796 | 2024-05-24 | DMS               | W   | 0.714      | 0.435        | -                | 0.444 (0.138)    | 0 (0.000) |    12.14 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1847 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.702      | 0.435        | 0.031 (0.010)    | 0.557 (0.170)    | 0 (0.000) |    11.82 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1936 | 2024-05-20 | SINNERS           | L   | 0.686      | -            | -                | -                | -         |    -5.55 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     1993 | 2024-05-18 | CPH Wolves        | W   | 0.673      | 0.143        | -                | 0.365 (0.035)    | 0 (0.000) |     8.06 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2158 | 2024-05-14 | LEON              | W   | 0.648      | -            | -                | -                | -         |     5.42 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2189 | 2024-05-13 | WOPA              | W   | 0.641      | -            | -                | -                | -         |     4.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2358 | 2024-05-05 | Nemiga            | L   | 0.588      | -            | -                | -                | -         |    -2.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2490 | 2024-04-29 | Nexus             | W   | 0.547      | 0.396        | 0.014 (0.003)    | 0.464 (0.100)    | -         |     8.05 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2508 | 2024-04-28 | brazylijski luz   | L   | 0.541      | -            | -                | -                | -         |    -9.27 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2511 | 2024-04-28 | LEON              | W   | 0.540      | 0.396        | 0.007 (0.001)    | 0.129 (0.028)    | -         |     4.70 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3404 | 2024-03-23 | FORZE             | L   | 0.300      | -            | -                | -                | -         |    -4.21 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3423 | 2024-03-22 | ex-Guild Eagles   | W   | 0.293      | -            | -                | -                | -         |     3.89 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3468 | 2024-03-20 | TSM               | W   | 0.279      | -            | -                | -                | -         |     2.27 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3695 | 2024-03-10 | 1WIN              | L   | 0.214      | -            | -                | -                | -         |    -2.83 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3763 | 2024-03-07 | Permitta          | L   | 0.195      | -            | -                | -                | -         |    -2.34 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3833 | 2024-03-05 | FORZE YNG         | W   | 0.181      | -            | -                | -                | -         |     0.38 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,201.39)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.866 | $5,000.00      | $4,331.94       |
| 2024-06-02 |      0.774 | $5,000.00      | $3,869.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
