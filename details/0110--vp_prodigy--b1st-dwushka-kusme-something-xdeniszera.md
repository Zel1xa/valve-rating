### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [110](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [81]( ../standings_europe.md)<br />
<br />
Final Rank Value:  840.2<br />
<br />
Final Rank Value (840.2) = Starting Rank Value (876.3) + Head To Head Adjustments (-36.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.159[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.231<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 876.3
- 400 + ( ( 0.231 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 876.3


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
|           34 |      456 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.71 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      578 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      670 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.45 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |      934 | 2024-06-15 | ARCRED            | L   | 0.886      | -            | -                | -                | -         |   -12.55 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |      995 | 2024-06-13 | HOTU              | W   | 0.874      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.76 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1004 | 2024-06-13 | 3DMAX             | L   | 0.873      | -            | -                | -                | -         |    -1.46 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1144 | 2024-06-09 | Illuminar         | L   | 0.846      | -            | -                | -                | -         |   -13.56 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1201 | 2024-06-08 | EYEBALLERS        | L   | 0.840      | -            | -                | -                | -         |   -13.45 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1307 | 2024-06-06 | Space             | L   | 0.828      | -            | -                | -                | -         |   -14.74 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1432 | 2024-06-04 | SINNERS           | W   | 0.813      | 0.435        | 0.038 (0.013)    | 0.768 (0.272)    | 0 (0.000) |    15.82 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1480 | 2024-06-02 | GUN5              | L   | 0.799      | -            | -                | -                | -         |   -10.77 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1501 | 2024-06-01 | 3DMAX             | W   | 0.794      | 0.435        | 0.505 (0.174)    | 1.000 (0.345)    | 0 (0.000) |    24.22 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1511 | 2024-06-01 | 777               | W   | 0.793      | 0.143        | 0.016 (0.002)    | -                | 0 (0.000) |     6.75 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1528 | 2024-05-31 | LEON              | L   | 0.788      | -            | -                | -                | -         |   -19.48 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1544 | 2024-05-31 | Alliance          | W   | 0.786      | 0.435        | 0.014 (0.005)    | 0.319 (0.109)    | 0 (0.000) |    10.16 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1555 | 2024-05-30 | Insilio           | L   | 0.782      | -            | -                | -                | -         |   -12.06 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1601 | 2024-05-28 | CYBERSHOKE        | W   | 0.769      | 0.372        | 0.040 (0.011)    | 0.348 (0.100)    | 0 (0.000) |    10.78 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1631 | 2024-05-27 | Permitta          | W   | 0.761      | 0.435        | 0.024 (0.008)    | 0.801 (0.265)    | 0 (0.000) |    11.93 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1684 | 2024-05-24 | DMS               | W   | 0.741      | 0.435        | -                | 0.447 (0.144)    | 0 (0.000) |    12.42 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1735 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.728      | 0.435        | 0.032 (0.010)    | 0.564 (0.178)    | 0 (0.000) |    11.76 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1844 | 2024-05-20 | SINNERS           | L   | 0.713      | -            | -                | -                | -         |    -6.78 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     1907 | 2024-05-18 | CPH Wolves        | W   | 0.700      | 0.143        | -                | 0.360 (0.036)    | 0 (0.000) |     8.26 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2078 | 2024-05-14 | LEON              | W   | 0.675      | -            | -                | -                | -         |     5.58 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2112 | 2024-05-13 | WOPA              | W   | 0.668      | -            | -                | -                | -         |     4.11 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2283 | 2024-05-05 | Nemiga            | L   | 0.614      | -            | -                | -                | -         |    -3.12 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2418 | 2024-04-29 | Nexus             | W   | 0.573      | 0.396        | 0.014 (0.003)    | 0.504 (0.114)    | -         |     8.46 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2436 | 2024-04-28 | brazylijski luz   | L   | 0.568      | -            | -                | -                | -         |    -9.50 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2439 | 2024-04-28 | LEON              | W   | 0.567      | 0.396        | 0.007 (0.002)    | 0.131 (0.029)    | -         |     4.87 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3356 | 2024-03-23 | FORZE             | L   | 0.327      | -            | -                | -                | -         |    -4.49 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3375 | 2024-03-22 | ex-Guild Eagles   | W   | 0.320      | -            | -                | -                | -         |     4.35 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3420 | 2024-03-20 | TSM               | W   | 0.306      | -            | -                | -                | -         |     2.49 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3652 | 2024-03-10 | 1WIN              | L   | 0.241      | -            | -                | -                | -         |    -3.62 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3721 | 2024-03-07 | Permitta          | L   | 0.222      | -            | -                | -                | -         |    -2.77 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3796 | 2024-03-05 | FORZE YNG         | W   | 0.208      | -            | -                | -                | -         |     0.42 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,470.83)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.893 | $5,000.00      | $4,466.67       |
| 2024-06-02 |      0.801 | $5,000.00      | $4,004.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
