### Roster Details<br />
Team Name: Perseverance<br />
Roster: CoJoMo, Gabe, mds, nooz, shutout<br />
Global Rank: [159](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  686.0<br />
<br />
Final Rank Value (686.0) = Starting Rank Value (736.2) + Head To Head Adjustments (-50.1)<br />

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
|           47 |      362 | 2024-07-24 | Victorum         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.28 | CoJoMo, Gabe, mds, nooz, shutout   |
|           46 |      480 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.52 | CoJoMo, Gabe, mds, nooz, shutout   |
|           45 |      614 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.48 | CoJoMo, Gabe, mds, shutout, xaler  |
|           44 |      618 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.77 | CoJoMo, Gabe, mds, shutout, xaler  |
|           43 |      678 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.61 | CoJoMo, Gabe, mds, shutout, xaler  |
|           42 |      684 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -17.05 | CoJoMo, Gabe, mds, shutout, xaler  |
|           41 |     1031 | 2024-06-14 | Akimbo           | L   | 0.862      | -            | -                | -                | -         |   -11.59 | CoJoMo, Gabe, mds, shutout, xaler  |
|           40 |     1483 | 2024-06-04 | Mythic           | L   | 0.795      | -            | -                | -                | -         |   -10.57 | CoJoMo, Gabe, Louie, mds, shutout  |
|           39 |     1784 | 2024-05-22 | BOSS             | L   | 0.710      | -            | -                | -                | -         |   -10.73 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           38 |     1788 | 2024-05-22 | BOSS             | W   | 0.710      | 0.477        | 0.014 (0.005)    | 0.333 (0.113)    | 0 (0.000) |    11.88 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           37 |     1833 | 2024-05-21 | NRG              | W   | 0.704      | 0.477        | 0.020 (0.007)    | 0.521 (0.175)    | 0 (0.000) |    16.38 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           36 |     1835 | 2024-05-21 | NRG              | L   | 0.703      | -            | -                | -                | -         |    -5.69 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           35 |     1868 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.697      | -            | -                | -                | -         |   -12.15 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           34 |     1872 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.697      | 0.477        | 0.003 (0.001)    | 0.274 (0.091)    | 0 (0.000) |     9.93 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           33 |     2035 | 2024-05-15 | Mythic           | L   | 0.664      | -            | -                | -                | -         |    -9.58 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           32 |     2041 | 2024-05-15 | Mythic           | W   | 0.663      | 0.477        | 0.010 (0.003)    | 0.299 (0.095)    | 0 (0.000) |    11.58 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           31 |     2102 | 2024-05-14 | Elevate          | L   | 0.656      | -            | -                | -                | -         |    -4.37 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           30 |     2105 | 2024-05-14 | Elevate          | L   | 0.656      | -            | -                | -                | -         |    -4.54 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           29 |     2159 | 2024-05-12 | NRG              | L   | 0.643      | -            | -                | -                | -         |    -6.29 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           28 |     2166 | 2024-05-12 | Mythic           | W   | 0.642      | 0.270        | 0.010 (0.002)    | 0.299 (0.052)    | 0 (0.000) |    11.22 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           27 |     2186 | 2024-05-11 | BOSS             | W   | 0.636      | 0.270        | 0.014 (0.002)    | 0.333 (0.057)    | 0 (0.000) |    11.94 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           26 |     2189 | 2024-05-11 | NRG              | L   | 0.636      | -            | -                | -                | -         |    -6.27 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           25 |     2192 | 2024-05-11 | Party Astronauts | W   | 0.635      | 0.270        | 0.041 (0.007)    | 0.531 (0.091)    | 0 (0.000) |    15.48 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           24 |     2255 | 2024-05-08 | Nouns            | L   | 0.617      | -            | -                | -                | -         |    -4.65 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           23 |     2257 | 2024-05-08 | Nouns            | L   | 0.617      | -            | -                | -                | -         |    -4.84 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           22 |     2767 | 2024-04-17 | Nouns            | L   | 0.476      | -            | -                | -                | -         |    -3.62 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           21 |     2919 | 2024-04-10 | MIGHT            | L   | 0.430      | -            | -                | -                | -         |   -10.46 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           20 |     2924 | 2024-04-10 | MIGHT            | W   | 0.430      | -            | -                | -                | 0 (0.000) |     3.10 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           19 |     3102 | 2024-04-04 | Carpe Diem       | W   | 0.390      | 0.477        | 0.005 (0.001)    | -                | 0 (0.000) |     4.98 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           18 |     3107 | 2024-04-04 | Carpe Diem       | W   | 0.390      | 0.477        | 0.005 (0.001)    | -                | -         |     5.14 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           17 |     3150 | 2024-04-03 | Limitless        | W   | 0.384      | 0.477        | -                | 0.167 (0.031)    | -         |     4.76 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           16 |     3152 | 2024-04-03 | Limitless        | W   | 0.383      | 0.477        | -                | 0.167 (0.031)    | -         |     4.92 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           15 |     3200 | 2024-04-02 | Party Astronauts | L   | 0.377      | -            | -                | -                | -         |    -2.86 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           14 |     3204 | 2024-04-02 | BOSS             | L   | 0.376      | -            | -                | -                | -         |    -4.81 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           13 |     3287 | 2024-03-27 | M80              | L   | 0.337      | -            | -                | -                | -         |    -0.65 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           12 |     3293 | 2024-03-27 | M80              | L   | 0.337      | -            | -                | -                | -         |    -0.66 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           11 |     3412 | 2024-03-20 | LAG              | W   | 0.290      | 0.477        | 0.012 (0.002)    | 0.340 (0.047)    | -         |     6.14 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|           10 |     3414 | 2024-03-20 | LAG              | L   | 0.290      | -            | -                | -                | -         |    -3.04 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            9 |     3430 | 2024-03-19 | Party Astronauts | L   | 0.284      | -            | -                | -                | -         |    -2.16 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            8 |     3432 | 2024-03-19 | Party Astronauts | L   | 0.284      | -            | -                | -                | -         |    -2.20 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            7 |     3527 | 2024-03-14 | Wildcard         | L   | 0.250      | -            | -                | -                | -         |    -2.13 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            6 |     3530 | 2024-03-14 | Wildcard         | L   | 0.250      | -            | -                | -                | -         |    -2.16 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            5 |     3559 | 2024-03-13 | Mythic           | W   | 0.243      | -            | -                | -                | -         |     4.37 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            4 |     3602 | 2024-03-12 | bubibabu         | W   | 0.237      | -            | -                | -                | -         |     1.00 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            3 |     4028 | 2024-02-22 | MIGHT            | L   | 0.110      | -            | -                | -                | -         |    -2.63 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            2 |     4272 | 2024-02-13 | Take Flyte       | L   | 0.051      | -            | -                | -                | -         |    -0.86 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            1 |     4275 | 2024-02-13 | Take Flyte       | W   | 0.050      | -            | -                | -                | -         |     0.74 | BeaKie, CoJoMo, Gabe, mds, shutout |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,327.74)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
