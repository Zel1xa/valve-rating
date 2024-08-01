### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, micro, SLIGHT<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [31]( ../standings_americas.md)<br />
<br />
Final Rank Value:  807.7<br />
<br />
Final Rank Value (807.7) = Starting Rank Value (819.2) + Head To Head Adjustments (-11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.352[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.133[<sup>2</sup>](#table1)
- LAN Wins: 0.021[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 819.2
- 400 + ( ( 0.204 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 819.2


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
|           59 |       13 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.27 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           58 |       17 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.87 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           57 |       63 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.49 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           56 |       64 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -8.00 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           55 |      387 | 2024-07-20 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.86 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           54 |      459 | 2024-07-18 | Elevate           | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.505 (0.241)    | 0 (0.000) |    21.32 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           53 |      462 | 2024-07-18 | Elevate           | L   | 1.000      | -            | -                | -                | -         |    -9.75 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           52 |      525 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.371 (0.177)    | 0 (0.000) |    17.05 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           51 |      532 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.371 (0.177)    | 0 (0.000) |    18.59 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           50 |      646 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.304 (0.145)    | 0 (0.000) |    15.91 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           49 |      649 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.304 (0.145)    | 0 (0.000) |    17.38 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           48 |      907 | 2024-06-15 | Elevate           | L   | 0.891      | -            | -                | -                | -         |    -6.75 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           47 |      948 | 2024-06-14 | Final Form        | W   | 0.882      | -            | -                | -                | 0 (0.000) |     6.39 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           46 |     1400 | 2024-06-04 | Mythic            | L   | 0.817      | -            | -                | -                | -         |   -11.16 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           45 |     1713 | 2024-05-22 | Perseverance      | W   | 0.731      | 0.477        | -                | 0.247 (0.086)    | 0 (0.000) |    11.12 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           44 |     1717 | 2024-05-22 | Perseverance      | L   | 0.730      | -            | -                | -                | -         |   -12.12 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           43 |     1796 | 2024-05-21 | LAG               | L   | 0.722      | -            | -                | -                | -         |   -10.02 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           42 |     1814 | 2024-05-20 | Limitless         | L   | 0.717      | -            | -                | -                | -         |   -11.35 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           41 |     1818 | 2024-05-20 | Limitless         | W   | 0.717      | -            | -                | -                | 0 (0.000) |    11.44 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           40 |     1853 | 2024-05-19 | M80               | L   | 0.710      | -            | -                | -                | -         |    -1.51 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           39 |     1856 | 2024-05-19 | M80               | L   | 0.709      | -            | -                | -                | -         |    -1.54 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           38 |     1923 | 2024-05-17 | NRG               | L   | 0.696      | -            | -                | -                | -         |    -6.91 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     1987 | 2024-05-15 | Wildcard          | L   | 0.684      | -            | -                | -                | -         |    -6.95 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     1997 | 2024-05-15 | Wildcard          | L   | 0.684      | -            | -                | -                | -         |    -7.33 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     2052 | 2024-05-14 | MIGHT             | W   | 0.677      | -            | -                | -                | 0 (0.000) |     3.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     2060 | 2024-05-14 | MIGHT             | W   | 0.677      | -            | -                | -                | -         |     3.73 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     2150 | 2024-05-11 | Perseverance      | L   | 0.656      | -            | -                | -                | -         |   -12.43 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     2152 | 2024-05-11 | Party Astronauts  | W   | 0.656      | 0.270        | 0.042 (0.007)    | 0.532 (0.094)    | -         |    13.97 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     2155 | 2024-05-11 | NRG               | L   | 0.655      | -            | -                | -                | -         |    -8.48 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     2194 | 2024-05-09 | Nouns             | L   | 0.644      | -            | -                | -                | -         |    -6.50 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     2199 | 2024-05-09 | Nouns             | L   | 0.644      | -            | -                | -                | -         |    -6.83 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2317 | 2024-05-03 | Ninjas in Pyjamas | L   | 0.602      | -            | -                | -                | -         |    -0.66 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           27 |     2355 | 2024-05-02 | FlyQuest          | L   | 0.593      | -            | -                | -                | -         |    -2.15 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           26 |     2377 | 2024-05-01 | BIG               | L   | 0.587      | -            | -                | -                | -         |    -1.92 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           25 |     2525 | 2024-04-24 | Mythic            | L   | 0.544      | -            | -                | -                | -         |   -10.43 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           24 |     2526 | 2024-04-24 | Mythic            | W   | 0.544      | 0.477        | -                | 0.304 (0.079)    | -         |     6.80 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           23 |     2866 | 2024-04-11 | Limitless         | W   | 0.457      | -            | -                | -                | -         |     3.78 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           22 |     2868 | 2024-04-11 | Limitless         | W   | 0.457      | -            | -                | -                | -         |     3.90 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           21 |     2897 | 2024-04-10 | NRG               | L   | 0.451      | -            | -                | -                | -         |    -6.57 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           20 |     2901 | 2024-04-10 | NRG               | W   | 0.450      | 0.477        | 0.020 (0.004)    | 0.519 (0.111)    | -         |     7.79 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           19 |     2954 | 2024-04-09 | LAG               | W   | 0.444      | 0.477        | 0.013 (0.003)    | 0.371 (0.079)    | -         |     7.74 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           18 |     2957 | 2024-04-09 | LAG               | W   | 0.444      | 0.477        | 0.013 (0.003)    | -                | -         |     8.04 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           17 |     3086 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.410      | -            | -                | -                | -         |     5.63 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           16 |     3092 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.410      | -            | -                | -                | -         |     5.84 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           15 |     3144 | 2024-04-03 | Party Astronauts  | L   | 0.403      | -            | -                | -                | -         |   -10.56 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           14 |     3187 | 2024-04-02 | Nouns             | L   | 0.397      | -            | -                | -                | -         |    -4.24 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           13 |     3192 | 2024-04-02 | Perseverance      | W   | 0.396      | -            | -                | -                | -         |     4.95 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           12 |     3268 | 2024-03-27 | Take Flyte        | W   | 0.357      | -            | -                | -                | -         |     4.14 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           11 |     3271 | 2024-03-27 | Take Flyte        | L   | 0.357      | -            | -                | -                | -         |    -7.26 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           10 |     3317 | 2024-03-26 | Elevate           | L   | 0.351      | -            | -                | -                | -         |    -2.81 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            9 |     3322 | 2024-03-26 | Elevate           | L   | 0.351      | -            | -                | -                | -         |    -2.88 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            8 |     3402 | 2024-03-20 | Party Astronauts  | L   | 0.311      | -            | -                | -                | -         |    -3.18 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            7 |     3404 | 2024-03-20 | Party Astronauts  | L   | 0.311      | -            | -                | -                | -         |    -3.26 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            6 |     3849 | 2024-03-03 | Liquid            | L   | 0.194      | -            | -                | -                | -         |    -0.18 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            5 |     3866 | 2024-03-02 | Complexity        | L   | 0.188      | -            | -                | -                | -         |    -0.06 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            4 |     3882 | 2024-03-01 | MIBR              | W   | 0.182      | 0.143        | 0.201 (0.005)    | -                | 1 (0.182) |     5.55 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            3 |     3952 | 2024-02-26 | Liquid            | L   | 0.156      | -            | -                | -                | -         |    -0.14 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            2 |     3967 | 2024-02-25 | Nouns             | L   | 0.151      | -            | -                | -                | -         |    -1.75 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            1 |     3970 | 2024-02-25 | Wildcard          | W   | 0.150      | -            | -                | -                | -         |     3.01 | brett, Cryptic, d4rty, freshie, PwnAlone |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,685.73)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.897 | $750.00        | $672.81         |
| 2024-06-09 |      0.850 | $2,000.00      | $1,700.00       |
| 2024-05-12 |      0.661 | $3,500.00      | $2,312.92       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
