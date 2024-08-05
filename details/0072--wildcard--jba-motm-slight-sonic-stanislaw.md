### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, motm, SLIGHT, Sonic, stanislaw<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [21]( ../standings_americas.md)<br />
<br />
Final Rank Value:  946.9<br />
<br />
Final Rank Value (946.9) = Starting Rank Value (876.0) + Head To Head Adjustments (70.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.141[<sup>2</sup>](#table1)
- LAN Wins: 0.019[<sup>2</sup>](#table1)

The average of these factors is 0.233<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 876.0
- 400 + ( ( 0.233 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 876.0


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
|           60 |      994 | 2024-06-16 | Nouns            | L   | 0.872      | -            | -                | -                | -         |   -12.40 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           59 |     1020 | 2024-06-15 | Mythic           | W   | 0.866      | 0.371        | -                | 0.299 (0.096)    | 0 (0.000) |     8.66 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           58 |     1094 | 2024-06-13 | Final Form       | W   | 0.854      | -            | -                | -                | 0 (0.000) |     4.24 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           57 |     1205 | 2024-06-09 | M80              | L   | 0.826      | -            | -                | -                | -         |    -4.29 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           56 |     1266 | 2024-06-08 | Nouns            | W   | 0.820      | 0.477        | 0.057 (0.022)    | 0.561 (0.219)    | 0 (0.000) |    14.61 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           55 |     1272 | 2024-06-08 | Party Astronauts | L   | 0.819      | -            | -                | -                | -         |   -11.63 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1323 | 2024-06-07 | LAG              | W   | 0.813      | 0.384        | 0.012 (0.004)    | 0.353 (0.110)    | 0 (0.000) |     8.72 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1379 | 2024-06-06 | M80              | L   | 0.807      | -            | -                | -                | -         |    -3.79 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1389 | 2024-06-06 | NRG              | L   | 0.806      | -            | -                | -                | -         |   -14.16 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1395 | 2024-06-06 | M80              | L   | 0.805      | -            | -                | -                | -         |    -4.20 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1414 | 2024-06-06 | NRG              | W   | 0.804      | -            | -                | -                | 0 (0.000) |    10.88 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1450 | 2024-06-05 | Party Astronauts | W   | 0.800      | 0.477        | 0.041 (0.016)    | 0.531 (0.203)    | 0 (0.000) |    13.03 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1504 | 2024-06-04 | Homyno           | W   | 0.793      | -            | -                | -                | 0 (0.000) |     5.61 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1794 | 2024-05-23 | M80              | L   | 0.713      | -            | -                | -                | -         |    -3.44 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1808 | 2024-05-22 | Take Flyte       | W   | 0.707      | -            | -                | -                | 0 (0.000) |     3.99 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1811 | 2024-05-22 | Take Flyte       | W   | 0.707      | -            | -                | -                | 0 (0.000) |     4.14 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1822 | 2024-05-22 | LAG              | W   | 0.706      | -            | -                | -                | -         |     7.61 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1868 | 2024-05-21 | Limitless        | W   | 0.699      | -            | -                | -                | -         |     7.21 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1872 | 2024-05-21 | Limitless        | W   | 0.699      | -            | -                | -                | -         |     7.61 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1931 | 2024-05-19 | Limitless        | W   | 0.686      | -            | -                | -                | -         |     3.86 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     1991 | 2024-05-17 | Nouns            | L   | 0.673      | -            | -                | -                | -         |   -10.63 | Grizz, JBa, motm, SLIGHT, stanislaw      |
|           39 |     2060 | 2024-05-15 | BOSS             | W   | 0.660      | 0.477        | 0.014 (0.004)    | 0.332 (0.105)    | -         |     7.27 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     2070 | 2024-05-15 | BOSS             | W   | 0.660      | 0.477        | 0.014 (0.004)    | 0.332 (0.105)    | -         |     7.67 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     2115 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.654      | -            | -                | -                | -         |     6.21 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     2120 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.653      | -            | -                | -                | -         |     6.52 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2165 | 2024-05-13 | Nouns            | W   | 0.647      | 0.477        | 0.057 (0.018)    | 0.561 (0.173)    | -         |    12.03 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2166 | 2024-05-13 | Nouns            | L   | 0.647      | -            | -                | -                | -         |    -8.45 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2210 | 2024-05-11 | Elevate          | L   | 0.633      | -            | -                | -                | -         |    -7.59 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2212 | 2024-05-11 | Mythic           | L   | 0.633      | -            | -                | -                | -         |   -13.44 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2262 | 2024-05-09 | MIGHT            | W   | 0.620      | -            | -                | -                | -         |     2.19 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2265 | 2024-05-09 | MIGHT            | W   | 0.620      | -            | -                | -                | -         |     2.24 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2278 | 2024-05-08 | Limitless        | W   | 0.614      | -            | -                | -                | -         |     3.65 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2281 | 2024-05-08 | Limitless        | W   | 0.613      | -            | -                | -                | -         |     3.77 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           27 |     2395 | 2024-05-02 | Party Astronauts | W   | 0.573      | 0.477        | 0.041 (0.011)    | 0.531 (0.145)    | -         |    10.66 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           26 |     2396 | 2024-05-02 | Party Astronauts | L   | 0.573      | -            | -                | -                | -         |    -7.51 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           25 |     2560 | 2024-04-25 | NRG              | W   | 0.527      | 0.477        | 0.020 (0.005)    | 0.521 (0.131)    | -         |     8.01 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2562 | 2024-04-25 | NRG              | L   | 0.527      | -            | -                | -                | -         |    -8.79 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2602 | 2024-04-23 | Elevate          | W   | 0.514      | 0.477        | 0.027 (0.007)    | 0.521 (0.128)    | -         |    10.47 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2604 | 2024-04-23 | Elevate          | L   | 0.513      | -            | -                | -                | -         |    -5.78 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     2796 | 2024-04-17 | Elevate          | L   | 0.473      | -            | -                | -                | -         |    -5.46 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     3049 | 2024-04-08 | Cloud9           | L   | 0.415      | -            | -                | -                | -         |    -3.51 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           19 |     3078 | 2024-04-08 | Virtus.pro       | L   | 0.408      | -            | -                | -                | -         |    -0.14 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           18 |     3314 | 2024-03-27 | Mythic           | W   | 0.333      | -            | -                | -                | -         |     3.83 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3320 | 2024-03-27 | Mythic           | W   | 0.333      | -            | -                | -                | -         |     3.94 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           16 |     3355 | 2024-03-26 | LAG              | W   | 0.327      | -            | -                | -                | -         |     4.64 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           15 |     3360 | 2024-03-26 | LAG              | L   | 0.327      | -            | -                | -                | -         |    -5.78 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           14 |     3555 | 2024-03-14 | Phoenix          | W   | 0.247      | -            | -                | -                | -         |     2.38 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3558 | 2024-03-14 | Phoenix          | W   | 0.246      | -            | -                | -                | -         |     2.42 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           12 |     3582 | 2024-03-13 | M80              | W   | 0.241      | 0.477        | 0.188 (0.022)    | -                | -         |     6.63 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           11 |     3583 | 2024-03-13 | M80              | L   | 0.240      | -            | -                | -                | -         |    -0.94 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           10 |     3631 | 2024-03-12 | Mythic           | L   | 0.233      | -            | -                | -                | -         |    -4.62 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3871 | 2024-03-03 | M80              | L   | 0.171      | -            | -                | -                | -         |    -0.68 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3884 | 2024-03-02 | BESTIA           | W   | 0.165      | -            | -                | -                | 1 (0.165) |     3.61 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3904 | 2024-03-01 | RED Canids       | L   | 0.159      | -            | -                | -                | -         |    -1.23 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     3987 | 2024-02-25 | Liquid           | L   | 0.127      | -            | -                | -                | -         |    -0.07 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     3991 | 2024-02-25 | BOSS             | L   | 0.126      | -            | -                | -                | -         |    -2.38 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     4008 | 2024-02-24 | NRG              | W   | 0.120      | -            | -                | -                | -         |     1.77 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     4009 | 2024-02-24 | Party Astronauts | W   | 0.120      | -            | -                | -                | -         |     2.17 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     4018 | 2024-02-24 | Akimbo           | W   | 0.119      | -            | -                | -                | -         |     1.28 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     4057 | 2024-02-22 | NRG              | L   | 0.106      | -            | -                | -                | -         |    -1.78 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,503.36)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.873 | $1,500.00      | $1,310.21       |
| 2024-06-09 |      0.826 | $15,000.00     | $12,395.83      |
| 2024-04-14 |      0.449 | $4,000.00      | $1,797.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
