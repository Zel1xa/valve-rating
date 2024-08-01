### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1341.7<br />
<br />
Final Rank Value (1341.7) = Starting Rank Value (1478.9) + Head To Head Adjustments (-137.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.459[<sup>2</sup>](#table1)
- Opponent Network: 0.243[<sup>2</sup>](#table1)
- LAN Wins: 0.827[<sup>2</sup>](#table1)

The average of these factors is 0.524<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1478.9
- 400 + ( ( 0.524 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1478.9


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
|           47 |      183 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.20 | gla1ve, Goofy, Kylar, podi, sdy    |
|           46 |      210 | 2024-07-26 | True Rippers       | W   | 1.000      | 0.650        | -                | 0.172 (0.112)    | 1 (1.000) |     0.90 | gla1ve, Goofy, Kylar, podi, sdy    |
|           45 |      250 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.018 (0.012)    | 0.451 (0.293)    | 1 (1.000) |     5.82 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      260 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -11.84 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      277 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.69 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      290 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.128 (0.083)    | 0.513 (0.334)    | 1 (1.000) |    13.58 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      905 | 2024-06-16 | Falcons            | L   | 0.892      | -            | -                | -                | -         |   -10.39 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      960 | 2024-06-14 | Complexity         | W   | 0.880      | 0.500        | 0.318 (0.140)    | 0.366 (0.161)    | 1 (0.880) |    22.06 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      969 | 2024-06-14 | MIBR               | W   | 0.879      | 0.500        | 0.201 (0.088)    | 0.637 (0.280)    | 1 (0.879) |    14.57 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1315 | 2024-06-06 | HEROIC             | L   | 0.826      | -            | -                | -                | -         |    -5.84 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1326 | 2024-06-06 | Astralis           | L   | 0.825      | -            | -                | -                | -         |    -3.41 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1364 | 2024-06-05 | Sashi              | W   | 0.820      | 0.715        | 0.187 (0.109)    | 0.970 (0.569)    | 1 (0.820) |     8.82 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1378 | 2024-06-05 | The MongolZ        | L   | 0.820      | -            | -                | -                | -         |    -1.00 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1387 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.819      | -            | -                | -                | -         |    -9.26 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1495 | 2024-06-01 | DMS                | L   | 0.794      | -            | -                | -                | -         |   -22.40 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1504 | 2024-06-01 | KOI                | W   | 0.793      | -            | -                | -                | -         |     2.08 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1514 | 2024-06-01 | DMS                | L   | 0.792      | -            | -                | -                | -         |   -22.78 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1810 | 2024-05-21 | Liquid             | L   | 0.718      | -            | -                | -                | -         |    -6.85 | dycha, gla1ve, Goofy, hades, Kylar |
|           29 |     1906 | 2024-05-18 | fnatic             | W   | 0.699      | 0.769        | 0.292 (0.157)    | 0.529 (0.284)    | -         |     9.09 | dycha, gla1ve, Goofy, hades, Kylar |
|           28 |     1930 | 2024-05-17 | Gaimin Gladiators  | W   | 0.694      | 0.769        | 0.040 (0.021)    | 0.360 (0.192)    | -         |     2.49 | dycha, gla1ve, Goofy, hades, Kylar |
|           27 |     1941 | 2024-05-17 | fnatic             | L   | 0.692      | -            | -                | -                | -         |   -12.56 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     2310 | 2024-05-04 | FURIA              | L   | 0.606      | -            | -                | -                | -         |    -3.84 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     2324 | 2024-05-03 | GamerLegion        | L   | 0.599      | -            | -                | -                | -         |   -15.31 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2344 | 2024-05-02 | Monte              | W   | 0.594      | 0.889        | 0.062 (0.033)    | 0.168 (0.089)    | 1 (0.594) |     1.90 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2374 | 2024-05-01 | Bad News Kangaroos | W   | 0.586      | 0.889        | 0.017 (0.009)    | -                | 1 (0.586) |     0.58 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2406 | 2024-04-30 | GamerLegion        | L   | 0.579      | -            | -                | -                | -         |   -15.27 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2674 | 2024-04-19 | AMKAL              | L   | 0.506      | -            | -                | -                | -         |   -13.32 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2763 | 2024-04-17 | Enterprise         | W   | 0.492      | 0.384        | -                | 0.622 (0.118)    | -         |     0.81 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2936 | 2024-04-10 | OG                 | L   | 0.446      | -            | -                | -                | -         |   -12.90 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     3021 | 2024-04-08 | FORZE              | L   | 0.432      | -            | -                | -                | -         |   -12.93 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     3130 | 2024-04-04 | Aurora Young Blud  | W   | 0.405      | -            | -                | -                | -         |     0.40 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3436 | 2024-03-19 | FURIA              | L   | 0.300      | -            | -                | -                | -         |    -1.77 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3452 | 2024-03-18 | paiN               | L   | 0.292      | -            | -                | -                | -         |    -5.92 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3459 | 2024-03-17 | KOI                | W   | 0.288      | -            | -                | -                | 1 (0.288) |     0.47 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3479 | 2024-03-17 | Imperial           | L   | 0.286      | -            | -                | -                | -         |    -6.72 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3615 | 2024-03-12 | B8                 | L   | 0.253      | -            | -                | -                | -         |    -7.11 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3628 | 2024-03-11 | HEROIC             | L   | 0.247      | -            | -                | -                | -         |    -2.93 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3638 | 2024-03-11 | Metizport          | W   | 0.246      | -            | -                | -                | -         |     0.31 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     4055 | 2024-02-22 | Astralis           | W   | 0.125      | -            | -                | -                | 1 (0.125) |     3.00 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     4078 | 2024-02-21 | Vitality           | L   | 0.119      | -            | -                | -                | -         |    -0.44 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     4111 | 2024-02-20 | GamerLegion        | W   | 0.112      | -            | -                | -                | -         |     0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4131 | 2024-02-19 | ex-Guild Eagles    | W   | 0.107      | -            | -                | -                | -         |     0.08 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4139 | 2024-02-19 | Spirit             | L   | 0.105      | -            | -                | -                | -         |    -0.27 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4356 | 2024-02-09 | Falcons            | L   | 0.040      | -            | -                | -                | -         |    -0.71 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4388 | 2024-02-06 | MOUZ               | L   | 0.020      | -            | -                | -                | -         |    -0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4399 | 2024-02-05 | G2                 | W   | 0.013      | 1.000        | 1.000 (0.013)    | -                | -         |     0.39 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4435 | 2024-02-03 | Vitality           | W   | 0.001      | -            | -                | -                | -         |     0.02 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,744.38)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.892 | $10,000.00     | $8,925.00       |
| 2024-06-09 |      0.846 | $8,000.00      | $6,768.89       |
| 2024-05-23 |      0.732 | $12,500.00     | $9,154.51       |
| 2024-05-12 |      0.659 | $7,000.00      | $4,616.11       |
| 2024-04-14 |      0.473 | $15,000.00     | $7,089.58       |
| 2024-03-20 |      0.307 | $10,000.00     | $3,068.06       |
| 2024-02-11 |      0.053 | $40,000.00     | $2,122.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
