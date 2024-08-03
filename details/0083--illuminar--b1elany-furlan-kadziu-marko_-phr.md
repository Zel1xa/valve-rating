### Roster Details<br />
Team Name: Illuminar<br />
Roster: b1elany, Furlan, kadziu, Markoś, phr<br />
Global Rank: [83](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [61]( ../standings_europe.md)<br />
<br />
Final Rank Value:  924.4<br />
<br />
Final Rank Value (924.4) = Starting Rank Value (905.9) + Head To Head Adjustments (18.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.412[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.247<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.9
- 400 + ( ( 0.247 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 905.9


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
|           26 |       45 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.93 | b1elany, Furlan, kadziu, Markoś, phr     |
|           25 |      117 | 2024-07-31 | Sampi             | W   | 1.000      | 0.143        | 0.028 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    15.13 | b1elany, Furlan, kadziu, Markoś, phr     |
|           24 |      416 | 2024-07-22 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -15.91 | b1elany, Furlan, kadziu, Markoś, phr     |
|           23 |      480 | 2024-07-20 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.930 (0.345)    | 0 (0.000) |    25.97 | b1elany, Furlan, kadziu, Markoś, phr     |
|           22 |      577 | 2024-07-18 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.63 | b1elany, Furlan, kadziu, Markoś, phr     |
|           21 |      681 | 2024-07-16 | kONO              | W   | 1.000      | 0.371        | 0.028 (0.011)    | 0.555 (0.206)    | 0 (0.000) |    12.98 | b1elany, Furlan, kadziu, Markoś, phr     |
|           20 |      729 | 2024-07-15 | ALTERNATE aTTaX   | W   | 1.000      | 0.371        | 0.032 (0.012)    | 0.580 (0.215)    | 0 (0.000) |    14.54 | b1elany, Furlan, kadziu, Markoś, phr     |
|           19 |      783 | 2024-07-11 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -17.09 | b1elany, Furlan, kadziu, Markoś, splawik |
|           18 |      962 | 2024-06-15 | B8                | L   | 0.872      | -            | -                | -                | -         |    -6.16 | b1elany, Furlan, kadziu, phr, ultimate   |
|           17 |     1016 | 2024-06-13 | GamerLegion       | W   | 0.860      | 0.435        | 0.174 (0.065)    | -                | 0 (0.000) |    22.29 | Furlan, kadziu, phr, splawik, ultimate   |
|           16 |     1027 | 2024-06-13 | Enterprise        | L   | 0.859      | -            | -                | -                | -         |   -11.74 | b1elany, Furlan, kadziu, phr, ultimate   |
|           15 |     1075 | 2024-06-11 | Sampi             | W   | 0.844      | 0.435        | 0.028 (0.010)    | 1.000 (0.367)    | 0 (0.000) |    12.76 | Furlan, kadziu, phr, splawik, ultimate   |
|           14 |     1164 | 2024-06-09 | VP.Prodigy        | W   | 0.831      | 0.435        | 0.026 (0.009)    | 0.416 (0.150)    | 0 (0.000) |    13.87 | b1elany, Furlan, kadziu, phr, ultimate   |
|           13 |     1197 | 2024-06-08 | 3DMAX             | W   | 0.826      | 0.450        | 0.504 (0.188)    | 1.000 (0.372)    | 0 (0.000) |    25.19 | b1elany, Furlan, kadziu, phr, ultimate   |
|           12 |     1265 | 2024-06-07 | EYEBALLERS        | W   | 0.819      | 0.450        | -                | 0.528 (0.195)    | 0 (0.000) |    14.78 | b1elany, Furlan, kadziu, phr, ultimate   |
|           11 |     1274 | 2024-06-07 | CYBERSHOKE        | W   | 0.818      | 0.435        | 0.039 (0.014)    | 0.327 (0.116)    | 0 (0.000) |    14.22 | b1elany, Furlan, kadziu, phr, ultimate   |
|           10 |     1317 | 2024-06-06 | Enterprise        | W   | 0.813      | 0.450        | 0.039 (0.014)    | 0.646 (0.236)    | -         |    15.95 | b1elany, Furlan, kadziu, phr, ultimate   |
|            9 |     1391 | 2024-06-05 | Aurora Young Blud | L   | 0.805      | -            | -                | -                | -         |   -12.47 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            8 |     1423 | 2024-06-04 | Passion UA        | L   | 0.799      | -            | -                | -                | -         |    -5.18 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            7 |     1575 | 2024-05-29 | INFINITE          | L   | 0.761      | -            | -                | -                | -         |   -20.01 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            6 |     1590 | 2024-05-29 | Passion UA        | L   | 0.758      | -            | -                | -                | -         |    -6.08 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            5 |     1685 | 2024-05-24 | Enterprise        | L   | 0.725      | -            | -                | -                | -         |   -10.13 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            4 |     1686 | 2024-05-24 | MOUZ NXT          | L   | 0.724      | -            | -                | -                | -         |    -6.64 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            3 |     1746 | 2024-05-22 | Zero Tenacity     | L   | 0.711      | -            | -                | -                | -         |    -4.72 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            2 |     1779 | 2024-05-21 | NAVI Junior       | L   | 0.706      | -            | -                | -                | -         |   -19.38 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            1 |     1815 | 2024-05-20 | Sampi             | L   | 0.699      | -            | -                | -                | -         |   -11.10 | ANeraX, b1elany, Furlan, phr, ultimate   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,972.15)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.885 | $2,500.00      | $2,212.62       |
| 2024-06-16 |      0.880 | $2,000.00      | $1,759.54       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
