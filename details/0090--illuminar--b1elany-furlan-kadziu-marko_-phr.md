### Roster Details<br />
Team Name: Illuminar<br />
Roster: b1elany, Furlan, kadziu, Markoś, phr<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  911.0<br />
<br />
Final Rank Value (911.0) = Starting Rank Value (905.4) + Head To Head Adjustments (5.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.410[<sup>2</sup>](#table1)
- Opponent Network: 0.229[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.4
- 400 + ( ( 0.246 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 905.4


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
|           27 |       18 | 2024-08-06 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -18.67 | b1elany, Furlan, kadziu, Markoś, phr     |
|           26 |      133 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.93 | b1elany, Furlan, kadziu, Markoś, phr     |
|           25 |      223 | 2024-07-31 | Sampi             | W   | 1.000      | 0.143        | 0.027 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    15.44 | b1elany, Furlan, kadziu, Markoś, phr     |
|           24 |      521 | 2024-07-22 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -15.89 | b1elany, Furlan, kadziu, Markoś, phr     |
|           23 |      585 | 2024-07-20 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | 0 (0.000) |    26.11 | b1elany, Furlan, kadziu, Markoś, phr     |
|           22 |      682 | 2024-07-18 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.00 | b1elany, Furlan, kadziu, Markoś, phr     |
|           21 |      789 | 2024-07-16 | kONO              | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.553 (0.205)    | 0 (0.000) |    12.94 | b1elany, Furlan, kadziu, Markoś, phr     |
|           20 |      837 | 2024-07-15 | ALTERNATE aTTaX   | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.537 (0.199)    | 0 (0.000) |    14.71 | b1elany, Furlan, kadziu, Markoś, phr     |
|           19 |      896 | 2024-07-11 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -17.17 | b1elany, Furlan, kadziu, Markoś, splawik |
|           18 |     1088 | 2024-06-15 | B8                | L   | 0.852      | -            | -                | -                | -         |    -6.03 | b1elany, Furlan, kadziu, phr, ultimate   |
|           17 |     1149 | 2024-06-13 | GamerLegion       | W   | 0.840      | 0.435        | 0.173 (0.063)    | -                | 0 (0.000) |    21.67 | Furlan, kadziu, phr, splawik, ultimate   |
|           16 |     1160 | 2024-06-13 | Enterprise        | L   | 0.839      | -            | -                | -                | -         |   -11.50 | b1elany, Furlan, kadziu, phr, ultimate   |
|           15 |     1212 | 2024-06-11 | Sampi             | W   | 0.825      | 0.435        | 0.027 (0.010)    | 1.000 (0.358)    | 0 (0.000) |    12.45 | Furlan, kadziu, phr, splawik, ultimate   |
|           14 |     1302 | 2024-06-09 | VP.Prodigy        | W   | 0.811      | 0.435        | 0.025 (0.009)    | 0.383 (0.135)    | 0 (0.000) |    13.41 | b1elany, Furlan, kadziu, phr, ultimate   |
|           13 |     1338 | 2024-06-08 | 3DMAX             | W   | 0.806      | 0.450        | 0.510 (0.185)    | 1.000 (0.363)    | 0 (0.000) |    24.64 | b1elany, Furlan, kadziu, phr, ultimate   |
|           12 |     1408 | 2024-06-07 | EYEBALLERS        | W   | 0.799      | 0.450        | -                | 0.488 (0.175)    | 0 (0.000) |    14.31 | b1elany, Furlan, kadziu, phr, ultimate   |
|           11 |     1417 | 2024-06-07 | CYBERSHOKE        | W   | 0.798      | 0.435        | 0.039 (0.014)    | 0.339 (0.118)    | 0 (0.000) |    13.49 | b1elany, Furlan, kadziu, phr, ultimate   |
|           10 |     1460 | 2024-06-06 | Enterprise        | W   | 0.793      | 0.450        | 0.039 (0.014)    | 0.641 (0.229)    | -         |    15.47 | b1elany, Furlan, kadziu, phr, ultimate   |
|            9 |     1534 | 2024-06-05 | Aurora Young Blud | L   | 0.785      | -            | -                | -                | -         |    -9.74 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            8 |     1567 | 2024-06-04 | Passion UA        | L   | 0.780      | -            | -                | -                | -         |    -4.88 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            7 |     1721 | 2024-05-29 | INFINITE          | L   | 0.741      | -            | -                | -                | -         |   -19.54 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            6 |     1736 | 2024-05-29 | Passion UA        | L   | 0.738      | -            | -                | -                | -         |    -5.66 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            5 |     1832 | 2024-05-24 | Enterprise        | L   | 0.705      | -            | -                | -                | -         |    -9.87 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            4 |     1833 | 2024-05-24 | MOUZ NXT          | L   | 0.705      | -            | -                | -                | -         |    -6.33 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            3 |     1893 | 2024-05-22 | Zero Tenacity     | L   | 0.691      | -            | -                | -                | -         |    -4.56 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            2 |     1926 | 2024-05-21 | NAVI Junior       | L   | 0.686      | -            | -                | -                | -         |   -15.50 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            1 |     1962 | 2024-05-20 | Sampi             | L   | 0.680      | -            | -                | -                | -         |   -10.79 | ANeraX, b1elany, Furlan, phr, ultimate   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,883.19)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.865 | $2,500.00      | $2,163.19       |
| 2024-06-16 |      0.860 | $2,000.00      | $1,720.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
