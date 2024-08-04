### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, micro, SLIGHT<br />
Global Rank: [124](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
<br />
Final Rank Value:  793.3<br />
<br />
Final Rank Value (793.3) = Starting Rank Value (806.1) + Head To Head Adjustments (-12.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.351[<sup>1</sup>](#table2)
- Bounty Collected: 0.305[<sup>2</sup>](#table1)
- Opponent Network: 0.120[<sup>2</sup>](#table1)
- LAN Wins: 0.019[<sup>2</sup>](#table1)

The average of these factors is 0.199<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 806.1
- 400 + ( ( 0.199 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 806.1


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
|           57 |      102 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.15 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           56 |      106 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.74 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           55 |      152 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.50 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           54 |      153 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -8.01 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           53 |      473 | 2024-07-20 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.72 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           52 |      542 | 2024-07-18 | Elevate           | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    21.82 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           51 |      544 | 2024-07-18 | Elevate           | L   | 1.000      | -            | -                | -                | -         |    -9.23 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           50 |      604 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.341 (0.162)    | 0 (0.000) |    17.09 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           49 |      611 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.341 (0.162)    | 0 (0.000) |    18.64 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           48 |      720 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.300 (0.143)    | 0 (0.000) |    17.01 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           47 |      980 | 2024-06-15 | Elevate           | L   | 0.871      | -            | -                | -                | -         |    -6.59 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           46 |     1029 | 2024-06-14 | Final Form        | W   | 0.862      | -            | -                | -                | 0 (0.000) |     6.16 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           45 |     1466 | 2024-06-04 | Mythic            | L   | 0.797      | -            | -                | -                | -         |   -11.20 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           44 |     1776 | 2024-05-22 | Perseverance      | W   | 0.711      | 0.477        | -                | 0.244 (0.083)    | 0 (0.000) |    10.75 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           43 |     1780 | 2024-05-22 | Perseverance      | L   | 0.711      | -            | -                | -                | -         |   -11.89 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           42 |     1861 | 2024-05-20 | Limitless         | L   | 0.698      | -            | -                | -                | -         |   -10.98 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           41 |     1865 | 2024-05-20 | Limitless         | W   | 0.697      | -            | -                | -                | 0 (0.000) |    11.20 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           40 |     1896 | 2024-05-19 | M80               | L   | 0.690      | -            | -                | -                | -         |    -1.54 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           39 |     1897 | 2024-05-19 | M80               | L   | 0.690      | -            | -                | -                | -         |    -1.56 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           38 |     1960 | 2024-05-17 | NRG               | L   | 0.677      | -            | -                | -                | -         |    -6.69 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     2024 | 2024-05-15 | Wildcard          | L   | 0.664      | -            | -                | -                | -         |    -6.73 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     2034 | 2024-05-15 | Wildcard          | L   | 0.664      | -            | -                | -                | -         |    -7.09 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     2083 | 2024-05-14 | MIGHT             | W   | 0.658      | -            | -                | -                | 0 (0.000) |     3.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     2091 | 2024-05-14 | MIGHT             | W   | 0.657      | -            | -                | -                | 0 (0.000) |     3.72 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     2178 | 2024-05-11 | Perseverance      | L   | 0.637      | -            | -                | -                | -         |   -11.95 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     2180 | 2024-05-11 | Party Astronauts  | W   | 0.636      | 0.270        | 0.041 (0.007)    | 0.531 (0.091)    | -         |    13.58 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     2183 | 2024-05-11 | NRG               | L   | 0.636      | -            | -                | -                | -         |    -8.13 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     2222 | 2024-05-09 | Nouns             | L   | 0.624      | -            | -                | -                | -         |    -6.25 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     2227 | 2024-05-09 | Nouns             | L   | 0.624      | -            | -                | -                | -         |    -6.57 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2343 | 2024-05-03 | Ninjas in Pyjamas | L   | 0.582      | -            | -                | -                | -         |    -0.24 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           27 |     2380 | 2024-05-02 | FlyQuest          | L   | 0.574      | -            | -                | -                | -         |    -2.16 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           26 |     2401 | 2024-05-01 | BIG               | L   | 0.567      | -            | -                | -                | -         |    -1.24 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           25 |     2548 | 2024-04-24 | Mythic            | L   | 0.525      | -            | -                | -                | -         |    -9.92 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           24 |     2549 | 2024-04-24 | Mythic            | W   | 0.524      | 0.477        | 0.010 (0.002)    | 0.300 (0.075)    | -         |     6.70 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           23 |     2878 | 2024-04-11 | Limitless         | W   | 0.438      | -            | -                | -                | -         |     3.76 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           22 |     2880 | 2024-04-11 | Limitless         | W   | 0.438      | -            | -                | -                | -         |     3.88 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           21 |     2909 | 2024-04-10 | NRG               | L   | 0.431      | -            | -                | -                | -         |    -6.16 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           20 |     2913 | 2024-04-10 | NRG               | W   | 0.431      | 0.477        | 0.020 (0.004)    | 0.521 (0.107)    | -         |     7.59 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           19 |     2966 | 2024-04-09 | LAG               | W   | 0.424      | 0.477        | 0.012 (0.002)    | 0.341 (0.069)    | -         |     7.44 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           18 |     2969 | 2024-04-09 | LAG               | W   | 0.424      | 0.477        | 0.012 (0.002)    | 0.341 (0.069)    | -         |     7.72 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           17 |     3098 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.391      | -            | -                | -                | -         |     5.44 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           16 |     3104 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.391      | -            | -                | -                | -         |     5.63 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           15 |     3155 | 2024-04-03 | Party Astronauts  | L   | 0.383      | -            | -                | -                | -         |    -9.96 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           14 |     3191 | 2024-04-02 | Nouns             | L   | 0.378      | -            | -                | -                | -         |    -3.96 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           13 |     3196 | 2024-04-02 | Perseverance      | W   | 0.377      | -            | -                | -                | -         |     4.82 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           12 |     3272 | 2024-03-27 | Take Flyte        | W   | 0.338      | -            | -                | -                | -         |     4.03 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           11 |     3275 | 2024-03-27 | Take Flyte        | L   | 0.338      | -            | -                | -                | -         |    -6.75 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           10 |     3320 | 2024-03-26 | Elevate           | L   | 0.331      | -            | -                | -                | -         |    -2.64 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            9 |     3325 | 2024-03-26 | Elevate           | L   | 0.331      | -            | -                | -                | -         |    -2.70 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            8 |     3401 | 2024-03-20 | Party Astronauts  | L   | 0.291      | -            | -                | -                | -         |    -2.95 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            7 |     3403 | 2024-03-20 | Party Astronauts  | L   | 0.291      | -            | -                | -                | -         |    -3.02 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            6 |     3837 | 2024-03-03 | Liquid            | L   | 0.175      | -            | -                | -                | -         |    -0.12 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            5 |     3854 | 2024-03-02 | Complexity        | L   | 0.168      | -            | -                | -                | -         |    -0.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            4 |     3869 | 2024-03-01 | MIBR              | W   | 0.163      | 0.143        | 0.209 (0.005)    | -                | 1 (0.163) |     4.97 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            3 |     3938 | 2024-02-26 | Liquid            | L   | 0.137      | -            | -                | -                | -         |    -0.09 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            2 |     3952 | 2024-02-25 | Nouns             | L   | 0.131      | -            | -                | -                | -         |    -1.49 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            1 |     3955 | 2024-02-25 | Wildcard          | W   | 0.130      | -            | -                | -                | -         |     2.64 | brett, Cryptic, d4rty, freshie, PwnAlone |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,564.20)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.878 | $750.00        | $658.23         |
| 2024-06-09 |      0.831 | $2,000.00      | $1,661.11       |
| 2024-05-12 |      0.641 | $3,500.00      | $2,244.86       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
