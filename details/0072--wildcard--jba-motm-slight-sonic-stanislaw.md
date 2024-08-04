### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, motm, SLIGHT, Sonic, stanislaw<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [21]( ../standings_americas.md)<br />
<br />
Final Rank Value:  947.1<br />
<br />
Final Rank Value (947.1) = Starting Rank Value (876.4) + Head To Head Adjustments (70.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.340[<sup>2</sup>](#table1)
- Opponent Network: 0.142[<sup>2</sup>](#table1)
- LAN Wins: 0.019[<sup>2</sup>](#table1)

The average of these factors is 0.233<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 876.4
- 400 + ( ( 0.233 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 876.4


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
|           60 |      990 | 2024-06-16 | Nouns            | L   | 0.874      | -            | -                | -                | -         |   -12.44 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           59 |     1016 | 2024-06-15 | Mythic           | W   | 0.869      | 0.371        | -                | 0.299 (0.096)    | 0 (0.000) |     8.66 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           58 |     1090 | 2024-06-13 | Final Form       | W   | 0.856      | -            | -                | -                | 0 (0.000) |     4.24 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           57 |     1201 | 2024-06-09 | M80              | L   | 0.829      | -            | -                | -                | -         |    -4.30 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           56 |     1262 | 2024-06-08 | Nouns            | W   | 0.822      | 0.477        | 0.057 (0.022)    | 0.561 (0.220)    | 0 (0.000) |    14.64 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           55 |     1268 | 2024-06-08 | Party Astronauts | L   | 0.821      | -            | -                | -                | -         |   -11.69 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1319 | 2024-06-07 | LAG              | W   | 0.816      | 0.384        | 0.012 (0.004)    | 0.353 (0.111)    | 0 (0.000) |     8.74 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1375 | 2024-06-06 | M80              | L   | 0.809      | -            | -                | -                | -         |    -3.80 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1385 | 2024-06-06 | NRG              | L   | 0.808      | -            | -                | -                | -         |   -14.22 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1391 | 2024-06-06 | M80              | L   | 0.807      | -            | -                | -                | -         |    -4.21 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1410 | 2024-06-06 | NRG              | W   | 0.807      | -            | -                | -                | 0 (0.000) |    10.89 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1446 | 2024-06-05 | Party Astronauts | W   | 0.802      | 0.477        | 0.041 (0.016)    | 0.531 (0.203)    | 0 (0.000) |    13.04 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1500 | 2024-06-04 | Homyno           | W   | 0.796      | -            | -                | -                | 0 (0.000) |     5.62 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1790 | 2024-05-23 | M80              | L   | 0.715      | -            | -                | -                | -         |    -3.46 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1804 | 2024-05-22 | Take Flyte       | W   | 0.710      | -            | -                | -                | 0 (0.000) |     3.99 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1807 | 2024-05-22 | Take Flyte       | W   | 0.709      | -            | -                | -                | 0 (0.000) |     4.14 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1818 | 2024-05-22 | LAG              | W   | 0.708      | -            | -                | -                | -         |     7.63 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1864 | 2024-05-21 | Limitless        | W   | 0.702      | -            | -                | -                | -         |     7.23 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1868 | 2024-05-21 | Limitless        | W   | 0.701      | -            | -                | -                | -         |     7.64 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1927 | 2024-05-19 | Limitless        | W   | 0.688      | -            | -                | -                | -         |     3.86 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     1987 | 2024-05-17 | Nouns            | L   | 0.676      | -            | -                | -                | -         |   -10.68 | Grizz, JBa, motm, SLIGHT, stanislaw      |
|           39 |     2056 | 2024-05-15 | BOSS             | W   | 0.663      | 0.477        | 0.014 (0.004)    | 0.332 (0.105)    | -         |     7.29 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     2066 | 2024-05-15 | BOSS             | W   | 0.662      | 0.477        | 0.014 (0.004)    | 0.332 (0.105)    | -         |     7.70 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     2111 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.656      | -            | -                | -                | -         |     6.22 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     2116 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.656      | -            | -                | -                | -         |     6.54 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2161 | 2024-05-13 | Nouns            | W   | 0.649      | 0.477        | 0.057 (0.018)    | 0.561 (0.174)    | -         |    12.07 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2162 | 2024-05-13 | Nouns            | L   | 0.649      | -            | -                | -                | -         |    -8.48 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2206 | 2024-05-11 | Elevate          | L   | 0.635      | -            | -                | -                | -         |    -7.62 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2208 | 2024-05-11 | Mythic           | L   | 0.635      | -            | -                | -                | -         |   -13.51 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2258 | 2024-05-09 | MIGHT            | W   | 0.622      | -            | -                | -                | -         |     2.20 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2261 | 2024-05-09 | MIGHT            | W   | 0.622      | -            | -                | -                | -         |     2.25 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2274 | 2024-05-08 | Limitless        | W   | 0.616      | -            | -                | -                | -         |     3.66 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2277 | 2024-05-08 | Limitless        | W   | 0.616      | -            | -                | -                | -         |     3.78 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           27 |     2391 | 2024-05-02 | Party Astronauts | W   | 0.576      | 0.477        | 0.041 (0.011)    | 0.531 (0.146)    | -         |    10.69 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           26 |     2392 | 2024-05-02 | Party Astronauts | L   | 0.575      | -            | -                | -                | -         |    -7.56 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           25 |     2556 | 2024-04-25 | NRG              | W   | 0.529      | 0.477        | 0.020 (0.005)    | 0.521 (0.132)    | -         |     8.02 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2558 | 2024-04-25 | NRG              | L   | 0.529      | -            | -                | -                | -         |    -8.86 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2598 | 2024-04-23 | Elevate          | W   | 0.516      | 0.477        | 0.027 (0.007)    | 0.521 (0.128)    | -         |    10.51 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2600 | 2024-04-23 | Elevate          | L   | 0.516      | -            | -                | -                | -         |    -5.81 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     2792 | 2024-04-17 | Elevate          | L   | 0.475      | -            | -                | -                | -         |    -5.50 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     3045 | 2024-04-08 | Cloud9           | L   | 0.417      | -            | -                | -                | -         |    -3.50 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           19 |     3074 | 2024-04-08 | Virtus.pro       | L   | 0.411      | -            | -                | -                | -         |    -0.14 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           18 |     3310 | 2024-03-27 | Mythic           | W   | 0.336      | -            | -                | -                | -         |     3.85 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3316 | 2024-03-27 | Mythic           | W   | 0.335      | -            | -                | -                | -         |     3.95 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           16 |     3351 | 2024-03-26 | LAG              | W   | 0.330      | -            | -                | -                | -         |     4.67 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           15 |     3356 | 2024-03-26 | LAG              | L   | 0.329      | -            | -                | -                | -         |    -5.82 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           14 |     3551 | 2024-03-14 | Phoenix          | W   | 0.249      | -            | -                | -                | -         |     2.40 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3554 | 2024-03-14 | Phoenix          | W   | 0.249      | -            | -                | -                | -         |     2.44 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           12 |     3578 | 2024-03-13 | M80              | W   | 0.243      | 0.477        | 0.188 (0.022)    | -                | -         |     6.70 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           11 |     3579 | 2024-03-13 | M80              | L   | 0.243      | -            | -                | -                | -         |    -0.95 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           10 |     3627 | 2024-03-12 | Mythic           | L   | 0.236      | -            | -                | -                | -         |    -4.68 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3867 | 2024-03-03 | M80              | L   | 0.173      | -            | -                | -                | -         |    -0.69 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3880 | 2024-03-02 | BESTIA           | W   | 0.167      | -            | -                | -                | 1 (0.167) |     3.66 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3900 | 2024-03-01 | RED Canids       | L   | 0.161      | -            | -                | -                | -         |    -1.24 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     3983 | 2024-02-25 | Liquid           | L   | 0.129      | -            | -                | -                | -         |    -0.07 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     3987 | 2024-02-25 | BOSS             | L   | 0.128      | -            | -                | -                | -         |    -2.42 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     4004 | 2024-02-24 | NRG              | W   | 0.122      | -            | -                | -                | -         |     1.80 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     4005 | 2024-02-24 | Party Astronauts | W   | 0.122      | -            | -                | -                | -         |     2.20 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     4014 | 2024-02-24 | Akimbo           | W   | 0.122      | -            | -                | -                | -         |     1.31 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     4053 | 2024-02-22 | NRG              | L   | 0.109      | -            | -                | -                | -         |    -1.83 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,552.23)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.876 | $1,500.00      | $1,313.78       |
| 2024-06-09 |      0.829 | $15,000.00     | $12,431.60      |
| 2024-04-14 |      0.452 | $4,000.00      | $1,806.85       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
