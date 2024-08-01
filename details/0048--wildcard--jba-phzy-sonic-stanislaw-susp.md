### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, phzy, Sonic, stanislaw, susp<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [12]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1057.5<br />
<br />
Final Rank Value (1057.5) = Starting Rank Value (917.9) + Head To Head Adjustments (139.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.443[<sup>1</sup>](#table2)
- Bounty Collected: 0.353[<sup>2</sup>](#table1)
- Opponent Network: 0.189[<sup>2</sup>](#table1)
- LAN Wins: 0.022[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 917.9
- 400 + ( ( 0.252 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 917.9


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
|           69 |       21 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |     9.79 | JBa, phzy, Sonic, stanislaw, susp        |
|           68 |       27 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    10.57 | JBa, phzy, Sonic, stanislaw, susp        |
|           67 |      362 | 2024-07-21 | NRG              | W   | 1.000      | 0.303        | -                | 0.519 (0.157)    | 0 (0.000) |    15.45 | JBa, phzy, Sonic, stanislaw, susp        |
|           66 |      363 | 2024-07-21 | Elevate          | W   | 1.000      | 0.303        | 0.027 (0.008)    | 0.505 (0.153)    | 0 (0.000) |    13.23 | JBa, phzy, Sonic, stanislaw, susp        |
|           65 |      389 | 2024-07-20 | Party Astronauts | W   | 1.000      | 0.303        | 0.042 (0.013)    | 0.532 (0.161)    | 0 (0.000) |    15.68 | JBa, phzy, Sonic, stanislaw, susp        |
|           64 |      466 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.23 | JBa, phzy, Sonic, stanislaw, susp        |
|           63 |      472 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.50 | JBa, phzy, Sonic, stanislaw, susp        |
|           62 |      540 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.06 | JBa, phzy, Sonic, stanislaw, susp        |
|           61 |      543 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.41 | JBa, phzy, Sonic, stanislaw, susp        |
|           60 |      599 | 2024-07-16 | LAG              | W   | 1.000      | 0.477        | -                | 0.371 (0.177)    | -         |    12.61 | JBa, phzy, Sonic, stanislaw, susp        |
|           59 |      605 | 2024-07-16 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -19.18 | JBa, phzy, Sonic, stanislaw, susp        |
|           58 |      893 | 2024-06-16 | Nouns            | L   | 0.894      | -            | -                | -                | -         |   -13.76 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           57 |      916 | 2024-06-15 | Mythic           | W   | 0.888      | -            | -                | -                | -         |     8.16 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           56 |      982 | 2024-06-13 | Final Form       | W   | 0.876      | -            | -                | -                | -         |     3.89 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           55 |     1095 | 2024-06-09 | M80              | L   | 0.848      | -            | -                | -                | -         |    -4.69 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1157 | 2024-06-08 | Nouns            | W   | 0.842      | 0.477        | 0.058 (0.023)    | 0.557 (0.224)    | -         |    13.60 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1164 | 2024-06-08 | Party Astronauts | L   | 0.841      | -            | -                | -                | -         |   -12.73 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1218 | 2024-06-07 | LAG              | W   | 0.835      | -            | -                | -                | -         |     8.65 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1279 | 2024-06-06 | M80              | L   | 0.829      | -            | -                | -                | -         |    -4.21 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1290 | 2024-06-06 | NRG              | L   | 0.828      | -            | -                | -                | -         |   -15.30 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1296 | 2024-06-06 | M80              | L   | 0.827      | -            | -                | -                | -         |    -4.70 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1315 | 2024-06-06 | NRG              | W   | 0.826      | -            | -                | -                | -         |    10.35 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1352 | 2024-06-05 | Party Astronauts | W   | 0.822      | 0.477        | 0.042 (0.016)    | 0.532 (0.209)    | -         |    12.44 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1408 | 2024-06-04 | Homyno           | W   | 0.815      | -            | -                | -                | -         |     4.99 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1701 | 2024-05-23 | M80              | L   | 0.734      | -            | -                | -                | -         |    -3.90 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1715 | 2024-05-22 | Take Flyte       | W   | 0.729      | -            | -                | -                | -         |     3.48 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1718 | 2024-05-22 | Take Flyte       | W   | 0.729      | -            | -                | -                | -         |     3.60 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1729 | 2024-05-22 | LAG              | W   | 0.728      | -            | -                | -                | -         |     7.51 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1787 | 2024-05-21 | Limitless        | W   | 0.721      | -            | -                | -                | -         |     6.57 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     1791 | 2024-05-21 | Limitless        | W   | 0.721      | -            | -                | -                | -         |     6.93 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           39 |     1858 | 2024-05-19 | Limitless        | W   | 0.708      | -            | -                | -                | -         |     3.34 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     1993 | 2024-05-15 | BOSS             | W   | 0.682      | -            | -                | -                | -         |     6.94 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     2003 | 2024-05-15 | BOSS             | W   | 0.682      | -            | -                | -                | -         |     7.32 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     2054 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.676      | -            | -                | -                | -         |     5.82 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2059 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.675      | -            | -                | -                | -         |     6.11 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2105 | 2024-05-13 | Nouns            | W   | 0.669      | 0.477        | 0.058 (0.019)    | 0.557 (0.178)    | -         |    11.76 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2106 | 2024-05-13 | Nouns            | L   | 0.669      | -            | -                | -                | -         |    -9.44 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2152 | 2024-05-11 | Elevate          | L   | 0.655      | -            | -                | -                | -         |    -8.56 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2154 | 2024-05-11 | Mythic           | L   | 0.655      | -            | -                | -                | -         |   -14.60 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2204 | 2024-05-09 | MIGHT            | W   | 0.642      | -            | -                | -                | -         |     1.94 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2207 | 2024-05-09 | MIGHT            | W   | 0.642      | -            | -                | -                | -         |     1.98 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2220 | 2024-05-08 | Limitless        | W   | 0.636      | -            | -                | -                | -         |     3.24 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           27 |     2223 | 2024-05-08 | Limitless        | W   | 0.635      | -            | -                | -                | -         |     3.34 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           26 |     2339 | 2024-05-02 | Party Astronauts | W   | 0.595      | 0.477        | 0.042 (0.012)    | 0.532 (0.151)    | -         |    10.40 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           25 |     2340 | 2024-05-02 | Party Astronauts | L   | 0.595      | -            | -                | -                | -         |    -8.49 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2507 | 2024-04-25 | NRG              | W   | 0.549      | -            | -                | -                | -         |     7.57 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2509 | 2024-04-25 | NRG              | L   | 0.549      | -            | -                | -                | -         |    -9.96 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2549 | 2024-04-23 | Elevate          | W   | 0.536      | 0.477        | 0.027 (0.007)    | -                | -         |    10.20 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     2551 | 2024-04-23 | Elevate          | L   | 0.535      | -            | -                | -                | -         |    -6.77 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     2751 | 2024-04-17 | Elevate          | L   | 0.494      | -            | -                | -                | -         |    -6.46 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           19 |     3280 | 2024-03-27 | Mythic           | W   | 0.355      | -            | -                | -                | -         |     3.63 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           18 |     3286 | 2024-03-27 | Mythic           | W   | 0.355      | -            | -                | -                | -         |     3.73 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3322 | 2024-03-26 | LAG              | W   | 0.349      | -            | -                | -                | -         |     4.70 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           16 |     3327 | 2024-03-26 | LAG              | L   | 0.349      | -            | -                | -                | -         |    -6.43 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           15 |     3526 | 2024-03-14 | Perseverance     | W   | 0.269      | -            | -                | -                | -         |     2.26 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           14 |     3529 | 2024-03-14 | Perseverance     | W   | 0.268      | -            | -                | -                | -         |     2.30 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3557 | 2024-03-13 | M80              | W   | 0.263      | 0.477        | 0.190 (0.024)    | -                | -         |     7.12 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           12 |     3558 | 2024-03-13 | M80              | L   | 0.262      | -            | -                | -                | -         |    -1.15 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           11 |     3606 | 2024-03-12 | Mythic           | L   | 0.255      | -            | -                | -                | -         |    -5.41 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           10 |     3854 | 2024-03-03 | M80              | L   | 0.193      | -            | -                | -                | -         |    -0.86 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3866 | 2024-03-02 | BESTIA           | W   | 0.187      | -            | -                | -                | 1 (0.187) |     3.80 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3887 | 2024-03-01 | RED Canids       | L   | 0.181      | -            | -                | -                | -         |    -2.01 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3972 | 2024-02-25 | Liquid           | L   | 0.149      | -            | -                | -                | -         |    -0.16 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     3976 | 2024-02-25 | BOSS             | L   | 0.148      | -            | -                | -                | -         |    -2.98 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     3994 | 2024-02-24 | NRG              | W   | 0.142      | -            | -                | -                | -         |     1.87 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     3995 | 2024-02-24 | Party Astronauts | W   | 0.142      | -            | -                | -                | -         |     2.37 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     4004 | 2024-02-24 | Akimbo           | W   | 0.141      | -            | -                | -                | -         |     1.33 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     4047 | 2024-02-22 | NRG              | L   | 0.128      | -            | -                | -                | -         |    -2.36 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     4409 | 2024-02-04 | Elevate          | L   | 0.008      | -            | -                | -                | -         |    -0.10 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,068.13)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.895 | $1,500.00      | $1,343.13       |
| 2024-06-09 |      0.848 | $15,000.00     | $12,725.00      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
