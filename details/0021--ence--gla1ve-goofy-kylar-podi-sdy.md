### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1340.4<br />
<br />
Final Rank Value (1340.4) = Starting Rank Value (1480.8) + Head To Head Adjustments (-140.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.460[<sup>2</sup>](#table1)
- Opponent Network: 0.244[<sup>2</sup>](#table1)
- LAN Wins: 0.828[<sup>2</sup>](#table1)

The average of these factors is 0.525<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1480.8
- 400 + ( ( 0.525 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1480.8


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
|           47 |      179 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.12 | gla1ve, Goofy, Kylar, podi, sdy    |
|           46 |      206 | 2024-07-26 | True Rippers       | W   | 1.000      | 0.650        | -                | 0.172 (0.112)    | 1 (1.000) |     0.91 | gla1ve, Goofy, Kylar, podi, sdy    |
|           45 |      246 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.018 (0.012)    | 0.451 (0.294)    | 1 (1.000) |     5.87 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      256 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -11.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      273 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.69 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      286 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.128 (0.083)    | 0.513 (0.334)    | 1 (1.000) |    13.68 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      901 | 2024-06-16 | Falcons            | L   | 0.893      | -            | -                | -                | -         |   -10.34 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      956 | 2024-06-14 | Complexity         | W   | 0.881      | 0.500        | 0.318 (0.140)    | 0.366 (0.161)    | 1 (0.881) |    22.13 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      965 | 2024-06-14 | MIBR               | W   | 0.880      | 0.500        | 0.201 (0.089)    | 0.637 (0.280)    | 1 (0.880) |    14.70 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1311 | 2024-06-06 | HEROIC             | L   | 0.828      | -            | -                | -                | -         |    -5.88 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1322 | 2024-06-06 | Astralis           | L   | 0.827      | -            | -                | -                | -         |    -3.43 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1360 | 2024-06-05 | Sashi              | W   | 0.822      | 0.715        | 0.187 (0.110)    | 0.971 (0.571)    | 1 (0.822) |     8.93 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1374 | 2024-06-05 | The MongolZ        | L   | 0.821      | -            | -                | -                | -         |    -1.00 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1383 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.820      | -            | -                | -                | -         |   -10.89 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1491 | 2024-06-01 | DMS                | L   | 0.795      | -            | -                | -                | -         |   -22.42 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1500 | 2024-06-01 | KOI                | W   | 0.794      | -            | -                | -                | -         |     2.10 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1510 | 2024-06-01 | DMS                | L   | 0.793      | -            | -                | -                | -         |   -22.80 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1806 | 2024-05-21 | Liquid             | L   | 0.719      | -            | -                | -                | -         |    -8.55 | dycha, gla1ve, Goofy, hades, Kylar |
|           29 |     1902 | 2024-05-18 | fnatic             | W   | 0.700      | 0.769        | 0.292 (0.157)    | 0.529 (0.285)    | -         |     9.10 | dycha, gla1ve, Goofy, hades, Kylar |
|           28 |     1926 | 2024-05-17 | Gaimin Gladiators  | W   | 0.696      | 0.769        | 0.040 (0.021)    | 0.361 (0.193)    | -         |     2.49 | dycha, gla1ve, Goofy, hades, Kylar |
|           27 |     1937 | 2024-05-17 | fnatic             | L   | 0.694      | -            | -                | -                | -         |   -12.59 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     2306 | 2024-05-04 | FURIA              | L   | 0.607      | -            | -                | -                | -         |    -3.88 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     2320 | 2024-05-03 | GamerLegion        | L   | 0.601      | -            | -                | -                | -         |   -15.35 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2340 | 2024-05-02 | Monte              | W   | 0.595      | 0.889        | 0.062 (0.033)    | 0.168 (0.089)    | 1 (0.595) |     1.89 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2370 | 2024-05-01 | Bad News Kangaroos | W   | 0.587      | 0.889        | 0.017 (0.009)    | -                | 1 (0.587) |     0.58 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2402 | 2024-04-30 | GamerLegion        | L   | 0.580      | -            | -                | -                | -         |   -15.31 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2670 | 2024-04-19 | AMKAL              | L   | 0.507      | -            | -                | -                | -         |   -13.37 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2759 | 2024-04-17 | Enterprise         | W   | 0.493      | 0.384        | -                | 0.622 (0.118)    | -         |     0.81 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2932 | 2024-04-10 | OG                 | L   | 0.447      | -            | -                | -                | -         |   -12.95 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     3017 | 2024-04-08 | FORZE              | L   | 0.434      | -            | -                | -                | -         |   -12.97 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     3126 | 2024-04-04 | Aurora Young Blud  | W   | 0.407      | -            | -                | -                | -         |     0.40 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3432 | 2024-03-19 | FURIA              | L   | 0.302      | -            | -                | -                | -         |    -1.78 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3448 | 2024-03-18 | paiN               | L   | 0.293      | -            | -                | -                | -         |    -5.95 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3455 | 2024-03-17 | KOI                | W   | 0.289      | -            | -                | -                | 1 (0.289) |     0.47 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3475 | 2024-03-17 | Imperial           | L   | 0.287      | -            | -                | -                | -         |    -6.75 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3611 | 2024-03-12 | B8                 | L   | 0.254      | -            | -                | -                | -         |    -7.15 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3624 | 2024-03-11 | HEROIC             | L   | 0.248      | -            | -                | -                | -         |    -2.95 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3634 | 2024-03-11 | Metizport          | W   | 0.247      | -            | -                | -                | -         |     0.31 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     4051 | 2024-02-22 | Astralis           | W   | 0.126      | -            | -                | -                | 1 (0.126) |     3.03 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     4074 | 2024-02-21 | Vitality           | L   | 0.121      | -            | -                | -                | -         |    -0.44 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     4107 | 2024-02-20 | GamerLegion        | W   | 0.113      | -            | -                | -                | -         |     0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4127 | 2024-02-19 | ex-Guild Eagles    | W   | 0.108      | -            | -                | -                | -         |     0.08 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4135 | 2024-02-19 | Spirit             | L   | 0.107      | -            | -                | -                | -         |    -0.27 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4352 | 2024-02-09 | Falcons            | L   | 0.042      | -            | -                | -                | -         |    -0.73 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4384 | 2024-02-06 | MOUZ               | L   | 0.022      | -            | -                | -                | -         |    -0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4395 | 2024-02-05 | G2                 | W   | 0.015      | 1.000        | 1.000 (0.015)    | -                | -         |     0.44 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4431 | 2024-02-03 | Vitality           | W   | 0.002      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,886.74)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.894 | $10,000.00     | $8,938.89       |
| 2024-06-09 |      0.848 | $8,000.00      | $6,780.00       |
| 2024-05-23 |      0.734 | $12,500.00     | $9,171.88       |
| 2024-05-12 |      0.661 | $7,000.00      | $4,625.83       |
| 2024-04-14 |      0.474 | $15,000.00     | $7,110.42       |
| 2024-03-20 |      0.308 | $10,000.00     | $3,081.94       |
| 2024-02-11 |      0.054 | $40,000.00     | $2,177.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
