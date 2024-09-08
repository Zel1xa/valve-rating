### Roster Details<br />
Team Name: Phoenix<br />
Roster: CoJoMo, Gabe, Louie, mds, shutout<br />
Global Rank: [173](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
<br />
Final Rank Value:  646.4<br />
<br />
Final Rank Value (646.4) = Starting Rank Value (696.8) + Head To Head Adjustments (-50.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.285[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.063[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 696.8
- 400 + ( ( 0.153 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 696.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           50 |      413 | 2024-08-26 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -13.20 | CoJoMo, Gabe, Louie, mds, shutout         |
|           49 |      431 | 2024-08-26 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.45 | CoJoMo, Gabe, Louie, mds, shutout         |
|           48 |      797 | 2024-08-15 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.27 | CoJoMo, Gabe, Louie, mds, shutout         |
|           47 |      943 | 2024-08-11 | Revenge Nation   | W   | 1.000      | 0.371        | 0.002 (0.001)    | 0.149 (0.055)    | 0 (0.000) |    16.32 | CoJoMo, Gabe, Louie, mds, shutout         |
|           46 |     1016 | 2024-08-08 | undefined        | L   | 0.997      | -            | -                | -                | -         |   -13.81 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           45 |     1184 | 2024-08-03 | DETONATE         | W   | 0.963      | 0.371        | -                | 0.109 (0.039)    | 0 (0.000) |     9.95 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           44 |     1550 | 2024-07-24 | Aether           | W   | 0.896      | -            | -                | -                | 0 (0.000) |     5.38 | CoJoMo, Gabe, mds, nooz, shutout          |
|           43 |     1668 | 2024-07-20 | timbermen        | L   | 0.869      | -            | -                | -                | -         |    -5.20 | CoJoMo, Gabe, mds, nooz, shutout          |
|           42 |     1802 | 2024-07-17 | timbermen        | L   | 0.850      | -            | -                | -                | -         |    -5.12 | CoJoMo, Gabe, mds, shutout, xaler         |
|           41 |     1806 | 2024-07-17 | timbermen        | L   | 0.850      | -            | -                | -                | -         |    -5.37 | CoJoMo, Gabe, mds, shutout, xaler         |
|           40 |     1866 | 2024-07-16 | Take Flyte       | L   | 0.844      | -            | -                | -                | -         |   -12.94 | CoJoMo, Gabe, mds, shutout, xaler         |
|           39 |     1872 | 2024-07-16 | Take Flyte       | L   | 0.843      | -            | -                | -                | -         |   -13.95 | CoJoMo, Gabe, mds, shutout, xaler         |
|           38 |     2222 | 2024-06-14 | Akimbo           | L   | 0.629      | -            | -                | -                | -         |    -9.42 | CoJoMo, Gabe, mds, shutout, xaler         |
|           37 |     2674 | 2024-06-04 | Mythic           | L   | 0.562      | -            | -                | -                | -         |    -7.18 | CoJoMo, Gabe, Louie, mds, shutout         |
|           36 |     2975 | 2024-05-22 | BOSS             | L   | 0.477      | -            | -                | -                | -         |    -6.78 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           35 |     2979 | 2024-05-22 | BOSS             | W   | 0.477      | 0.477        | 0.013 (0.003)    | 0.401 (0.091)    | 0 (0.000) |     8.44 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           34 |     3024 | 2024-05-21 | NRG              | W   | 0.470      | 0.477        | 0.018 (0.004)    | 0.573 (0.129)    | 0 (0.000) |    10.63 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           33 |     3026 | 2024-05-21 | NRG              | L   | 0.470      | -            | -                | -                | -         |    -4.20 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           32 |     3059 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.463      | -            | -                | -                | -         |    -6.75 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           31 |     3063 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.463      | 0.477        | 0.006 (0.001)    | 0.540 (0.119)    | 0 (0.000) |     8.03 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           30 |     3226 | 2024-05-15 | Mythic           | L   | 0.430      | -            | -                | -                | -         |    -5.72 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           29 |     3232 | 2024-05-15 | Mythic           | W   | 0.430      | 0.477        | 0.007 (0.002)    | 0.276 (0.057)    | 0 (0.000) |     8.01 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           28 |     3293 | 2024-05-14 | timbermen        | L   | 0.423      | -            | -                | -                | -         |    -2.92 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           27 |     3296 | 2024-05-14 | timbermen        | L   | 0.423      | -            | -                | -                | -         |    -3.00 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           26 |     3350 | 2024-05-12 | NRG              | L   | 0.410      | -            | -                | -                | -         |    -4.07 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           25 |     3357 | 2024-05-12 | Mythic           | W   | 0.408      | 0.270        | 0.007 (0.001)    | 0.276 (0.030)    | 0 (0.000) |     7.65 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           24 |     3377 | 2024-05-11 | BOSS             | W   | 0.402      | 0.270        | 0.013 (0.001)    | 0.401 (0.044)    | 0 (0.000) |     7.75 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           23 |     3380 | 2024-05-11 | NRG              | L   | 0.402      | -            | -                | -                | -         |    -4.00 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           22 |     3383 | 2024-05-11 | Party Astronauts | W   | 0.402      | 0.270        | 0.033 (0.004)    | 0.484 (0.053)    | 0 (0.000) |     9.38 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           21 |     3446 | 2024-05-08 | Nouns            | L   | 0.383      | -            | -                | -                | -         |    -2.99 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           20 |     3448 | 2024-05-08 | Nouns            | L   | 0.383      | -            | -                | -                | -         |    -3.06 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           19 |     3958 | 2024-04-17 | Nouns            | L   | 0.243      | -            | -                | -                | -         |    -1.91 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           18 |     4110 | 2024-04-10 | MIGHT            | L   | 0.197      | -            | -                | -                | -         |    -4.75 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           17 |     4115 | 2024-04-10 | MIGHT            | W   | 0.197      | -            | -                | -                | -         |     1.46 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           16 |     4293 | 2024-04-04 | Carpe Diem       | W   | 0.157      | 0.477        | 0.004 (0.000)    | -                | -         |     2.47 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           15 |     4298 | 2024-04-04 | Carpe Diem       | W   | 0.157      | 0.477        | 0.004 (0.000)    | -                | -         |     2.50 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           14 |     4341 | 2024-04-03 | Limitless        | W   | 0.150      | -            | -                | -                | -         |     1.92 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           13 |     4343 | 2024-04-03 | Limitless        | W   | 0.150      | -            | -                | -                | -         |     1.95 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           12 |     4391 | 2024-04-02 | Party Astronauts | L   | 0.144      | -            | -                | -                | -         |    -1.26 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           11 |     4395 | 2024-04-02 | BOSS             | L   | 0.142      | -            | -                | -                | -         |    -1.72 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           10 |     4478 | 2024-03-27 | M80              | L   | 0.103      | -            | -                | -                | -         |    -0.33 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            9 |     4484 | 2024-03-27 | M80              | L   | 0.103      | -            | -                | -                | -         |    -0.33 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            8 |     4603 | 2024-03-20 | LAG              | W   | 0.057      | 0.477        | -                | 0.371 (0.010)    | -         |     1.05 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            7 |     4605 | 2024-03-20 | LAG              | L   | 0.057      | -            | -                | -                | -         |    -0.74 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            6 |     4621 | 2024-03-19 | Party Astronauts | L   | 0.051      | -            | -                | -                | -         |    -0.45 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            5 |     4623 | 2024-03-19 | Party Astronauts | L   | 0.050      | -            | -                | -                | -         |    -0.44 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            4 |     4718 | 2024-03-14 | Wildcard         | L   | 0.017      | -            | -                | -                | -         |    -0.07 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            3 |     4721 | 2024-03-14 | Wildcard         | L   | 0.016      | -            | -                | -                | -         |    -0.07 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            2 |     4750 | 2024-03-13 | Mythic           | W   | 0.009      | -            | -                | -                | -         |     0.17 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            1 |     4793 | 2024-03-12 | bubibabu         | W   | 0.003      | -            | -                | -                | -         |     0.02 | BeaKie, CoJoMo, Gabe, mds, shutout        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($954.22)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
