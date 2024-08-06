### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, micro, SLIGHT<br />
Global Rank: [131](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  782.9<br />
<br />
Final Rank Value (782.9) = Starting Rank Value (808.1) + Head To Head Adjustments (-25.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.122[<sup>2</sup>](#table1)
- LAN Wins: 0.017[<sup>2</sup>](#table1)

The average of these factors is 0.198<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 808.1
- 400 + ( ( 0.198 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 808.1


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
|           58 |       76 | 2024-08-03 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -7.80 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           57 |      184 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.34 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           56 |      188 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.95 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           55 |      234 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.50 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           54 |      235 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -8.01 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           53 |      555 | 2024-07-20 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.78 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           52 |      624 | 2024-07-18 | Elevate           | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.501 (0.239)    | 0 (0.000) |    21.85 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           51 |      626 | 2024-07-18 | Elevate           | L   | 1.000      | -            | -                | -                | -         |    -9.20 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           50 |      686 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | 0 (0.000) |    16.32 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           49 |      693 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | 0 (0.000) |    17.82 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           48 |      802 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.285 (0.136)    | 0 (0.000) |    16.89 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           47 |     1062 | 2024-06-15 | Elevate           | L   | 0.856      | -            | -                | -                | -         |    -6.48 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           46 |     1111 | 2024-06-14 | Final Form        | W   | 0.847      | -            | -                | -                | 0 (0.000) |     6.22 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           45 |     1548 | 2024-06-04 | Mythic            | L   | 0.782      | -            | -                | -                | -         |   -11.05 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           44 |     1858 | 2024-05-22 | Phoenix           | W   | 0.696      | 0.477        | -                | 0.270 (0.090)    | 0 (0.000) |    10.50 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           43 |     1862 | 2024-05-22 | Phoenix           | L   | 0.696      | -            | -                | -                | -         |   -11.66 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           42 |     1943 | 2024-05-20 | Limitless         | L   | 0.682      | -            | -                | -                | -         |   -10.75 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           41 |     1947 | 2024-05-20 | Limitless         | W   | 0.682      | -            | -                | -                | 0 (0.000) |    10.95 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           40 |     1978 | 2024-05-19 | M80               | L   | 0.675      | -            | -                | -                | -         |    -1.52 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           39 |     1979 | 2024-05-19 | M80               | L   | 0.675      | -            | -                | -                | -         |    -1.54 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           38 |     2042 | 2024-05-17 | NRG               | L   | 0.662      | -            | -                | -                | -         |    -6.63 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     2106 | 2024-05-15 | Wildcard          | L   | 0.649      | -            | -                | -                | -         |    -7.21 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     2116 | 2024-05-15 | Wildcard          | L   | 0.649      | -            | -                | -                | -         |    -7.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     2165 | 2024-05-14 | MIGHT             | W   | 0.642      | -            | -                | -                | 0 (0.000) |     3.49 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     2173 | 2024-05-14 | MIGHT             | W   | 0.642      | -            | -                | -                | 0 (0.000) |     3.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     2260 | 2024-05-11 | Phoenix           | L   | 0.621      | -            | -                | -                | -         |   -11.71 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     2262 | 2024-05-11 | Party Astronauts  | W   | 0.621      | 0.270        | 0.041 (0.007)    | 0.510 (0.086)    | -         |    13.14 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     2265 | 2024-05-11 | NRG               | L   | 0.621      | -            | -                | -                | -         |    -8.03 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     2304 | 2024-05-09 | Nouns             | L   | 0.609      | -            | -                | -                | -         |    -6.19 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     2309 | 2024-05-09 | Nouns             | L   | 0.609      | -            | -                | -                | -         |    -6.49 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2425 | 2024-05-03 | Ninjas in Pyjamas | L   | 0.567      | -            | -                | -                | -         |    -0.22 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           27 |     2462 | 2024-05-02 | FlyQuest          | L   | 0.559      | -            | -                | -                | -         |    -2.17 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           26 |     2483 | 2024-05-01 | BIG               | L   | 0.552      | -            | -                | -                | -         |    -1.22 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           25 |     2630 | 2024-04-24 | Mythic            | L   | 0.509      | -            | -                | -                | -         |    -9.65 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           24 |     2631 | 2024-04-24 | Mythic            | W   | 0.509      | 0.477        | 0.010 (0.002)    | 0.285 (0.069)    | -         |     6.50 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           23 |     2960 | 2024-04-11 | Limitless         | W   | 0.423      | -            | -                | -                | -         |     3.64 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           22 |     2962 | 2024-04-11 | Limitless         | W   | 0.422      | -            | -                | -                | -         |     3.75 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           21 |     2991 | 2024-04-10 | NRG               | L   | 0.416      | -            | -                | -                | -         |    -5.97 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           20 |     2995 | 2024-04-10 | NRG               | W   | 0.416      | 0.477        | 0.020 (0.004)    | 0.502 (0.100)    | -         |     7.30 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           19 |     3048 | 2024-04-09 | LAG               | W   | 0.409      | 0.477        | 0.012 (0.002)    | 0.376 (0.073)    | -         |     6.92 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           18 |     3051 | 2024-04-09 | LAG               | W   | 0.409      | 0.477        | 0.012 (0.002)    | 0.376 (0.073)    | -         |     7.17 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           17 |     3180 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.376      | -            | -                | -                | -         |     5.19 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           16 |     3186 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.375      | -            | -                | -                | -         |     5.36 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           15 |     3237 | 2024-04-03 | Party Astronauts  | L   | 0.368      | -            | -                | -                | -         |    -9.58 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           14 |     3273 | 2024-04-02 | Nouns             | L   | 0.363      | -            | -                | -                | -         |    -3.88 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           13 |     3278 | 2024-04-02 | Phoenix           | W   | 0.361      | -            | -                | -                | -         |     4.59 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           12 |     3354 | 2024-03-27 | Take Flyte        | W   | 0.323      | -            | -                | -                | -         |     3.85 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           11 |     3357 | 2024-03-27 | Take Flyte        | L   | 0.323      | -            | -                | -                | -         |    -6.44 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           10 |     3402 | 2024-03-26 | Elevate           | L   | 0.316      | -            | -                | -                | -         |    -2.50 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            9 |     3407 | 2024-03-26 | Elevate           | L   | 0.316      | -            | -                | -                | -         |    -2.55 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            8 |     3483 | 2024-03-20 | Party Astronauts  | L   | 0.276      | -            | -                | -                | -         |    -2.86 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            7 |     3485 | 2024-03-20 | Party Astronauts  | L   | 0.276      | -            | -                | -                | -         |    -2.92 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            6 |     3919 | 2024-03-03 | Liquid            | L   | 0.160      | -            | -                | -                | -         |    -0.06 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            5 |     3936 | 2024-03-02 | Complexity        | L   | 0.153      | -            | -                | -                | -         |    -0.04 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            4 |     3951 | 2024-03-01 | MIBR              | W   | 0.148      | 0.143        | 0.207 (0.004)    | -                | 1 (0.148) |     4.50 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            3 |     4020 | 2024-02-26 | Liquid            | L   | 0.122      | -            | -                | -                | -         |    -0.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            2 |     4034 | 2024-02-25 | Nouns             | L   | 0.116      | -            | -                | -                | -         |    -1.34 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            1 |     4037 | 2024-02-25 | Wildcard          | W   | 0.115      | -            | -                | -                | -         |     2.16 | brett, Cryptic, d4rty, freshie, PwnAlone |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,469.58)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.863 | $750.00        | $646.88         |
| 2024-06-09 |      0.815 | $2,000.00      | $1,630.83       |
| 2024-05-12 |      0.626 | $3,500.00      | $2,191.88       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
