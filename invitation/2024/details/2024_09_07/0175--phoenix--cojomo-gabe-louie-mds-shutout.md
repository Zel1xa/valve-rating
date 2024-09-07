### Roster Details<br />
Team Name: Phoenix<br />
Roster: CoJoMo, Gabe, Louie, mds, shutout<br />
Global Rank: [175](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Americas]( ../../standings_americas_2024_09_07.md)<br />
Regional Rank: [47]( ../../standings_americas_2024_09_07.md)<br />
<br />
Final Rank Value:  651.3<br />
<br />
Final Rank Value (651.3) = Starting Rank Value (701.8) + Head To Head Adjustments (-50.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.066[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.154<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.8
- 400 + ( ( 0.154 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 701.8


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
|           50 |      381 | 2024-08-26 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -13.18 | CoJoMo, Gabe, Louie, mds, shutout         |
|           49 |      399 | 2024-08-26 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.41 | CoJoMo, Gabe, Louie, mds, shutout         |
|           48 |      765 | 2024-08-15 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.22 | CoJoMo, Gabe, Louie, mds, shutout         |
|           47 |      911 | 2024-08-11 | Revenge Nation   | W   | 1.000      | 0.371        | 0.002 (0.001)    | 0.154 (0.057)    | 0 (0.000) |    16.35 | CoJoMo, Gabe, Louie, mds, shutout         |
|           46 |      984 | 2024-08-08 | undefined        | L   | 1.000      | -            | -                | -                | -         |   -13.89 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           45 |     1152 | 2024-08-03 | DETONATE         | W   | 0.971      | 0.371        | -                | 0.112 (0.040)    | 0 (0.000) |     9.93 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           44 |     1518 | 2024-07-24 | Aether           | W   | 0.904      | -            | -                | -                | 0 (0.000) |     5.30 | CoJoMo, Gabe, mds, nooz, shutout          |
|           43 |     1636 | 2024-07-20 | timbermen        | L   | 0.877      | -            | -                | -                | -         |    -5.20 | CoJoMo, Gabe, mds, nooz, shutout          |
|           42 |     1770 | 2024-07-17 | timbermen        | L   | 0.858      | -            | -                | -                | -         |    -5.12 | CoJoMo, Gabe, mds, shutout, xaler         |
|           41 |     1774 | 2024-07-17 | timbermen        | L   | 0.858      | -            | -                | -                | -         |    -5.37 | CoJoMo, Gabe, mds, shutout, xaler         |
|           40 |     1834 | 2024-07-16 | Take Flyte       | L   | 0.852      | -            | -                | -                | -         |   -13.07 | CoJoMo, Gabe, mds, shutout, xaler         |
|           39 |     1840 | 2024-07-16 | Take Flyte       | L   | 0.851      | -            | -                | -                | -         |   -14.10 | CoJoMo, Gabe, mds, shutout, xaler         |
|           38 |     2190 | 2024-06-14 | Akimbo           | L   | 0.637      | -            | -                | -                | -         |    -9.55 | CoJoMo, Gabe, mds, shutout, xaler         |
|           37 |     2642 | 2024-06-04 | Mythic           | L   | 0.569      | -            | -                | -                | -         |    -7.32 | CoJoMo, Gabe, Louie, mds, shutout         |
|           36 |     2943 | 2024-05-22 | BOSS             | L   | 0.485      | -            | -                | -                | -         |    -6.88 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           35 |     2947 | 2024-05-22 | BOSS             | W   | 0.485      | 0.477        | 0.013 (0.003)    | 0.414 (0.096)    | 0 (0.000) |     8.59 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           34 |     2992 | 2024-05-21 | NRG              | W   | 0.478      | 0.477        | 0.018 (0.004)    | 0.592 (0.135)    | 0 (0.000) |    10.85 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           33 |     2994 | 2024-05-21 | NRG              | L   | 0.478      | -            | -                | -                | -         |    -4.24 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           32 |     3027 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.471      | -            | -                | -                | -         |    -6.85 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           31 |     3031 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.471      | 0.477        | 0.006 (0.001)    | 0.556 (0.125)    | 0 (0.000) |     8.18 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           30 |     3194 | 2024-05-15 | Mythic           | L   | 0.438      | -            | -                | -                | -         |    -5.87 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           29 |     3200 | 2024-05-15 | Mythic           | W   | 0.438      | 0.477        | 0.007 (0.002)    | 0.287 (0.060)    | 0 (0.000) |     8.12 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           28 |     3261 | 2024-05-14 | timbermen        | L   | 0.431      | -            | -                | -                | -         |    -2.94 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           27 |     3264 | 2024-05-14 | timbermen        | L   | 0.431      | -            | -                | -                | -         |    -3.02 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           26 |     3318 | 2024-05-12 | NRG              | L   | 0.418      | -            | -                | -                | -         |    -4.12 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           25 |     3325 | 2024-05-12 | Mythic           | W   | 0.416      | 0.270        | 0.007 (0.001)    | 0.287 (0.032)    | 0 (0.000) |     7.76 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           24 |     3345 | 2024-05-11 | BOSS             | W   | 0.410      | 0.270        | 0.013 (0.001)    | 0.414 (0.046)    | 0 (0.000) |     7.92 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           23 |     3348 | 2024-05-11 | NRG              | L   | 0.410      | -            | -                | -                | -         |    -4.06 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           22 |     3351 | 2024-05-11 | Party Astronauts | W   | 0.410      | 0.270        | 0.033 (0.004)    | 0.500 (0.055)    | 0 (0.000) |     9.60 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           21 |     3414 | 2024-05-08 | Nouns            | L   | 0.391      | -            | -                | -                | -         |    -3.02 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           20 |     3416 | 2024-05-08 | Nouns            | L   | 0.391      | -            | -                | -                | -         |    -3.10 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           19 |     3926 | 2024-04-17 | Nouns            | L   | 0.250      | -            | -                | -                | -         |    -1.95 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           18 |     4078 | 2024-04-10 | MIGHT            | L   | 0.205      | -            | -                | -                | -         |    -4.97 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           17 |     4083 | 2024-04-10 | MIGHT            | W   | 0.205      | -            | -                | -                | -         |     1.49 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           16 |     4261 | 2024-04-04 | Carpe Diem       | W   | 0.165      | 0.477        | 0.004 (0.000)    | -                | -         |     2.59 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           15 |     4266 | 2024-04-04 | Carpe Diem       | W   | 0.165      | 0.477        | 0.004 (0.000)    | -                | -         |     2.62 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           14 |     4309 | 2024-04-03 | Limitless        | W   | 0.158      | -            | -                | -                | -         |     2.01 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           13 |     4311 | 2024-04-03 | Limitless        | W   | 0.158      | -            | -                | -                | -         |     2.04 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           12 |     4359 | 2024-04-02 | Party Astronauts | L   | 0.152      | -            | -                | -                | -         |    -1.31 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           11 |     4363 | 2024-04-02 | BOSS             | L   | 0.150      | -            | -                | -                | -         |    -1.81 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           10 |     4446 | 2024-03-27 | M80              | L   | 0.111      | -            | -                | -                | -         |    -0.34 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            9 |     4452 | 2024-03-27 | M80              | L   | 0.111      | -            | -                | -                | -         |    -0.34 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            8 |     4571 | 2024-03-20 | LAG              | W   | 0.065      | 0.477        | -                | 0.385 (0.012)    | -         |     1.20 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            7 |     4573 | 2024-03-20 | LAG              | L   | 0.065      | -            | -                | -                | -         |    -0.84 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            6 |     4589 | 2024-03-19 | Party Astronauts | L   | 0.059      | -            | -                | -                | -         |    -0.51 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            5 |     4591 | 2024-03-19 | Party Astronauts | L   | 0.058      | -            | -                | -                | -         |    -0.51 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            4 |     4686 | 2024-03-14 | Wildcard         | L   | 0.025      | -            | -                | -                | -         |    -0.12 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            3 |     4689 | 2024-03-14 | Wildcard         | L   | 0.024      | -            | -                | -                | -         |    -0.11 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            2 |     4718 | 2024-03-13 | Mythic           | W   | 0.017      | -            | -                | -                | -         |     0.32 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            1 |     4761 | 2024-03-12 | bubibabu         | W   | 0.011      | -            | -                | -                | -         |     0.06 | BeaKie, CoJoMo, Gabe, mds, shutout        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($966.89)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
