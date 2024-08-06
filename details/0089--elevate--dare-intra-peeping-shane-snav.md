### Roster Details<br />
Team Name: Elevate<br />
Roster: dare, intra, Peeping, shane, snav<br />
Global Rank: [89](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [23]( ../standings_americas.md)<br />
<br />
Final Rank Value:  907.3<br />
<br />
Final Rank Value (907.3) = Starting Rank Value (1002.0) + Head To Head Adjustments (-94.6)<br />

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
|           69 |       58 | 2024-08-03 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.510 (0.155)    | 0 (0.000) |    19.14 | dare, intra, Peeping, shane, snav   |
|           68 |      169 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -13.79 | dare, dea, Peeping, shane, snav     |
|           67 |      175 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.06 | dare, dea, Peeping, shane, snav     |
|           66 |      414 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -12.34 | dare, dea, Peeping, shane, snav     |
|           65 |      417 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -13.44 | dare, dea, Peeping, shane, snav     |
|           64 |      510 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -18.54 | dare, Fr3nk1e, Peeping, shane, snav |
|           63 |      538 | 2024-07-20 | Phoenix          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.54 | dare, Fr3nk1e, Peeping, shane, snav |
|           62 |      608 | 2024-07-18 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -21.85 | dare, Fr3nk1e, Peeping, shane, snav |
|           61 |      610 | 2024-07-18 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.319 (0.152)    | 0 (0.000) |     9.20 | dare, Fr3nk1e, Peeping, shane, snav |
|           60 |      672 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.270 (0.129)    | 0 (0.000) |     5.50 | dare, Fr3nk1e, Peeping, shane, snav |
|           59 |      676 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.270 (0.129)    | 0 (0.000) |     5.79 | dare, Fr3nk1e, Peeping, shane, snav |
|           58 |      734 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.285 (0.136)    | 0 (0.000) |     8.70 | dare, Fr3nk1e, Peeping, shane, snav |
|           57 |      741 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.285 (0.136)    | 0 (0.000) |     9.35 | dare, Fr3nk1e, Peeping, shane, snav |
|           56 |      785 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -20.24 | dare, dea, Peeping, shane, snav     |
|           55 |      789 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -21.89 | dare, dea, Peeping, shane, snav     |
|           54 |     1000 | 2024-06-23 | Locke's Kittens  | W   | 0.910      | -            | -                | -                | 1 (0.910) |     6.82 | dare, dea, Peeping, shane, snav     |
|           53 |     1002 | 2024-06-23 | WICKED           | W   | 0.909      | -            | -                | -                | 1 (0.909) |     3.02 | dare, dea, Peeping, shane, snav     |
|           52 |     1006 | 2024-06-22 | LOCK IN          | W   | 0.903      | -            | -                | -                | 1 (0.903) |     1.11 | dare, dea, Peeping, shane, snav     |
|           51 |     1023 | 2024-06-16 | Legacy           | L   | 0.863      | -            | -                | -                | -         |   -11.24 | dare, dea, Peeping, shane, snav     |
|           50 |     1046 | 2024-06-15 | BOSS             | W   | 0.857      | -            | -                | -                | -         |     6.49 | dare, dea, Peeping, shane, snav     |
|           49 |     1081 | 2024-06-14 | FLUFFY AIMERS    | W   | 0.850      | -            | -                | -                | -         |     4.85 | dare, dea, Peeping, shane, snav     |
|           48 |     1359 | 2024-06-07 | Nouns            | L   | 0.802      | -            | -                | -                | -         |   -12.85 | dare, dea, Peeping, shane, snav     |
|           47 |     1362 | 2024-06-07 | Nouns            | W   | 0.802      | 0.143        | 0.057 (0.007)    | -                | -         |    12.59 | dare, dea, Peeping, shane, snav     |
|           46 |     1367 | 2024-06-07 | Legacy           | L   | 0.801      | -            | -                | -                | -         |   -11.11 | dare, dea, Peeping, shane, snav     |
|           45 |     1408 | 2024-06-06 | Nouns            | L   | 0.797      | -            | -                | -                | -         |   -12.69 | dare, dea, Peeping, shane, snav     |
|           44 |     1418 | 2024-06-06 | FlyQuest RED     | W   | 0.796      | 0.384        | 0.017 (0.005)    | -                | -         |     5.22 | dare, dea, Peeping, shane, snav     |
|           43 |     1479 | 2024-06-05 | Mythic           | W   | 0.790      | 0.477        | -                | 0.285 (0.107)    | -         |     6.98 | dare, dea, Peeping, shane, snav     |
|           42 |     1531 | 2024-06-04 | Party Astronauts | L   | 0.783      | -            | -                | -                | -         |   -13.76 | dare, dea, Peeping, shane, snav     |
|           41 |     1839 | 2024-05-22 | NRG              | W   | 0.697      | 0.477        | 0.020 (0.007)    | 0.502 (0.167)    | -         |     8.66 | dare, dea, Peeping, shane, snav     |
|           40 |     1845 | 2024-05-22 | NRG              | W   | 0.697      | 0.477        | 0.020 (0.007)    | 0.502 (0.167)    | -         |     9.20 | dare, dea, Peeping, shane, snav     |
|           39 |     1888 | 2024-05-21 | Take Flyte       | W   | 0.690      | -            | -                | -                | -         |     3.31 | dare, dea, Peeping, shane, snav     |
|           38 |     1892 | 2024-05-21 | Take Flyte       | W   | 0.690      | -            | -                | -                | -         |     3.41 | dare, dea, Peeping, shane, snav     |
|           37 |     1933 | 2024-05-20 | Mythic           | L   | 0.683      | -            | -                | -                | -         |   -16.05 | dare, dea, Peeping, shane, snav     |
|           36 |     2019 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.664      | -            | -                | -                | -         |     4.01 | dare, dea, Peeping, shane, snav     |
|           35 |     2020 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.663      | -            | -                | -                | -         |     4.16 | dare, dea, Peeping, shane, snav     |
|           34 |     2091 | 2024-05-15 | Limitless        | W   | 0.650      | -            | -                | -                | -         |     2.60 | dare, dea, Peeping, shane, snav     |
|           33 |     2098 | 2024-05-15 | Limitless        | W   | 0.650      | -            | -                | -                | -         |     2.67 | dare, dea, Peeping, shane, snav     |
|           32 |     2144 | 2024-05-14 | M80              | L   | 0.644      | -            | -                | -                | -         |    -3.58 | dare, dea, Peeping, shane, snav     |
|           31 |     2151 | 2024-05-14 | M80              | L   | 0.643      | -            | -                | -                | -         |    -3.70 | dare, dea, Peeping, shane, snav     |
|           30 |     2160 | 2024-05-14 | Phoenix          | W   | 0.643      | -            | -                | -                | -         |     4.27 | dare, dea, Peeping, shane, snav     |
|           29 |     2163 | 2024-05-14 | Phoenix          | W   | 0.643      | -            | -                | -                | -         |     4.44 | dare, dea, Peeping, shane, snav     |
|           28 |     2219 | 2024-05-12 | NRG              | L   | 0.629      | -            | -                | -                | -         |   -12.57 | dare, dea, intra, Peeping, snav     |
|           27 |     2239 | 2024-05-11 | Nouns            | W   | 0.623      | 0.270        | 0.057 (0.010)    | -                | -         |     8.74 | dare, dea, intra, Peeping, snav     |
|           26 |     2240 | 2024-05-11 | Wildcard         | W   | 0.623      | 0.270        | 0.048 (0.008)    | -                | -         |     7.45 | dare, dea, intra, Peeping, snav     |
|           25 |     2243 | 2024-05-11 | Nouns            | L   | 0.623      | -            | -                | -                | -         |   -10.53 | dare, dea, intra, Peeping, snav     |
|           24 |     2310 | 2024-05-08 | MIGHT            | W   | 0.604      | -            | -                | -                | -         |     1.45 | dare, dea, Peeping, shane, snav     |
|           23 |     2312 | 2024-05-08 | MIGHT            | W   | 0.603      | -            | -                | -                | -         |     1.47 | dare, dea, Peeping, shane, snav     |
|           22 |     2334 | 2024-05-07 | Party Astronauts | W   | 0.597      | 0.477        | 0.041 (0.012)    | 0.510 (0.145)    | -         |     8.61 | dare, dea, Peeping, shane, snav     |
|           21 |     2335 | 2024-05-07 | Party Astronauts | L   | 0.597      | -            | -                | -                | -         |   -10.44 | dare, dea, Peeping, shane, snav     |
|           20 |     2632 | 2024-04-23 | Wildcard         | L   | 0.504      | -            | -                | -                | -         |   -10.28 | dare, dea, Peeping, shane, snav     |
|           19 |     2634 | 2024-04-23 | Wildcard         | W   | 0.503      | 0.477        | 0.048 (0.011)    | -                | -         |     5.65 | dare, dea, Peeping, shane, snav     |
|           18 |     2771 | 2024-04-18 | Legacy           | L   | 0.470      | -            | -                | -                | -         |    -6.78 | dare, dea, Peeping, shane, snav     |
|           17 |     2776 | 2024-04-18 | M80              | L   | 0.469      | -            | -                | -                | -         |    -3.29 | dare, dea, Peeping, shane, snav     |
|           16 |     2821 | 2024-04-17 | Nouns            | W   | 0.463      | -            | -                | -                | -         |     6.28 | dare, dea, Peeping, shane, snav     |
|           15 |     2826 | 2024-04-17 | Wildcard         | W   | 0.462      | -            | -                | -                | -         |     5.33 | dare, dea, Peeping, shane, snav     |
|           14 |     2974 | 2024-04-10 | Nouns            | L   | 0.417      | -            | -                | -                | -         |    -7.70 | dare, dea, Peeping, shane, snav     |
|           13 |     2980 | 2024-04-10 | Nouns            | L   | 0.417      | -            | -                | -                | -         |    -7.97 | dare, dea, Peeping, shane, snav     |
|           12 |     3209 | 2024-04-03 | LAG              | W   | 0.370      | -            | -                | -                | -         |     3.54 | dare, dea, Peeping, shane, snav     |
|           11 |     3211 | 2024-04-03 | LAG              | L   | 0.370      | -            | -                | -                | -         |    -8.29 | dare, dea, Peeping, shane, snav     |
|           10 |     3386 | 2024-03-26 | BOSS             | W   | 0.317      | -            | -                | -                | -         |     2.51 | dare, dea, Peeping, shane, snav     |
|            9 |     3391 | 2024-03-26 | BOSS             | W   | 0.317      | -            | -                | -                | -         |     2.56 | dare, dea, Peeping, shane, snav     |
|            8 |     3558 | 2024-03-15 | Carpe Diem       | W   | 0.244      | -            | -                | -                | -         |     1.13 | dare, dea, Peeping, shane, snav     |
|            7 |     3560 | 2024-03-15 | Carpe Diem       | W   | 0.244      | -            | -                | -                | -         |     1.14 | dare, dea, Peeping, shane, snav     |
|            6 |     3659 | 2024-03-12 | Party Astronauts | L   | 0.223      | -            | -                | -                | -         |    -4.23 | dare, dea, Peeping, shane, snav     |
|            5 |     3759 | 2024-03-08 | Spirit           | L   | 0.194      | -            | -                | -                | -         |    -0.04 | dare, MRC9, Peeping, shane, snav    |
|            4 |     3911 | 2024-03-02 | ODDIK            | L   | 0.155      | -            | -                | -                | -         |    -2.50 | dare, nbgee12, Peeping, shane, snav |
|            3 |     3939 | 2024-03-01 | Complexity       | L   | 0.148      | -            | -                | -                | -         |    -0.12 | dare, nbgee12, Peeping, shane, snav |
|            2 |     4328 | 2024-02-13 | Mythic           | L   | 0.037      | -            | -                | -                | -         |    -0.90 | dare, dea, Peeping, shane, snav     |
|            1 |     4331 | 2024-02-13 | Mythic           | W   | 0.037      | -            | -                | -                | -         |     0.27 | dare, dea, Peeping, shane, snav     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,536.85)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-23 |      0.910 | $3,000.00      | $2,730.97       |
| 2024-06-16 |      0.863 | $1,500.00      | $1,295.07       |
| 2024-06-09 |      0.816 | $4,250.00      | $3,469.26       |
| 2024-03-10 |      0.208 | $5,000.00      | $1,041.55       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
