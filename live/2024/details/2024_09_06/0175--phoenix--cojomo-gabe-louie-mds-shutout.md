### Roster Details<br />
Team Name: Phoenix<br />
Roster: CoJoMo, Gabe, Louie, mds, shutout<br />
Global Rank: [175](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Americas]( ../../standings_americas_2024_09_06.md)<br />
Regional Rank: [47]( ../../standings_americas_2024_09_06.md)<br />
<br />
Final Rank Value:  651.6<br />
<br />
Final Rank Value (651.6) = Starting Rank Value (702.0) + Head To Head Adjustments (-50.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.066[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.155<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 702.0
- 400 + ( ( 0.155 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 702.0


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
|           50 |      376 | 2024-08-26 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -13.18 | CoJoMo, Gabe, Louie, mds, shutout         |
|           49 |      394 | 2024-08-26 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.40 | CoJoMo, Gabe, Louie, mds, shutout         |
|           48 |      760 | 2024-08-15 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.20 | CoJoMo, Gabe, Louie, mds, shutout         |
|           47 |      906 | 2024-08-11 | Revenge Nation   | W   | 1.000      | 0.371        | 0.002 (0.001)    | 0.154 (0.057)    | 0 (0.000) |    16.38 | CoJoMo, Gabe, Louie, mds, shutout         |
|           46 |      979 | 2024-08-08 | undefined        | L   | 1.000      | -            | -                | -                | -         |   -13.90 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           45 |     1147 | 2024-08-03 | DETONATE         | W   | 0.975      | 0.371        | -                | 0.112 (0.040)    | 0 (0.000) |     9.97 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           44 |     1513 | 2024-07-24 | Aether           | W   | 0.908      | -            | -                | -                | 0 (0.000) |     5.32 | CoJoMo, Gabe, mds, nooz, shutout          |
|           43 |     1631 | 2024-07-20 | timbermen        | L   | 0.881      | -            | -                | -                | -         |    -5.22 | CoJoMo, Gabe, mds, nooz, shutout          |
|           42 |     1765 | 2024-07-17 | timbermen        | L   | 0.862      | -            | -                | -                | -         |    -5.14 | CoJoMo, Gabe, mds, shutout, xaler         |
|           41 |     1769 | 2024-07-17 | timbermen        | L   | 0.862      | -            | -                | -                | -         |    -5.39 | CoJoMo, Gabe, mds, shutout, xaler         |
|           40 |     1829 | 2024-07-16 | Take Flyte       | L   | 0.856      | -            | -                | -                | -         |   -13.14 | CoJoMo, Gabe, mds, shutout, xaler         |
|           39 |     1835 | 2024-07-16 | Take Flyte       | L   | 0.855      | -            | -                | -                | -         |   -14.17 | CoJoMo, Gabe, mds, shutout, xaler         |
|           38 |     2185 | 2024-06-14 | Akimbo           | L   | 0.641      | -            | -                | -                | -         |    -9.61 | CoJoMo, Gabe, mds, shutout, xaler         |
|           37 |     2637 | 2024-06-04 | Mythic           | L   | 0.573      | -            | -                | -                | -         |    -7.37 | CoJoMo, Gabe, Louie, mds, shutout         |
|           36 |     2938 | 2024-05-22 | BOSS             | L   | 0.489      | -            | -                | -                | -         |    -6.95 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           35 |     2942 | 2024-05-22 | BOSS             | W   | 0.489      | 0.477        | 0.013 (0.003)    | 0.413 (0.096)    | 0 (0.000) |     8.65 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           34 |     2987 | 2024-05-21 | NRG              | W   | 0.482      | 0.477        | 0.018 (0.004)    | 0.591 (0.136)    | 0 (0.000) |    10.94 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           33 |     2989 | 2024-05-21 | NRG              | L   | 0.482      | -            | -                | -                | -         |    -4.27 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           32 |     3022 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.475      | -            | -                | -                | -         |    -6.91 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           31 |     3026 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.475      | 0.477        | 0.006 (0.001)    | 0.554 (0.126)    | 0 (0.000) |     8.25 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           30 |     3189 | 2024-05-15 | Mythic           | L   | 0.442      | -            | -                | -                | -         |    -5.92 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           29 |     3195 | 2024-05-15 | Mythic           | W   | 0.442      | 0.477        | 0.007 (0.002)    | 0.287 (0.061)    | 0 (0.000) |     8.19 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           28 |     3256 | 2024-05-14 | timbermen        | L   | 0.435      | -            | -                | -                | -         |    -2.97 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           27 |     3259 | 2024-05-14 | timbermen        | L   | 0.435      | -            | -                | -                | -         |    -3.05 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           26 |     3313 | 2024-05-12 | NRG              | L   | 0.422      | -            | -                | -                | -         |    -4.16 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           25 |     3320 | 2024-05-12 | Mythic           | W   | 0.420      | 0.270        | 0.007 (0.001)    | 0.287 (0.033)    | 0 (0.000) |     7.83 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           24 |     3340 | 2024-05-11 | BOSS             | W   | 0.414      | 0.270        | 0.013 (0.001)    | 0.413 (0.046)    | 0 (0.000) |     7.99 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           23 |     3343 | 2024-05-11 | NRG              | L   | 0.414      | -            | -                | -                | -         |    -4.10 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           22 |     3346 | 2024-05-11 | Party Astronauts | W   | 0.414      | 0.270        | 0.033 (0.004)    | 0.500 (0.056)    | 0 (0.000) |     9.70 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           21 |     3409 | 2024-05-08 | Nouns            | L   | 0.395      | -            | -                | -                | -         |    -3.05 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           20 |     3411 | 2024-05-08 | Nouns            | L   | 0.395      | -            | -                | -                | -         |    -3.13 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           19 |     3921 | 2024-04-17 | Nouns            | L   | 0.254      | -            | -                | -                | -         |    -1.98 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           18 |     4073 | 2024-04-10 | MIGHT            | L   | 0.209      | -            | -                | -                | -         |    -5.07 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           17 |     4078 | 2024-04-10 | MIGHT            | W   | 0.209      | -            | -                | -                | -         |     1.52 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           16 |     4256 | 2024-04-04 | Carpe Diem       | W   | 0.169      | 0.477        | 0.004 (0.000)    | -                | -         |     2.65 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           15 |     4261 | 2024-04-04 | Carpe Diem       | W   | 0.169      | 0.477        | 0.004 (0.000)    | -                | -         |     2.68 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           14 |     4304 | 2024-04-03 | Limitless        | W   | 0.162      | -            | -                | -                | -         |     2.06 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           13 |     4306 | 2024-04-03 | Limitless        | W   | 0.162      | -            | -                | -                | -         |     2.09 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           12 |     4354 | 2024-04-02 | Party Astronauts | L   | 0.156      | -            | -                | -                | -         |    -1.34 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           11 |     4358 | 2024-04-02 | BOSS             | L   | 0.154      | -            | -                | -                | -         |    -1.86 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           10 |     4441 | 2024-03-27 | M80              | L   | 0.115      | -            | -                | -                | -         |    -0.35 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            9 |     4447 | 2024-03-27 | M80              | L   | 0.115      | -            | -                | -                | -         |    -0.35 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            8 |     4566 | 2024-03-20 | LAG              | W   | 0.069      | 0.477        | -                | 0.385 (0.013)    | -         |     1.28 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            7 |     4568 | 2024-03-20 | LAG              | L   | 0.069      | -            | -                | -                | -         |    -0.89 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            6 |     4584 | 2024-03-19 | Party Astronauts | L   | 0.063      | -            | -                | -                | -         |    -0.54 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            5 |     4586 | 2024-03-19 | Party Astronauts | L   | 0.062      | -            | -                | -                | -         |    -0.54 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            4 |     4681 | 2024-03-14 | Wildcard         | L   | 0.029      | -            | -                | -                | -         |    -0.13 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            3 |     4684 | 2024-03-14 | Wildcard         | L   | 0.028      | -            | -                | -                | -         |    -0.13 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            2 |     4713 | 2024-03-13 | Mythic           | W   | 0.021      | -            | -                | -                | -         |     0.40 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            1 |     4756 | 2024-03-12 | bubibabu         | W   | 0.015      | -            | -                | -                | -         |     0.07 | BeaKie, CoJoMo, Gabe, mds, shutout        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($973.30)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
