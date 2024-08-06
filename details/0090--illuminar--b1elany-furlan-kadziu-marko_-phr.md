### Roster Details<br />
Team Name: Illuminar<br />
Roster: b1elany, Furlan, kadziu, Markoś, phr<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  908.0<br />
<br />
Final Rank Value (908.0) = Starting Rank Value (905.5) + Head To Head Adjustments (2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.410[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.5
- 400 + ( ( 0.246 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 905.5


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
|           27 |        6 | 2024-08-06 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -18.58 | b1elany, Furlan, kadziu, Markoś, phr     |
|           26 |      122 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.97 | b1elany, Furlan, kadziu, Markoś, phr     |
|           25 |      212 | 2024-07-31 | Sampi             | W   | 1.000      | 0.143        | 0.027 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    15.40 | b1elany, Furlan, kadziu, Markoś, phr     |
|           24 |      510 | 2024-07-22 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -15.83 | b1elany, Furlan, kadziu, Markoś, phr     |
|           23 |      574 | 2024-07-20 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | 0 (0.000) |    26.13 | b1elany, Furlan, kadziu, Markoś, phr     |
|           22 |      671 | 2024-07-18 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.91 | b1elany, Furlan, kadziu, Markoś, phr     |
|           21 |      778 | 2024-07-16 | kONO              | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.553 (0.205)    | 0 (0.000) |    13.05 | b1elany, Furlan, kadziu, Markoś, phr     |
|           20 |      826 | 2024-07-15 | ALTERNATE aTTaX   | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.537 (0.199)    | 0 (0.000) |    14.79 | b1elany, Furlan, kadziu, Markoś, phr     |
|           19 |      885 | 2024-07-11 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -17.04 | b1elany, Furlan, kadziu, Markoś, splawik |
|           18 |     1077 | 2024-06-15 | B8                | L   | 0.853      | -            | -                | -                | -         |    -5.97 | b1elany, Furlan, kadziu, phr, ultimate   |
|           17 |     1138 | 2024-06-13 | GamerLegion       | W   | 0.842      | 0.435        | 0.173 (0.063)    | -                | 0 (0.000) |    21.78 | Furlan, kadziu, phr, splawik, ultimate   |
|           16 |     1149 | 2024-06-13 | Enterprise        | L   | 0.840      | -            | -                | -                | -         |   -11.44 | b1elany, Furlan, kadziu, phr, ultimate   |
|           15 |     1201 | 2024-06-11 | Sampi             | W   | 0.826      | 0.435        | 0.027 (0.010)    | 1.000 (0.359)    | 0 (0.000) |    12.42 | Furlan, kadziu, phr, splawik, ultimate   |
|           14 |     1291 | 2024-06-09 | VP.Prodigy        | W   | 0.813      | 0.435        | 0.025 (0.009)    | 0.383 (0.135)    | 0 (0.000) |    13.53 | b1elany, Furlan, kadziu, phr, ultimate   |
|           13 |     1327 | 2024-06-08 | 3DMAX             | W   | 0.808      | 0.450        | 0.510 (0.185)    | 1.000 (0.364)    | 0 (0.000) |    24.70 | b1elany, Furlan, kadziu, phr, ultimate   |
|           12 |     1397 | 2024-06-07 | EYEBALLERS        | W   | 0.800      | 0.450        | -                | 0.488 (0.176)    | 0 (0.000) |    14.43 | b1elany, Furlan, kadziu, phr, ultimate   |
|           11 |     1406 | 2024-06-07 | CYBERSHOKE        | W   | 0.799      | 0.435        | 0.039 (0.014)    | 0.339 (0.118)    | 0 (0.000) |    13.63 | b1elany, Furlan, kadziu, phr, ultimate   |
|           10 |     1449 | 2024-06-06 | Enterprise        | W   | 0.795      | 0.450        | 0.039 (0.014)    | 0.641 (0.229)    | -         |    15.59 | b1elany, Furlan, kadziu, phr, ultimate   |
|            9 |     1523 | 2024-06-05 | Aurora Young Blud | L   | 0.787      | -            | -                | -                | -         |   -10.80 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            8 |     1556 | 2024-06-04 | Passion UA        | L   | 0.781      | -            | -                | -                | -         |    -4.86 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            7 |     1710 | 2024-05-29 | INFINITE          | L   | 0.742      | -            | -                | -                | -         |   -19.56 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            6 |     1725 | 2024-05-29 | Passion UA        | L   | 0.739      | -            | -                | -                | -         |    -5.64 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            5 |     1821 | 2024-05-24 | Enterprise        | L   | 0.707      | -            | -                | -                | -         |    -9.83 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            4 |     1822 | 2024-05-24 | MOUZ NXT          | L   | 0.706      | -            | -                | -                | -         |    -6.28 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            3 |     1882 | 2024-05-22 | Zero Tenacity     | L   | 0.693      | -            | -                | -                | -         |    -4.52 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            2 |     1915 | 2024-05-21 | NAVI Junior       | L   | 0.688      | -            | -                | -                | -         |   -18.89 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            1 |     1951 | 2024-05-20 | Sampi             | L   | 0.681      | -            | -                | -                | -         |   -10.85 | ANeraX, b1elany, Furlan, phr, ultimate   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,889.44)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.867 | $2,500.00      | $2,166.67       |
| 2024-06-16 |      0.861 | $2,000.00      | $1,722.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
