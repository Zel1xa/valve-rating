### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, motm, SLIGHT, Sonic, stanislaw<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [21]( ../standings_americas.md)<br />
<br />
Final Rank Value:  944.9<br />
<br />
Final Rank Value (944.9) = Starting Rank Value (874.7) + Head To Head Adjustments (70.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.136[<sup>2</sup>](#table1)
- LAN Wins: 0.018[<sup>2</sup>](#table1)

The average of these factors is 0.231<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 874.7
- 400 + ( ( 0.231 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 874.7


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
|           60 |     1026 | 2024-06-16 | Nouns            | L   | 0.862      | -            | -                | -                | -         |   -12.28 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           59 |     1052 | 2024-06-15 | Mythic           | W   | 0.857      | -            | -                | -                | 0 (0.000) |     8.60 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           58 |     1126 | 2024-06-13 | Final Form       | W   | 0.845      | -            | -                | -                | 0 (0.000) |     4.25 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           57 |     1237 | 2024-06-09 | M80              | L   | 0.817      | -            | -                | -                | -         |    -4.25 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           56 |     1298 | 2024-06-08 | Nouns            | W   | 0.811      | 0.477        | 0.057 (0.022)    | 0.541 (0.209)    | 0 (0.000) |    14.44 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           55 |     1304 | 2024-06-08 | Party Astronauts | L   | 0.809      | -            | -                | -                | -         |   -11.52 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1355 | 2024-06-07 | LAG              | W   | 0.804      | 0.384        | 0.012 (0.004)    | 0.376 (0.116)    | 0 (0.000) |     8.64 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1411 | 2024-06-06 | M80              | L   | 0.797      | -            | -                | -                | -         |    -3.76 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1421 | 2024-06-06 | NRG              | L   | 0.796      | -            | -                | -                | -         |   -13.98 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1427 | 2024-06-06 | M80              | L   | 0.796      | -            | -                | -                | -         |    -4.16 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1446 | 2024-06-06 | NRG              | W   | 0.795      | -            | -                | -                | 0 (0.000) |    10.78 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1482 | 2024-06-05 | Party Astronauts | W   | 0.791      | 0.477        | 0.041 (0.015)    | 0.510 (0.192)    | 0 (0.000) |    12.87 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1536 | 2024-06-04 | Homyno           | W   | 0.784      | -            | -                | -                | 0 (0.000) |     5.60 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1826 | 2024-05-23 | M80              | L   | 0.703      | -            | -                | -                | -         |    -3.41 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1840 | 2024-05-22 | Take Flyte       | W   | 0.698      | -            | -                | -                | 0 (0.000) |     3.98 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1843 | 2024-05-22 | Take Flyte       | W   | 0.698      | -            | -                | -                | 0 (0.000) |     4.13 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1854 | 2024-05-22 | LAG              | W   | 0.697      | 0.384        | -                | 0.376 (0.101)    | -         |     7.53 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1900 | 2024-05-21 | Limitless        | W   | 0.690      | -            | -                | -                | -         |     7.14 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1904 | 2024-05-21 | Limitless        | W   | 0.689      | -            | -                | -                | -         |     7.54 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1963 | 2024-05-19 | Limitless        | W   | 0.677      | -            | -                | -                | -         |     3.85 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     2023 | 2024-05-17 | Nouns            | L   | 0.664      | -            | -                | -                | -         |   -10.48 | Grizz, JBa, motm, SLIGHT, stanislaw      |
|           39 |     2092 | 2024-05-15 | BOSS             | W   | 0.651      | 0.477        | 0.014 (0.004)    | 0.319 (0.099)    | -         |     7.22 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     2102 | 2024-05-15 | BOSS             | W   | 0.651      | 0.477        | 0.014 (0.004)    | 0.319 (0.099)    | -         |     7.61 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     2147 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.644      | -            | -                | -                | -         |     6.17 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     2152 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.644      | -            | -                | -                | -         |     6.47 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2197 | 2024-05-13 | Nouns            | W   | 0.637      | 0.477        | 0.057 (0.017)    | 0.541 (0.164)    | -         |    11.84 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2198 | 2024-05-13 | Nouns            | L   | 0.637      | -            | -                | -                | -         |    -8.34 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2242 | 2024-05-11 | Elevate          | L   | 0.624      | -            | -                | -                | -         |    -7.46 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2244 | 2024-05-11 | Mythic           | L   | 0.623      | -            | -                | -                | -         |   -13.21 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2294 | 2024-05-09 | MIGHT            | W   | 0.611      | -            | -                | -                | -         |     2.17 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2297 | 2024-05-09 | MIGHT            | W   | 0.610      | -            | -                | -                | -         |     2.22 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2310 | 2024-05-08 | Limitless        | W   | 0.604      | -            | -                | -                | -         |     3.64 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2313 | 2024-05-08 | Limitless        | W   | 0.604      | -            | -                | -                | -         |     3.76 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           27 |     2427 | 2024-05-02 | Party Astronauts | W   | 0.564      | 0.477        | 0.041 (0.011)    | 0.510 (0.137)    | -         |    10.47 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           26 |     2428 | 2024-05-02 | Party Astronauts | L   | 0.564      | -            | -                | -                | -         |    -7.41 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           25 |     2592 | 2024-04-25 | NRG              | W   | 0.517      | 0.477        | 0.020 (0.005)    | 0.502 (0.124)    | -         |     7.87 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2594 | 2024-04-25 | NRG              | L   | 0.517      | -            | -                | -                | -         |    -8.63 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2634 | 2024-04-23 | Elevate          | W   | 0.504      | 0.477        | 0.027 (0.006)    | 0.501 (0.120)    | -         |    10.29 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2636 | 2024-04-23 | Elevate          | L   | 0.504      | -            | -                | -                | -         |    -5.66 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     2828 | 2024-04-17 | Elevate          | L   | 0.463      | -            | -                | -                | -         |    -5.34 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     3081 | 2024-04-08 | Cloud9           | L   | 0.405      | -            | -                | -                | -         |    -3.50 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           19 |     3110 | 2024-04-08 | Virtus.pro       | L   | 0.399      | -            | -                | -                | -         |    -0.14 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           18 |     3346 | 2024-03-27 | Mythic           | W   | 0.324      | -            | -                | -                | -         |     3.73 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3352 | 2024-03-27 | Mythic           | W   | 0.324      | -            | -                | -                | -         |     3.83 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           16 |     3387 | 2024-03-26 | LAG              | W   | 0.318      | -            | -                | -                | -         |     4.50 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           15 |     3392 | 2024-03-26 | LAG              | L   | 0.318      | -            | -                | -                | -         |    -5.62 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           14 |     3587 | 2024-03-14 | Phoenix          | W   | 0.237      | -            | -                | -                | -         |     2.30 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3590 | 2024-03-14 | Phoenix          | W   | 0.237      | -            | -                | -                | -         |     2.34 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           12 |     3614 | 2024-03-13 | M80              | W   | 0.231      | 0.477        | 0.188 (0.021)    | -                | -         |     6.37 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           11 |     3615 | 2024-03-13 | M80              | L   | 0.231      | -            | -                | -                | -         |    -0.91 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           10 |     3663 | 2024-03-12 | Mythic           | L   | 0.224      | -            | -                | -                | -         |    -4.43 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3903 | 2024-03-03 | M80              | L   | 0.161      | -            | -                | -                | -         |    -0.65 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3916 | 2024-03-02 | BESTIA           | W   | 0.155      | -            | -                | -                | 1 (0.155) |     3.39 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3936 | 2024-03-01 | RED Canids       | L   | 0.149      | -            | -                | -                | -         |    -1.17 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     4019 | 2024-02-25 | Liquid           | L   | 0.118      | -            | -                | -                | -         |    -0.07 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     4023 | 2024-02-25 | BOSS             | L   | 0.117      | -            | -                | -                | -         |    -2.19 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     4040 | 2024-02-24 | NRG              | W   | 0.111      | -            | -                | -                | -         |     1.63 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     4041 | 2024-02-24 | Party Astronauts | W   | 0.110      | -            | -                | -                | -         |     1.99 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     4050 | 2024-02-24 | Akimbo           | W   | 0.110      | -            | -                | -                | -         |     1.19 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     4089 | 2024-02-22 | NRG              | L   | 0.097      | -            | -                | -                | -         |    -1.62 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,309.75)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.864 | $1,500.00      | $1,296.04       |
| 2024-06-09 |      0.817 | $15,000.00     | $12,254.17      |
| 2024-04-14 |      0.440 | $4,000.00      | $1,759.54       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
