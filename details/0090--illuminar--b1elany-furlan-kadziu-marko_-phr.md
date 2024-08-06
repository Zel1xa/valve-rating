### Roster Details<br />
Team Name: Illuminar<br />
Roster: b1elany, Furlan, kadziu, Markoś, phr<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  907.3<br />
<br />
Final Rank Value (907.3) = Starting Rank Value (904.9) + Head To Head Adjustments (2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.410[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 904.9
- 400 + ( ( 0.246 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 904.9


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
|           27 |        3 | 2024-08-06 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -18.58 | b1elany, Furlan, kadziu, Markoś, phr     |
|           26 |      118 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.96 | b1elany, Furlan, kadziu, Markoś, phr     |
|           25 |      208 | 2024-07-31 | Sampi             | W   | 1.000      | 0.143        | 0.027 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    15.23 | b1elany, Furlan, kadziu, Markoś, phr     |
|           24 |      506 | 2024-07-22 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -15.81 | b1elany, Furlan, kadziu, Markoś, phr     |
|           23 |      570 | 2024-07-20 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | 0 (0.000) |    26.14 | b1elany, Furlan, kadziu, Markoś, phr     |
|           22 |      667 | 2024-07-18 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.90 | b1elany, Furlan, kadziu, Markoś, phr     |
|           21 |      774 | 2024-07-16 | kONO              | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.565 (0.209)    | 0 (0.000) |    13.05 | b1elany, Furlan, kadziu, Markoś, phr     |
|           20 |      822 | 2024-07-15 | ALTERNATE aTTaX   | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.549 (0.203)    | 0 (0.000) |    14.78 | b1elany, Furlan, kadziu, Markoś, phr     |
|           19 |      881 | 2024-07-11 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -17.05 | b1elany, Furlan, kadziu, Markoś, splawik |
|           18 |     1073 | 2024-06-15 | B8                | L   | 0.854      | -            | -                | -                | -         |    -5.99 | b1elany, Furlan, kadziu, phr, ultimate   |
|           17 |     1134 | 2024-06-13 | GamerLegion       | W   | 0.842      | 0.435        | 0.173 (0.063)    | -                | 0 (0.000) |    21.81 | Furlan, kadziu, phr, splawik, ultimate   |
|           16 |     1145 | 2024-06-13 | Enterprise        | L   | 0.841      | -            | -                | -                | -         |   -11.43 | b1elany, Furlan, kadziu, phr, ultimate   |
|           15 |     1197 | 2024-06-11 | Sampi             | W   | 0.826      | 0.435        | 0.027 (0.010)    | 1.000 (0.359)    | 0 (0.000) |    12.45 | Furlan, kadziu, phr, splawik, ultimate   |
|           14 |     1287 | 2024-06-09 | VP.Prodigy        | W   | 0.813      | 0.435        | 0.025 (0.009)    | 0.392 (0.138)    | 0 (0.000) |    13.55 | b1elany, Furlan, kadziu, phr, ultimate   |
|           13 |     1323 | 2024-06-08 | 3DMAX             | W   | 0.808      | 0.450        | 0.509 (0.185)    | 1.000 (0.364)    | 0 (0.000) |    24.71 | b1elany, Furlan, kadziu, phr, ultimate   |
|           12 |     1393 | 2024-06-07 | EYEBALLERS        | W   | 0.801      | 0.450        | -                | 0.499 (0.180)    | 0 (0.000) |    14.31 | b1elany, Furlan, kadziu, phr, ultimate   |
|           11 |     1402 | 2024-06-07 | CYBERSHOKE        | W   | 0.799      | 0.435        | 0.039 (0.014)    | 0.347 (0.120)    | 0 (0.000) |    13.66 | b1elany, Furlan, kadziu, phr, ultimate   |
|           10 |     1445 | 2024-06-06 | Enterprise        | W   | 0.795      | 0.450        | 0.039 (0.014)    | 0.616 (0.220)    | -         |    15.61 | b1elany, Furlan, kadziu, phr, ultimate   |
|            9 |     1519 | 2024-06-05 | Aurora Young Blud | L   | 0.787      | -            | -                | -                | -         |   -10.79 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            8 |     1552 | 2024-06-04 | Passion UA        | L   | 0.781      | -            | -                | -                | -         |    -4.85 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            7 |     1706 | 2024-05-29 | INFINITE          | L   | 0.743      | -            | -                | -                | -         |   -19.56 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            6 |     1721 | 2024-05-29 | Passion UA        | L   | 0.740      | -            | -                | -                | -         |    -5.63 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            5 |     1817 | 2024-05-24 | Enterprise        | L   | 0.707      | -            | -                | -                | -         |    -9.81 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            4 |     1818 | 2024-05-24 | MOUZ NXT          | L   | 0.706      | -            | -                | -                | -         |    -6.27 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            3 |     1878 | 2024-05-22 | Zero Tenacity     | L   | 0.693      | -            | -                | -                | -         |    -4.60 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            2 |     1911 | 2024-05-21 | NAVI Junior       | L   | 0.688      | -            | -                | -                | -         |   -18.89 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            1 |     1947 | 2024-05-20 | Sampi             | L   | 0.681      | -            | -                | -                | -         |   -10.83 | ANeraX, b1elany, Furlan, phr, ultimate   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,890.69)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.867 | $2,500.00      | $2,167.36       |
| 2024-06-16 |      0.862 | $2,000.00      | $1,723.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
