### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1342.5<br />
<br />
Final Rank Value (1342.5) = Starting Rank Value (1480.1) + Head To Head Adjustments (-137.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.459[<sup>2</sup>](#table1)
- Opponent Network: 0.246[<sup>2</sup>](#table1)
- LAN Wins: 0.827[<sup>2</sup>](#table1)

The average of these factors is 0.525<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1480.1
- 400 + ( ( 0.525 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1480.1


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
|           47 |      185 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.22 | gla1ve, Goofy, Kylar, podi, sdy    |
|           46 |      212 | 2024-07-26 | True Rippers       | W   | 1.000      | 0.650        | -                | 0.172 (0.112)    | 1 (1.000) |     0.90 | gla1ve, Goofy, Kylar, podi, sdy    |
|           45 |      252 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.018 (0.012)    | 0.457 (0.297)    | 1 (1.000) |     5.90 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      262 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -11.85 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      279 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.70 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      292 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.128 (0.083)    | 0.513 (0.334)    | 1 (1.000) |    13.55 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      907 | 2024-06-16 | Falcons            | L   | 0.891      | -            | -                | -                | -         |   -10.42 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      962 | 2024-06-14 | Complexity         | W   | 0.879      | 0.500        | 0.318 (0.140)    | 0.366 (0.161)    | 1 (0.879) |    22.03 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      971 | 2024-06-14 | MIBR               | W   | 0.878      | 0.500        | 0.201 (0.088)    | 0.637 (0.280)    | 1 (0.878) |    14.53 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1317 | 2024-06-06 | HEROIC             | L   | 0.826      | -            | -                | -                | -         |    -5.86 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1328 | 2024-06-06 | Astralis           | L   | 0.825      | -            | -                | -                | -         |    -3.43 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1366 | 2024-06-05 | Sashi              | W   | 0.820      | 0.715        | 0.186 (0.109)    | 0.970 (0.569)    | 1 (0.820) |     8.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1380 | 2024-06-05 | The MongolZ        | L   | 0.819      | -            | -                | -                | -         |    -1.01 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1389 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.818      | -            | -                | -                | -         |    -9.26 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1497 | 2024-06-01 | DMS                | L   | 0.793      | -            | -                | -                | -         |   -22.40 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1506 | 2024-06-01 | KOI                | W   | 0.793      | -            | -                | -                | -         |     2.07 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1516 | 2024-06-01 | DMS                | L   | 0.792      | -            | -                | -                | -         |   -22.78 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1812 | 2024-05-21 | Liquid             | L   | 0.718      | -            | -                | -                | -         |    -6.87 | dycha, gla1ve, Goofy, hades, Kylar |
|           29 |     1908 | 2024-05-18 | fnatic             | W   | 0.699      | 0.769        | 0.292 (0.157)    | 0.568 (0.305)    | -         |     9.06 | dycha, gla1ve, Goofy, hades, Kylar |
|           28 |     1932 | 2024-05-17 | Gaimin Gladiators  | W   | 0.694      | 0.769        | 0.040 (0.021)    | 0.360 (0.192)    | -         |     2.47 | dycha, gla1ve, Goofy, hades, Kylar |
|           27 |     1943 | 2024-05-17 | fnatic             | L   | 0.692      | -            | -                | -                | -         |   -12.59 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     2312 | 2024-05-04 | FURIA              | L   | 0.606      | -            | -                | -                | -         |    -3.84 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     2326 | 2024-05-03 | GamerLegion        | L   | 0.599      | -            | -                | -                | -         |   -15.30 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2346 | 2024-05-02 | Monte              | W   | 0.593      | 0.889        | 0.062 (0.032)    | 0.168 (0.088)    | 1 (0.593) |     1.89 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2376 | 2024-05-01 | Bad News Kangaroos | W   | 0.586      | 0.889        | 0.017 (0.009)    | -                | 1 (0.586) |     0.58 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2408 | 2024-04-30 | GamerLegion        | L   | 0.578      | -            | -                | -                | -         |   -15.26 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2676 | 2024-04-19 | AMKAL              | L   | 0.506      | -            | -                | -                | -         |   -13.33 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2765 | 2024-04-17 | Enterprise         | W   | 0.492      | 0.384        | -                | 0.622 (0.118)    | -         |     0.80 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2938 | 2024-04-10 | OG                 | L   | 0.445      | -            | -                | -                | -         |   -12.90 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     3023 | 2024-04-08 | FORZE              | L   | 0.432      | -            | -                | -                | -         |   -12.92 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     3132 | 2024-04-04 | Aurora Young Blud  | W   | 0.405      | -            | -                | -                | -         |     0.40 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3438 | 2024-03-19 | FURIA              | L   | 0.300      | -            | -                | -                | -         |    -1.77 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3454 | 2024-03-18 | paiN               | L   | 0.292      | -            | -                | -                | -         |    -5.93 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3461 | 2024-03-17 | KOI                | W   | 0.287      | -            | -                | -                | 1 (0.287) |     0.47 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3481 | 2024-03-17 | Imperial           | L   | 0.285      | -            | -                | -                | -         |    -6.73 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3617 | 2024-03-12 | B8                 | L   | 0.252      | -            | -                | -                | -         |    -7.11 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3630 | 2024-03-11 | HEROIC             | L   | 0.247      | -            | -                | -                | -         |    -2.94 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3640 | 2024-03-11 | Metizport          | W   | 0.246      | -            | -                | -                | -         |     0.31 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     4057 | 2024-02-22 | Astralis           | W   | 0.125      | -            | -                | -                | 1 (0.125) |     2.99 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     4080 | 2024-02-21 | Vitality           | L   | 0.119      | -            | -                | -                | -         |    -0.44 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     4113 | 2024-02-20 | GamerLegion        | W   | 0.112      | -            | -                | -                | -         |     0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4133 | 2024-02-19 | ex-Guild Eagles    | W   | 0.106      | -            | -                | -                | -         |     0.08 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4141 | 2024-02-19 | Spirit             | L   | 0.105      | -            | -                | -                | -         |    -0.27 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4358 | 2024-02-09 | Falcons            | L   | 0.040      | -            | -                | -                | -         |    -0.70 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4390 | 2024-02-06 | MOUZ               | L   | 0.020      | -            | -                | -                | -         |    -0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4401 | 2024-02-05 | G2                 | W   | 0.013      | 1.000        | 1.000 (0.013)    | -                | -         |     0.39 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4437 | 2024-02-03 | Vitality           | W   | 0.001      | -            | -                | -                | -         |     0.01 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,715.90)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.892 | $10,000.00     | $8,922.22       |
| 2024-06-09 |      0.846 | $8,000.00      | $6,766.67       |
| 2024-05-23 |      0.732 | $12,500.00     | $9,151.04       |
| 2024-05-12 |      0.659 | $7,000.00      | $4,614.17       |
| 2024-04-14 |      0.472 | $15,000.00     | $7,085.42       |
| 2024-03-20 |      0.307 | $10,000.00     | $3,065.28       |
| 2024-02-11 |      0.053 | $40,000.00     | $2,111.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
