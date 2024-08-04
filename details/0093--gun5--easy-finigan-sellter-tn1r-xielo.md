### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [93](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  875.3<br />
<br />
Final Rank Value (875.3) = Starting Rank Value (928.1) + Head To Head Adjustments (-52.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.468[<sup>1</sup>](#table2)
- Bounty Collected: 0.378[<sup>2</sup>](#table1)
- Opponent Network: 0.187[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 928.1
- 400 + ( ( 0.258 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 928.1


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
|           38 |       37 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.534 (0.267)    | 0 (0.000) |    25.25 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       43 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.42 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |      109 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.82 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |      127 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.30 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      173 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.92 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      217 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    13.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      253 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.09 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      282 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.74 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      287 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.29 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      330 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -15.90 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      366 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.62 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      437 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -17.30 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      490 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    12.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      531 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.15 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      673 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.68 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      696 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.86 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      732 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -25.12 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      785 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.25 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |     1022 | 2024-06-15 | 3DMAX             | L   | 0.867      | -            | -                | -                | -         |    -1.99 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1066 | 2024-06-14 | Gaimin Gladiators | W   | 0.860      | 0.435        | 0.038 (0.014)    | 0.351 (0.131)    | 0 (0.000) |    12.70 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1083 | 2024-06-14 | Spirit Academy    | L   | 0.859      | -            | -                | -                | -         |   -21.83 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1187 | 2024-06-10 | EYEBALLERS        | W   | 0.832      | 0.435        | -                | 0.509 (0.184)    | 0 (0.000) |     9.58 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1341 | 2024-06-07 | HAVU              | W   | 0.814      | -            | -                | -                | 0 (0.000) |     4.72 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1468 | 2024-06-05 | CYBERSHOKE        | W   | 0.800      | 0.435        | 0.039 (0.014)    | 0.351 (0.122)    | -         |     8.37 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1552 | 2024-06-03 | Permitta          | L   | 0.785      | -            | -                | -                | -         |   -15.26 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1565 | 2024-06-02 | FURIA             | W   | 0.780      | 0.435        | 0.284 (0.096)    | 0.490 (0.166)    | -         |    23.78 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1576 | 2024-06-02 | VP.Prodigy        | W   | 0.778      | 0.435        | 0.025 (0.009)    | 0.401 (0.136)    | -         |    11.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1585 | 2024-06-01 | SINNERS           | W   | 0.774      | 0.435        | 0.037 (0.013)    | 0.797 (0.268)    | -         |    16.34 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1630 | 2024-05-31 | GamerLegion       | W   | 0.767      | 0.435        | 0.173 (0.058)    | -                | -         |    19.19 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1709 | 2024-05-28 | Permitta          | L   | 0.745      | -            | -                | -                | -         |   -12.39 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1749 | 2024-05-26 | DMS               | W   | 0.732      | 0.435        | -                | 0.446 (0.142)    | -         |    10.84 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1775 | 2024-05-24 | SINNERS           | L   | 0.721      | -            | -                | -                | -         |    -7.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1790 | 2024-05-23 | Sampi             | L   | 0.714      | -            | -                | -                | -         |   -12.24 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1961 | 2024-05-18 | NOM               | W   | 0.681      | -            | -                | -                | -         |     2.35 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2033 | 2024-05-16 | Space             | W   | 0.667      | -            | -                | -                | -         |     7.82 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2080 | 2024-05-15 | 777               | W   | 0.661      | -            | -                | -                | -         |     4.76 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3191 | 2024-04-03 | 3DMAX             | L   | 0.381      | -            | -                | -                | -         |    -0.21 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3296 | 2024-03-28 | Space             | W   | 0.340      | -            | -                | -                | -         |     3.64 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,566.37)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.874 | $2,000.00      | $1,747.04       |
| 2024-06-16 |      0.872 | $2,500.00      | $2,181.02       |
| 2024-06-09 |      0.827 | $3,000.00      | $2,480.35       |
| 2024-06-02 |      0.780 | $22,000.00     | $17,157.96      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
