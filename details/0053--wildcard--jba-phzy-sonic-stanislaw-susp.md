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
Final Rank Value:  1032.3<br />
<br />
Final Rank Value (1032.3) = Starting Rank Value (904.6) + Head To Head Adjustments (127.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.442[<sup>1</sup>](#table2)
- Bounty Collected: 0.348[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.022[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 904.6
- 400 + ( ( 0.245 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 904.6


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
|           69 |      326 | 2024-07-21 | NRG              | W   | 1.000      | 0.303        | 0.020 (0.006)    | 0.519 (0.157)    | 0 (0.000) |    15.38 | JBa, phzy, Sonic, stanislaw, susp        |
|           68 |      327 | 2024-07-21 | Elevate          | W   | 1.000      | 0.303        | 0.027 (0.008)    | 0.505 (0.153)    | 0 (0.000) |    13.62 | JBa, phzy, Sonic, stanislaw, susp        |
|           67 |      352 | 2024-07-20 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.013)    | 0.533 (0.161)    | 0 (0.000) |    15.73 | JBa, phzy, Sonic, stanislaw, susp        |
|           66 |      426 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.34 | JBa, phzy, Sonic, stanislaw, susp        |
|           65 |      431 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.62 | JBa, phzy, Sonic, stanislaw, susp        |
|           64 |      496 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.14 | JBa, phzy, Sonic, stanislaw, susp        |
|           63 |      499 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.50 | JBa, phzy, Sonic, stanislaw, susp        |
|           62 |      555 | 2024-07-16 | LAG              | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.344 (0.164)    | 0 (0.000) |    12.50 | JBa, phzy, Sonic, stanislaw, susp        |
|           61 |      561 | 2024-07-16 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -19.29 | JBa, phzy, Sonic, stanislaw, susp        |
|           60 |      841 | 2024-06-16 | Nouns            | L   | 0.900      | -            | -                | -                | -         |   -13.54 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           59 |      867 | 2024-06-15 | Mythic           | W   | 0.894      | -            | -                | -                | 0 (0.000) |     8.31 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           58 |      941 | 2024-06-13 | Final Form       | W   | 0.882      | -            | -                | -                | -         |     3.94 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           57 |     1052 | 2024-06-09 | M80              | L   | 0.854      | -            | -                | -                | -         |    -4.67 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           56 |     1113 | 2024-06-08 | Nouns            | W   | 0.848      | 0.477        | 0.058 (0.023)    | 0.546 (0.221)    | -         |    14.30 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           55 |     1119 | 2024-06-08 | Party Astronauts | L   | 0.847      | -            | -                | -                | -         |   -12.70 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1170 | 2024-06-07 | LAG              | W   | 0.841      | -            | -                | -                | -         |     8.61 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1226 | 2024-06-06 | M80              | L   | 0.835      | -            | -                | -                | -         |    -4.16 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1236 | 2024-06-06 | NRG              | L   | 0.834      | -            | -                | -                | -         |   -15.48 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1242 | 2024-06-06 | M80              | L   | 0.833      | -            | -                | -                | -         |    -4.65 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1261 | 2024-06-06 | NRG              | W   | 0.832      | -            | -                | -                | -         |    10.34 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1297 | 2024-06-05 | Party Astronauts | W   | 0.828      | 0.477        | 0.041 (0.016)    | 0.533 (0.210)    | -         |    12.69 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1351 | 2024-06-04 | Homyno           | W   | 0.821      | -            | -                | -                | -         |     5.17 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1641 | 2024-05-23 | M80              | L   | 0.740      | -            | -                | -                | -         |    -3.87 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1655 | 2024-05-22 | Take Flyte       | W   | 0.735      | -            | -                | -                | -         |     3.62 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1658 | 2024-05-22 | Take Flyte       | W   | 0.735      | -            | -                | -                | -         |     3.74 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1669 | 2024-05-22 | LAG              | W   | 0.734      | -            | -                | -                | -         |     7.44 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1715 | 2024-05-21 | Limitless        | W   | 0.727      | -            | -                | -                | -         |     6.81 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1719 | 2024-05-21 | Limitless        | W   | 0.727      | -            | -                | -                | -         |     7.19 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1778 | 2024-05-19 | Limitless        | W   | 0.714      | -            | -                | -                | -         |     3.48 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     1907 | 2024-05-15 | BOSS             | W   | 0.688      | -            | -                | -                | -         |     7.10 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           39 |     1917 | 2024-05-15 | BOSS             | W   | 0.688      | -            | -                | -                | -         |     7.50 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     1962 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.682      | -            | -                | -                | -         |     6.07 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     1967 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.681      | -            | -                | -                | -         |     6.38 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     2012 | 2024-05-13 | Nouns            | W   | 0.675      | 0.477        | 0.058 (0.019)    | 0.546 (0.176)    | -         |    12.10 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2013 | 2024-05-13 | Nouns            | L   | 0.675      | -            | -                | -                | -         |    -9.28 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2057 | 2024-05-11 | Elevate          | L   | 0.661      | -            | -                | -                | -         |    -8.43 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2059 | 2024-05-11 | Mythic           | L   | 0.661      | -            | -                | -                | -         |   -14.58 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2109 | 2024-05-09 | MIGHT            | W   | 0.648      | -            | -                | -                | -         |     2.05 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2112 | 2024-05-09 | MIGHT            | W   | 0.648      | -            | -                | -                | -         |     2.09 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2125 | 2024-05-08 | Limitless        | W   | 0.642      | -            | -                | -                | -         |     3.41 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2128 | 2024-05-08 | Limitless        | W   | 0.641      | -            | -                | -                | -         |     3.52 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2242 | 2024-05-02 | Party Astronauts | W   | 0.601      | 0.477        | 0.041 (0.012)    | 0.533 (0.153)    | -         |    10.76 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           27 |     2243 | 2024-05-02 | Party Astronauts | L   | 0.601      | -            | -                | -                | -         |    -8.31 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           26 |     2407 | 2024-04-25 | NRG              | W   | 0.555      | 0.477        | -                | 0.519 (0.137)    | -         |     7.75 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           25 |     2409 | 2024-04-25 | NRG              | L   | 0.555      | -            | -                | -                | -         |    -9.97 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2449 | 2024-04-23 | Elevate          | W   | 0.542      | 0.477        | 0.027 (0.007)    | 0.505 (0.130)    | -         |    10.52 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2451 | 2024-04-23 | Elevate          | L   | 0.541      | -            | -                | -                | -         |    -6.62 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2643 | 2024-04-17 | Elevate          | L   | 0.500      | -            | -                | -                | -         |    -6.32 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     3161 | 2024-03-27 | Mythic           | W   | 0.361      | -            | -                | -                | -         |     3.82 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     3167 | 2024-03-27 | Mythic           | W   | 0.361      | -            | -                | -                | -         |     3.92 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           19 |     3202 | 2024-03-26 | LAG              | W   | 0.355      | -            | -                | -                | -         |     4.95 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           18 |     3207 | 2024-03-26 | LAG              | L   | 0.355      | -            | -                | -                | -         |    -6.37 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3402 | 2024-03-14 | Perseverance     | W   | 0.275      | -            | -                | -                | -         |     2.41 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           16 |     3405 | 2024-03-14 | Perseverance     | W   | 0.274      | -            | -                | -                | -         |     2.45 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           15 |     3429 | 2024-03-13 | M80              | W   | 0.269      | 0.477        | 0.189 (0.024)    | -                | -         |     7.36 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           14 |     3430 | 2024-03-13 | M80              | L   | 0.268      | -            | -                | -                | -         |    -1.10 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3478 | 2024-03-12 | Mythic           | L   | 0.261      | -            | -                | -                | -         |    -5.44 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           12 |     3718 | 2024-03-03 | M80              | L   | 0.199      | -            | -                | -                | -         |    -0.82 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           11 |     3731 | 2024-03-02 | BESTIA           | W   | 0.193      | -            | -                | -                | 1 (0.193) |     4.04 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           10 |     3751 | 2024-03-01 | RED Canids       | L   | 0.187      | -            | -                | -                | -         |    -1.56 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3834 | 2024-02-25 | Liquid           | L   | 0.155      | -            | -                | -                | -         |    -0.20 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3838 | 2024-02-25 | BOSS             | L   | 0.154      | -            | -                | -                | -         |    -3.06 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3855 | 2024-02-24 | NRG              | W   | 0.148      | -            | -                | -                | -         |     1.98 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     3856 | 2024-02-24 | Party Astronauts | W   | 0.148      | -            | -                | -                | -         |     2.56 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     3865 | 2024-02-24 | Akimbo           | W   | 0.147      | -            | -                | -                | -         |     1.45 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     3904 | 2024-02-22 | NRG              | L   | 0.134      | -            | -                | -                | -         |    -2.44 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     4254 | 2024-02-04 | Elevate          | L   | 0.014      | -            | -                | -                | -         |    -0.16 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     4311 | 2024-02-02 | NRG              | W   | 0.001      | -            | -                | -                | -         |     0.01 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     4315 | 2024-02-02 | Carpe Diem       | W   | 0.000      | -            | -                | -                | -         |     0.00 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,167.20)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.901 | $1,500.00      | $1,352.13       |
| 2024-06-09 |      0.854 | $15,000.00     | $12,815.07      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
