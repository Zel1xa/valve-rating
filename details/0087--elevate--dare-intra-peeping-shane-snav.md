### Roster Details<br />
Team Name: Elevate<br />
Roster: dare, intra, Peeping, shane, snav<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [23]( ../standings_americas.md)<br />
<br />
Final Rank Value:  908.3<br />
<br />
Final Rank Value (908.3) = Starting Rank Value (1003.8) + Head To Head Adjustments (-95.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.150[<sup>2</sup>](#table1)
- LAN Wins: 0.316[<sup>2</sup>](#table1)

The average of these factors is 0.295<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1003.8
- 400 + ( ( 0.295 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1003.8


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
|           69 |       22 | 2024-08-03 | Party Astronauts | W   | 1.000      | 0.303        | 0.041 (0.012)    | 0.531 (0.161)    | 0 (0.000) |    19.16 | dare, intra, Peeping, shane, snav   |
|           68 |      135 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -13.84 | dare, dea, Peeping, shane, snav     |
|           67 |      141 | 2024-07-31 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.11 | dare, dea, Peeping, shane, snav     |
|           66 |      380 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -12.31 | dare, dea, Peeping, shane, snav     |
|           65 |      383 | 2024-07-24 | Nouns            | L   | 1.000      | -            | -                | -                | -         |   -13.40 | dare, dea, Peeping, shane, snav     |
|           64 |      476 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -18.59 | dare, Fr3nk1e, Peeping, shane, snav |
|           63 |      504 | 2024-07-20 | Phoenix          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.52 | dare, Fr3nk1e, Peeping, shane, snav |
|           62 |      574 | 2024-07-18 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -21.88 | dare, Fr3nk1e, Peeping, shane, snav |
|           61 |      576 | 2024-07-18 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.332 (0.159)    | 0 (0.000) |     9.16 | dare, Fr3nk1e, Peeping, shane, snav |
|           60 |      638 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.283 (0.135)    | 0 (0.000) |     5.47 | dare, Fr3nk1e, Peeping, shane, snav |
|           59 |      642 | 2024-07-17 | Phoenix          | W   | 1.000      | 0.477        | -                | 0.283 (0.135)    | 0 (0.000) |     5.76 | dare, Fr3nk1e, Peeping, shane, snav |
|           58 |      700 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.299 (0.143)    | 0 (0.000) |     8.69 | dare, Fr3nk1e, Peeping, shane, snav |
|           57 |      707 | 2024-07-16 | Mythic           | W   | 1.000      | 0.477        | -                | 0.299 (0.143)    | 0 (0.000) |     9.34 | dare, Fr3nk1e, Peeping, shane, snav |
|           56 |      751 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -20.23 | dare, dea, Peeping, shane, snav     |
|           55 |      755 | 2024-07-15 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -21.89 | dare, dea, Peeping, shane, snav     |
|           54 |      966 | 2024-06-23 | Locke's Kittens  | W   | 0.923      | -            | -                | -                | 1 (0.923) |     6.84 | dare, dea, Peeping, shane, snav     |
|           53 |      968 | 2024-06-23 | WICKED           | W   | 0.921      | -            | -                | -                | 1 (0.921) |     3.04 | dare, dea, Peeping, shane, snav     |
|           52 |      972 | 2024-06-22 | LOCK IN          | W   | 0.915      | -            | -                | -                | 1 (0.915) |     1.12 | dare, dea, Peeping, shane, snav     |
|           51 |      989 | 2024-06-16 | Legacy           | L   | 0.875      | -            | -                | -                | -         |   -11.30 | dare, dea, Peeping, shane, snav     |
|           50 |     1012 | 2024-06-15 | BOSS             | W   | 0.869      | -            | -                | -                | -         |     6.54 | dare, dea, Peeping, shane, snav     |
|           49 |     1047 | 2024-06-14 | FLUFFY AIMERS    | W   | 0.863      | -            | -                | -                | -         |     4.83 | dare, dea, Peeping, shane, snav     |
|           48 |     1325 | 2024-06-07 | Nouns            | L   | 0.815      | -            | -                | -                | -         |   -13.00 | dare, dea, Peeping, shane, snav     |
|           47 |     1328 | 2024-06-07 | Nouns            | W   | 0.814      | 0.143        | 0.057 (0.007)    | -                | -         |    12.82 | dare, dea, Peeping, shane, snav     |
|           46 |     1333 | 2024-06-07 | Legacy           | L   | 0.814      | -            | -                | -                | -         |   -11.16 | dare, dea, Peeping, shane, snav     |
|           45 |     1374 | 2024-06-06 | Nouns            | L   | 0.809      | -            | -                | -                | -         |   -12.84 | dare, dea, Peeping, shane, snav     |
|           44 |     1384 | 2024-06-06 | FlyQuest RED     | W   | 0.808      | 0.384        | 0.017 (0.005)    | -                | -         |     5.28 | dare, dea, Peeping, shane, snav     |
|           43 |     1445 | 2024-06-05 | Mythic           | W   | 0.802      | 0.477        | -                | 0.299 (0.114)    | -         |     7.08 | dare, dea, Peeping, shane, snav     |
|           42 |     1497 | 2024-06-04 | Party Astronauts | L   | 0.796      | -            | -                | -                | -         |   -13.95 | dare, dea, Peeping, shane, snav     |
|           41 |     1805 | 2024-05-22 | NRG              | W   | 0.709      | 0.477        | 0.020 (0.007)    | 0.521 (0.176)    | -         |     8.83 | dare, dea, Peeping, shane, snav     |
|           40 |     1811 | 2024-05-22 | NRG              | W   | 0.709      | 0.477        | 0.020 (0.007)    | 0.521 (0.176)    | -         |     9.38 | dare, dea, Peeping, shane, snav     |
|           39 |     1854 | 2024-05-21 | Take Flyte       | W   | 0.703      | -            | -                | -                | -         |     3.34 | dare, dea, Peeping, shane, snav     |
|           38 |     1858 | 2024-05-21 | Take Flyte       | W   | 0.702      | -            | -                | -                | -         |     3.45 | dare, dea, Peeping, shane, snav     |
|           37 |     1899 | 2024-05-20 | Mythic           | L   | 0.695      | -            | -                | -                | -         |   -16.36 | dare, dea, Peeping, shane, snav     |
|           36 |     1985 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.676      | -            | -                | -                | -         |     3.99 | dare, dea, Peeping, shane, snav     |
|           35 |     1986 | 2024-05-17 | FLUFFY AIMERS    | W   | 0.676      | -            | -                | -                | -         |     4.14 | dare, dea, Peeping, shane, snav     |
|           34 |     2057 | 2024-05-15 | Limitless        | W   | 0.663      | -            | -                | -                | -         |     2.62 | dare, dea, Peeping, shane, snav     |
|           33 |     2064 | 2024-05-15 | Limitless        | W   | 0.662      | -            | -                | -                | -         |     2.69 | dare, dea, Peeping, shane, snav     |
|           32 |     2110 | 2024-05-14 | M80              | L   | 0.656      | -            | -                | -                | -         |    -3.60 | dare, dea, Peeping, shane, snav     |
|           31 |     2117 | 2024-05-14 | M80              | L   | 0.656      | -            | -                | -                | -         |    -3.72 | dare, dea, Peeping, shane, snav     |
|           30 |     2126 | 2024-05-14 | Phoenix          | W   | 0.655      | -            | -                | -                | -         |     4.34 | dare, dea, Peeping, shane, snav     |
|           29 |     2129 | 2024-05-14 | Phoenix          | W   | 0.655      | -            | -                | -                | -         |     4.51 | dare, dea, Peeping, shane, snav     |
|           28 |     2185 | 2024-05-12 | NRG              | L   | 0.641      | -            | -                | -                | -         |   -12.82 | dare, dea, intra, Peeping, snav     |
|           27 |     2205 | 2024-05-11 | Nouns            | W   | 0.636      | 0.270        | 0.057 (0.010)    | -                | -         |     8.95 | dare, dea, intra, Peeping, snav     |
|           26 |     2206 | 2024-05-11 | Wildcard         | W   | 0.635      | 0.270        | 0.048 (0.008)    | -                | -         |     7.62 | dare, dea, intra, Peeping, snav     |
|           25 |     2209 | 2024-05-11 | Nouns            | L   | 0.635      | -            | -                | -                | -         |   -10.69 | dare, dea, intra, Peeping, snav     |
|           24 |     2276 | 2024-05-08 | MIGHT            | W   | 0.616      | -            | -                | -                | -         |     1.48 | dare, dea, Peeping, shane, snav     |
|           23 |     2278 | 2024-05-08 | MIGHT            | W   | 0.616      | -            | -                | -                | -         |     1.50 | dare, dea, Peeping, shane, snav     |
|           22 |     2300 | 2024-05-07 | Party Astronauts | W   | 0.610      | 0.477        | 0.041 (0.012)    | 0.531 (0.154)    | -         |     8.82 | dare, dea, Peeping, shane, snav     |
|           21 |     2301 | 2024-05-07 | Party Astronauts | L   | 0.609      | -            | -                | -                | -         |   -10.63 | dare, dea, Peeping, shane, snav     |
|           20 |     2598 | 2024-04-23 | Wildcard         | L   | 0.516      | -            | -                | -                | -         |   -10.51 | dare, dea, Peeping, shane, snav     |
|           19 |     2600 | 2024-04-23 | Wildcard         | W   | 0.516      | 0.477        | 0.048 (0.012)    | -                | -         |     5.81 | dare, dea, Peeping, shane, snav     |
|           18 |     2737 | 2024-04-18 | Legacy           | L   | 0.483      | -            | -                | -                | -         |    -6.87 | dare, dea, Peeping, shane, snav     |
|           17 |     2742 | 2024-04-18 | M80              | L   | 0.481      | -            | -                | -                | -         |    -3.35 | dare, dea, Peeping, shane, snav     |
|           16 |     2787 | 2024-04-17 | Nouns            | W   | 0.475      | -            | -                | -                | -         |     6.48 | dare, dea, Peeping, shane, snav     |
|           15 |     2792 | 2024-04-17 | Wildcard         | W   | 0.475      | -            | -                | -                | -         |     5.50 | dare, dea, Peeping, shane, snav     |
|           14 |     2940 | 2024-04-10 | Nouns            | L   | 0.429      | -            | -                | -                | -         |    -7.89 | dare, dea, Peeping, shane, snav     |
|           13 |     2946 | 2024-04-10 | Nouns            | L   | 0.429      | -            | -                | -                | -         |    -8.18 | dare, dea, Peeping, shane, snav     |
|           12 |     3175 | 2024-04-03 | LAG              | W   | 0.383      | -            | -                | -                | -         |     3.67 | dare, dea, Peeping, shane, snav     |
|           11 |     3177 | 2024-04-03 | LAG              | L   | 0.382      | -            | -                | -                | -         |    -8.55 | dare, dea, Peeping, shane, snav     |
|           10 |     3352 | 2024-03-26 | BOSS             | W   | 0.330      | -            | -                | -                | -         |     2.59 | dare, dea, Peeping, shane, snav     |
|            9 |     3357 | 2024-03-26 | BOSS             | W   | 0.329      | -            | -                | -                | -         |     2.65 | dare, dea, Peeping, shane, snav     |
|            8 |     3524 | 2024-03-15 | Carpe Diem       | W   | 0.256      | -            | -                | -                | -         |     1.18 | dare, dea, Peeping, shane, snav     |
|            7 |     3526 | 2024-03-15 | Carpe Diem       | W   | 0.256      | -            | -                | -                | -         |     1.20 | dare, dea, Peeping, shane, snav     |
|            6 |     3625 | 2024-03-12 | Party Astronauts | L   | 0.236      | -            | -                | -                | -         |    -4.46 | dare, dea, Peeping, shane, snav     |
|            5 |     3725 | 2024-03-08 | Spirit           | L   | 0.206      | -            | -                | -                | -         |    -0.04 | dare, MRC9, Peeping, shane, snav    |
|            4 |     3877 | 2024-03-02 | ODDIK            | L   | 0.168      | -            | -                | -                | -         |    -2.69 | dare, nbgee12, Peeping, shane, snav |
|            3 |     3905 | 2024-03-01 | Complexity       | L   | 0.161      | -            | -                | -                | -         |    -0.13 | dare, nbgee12, Peeping, shane, snav |
|            2 |     4294 | 2024-02-13 | Mythic           | L   | 0.050      | -            | -                | -                | -         |    -1.20 | dare, dea, Peeping, shane, snav     |
|            1 |     4297 | 2024-02-13 | Mythic           | W   | 0.049      | -            | -                | -                | -         |     0.36 | dare, dea, Peeping, shane, snav     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,708.41)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-23 |      0.923 | $3,000.00      | $2,768.40       |
| 2024-06-16 |      0.876 | $1,500.00      | $1,313.78       |
| 2024-06-09 |      0.829 | $4,250.00      | $3,522.29       |
| 2024-03-10 |      0.221 | $5,000.00      | $1,103.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
