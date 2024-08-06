### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [99](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [69]( ../standings_europe.md)<br />
<br />
Final Rank Value:  871.7<br />
<br />
Final Rank Value (871.7) = Starting Rank Value (929.8) + Head To Head Adjustments (-58.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.467[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 929.8
- 400 + ( ( 0.258 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 929.8


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
|           39 |        0 | 2024-08-06 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -6.72 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           38 |       85 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.590 (0.295)    | 0 (0.000) |    25.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       90 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.39 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |      155 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.77 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |      174 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      221 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.97 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      264 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.540 (0.235)    | 0 (0.000) |    13.47 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      300 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.44 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      329 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.77 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      334 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.18 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      377 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -15.28 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      413 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.56 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      484 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -16.58 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      537 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.540 (0.235)    | 0 (0.000) |    12.86 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      578 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -15.60 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      720 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.16 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      743 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      779 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -27.89 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      832 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.26 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |     1069 | 2024-06-15 | 3DMAX             | L   | 0.854      | -            | -                | -                | -         |    -1.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1113 | 2024-06-14 | Gaimin Gladiators | W   | 0.847      | 0.435        | 0.037 (0.014)    | 0.331 (0.122)    | 0 (0.000) |    12.35 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1130 | 2024-06-14 | Spirit Academy    | L   | 0.846      | -            | -                | -                | -         |   -21.48 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1234 | 2024-06-10 | EYEBALLERS        | W   | 0.819      | 0.435        | -                | 0.488 (0.174)    | 0 (0.000) |     9.56 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1388 | 2024-06-07 | HAVU              | W   | 0.801      | -            | -                | -                | 0 (0.000) |     4.60 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1515 | 2024-06-05 | CYBERSHOKE        | W   | 0.787      | 0.435        | 0.039 (0.013)    | 0.339 (0.116)    | -         |     8.21 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1599 | 2024-06-03 | Permitta          | L   | 0.772      | -            | -                | -                | -         |   -14.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1612 | 2024-06-02 | FURIA             | W   | 0.767      | 0.435        | 0.284 (0.095)    | 0.468 (0.156)    | -         |    23.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1623 | 2024-06-02 | VP.Prodigy        | W   | 0.765      | 0.435        | 0.025 (0.008)    | 0.383 (0.127)    | -         |    10.90 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1632 | 2024-06-01 | SINNERS           | W   | 0.761      | 0.435        | 0.037 (0.012)    | 0.800 (0.265)    | -         |    16.17 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1677 | 2024-05-31 | GamerLegion       | W   | 0.753      | 0.435        | 0.173 (0.057)    | -                | -         |    18.76 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1756 | 2024-05-28 | Permitta          | L   | 0.732      | -            | -                | -                | -         |   -11.71 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1796 | 2024-05-26 | DMS               | W   | 0.718      | 0.435        | -                | 0.428 (0.134)    | -         |    10.68 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1822 | 2024-05-24 | SINNERS           | L   | 0.708      | -            | -                | -                | -         |    -7.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1837 | 2024-05-23 | Sampi             | L   | 0.701      | -            | -                | -                | -         |   -12.03 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     2008 | 2024-05-18 | NOM               | W   | 0.667      | -            | -                | -                | -         |     2.36 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2080 | 2024-05-16 | Space             | W   | 0.654      | -            | -                | -                | -         |     7.76 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2127 | 2024-05-15 | 777               | W   | 0.647      | -            | -                | -                | -         |     4.62 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3238 | 2024-04-03 | 3DMAX             | L   | 0.367      | -            | -                | -                | -         |    -0.19 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3343 | 2024-03-28 | Space             | W   | 0.327      | -            | -                | -                | -         |     3.56 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,175.76)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.860 | $2,000.00      | $1,720.56       |
| 2024-06-16 |      0.859 | $2,500.00      | $2,147.92       |
| 2024-06-09 |      0.814 | $3,000.00      | $2,440.63       |
| 2024-06-02 |      0.767 | $22,000.00     | $16,866.67      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
