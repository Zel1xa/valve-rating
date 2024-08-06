### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  875.3<br />
<br />
Final Rank Value (875.3) = Starting Rank Value (928.2) + Head To Head Adjustments (-52.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.467[<sup>1</sup>](#table2)
- Bounty Collected: 0.378[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 928.2
- 400 + ( ( 0.257 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 928.2


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
|           38 |       67 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.565 (0.282)    | 0 (0.000) |    25.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       72 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.43 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |      138 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |      156 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.45 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      203 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.91 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      246 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.514 (0.223)    | 0 (0.000) |    13.19 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      282 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.52 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      311 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.79 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      316 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      359 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -15.72 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      395 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.48 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      466 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -17.10 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      519 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.514 (0.223)    | 0 (0.000) |    12.51 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      560 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -15.87 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      702 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.13 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      725 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.90 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      761 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -27.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      814 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.22 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |     1051 | 2024-06-15 | 3DMAX             | L   | 0.858      | -            | -                | -                | -         |    -1.90 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1095 | 2024-06-14 | Gaimin Gladiators | W   | 0.851      | 0.435        | 0.037 (0.014)    | 0.340 (0.126)    | 0 (0.000) |    12.47 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1112 | 2024-06-14 | Spirit Academy    | L   | 0.849      | -            | -                | -                | -         |   -21.57 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1216 | 2024-06-10 | EYEBALLERS        | W   | 0.823      | 0.435        | -                | 0.500 (0.179)    | 0 (0.000) |     9.51 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1370 | 2024-06-07 | HAVU              | W   | 0.804      | -            | -                | -                | 0 (0.000) |     4.65 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1497 | 2024-06-05 | CYBERSHOKE        | W   | 0.791      | 0.435        | 0.039 (0.013)    | 0.346 (0.119)    | -         |     8.29 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1581 | 2024-06-03 | Permitta          | L   | 0.776      | -            | -                | -                | -         |   -14.87 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1594 | 2024-06-02 | FURIA             | W   | 0.771      | 0.435        | 0.284 (0.095)    | 0.480 (0.161)    | -         |    23.51 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1605 | 2024-06-02 | VP.Prodigy        | W   | 0.769      | 0.435        | 0.025 (0.008)    | 0.393 (0.131)    | -         |    10.97 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1614 | 2024-06-01 | SINNERS           | W   | 0.765      | 0.435        | 0.037 (0.012)    | 0.808 (0.269)    | -         |    16.26 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1659 | 2024-05-31 | GamerLegion       | W   | 0.757      | 0.435        | 0.173 (0.057)    | -                | -         |    18.92 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1738 | 2024-05-28 | Permitta          | L   | 0.736      | -            | -                | -                | -         |   -12.00 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1778 | 2024-05-26 | DMS               | W   | 0.722      | 0.435        | -                | 0.438 (0.137)    | -         |    10.78 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1804 | 2024-05-24 | SINNERS           | L   | 0.711      | -            | -                | -                | -         |    -7.15 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1819 | 2024-05-23 | Sampi             | L   | 0.705      | -            | -                | -                | -         |   -12.08 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1990 | 2024-05-18 | NOM               | W   | 0.671      | -            | -                | -                | -         |     2.39 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2062 | 2024-05-16 | Space             | W   | 0.658      | -            | -                | -                | -         |     7.71 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2109 | 2024-05-15 | 777               | W   | 0.651      | -            | -                | -                | -         |     4.67 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3220 | 2024-04-03 | 3DMAX             | L   | 0.371      | -            | -                | -                | -         |    -0.20 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3325 | 2024-03-28 | Space             | W   | 0.331      | -            | -                | -                | -         |     3.54 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,290.49)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.864 | $2,000.00      | $1,728.33       |
| 2024-06-16 |      0.863 | $2,500.00      | $2,157.64       |
| 2024-06-09 |      0.817 | $3,000.00      | $2,452.29       |
| 2024-06-02 |      0.771 | $22,000.00     | $16,952.22      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
