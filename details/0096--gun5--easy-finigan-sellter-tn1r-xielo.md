### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  876.9<br />
<br />
Final Rank Value (876.9) = Starting Rank Value (928.0) + Head To Head Adjustments (-51.1)<br />

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
|           38 |       78 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.590 (0.295)    | 0 (0.000) |    25.39 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       83 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.46 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |      149 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.77 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |      167 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.41 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      214 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.94 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      257 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.502 (0.218)    | 0 (0.000) |    13.47 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      293 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.48 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      322 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.82 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      327 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.14 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      370 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -15.29 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      406 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      477 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -16.59 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      530 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.502 (0.218)    | 0 (0.000) |    12.86 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      571 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -15.74 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      713 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.10 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      736 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.90 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      772 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -27.86 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      825 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.20 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |     1062 | 2024-06-15 | 3DMAX             | L   | 0.855      | -            | -                | -                | -         |    -1.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1106 | 2024-06-14 | Gaimin Gladiators | W   | 0.848      | 0.435        | 0.037 (0.014)    | 0.331 (0.122)    | 0 (0.000) |    12.40 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1123 | 2024-06-14 | Spirit Academy    | L   | 0.846      | -            | -                | -                | -         |   -21.45 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1227 | 2024-06-10 | EYEBALLERS        | W   | 0.820      | 0.435        | -                | 0.488 (0.174)    | 0 (0.000) |     9.60 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1381 | 2024-06-07 | HAVU              | W   | 0.801      | -            | -                | -                | 0 (0.000) |     4.63 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1508 | 2024-06-05 | CYBERSHOKE        | W   | 0.788      | 0.435        | 0.039 (0.013)    | 0.339 (0.116)    | -         |     8.28 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1592 | 2024-06-03 | Permitta          | L   | 0.773      | -            | -                | -                | -         |   -14.67 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1605 | 2024-06-02 | FURIA             | W   | 0.767      | 0.435        | 0.284 (0.095)    | 0.469 (0.156)    | -         |    23.41 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1616 | 2024-06-02 | VP.Prodigy        | W   | 0.766      | 0.435        | 0.025 (0.008)    | 0.383 (0.127)    | -         |    10.94 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1625 | 2024-06-01 | SINNERS           | W   | 0.762      | 0.435        | 0.037 (0.012)    | 0.790 (0.261)    | -         |    16.21 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1670 | 2024-05-31 | GamerLegion       | W   | 0.754      | 0.435        | 0.173 (0.057)    | -                | -         |    18.81 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1749 | 2024-05-28 | Permitta          | L   | 0.732      | -            | -                | -                | -         |   -11.92 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1789 | 2024-05-26 | DMS               | W   | 0.719      | 0.435        | -                | 0.428 (0.134)    | -         |    10.73 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1815 | 2024-05-24 | SINNERS           | L   | 0.708      | -            | -                | -                | -         |    -7.10 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1830 | 2024-05-23 | Sampi             | L   | 0.702      | -            | -                | -                | -         |   -12.03 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     2001 | 2024-05-18 | NOM               | W   | 0.668      | -            | -                | -                | -         |     2.39 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2073 | 2024-05-16 | Space             | W   | 0.655      | -            | -                | -                | -         |     7.74 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2120 | 2024-05-15 | 777               | W   | 0.648      | -            | -                | -                | -         |     4.66 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3231 | 2024-04-03 | 3DMAX             | L   | 0.368      | -            | -                | -                | -         |    -0.19 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3336 | 2024-03-28 | Space             | W   | 0.328      | -            | -                | -                | -         |     3.55 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,197.62)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.861 | $2,000.00      | $1,722.04       |
| 2024-06-16 |      0.860 | $2,500.00      | $2,149.77       |
| 2024-06-09 |      0.814 | $3,000.00      | $2,442.85       |
| 2024-06-02 |      0.767 | $22,000.00     | $16,882.96      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
