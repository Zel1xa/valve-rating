### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1334.7<br />
<br />
Final Rank Value (1334.7) = Starting Rank Value (1477.7) + Head To Head Adjustments (-142.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.268[<sup>2</sup>](#table1)
- LAN Wins: 0.803[<sup>2</sup>](#table1)

The average of these factors is 0.526<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1477.7
- 400 + ( ( 0.526 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1477.7


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
|           46 |        9 | 2024-08-05 | PARIVISION         | L   | 1.000      | -            | -                | -                | -         |   -25.62 | gla1ve, Goofy, Kylar, podi, sdy    |
|           45 |       22 | 2024-08-04 | 9INE               | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.533 (0.231)    | -         |     2.65 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      324 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.45 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      351 | 2024-07-26 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      391 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.565 (0.367)    | 1 (1.000) |     5.52 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      401 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.27 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      418 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.88 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      431 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.511 (0.332)    | 1 (1.000) |    12.81 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1031 | 2024-06-16 | Falcons            | L   | 0.865      | -            | -                | -                | -         |   -11.32 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1095 | 2024-06-14 | Complexity         | W   | 0.853      | 0.500        | 0.342 (0.146)    | 0.373 (0.159)    | 1 (0.853) |    21.29 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1104 | 2024-06-14 | MIBR               | W   | 0.852      | 0.500        | 0.208 (0.089)    | 0.649 (0.276)    | 1 (0.852) |    15.49 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1437 | 2024-06-06 | HEROIC             | L   | 0.800      | -            | -                | -                | -         |    -5.96 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1448 | 2024-06-06 | Astralis           | L   | 0.799      | -            | -                | -                | -         |    -3.04 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1484 | 2024-06-05 | Sashi              | W   | 0.794      | 0.715        | 0.184 (0.104)    | 0.983 (0.558)    | 1 (0.794) |     7.89 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1497 | 2024-06-05 | The MongolZ        | L   | 0.793      | -            | -                | -                | -         |    -1.08 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1506 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.792      | -            | -                | -                | -         |    -6.02 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1613 | 2024-06-01 | DMS                | L   | 0.767      | -            | -                | -                | -         |   -21.85 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1622 | 2024-06-01 | KOI                | W   | 0.766      | -            | -                | -                | -         |     3.29 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1632 | 2024-06-01 | DMS                | L   | 0.765      | -            | -                | -                | -         |   -22.17 | gla1ve, Goofy, Kylar, podi, sdy    |
|           27 |     1911 | 2024-05-21 | Liquid             | L   | 0.691      | -            | -                | -                | -         |    -5.50 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     1997 | 2024-05-18 | fnatic             | W   | 0.672      | 0.769        | 0.371 (0.192)    | 0.697 (0.360)    | -         |    12.99 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     2020 | 2024-05-17 | Gaimin Gladiators  | W   | 0.668      | 0.769        | 0.037 (0.019)    | 0.342 (0.175)    | -         |     2.13 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2031 | 2024-05-17 | fnatic             | L   | 0.666      | -            | -                | -                | -         |    -7.59 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2389 | 2024-05-04 | FURIA              | L   | 0.579      | -            | -                | -                | -         |    -3.78 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2403 | 2024-05-03 | GamerLegion        | L   | 0.573      | -            | -                | -                | -         |   -14.78 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2423 | 2024-05-02 | Monte              | W   | 0.567      | 0.889        | 0.057 (0.029)    | -                | 1 (0.567) |     1.62 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2451 | 2024-05-01 | Bad News Kangaroos | W   | 0.559      | 0.889        | 0.017 (0.008)    | 0.222 (0.111)    | 1 (0.559) |     0.56 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2482 | 2024-04-30 | GamerLegion        | L   | 0.552      | -            | -                | -                | -         |   -14.68 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2743 | 2024-04-19 | AMKAL              | L   | 0.479      | -            | -                | -                | -         |   -12.72 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2830 | 2024-04-17 | Enterprise         | W   | 0.465      | 0.384        | -                | 0.616 (0.110)    | -         |     0.77 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3001 | 2024-04-10 | OG                 | L   | 0.419      | -            | -                | -                | -         |   -12.16 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3086 | 2024-04-08 | FORZE              | L   | 0.406      | -            | -                | -                | -         |   -12.18 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3194 | 2024-04-04 | Aurora Young Blud  | W   | 0.379      | -            | -                | -                | -         |     0.42 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3488 | 2024-03-19 | FURIA              | L   | 0.273      | -            | -                | -                | -         |    -1.72 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3504 | 2024-03-18 | paiN               | L   | 0.265      | -            | -                | -                | -         |    -4.89 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3511 | 2024-03-17 | KOI                | W   | 0.261      | -            | -                | -                | 1 (0.261) |     0.86 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3531 | 2024-03-17 | Imperial           | L   | 0.259      | -            | -                | -                | -         |    -6.23 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3662 | 2024-03-12 | B8                 | L   | 0.226      | -            | -                | -                | -         |    -6.39 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3675 | 2024-03-11 | HEROIC             | L   | 0.220      | -            | -                | -                | -         |    -2.72 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     3685 | 2024-03-11 | Metizport          | W   | 0.219      | -            | -                | -                | -         |     0.20 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4087 | 2024-02-22 | Astralis           | W   | 0.098      | -            | -                | -                | 1 (0.098) |     2.49 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4109 | 2024-02-21 | Vitality           | L   | 0.093      | -            | -                | -                | -         |    -0.32 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4142 | 2024-02-20 | GamerLegion        | W   | 0.085      | -            | -                | -                | -         |     0.05 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4162 | 2024-02-19 | ex-Guild Eagles    | W   | 0.080      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4170 | 2024-02-19 | Spirit             | L   | 0.079      | -            | -                | -                | -         |    -0.21 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4375 | 2024-02-09 | Falcons            | L   | 0.014      | -            | -                | -                | -         |    -0.25 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,011.04)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.866 | $10,000.00     | $8,658.33       |
| 2024-06-09 |      0.819 | $8,000.00      | $6,555.56       |
| 2024-05-23 |      0.706 | $12,500.00     | $8,821.18       |
| 2024-05-12 |      0.633 | $7,000.00      | $4,429.44       |
| 2024-04-14 |      0.446 | $15,000.00     | $6,689.58       |
| 2024-03-20 |      0.280 | $10,000.00     | $2,801.39       |
| 2024-02-11 |      0.026 | $40,000.00     | $1,055.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
