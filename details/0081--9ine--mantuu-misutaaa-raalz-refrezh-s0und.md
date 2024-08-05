### Roster Details<br />
Team Name: 9INE<br />
Roster: mantuu, misutaaa, raalz, refrezh, s0und<br />
Global Rank: [81](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  930.6<br />
<br />
Final Rank Value (930.6) = Starting Rank Value (911.6) + Head To Head Adjustments (19.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.237[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 911.6
- 400 + ( ( 0.250 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 911.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |       14 | 2024-08-04 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -2.67 | mantuu, misutaaa, raalz, refrezh, s0und |
|           33 |       65 | 2024-08-03 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.36 | mantuu, misutaaa, raalz, refrezh, s0und |
|           32 |       89 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.51 | mantuu, misutaaa, raalz, refrezh, s0und |
|           31 |       98 | 2024-08-02 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.58 | mantuu, misutaaa, raalz, refrezh, s0und |
|           30 |      142 | 2024-08-01 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.86 | mantuu, misutaaa, raalz, refrezh, s0und |
|           29 |      188 | 2024-07-31 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -22.63 | mantuu, misutaaa, raalz, refrezh, s0und |
|           28 |      194 | 2024-07-31 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.60 | mantuu, misutaaa, raalz, refrezh, s0und |
|           27 |      255 | 2024-07-29 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -11.04 | mantuu, misutaaa, raalz, refrezh, s0und |
|           26 |      324 | 2024-07-27 | Aurora Young Blud | W   | 1.000      | 0.435        | 0.003 (0.001)    | 0.499 (0.217)    | 0 (0.000) |    13.01 | mantuu, misutaaa, raalz, refrezh, s0und |
|           25 |      392 | 2024-07-25 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -9.28 | mantuu, misutaaa, raalz, refrezh, s0und |
|           24 |      419 | 2024-07-24 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.37 | mantuu, misutaaa, raalz, refrezh, s0und |
|           23 |      426 | 2024-07-24 | Rebels            | W   | 1.000      | 0.371        | 0.038 (0.014)    | 0.598 (0.222)    | 0 (0.000) |    18.25 | mantuu, misutaaa, raalz, refrezh, s0und |
|           22 |      457 | 2024-07-23 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.83 | mantuu, misutaaa, raalz, refrezh, s0und |
|           21 |      488 | 2024-07-22 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.14 | mantuu, misutaaa, raalz, refrezh, s0und |
|           20 |      514 | 2024-07-21 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.624 (0.231)    | 0 (0.000) |    14.67 | mantuu, misutaaa, raalz, refrezh, s0und |
|           19 |      589 | 2024-07-19 | Insilio           | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.559 (0.207)    | 0 (0.000) |    17.10 | mantuu, misutaaa, raalz, refrezh, s0und |
|           18 |      611 | 2024-07-18 | K10               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.47 | mantuu, misutaaa, raalz, refrezh, s0und |
|           17 |      631 | 2024-07-18 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -5.09 | mantuu, misutaaa, raalz, refrezh, s0und |
|           16 |      681 | 2024-07-17 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.63 | mantuu, misutaaa, raalz, refrezh, s0und |
|           15 |      704 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.520 (0.193)    | -         |    13.50 | mantuu, misutaaa, raalz, refrezh, s0und |
|           14 |      713 | 2024-07-17 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.00 | mantuu, misutaaa, raalz, refrezh, s0und |
|           13 |      748 | 2024-07-16 | CPH Wolves        | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.365 (0.122)    | -         |    12.43 | mantuu, misutaaa, raalz, refrezh, s0und |
|           12 |      799 | 2024-07-15 | B8                | L   | 1.000      | -            | -                | -                | -         |    -5.57 | mantuu, misutaaa, raalz, refrezh, s0und |
|           11 |      839 | 2024-07-13 | ROSOMAHA          | W   | 1.000      | -            | -                | -                | -         |     3.42 | mantuu, misutaaa, raalz, refrezh, s0und |
|           10 |      868 | 2024-07-11 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -17.08 | mantuu, misutaaa, raalz, refrezh, s0und |
|            9 |      890 | 2024-07-10 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -5.38 | mantuu, misutaaa, n0te, raalz, s0und    |
|            8 |      910 | 2024-07-09 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.81 | mantuu, misutaaa, raalz, refrezh, s0und |
|            7 |     1123 | 2024-06-13 | 3DMAX             | L   | 0.847      | -            | -                | -                | -         |    -1.53 | mantuu, misutaaa, raalz, refrezh, s0und |
|            6 |     1233 | 2024-06-09 | 3DMAX             | W   | 0.821      | 0.450        | 0.508 (0.188)    | 1.000 (0.369)    | -         |    24.46 | mantuu, misutaaa, raalz, refrezh, s0und |
|            5 |     1295 | 2024-06-08 | BLEED             | L   | 0.815      | -            | -                | -                | -         |    -1.87 | mantuu, misutaaa, raalz, refrezh, s0und |
|            4 |     1353 | 2024-06-07 | Endpoint          | W   | 0.808      | 0.450        | 0.012 (0.004)    | 0.520 (0.189)    | -         |    11.27 | mantuu, misutaaa, raalz, refrezh, s0und |
|            3 |     1379 | 2024-06-07 | Nexus             | W   | 0.806      | 0.500        | 0.014 (0.006)    | 0.464 (0.187)    | -         |     8.09 | mantuu, misutaaa, raalz, refrezh, s0und |
|            2 |     1443 | 2024-06-06 | EYEBALLERS        | L   | 0.800      | -            | -                | -                | -         |   -12.70 | mantuu, misutaaa, raalz, refrezh, s0und |
|            1 |     1477 | 2024-06-05 | Rebels            | L   | 0.795      | -            | -                | -                | -         |    -9.27 | mantuu, misutaaa, raalz, refrezh, s0und |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,181.94)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.873 | $2,500.00      | $2,181.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
