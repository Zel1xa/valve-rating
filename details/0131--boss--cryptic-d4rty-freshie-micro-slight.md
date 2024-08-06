### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, micro, SLIGHT<br />
Global Rank: [131](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  783.0<br />
<br />
Final Rank Value (783.0) = Starting Rank Value (808.2) + Head To Head Adjustments (-25.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.122[<sup>2</sup>](#table1)
- LAN Wins: 0.017[<sup>2</sup>](#table1)

The average of these factors is 0.198<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 808.2
- 400 + ( ( 0.198 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 808.2


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
|           58 |       72 | 2024-08-03 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -7.80 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           57 |      180 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.34 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           56 |      184 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.95 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           55 |      230 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.50 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           54 |      231 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -8.01 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           53 |      551 | 2024-07-20 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.78 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           52 |      620 | 2024-07-18 | Elevate           | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.501 (0.239)    | 0 (0.000) |    21.85 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           51 |      622 | 2024-07-18 | Elevate           | L   | 1.000      | -            | -                | -                | -         |    -9.20 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           50 |      682 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | 0 (0.000) |    16.32 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           49 |      689 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | 0 (0.000) |    17.82 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           48 |      798 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.285 (0.136)    | 0 (0.000) |    16.89 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           47 |     1058 | 2024-06-15 | Elevate           | L   | 0.857      | -            | -                | -                | -         |    -6.49 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           46 |     1107 | 2024-06-14 | Final Form        | W   | 0.847      | -            | -                | -                | 0 (0.000) |     6.22 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           45 |     1544 | 2024-06-04 | Mythic            | L   | 0.783      | -            | -                | -                | -         |   -11.05 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           44 |     1854 | 2024-05-22 | Phoenix           | W   | 0.696      | 0.477        | -                | 0.270 (0.090)    | 0 (0.000) |    10.51 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           43 |     1858 | 2024-05-22 | Phoenix           | L   | 0.696      | -            | -                | -                | -         |   -11.67 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           42 |     1939 | 2024-05-20 | Limitless         | L   | 0.683      | -            | -                | -                | -         |   -10.76 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           41 |     1943 | 2024-05-20 | Limitless         | W   | 0.682      | -            | -                | -                | 0 (0.000) |    10.96 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           40 |     1974 | 2024-05-19 | M80               | L   | 0.676      | -            | -                | -                | -         |    -1.52 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           39 |     1975 | 2024-05-19 | M80               | L   | 0.675      | -            | -                | -                | -         |    -1.54 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           38 |     2038 | 2024-05-17 | NRG               | L   | 0.662      | -            | -                | -                | -         |    -6.63 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     2102 | 2024-05-15 | Wildcard          | L   | 0.650      | -            | -                | -                | -         |    -7.21 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     2112 | 2024-05-15 | Wildcard          | L   | 0.649      | -            | -                | -                | -         |    -7.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     2161 | 2024-05-14 | MIGHT             | W   | 0.643      | -            | -                | -                | 0 (0.000) |     3.49 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     2169 | 2024-05-14 | MIGHT             | W   | 0.642      | -            | -                | -                | 0 (0.000) |     3.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     2256 | 2024-05-11 | Phoenix           | L   | 0.622      | -            | -                | -                | -         |   -11.72 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     2258 | 2024-05-11 | Party Astronauts  | W   | 0.622      | 0.270        | 0.041 (0.007)    | 0.510 (0.086)    | -         |    13.15 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     2261 | 2024-05-11 | NRG               | L   | 0.621      | -            | -                | -                | -         |    -8.04 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     2300 | 2024-05-09 | Nouns             | L   | 0.610      | -            | -                | -                | -         |    -6.19 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     2305 | 2024-05-09 | Nouns             | L   | 0.609      | -            | -                | -                | -         |    -6.49 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2421 | 2024-05-03 | Ninjas in Pyjamas | L   | 0.567      | -            | -                | -                | -         |    -0.22 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           27 |     2458 | 2024-05-02 | FlyQuest          | L   | 0.559      | -            | -                | -                | -         |    -2.17 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           26 |     2479 | 2024-05-01 | BIG               | L   | 0.552      | -            | -                | -                | -         |    -1.22 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           25 |     2626 | 2024-04-24 | Mythic            | L   | 0.510      | -            | -                | -                | -         |    -9.66 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           24 |     2627 | 2024-04-24 | Mythic            | W   | 0.509      | 0.477        | 0.010 (0.002)    | 0.285 (0.069)    | -         |     6.50 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           23 |     2956 | 2024-04-11 | Limitless         | W   | 0.423      | -            | -                | -                | -         |     3.64 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           22 |     2958 | 2024-04-11 | Limitless         | W   | 0.423      | -            | -                | -                | -         |     3.75 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           21 |     2987 | 2024-04-10 | NRG               | L   | 0.416      | -            | -                | -                | -         |    -5.97 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           20 |     2991 | 2024-04-10 | NRG               | W   | 0.416      | 0.477        | 0.020 (0.004)    | 0.502 (0.100)    | -         |     7.30 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           19 |     3044 | 2024-04-09 | LAG               | W   | 0.410      | 0.477        | 0.012 (0.002)    | 0.376 (0.073)    | -         |     6.93 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           18 |     3047 | 2024-04-09 | LAG               | W   | 0.409      | 0.477        | 0.012 (0.002)    | 0.376 (0.073)    | -         |     7.18 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           17 |     3176 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.376      | -            | -                | -                | -         |     5.20 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           16 |     3182 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.376      | -            | -                | -                | -         |     5.37 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           15 |     3233 | 2024-04-03 | Party Astronauts  | L   | 0.368      | -            | -                | -                | -         |    -9.59 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           14 |     3269 | 2024-04-02 | Nouns             | L   | 0.363      | -            | -                | -                | -         |    -3.88 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           13 |     3274 | 2024-04-02 | Phoenix           | W   | 0.362      | -            | -                | -                | -         |     4.59 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           12 |     3350 | 2024-03-27 | Take Flyte        | W   | 0.323      | -            | -                | -                | -         |     3.86 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           11 |     3353 | 2024-03-27 | Take Flyte        | L   | 0.323      | -            | -                | -                | -         |    -6.45 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           10 |     3398 | 2024-03-26 | Elevate           | L   | 0.317      | -            | -                | -                | -         |    -2.51 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            9 |     3403 | 2024-03-26 | Elevate           | L   | 0.316      | -            | -                | -                | -         |    -2.56 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            8 |     3479 | 2024-03-20 | Party Astronauts  | L   | 0.277      | -            | -                | -                | -         |    -2.87 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            7 |     3481 | 2024-03-20 | Party Astronauts  | L   | 0.276      | -            | -                | -                | -         |    -2.93 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            6 |     3915 | 2024-03-03 | Liquid            | L   | 0.160      | -            | -                | -                | -         |    -0.06 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            5 |     3932 | 2024-03-02 | Complexity        | L   | 0.154      | -            | -                | -                | -         |    -0.04 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            4 |     3947 | 2024-03-01 | MIBR              | W   | 0.148      | 0.143        | 0.208 (0.004)    | -                | 1 (0.148) |     4.51 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            3 |     4016 | 2024-02-26 | Liquid            | L   | 0.122      | -            | -                | -                | -         |    -0.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            2 |     4030 | 2024-02-25 | Nouns             | L   | 0.117      | -            | -                | -                | -         |    -1.34 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            1 |     4033 | 2024-02-25 | Wildcard          | W   | 0.115      | -            | -                | -                | -         |     2.17 | brett, Cryptic, d4rty, freshie, PwnAlone |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,472.19)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.863 | $750.00        | $647.19         |
| 2024-06-09 |      0.816 | $2,000.00      | $1,631.67       |
| 2024-05-12 |      0.627 | $3,500.00      | $2,193.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
