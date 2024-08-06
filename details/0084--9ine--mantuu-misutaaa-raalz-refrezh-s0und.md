### Roster Details<br />
Team Name: 9INE<br />
Roster: mantuu, misutaaa, raalz, refrezh, s0und<br />
Global Rank: [84](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  936.0<br />
<br />
Final Rank Value (936.0) = Starting Rank Value (914.8) + Head To Head Adjustments (21.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.387[<sup>2</sup>](#table1)
- Opponent Network: 0.237[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 914.8
- 400 + ( ( 0.250 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 914.8


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
|           34 |       46 | 2024-08-04 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -2.69 | mantuu, misutaaa, raalz, refrezh, s0und |
|           33 |       97 | 2024-08-03 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.31 | mantuu, misutaaa, raalz, refrezh, s0und |
|           32 |      121 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.52 | mantuu, misutaaa, raalz, refrezh, s0und |
|           31 |      130 | 2024-08-02 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.53 | mantuu, misutaaa, raalz, refrezh, s0und |
|           30 |      174 | 2024-08-01 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.90 | mantuu, misutaaa, raalz, refrezh, s0und |
|           29 |      220 | 2024-07-31 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -22.58 | mantuu, misutaaa, raalz, refrezh, s0und |
|           28 |      226 | 2024-07-31 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.20 | mantuu, misutaaa, raalz, refrezh, s0und |
|           27 |      287 | 2024-07-29 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -11.17 | mantuu, misutaaa, raalz, refrezh, s0und |
|           26 |      356 | 2024-07-27 | Aurora Young Blud | W   | 1.000      | 0.435        | 0.019 (0.008)    | 0.522 (0.227)    | 0 (0.000) |    14.34 | mantuu, misutaaa, raalz, refrezh, s0und |
|           25 |      424 | 2024-07-25 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -9.26 | mantuu, misutaaa, raalz, refrezh, s0und |
|           24 |      451 | 2024-07-24 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.71 | mantuu, misutaaa, raalz, refrezh, s0und |
|           23 |      458 | 2024-07-24 | Rebels            | W   | 1.000      | 0.371        | 0.038 (0.014)    | 0.578 (0.214)    | 0 (0.000) |    18.20 | mantuu, misutaaa, raalz, refrezh, s0und |
|           22 |      489 | 2024-07-23 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.79 | mantuu, misutaaa, raalz, refrezh, s0und |
|           21 |      520 | 2024-07-22 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.10 | mantuu, misutaaa, raalz, refrezh, s0und |
|           20 |      546 | 2024-07-21 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.641 (0.237)    | 0 (0.000) |    14.73 | mantuu, misutaaa, raalz, refrezh, s0und |
|           19 |      621 | 2024-07-19 | Insilio           | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.539 (0.200)    | 0 (0.000) |    17.24 | mantuu, misutaaa, raalz, refrezh, s0und |
|           18 |      643 | 2024-07-18 | K10               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.40 | mantuu, misutaaa, raalz, refrezh, s0und |
|           17 |      663 | 2024-07-18 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -5.11 | mantuu, misutaaa, raalz, refrezh, s0und |
|           16 |      713 | 2024-07-17 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.55 | mantuu, misutaaa, raalz, refrezh, s0und |
|           15 |      736 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.540 (0.200)    | -         |    13.88 | mantuu, misutaaa, raalz, refrezh, s0und |
|           14 |      745 | 2024-07-17 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.05 | mantuu, misutaaa, raalz, refrezh, s0und |
|           13 |      780 | 2024-07-16 | CPH Wolves        | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.354 (0.118)    | -         |    12.34 | mantuu, misutaaa, raalz, refrezh, s0und |
|           12 |      831 | 2024-07-15 | B8                | L   | 1.000      | -            | -                | -                | -         |    -5.60 | mantuu, misutaaa, raalz, refrezh, s0und |
|           11 |      871 | 2024-07-13 | ROSOMAHA          | W   | 1.000      | -            | -                | -                | -         |     3.38 | mantuu, misutaaa, raalz, refrezh, s0und |
|           10 |      900 | 2024-07-11 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -16.94 | mantuu, misutaaa, raalz, refrezh, s0und |
|            9 |      922 | 2024-07-10 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -5.43 | mantuu, misutaaa, n0te, raalz, s0und    |
|            8 |      942 | 2024-07-09 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.82 | mantuu, misutaaa, raalz, refrezh, s0und |
|            7 |     1155 | 2024-06-13 | 3DMAX             | L   | 0.840      | -            | -                | -                | -         |    -1.50 | mantuu, misutaaa, raalz, refrezh, s0und |
|            6 |     1265 | 2024-06-09 | 3DMAX             | W   | 0.813      | 0.450        | 0.510 (0.187)    | 1.000 (0.366)    | -         |    24.26 | mantuu, misutaaa, raalz, refrezh, s0und |
|            5 |     1327 | 2024-06-08 | BLEED             | L   | 0.807      | -            | -                | -                | -         |    -1.86 | mantuu, misutaaa, raalz, refrezh, s0und |
|            4 |     1385 | 2024-06-07 | Endpoint          | W   | 0.801      | 0.450        | 0.012 (0.004)    | 0.540 (0.195)    | -         |    11.30 | mantuu, misutaaa, raalz, refrezh, s0und |
|            3 |     1411 | 2024-06-07 | Nexus             | W   | 0.799      | 0.500        | 0.014 (0.005)    | 0.447 (0.179)    | -         |     8.08 | mantuu, misutaaa, raalz, refrezh, s0und |
|            2 |     1475 | 2024-06-06 | EYEBALLERS        | L   | 0.792      | -            | -                | -                | -         |   -12.48 | mantuu, misutaaa, raalz, refrezh, s0und |
|            1 |     1509 | 2024-06-05 | Rebels            | L   | 0.787      | -            | -                | -                | -         |    -9.27 | mantuu, misutaaa, raalz, refrezh, s0und |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,163.19)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.865 | $2,500.00      | $2,163.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
