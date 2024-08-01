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
|           59 |       17 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.27 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           58 |       21 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.87 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           57 |       67 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.50 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           56 |       68 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -8.00 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           55 |      391 | 2024-07-20 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.87 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           54 |      463 | 2024-07-18 | Elevate           | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    21.31 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           53 |      466 | 2024-07-18 | Elevate           | L   | 1.000      | -            | -                | -                | -         |    -9.76 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           52 |      529 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.371 (0.177)    | 0 (0.000) |    17.04 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           51 |      536 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.371 (0.177)    | 0 (0.000) |    18.58 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           50 |      650 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.304 (0.145)    | 0 (0.000) |    15.90 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           49 |      653 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.304 (0.145)    | 0 (0.000) |    17.37 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           48 |      911 | 2024-06-15 | Elevate           | L   | 0.889      | -            | -                | -                | -         |    -6.75 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           47 |      952 | 2024-06-14 | Final Form        | W   | 0.880      | -            | -                | -                | 0 (0.000) |     6.38 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           46 |     1404 | 2024-06-04 | Mythic            | L   | 0.816      | -            | -                | -                | -         |   -11.15 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           45 |     1717 | 2024-05-22 | Perseverance      | W   | 0.729      | 0.477        | -                | 0.247 (0.086)    | 0 (0.000) |    11.10 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           44 |     1721 | 2024-05-22 | Perseverance      | L   | 0.729      | -            | -                | -                | -         |   -12.10 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           43 |     1800 | 2024-05-21 | LAG               | L   | 0.720      | -            | -                | -                | -         |   -10.01 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           42 |     1818 | 2024-05-20 | Limitless         | L   | 0.716      | -            | -                | -                | -         |   -11.34 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           41 |     1822 | 2024-05-20 | Limitless         | W   | 0.715      | -            | -                | -                | 0 (0.000) |    11.41 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           40 |     1857 | 2024-05-19 | M80               | L   | 0.708      | -            | -                | -                | -         |    -1.51 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           39 |     1860 | 2024-05-19 | M80               | L   | 0.708      | -            | -                | -                | -         |    -1.53 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           38 |     1927 | 2024-05-17 | NRG               | L   | 0.695      | -            | -                | -                | -         |    -6.90 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     1991 | 2024-05-15 | Wildcard          | L   | 0.682      | -            | -                | -                | -         |    -6.94 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     2001 | 2024-05-15 | Wildcard          | L   | 0.682      | -            | -                | -                | -         |    -7.32 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     2056 | 2024-05-14 | MIGHT             | W   | 0.676      | -            | -                | -                | 0 (0.000) |     3.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     2064 | 2024-05-14 | MIGHT             | W   | 0.675      | -            | -                | -                | -         |     3.72 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     2154 | 2024-05-11 | Perseverance      | L   | 0.655      | -            | -                | -                | -         |   -12.41 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     2156 | 2024-05-11 | Party Astronauts  | W   | 0.654      | 0.270        | 0.042 (0.007)    | 0.532 (0.094)    | -         |    13.93 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     2159 | 2024-05-11 | NRG               | L   | 0.654      | -            | -                | -                | -         |    -8.47 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     2198 | 2024-05-09 | Nouns             | L   | 0.642      | -            | -                | -                | -         |    -6.49 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     2203 | 2024-05-09 | Nouns             | L   | 0.642      | -            | -                | -                | -         |    -6.83 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2321 | 2024-05-03 | Ninjas in Pyjamas | L   | 0.600      | -            | -                | -                | -         |    -0.49 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           27 |     2359 | 2024-05-02 | FlyQuest          | L   | 0.592      | -            | -                | -                | -         |    -2.15 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           26 |     2381 | 2024-05-01 | BIG               | L   | 0.585      | -            | -                | -                | -         |    -1.92 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           25 |     2529 | 2024-04-24 | Mythic            | L   | 0.543      | -            | -                | -                | -         |   -10.40 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           24 |     2530 | 2024-04-24 | Mythic            | W   | 0.542      | 0.477        | -                | 0.304 (0.078)    | -         |     6.79 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           23 |     2870 | 2024-04-11 | Limitless         | W   | 0.456      | -            | -                | -                | -         |     3.77 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           22 |     2872 | 2024-04-11 | Limitless         | W   | 0.456      | -            | -                | -                | -         |     3.89 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           21 |     2901 | 2024-04-10 | NRG               | L   | 0.449      | -            | -                | -                | -         |    -6.55 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           20 |     2905 | 2024-04-10 | NRG               | W   | 0.449      | 0.477        | 0.020 (0.004)    | 0.519 (0.111)    | -         |     7.77 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           19 |     2958 | 2024-04-09 | LAG               | W   | 0.443      | 0.477        | 0.013 (0.003)    | 0.371 (0.078)    | -         |     7.71 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           18 |     2961 | 2024-04-09 | LAG               | W   | 0.442      | 0.477        | 0.013 (0.003)    | -                | -         |     8.02 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           17 |     3090 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.409      | -            | -                | -                | -         |     5.61 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           16 |     3096 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.409      | -            | -                | -                | -         |     5.82 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           15 |     3148 | 2024-04-03 | Party Astronauts  | L   | 0.401      | -            | -                | -                | -         |   -10.52 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           14 |     3191 | 2024-04-02 | Nouns             | L   | 0.396      | -            | -                | -                | -         |    -4.22 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           13 |     3196 | 2024-04-02 | Perseverance      | W   | 0.395      | -            | -                | -                | -         |     4.93 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           12 |     3272 | 2024-03-27 | Take Flyte        | W   | 0.356      | -            | -                | -                | -         |     4.13 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           11 |     3275 | 2024-03-27 | Take Flyte        | L   | 0.356      | -            | -                | -                | -         |    -7.23 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           10 |     3321 | 2024-03-26 | Elevate           | L   | 0.349      | -            | -                | -                | -         |    -2.80 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            9 |     3326 | 2024-03-26 | Elevate           | L   | 0.349      | -            | -                | -                | -         |    -2.87 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            8 |     3406 | 2024-03-20 | Party Astronauts  | L   | 0.309      | -            | -                | -                | -         |    -3.17 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            7 |     3408 | 2024-03-20 | Party Astronauts  | L   | 0.309      | -            | -                | -                | -         |    -3.25 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            6 |     3853 | 2024-03-03 | Liquid            | L   | 0.193      | -            | -                | -                | -         |    -0.12 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            5 |     3870 | 2024-03-02 | Complexity        | L   | 0.186      | -            | -                | -                | -         |    -0.06 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            4 |     3886 | 2024-03-01 | MIBR              | W   | 0.181      | 0.143        | 0.201 (0.005)    | -                | 1 (0.181) |     5.50 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            3 |     3956 | 2024-02-26 | Liquid            | L   | 0.155      | -            | -                | -                | -         |    -0.09 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            2 |     3971 | 2024-02-25 | Nouns             | L   | 0.149      | -            | -                | -                | -         |    -1.73 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            1 |     3974 | 2024-02-25 | Wildcard          | W   | 0.148      | -            | -                | -                | -         |     2.98 | brett, Cryptic, d4rty, freshie, PwnAlone |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,677.05)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.896 | $750.00        | $671.77         |
| 2024-06-09 |      0.849 | $2,000.00      | $1,697.22       |
| 2024-05-12 |      0.659 | $3,500.00      | $2,308.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
