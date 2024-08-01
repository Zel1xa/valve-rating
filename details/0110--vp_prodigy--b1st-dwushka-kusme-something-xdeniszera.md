### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [110](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [81]( ../standings_europe.md)<br />
<br />
Final Rank Value:  839.5<br />
<br />
Final Rank Value (839.5) = Starting Rank Value (875.6) + Head To Head Adjustments (-36.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.159[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.231<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 875.6
- 400 + ( ( 0.231 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 875.6


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
|           34 |      460 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.70 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      582 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      674 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.43 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |      938 | 2024-06-15 | ARCRED            | L   | 0.885      | -            | -                | -                | -         |   -12.53 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |      999 | 2024-06-13 | HOTU              | W   | 0.873      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.76 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1008 | 2024-06-13 | 3DMAX             | L   | 0.871      | -            | -                | -                | -         |    -1.46 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1148 | 2024-06-09 | Illuminar         | L   | 0.844      | -            | -                | -                | -         |   -13.54 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1205 | 2024-06-08 | EYEBALLERS        | L   | 0.838      | -            | -                | -                | -         |   -13.43 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1311 | 2024-06-06 | Space             | L   | 0.827      | -            | -                | -                | -         |   -14.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1436 | 2024-06-04 | SINNERS           | W   | 0.812      | 0.435        | 0.038 (0.013)    | 0.768 (0.271)    | 0 (0.000) |    15.79 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1484 | 2024-06-02 | GUN5              | L   | 0.798      | -            | -                | -                | -         |   -10.75 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1505 | 2024-06-01 | 3DMAX             | W   | 0.793      | 0.435        | 0.505 (0.174)    | 1.000 (0.345)    | 0 (0.000) |    24.18 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1515 | 2024-06-01 | 777               | W   | 0.792      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.75 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1532 | 2024-05-31 | LEON              | L   | 0.787      | -            | -                | -                | -         |   -19.44 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1548 | 2024-05-31 | Alliance          | W   | 0.784      | 0.435        | 0.014 (0.005)    | 0.319 (0.109)    | 0 (0.000) |    10.14 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1559 | 2024-05-30 | Insilio           | L   | 0.780      | -            | -                | -                | -         |   -12.04 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1605 | 2024-05-28 | CYBERSHOKE        | W   | 0.767      | 0.372        | 0.040 (0.011)    | 0.348 (0.099)    | 0 (0.000) |    10.76 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1635 | 2024-05-27 | Permitta          | W   | 0.759      | 0.435        | 0.024 (0.008)    | 0.801 (0.264)    | 0 (0.000) |    11.91 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1688 | 2024-05-24 | DMS               | W   | 0.739      | 0.435        | -                | 0.447 (0.144)    | 0 (0.000) |    12.39 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1739 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.727      | 0.435        | 0.032 (0.010)    | 0.563 (0.178)    | 0 (0.000) |    11.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1848 | 2024-05-20 | SINNERS           | L   | 0.712      | -            | -                | -                | -         |    -6.77 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     1911 | 2024-05-18 | CPH Wolves        | W   | 0.699      | 0.143        | -                | 0.360 (0.036)    | 0 (0.000) |     8.25 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2082 | 2024-05-14 | LEON              | W   | 0.674      | -            | -                | -                | -         |     5.57 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2116 | 2024-05-13 | WOPA              | W   | 0.666      | -            | -                | -                | -         |     4.11 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2287 | 2024-05-05 | Nemiga            | L   | 0.613      | -            | -                | -                | -         |    -3.13 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2422 | 2024-04-29 | Nexus             | W   | 0.572      | 0.396        | 0.014 (0.003)    | 0.504 (0.114)    | -         |     8.44 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2440 | 2024-04-28 | brazylijski luz   | L   | 0.566      | -            | -                | -                | -         |    -9.48 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2443 | 2024-04-28 | LEON              | W   | 0.565      | 0.396        | 0.007 (0.002)    | 0.131 (0.029)    | -         |     4.87 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3360 | 2024-03-23 | FORZE             | L   | 0.326      | -            | -                | -                | -         |    -4.47 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3379 | 2024-03-22 | ex-Guild Eagles   | W   | 0.318      | -            | -                | -                | -         |     4.33 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3424 | 2024-03-20 | TSM               | W   | 0.305      | -            | -                | -                | -         |     2.48 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3656 | 2024-03-10 | 1WIN              | L   | 0.239      | -            | -                | -                | -         |    -3.58 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3725 | 2024-03-07 | Permitta          | L   | 0.220      | -            | -                | -                | -         |    -2.76 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3800 | 2024-03-05 | FORZE YNG         | W   | 0.207      | -            | -                | -                | -         |     0.42 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,456.94)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.892 | $5,000.00      | $4,459.72       |
| 2024-06-02 |      0.799 | $5,000.00      | $3,997.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
