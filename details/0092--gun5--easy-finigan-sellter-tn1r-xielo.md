### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [92](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  865.1<br />
<br />
Final Rank Value (865.1) = Starting Rank Value (927.5) + Head To Head Adjustments (-62.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.468[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 927.5
- 400 + ( ( 0.258 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 927.5


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
|           38 |        8 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.534 (0.267)    | 0 (0.000) |    25.46 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       14 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.19 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |       80 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.44 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |       96 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.56 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      145 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.67 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      186 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    13.73 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      223 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.50 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      251 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.16 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      256 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -25.96 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      299 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -21.73 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      335 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.35 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      406 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -23.55 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      459 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    12.57 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      500 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.14 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      639 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.66 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      666 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.89 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      701 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -25.08 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      755 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.20 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |      991 | 2024-06-15 | 3DMAX             | L   | 0.869      | -            | -                | -                | -         |    -2.00 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1035 | 2024-06-14 | Gaimin Gladiators | W   | 0.862      | 0.435        | 0.038 (0.014)    | 0.351 (0.132)    | 0 (0.000) |    12.63 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1052 | 2024-06-14 | Spirit Academy    | L   | 0.860      | -            | -                | -                | -         |   -21.84 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1156 | 2024-06-10 | EYEBALLERS        | W   | 0.834      | 0.435        | -                | 0.510 (0.185)    | 0 (0.000) |     9.72 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1310 | 2024-06-07 | HAVU              | W   | 0.815      | -            | -                | -                | 0 (0.000) |     4.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1437 | 2024-06-05 | CYBERSHOKE        | W   | 0.802      | 0.435        | 0.039 (0.014)    | 0.351 (0.122)    | -         |     8.39 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1521 | 2024-06-03 | Permitta          | L   | 0.787      | -            | -                | -                | -         |   -15.28 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1534 | 2024-06-02 | FURIA             | W   | 0.781      | 0.435        | 0.284 (0.096)    | 0.491 (0.167)    | -         |    23.82 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1545 | 2024-06-02 | VP.Prodigy        | W   | 0.780      | 0.435        | 0.026 (0.009)    | 0.401 (0.136)    | -         |    11.15 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1554 | 2024-06-01 | SINNERS           | W   | 0.776      | 0.435        | 0.037 (0.013)    | 0.758 (0.255)    | -         |    15.57 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1599 | 2024-05-31 | GamerLegion       | W   | 0.768      | 0.435        | 0.174 (0.058)    | -                | -         |    19.26 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1678 | 2024-05-28 | Permitta          | L   | 0.746      | -            | -                | -                | -         |   -12.43 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1718 | 2024-05-26 | DMS               | W   | 0.733      | 0.435        | -                | 0.446 (0.142)    | -         |    10.89 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1744 | 2024-05-24 | SINNERS           | L   | 0.722      | -            | -                | -                | -         |    -8.29 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1759 | 2024-05-23 | Sampi             | L   | 0.716      | -            | -                | -                | -         |   -12.29 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1930 | 2024-05-18 | NOM               | W   | 0.682      | -            | -                | -                | -         |     2.36 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2002 | 2024-05-16 | Space             | W   | 0.669      | -            | -                | -                | -         |     7.92 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2049 | 2024-05-15 | 777               | W   | 0.662      | -            | -                | -                | -         |     4.79 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3160 | 2024-04-03 | 3DMAX             | L   | 0.382      | -            | -                | -                | -         |    -0.21 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3265 | 2024-03-28 | Space             | W   | 0.342      | -            | -                | -                | -         |     3.71 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,610.07)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.875 | $2,000.00      | $1,750.00       |
| 2024-06-16 |      0.874 | $2,500.00      | $2,184.72       |
| 2024-06-09 |      0.828 | $3,000.00      | $2,484.79       |
| 2024-06-02 |      0.781 | $22,000.00     | $17,190.56      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
