### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, phzy, Sonic, stanislaw, susp<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [13]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1049.3<br />
<br />
Final Rank Value (1049.3) = Starting Rank Value (910.3) + Head To Head Adjustments (139.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.442[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.020[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 910.3
- 400 + ( ( 0.250 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 910.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           68 |      100 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |     9.99 | JBa, phzy, Sonic, stanislaw, susp        |
|           67 |      106 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    10.80 | JBa, phzy, Sonic, stanislaw, susp        |
|           66 |      440 | 2024-07-21 | NRG              | W   | 1.000      | 0.303        | -                | 0.521 (0.158)    | 0 (0.000) |    15.40 | JBa, phzy, Sonic, stanislaw, susp        |
|           65 |      441 | 2024-07-21 | Elevate          | W   | 1.000      | 0.303        | 0.027 (0.008)    | 0.505 (0.153)    | 0 (0.000) |    13.55 | JBa, phzy, Sonic, stanislaw, susp        |
|           64 |      466 | 2024-07-20 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.532 (0.161)    | 0 (0.000) |    15.65 | JBa, phzy, Sonic, stanislaw, susp        |
|           63 |      540 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.34 | JBa, phzy, Sonic, stanislaw, susp        |
|           62 |      545 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.62 | JBa, phzy, Sonic, stanislaw, susp        |
|           61 |      610 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.12 | JBa, phzy, Sonic, stanislaw, susp        |
|           60 |      613 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.47 | JBa, phzy, Sonic, stanislaw, susp        |
|           59 |      669 | 2024-07-16 | LAG              | W   | 1.000      | 0.477        | -                | 0.341 (0.163)    | -         |    12.41 | JBa, phzy, Sonic, stanislaw, susp        |
|           58 |      675 | 2024-07-16 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -19.39 | JBa, phzy, Sonic, stanislaw, susp        |
|           57 |      954 | 2024-06-16 | Nouns            | L   | 0.879      | -            | -                | -                | -         |   -13.39 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           56 |      980 | 2024-06-15 | Mythic           | W   | 0.873      | -            | -                | -                | -         |     8.08 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           55 |     1054 | 2024-06-13 | Final Form       | W   | 0.861      | -            | -                | -                | -         |     3.85 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1165 | 2024-06-09 | M80              | L   | 0.834      | -            | -                | -                | -         |    -4.75 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1226 | 2024-06-08 | Nouns            | W   | 0.827      | 0.477        | 0.057 (0.023)    | 0.547 (0.216)    | -         |    13.78 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1232 | 2024-06-08 | Party Astronauts | L   | 0.826      | -            | -                | -                | -         |   -12.51 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1283 | 2024-06-07 | LAG              | W   | 0.820      | -            | -                | -                | -         |     8.28 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1339 | 2024-06-06 | M80              | L   | 0.814      | -            | -                | -                | -         |    -4.28 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1349 | 2024-06-06 | NRG              | L   | 0.813      | -            | -                | -                | -         |   -15.11 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1355 | 2024-06-06 | M80              | L   | 0.812      | -            | -                | -                | -         |    -4.77 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1374 | 2024-06-06 | NRG              | W   | 0.812      | -            | -                | -                | -         |    10.08 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1410 | 2024-06-05 | Party Astronauts | W   | 0.807      | 0.477        | 0.041 (0.016)    | 0.532 (0.205)    | -         |    12.22 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1464 | 2024-06-04 | Homyno           | W   | 0.800      | -            | -                | -                | -         |     5.00 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1754 | 2024-05-23 | M80              | L   | 0.720      | -            | -                | -                | -         |    -3.98 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1768 | 2024-05-22 | Take Flyte       | W   | 0.714      | -            | -                | -                | -         |     3.49 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1771 | 2024-05-22 | Take Flyte       | W   | 0.714      | -            | -                | -                | -         |     3.61 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1782 | 2024-05-22 | LAG              | W   | 0.713      | -            | -                | -                | -         |     7.08 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     1828 | 2024-05-21 | Limitless        | W   | 0.706      | -            | -                | -                | -         |     6.48 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           39 |     1832 | 2024-05-21 | Limitless        | W   | 0.706      | -            | -                | -                | -         |     6.83 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     1891 | 2024-05-19 | Limitless        | W   | 0.693      | -            | -                | -                | -         |     3.35 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     2020 | 2024-05-15 | BOSS             | W   | 0.667      | -            | -                | -                | -         |     6.76 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     2030 | 2024-05-15 | BOSS             | W   | 0.667      | -            | -                | -                | -         |     7.13 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2075 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.661      | -            | -                | -                | -         |     5.73 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2080 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.661      | -            | -                | -                | -         |     6.00 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2125 | 2024-05-13 | Nouns            | W   | 0.654      | 0.477        | 0.057 (0.018)    | 0.547 (0.171)    | -         |    11.50 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2126 | 2024-05-13 | Nouns            | L   | 0.654      | -            | -                | -                | -         |    -9.24 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2170 | 2024-05-11 | Elevate          | L   | 0.640      | -            | -                | -                | -         |    -8.42 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2172 | 2024-05-11 | Mythic           | L   | 0.640      | -            | -                | -                | -         |   -14.24 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2222 | 2024-05-09 | MIGHT            | W   | 0.627      | -            | -                | -                | -         |     1.93 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2225 | 2024-05-09 | MIGHT            | W   | 0.627      | -            | -                | -                | -         |     1.97 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           27 |     2238 | 2024-05-08 | Limitless        | W   | 0.621      | -            | -                | -                | -         |     3.24 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           26 |     2241 | 2024-05-08 | Limitless        | W   | 0.621      | -            | -                | -                | -         |     3.34 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           25 |     2355 | 2024-05-02 | Party Astronauts | W   | 0.581      | 0.477        | 0.041 (0.011)    | 0.532 (0.147)    | -         |    10.12 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2356 | 2024-05-02 | Party Astronauts | L   | 0.580      | -            | -                | -                | -         |    -8.32 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2519 | 2024-04-25 | NRG              | W   | 0.534      | -            | -                | -                | -         |     7.41 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2521 | 2024-04-25 | NRG              | L   | 0.534      | -            | -                | -                | -         |    -9.65 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     2561 | 2024-04-23 | Elevate          | W   | 0.521      | 0.477        | 0.027 (0.007)    | -                | -         |     9.87 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     2563 | 2024-04-23 | Elevate          | L   | 0.521      | -            | -                | -                | -         |    -6.64 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           19 |     2755 | 2024-04-17 | Elevate          | L   | 0.480      | -            | -                | -                | -         |    -6.31 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           18 |     3273 | 2024-03-27 | Mythic           | W   | 0.340      | -            | -                | -                | -         |     3.49 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3279 | 2024-03-27 | Mythic           | W   | 0.340      | -            | -                | -                | -         |     3.59 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           16 |     3314 | 2024-03-26 | LAG              | W   | 0.335      | -            | -                | -                | -         |     4.47 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           15 |     3319 | 2024-03-26 | LAG              | L   | 0.334      | -            | -                | -                | -         |    -6.19 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           14 |     3514 | 2024-03-14 | Perseverance     | W   | 0.254      | -            | -                | -                | -         |     2.16 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3517 | 2024-03-14 | Perseverance     | W   | 0.254      | -            | -                | -                | -         |     2.19 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           12 |     3541 | 2024-03-13 | M80              | W   | 0.248      | 0.477        | 0.188 (0.022)    | -                | -         |     6.68 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           11 |     3542 | 2024-03-13 | M80              | L   | 0.247      | -            | -                | -                | -         |    -1.13 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           10 |     3589 | 2024-03-12 | Mythic           | L   | 0.240      | -            | -                | -                | -         |    -5.09 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3829 | 2024-03-03 | M80              | L   | 0.178      | -            | -                | -                | -         |    -0.82 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3842 | 2024-03-02 | BESTIA           | W   | 0.172      | -            | -                | -                | 1 (0.172) |     3.54 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3862 | 2024-03-01 | RED Canids       | L   | 0.166      | -            | -                | -                | -         |    -1.46 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     3945 | 2024-02-25 | Liquid           | L   | 0.134      | -            | -                | -                | -         |    -0.15 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     3949 | 2024-02-25 | BOSS             | L   | 0.133      | -            | -                | -                | -         |    -2.71 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     3966 | 2024-02-24 | NRG              | W   | 0.127      | -            | -                | -                | -         |     1.69 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     3967 | 2024-02-24 | Party Astronauts | W   | 0.127      | -            | -                | -                | -         |     2.12 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     3976 | 2024-02-24 | Akimbo           | W   | 0.127      | -            | -                | -                | -         |     1.19 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     4015 | 2024-02-22 | NRG              | L   | 0.113      | -            | -                | -                | -         |    -2.08 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,825.21)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.881 | $1,500.00      | $1,321.04       |
| 2024-06-09 |      0.834 | $15,000.00     | $12,504.17      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
