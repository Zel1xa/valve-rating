### Roster Details<br />
Team Name: 1WIN<br />
Roster: buster, HObbit, lattykk, neaLaN, Ryujin<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  967.5<br />
<br />
Final Rank Value (967.5) = Starting Rank Value (894.1) + Head To Head Adjustments (73.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.396[<sup>2</sup>](#table1)
- Opponent Network: 0.175[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 894.1
- 400 + ( ( 0.240 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 894.1


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
|           41 |       52 | 2024-07-31 | Into the Breach | W   | 1.000      | 0.435        | -                | 0.270 (0.117)    | 0 (0.000) |     7.17 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           40 |       95 | 2024-07-30 | ECLOT           | L   | 1.000      | -            | -                | -                | -         |   -13.65 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           39 |      118 | 2024-07-29 | CYBERSHOKE      | L   | 1.000      | -            | -                | -                | -         |   -17.43 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           38 |      129 | 2024-07-29 | NOM             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.10 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           37 |      168 | 2024-07-28 | TSM             | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | 0 (0.000) |    16.37 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           36 |      181 | 2024-07-27 | CPH Wolves      | W   | 1.000      | 0.435        | -                | 0.360 (0.156)    | 0 (0.000) |    11.34 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           35 |      278 | 2024-07-24 | BC.Game         | W   | 1.000      | 0.435        | -                | 0.193 (0.084)    | 0 (0.000) |     6.67 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           34 |     1183 | 2024-06-08 | Monte           | L   | 0.840      | -            | -                | -                | -         |   -11.43 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           33 |     1184 | 2024-06-08 | Quixal          | W   | 0.840      | -            | -                | -                | 0 (0.000) |     1.07 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           32 |     1194 | 2024-06-08 | AMKAL           | L   | 0.839      | -            | -                | -                | -         |    -6.03 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           31 |     1324 | 2024-06-06 | FAVBET          | L   | 0.826      | -            | -                | -                | -         |   -18.90 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           30 |     1506 | 2024-06-01 | Insilio         | L   | 0.793      | -            | -                | -                | -         |   -14.28 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           29 |     1564 | 2024-05-30 | V1dar           | W   | 0.779      | -            | -                | -                | 0 (0.000) |     1.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           28 |     1653 | 2024-05-26 | 9 Pandas        | L   | 0.752      | -            | -                | -                | -         |   -10.27 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           27 |     1678 | 2024-05-25 | FURIA           | W   | 0.745      | 0.435        | 0.286 (0.093)    | 0.494 (0.160)    | 0 (0.000) |    22.75 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           26 |     1702 | 2024-05-23 | ECSTATIC        | W   | 0.733      | -            | -                | -                | 0 (0.000) |     0.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           25 |     1901 | 2024-05-18 | SINNERS         | W   | 0.699      | 0.435        | 0.038 (0.012)    | 0.768 (0.234)    | 0 (0.000) |    12.58 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           24 |     1982 | 2024-05-16 | Zero Tenacity   | W   | 0.685      | 0.435        | 0.139 (0.041)    | 1.000 (0.298)    | -         |    13.96 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           23 |     2113 | 2024-05-13 | Permitta        | W   | 0.667      | 0.435        | 0.024 (0.007)    | 0.801 (0.232)    | -         |     9.06 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           22 |     2215 | 2024-05-09 | Sashi           | L   | 0.639      | -            | -                | -                | -         |    -3.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           21 |     2243 | 2024-05-08 | Nemiga          | W   | 0.631      | 0.396        | 0.324 (0.081)    | 0.697 (0.174)    | -         |    15.51 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           20 |     2253 | 2024-05-07 | BLEED           | W   | 0.627      | 0.396        | 0.095 (0.024)    | 0.406 (0.101)    | -         |    13.44 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           19 |     2301 | 2024-05-05 | ex-Guild Eagles | W   | 0.612      | -            | -                | -                | -         |     7.63 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           18 |     2346 | 2024-05-02 | Soda            | W   | 0.593      | -            | -                | -                | -         |     2.40 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           17 |     2354 | 2024-05-02 | 500             | W   | 0.592      | -            | -                | -                | -         |     5.34 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           16 |     2419 | 2024-04-29 | ECLOT           | L   | 0.573      | -            | -                | -                | -         |    -4.69 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           15 |     2421 | 2024-04-29 | SINNERS         | L   | 0.572      | -            | -                | -                | -         |    -6.39 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           14 |     2437 | 2024-04-28 | Sangal          | L   | 0.567      | -            | -                | -                | -         |    -4.67 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           13 |     2470 | 2024-04-27 | Nemiga          | L   | 0.559      | -            | -                | -                | -         |    -3.89 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           12 |     2518 | 2024-04-25 | Permitta        | W   | 0.546      | 0.435        | 0.024 (0.006)    | 0.801 (0.190)    | -         |     9.66 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           11 |     2559 | 2024-04-23 | HAVU            | W   | 0.532      | -            | -                | -                | -         |     3.87 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           10 |     2600 | 2024-04-21 | Nemiga          | L   | 0.518      | -            | -                | -                | -         |    -3.48 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            9 |     2622 | 2024-04-20 | Portugal        | W   | 0.513      | -            | -                | -                | -         |     3.63 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            8 |     2798 | 2024-04-16 | ENCE Academy    | W   | 0.486      | -            | -                | -                | -         |     4.40 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            7 |     2826 | 2024-04-15 | Lazer Cats      | W   | 0.477      | -            | -                | -                | -         |     1.62 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            6 |     2991 | 2024-04-09 | Aurora          | L   | 0.439      | -            | -                | -                | -         |    -0.20 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            5 |     3012 | 2024-04-08 | 9 Pandas        | W   | 0.433      | 0.143        | 0.083 (0.005)    | -                | -         |     8.76 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            4 |     3024 | 2024-04-08 | Aurora          | W   | 0.432      | 0.143        | 0.431 (0.027)    | -                | -         |    13.44 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            3 |     3634 | 2024-03-11 | Insilio         | L   | 0.246      | -            | -                | -                | -         |    -3.83 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            2 |     3656 | 2024-03-10 | VP.Prodigy      | W   | 0.239      | -            | -                | -                | -         |     3.58 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            1 |     3785 | 2024-03-05 | ARCRED          | L   | 0.207      | -            | -                | -                | -         |    -3.60 | buster, lattykk, neaLaN, oz1k, Ryujin   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,874.17)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.753 | $5,000.00      | $3,765.28       |
| 2024-05-09 |      0.639 | $8,000.00      | $5,108.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
