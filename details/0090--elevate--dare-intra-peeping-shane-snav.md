### Roster Details<br />
Team Name: Elevate<br />
Roster: dare, intra, Peeping, shane, snav<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [23]( ../standings_americas.md)<br />
<br />
Final Rank Value:  907.8<br />
<br />
Final Rank Value (907.8) = Starting Rank Value (1002.8) + Head To Head Adjustments (-95.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.146[<sup>2</sup>](#table1)
- LAN Wins: 0.315[<sup>2</sup>](#table1)

The average of these factors is 0.294<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1002.8
- 400 + ( ( 0.294 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1002.8


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
|           69 |       48 | 2024-08-03 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.523 (0.158)    | 0 (0.000) |    19.16 | dare, intra, Peeping, shane, snav   |
|           68 |      161 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -13.82 | dare, dea, Peeping, shane, snav     |
|           67 |      167 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.09 | dare, dea, Peeping, shane, snav     |
|           66 |      406 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -12.33 | dare, dea, Peeping, shane, snav     |
|           65 |      409 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -13.42 | dare, dea, Peeping, shane, snav     |
|           64 |      502 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -18.57 | dare, Fr3nk1e, Peeping, shane, snav |
|           63 |      530 | 2024-07-20 | Phoenix          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.53 | dare, Fr3nk1e, Peeping, shane, snav |
|           62 |      600 | 2024-07-18 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -21.88 | dare, Fr3nk1e, Peeping, shane, snav |
|           61 |      602 | 2024-07-18 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.327 (0.156)    | 0 (0.000) |     9.16 | dare, Fr3nk1e, Peeping, shane, snav |
|           60 |      664 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.278 (0.132)    | 0 (0.000) |     5.49 | dare, Fr3nk1e, Peeping, shane, snav |
|           59 |      668 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.278 (0.132)    | 0 (0.000) |     5.78 | dare, Fr3nk1e, Peeping, shane, snav |
|           58 |      726 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.293 (0.140)    | 0 (0.000) |     8.69 | dare, Fr3nk1e, Peeping, shane, snav |
|           57 |      733 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.293 (0.140)    | 0 (0.000) |     9.34 | dare, Fr3nk1e, Peeping, shane, snav |
|           56 |      777 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -20.24 | dare, dea, Peeping, shane, snav     |
|           55 |      781 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -21.89 | dare, dea, Peeping, shane, snav     |
|           54 |      992 | 2024-06-23 | Locke's Kittens  | W   | 0.916      | -            | -                | -                | 1 (0.916) |     6.82 | dare, dea, Peeping, shane, snav     |
|           53 |      994 | 2024-06-23 | WICKED           | W   | 0.914      | -            | -                | -                | 1 (0.914) |     3.03 | dare, dea, Peeping, shane, snav     |
|           52 |      998 | 2024-06-22 | LOCK IN          | W   | 0.908      | -            | -                | -                | 1 (0.908) |     1.12 | dare, dea, Peeping, shane, snav     |
|           51 |     1015 | 2024-06-16 | Legacy           | L   | 0.868      | -            | -                | -                | -         |   -11.26 | dare, dea, Peeping, shane, snav     |
|           50 |     1038 | 2024-06-15 | BOSS             | W   | 0.862      | -            | -                | -                | -         |     6.49 | dare, dea, Peeping, shane, snav     |
|           49 |     1073 | 2024-06-14 | FLUFFY AIMERS    | W   | 0.856      | -            | -                | -                | -         |     4.87 | dare, dea, Peeping, shane, snav     |
|           48 |     1351 | 2024-06-07 | Nouns            | L   | 0.807      | -            | -                | -                | -         |   -12.91 | dare, dea, Peeping, shane, snav     |
|           47 |     1354 | 2024-06-07 | Nouns            | W   | 0.807      | 0.143        | 0.057 (0.007)    | -                | -         |    12.69 | dare, dea, Peeping, shane, snav     |
|           46 |     1359 | 2024-06-07 | Legacy           | L   | 0.807      | -            | -                | -                | -         |   -11.13 | dare, dea, Peeping, shane, snav     |
|           45 |     1400 | 2024-06-06 | Nouns            | L   | 0.802      | -            | -                | -                | -         |   -12.75 | dare, dea, Peeping, shane, snav     |
|           44 |     1410 | 2024-06-06 | FlyQuest RED     | W   | 0.801      | 0.384        | 0.017 (0.005)    | -                | -         |     5.24 | dare, dea, Peeping, shane, snav     |
|           43 |     1471 | 2024-06-05 | Mythic           | W   | 0.795      | 0.477        | -                | 0.293 (0.111)    | -         |     7.02 | dare, dea, Peeping, shane, snav     |
|           42 |     1523 | 2024-06-04 | Party Astronauts | L   | 0.788      | -            | -                | -                | -         |   -13.84 | dare, dea, Peeping, shane, snav     |
|           41 |     1831 | 2024-05-22 | NRG              | W   | 0.702      | 0.477        | 0.020 (0.007)    | 0.514 (0.172)    | -         |     8.74 | dare, dea, Peeping, shane, snav     |
|           40 |     1837 | 2024-05-22 | NRG              | W   | 0.702      | 0.477        | 0.020 (0.007)    | 0.514 (0.172)    | -         |     9.28 | dare, dea, Peeping, shane, snav     |
|           39 |     1880 | 2024-05-21 | Take Flyte       | W   | 0.695      | -            | -                | -                | -         |     3.31 | dare, dea, Peeping, shane, snav     |
|           38 |     1884 | 2024-05-21 | Take Flyte       | W   | 0.695      | -            | -                | -                | -         |     3.42 | dare, dea, Peeping, shane, snav     |
|           37 |     1925 | 2024-05-20 | Mythic           | L   | 0.688      | -            | -                | -                | -         |   -16.18 | dare, dea, Peeping, shane, snav     |
|           36 |     2011 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.669      | -            | -                | -                | -         |     4.03 | dare, dea, Peeping, shane, snav     |
|           35 |     2012 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.668      | -            | -                | -                | -         |     4.18 | dare, dea, Peeping, shane, snav     |
|           34 |     2083 | 2024-05-15 | Limitless        | W   | 0.655      | -            | -                | -                | -         |     2.61 | dare, dea, Peeping, shane, snav     |
|           33 |     2090 | 2024-05-15 | Limitless        | W   | 0.655      | -            | -                | -                | -         |     2.67 | dare, dea, Peeping, shane, snav     |
|           32 |     2136 | 2024-05-14 | M80              | L   | 0.649      | -            | -                | -                | -         |    -3.58 | dare, dea, Peeping, shane, snav     |
|           31 |     2143 | 2024-05-14 | M80              | L   | 0.648      | -            | -                | -                | -         |    -3.71 | dare, dea, Peeping, shane, snav     |
|           30 |     2152 | 2024-05-14 | Phoenix          | W   | 0.648      | -            | -                | -                | -         |     4.30 | dare, dea, Peeping, shane, snav     |
|           29 |     2155 | 2024-05-14 | Phoenix          | W   | 0.648      | -            | -                | -                | -         |     4.47 | dare, dea, Peeping, shane, snav     |
|           28 |     2211 | 2024-05-12 | NRG              | L   | 0.634      | -            | -                | -                | -         |   -12.67 | dare, dea, intra, Peeping, snav     |
|           27 |     2231 | 2024-05-11 | Nouns            | W   | 0.628      | 0.270        | 0.057 (0.010)    | -                | -         |     8.83 | dare, dea, intra, Peeping, snav     |
|           26 |     2232 | 2024-05-11 | Wildcard         | W   | 0.628      | 0.270        | 0.048 (0.008)    | -                | -         |     7.51 | dare, dea, intra, Peeping, snav     |
|           25 |     2235 | 2024-05-11 | Nouns            | L   | 0.628      | -            | -                | -                | -         |   -10.60 | dare, dea, intra, Peeping, snav     |
|           24 |     2302 | 2024-05-08 | MIGHT            | W   | 0.609      | -            | -                | -                | -         |     1.46 | dare, dea, Peeping, shane, snav     |
|           23 |     2304 | 2024-05-08 | MIGHT            | W   | 0.608      | -            | -                | -                | -         |     1.48 | dare, dea, Peeping, shane, snav     |
|           22 |     2326 | 2024-05-07 | Party Astronauts | W   | 0.602      | 0.477        | 0.041 (0.012)    | 0.523 (0.150)    | -         |     8.71 | dare, dea, Peeping, shane, snav     |
|           21 |     2327 | 2024-05-07 | Party Astronauts | L   | 0.602      | -            | -                | -                | -         |   -10.51 | dare, dea, Peeping, shane, snav     |
|           20 |     2624 | 2024-04-23 | Wildcard         | L   | 0.509      | -            | -                | -                | -         |   -10.38 | dare, dea, Peeping, shane, snav     |
|           19 |     2626 | 2024-04-23 | Wildcard         | W   | 0.508      | 0.477        | 0.048 (0.012)    | -                | -         |     5.71 | dare, dea, Peeping, shane, snav     |
|           18 |     2763 | 2024-04-18 | Legacy           | L   | 0.475      | -            | -                | -                | -         |    -6.81 | dare, dea, Peeping, shane, snav     |
|           17 |     2768 | 2024-04-18 | M80              | L   | 0.474      | -            | -                | -                | -         |    -3.31 | dare, dea, Peeping, shane, snav     |
|           16 |     2813 | 2024-04-17 | Nouns            | W   | 0.468      | -            | -                | -                | -         |     6.37 | dare, dea, Peeping, shane, snav     |
|           15 |     2818 | 2024-04-17 | Wildcard         | W   | 0.468      | -            | -                | -                | -         |     5.39 | dare, dea, Peeping, shane, snav     |
|           14 |     2966 | 2024-04-10 | Nouns            | L   | 0.422      | -            | -                | -                | -         |    -7.78 | dare, dea, Peeping, shane, snav     |
|           13 |     2972 | 2024-04-10 | Nouns            | L   | 0.422      | -            | -                | -                | -         |    -8.06 | dare, dea, Peeping, shane, snav     |
|           12 |     3201 | 2024-04-03 | LAG              | W   | 0.375      | -            | -                | -                | -         |     3.59 | dare, dea, Peeping, shane, snav     |
|           11 |     3203 | 2024-04-03 | LAG              | L   | 0.375      | -            | -                | -                | -         |    -8.40 | dare, dea, Peeping, shane, snav     |
|           10 |     3378 | 2024-03-26 | BOSS             | W   | 0.322      | -            | -                | -                | -         |     2.53 | dare, dea, Peeping, shane, snav     |
|            9 |     3383 | 2024-03-26 | BOSS             | W   | 0.322      | -            | -                | -                | -         |     2.58 | dare, dea, Peeping, shane, snav     |
|            8 |     3550 | 2024-03-15 | Carpe Diem       | W   | 0.249      | -            | -                | -                | -         |     1.15 | dare, dea, Peeping, shane, snav     |
|            7 |     3552 | 2024-03-15 | Carpe Diem       | W   | 0.249      | -            | -                | -                | -         |     1.16 | dare, dea, Peeping, shane, snav     |
|            6 |     3651 | 2024-03-12 | Party Astronauts | L   | 0.229      | -            | -                | -                | -         |    -4.32 | dare, dea, Peeping, shane, snav     |
|            5 |     3751 | 2024-03-08 | Spirit           | L   | 0.199      | -            | -                | -                | -         |    -0.04 | dare, MRC9, Peeping, shane, snav    |
|            4 |     3903 | 2024-03-02 | ODDIK            | L   | 0.160      | -            | -                | -                | -         |    -2.58 | dare, nbgee12, Peeping, shane, snav |
|            3 |     3931 | 2024-03-01 | Complexity       | L   | 0.153      | -            | -                | -                | -         |    -0.12 | dare, nbgee12, Peeping, shane, snav |
|            2 |     4320 | 2024-02-13 | Mythic           | L   | 0.042      | -            | -                | -                | -         |    -1.03 | dare, dea, Peeping, shane, snav     |
|            1 |     4323 | 2024-02-13 | Mythic           | W   | 0.042      | -            | -                | -                | -         |     0.31 | dare, dea, Peeping, shane, snav     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,608.78)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-23 |      0.916 | $3,000.00      | $2,746.67       |
| 2024-06-16 |      0.869 | $1,500.00      | $1,302.92       |
| 2024-06-09 |      0.822 | $4,250.00      | $3,491.49       |
| 2024-03-10 |      0.214 | $5,000.00      | $1,067.71       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
