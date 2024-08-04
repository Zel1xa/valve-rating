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
Final Rank Value:  1048.9<br />
<br />
Final Rank Value (1048.9) = Starting Rank Value (910.0) + Head To Head Adjustments (138.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.442[<sup>1</sup>](#table2)
- Bounty Collected: 0.351[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.019[<sup>2</sup>](#table1)

The average of these factors is 0.249<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 910.0
- 400 + ( ( 0.249 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 910.0


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
|           68 |      103 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    10.00 | JBa, phzy, Sonic, stanislaw, susp        |
|           67 |      109 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    10.81 | JBa, phzy, Sonic, stanislaw, susp        |
|           66 |      443 | 2024-07-21 | NRG              | W   | 1.000      | 0.303        | -                | 0.521 (0.158)    | 0 (0.000) |    15.40 | JBa, phzy, Sonic, stanislaw, susp        |
|           65 |      444 | 2024-07-21 | Elevate          | W   | 1.000      | 0.303        | 0.027 (0.008)    | 0.505 (0.153)    | 0 (0.000) |    13.56 | JBa, phzy, Sonic, stanislaw, susp        |
|           64 |      469 | 2024-07-20 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.531 (0.161)    | 0 (0.000) |    15.65 | JBa, phzy, Sonic, stanislaw, susp        |
|           63 |      543 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.34 | JBa, phzy, Sonic, stanislaw, susp        |
|           62 |      548 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.62 | JBa, phzy, Sonic, stanislaw, susp        |
|           61 |      613 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.13 | JBa, phzy, Sonic, stanislaw, susp        |
|           60 |      616 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.48 | JBa, phzy, Sonic, stanislaw, susp        |
|           59 |      672 | 2024-07-16 | LAG              | W   | 1.000      | 0.477        | -                | 0.341 (0.162)    | -         |    12.42 | JBa, phzy, Sonic, stanislaw, susp        |
|           58 |      678 | 2024-07-16 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -19.38 | JBa, phzy, Sonic, stanislaw, susp        |
|           57 |      958 | 2024-06-16 | Nouns            | L   | 0.876      | -            | -                | -                | -         |   -13.34 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           56 |      984 | 2024-06-15 | Mythic           | W   | 0.870      | -            | -                | -                | -         |     8.06 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           55 |     1058 | 2024-06-13 | Final Form       | W   | 0.858      | -            | -                | -                | -         |     3.84 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1169 | 2024-06-09 | M80              | L   | 0.831      | -            | -                | -                | -         |    -4.74 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1230 | 2024-06-08 | Nouns            | W   | 0.824      | 0.477        | 0.057 (0.023)    | 0.548 (0.215)    | -         |    13.73 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1236 | 2024-06-08 | Party Astronauts | L   | 0.823      | -            | -                | -                | -         |   -12.47 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1287 | 2024-06-07 | LAG              | W   | 0.817      | -            | -                | -                | -         |     8.26 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1343 | 2024-06-06 | M80              | L   | 0.811      | -            | -                | -                | -         |    -4.26 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1353 | 2024-06-06 | NRG              | L   | 0.810      | -            | -                | -                | -         |   -15.05 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1359 | 2024-06-06 | M80              | L   | 0.809      | -            | -                | -                | -         |    -4.76 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1378 | 2024-06-06 | NRG              | W   | 0.809      | -            | -                | -                | -         |    10.05 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1414 | 2024-06-05 | Party Astronauts | W   | 0.804      | 0.477        | 0.041 (0.016)    | 0.531 (0.204)    | -         |    12.18 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1468 | 2024-06-04 | Homyno           | W   | 0.797      | -            | -                | -                | -         |     4.98 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1758 | 2024-05-23 | M80              | L   | 0.717      | -            | -                | -                | -         |    -3.96 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1772 | 2024-05-22 | Take Flyte       | W   | 0.711      | -            | -                | -                | -         |     3.48 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1775 | 2024-05-22 | Take Flyte       | W   | 0.711      | -            | -                | -                | -         |     3.60 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1786 | 2024-05-22 | LAG              | W   | 0.710      | -            | -                | -                | -         |     7.06 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     1832 | 2024-05-21 | Limitless        | W   | 0.703      | -            | -                | -                | -         |     6.46 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           39 |     1836 | 2024-05-21 | Limitless        | W   | 0.703      | -            | -                | -                | -         |     6.80 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     1895 | 2024-05-19 | Limitless        | W   | 0.690      | -            | -                | -                | -         |     3.34 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     2024 | 2024-05-15 | BOSS             | W   | 0.664      | -            | -                | -                | -         |     6.73 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     2034 | 2024-05-15 | BOSS             | W   | 0.664      | -            | -                | -                | -         |     7.09 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2079 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.658      | -            | -                | -                | -         |     5.70 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2084 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.657      | -            | -                | -                | -         |     5.98 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2129 | 2024-05-13 | Nouns            | W   | 0.651      | 0.477        | 0.057 (0.018)    | 0.548 (0.170)    | -         |    11.44 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2130 | 2024-05-13 | Nouns            | L   | 0.651      | -            | -                | -                | -         |    -9.21 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2174 | 2024-05-11 | Elevate          | L   | 0.637      | -            | -                | -                | -         |    -8.38 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2176 | 2024-05-11 | Mythic           | L   | 0.637      | -            | -                | -                | -         |   -14.17 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2226 | 2024-05-09 | MIGHT            | W   | 0.624      | -            | -                | -                | -         |     1.93 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2229 | 2024-05-09 | MIGHT            | W   | 0.624      | -            | -                | -                | -         |     1.96 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           27 |     2242 | 2024-05-08 | Limitless        | W   | 0.618      | -            | -                | -                | -         |     3.23 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           26 |     2245 | 2024-05-08 | Limitless        | W   | 0.618      | -            | -                | -                | -         |     3.33 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           25 |     2359 | 2024-05-02 | Party Astronauts | W   | 0.578      | 0.477        | 0.041 (0.011)    | 0.531 (0.146)    | -         |    10.06 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2360 | 2024-05-02 | Party Astronauts | L   | 0.577      | -            | -                | -                | -         |    -8.28 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2524 | 2024-04-25 | NRG              | W   | 0.531      | -            | -                | -                | -         |     7.37 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2526 | 2024-04-25 | NRG              | L   | 0.531      | -            | -                | -                | -         |    -9.59 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     2566 | 2024-04-23 | Elevate          | W   | 0.518      | 0.477        | 0.027 (0.007)    | -                | -         |     9.82 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     2568 | 2024-04-23 | Elevate          | L   | 0.517      | -            | -                | -                | -         |    -6.59 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           19 |     2760 | 2024-04-17 | Elevate          | L   | 0.477      | -            | -                | -                | -         |    -6.27 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           18 |     3278 | 2024-03-27 | Mythic           | W   | 0.337      | -            | -                | -                | -         |     3.46 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3284 | 2024-03-27 | Mythic           | W   | 0.337      | -            | -                | -                | -         |     3.55 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           16 |     3319 | 2024-03-26 | LAG              | W   | 0.331      | -            | -                | -                | -         |     4.43 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           15 |     3324 | 2024-03-26 | LAG              | L   | 0.331      | -            | -                | -                | -         |    -6.13 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           14 |     3519 | 2024-03-14 | Perseverance     | W   | 0.251      | -            | -                | -                | -         |     2.13 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3522 | 2024-03-14 | Perseverance     | W   | 0.251      | -            | -                | -                | -         |     2.17 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           12 |     3546 | 2024-03-13 | M80              | W   | 0.245      | 0.477        | 0.188 (0.022)    | -                | -         |     6.59 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           11 |     3547 | 2024-03-13 | M80              | L   | 0.244      | -            | -                | -                | -         |    -1.12 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           10 |     3595 | 2024-03-12 | Mythic           | L   | 0.237      | -            | -                | -                | -         |    -5.03 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3835 | 2024-03-03 | M80              | L   | 0.175      | -            | -                | -                | -         |    -0.81 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3848 | 2024-03-02 | BESTIA           | W   | 0.169      | -            | -                | -                | 1 (0.169) |     3.48 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3868 | 2024-03-01 | RED Canids       | L   | 0.163      | -            | -                | -                | -         |    -1.44 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     3951 | 2024-02-25 | Liquid           | L   | 0.131      | -            | -                | -                | -         |    -0.15 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     3955 | 2024-02-25 | BOSS             | L   | 0.130      | -            | -                | -                | -         |    -2.64 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     3972 | 2024-02-24 | NRG              | W   | 0.124      | -            | -                | -                | -         |     1.65 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     3973 | 2024-02-24 | Party Astronauts | W   | 0.124      | -            | -                | -                | -         |     2.06 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     3982 | 2024-02-24 | Akimbo           | W   | 0.124      | -            | -                | -                | -         |     1.17 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     4021 | 2024-02-22 | NRG              | L   | 0.110      | -            | -                | -                | -         |    -2.02 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,774.79)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.878 | $1,500.00      | $1,316.46       |
| 2024-06-09 |      0.831 | $15,000.00     | $12,458.33      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
