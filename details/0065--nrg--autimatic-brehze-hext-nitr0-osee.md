### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  990.0<br />
<br />
Final Rank Value (990.0) = Starting Rank Value (850.0) + Head To Head Adjustments (140.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.160[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.219<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.0
- 400 + ( ( 0.219 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 850.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           75 |       51 | 2024-08-03 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.77 | autimatic, Brehze, HexT, nitr0, oSee |
|           74 |      159 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.327 (0.156)    | 0 (0.000) |     8.31 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |      163 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.327 (0.156)    | 0 (0.000) |     8.91 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      207 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.50 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      211 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.93 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      500 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -20.06 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      504 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.057 (0.017)    | 0.553 (0.167)    | 0 (0.000) |    14.39 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      530 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.73 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      598 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.384 (0.183)    | 0 (0.000) |     8.38 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      602 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.384 (0.183)    | 0 (0.000) |     8.99 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      664 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.293 (0.140)    | 0 (0.000) |     7.49 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      669 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.00 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      726 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.310 (0.148)    | 0 (0.000) |     5.76 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      731 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.310 (0.148)    | -         |     6.08 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |      778 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.52 | autimatic, Brehze, HexT, nitr0, oSee |
|           60 |      781 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     8.03 | autimatic, Brehze, HexT, nitr0, oSee |
|           59 |     1239 | 2024-06-09 | M80              | W   | 0.820      | 0.143        | 0.188 (0.022)    | -                | -         |    22.30 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1311 | 2024-06-08 | Party Astronauts | W   | 0.813      | -            | -                | -                | -         |    15.60 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1357 | 2024-06-07 | Party Astronauts | L   | 0.807      | -            | -                | -                | -         |    -9.95 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1401 | 2024-06-06 | Party Astronauts | L   | 0.802      | -            | -                | -                | -         |   -11.08 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1410 | 2024-06-06 | Wildcard         | W   | 0.801      | 0.143        | 0.048 (0.005)    | -                | -         |    14.07 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1414 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.801      | -            | -                | -                | -         |     6.55 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1435 | 2024-06-06 | Wildcard         | L   | 0.800      | -            | -                | -                | -         |   -10.84 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1468 | 2024-06-05 | LAG              | W   | 0.796      | -            | -                | -                | -         |    10.09 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1482 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.794      | -            | -                | -                | -         |     6.88 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1519 | 2024-06-04 | Nouns            | L   | 0.789      | -            | -                | -                | -         |    -9.55 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1814 | 2024-05-23 | Nouns            | L   | 0.709      | -            | -                | -                | -         |    -9.17 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1830 | 2024-05-22 | Elevate          | L   | 0.703      | -            | -                | -                | -         |    -8.74 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1836 | 2024-05-22 | Elevate          | L   | 0.702      | -            | -                | -                | -         |    -9.28 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1859 | 2024-05-22 | Legacy           | W   | 0.700      | 0.384        | 0.122 (0.033)    | 0.635 (0.171)    | -         |    13.77 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1882 | 2024-05-21 | Phoenix          | L   | 0.696      | -            | -                | -                | -         |   -16.16 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1884 | 2024-05-21 | Phoenix          | W   | 0.696      | -            | -                | -                | -         |     5.67 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1915 | 2024-05-20 | M80              | L   | 0.689      | -            | -                | -                | -         |    -3.07 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1919 | 2024-05-20 | M80              | L   | 0.689      | -            | -                | -                | -         |    -3.16 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1978 | 2024-05-18 | Nouns            | L   | 0.675      | -            | -                | -                | -         |   -10.71 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1983 | 2024-05-18 | Party Astronauts | W   | 0.674      | 0.303        | 0.041 (0.008)    | -                | -         |    10.64 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     2017 | 2024-05-17 | BOSS             | W   | 0.668      | -            | -                | -                | -         |     6.65 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     2086 | 2024-05-15 | LAG              | W   | 0.656      | -            | -                | -                | -         |     7.34 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2093 | 2024-05-15 | LAG              | W   | 0.656      | -            | -                | -                | -         |     7.74 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2138 | 2024-05-14 | Take Flyte       | W   | 0.649      | -            | -                | -                | -         |     4.96 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2143 | 2024-05-14 | Take Flyte       | W   | 0.649      | -            | -                | -                | -         |     5.18 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2208 | 2024-05-12 | Phoenix          | W   | 0.635      | -            | -                | -                | -         |     6.25 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2210 | 2024-05-12 | Elevate          | W   | 0.635      | -            | -                | -                | -         |    12.68 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2238 | 2024-05-11 | Phoenix          | W   | 0.628      | -            | -                | -                | -         |     6.23 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2240 | 2024-05-11 | BOSS             | W   | 0.627      | -            | -                | -                | -         |     8.07 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2344 | 2024-05-06 | Party Astronauts | W   | 0.596      | 0.477        | 0.041 (0.012)    | 0.523 (0.149)    | -         |    11.57 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2345 | 2024-05-06 | Party Astronauts | L   | 0.596      | -            | -                | -                | -         |    -7.27 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2581 | 2024-04-25 | Wildcard         | L   | 0.522      | -            | -                | -                | -         |    -7.95 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2583 | 2024-04-25 | Wildcard         | W   | 0.522      | 0.477        | 0.048 (0.012)    | -                | -         |     8.71 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2819 | 2024-04-17 | Akimbo           | L   | 0.468      | -            | -                | -                | -         |    -9.57 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2878 | 2024-04-15 | Mythic           | W   | 0.456      | -            | -                | -                | -         |     5.17 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2879 | 2024-04-15 | Mythic           | W   | 0.455      | -            | -                | -                | -         |     5.37 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2966 | 2024-04-10 | BOSS             | W   | 0.422      | -            | -                | -                | -         |     6.03 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2970 | 2024-04-10 | BOSS             | L   | 0.422      | -            | -                | -                | -         |    -7.44 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     3024 | 2024-04-09 | Carpe Diem       | W   | 0.416      | -            | -                | -                | -         |     3.29 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     3027 | 2024-04-09 | Carpe Diem       | W   | 0.416      | -            | -                | -                | -         |     3.39 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3327 | 2024-03-27 | Nouns            | W   | 0.329      | 0.477        | 0.057 (0.009)    | -                | -         |     6.25 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3331 | 2024-03-27 | Nouns            | L   | 0.329      | -            | -                | -                | -         |    -4.19 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3379 | 2024-03-26 | MIGHT            | W   | 0.323      | -            | -                | -                | -         |     1.53 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3384 | 2024-03-26 | MIGHT            | W   | 0.323      | -            | -                | -                | -         |     1.55 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3550 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.249      | -            | -                | -                | -         |     3.03 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3552 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.249      | -            | -                | -                | -         |    -4.91 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3570 | 2024-03-14 | Limitless        | W   | 0.243      | -            | -                | -                | -         |     1.89 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3574 | 2024-03-14 | Limitless        | W   | 0.242      | -            | -                | -                | -         |     1.92 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3649 | 2024-03-12 | Carpe Diem       | L   | 0.229      | -            | -                | -                | -         |    -5.21 | autimatic, Brehze, HexT, oSee, Walco |
|           10 |     3904 | 2024-03-02 | MIBR             | L   | 0.160      | -            | -                | -                | -         |    -0.21 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3923 | 2024-03-01 | Imperial         | L   | 0.155      | -            | -                | -                | -         |    -0.46 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     4029 | 2024-02-24 | Wildcard         | L   | 0.116      | -            | -                | -                | -         |    -1.71 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     4031 | 2024-02-24 | Limitless        | W   | 0.115      | -            | -                | -                | -         |     0.91 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     4037 | 2024-02-24 | Mythic           | W   | 0.115      | -            | -                | -                | -         |     1.52 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     4073 | 2024-02-22 | Party Astronauts | L   | 0.102      | -            | -                | -                | -         |    -1.28 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4078 | 2024-02-22 | Wildcard         | W   | 0.102      | -            | -                | -                | -         |     1.71 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4126 | 2024-02-20 | Party Astronauts | L   | 0.089      | -            | -                | -                | -         |    -1.13 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4151 | 2024-02-19 | Party Astronauts | W   | 0.083      | -            | -                | -                | -         |     1.57 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4153 | 2024-02-19 | Mythic           | W   | 0.082      | -            | -                | -                | -         |     1.08 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,439.05)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.822 | $4,250.00      | $3,493.26       |
| 2024-05-18 |      0.675 | $1,000.00      | $675.46         |
| 2024-05-12 |      0.635 | $2,000.00      | $1,270.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
