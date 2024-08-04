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
|           38 |       38 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.534 (0.267)    | 0 (0.000) |    25.27 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       44 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.42 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |      110 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.82 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |      128 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.30 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      174 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.92 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      218 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    13.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      254 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.09 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      283 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.74 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      288 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.29 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      331 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -15.90 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      367 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.62 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      438 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -17.29 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      491 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    12.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      532 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.14 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      674 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.68 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      697 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.86 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      733 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -25.12 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      786 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.25 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |     1023 | 2024-06-15 | 3DMAX             | L   | 0.867      | -            | -                | -                | -         |    -1.99 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1067 | 2024-06-14 | Gaimin Gladiators | W   | 0.860      | 0.435        | 0.038 (0.014)    | 0.350 (0.131)    | 0 (0.000) |    12.69 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1084 | 2024-06-14 | Spirit Academy    | L   | 0.858      | -            | -                | -                | -         |   -21.82 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1188 | 2024-06-10 | EYEBALLERS        | W   | 0.832      | 0.435        | -                | 0.509 (0.184)    | 0 (0.000) |     9.58 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1342 | 2024-06-07 | HAVU              | W   | 0.813      | -            | -                | -                | 0 (0.000) |     4.72 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1469 | 2024-06-05 | CYBERSHOKE        | W   | 0.800      | 0.435        | 0.039 (0.014)    | 0.351 (0.122)    | -         |     8.37 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1553 | 2024-06-03 | Permitta          | L   | 0.785      | -            | -                | -                | -         |   -15.25 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1566 | 2024-06-02 | FURIA             | W   | 0.780      | 0.435        | 0.284 (0.096)    | 0.490 (0.166)    | -         |    23.77 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1577 | 2024-06-02 | VP.Prodigy        | W   | 0.778      | 0.435        | 0.025 (0.009)    | 0.401 (0.135)    | -         |    11.10 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1586 | 2024-06-01 | SINNERS           | W   | 0.774      | 0.435        | 0.037 (0.013)    | 0.797 (0.268)    | -         |    16.34 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1631 | 2024-05-31 | GamerLegion       | W   | 0.766      | 0.435        | 0.173 (0.058)    | -                | -         |    19.18 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1710 | 2024-05-28 | Permitta          | L   | 0.745      | -            | -                | -                | -         |   -12.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1750 | 2024-05-26 | DMS               | W   | 0.731      | 0.435        | -                | 0.446 (0.142)    | -         |    10.83 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1776 | 2024-05-24 | SINNERS           | L   | 0.720      | -            | -                | -                | -         |    -7.37 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1791 | 2024-05-23 | Sampi             | L   | 0.714      | -            | -                | -                | -         |   -12.23 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1962 | 2024-05-18 | NOM               | W   | 0.680      | -            | -                | -                | -         |     2.35 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2034 | 2024-05-16 | Space             | W   | 0.667      | -            | -                | -                | -         |     7.82 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2081 | 2024-05-15 | 777               | W   | 0.660      | -            | -                | -                | -         |     4.76 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3192 | 2024-04-03 | 3DMAX             | L   | 0.380      | -            | -                | -                | -         |    -0.21 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3297 | 2024-03-28 | Space             | W   | 0.340      | -            | -                | -                | -         |     3.64 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,557.49)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.873 | $2,000.00      | $1,746.44       |
| 2024-06-16 |      0.872 | $2,500.00      | $2,180.27       |
| 2024-06-09 |      0.826 | $3,000.00      | $2,479.44       |
| 2024-06-02 |      0.780 | $22,000.00     | $17,151.34      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
