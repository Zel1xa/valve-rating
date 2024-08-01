### Roster Details<br />
Team Name: Illuminar<br />
Roster: b1elany, Furlan, kadziu, Markoś, phr<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  949.0<br />
<br />
Final Rank Value (949.0) = Starting Rank Value (919.6) + Head To Head Adjustments (29.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.421[<sup>2</sup>](#table1)
- Opponent Network: 0.244[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 919.6
- 400 + ( ( 0.252 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 919.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |       53 | 2024-07-31 | Sampi             | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    14.64 | b1elany, Furlan, kadziu, Markoś, phr     |
|           25 |      355 | 2024-07-22 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -16.02 | b1elany, Furlan, kadziu, Markoś, phr     |
|           24 |      421 | 2024-07-20 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.124 (0.046)    | 0.818 (0.303)    | 0 (0.000) |    25.84 | b1elany, Furlan, kadziu, Markoś, phr     |
|           23 |      524 | 2024-07-18 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.07 | b1elany, Furlan, kadziu, Markoś, phr     |
|           22 |      634 | 2024-07-16 | kONO              | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.547 (0.203)    | 0 (0.000) |    13.47 | b1elany, Furlan, kadziu, Markoś, phr     |
|           21 |      686 | 2024-07-15 | ALTERNATE aTTaX   | W   | 1.000      | 0.371        | 0.032 (0.012)    | 0.564 (0.209)    | 0 (0.000) |    13.00 | b1elany, Furlan, kadziu, Markoś, phr     |
|           20 |      746 | 2024-07-11 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -17.17 | b1elany, Furlan, kadziu, Markoś, splawik |
|           19 |      933 | 2024-06-15 | B8                | L   | 0.886      | -            | -                | -                | -         |    -6.92 | b1elany, Furlan, kadziu, phr, ultimate   |
|           18 |      988 | 2024-06-13 | GamerLegion       | W   | 0.875      | 0.435        | 0.176 (0.067)    | -                | 0 (0.000) |    22.40 | Furlan, kadziu, phr, splawik, ultimate   |
|           17 |      999 | 2024-06-13 | Enterprise        | L   | 0.873      | -            | -                | -                | -         |   -12.66 | b1elany, Furlan, kadziu, phr, ultimate   |
|           16 |     1052 | 2024-06-11 | Sampi             | W   | 0.859      | 0.435        | 0.028 (0.011)    | 1.000 (0.373)    | 0 (0.000) |    11.90 | Furlan, kadziu, phr, splawik, ultimate   |
|           15 |     1144 | 2024-06-09 | VP.Prodigy        | W   | 0.846      | 0.435        | 0.026 (0.010)    | 0.405 (0.149)    | 0 (0.000) |    13.56 | b1elany, Furlan, kadziu, phr, ultimate   |
|           14 |     1181 | 2024-06-08 | 3DMAX             | W   | 0.841      | 0.450        | 0.505 (0.191)    | 1.000 (0.378)    | 0 (0.000) |    25.55 | b1elany, Furlan, kadziu, phr, ultimate   |
|           13 |     1258 | 2024-06-07 | EYEBALLERS        | W   | 0.833      | 0.450        | -                | 0.513 (0.192)    | 0 (0.000) |    14.48 | b1elany, Furlan, kadziu, phr, ultimate   |
|           12 |     1267 | 2024-06-07 | CYBERSHOKE        | W   | 0.832      | 0.435        | 0.040 (0.014)    | -                | 0 (0.000) |    13.68 | b1elany, Furlan, kadziu, phr, ultimate   |
|           11 |     1312 | 2024-06-06 | Enterprise        | W   | 0.828      | 0.450        | 0.040 (0.015)    | 0.622 (0.232)    | -         |    15.47 | b1elany, Furlan, kadziu, phr, ultimate   |
|           10 |     1389 | 2024-06-05 | Aurora Young Blud | L   | 0.820      | -            | -                | -                | -         |   -12.53 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            9 |     1422 | 2024-06-04 | Passion UA        | L   | 0.814      | -            | -                | -                | -         |    -5.68 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            8 |     1577 | 2024-05-29 | INFINITE          | L   | 0.775      | -            | -                | -                | -         |   -20.77 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            7 |     1592 | 2024-05-29 | Passion UA        | L   | 0.772      | -            | -                | -                | -         |    -6.66 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            6 |     1690 | 2024-05-24 | Enterprise        | L   | 0.740      | -            | -                | -                | -         |   -11.20 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            5 |     1691 | 2024-05-24 | MOUZ NXT          | L   | 0.739      | -            | -                | -                | -         |    -7.40 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            4 |     1761 | 2024-05-22 | Zero Tenacity     | L   | 0.726      | -            | -                | -                | -         |    -5.92 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            3 |     1799 | 2024-05-21 | NAVI Junior       | L   | 0.721      | -            | -                | -                | -         |   -20.10 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            2 |     1838 | 2024-05-20 | Sampi             | L   | 0.714      | -            | -                | -                | -         |   -12.39 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            1 |     1855 | 2024-05-19 | Passion UA        | W   | 0.709      | 0.371        | 0.172 (0.045)    | 1.000 (0.263)    | -         |    13.92 | ANeraX, b1elany, Furlan, phr, ultimate   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,038.19)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.900 | $2,500.00      | $2,249.31       |
| 2024-06-16 |      0.894 | $2,000.00      | $1,788.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
