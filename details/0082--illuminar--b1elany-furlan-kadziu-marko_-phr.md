### Roster Details<br />
Team Name: Illuminar<br />
Roster: b1elany, Furlan, kadziu, Markoś, phr<br />
Global Rank: [82](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [61]( ../standings_europe.md)<br />
<br />
Final Rank Value:  922.4<br />
<br />
Final Rank Value (922.4) = Starting Rank Value (903.1) + Head To Head Adjustments (19.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 903.1
- 400 + ( ( 0.246 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 903.1


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
|           26 |       56 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.91 | b1elany, Furlan, kadziu, Markoś, phr     |
|           25 |      142 | 2024-07-31 | Sampi             | W   | 1.000      | 0.143        | 0.027 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    15.23 | b1elany, Furlan, kadziu, Markoś, phr     |
|           24 |      442 | 2024-07-22 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -15.86 | b1elany, Furlan, kadziu, Markoś, phr     |
|           23 |      506 | 2024-07-20 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.901 (0.334)    | 0 (0.000) |    26.05 | b1elany, Furlan, kadziu, Markoś, phr     |
|           22 |      603 | 2024-07-18 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.83 | b1elany, Furlan, kadziu, Markoś, phr     |
|           21 |      710 | 2024-07-16 | kONO              | W   | 1.000      | 0.371        | 0.028 (0.011)    | 0.536 (0.199)    | 0 (0.000) |    13.11 | b1elany, Furlan, kadziu, Markoś, phr     |
|           20 |      758 | 2024-07-15 | ALTERNATE aTTaX   | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.560 (0.208)    | 0 (0.000) |    14.62 | b1elany, Furlan, kadziu, Markoś, phr     |
|           19 |      817 | 2024-07-11 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -16.99 | b1elany, Furlan, kadziu, Markoś, splawik |
|           18 |     1009 | 2024-06-15 | B8                | L   | 0.867      | -            | -                | -                | -         |    -6.04 | b1elany, Furlan, kadziu, phr, ultimate   |
|           17 |     1070 | 2024-06-13 | GamerLegion       | W   | 0.855      | 0.435        | 0.174 (0.065)    | -                | 0 (0.000) |    22.27 | Furlan, kadziu, phr, splawik, ultimate   |
|           16 |     1081 | 2024-06-13 | Enterprise        | L   | 0.854      | -            | -                | -                | -         |   -11.66 | b1elany, Furlan, kadziu, phr, ultimate   |
|           15 |     1133 | 2024-06-11 | Sampi             | W   | 0.840      | 0.435        | 0.027 (0.010)    | 1.000 (0.365)    | 0 (0.000) |    12.47 | Furlan, kadziu, phr, splawik, ultimate   |
|           14 |     1223 | 2024-06-09 | VP.Prodigy        | W   | 0.826      | 0.435        | 0.026 (0.009)    | 0.401 (0.144)    | 0 (0.000) |    13.81 | b1elany, Furlan, kadziu, phr, ultimate   |
|           13 |     1259 | 2024-06-08 | 3DMAX             | W   | 0.821      | 0.450        | 0.506 (0.187)    | 1.000 (0.370)    | 0 (0.000) |    25.09 | b1elany, Furlan, kadziu, phr, ultimate   |
|           12 |     1329 | 2024-06-07 | EYEBALLERS        | W   | 0.814      | 0.450        | -                | 0.510 (0.187)    | 0 (0.000) |    14.75 | b1elany, Furlan, kadziu, phr, ultimate   |
|           11 |     1338 | 2024-06-07 | CYBERSHOKE        | W   | 0.813      | 0.435        | 0.039 (0.014)    | 0.351 (0.124)    | 0 (0.000) |    13.96 | b1elany, Furlan, kadziu, phr, ultimate   |
|           10 |     1381 | 2024-06-06 | Enterprise        | W   | 0.808      | 0.450        | 0.039 (0.014)    | 0.625 (0.227)    | -         |    15.86 | b1elany, Furlan, kadziu, phr, ultimate   |
|            9 |     1455 | 2024-06-05 | Aurora Young Blud | L   | 0.800      | -            | -                | -                | -         |   -12.40 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            8 |     1488 | 2024-06-04 | Passion UA        | L   | 0.795      | -            | -                | -                | -         |    -5.05 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            7 |     1642 | 2024-05-29 | INFINITE          | L   | 0.756      | -            | -                | -                | -         |   -19.86 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            6 |     1657 | 2024-05-29 | Passion UA        | L   | 0.753      | -            | -                | -                | -         |    -5.91 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            5 |     1753 | 2024-05-24 | Enterprise        | L   | 0.720      | -            | -                | -                | -         |   -10.05 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            4 |     1754 | 2024-05-24 | MOUZ NXT          | L   | 0.720      | -            | -                | -                | -         |    -6.50 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            3 |     1814 | 2024-05-22 | Zero Tenacity     | L   | 0.706      | -            | -                | -                | -         |    -4.61 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            2 |     1847 | 2024-05-21 | NAVI Junior       | L   | 0.701      | -            | -                | -                | -         |   -19.22 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            1 |     1883 | 2024-05-20 | Sampi             | L   | 0.695      | -            | -                | -                | -         |   -11.02 | ANeraX, b1elany, Furlan, phr, ultimate   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,950.69)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.880 | $2,500.00      | $2,200.69       |
| 2024-06-16 |      0.875 | $2,000.00      | $1,750.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
