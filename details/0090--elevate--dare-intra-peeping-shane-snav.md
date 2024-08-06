### Roster Details<br />
Team Name: Elevate<br />
Roster: dare, intra, Peeping, shane, snav<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [23]( ../standings_americas.md)<br />
<br />
Final Rank Value:  908.0<br />
<br />
Final Rank Value (908.0) = Starting Rank Value (1002.6) + Head To Head Adjustments (-94.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.146[<sup>2</sup>](#table1)
- LAN Wins: 0.315[<sup>2</sup>](#table1)

The average of these factors is 0.294<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1002.6
- 400 + ( ( 0.294 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1002.6


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
|           69 |       50 | 2024-08-03 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.522 (0.158)    | 0 (0.000) |    19.15 | dare, intra, Peeping, shane, snav   |
|           68 |      163 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -13.80 | dare, dea, Peeping, shane, snav     |
|           67 |      169 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.06 | dare, dea, Peeping, shane, snav     |
|           66 |      408 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -12.33 | dare, dea, Peeping, shane, snav     |
|           65 |      411 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -13.43 | dare, dea, Peeping, shane, snav     |
|           64 |      504 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -18.54 | dare, Fr3nk1e, Peeping, shane, snav |
|           63 |      532 | 2024-07-20 | Phoenix          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.53 | dare, Fr3nk1e, Peeping, shane, snav |
|           62 |      602 | 2024-07-18 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -21.85 | dare, Fr3nk1e, Peeping, shane, snav |
|           61 |      604 | 2024-07-18 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.326 (0.156)    | 0 (0.000) |     9.20 | dare, Fr3nk1e, Peeping, shane, snav |
|           60 |      666 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.277 (0.132)    | 0 (0.000) |     5.49 | dare, Fr3nk1e, Peeping, shane, snav |
|           59 |      670 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.277 (0.132)    | 0 (0.000) |     5.79 | dare, Fr3nk1e, Peeping, shane, snav |
|           58 |      728 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.292 (0.139)    | 0 (0.000) |     8.70 | dare, Fr3nk1e, Peeping, shane, snav |
|           57 |      735 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.292 (0.139)    | 0 (0.000) |     9.35 | dare, Fr3nk1e, Peeping, shane, snav |
|           56 |      779 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -20.24 | dare, dea, Peeping, shane, snav     |
|           55 |      783 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -21.89 | dare, dea, Peeping, shane, snav     |
|           54 |      994 | 2024-06-23 | Locke's Kittens  | W   | 0.914      | -            | -                | -                | 1 (0.914) |     6.81 | dare, dea, Peeping, shane, snav     |
|           53 |      996 | 2024-06-23 | WICKED           | W   | 0.912      | -            | -                | -                | 1 (0.912) |     3.02 | dare, dea, Peeping, shane, snav     |
|           52 |     1000 | 2024-06-22 | LOCK IN          | W   | 0.906      | -            | -                | -                | 1 (0.906) |     1.11 | dare, dea, Peeping, shane, snav     |
|           51 |     1017 | 2024-06-16 | Legacy           | L   | 0.866      | -            | -                | -                | -         |   -11.26 | dare, dea, Peeping, shane, snav     |
|           50 |     1040 | 2024-06-15 | BOSS             | W   | 0.860      | -            | -                | -                | -         |     6.51 | dare, dea, Peeping, shane, snav     |
|           49 |     1075 | 2024-06-14 | FLUFFY AIMERS    | W   | 0.854      | -            | -                | -                | -         |     4.86 | dare, dea, Peeping, shane, snav     |
|           48 |     1353 | 2024-06-07 | Nouns            | L   | 0.806      | -            | -                | -                | -         |   -12.89 | dare, dea, Peeping, shane, snav     |
|           47 |     1356 | 2024-06-07 | Nouns            | W   | 0.805      | 0.143        | 0.057 (0.007)    | -                | -         |    12.66 | dare, dea, Peeping, shane, snav     |
|           46 |     1361 | 2024-06-07 | Legacy           | L   | 0.805      | -            | -                | -                | -         |   -11.12 | dare, dea, Peeping, shane, snav     |
|           45 |     1402 | 2024-06-06 | Nouns            | L   | 0.800      | -            | -                | -                | -         |   -12.73 | dare, dea, Peeping, shane, snav     |
|           44 |     1412 | 2024-06-06 | FlyQuest RED     | W   | 0.799      | 0.384        | 0.017 (0.005)    | -                | -         |     5.22 | dare, dea, Peeping, shane, snav     |
|           43 |     1473 | 2024-06-05 | Mythic           | W   | 0.793      | 0.477        | -                | 0.292 (0.111)    | -         |     7.02 | dare, dea, Peeping, shane, snav     |
|           42 |     1525 | 2024-06-04 | Party Astronauts | L   | 0.787      | -            | -                | -                | -         |   -13.81 | dare, dea, Peeping, shane, snav     |
|           41 |     1833 | 2024-05-22 | NRG              | W   | 0.700      | 0.477        | 0.020 (0.007)    | 0.514 (0.171)    | -         |     8.72 | dare, dea, Peeping, shane, snav     |
|           40 |     1839 | 2024-05-22 | NRG              | W   | 0.700      | 0.477        | 0.020 (0.007)    | 0.514 (0.171)    | -         |     9.26 | dare, dea, Peeping, shane, snav     |
|           39 |     1882 | 2024-05-21 | Take Flyte       | W   | 0.694      | -            | -                | -                | -         |     3.31 | dare, dea, Peeping, shane, snav     |
|           38 |     1886 | 2024-05-21 | Take Flyte       | W   | 0.693      | -            | -                | -                | -         |     3.42 | dare, dea, Peeping, shane, snav     |
|           37 |     1927 | 2024-05-20 | Mythic           | L   | 0.686      | -            | -                | -                | -         |   -16.13 | dare, dea, Peeping, shane, snav     |
|           36 |     2013 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.667      | -            | -                | -                | -         |     4.02 | dare, dea, Peeping, shane, snav     |
|           35 |     2014 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.667      | -            | -                | -                | -         |     4.17 | dare, dea, Peeping, shane, snav     |
|           34 |     2085 | 2024-05-15 | Limitless        | W   | 0.654      | -            | -                | -                | -         |     2.60 | dare, dea, Peeping, shane, snav     |
|           33 |     2092 | 2024-05-15 | Limitless        | W   | 0.653      | -            | -                | -                | -         |     2.67 | dare, dea, Peeping, shane, snav     |
|           32 |     2138 | 2024-05-14 | M80              | L   | 0.647      | -            | -                | -                | -         |    -3.58 | dare, dea, Peeping, shane, snav     |
|           31 |     2145 | 2024-05-14 | M80              | L   | 0.647      | -            | -                | -                | -         |    -3.70 | dare, dea, Peeping, shane, snav     |
|           30 |     2154 | 2024-05-14 | Phoenix          | W   | 0.646      | -            | -                | -                | -         |     4.29 | dare, dea, Peeping, shane, snav     |
|           29 |     2157 | 2024-05-14 | Phoenix          | W   | 0.646      | -            | -                | -                | -         |     4.46 | dare, dea, Peeping, shane, snav     |
|           28 |     2213 | 2024-05-12 | NRG              | L   | 0.632      | -            | -                | -                | -         |   -12.63 | dare, dea, intra, Peeping, snav     |
|           27 |     2233 | 2024-05-11 | Nouns            | W   | 0.627      | 0.270        | 0.057 (0.010)    | -                | -         |     8.81 | dare, dea, intra, Peeping, snav     |
|           26 |     2234 | 2024-05-11 | Wildcard         | W   | 0.626      | 0.270        | 0.048 (0.008)    | -                | -         |     7.50 | dare, dea, intra, Peeping, snav     |
|           25 |     2237 | 2024-05-11 | Nouns            | L   | 0.626      | -            | -                | -                | -         |   -10.57 | dare, dea, intra, Peeping, snav     |
|           24 |     2304 | 2024-05-08 | MIGHT            | W   | 0.607      | -            | -                | -                | -         |     1.46 | dare, dea, Peeping, shane, snav     |
|           23 |     2306 | 2024-05-08 | MIGHT            | W   | 0.607      | -            | -                | -                | -         |     1.48 | dare, dea, Peeping, shane, snav     |
|           22 |     2328 | 2024-05-07 | Party Astronauts | W   | 0.601      | 0.477        | 0.041 (0.012)    | 0.522 (0.150)    | -         |     8.68 | dare, dea, Peeping, shane, snav     |
|           21 |     2329 | 2024-05-07 | Party Astronauts | L   | 0.600      | -            | -                | -                | -         |   -10.48 | dare, dea, Peeping, shane, snav     |
|           20 |     2626 | 2024-04-23 | Wildcard         | L   | 0.507      | -            | -                | -                | -         |   -10.33 | dare, dea, Peeping, shane, snav     |
|           19 |     2628 | 2024-04-23 | Wildcard         | W   | 0.507      | 0.477        | 0.048 (0.012)    | -                | -         |     5.70 | dare, dea, Peeping, shane, snav     |
|           18 |     2765 | 2024-04-18 | Legacy           | L   | 0.473      | -            | -                | -                | -         |    -6.80 | dare, dea, Peeping, shane, snav     |
|           17 |     2770 | 2024-04-18 | M80              | L   | 0.472      | -            | -                | -                | -         |    -3.31 | dare, dea, Peeping, shane, snav     |
|           16 |     2815 | 2024-04-17 | Nouns            | W   | 0.466      | -            | -                | -                | -         |     6.34 | dare, dea, Peeping, shane, snav     |
|           15 |     2820 | 2024-04-17 | Wildcard         | W   | 0.466      | -            | -                | -                | -         |     5.38 | dare, dea, Peeping, shane, snav     |
|           14 |     2968 | 2024-04-10 | Nouns            | L   | 0.420      | -            | -                | -                | -         |    -7.75 | dare, dea, Peeping, shane, snav     |
|           13 |     2974 | 2024-04-10 | Nouns            | L   | 0.420      | -            | -                | -                | -         |    -8.02 | dare, dea, Peeping, shane, snav     |
|           12 |     3203 | 2024-04-03 | LAG              | W   | 0.374      | -            | -                | -                | -         |     3.57 | dare, dea, Peeping, shane, snav     |
|           11 |     3205 | 2024-04-03 | LAG              | L   | 0.373      | -            | -                | -                | -         |    -8.36 | dare, dea, Peeping, shane, snav     |
|           10 |     3380 | 2024-03-26 | BOSS             | W   | 0.321      | -            | -                | -                | -         |     2.54 | dare, dea, Peeping, shane, snav     |
|            9 |     3385 | 2024-03-26 | BOSS             | W   | 0.320      | -            | -                | -                | -         |     2.59 | dare, dea, Peeping, shane, snav     |
|            8 |     3552 | 2024-03-15 | Carpe Diem       | W   | 0.247      | -            | -                | -                | -         |     1.14 | dare, dea, Peeping, shane, snav     |
|            7 |     3554 | 2024-03-15 | Carpe Diem       | W   | 0.247      | -            | -                | -                | -         |     1.16 | dare, dea, Peeping, shane, snav     |
|            6 |     3653 | 2024-03-12 | Party Astronauts | L   | 0.227      | -            | -                | -                | -         |    -4.29 | dare, dea, Peeping, shane, snav     |
|            5 |     3753 | 2024-03-08 | Spirit           | L   | 0.197      | -            | -                | -                | -         |    -0.04 | dare, MRC9, Peeping, shane, snav    |
|            4 |     3905 | 2024-03-02 | ODDIK            | L   | 0.159      | -            | -                | -                | -         |    -2.55 | dare, nbgee12, Peeping, shane, snav |
|            3 |     3933 | 2024-03-01 | Complexity       | L   | 0.152      | -            | -                | -                | -         |    -0.12 | dare, nbgee12, Peeping, shane, snav |
|            2 |     4322 | 2024-02-13 | Mythic           | L   | 0.041      | -            | -                | -                | -         |    -0.98 | dare, dea, Peeping, shane, snav     |
|            1 |     4325 | 2024-02-13 | Mythic           | W   | 0.040      | -            | -                | -                | -         |     0.30 | dare, dea, Peeping, shane, snav     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,583.96)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-23 |      0.914 | $3,000.00      | $2,741.25       |
| 2024-06-16 |      0.867 | $1,500.00      | $1,300.21       |
| 2024-06-09 |      0.820 | $4,250.00      | $3,483.82       |
| 2024-03-10 |      0.212 | $5,000.00      | $1,058.68       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
