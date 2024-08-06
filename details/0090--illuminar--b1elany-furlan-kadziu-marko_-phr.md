### Roster Details<br />
Team Name: Illuminar<br />
Roster: b1elany, Furlan, kadziu, Markoś, phr<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  911.8<br />
<br />
Final Rank Value (911.8) = Starting Rank Value (906.1) + Head To Head Adjustments (5.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.410[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 906.1
- 400 + ( ( 0.246 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 906.1


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
|           27 |       22 | 2024-08-06 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -18.70 | b1elany, Furlan, kadziu, Markoś, phr     |
|           26 |      137 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.85 | b1elany, Furlan, kadziu, Markoś, phr     |
|           25 |      227 | 2024-07-31 | Sampi             | W   | 1.000      | 0.143        | 0.027 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    15.44 | b1elany, Furlan, kadziu, Markoś, phr     |
|           24 |      525 | 2024-07-22 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -15.90 | b1elany, Furlan, kadziu, Markoś, phr     |
|           23 |      589 | 2024-07-20 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | 0 (0.000) |    26.10 | b1elany, Furlan, kadziu, Markoś, phr     |
|           22 |      686 | 2024-07-18 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.97 | b1elany, Furlan, kadziu, Markoś, phr     |
|           21 |      793 | 2024-07-16 | kONO              | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.553 (0.205)    | 0 (0.000) |    12.93 | b1elany, Furlan, kadziu, Markoś, phr     |
|           20 |      841 | 2024-07-15 | ALTERNATE aTTaX   | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.537 (0.199)    | 0 (0.000) |    14.74 | b1elany, Furlan, kadziu, Markoś, phr     |
|           19 |      900 | 2024-07-11 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -17.19 | b1elany, Furlan, kadziu, Markoś, splawik |
|           18 |     1092 | 2024-06-15 | B8                | L   | 0.852      | -            | -                | -                | -         |    -6.00 | b1elany, Furlan, kadziu, phr, ultimate   |
|           17 |     1153 | 2024-06-13 | GamerLegion       | W   | 0.840      | 0.435        | 0.173 (0.063)    | -                | 0 (0.000) |    21.66 | Furlan, kadziu, phr, splawik, ultimate   |
|           16 |     1164 | 2024-06-13 | Enterprise        | L   | 0.839      | -            | -                | -                | -         |   -11.50 | b1elany, Furlan, kadziu, phr, ultimate   |
|           15 |     1216 | 2024-06-11 | Sampi             | W   | 0.824      | 0.435        | 0.027 (0.010)    | 1.000 (0.358)    | 0 (0.000) |    12.45 | Furlan, kadziu, phr, splawik, ultimate   |
|           14 |     1306 | 2024-06-09 | VP.Prodigy        | W   | 0.811      | 0.435        | 0.025 (0.009)    | 0.383 (0.135)    | 0 (0.000) |    13.41 | b1elany, Furlan, kadziu, phr, ultimate   |
|           13 |     1342 | 2024-06-08 | 3DMAX             | W   | 0.806      | 0.450        | 0.510 (0.185)    | 1.000 (0.363)    | 0 (0.000) |    24.64 | b1elany, Furlan, kadziu, phr, ultimate   |
|           12 |     1412 | 2024-06-07 | EYEBALLERS        | W   | 0.799      | 0.450        | -                | 0.488 (0.175)    | 0 (0.000) |    14.30 | b1elany, Furlan, kadziu, phr, ultimate   |
|           11 |     1421 | 2024-06-07 | CYBERSHOKE        | W   | 0.798      | 0.435        | 0.039 (0.014)    | 0.378 (0.131)    | 0 (0.000) |    13.47 | b1elany, Furlan, kadziu, phr, ultimate   |
|           10 |     1464 | 2024-06-06 | Enterprise        | W   | 0.793      | 0.450        | 0.039 (0.014)    | 0.641 (0.229)    | -         |    15.46 | b1elany, Furlan, kadziu, phr, ultimate   |
|            9 |     1538 | 2024-06-05 | Aurora Young Blud | L   | 0.785      | -            | -                | -                | -         |    -9.75 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            8 |     1571 | 2024-06-04 | Passion UA        | L   | 0.779      | -            | -                | -                | -         |    -4.87 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            7 |     1725 | 2024-05-29 | INFINITE          | L   | 0.741      | -            | -                | -                | -         |   -19.55 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            6 |     1740 | 2024-05-29 | Passion UA        | L   | 0.738      | -            | -                | -                | -         |    -5.65 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            5 |     1836 | 2024-05-24 | Enterprise        | L   | 0.705      | -            | -                | -                | -         |    -9.89 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            4 |     1837 | 2024-05-24 | MOUZ NXT          | L   | 0.705      | -            | -                | -                | -         |    -6.30 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            3 |     1897 | 2024-05-22 | Zero Tenacity     | L   | 0.691      | -            | -                | -                | -         |    -4.52 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            2 |     1930 | 2024-05-21 | NAVI Junior       | L   | 0.686      | -            | -                | -                | -         |   -15.52 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            1 |     1966 | 2024-05-20 | Sampi             | L   | 0.680      | -            | -                | -                | -         |   -10.78 | ANeraX, b1elany, Furlan, phr, ultimate   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,882.57)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.865 | $2,500.00      | $2,162.85       |
| 2024-06-16 |      0.860 | $2,000.00      | $1,719.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
