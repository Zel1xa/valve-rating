### Roster Details<br />
Team Name: 9INE<br />
Roster: mantuu, misutaaa, raalz, refrezh, s0und<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  934.2<br />
<br />
Final Rank Value (934.2) = Starting Rank Value (913.3) + Head To Head Adjustments (20.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.387[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 913.3
- 400 + ( ( 0.250 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 913.3


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
|           34 |       35 | 2024-08-04 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -2.67 | mantuu, misutaaa, raalz, refrezh, s0und |
|           33 |       86 | 2024-08-03 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.31 | mantuu, misutaaa, raalz, refrezh, s0und |
|           32 |      110 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.60 | mantuu, misutaaa, raalz, refrezh, s0und |
|           31 |      119 | 2024-08-02 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.53 | mantuu, misutaaa, raalz, refrezh, s0und |
|           30 |      163 | 2024-08-01 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.90 | mantuu, misutaaa, raalz, refrezh, s0und |
|           29 |      209 | 2024-07-31 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -22.56 | mantuu, misutaaa, raalz, refrezh, s0und |
|           28 |      215 | 2024-07-31 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.37 | mantuu, misutaaa, raalz, refrezh, s0und |
|           27 |      276 | 2024-07-29 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -11.15 | mantuu, misutaaa, raalz, refrezh, s0und |
|           26 |      345 | 2024-07-27 | Aurora Young Blud | W   | 1.000      | 0.435        | 0.019 (0.008)    | 0.521 (0.227)    | 0 (0.000) |    14.38 | mantuu, misutaaa, raalz, refrezh, s0und |
|           25 |      413 | 2024-07-25 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -9.26 | mantuu, misutaaa, raalz, refrezh, s0und |
|           24 |      440 | 2024-07-24 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.66 | mantuu, misutaaa, raalz, refrezh, s0und |
|           23 |      447 | 2024-07-24 | Rebels            | W   | 1.000      | 0.371        | 0.038 (0.014)    | 0.578 (0.214)    | 0 (0.000) |    18.23 | mantuu, misutaaa, raalz, refrezh, s0und |
|           22 |      478 | 2024-07-23 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.80 | mantuu, misutaaa, raalz, refrezh, s0und |
|           21 |      509 | 2024-07-22 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.13 | mantuu, misutaaa, raalz, refrezh, s0und |
|           20 |      535 | 2024-07-21 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.641 (0.237)    | 0 (0.000) |    14.73 | mantuu, misutaaa, raalz, refrezh, s0und |
|           19 |      610 | 2024-07-19 | Insilio           | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.539 (0.200)    | 0 (0.000) |    17.24 | mantuu, misutaaa, raalz, refrezh, s0und |
|           18 |      632 | 2024-07-18 | K10               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.45 | mantuu, misutaaa, raalz, refrezh, s0und |
|           17 |      652 | 2024-07-18 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -5.10 | mantuu, misutaaa, raalz, refrezh, s0und |
|           16 |      702 | 2024-07-17 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.60 | mantuu, misutaaa, raalz, refrezh, s0und |
|           15 |      725 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.502 (0.186)    | -         |    13.74 | mantuu, misutaaa, raalz, refrezh, s0und |
|           14 |      734 | 2024-07-17 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.02 | mantuu, misutaaa, raalz, refrezh, s0und |
|           13 |      769 | 2024-07-16 | CPH Wolves        | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.353 (0.118)    | -         |    12.38 | mantuu, misutaaa, raalz, refrezh, s0und |
|           12 |      820 | 2024-07-15 | B8                | L   | 1.000      | -            | -                | -                | -         |    -5.58 | mantuu, misutaaa, raalz, refrezh, s0und |
|           11 |      860 | 2024-07-13 | ROSOMAHA          | W   | 1.000      | -            | -                | -                | -         |     3.41 | mantuu, misutaaa, raalz, refrezh, s0und |
|           10 |      889 | 2024-07-11 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -17.10 | mantuu, misutaaa, raalz, refrezh, s0und |
|            9 |      911 | 2024-07-10 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -5.41 | mantuu, misutaaa, n0te, raalz, s0und    |
|            8 |      931 | 2024-07-09 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.82 | mantuu, misutaaa, raalz, refrezh, s0und |
|            7 |     1144 | 2024-06-13 | 3DMAX             | L   | 0.841      | -            | -                | -                | -         |    -1.49 | mantuu, misutaaa, raalz, refrezh, s0und |
|            6 |     1254 | 2024-06-09 | 3DMAX             | W   | 0.814      | 0.450        | 0.510 (0.187)    | 1.000 (0.367)    | -         |    24.30 | mantuu, misutaaa, raalz, refrezh, s0und |
|            5 |     1316 | 2024-06-08 | BLEED             | L   | 0.808      | -            | -                | -                | -         |    -1.86 | mantuu, misutaaa, raalz, refrezh, s0und |
|            4 |     1374 | 2024-06-07 | Endpoint          | W   | 0.802      | 0.450        | 0.012 (0.004)    | 0.502 (0.181)    | -         |    11.16 | mantuu, misutaaa, raalz, refrezh, s0und |
|            3 |     1400 | 2024-06-07 | Nexus             | W   | 0.800      | 0.500        | 0.014 (0.005)    | 0.447 (0.179)    | -         |     8.08 | mantuu, misutaaa, raalz, refrezh, s0und |
|            2 |     1464 | 2024-06-06 | EYEBALLERS        | L   | 0.793      | -            | -                | -                | -         |   -12.48 | mantuu, misutaaa, raalz, refrezh, s0und |
|            1 |     1498 | 2024-06-05 | Rebels            | L   | 0.788      | -            | -                | -                | -         |    -9.23 | mantuu, misutaaa, raalz, refrezh, s0und |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,165.74)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.866 | $2,500.00      | $2,165.74       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
