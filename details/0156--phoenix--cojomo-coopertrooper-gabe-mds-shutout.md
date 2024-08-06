### Roster Details<br />
Team Name: Phoenix<br />
Roster: CoJoMo, CooperTrooper, Gabe, mds, shutout<br />
Global Rank: [156](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  695.4<br />
<br />
Final Rank Value (695.4) = Starting Rank Value (736.3) + Head To Head Adjustments (-40.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.283[<sup>2</sup>](#table1)
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
|           48 |       52 | 2024-08-03 | DETONATE         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.74 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           47 |      418 | 2024-07-24 | Aether           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.29 | CoJoMo, Gabe, mds, nooz, shutout          |
|           46 |      536 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.54 | CoJoMo, Gabe, mds, nooz, shutout          |
|           45 |      670 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.50 | CoJoMo, Gabe, mds, shutout, xaler         |
|           44 |      674 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.79 | CoJoMo, Gabe, mds, shutout, xaler         |
|           43 |      734 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.57 | CoJoMo, Gabe, mds, shutout, xaler         |
|           42 |      740 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -17.01 | CoJoMo, Gabe, mds, shutout, xaler         |
|           41 |     1087 | 2024-06-14 | Akimbo           | L   | 0.850      | -            | -                | -                | -         |   -11.41 | CoJoMo, Gabe, mds, shutout, xaler         |
|           40 |     1539 | 2024-06-04 | Mythic           | L   | 0.782      | -            | -                | -                | -         |   -10.44 | CoJoMo, Gabe, Louie, mds, shutout         |
|           39 |     1840 | 2024-05-22 | BOSS             | L   | 0.698      | -            | -                | -                | -         |   -10.52 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           38 |     1844 | 2024-05-22 | BOSS             | W   | 0.698      | 0.477        | 0.014 (0.005)    | 0.326 (0.108)    | 0 (0.000) |    11.70 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           37 |     1889 | 2024-05-21 | NRG              | W   | 0.691      | 0.477        | 0.020 (0.007)    | 0.513 (0.169)    | 0 (0.000) |    16.04 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           36 |     1891 | 2024-05-21 | NRG              | L   | 0.691      | -            | -                | -                | -         |    -5.64 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           35 |     1924 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.684      | -            | -                | -                | -         |   -11.78 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           34 |     1928 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.684      | 0.477        | 0.003 (0.001)    | 0.311 (0.101)    | 0 (0.000) |     9.92 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           33 |     2091 | 2024-05-15 | Mythic           | L   | 0.651      | -            | -                | -                | -         |    -9.41 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           32 |     2097 | 2024-05-15 | Mythic           | W   | 0.651      | 0.477        | 0.010 (0.003)    | 0.291 (0.090)    | 0 (0.000) |    11.36 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           31 |     2158 | 2024-05-14 | Elevate          | L   | 0.644      | -            | -                | -                | -         |    -4.27 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           30 |     2161 | 2024-05-14 | Elevate          | L   | 0.644      | -            | -                | -                | -         |    -4.44 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           29 |     2215 | 2024-05-12 | NRG              | L   | 0.630      | -            | -                | -                | -         |    -6.20 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           28 |     2222 | 2024-05-12 | Mythic           | W   | 0.629      | 0.270        | 0.010 (0.002)    | 0.291 (0.050)    | 0 (0.000) |    11.00 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           27 |     2242 | 2024-05-11 | BOSS             | W   | 0.623      | 0.270        | 0.014 (0.002)    | 0.326 (0.055)    | 0 (0.000) |    11.75 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           26 |     2245 | 2024-05-11 | NRG              | L   | 0.623      | -            | -                | -                | -         |    -6.18 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           25 |     2248 | 2024-05-11 | Party Astronauts | W   | 0.623      | 0.270        | 0.041 (0.007)    | 0.522 (0.088)    | 0 (0.000) |    15.11 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           24 |     2311 | 2024-05-08 | Nouns            | L   | 0.604      | -            | -                | -                | -         |    -4.59 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           23 |     2313 | 2024-05-08 | Nouns            | L   | 0.604      | -            | -                | -                | -         |    -4.77 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           22 |     2823 | 2024-04-17 | Nouns            | L   | 0.463      | -            | -                | -                | -         |    -3.55 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           21 |     2975 | 2024-04-10 | MIGHT            | L   | 0.418      | -            | -                | -                | -         |   -10.15 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           20 |     2980 | 2024-04-10 | MIGHT            | W   | 0.417      | -            | -                | -                | 0 (0.000) |     3.01 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           19 |     3158 | 2024-04-04 | Carpe Diem       | W   | 0.378      | 0.477        | 0.005 (0.001)    | -                | -         |     4.83 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           18 |     3163 | 2024-04-04 | Carpe Diem       | W   | 0.378      | 0.477        | 0.005 (0.001)    | -                | -         |     4.98 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           17 |     3206 | 2024-04-03 | Limitless        | W   | 0.371      | 0.477        | -                | 0.163 (0.029)    | -         |     4.62 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           16 |     3208 | 2024-04-03 | Limitless        | W   | 0.371      | 0.477        | -                | 0.163 (0.029)    | -         |     4.76 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           15 |     3256 | 2024-04-02 | Party Astronauts | L   | 0.364      | -            | -                | -                | -         |    -2.80 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           14 |     3260 | 2024-04-02 | BOSS             | L   | 0.363      | -            | -                | -                | -         |    -4.60 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           13 |     3343 | 2024-03-27 | M80              | L   | 0.324      | -            | -                | -                | -         |    -0.64 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           12 |     3349 | 2024-03-27 | M80              | L   | 0.324      | -            | -                | -                | -         |    -0.65 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           11 |     3468 | 2024-03-20 | LAG              | W   | 0.278      | 0.477        | 0.012 (0.002)    | 0.385 (0.051)    | -         |     5.73 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|           10 |     3470 | 2024-03-20 | LAG              | L   | 0.278      | -            | -                | -                | -         |    -3.06 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            9 |     3486 | 2024-03-19 | Party Astronauts | L   | 0.272      | -            | -                | -                | -         |    -2.09 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            8 |     3488 | 2024-03-19 | Party Astronauts | L   | 0.271      | -            | -                | -                | -         |    -2.13 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            7 |     3583 | 2024-03-14 | Wildcard         | L   | 0.238      | -            | -                | -                | -         |    -2.30 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            6 |     3586 | 2024-03-14 | Wildcard         | L   | 0.237      | -            | -                | -                | -         |    -2.34 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            5 |     3615 | 2024-03-13 | Mythic           | W   | 0.230      | -            | -                | -                | -         |     4.14 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            4 |     3658 | 2024-03-12 | bubibabu         | W   | 0.224      | -            | -                | -                | -         |     0.94 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            3 |     4084 | 2024-02-22 | MIGHT            | L   | 0.097      | -            | -                | -                | -         |    -2.33 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            2 |     4328 | 2024-02-13 | Take Flyte       | L   | 0.038      | -            | -                | -                | -         |    -0.64 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            1 |     4331 | 2024-02-13 | Take Flyte       | W   | 0.038      | -            | -                | -                | -         |     0.56 | BeaKie, CoJoMo, Gabe, mds, shutout        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,307.56)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
