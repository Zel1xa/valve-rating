### Roster Details<br />
Team Name: 9INE<br />
Roster: mantuu, misutaaa, raalz, refrezh, s0und<br />
Global Rank: [79](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  930.3<br />
<br />
Final Rank Value (930.3) = Starting Rank Value (909.6) + Head To Head Adjustments (20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.235[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.249<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 909.6
- 400 + ( ( 0.249 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 909.6


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
|           33 |       18 | 2024-08-03 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.39 | mantuu, misutaaa, raalz, refrezh, s0und |
|           32 |       42 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.46 | mantuu, misutaaa, raalz, refrezh, s0und |
|           31 |       50 | 2024-08-02 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.62 | mantuu, misutaaa, raalz, refrezh, s0und |
|           30 |       93 | 2024-08-01 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -9.04 | mantuu, misutaaa, raalz, refrezh, s0und |
|           29 |      139 | 2024-07-31 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -22.74 | mantuu, misutaaa, raalz, refrezh, s0und |
|           28 |      144 | 2024-07-31 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.62 | mantuu, misutaaa, raalz, refrezh, s0und |
|           27 |      206 | 2024-07-29 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -11.03 | mantuu, misutaaa, raalz, refrezh, s0und |
|           26 |      275 | 2024-07-27 | Aurora Young Blud | W   | 1.000      | 0.435        | 0.003 (0.001)    | 0.420 (0.182)    | 0 (0.000) |    12.28 | mantuu, misutaaa, raalz, refrezh, s0und |
|           25 |      343 | 2024-07-25 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -9.57 | mantuu, misutaaa, raalz, refrezh, s0und |
|           24 |      370 | 2024-07-24 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.44 | mantuu, misutaaa, raalz, refrezh, s0und |
|           23 |      377 | 2024-07-24 | Rebels            | W   | 1.000      | 0.371        | 0.038 (0.014)    | 0.599 (0.222)    | 0 (0.000) |    18.28 | mantuu, misutaaa, raalz, refrezh, s0und |
|           22 |      408 | 2024-07-23 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -9.12 | mantuu, misutaaa, raalz, refrezh, s0und |
|           21 |      439 | 2024-07-22 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.14 | mantuu, misutaaa, raalz, refrezh, s0und |
|           20 |      465 | 2024-07-21 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.625 (0.231)    | 0 (0.000) |    14.67 | mantuu, misutaaa, raalz, refrezh, s0und |
|           19 |      540 | 2024-07-19 | Insilio           | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.561 (0.208)    | 0 (0.000) |    17.11 | mantuu, misutaaa, raalz, refrezh, s0und |
|           18 |      562 | 2024-07-18 | K10               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.52 | mantuu, misutaaa, raalz, refrezh, s0und |
|           17 |      582 | 2024-07-18 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -5.22 | mantuu, misutaaa, raalz, refrezh, s0und |
|           16 |      632 | 2024-07-17 | Astralis Talent   | W   | 1.000      | 0.143        | 0.009 (0.001)    | -                | 0 (0.000) |     7.63 | mantuu, misutaaa, raalz, refrezh, s0und |
|           15 |      656 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.522 (0.194)    | -         |    13.74 | mantuu, misutaaa, raalz, refrezh, s0und |
|           14 |      665 | 2024-07-17 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.97 | mantuu, misutaaa, raalz, refrezh, s0und |
|           13 |      700 | 2024-07-16 | CPH Wolves        | W   | 1.000      | 0.333        | -                | 0.364 (0.121)    | -         |    12.45 | mantuu, misutaaa, raalz, refrezh, s0und |
|           12 |      750 | 2024-07-15 | B8                | L   | 1.000      | -            | -                | -                | -         |    -5.56 | mantuu, misutaaa, raalz, refrezh, s0und |
|           11 |      790 | 2024-07-13 | ROSOMAHA          | W   | 1.000      | -            | -                | -                | -         |     3.45 | mantuu, misutaaa, raalz, refrezh, s0und |
|           10 |      819 | 2024-07-11 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -17.08 | mantuu, misutaaa, raalz, refrezh, s0und |
|            9 |      841 | 2024-07-10 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -5.41 | mantuu, misutaaa, n0te, raalz, s0und    |
|            8 |      861 | 2024-07-09 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.93 | mantuu, misutaaa, raalz, refrezh, s0und |
|            7 |     1074 | 2024-06-13 | 3DMAX             | L   | 0.855      | -            | -                | -                | -         |    -1.59 | mantuu, misutaaa, raalz, refrezh, s0und |
|            6 |     1184 | 2024-06-09 | 3DMAX             | W   | 0.828      | 0.450        | 0.506 (0.189)    | 1.000 (0.373)    | -         |    24.64 | mantuu, misutaaa, raalz, refrezh, s0und |
|            5 |     1246 | 2024-06-08 | BLEED             | L   | 0.822      | -            | -                | -                | -         |    -1.92 | mantuu, misutaaa, raalz, refrezh, s0und |
|            4 |     1304 | 2024-06-07 | Endpoint          | W   | 0.816      | 0.450        | 0.012 (0.004)    | 0.522 (0.192)    | -         |    11.37 | mantuu, misutaaa, raalz, refrezh, s0und |
|            3 |     1330 | 2024-06-07 | Nexus             | W   | 0.814      | 0.500        | 0.014 (0.006)    | 0.465 (0.189)    | -         |     8.19 | mantuu, misutaaa, raalz, refrezh, s0und |
|            2 |     1394 | 2024-06-06 | EYEBALLERS        | L   | 0.807      | -            | -                | -                | -         |   -12.65 | mantuu, misutaaa, raalz, refrezh, s0und |
|            1 |     1428 | 2024-06-05 | Rebels            | L   | 0.802      | -            | -                | -                | -         |    -9.29 | mantuu, misutaaa, raalz, refrezh, s0und |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,200.69)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.880 | $2,500.00      | $2,200.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
