### Roster Details<br />
Team Name: Illuminar<br />
Roster: b1elany, Furlan, kadziu, Markoś, phr<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  925.7<br />
<br />
Final Rank Value (925.7) = Starting Rank Value (905.0) + Head To Head Adjustments (20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.0
- 400 + ( ( 0.246 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 905.0


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
|           26 |      114 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.94 | b1elany, Furlan, kadziu, Markoś, phr     |
|           25 |      204 | 2024-07-31 | Sampi             | W   | 1.000      | 0.143        | 0.027 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    15.23 | b1elany, Furlan, kadziu, Markoś, phr     |
|           24 |      502 | 2024-07-22 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -15.82 | b1elany, Furlan, kadziu, Markoś, phr     |
|           23 |      566 | 2024-07-20 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | 0 (0.000) |    26.13 | b1elany, Furlan, kadziu, Markoś, phr     |
|           22 |      663 | 2024-07-18 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.91 | b1elany, Furlan, kadziu, Markoś, phr     |
|           21 |      770 | 2024-07-16 | kONO              | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.566 (0.210)    | 0 (0.000) |    12.97 | b1elany, Furlan, kadziu, Markoś, phr     |
|           20 |      818 | 2024-07-15 | ALTERNATE aTTaX   | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.550 (0.204)    | 0 (0.000) |    14.77 | b1elany, Furlan, kadziu, Markoś, phr     |
|           19 |      877 | 2024-07-11 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -17.14 | b1elany, Furlan, kadziu, Markoś, splawik |
|           18 |     1069 | 2024-06-15 | B8                | L   | 0.856      | -            | -                | -                | -         |    -6.00 | b1elany, Furlan, kadziu, phr, ultimate   |
|           17 |     1130 | 2024-06-13 | GamerLegion       | W   | 0.844      | 0.435        | 0.173 (0.063)    | -                | 0 (0.000) |    21.89 | Furlan, kadziu, phr, splawik, ultimate   |
|           16 |     1141 | 2024-06-13 | Enterprise        | L   | 0.843      | -            | -                | -                | -         |   -11.47 | b1elany, Furlan, kadziu, phr, ultimate   |
|           15 |     1193 | 2024-06-11 | Sampi             | W   | 0.829      | 0.435        | 0.027 (0.010)    | 1.000 (0.360)    | 0 (0.000) |    12.47 | Furlan, kadziu, phr, splawik, ultimate   |
|           14 |     1283 | 2024-06-09 | VP.Prodigy        | W   | 0.815      | 0.435        | 0.025 (0.009)    | 0.393 (0.139)    | 0 (0.000) |    13.58 | b1elany, Furlan, kadziu, phr, ultimate   |
|           13 |     1319 | 2024-06-08 | 3DMAX             | W   | 0.811      | 0.450        | 0.509 (0.186)    | 1.000 (0.365)    | 0 (0.000) |    24.78 | b1elany, Furlan, kadziu, phr, ultimate   |
|           12 |     1389 | 2024-06-07 | EYEBALLERS        | W   | 0.803      | 0.450        | -                | 0.500 (0.181)    | 0 (0.000) |    14.36 | b1elany, Furlan, kadziu, phr, ultimate   |
|           11 |     1398 | 2024-06-07 | CYBERSHOKE        | W   | 0.802      | 0.435        | 0.039 (0.014)    | 0.346 (0.121)    | 0 (0.000) |    13.71 | b1elany, Furlan, kadziu, phr, ultimate   |
|           10 |     1441 | 2024-06-06 | Enterprise        | W   | 0.797      | 0.450        | 0.039 (0.014)    | 0.616 (0.221)    | -         |    15.65 | b1elany, Furlan, kadziu, phr, ultimate   |
|            9 |     1515 | 2024-06-05 | Aurora Young Blud | L   | 0.789      | -            | -                | -                | -         |   -10.82 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            8 |     1548 | 2024-06-04 | Passion UA        | L   | 0.784      | -            | -                | -                | -         |    -4.88 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            7 |     1702 | 2024-05-29 | INFINITE          | L   | 0.745      | -            | -                | -                | -         |   -19.62 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            6 |     1717 | 2024-05-29 | Passion UA        | L   | 0.742      | -            | -                | -                | -         |    -5.66 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            5 |     1813 | 2024-05-24 | Enterprise        | L   | 0.709      | -            | -                | -                | -         |    -9.87 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            4 |     1814 | 2024-05-24 | MOUZ NXT          | L   | 0.709      | -            | -                | -                | -         |    -6.30 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            3 |     1874 | 2024-05-22 | Zero Tenacity     | L   | 0.696      | -            | -                | -                | -         |    -4.62 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            2 |     1907 | 2024-05-21 | NAVI Junior       | L   | 0.691      | -            | -                | -                | -         |   -18.96 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            1 |     1943 | 2024-05-20 | Sampi             | L   | 0.684      | -            | -                | -                | -         |   -10.88 | ANeraX, b1elany, Furlan, phr, ultimate   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,901.94)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.869 | $2,500.00      | $2,173.61       |
| 2024-06-16 |      0.864 | $2,000.00      | $1,728.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
