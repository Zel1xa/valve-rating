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
|           48 |       45 | 2024-08-03 | Detonate         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.72 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           47 |      411 | 2024-07-24 | Victorum         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.29 | CoJoMo, Gabe, mds, nooz, shutout          |
|           46 |      529 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.53 | CoJoMo, Gabe, mds, nooz, shutout          |
|           45 |      663 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.49 | CoJoMo, Gabe, mds, shutout, xaler         |
|           44 |      667 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.78 | CoJoMo, Gabe, mds, shutout, xaler         |
|           43 |      727 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.58 | CoJoMo, Gabe, mds, shutout, xaler         |
|           42 |      733 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -17.02 | CoJoMo, Gabe, mds, shutout, xaler         |
|           41 |     1080 | 2024-06-14 | Akimbo           | L   | 0.854      | -            | -                | -                | -         |   -11.46 | CoJoMo, Gabe, mds, shutout, xaler         |
|           40 |     1532 | 2024-06-04 | Mythic           | L   | 0.787      | -            | -                | -                | -         |   -10.50 | CoJoMo, Gabe, Louie, mds, shutout         |
|           39 |     1833 | 2024-05-22 | BOSS             | L   | 0.703      | -            | -                | -                | -         |   -10.63 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           38 |     1837 | 2024-05-22 | BOSS             | W   | 0.702      | 0.477        | 0.014 (0.005)    | 0.327 (0.109)    | 0 (0.000) |    11.73 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           37 |     1882 | 2024-05-21 | NRG              | W   | 0.696      | 0.477        | 0.020 (0.007)    | 0.514 (0.170)    | 0 (0.000) |    16.16 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           36 |     1884 | 2024-05-21 | NRG              | L   | 0.696      | -            | -                | -                | -         |    -5.67 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           35 |     1917 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.689      | -            | -                | -                | -         |   -11.86 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           34 |     1921 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.689      | 0.477        | 0.003 (0.001)    | 0.310 (0.102)    | 0 (0.000) |     9.98 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           33 |     2084 | 2024-05-15 | Mythic           | L   | 0.656      | -            | -                | -                | -         |    -9.48 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           32 |     2090 | 2024-05-15 | Mythic           | W   | 0.656      | 0.477        | 0.010 (0.003)    | 0.293 (0.092)    | 0 (0.000) |    11.43 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           31 |     2151 | 2024-05-14 | Elevate          | L   | 0.648      | -            | -                | -                | -         |    -4.30 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           30 |     2154 | 2024-05-14 | Elevate          | L   | 0.648      | -            | -                | -                | -         |    -4.47 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           29 |     2208 | 2024-05-12 | NRG              | L   | 0.635      | -            | -                | -                | -         |    -6.25 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           28 |     2215 | 2024-05-12 | Mythic           | W   | 0.634      | 0.270        | 0.010 (0.002)    | 0.293 (0.050)    | 0 (0.000) |    11.07 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           27 |     2235 | 2024-05-11 | BOSS             | W   | 0.628      | 0.270        | 0.014 (0.002)    | 0.327 (0.055)    | 0 (0.000) |    11.80 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           26 |     2238 | 2024-05-11 | NRG              | L   | 0.628      | -            | -                | -                | -         |    -6.23 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           25 |     2241 | 2024-05-11 | Party Astronauts | W   | 0.627      | 0.270        | 0.041 (0.007)    | 0.523 (0.089)    | 0 (0.000) |    15.23 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           24 |     2304 | 2024-05-08 | Nouns            | L   | 0.609      | -            | -                | -                | -         |    -4.61 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           23 |     2306 | 2024-05-08 | Nouns            | L   | 0.609      | -            | -                | -                | -         |    -4.80 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           22 |     2816 | 2024-04-17 | Nouns            | L   | 0.468      | -            | -                | -                | -         |    -3.58 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           21 |     2968 | 2024-04-10 | MIGHT            | L   | 0.422      | -            | -                | -                | -         |   -10.26 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           20 |     2973 | 2024-04-10 | MIGHT            | W   | 0.422      | -            | -                | -                | 0 (0.000) |     3.05 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           19 |     3151 | 2024-04-04 | Carpe Diem       | W   | 0.383      | 0.477        | 0.005 (0.001)    | -                | -         |     4.89 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           18 |     3156 | 2024-04-04 | Carpe Diem       | W   | 0.382      | 0.477        | 0.005 (0.001)    | -                | -         |     5.05 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           17 |     3199 | 2024-04-03 | Limitless        | W   | 0.376      | 0.477        | -                | 0.164 (0.029)    | -         |     4.67 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           16 |     3201 | 2024-04-03 | Limitless        | W   | 0.376      | 0.477        | -                | 0.164 (0.029)    | -         |     4.82 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           15 |     3249 | 2024-04-02 | Party Astronauts | L   | 0.369      | -            | -                | -                | -         |    -2.82 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           14 |     3253 | 2024-04-02 | BOSS             | L   | 0.368      | -            | -                | -                | -         |    -4.69 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           13 |     3336 | 2024-03-27 | M80              | L   | 0.329      | -            | -                | -                | -         |    -0.65 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           12 |     3342 | 2024-03-27 | M80              | L   | 0.329      | -            | -                | -                | -         |    -0.65 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           11 |     3461 | 2024-03-20 | LAG              | W   | 0.282      | 0.477        | 0.012 (0.002)    | 0.347 (0.047)    | -         |     5.84 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|           10 |     3463 | 2024-03-20 | LAG              | L   | 0.282      | -            | -                | -                | -         |    -3.10 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            9 |     3479 | 2024-03-19 | Party Astronauts | L   | 0.276      | -            | -                | -                | -         |    -2.12 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            8 |     3481 | 2024-03-19 | Party Astronauts | L   | 0.276      | -            | -                | -                | -         |    -2.16 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            7 |     3576 | 2024-03-14 | Wildcard         | L   | 0.242      | -            | -                | -                | -         |    -2.35 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            6 |     3579 | 2024-03-14 | Wildcard         | L   | 0.242      | -            | -                | -                | -         |    -2.39 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            5 |     3608 | 2024-03-13 | Mythic           | W   | 0.235      | -            | -                | -                | -         |     4.23 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            4 |     3651 | 2024-03-12 | bubibabu         | W   | 0.229      | -            | -                | -                | -         |     0.96 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            3 |     4077 | 2024-02-22 | MIGHT            | L   | 0.102      | -            | -                | -                | -         |    -2.44 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            2 |     4321 | 2024-02-13 | Take Flyte       | L   | 0.043      | -            | -                | -                | -         |    -0.72 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            1 |     4324 | 2024-02-13 | Take Flyte       | W   | 0.043      | -            | -                | -                | -         |     0.63 | BeaKie, CoJoMo, Gabe, mds, shutout        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,315.11)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
