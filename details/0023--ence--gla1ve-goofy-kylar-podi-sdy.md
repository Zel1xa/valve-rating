### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1351.3<br />
<br />
Final Rank Value (1351.3) = Starting Rank Value (1468.2) + Head To Head Adjustments (-116.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.564[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.257[<sup>2</sup>](#table1)
- LAN Wins: 0.805[<sup>2</sup>](#table1)

The average of these factors is 0.522<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1468.2
- 400 + ( ( 0.522 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1468.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |      299 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.36 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      326 | 2024-07-26 | True Rippers       | W   | 1.000      | 0.650        | -                | 0.170 (0.111)    | 1 (1.000) |     0.83 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      366 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.534 (0.347)    | 1 (1.000) |     5.59 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      376 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.19 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      393 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      406 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.517 (0.336)    | 1 (1.000) |    12.94 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |     1006 | 2024-06-16 | Falcons            | L   | 0.872      | -            | -                | -                | -         |   -11.10 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1070 | 2024-06-14 | Complexity         | W   | 0.860      | 0.500        | 0.342 (0.147)    | 0.380 (0.163)    | 1 (0.860) |    21.66 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1079 | 2024-06-14 | MIBR               | W   | 0.859      | 0.500        | 0.209 (0.090)    | 0.659 (0.283)    | 1 (0.859) |    15.98 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1412 | 2024-06-06 | HEROIC             | L   | 0.806      | -            | -                | -                | -         |    -5.78 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1423 | 2024-06-06 | Astralis           | L   | 0.806      | -            | -                | -                | -         |    -2.94 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1459 | 2024-06-05 | Sashi              | W   | 0.801      | 0.715        | 0.184 (0.105)    | 0.962 (0.551)    | 1 (0.801) |     8.22 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1472 | 2024-06-05 | The MongolZ        | L   | 0.800      | -            | -                | -                | -         |    -1.05 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1481 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.799      | -            | -                | -                | -         |    -5.90 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1588 | 2024-06-01 | DMS                | L   | 0.774      | -            | -                | -                | -         |   -21.97 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1597 | 2024-06-01 | KOI                | W   | 0.773      | -            | -                | -                | -         |     3.48 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1607 | 2024-06-01 | DMS                | L   | 0.772      | -            | -                | -                | -         |   -22.30 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1886 | 2024-05-21 | Liquid             | L   | 0.698      | -            | -                | -                | -         |    -5.36 | dycha, gla1ve, Goofy, hades, Kylar |
|           27 |     1972 | 2024-05-18 | fnatic             | W   | 0.679      | 0.769        | 0.371 (0.193)    | 0.708 (0.370)    | -         |    13.35 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     1995 | 2024-05-17 | Gaimin Gladiators  | W   | 0.674      | 0.769        | 0.038 (0.020)    | 0.350 (0.182)    | -         |     2.28 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     2006 | 2024-05-17 | fnatic             | L   | 0.672      | -            | -                | -                | -         |    -7.42 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2364 | 2024-05-04 | FURIA              | L   | 0.586      | -            | -                | -                | -         |    -3.71 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2378 | 2024-05-03 | GamerLegion        | L   | 0.579      | -            | -                | -                | -         |   -14.81 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2398 | 2024-05-02 | Monte              | W   | 0.574      | 0.889        | 0.057 (0.029)    | -                | 1 (0.574) |     1.74 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2426 | 2024-05-01 | Bad News Kangaroos | W   | 0.566      | 0.889        | 0.017 (0.008)    | 0.226 (0.114)    | 1 (0.566) |     0.60 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2457 | 2024-04-30 | GamerLegion        | L   | 0.559      | -            | -                | -                | -         |   -14.73 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2718 | 2024-04-19 | AMKAL              | L   | 0.486      | -            | -                | -                | -         |   -12.77 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2805 | 2024-04-17 | Enterprise         | W   | 0.472      | 0.384        | 0.039 (0.007)    | 0.625 (0.113)    | -         |     0.82 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2976 | 2024-04-10 | OG                 | L   | 0.426      | -            | -                | -                | -         |   -12.30 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3061 | 2024-04-08 | FORZE              | L   | 0.413      | -            | -                | -                | -         |   -12.35 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3169 | 2024-04-04 | Aurora Young Blud  | W   | 0.386      | -            | -                | -                | -         |     0.38 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3463 | 2024-03-19 | FURIA              | L   | 0.280      | -            | -                | -                | -         |    -1.70 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3479 | 2024-03-18 | paiN               | L   | 0.272      | -            | -                | -                | -         |    -4.85 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3486 | 2024-03-17 | KOI                | W   | 0.268      | -            | -                | -                | 1 (0.268) |     0.93 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3506 | 2024-03-17 | Imperial           | L   | 0.266      | -            | -                | -                | -         |    -6.27 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3637 | 2024-03-12 | B8                 | L   | 0.233      | -            | -                | -                | -         |    -6.54 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3650 | 2024-03-11 | HEROIC             | L   | 0.227      | -            | -                | -                | -         |    -2.70 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3660 | 2024-03-11 | Metizport          | W   | 0.226      | -            | -                | -                | -         |     0.21 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     4062 | 2024-02-22 | Astralis           | W   | 0.105      | -            | -                | -                | 1 (0.105) |     2.69 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4084 | 2024-02-21 | Vitality           | L   | 0.100      | -            | -                | -                | -         |    -0.33 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4117 | 2024-02-20 | GamerLegion        | W   | 0.092      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4137 | 2024-02-19 | ex-Guild Eagles    | W   | 0.087      | -            | -                | -                | -         |     0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4145 | 2024-02-19 | Spirit             | L   | 0.085      | -            | -                | -                | -         |    -0.21 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4350 | 2024-02-09 | Falcons            | L   | 0.021      | -            | -                | -                | -         |    -0.37 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4384 | 2024-02-06 | MOUZ               | L   | 0.001      | -            | -                | -                | -         |    -0.00 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,710.98)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.873 | $10,000.00     | $8,726.62       |
| 2024-06-09 |      0.826 | $8,000.00      | $6,610.19       |
| 2024-05-23 |      0.713 | $12,500.00     | $8,906.54       |
| 2024-05-12 |      0.640 | $7,000.00      | $4,477.25       |
| 2024-04-14 |      0.453 | $15,000.00     | $6,792.01       |
| 2024-03-20 |      0.287 | $10,000.00     | $2,869.68       |
| 2024-02-11 |      0.033 | $40,000.00     | $1,328.70       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
