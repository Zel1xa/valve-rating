### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1350.3<br />
<br />
Final Rank Value (1350.3) = Starting Rank Value (1467.5) + Head To Head Adjustments (-117.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.564[<sup>1</sup>](#table2)
- Bounty Collected: 0.461[<sup>2</sup>](#table1)
- Opponent Network: 0.257[<sup>2</sup>](#table1)
- LAN Wins: 0.805[<sup>2</sup>](#table1)

The average of these factors is 0.522<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1467.5
- 400 + ( ( 0.522 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1467.5


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
|           45 |      275 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.37 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      302 | 2024-07-26 | True Rippers       | W   | 1.000      | 0.650        | -                | 0.171 (0.111)    | 1 (1.000) |     0.83 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      342 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.534 (0.347)    | 1 (1.000) |     5.55 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      352 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.21 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      369 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.78 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      382 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.517 (0.336)    | 1 (1.000) |    12.90 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      982 | 2024-06-16 | Falcons            | L   | 0.873      | -            | -                | -                | -         |   -11.06 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1046 | 2024-06-14 | Complexity         | W   | 0.861      | 0.500        | 0.310 (0.133)    | 0.380 (0.164)    | 1 (0.861) |    21.52 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1055 | 2024-06-14 | MIBR               | W   | 0.860      | 0.500        | 0.209 (0.090)    | 0.659 (0.283)    | 1 (0.860) |    16.04 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1388 | 2024-06-06 | HEROIC             | L   | 0.808      | -            | -                | -                | -         |    -5.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1399 | 2024-06-06 | Astralis           | L   | 0.807      | -            | -                | -                | -         |    -2.93 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1435 | 2024-06-05 | Sashi              | W   | 0.802      | 0.715        | 0.184 (0.106)    | 0.962 (0.552)    | 1 (0.802) |     8.23 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1448 | 2024-06-05 | The MongolZ        | L   | 0.801      | -            | -                | -                | -         |    -1.05 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1457 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.800      | -            | -                | -                | -         |    -5.88 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1564 | 2024-06-01 | DMS                | L   | 0.775      | -            | -                | -                | -         |   -21.99 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1573 | 2024-06-01 | KOI                | W   | 0.774      | -            | -                | -                | -         |     3.49 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1583 | 2024-06-01 | DMS                | L   | 0.773      | -            | -                | -                | -         |   -22.33 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1862 | 2024-05-21 | Liquid             | L   | 0.699      | -            | -                | -                | -         |    -5.41 | dycha, gla1ve, Goofy, hades, Kylar |
|           27 |     1948 | 2024-05-18 | fnatic             | W   | 0.680      | 0.769        | 0.371 (0.194)    | 0.708 (0.370)    | -         |    13.37 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     1971 | 2024-05-17 | Gaimin Gladiators  | W   | 0.676      | 0.769        | 0.038 (0.020)    | 0.351 (0.182)    | -         |     2.27 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     1982 | 2024-05-17 | fnatic             | L   | 0.674      | -            | -                | -                | -         |    -7.43 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2340 | 2024-05-04 | FURIA              | L   | 0.587      | -            | -                | -                | -         |    -3.71 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2354 | 2024-05-03 | GamerLegion        | L   | 0.581      | -            | -                | -                | -         |   -14.82 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2374 | 2024-05-02 | Monte              | W   | 0.575      | 0.889        | 0.058 (0.029)    | -                | 1 (0.575) |     1.76 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2402 | 2024-05-01 | Bad News Kangaroos | W   | 0.567      | 0.889        | 0.017 (0.008)    | 0.226 (0.114)    | 1 (0.567) |     0.60 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2433 | 2024-04-30 | GamerLegion        | L   | 0.560      | -            | -                | -                | -         |   -14.75 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2694 | 2024-04-19 | AMKAL              | L   | 0.487      | -            | -                | -                | -         |   -12.79 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2781 | 2024-04-17 | Enterprise         | W   | 0.473      | 0.384        | 0.039 (0.007)    | 0.625 (0.114)    | -         |     0.83 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2952 | 2024-04-10 | OG                 | L   | 0.427      | -            | -                | -                | -         |   -12.32 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3037 | 2024-04-08 | FORZE              | L   | 0.414      | -            | -                | -                | -         |   -12.38 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3145 | 2024-04-04 | Aurora Young Blud  | W   | 0.387      | -            | -                | -                | -         |     0.39 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3439 | 2024-03-19 | FURIA              | L   | 0.281      | -            | -                | -                | -         |    -1.71 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3455 | 2024-03-18 | paiN               | L   | 0.273      | -            | -                | -                | -         |    -4.86 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3462 | 2024-03-17 | KOI                | W   | 0.269      | -            | -                | -                | 1 (0.269) |     0.94 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3482 | 2024-03-17 | Imperial           | L   | 0.267      | -            | -                | -                | -         |    -6.28 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3613 | 2024-03-12 | B8                 | L   | 0.234      | -            | -                | -                | -         |    -6.58 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3626 | 2024-03-11 | HEROIC             | L   | 0.228      | -            | -                | -                | -         |    -2.72 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3636 | 2024-03-11 | Metizport          | W   | 0.227      | -            | -                | -                | -         |     0.31 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     4038 | 2024-02-22 | Astralis           | W   | 0.106      | -            | -                | -                | 1 (0.106) |     2.72 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4060 | 2024-02-21 | Vitality           | L   | 0.101      | -            | -                | -                | -         |    -0.33 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4093 | 2024-02-20 | GamerLegion        | W   | 0.093      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4113 | 2024-02-19 | ex-Guild Eagles    | W   | 0.088      | -            | -                | -                | -         |     0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4121 | 2024-02-19 | Spirit             | L   | 0.086      | -            | -                | -                | -         |    -0.22 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4326 | 2024-02-09 | Falcons            | L   | 0.022      | -            | -                | -                | -         |    -0.39 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4360 | 2024-02-06 | MOUZ               | L   | 0.002      | -            | -                | -                | -         |    -0.01 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,820.13)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.874 | $10,000.00     | $8,737.27       |
| 2024-06-09 |      0.827 | $8,000.00      | $6,618.70       |
| 2024-05-23 |      0.714 | $12,500.00     | $8,919.85       |
| 2024-05-12 |      0.641 | $7,000.00      | $4,484.70       |
| 2024-04-14 |      0.454 | $15,000.00     | $6,807.99       |
| 2024-03-20 |      0.288 | $10,000.00     | $2,880.32       |
| 2024-02-11 |      0.034 | $40,000.00     | $1,371.30       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
