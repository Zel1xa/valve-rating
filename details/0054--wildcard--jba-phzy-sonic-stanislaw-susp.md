### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, phzy, Sonic, stanislaw, susp<br />
Global Rank: [54](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [13]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1048.9<br />
<br />
Final Rank Value (1048.9) = Starting Rank Value (910.0) + Head To Head Adjustments (138.9)<br />

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
|           68 |      111 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    10.00 | JBa, phzy, Sonic, stanislaw, susp        |
|           67 |      117 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    10.81 | JBa, phzy, Sonic, stanislaw, susp        |
|           66 |      451 | 2024-07-21 | NRG              | W   | 1.000      | 0.303        | -                | 0.521 (0.158)    | 0 (0.000) |    15.40 | JBa, phzy, Sonic, stanislaw, susp        |
|           65 |      452 | 2024-07-21 | Elevate          | W   | 1.000      | 0.303        | 0.027 (0.008)    | 0.505 (0.153)    | 0 (0.000) |    13.56 | JBa, phzy, Sonic, stanislaw, susp        |
|           64 |      477 | 2024-07-20 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.531 (0.161)    | 0 (0.000) |    15.65 | JBa, phzy, Sonic, stanislaw, susp        |
|           63 |      551 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.34 | JBa, phzy, Sonic, stanislaw, susp        |
|           62 |      556 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.62 | JBa, phzy, Sonic, stanislaw, susp        |
|           61 |      621 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.12 | JBa, phzy, Sonic, stanislaw, susp        |
|           60 |      624 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.48 | JBa, phzy, Sonic, stanislaw, susp        |
|           59 |      680 | 2024-07-16 | LAG              | W   | 1.000      | 0.477        | -                | 0.340 (0.162)    | -         |    12.42 | JBa, phzy, Sonic, stanislaw, susp        |
|           58 |      686 | 2024-07-16 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -19.39 | JBa, phzy, Sonic, stanislaw, susp        |
|           57 |      966 | 2024-06-16 | Nouns            | L   | 0.875      | -            | -                | -                | -         |   -13.33 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           56 |      992 | 2024-06-15 | Mythic           | W   | 0.870      | -            | -                | -                | -         |     8.05 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           55 |     1066 | 2024-06-13 | Final Form       | W   | 0.857      | -            | -                | -                | -         |     3.84 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1177 | 2024-06-09 | M80              | L   | 0.830      | -            | -                | -                | -         |    -4.71 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1238 | 2024-06-08 | Nouns            | W   | 0.823      | 0.477        | 0.057 (0.022)    | 0.548 (0.215)    | -         |    13.72 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1244 | 2024-06-08 | Party Astronauts | L   | 0.822      | -            | -                | -                | -         |   -12.46 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1295 | 2024-06-07 | LAG              | W   | 0.817      | -            | -                | -                | -         |     8.25 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1351 | 2024-06-06 | M80              | L   | 0.810      | -            | -                | -                | -         |    -4.23 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1361 | 2024-06-06 | NRG              | L   | 0.809      | -            | -                | -                | -         |   -15.04 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1367 | 2024-06-06 | M80              | L   | 0.808      | -            | -                | -                | -         |    -4.72 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1386 | 2024-06-06 | NRG              | W   | 0.808      | -            | -                | -                | -         |    10.04 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1422 | 2024-06-05 | Party Astronauts | W   | 0.803      | 0.477        | 0.041 (0.016)    | 0.531 (0.204)    | -         |    12.17 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1476 | 2024-06-04 | Homyno           | W   | 0.797      | -            | -                | -                | -         |     4.98 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1766 | 2024-05-23 | M80              | L   | 0.716      | -            | -                | -                | -         |    -3.93 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1780 | 2024-05-22 | Take Flyte       | W   | 0.711      | -            | -                | -                | -         |     3.48 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1783 | 2024-05-22 | Take Flyte       | W   | 0.710      | -            | -                | -                | -         |     3.60 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1794 | 2024-05-22 | LAG              | W   | 0.710      | -            | -                | -                | -         |     7.05 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     1840 | 2024-05-21 | Limitless        | W   | 0.703      | -            | -                | -                | -         |     6.45 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           39 |     1844 | 2024-05-21 | Limitless        | W   | 0.702      | -            | -                | -                | -         |     6.79 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     1903 | 2024-05-19 | Limitless        | W   | 0.690      | -            | -                | -                | -         |     3.34 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     2032 | 2024-05-15 | BOSS             | W   | 0.664      | -            | -                | -                | -         |     6.73 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     2042 | 2024-05-15 | BOSS             | W   | 0.663      | -            | -                | -                | -         |     7.09 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2087 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.657      | -            | -                | -                | -         |     5.70 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2092 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.657      | -            | -                | -                | -         |     5.97 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2137 | 2024-05-13 | Nouns            | W   | 0.650      | 0.477        | 0.057 (0.018)    | 0.548 (0.170)    | -         |    11.43 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2138 | 2024-05-13 | Nouns            | L   | 0.650      | -            | -                | -                | -         |    -9.20 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2182 | 2024-05-11 | Elevate          | L   | 0.636      | -            | -                | -                | -         |    -8.37 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2184 | 2024-05-11 | Mythic           | L   | 0.636      | -            | -                | -                | -         |   -14.15 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2234 | 2024-05-09 | MIGHT            | W   | 0.623      | -            | -                | -                | -         |     1.92 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2237 | 2024-05-09 | MIGHT            | W   | 0.623      | -            | -                | -                | -         |     1.96 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           27 |     2250 | 2024-05-08 | Limitless        | W   | 0.617      | -            | -                | -                | -         |     3.23 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           26 |     2253 | 2024-05-08 | Limitless        | W   | 0.617      | -            | -                | -                | -         |     3.33 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           25 |     2367 | 2024-05-02 | Party Astronauts | W   | 0.577      | 0.477        | 0.041 (0.011)    | 0.531 (0.146)    | -         |    10.05 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2368 | 2024-05-02 | Party Astronauts | L   | 0.577      | -            | -                | -                | -         |    -8.27 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2532 | 2024-04-25 | NRG              | W   | 0.530      | -            | -                | -                | -         |     7.36 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2534 | 2024-04-25 | NRG              | L   | 0.530      | -            | -                | -                | -         |    -9.58 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     2574 | 2024-04-23 | Elevate          | W   | 0.517      | 0.477        | 0.027 (0.007)    | -                | -         |     9.80 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     2576 | 2024-04-23 | Elevate          | L   | 0.517      | -            | -                | -                | -         |    -6.59 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           19 |     2768 | 2024-04-17 | Elevate          | L   | 0.476      | -            | -                | -                | -         |    -6.26 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           18 |     3286 | 2024-03-27 | Mythic           | W   | 0.337      | -            | -                | -                | -         |     3.46 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3292 | 2024-03-27 | Mythic           | W   | 0.337      | -            | -                | -                | -         |     3.54 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           16 |     3327 | 2024-03-26 | LAG              | W   | 0.331      | -            | -                | -                | -         |     4.42 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           15 |     3332 | 2024-03-26 | LAG              | L   | 0.330      | -            | -                | -                | -         |    -6.12 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           14 |     3527 | 2024-03-14 | Perseverance     | W   | 0.250      | -            | -                | -                | -         |     2.13 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3530 | 2024-03-14 | Perseverance     | W   | 0.250      | -            | -                | -                | -         |     2.16 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           12 |     3554 | 2024-03-13 | M80              | W   | 0.244      | 0.477        | 0.188 (0.022)    | -                | -         |     6.58 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           11 |     3555 | 2024-03-13 | M80              | L   | 0.244      | -            | -                | -                | -         |    -1.11 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           10 |     3603 | 2024-03-12 | Mythic           | L   | 0.237      | -            | -                | -                | -         |    -5.01 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3843 | 2024-03-03 | M80              | L   | 0.174      | -            | -                | -                | -         |    -0.80 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3856 | 2024-03-02 | BESTIA           | W   | 0.168      | -            | -                | -                | 1 (0.168) |     3.47 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3876 | 2024-03-01 | RED Canids       | L   | 0.162      | -            | -                | -                | -         |    -1.43 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     3959 | 2024-02-25 | Liquid           | L   | 0.131      | -            | -                | -                | -         |    -0.09 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     3963 | 2024-02-25 | BOSS             | L   | 0.129      | -            | -                | -                | -         |    -2.63 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     3980 | 2024-02-24 | NRG              | W   | 0.124      | -            | -                | -                | -         |     1.64 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     3981 | 2024-02-24 | Party Astronauts | W   | 0.123      | -            | -                | -                | -         |     2.05 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     3990 | 2024-02-24 | Akimbo           | W   | 0.123      | -            | -                | -                | -         |     1.16 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     4029 | 2024-02-22 | NRG              | L   | 0.110      | -            | -                | -                | -         |    -2.01 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,762.95)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.877 | $1,500.00      | $1,315.38       |
| 2024-06-09 |      0.830 | $15,000.00     | $12,447.57      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
