### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, motm, SLIGHT, Sonic, stanislaw<br />
Global Rank: [82](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [21]( ../standings_americas.md)<br />
<br />
Final Rank Value:  944.6<br />
<br />
Final Rank Value (944.6) = Starting Rank Value (874.4) + Head To Head Adjustments (70.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.136[<sup>2</sup>](#table1)
- LAN Wins: 0.018[<sup>2</sup>](#table1)

The average of these factors is 0.231<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 874.4
- 400 + ( ( 0.231 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 874.4


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
|           60 |     1039 | 2024-06-16 | Nouns            | L   | 0.861      | -            | -                | -                | -         |   -12.26 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           59 |     1065 | 2024-06-15 | Mythic           | W   | 0.855      | -            | -                | -                | 0 (0.000) |     8.59 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           58 |     1139 | 2024-06-13 | Final Form       | W   | 0.843      | -            | -                | -                | 0 (0.000) |     4.25 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           57 |     1250 | 2024-06-09 | M80              | L   | 0.816      | -            | -                | -                | -         |    -4.24 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           56 |     1311 | 2024-06-08 | Nouns            | W   | 0.809      | 0.477        | 0.057 (0.022)    | 0.541 (0.209)    | 0 (0.000) |    14.41 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           55 |     1317 | 2024-06-08 | Party Astronauts | L   | 0.808      | -            | -                | -                | -         |   -11.49 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1368 | 2024-06-07 | LAG              | W   | 0.802      | 0.384        | 0.012 (0.004)    | 0.376 (0.116)    | 0 (0.000) |     8.63 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1424 | 2024-06-06 | M80              | L   | 0.796      | -            | -                | -                | -         |    -3.75 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1434 | 2024-06-06 | NRG              | L   | 0.795      | -            | -                | -                | -         |   -13.95 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1440 | 2024-06-06 | M80              | L   | 0.794      | -            | -                | -                | -         |    -4.16 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1459 | 2024-06-06 | NRG              | W   | 0.794      | -            | -                | -                | 0 (0.000) |    10.76 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1495 | 2024-06-05 | Party Astronauts | W   | 0.789      | 0.477        | 0.041 (0.015)    | 0.510 (0.192)    | 0 (0.000) |    12.85 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1549 | 2024-06-04 | Homyno           | W   | 0.782      | -            | -                | -                | 0 (0.000) |     5.60 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1839 | 2024-05-23 | M80              | L   | 0.702      | -            | -                | -                | -         |    -3.40 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1853 | 2024-05-22 | Take Flyte       | W   | 0.696      | -            | -                | -                | 0 (0.000) |     3.98 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1856 | 2024-05-22 | Take Flyte       | W   | 0.696      | -            | -                | -                | 0 (0.000) |     4.13 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1867 | 2024-05-22 | LAG              | W   | 0.695      | 0.384        | -                | 0.376 (0.100)    | -         |     7.52 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1913 | 2024-05-21 | Limitless        | W   | 0.688      | -            | -                | -                | -         |     7.13 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1917 | 2024-05-21 | Limitless        | W   | 0.688      | -            | -                | -                | -         |     7.53 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1976 | 2024-05-19 | Limitless        | W   | 0.675      | -            | -                | -                | -         |     3.84 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     2036 | 2024-05-17 | Nouns            | L   | 0.662      | -            | -                | -                | -         |   -10.45 | Grizz, JBa, motm, SLIGHT, stanislaw      |
|           39 |     2105 | 2024-05-15 | BOSS             | W   | 0.649      | 0.477        | 0.014 (0.004)    | 0.319 (0.099)    | -         |     7.21 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     2115 | 2024-05-15 | BOSS             | W   | 0.649      | 0.477        | 0.014 (0.004)    | 0.319 (0.099)    | -         |     7.60 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     2160 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.643      | -            | -                | -                | -         |     6.16 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     2165 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.642      | -            | -                | -                | -         |     6.46 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2210 | 2024-05-13 | Nouns            | W   | 0.636      | 0.477        | 0.057 (0.017)    | 0.541 (0.164)    | -         |    11.82 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2211 | 2024-05-13 | Nouns            | L   | 0.636      | -            | -                | -                | -         |    -8.32 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2255 | 2024-05-11 | Elevate          | L   | 0.622      | -            | -                | -                | -         |    -7.43 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2257 | 2024-05-11 | Mythic           | L   | 0.622      | -            | -                | -                | -         |   -13.17 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2307 | 2024-05-09 | MIGHT            | W   | 0.609      | -            | -                | -                | -         |     2.17 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2310 | 2024-05-09 | MIGHT            | W   | 0.609      | -            | -                | -                | -         |     2.21 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2323 | 2024-05-08 | Limitless        | W   | 0.603      | -            | -                | -                | -         |     3.64 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2326 | 2024-05-08 | Limitless        | W   | 0.603      | -            | -                | -                | -         |     3.76 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           27 |     2440 | 2024-05-02 | Party Astronauts | W   | 0.563      | 0.477        | 0.041 (0.011)    | 0.510 (0.137)    | -         |    10.44 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           26 |     2441 | 2024-05-02 | Party Astronauts | L   | 0.562      | -            | -                | -                | -         |    -7.39 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           25 |     2605 | 2024-04-25 | NRG              | W   | 0.516      | 0.477        | 0.020 (0.005)    | 0.502 (0.124)    | -         |     7.85 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2607 | 2024-04-25 | NRG              | L   | 0.516      | -            | -                | -                | -         |    -8.60 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2647 | 2024-04-23 | Elevate          | W   | 0.503      | 0.477        | 0.027 (0.006)    | 0.501 (0.120)    | -         |    10.26 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2649 | 2024-04-23 | Elevate          | L   | 0.502      | -            | -                | -                | -         |    -5.64 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     2841 | 2024-04-17 | Elevate          | L   | 0.462      | -            | -                | -                | -         |    -5.32 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     3094 | 2024-04-08 | Cloud9           | L   | 0.404      | -            | -                | -                | -         |    -3.50 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           19 |     3123 | 2024-04-08 | Virtus.pro       | L   | 0.398      | -            | -                | -                | -         |    -0.14 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           18 |     3359 | 2024-03-27 | Mythic           | W   | 0.322      | -            | -                | -                | -         |     3.72 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3365 | 2024-03-27 | Mythic           | W   | 0.322      | -            | -                | -                | -         |     3.82 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           16 |     3400 | 2024-03-26 | LAG              | W   | 0.316      | -            | -                | -                | -         |     4.48 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           15 |     3405 | 2024-03-26 | LAG              | L   | 0.316      | -            | -                | -                | -         |    -5.59 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           14 |     3600 | 2024-03-14 | Phoenix          | W   | 0.236      | -            | -                | -                | -         |     2.29 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3603 | 2024-03-14 | Phoenix          | W   | 0.236      | -            | -                | -                | -         |     2.33 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           12 |     3627 | 2024-03-13 | M80              | W   | 0.230      | 0.477        | 0.188 (0.021)    | -                | -         |     6.33 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           11 |     3628 | 2024-03-13 | M80              | L   | 0.229      | -            | -                | -                | -         |    -0.91 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           10 |     3676 | 2024-03-12 | Mythic           | L   | 0.222      | -            | -                | -                | -         |    -4.40 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3916 | 2024-03-03 | M80              | L   | 0.160      | -            | -                | -                | -         |    -0.64 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3929 | 2024-03-02 | BESTIA           | W   | 0.154      | -            | -                | -                | 1 (0.154) |     3.36 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3949 | 2024-03-01 | RED Canids       | L   | 0.148      | -            | -                | -                | -         |    -1.15 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     4032 | 2024-02-25 | Liquid           | L   | 0.116      | -            | -                | -                | -         |    -0.07 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     4036 | 2024-02-25 | BOSS             | L   | 0.115      | -            | -                | -                | -         |    -2.16 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     4053 | 2024-02-24 | NRG              | W   | 0.109      | -            | -                | -                | -         |     1.61 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     4054 | 2024-02-24 | Party Astronauts | W   | 0.109      | -            | -                | -                | -         |     1.96 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     4063 | 2024-02-24 | Akimbo           | W   | 0.109      | -            | -                | -                | -         |     1.17 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     4102 | 2024-02-22 | NRG              | L   | 0.095      | -            | -                | -                | -         |    -1.60 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,281.27)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.863 | $1,500.00      | $1,293.96       |
| 2024-06-09 |      0.816 | $15,000.00     | $12,233.33      |
| 2024-04-14 |      0.438 | $4,000.00      | $1,753.98       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
