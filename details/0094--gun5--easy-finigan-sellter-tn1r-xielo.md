### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  873.5<br />
<br />
Final Rank Value (873.5) = Starting Rank Value (927.9) + Head To Head Adjustments (-54.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.468[<sup>1</sup>](#table2)
- Bounty Collected: 0.378[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 927.9
- 400 + ( ( 0.258 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 927.9


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
|           38 |       43 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.017 (0.009)    | 0.534 (0.267)    | 0 (0.000) |    25.32 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |       48 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.42 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |      114 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |      132 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.34 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      179 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.87 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      222 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    13.19 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      258 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    20.19 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      287 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.83 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      292 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -26.23 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      335 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -15.79 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      371 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.51 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      442 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -17.17 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      495 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.522 (0.227)    | 0 (0.000) |    12.49 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      536 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -16.03 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      678 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.54 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      701 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.91 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      737 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -27.89 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      790 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.24 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |     1027 | 2024-06-15 | 3DMAX             | L   | 0.865      | -            | -                | -                | -         |    -1.97 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |     1071 | 2024-06-14 | Gaimin Gladiators | W   | 0.858      | 0.435        | 0.038 (0.014)    | 0.349 (0.130)    | 0 (0.000) |    12.63 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |     1088 | 2024-06-14 | Spirit Academy    | L   | 0.856      | -            | -                | -                | -         |   -21.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1192 | 2024-06-10 | EYEBALLERS        | W   | 0.830      | 0.435        | -                | 0.509 (0.183)    | 0 (0.000) |     9.56 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1346 | 2024-06-07 | HAVU              | W   | 0.811      | -            | -                | -                | 0 (0.000) |     4.70 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1473 | 2024-06-05 | CYBERSHOKE        | W   | 0.798      | 0.435        | 0.039 (0.014)    | 0.351 (0.122)    | -         |     8.36 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1557 | 2024-06-03 | Permitta          | L   | 0.783      | -            | -                | -                | -         |   -15.20 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1570 | 2024-06-02 | FURIA             | W   | 0.777      | 0.435        | 0.284 (0.096)    | 0.490 (0.165)    | -         |    23.70 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1581 | 2024-06-02 | VP.Prodigy        | W   | 0.776      | 0.435        | 0.025 (0.009)    | 0.400 (0.135)    | -         |    11.07 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1590 | 2024-06-01 | SINNERS           | W   | 0.772      | 0.435        | 0.037 (0.013)    | 0.797 (0.267)    | -         |    16.30 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1635 | 2024-05-31 | GamerLegion       | W   | 0.764      | 0.435        | 0.173 (0.058)    | -                | -         |    19.14 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1714 | 2024-05-28 | Permitta          | L   | 0.742      | -            | -                | -                | -         |   -12.34 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1754 | 2024-05-26 | DMS               | W   | 0.729      | 0.435        | -                | 0.446 (0.141)    | -         |    10.80 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1780 | 2024-05-24 | SINNERS           | L   | 0.718      | -            | -                | -                | -         |    -7.34 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1795 | 2024-05-23 | Sampi             | L   | 0.711      | -            | -                | -                | -         |   -12.20 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1966 | 2024-05-18 | NOM               | W   | 0.678      | -            | -                | -                | -         |     2.34 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     2038 | 2024-05-16 | Space             | W   | 0.665      | -            | -                | -                | -         |     7.79 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     2085 | 2024-05-15 | 777               | W   | 0.658      | -            | -                | -                | -         |     4.75 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3196 | 2024-04-03 | 3DMAX             | L   | 0.378      | -            | -                | -                | -         |    -0.20 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3301 | 2024-03-28 | Space             | W   | 0.338      | -            | -                | -                | -         |     3.62 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,487.15)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.871 | $2,000.00      | $1,741.67       |
| 2024-06-16 |      0.870 | $2,500.00      | $2,174.31       |
| 2024-06-09 |      0.824 | $3,000.00      | $2,472.29       |
| 2024-06-02 |      0.777 | $22,000.00     | $17,098.89      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
