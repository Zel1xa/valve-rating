### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, motm, SLIGHT, Sonic, stanislaw<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [21]( ../standings_americas.md)<br />
<br />
Final Rank Value:  946.1<br />
<br />
Final Rank Value (946.1) = Starting Rank Value (875.4) + Head To Head Adjustments (70.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.140[<sup>2</sup>](#table1)
- LAN Wins: 0.019[<sup>2</sup>](#table1)

The average of these factors is 0.232<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 875.4
- 400 + ( ( 0.232 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 875.4


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
|           60 |     1007 | 2024-06-16 | Nouns            | L   | 0.868      | -            | -                | -                | -         |   -12.35 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           59 |     1033 | 2024-06-15 | Mythic           | W   | 0.863      | 0.371        | -                | 0.297 (0.095)    | 0 (0.000) |     8.64 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           58 |     1107 | 2024-06-13 | Final Form       | W   | 0.851      | -            | -                | -                | 0 (0.000) |     4.24 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           57 |     1218 | 2024-06-09 | M80              | L   | 0.823      | -            | -                | -                | -         |    -4.27 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           56 |     1279 | 2024-06-08 | Nouns            | W   | 0.817      | 0.477        | 0.057 (0.022)    | 0.560 (0.218)    | 0 (0.000) |    14.56 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           55 |     1285 | 2024-06-08 | Party Astronauts | L   | 0.816      | -            | -                | -                | -         |   -11.58 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1336 | 2024-06-07 | LAG              | W   | 0.810      | 0.384        | 0.012 (0.004)    | 0.351 (0.109)    | 0 (0.000) |     8.69 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1392 | 2024-06-06 | M80              | L   | 0.803      | -            | -                | -                | -         |    -3.78 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1402 | 2024-06-06 | NRG              | L   | 0.802      | -            | -                | -                | -         |   -14.09 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1408 | 2024-06-06 | M80              | L   | 0.802      | -            | -                | -                | -         |    -4.18 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1427 | 2024-06-06 | NRG              | W   | 0.801      | -            | -                | -                | 0 (0.000) |    10.85 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1463 | 2024-06-05 | Party Astronauts | W   | 0.797      | 0.477        | 0.041 (0.016)    | 0.529 (0.201)    | 0 (0.000) |    12.98 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1517 | 2024-06-04 | Homyno           | W   | 0.790      | -            | -                | -                | 0 (0.000) |     5.61 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1807 | 2024-05-23 | M80              | L   | 0.709      | -            | -                | -                | -         |    -3.43 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1821 | 2024-05-22 | Take Flyte       | W   | 0.704      | -            | -                | -                | 0 (0.000) |     3.99 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1824 | 2024-05-22 | Take Flyte       | W   | 0.704      | -            | -                | -                | 0 (0.000) |     4.14 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1835 | 2024-05-22 | LAG              | W   | 0.703      | -            | -                | -                | -         |     7.59 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1881 | 2024-05-21 | Limitless        | W   | 0.696      | -            | -                | -                | -         |     7.18 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1885 | 2024-05-21 | Limitless        | W   | 0.696      | -            | -                | -                | -         |     7.59 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1944 | 2024-05-19 | Limitless        | W   | 0.683      | -            | -                | -                | -         |     3.85 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     2004 | 2024-05-17 | Nouns            | L   | 0.670      | -            | -                | -                | -         |   -10.57 | Grizz, JBa, motm, SLIGHT, stanislaw      |
|           39 |     2073 | 2024-05-15 | BOSS             | W   | 0.657      | 0.477        | 0.014 (0.004)    | 0.331 (0.104)    | -         |     7.25 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     2083 | 2024-05-15 | BOSS             | W   | 0.657      | 0.477        | 0.014 (0.004)    | 0.331 (0.104)    | -         |     7.64 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     2128 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.650      | -            | -                | -                | -         |     6.19 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     2133 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.650      | -            | -                | -                | -         |     6.50 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2178 | 2024-05-13 | Nouns            | W   | 0.644      | 0.477        | 0.057 (0.018)    | 0.560 (0.172)    | -         |    11.97 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2179 | 2024-05-13 | Nouns            | L   | 0.643      | -            | -                | -                | -         |    -8.40 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2223 | 2024-05-11 | Elevate          | L   | 0.630      | -            | -                | -                | -         |    -7.54 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2225 | 2024-05-11 | Mythic           | L   | 0.629      | -            | -                | -                | -         |   -13.35 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2275 | 2024-05-09 | MIGHT            | W   | 0.617      | -            | -                | -                | -         |     2.18 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2278 | 2024-05-09 | MIGHT            | W   | 0.616      | -            | -                | -                | -         |     2.23 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2291 | 2024-05-08 | Limitless        | W   | 0.610      | -            | -                | -                | -         |     3.65 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2294 | 2024-05-08 | Limitless        | W   | 0.610      | -            | -                | -                | -         |     3.77 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           27 |     2408 | 2024-05-02 | Party Astronauts | W   | 0.570      | 0.477        | 0.041 (0.011)    | 0.529 (0.144)    | -         |    10.60 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           26 |     2409 | 2024-05-02 | Party Astronauts | L   | 0.570      | -            | -                | -                | -         |    -7.46 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           25 |     2573 | 2024-04-25 | NRG              | W   | 0.524      | 0.477        | 0.020 (0.005)    | 0.520 (0.130)    | -         |     7.96 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2575 | 2024-04-25 | NRG              | L   | 0.523      | -            | -                | -                | -         |    -8.73 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2615 | 2024-04-23 | Elevate          | W   | 0.510      | 0.477        | 0.027 (0.007)    | 0.519 (0.126)    | -         |    10.41 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2617 | 2024-04-23 | Elevate          | L   | 0.510      | -            | -                | -                | -         |    -5.73 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     2809 | 2024-04-17 | Elevate          | L   | 0.469      | -            | -                | -                | -         |    -5.41 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     3062 | 2024-04-08 | Cloud9           | L   | 0.411      | -            | -                | -                | -         |    -3.51 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           19 |     3091 | 2024-04-08 | Virtus.pro       | L   | 0.405      | -            | -                | -                | -         |    -0.14 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           18 |     3327 | 2024-03-27 | Mythic           | W   | 0.330      | -            | -                | -                | -         |     3.80 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3333 | 2024-03-27 | Mythic           | W   | 0.330      | -            | -                | -                | -         |     3.90 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           16 |     3368 | 2024-03-26 | LAG              | W   | 0.324      | -            | -                | -                | -         |     4.59 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           15 |     3373 | 2024-03-26 | LAG              | L   | 0.324      | -            | -                | -                | -         |    -5.72 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           14 |     3568 | 2024-03-14 | Phoenix          | W   | 0.243      | -            | -                | -                | -         |     2.35 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3571 | 2024-03-14 | Phoenix          | W   | 0.243      | -            | -                | -                | -         |     2.40 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           12 |     3595 | 2024-03-13 | M80              | W   | 0.237      | 0.477        | 0.188 (0.021)    | -                | -         |     6.54 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           11 |     3596 | 2024-03-13 | M80              | L   | 0.237      | -            | -                | -                | -         |    -0.93 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           10 |     3644 | 2024-03-12 | Mythic           | L   | 0.230      | -            | -                | -                | -         |    -4.55 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3884 | 2024-03-03 | M80              | L   | 0.168      | -            | -                | -                | -         |    -0.67 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3897 | 2024-03-02 | BESTIA           | W   | 0.161      | -            | -                | -                | 1 (0.161) |     3.54 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3917 | 2024-03-01 | RED Canids       | L   | 0.156      | -            | -                | -                | -         |    -1.20 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     4000 | 2024-02-25 | Liquid           | L   | 0.124      | -            | -                | -                | -         |    -0.07 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     4004 | 2024-02-25 | BOSS             | L   | 0.123      | -            | -                | -                | -         |    -2.31 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     4021 | 2024-02-24 | NRG              | W   | 0.117      | -            | -                | -                | -         |     1.72 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     4022 | 2024-02-24 | Party Astronauts | W   | 0.116      | -            | -                | -                | -         |     2.10 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     4031 | 2024-02-24 | Akimbo           | W   | 0.116      | -            | -                | -                | -         |     1.25 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     4070 | 2024-02-22 | NRG              | L   | 0.103      | -            | -                | -                | -         |    -1.73 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,435.02)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.870 | $1,500.00      | $1,305.21       |
| 2024-06-09 |      0.823 | $15,000.00     | $12,345.83      |
| 2024-04-14 |      0.446 | $4,000.00      | $1,783.98       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
