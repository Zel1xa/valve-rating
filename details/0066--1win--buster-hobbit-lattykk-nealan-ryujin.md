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
|           41 |       55 | 2024-07-31 | Into the Breach | W   | 1.000      | 0.435        | -                | 0.270 (0.117)    | 0 (0.000) |     7.17 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           40 |       97 | 2024-07-30 | ECLOT           | L   | 1.000      | -            | -                | -                | -         |   -13.65 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           39 |      120 | 2024-07-29 | CYBERSHOKE      | L   | 1.000      | -            | -                | -                | -         |   -17.42 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           38 |      132 | 2024-07-29 | NOM             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.10 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           37 |      170 | 2024-07-28 | TSM             | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | 0 (0.000) |    16.38 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           36 |      183 | 2024-07-27 | CPH Wolves      | W   | 1.000      | 0.435        | -                | 0.360 (0.156)    | 0 (0.000) |    11.34 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           35 |      280 | 2024-07-24 | BC.Game         | W   | 1.000      | 0.435        | -                | 0.193 (0.084)    | 0 (0.000) |     6.68 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           34 |     1185 | 2024-06-08 | Monte           | L   | 0.840      | -            | -                | -                | -         |   -11.42 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           33 |     1186 | 2024-06-08 | Quixal          | W   | 0.839      | -            | -                | -                | 0 (0.000) |     1.07 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           32 |     1196 | 2024-06-08 | AMKAL           | L   | 0.839      | -            | -                | -                | -         |    -6.03 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           31 |     1326 | 2024-06-06 | FAVBET          | L   | 0.825      | -            | -                | -                | -         |   -18.89 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           30 |     1508 | 2024-06-01 | Insilio         | L   | 0.792      | -            | -                | -                | -         |   -14.28 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           29 |     1566 | 2024-05-30 | V1dar           | W   | 0.779      | -            | -                | -                | 0 (0.000) |     1.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           28 |     1655 | 2024-05-26 | 9 Pandas        | L   | 0.752      | -            | -                | -                | -         |   -10.26 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           27 |     1680 | 2024-05-25 | FURIA           | W   | 0.745      | 0.435        | 0.286 (0.093)    | 0.494 (0.160)    | 0 (0.000) |    22.74 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           26 |     1704 | 2024-05-23 | ECSTATIC        | W   | 0.733      | -            | -                | -                | 0 (0.000) |     0.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           25 |     1903 | 2024-05-18 | SINNERS         | W   | 0.699      | 0.435        | 0.038 (0.012)    | 0.768 (0.233)    | 0 (0.000) |    12.58 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           24 |     1984 | 2024-05-16 | Zero Tenacity   | W   | 0.685      | 0.435        | 0.139 (0.041)    | 1.000 (0.298)    | -         |    13.97 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           23 |     2115 | 2024-05-13 | Permitta        | W   | 0.666      | 0.435        | 0.024 (0.007)    | 0.801 (0.232)    | -         |     9.02 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           22 |     2217 | 2024-05-09 | Sashi           | L   | 0.638      | -            | -                | -                | -         |    -3.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           21 |     2245 | 2024-05-08 | Nemiga          | W   | 0.631      | 0.396        | 0.324 (0.081)    | 0.697 (0.174)    | -         |    15.50 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           20 |     2255 | 2024-05-07 | BLEED           | W   | 0.626      | 0.396        | 0.095 (0.024)    | 0.406 (0.101)    | -         |    13.43 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           19 |     2303 | 2024-05-05 | ex-Guild Eagles | W   | 0.611      | -            | -                | -                | -         |     7.63 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           18 |     2348 | 2024-05-02 | Soda            | W   | 0.593      | -            | -                | -                | -         |     2.40 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           17 |     2356 | 2024-05-02 | 500             | W   | 0.592      | -            | -                | -                | -         |     5.34 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           16 |     2421 | 2024-04-29 | ECLOT           | L   | 0.573      | -            | -                | -                | -         |    -4.69 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           15 |     2423 | 2024-04-29 | SINNERS         | L   | 0.572      | -            | -                | -                | -         |    -6.38 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           14 |     2439 | 2024-04-28 | Sangal          | L   | 0.566      | -            | -                | -                | -         |    -4.66 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           13 |     2472 | 2024-04-27 | Nemiga          | L   | 0.558      | -            | -                | -                | -         |    -3.89 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           12 |     2520 | 2024-04-25 | Permitta        | W   | 0.546      | 0.435        | 0.024 (0.006)    | 0.801 (0.190)    | -         |     9.61 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           11 |     2561 | 2024-04-23 | HAVU            | W   | 0.532      | -            | -                | -                | -         |     3.87 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           10 |     2602 | 2024-04-21 | Nemiga          | L   | 0.518      | -            | -                | -                | -         |    -3.48 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            9 |     2624 | 2024-04-20 | Portugal        | W   | 0.513      | -            | -                | -                | -         |     3.62 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            8 |     2800 | 2024-04-16 | ENCE Academy    | W   | 0.486      | -            | -                | -                | -         |     4.40 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            7 |     2828 | 2024-04-15 | Lazer Cats      | W   | 0.477      | -            | -                | -                | -         |     1.62 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            6 |     2993 | 2024-04-09 | Aurora          | L   | 0.439      | -            | -                | -                | -         |    -0.20 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            5 |     3014 | 2024-04-08 | 9 Pandas        | W   | 0.433      | 0.143        | 0.083 (0.005)    | -                | -         |     8.76 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            4 |     3026 | 2024-04-08 | Aurora          | W   | 0.432      | 0.143        | 0.431 (0.027)    | -                | -         |    13.44 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            3 |     3636 | 2024-03-11 | Insilio         | L   | 0.246      | -            | -                | -                | -         |    -3.83 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            2 |     3658 | 2024-03-10 | VP.Prodigy      | W   | 0.239      | -            | -                | -                | -         |     3.58 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            1 |     3787 | 2024-03-05 | ARCRED          | L   | 0.207      | -            | -                | -                | -         |    -3.59 | buster, lattykk, neaLaN, oz1k, Ryujin   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,870.56)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.753 | $5,000.00      | $3,763.89       |
| 2024-05-09 |      0.638 | $8,000.00      | $5,106.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
