### Roster Details<br />
Team Name: Perseverance<br />
Roster: CoJoMo, Gabe, mds, nooz, shutout<br />
Global Rank: [160](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  686.2<br />
<br />
Final Rank Value (686.2) = Starting Rank Value (736.4) + Head To Head Adjustments (-50.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.285[<sup>2</sup>](#table1)
- Opponent Network: 0.079[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.165<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.4
- 400 + ( ( 0.165 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 736.4


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
|           47 |      351 | 2024-07-24 | Victorum         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.28 | CoJoMo, Gabe, mds, nooz, shutout   |
|           46 |      469 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.52 | CoJoMo, Gabe, mds, nooz, shutout   |
|           45 |      603 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.48 | CoJoMo, Gabe, mds, shutout, xaler  |
|           44 |      607 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.77 | CoJoMo, Gabe, mds, shutout, xaler  |
|           43 |      667 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.61 | CoJoMo, Gabe, mds, shutout, xaler  |
|           42 |      673 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -17.05 | CoJoMo, Gabe, mds, shutout, xaler  |
|           41 |     1019 | 2024-06-14 | Akimbo           | L   | 0.866      | -            | -                | -                | -         |   -11.63 | CoJoMo, Gabe, mds, shutout, xaler  |
|           40 |     1471 | 2024-06-04 | Mythic           | L   | 0.799      | -            | -                | -                | -         |   -10.62 | CoJoMo, Gabe, Louie, mds, shutout  |
|           39 |     1772 | 2024-05-22 | BOSS             | L   | 0.714      | -            | -                | -                | -         |   -10.79 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           38 |     1776 | 2024-05-22 | BOSS             | W   | 0.714      | 0.477        | 0.014 (0.005)    | 0.333 (0.113)    | 0 (0.000) |    11.94 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           37 |     1821 | 2024-05-21 | NRG              | W   | 0.707      | 0.477        | 0.020 (0.007)    | 0.521 (0.176)    | 0 (0.000) |    16.48 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           36 |     1823 | 2024-05-21 | NRG              | L   | 0.707      | -            | -                | -                | -         |    -5.71 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           35 |     1856 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.701      | -            | -                | -                | -         |   -12.23 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           34 |     1860 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.700      | 0.477        | 0.003 (0.001)    | 0.274 (0.091)    | 0 (0.000) |     9.97 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           33 |     2023 | 2024-05-15 | Mythic           | L   | 0.667      | -            | -                | -                | -         |    -9.64 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           32 |     2029 | 2024-05-15 | Mythic           | W   | 0.667      | 0.477        | 0.010 (0.003)    | 0.300 (0.096)    | 0 (0.000) |    11.65 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           31 |     2090 | 2024-05-14 | Elevate          | L   | 0.660      | -            | -                | -                | -         |    -4.39 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           30 |     2093 | 2024-05-14 | Elevate          | L   | 0.660      | -            | -                | -                | -         |    -4.57 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           29 |     2147 | 2024-05-12 | NRG              | L   | 0.647      | -            | -                | -                | -         |    -6.33 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           28 |     2154 | 2024-05-12 | Mythic           | W   | 0.646      | 0.270        | 0.010 (0.002)    | 0.300 (0.052)    | 0 (0.000) |    11.29 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           27 |     2174 | 2024-05-11 | BOSS             | W   | 0.640      | 0.270        | 0.014 (0.002)    | 0.333 (0.058)    | 0 (0.000) |    12.02 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           26 |     2177 | 2024-05-11 | NRG              | L   | 0.639      | -            | -                | -                | -         |    -6.31 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           25 |     2180 | 2024-05-11 | Party Astronauts | W   | 0.639      | 0.270        | 0.041 (0.007)    | 0.532 (0.092)    | 0 (0.000) |    15.58 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           24 |     2243 | 2024-05-08 | Nouns            | L   | 0.621      | -            | -                | -                | -         |    -4.67 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           23 |     2245 | 2024-05-08 | Nouns            | L   | 0.620      | -            | -                | -                | -         |    -4.87 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           22 |     2754 | 2024-04-17 | Nouns            | L   | 0.480      | -            | -                | -                | -         |    -3.64 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           21 |     2906 | 2024-04-10 | MIGHT            | L   | 0.434      | -            | -                | -                | -         |   -10.55 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           20 |     2911 | 2024-04-10 | MIGHT            | W   | 0.434      | -            | -                | -                | 0 (0.000) |     3.13 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           19 |     3089 | 2024-04-04 | Carpe Diem       | W   | 0.394      | 0.477        | 0.005 (0.001)    | -                | 0 (0.000) |     5.02 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           18 |     3094 | 2024-04-04 | Carpe Diem       | W   | 0.394      | 0.477        | 0.005 (0.001)    | -                | -         |     5.20 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           17 |     3137 | 2024-04-03 | Limitless        | W   | 0.388      | 0.477        | -                | 0.168 (0.031)    | -         |     4.81 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           16 |     3139 | 2024-04-03 | Limitless        | W   | 0.387      | 0.477        | -                | 0.168 (0.031)    | -         |     4.96 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           15 |     3187 | 2024-04-02 | Party Astronauts | L   | 0.381      | -            | -                | -                | -         |    -2.89 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           14 |     3191 | 2024-04-02 | BOSS             | L   | 0.380      | -            | -                | -                | -         |    -4.85 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           13 |     3274 | 2024-03-27 | M80              | L   | 0.340      | -            | -                | -                | -         |    -0.66 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           12 |     3280 | 2024-03-27 | M80              | L   | 0.340      | -            | -                | -                | -         |    -0.67 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           11 |     3399 | 2024-03-20 | LAG              | W   | 0.294      | 0.477        | 0.012 (0.002)    | 0.341 (0.048)    | -         |     6.23 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|           10 |     3401 | 2024-03-20 | LAG              | L   | 0.294      | -            | -                | -                | -         |    -3.07 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            9 |     3417 | 2024-03-19 | Party Astronauts | L   | 0.288      | -            | -                | -                | -         |    -2.19 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            8 |     3419 | 2024-03-19 | Party Astronauts | L   | 0.287      | -            | -                | -                | -         |    -2.23 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            7 |     3514 | 2024-03-14 | Wildcard         | L   | 0.254      | -            | -                | -                | -         |    -2.16 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            6 |     3517 | 2024-03-14 | Wildcard         | L   | 0.254      | -            | -                | -                | -         |    -2.19 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            5 |     3546 | 2024-03-13 | Mythic           | W   | 0.246      | -            | -                | -                | -         |     4.44 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            4 |     3588 | 2024-03-12 | bubibabu         | W   | 0.241      | -            | -                | -                | -         |     1.01 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            3 |     4014 | 2024-02-22 | MIGHT            | L   | 0.113      | -            | -                | -                | -         |    -2.72 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            2 |     4257 | 2024-02-13 | Take Flyte       | L   | 0.054      | -            | -                | -                | -         |    -0.92 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            1 |     4260 | 2024-02-13 | Take Flyte       | W   | 0.054      | -            | -                | -                | -         |     0.79 | BeaKie, CoJoMo, Gabe, mds, shutout |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,333.78)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
