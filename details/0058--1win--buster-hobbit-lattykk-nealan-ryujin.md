### Roster Details<br />
Team Name: 1WIN<br />
Roster: buster, HObbit, lattykk, neaLaN, Ryujin<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1010.4<br />
<br />
Final Rank Value (1010.4) = Starting Rank Value (920.0) + Head To Head Adjustments (90.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.409[<sup>2</sup>](#table1)
- Opponent Network: 0.220[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.254<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 920.0
- 400 + ( ( 0.254 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 920.0


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
|           45 |        0 | 2024-08-04 | TSM             | W   | 1.000      | 0.426        | 0.040 (0.017)    | 0.394 (0.168)    | 0 (0.000) |    14.31 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           44 |       15 | 2024-08-04 | Young Ninjas    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.55 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           43 |       33 | 2024-08-03 | MOUZ NXT        | W   | 1.000      | 0.435        | 0.139 (0.060)    | 1.000 (0.435)    | 0 (0.000) |    21.28 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           42 |       54 | 2024-08-03 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -17.23 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           41 |      168 | 2024-07-31 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.50 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           40 |      211 | 2024-07-30 | ECLOT           | L   | 1.000      | -            | -                | -                | -         |   -12.22 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           39 |      233 | 2024-07-29 | CYBERSHOKE      | L   | 1.000      | -            | -                | -                | -         |   -18.22 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           38 |      244 | 2024-07-29 | NOM             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.83 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           37 |      283 | 2024-07-28 | TSM             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.60 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           36 |      296 | 2024-07-27 | CPH Wolves      | W   | 1.000      | 0.435        | -                | 0.365 (0.158)    | 0 (0.000) |    10.43 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           35 |      393 | 2024-07-24 | BC.Game         | W   | 1.000      | 0.435        | 0.022 (0.009)    | 0.315 (0.137)    | 0 (0.000) |    12.13 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           34 |     1288 | 2024-06-08 | Monte           | L   | 0.820      | -            | -                | -                | -         |   -11.52 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           33 |     1289 | 2024-06-08 | Quixal          | W   | 0.820      | -            | -                | -                | 0 (0.000) |     0.96 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           32 |     1299 | 2024-06-08 | AMKAL           | L   | 0.819      | -            | -                | -                | -         |    -6.30 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           31 |     1420 | 2024-06-06 | FAVBET          | L   | 0.806      | -            | -                | -                | -         |   -19.03 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           30 |     1598 | 2024-06-01 | Insilio         | L   | 0.773      | -            | -                | -                | -         |   -14.59 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           29 |     1656 | 2024-05-30 | V1dar           | W   | 0.760      | -            | -                | -                | 0 (0.000) |     1.60 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           28 |     1743 | 2024-05-26 | 9 Pandas        | L   | 0.733      | -            | -                | -                | -         |   -10.71 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           27 |     1768 | 2024-05-25 | FURIA           | W   | 0.726      | 0.435        | 0.284 (0.090)    | 0.490 (0.155)    | -         |    22.07 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           26 |     1792 | 2024-05-23 | ECSTATIC        | W   | 0.714      | -            | -                | -                | -         |     0.73 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           25 |     1966 | 2024-05-18 | SINNERS         | W   | 0.680      | 0.435        | 0.037 (0.011)    | 0.797 (0.235)    | -         |    13.14 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           24 |     2046 | 2024-05-16 | Zero Tenacity   | W   | 0.666      | 0.435        | 0.137 (0.040)    | 1.000 (0.289)    | -         |    13.20 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           23 |     2168 | 2024-05-13 | Permitta        | W   | 0.647      | 0.435        | 0.024 (0.007)    | 0.876 (0.246)    | -         |     8.42 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           22 |     2270 | 2024-05-09 | Sashi           | L   | 0.619      | -            | -                | -                | -         |    -4.08 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           21 |     2296 | 2024-05-08 | Nemiga          | W   | 0.612      | 0.396        | 0.317 (0.077)    | 0.734 (0.178)    | -         |    14.98 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           20 |     2306 | 2024-05-07 | BLEED           | W   | 0.607      | 0.396        | 0.091 (0.022)    | -                | -         |    12.62 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           19 |     2354 | 2024-05-05 | ex-Guild Eagles | W   | 0.592      | -            | -                | -                | -         |     6.68 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           18 |     2398 | 2024-05-02 | Soda            | W   | 0.574      | -            | -                | -                | -         |     0.84 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           17 |     2406 | 2024-05-02 | 500             | W   | 0.573      | -            | -                | -                | -         |     4.24 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           16 |     2469 | 2024-04-29 | ECLOT           | L   | 0.553      | -            | -                | -                | -         |    -3.40 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           15 |     2471 | 2024-04-29 | SINNERS         | L   | 0.553      | -            | -                | -                | -         |    -5.41 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           14 |     2487 | 2024-04-28 | Sangal          | L   | 0.547      | -            | -                | -                | -         |    -4.74 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           13 |     2519 | 2024-04-27 | Nemiga          | L   | 0.539      | -            | -                | -                | -         |    -3.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           12 |     2568 | 2024-04-25 | Permitta        | W   | 0.527      | 0.435        | -                | 0.876 (0.200)    | -         |     8.72 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           11 |     2607 | 2024-04-23 | HAVU            | W   | 0.513      | -            | -                | -                | -         |     3.30 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           10 |     2646 | 2024-04-21 | Nemiga          | L   | 0.499      | -            | -                | -                | -         |    -3.57 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            9 |     2666 | 2024-04-20 | Portugal        | W   | 0.494      | -            | -                | -                | -         |     3.05 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            8 |     2838 | 2024-04-16 | ENCE Academy    | W   | 0.466      | -            | -                | -                | -         |     3.56 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            7 |     2866 | 2024-04-15 | Lazer Cats      | W   | 0.458      | -            | -                | -                | -         |     1.37 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            6 |     3030 | 2024-04-09 | Aurora          | L   | 0.420      | -            | -                | -                | -         |    -0.23 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            5 |     3051 | 2024-04-08 | 9 Pandas        | W   | 0.414      | -            | -                | -                | -         |     7.87 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            4 |     3063 | 2024-04-08 | Aurora          | W   | 0.413      | 0.143        | 0.423 (0.025)    | -                | -         |    12.80 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            3 |     3655 | 2024-03-11 | Insilio         | L   | 0.227      | -            | -                | -                | -         |    -3.82 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            2 |     3677 | 2024-03-10 | VP.Prodigy      | W   | 0.220      | -            | -                | -                | -         |     2.99 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            1 |     3805 | 2024-03-05 | ARCRED          | L   | 0.188      | -            | -                | -                | -         |    -3.42 | buster, lattykk, neaLaN, oz1k, Ryujin   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,620.19)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.734 | $5,000.00      | $3,667.59       |
| 2024-05-09 |      0.619 | $8,000.00      | $4,952.59       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
