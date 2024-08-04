### Roster Details<br />
Team Name: 9INE<br />
Roster: mantuu, misutaaa, raalz, refrezh, s0und<br />
Global Rank: [81](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  932.6<br />
<br />
Final Rank Value (932.6) = Starting Rank Value (910.5) + Head To Head Adjustments (22.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 910.5
- 400 + ( ( 0.250 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 910.5


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
|           33 |       48 | 2024-08-03 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.36 | mantuu, misutaaa, raalz, refrezh, s0und |
|           32 |       72 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.42 | mantuu, misutaaa, raalz, refrezh, s0und |
|           31 |       81 | 2024-08-02 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.59 | mantuu, misutaaa, raalz, refrezh, s0und |
|           30 |      125 | 2024-08-01 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.90 | mantuu, misutaaa, raalz, refrezh, s0und |
|           29 |      171 | 2024-07-31 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -22.61 | mantuu, misutaaa, raalz, refrezh, s0und |
|           28 |      176 | 2024-07-31 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.59 | mantuu, misutaaa, raalz, refrezh, s0und |
|           27 |      238 | 2024-07-29 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -11.04 | mantuu, misutaaa, raalz, refrezh, s0und |
|           26 |      307 | 2024-07-27 | Aurora Young Blud | W   | 1.000      | 0.435        | 0.003 (0.001)    | 0.460 (0.200)    | 0 (0.000) |    12.99 | mantuu, misutaaa, raalz, refrezh, s0und |
|           25 |      375 | 2024-07-25 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -9.34 | mantuu, misutaaa, raalz, refrezh, s0und |
|           24 |      402 | 2024-07-24 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.31 | mantuu, misutaaa, raalz, refrezh, s0und |
|           23 |      409 | 2024-07-24 | Rebels            | W   | 1.000      | 0.371        | 0.038 (0.014)    | 0.600 (0.222)    | 0 (0.000) |    18.30 | mantuu, misutaaa, raalz, refrezh, s0und |
|           22 |      440 | 2024-07-23 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.90 | mantuu, misutaaa, raalz, refrezh, s0und |
|           21 |      471 | 2024-07-22 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.14 | mantuu, misutaaa, raalz, refrezh, s0und |
|           20 |      497 | 2024-07-21 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.625 (0.232)    | 0 (0.000) |    14.71 | mantuu, misutaaa, raalz, refrezh, s0und |
|           19 |      572 | 2024-07-19 | Insilio           | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.561 (0.208)    | 0 (0.000) |    17.14 | mantuu, misutaaa, raalz, refrezh, s0und |
|           18 |      594 | 2024-07-18 | K10               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.50 | mantuu, misutaaa, raalz, refrezh, s0und |
|           17 |      614 | 2024-07-18 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -5.11 | mantuu, misutaaa, raalz, refrezh, s0und |
|           16 |      664 | 2024-07-17 | Astralis Talent   | W   | 1.000      | 0.143        | 0.009 (0.001)    | -                | 0 (0.000) |     7.63 | mantuu, misutaaa, raalz, refrezh, s0und |
|           15 |      687 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.522 (0.194)    | -         |    13.51 | mantuu, misutaaa, raalz, refrezh, s0und |
|           14 |      696 | 2024-07-17 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.95 | mantuu, misutaaa, raalz, refrezh, s0und |
|           13 |      731 | 2024-07-16 | CPH Wolves        | W   | 1.000      | 0.333        | -                | 0.365 (0.122)    | -         |    12.43 | mantuu, misutaaa, raalz, refrezh, s0und |
|           12 |      782 | 2024-07-15 | B8                | L   | 1.000      | -            | -                | -                | -         |    -5.54 | mantuu, misutaaa, raalz, refrezh, s0und |
|           11 |      822 | 2024-07-13 | ROSOMAHA          | W   | 1.000      | -            | -                | -                | -         |     3.44 | mantuu, misutaaa, raalz, refrezh, s0und |
|           10 |      851 | 2024-07-11 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -17.06 | mantuu, misutaaa, raalz, refrezh, s0und |
|            9 |      873 | 2024-07-10 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -5.36 | mantuu, misutaaa, n0te, raalz, s0und    |
|            8 |      893 | 2024-07-09 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.81 | mantuu, misutaaa, raalz, refrezh, s0und |
|            7 |     1106 | 2024-06-13 | 3DMAX             | L   | 0.853      | -            | -                | -                | -         |    -1.57 | mantuu, misutaaa, raalz, refrezh, s0und |
|            6 |     1216 | 2024-06-09 | 3DMAX             | W   | 0.827      | 0.450        | 0.506 (0.188)    | 1.000 (0.372)    | -         |    24.61 | mantuu, misutaaa, raalz, refrezh, s0und |
|            5 |     1278 | 2024-06-08 | BLEED             | L   | 0.820      | -            | -                | -                | -         |    -1.90 | mantuu, misutaaa, raalz, refrezh, s0und |
|            4 |     1336 | 2024-06-07 | Endpoint          | W   | 0.814      | 0.450        | 0.012 (0.004)    | 0.522 (0.191)    | -         |    11.37 | mantuu, misutaaa, raalz, refrezh, s0und |
|            3 |     1362 | 2024-06-07 | Nexus             | W   | 0.812      | 0.500        | 0.014 (0.006)    | 0.465 (0.189)    | -         |     8.15 | mantuu, misutaaa, raalz, refrezh, s0und |
|            2 |     1426 | 2024-06-06 | EYEBALLERS        | L   | 0.805      | -            | -                | -                | -         |   -12.75 | mantuu, misutaaa, raalz, refrezh, s0und |
|            1 |     1460 | 2024-06-05 | Rebels            | L   | 0.800      | -            | -                | -                | -         |    -9.27 | mantuu, misutaaa, raalz, refrezh, s0und |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,196.24)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.878 | $2,500.00      | $2,196.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
