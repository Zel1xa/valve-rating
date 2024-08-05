### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
<br />
Final Rank Value:  859.0<br />
<br />
Final Rank Value (859.0) = Starting Rank Value (925.5) + Head To Head Adjustments (-66.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.468[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.172[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.255<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 925.5
- 400 + ( ( 0.255 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 925.5


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
|           34 |       25 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.60 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |       69 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.523 (0.227)    | 0 (0.000) |    14.00 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      105 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | 0 (0.000) |    20.60 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      134 | 2024-07-28 | Astralis Talent   | W   | 1.000      | 0.435        | 0.009 (0.004)    | -                | 0 (0.000) |    10.47 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      139 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -25.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      182 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -22.89 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      218 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.02 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      289 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -24.68 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      342 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.523 (0.227)    | 0 (0.000) |    12.79 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      383 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      525 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.63 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      548 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.93 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      584 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -28.18 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      637 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |      874 | 2024-06-15 | 3DMAX             | L   | 0.893      | -            | -                | -                | -         |    -2.03 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |      918 | 2024-06-14 | Gaimin Gladiators | W   | 0.886      | 0.435        | 0.040 (0.015)    | 0.363 (0.140)    | 0 (0.000) |    13.50 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |      935 | 2024-06-14 | Spirit Academy    | L   | 0.884      | -            | -                | -                | -         |   -22.37 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1039 | 2024-06-10 | EYEBALLERS        | W   | 0.858      | 0.435        | -                | 0.513 (0.191)    | 0 (0.000) |    10.14 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1193 | 2024-06-07 | HAVU              | W   | 0.839      | -            | -                | -                | 0 (0.000) |     5.03 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1320 | 2024-06-05 | CYBERSHOKE        | W   | 0.826      | 0.435        | 0.039 (0.014)    | 0.347 (0.125)    | 0 (0.000) |     8.78 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1404 | 2024-06-03 | Permitta          | L   | 0.811      | -            | -                | -                | -         |   -15.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1417 | 2024-06-02 | FURIA             | W   | 0.805      | 0.435        | 0.284 (0.099)    | 0.495 (0.173)    | 0 (0.000) |    24.62 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1428 | 2024-06-02 | VP.Prodigy        | W   | 0.804      | 0.435        | 0.026 (0.009)    | 0.406 (0.142)    | -         |    11.70 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1437 | 2024-06-01 | SINNERS           | W   | 0.800      | 0.435        | 0.038 (0.013)    | 0.721 (0.251)    | -         |    15.52 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1482 | 2024-05-31 | GamerLegion       | W   | 0.792      | 0.435        | 0.175 (0.060)    | 0.273 (0.094)    | -         |    20.22 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1561 | 2024-05-28 | Permitta          | L   | 0.770      | -            | -                | -                | -         |   -12.96 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1601 | 2024-05-26 | DMS               | W   | 0.757      | 0.435        | -                | 0.447 (0.147)    | -         |    11.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1627 | 2024-05-24 | SINNERS           | L   | 0.746      | -            | -                | -                | -         |    -9.18 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1642 | 2024-05-23 | Sampi             | L   | 0.739      | -            | -                | -                | -         |   -12.53 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1813 | 2024-05-18 | NOM               | W   | 0.706      | -            | -                | -                | -         |     2.45 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     1885 | 2024-05-16 | Space             | W   | 0.693      | -            | -                | -                | -         |     8.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     1932 | 2024-05-15 | 777               | W   | 0.686      | -            | -                | -                | -         |     5.08 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3043 | 2024-04-03 | 3DMAX             | L   | 0.406      | -            | -                | -                | -         |    -0.21 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3148 | 2024-03-28 | Space             | W   | 0.365      | -            | -                | -                | -         |     4.05 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,311.65)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.899 | $2,000.00      | $1,797.56       |
| 2024-06-16 |      0.898 | $2,500.00      | $2,244.18       |
| 2024-06-09 |      0.852 | $3,000.00      | $2,556.14       |
| 2024-06-02 |      0.805 | $22,000.00     | $17,713.77      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
