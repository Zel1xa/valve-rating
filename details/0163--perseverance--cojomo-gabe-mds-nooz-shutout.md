### Roster Details<br />
Team Name: Perseverance<br />
Roster: CoJoMo, Gabe, mds, nooz, shutout<br />
Global Rank: [163](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [45]( ../standings_americas.md)<br />
<br />
Final Rank Value:  687.5<br />
<br />
Final Rank Value (687.5) = Starting Rank Value (741.5) + Head To Head Adjustments (-54.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.296[<sup>1</sup>](#table2)
- Bounty Collected: 0.286[<sup>2</sup>](#table1)
- Opponent Network: 0.082[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.166<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 741.5
- 400 + ( ( 0.166 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 741.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |      270 | 2024-07-24 | Victorum         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.25 | CoJoMo, Gabe, mds, nooz, shutout   |
|           47 |      390 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.52 | CoJoMo, Gabe, mds, nooz, shutout   |
|           46 |      531 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.51 | CoJoMo, Gabe, mds, shutout, xaler  |
|           45 |      535 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.80 | CoJoMo, Gabe, mds, shutout, xaler  |
|           44 |      595 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.47 | CoJoMo, Gabe, mds, shutout, xaler  |
|           43 |      601 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -16.90 | CoJoMo, Gabe, mds, shutout, xaler  |
|           42 |      947 | 2024-06-14 | Akimbo           | L   | 0.881      | -            | -                | -                | -         |   -11.59 | CoJoMo, Gabe, mds, shutout, xaler  |
|           41 |     1413 | 2024-06-04 | Mythic           | L   | 0.814      | -            | -                | -                | -         |   -10.60 | CoJoMo, Gabe, Louie, mds, shutout  |
|           40 |     1717 | 2024-05-22 | BOSS             | L   | 0.729      | -            | -                | -                | -         |   -11.10 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           39 |     1721 | 2024-05-22 | BOSS             | W   | 0.729      | 0.477        | 0.014 (0.005)    | 0.334 (0.116)    | 0 (0.000) |    12.10 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           38 |     1776 | 2024-05-21 | NRG              | W   | 0.722      | 0.477        | 0.020 (0.007)    | 0.519 (0.179)    | 0 (0.000) |    17.11 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           37 |     1779 | 2024-05-21 | NRG              | L   | 0.722      | -            | -                | -                | -         |    -5.53 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           36 |     1817 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.716      | -            | -                | -                | -         |   -12.43 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           35 |     1821 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.715      | 0.477        | 0.003 (0.001)    | 0.305 (0.104)    | 0 (0.000) |    10.24 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           34 |     1858 | 2024-05-19 | NRG              | L   | 0.708      | -            | -                | -                | -         |    -5.58 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           33 |     1994 | 2024-05-15 | Mythic           | L   | 0.682      | -            | -                | -                | -         |    -9.83 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           32 |     2000 | 2024-05-15 | Mythic           | W   | 0.682      | 0.477        | 0.010 (0.003)    | 0.304 (0.099)    | 0 (0.000) |    11.93 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           31 |     2067 | 2024-05-14 | Elevate          | L   | 0.675      | -            | -                | -                | -         |    -4.42 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           30 |     2070 | 2024-05-14 | Elevate          | L   | 0.675      | -            | -                | -                | -         |    -4.61 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           29 |     2127 | 2024-05-12 | NRG              | L   | 0.662      | -            | -                | -                | -         |    -6.45 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           28 |     2134 | 2024-05-12 | Mythic           | W   | 0.661      | 0.270        | 0.010 (0.002)    | 0.304 (0.054)    | 0 (0.000) |    11.58 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           27 |     2154 | 2024-05-11 | BOSS             | W   | 0.655      | 0.270        | 0.014 (0.003)    | 0.334 (0.059)    | 0 (0.000) |    12.41 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           26 |     2157 | 2024-05-11 | NRG              | L   | 0.654      | -            | -                | -                | -         |    -6.43 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           25 |     2160 | 2024-05-11 | Party Astronauts | W   | 0.654      | 0.270        | 0.042 (0.007)    | 0.532 (0.094)    | 0 (0.000) |    16.02 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           24 |     2223 | 2024-05-08 | Nouns            | L   | 0.636      | -            | -                | -                | -         |    -4.74 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           23 |     2225 | 2024-05-08 | Nouns            | L   | 0.635      | -            | -                | -                | -         |    -4.94 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           22 |     2748 | 2024-04-17 | Nouns            | L   | 0.495      | -            | -                | -                | -         |    -3.72 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           21 |     2903 | 2024-04-10 | MIGHT            | L   | 0.449      | -            | -                | -                | -         |   -10.94 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           20 |     2908 | 2024-04-10 | MIGHT            | W   | 0.449      | -            | -                | -                | 0 (0.000) |     3.21 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           19 |     3086 | 2024-04-04 | Carpe Diem       | W   | 0.409      | 0.477        | 0.005 (0.001)    | -                | 0 (0.000) |     5.18 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           18 |     3091 | 2024-04-04 | Carpe Diem       | W   | 0.409      | 0.477        | 0.005 (0.001)    | -                | -         |     5.37 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           17 |     3135 | 2024-04-03 | Limitless        | W   | 0.403      | 0.477        | -                | 0.170 (0.033)    | -         |     4.95 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           16 |     3137 | 2024-04-03 | Limitless        | W   | 0.402      | 0.477        | -                | 0.170 (0.033)    | -         |     5.12 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           15 |     3192 | 2024-04-02 | Party Astronauts | L   | 0.396      | -            | -                | -                | -         |    -2.95 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           14 |     3196 | 2024-04-02 | BOSS             | L   | 0.395      | -            | -                | -                | -         |    -4.93 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           13 |     3279 | 2024-03-27 | M80              | L   | 0.355      | -            | -                | -                | -         |    -0.66 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           12 |     3285 | 2024-03-27 | M80              | L   | 0.355      | -            | -                | -                | -         |    -0.66 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           11 |     3409 | 2024-03-20 | LAG              | W   | 0.309      | 0.477        | 0.013 (0.002)    | 0.371 (0.055)    | -         |     6.61 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|           10 |     3411 | 2024-03-20 | LAG              | L   | 0.309      | -            | -                | -                | -         |    -3.17 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            9 |     3427 | 2024-03-19 | Party Astronauts | L   | 0.303      | -            | -                | -                | -         |    -2.26 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            8 |     3429 | 2024-03-19 | Party Astronauts | L   | 0.302      | -            | -                | -                | -         |    -2.30 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            7 |     3524 | 2024-03-14 | Wildcard         | L   | 0.269      | -            | -                | -                | -         |    -2.26 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            6 |     3527 | 2024-03-14 | Wildcard         | L   | 0.269      | -            | -                | -                | -         |    -2.30 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            5 |     3560 | 2024-03-13 | Mythic           | W   | 0.261      | -            | -                | -                | -         |     4.73 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            4 |     3603 | 2024-03-12 | bubibabu         | W   | 0.256      | -            | -                | -                | -         |     1.05 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            3 |     4044 | 2024-02-22 | MIGHT            | L   | 0.128      | -            | -                | -                | -         |    -3.09 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            2 |     4290 | 2024-02-13 | Take Flyte       | L   | 0.069      | -            | -                | -                | -         |    -1.18 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            1 |     4293 | 2024-02-13 | Take Flyte       | W   | 0.069      | -            | -                | -                | -         |     1.01 | BeaKie, CoJoMo, Gabe, mds, shutout |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,357.78)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
