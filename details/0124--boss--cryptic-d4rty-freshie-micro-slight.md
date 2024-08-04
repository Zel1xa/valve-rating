### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, micro, SLIGHT<br />
Global Rank: [124](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
<br />
Final Rank Value:  793.6<br />
<br />
Final Rank Value (793.6) = Starting Rank Value (806.4) + Head To Head Adjustments (-12.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.351[<sup>1</sup>](#table2)
- Bounty Collected: 0.305[<sup>2</sup>](#table1)
- Opponent Network: 0.121[<sup>2</sup>](#table1)
- LAN Wins: 0.019[<sup>2</sup>](#table1)

The average of these factors is 0.199<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 806.4
- 400 + ( ( 0.199 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 806.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           57 |       99 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.15 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           56 |      103 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.73 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           55 |      149 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.50 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           54 |      150 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -8.00 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           53 |      470 | 2024-07-20 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.71 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           52 |      539 | 2024-07-18 | Elevate           | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    21.82 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           51 |      541 | 2024-07-18 | Elevate           | L   | 1.000      | -            | -                | -                | -         |    -9.23 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           50 |      601 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.341 (0.163)    | 0 (0.000) |    17.09 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           49 |      608 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.341 (0.163)    | 0 (0.000) |    18.64 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           48 |      717 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.300 (0.143)    | 0 (0.000) |    17.01 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           47 |      976 | 2024-06-15 | Elevate           | L   | 0.874      | -            | -                | -                | -         |    -6.62 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           46 |     1025 | 2024-06-14 | Final Form        | W   | 0.865      | -            | -                | -                | 0 (0.000) |     6.18 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           45 |     1462 | 2024-06-04 | Mythic            | L   | 0.801      | -            | -                | -                | -         |   -11.24 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           44 |     1772 | 2024-05-22 | Perseverance      | W   | 0.714      | 0.477        | -                | 0.244 (0.083)    | 0 (0.000) |    10.79 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           43 |     1776 | 2024-05-22 | Perseverance      | L   | 0.714      | -            | -                | -                | -         |   -11.94 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           42 |     1857 | 2024-05-20 | Limitless         | L   | 0.701      | -            | -                | -                | -         |   -11.02 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           41 |     1861 | 2024-05-20 | Limitless         | W   | 0.700      | -            | -                | -                | 0 (0.000) |    11.25 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           40 |     1892 | 2024-05-19 | M80               | L   | 0.693      | -            | -                | -                | -         |    -1.54 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           39 |     1893 | 2024-05-19 | M80               | L   | 0.693      | -            | -                | -                | -         |    -1.56 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           38 |     1956 | 2024-05-17 | NRG               | L   | 0.680      | -            | -                | -                | -         |    -6.72 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     2020 | 2024-05-15 | Wildcard          | L   | 0.667      | -            | -                | -                | -         |    -6.76 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     2030 | 2024-05-15 | Wildcard          | L   | 0.667      | -            | -                | -                | -         |    -7.13 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     2079 | 2024-05-14 | MIGHT             | W   | 0.661      | -            | -                | -                | 0 (0.000) |     3.61 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     2087 | 2024-05-14 | MIGHT             | W   | 0.660      | -            | -                | -                | 0 (0.000) |     3.74 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     2174 | 2024-05-11 | Perseverance      | L   | 0.640      | -            | -                | -                | -         |   -12.02 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     2176 | 2024-05-11 | Party Astronauts  | W   | 0.639      | 0.270        | 0.041 (0.007)    | 0.532 (0.092)    | -         |    13.65 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     2179 | 2024-05-11 | NRG               | L   | 0.639      | -            | -                | -                | -         |    -8.18 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     2218 | 2024-05-09 | Nouns             | L   | 0.627      | -            | -                | -                | -         |    -6.29 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     2223 | 2024-05-09 | Nouns             | L   | 0.627      | -            | -                | -                | -         |    -6.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2339 | 2024-05-03 | Ninjas in Pyjamas | L   | 0.585      | -            | -                | -                | -         |    -0.24 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           27 |     2376 | 2024-05-02 | FlyQuest          | L   | 0.577      | -            | -                | -                | -         |    -2.16 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           26 |     2397 | 2024-05-01 | BIG               | L   | 0.570      | -            | -                | -                | -         |    -1.24 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           25 |     2543 | 2024-04-24 | Mythic            | L   | 0.528      | -            | -                | -                | -         |    -9.99 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           24 |     2544 | 2024-04-24 | Mythic            | W   | 0.527      | 0.477        | 0.010 (0.002)    | 0.300 (0.076)    | -         |     6.73 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           23 |     2873 | 2024-04-11 | Limitless         | W   | 0.441      | -            | -                | -                | -         |     3.78 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           22 |     2875 | 2024-04-11 | Limitless         | W   | 0.441      | -            | -                | -                | -         |     3.90 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           21 |     2904 | 2024-04-10 | NRG               | L   | 0.434      | -            | -                | -                | -         |    -6.21 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           20 |     2908 | 2024-04-10 | NRG               | W   | 0.434      | 0.477        | 0.020 (0.004)    | 0.521 (0.108)    | -         |     7.64 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           19 |     2961 | 2024-04-09 | LAG               | W   | 0.427      | 0.477        | 0.012 (0.003)    | 0.341 (0.070)    | -         |     7.50 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           18 |     2964 | 2024-04-09 | LAG               | W   | 0.427      | 0.477        | 0.012 (0.003)    | 0.341 (0.069)    | -         |     7.78 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           17 |     3093 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.394      | -            | -                | -                | -         |     5.49 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           16 |     3099 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.394      | -            | -                | -                | -         |     5.67 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           15 |     3150 | 2024-04-03 | Party Astronauts  | L   | 0.386      | -            | -                | -                | -         |   -10.04 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           14 |     3186 | 2024-04-02 | Nouns             | L   | 0.381      | -            | -                | -                | -         |    -4.00 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           13 |     3191 | 2024-04-02 | Perseverance      | W   | 0.380      | -            | -                | -                | -         |     4.85 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           12 |     3267 | 2024-03-27 | Take Flyte        | W   | 0.341      | -            | -                | -                | -         |     4.07 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           11 |     3270 | 2024-03-27 | Take Flyte        | L   | 0.341      | -            | -                | -                | -         |    -6.81 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           10 |     3315 | 2024-03-26 | Elevate           | L   | 0.334      | -            | -                | -                | -         |    -2.67 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            9 |     3320 | 2024-03-26 | Elevate           | L   | 0.334      | -            | -                | -                | -         |    -2.73 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            8 |     3396 | 2024-03-20 | Party Astronauts  | L   | 0.294      | -            | -                | -                | -         |    -2.98 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            7 |     3398 | 2024-03-20 | Party Astronauts  | L   | 0.294      | -            | -                | -                | -         |    -3.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            6 |     3831 | 2024-03-03 | Liquid            | L   | 0.178      | -            | -                | -                | -         |    -0.12 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            5 |     3848 | 2024-03-02 | Complexity        | L   | 0.171      | -            | -                | -                | -         |    -0.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            4 |     3863 | 2024-03-01 | MIBR              | W   | 0.166      | 0.143        | 0.210 (0.005)    | -                | 1 (0.166) |     5.07 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            3 |     3932 | 2024-02-26 | Liquid            | L   | 0.140      | -            | -                | -                | -         |    -0.09 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            2 |     3946 | 2024-02-25 | Nouns             | L   | 0.134      | -            | -                | -                | -         |    -1.53 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            1 |     3949 | 2024-02-25 | Wildcard          | W   | 0.133      | -            | -                | -                | -         |     2.71 | brett, Cryptic, d4rty, freshie, PwnAlone |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,583.30)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.881 | $750.00        | $660.52         |
| 2024-06-09 |      0.834 | $2,000.00      | $1,667.22       |
| 2024-05-12 |      0.644 | $3,500.00      | $2,255.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
