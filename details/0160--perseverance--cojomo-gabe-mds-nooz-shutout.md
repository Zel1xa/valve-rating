### Roster Details<br />
Team Name: Perseverance<br />
Roster: CoJoMo, Gabe, mds, nooz, shutout<br />
Global Rank: [160](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  686.1<br />
<br />
Final Rank Value (686.1) = Starting Rank Value (736.2) + Head To Head Adjustments (-50.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.078[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.2
- 400 + ( ( 0.164 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 736.2


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
|           47 |      354 | 2024-07-24 | Victorum         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.28 | CoJoMo, Gabe, mds, nooz, shutout   |
|           46 |      472 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.52 | CoJoMo, Gabe, mds, nooz, shutout   |
|           45 |      606 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.48 | CoJoMo, Gabe, mds, shutout, xaler  |
|           44 |      610 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.77 | CoJoMo, Gabe, mds, shutout, xaler  |
|           43 |      670 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.61 | CoJoMo, Gabe, mds, shutout, xaler  |
|           42 |      676 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -17.05 | CoJoMo, Gabe, mds, shutout, xaler  |
|           41 |     1023 | 2024-06-14 | Akimbo           | L   | 0.863      | -            | -                | -                | -         |   -11.60 | CoJoMo, Gabe, mds, shutout, xaler  |
|           40 |     1475 | 2024-06-04 | Mythic           | L   | 0.796      | -            | -                | -                | -         |   -10.58 | CoJoMo, Gabe, Louie, mds, shutout  |
|           39 |     1776 | 2024-05-22 | BOSS             | L   | 0.711      | -            | -                | -                | -         |   -10.75 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           38 |     1780 | 2024-05-22 | BOSS             | W   | 0.711      | 0.477        | 0.014 (0.005)    | 0.333 (0.113)    | 0 (0.000) |    11.89 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           37 |     1825 | 2024-05-21 | NRG              | W   | 0.704      | 0.477        | 0.020 (0.007)    | 0.521 (0.175)    | 0 (0.000) |    16.40 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           36 |     1827 | 2024-05-21 | NRG              | L   | 0.704      | -            | -                | -                | -         |    -5.69 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           35 |     1860 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.698      | -            | -                | -                | -         |   -12.17 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           34 |     1864 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.697      | 0.477        | 0.003 (0.001)    | 0.274 (0.091)    | 0 (0.000) |     9.94 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           33 |     2027 | 2024-05-15 | Mythic           | L   | 0.664      | -            | -                | -                | -         |    -9.60 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           32 |     2033 | 2024-05-15 | Mythic           | W   | 0.664      | 0.477        | 0.010 (0.003)    | 0.300 (0.095)    | 0 (0.000) |    11.60 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           31 |     2094 | 2024-05-14 | Elevate          | L   | 0.657      | -            | -                | -                | -         |    -4.38 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           30 |     2097 | 2024-05-14 | Elevate          | L   | 0.657      | -            | -                | -                | -         |    -4.55 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           29 |     2151 | 2024-05-12 | NRG              | L   | 0.644      | -            | -                | -                | -         |    -6.30 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           28 |     2158 | 2024-05-12 | Mythic           | W   | 0.642      | 0.270        | 0.010 (0.002)    | 0.300 (0.052)    | 0 (0.000) |    11.23 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           27 |     2178 | 2024-05-11 | BOSS             | W   | 0.637      | 0.270        | 0.014 (0.002)    | 0.333 (0.057)    | 0 (0.000) |    11.95 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           26 |     2181 | 2024-05-11 | NRG              | L   | 0.636      | -            | -                | -                | -         |    -6.28 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           25 |     2184 | 2024-05-11 | Party Astronauts | W   | 0.636      | 0.270        | 0.041 (0.007)    | 0.531 (0.091)    | 0 (0.000) |    15.50 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           24 |     2247 | 2024-05-08 | Nouns            | L   | 0.618      | -            | -                | -                | -         |    -4.66 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           23 |     2249 | 2024-05-08 | Nouns            | L   | 0.617      | -            | -                | -                | -         |    -4.85 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           22 |     2759 | 2024-04-17 | Nouns            | L   | 0.477      | -            | -                | -                | -         |    -3.63 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           21 |     2911 | 2024-04-10 | MIGHT            | L   | 0.431      | -            | -                | -                | -         |   -10.47 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           20 |     2916 | 2024-04-10 | MIGHT            | W   | 0.431      | -            | -                | -                | 0 (0.000) |     3.11 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           19 |     3094 | 2024-04-04 | Carpe Diem       | W   | 0.391      | 0.477        | 0.005 (0.001)    | -                | 0 (0.000) |     4.99 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           18 |     3099 | 2024-04-04 | Carpe Diem       | W   | 0.391      | 0.477        | 0.005 (0.001)    | -                | -         |     5.15 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           17 |     3142 | 2024-04-03 | Limitless        | W   | 0.384      | 0.477        | -                | 0.167 (0.031)    | -         |     4.77 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           16 |     3144 | 2024-04-03 | Limitless        | W   | 0.384      | 0.477        | -                | 0.167 (0.031)    | -         |     4.93 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           15 |     3192 | 2024-04-02 | Party Astronauts | L   | 0.378      | -            | -                | -                | -         |    -2.87 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           14 |     3196 | 2024-04-02 | BOSS             | L   | 0.377      | -            | -                | -                | -         |    -4.82 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           13 |     3279 | 2024-03-27 | M80              | L   | 0.337      | -            | -                | -                | -         |    -0.66 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           12 |     3285 | 2024-03-27 | M80              | L   | 0.337      | -            | -                | -                | -         |    -0.66 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           11 |     3404 | 2024-03-20 | LAG              | W   | 0.291      | 0.477        | 0.012 (0.002)    | 0.341 (0.047)    | -         |     6.16 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|           10 |     3406 | 2024-03-20 | LAG              | L   | 0.291      | -            | -                | -                | -         |    -3.04 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            9 |     3422 | 2024-03-19 | Party Astronauts | L   | 0.285      | -            | -                | -                | -         |    -2.17 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            8 |     3424 | 2024-03-19 | Party Astronauts | L   | 0.284      | -            | -                | -                | -         |    -2.21 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            7 |     3519 | 2024-03-14 | Wildcard         | L   | 0.251      | -            | -                | -                | -         |    -2.13 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            6 |     3522 | 2024-03-14 | Wildcard         | L   | 0.251      | -            | -                | -                | -         |    -2.17 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            5 |     3551 | 2024-03-13 | Mythic           | W   | 0.243      | -            | -                | -                | -         |     4.38 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            4 |     3594 | 2024-03-12 | bubibabu         | W   | 0.237      | -            | -                | -                | -         |     1.00 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            3 |     4020 | 2024-02-22 | MIGHT            | L   | 0.110      | -            | -                | -                | -         |    -2.65 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            2 |     4264 | 2024-02-13 | Take Flyte       | L   | 0.051      | -            | -                | -                | -         |    -0.87 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            1 |     4267 | 2024-02-13 | Take Flyte       | W   | 0.051      | -            | -                | -                | -         |     0.75 | BeaKie, CoJoMo, Gabe, mds, shutout |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,328.89)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
