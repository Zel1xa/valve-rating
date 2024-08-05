### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  874.3<br />
<br />
Final Rank Value (874.3) = Starting Rank Value (927.5) + Head To Head Adjustments (-53.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.467[<sup>1</sup>](#table2)
- Bounty Collected: 0.378[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 927.5
- 400 + ( ( 0.258 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 927.5


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
|           38 |       55 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.532 (0.266)    | 0 (0.000) |    25.34 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       61 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.43 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |      127 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |      145 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.47 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      192 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.89 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      235 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.520 (0.226)    | 0 (0.000) |    13.20 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      272 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      300 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.83 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      305 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.09 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      348 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -15.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      384 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      455 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -17.13 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      508 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.520 (0.226)    | 0 (0.000) |    12.52 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      549 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.01 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      691 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.16 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      714 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.91 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      750 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -27.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      803 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.20 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |     1040 | 2024-06-15 | 3DMAX             | L   | 0.861      | -            | -                | -                | -         |    -1.93 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1084 | 2024-06-14 | Gaimin Gladiators | W   | 0.854      | 0.435        | 0.037 (0.014)    | 0.346 (0.129)    | 0 (0.000) |    12.56 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1101 | 2024-06-14 | Spirit Academy    | L   | 0.853      | -            | -                | -                | -         |   -21.66 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1205 | 2024-06-10 | EYEBALLERS        | W   | 0.826      | 0.435        | -                | 0.507 (0.182)    | 0 (0.000) |     9.53 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1359 | 2024-06-07 | HAVU              | W   | 0.808      | -            | -                | -                | 0 (0.000) |     4.68 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1486 | 2024-06-05 | CYBERSHOKE        | W   | 0.794      | 0.435        | 0.039 (0.013)    | 0.351 (0.121)    | -         |     8.36 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1570 | 2024-06-03 | Permitta          | L   | 0.779      | -            | -                | -                | -         |   -15.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1583 | 2024-06-02 | FURIA             | W   | 0.774      | 0.435        | 0.284 (0.096)    | 0.487 (0.164)    | -         |    23.61 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1594 | 2024-06-02 | VP.Prodigy        | W   | 0.772      | 0.435        | 0.025 (0.009)    | 0.398 (0.134)    | -         |    11.02 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1603 | 2024-06-01 | SINNERS           | W   | 0.768      | 0.435        | 0.037 (0.012)    | 0.794 (0.265)    | -         |    16.24 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1648 | 2024-05-31 | GamerLegion       | W   | 0.761      | 0.435        | 0.173 (0.057)    | -                | -         |    19.04 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1727 | 2024-05-28 | Permitta          | L   | 0.739      | -            | -                | -                | -         |   -12.27 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1767 | 2024-05-26 | DMS               | W   | 0.726      | 0.435        | -                | 0.444 (0.140)    | -         |    10.86 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1793 | 2024-05-24 | SINNERS           | L   | 0.715      | -            | -                | -                | -         |    -7.29 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1808 | 2024-05-23 | Sampi             | L   | 0.708      | -            | -                | -                | -         |   -12.14 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1979 | 2024-05-18 | NOM               | W   | 0.675      | -            | -                | -                | -         |     2.41 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2051 | 2024-05-16 | Space             | W   | 0.661      | -            | -                | -                | -         |     7.76 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2098 | 2024-05-15 | 777               | W   | 0.655      | -            | -                | -                | -         |     4.74 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3209 | 2024-04-03 | 3DMAX             | L   | 0.375      | -            | -                | -                | -         |    -0.20 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3314 | 2024-03-28 | Space             | W   | 0.334      | -            | -                | -                | -         |     3.59 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,388.82)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.868 | $2,000.00      | $1,735.00       |
| 2024-06-16 |      0.866 | $2,500.00      | $2,165.97       |
| 2024-06-09 |      0.821 | $3,000.00      | $2,462.29       |
| 2024-06-02 |      0.774 | $22,000.00     | $17,025.56      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
