### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  875.4<br />
<br />
Final Rank Value (875.4) = Starting Rank Value (928.3) + Head To Head Adjustments (-52.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.467[<sup>1</sup>](#table2)
- Bounty Collected: 0.378[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 928.3
- 400 + ( ( 0.258 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 928.3


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
|           38 |       65 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.565 (0.282)    | 0 (0.000) |    25.37 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       70 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.42 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |      136 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.76 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |      154 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.45 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      201 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.91 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      244 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.514 (0.223)    | 0 (0.000) |    13.19 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      280 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.50 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      309 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.78 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      314 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      357 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -15.74 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      393 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      464 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -17.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      517 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.514 (0.223)    | 0 (0.000) |    12.50 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      558 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -15.87 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      700 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.14 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      723 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.90 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      759 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -27.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      812 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.23 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |     1049 | 2024-06-15 | 3DMAX             | L   | 0.860      | -            | -                | -                | -         |    -1.92 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1093 | 2024-06-14 | Gaimin Gladiators | W   | 0.853      | 0.435        | 0.037 (0.014)    | 0.342 (0.127)    | 0 (0.000) |    12.52 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1110 | 2024-06-14 | Spirit Academy    | L   | 0.851      | -            | -                | -                | -         |   -21.62 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1214 | 2024-06-10 | EYEBALLERS        | W   | 0.825      | 0.435        | -                | 0.500 (0.179)    | 0 (0.000) |     9.52 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1368 | 2024-06-07 | HAVU              | W   | 0.806      | -            | -                | -                | 0 (0.000) |     4.66 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1495 | 2024-06-05 | CYBERSHOKE        | W   | 0.793      | 0.435        | 0.039 (0.013)    | 0.346 (0.119)    | -         |     8.30 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1579 | 2024-06-03 | Permitta          | L   | 0.778      | -            | -                | -                | -         |   -14.91 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1592 | 2024-06-02 | FURIA             | W   | 0.772      | 0.435        | 0.284 (0.095)    | 0.481 (0.161)    | -         |    23.56 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1603 | 2024-06-02 | VP.Prodigy        | W   | 0.771      | 0.435        | 0.025 (0.009)    | 0.393 (0.132)    | -         |    11.00 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1612 | 2024-06-01 | SINNERS           | W   | 0.767      | 0.435        | 0.037 (0.012)    | 0.809 (0.269)    | -         |    16.29 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1657 | 2024-05-31 | GamerLegion       | W   | 0.759      | 0.435        | 0.173 (0.057)    | -                | -         |    18.97 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1736 | 2024-05-28 | Permitta          | L   | 0.737      | -            | -                | -                | -         |   -12.03 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1776 | 2024-05-26 | DMS               | W   | 0.724      | 0.435        | -                | 0.438 (0.138)    | -         |    10.81 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1802 | 2024-05-24 | SINNERS           | L   | 0.713      | -            | -                | -                | -         |    -7.17 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1817 | 2024-05-23 | Sampi             | L   | 0.707      | -            | -                | -                | -         |   -12.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1988 | 2024-05-18 | NOM               | W   | 0.673      | -            | -                | -                | -         |     2.40 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2060 | 2024-05-16 | Space             | W   | 0.660      | -            | -                | -                | -         |     7.73 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2107 | 2024-05-15 | 777               | W   | 0.653      | -            | -                | -                | -         |     4.68 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3218 | 2024-04-03 | 3DMAX             | L   | 0.373      | -            | -                | -                | -         |    -0.20 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3323 | 2024-03-28 | Space             | W   | 0.333      | -            | -                | -                | -         |     3.56 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,343.75)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.866 | $2,000.00      | $1,731.94       |
| 2024-06-16 |      0.865 | $2,500.00      | $2,162.15       |
| 2024-06-09 |      0.819 | $3,000.00      | $2,457.71       |
| 2024-06-02 |      0.772 | $22,000.00     | $16,991.94      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
