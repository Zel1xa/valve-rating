### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [69]( ../standings_europe.md)<br />
<br />
Final Rank Value:  878.2<br />
<br />
Final Rank Value (878.2) = Starting Rank Value (929.7) + Head To Head Adjustments (-51.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.467[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 929.7
- 400 + ( ( 0.257 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 929.7


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
|           38 |       83 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.590 (0.295)    | 0 (0.000) |    25.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       88 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |      154 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.76 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |      172 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      219 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.97 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      262 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.540 (0.235)    | 0 (0.000) |    13.48 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      298 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.44 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      327 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.77 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      332 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.18 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      375 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -15.29 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      411 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.55 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      482 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -16.58 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      535 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.540 (0.235)    | 0 (0.000) |    12.86 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      576 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -15.60 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      718 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.15 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      741 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      777 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -27.89 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      830 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.26 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |     1067 | 2024-06-15 | 3DMAX             | L   | 0.854      | -            | -                | -                | -         |    -1.89 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1111 | 2024-06-14 | Gaimin Gladiators | W   | 0.847      | 0.435        | 0.037 (0.014)    | 0.331 (0.122)    | 0 (0.000) |    12.35 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1128 | 2024-06-14 | Spirit Academy    | L   | 0.846      | -            | -                | -                | -         |   -21.48 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1232 | 2024-06-10 | EYEBALLERS        | W   | 0.819      | 0.435        | -                | 0.488 (0.174)    | 0 (0.000) |     9.56 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1386 | 2024-06-07 | HAVU              | W   | 0.801      | -            | -                | -                | 0 (0.000) |     4.60 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1513 | 2024-06-05 | CYBERSHOKE        | W   | 0.787      | 0.435        | 0.039 (0.013)    | 0.339 (0.116)    | -         |     8.22 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1597 | 2024-06-03 | Permitta          | L   | 0.772      | -            | -                | -                | -         |   -14.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1610 | 2024-06-02 | FURIA             | W   | 0.767      | 0.435        | 0.284 (0.095)    | 0.469 (0.156)    | -         |    23.39 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1621 | 2024-06-02 | VP.Prodigy        | W   | 0.765      | 0.435        | 0.025 (0.008)    | 0.383 (0.127)    | -         |    10.90 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1630 | 2024-06-01 | SINNERS           | W   | 0.761      | 0.435        | 0.037 (0.012)    | 0.790 (0.261)    | -         |    16.17 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1675 | 2024-05-31 | GamerLegion       | W   | 0.754      | 0.435        | 0.173 (0.057)    | -                | -         |    18.76 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1754 | 2024-05-28 | Permitta          | L   | 0.732      | -            | -                | -                | -         |   -11.71 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1794 | 2024-05-26 | DMS               | W   | 0.719      | 0.435        | -                | 0.428 (0.134)    | -         |    10.68 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1820 | 2024-05-24 | SINNERS           | L   | 0.708      | -            | -                | -                | -         |    -7.12 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1835 | 2024-05-23 | Sampi             | L   | 0.701      | -            | -                | -                | -         |   -12.03 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     2006 | 2024-05-18 | NOM               | W   | 0.668      | -            | -                | -                | -         |     2.37 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2078 | 2024-05-16 | Space             | W   | 0.654      | -            | -                | -                | -         |     7.76 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2125 | 2024-05-15 | 777               | W   | 0.648      | -            | -                | -                | -         |     4.63 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3236 | 2024-04-03 | 3DMAX             | L   | 0.368      | -            | -                | -                | -         |    -0.19 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3341 | 2024-03-28 | Space             | W   | 0.327      | -            | -                | -                | -         |     3.56 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,181.23)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.860 | $2,000.00      | $1,720.93       |
| 2024-06-16 |      0.859 | $2,500.00      | $2,148.38       |
| 2024-06-09 |      0.814 | $3,000.00      | $2,441.18       |
| 2024-06-02 |      0.767 | $22,000.00     | $16,870.74      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
