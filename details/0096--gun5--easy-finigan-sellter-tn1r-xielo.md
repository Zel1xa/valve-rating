### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  876.4<br />
<br />
Final Rank Value (876.4) = Starting Rank Value (928.0) + Head To Head Adjustments (-51.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.467[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 928.0
- 400 + ( ( 0.257 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 928.0


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
|           38 |       75 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.590 (0.295)    | 0 (0.000) |    25.39 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       80 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.46 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |      146 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |      164 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.42 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      211 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.93 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      254 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.502 (0.218)    | 0 (0.000) |    13.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      290 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      319 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.78 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      324 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.13 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      367 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -15.31 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      403 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.51 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      474 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -16.62 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      527 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.502 (0.218)    | 0 (0.000) |    12.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      568 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -15.82 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      710 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      733 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.91 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      769 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -27.86 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      822 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.20 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |     1059 | 2024-06-15 | 3DMAX             | L   | 0.855      | -            | -                | -                | -         |    -1.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1103 | 2024-06-14 | Gaimin Gladiators | W   | 0.848      | 0.435        | 0.037 (0.014)    | 0.331 (0.122)    | 0 (0.000) |    12.42 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1120 | 2024-06-14 | Spirit Academy    | L   | 0.847      | -            | -                | -                | -         |   -21.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1224 | 2024-06-10 | EYEBALLERS        | W   | 0.820      | 0.435        | -                | 0.488 (0.174)    | 0 (0.000) |     9.60 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1378 | 2024-06-07 | HAVU              | W   | 0.802      | -            | -                | -                | 0 (0.000) |     4.64 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1505 | 2024-06-05 | CYBERSHOKE        | W   | 0.788      | 0.435        | 0.039 (0.013)    | 0.339 (0.116)    | -         |     8.26 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1589 | 2024-06-03 | Permitta          | L   | 0.773      | -            | -                | -                | -         |   -14.78 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1602 | 2024-06-02 | FURIA             | W   | 0.768      | 0.435        | 0.284 (0.095)    | 0.469 (0.156)    | -         |    23.42 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1613 | 2024-06-02 | VP.Prodigy        | W   | 0.766      | 0.435        | 0.025 (0.008)    | 0.383 (0.128)    | -         |    10.94 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1622 | 2024-06-01 | SINNERS           | W   | 0.762      | 0.435        | 0.037 (0.012)    | 0.790 (0.262)    | -         |    16.22 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1667 | 2024-05-31 | GamerLegion       | W   | 0.755      | 0.435        | 0.173 (0.057)    | -                | -         |    18.82 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1746 | 2024-05-28 | Permitta          | L   | 0.733      | -            | -                | -                | -         |   -11.93 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1786 | 2024-05-26 | DMS               | W   | 0.719      | 0.435        | -                | 0.428 (0.134)    | -         |    10.74 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1812 | 2024-05-24 | SINNERS           | L   | 0.709      | -            | -                | -                | -         |    -7.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1827 | 2024-05-23 | Sampi             | L   | 0.702      | -            | -                | -                | -         |   -12.03 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1998 | 2024-05-18 | NOM               | W   | 0.669      | -            | -                | -                | -         |     2.39 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2070 | 2024-05-16 | Space             | W   | 0.655      | -            | -                | -                | -         |     7.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2117 | 2024-05-15 | 777               | W   | 0.649      | -            | -                | -                | -         |     4.67 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3228 | 2024-04-03 | 3DMAX             | L   | 0.369      | -            | -                | -                | -         |    -0.19 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3333 | 2024-03-28 | Space             | W   | 0.328      | -            | -                | -                | -         |     3.56 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,208.54)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.861 | $2,000.00      | $1,722.78       |
| 2024-06-16 |      0.860 | $2,500.00      | $2,150.69       |
| 2024-06-09 |      0.815 | $3,000.00      | $2,443.96       |
| 2024-06-02 |      0.768 | $22,000.00     | $16,891.11      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
