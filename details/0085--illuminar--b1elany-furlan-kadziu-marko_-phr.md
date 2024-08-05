### Roster Details<br />
Team Name: Illuminar<br />
Roster: b1elany, Furlan, kadziu, Markoś, phr<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  924.2<br />
<br />
Final Rank Value (924.2) = Starting Rank Value (904.1) + Head To Head Adjustments (20.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 904.1
- 400 + ( ( 0.246 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 904.1


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
|           26 |      103 | 2024-08-02 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.92 | b1elany, Furlan, kadziu, Markoś, phr     |
|           25 |      193 | 2024-07-31 | Sampi             | W   | 1.000      | 0.143        | 0.027 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    15.23 | b1elany, Furlan, kadziu, Markoś, phr     |
|           24 |      491 | 2024-07-22 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -15.87 | b1elany, Furlan, kadziu, Markoś, phr     |
|           23 |      555 | 2024-07-20 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.940 (0.348)    | 0 (0.000) |    26.17 | b1elany, Furlan, kadziu, Markoś, phr     |
|           22 |      652 | 2024-07-18 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.86 | b1elany, Furlan, kadziu, Markoś, phr     |
|           21 |      759 | 2024-07-16 | kONO              | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.574 (0.213)    | 0 (0.000) |    13.03 | b1elany, Furlan, kadziu, Markoś, phr     |
|           20 |      807 | 2024-07-15 | ALTERNATE aTTaX   | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.557 (0.207)    | 0 (0.000) |    14.79 | b1elany, Furlan, kadziu, Markoś, phr     |
|           19 |      866 | 2024-07-11 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -17.08 | b1elany, Furlan, kadziu, Markoś, splawik |
|           18 |     1058 | 2024-06-15 | B8                | L   | 0.859      | -            | -                | -                | -         |    -5.99 | b1elany, Furlan, kadziu, phr, ultimate   |
|           17 |     1119 | 2024-06-13 | GamerLegion       | W   | 0.848      | 0.435        | 0.173 (0.064)    | -                | 0 (0.000) |    22.04 | Furlan, kadziu, phr, splawik, ultimate   |
|           16 |     1130 | 2024-06-13 | Enterprise        | L   | 0.846      | -            | -                | -                | -         |   -11.58 | b1elany, Furlan, kadziu, phr, ultimate   |
|           15 |     1182 | 2024-06-11 | Sampi             | W   | 0.832      | 0.435        | 0.027 (0.010)    | 1.000 (0.362)    | 0 (0.000) |    12.53 | Furlan, kadziu, phr, splawik, ultimate   |
|           14 |     1272 | 2024-06-09 | VP.Prodigy        | W   | 0.819      | 0.435        | 0.025 (0.009)    | 0.398 (0.142)    | 0 (0.000) |    13.67 | b1elany, Furlan, kadziu, phr, ultimate   |
|           13 |     1308 | 2024-06-08 | 3DMAX             | W   | 0.814      | 0.450        | 0.508 (0.186)    | 1.000 (0.366)    | 0 (0.000) |    24.88 | b1elany, Furlan, kadziu, phr, ultimate   |
|           12 |     1378 | 2024-06-07 | EYEBALLERS        | W   | 0.806      | 0.450        | -                | 0.507 (0.184)    | 0 (0.000) |    14.45 | b1elany, Furlan, kadziu, phr, ultimate   |
|           11 |     1387 | 2024-06-07 | CYBERSHOKE        | W   | 0.805      | 0.435        | 0.039 (0.014)    | 0.351 (0.123)    | 0 (0.000) |    13.84 | b1elany, Furlan, kadziu, phr, ultimate   |
|           10 |     1430 | 2024-06-06 | Enterprise        | W   | 0.801      | 0.450        | 0.039 (0.014)    | 0.624 (0.225)    | -         |    15.65 | b1elany, Furlan, kadziu, phr, ultimate   |
|            9 |     1504 | 2024-06-05 | Aurora Young Blud | L   | 0.793      | -            | -                | -                | -         |   -11.62 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            8 |     1537 | 2024-06-04 | Passion UA        | L   | 0.787      | -            | -                | -                | -         |    -4.94 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            7 |     1691 | 2024-05-29 | INFINITE          | L   | 0.748      | -            | -                | -                | -         |   -19.69 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            6 |     1706 | 2024-05-29 | Passion UA        | L   | 0.746      | -            | -                | -                | -         |    -5.75 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            5 |     1802 | 2024-05-24 | Enterprise        | L   | 0.713      | -            | -                | -                | -         |    -9.99 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            4 |     1803 | 2024-05-24 | MOUZ NXT          | L   | 0.712      | -            | -                | -                | -         |    -6.32 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            3 |     1863 | 2024-05-22 | Zero Tenacity     | L   | 0.699      | -            | -                | -                | -         |    -4.60 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            2 |     1896 | 2024-05-21 | NAVI Junior       | L   | 0.694      | -            | -                | -                | -         |   -19.04 | ANeraX, b1elany, Furlan, phr, ultimate   |
|            1 |     1932 | 2024-05-20 | Sampi             | L   | 0.687      | -            | -                | -                | -         |   -10.92 | ANeraX, b1elany, Furlan, phr, ultimate   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,916.94)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.873 | $2,500.00      | $2,181.94       |
| 2024-06-16 |      0.868 | $2,000.00      | $1,735.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
