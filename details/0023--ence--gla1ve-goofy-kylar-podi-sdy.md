### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1351.2<br />
<br />
Final Rank Value (1351.2) = Starting Rank Value (1468.3) + Head To Head Adjustments (-117.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.564[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.257[<sup>2</sup>](#table1)
- LAN Wins: 0.805[<sup>2</sup>](#table1)

The average of these factors is 0.522<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1468.3
- 400 + ( ( 0.522 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1468.3


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
|           45 |      298 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.36 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      325 | 2024-07-26 | True Rippers       | W   | 1.000      | 0.650        | -                | 0.170 (0.111)    | 1 (1.000) |     0.83 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      365 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.534 (0.347)    | 1 (1.000) |     5.58 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      375 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.21 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      392 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.80 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      405 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.517 (0.336)    | 1 (1.000) |    12.93 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |     1005 | 2024-06-16 | Falcons            | L   | 0.872      | -            | -                | -                | -         |   -11.10 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1069 | 2024-06-14 | Complexity         | W   | 0.860      | 0.500        | 0.342 (0.147)    | 0.380 (0.163)    | 1 (0.860) |    21.67 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1078 | 2024-06-14 | MIBR               | W   | 0.859      | 0.500        | 0.209 (0.090)    | 0.659 (0.283)    | 1 (0.859) |    15.99 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1411 | 2024-06-06 | HEROIC             | L   | 0.807      | -            | -                | -                | -         |    -5.78 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1422 | 2024-06-06 | Astralis           | L   | 0.806      | -            | -                | -                | -         |    -2.94 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1458 | 2024-06-05 | Sashi              | W   | 0.801      | 0.715        | 0.184 (0.105)    | 0.962 (0.551)    | 1 (0.801) |     8.23 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1471 | 2024-06-05 | The MongolZ        | L   | 0.800      | -            | -                | -                | -         |    -1.05 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1480 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.799      | -            | -                | -                | -         |    -5.90 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1587 | 2024-06-01 | DMS                | L   | 0.774      | -            | -                | -                | -         |   -21.98 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1596 | 2024-06-01 | KOI                | W   | 0.773      | -            | -                | -                | -         |     3.49 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1606 | 2024-06-01 | DMS                | L   | 0.772      | -            | -                | -                | -         |   -22.31 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1885 | 2024-05-21 | Liquid             | L   | 0.699      | -            | -                | -                | -         |    -5.36 | dycha, gla1ve, Goofy, hades, Kylar |
|           27 |     1971 | 2024-05-18 | fnatic             | W   | 0.679      | 0.769        | 0.371 (0.194)    | 0.708 (0.370)    | -         |    13.36 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     1994 | 2024-05-17 | Gaimin Gladiators  | W   | 0.675      | 0.769        | 0.038 (0.020)    | 0.351 (0.182)    | -         |     2.29 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     2005 | 2024-05-17 | fnatic             | L   | 0.673      | -            | -                | -                | -         |    -7.42 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2363 | 2024-05-04 | FURIA              | L   | 0.587      | -            | -                | -                | -         |    -3.71 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2377 | 2024-05-03 | GamerLegion        | L   | 0.580      | -            | -                | -                | -         |   -14.82 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2397 | 2024-05-02 | Monte              | W   | 0.574      | 0.889        | 0.058 (0.029)    | -                | 1 (0.574) |     1.74 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2425 | 2024-05-01 | Bad News Kangaroos | W   | 0.566      | 0.889        | 0.017 (0.008)    | 0.226 (0.114)    | 1 (0.566) |     0.60 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2456 | 2024-04-30 | GamerLegion        | L   | 0.559      | -            | -                | -                | -         |   -14.74 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2717 | 2024-04-19 | AMKAL              | L   | 0.486      | -            | -                | -                | -         |   -12.78 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2804 | 2024-04-17 | Enterprise         | W   | 0.473      | 0.384        | 0.039 (0.007)    | 0.625 (0.113)    | -         |     0.82 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2975 | 2024-04-10 | OG                 | L   | 0.426      | -            | -                | -                | -         |   -12.31 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3060 | 2024-04-08 | FORZE              | L   | 0.413      | -            | -                | -                | -         |   -12.36 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3168 | 2024-04-04 | Aurora Young Blud  | W   | 0.386      | -            | -                | -                | -         |     0.38 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3462 | 2024-03-19 | FURIA              | L   | 0.281      | -            | -                | -                | -         |    -1.70 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3478 | 2024-03-18 | paiN               | L   | 0.272      | -            | -                | -                | -         |    -4.86 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3485 | 2024-03-17 | KOI                | W   | 0.268      | -            | -                | -                | 1 (0.268) |     0.94 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3505 | 2024-03-17 | Imperial           | L   | 0.266      | -            | -                | -                | -         |    -6.27 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3636 | 2024-03-12 | B8                 | L   | 0.233      | -            | -                | -                | -         |    -6.55 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3649 | 2024-03-11 | HEROIC             | L   | 0.228      | -            | -                | -                | -         |    -2.71 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3659 | 2024-03-11 | Metizport          | W   | 0.226      | -            | -                | -                | -         |     0.21 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     4061 | 2024-02-22 | Astralis           | W   | 0.105      | -            | -                | -                | 1 (0.105) |     2.70 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4083 | 2024-02-21 | Vitality           | L   | 0.100      | -            | -                | -                | -         |    -0.33 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4116 | 2024-02-20 | GamerLegion        | W   | 0.092      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4136 | 2024-02-19 | ex-Guild Eagles    | W   | 0.087      | -            | -                | -                | -         |     0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4144 | 2024-02-19 | Spirit             | L   | 0.086      | -            | -                | -                | -         |    -0.21 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4349 | 2024-02-09 | Falcons            | L   | 0.021      | -            | -                | -                | -         |    -0.37 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4383 | 2024-02-06 | MOUZ               | L   | 0.001      | -            | -                | -                | -         |    -0.00 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,741.83)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.873 | $10,000.00     | $8,729.63       |
| 2024-06-09 |      0.827 | $8,000.00      | $6,612.59       |
| 2024-05-23 |      0.713 | $12,500.00     | $8,910.30       |
| 2024-05-12 |      0.640 | $7,000.00      | $4,479.35       |
| 2024-04-14 |      0.453 | $15,000.00     | $6,796.53       |
| 2024-03-20 |      0.287 | $10,000.00     | $2,872.69       |
| 2024-02-11 |      0.034 | $40,000.00     | $1,340.74       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
