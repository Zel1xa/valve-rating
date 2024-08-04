### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, micro, SLIGHT<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  783.4<br />
<br />
Final Rank Value (783.4) = Starting Rank Value (807.8) + Head To Head Adjustments (-24.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.351[<sup>1</sup>](#table2)
- Bounty Collected: 0.305[<sup>2</sup>](#table1)
- Opponent Network: 0.124[<sup>2</sup>](#table1)
- LAN Wins: 0.018[<sup>2</sup>](#table1)

The average of these factors is 0.199<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 807.8
- 400 + ( ( 0.199 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 807.8


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
|           58 |       26 | 2024-08-03 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -7.77 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           57 |      134 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.31 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           56 |      138 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.91 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           55 |      184 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.45 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           54 |      185 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.95 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           53 |      505 | 2024-07-20 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.73 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           52 |      574 | 2024-07-18 | Elevate           | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.521 (0.248)    | 0 (0.000) |    21.88 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           51 |      576 | 2024-07-18 | Elevate           | L   | 1.000      | -            | -                | -                | -         |    -9.16 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           50 |      636 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.353 (0.168)    | 0 (0.000) |    16.37 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           49 |      643 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.353 (0.168)    | 0 (0.000) |    17.87 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           48 |      752 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.299 (0.143)    | 0 (0.000) |    16.94 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           47 |     1012 | 2024-06-15 | Elevate           | L   | 0.869      | -            | -                | -                | -         |    -6.54 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           46 |     1061 | 2024-06-14 | Final Form        | W   | 0.860      | -            | -                | -                | 0 (0.000) |     6.16 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           45 |     1498 | 2024-06-04 | Mythic            | L   | 0.796      | -            | -                | -                | -         |   -11.20 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           44 |     1808 | 2024-05-22 | Phoenix           | W   | 0.709      | 0.477        | -                | 0.283 (0.096)    | 0 (0.000) |    10.71 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           43 |     1812 | 2024-05-22 | Phoenix           | L   | 0.709      | -            | -                | -                | -         |   -11.87 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           42 |     1893 | 2024-05-20 | Limitless         | L   | 0.696      | -            | -                | -                | -         |   -10.94 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           41 |     1897 | 2024-05-20 | Limitless         | W   | 0.695      | -            | -                | -                | 0 (0.000) |    11.19 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           40 |     1928 | 2024-05-19 | M80               | L   | 0.688      | -            | -                | -                | -         |    -1.52 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           39 |     1929 | 2024-05-19 | M80               | L   | 0.688      | -            | -                | -                | -         |    -1.55 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           38 |     1992 | 2024-05-17 | NRG               | L   | 0.675      | -            | -                | -                | -         |    -6.71 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     2056 | 2024-05-15 | Wildcard          | L   | 0.663      | -            | -                | -                | -         |    -7.29 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     2066 | 2024-05-15 | Wildcard          | L   | 0.662      | -            | -                | -                | -         |    -7.70 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     2115 | 2024-05-14 | MIGHT             | W   | 0.656      | -            | -                | -                | 0 (0.000) |     3.57 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     2123 | 2024-05-14 | MIGHT             | W   | 0.655      | -            | -                | -                | 0 (0.000) |     3.69 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     2210 | 2024-05-11 | Phoenix           | L   | 0.635      | -            | -                | -                | -         |   -11.96 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     2212 | 2024-05-11 | Party Astronauts  | W   | 0.634      | 0.270        | 0.041 (0.007)    | 0.531 (0.091)    | -         |    13.46 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     2215 | 2024-05-11 | NRG               | L   | 0.634      | -            | -                | -                | -         |    -8.19 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     2254 | 2024-05-09 | Nouns             | L   | 0.623      | -            | -                | -                | -         |    -6.26 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     2259 | 2024-05-09 | Nouns             | L   | 0.622      | -            | -                | -                | -         |    -6.57 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2375 | 2024-05-03 | Ninjas in Pyjamas | L   | 0.580      | -            | -                | -                | -         |    -0.23 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           27 |     2412 | 2024-05-02 | FlyQuest          | L   | 0.572      | -            | -                | -                | -         |    -2.15 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           26 |     2433 | 2024-05-01 | BIG               | L   | 0.565      | -            | -                | -                | -         |    -1.24 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           25 |     2580 | 2024-04-24 | Mythic            | L   | 0.523      | -            | -                | -                | -         |    -9.92 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           24 |     2581 | 2024-04-24 | Mythic            | W   | 0.522      | 0.477        | 0.010 (0.002)    | 0.299 (0.075)    | -         |     6.64 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           23 |     2910 | 2024-04-11 | Limitless         | W   | 0.436      | -            | -                | -                | -         |     3.73 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           22 |     2912 | 2024-04-11 | Limitless         | W   | 0.436      | -            | -                | -                | -         |     3.85 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           21 |     2941 | 2024-04-10 | NRG               | L   | 0.429      | -            | -                | -                | -         |    -6.16 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           20 |     2945 | 2024-04-10 | NRG               | W   | 0.429      | 0.477        | 0.020 (0.004)    | 0.521 (0.107)    | -         |     7.53 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           19 |     2998 | 2024-04-09 | LAG               | W   | 0.423      | 0.477        | 0.012 (0.002)    | 0.353 (0.071)    | -         |     7.18 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           18 |     3001 | 2024-04-09 | LAG               | W   | 0.422      | 0.477        | 0.012 (0.002)    | 0.353 (0.071)    | -         |     7.45 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           17 |     3130 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.389      | -            | -                | -                | -         |     5.39 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           16 |     3136 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.389      | -            | -                | -                | -         |     5.57 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           15 |     3187 | 2024-04-03 | Party Astronauts  | L   | 0.381      | -            | -                | -                | -         |    -9.92 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           14 |     3223 | 2024-04-02 | Nouns             | L   | 0.376      | -            | -                | -                | -         |    -3.97 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           13 |     3228 | 2024-04-02 | Phoenix           | W   | 0.375      | -            | -                | -                | -         |     4.76 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           12 |     3304 | 2024-03-27 | Take Flyte        | W   | 0.336      | -            | -                | -                | -         |     4.01 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           11 |     3307 | 2024-03-27 | Take Flyte        | L   | 0.336      | -            | -                | -                | -         |    -6.71 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           10 |     3352 | 2024-03-26 | Elevate           | L   | 0.330      | -            | -                | -                | -         |    -2.59 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            9 |     3357 | 2024-03-26 | Elevate           | L   | 0.329      | -            | -                | -                | -         |    -2.65 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            8 |     3433 | 2024-03-20 | Party Astronauts  | L   | 0.290      | -            | -                | -                | -         |    -2.97 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            7 |     3435 | 2024-03-20 | Party Astronauts  | L   | 0.289      | -            | -                | -                | -         |    -3.04 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            6 |     3869 | 2024-03-03 | Liquid            | L   | 0.173      | -            | -                | -                | -         |    -0.07 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            5 |     3886 | 2024-03-02 | Complexity        | L   | 0.167      | -            | -                | -                | -         |    -0.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            4 |     3901 | 2024-03-01 | MIBR              | W   | 0.161      | 0.143        | 0.209 (0.005)    | -                | 1 (0.161) |     4.91 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            3 |     3970 | 2024-02-26 | Liquid            | L   | 0.135      | -            | -                | -                | -         |    -0.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            2 |     3984 | 2024-02-25 | Nouns             | L   | 0.129      | -            | -                | -                | -         |    -1.48 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            1 |     3987 | 2024-02-25 | Wildcard          | W   | 0.128      | -            | -                | -                | -         |     2.42 | brett, Cryptic, d4rty, freshie, PwnAlone |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,553.06)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.876 | $750.00        | $656.89         |
| 2024-06-09 |      0.829 | $2,000.00      | $1,657.55       |
| 2024-05-12 |      0.640 | $3,500.00      | $2,238.62       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
