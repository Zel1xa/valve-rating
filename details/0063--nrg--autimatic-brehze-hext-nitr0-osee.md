### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [18]( ../standings_americas.md)<br />
<br />
Final Rank Value:  989.3<br />
<br />
Final Rank Value (989.3) = Starting Rank Value (849.5) + Head To Head Adjustments (139.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.160[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 849.5
- 400 + ( ( 0.220 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 849.5


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
|           74 |      110 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.333 (0.159)    | 0 (0.000) |     8.15 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |      114 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.333 (0.159)    | 0 (0.000) |     8.74 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      158 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.48 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      162 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.91 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      451 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.40 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      455 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.057 (0.017)    | 0.548 (0.166)    | 0 (0.000) |    14.27 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      481 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.72 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      549 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.186)    | 0 (0.000) |     8.26 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      553 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.186)    | 0 (0.000) |     8.86 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      615 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.299 (0.143)    | 0 (0.000) |     7.47 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      620 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.299 (0.143)    | 0 (0.000) |     7.97 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      677 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.274 (0.131)    | 0 (0.000) |     5.58 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      682 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.89 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |      729 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.49 | autimatic, Brehze, HexT, nitr0, oSee |
|           60 |      732 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     8.00 | autimatic, Brehze, HexT, nitr0, oSee |
|           59 |     1190 | 2024-06-09 | M80              | W   | 0.828      | 0.143        | 0.188 (0.022)    | -                | -         |    22.52 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1262 | 2024-06-08 | Party Astronauts | W   | 0.821      | -            | -                | -                | -         |    15.74 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1308 | 2024-06-07 | Party Astronauts | L   | 0.815      | -            | -                | -                | -         |   -10.04 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1352 | 2024-06-06 | Party Astronauts | L   | 0.810      | -            | -                | -                | -         |   -11.18 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1361 | 2024-06-06 | Wildcard         | W   | 0.809      | 0.143        | 0.055 (0.006)    | -                | -         |    15.04 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1365 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.809      | -            | -                | -                | -         |     6.44 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1386 | 2024-06-06 | Wildcard         | L   | 0.808      | -            | -                | -                | -         |   -10.04 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1419 | 2024-06-05 | LAG              | W   | 0.804      | -            | -                | -                | -         |    10.46 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1433 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.802      | -            | -                | -                | -         |     6.79 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1470 | 2024-06-04 | Nouns            | L   | 0.797      | -            | -                | -                | -         |    -9.83 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1765 | 2024-05-23 | Nouns            | L   | 0.717      | -            | -                | -                | -         |    -9.47 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1781 | 2024-05-22 | Elevate          | L   | 0.710      | -            | -                | -                | -         |    -8.90 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1787 | 2024-05-22 | Elevate          | L   | 0.710      | -            | -                | -                | -         |    -9.46 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1810 | 2024-05-22 | Legacy           | W   | 0.708      | 0.384        | 0.122 (0.033)    | 0.643 (0.175)    | -         |    13.91 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1833 | 2024-05-21 | Perseverance     | L   | 0.704      | -            | -                | -                | -         |   -16.38 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1835 | 2024-05-21 | Perseverance     | W   | 0.703      | -            | -                | -                | -         |     5.69 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1866 | 2024-05-20 | M80              | L   | 0.697      | -            | -                | -                | -         |    -3.10 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1870 | 2024-05-20 | M80              | L   | 0.697      | -            | -                | -                | -         |    -3.19 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1929 | 2024-05-18 | Nouns            | L   | 0.683      | -            | -                | -                | -         |   -11.07 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1934 | 2024-05-18 | Party Astronauts | W   | 0.682      | 0.303        | 0.041 (0.008)    | -                | -         |    10.76 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     1968 | 2024-05-17 | BOSS             | W   | 0.676      | -            | -                | -                | -         |     6.69 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     2037 | 2024-05-15 | LAG              | W   | 0.664      | -            | -                | -                | -         |     7.62 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2044 | 2024-05-15 | LAG              | W   | 0.663      | -            | -                | -                | -         |     8.05 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2089 | 2024-05-14 | Take Flyte       | W   | 0.657      | -            | -                | -                | -         |     4.95 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2094 | 2024-05-14 | Take Flyte       | W   | 0.657      | -            | -                | -                | -         |     5.17 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2159 | 2024-05-12 | Perseverance     | W   | 0.643      | -            | -                | -                | -         |     6.29 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2161 | 2024-05-12 | Elevate          | W   | 0.642      | -            | -                | -                | -         |    12.78 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2189 | 2024-05-11 | Perseverance     | W   | 0.636      | -            | -                | -                | -         |     6.27 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2191 | 2024-05-11 | BOSS             | W   | 0.635      | -            | -                | -                | -         |     8.13 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2295 | 2024-05-06 | Party Astronauts | W   | 0.604      | 0.477        | 0.041 (0.012)    | 0.531 (0.153)    | -         |    11.77 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2296 | 2024-05-06 | Party Astronauts | L   | 0.603      | -            | -                | -                | -         |    -7.32 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2532 | 2024-04-25 | Wildcard         | L   | 0.530      | -            | -                | -                | -         |    -7.36 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2534 | 2024-04-25 | Wildcard         | W   | 0.530      | 0.477        | 0.055 (0.014)    | -                | -         |     9.58 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2770 | 2024-04-17 | Akimbo           | L   | 0.476      | -            | -                | -                | -         |    -9.75 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2829 | 2024-04-15 | Mythic           | W   | 0.463      | -            | -                | -                | -         |     5.26 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2830 | 2024-04-15 | Mythic           | W   | 0.463      | -            | -                | -                | -         |     5.46 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2917 | 2024-04-10 | BOSS             | W   | 0.430      | -            | -                | -                | -         |     6.15 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2921 | 2024-04-10 | BOSS             | L   | 0.430      | -            | -                | -                | -         |    -7.58 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     2975 | 2024-04-09 | Carpe Diem       | W   | 0.424      | -            | -                | -                | -         |     3.35 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     2978 | 2024-04-09 | Carpe Diem       | W   | 0.423      | -            | -                | -                | -         |     3.45 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3278 | 2024-03-27 | Nouns            | W   | 0.337      | 0.477        | 0.057 (0.009)    | -                | -         |     6.42 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3282 | 2024-03-27 | Nouns            | L   | 0.337      | -            | -                | -                | -         |    -4.27 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3330 | 2024-03-26 | MIGHT            | W   | 0.331      | -            | -                | -                | -         |     1.57 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3335 | 2024-03-26 | MIGHT            | W   | 0.330      | -            | -                | -                | -         |     1.60 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3501 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.257      | -            | -                | -                | -         |     3.13 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3503 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.257      | -            | -                | -                | -         |    -5.05 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3521 | 2024-03-14 | Limitless        | W   | 0.251      | -            | -                | -                | -         |     1.95 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3525 | 2024-03-14 | Limitless        | W   | 0.250      | -            | -                | -                | -         |     1.98 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3600 | 2024-03-12 | Carpe Diem       | L   | 0.237      | -            | -                | -                | -         |    -5.39 | autimatic, Brehze, HexT, oSee, Walco |
|           10 |     3855 | 2024-03-02 | MIBR             | L   | 0.168      | -            | -                | -                | -         |    -0.22 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3874 | 2024-03-01 | Imperial         | L   | 0.163      | -            | -                | -                | -         |    -0.47 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     3980 | 2024-02-24 | Wildcard         | L   | 0.124      | -            | -                | -                | -         |    -1.64 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     3982 | 2024-02-24 | Limitless        | W   | 0.123      | -            | -                | -                | -         |     0.97 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     3988 | 2024-02-24 | Mythic           | W   | 0.123      | -            | -                | -                | -         |     1.62 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     4024 | 2024-02-22 | Party Astronauts | L   | 0.110      | -            | -                | -                | -         |    -1.37 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4029 | 2024-02-22 | Wildcard         | W   | 0.110      | -            | -                | -                | -         |     2.01 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4077 | 2024-02-20 | Party Astronauts | L   | 0.097      | -            | -                | -                | -         |    -1.22 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4102 | 2024-02-19 | Party Astronauts | W   | 0.091      | -            | -                | -                | -         |     1.73 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4104 | 2024-02-19 | Mythic           | W   | 0.089      | -            | -                | -                | -         |     1.19 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,496.28)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.830 | $4,250.00      | $3,526.81       |
| 2024-05-18 |      0.683 | $1,000.00      | $683.36         |
| 2024-05-12 |      0.643 | $2,000.00      | $1,286.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
