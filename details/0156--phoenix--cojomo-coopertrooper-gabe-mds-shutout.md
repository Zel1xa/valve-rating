### Roster Details<br />
Team Name: Phoenix<br />
Roster: CoJoMo, CooperTrooper, Gabe, mds, shutout<br />
Global Rank: [156](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  695.3<br />
<br />
Final Rank Value (695.3) = Starting Rank Value (736.3) + Head To Head Adjustments (-41.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.077[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.3
- 400 + ( ( 0.164 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 736.3


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
|           48 |       46 | 2024-08-03 | Detonate         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.72 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           47 |      412 | 2024-07-24 | Victorum         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.29 | CoJoMo, Gabe, mds, nooz, shutout          |
|           46 |      530 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.53 | CoJoMo, Gabe, mds, nooz, shutout          |
|           45 |      664 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.49 | CoJoMo, Gabe, mds, shutout, xaler         |
|           44 |      668 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.78 | CoJoMo, Gabe, mds, shutout, xaler         |
|           43 |      728 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.58 | CoJoMo, Gabe, mds, shutout, xaler         |
|           42 |      734 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -17.02 | CoJoMo, Gabe, mds, shutout, xaler         |
|           41 |     1081 | 2024-06-14 | Akimbo           | L   | 0.854      | -            | -                | -                | -         |   -11.45 | CoJoMo, Gabe, mds, shutout, xaler         |
|           40 |     1533 | 2024-06-04 | Mythic           | L   | 0.787      | -            | -                | -                | -         |   -10.49 | CoJoMo, Gabe, Louie, mds, shutout         |
|           39 |     1834 | 2024-05-22 | BOSS             | L   | 0.702      | -            | -                | -                | -         |   -10.62 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           38 |     1838 | 2024-05-22 | BOSS             | W   | 0.702      | 0.477        | 0.014 (0.005)    | 0.327 (0.109)    | 0 (0.000) |    11.73 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           37 |     1883 | 2024-05-21 | NRG              | W   | 0.695      | 0.477        | 0.020 (0.007)    | 0.514 (0.170)    | 0 (0.000) |    16.15 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           36 |     1885 | 2024-05-21 | NRG              | L   | 0.695      | -            | -                | -                | -         |    -5.67 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           35 |     1918 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.689      | -            | -                | -                | -         |   -11.86 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           34 |     1922 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.688      | 0.477        | 0.003 (0.001)    | 0.310 (0.102)    | 0 (0.000) |     9.98 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           33 |     2085 | 2024-05-15 | Mythic           | L   | 0.655      | -            | -                | -                | -         |    -9.48 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           32 |     2091 | 2024-05-15 | Mythic           | W   | 0.655      | 0.477        | 0.010 (0.003)    | 0.293 (0.092)    | 0 (0.000) |    11.42 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           31 |     2152 | 2024-05-14 | Elevate          | L   | 0.648      | -            | -                | -                | -         |    -4.30 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           30 |     2155 | 2024-05-14 | Elevate          | L   | 0.648      | -            | -                | -                | -         |    -4.47 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           29 |     2209 | 2024-05-12 | NRG              | L   | 0.635      | -            | -                | -                | -         |    -6.24 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           28 |     2216 | 2024-05-12 | Mythic           | W   | 0.633      | 0.270        | 0.010 (0.002)    | 0.293 (0.050)    | 0 (0.000) |    11.06 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           27 |     2236 | 2024-05-11 | BOSS             | W   | 0.628      | 0.270        | 0.014 (0.002)    | 0.327 (0.055)    | 0 (0.000) |    11.80 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           26 |     2239 | 2024-05-11 | NRG              | L   | 0.627      | -            | -                | -                | -         |    -6.22 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           25 |     2242 | 2024-05-11 | Party Astronauts | W   | 0.627      | 0.270        | 0.041 (0.007)    | 0.523 (0.089)    | 0 (0.000) |    15.22 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           24 |     2305 | 2024-05-08 | Nouns            | L   | 0.608      | -            | -                | -                | -         |    -4.61 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           23 |     2307 | 2024-05-08 | Nouns            | L   | 0.608      | -            | -                | -                | -         |    -4.79 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           22 |     2817 | 2024-04-17 | Nouns            | L   | 0.468      | -            | -                | -                | -         |    -3.58 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           21 |     2969 | 2024-04-10 | MIGHT            | L   | 0.422      | -            | -                | -                | -         |   -10.25 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           20 |     2974 | 2024-04-10 | MIGHT            | W   | 0.422      | -            | -                | -                | 0 (0.000) |     3.05 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           19 |     3152 | 2024-04-04 | Carpe Diem       | W   | 0.382      | 0.477        | 0.005 (0.001)    | -                | -         |     4.88 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           18 |     3157 | 2024-04-04 | Carpe Diem       | W   | 0.382      | 0.477        | 0.005 (0.001)    | -                | -         |     5.04 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           17 |     3200 | 2024-04-03 | Limitless        | W   | 0.375      | 0.477        | -                | 0.164 (0.029)    | -         |     4.67 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           16 |     3202 | 2024-04-03 | Limitless        | W   | 0.375      | 0.477        | -                | 0.164 (0.029)    | -         |     4.82 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           15 |     3250 | 2024-04-02 | Party Astronauts | L   | 0.369      | -            | -                | -                | -         |    -2.82 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           14 |     3254 | 2024-04-02 | BOSS             | L   | 0.367      | -            | -                | -                | -         |    -4.68 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           13 |     3337 | 2024-03-27 | M80              | L   | 0.328      | -            | -                | -                | -         |    -0.65 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           12 |     3343 | 2024-03-27 | M80              | L   | 0.328      | -            | -                | -                | -         |    -0.65 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           11 |     3462 | 2024-03-20 | LAG              | W   | 0.282      | 0.477        | 0.012 (0.002)    | 0.347 (0.047)    | -         |     5.83 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|           10 |     3464 | 2024-03-20 | LAG              | L   | 0.282      | -            | -                | -                | -         |    -3.10 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            9 |     3480 | 2024-03-19 | Party Astronauts | L   | 0.276      | -            | -                | -                | -         |    -2.12 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            8 |     3482 | 2024-03-19 | Party Astronauts | L   | 0.275      | -            | -                | -                | -         |    -2.15 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            7 |     3577 | 2024-03-14 | Wildcard         | L   | 0.242      | -            | -                | -                | -         |    -2.34 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            6 |     3580 | 2024-03-14 | Wildcard         | L   | 0.242      | -            | -                | -                | -         |    -2.38 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            5 |     3609 | 2024-03-13 | Mythic           | W   | 0.234      | -            | -                | -                | -         |     4.22 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            4 |     3652 | 2024-03-12 | bubibabu         | W   | 0.228      | -            | -                | -                | -         |     0.96 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            3 |     4078 | 2024-02-22 | MIGHT            | L   | 0.101      | -            | -                | -                | -         |    -2.43 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            2 |     4322 | 2024-02-13 | Take Flyte       | L   | 0.042      | -            | -                | -                | -         |    -0.71 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            1 |     4325 | 2024-02-13 | Take Flyte       | W   | 0.042      | -            | -                | -                | -         |     0.62 | BeaKie, CoJoMo, Gabe, mds, shutout        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,314.44)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
