### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [101](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  861.5<br />
<br />
Final Rank Value (861.5) = Starting Rank Value (942.8) + Head To Head Adjustments (-81.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.469[<sup>1</sup>](#table2)
- Bounty Collected: 0.389[<sup>2</sup>](#table1)
- Opponent Network: 0.197[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.264<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 942.8
- 400 + ( ( 0.264 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 942.8


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
|           37 |        2 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -19.90 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |       14 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.21 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |       61 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.97 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      104 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.555 (0.241)    | 0 (0.000) |    14.00 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      141 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | 0 (0.000) |    19.94 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      169 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.89 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      174 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.34 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      217 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -22.70 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      253 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.99 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      324 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -24.50 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      379 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.555 (0.241)    | 0 (0.000) |    12.82 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      421 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.01 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      569 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -12.50 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      593 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.62 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      630 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -25.58 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      689 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.81 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      922 | 2024-06-15 | 3DMAX             | L   | 0.887      | -            | -                | -                | -         |    -2.31 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |      960 | 2024-06-14 | Gaimin Gladiators | W   | 0.880      | 0.435        | 0.040 (0.015)    | 0.360 (0.138)    | 0 (0.000) |    12.53 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |      976 | 2024-06-14 | Spirit Academy    | L   | 0.878      | -            | -                | -                | -         |   -22.71 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1082 | 2024-06-10 | EYEBALLERS        | W   | 0.852      | 0.435        | -                | 0.512 (0.190)    | 0 (0.000) |     9.30 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1245 | 2024-06-07 | HAVU              | W   | 0.833      | -            | -                | -                | 0 (0.000) |     4.50 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1377 | 2024-06-05 | CYBERSHOKE        | W   | 0.820      | 0.435        | 0.040 (0.014)    | 0.348 (0.124)    | 0 (0.000) |     7.96 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1461 | 2024-06-03 | Permitta          | L   | 0.805      | -            | -                | -                | -         |   -16.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1474 | 2024-06-02 | FURIA             | W   | 0.799      | 0.435        | 0.286 (0.099)    | 0.494 (0.172)    | -         |    24.28 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1486 | 2024-06-02 | VP.Prodigy        | W   | 0.797      | 0.435        | 0.026 (0.009)    | 0.405 (0.140)    | -         |    10.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1495 | 2024-06-01 | SINNERS           | W   | 0.794      | 0.435        | 0.038 (0.013)    | 0.768 (0.265)    | -         |    15.18 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1540 | 2024-05-31 | GamerLegion       | W   | 0.786      | 0.435        | 0.176 (0.060)    | -                | -         |    19.22 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1619 | 2024-05-28 | Permitta          | L   | 0.764      | -            | -                | -                | -         |   -13.71 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1661 | 2024-05-26 | DMS               | W   | 0.751      | 0.435        | -                | 0.447 (0.146)    | -         |    10.35 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1687 | 2024-05-24 | SINNERS           | L   | 0.740      | -            | -                | -                | -         |    -9.29 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1702 | 2024-05-23 | Sampi             | L   | 0.733      | -            | -                | -                | -         |   -13.61 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1814 | 2024-05-21 | Zero Tenacity     | W   | 0.718      | 0.435        | 0.139 (0.043)    | 1.000 (0.312)    | -         |    14.42 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1898 | 2024-05-18 | NOM               | W   | 0.700      | -            | -                | -                | -         |     2.25 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     1971 | 2024-05-16 | Space             | W   | 0.687      | -            | -                | -                | -         |     7.83 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2018 | 2024-05-15 | 777               | W   | 0.680      | -            | -                | -                | -         |     4.67 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3156 | 2024-04-03 | 3DMAX             | L   | 0.400      | -            | -                | -                | -         |    -0.23 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3267 | 2024-03-28 | Space             | W   | 0.359      | -            | -                | -                | -         |     3.73 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,134.51)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.893 | $2,000.00      | $1,785.56       |
| 2024-06-16 |      0.892 | $2,500.00      | $2,229.17       |
| 2024-06-09 |      0.846 | $3,000.00      | $2,538.13       |
| 2024-06-02 |      0.799 | $22,000.00     | $17,581.67      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
