### Roster Details<br />
Team Name: Phoenix<br />
Roster: CoJoMo, CooperTrooper, Gabe, mds, shutout<br />
Global Rank: [156](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  695.1<br />
<br />
Final Rank Value (695.1) = Starting Rank Value (736.0) + Head To Head Adjustments (-40.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.283[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.163<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.0
- 400 + ( ( 0.163 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 736.0


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
|           48 |       66 | 2024-08-03 | DETONATE         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.76 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           47 |      432 | 2024-07-24 | Aether           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.30 | CoJoMo, Gabe, mds, nooz, shutout          |
|           46 |      550 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.54 | CoJoMo, Gabe, mds, nooz, shutout          |
|           45 |      684 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.50 | CoJoMo, Gabe, mds, shutout, xaler         |
|           44 |      688 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.79 | CoJoMo, Gabe, mds, shutout, xaler         |
|           43 |      748 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.56 | CoJoMo, Gabe, mds, shutout, xaler         |
|           42 |      754 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -17.00 | CoJoMo, Gabe, mds, shutout, xaler         |
|           41 |     1101 | 2024-06-14 | Akimbo           | L   | 0.848      | -            | -                | -                | -         |   -11.38 | CoJoMo, Gabe, mds, shutout, xaler         |
|           40 |     1553 | 2024-06-04 | Mythic           | L   | 0.781      | -            | -                | -                | -         |   -10.43 | CoJoMo, Gabe, Louie, mds, shutout         |
|           39 |     1854 | 2024-05-22 | BOSS             | L   | 0.696      | -            | -                | -                | -         |   -10.51 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           38 |     1858 | 2024-05-22 | BOSS             | W   | 0.696      | 0.477        | 0.014 (0.005)    | 0.319 (0.106)    | 0 (0.000) |    11.67 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           37 |     1903 | 2024-05-21 | NRG              | W   | 0.690      | 0.477        | 0.020 (0.007)    | 0.502 (0.165)    | 0 (0.000) |    16.00 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           36 |     1905 | 2024-05-21 | NRG              | L   | 0.689      | -            | -                | -                | -         |    -5.64 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           35 |     1938 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.683      | -            | -                | -                | -         |   -11.75 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           34 |     1942 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.682      | 0.477        | 0.003 (0.001)    | 0.304 (0.099)    | 0 (0.000) |     9.90 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           33 |     2105 | 2024-05-15 | Mythic           | L   | 0.650      | -            | -                | -                | -         |    -9.39 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           32 |     2111 | 2024-05-15 | Mythic           | W   | 0.649      | 0.477        | 0.010 (0.003)    | 0.285 (0.088)    | 0 (0.000) |    11.33 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           31 |     2172 | 2024-05-14 | Elevate          | L   | 0.642      | -            | -                | -                | -         |    -4.27 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           30 |     2175 | 2024-05-14 | Elevate          | L   | 0.642      | -            | -                | -                | -         |    -4.43 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           29 |     2229 | 2024-05-12 | NRG              | L   | 0.629      | -            | -                | -                | -         |    -6.20 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           28 |     2236 | 2024-05-12 | Mythic           | W   | 0.628      | 0.270        | 0.010 (0.002)    | 0.285 (0.048)    | 0 (0.000) |    10.97 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           27 |     2256 | 2024-05-11 | BOSS             | W   | 0.622      | 0.270        | 0.014 (0.002)    | 0.319 (0.054)    | 0 (0.000) |    11.72 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           26 |     2259 | 2024-05-11 | NRG              | L   | 0.622      | -            | -                | -                | -         |    -6.18 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           25 |     2262 | 2024-05-11 | Party Astronauts | W   | 0.621      | 0.270        | 0.041 (0.007)    | 0.510 (0.086)    | 0 (0.000) |    15.06 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           24 |     2325 | 2024-05-08 | Nouns            | L   | 0.603      | -            | -                | -                | -         |    -4.59 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           23 |     2327 | 2024-05-08 | Nouns            | L   | 0.603      | -            | -                | -                | -         |    -4.77 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           22 |     2837 | 2024-04-17 | Nouns            | L   | 0.462      | -            | -                | -                | -         |    -3.55 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           21 |     2989 | 2024-04-10 | MIGHT            | L   | 0.416      | -            | -                | -                | -         |   -10.12 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           20 |     2994 | 2024-04-10 | MIGHT            | W   | 0.416      | -            | -                | -                | 0 (0.000) |     3.00 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           19 |     3172 | 2024-04-04 | Carpe Diem       | W   | 0.376      | 0.477        | 0.005 (0.001)    | -                | -         |     4.82 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           18 |     3177 | 2024-04-04 | Carpe Diem       | W   | 0.376      | 0.477        | 0.005 (0.001)    | -                | -         |     4.97 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           17 |     3220 | 2024-04-03 | Limitless        | W   | 0.370      | 0.477        | -                | 0.159 (0.028)    | -         |     4.61 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           16 |     3222 | 2024-04-03 | Limitless        | W   | 0.369      | 0.477        | -                | 0.159 (0.028)    | -         |     4.75 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           15 |     3270 | 2024-04-02 | Party Astronauts | L   | 0.363      | -            | -                | -                | -         |    -2.79 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           14 |     3274 | 2024-04-02 | BOSS             | L   | 0.362      | -            | -                | -                | -         |    -4.59 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           13 |     3357 | 2024-03-27 | M80              | L   | 0.323      | -            | -                | -                | -         |    -0.64 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           12 |     3363 | 2024-03-27 | M80              | L   | 0.323      | -            | -                | -                | -         |    -0.64 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           11 |     3482 | 2024-03-20 | LAG              | W   | 0.276      | 0.477        | 0.012 (0.002)    | 0.376 (0.050)    | -         |     5.70 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|           10 |     3484 | 2024-03-20 | LAG              | L   | 0.276      | -            | -                | -                | -         |    -3.05 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            9 |     3500 | 2024-03-19 | Party Astronauts | L   | 0.270      | -            | -                | -                | -         |    -2.09 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            8 |     3502 | 2024-03-19 | Party Astronauts | L   | 0.270      | -            | -                | -                | -         |    -2.12 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            7 |     3597 | 2024-03-14 | Wildcard         | L   | 0.236      | -            | -                | -                | -         |    -2.29 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            6 |     3600 | 2024-03-14 | Wildcard         | L   | 0.236      | -            | -                | -                | -         |    -2.33 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            5 |     3629 | 2024-03-13 | Mythic           | W   | 0.229      | -            | -                | -                | -         |     4.11 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            4 |     3672 | 2024-03-12 | bubibabu         | W   | 0.223      | -            | -                | -                | -         |     0.94 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            3 |     4098 | 2024-02-22 | MIGHT            | L   | 0.096      | -            | -                | -                | -         |    -2.30 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            2 |     4342 | 2024-02-13 | Take Flyte       | L   | 0.037      | -            | -                | -                | -         |    -0.62 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            1 |     4345 | 2024-02-13 | Take Flyte       | W   | 0.036      | -            | -                | -                | -         |     0.54 | BeaKie, CoJoMo, Gabe, mds, shutout        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,305.33)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
