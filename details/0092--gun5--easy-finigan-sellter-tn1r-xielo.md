### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [92](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  865.4<br />
<br />
Final Rank Value (865.4) = Starting Rank Value (927.8) + Head To Head Adjustments (-62.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.468[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.187[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 927.8
- 400 + ( ( 0.258 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 927.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |        5 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.534 (0.267)    | 0 (0.000) |    25.46 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       11 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.09 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |       77 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.45 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |       93 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.56 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      142 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.67 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      183 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    13.72 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      220 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.47 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      248 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.15 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      253 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -25.96 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      296 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -21.74 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      332 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.36 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      403 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -23.57 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      456 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    12.56 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      497 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.15 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      636 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.70 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      663 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      698 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -25.09 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      752 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.21 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |      987 | 2024-06-15 | 3DMAX             | L   | 0.872      | -            | -                | -                | -         |    -2.02 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1031 | 2024-06-14 | Gaimin Gladiators | W   | 0.865      | 0.435        | 0.038 (0.014)    | 0.353 (0.133)    | 0 (0.000) |    12.71 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1048 | 2024-06-14 | Spirit Academy    | L   | 0.863      | -            | -                | -                | -         |   -21.93 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1152 | 2024-06-10 | EYEBALLERS        | W   | 0.837      | 0.435        | -                | 0.510 (0.186)    | 0 (0.000) |     9.74 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1306 | 2024-06-07 | HAVU              | W   | 0.818      | -            | -                | -                | 0 (0.000) |     4.77 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1433 | 2024-06-05 | CYBERSHOKE        | W   | 0.805      | 0.435        | 0.039 (0.014)    | 0.350 (0.123)    | -         |     8.40 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1517 | 2024-06-03 | Permitta          | L   | 0.790      | -            | -                | -                | -         |   -15.35 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1530 | 2024-06-02 | FURIA             | W   | 0.784      | 0.435        | 0.284 (0.097)    | 0.491 (0.167)    | -         |    23.91 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1541 | 2024-06-02 | VP.Prodigy        | W   | 0.783      | 0.435        | 0.026 (0.009)    | 0.402 (0.137)    | -         |    11.19 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1550 | 2024-06-01 | SINNERS           | W   | 0.779      | 0.435        | 0.037 (0.013)    | 0.758 (0.257)    | -         |    15.63 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1595 | 2024-05-31 | GamerLegion       | W   | 0.771      | 0.435        | 0.174 (0.058)    | -                | -         |    19.35 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1674 | 2024-05-28 | Permitta          | L   | 0.749      | -            | -                | -                | -         |   -12.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1714 | 2024-05-26 | DMS               | W   | 0.736      | 0.435        | -                | 0.446 (0.143)    | -         |    10.93 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1740 | 2024-05-24 | SINNERS           | L   | 0.725      | -            | -                | -                | -         |    -8.33 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1755 | 2024-05-23 | Sampi             | L   | 0.719      | -            | -                | -                | -         |   -12.33 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1926 | 2024-05-18 | NOM               | W   | 0.685      | -            | -                | -                | -         |     2.37 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     1998 | 2024-05-16 | Space             | W   | 0.672      | -            | -                | -                | -         |     7.96 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2045 | 2024-05-15 | 777               | W   | 0.665      | -            | -                | -                | -         |     4.80 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3155 | 2024-04-03 | 3DMAX             | L   | 0.385      | -            | -                | -                | -         |    -0.21 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3260 | 2024-03-28 | Space             | W   | 0.345      | -            | -                | -                | -         |     3.74 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,700.21)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.878 | $2,000.00      | $1,756.11       |
| 2024-06-16 |      0.877 | $2,500.00      | $2,192.36       |
| 2024-06-09 |      0.831 | $3,000.00      | $2,493.96       |
| 2024-06-02 |      0.784 | $22,000.00     | $17,257.78      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
