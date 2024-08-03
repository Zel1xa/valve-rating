### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1338.6<br />
<br />
Final Rank Value (1338.6) = Starting Rank Value (1467.6) + Head To Head Adjustments (-129.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.565[<sup>1</sup>](#table2)
- Bounty Collected: 0.457[<sup>2</sup>](#table1)
- Opponent Network: 0.259[<sup>2</sup>](#table1)
- LAN Wins: 0.807[<sup>2</sup>](#table1)

The average of these factors is 0.522<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1467.6
- 400 + ( ( 0.522 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1467.6


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
|           45 |      241 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.13 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      268 | 2024-07-26 | True Rippers       | W   | 1.000      | 0.650        | -                | 0.177 (0.115)    | 1 (1.000) |     0.90 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      308 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.018 (0.011)    | 0.553 (0.359)    | 1 (1.000) |     5.81 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      318 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -11.76 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      335 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.61 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      348 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.534 (0.347)    | 1 (1.000) |    13.50 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      933 | 2024-06-16 | Falcons            | L   | 0.878      | -            | -                | -                | -         |   -10.50 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |      984 | 2024-06-14 | Complexity         | W   | 0.866      | 0.500        | 0.313 (0.135)    | 0.394 (0.170)    | 1 (0.866) |    21.93 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |      993 | 2024-06-14 | MIBR               | W   | 0.865      | 0.500        | 0.210 (0.091)    | 0.682 (0.295)    | 1 (0.865) |    16.25 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1316 | 2024-06-06 | HEROIC             | L   | 0.813      | -            | -                | -                | -         |    -5.65 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1327 | 2024-06-06 | Astralis           | L   | 0.812      | -            | -                | -                | -         |    -3.21 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1362 | 2024-06-05 | Sashi              | W   | 0.807      | 0.715        | 0.184 (0.106)    | 0.998 (0.576)    | 1 (0.807) |     8.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1376 | 2024-06-05 | The MongolZ        | L   | 0.806      | -            | -                | -                | -         |    -0.97 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1385 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.805      | -            | -                | -                | -         |    -6.74 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1490 | 2024-06-01 | DMS                | L   | 0.780      | -            | -                | -                | -         |   -21.96 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1498 | 2024-06-01 | KOI                | W   | 0.780      | -            | -                | -                | -         |     2.07 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1508 | 2024-06-01 | DMS                | L   | 0.779      | -            | -                | -                | -         |   -22.34 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1786 | 2024-05-21 | Liquid             | L   | 0.705      | -            | -                | -                | -         |    -6.97 | dycha, gla1ve, Goofy, hades, Kylar |
|           27 |     1871 | 2024-05-18 | fnatic             | W   | 0.686      | 0.769        | 0.290 (0.153)    | 0.627 (0.330)    | -         |     9.03 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     1894 | 2024-05-17 | Gaimin Gladiators  | W   | 0.681      | 0.769        | 0.038 (0.020)    | 0.366 (0.191)    | -         |     2.41 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     1905 | 2024-05-17 | fnatic             | L   | 0.679      | -            | -                | -                | -         |   -12.22 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2262 | 2024-05-04 | FURIA              | L   | 0.593      | -            | -                | -                | -         |    -3.82 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2276 | 2024-05-03 | GamerLegion        | L   | 0.586      | -            | -                | -                | -         |   -14.93 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2296 | 2024-05-02 | Monte              | W   | 0.580      | 0.889        | 0.060 (0.031)    | 0.168 (0.087)    | 1 (0.580) |     1.83 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2324 | 2024-05-01 | Bad News Kangaroos | W   | 0.573      | 0.889        | 0.017 (0.009)    | -                | 1 (0.573) |     0.57 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2355 | 2024-04-30 | GamerLegion        | L   | 0.565      | -            | -                | -                | -         |   -14.87 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2615 | 2024-04-19 | AMKAL              | L   | 0.492      | -            | -                | -                | -         |   -12.88 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2702 | 2024-04-17 | Enterprise         | W   | 0.479      | 0.384        | 0.039 (0.007)    | 0.646 (0.119)    | -         |     0.86 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2873 | 2024-04-10 | OG                 | L   | 0.432      | -            | -                | -                | -         |   -12.51 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     2958 | 2024-04-08 | FORZE              | L   | 0.419      | -            | -                | -                | -         |   -12.53 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3066 | 2024-04-04 | Aurora Young Blud  | W   | 0.392      | -            | -                | -                | -         |     0.35 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3355 | 2024-03-19 | FURIA              | L   | 0.287      | -            | -                | -                | -         |    -1.72 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3371 | 2024-03-18 | paiN               | L   | 0.279      | -            | -                | -                | -         |    -5.49 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3378 | 2024-03-17 | KOI                | W   | 0.274      | -            | -                | -                | 1 (0.274) |     0.46 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3398 | 2024-03-17 | Imperial           | L   | 0.272      | -            | -                | -                | -         |    -6.65 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3526 | 2024-03-12 | B8                 | L   | 0.239      | -            | -                | -                | -         |    -6.72 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3539 | 2024-03-11 | HEROIC             | L   | 0.234      | -            | -                | -                | -         |    -2.75 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3549 | 2024-03-11 | Metizport          | W   | 0.233      | -            | -                | -                | -         |     0.31 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     3951 | 2024-02-22 | Astralis           | W   | 0.112      | -            | -                | -                | 1 (0.112) |     2.74 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     3973 | 2024-02-21 | Vitality           | L   | 0.106      | -            | -                | -                | -         |    -0.34 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4006 | 2024-02-20 | GamerLegion        | W   | 0.099      | -            | -                | -                | -         |     0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4026 | 2024-02-19 | ex-Guild Eagles    | W   | 0.093      | -            | -                | -                | -         |     0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4034 | 2024-02-19 | Spirit             | L   | 0.092      | -            | -                | -                | -         |    -0.22 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4240 | 2024-02-09 | Falcons            | L   | 0.027      | -            | -                | -                | -         |    -0.47 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4272 | 2024-02-06 | MOUZ               | L   | 0.007      | -            | -                | -                | -         |    -0.03 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,382.45)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.879 | $10,000.00     | $8,792.13       |
| 2024-06-09 |      0.833 | $8,000.00      | $6,662.59       |
| 2024-05-23 |      0.719 | $12,500.00     | $8,988.43       |
| 2024-05-12 |      0.646 | $7,000.00      | $4,523.10       |
| 2024-04-14 |      0.459 | $15,000.00     | $6,890.28       |
| 2024-03-20 |      0.294 | $10,000.00     | $2,935.19       |
| 2024-02-11 |      0.040 | $40,000.00     | $1,590.74       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
