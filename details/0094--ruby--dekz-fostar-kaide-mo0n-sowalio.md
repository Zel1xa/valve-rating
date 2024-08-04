### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  874.7<br />
<br />
Final Rank Value (874.7) = Starting Rank Value (925.2) + Head To Head Adjustments (-50.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.373[<sup>2</sup>](#table1)
- Opponent Network: 0.160[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 925.2
- 400 + ( ( 0.257 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 925.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |       18 | 2024-08-04 | Project G       | L   | 1.000      | -            | -                | -                | -         |   -27.42 | dekz, fostar, Kaide, mo0N, sowalio |
|           47 |      361 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -1.21 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      441 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | -                | 0.235 (0.102)    | 0 (0.000) |    12.37 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      536 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -8.78 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      688 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.401 (0.174)    | 0 (0.000) |    14.73 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      734 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.14 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |     1004 | 2024-06-16 | ARCRED          | W   | 0.872      | 0.450        | 0.041 (0.016)    | 0.344 (0.135)    | 0 (0.000) |    16.02 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |     1024 | 2024-06-15 | System5         | L   | 0.867      | -            | -                | -                | -         |   -21.03 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |     1037 | 2024-06-15 | Spirit Academy  | W   | 0.866      | 0.450        | 0.013 (0.005)    | -                | 0 (0.000) |     8.14 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |     1068 | 2024-06-14 | Zero Tenacity   | L   | 0.860      | -            | -                | -                | -         |    -7.21 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |     1075 | 2024-06-14 | LEON            | W   | 0.859      | -            | -                | -                | 0 (0.000) |     6.43 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1217 | 2024-06-09 | Insilio         | L   | 0.827      | -            | -                | -                | -         |   -10.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1364 | 2024-06-07 | SINNERS         | L   | 0.812      | -            | -                | -                | -         |    -9.14 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1477 | 2024-06-05 | ARCRED          | L   | 0.799      | -            | -                | -                | -         |   -12.94 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1493 | 2024-06-05 | Rare Atom       | L   | 0.798      | -            | -                | -                | -         |   -20.13 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1542 | 2024-06-03 | Insilio         | W   | 0.787      | 0.372        | 0.023 (0.007)    | 0.561 (0.164)    | 0 (0.000) |    12.50 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1551 | 2024-06-03 | HAVU            | L   | 0.786      | -            | -                | -                | -         |   -19.38 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1585 | 2024-06-01 | Zero Tenacity   | W   | 0.774      | 0.372        | 0.137 (0.039)    | 1.000 (0.288)    | 0 (0.000) |    17.73 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1648 | 2024-05-30 | Portugal        | W   | 0.761      | -            | -                | -                | 0 (0.000) |     4.64 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1661 | 2024-05-30 | FURIA           | L   | 0.759      | -            | -                | -                | -         |    -0.58 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1705 | 2024-05-28 | MOUZ NXT        | L   | 0.746      | -            | -                | -                | -         |    -7.77 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1746 | 2024-05-26 | Zero Tenacity   | L   | 0.732      | -            | -                | -                | -         |    -6.65 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1756 | 2024-05-25 | B8              | L   | 0.727      | -            | -                | -                | -         |    -5.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1794 | 2024-05-23 | Nexus           | W   | 0.713      | 0.435        | 0.014 (0.004)    | 0.465 (0.144)    | 0 (0.000) |     6.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1887 | 2024-05-21 | Endpoint        | W   | 0.698      | 0.435        | 0.012 (0.004)    | 0.522 (0.158)    | 0 (0.000) |    10.49 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2225 | 2024-05-11 | 9 Pandas        | L   | 0.633      | -            | -                | -                | -         |    -8.23 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2251 | 2024-05-10 | Nemiga          | W   | 0.625      | 0.435        | 0.317 (0.086)    | 0.734 (0.199)    | -         |    15.56 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2308 | 2024-05-07 | Insilio         | W   | 0.607      | 0.435        | 0.023 (0.006)    | 0.561 (0.148)    | -         |     9.75 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2351 | 2024-05-05 | HAVU            | W   | 0.592      | -            | -                | -                | -         |     4.28 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2381 | 2024-05-03 | V1dar           | W   | 0.579      | -            | -                | -                | -         |     1.91 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2438 | 2024-05-01 | GL Academy      | L   | 0.565      | -            | -                | -                | -         |   -12.86 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2480 | 2024-04-29 | Permitta        | L   | 0.551      | -            | -                | -                | -         |    -8.34 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2511 | 2024-04-27 | Astralis Talent | W   | 0.540      | -            | -                | -                | -         |     0.81 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2671 | 2024-04-20 | Zero Tenacity   | L   | 0.493      | -            | -                | -                | -         |    -5.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2751 | 2024-04-18 | Sashi           | L   | 0.480      | -            | -                | -                | -         |    -4.06 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2761 | 2024-04-18 | Aurora          | W   | 0.480      | 0.143        | 0.423 (0.029)    | -                | -         |    14.83 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2768 | 2024-04-18 | NOM             | W   | 0.479      | -            | -                | -                | -         |     1.66 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2821 | 2024-04-17 | JANO            | W   | 0.471      | -            | -                | -                | -         |     3.01 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3461 | 2024-03-19 | Sashi           | L   | 0.280      | -            | -                | -                | -         |    -2.12 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3518 | 2024-03-16 | Permitta        | W   | 0.260      | 0.372        | -                | 0.876 (0.085)    | -         |     4.56 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3655 | 2024-03-11 | Nexus           | L   | 0.227      | -            | -                | -                | -         |    -4.47 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3692 | 2024-03-09 | Spirit Academy  | W   | 0.213      | -            | -                | -                | -         |     0.75 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3718 | 2024-03-08 | ARCRED          | W   | 0.207      | -            | -                | -                | -         |     2.74 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3948 | 2024-02-27 | Spirit Academy  | L   | 0.140      | -            | -                | -                | -         |    -3.96 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3952 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.140      | -            | -                | -                | -         |     2.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4357 | 2024-02-09 | FORZE           | L   | 0.019      | -            | -                | -                | -         |    -0.34 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4368 | 2024-02-08 | AMKAL           | L   | 0.014      | -            | -                | -                | -         |    -0.10 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4371 | 2024-02-08 | ex-Guild Eagles | W   | 0.013      | -            | -                | -                | -         |     0.14 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,835.06)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.872 | $30,000.00     | $26,163.19      |
| 2024-06-10 |      0.834 | $3,300.00      | $2,751.91       |
| 2024-05-12 |      0.640 | $2,000.00      | $1,280.19       |
| 2024-03-25 |      0.320 | $2,000.00      | $639.77         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
