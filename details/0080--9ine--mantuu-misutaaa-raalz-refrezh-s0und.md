### Roster Details<br />
Team Name: 9INE<br />
Roster: mantuu, misutaaa, raalz, refrezh, s0und<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  933.0<br />
<br />
Final Rank Value (933.0) = Starting Rank Value (912.3) + Head To Head Adjustments (20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 912.3
- 400 + ( ( 0.250 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 912.3


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
|           34 |       29 | 2024-08-04 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -2.66 | mantuu, misutaaa, raalz, refrezh, s0und |
|           33 |       80 | 2024-08-03 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.36 | mantuu, misutaaa, raalz, refrezh, s0und |
|           32 |      104 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.55 | mantuu, misutaaa, raalz, refrezh, s0und |
|           31 |      113 | 2024-08-02 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.58 | mantuu, misutaaa, raalz, refrezh, s0und |
|           30 |      157 | 2024-08-01 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.89 | mantuu, misutaaa, raalz, refrezh, s0und |
|           29 |      203 | 2024-07-31 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -22.54 | mantuu, misutaaa, raalz, refrezh, s0und |
|           28 |      209 | 2024-07-31 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.31 | mantuu, misutaaa, raalz, refrezh, s0und |
|           27 |      270 | 2024-07-29 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -11.07 | mantuu, misutaaa, raalz, refrezh, s0und |
|           26 |      339 | 2024-07-27 | Aurora Young Blud | W   | 1.000      | 0.435        | 0.003 (0.001)    | 0.533 (0.232)    | 0 (0.000) |    13.55 | mantuu, misutaaa, raalz, refrezh, s0und |
|           25 |      407 | 2024-07-25 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -9.28 | mantuu, misutaaa, raalz, refrezh, s0und |
|           24 |      434 | 2024-07-24 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.62 | mantuu, misutaaa, raalz, refrezh, s0und |
|           23 |      441 | 2024-07-24 | Rebels            | W   | 1.000      | 0.371        | 0.038 (0.014)    | 0.591 (0.219)    | 0 (0.000) |    18.24 | mantuu, misutaaa, raalz, refrezh, s0und |
|           22 |      472 | 2024-07-23 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.82 | mantuu, misutaaa, raalz, refrezh, s0und |
|           21 |      503 | 2024-07-22 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.13 | mantuu, misutaaa, raalz, refrezh, s0und |
|           20 |      529 | 2024-07-21 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.616 (0.228)    | 0 (0.000) |    14.76 | mantuu, misutaaa, raalz, refrezh, s0und |
|           19 |      604 | 2024-07-19 | Insilio           | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.552 (0.204)    | 0 (0.000) |    17.24 | mantuu, misutaaa, raalz, refrezh, s0und |
|           18 |      626 | 2024-07-18 | K10               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.45 | mantuu, misutaaa, raalz, refrezh, s0und |
|           17 |      646 | 2024-07-18 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -5.10 | mantuu, misutaaa, raalz, refrezh, s0und |
|           16 |      696 | 2024-07-17 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.57 | mantuu, misutaaa, raalz, refrezh, s0und |
|           15 |      719 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.513 (0.190)    | -         |    13.78 | mantuu, misutaaa, raalz, refrezh, s0und |
|           14 |      728 | 2024-07-17 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.00 | mantuu, misutaaa, raalz, refrezh, s0und |
|           13 |      763 | 2024-07-16 | CPH Wolves        | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.361 (0.120)    | -         |    12.41 | mantuu, misutaaa, raalz, refrezh, s0und |
|           12 |      814 | 2024-07-15 | B8                | L   | 1.000      | -            | -                | -                | -         |    -5.57 | mantuu, misutaaa, raalz, refrezh, s0und |
|           11 |      854 | 2024-07-13 | ROSOMAHA          | W   | 1.000      | -            | -                | -                | -         |     3.41 | mantuu, misutaaa, raalz, refrezh, s0und |
|           10 |      883 | 2024-07-11 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -17.05 | mantuu, misutaaa, raalz, refrezh, s0und |
|            9 |      905 | 2024-07-10 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -5.39 | mantuu, misutaaa, n0te, raalz, s0und    |
|            8 |      925 | 2024-07-09 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.82 | mantuu, misutaaa, raalz, refrezh, s0und |
|            7 |     1138 | 2024-06-13 | 3DMAX             | L   | 0.842      | -            | -                | -                | -         |    -1.49 | mantuu, misutaaa, raalz, refrezh, s0und |
|            6 |     1248 | 2024-06-09 | 3DMAX             | W   | 0.815      | 0.450        | 0.509 (0.187)    | 1.000 (0.367)    | -         |    24.32 | mantuu, misutaaa, raalz, refrezh, s0und |
|            5 |     1310 | 2024-06-08 | BLEED             | L   | 0.809      | -            | -                | -                | -         |    -1.85 | mantuu, misutaaa, raalz, refrezh, s0und |
|            4 |     1368 | 2024-06-07 | Endpoint          | W   | 0.802      | 0.450        | 0.012 (0.004)    | 0.513 (0.185)    | -         |    11.22 | mantuu, misutaaa, raalz, refrezh, s0und |
|            3 |     1394 | 2024-06-07 | Nexus             | W   | 0.801      | 0.500        | 0.014 (0.005)    | 0.457 (0.183)    | -         |     8.11 | mantuu, misutaaa, raalz, refrezh, s0und |
|            2 |     1458 | 2024-06-06 | EYEBALLERS        | L   | 0.794      | -            | -                | -                | -         |   -12.45 | mantuu, misutaaa, raalz, refrezh, s0und |
|            1 |     1492 | 2024-06-05 | Rebels            | L   | 0.789      | -            | -                | -                | -         |    -9.21 | mantuu, misutaaa, raalz, refrezh, s0und |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,167.36)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.867 | $2,500.00      | $2,167.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
