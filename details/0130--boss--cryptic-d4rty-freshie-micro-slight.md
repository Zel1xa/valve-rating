### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, micro, SLIGHT<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  783.0<br />
<br />
Final Rank Value (783.0) = Starting Rank Value (808.3) + Head To Head Adjustments (-25.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.123[<sup>2</sup>](#table1)
- LAN Wins: 0.017[<sup>2</sup>](#table1)

The average of these factors is 0.198<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 808.3
- 400 + ( ( 0.198 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 808.3


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
|           58 |       64 | 2024-08-03 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -7.80 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           57 |      172 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.34 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           56 |      176 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.95 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           55 |      222 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.50 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           54 |      223 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -8.00 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           53 |      543 | 2024-07-20 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.77 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           52 |      612 | 2024-07-18 | Elevate           | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.501 (0.239)    | 0 (0.000) |    21.85 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           51 |      614 | 2024-07-18 | Elevate           | L   | 1.000      | -            | -                | -                | -         |    -9.20 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           50 |      674 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | 0 (0.000) |    16.32 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           49 |      681 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | 0 (0.000) |    17.82 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           48 |      790 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.285 (0.136)    | 0 (0.000) |    16.89 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           47 |     1050 | 2024-06-15 | Elevate           | L   | 0.857      | -            | -                | -                | -         |    -6.49 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           46 |     1099 | 2024-06-14 | Final Form        | W   | 0.848      | -            | -                | -                | 0 (0.000) |     6.22 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           45 |     1536 | 2024-06-04 | Mythic            | L   | 0.784      | -            | -                | -                | -         |   -11.06 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           44 |     1846 | 2024-05-22 | Phoenix           | W   | 0.697      | 0.477        | -                | 0.270 (0.090)    | 0 (0.000) |    10.52 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           43 |     1850 | 2024-05-22 | Phoenix           | L   | 0.697      | -            | -                | -                | -         |   -11.68 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           42 |     1931 | 2024-05-20 | Limitless         | L   | 0.684      | -            | -                | -                | -         |   -10.77 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           41 |     1935 | 2024-05-20 | Limitless         | W   | 0.683      | -            | -                | -                | 0 (0.000) |    10.97 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           40 |     1966 | 2024-05-19 | M80               | L   | 0.676      | -            | -                | -                | -         |    -1.52 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           39 |     1967 | 2024-05-19 | M80               | L   | 0.676      | -            | -                | -                | -         |    -1.55 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           38 |     2030 | 2024-05-17 | NRG               | L   | 0.663      | -            | -                | -                | -         |    -6.64 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     2094 | 2024-05-15 | Wildcard          | L   | 0.650      | -            | -                | -                | -         |    -7.22 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     2104 | 2024-05-15 | Wildcard          | L   | 0.650      | -            | -                | -                | -         |    -7.61 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     2153 | 2024-05-14 | MIGHT             | W   | 0.644      | -            | -                | -                | 0 (0.000) |     3.49 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     2161 | 2024-05-14 | MIGHT             | W   | 0.643      | -            | -                | -                | 0 (0.000) |     3.61 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     2248 | 2024-05-11 | Phoenix           | L   | 0.623      | -            | -                | -                | -         |   -11.73 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     2250 | 2024-05-11 | Party Astronauts  | W   | 0.622      | 0.270        | 0.041 (0.007)    | 0.510 (0.086)    | -         |    13.16 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     2253 | 2024-05-11 | NRG               | L   | 0.622      | -            | -                | -                | -         |    -8.05 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     2292 | 2024-05-09 | Nouns             | L   | 0.610      | -            | -                | -                | -         |    -6.20 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     2297 | 2024-05-09 | Nouns             | L   | 0.610      | -            | -                | -                | -         |    -6.50 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2413 | 2024-05-03 | Ninjas in Pyjamas | L   | 0.568      | -            | -                | -                | -         |    -0.22 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           27 |     2450 | 2024-05-02 | FlyQuest          | L   | 0.560      | -            | -                | -                | -         |    -2.17 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           26 |     2471 | 2024-05-01 | BIG               | L   | 0.553      | -            | -                | -                | -         |    -1.22 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           25 |     2618 | 2024-04-24 | Mythic            | L   | 0.511      | -            | -                | -                | -         |    -9.67 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           24 |     2619 | 2024-04-24 | Mythic            | W   | 0.510      | 0.477        | 0.010 (0.002)    | 0.285 (0.069)    | -         |     6.51 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           23 |     2948 | 2024-04-11 | Limitless         | W   | 0.424      | -            | -                | -                | -         |     3.65 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           22 |     2950 | 2024-04-11 | Limitless         | W   | 0.424      | -            | -                | -                | -         |     3.76 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           21 |     2979 | 2024-04-10 | NRG               | L   | 0.417      | -            | -                | -                | -         |    -5.99 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           20 |     2983 | 2024-04-10 | NRG               | W   | 0.417      | 0.477        | 0.020 (0.004)    | 0.502 (0.100)    | -         |     7.32 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           19 |     3036 | 2024-04-09 | LAG               | W   | 0.410      | 0.477        | 0.012 (0.002)    | 0.376 (0.074)    | -         |     6.94 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           18 |     3039 | 2024-04-09 | LAG               | W   | 0.410      | 0.477        | 0.012 (0.002)    | 0.376 (0.074)    | -         |     7.19 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           17 |     3168 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.377      | -            | -                | -                | -         |     5.21 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           16 |     3174 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.377      | -            | -                | -                | -         |     5.38 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           15 |     3225 | 2024-04-03 | Party Astronauts  | L   | 0.369      | -            | -                | -                | -         |    -9.61 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           14 |     3261 | 2024-04-02 | Nouns             | L   | 0.364      | -            | -                | -                | -         |    -3.89 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           13 |     3266 | 2024-04-02 | Phoenix           | W   | 0.363      | -            | -                | -                | -         |     4.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           12 |     3342 | 2024-03-27 | Take Flyte        | W   | 0.324      | -            | -                | -                | -         |     3.87 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           11 |     3345 | 2024-03-27 | Take Flyte        | L   | 0.324      | -            | -                | -                | -         |    -6.46 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           10 |     3390 | 2024-03-26 | Elevate           | L   | 0.317      | -            | -                | -                | -         |    -2.51 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            9 |     3395 | 2024-03-26 | Elevate           | L   | 0.317      | -            | -                | -                | -         |    -2.56 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            8 |     3471 | 2024-03-20 | Party Astronauts  | L   | 0.277      | -            | -                | -                | -         |    -2.88 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            7 |     3473 | 2024-03-20 | Party Astronauts  | L   | 0.277      | -            | -                | -                | -         |    -2.94 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            6 |     3907 | 2024-03-03 | Liquid            | L   | 0.161      | -            | -                | -                | -         |    -0.07 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            5 |     3924 | 2024-03-02 | Complexity        | L   | 0.154      | -            | -                | -                | -         |    -0.04 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            4 |     3939 | 2024-03-01 | MIBR              | W   | 0.149      | 0.143        | 0.208 (0.004)    | -                | 1 (0.149) |     4.54 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            3 |     4008 | 2024-02-26 | Liquid            | L   | 0.123      | -            | -                | -                | -         |    -0.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            2 |     4022 | 2024-02-25 | Nouns             | L   | 0.117      | -            | -                | -                | -         |    -1.35 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            1 |     4025 | 2024-02-25 | Wildcard          | W   | 0.116      | -            | -                | -                | -         |     2.18 | brett, Cryptic, d4rty, freshie, PwnAlone |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,476.82)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.864 | $750.00        | $647.74         |
| 2024-06-09 |      0.817 | $2,000.00      | $1,633.15       |
| 2024-05-12 |      0.627 | $3,500.00      | $2,195.93       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
