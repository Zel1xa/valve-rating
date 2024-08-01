### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, micro, SLIGHT<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [31]( ../standings_americas.md)<br />
<br />
Final Rank Value:  807.2<br />
<br />
Final Rank Value (807.2) = Starting Rank Value (818.5) + Head To Head Adjustments (-11.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.352[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.133[<sup>2</sup>](#table1)
- LAN Wins: 0.021[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 818.5
- 400 + ( ( 0.203 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 818.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           59 |       20 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.27 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           58 |       24 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.87 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           57 |       70 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.50 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           56 |       71 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -8.00 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           55 |      393 | 2024-07-20 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.87 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           54 |      465 | 2024-07-18 | Elevate           | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    21.31 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           53 |      468 | 2024-07-18 | Elevate           | L   | 1.000      | -            | -                | -                | -         |    -9.76 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           52 |      531 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.371 (0.177)    | 0 (0.000) |    17.04 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           51 |      538 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.371 (0.177)    | 0 (0.000) |    18.58 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           50 |      652 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.303 (0.145)    | 0 (0.000) |    15.90 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           49 |      655 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.303 (0.145)    | 0 (0.000) |    17.37 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           48 |      913 | 2024-06-15 | Elevate           | L   | 0.889      | -            | -                | -                | -         |    -6.75 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           47 |      954 | 2024-06-14 | Final Form        | W   | 0.880      | -            | -                | -                | 0 (0.000) |     6.38 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           46 |     1406 | 2024-06-04 | Mythic            | L   | 0.815      | -            | -                | -                | -         |   -11.14 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           45 |     1719 | 2024-05-22 | Perseverance      | W   | 0.729      | 0.477        | -                | 0.247 (0.086)    | 0 (0.000) |    11.09 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           44 |     1723 | 2024-05-22 | Perseverance      | L   | 0.729      | -            | -                | -                | -         |   -12.10 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           43 |     1802 | 2024-05-21 | LAG               | L   | 0.720      | -            | -                | -                | -         |   -10.01 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           42 |     1820 | 2024-05-20 | Limitless         | L   | 0.715      | -            | -                | -                | -         |   -11.33 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           41 |     1824 | 2024-05-20 | Limitless         | W   | 0.715      | -            | -                | -                | 0 (0.000) |    11.40 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           40 |     1859 | 2024-05-19 | M80               | L   | 0.708      | -            | -                | -                | -         |    -1.50 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           39 |     1862 | 2024-05-19 | M80               | L   | 0.708      | -            | -                | -                | -         |    -1.53 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           38 |     1929 | 2024-05-17 | NRG               | L   | 0.694      | -            | -                | -                | -         |    -6.90 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     1993 | 2024-05-15 | Wildcard          | L   | 0.682      | -            | -                | -                | -         |    -6.94 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     2003 | 2024-05-15 | Wildcard          | L   | 0.682      | -            | -                | -                | -         |    -7.32 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     2058 | 2024-05-14 | MIGHT             | W   | 0.675      | -            | -                | -                | 0 (0.000) |     3.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     2066 | 2024-05-14 | MIGHT             | W   | 0.675      | -            | -                | -                | -         |     3.72 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     2156 | 2024-05-11 | Perseverance      | L   | 0.654      | -            | -                | -                | -         |   -12.40 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     2158 | 2024-05-11 | Party Astronauts  | W   | 0.654      | 0.270        | 0.042 (0.007)    | 0.532 (0.094)    | -         |    13.93 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     2161 | 2024-05-11 | NRG               | L   | 0.654      | -            | -                | -                | -         |    -8.46 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     2200 | 2024-05-09 | Nouns             | L   | 0.642      | -            | -                | -                | -         |    -6.49 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     2205 | 2024-05-09 | Nouns             | L   | 0.642      | -            | -                | -                | -         |    -6.82 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2323 | 2024-05-03 | Ninjas in Pyjamas | L   | 0.600      | -            | -                | -                | -         |    -0.49 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           27 |     2361 | 2024-05-02 | FlyQuest          | L   | 0.592      | -            | -                | -                | -         |    -2.15 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           26 |     2383 | 2024-05-01 | BIG               | L   | 0.585      | -            | -                | -                | -         |    -1.92 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           25 |     2531 | 2024-04-24 | Mythic            | L   | 0.542      | -            | -                | -                | -         |   -10.39 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           24 |     2532 | 2024-04-24 | Mythic            | W   | 0.542      | 0.477        | -                | 0.303 (0.078)    | -         |     6.79 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           23 |     2872 | 2024-04-11 | Limitless         | W   | 0.455      | -            | -                | -                | -         |     3.77 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           22 |     2874 | 2024-04-11 | Limitless         | W   | 0.455      | -            | -                | -                | -         |     3.89 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           21 |     2903 | 2024-04-10 | NRG               | L   | 0.449      | -            | -                | -                | -         |    -6.55 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           20 |     2907 | 2024-04-10 | NRG               | W   | 0.449      | 0.477        | 0.020 (0.004)    | 0.519 (0.111)    | -         |     7.77 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           19 |     2960 | 2024-04-09 | LAG               | W   | 0.442      | 0.477        | 0.013 (0.003)    | 0.371 (0.078)    | -         |     7.71 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           18 |     2963 | 2024-04-09 | LAG               | W   | 0.442      | 0.477        | 0.013 (0.003)    | -                | -         |     8.01 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           17 |     3092 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.409      | -            | -                | -                | -         |     5.61 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           16 |     3098 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.408      | -            | -                | -                | -         |     5.81 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           15 |     3150 | 2024-04-03 | Party Astronauts  | L   | 0.401      | -            | -                | -                | -         |   -10.51 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           14 |     3193 | 2024-04-02 | Nouns             | L   | 0.396      | -            | -                | -                | -         |    -4.22 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           13 |     3198 | 2024-04-02 | Perseverance      | W   | 0.394      | -            | -                | -                | -         |     4.93 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           12 |     3274 | 2024-03-27 | Take Flyte        | W   | 0.356      | -            | -                | -                | -         |     4.13 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           11 |     3277 | 2024-03-27 | Take Flyte        | L   | 0.356      | -            | -                | -                | -         |    -7.23 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           10 |     3323 | 2024-03-26 | Elevate           | L   | 0.349      | -            | -                | -                | -         |    -2.80 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            9 |     3328 | 2024-03-26 | Elevate           | L   | 0.349      | -            | -                | -                | -         |    -2.86 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            8 |     3408 | 2024-03-20 | Party Astronauts  | L   | 0.309      | -            | -                | -                | -         |    -3.17 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            7 |     3410 | 2024-03-20 | Party Astronauts  | L   | 0.309      | -            | -                | -                | -         |    -3.24 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            6 |     3855 | 2024-03-03 | Liquid            | L   | 0.193      | -            | -                | -                | -         |    -0.12 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            5 |     3872 | 2024-03-02 | Complexity        | L   | 0.186      | -            | -                | -                | -         |    -0.06 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            4 |     3888 | 2024-03-01 | MIBR              | W   | 0.181      | 0.143        | 0.201 (0.005)    | -                | 1 (0.181) |     5.50 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            3 |     3958 | 2024-02-26 | Liquid            | L   | 0.155      | -            | -                | -                | -         |    -0.09 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            2 |     3973 | 2024-02-25 | Nouns             | L   | 0.149      | -            | -                | -                | -         |    -1.73 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            1 |     3976 | 2024-02-25 | Wildcard          | W   | 0.148      | -            | -                | -                | -         |     2.98 | brett, Cryptic, d4rty, freshie, PwnAlone |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,675.31)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.895 | $750.00        | $671.56         |
| 2024-06-09 |      0.848 | $2,000.00      | $1,696.67       |
| 2024-05-12 |      0.659 | $3,500.00      | $2,307.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
