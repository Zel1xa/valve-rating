### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, micro, SLIGHT<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  783.6<br />
<br />
Final Rank Value (783.6) = Starting Rank Value (807.6) + Head To Head Adjustments (-24.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.351[<sup>1</sup>](#table2)
- Bounty Collected: 0.305[<sup>2</sup>](#table1)
- Opponent Network: 0.123[<sup>2</sup>](#table1)
- LAN Wins: 0.018[<sup>2</sup>](#table1)

The average of these factors is 0.199<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 807.6
- 400 + ( ( 0.199 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 807.6


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
|           58 |       30 | 2024-08-03 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -7.76 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           57 |      138 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.30 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           56 |      142 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.90 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           55 |      188 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.45 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           54 |      189 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.95 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           53 |      509 | 2024-07-20 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.72 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           52 |      578 | 2024-07-18 | Elevate           | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.521 (0.248)    | 0 (0.000) |    21.88 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           51 |      580 | 2024-07-18 | Elevate           | L   | 1.000      | -            | -                | -                | -         |    -9.16 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           50 |      640 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.353 (0.168)    | 0 (0.000) |    16.36 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           49 |      647 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.353 (0.168)    | 0 (0.000) |    17.86 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           48 |      756 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.299 (0.142)    | 0 (0.000) |    16.95 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           47 |     1016 | 2024-06-15 | Elevate           | L   | 0.867      | -            | -                | -                | -         |    -6.53 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           46 |     1065 | 2024-06-14 | Final Form        | W   | 0.858      | -            | -                | -                | 0 (0.000) |     6.30 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           45 |     1502 | 2024-06-04 | Mythic            | L   | 0.793      | -            | -                | -                | -         |   -11.15 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           44 |     1812 | 2024-05-22 | Phoenix           | W   | 0.707      | 0.477        | -                | 0.283 (0.095)    | 0 (0.000) |    10.69 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           43 |     1816 | 2024-05-22 | Phoenix           | L   | 0.707      | -            | -                | -                | -         |   -11.81 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           42 |     1897 | 2024-05-20 | Limitless         | L   | 0.693      | -            | -                | -                | -         |   -10.90 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           41 |     1901 | 2024-05-20 | Limitless         | W   | 0.693      | -            | -                | -                | 0 (0.000) |    11.14 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           40 |     1932 | 2024-05-19 | M80               | L   | 0.686      | -            | -                | -                | -         |    -1.52 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           39 |     1933 | 2024-05-19 | M80               | L   | 0.686      | -            | -                | -                | -         |    -1.55 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           38 |     1996 | 2024-05-17 | NRG               | L   | 0.672      | -            | -                | -                | -         |    -6.68 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     2060 | 2024-05-15 | Wildcard          | L   | 0.660      | -            | -                | -                | -         |    -7.27 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     2070 | 2024-05-15 | Wildcard          | L   | 0.660      | -            | -                | -                | -         |    -7.67 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     2119 | 2024-05-14 | MIGHT             | W   | 0.653      | -            | -                | -                | 0 (0.000) |     3.56 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     2127 | 2024-05-14 | MIGHT             | W   | 0.653      | -            | -                | -                | 0 (0.000) |     3.68 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     2214 | 2024-05-11 | Phoenix           | L   | 0.632      | -            | -                | -                | -         |   -11.90 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     2216 | 2024-05-11 | Party Astronauts  | W   | 0.632      | 0.270        | 0.041 (0.007)    | 0.531 (0.091)    | -         |    13.42 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     2219 | 2024-05-11 | NRG               | L   | 0.632      | -            | -                | -                | -         |    -8.13 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     2258 | 2024-05-09 | Nouns             | L   | 0.620      | -            | -                | -                | -         |    -6.24 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     2263 | 2024-05-09 | Nouns             | L   | 0.620      | -            | -                | -                | -         |    -6.55 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2379 | 2024-05-03 | Ninjas in Pyjamas | L   | 0.578      | -            | -                | -                | -         |    -0.23 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           27 |     2416 | 2024-05-02 | FlyQuest          | L   | 0.570      | -            | -                | -                | -         |    -2.15 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           26 |     2437 | 2024-05-01 | BIG               | L   | 0.563      | -            | -                | -                | -         |    -1.24 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           25 |     2584 | 2024-04-24 | Mythic            | L   | 0.520      | -            | -                | -                | -         |    -9.86 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           24 |     2585 | 2024-04-24 | Mythic            | W   | 0.520      | 0.477        | 0.010 (0.002)    | 0.299 (0.074)    | -         |     6.64 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           23 |     2914 | 2024-04-11 | Limitless         | W   | 0.434      | -            | -                | -                | -         |     3.72 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           22 |     2916 | 2024-04-11 | Limitless         | W   | 0.433      | -            | -                | -                | -         |     3.83 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           21 |     2945 | 2024-04-10 | NRG               | L   | 0.427      | -            | -                | -                | -         |    -6.10 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           20 |     2949 | 2024-04-10 | NRG               | W   | 0.427      | 0.477        | 0.020 (0.004)    | 0.521 (0.106)    | -         |     7.51 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           19 |     3002 | 2024-04-09 | LAG               | W   | 0.420      | 0.477        | 0.012 (0.002)    | 0.353 (0.071)    | -         |     7.14 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           18 |     3005 | 2024-04-09 | LAG               | W   | 0.420      | 0.477        | 0.012 (0.002)    | 0.353 (0.071)    | -         |     7.41 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           17 |     3134 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.387      | -            | -                | -                | -         |     5.35 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           16 |     3140 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.386      | -            | -                | -                | -         |     5.53 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           15 |     3191 | 2024-04-03 | Party Astronauts  | L   | 0.379      | -            | -                | -                | -         |    -9.86 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           14 |     3227 | 2024-04-02 | Nouns             | L   | 0.374      | -            | -                | -                | -         |    -3.94 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           13 |     3232 | 2024-04-02 | Phoenix           | W   | 0.372      | -            | -                | -                | -         |     4.74 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           12 |     3308 | 2024-03-27 | Take Flyte        | W   | 0.334      | -            | -                | -                | -         |     3.99 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           11 |     3311 | 2024-03-27 | Take Flyte        | L   | 0.334      | -            | -                | -                | -         |    -6.66 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           10 |     3356 | 2024-03-26 | Elevate           | L   | 0.327      | -            | -                | -                | -         |    -2.57 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            9 |     3361 | 2024-03-26 | Elevate           | L   | 0.327      | -            | -                | -                | -         |    -2.63 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            8 |     3437 | 2024-03-20 | Party Astronauts  | L   | 0.287      | -            | -                | -                | -         |    -2.94 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            7 |     3439 | 2024-03-20 | Party Astronauts  | L   | 0.287      | -            | -                | -                | -         |    -3.00 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            6 |     3873 | 2024-03-03 | Liquid            | L   | 0.171      | -            | -                | -                | -         |    -0.07 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            5 |     3890 | 2024-03-02 | Complexity        | L   | 0.164      | -            | -                | -                | -         |    -0.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            4 |     3905 | 2024-03-01 | MIBR              | W   | 0.159      | 0.143        | 0.209 (0.005)    | -                | 1 (0.159) |     4.84 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            3 |     3974 | 2024-02-26 | Liquid            | L   | 0.133      | -            | -                | -                | -         |    -0.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            2 |     3988 | 2024-02-25 | Nouns             | L   | 0.127      | -            | -                | -                | -         |    -1.45 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            1 |     3991 | 2024-02-25 | Wildcard          | W   | 0.126      | -            | -                | -                | -         |     2.38 | brett, Cryptic, d4rty, freshie, PwnAlone |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,538.16)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.873 | $750.00        | $655.10         |
| 2024-06-09 |      0.826 | $2,000.00      | $1,652.78       |
| 2024-05-12 |      0.637 | $3,500.00      | $2,230.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
