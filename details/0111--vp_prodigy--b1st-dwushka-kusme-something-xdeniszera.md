### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [111](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [79]( ../standings_europe.md)<br />
<br />
Final Rank Value:  840.5<br />
<br />
Final Rank Value (840.5) = Starting Rank Value (871.1) + Head To Head Adjustments (-30.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.378[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 871.1
- 400 + ( ( 0.229 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 871.1


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
|           34 |      618 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.74 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      735 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.48 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      820 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -13.53 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     1089 | 2024-06-15 | ARCRED            | L   | 0.852      | -            | -                | -                | -         |   -10.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     1156 | 2024-06-13 | HOTU              | W   | 0.839      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.57 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1165 | 2024-06-13 | 3DMAX             | L   | 0.838      | -            | -                | -                | -         |    -1.26 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1302 | 2024-06-09 | Illuminar         | L   | 0.811      | -            | -                | -                | -         |   -13.41 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1357 | 2024-06-08 | EYEBALLERS        | L   | 0.805      | -            | -                | -                | -         |   -12.85 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1455 | 2024-06-06 | Space             | L   | 0.794      | -            | -                | -                | -         |   -14.18 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1577 | 2024-06-04 | SINNERS           | W   | 0.779      | 0.435        | 0.037 (0.013)    | 0.800 (0.271)    | 0 (0.000) |    16.20 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1624 | 2024-06-02 | GUN5              | L   | 0.765      | -            | -                | -                | -         |   -10.89 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1645 | 2024-06-01 | 3DMAX             | W   | 0.760      | 0.435        | 0.510 (0.168)    | 1.000 (0.330)    | 0 (0.000) |    23.24 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1655 | 2024-06-01 | 777               | W   | 0.759      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.41 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1672 | 2024-05-31 | LEON              | L   | 0.754      | -            | -                | -                | -         |   -18.61 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1688 | 2024-05-31 | Alliance          | W   | 0.751      | 0.435        | 0.017 (0.006)    | 0.282 (0.092)    | 0 (0.000) |     9.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1699 | 2024-05-30 | Insilio           | L   | 0.747      | -            | -                | -                | -         |   -11.44 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1745 | 2024-05-28 | CYBERSHOKE        | W   | 0.734      | 0.372        | 0.039 (0.011)    | 0.339 (0.093)    | 0 (0.000) |    10.33 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1775 | 2024-05-27 | Permitta          | W   | 0.726      | 0.435        | 0.039 (0.012)    | 0.919 (0.290)    | 0 (0.000) |    12.20 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1826 | 2024-05-24 | DMS               | W   | 0.706      | 0.435        | -                | 0.428 (0.131)    | 0 (0.000) |    11.96 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1877 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.694      | 0.435        | 0.031 (0.009)    | 0.537 (0.162)    | 0 (0.000) |    11.77 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1966 | 2024-05-20 | SINNERS           | L   | 0.679      | -            | -                | -                | -         |    -5.38 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     2023 | 2024-05-18 | CPH Wolves        | W   | 0.666      | 0.143        | -                | 0.354 (0.034)    | 0 (0.000) |     7.96 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2188 | 2024-05-14 | LEON              | W   | 0.641      | -            | -                | -                | -         |     5.35 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2219 | 2024-05-13 | WOPA              | W   | 0.633      | -            | -                | -                | -         |     3.96 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2388 | 2024-05-05 | Nemiga            | L   | 0.580      | -            | -                | -                | -         |    -2.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2520 | 2024-04-29 | Nexus             | W   | 0.539      | 0.396        | 0.014 (0.003)    | 0.447 (0.095)    | -         |     8.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2538 | 2024-04-28 | brazylijski luz   | L   | 0.533      | -            | -                | -                | -         |    -9.20 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2541 | 2024-04-28 | LEON              | W   | 0.532      | 0.396        | 0.007 (0.001)    | 0.124 (0.026)    | -         |     4.61 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3434 | 2024-03-23 | FORZE             | L   | 0.293      | -            | -                | -                | -         |    -4.13 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3453 | 2024-03-22 | ex-Guild Eagles   | W   | 0.285      | -            | -                | -                | -         |     3.79 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3498 | 2024-03-20 | TSM               | W   | 0.272      | -            | -                | -                | -         |     2.19 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3725 | 2024-03-10 | 1WIN              | L   | 0.206      | -            | -                | -                | -         |    -2.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3793 | 2024-03-07 | Permitta          | L   | 0.187      | -            | -                | -                | -         |    -2.01 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3863 | 2024-03-05 | FORZE YNG         | W   | 0.174      | -            | -                | -                | -         |     0.36 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,126.39)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.859 | $5,000.00      | $4,294.44       |
| 2024-06-02 |      0.766 | $5,000.00      | $3,831.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
