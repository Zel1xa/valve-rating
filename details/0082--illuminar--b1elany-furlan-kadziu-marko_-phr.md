### Roster Details<br />
Team Name: Illuminar<br />
Roster: b1elany, Furlan, kadziu, Markoś, phr<br />
Global Rank: [82](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [61]( ../standings_europe.md)<br />
<br />
Final Rank Value:  922.7<br />
<br />
Final Rank Value (922.7) = Starting Rank Value (903.2) + Head To Head Adjustments (19.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 903.2
- 400 + ( ( 0.246 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 903.2


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
|           26 |       53 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.77 | b1elany, Furlan, kadziu, Markoś, phr     |
|           25 |      139 | 2024-07-31 | Sampi             | W   | 1.000      | 0.143        | 0.027 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    15.23 | b1elany, Furlan, kadziu, Markoś, phr     |
|           24 |      439 | 2024-07-22 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -15.85 | b1elany, Furlan, kadziu, Markoś, phr     |
|           23 |      503 | 2024-07-20 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.901 (0.334)    | 0 (0.000) |    26.05 | b1elany, Furlan, kadziu, Markoś, phr     |
|           22 |      600 | 2024-07-18 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.82 | b1elany, Furlan, kadziu, Markoś, phr     |
|           21 |      707 | 2024-07-16 | kONO              | W   | 1.000      | 0.371        | 0.028 (0.011)    | 0.536 (0.199)    | 0 (0.000) |    13.12 | b1elany, Furlan, kadziu, Markoś, phr     |
|           20 |      755 | 2024-07-15 | ALTERNATE aTTaX   | W   | 1.000      | 0.371        | 0.032 (0.012)    | 0.561 (0.208)    | 0 (0.000) |    14.61 | b1elany, Furlan, kadziu, Markoś, phr     |
|           19 |      813 | 2024-07-11 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -16.97 | b1elany, Furlan, kadziu, Markoś, splawik |
|           18 |     1005 | 2024-06-15 | B8                | L   | 0.870      | -            | -                | -                | -         |    -6.05 | b1elany, Furlan, kadziu, phr, ultimate   |
|           17 |     1066 | 2024-06-13 | GamerLegion       | W   | 0.858      | 0.435        | 0.174 (0.065)    | -                | 0 (0.000) |    22.37 | Furlan, kadziu, phr, splawik, ultimate   |
|           16 |     1077 | 2024-06-13 | Enterprise        | L   | 0.857      | -            | -                | -                | -         |   -11.68 | b1elany, Furlan, kadziu, phr, ultimate   |
|           15 |     1129 | 2024-06-11 | Sampi             | W   | 0.843      | 0.435        | 0.027 (0.010)    | 1.000 (0.366)    | 0 (0.000) |    12.52 | Furlan, kadziu, phr, splawik, ultimate   |
|           14 |     1219 | 2024-06-09 | VP.Prodigy        | W   | 0.829      | 0.435        | 0.026 (0.009)    | 0.402 (0.145)    | 0 (0.000) |    13.87 | b1elany, Furlan, kadziu, phr, ultimate   |
|           13 |     1255 | 2024-06-08 | 3DMAX             | W   | 0.824      | 0.450        | 0.505 (0.187)    | 1.000 (0.371)    | 0 (0.000) |    25.17 | b1elany, Furlan, kadziu, phr, ultimate   |
|           12 |     1325 | 2024-06-07 | EYEBALLERS        | W   | 0.817      | 0.450        | -                | 0.510 (0.188)    | 0 (0.000) |    14.82 | b1elany, Furlan, kadziu, phr, ultimate   |
|           11 |     1334 | 2024-06-07 | CYBERSHOKE        | W   | 0.816      | 0.435        | 0.039 (0.014)    | 0.350 (0.124)    | 0 (0.000) |    14.02 | b1elany, Furlan, kadziu, phr, ultimate   |
|           10 |     1377 | 2024-06-06 | Enterprise        | W   | 0.811      | 0.450        | 0.039 (0.014)    | 0.624 (0.228)    | -         |    15.94 | b1elany, Furlan, kadziu, phr, ultimate   |
|            9 |     1451 | 2024-06-05 | Aurora Young Blud | L   | 0.803      | -            | -                | -                | -         |   -12.43 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            8 |     1484 | 2024-06-04 | Passion UA        | L   | 0.798      | -            | -                | -                | -         |    -5.15 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            7 |     1638 | 2024-05-29 | INFINITE          | L   | 0.759      | -            | -                | -                | -         |   -19.93 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            6 |     1653 | 2024-05-29 | Passion UA        | L   | 0.756      | -            | -                | -                | -         |    -6.04 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            5 |     1749 | 2024-05-24 | Enterprise        | L   | 0.723      | -            | -                | -                | -         |   -10.08 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            4 |     1750 | 2024-05-24 | MOUZ NXT          | L   | 0.723      | -            | -                | -                | -         |    -6.51 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            3 |     1810 | 2024-05-22 | Zero Tenacity     | L   | 0.709      | -            | -                | -                | -         |    -4.62 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            2 |     1843 | 2024-05-21 | NAVI Junior       | L   | 0.704      | -            | -                | -                | -         |   -19.30 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            1 |     1879 | 2024-05-20 | Sampi             | L   | 0.698      | -            | -                | -                | -         |   -11.06 | ANeraX, b1elany, Furlan, phr, ultimate   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,964.44)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.883 | $2,500.00      | $2,208.33       |
| 2024-06-16 |      0.878 | $2,000.00      | $1,756.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
