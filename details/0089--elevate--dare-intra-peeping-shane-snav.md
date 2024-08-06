### Roster Details<br />
Team Name: Elevate<br />
Roster: dare, intra, Peeping, shane, snav<br />
Global Rank: [89](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [23]( ../standings_americas.md)<br />
<br />
Final Rank Value:  907.8<br />
<br />
Final Rank Value (907.8) = Starting Rank Value (1002.4) + Head To Head Adjustments (-94.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.146[<sup>2</sup>](#table1)
- LAN Wins: 0.314[<sup>2</sup>](#table1)

The average of these factors is 0.294<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1002.4
- 400 + ( ( 0.294 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1002.4


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
|           69 |       54 | 2024-08-03 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.522 (0.158)    | 0 (0.000) |    19.14 | dare, intra, Peeping, shane, snav   |
|           68 |      167 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -13.79 | dare, dea, Peeping, shane, snav     |
|           67 |      173 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.05 | dare, dea, Peeping, shane, snav     |
|           66 |      412 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -12.34 | dare, dea, Peeping, shane, snav     |
|           65 |      415 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -13.44 | dare, dea, Peeping, shane, snav     |
|           64 |      508 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -18.53 | dare, Fr3nk1e, Peeping, shane, snav |
|           63 |      536 | 2024-07-20 | Phoenix          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.54 | dare, Fr3nk1e, Peeping, shane, snav |
|           62 |      606 | 2024-07-18 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -21.85 | dare, Fr3nk1e, Peeping, shane, snav |
|           61 |      608 | 2024-07-18 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.326 (0.155)    | 0 (0.000) |     9.20 | dare, Fr3nk1e, Peeping, shane, snav |
|           60 |      670 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.277 (0.132)    | 0 (0.000) |     5.50 | dare, Fr3nk1e, Peeping, shane, snav |
|           59 |      674 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.277 (0.132)    | 0 (0.000) |     5.79 | dare, Fr3nk1e, Peeping, shane, snav |
|           58 |      732 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.291 (0.139)    | 0 (0.000) |     8.70 | dare, Fr3nk1e, Peeping, shane, snav |
|           57 |      739 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.291 (0.139)    | 0 (0.000) |     9.35 | dare, Fr3nk1e, Peeping, shane, snav |
|           56 |      783 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -20.25 | dare, dea, Peeping, shane, snav     |
|           55 |      787 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -21.90 | dare, dea, Peeping, shane, snav     |
|           54 |      998 | 2024-06-23 | Locke's Kittens  | W   | 0.911      | -            | -                | -                | 1 (0.911) |     6.79 | dare, dea, Peeping, shane, snav     |
|           53 |     1000 | 2024-06-23 | WICKED           | W   | 0.909      | -            | -                | -                | 1 (0.909) |     3.02 | dare, dea, Peeping, shane, snav     |
|           52 |     1004 | 2024-06-22 | LOCK IN          | W   | 0.904      | -            | -                | -                | 1 (0.904) |     1.11 | dare, dea, Peeping, shane, snav     |
|           51 |     1021 | 2024-06-16 | Legacy           | L   | 0.863      | -            | -                | -                | -         |   -11.24 | dare, dea, Peeping, shane, snav     |
|           50 |     1044 | 2024-06-15 | BOSS             | W   | 0.858      | -            | -                | -                | -         |     6.50 | dare, dea, Peeping, shane, snav     |
|           49 |     1079 | 2024-06-14 | FLUFFY AIMERS    | W   | 0.851      | -            | -                | -                | -         |     4.85 | dare, dea, Peeping, shane, snav     |
|           48 |     1357 | 2024-06-07 | Nouns            | L   | 0.803      | -            | -                | -                | -         |   -12.85 | dare, dea, Peeping, shane, snav     |
|           47 |     1360 | 2024-06-07 | Nouns            | W   | 0.803      | 0.143        | 0.057 (0.007)    | -                | -         |    12.61 | dare, dea, Peeping, shane, snav     |
|           46 |     1365 | 2024-06-07 | Legacy           | L   | 0.802      | -            | -                | -                | -         |   -11.10 | dare, dea, Peeping, shane, snav     |
|           45 |     1406 | 2024-06-06 | Nouns            | L   | 0.797      | -            | -                | -                | -         |   -12.70 | dare, dea, Peeping, shane, snav     |
|           44 |     1416 | 2024-06-06 | FlyQuest RED     | W   | 0.797      | 0.384        | 0.017 (0.005)    | -                | -         |     5.20 | dare, dea, Peeping, shane, snav     |
|           43 |     1477 | 2024-06-05 | Mythic           | W   | 0.791      | 0.477        | -                | 0.291 (0.110)    | -         |     6.99 | dare, dea, Peeping, shane, snav     |
|           42 |     1529 | 2024-06-04 | Party Astronauts | L   | 0.784      | -            | -                | -                | -         |   -13.77 | dare, dea, Peeping, shane, snav     |
|           41 |     1837 | 2024-05-22 | NRG              | W   | 0.698      | 0.477        | 0.020 (0.007)    | 0.513 (0.171)    | -         |     8.68 | dare, dea, Peeping, shane, snav     |
|           40 |     1843 | 2024-05-22 | NRG              | W   | 0.698      | 0.477        | 0.020 (0.007)    | 0.513 (0.171)    | -         |     9.22 | dare, dea, Peeping, shane, snav     |
|           39 |     1886 | 2024-05-21 | Take Flyte       | W   | 0.691      | -            | -                | -                | -         |     3.30 | dare, dea, Peeping, shane, snav     |
|           38 |     1890 | 2024-05-21 | Take Flyte       | W   | 0.691      | -            | -                | -                | -         |     3.41 | dare, dea, Peeping, shane, snav     |
|           37 |     1931 | 2024-05-20 | Mythic           | L   | 0.684      | -            | -                | -                | -         |   -16.08 | dare, dea, Peeping, shane, snav     |
|           36 |     2017 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.664      | -            | -                | -                | -         |     4.01 | dare, dea, Peeping, shane, snav     |
|           35 |     2018 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.664      | -            | -                | -                | -         |     4.16 | dare, dea, Peeping, shane, snav     |
|           34 |     2089 | 2024-05-15 | Limitless        | W   | 0.651      | -            | -                | -                | -         |     2.59 | dare, dea, Peeping, shane, snav     |
|           33 |     2096 | 2024-05-15 | Limitless        | W   | 0.651      | -            | -                | -                | -         |     2.66 | dare, dea, Peeping, shane, snav     |
|           32 |     2142 | 2024-05-14 | M80              | L   | 0.645      | -            | -                | -                | -         |    -3.58 | dare, dea, Peeping, shane, snav     |
|           31 |     2149 | 2024-05-14 | M80              | L   | 0.644      | -            | -                | -                | -         |    -3.70 | dare, dea, Peeping, shane, snav     |
|           30 |     2158 | 2024-05-14 | Phoenix          | W   | 0.644      | -            | -                | -                | -         |     4.27 | dare, dea, Peeping, shane, snav     |
|           29 |     2161 | 2024-05-14 | Phoenix          | W   | 0.644      | -            | -                | -                | -         |     4.44 | dare, dea, Peeping, shane, snav     |
|           28 |     2217 | 2024-05-12 | NRG              | L   | 0.630      | -            | -                | -                | -         |   -12.58 | dare, dea, intra, Peeping, snav     |
|           27 |     2237 | 2024-05-11 | Nouns            | W   | 0.624      | 0.270        | 0.057 (0.010)    | -                | -         |     8.77 | dare, dea, intra, Peeping, snav     |
|           26 |     2238 | 2024-05-11 | Wildcard         | W   | 0.624      | 0.270        | 0.048 (0.008)    | -                | -         |     7.46 | dare, dea, intra, Peeping, snav     |
|           25 |     2241 | 2024-05-11 | Nouns            | L   | 0.624      | -            | -                | -                | -         |   -10.54 | dare, dea, intra, Peeping, snav     |
|           24 |     2308 | 2024-05-08 | MIGHT            | W   | 0.604      | -            | -                | -                | -         |     1.45 | dare, dea, Peeping, shane, snav     |
|           23 |     2310 | 2024-05-08 | MIGHT            | W   | 0.604      | -            | -                | -                | -         |     1.47 | dare, dea, Peeping, shane, snav     |
|           22 |     2332 | 2024-05-07 | Party Astronauts | W   | 0.598      | 0.477        | 0.041 (0.012)    | 0.522 (0.149)    | -         |     8.64 | dare, dea, Peeping, shane, snav     |
|           21 |     2333 | 2024-05-07 | Party Astronauts | L   | 0.598      | -            | -                | -                | -         |   -10.44 | dare, dea, Peeping, shane, snav     |
|           20 |     2630 | 2024-04-23 | Wildcard         | L   | 0.505      | -            | -                | -                | -         |   -10.29 | dare, dea, Peeping, shane, snav     |
|           19 |     2632 | 2024-04-23 | Wildcard         | W   | 0.504      | 0.477        | 0.048 (0.011)    | -                | -         |     5.67 | dare, dea, Peeping, shane, snav     |
|           18 |     2769 | 2024-04-18 | Legacy           | L   | 0.471      | -            | -                | -                | -         |    -6.77 | dare, dea, Peeping, shane, snav     |
|           17 |     2774 | 2024-04-18 | M80              | L   | 0.470      | -            | -                | -                | -         |    -3.29 | dare, dea, Peeping, shane, snav     |
|           16 |     2819 | 2024-04-17 | Nouns            | W   | 0.464      | -            | -                | -                | -         |     6.30 | dare, dea, Peeping, shane, snav     |
|           15 |     2824 | 2024-04-17 | Wildcard         | W   | 0.463      | -            | -                | -                | -         |     5.34 | dare, dea, Peeping, shane, snav     |
|           14 |     2972 | 2024-04-10 | Nouns            | L   | 0.418      | -            | -                | -                | -         |    -7.70 | dare, dea, Peeping, shane, snav     |
|           13 |     2978 | 2024-04-10 | Nouns            | L   | 0.417      | -            | -                | -                | -         |    -7.98 | dare, dea, Peeping, shane, snav     |
|           12 |     3207 | 2024-04-03 | LAG              | W   | 0.371      | -            | -                | -                | -         |     3.54 | dare, dea, Peeping, shane, snav     |
|           11 |     3209 | 2024-04-03 | LAG              | L   | 0.371      | -            | -                | -                | -         |    -8.31 | dare, dea, Peeping, shane, snav     |
|           10 |     3384 | 2024-03-26 | BOSS             | W   | 0.318      | -            | -                | -                | -         |     2.52 | dare, dea, Peeping, shane, snav     |
|            9 |     3389 | 2024-03-26 | BOSS             | W   | 0.318      | -            | -                | -                | -         |     2.57 | dare, dea, Peeping, shane, snav     |
|            8 |     3556 | 2024-03-15 | Carpe Diem       | W   | 0.245      | -            | -                | -                | -         |     1.13 | dare, dea, Peeping, shane, snav     |
|            7 |     3558 | 2024-03-15 | Carpe Diem       | W   | 0.244      | -            | -                | -                | -         |     1.14 | dare, dea, Peeping, shane, snav     |
|            6 |     3657 | 2024-03-12 | Party Astronauts | L   | 0.224      | -            | -                | -                | -         |    -4.24 | dare, dea, Peeping, shane, snav     |
|            5 |     3757 | 2024-03-08 | Spirit           | L   | 0.195      | -            | -                | -                | -         |    -0.04 | dare, MRC9, Peeping, shane, snav    |
|            4 |     3909 | 2024-03-02 | ODDIK            | L   | 0.156      | -            | -                | -                | -         |    -2.51 | dare, nbgee12, Peeping, shane, snav |
|            3 |     3937 | 2024-03-01 | Complexity       | L   | 0.149      | -            | -                | -                | -         |    -0.12 | dare, nbgee12, Peeping, shane, snav |
|            2 |     4326 | 2024-02-13 | Mythic           | L   | 0.038      | -            | -                | -                | -         |    -0.92 | dare, dea, Peeping, shane, snav     |
|            1 |     4329 | 2024-02-13 | Mythic           | W   | 0.038      | -            | -                | -                | -         |     0.28 | dare, dea, Peeping, shane, snav     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,549.58)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-23 |      0.911 | $3,000.00      | $2,733.75       |
| 2024-06-16 |      0.864 | $1,500.00      | $1,296.46       |
| 2024-06-09 |      0.817 | $4,250.00      | $3,473.19       |
| 2024-03-10 |      0.209 | $5,000.00      | $1,046.18       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
