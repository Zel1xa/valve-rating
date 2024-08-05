### Roster Details<br />
Team Name: 1WIN<br />
Roster: buster, HObbit, lattykk, neaLaN, Ryujin<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1010.2<br />
<br />
Final Rank Value (1010.2) = Starting Rank Value (919.8) + Head To Head Adjustments (90.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.408[<sup>2</sup>](#table1)
- Opponent Network: 0.220[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.254<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 919.8
- 400 + ( ( 0.254 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 919.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |        5 | 2024-08-04 | TSM             | W   | 1.000      | 0.426        | 0.040 (0.017)    | 0.395 (0.168)    | 0 (0.000) |    14.32 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           44 |       20 | 2024-08-04 | Young Ninjas    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.53 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           43 |       38 | 2024-08-03 | MOUZ NXT        | W   | 1.000      | 0.435        | 0.139 (0.060)    | 1.000 (0.435)    | 0 (0.000) |    21.29 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           42 |       59 | 2024-08-03 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -17.23 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           41 |      173 | 2024-07-31 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.51 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           40 |      216 | 2024-07-30 | ECLOT           | L   | 1.000      | -            | -                | -                | -         |   -12.21 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           39 |      238 | 2024-07-29 | CYBERSHOKE      | L   | 1.000      | -            | -                | -                | -         |   -18.21 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           38 |      249 | 2024-07-29 | NOM             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.83 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           37 |      288 | 2024-07-28 | TSM             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.62 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           36 |      301 | 2024-07-27 | CPH Wolves      | W   | 1.000      | 0.435        | -                | 0.365 (0.159)    | 0 (0.000) |    10.44 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           35 |      398 | 2024-07-24 | BC.Game         | W   | 1.000      | 0.435        | 0.022 (0.009)    | 0.316 (0.137)    | 0 (0.000) |    12.14 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           34 |     1293 | 2024-06-08 | Monte           | L   | 0.818      | -            | -                | -                | -         |   -11.47 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           33 |     1294 | 2024-06-08 | Quixal          | W   | 0.817      | -            | -                | -                | 0 (0.000) |     0.96 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           32 |     1304 | 2024-06-08 | AMKAL           | L   | 0.817      | -            | -                | -                | -         |    -6.28 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           31 |     1425 | 2024-06-06 | FAVBET          | L   | 0.803      | -            | -                | -                | -         |   -18.97 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           30 |     1603 | 2024-06-01 | Insilio         | L   | 0.771      | -            | -                | -                | -         |   -14.53 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           29 |     1661 | 2024-05-30 | V1dar           | W   | 0.757      | -            | -                | -                | 0 (0.000) |     1.60 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           28 |     1748 | 2024-05-26 | 9 Pandas        | L   | 0.730      | -            | -                | -                | -         |   -10.68 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           27 |     1773 | 2024-05-25 | FURIA           | W   | 0.723      | 0.435        | 0.284 (0.089)    | 0.490 (0.154)    | -         |    21.99 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           26 |     1797 | 2024-05-23 | ECSTATIC        | W   | 0.711      | -            | -                | -                | -         |     0.73 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           25 |     1971 | 2024-05-18 | SINNERS         | W   | 0.677      | 0.435        | 0.037 (0.011)    | 0.797 (0.234)    | -         |    13.12 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           24 |     2051 | 2024-05-16 | Zero Tenacity   | W   | 0.663      | 0.435        | 0.137 (0.039)    | 1.000 (0.288)    | -         |    13.18 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           23 |     2173 | 2024-05-13 | Permitta        | W   | 0.644      | 0.435        | 0.024 (0.007)    | 0.876 (0.245)    | -         |     8.39 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           22 |     2275 | 2024-05-09 | Sashi           | L   | 0.616      | -            | -                | -                | -         |    -4.06 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           21 |     2301 | 2024-05-08 | Nemiga          | W   | 0.609      | 0.396        | 0.317 (0.076)    | 0.733 (0.177)    | -         |    14.92 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           20 |     2311 | 2024-05-07 | BLEED           | W   | 0.604      | 0.396        | 0.091 (0.022)    | -                | -         |    12.56 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           19 |     2359 | 2024-05-05 | ex-Guild Eagles | W   | 0.589      | -            | -                | -                | -         |     6.64 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           18 |     2403 | 2024-05-02 | Soda            | W   | 0.571      | -            | -                | -                | -         |     0.83 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           17 |     2411 | 2024-05-02 | 500             | W   | 0.570      | -            | -                | -                | -         |     4.21 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           16 |     2474 | 2024-04-29 | ECLOT           | L   | 0.551      | -            | -                | -                | -         |    -3.39 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           15 |     2476 | 2024-04-29 | SINNERS         | L   | 0.550      | -            | -                | -                | -         |    -5.36 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           14 |     2492 | 2024-04-28 | Sangal          | L   | 0.544      | -            | -                | -                | -         |    -4.68 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           13 |     2524 | 2024-04-27 | Nemiga          | L   | 0.537      | -            | -                | -                | -         |    -3.80 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           12 |     2573 | 2024-04-25 | Permitta        | W   | 0.524      | 0.435        | -                | 0.876 (0.199)    | -         |     8.67 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           11 |     2612 | 2024-04-23 | HAVU            | W   | 0.510      | -            | -                | -                | -         |     3.29 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           10 |     2651 | 2024-04-21 | Nemiga          | L   | 0.496      | -            | -                | -                | -         |    -3.55 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            9 |     2671 | 2024-04-20 | Portugal        | W   | 0.491      | -            | -                | -                | -         |     3.03 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            8 |     2843 | 2024-04-16 | ENCE Academy    | W   | 0.464      | -            | -                | -                | -         |     3.54 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            7 |     2871 | 2024-04-15 | Lazer Cats      | W   | 0.455      | -            | -                | -                | -         |     1.36 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            6 |     3035 | 2024-04-09 | Aurora          | L   | 0.417      | -            | -                | -                | -         |    -0.23 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            5 |     3056 | 2024-04-08 | 9 Pandas        | W   | 0.411      | -            | -                | -                | -         |     7.81 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            4 |     3068 | 2024-04-08 | Aurora          | W   | 0.410      | 0.143        | 0.423 (0.025)    | -                | -         |    12.72 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            3 |     3660 | 2024-03-11 | Insilio         | L   | 0.224      | -            | -                | -                | -         |    -3.78 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            2 |     3682 | 2024-03-10 | VP.Prodigy      | W   | 0.217      | -            | -                | -                | -         |     2.96 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            1 |     3810 | 2024-03-05 | ARCRED          | L   | 0.185      | -            | -                | -                | -         |    -3.37 | buster, lattykk, neaLaN, oz1k, Ryujin   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,585.28)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.731 | $5,000.00      | $3,654.17       |
| 2024-05-09 |      0.616 | $8,000.00      | $4,931.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
