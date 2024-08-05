### Roster Details<br />
Team Name: 9INE<br />
Roster: mantuu, misutaaa, raalz, refrezh, s0und<br />
Global Rank: [81](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  929.8<br />
<br />
Final Rank Value (929.8) = Starting Rank Value (910.6) + Head To Head Adjustments (19.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 910.6
- 400 + ( ( 0.250 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 910.6


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
|           34 |        2 | 2024-08-04 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -2.67 | mantuu, misutaaa, raalz, refrezh, s0und |
|           33 |       52 | 2024-08-03 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.36 | mantuu, misutaaa, raalz, refrezh, s0und |
|           32 |       76 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.50 | mantuu, misutaaa, raalz, refrezh, s0und |
|           31 |       85 | 2024-08-02 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.59 | mantuu, misutaaa, raalz, refrezh, s0und |
|           30 |      129 | 2024-08-01 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.90 | mantuu, misutaaa, raalz, refrezh, s0und |
|           29 |      175 | 2024-07-31 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -22.61 | mantuu, misutaaa, raalz, refrezh, s0und |
|           28 |      181 | 2024-07-31 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.60 | mantuu, misutaaa, raalz, refrezh, s0und |
|           27 |      242 | 2024-07-29 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -11.04 | mantuu, misutaaa, raalz, refrezh, s0und |
|           26 |      311 | 2024-07-27 | Aurora Young Blud | W   | 1.000      | 0.435        | 0.003 (0.001)    | 0.460 (0.200)    | 0 (0.000) |    12.99 | mantuu, misutaaa, raalz, refrezh, s0und |
|           25 |      379 | 2024-07-25 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -9.35 | mantuu, misutaaa, raalz, refrezh, s0und |
|           24 |      406 | 2024-07-24 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.30 | mantuu, misutaaa, raalz, refrezh, s0und |
|           23 |      413 | 2024-07-24 | Rebels            | W   | 1.000      | 0.371        | 0.038 (0.014)    | 0.600 (0.222)    | 0 (0.000) |    18.29 | mantuu, misutaaa, raalz, refrezh, s0und |
|           22 |      444 | 2024-07-23 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.90 | mantuu, misutaaa, raalz, refrezh, s0und |
|           21 |      475 | 2024-07-22 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.14 | mantuu, misutaaa, raalz, refrezh, s0und |
|           20 |      501 | 2024-07-21 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.625 (0.232)    | 0 (0.000) |    14.70 | mantuu, misutaaa, raalz, refrezh, s0und |
|           19 |      576 | 2024-07-19 | Insilio           | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.561 (0.208)    | 0 (0.000) |    17.12 | mantuu, misutaaa, raalz, refrezh, s0und |
|           18 |      598 | 2024-07-18 | K10               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.50 | mantuu, misutaaa, raalz, refrezh, s0und |
|           17 |      618 | 2024-07-18 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -5.11 | mantuu, misutaaa, raalz, refrezh, s0und |
|           16 |      668 | 2024-07-17 | Astralis Talent   | W   | 1.000      | 0.143        | 0.009 (0.001)    | -                | 0 (0.000) |     7.64 | mantuu, misutaaa, raalz, refrezh, s0und |
|           15 |      691 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.522 (0.193)    | -         |    13.50 | mantuu, misutaaa, raalz, refrezh, s0und |
|           14 |      700 | 2024-07-17 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.96 | mantuu, misutaaa, raalz, refrezh, s0und |
|           13 |      735 | 2024-07-16 | CPH Wolves        | W   | 1.000      | 0.333        | -                | 0.365 (0.122)    | -         |    12.42 | mantuu, misutaaa, raalz, refrezh, s0und |
|           12 |      786 | 2024-07-15 | B8                | L   | 1.000      | -            | -                | -                | -         |    -5.55 | mantuu, misutaaa, raalz, refrezh, s0und |
|           11 |      826 | 2024-07-13 | ROSOMAHA          | W   | 1.000      | -            | -                | -                | -         |     3.44 | mantuu, misutaaa, raalz, refrezh, s0und |
|           10 |      855 | 2024-07-11 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -17.07 | mantuu, misutaaa, raalz, refrezh, s0und |
|            9 |      877 | 2024-07-10 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -5.36 | mantuu, misutaaa, n0te, raalz, s0und    |
|            8 |      897 | 2024-07-09 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.82 | mantuu, misutaaa, raalz, refrezh, s0und |
|            7 |     1110 | 2024-06-13 | 3DMAX             | L   | 0.851      | -            | -                | -                | -         |    -1.55 | mantuu, misutaaa, raalz, refrezh, s0und |
|            6 |     1220 | 2024-06-09 | 3DMAX             | W   | 0.824      | 0.450        | 0.507 (0.188)    | 1.000 (0.371)    | -         |    24.55 | mantuu, misutaaa, raalz, refrezh, s0und |
|            5 |     1282 | 2024-06-08 | BLEED             | L   | 0.818      | -            | -                | -                | -         |    -1.89 | mantuu, misutaaa, raalz, refrezh, s0und |
|            4 |     1340 | 2024-06-07 | Endpoint          | W   | 0.811      | 0.450        | 0.012 (0.004)    | 0.522 (0.191)    | -         |    11.33 | mantuu, misutaaa, raalz, refrezh, s0und |
|            3 |     1366 | 2024-06-07 | Nexus             | W   | 0.810      | 0.500        | 0.014 (0.006)    | 0.465 (0.188)    | -         |     8.12 | mantuu, misutaaa, raalz, refrezh, s0und |
|            2 |     1430 | 2024-06-06 | EYEBALLERS        | L   | 0.803      | -            | -                | -                | -         |   -12.72 | mantuu, misutaaa, raalz, refrezh, s0und |
|            1 |     1464 | 2024-06-05 | Rebels            | L   | 0.798      | -            | -                | -                | -         |    -9.26 | mantuu, misutaaa, raalz, refrezh, s0und |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,190.28)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.876 | $2,500.00      | $2,190.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
