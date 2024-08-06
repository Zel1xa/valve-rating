### Roster Details<br />
Team Name: Elevate<br />
Roster: dare, intra, Peeping, shane, snav<br />
Global Rank: [91](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [23]( ../standings_americas.md)<br />
<br />
Final Rank Value:  907.4<br />
<br />
Final Rank Value (907.4) = Starting Rank Value (1002.0) + Head To Head Adjustments (-94.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.142[<sup>2</sup>](#table1)
- LAN Wins: 0.314[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1002.0
- 400 + ( ( 0.293 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1002.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           69 |       61 | 2024-08-03 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.510 (0.155)    | 0 (0.000) |    19.14 | dare, intra, Peeping, shane, snav   |
|           68 |      174 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -13.79 | dare, dea, Peeping, shane, snav     |
|           67 |      180 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.06 | dare, dea, Peeping, shane, snav     |
|           66 |      419 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -12.34 | dare, dea, Peeping, shane, snav     |
|           65 |      422 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -13.44 | dare, dea, Peeping, shane, snav     |
|           64 |      515 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -18.54 | dare, Fr3nk1e, Peeping, shane, snav |
|           63 |      543 | 2024-07-20 | Phoenix          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.54 | dare, Fr3nk1e, Peeping, shane, snav |
|           62 |      613 | 2024-07-18 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -21.85 | dare, Fr3nk1e, Peeping, shane, snav |
|           61 |      615 | 2024-07-18 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.319 (0.152)    | 0 (0.000) |     9.20 | dare, Fr3nk1e, Peeping, shane, snav |
|           60 |      677 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.270 (0.129)    | 0 (0.000) |     5.50 | dare, Fr3nk1e, Peeping, shane, snav |
|           59 |      681 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.270 (0.129)    | 0 (0.000) |     5.79 | dare, Fr3nk1e, Peeping, shane, snav |
|           58 |      739 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.285 (0.136)    | 0 (0.000) |     8.70 | dare, Fr3nk1e, Peeping, shane, snav |
|           57 |      746 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.285 (0.136)    | 0 (0.000) |     9.35 | dare, Fr3nk1e, Peeping, shane, snav |
|           56 |      790 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -20.24 | dare, dea, Peeping, shane, snav     |
|           55 |      794 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -21.89 | dare, dea, Peeping, shane, snav     |
|           54 |     1005 | 2024-06-23 | Locke's Kittens  | W   | 0.911      | -            | -                | -                | 1 (0.911) |     6.83 | dare, dea, Peeping, shane, snav     |
|           53 |     1007 | 2024-06-23 | WICKED           | W   | 0.909      | -            | -                | -                | 1 (0.909) |     3.03 | dare, dea, Peeping, shane, snav     |
|           52 |     1011 | 2024-06-22 | LOCK IN          | W   | 0.903      | -            | -                | -                | 1 (0.903) |     1.11 | dare, dea, Peeping, shane, snav     |
|           51 |     1028 | 2024-06-16 | Legacy           | L   | 0.863      | -            | -                | -                | -         |   -11.25 | dare, dea, Peeping, shane, snav     |
|           50 |     1051 | 2024-06-15 | BOSS             | W   | 0.857      | -            | -                | -                | -         |     6.49 | dare, dea, Peeping, shane, snav     |
|           49 |     1086 | 2024-06-14 | FLUFFY AIMERS    | W   | 0.851      | -            | -                | -                | -         |     4.85 | dare, dea, Peeping, shane, snav     |
|           48 |     1364 | 2024-06-07 | Nouns            | L   | 0.803      | -            | -                | -                | -         |   -12.85 | dare, dea, Peeping, shane, snav     |
|           47 |     1367 | 2024-06-07 | Nouns            | W   | 0.802      | 0.143        | 0.057 (0.007)    | -                | -         |    12.59 | dare, dea, Peeping, shane, snav     |
|           46 |     1372 | 2024-06-07 | Legacy           | L   | 0.802      | -            | -                | -                | -         |   -11.11 | dare, dea, Peeping, shane, snav     |
|           45 |     1413 | 2024-06-06 | Nouns            | L   | 0.797      | -            | -                | -                | -         |   -12.70 | dare, dea, Peeping, shane, snav     |
|           44 |     1423 | 2024-06-06 | FlyQuest RED     | W   | 0.796      | 0.384        | 0.017 (0.005)    | -                | -         |     5.22 | dare, dea, Peeping, shane, snav     |
|           43 |     1484 | 2024-06-05 | Mythic           | W   | 0.790      | 0.477        | -                | 0.285 (0.107)    | -         |     6.99 | dare, dea, Peeping, shane, snav     |
|           42 |     1536 | 2024-06-04 | Party Astronauts | L   | 0.784      | -            | -                | -                | -         |   -13.77 | dare, dea, Peeping, shane, snav     |
|           41 |     1844 | 2024-05-22 | NRG              | W   | 0.697      | 0.477        | 0.020 (0.007)    | 0.502 (0.167)    | -         |     8.67 | dare, dea, Peeping, shane, snav     |
|           40 |     1850 | 2024-05-22 | NRG              | W   | 0.697      | 0.477        | 0.020 (0.007)    | 0.502 (0.167)    | -         |     9.20 | dare, dea, Peeping, shane, snav     |
|           39 |     1893 | 2024-05-21 | Take Flyte       | W   | 0.690      | -            | -                | -                | -         |     3.31 | dare, dea, Peeping, shane, snav     |
|           38 |     1897 | 2024-05-21 | Take Flyte       | W   | 0.690      | -            | -                | -                | -         |     3.41 | dare, dea, Peeping, shane, snav     |
|           37 |     1938 | 2024-05-20 | Mythic           | L   | 0.683      | -            | -                | -                | -         |   -16.06 | dare, dea, Peeping, shane, snav     |
|           36 |     2024 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.664      | -            | -                | -                | -         |     4.01 | dare, dea, Peeping, shane, snav     |
|           35 |     2025 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.664      | -            | -                | -                | -         |     4.16 | dare, dea, Peeping, shane, snav     |
|           34 |     2096 | 2024-05-15 | Limitless        | W   | 0.650      | -            | -                | -                | -         |     2.60 | dare, dea, Peeping, shane, snav     |
|           33 |     2103 | 2024-05-15 | Limitless        | W   | 0.650      | -            | -                | -                | -         |     2.67 | dare, dea, Peeping, shane, snav     |
|           32 |     2149 | 2024-05-14 | M80              | L   | 0.644      | -            | -                | -                | -         |    -3.58 | dare, dea, Peeping, shane, snav     |
|           31 |     2156 | 2024-05-14 | M80              | L   | 0.644      | -            | -                | -                | -         |    -3.70 | dare, dea, Peeping, shane, snav     |
|           30 |     2165 | 2024-05-14 | Phoenix          | W   | 0.643      | -            | -                | -                | -         |     4.27 | dare, dea, Peeping, shane, snav     |
|           29 |     2168 | 2024-05-14 | Phoenix          | W   | 0.643      | -            | -                | -                | -         |     4.44 | dare, dea, Peeping, shane, snav     |
|           28 |     2224 | 2024-05-12 | NRG              | L   | 0.629      | -            | -                | -                | -         |   -12.58 | dare, dea, intra, Peeping, snav     |
|           27 |     2244 | 2024-05-11 | Nouns            | W   | 0.623      | 0.270        | 0.057 (0.010)    | -                | -         |     8.75 | dare, dea, intra, Peeping, snav     |
|           26 |     2245 | 2024-05-11 | Wildcard         | W   | 0.623      | 0.270        | 0.048 (0.008)    | -                | -         |     7.45 | dare, dea, intra, Peeping, snav     |
|           25 |     2248 | 2024-05-11 | Nouns            | L   | 0.623      | -            | -                | -                | -         |   -10.54 | dare, dea, intra, Peeping, snav     |
|           24 |     2315 | 2024-05-08 | MIGHT            | W   | 0.604      | -            | -                | -                | -         |     1.45 | dare, dea, Peeping, shane, snav     |
|           23 |     2317 | 2024-05-08 | MIGHT            | W   | 0.604      | -            | -                | -                | -         |     1.47 | dare, dea, Peeping, shane, snav     |
|           22 |     2339 | 2024-05-07 | Party Astronauts | W   | 0.597      | 0.477        | 0.041 (0.012)    | 0.510 (0.145)    | -         |     8.62 | dare, dea, Peeping, shane, snav     |
|           21 |     2340 | 2024-05-07 | Party Astronauts | L   | 0.597      | -            | -                | -                | -         |   -10.44 | dare, dea, Peeping, shane, snav     |
|           20 |     2637 | 2024-04-23 | Wildcard         | L   | 0.504      | -            | -                | -                | -         |   -10.28 | dare, dea, Peeping, shane, snav     |
|           19 |     2639 | 2024-04-23 | Wildcard         | W   | 0.504      | 0.477        | 0.048 (0.011)    | -                | -         |     5.65 | dare, dea, Peeping, shane, snav     |
|           18 |     2776 | 2024-04-18 | Legacy           | L   | 0.470      | -            | -                | -                | -         |    -6.78 | dare, dea, Peeping, shane, snav     |
|           17 |     2781 | 2024-04-18 | M80              | L   | 0.469      | -            | -                | -                | -         |    -3.29 | dare, dea, Peeping, shane, snav     |
|           16 |     2826 | 2024-04-17 | Nouns            | W   | 0.463      | -            | -                | -                | -         |     6.28 | dare, dea, Peeping, shane, snav     |
|           15 |     2831 | 2024-04-17 | Wildcard         | W   | 0.463      | -            | -                | -                | -         |     5.33 | dare, dea, Peeping, shane, snav     |
|           14 |     2979 | 2024-04-10 | Nouns            | L   | 0.417      | -            | -                | -                | -         |    -7.70 | dare, dea, Peeping, shane, snav     |
|           13 |     2985 | 2024-04-10 | Nouns            | L   | 0.417      | -            | -                | -                | -         |    -7.98 | dare, dea, Peeping, shane, snav     |
|           12 |     3214 | 2024-04-03 | LAG              | W   | 0.370      | -            | -                | -                | -         |     3.54 | dare, dea, Peeping, shane, snav     |
|           11 |     3216 | 2024-04-03 | LAG              | L   | 0.370      | -            | -                | -                | -         |    -8.29 | dare, dea, Peeping, shane, snav     |
|           10 |     3391 | 2024-03-26 | BOSS             | W   | 0.317      | -            | -                | -                | -         |     2.51 | dare, dea, Peeping, shane, snav     |
|            9 |     3396 | 2024-03-26 | BOSS             | W   | 0.317      | -            | -                | -                | -         |     2.56 | dare, dea, Peeping, shane, snav     |
|            8 |     3563 | 2024-03-15 | Carpe Diem       | W   | 0.244      | -            | -                | -                | -         |     1.13 | dare, dea, Peeping, shane, snav     |
|            7 |     3565 | 2024-03-15 | Carpe Diem       | W   | 0.244      | -            | -                | -                | -         |     1.15 | dare, dea, Peeping, shane, snav     |
|            6 |     3664 | 2024-03-12 | Party Astronauts | L   | 0.224      | -            | -                | -                | -         |    -4.24 | dare, dea, Peeping, shane, snav     |
|            5 |     3764 | 2024-03-08 | Spirit           | L   | 0.194      | -            | -                | -                | -         |    -0.04 | dare, MRC9, Peeping, shane, snav    |
|            4 |     3916 | 2024-03-02 | ODDIK            | L   | 0.155      | -            | -                | -                | -         |    -2.51 | dare, nbgee12, Peeping, shane, snav |
|            3 |     3944 | 2024-03-01 | Complexity       | L   | 0.149      | -            | -                | -                | -         |    -0.12 | dare, nbgee12, Peeping, shane, snav |
|            2 |     4333 | 2024-02-13 | Mythic           | L   | 0.038      | -            | -                | -                | -         |    -0.91 | dare, dea, Peeping, shane, snav     |
|            1 |     4336 | 2024-02-13 | Mythic           | W   | 0.037      | -            | -                | -                | -         |     0.27 | dare, dea, Peeping, shane, snav     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,540.67)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-23 |      0.911 | $3,000.00      | $2,731.81       |
| 2024-06-16 |      0.864 | $1,500.00      | $1,295.49       |
| 2024-06-09 |      0.817 | $4,250.00      | $3,470.44       |
| 2024-03-10 |      0.209 | $5,000.00      | $1,042.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
