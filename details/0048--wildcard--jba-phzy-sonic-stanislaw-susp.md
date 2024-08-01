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
Final Rank Value:  1058.2<br />
<br />
Final Rank Value (1058.2) = Starting Rank Value (918.7) + Head To Head Adjustments (139.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.443[<sup>1</sup>](#table2)
- Bounty Collected: 0.354[<sup>2</sup>](#table1)
- Opponent Network: 0.189[<sup>2</sup>](#table1)
- LAN Wins: 0.022[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 918.7
- 400 + ( ( 0.252 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 918.7


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
|           69 |       14 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |     9.79 | JBa, phzy, Sonic, stanislaw, susp        |
|           68 |       20 | 2024-07-31 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    10.57 | JBa, phzy, Sonic, stanislaw, susp        |
|           67 |      356 | 2024-07-21 | NRG              | W   | 1.000      | 0.303        | -                | 0.519 (0.157)    | 0 (0.000) |    15.45 | JBa, phzy, Sonic, stanislaw, susp        |
|           66 |      357 | 2024-07-21 | Elevate          | W   | 1.000      | 0.303        | 0.027 (0.008)    | 0.505 (0.153)    | 0 (0.000) |    13.23 | JBa, phzy, Sonic, stanislaw, susp        |
|           65 |      383 | 2024-07-20 | Party Astronauts | W   | 1.000      | 0.303        | 0.042 (0.013)    | 0.532 (0.161)    | 0 (0.000) |    15.68 | JBa, phzy, Sonic, stanislaw, susp        |
|           64 |      460 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.23 | JBa, phzy, Sonic, stanislaw, susp        |
|           63 |      466 | 2024-07-18 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.50 | JBa, phzy, Sonic, stanislaw, susp        |
|           62 |      534 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.06 | JBa, phzy, Sonic, stanislaw, susp        |
|           61 |      537 | 2024-07-17 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.41 | JBa, phzy, Sonic, stanislaw, susp        |
|           60 |      593 | 2024-07-16 | LAG              | W   | 1.000      | 0.477        | -                | 0.371 (0.177)    | -         |    12.61 | JBa, phzy, Sonic, stanislaw, susp        |
|           59 |      599 | 2024-07-16 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -19.18 | JBa, phzy, Sonic, stanislaw, susp        |
|           58 |      887 | 2024-06-16 | Nouns            | L   | 0.895      | -            | -                | -                | -         |   -13.78 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           57 |      910 | 2024-06-15 | Mythic           | W   | 0.890      | -            | -                | -                | -         |     8.17 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           56 |      976 | 2024-06-13 | Final Form       | W   | 0.878      | -            | -                | -                | -         |     3.89 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           55 |     1089 | 2024-06-09 | M80              | L   | 0.850      | -            | -                | -                | -         |    -4.71 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1151 | 2024-06-08 | Nouns            | W   | 0.844      | 0.477        | 0.058 (0.023)    | 0.557 (0.224)    | -         |    13.63 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1158 | 2024-06-08 | Party Astronauts | L   | 0.843      | -            | -                | -                | -         |   -12.75 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1212 | 2024-06-07 | LAG              | W   | 0.837      | -            | -                | -                | -         |     8.67 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1273 | 2024-06-06 | M80              | L   | 0.830      | -            | -                | -                | -         |    -4.23 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           50 |     1284 | 2024-06-06 | NRG              | L   | 0.829      | -            | -                | -                | -         |   -15.33 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           49 |     1290 | 2024-06-06 | M80              | L   | 0.829      | -            | -                | -                | -         |    -4.73 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           48 |     1309 | 2024-06-06 | NRG              | W   | 0.828      | -            | -                | -                | -         |    10.36 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           47 |     1346 | 2024-06-05 | Party Astronauts | W   | 0.824      | 0.477        | 0.042 (0.016)    | 0.532 (0.209)    | -         |    12.46 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           46 |     1402 | 2024-06-04 | Homyno           | W   | 0.817      | -            | -                | -                | -         |     4.99 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           45 |     1695 | 2024-05-23 | M80              | L   | 0.736      | -            | -                | -                | -         |    -3.93 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           44 |     1709 | 2024-05-22 | Take Flyte       | W   | 0.731      | -            | -                | -                | -         |     3.48 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           43 |     1712 | 2024-05-22 | Take Flyte       | W   | 0.731      | -            | -                | -                | -         |     3.60 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           42 |     1723 | 2024-05-22 | LAG              | W   | 0.730      | -            | -                | -                | -         |     7.52 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           41 |     1781 | 2024-05-21 | Limitless        | W   | 0.723      | -            | -                | -                | -         |     6.58 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           40 |     1785 | 2024-05-21 | Limitless        | W   | 0.723      | -            | -                | -                | -         |     6.94 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           39 |     1852 | 2024-05-19 | Limitless        | W   | 0.710      | -            | -                | -                | -         |     3.34 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           38 |     1987 | 2024-05-15 | BOSS             | W   | 0.684      | -            | -                | -                | -         |     6.95 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           37 |     1997 | 2024-05-15 | BOSS             | W   | 0.684      | -            | -                | -                | -         |     7.33 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           36 |     2048 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.677      | -            | -                | -                | -         |     5.83 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           35 |     2053 | 2024-05-14 | FLUFFY AIMERS    | W   | 0.677      | -            | -                | -                | -         |     6.12 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           34 |     2099 | 2024-05-13 | Nouns            | W   | 0.671      | 0.477        | 0.058 (0.019)    | 0.557 (0.178)    | -         |    11.79 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           33 |     2100 | 2024-05-13 | Nouns            | L   | 0.670      | -            | -                | -                | -         |    -9.47 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           32 |     2146 | 2024-05-11 | Elevate          | L   | 0.657      | -            | -                | -                | -         |    -8.58 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           31 |     2148 | 2024-05-11 | Mythic           | L   | 0.656      | -            | -                | -                | -         |   -14.64 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           30 |     2198 | 2024-05-09 | MIGHT            | W   | 0.644      | -            | -                | -                | -         |     1.94 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           29 |     2201 | 2024-05-09 | MIGHT            | W   | 0.643      | -            | -                | -                | -         |     1.98 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           28 |     2214 | 2024-05-08 | Limitless        | W   | 0.637      | -            | -                | -                | -         |     3.24 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           27 |     2217 | 2024-05-08 | Limitless        | W   | 0.637      | -            | -                | -                | -         |     3.34 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           26 |     2333 | 2024-05-02 | Party Astronauts | W   | 0.597      | 0.477        | 0.042 (0.012)    | 0.532 (0.152)    | -         |    10.43 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           25 |     2334 | 2024-05-02 | Party Astronauts | L   | 0.597      | -            | -                | -                | -         |    -8.52 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           24 |     2501 | 2024-04-25 | NRG              | W   | 0.551      | -            | -                | -                | -         |     7.59 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           23 |     2503 | 2024-04-25 | NRG              | L   | 0.550      | -            | -                | -                | -         |   -10.00 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           22 |     2543 | 2024-04-23 | Elevate          | W   | 0.537      | 0.477        | 0.027 (0.007)    | -                | -         |    10.23 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           21 |     2545 | 2024-04-23 | Elevate          | L   | 0.537      | -            | -                | -                | -         |    -6.79 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           20 |     2745 | 2024-04-17 | Elevate          | L   | 0.496      | -            | -                | -                | -         |    -6.48 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           19 |     3274 | 2024-03-27 | Mythic           | W   | 0.357      | -            | -                | -                | -         |     3.65 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           18 |     3280 | 2024-03-27 | Mythic           | W   | 0.357      | -            | -                | -                | -         |     3.75 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           17 |     3316 | 2024-03-26 | LAG              | W   | 0.351      | -            | -                | -                | -         |     4.73 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           16 |     3321 | 2024-03-26 | LAG              | L   | 0.351      | -            | -                | -                | -         |    -6.46 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           15 |     3520 | 2024-03-14 | Perseverance     | W   | 0.270      | -            | -                | -                | -         |     2.27 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           14 |     3523 | 2024-03-14 | Perseverance     | W   | 0.270      | -            | -                | -                | -         |     2.31 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           13 |     3551 | 2024-03-13 | M80              | W   | 0.264      | 0.477        | 0.190 (0.024)    | -                | -         |     7.17 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           12 |     3552 | 2024-03-13 | M80              | L   | 0.264      | -            | -                | -                | -         |    -1.16 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           11 |     3600 | 2024-03-12 | Mythic           | L   | 0.257      | -            | -                | -                | -         |    -5.44 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           10 |     3848 | 2024-03-03 | M80              | L   | 0.194      | -            | -                | -                | -         |    -0.86 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     3860 | 2024-03-02 | BESTIA           | W   | 0.188      | -            | -                | -                | 1 (0.188) |     3.83 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     3881 | 2024-03-01 | RED Canids       | L   | 0.182      | -            | -                | -                | -         |    -2.02 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     3966 | 2024-02-25 | Liquid           | L   | 0.151      | -            | -                | -                | -         |    -0.23 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     3970 | 2024-02-25 | BOSS             | L   | 0.150      | -            | -                | -                | -         |    -3.01 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     3988 | 2024-02-24 | NRG              | W   | 0.144      | -            | -                | -                | -         |     1.89 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     3989 | 2024-02-24 | Party Astronauts | W   | 0.143      | -            | -                | -                | -         |     2.40 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     3998 | 2024-02-24 | Akimbo           | W   | 0.143      | -            | -                | -                | -         |     1.34 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     4041 | 2024-02-22 | NRG              | L   | 0.130      | -            | -                | -                | -         |    -2.39 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     4403 | 2024-02-04 | Elevate          | L   | 0.010      | -            | -                | -                | -         |    -0.12 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,095.63)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.897 | $1,500.00      | $1,345.63       |
| 2024-06-09 |      0.850 | $15,000.00     | $12,750.00      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
