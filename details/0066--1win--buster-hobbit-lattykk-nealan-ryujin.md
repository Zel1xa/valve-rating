### Roster Details<br />
Team Name: 1WIN<br />
Roster: buster, HObbit, lattykk, neaLaN, Ryujin<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  966.6<br />
<br />
Final Rank Value (966.6) = Starting Rank Value (893.2) + Head To Head Adjustments (73.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.397[<sup>2</sup>](#table1)
- Opponent Network: 0.172[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.239<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 893.2
- 400 + ( ( 0.239 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 893.2


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
|           41 |       48 | 2024-07-31 | Into the Breach | W   | 1.000      | 0.435        | -                | 0.231 (0.100)    | 0 (0.000) |     6.69 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           40 |       91 | 2024-07-30 | ECLOT           | L   | 1.000      | -            | -                | -                | -         |   -13.59 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           39 |      114 | 2024-07-29 | CYBERSHOKE      | L   | 1.000      | -            | -                | -                | -         |   -17.38 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           38 |      125 | 2024-07-29 | NOM             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.11 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           37 |      164 | 2024-07-28 | TSM             | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | 0 (0.000) |    16.41 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           36 |      177 | 2024-07-27 | CPH Wolves      | W   | 1.000      | 0.435        | -                | 0.360 (0.156)    | 0 (0.000) |    11.38 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           35 |      274 | 2024-07-24 | BC.Game         | W   | 1.000      | 0.435        | -                | 0.154 (0.067)    | 0 (0.000) |     6.06 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           34 |     1179 | 2024-06-08 | Monte           | L   | 0.841      | -            | -                | -                | -         |   -11.42 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           33 |     1180 | 2024-06-08 | Quixal          | W   | 0.841      | -            | -                | -                | 0 (0.000) |     1.07 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           32 |     1190 | 2024-06-08 | AMKAL           | L   | 0.840      | -            | -                | -                | -         |    -6.03 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           31 |     1320 | 2024-06-06 | FAVBET          | L   | 0.827      | -            | -                | -                | -         |   -18.91 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           30 |     1502 | 2024-06-01 | Insilio         | L   | 0.794      | -            | -                | -                | -         |   -14.27 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           29 |     1560 | 2024-05-30 | V1dar           | W   | 0.781      | -            | -                | -                | 0 (0.000) |     1.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           28 |     1649 | 2024-05-26 | 9 Pandas        | L   | 0.754      | -            | -                | -                | -         |   -10.25 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           27 |     1674 | 2024-05-25 | FURIA           | W   | 0.746      | 0.435        | 0.286 (0.093)    | 0.495 (0.160)    | 0 (0.000) |    22.79 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           26 |     1698 | 2024-05-23 | ECSTATIC        | W   | 0.735      | -            | -                | -                | 0 (0.000) |     0.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           25 |     1897 | 2024-05-18 | SINNERS         | W   | 0.701      | 0.435        | 0.038 (0.012)    | 0.768 (0.234)    | 0 (0.000) |    12.64 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           24 |     1978 | 2024-05-16 | Zero Tenacity   | W   | 0.686      | 0.435        | 0.139 (0.041)    | 1.000 (0.298)    | -         |    14.01 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           23 |     2109 | 2024-05-13 | Permitta        | W   | 0.668      | 0.435        | 0.024 (0.007)    | 0.801 (0.233)    | -         |     9.11 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           22 |     2211 | 2024-05-09 | Sashi           | L   | 0.640      | -            | -                | -                | -         |    -3.80 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           21 |     2239 | 2024-05-08 | Nemiga          | W   | 0.633      | 0.396        | 0.324 (0.081)    | 0.697 (0.175)    | -         |    15.57 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           20 |     2249 | 2024-05-07 | BLEED           | W   | 0.628      | 0.396        | 0.095 (0.024)    | 0.407 (0.101)    | -         |    13.51 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           19 |     2297 | 2024-05-05 | ex-Guild Eagles | W   | 0.613      | -            | -                | -                | -         |     7.69 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           18 |     2342 | 2024-05-02 | Soda            | W   | 0.594      | -            | -                | -                | -         |     2.41 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           17 |     2350 | 2024-05-02 | 500             | W   | 0.593      | -            | -                | -                | -         |     5.38 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           16 |     2415 | 2024-04-29 | ECLOT           | L   | 0.574      | -            | -                | -                | -         |    -4.67 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           15 |     2417 | 2024-04-29 | SINNERS         | L   | 0.574      | -            | -                | -                | -         |    -6.37 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           14 |     2433 | 2024-04-28 | Sangal          | L   | 0.568      | -            | -                | -                | -         |    -4.66 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           13 |     2466 | 2024-04-27 | Nemiga          | L   | 0.560      | -            | -                | -                | -         |    -3.87 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           12 |     2514 | 2024-04-25 | Permitta        | W   | 0.547      | 0.435        | 0.024 (0.006)    | 0.801 (0.191)    | -         |     9.72 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           11 |     2555 | 2024-04-23 | HAVU            | W   | 0.534      | -            | -                | -                | -         |     3.90 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           10 |     2596 | 2024-04-21 | Nemiga          | L   | 0.520      | -            | -                | -                | -         |    -3.46 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            9 |     2618 | 2024-04-20 | Portugal        | W   | 0.515      | -            | -                | -                | -         |     3.66 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            8 |     2794 | 2024-04-16 | ENCE Academy    | W   | 0.487      | -            | -                | -                | -         |     4.44 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            7 |     2822 | 2024-04-15 | Lazer Cats      | W   | 0.479      | -            | -                | -                | -         |     1.63 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            6 |     2987 | 2024-04-09 | Aurora          | L   | 0.441      | -            | -                | -                | -         |    -0.20 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            5 |     3008 | 2024-04-08 | 9 Pandas        | W   | 0.435      | 0.143        | 0.083 (0.005)    | -                | -         |     8.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            4 |     3020 | 2024-04-08 | Aurora          | W   | 0.434      | 0.143        | 0.432 (0.027)    | -                | -         |    13.49 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            3 |     3630 | 2024-03-11 | Insilio         | L   | 0.248      | -            | -                | -                | -         |    -3.84 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            2 |     3652 | 2024-03-10 | VP.Prodigy      | W   | 0.241      | -            | -                | -                | -         |     3.62 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            1 |     3781 | 2024-03-05 | ARCRED          | L   | 0.209      | -            | -                | -                | -         |    -3.61 | buster, lattykk, neaLaN, oz1k, Ryujin   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,892.22)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.754 | $5,000.00      | $3,772.22       |
| 2024-05-09 |      0.640 | $8,000.00      | $5,120.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
