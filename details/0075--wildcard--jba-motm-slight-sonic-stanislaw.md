### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, motm, SLIGHT, Sonic, stanislaw<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [21]( ../standings_americas.md)<br />
<br />
Final Rank Value:  945.7<br />
<br />
Final Rank Value (945.7) = Starting Rank Value (874.9) + Head To Head Adjustments (70.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.138[<sup>2</sup>](#table1)
- LAN Wins: 0.018[<sup>2</sup>](#table1)

The average of these factors is 0.232<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 874.9
- 400 + ( ( 0.232 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 874.9


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
|           60 |     1015 | 2024-06-16 | Nouns            | L   | 0.867      | -            | -                | -                | -         |   -12.34 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           59 |     1041 | 2024-06-15 | Mythic           | W   | 0.862      | 0.371        | -                | 0.293 (0.094)    | 0 (0.000) |     8.63 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           58 |     1115 | 2024-06-13 | Final Form       | W   | 0.850      | -            | -                | -                | 0 (0.000) |     4.25 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           57 |     1226 | 2024-06-09 | M80              | L   | 0.822      | -            | -                | -                | -         |    -4.26 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           56 |     1287 | 2024-06-08 | Nouns            | W   | 0.816      | 0.477        | 0.057 (0.022)    | 0.553 (0.215)    | 0 (0.000) |    14.54 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           55 |     1293 | 2024-06-08 | Party Astronauts | L   | 0.814      | -            | -                | -                | -         |   -11.57 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1344 | 2024-06-07 | LAG              | W   | 0.809      | 0.384        | 0.012 (0.004)    | 0.347 (0.108)    | 0 (0.000) |     8.69 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1400 | 2024-06-06 | M80              | L   | 0.802      | -            | -                | -                | -         |    -3.77 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1410 | 2024-06-06 | NRG              | L   | 0.801      | -            | -                | -                | -         |   -14.07 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1416 | 2024-06-06 | M80              | L   | 0.801      | -            | -                | -                | -         |    -4.18 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1435 | 2024-06-06 | NRG              | W   | 0.800      | -            | -                | -                | 0 (0.000) |    10.84 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1471 | 2024-06-05 | Party Astronauts | W   | 0.796      | 0.477        | 0.041 (0.016)    | 0.523 (0.198)    | 0 (0.000) |    12.96 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1525 | 2024-06-04 | Homyno           | W   | 0.789      | -            | -                | -                | 0 (0.000) |     5.61 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1815 | 2024-05-23 | M80              | L   | 0.708      | -            | -                | -                | -         |    -3.42 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1829 | 2024-05-22 | Take Flyte       | W   | 0.703      | -            | -                | -                | 0 (0.000) |     3.99 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1832 | 2024-05-22 | Take Flyte       | W   | 0.703      | -            | -                | -                | 0 (0.000) |     4.14 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1843 | 2024-05-22 | LAG              | W   | 0.702      | -            | -                | -                | -         |     7.58 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1889 | 2024-05-21 | Limitless        | W   | 0.695      | -            | -                | -                | -         |     7.18 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1893 | 2024-05-21 | Limitless        | W   | 0.694      | -            | -                | -                | -         |     7.58 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1952 | 2024-05-19 | Limitless        | W   | 0.682      | -            | -                | -                | -         |     3.85 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     2012 | 2024-05-17 | Nouns            | L   | 0.669      | -            | -                | -                | -         |   -10.55 | Grizz, JBa, motm, SLIGHT, stanislaw      |
|           39 |     2081 | 2024-05-15 | BOSS             | W   | 0.656      | 0.477        | 0.014 (0.004)    | 0.327 (0.102)    | -         |     7.24 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     2091 | 2024-05-15 | BOSS             | W   | 0.656      | 0.477        | 0.014 (0.004)    | 0.327 (0.102)    | -         |     7.63 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     2136 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.649      | -            | -                | -                | -         |     6.19 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     2141 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.649      | -            | -                | -                | -         |     6.50 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2186 | 2024-05-13 | Nouns            | W   | 0.642      | 0.477        | 0.057 (0.017)    | 0.553 (0.169)    | -         |    11.95 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2187 | 2024-05-13 | Nouns            | L   | 0.642      | -            | -                | -                | -         |    -8.39 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2231 | 2024-05-11 | Elevate          | L   | 0.629      | -            | -                | -                | -         |    -7.52 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2233 | 2024-05-11 | Mythic           | L   | 0.628      | -            | -                | -                | -         |   -13.32 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2283 | 2024-05-09 | MIGHT            | W   | 0.616      | -            | -                | -                | -         |     2.18 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2286 | 2024-05-09 | MIGHT            | W   | 0.615      | -            | -                | -                | -         |     2.23 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2299 | 2024-05-08 | Limitless        | W   | 0.609      | -            | -                | -                | -         |     3.65 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2302 | 2024-05-08 | Limitless        | W   | 0.609      | -            | -                | -                | -         |     3.77 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           27 |     2416 | 2024-05-02 | Party Astronauts | W   | 0.569      | 0.477        | 0.041 (0.011)    | 0.523 (0.142)    | -         |    10.58 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           26 |     2417 | 2024-05-02 | Party Astronauts | L   | 0.569      | -            | -                | -                | -         |    -7.45 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           25 |     2581 | 2024-04-25 | NRG              | W   | 0.522      | 0.477        | 0.020 (0.005)    | 0.514 (0.128)    | -         |     7.95 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2583 | 2024-04-25 | NRG              | L   | 0.522      | -            | -                | -                | -         |    -8.71 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2623 | 2024-04-23 | Elevate          | W   | 0.509      | 0.477        | 0.027 (0.006)    | 0.513 (0.125)    | -         |    10.39 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2625 | 2024-04-23 | Elevate          | L   | 0.509      | -            | -                | -                | -         |    -5.71 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     2817 | 2024-04-17 | Elevate          | L   | 0.468      | -            | -                | -                | -         |    -5.40 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     3070 | 2024-04-08 | Cloud9           | L   | 0.410      | -            | -                | -                | -         |    -3.50 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           19 |     3099 | 2024-04-08 | Virtus.pro       | L   | 0.404      | -            | -                | -                | -         |    -0.14 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           18 |     3335 | 2024-03-27 | Mythic           | W   | 0.329      | -            | -                | -                | -         |     3.79 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3341 | 2024-03-27 | Mythic           | W   | 0.329      | -            | -                | -                | -         |     3.89 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           16 |     3376 | 2024-03-26 | LAG              | W   | 0.323      | -            | -                | -                | -         |     4.58 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           15 |     3381 | 2024-03-26 | LAG              | L   | 0.323      | -            | -                | -                | -         |    -5.70 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           14 |     3576 | 2024-03-14 | Phoenix          | W   | 0.242      | -            | -                | -                | -         |     2.35 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3579 | 2024-03-14 | Phoenix          | W   | 0.242      | -            | -                | -                | -         |     2.39 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           12 |     3603 | 2024-03-13 | M80              | W   | 0.236      | 0.477        | 0.188 (0.021)    | -                | -         |     6.51 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           11 |     3604 | 2024-03-13 | M80              | L   | 0.236      | -            | -                | -                | -         |    -0.93 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           10 |     3652 | 2024-03-12 | Mythic           | L   | 0.229      | -            | -                | -                | -         |    -4.53 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3892 | 2024-03-03 | M80              | L   | 0.166      | -            | -                | -                | -         |    -0.66 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3905 | 2024-03-02 | BESTIA           | W   | 0.160      | -            | -                | -                | 1 (0.160) |     3.51 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3925 | 2024-03-01 | RED Canids       | L   | 0.154      | -            | -                | -                | -         |    -1.19 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     4008 | 2024-02-25 | Liquid           | L   | 0.123      | -            | -                | -                | -         |    -0.07 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     4012 | 2024-02-25 | BOSS             | L   | 0.122      | -            | -                | -                | -         |    -2.29 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     4029 | 2024-02-24 | NRG              | W   | 0.116      | -            | -                | -                | -         |     1.71 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     4030 | 2024-02-24 | Party Astronauts | W   | 0.115      | -            | -                | -                | -         |     2.08 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     4039 | 2024-02-24 | Akimbo           | W   | 0.115      | -            | -                | -                | -         |     1.24 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     4078 | 2024-02-22 | NRG              | L   | 0.102      | -            | -                | -                | -         |    -1.71 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,412.25)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.869 | $1,500.00      | $1,303.54       |
| 2024-06-09 |      0.822 | $15,000.00     | $12,329.17      |
| 2024-04-14 |      0.445 | $4,000.00      | $1,779.54       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
