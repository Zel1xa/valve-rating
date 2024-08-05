### Roster Details<br />
Team Name: Elevate<br />
Roster: dare, intra, Peeping, shane, snav<br />
Global Rank: [89](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [23]( ../standings_americas.md)<br />
<br />
Final Rank Value:  908.2<br />
<br />
Final Rank Value (908.2) = Starting Rank Value (1003.2) + Head To Head Adjustments (-95.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.148[<sup>2</sup>](#table1)
- LAN Wins: 0.315[<sup>2</sup>](#table1)

The average of these factors is 0.295<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1003.2
- 400 + ( ( 0.295 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1003.2


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
|           69 |       39 | 2024-08-03 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.529 (0.160)    | 0 (0.000) |    19.16 | dare, intra, Peeping, shane, snav   |
|           68 |      152 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -13.82 | dare, dea, Peeping, shane, snav     |
|           67 |      158 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.09 | dare, dea, Peeping, shane, snav     |
|           66 |      397 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -12.32 | dare, dea, Peeping, shane, snav     |
|           65 |      400 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -13.42 | dare, dea, Peeping, shane, snav     |
|           64 |      493 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -18.57 | dare, Fr3nk1e, Peeping, shane, snav |
|           63 |      521 | 2024-07-20 | Phoenix          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.53 | dare, Fr3nk1e, Peeping, shane, snav |
|           62 |      591 | 2024-07-18 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -21.88 | dare, Fr3nk1e, Peeping, shane, snav |
|           61 |      593 | 2024-07-18 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.331 (0.158)    | 0 (0.000) |     9.16 | dare, Fr3nk1e, Peeping, shane, snav |
|           60 |      655 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.281 (0.134)    | 0 (0.000) |     5.49 | dare, Fr3nk1e, Peeping, shane, snav |
|           59 |      659 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.281 (0.134)    | 0 (0.000) |     5.78 | dare, Fr3nk1e, Peeping, shane, snav |
|           58 |      717 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.297 (0.142)    | 0 (0.000) |     8.69 | dare, Fr3nk1e, Peeping, shane, snav |
|           57 |      724 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.297 (0.142)    | 0 (0.000) |     9.34 | dare, Fr3nk1e, Peeping, shane, snav |
|           56 |      768 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -20.25 | dare, dea, Peeping, shane, snav     |
|           55 |      772 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -21.90 | dare, dea, Peeping, shane, snav     |
|           54 |      983 | 2024-06-23 | Locke's Kittens  | W   | 0.917      | -            | -                | -                | 1 (0.917) |     6.81 | dare, dea, Peeping, shane, snav     |
|           53 |      985 | 2024-06-23 | WICKED           | W   | 0.915      | -            | -                | -                | 1 (0.915) |     3.02 | dare, dea, Peeping, shane, snav     |
|           52 |      989 | 2024-06-22 | LOCK IN          | W   | 0.910      | -            | -                | -                | 1 (0.910) |     1.12 | dare, dea, Peeping, shane, snav     |
|           51 |     1006 | 2024-06-16 | Legacy           | L   | 0.869      | -            | -                | -                | -         |   -11.27 | dare, dea, Peeping, shane, snav     |
|           50 |     1029 | 2024-06-15 | BOSS             | W   | 0.864      | -            | -                | -                | -         |     6.50 | dare, dea, Peeping, shane, snav     |
|           49 |     1064 | 2024-06-14 | FLUFFY AIMERS    | W   | 0.857      | -            | -                | -                | -         |     4.87 | dare, dea, Peeping, shane, snav     |
|           48 |     1342 | 2024-06-07 | Nouns            | L   | 0.809      | -            | -                | -                | -         |   -12.93 | dare, dea, Peeping, shane, snav     |
|           47 |     1345 | 2024-06-07 | Nouns            | W   | 0.809      | 0.143        | 0.057 (0.007)    | -                | -         |    12.72 | dare, dea, Peeping, shane, snav     |
|           46 |     1350 | 2024-06-07 | Legacy           | L   | 0.808      | -            | -                | -                | -         |   -11.13 | dare, dea, Peeping, shane, snav     |
|           45 |     1391 | 2024-06-06 | Nouns            | L   | 0.803      | -            | -                | -                | -         |   -12.77 | dare, dea, Peeping, shane, snav     |
|           44 |     1401 | 2024-06-06 | FlyQuest RED     | W   | 0.802      | 0.384        | 0.017 (0.005)    | -                | -         |     5.24 | dare, dea, Peeping, shane, snav     |
|           43 |     1462 | 2024-06-05 | Mythic           | W   | 0.797      | 0.477        | -                | 0.297 (0.113)    | -         |     7.04 | dare, dea, Peeping, shane, snav     |
|           42 |     1514 | 2024-06-04 | Party Astronauts | L   | 0.790      | -            | -                | -                | -         |   -13.85 | dare, dea, Peeping, shane, snav     |
|           41 |     1822 | 2024-05-22 | NRG              | W   | 0.704      | 0.477        | 0.020 (0.007)    | 0.520 (0.174)    | -         |     8.76 | dare, dea, Peeping, shane, snav     |
|           40 |     1828 | 2024-05-22 | NRG              | W   | 0.703      | 0.477        | 0.020 (0.007)    | 0.520 (0.174)    | -         |     9.30 | dare, dea, Peeping, shane, snav     |
|           39 |     1871 | 2024-05-21 | Take Flyte       | W   | 0.697      | -            | -                | -                | -         |     3.32 | dare, dea, Peeping, shane, snav     |
|           38 |     1875 | 2024-05-21 | Take Flyte       | W   | 0.697      | -            | -                | -                | -         |     3.42 | dare, dea, Peeping, shane, snav     |
|           37 |     1916 | 2024-05-20 | Mythic           | L   | 0.689      | -            | -                | -                | -         |   -16.22 | dare, dea, Peeping, shane, snav     |
|           36 |     2002 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.670      | -            | -                | -                | -         |     4.03 | dare, dea, Peeping, shane, snav     |
|           35 |     2003 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.670      | -            | -                | -                | -         |     4.18 | dare, dea, Peeping, shane, snav     |
|           34 |     2074 | 2024-05-15 | Limitless        | W   | 0.657      | -            | -                | -                | -         |     2.61 | dare, dea, Peeping, shane, snav     |
|           33 |     2081 | 2024-05-15 | Limitless        | W   | 0.657      | -            | -                | -                | -         |     2.67 | dare, dea, Peeping, shane, snav     |
|           32 |     2127 | 2024-05-14 | M80              | L   | 0.650      | -            | -                | -                | -         |    -3.59 | dare, dea, Peeping, shane, snav     |
|           31 |     2134 | 2024-05-14 | M80              | L   | 0.650      | -            | -                | -                | -         |    -3.71 | dare, dea, Peeping, shane, snav     |
|           30 |     2143 | 2024-05-14 | Phoenix          | W   | 0.650      | -            | -                | -                | -         |     4.31 | dare, dea, Peeping, shane, snav     |
|           29 |     2146 | 2024-05-14 | Phoenix          | W   | 0.649      | -            | -                | -                | -         |     4.48 | dare, dea, Peeping, shane, snav     |
|           28 |     2202 | 2024-05-12 | NRG              | L   | 0.636      | -            | -                | -                | -         |   -12.69 | dare, dea, intra, Peeping, snav     |
|           27 |     2222 | 2024-05-11 | Nouns            | W   | 0.630      | 0.270        | 0.057 (0.010)    | -                | -         |     8.86 | dare, dea, intra, Peeping, snav     |
|           26 |     2223 | 2024-05-11 | Wildcard         | W   | 0.630      | 0.270        | 0.048 (0.008)    | -                | -         |     7.54 | dare, dea, intra, Peeping, snav     |
|           25 |     2226 | 2024-05-11 | Nouns            | L   | 0.629      | -            | -                | -                | -         |   -10.61 | dare, dea, intra, Peeping, snav     |
|           24 |     2293 | 2024-05-08 | MIGHT            | W   | 0.610      | -            | -                | -                | -         |     1.47 | dare, dea, Peeping, shane, snav     |
|           23 |     2295 | 2024-05-08 | MIGHT            | W   | 0.610      | -            | -                | -                | -         |     1.49 | dare, dea, Peeping, shane, snav     |
|           22 |     2317 | 2024-05-07 | Party Astronauts | W   | 0.604      | 0.477        | 0.041 (0.012)    | 0.529 (0.152)    | -         |     8.74 | dare, dea, Peeping, shane, snav     |
|           21 |     2318 | 2024-05-07 | Party Astronauts | L   | 0.604      | -            | -                | -                | -         |   -10.52 | dare, dea, Peeping, shane, snav     |
|           20 |     2615 | 2024-04-23 | Wildcard         | L   | 0.510      | -            | -                | -                | -         |   -10.41 | dare, dea, Peeping, shane, snav     |
|           19 |     2617 | 2024-04-23 | Wildcard         | W   | 0.510      | 0.477        | 0.048 (0.012)    | -                | -         |     5.73 | dare, dea, Peeping, shane, snav     |
|           18 |     2754 | 2024-04-18 | Legacy           | L   | 0.477      | -            | -                | -                | -         |    -6.82 | dare, dea, Peeping, shane, snav     |
|           17 |     2759 | 2024-04-18 | M80              | L   | 0.476      | -            | -                | -                | -         |    -3.32 | dare, dea, Peeping, shane, snav     |
|           16 |     2804 | 2024-04-17 | Nouns            | W   | 0.470      | -            | -                | -                | -         |     6.40 | dare, dea, Peeping, shane, snav     |
|           15 |     2809 | 2024-04-17 | Wildcard         | W   | 0.469      | -            | -                | -                | -         |     5.41 | dare, dea, Peeping, shane, snav     |
|           14 |     2957 | 2024-04-10 | Nouns            | L   | 0.424      | -            | -                | -                | -         |    -7.80 | dare, dea, Peeping, shane, snav     |
|           13 |     2963 | 2024-04-10 | Nouns            | L   | 0.423      | -            | -                | -                | -         |    -8.08 | dare, dea, Peeping, shane, snav     |
|           12 |     3192 | 2024-04-03 | LAG              | W   | 0.377      | -            | -                | -                | -         |     3.61 | dare, dea, Peeping, shane, snav     |
|           11 |     3194 | 2024-04-03 | LAG              | L   | 0.377      | -            | -                | -                | -         |    -8.43 | dare, dea, Peeping, shane, snav     |
|           10 |     3369 | 2024-03-26 | BOSS             | W   | 0.324      | -            | -                | -                | -         |     2.54 | dare, dea, Peeping, shane, snav     |
|            9 |     3374 | 2024-03-26 | BOSS             | W   | 0.324      | -            | -                | -                | -         |     2.60 | dare, dea, Peeping, shane, snav     |
|            8 |     3541 | 2024-03-15 | Carpe Diem       | W   | 0.251      | -            | -                | -                | -         |     1.16 | dare, dea, Peeping, shane, snav     |
|            7 |     3543 | 2024-03-15 | Carpe Diem       | W   | 0.250      | -            | -                | -                | -         |     1.17 | dare, dea, Peeping, shane, snav     |
|            6 |     3642 | 2024-03-12 | Party Astronauts | L   | 0.230      | -            | -                | -                | -         |    -4.35 | dare, dea, Peeping, shane, snav     |
|            5 |     3742 | 2024-03-08 | Spirit           | L   | 0.200      | -            | -                | -                | -         |    -0.04 | dare, MRC9, Peeping, shane, snav    |
|            4 |     3894 | 2024-03-02 | ODDIK            | L   | 0.162      | -            | -                | -                | -         |    -2.60 | dare, nbgee12, Peeping, shane, snav |
|            3 |     3922 | 2024-03-01 | Complexity       | L   | 0.155      | -            | -                | -                | -         |    -0.13 | dare, nbgee12, Peeping, shane, snav |
|            2 |     4311 | 2024-02-13 | Mythic           | L   | 0.044      | -            | -                | -                | -         |    -1.06 | dare, dea, Peeping, shane, snav     |
|            1 |     4314 | 2024-02-13 | Mythic           | W   | 0.044      | -            | -                | -                | -         |     0.32 | dare, dea, Peeping, shane, snav     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,629.79)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-23 |      0.917 | $3,000.00      | $2,751.25       |
| 2024-06-16 |      0.870 | $1,500.00      | $1,305.21       |
| 2024-06-09 |      0.823 | $4,250.00      | $3,497.99       |
| 2024-03-10 |      0.215 | $5,000.00      | $1,075.35       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
