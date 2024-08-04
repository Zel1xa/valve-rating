### Roster Details<br />
Team Name: 9INE<br />
Roster: mantuu, misutaaa, raalz, refrezh, s0und<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  932.4<br />
<br />
Final Rank Value (932.4) = Starting Rank Value (910.5) + Head To Head Adjustments (21.9)<br />

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
- 400 + ( ( 0.250 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 910.5


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
|           33 |       26 | 2024-08-03 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.35 | mantuu, misutaaa, raalz, refrezh, s0und |
|           32 |       50 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.48 | mantuu, misutaaa, raalz, refrezh, s0und |
|           31 |       59 | 2024-08-02 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.58 | mantuu, misutaaa, raalz, refrezh, s0und |
|           30 |      101 | 2024-08-01 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.96 | mantuu, misutaaa, raalz, refrezh, s0und |
|           29 |      147 | 2024-07-31 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -22.56 | mantuu, misutaaa, raalz, refrezh, s0und |
|           28 |      151 | 2024-07-31 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.42 | mantuu, misutaaa, raalz, refrezh, s0und |
|           27 |      214 | 2024-07-29 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -11.06 | mantuu, misutaaa, raalz, refrezh, s0und |
|           26 |      283 | 2024-07-27 | Aurora Young Blud | W   | 1.000      | 0.435        | 0.003 (0.001)    | 0.459 (0.200)    | 0 (0.000) |    13.00 | mantuu, misutaaa, raalz, refrezh, s0und |
|           25 |      351 | 2024-07-25 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -9.41 | mantuu, misutaaa, raalz, refrezh, s0und |
|           24 |      378 | 2024-07-24 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.47 | mantuu, misutaaa, raalz, refrezh, s0und |
|           23 |      385 | 2024-07-24 | Rebels            | W   | 1.000      | 0.371        | 0.038 (0.014)    | 0.599 (0.222)    | 0 (0.000) |    18.27 | mantuu, misutaaa, raalz, refrezh, s0und |
|           22 |      416 | 2024-07-23 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.96 | mantuu, misutaaa, raalz, refrezh, s0und |
|           21 |      447 | 2024-07-22 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.13 | mantuu, misutaaa, raalz, refrezh, s0und |
|           20 |      473 | 2024-07-21 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.625 (0.231)    | 0 (0.000) |    14.65 | mantuu, misutaaa, raalz, refrezh, s0und |
|           19 |      548 | 2024-07-19 | Insilio           | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.561 (0.208)    | 0 (0.000) |    17.15 | mantuu, misutaaa, raalz, refrezh, s0und |
|           18 |      570 | 2024-07-18 | K10               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.50 | mantuu, misutaaa, raalz, refrezh, s0und |
|           17 |      590 | 2024-07-18 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -5.23 | mantuu, misutaaa, raalz, refrezh, s0und |
|           16 |      640 | 2024-07-17 | Astralis Talent   | W   | 1.000      | 0.143        | 0.009 (0.001)    | -                | 0 (0.000) |     7.63 | mantuu, misutaaa, raalz, refrezh, s0und |
|           15 |      664 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.522 (0.194)    | -         |    13.73 | mantuu, misutaaa, raalz, refrezh, s0und |
|           14 |      673 | 2024-07-17 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.98 | mantuu, misutaaa, raalz, refrezh, s0und |
|           13 |      708 | 2024-07-16 | CPH Wolves        | W   | 1.000      | 0.333        | -                | 0.364 (0.121)    | -         |    12.42 | mantuu, misutaaa, raalz, refrezh, s0und |
|           12 |      758 | 2024-07-15 | B8                | L   | 1.000      | -            | -                | -                | -         |    -5.57 | mantuu, misutaaa, raalz, refrezh, s0und |
|           11 |      798 | 2024-07-13 | ROSOMAHA          | W   | 1.000      | -            | -                | -                | -         |     3.44 | mantuu, misutaaa, raalz, refrezh, s0und |
|           10 |      827 | 2024-07-11 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -17.11 | mantuu, misutaaa, raalz, refrezh, s0und |
|            9 |      849 | 2024-07-10 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -5.38 | mantuu, misutaaa, n0te, raalz, s0und    |
|            8 |      869 | 2024-07-09 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.95 | mantuu, misutaaa, raalz, refrezh, s0und |
|            7 |     1082 | 2024-06-13 | 3DMAX             | L   | 0.854      | -            | -                | -                | -         |    -1.58 | mantuu, misutaaa, raalz, refrezh, s0und |
|            6 |     1192 | 2024-06-09 | 3DMAX             | W   | 0.828      | 0.450        | 0.506 (0.188)    | 1.000 (0.372)    | -         |    24.63 | mantuu, misutaaa, raalz, refrezh, s0und |
|            5 |     1254 | 2024-06-08 | BLEED             | L   | 0.822      | -            | -                | -                | -         |    -1.91 | mantuu, misutaaa, raalz, refrezh, s0und |
|            4 |     1312 | 2024-06-07 | Endpoint          | W   | 0.815      | 0.450        | 0.012 (0.004)    | 0.522 (0.192)    | -         |    11.33 | mantuu, misutaaa, raalz, refrezh, s0und |
|            3 |     1338 | 2024-06-07 | Nexus             | W   | 0.813      | 0.500        | 0.014 (0.006)    | 0.465 (0.189)    | -         |     8.16 | mantuu, misutaaa, raalz, refrezh, s0und |
|            2 |     1402 | 2024-06-06 | EYEBALLERS        | L   | 0.807      | -            | -                | -                | -         |   -12.66 | mantuu, misutaaa, raalz, refrezh, s0und |
|            1 |     1436 | 2024-06-05 | Rebels            | L   | 0.802      | -            | -                | -                | -         |    -9.31 | mantuu, misutaaa, raalz, refrezh, s0und |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,198.90)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.880 | $2,500.00      | $2,198.90       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
