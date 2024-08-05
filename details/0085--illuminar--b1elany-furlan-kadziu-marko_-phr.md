### Roster Details<br />
Team Name: Illuminar<br />
Roster: b1elany, Furlan, kadziu, Markoś, phr<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  925.9<br />
<br />
Final Rank Value (925.9) = Starting Rank Value (905.1) + Head To Head Adjustments (20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.1
- 400 + ( ( 0.246 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 905.1


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
|           26 |      112 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.93 | b1elany, Furlan, kadziu, Markoś, phr     |
|           25 |      202 | 2024-07-31 | Sampi             | W   | 1.000      | 0.143        | 0.027 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    15.23 | b1elany, Furlan, kadziu, Markoś, phr     |
|           24 |      500 | 2024-07-22 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -15.81 | b1elany, Furlan, kadziu, Markoś, phr     |
|           23 |      564 | 2024-07-20 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | 0 (0.000) |    26.13 | b1elany, Furlan, kadziu, Markoś, phr     |
|           22 |      661 | 2024-07-18 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.91 | b1elany, Furlan, kadziu, Markoś, phr     |
|           21 |      768 | 2024-07-16 | kONO              | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.566 (0.210)    | 0 (0.000) |    12.97 | b1elany, Furlan, kadziu, Markoś, phr     |
|           20 |      816 | 2024-07-15 | ALTERNATE aTTaX   | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.550 (0.204)    | 0 (0.000) |    14.77 | b1elany, Furlan, kadziu, Markoś, phr     |
|           19 |      875 | 2024-07-11 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -17.14 | b1elany, Furlan, kadziu, Markoś, splawik |
|           18 |     1067 | 2024-06-15 | B8                | L   | 0.858      | -            | -                | -                | -         |    -6.01 | b1elany, Furlan, kadziu, phr, ultimate   |
|           17 |     1128 | 2024-06-13 | GamerLegion       | W   | 0.846      | 0.435        | 0.173 (0.064)    | -                | 0 (0.000) |    21.95 | Furlan, kadziu, phr, splawik, ultimate   |
|           16 |     1139 | 2024-06-13 | Enterprise        | L   | 0.845      | -            | -                | -                | -         |   -11.49 | b1elany, Furlan, kadziu, phr, ultimate   |
|           15 |     1191 | 2024-06-11 | Sampi             | W   | 0.831      | 0.435        | 0.027 (0.010)    | 1.000 (0.361)    | 0 (0.000) |    12.51 | Furlan, kadziu, phr, splawik, ultimate   |
|           14 |     1281 | 2024-06-09 | VP.Prodigy        | W   | 0.817      | 0.435        | 0.025 (0.009)    | 0.393 (0.140)    | 0 (0.000) |    13.62 | b1elany, Furlan, kadziu, phr, ultimate   |
|           13 |     1317 | 2024-06-08 | 3DMAX             | W   | 0.812      | 0.450        | 0.508 (0.186)    | 1.000 (0.366)    | 0 (0.000) |    24.83 | b1elany, Furlan, kadziu, phr, ultimate   |
|           12 |     1387 | 2024-06-07 | EYEBALLERS        | W   | 0.805      | 0.450        | -                | 0.500 (0.181)    | 0 (0.000) |    14.40 | b1elany, Furlan, kadziu, phr, ultimate   |
|           11 |     1396 | 2024-06-07 | CYBERSHOKE        | W   | 0.804      | 0.435        | 0.039 (0.014)    | 0.346 (0.121)    | 0 (0.000) |    13.74 | b1elany, Furlan, kadziu, phr, ultimate   |
|           10 |     1439 | 2024-06-06 | Enterprise        | W   | 0.799      | 0.450        | 0.039 (0.014)    | 0.616 (0.222)    | -         |    15.69 | b1elany, Furlan, kadziu, phr, ultimate   |
|            9 |     1513 | 2024-06-05 | Aurora Young Blud | L   | 0.791      | -            | -                | -                | -         |   -10.84 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            8 |     1546 | 2024-06-04 | Passion UA        | L   | 0.786      | -            | -                | -                | -         |    -4.88 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            7 |     1700 | 2024-05-29 | INFINITE          | L   | 0.747      | -            | -                | -                | -         |   -19.67 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            6 |     1715 | 2024-05-29 | Passion UA        | L   | 0.744      | -            | -                | -                | -         |    -5.67 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            5 |     1811 | 2024-05-24 | Enterprise        | L   | 0.711      | -            | -                | -                | -         |    -9.89 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            4 |     1812 | 2024-05-24 | MOUZ NXT          | L   | 0.711      | -            | -                | -                | -         |    -6.31 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            3 |     1872 | 2024-05-22 | Zero Tenacity     | L   | 0.697      | -            | -                | -                | -         |    -4.63 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            2 |     1905 | 2024-05-21 | NAVI Junior       | L   | 0.692      | -            | -                | -                | -         |   -19.01 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            1 |     1941 | 2024-05-20 | Sampi             | L   | 0.686      | -            | -                | -                | -         |   -10.90 | ANeraX, b1elany, Furlan, phr, ultimate   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,910.07)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.871 | $2,500.00      | $2,178.13       |
| 2024-06-16 |      0.866 | $2,000.00      | $1,731.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
