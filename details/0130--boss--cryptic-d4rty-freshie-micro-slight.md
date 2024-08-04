### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, micro, SLIGHT<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  783.4<br />
<br />
Final Rank Value (783.4) = Starting Rank Value (807.9) + Head To Head Adjustments (-24.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.351[<sup>1</sup>](#table2)
- Bounty Collected: 0.305[<sup>2</sup>](#table1)
- Opponent Network: 0.124[<sup>2</sup>](#table1)
- LAN Wins: 0.018[<sup>2</sup>](#table1)

The average of these factors is 0.199<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 807.9
- 400 + ( ( 0.199 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 807.9


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
|           58 |       25 | 2024-08-03 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -7.77 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           57 |      133 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.31 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           56 |      137 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.91 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           55 |      183 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.45 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           54 |      184 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.95 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           53 |      504 | 2024-07-20 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.73 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           52 |      573 | 2024-07-18 | Elevate           | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.521 (0.248)    | 0 (0.000) |    21.88 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           51 |      575 | 2024-07-18 | Elevate           | L   | 1.000      | -            | -                | -                | -         |    -9.16 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           50 |      635 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.353 (0.169)    | 0 (0.000) |    16.37 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           49 |      642 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.353 (0.169)    | 0 (0.000) |    17.87 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           48 |      751 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.299 (0.143)    | 0 (0.000) |    16.94 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           47 |     1011 | 2024-06-15 | Elevate           | L   | 0.870      | -            | -                | -                | -         |    -6.55 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           46 |     1060 | 2024-06-14 | Final Form        | W   | 0.861      | -            | -                | -                | 0 (0.000) |     6.17 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           45 |     1497 | 2024-06-04 | Mythic            | L   | 0.796      | -            | -                | -                | -         |   -11.20 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           44 |     1807 | 2024-05-22 | Phoenix           | W   | 0.710      | 0.477        | -                | 0.283 (0.096)    | 0 (0.000) |    10.72 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           43 |     1811 | 2024-05-22 | Phoenix           | L   | 0.709      | -            | -                | -                | -         |   -11.87 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           42 |     1892 | 2024-05-20 | Limitless         | L   | 0.696      | -            | -                | -                | -         |   -10.94 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           41 |     1896 | 2024-05-20 | Limitless         | W   | 0.696      | -            | -                | -                | 0 (0.000) |    11.19 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           40 |     1927 | 2024-05-19 | M80               | L   | 0.689      | -            | -                | -                | -         |    -1.52 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           39 |     1928 | 2024-05-19 | M80               | L   | 0.689      | -            | -                | -                | -         |    -1.55 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           38 |     1991 | 2024-05-17 | NRG               | L   | 0.675      | -            | -                | -                | -         |    -6.72 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     2055 | 2024-05-15 | Wildcard          | L   | 0.663      | -            | -                | -                | -         |    -7.30 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     2065 | 2024-05-15 | Wildcard          | L   | 0.663      | -            | -                | -                | -         |    -7.70 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     2114 | 2024-05-14 | MIGHT             | W   | 0.656      | -            | -                | -                | 0 (0.000) |     3.57 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     2122 | 2024-05-14 | MIGHT             | W   | 0.656      | -            | -                | -                | 0 (0.000) |     3.69 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     2209 | 2024-05-11 | Phoenix           | L   | 0.635      | -            | -                | -                | -         |   -11.96 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     2211 | 2024-05-11 | Party Astronauts  | W   | 0.635      | 0.270        | 0.041 (0.007)    | 0.531 (0.091)    | -         |    13.46 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     2214 | 2024-05-11 | NRG               | L   | 0.634      | -            | -                | -                | -         |    -8.19 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     2253 | 2024-05-09 | Nouns             | L   | 0.623      | -            | -                | -                | -         |    -6.26 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     2258 | 2024-05-09 | Nouns             | L   | 0.623      | -            | -                | -                | -         |    -6.58 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2374 | 2024-05-03 | Ninjas in Pyjamas | L   | 0.581      | -            | -                | -                | -         |    -0.23 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           27 |     2411 | 2024-05-02 | FlyQuest          | L   | 0.572      | -            | -                | -                | -         |    -2.15 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           26 |     2432 | 2024-05-01 | BIG               | L   | 0.566      | -            | -                | -                | -         |    -1.24 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           25 |     2579 | 2024-04-24 | Mythic            | L   | 0.523      | -            | -                | -                | -         |    -9.93 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           24 |     2580 | 2024-04-24 | Mythic            | W   | 0.523      | 0.477        | 0.010 (0.002)    | 0.299 (0.075)    | -         |     6.65 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           23 |     2909 | 2024-04-11 | Limitless         | W   | 0.436      | -            | -                | -                | -         |     3.74 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           22 |     2911 | 2024-04-11 | Limitless         | W   | 0.436      | -            | -                | -                | -         |     3.85 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           21 |     2940 | 2024-04-10 | NRG               | L   | 0.430      | -            | -                | -                | -         |    -6.16 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           20 |     2944 | 2024-04-10 | NRG               | W   | 0.429      | 0.477        | 0.020 (0.004)    | 0.521 (0.107)    | -         |     7.54 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           19 |     2997 | 2024-04-09 | LAG               | W   | 0.423      | 0.477        | 0.012 (0.002)    | 0.353 (0.071)    | -         |     7.19 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           18 |     3000 | 2024-04-09 | LAG               | W   | 0.423      | 0.477        | 0.012 (0.002)    | 0.353 (0.071)    | -         |     7.46 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           17 |     3129 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.389      | -            | -                | -                | -         |     5.39 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           16 |     3135 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.389      | -            | -                | -                | -         |     5.57 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           15 |     3186 | 2024-04-03 | Party Astronauts  | L   | 0.382      | -            | -                | -                | -         |    -9.93 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           14 |     3222 | 2024-04-02 | Nouns             | L   | 0.376      | -            | -                | -                | -         |    -3.97 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           13 |     3227 | 2024-04-02 | Phoenix           | W   | 0.375      | -            | -                | -                | -         |     4.76 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           12 |     3303 | 2024-03-27 | Take Flyte        | W   | 0.337      | -            | -                | -                | -         |     4.02 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           11 |     3306 | 2024-03-27 | Take Flyte        | L   | 0.336      | -            | -                | -                | -         |    -6.72 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           10 |     3351 | 2024-03-26 | Elevate           | L   | 0.330      | -            | -                | -                | -         |    -2.59 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            9 |     3356 | 2024-03-26 | Elevate           | L   | 0.330      | -            | -                | -                | -         |    -2.65 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            8 |     3432 | 2024-03-20 | Party Astronauts  | L   | 0.290      | -            | -                | -                | -         |    -2.98 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            7 |     3434 | 2024-03-20 | Party Astronauts  | L   | 0.290      | -            | -                | -                | -         |    -3.04 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            6 |     3868 | 2024-03-03 | Liquid            | L   | 0.174      | -            | -                | -                | -         |    -0.07 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            5 |     3885 | 2024-03-02 | Complexity        | L   | 0.167      | -            | -                | -                | -         |    -0.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            4 |     3900 | 2024-03-01 | MIBR              | W   | 0.161      | 0.143        | 0.209 (0.005)    | -                | 1 (0.161) |     4.92 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            3 |     3969 | 2024-02-26 | Liquid            | L   | 0.135      | -            | -                | -                | -         |    -0.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            2 |     3983 | 2024-02-25 | Nouns             | L   | 0.130      | -            | -                | -                | -         |    -1.48 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            1 |     3986 | 2024-02-25 | Wildcard          | W   | 0.129      | -            | -                | -                | -         |     2.43 | brett, Cryptic, d4rty, freshie, PwnAlone |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,554.94)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.876 | $750.00        | $657.12         |
| 2024-06-09 |      0.829 | $2,000.00      | $1,658.15       |
| 2024-05-12 |      0.640 | $3,500.00      | $2,239.68       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
