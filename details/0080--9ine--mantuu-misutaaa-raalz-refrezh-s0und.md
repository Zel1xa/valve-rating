### Roster Details<br />
Team Name: 9INE<br />
Roster: mantuu, misutaaa, raalz, refrezh, s0und<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  931.9<br />
<br />
Final Rank Value (931.9) = Starting Rank Value (912.1) + Head To Head Adjustments (19.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.237[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 912.1
- 400 + ( ( 0.250 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 912.1


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
|           34 |       23 | 2024-08-04 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -2.66 | mantuu, misutaaa, raalz, refrezh, s0und |
|           33 |       74 | 2024-08-03 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.35 | mantuu, misutaaa, raalz, refrezh, s0und |
|           32 |       98 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.51 | mantuu, misutaaa, raalz, refrezh, s0und |
|           31 |      107 | 2024-08-02 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.57 | mantuu, misutaaa, raalz, refrezh, s0und |
|           30 |      151 | 2024-08-01 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.89 | mantuu, misutaaa, raalz, refrezh, s0und |
|           29 |      197 | 2024-07-31 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -22.60 | mantuu, misutaaa, raalz, refrezh, s0und |
|           28 |      203 | 2024-07-31 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.51 | mantuu, misutaaa, raalz, refrezh, s0und |
|           27 |      264 | 2024-07-29 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -11.08 | mantuu, misutaaa, raalz, refrezh, s0und |
|           26 |      333 | 2024-07-27 | Aurora Young Blud | W   | 1.000      | 0.435        | 0.003 (0.001)    | 0.532 (0.231)    | 0 (0.000) |    13.56 | mantuu, misutaaa, raalz, refrezh, s0und |
|           25 |      401 | 2024-07-25 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -9.30 | mantuu, misutaaa, raalz, refrezh, s0und |
|           24 |      428 | 2024-07-24 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.42 | mantuu, misutaaa, raalz, refrezh, s0und |
|           23 |      435 | 2024-07-24 | Rebels            | W   | 1.000      | 0.371        | 0.038 (0.014)    | 0.591 (0.219)    | 0 (0.000) |    18.25 | mantuu, misutaaa, raalz, refrezh, s0und |
|           22 |      466 | 2024-07-23 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -8.85 | mantuu, misutaaa, raalz, refrezh, s0und |
|           21 |      497 | 2024-07-22 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.13 | mantuu, misutaaa, raalz, refrezh, s0und |
|           20 |      523 | 2024-07-21 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.616 (0.228)    | 0 (0.000) |    14.78 | mantuu, misutaaa, raalz, refrezh, s0und |
|           19 |      598 | 2024-07-19 | Insilio           | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.552 (0.205)    | 0 (0.000) |    17.24 | mantuu, misutaaa, raalz, refrezh, s0und |
|           18 |      620 | 2024-07-18 | K10               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.47 | mantuu, misutaaa, raalz, refrezh, s0und |
|           17 |      640 | 2024-07-18 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -5.11 | mantuu, misutaaa, raalz, refrezh, s0und |
|           16 |      690 | 2024-07-17 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.58 | mantuu, misutaaa, raalz, refrezh, s0und |
|           15 |      713 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.514 (0.190)    | -         |    13.51 | mantuu, misutaaa, raalz, refrezh, s0und |
|           14 |      722 | 2024-07-17 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.01 | mantuu, misutaaa, raalz, refrezh, s0und |
|           13 |      757 | 2024-07-16 | CPH Wolves        | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.361 (0.120)    | -         |    12.41 | mantuu, misutaaa, raalz, refrezh, s0und |
|           12 |      808 | 2024-07-15 | B8                | L   | 1.000      | -            | -                | -                | -         |    -5.57 | mantuu, misutaaa, raalz, refrezh, s0und |
|           11 |      848 | 2024-07-13 | ROSOMAHA          | W   | 1.000      | -            | -                | -                | -         |     3.42 | mantuu, misutaaa, raalz, refrezh, s0und |
|           10 |      877 | 2024-07-11 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -17.07 | mantuu, misutaaa, raalz, refrezh, s0und |
|            9 |      899 | 2024-07-10 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -5.38 | mantuu, misutaaa, n0te, raalz, s0und    |
|            8 |      919 | 2024-07-09 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -4.83 | mantuu, misutaaa, raalz, refrezh, s0und |
|            7 |     1132 | 2024-06-13 | 3DMAX             | L   | 0.846      | -            | -                | -                | -         |    -1.52 | mantuu, misutaaa, raalz, refrezh, s0und |
|            6 |     1242 | 2024-06-09 | 3DMAX             | W   | 0.819      | 0.450        | 0.508 (0.187)    | 1.000 (0.369)    | -         |    24.43 | mantuu, misutaaa, raalz, refrezh, s0und |
|            5 |     1304 | 2024-06-08 | BLEED             | L   | 0.813      | -            | -                | -                | -         |    -1.86 | mantuu, misutaaa, raalz, refrezh, s0und |
|            4 |     1362 | 2024-06-07 | Endpoint          | W   | 0.807      | 0.450        | 0.012 (0.004)    | 0.514 (0.187)    | -         |    11.26 | mantuu, misutaaa, raalz, refrezh, s0und |
|            3 |     1388 | 2024-06-07 | Nexus             | W   | 0.805      | 0.500        | 0.014 (0.006)    | 0.458 (0.184)    | -         |     8.09 | mantuu, misutaaa, raalz, refrezh, s0und |
|            2 |     1452 | 2024-06-06 | EYEBALLERS        | L   | 0.798      | -            | -                | -                | -         |   -12.65 | mantuu, misutaaa, raalz, refrezh, s0und |
|            1 |     1486 | 2024-06-05 | Rebels            | L   | 0.793      | -            | -                | -                | -         |    -9.27 | mantuu, misutaaa, raalz, refrezh, s0und |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,178.13)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.871 | $2,500.00      | $2,178.13       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
