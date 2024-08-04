### Roster Details<br />
Team Name: Illuminar<br />
Roster: b1elany, Furlan, kadziu, Markoś, phr<br />
Global Rank: [84](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  923.1<br />
<br />
Final Rank Value (923.1) = Starting Rank Value (903.0) + Head To Head Adjustments (20.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 903.0
- 400 + ( ( 0.246 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 903.0


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
|           26 |       63 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.88 | b1elany, Furlan, kadziu, Markoś, phr     |
|           25 |      150 | 2024-07-31 | Sampi             | W   | 1.000      | 0.143        | 0.027 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    15.27 | b1elany, Furlan, kadziu, Markoś, phr     |
|           24 |      450 | 2024-07-22 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -15.87 | b1elany, Furlan, kadziu, Markoś, phr     |
|           23 |      514 | 2024-07-20 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.902 (0.334)    | 0 (0.000) |    26.04 | b1elany, Furlan, kadziu, Markoś, phr     |
|           22 |      611 | 2024-07-18 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.84 | b1elany, Furlan, kadziu, Markoś, phr     |
|           21 |      718 | 2024-07-16 | kONO              | W   | 1.000      | 0.371        | 0.028 (0.011)    | 0.536 (0.199)    | 0 (0.000) |    13.08 | b1elany, Furlan, kadziu, Markoś, phr     |
|           20 |      766 | 2024-07-15 | ALTERNATE aTTaX   | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.560 (0.208)    | 0 (0.000) |    14.61 | b1elany, Furlan, kadziu, Markoś, phr     |
|           19 |      825 | 2024-07-11 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -17.02 | b1elany, Furlan, kadziu, Markoś, splawik |
|           18 |     1017 | 2024-06-15 | B8                | L   | 0.866      | -            | -                | -                | -         |    -6.05 | b1elany, Furlan, kadziu, phr, ultimate   |
|           17 |     1078 | 2024-06-13 | GamerLegion       | W   | 0.855      | 0.435        | 0.174 (0.064)    | -                | 0 (0.000) |    22.24 | Furlan, kadziu, phr, splawik, ultimate   |
|           16 |     1089 | 2024-06-13 | Enterprise        | L   | 0.853      | -            | -                | -                | -         |   -11.66 | b1elany, Furlan, kadziu, phr, ultimate   |
|           15 |     1141 | 2024-06-11 | Sampi             | W   | 0.839      | 0.435        | 0.027 (0.010)    | 1.000 (0.365)    | 0 (0.000) |    12.48 | Furlan, kadziu, phr, splawik, ultimate   |
|           14 |     1231 | 2024-06-09 | VP.Prodigy        | W   | 0.826      | 0.435        | 0.025 (0.009)    | 0.401 (0.144)    | 0 (0.000) |    13.78 | b1elany, Furlan, kadziu, phr, ultimate   |
|           13 |     1267 | 2024-06-08 | 3DMAX             | W   | 0.821      | 0.450        | 0.506 (0.187)    | 1.000 (0.369)    | 0 (0.000) |    25.07 | b1elany, Furlan, kadziu, phr, ultimate   |
|           12 |     1337 | 2024-06-07 | EYEBALLERS        | W   | 0.813      | 0.450        | -                | 0.510 (0.186)    | 0 (0.000) |    14.72 | b1elany, Furlan, kadziu, phr, ultimate   |
|           11 |     1346 | 2024-06-07 | CYBERSHOKE        | W   | 0.812      | 0.435        | 0.039 (0.014)    | 0.351 (0.124)    | 0 (0.000) |    13.97 | b1elany, Furlan, kadziu, phr, ultimate   |
|           10 |     1389 | 2024-06-06 | Enterprise        | W   | 0.807      | 0.450        | 0.039 (0.014)    | 0.625 (0.227)    | -         |    15.82 | b1elany, Furlan, kadziu, phr, ultimate   |
|            9 |     1463 | 2024-06-05 | Aurora Young Blud | L   | 0.800      | -            | -                | -                | -         |   -11.70 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            8 |     1496 | 2024-06-04 | Passion UA        | L   | 0.794      | -            | -                | -                | -         |    -5.03 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            7 |     1650 | 2024-05-29 | INFINITE          | L   | 0.755      | -            | -                | -                | -         |   -19.84 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            6 |     1665 | 2024-05-29 | Passion UA        | L   | 0.752      | -            | -                | -                | -         |    -5.88 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            5 |     1761 | 2024-05-24 | Enterprise        | L   | 0.720      | -            | -                | -                | -         |   -10.04 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            4 |     1762 | 2024-05-24 | MOUZ NXT          | L   | 0.719      | -            | -                | -                | -         |    -6.47 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            3 |     1822 | 2024-05-22 | Zero Tenacity     | L   | 0.706      | -            | -                | -                | -         |    -4.59 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            2 |     1855 | 2024-05-21 | NAVI Junior       | L   | 0.701      | -            | -                | -                | -         |   -19.20 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            1 |     1891 | 2024-05-20 | Sampi             | L   | 0.694      | -            | -                | -                | -         |   -10.99 | ANeraX, b1elany, Furlan, phr, ultimate   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,947.47)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.880 | $2,500.00      | $2,198.90       |
| 2024-06-16 |      0.874 | $2,000.00      | $1,748.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
