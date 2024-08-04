### Roster Details<br />
Team Name: 1WIN<br />
Roster: buster, HObbit, lattykk, neaLaN, Ryujin<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  950.1<br />
<br />
Final Rank Value (950.1) = Starting Rank Value (890.0) + Head To Head Adjustments (60.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.394[<sup>2</sup>](#table1)
- Opponent Network: 0.177[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 890.0
- 400 + ( ( 0.240 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 890.0


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
|           42 |       22 | 2024-08-03 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -16.12 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           41 |      134 | 2024-07-31 | Into the Breach | W   | 1.000      | 0.435        | -                | 0.235 (0.102)    | 0 (0.000) |     7.06 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           40 |      176 | 2024-07-30 | ECLOT           | L   | 1.000      | -            | -                | -                | -         |   -11.51 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           39 |      199 | 2024-07-29 | CYBERSHOKE      | L   | 1.000      | -            | -                | -                | -         |   -17.38 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           38 |      211 | 2024-07-29 | NOM             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.15 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           37 |      249 | 2024-07-28 | TSM             | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    16.48 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           36 |      262 | 2024-07-27 | CPH Wolves      | W   | 1.000      | 0.435        | -                | 0.363 (0.158)    | 0 (0.000) |    11.30 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           35 |      359 | 2024-07-24 | BC.Game         | W   | 1.000      | 0.435        | -                | 0.274 (0.119)    | 0 (0.000) |     7.12 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           34 |     1253 | 2024-06-08 | Monte           | L   | 0.825      | -            | -                | -                | -         |   -10.92 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           33 |     1254 | 2024-06-08 | Quixal          | W   | 0.825      | -            | -                | -                | 0 (0.000) |     1.07 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           32 |     1264 | 2024-06-08 | AMKAL           | L   | 0.824      | -            | -                | -                | -         |    -5.81 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           31 |     1385 | 2024-06-06 | FAVBET          | L   | 0.811      | -            | -                | -                | -         |   -18.62 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           30 |     1563 | 2024-06-01 | Insilio         | L   | 0.778      | -            | -                | -                | -         |   -14.01 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           29 |     1621 | 2024-05-30 | V1dar           | W   | 0.764      | -            | -                | -                | 0 (0.000) |     1.80 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           28 |     1708 | 2024-05-26 | 9 Pandas        | L   | 0.737      | -            | -                | -                | -         |    -9.98 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           27 |     1733 | 2024-05-25 | FURIA           | W   | 0.730      | 0.435        | 0.284 (0.090)    | 0.491 (0.156)    | 0 (0.000) |    22.28 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           26 |     1757 | 2024-05-23 | ECSTATIC        | W   | 0.718      | -            | -                | -                | 0 (0.000) |     0.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           25 |     1931 | 2024-05-18 | SINNERS         | W   | 0.684      | 0.435        | 0.037 (0.011)    | 0.758 (0.225)    | 0 (0.000) |    12.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           24 |     2011 | 2024-05-16 | Zero Tenacity   | W   | 0.670      | 0.435        | 0.137 (0.040)    | 1.000 (0.291)    | -         |    13.85 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           23 |     2133 | 2024-05-13 | Permitta        | W   | 0.652      | 0.435        | 0.024 (0.007)    | 0.876 (0.248)    | -         |     9.08 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           22 |     2235 | 2024-05-09 | Sashi           | L   | 0.624      | -            | -                | -                | -         |    -3.73 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           21 |     2261 | 2024-05-08 | Nemiga          | W   | 0.616      | 0.396        | 0.318 (0.078)    | 0.695 (0.170)    | -         |    15.24 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           20 |     2271 | 2024-05-07 | BLEED           | W   | 0.612      | 0.396        | 0.092 (0.022)    | 0.399 (0.097)    | -         |    13.29 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           19 |     2319 | 2024-05-05 | ex-Guild Eagles | W   | 0.597      | -            | -                | -                | -         |     7.41 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           18 |     2363 | 2024-05-02 | Soda            | W   | 0.578      | -            | -                | -                | -         |     0.96 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           17 |     2371 | 2024-05-02 | 500             | W   | 0.577      | -            | -                | -                | -         |     4.76 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           16 |     2434 | 2024-04-29 | ECLOT           | L   | 0.558      | -            | -                | -                | -         |    -3.09 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           15 |     2436 | 2024-04-29 | SINNERS         | L   | 0.557      | -            | -                | -                | -         |    -5.79 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           14 |     2452 | 2024-04-28 | Sangal          | L   | 0.552      | -            | -                | -                | -         |    -4.36 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           13 |     2484 | 2024-04-27 | Nemiga          | L   | 0.544      | -            | -                | -                | -         |    -3.70 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           12 |     2532 | 2024-04-25 | Permitta        | W   | 0.531      | 0.435        | 0.024 (0.005)    | 0.876 (0.202)    | -         |     9.39 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           11 |     2571 | 2024-04-23 | HAVU            | W   | 0.517      | -            | -                | -                | -         |     3.75 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           10 |     2610 | 2024-04-21 | Nemiga          | L   | 0.503      | -            | -                | -                | -         |    -3.46 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            9 |     2630 | 2024-04-20 | Portugal        | W   | 0.498      | -            | -                | -                | -         |     3.49 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            8 |     2802 | 2024-04-16 | ENCE Academy    | W   | 0.471      | -            | -                | -                | -         |     4.05 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            7 |     2830 | 2024-04-15 | Lazer Cats      | W   | 0.463      | -            | -                | -                | -         |     1.59 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            6 |     2994 | 2024-04-09 | Aurora          | L   | 0.424      | -            | -                | -                | -         |    -0.20 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            5 |     3015 | 2024-04-08 | 9 Pandas        | W   | 0.418      | 0.143        | 0.082 (0.005)    | -                | -         |     8.48 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            4 |     3027 | 2024-04-08 | Aurora          | W   | 0.417      | 0.143        | 0.424 (0.025)    | -                | -         |    12.97 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            3 |     3618 | 2024-03-11 | Insilio         | L   | 0.231      | -            | -                | -                | -         |    -3.61 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            2 |     3640 | 2024-03-10 | VP.Prodigy      | W   | 0.224      | -            | -                | -                | -         |     3.34 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            1 |     3768 | 2024-03-05 | ARCRED          | L   | 0.192      | -            | -                | -                | -         |    -3.25 | buster, lattykk, neaLaN, oz1k, Ryujin   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,679.17)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.738 | $5,000.00      | $3,690.28       |
| 2024-05-09 |      0.624 | $8,000.00      | $4,988.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
