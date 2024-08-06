### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  875.2<br />
<br />
Final Rank Value (875.2) = Starting Rank Value (928.0) + Head To Head Adjustments (-52.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.467[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.184[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 928.0
- 400 + ( ( 0.257 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 928.0


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
|           38 |       71 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.564 (0.282)    | 0 (0.000) |    25.40 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       76 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.44 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |      142 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.70 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |      160 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.45 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      207 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.90 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      250 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.513 (0.223)    | 0 (0.000) |    13.21 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      286 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.54 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      315 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.80 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      320 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      363 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -15.71 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      399 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.48 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      470 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -17.08 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      523 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.513 (0.223)    | 0 (0.000) |    12.53 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      564 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -15.85 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      706 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.10 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      729 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.91 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      765 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -27.87 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      818 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.20 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |     1055 | 2024-06-15 | 3DMAX             | L   | 0.856      | -            | -                | -                | -         |    -1.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1099 | 2024-06-14 | Gaimin Gladiators | W   | 0.849      | 0.435        | 0.037 (0.014)    | 0.339 (0.125)    | 0 (0.000) |    12.43 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1116 | 2024-06-14 | Spirit Academy    | L   | 0.847      | -            | -                | -                | -         |   -21.50 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1220 | 2024-06-10 | EYEBALLERS        | W   | 0.820      | 0.435        | -                | 0.499 (0.178)    | 0 (0.000) |     9.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1374 | 2024-06-07 | HAVU              | W   | 0.802      | -            | -                | -                | 0 (0.000) |     4.63 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1501 | 2024-06-05 | CYBERSHOKE        | W   | 0.789      | 0.435        | 0.039 (0.013)    | 0.347 (0.119)    | -         |     8.28 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1585 | 2024-06-03 | Permitta          | L   | 0.774      | -            | -                | -                | -         |   -14.80 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1598 | 2024-06-02 | FURIA             | W   | 0.768      | 0.435        | 0.284 (0.095)    | 0.479 (0.160)    | -         |    23.44 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1609 | 2024-06-02 | VP.Prodigy        | W   | 0.766      | 0.435        | 0.025 (0.008)    | 0.392 (0.130)    | -         |    10.95 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1618 | 2024-06-01 | SINNERS           | W   | 0.762      | 0.435        | 0.037 (0.012)    | 0.808 (0.268)    | -         |    16.22 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1663 | 2024-05-31 | GamerLegion       | W   | 0.755      | 0.435        | 0.173 (0.057)    | -                | -         |    18.84 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1742 | 2024-05-28 | Permitta          | L   | 0.733      | -            | -                | -                | -         |   -11.95 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1782 | 2024-05-26 | DMS               | W   | 0.720      | 0.435        | -                | 0.437 (0.137)    | -         |    10.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1808 | 2024-05-24 | SINNERS           | L   | 0.709      | -            | -                | -                | -         |    -7.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1823 | 2024-05-23 | Sampi             | L   | 0.702      | -            | -                | -                | -         |   -12.02 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1994 | 2024-05-18 | NOM               | W   | 0.669      | -            | -                | -                | -         |     2.39 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2066 | 2024-05-16 | Space             | W   | 0.656      | -            | -                | -                | -         |     7.69 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2113 | 2024-05-15 | 777               | W   | 0.649      | -            | -                | -                | -         |     4.66 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3224 | 2024-04-03 | 3DMAX             | L   | 0.369      | -            | -                | -                | -         |    -0.19 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3329 | 2024-03-28 | Space             | W   | 0.328      | -            | -                | -                | -         |     3.53 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,216.74)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.862 | $2,000.00      | $1,723.33       |
| 2024-06-16 |      0.861 | $2,500.00      | $2,151.39       |
| 2024-06-09 |      0.815 | $3,000.00      | $2,444.79       |
| 2024-06-02 |      0.768 | $22,000.00     | $16,897.22      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
