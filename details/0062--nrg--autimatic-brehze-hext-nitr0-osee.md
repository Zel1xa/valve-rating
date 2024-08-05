### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  990.4<br />
<br />
Final Rank Value (990.4) = Starting Rank Value (850.4) + Head To Head Adjustments (139.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.4
- 400 + ( ( 0.220 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 850.4


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
|           75 |       43 | 2024-08-03 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.77 | autimatic, Brehze, HexT, nitr0, oSee |
|           74 |      151 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.331 (0.158)    | 0 (0.000) |     8.30 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |      155 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.331 (0.158)    | 0 (0.000) |     8.91 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      199 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.50 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      203 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.93 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      492 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -20.07 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      496 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.057 (0.017)    | 0.560 (0.170)    | 0 (0.000) |    14.40 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      522 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.73 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      590 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.185)    | 0 (0.000) |     8.37 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      594 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.185)    | 0 (0.000) |     8.98 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      656 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.297 (0.142)    | 0 (0.000) |     7.49 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      661 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.99 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      718 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.314 (0.150)    | 0 (0.000) |     5.75 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      723 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.314 (0.150)    | -         |     6.07 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |      770 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.51 | autimatic, Brehze, HexT, nitr0, oSee |
|           60 |      773 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     8.02 | autimatic, Brehze, HexT, nitr0, oSee |
|           59 |     1231 | 2024-06-09 | M80              | W   | 0.821      | 0.143        | 0.188 (0.022)    | -                | -         |    22.33 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1303 | 2024-06-08 | Party Astronauts | W   | 0.814      | -            | -                | -                | -         |    15.62 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1349 | 2024-06-07 | Party Astronauts | L   | 0.808      | -            | -                | -                | -         |    -9.96 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1393 | 2024-06-06 | Party Astronauts | L   | 0.803      | -            | -                | -                | -         |   -11.09 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1402 | 2024-06-06 | Wildcard         | W   | 0.802      | 0.143        | 0.048 (0.005)    | -                | -         |    14.09 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1406 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.802      | -            | -                | -                | -         |     6.55 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1427 | 2024-06-06 | Wildcard         | L   | 0.801      | -            | -                | -                | -         |   -10.85 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1460 | 2024-06-05 | LAG              | W   | 0.797      | -            | -                | -                | -         |    10.10 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1474 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.795      | -            | -                | -                | -         |     6.88 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1511 | 2024-06-04 | Nouns            | L   | 0.790      | -            | -                | -                | -         |    -9.56 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1806 | 2024-05-23 | Nouns            | L   | 0.710      | -            | -                | -                | -         |    -9.19 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1822 | 2024-05-22 | Elevate          | L   | 0.704      | -            | -                | -                | -         |    -8.76 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1828 | 2024-05-22 | Elevate          | L   | 0.703      | -            | -                | -                | -         |    -9.30 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1851 | 2024-05-22 | Legacy           | W   | 0.701      | 0.384        | 0.122 (0.033)    | 0.642 (0.173)    | -         |    13.80 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1874 | 2024-05-21 | Phoenix          | L   | 0.697      | -            | -                | -                | -         |   -16.19 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1876 | 2024-05-21 | Phoenix          | W   | 0.697      | -            | -                | -                | -         |     5.67 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1907 | 2024-05-20 | M80              | L   | 0.690      | -            | -                | -                | -         |    -3.07 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1911 | 2024-05-20 | M80              | L   | 0.690      | -            | -                | -                | -         |    -3.16 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1970 | 2024-05-18 | Nouns            | L   | 0.677      | -            | -                | -                | -         |   -10.72 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1975 | 2024-05-18 | Party Astronauts | W   | 0.675      | 0.303        | 0.041 (0.008)    | -                | -         |    10.65 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     2009 | 2024-05-17 | BOSS             | W   | 0.669      | -            | -                | -                | -         |     6.65 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     2078 | 2024-05-15 | LAG              | W   | 0.657      | -            | -                | -                | -         |     7.34 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2085 | 2024-05-15 | LAG              | W   | 0.657      | -            | -                | -                | -         |     7.75 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2130 | 2024-05-14 | Take Flyte       | W   | 0.650      | -            | -                | -                | -         |     4.96 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2135 | 2024-05-14 | Take Flyte       | W   | 0.650      | -            | -                | -                | -         |     5.18 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2200 | 2024-05-12 | Phoenix          | W   | 0.636      | -            | -                | -                | -         |     6.25 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2202 | 2024-05-12 | Elevate          | W   | 0.636      | -            | -                | -                | -         |    12.69 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2230 | 2024-05-11 | Phoenix          | W   | 0.629      | -            | -                | -                | -         |     6.23 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2232 | 2024-05-11 | BOSS             | W   | 0.628      | -            | -                | -                | -         |     8.09 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2336 | 2024-05-06 | Party Astronauts | W   | 0.597      | 0.477        | 0.041 (0.012)    | 0.529 (0.151)    | -         |    11.60 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2337 | 2024-05-06 | Party Astronauts | L   | 0.597      | -            | -                | -                | -         |    -7.28 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2573 | 2024-04-25 | Wildcard         | L   | 0.524      | -            | -                | -                | -         |    -7.96 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2575 | 2024-04-25 | Wildcard         | W   | 0.523      | 0.477        | 0.048 (0.012)    | -                | -         |     8.73 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2811 | 2024-04-17 | Akimbo           | L   | 0.469      | -            | -                | -                | -         |    -9.60 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2870 | 2024-04-15 | Mythic           | W   | 0.457      | -            | -                | -                | -         |     5.18 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2871 | 2024-04-15 | Mythic           | W   | 0.456      | -            | -                | -                | -         |     5.38 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2958 | 2024-04-10 | BOSS             | W   | 0.424      | -            | -                | -                | -         |     6.05 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2962 | 2024-04-10 | BOSS             | L   | 0.423      | -            | -                | -                | -         |    -7.46 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     3016 | 2024-04-09 | Carpe Diem       | W   | 0.417      | -            | -                | -                | -         |     3.29 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     3019 | 2024-04-09 | Carpe Diem       | W   | 0.417      | -            | -                | -                | -         |     3.39 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3319 | 2024-03-27 | Nouns            | W   | 0.331      | 0.477        | 0.057 (0.009)    | -                | -         |     6.28 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3323 | 2024-03-27 | Nouns            | L   | 0.330      | -            | -                | -                | -         |    -4.20 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3371 | 2024-03-26 | MIGHT            | W   | 0.324      | -            | -                | -                | -         |     1.53 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3376 | 2024-03-26 | MIGHT            | W   | 0.324      | -            | -                | -                | -         |     1.56 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3542 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.251      | -            | -                | -                | -         |     3.03 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3544 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.250      | -            | -                | -                | -         |    -4.94 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3562 | 2024-03-14 | Limitless        | W   | 0.244      | -            | -                | -                | -         |     1.89 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3566 | 2024-03-14 | Limitless        | W   | 0.244      | -            | -                | -                | -         |     1.92 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3641 | 2024-03-12 | Carpe Diem       | L   | 0.230      | -            | -                | -                | -         |    -5.24 | autimatic, Brehze, HexT, oSee, Walco |
|           10 |     3896 | 2024-03-02 | MIBR             | L   | 0.161      | -            | -                | -                | -         |    -0.21 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3915 | 2024-03-01 | Imperial         | L   | 0.156      | -            | -                | -                | -         |    -0.46 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     4021 | 2024-02-24 | Wildcard         | L   | 0.117      | -            | -                | -                | -         |    -1.72 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     4023 | 2024-02-24 | Limitless        | W   | 0.116      | -            | -                | -                | -         |     0.92 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     4029 | 2024-02-24 | Mythic           | W   | 0.116      | -            | -                | -                | -         |     1.53 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     4065 | 2024-02-22 | Party Astronauts | L   | 0.103      | -            | -                | -                | -         |    -1.29 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4070 | 2024-02-22 | Wildcard         | W   | 0.103      | -            | -                | -                | -         |     1.73 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4118 | 2024-02-20 | Party Astronauts | L   | 0.090      | -            | -                | -                | -         |    -1.14 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4143 | 2024-02-19 | Party Astronauts | W   | 0.084      | -            | -                | -                | -         |     1.59 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4145 | 2024-02-19 | Mythic           | W   | 0.083      | -            | -                | -                | -         |     1.10 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,447.11)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.823 | $4,250.00      | $3,497.99       |
| 2024-05-18 |      0.677 | $1,000.00      | $676.57         |
| 2024-05-12 |      0.636 | $2,000.00      | $1,272.55       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
