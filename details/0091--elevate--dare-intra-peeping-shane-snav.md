### Roster Details<br />
Team Name: Elevate<br />
Roster: dare, intra, Peeping, shane, snav<br />
Global Rank: [91](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [23]( ../standings_americas.md)<br />
<br />
Final Rank Value:  907.3<br />
<br />
Final Rank Value (907.3) = Starting Rank Value (1001.9) + Head To Head Adjustments (-94.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.142[<sup>2</sup>](#table1)
- LAN Wins: 0.314[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1001.9
- 400 + ( ( 0.293 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1001.9


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
|           69 |       71 | 2024-08-03 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.510 (0.155)    | 0 (0.000) |    19.13 | dare, intra, Peeping, shane, snav   |
|           68 |      184 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -13.79 | dare, dea, Peeping, shane, snav     |
|           67 |      190 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.05 | dare, dea, Peeping, shane, snav     |
|           66 |      429 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -12.35 | dare, dea, Peeping, shane, snav     |
|           65 |      432 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -13.45 | dare, dea, Peeping, shane, snav     |
|           64 |      525 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -18.53 | dare, Fr3nk1e, Peeping, shane, snav |
|           63 |      553 | 2024-07-20 | Phoenix          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.54 | dare, Fr3nk1e, Peeping, shane, snav |
|           62 |      623 | 2024-07-18 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -21.85 | dare, Fr3nk1e, Peeping, shane, snav |
|           61 |      625 | 2024-07-18 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.319 (0.152)    | 0 (0.000) |     9.20 | dare, Fr3nk1e, Peeping, shane, snav |
|           60 |      687 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.270 (0.129)    | 0 (0.000) |     5.50 | dare, Fr3nk1e, Peeping, shane, snav |
|           59 |      691 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.270 (0.129)    | 0 (0.000) |     5.79 | dare, Fr3nk1e, Peeping, shane, snav |
|           58 |      749 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.285 (0.136)    | 0 (0.000) |     8.70 | dare, Fr3nk1e, Peeping, shane, snav |
|           57 |      756 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.285 (0.136)    | 0 (0.000) |     9.35 | dare, Fr3nk1e, Peeping, shane, snav |
|           56 |      800 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -20.24 | dare, dea, Peeping, shane, snav     |
|           55 |      804 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -21.89 | dare, dea, Peeping, shane, snav     |
|           54 |     1015 | 2024-06-23 | Locke's Kittens  | W   | 0.910      | -            | -                | -                | 1 (0.910) |     6.82 | dare, dea, Peeping, shane, snav     |
|           53 |     1017 | 2024-06-23 | WICKED           | W   | 0.908      | -            | -                | -                | 1 (0.908) |     3.02 | dare, dea, Peeping, shane, snav     |
|           52 |     1021 | 2024-06-22 | LOCK IN          | W   | 0.902      | -            | -                | -                | 1 (0.902) |     1.11 | dare, dea, Peeping, shane, snav     |
|           51 |     1038 | 2024-06-16 | Legacy           | L   | 0.862      | -            | -                | -                | -         |   -11.24 | dare, dea, Peeping, shane, snav     |
|           50 |     1061 | 2024-06-15 | BOSS             | W   | 0.856      | -            | -                | -                | -         |     6.48 | dare, dea, Peeping, shane, snav     |
|           49 |     1096 | 2024-06-14 | FLUFFY AIMERS    | W   | 0.850      | -            | -                | -                | -         |     4.85 | dare, dea, Peeping, shane, snav     |
|           48 |     1374 | 2024-06-07 | Nouns            | L   | 0.802      | -            | -                | -                | -         |   -12.84 | dare, dea, Peeping, shane, snav     |
|           47 |     1377 | 2024-06-07 | Nouns            | W   | 0.801      | 0.143        | 0.057 (0.007)    | -                | -         |    12.57 | dare, dea, Peeping, shane, snav     |
|           46 |     1382 | 2024-06-07 | Legacy           | L   | 0.801      | -            | -                | -                | -         |   -11.10 | dare, dea, Peeping, shane, snav     |
|           45 |     1423 | 2024-06-06 | Nouns            | L   | 0.796      | -            | -                | -                | -         |   -12.69 | dare, dea, Peeping, shane, snav     |
|           44 |     1433 | 2024-06-06 | FlyQuest RED     | W   | 0.795      | 0.384        | 0.017 (0.005)    | -                | -         |     5.21 | dare, dea, Peeping, shane, snav     |
|           43 |     1494 | 2024-06-05 | Mythic           | W   | 0.789      | 0.477        | -                | 0.285 (0.107)    | -         |     6.97 | dare, dea, Peeping, shane, snav     |
|           42 |     1546 | 2024-06-04 | Party Astronauts | L   | 0.782      | -            | -                | -                | -         |   -13.75 | dare, dea, Peeping, shane, snav     |
|           41 |     1854 | 2024-05-22 | NRG              | W   | 0.696      | 0.477        | 0.020 (0.007)    | 0.502 (0.167)    | -         |     8.65 | dare, dea, Peeping, shane, snav     |
|           40 |     1860 | 2024-05-22 | NRG              | W   | 0.696      | 0.477        | 0.020 (0.007)    | 0.502 (0.167)    | -         |     9.19 | dare, dea, Peeping, shane, snav     |
|           39 |     1903 | 2024-05-21 | Take Flyte       | W   | 0.689      | -            | -                | -                | -         |     3.30 | dare, dea, Peeping, shane, snav     |
|           38 |     1907 | 2024-05-21 | Take Flyte       | W   | 0.689      | -            | -                | -                | -         |     3.41 | dare, dea, Peeping, shane, snav     |
|           37 |     1948 | 2024-05-20 | Mythic           | L   | 0.682      | -            | -                | -                | -         |   -16.04 | dare, dea, Peeping, shane, snav     |
|           36 |     2034 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.663      | -            | -                | -                | -         |     4.00 | dare, dea, Peeping, shane, snav     |
|           35 |     2035 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.662      | -            | -                | -                | -         |     4.15 | dare, dea, Peeping, shane, snav     |
|           34 |     2106 | 2024-05-15 | Limitless        | W   | 0.649      | -            | -                | -                | -         |     2.60 | dare, dea, Peeping, shane, snav     |
|           33 |     2113 | 2024-05-15 | Limitless        | W   | 0.649      | -            | -                | -                | -         |     2.66 | dare, dea, Peeping, shane, snav     |
|           32 |     2159 | 2024-05-14 | M80              | L   | 0.643      | -            | -                | -                | -         |    -3.57 | dare, dea, Peeping, shane, snav     |
|           31 |     2166 | 2024-05-14 | M80              | L   | 0.642      | -            | -                | -                | -         |    -3.69 | dare, dea, Peeping, shane, snav     |
|           30 |     2175 | 2024-05-14 | Phoenix          | W   | 0.642      | -            | -                | -                | -         |     4.26 | dare, dea, Peeping, shane, snav     |
|           29 |     2178 | 2024-05-14 | Phoenix          | W   | 0.642      | -            | -                | -                | -         |     4.43 | dare, dea, Peeping, shane, snav     |
|           28 |     2234 | 2024-05-12 | NRG              | L   | 0.628      | -            | -                | -                | -         |   -12.56 | dare, dea, intra, Peeping, snav     |
|           27 |     2254 | 2024-05-11 | Nouns            | W   | 0.622      | 0.270        | 0.057 (0.010)    | -                | -         |     8.73 | dare, dea, intra, Peeping, snav     |
|           26 |     2255 | 2024-05-11 | Wildcard         | W   | 0.622      | 0.270        | 0.048 (0.008)    | -                | -         |     7.43 | dare, dea, intra, Peeping, snav     |
|           25 |     2258 | 2024-05-11 | Nouns            | L   | 0.622      | -            | -                | -                | -         |   -10.52 | dare, dea, intra, Peeping, snav     |
|           24 |     2325 | 2024-05-08 | MIGHT            | W   | 0.603      | -            | -                | -                | -         |     1.45 | dare, dea, Peeping, shane, snav     |
|           23 |     2327 | 2024-05-08 | MIGHT            | W   | 0.603      | -            | -                | -                | -         |     1.47 | dare, dea, Peeping, shane, snav     |
|           22 |     2349 | 2024-05-07 | Party Astronauts | W   | 0.596      | 0.477        | 0.041 (0.012)    | 0.510 (0.145)    | -         |     8.60 | dare, dea, Peeping, shane, snav     |
|           21 |     2350 | 2024-05-07 | Party Astronauts | L   | 0.596      | -            | -                | -                | -         |   -10.43 | dare, dea, Peeping, shane, snav     |
|           20 |     2647 | 2024-04-23 | Wildcard         | L   | 0.503      | -            | -                | -                | -         |   -10.26 | dare, dea, Peeping, shane, snav     |
|           19 |     2649 | 2024-04-23 | Wildcard         | W   | 0.502      | 0.477        | 0.048 (0.011)    | -                | -         |     5.64 | dare, dea, Peeping, shane, snav     |
|           18 |     2786 | 2024-04-18 | Legacy           | L   | 0.469      | -            | -                | -                | -         |    -6.77 | dare, dea, Peeping, shane, snav     |
|           17 |     2791 | 2024-04-18 | M80              | L   | 0.468      | -            | -                | -                | -         |    -3.29 | dare, dea, Peeping, shane, snav     |
|           16 |     2836 | 2024-04-17 | Nouns            | W   | 0.462      | -            | -                | -                | -         |     6.26 | dare, dea, Peeping, shane, snav     |
|           15 |     2841 | 2024-04-17 | Wildcard         | W   | 0.462      | -            | -                | -                | -         |     5.32 | dare, dea, Peeping, shane, snav     |
|           14 |     2989 | 2024-04-10 | Nouns            | L   | 0.416      | -            | -                | -                | -         |    -7.68 | dare, dea, Peeping, shane, snav     |
|           13 |     2995 | 2024-04-10 | Nouns            | L   | 0.416      | -            | -                | -                | -         |    -7.96 | dare, dea, Peeping, shane, snav     |
|           12 |     3224 | 2024-04-03 | LAG              | W   | 0.369      | -            | -                | -                | -         |     3.53 | dare, dea, Peeping, shane, snav     |
|           11 |     3226 | 2024-04-03 | LAG              | L   | 0.369      | -            | -                | -                | -         |    -8.27 | dare, dea, Peeping, shane, snav     |
|           10 |     3401 | 2024-03-26 | BOSS             | W   | 0.316      | -            | -                | -                | -         |     2.50 | dare, dea, Peeping, shane, snav     |
|            9 |     3406 | 2024-03-26 | BOSS             | W   | 0.316      | -            | -                | -                | -         |     2.56 | dare, dea, Peeping, shane, snav     |
|            8 |     3573 | 2024-03-15 | Carpe Diem       | W   | 0.243      | -            | -                | -                | -         |     1.13 | dare, dea, Peeping, shane, snav     |
|            7 |     3575 | 2024-03-15 | Carpe Diem       | W   | 0.243      | -            | -                | -                | -         |     1.14 | dare, dea, Peeping, shane, snav     |
|            6 |     3674 | 2024-03-12 | Party Astronauts | L   | 0.223      | -            | -                | -                | -         |    -4.22 | dare, dea, Peeping, shane, snav     |
|            5 |     3774 | 2024-03-08 | Spirit           | L   | 0.193      | -            | -                | -                | -         |    -0.04 | dare, MRC9, Peeping, shane, snav    |
|            4 |     3926 | 2024-03-02 | ODDIK            | L   | 0.154      | -            | -                | -                | -         |    -2.49 | dare, nbgee12, Peeping, shane, snav |
|            3 |     3954 | 2024-03-01 | Complexity       | L   | 0.147      | -            | -                | -                | -         |    -0.12 | dare, nbgee12, Peeping, shane, snav |
|            2 |     4343 | 2024-02-13 | Mythic           | L   | 0.037      | -            | -                | -                | -         |    -0.88 | dare, dea, Peeping, shane, snav     |
|            1 |     4346 | 2024-02-13 | Mythic           | W   | 0.036      | -            | -                | -                | -         |     0.27 | dare, dea, Peeping, shane, snav     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,526.67)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-23 |      0.910 | $3,000.00      | $2,728.75       |
| 2024-06-16 |      0.863 | $1,500.00      | $1,293.96       |
| 2024-06-09 |      0.816 | $4,250.00      | $3,466.11       |
| 2024-03-10 |      0.208 | $5,000.00      | $1,037.85       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
