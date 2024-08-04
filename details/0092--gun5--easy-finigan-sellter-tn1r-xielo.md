### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [92](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  875.0<br />
<br />
Final Rank Value (875.0) = Starting Rank Value (927.5) + Head To Head Adjustments (-52.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.468[<sup>1</sup>](#table2)
- Bounty Collected: 0.378[<sup>2</sup>](#table1)
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
|           38 |       16 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.534 (0.267)    | 0 (0.000) |    25.22 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       22 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.46 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |       88 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.83 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |      104 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.30 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      152 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.91 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      194 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    13.27 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      231 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.06 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      259 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      264 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.27 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      307 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -15.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      343 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.60 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      414 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -16.81 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      467 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    12.59 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      508 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.12 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      647 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.66 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      674 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      709 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -25.08 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      763 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.20 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |      999 | 2024-06-15 | 3DMAX             | L   | 0.868      | -            | -                | -                | -         |    -1.98 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1043 | 2024-06-14 | Gaimin Gladiators | W   | 0.861      | 0.435        | 0.038 (0.014)    | 0.351 (0.131)    | 0 (0.000) |    12.69 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1060 | 2024-06-14 | Spirit Academy    | L   | 0.860      | -            | -                | -                | -         |   -21.81 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1164 | 2024-06-10 | EYEBALLERS        | W   | 0.833      | 0.435        | -                | 0.510 (0.184)    | 0 (0.000) |     9.72 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1318 | 2024-06-07 | HAVU              | W   | 0.815      | -            | -                | -                | 0 (0.000) |     4.76 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1445 | 2024-06-05 | CYBERSHOKE        | W   | 0.801      | 0.435        | 0.039 (0.014)    | 0.351 (0.122)    | -         |     8.43 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1529 | 2024-06-03 | Permitta          | L   | 0.786      | -            | -                | -                | -         |   -15.24 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1542 | 2024-06-02 | FURIA             | W   | 0.781      | 0.435        | 0.284 (0.096)    | 0.490 (0.166)    | -         |    23.81 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1553 | 2024-06-02 | VP.Prodigy        | W   | 0.779      | 0.435        | 0.025 (0.009)    | 0.401 (0.136)    | -         |    11.14 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1562 | 2024-06-01 | SINNERS           | W   | 0.775      | 0.435        | 0.037 (0.013)    | 0.757 (0.255)    | -         |    15.59 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1607 | 2024-05-31 | GamerLegion       | W   | 0.767      | 0.435        | 0.174 (0.058)    | -                | -         |    19.24 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1686 | 2024-05-28 | Permitta          | L   | 0.746      | -            | -                | -                | -         |   -12.39 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1726 | 2024-05-26 | DMS               | W   | 0.732      | 0.435        | -                | 0.446 (0.142)    | -         |    10.88 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1752 | 2024-05-24 | SINNERS           | L   | 0.722      | -            | -                | -                | -         |    -8.25 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1767 | 2024-05-23 | Sampi             | L   | 0.715      | -            | -                | -                | -         |   -12.25 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1938 | 2024-05-18 | NOM               | W   | 0.682      | -            | -                | -                | -         |     2.36 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2010 | 2024-05-16 | Space             | W   | 0.668      | -            | -                | -                | -         |     7.91 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2057 | 2024-05-15 | 777               | W   | 0.662      | -            | -                | -                | -         |     4.78 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3168 | 2024-04-03 | 3DMAX             | L   | 0.382      | -            | -                | -                | -         |    -0.21 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3273 | 2024-03-28 | Space             | W   | 0.341      | -            | -                | -                | -         |     3.70 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,588.90)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.874 | $2,000.00      | $1,748.56       |
| 2024-06-16 |      0.873 | $2,500.00      | $2,182.93       |
| 2024-06-09 |      0.828 | $3,000.00      | $2,482.64       |
| 2024-06-02 |      0.781 | $22,000.00     | $17,174.77      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
