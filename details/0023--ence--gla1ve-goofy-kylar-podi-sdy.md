### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1334.8<br />
<br />
Final Rank Value (1334.8) = Starting Rank Value (1477.6) + Head To Head Adjustments (-142.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.268[<sup>2</sup>](#table1)
- LAN Wins: 0.803[<sup>2</sup>](#table1)

The average of these factors is 0.525<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1477.6
- 400 + ( ( 0.525 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1477.6


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
|           46 |       10 | 2024-08-05 | PARIVISION         | L   | 1.000      | -            | -                | -                | -         |   -25.61 | gla1ve, Goofy, Kylar, podi, sdy    |
|           45 |       23 | 2024-08-04 | 9INE               | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.533 (0.232)    | -         |     2.66 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      325 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.42 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      352 | 2024-07-26 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      392 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.565 (0.367)    | 1 (1.000) |     5.53 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      402 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.26 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      419 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.87 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      432 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.511 (0.332)    | 1 (1.000) |    12.82 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1032 | 2024-06-16 | Falcons            | L   | 0.865      | -            | -                | -                | -         |   -11.32 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1096 | 2024-06-14 | Complexity         | W   | 0.853      | 0.500        | 0.342 (0.146)    | 0.373 (0.159)    | 1 (0.853) |    21.28 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1105 | 2024-06-14 | MIBR               | W   | 0.852      | 0.500        | 0.208 (0.089)    | 0.648 (0.276)    | 1 (0.852) |    15.48 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1438 | 2024-06-06 | HEROIC             | L   | 0.799      | -            | -                | -                | -         |    -5.97 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1449 | 2024-06-06 | Astralis           | L   | 0.798      | -            | -                | -                | -         |    -3.04 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1485 | 2024-06-05 | Sashi              | W   | 0.793      | 0.715        | 0.184 (0.104)    | 0.983 (0.558)    | 1 (0.793) |     7.89 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1498 | 2024-06-05 | The MongolZ        | L   | 0.792      | -            | -                | -                | -         |    -1.08 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1507 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.792      | -            | -                | -                | -         |    -6.02 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1614 | 2024-06-01 | DMS                | L   | 0.767      | -            | -                | -                | -         |   -21.84 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1623 | 2024-06-01 | KOI                | W   | 0.766      | -            | -                | -                | -         |     3.29 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1633 | 2024-06-01 | DMS                | L   | 0.765      | -            | -                | -                | -         |   -22.16 | gla1ve, Goofy, Kylar, podi, sdy    |
|           27 |     1912 | 2024-05-21 | Liquid             | L   | 0.691      | -            | -                | -                | -         |    -5.50 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     1998 | 2024-05-18 | fnatic             | W   | 0.672      | 0.769        | 0.371 (0.191)    | 0.697 (0.360)    | -         |    12.98 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     2021 | 2024-05-17 | Gaimin Gladiators  | W   | 0.667      | 0.769        | 0.037 (0.019)    | 0.342 (0.175)    | -         |     2.13 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2032 | 2024-05-17 | fnatic             | L   | 0.665      | -            | -                | -                | -         |    -7.58 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2390 | 2024-05-04 | FURIA              | L   | 0.579      | -            | -                | -                | -         |    -3.78 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2404 | 2024-05-03 | GamerLegion        | L   | 0.572      | -            | -                | -                | -         |   -14.78 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2424 | 2024-05-02 | Monte              | W   | 0.566      | 0.889        | 0.057 (0.029)    | -                | 1 (0.566) |     1.62 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2452 | 2024-05-01 | Bad News Kangaroos | W   | 0.559      | 0.889        | 0.017 (0.008)    | 0.222 (0.111)    | 1 (0.559) |     0.56 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2483 | 2024-04-30 | GamerLegion        | L   | 0.551      | -            | -                | -                | -         |   -14.67 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2744 | 2024-04-19 | AMKAL              | L   | 0.479      | -            | -                | -                | -         |   -12.70 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2831 | 2024-04-17 | Enterprise         | W   | 0.465      | 0.384        | -                | 0.616 (0.110)    | -         |     0.78 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3002 | 2024-04-10 | OG                 | L   | 0.419      | -            | -                | -                | -         |   -12.15 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3087 | 2024-04-08 | FORZE              | L   | 0.405      | -            | -                | -                | -         |   -12.17 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3195 | 2024-04-04 | Aurora Young Blud  | W   | 0.378      | -            | -                | -                | -         |     0.42 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3489 | 2024-03-19 | FURIA              | L   | 0.273      | -            | -                | -                | -         |    -1.72 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3505 | 2024-03-18 | paiN               | L   | 0.265      | -            | -                | -                | -         |    -4.88 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3512 | 2024-03-17 | KOI                | W   | 0.261      | -            | -                | -                | 1 (0.261) |     0.86 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3532 | 2024-03-17 | Imperial           | L   | 0.259      | -            | -                | -                | -         |    -6.22 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3663 | 2024-03-12 | B8                 | L   | 0.226      | -            | -                | -                | -         |    -6.38 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3676 | 2024-03-11 | HEROIC             | L   | 0.220      | -            | -                | -                | -         |    -2.72 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     3686 | 2024-03-11 | Metizport          | W   | 0.219      | -            | -                | -                | -         |     0.20 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4088 | 2024-02-22 | Astralis           | W   | 0.098      | -            | -                | -                | 1 (0.098) |     2.48 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4110 | 2024-02-21 | Vitality           | L   | 0.092      | -            | -                | -                | -         |    -0.32 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4143 | 2024-02-20 | GamerLegion        | W   | 0.085      | -            | -                | -                | -         |     0.05 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4163 | 2024-02-19 | ex-Guild Eagles    | W   | 0.079      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4171 | 2024-02-19 | Spirit             | L   | 0.078      | -            | -                | -                | -         |    -0.21 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4376 | 2024-02-09 | Falcons            | L   | 0.013      | -            | -                | -                | -         |    -0.24 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,968.33)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.865 | $10,000.00     | $8,654.17       |
| 2024-06-09 |      0.819 | $8,000.00      | $6,552.22       |
| 2024-05-23 |      0.705 | $12,500.00     | $8,815.97       |
| 2024-05-12 |      0.632 | $7,000.00      | $4,426.53       |
| 2024-04-14 |      0.446 | $15,000.00     | $6,683.33       |
| 2024-03-20 |      0.280 | $10,000.00     | $2,797.22       |
| 2024-02-11 |      0.026 | $40,000.00     | $1,038.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
