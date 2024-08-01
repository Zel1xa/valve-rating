### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
<br />
Final Rank Value:  866.1<br />
<br />
Final Rank Value (866.1) = Starting Rank Value (943.6) + Head To Head Adjustments (-77.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.469[<sup>1</sup>](#table2)
- Bounty Collected: 0.390[<sup>2</sup>](#table1)
- Opponent Network: 0.197[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.264<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 943.6
- 400 + ( ( 0.264 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 943.6


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
|           37 |        6 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.61 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |        7 | 2024-08-01 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -13.47 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |       55 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.92 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |       98 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.555 (0.241)    | 0 (0.000) |    14.12 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      135 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | 0 (0.000) |    20.04 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      163 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.00 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      168 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.27 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      211 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -23.34 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      247 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.87 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      318 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -25.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      373 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.555 (0.241)    | 0 (0.000) |    12.91 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      415 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      560 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -12.42 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      587 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.65 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      624 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -28.48 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      683 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.83 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      916 | 2024-06-15 | 3DMAX             | L   | 0.888      | -            | -                | -                | -         |    -2.32 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |      954 | 2024-06-14 | Gaimin Gladiators | W   | 0.881      | 0.435        | 0.040 (0.015)    | 0.361 (0.138)    | 0 (0.000) |    12.57 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |      970 | 2024-06-14 | Spirit Academy    | L   | 0.880      | -            | -                | -                | -         |   -22.76 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1076 | 2024-06-10 | EYEBALLERS        | W   | 0.853      | 0.435        | -                | 0.513 (0.190)    | 0 (0.000) |     9.31 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1239 | 2024-06-07 | HAVU              | W   | 0.835      | -            | -                | -                | 0 (0.000) |     4.50 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1371 | 2024-06-05 | CYBERSHOKE        | W   | 0.821      | 0.435        | 0.040 (0.014)    | 0.348 (0.124)    | 0 (0.000) |     7.96 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1455 | 2024-06-03 | Permitta          | L   | 0.806      | -            | -                | -                | -         |   -16.51 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1468 | 2024-06-02 | FURIA             | W   | 0.801      | 0.435        | 0.286 (0.100)    | 0.495 (0.172)    | -         |    24.32 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1480 | 2024-06-02 | VP.Prodigy        | W   | 0.799      | 0.435        | 0.026 (0.009)    | 0.405 (0.141)    | -         |    10.77 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1489 | 2024-06-01 | SINNERS           | W   | 0.795      | 0.435        | 0.038 (0.013)    | 0.768 (0.266)    | -         |    15.21 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1534 | 2024-05-31 | GamerLegion       | W   | 0.788      | 0.435        | 0.176 (0.060)    | -                | -         |    19.26 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1613 | 2024-05-28 | Permitta          | L   | 0.766      | -            | -                | -                | -         |   -13.71 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1655 | 2024-05-26 | DMS               | W   | 0.752      | 0.435        | -                | 0.447 (0.146)    | -         |    10.36 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1681 | 2024-05-24 | SINNERS           | L   | 0.742      | -            | -                | -                | -         |    -9.31 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1696 | 2024-05-23 | Sampi             | L   | 0.735      | -            | -                | -                | -         |   -13.64 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1808 | 2024-05-21 | Zero Tenacity     | W   | 0.719      | 0.435        | 0.139 (0.043)    | 1.000 (0.313)    | -         |    14.42 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1892 | 2024-05-18 | NOM               | W   | 0.702      | -            | -                | -                | -         |     2.24 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     1965 | 2024-05-16 | Space             | W   | 0.688      | -            | -                | -                | -         |     7.84 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2012 | 2024-05-15 | 777               | W   | 0.682      | -            | -                | -                | -         |     4.67 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3150 | 2024-04-03 | 3DMAX             | L   | 0.402      | -            | -                | -                | -         |    -0.23 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3261 | 2024-03-28 | Space             | W   | 0.361      | -            | -                | -                | -         |     3.75 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,183.68)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.894 | $2,000.00      | $1,788.89       |
| 2024-06-16 |      0.893 | $2,500.00      | $2,233.33       |
| 2024-06-09 |      0.848 | $3,000.00      | $2,543.13       |
| 2024-06-02 |      0.801 | $22,000.00     | $17,618.33      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
