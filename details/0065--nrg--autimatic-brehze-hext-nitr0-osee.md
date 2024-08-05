### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  989.9<br />
<br />
Final Rank Value (989.9) = Starting Rank Value (850.0) + Head To Head Adjustments (139.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
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
|           75 |       52 | 2024-08-03 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.77 | autimatic, Brehze, HexT, nitr0, oSee |
|           74 |      160 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.327 (0.156)    | 0 (0.000) |     8.31 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |      164 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.327 (0.156)    | 0 (0.000) |     8.91 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      208 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.50 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      212 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.93 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      501 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -20.06 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      505 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.057 (0.017)    | 0.553 (0.167)    | 0 (0.000) |    14.39 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      531 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.73 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      599 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.384 (0.183)    | 0 (0.000) |     8.38 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      603 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.384 (0.183)    | 0 (0.000) |     8.99 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      665 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.293 (0.140)    | 0 (0.000) |     7.49 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      670 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.00 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      727 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.310 (0.148)    | 0 (0.000) |     5.76 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      732 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.310 (0.148)    | -         |     6.08 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |      779 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.52 | autimatic, Brehze, HexT, nitr0, oSee |
|           60 |      782 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     8.03 | autimatic, Brehze, HexT, nitr0, oSee |
|           59 |     1240 | 2024-06-09 | M80              | W   | 0.820      | 0.143        | 0.188 (0.022)    | -                | -         |    22.28 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1312 | 2024-06-08 | Party Astronauts | W   | 0.813      | -            | -                | -                | -         |    15.59 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1358 | 2024-06-07 | Party Astronauts | L   | 0.807      | -            | -                | -                | -         |    -9.94 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1402 | 2024-06-06 | Party Astronauts | L   | 0.802      | -            | -                | -                | -         |   -11.07 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1411 | 2024-06-06 | Wildcard         | W   | 0.801      | 0.143        | 0.048 (0.005)    | -                | -         |    14.06 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1415 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.801      | -            | -                | -                | -         |     6.55 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1436 | 2024-06-06 | Wildcard         | L   | 0.800      | -            | -                | -                | -         |   -10.84 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1469 | 2024-06-05 | LAG              | W   | 0.795      | -            | -                | -                | -         |    10.09 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1483 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.793      | -            | -                | -                | -         |     6.88 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1520 | 2024-06-04 | Nouns            | L   | 0.789      | -            | -                | -                | -         |    -9.55 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1815 | 2024-05-23 | Nouns            | L   | 0.708      | -            | -                | -                | -         |    -9.17 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1831 | 2024-05-22 | Elevate          | L   | 0.702      | -            | -                | -                | -         |    -8.74 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1837 | 2024-05-22 | Elevate          | L   | 0.702      | -            | -                | -                | -         |    -9.28 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1860 | 2024-05-22 | Legacy           | W   | 0.700      | 0.384        | 0.122 (0.033)    | 0.635 (0.171)    | -         |    13.76 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1883 | 2024-05-21 | Phoenix          | L   | 0.695      | -            | -                | -                | -         |   -16.15 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1885 | 2024-05-21 | Phoenix          | W   | 0.695      | -            | -                | -                | -         |     5.67 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1916 | 2024-05-20 | M80              | L   | 0.689      | -            | -                | -                | -         |    -3.06 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1920 | 2024-05-20 | M80              | L   | 0.688      | -            | -                | -                | -         |    -3.16 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1979 | 2024-05-18 | Nouns            | L   | 0.675      | -            | -                | -                | -         |   -10.70 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1984 | 2024-05-18 | Party Astronauts | W   | 0.673      | 0.303        | 0.041 (0.008)    | -                | -         |    10.63 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     2018 | 2024-05-17 | BOSS             | W   | 0.668      | -            | -                | -                | -         |     6.64 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     2087 | 2024-05-15 | LAG              | W   | 0.655      | -            | -                | -                | -         |     7.33 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2094 | 2024-05-15 | LAG              | W   | 0.655      | -            | -                | -                | -         |     7.74 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2139 | 2024-05-14 | Take Flyte       | W   | 0.649      | -            | -                | -                | -         |     4.96 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2144 | 2024-05-14 | Take Flyte       | W   | 0.648      | -            | -                | -                | -         |     5.18 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2209 | 2024-05-12 | Phoenix          | W   | 0.635      | -            | -                | -                | -         |     6.24 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2211 | 2024-05-12 | Elevate          | W   | 0.634      | -            | -                | -                | -         |    12.67 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2239 | 2024-05-11 | Phoenix          | W   | 0.627      | -            | -                | -                | -         |     6.22 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2241 | 2024-05-11 | BOSS             | W   | 0.627      | -            | -                | -                | -         |     8.07 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2345 | 2024-05-06 | Party Astronauts | W   | 0.595      | 0.477        | 0.041 (0.012)    | 0.523 (0.148)    | -         |    11.57 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2346 | 2024-05-06 | Party Astronauts | L   | 0.595      | -            | -                | -                | -         |    -7.27 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2582 | 2024-04-25 | Wildcard         | L   | 0.522      | -            | -                | -                | -         |    -7.94 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2584 | 2024-04-25 | Wildcard         | W   | 0.522      | 0.477        | 0.048 (0.012)    | -                | -         |     8.70 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2820 | 2024-04-17 | Akimbo           | L   | 0.468      | -            | -                | -                | -         |    -9.56 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2879 | 2024-04-15 | Mythic           | W   | 0.455      | -            | -                | -                | -         |     5.17 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2880 | 2024-04-15 | Mythic           | W   | 0.455      | -            | -                | -                | -         |     5.36 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2967 | 2024-04-10 | BOSS             | W   | 0.422      | -            | -                | -                | -         |     6.03 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2971 | 2024-04-10 | BOSS             | L   | 0.422      | -            | -                | -                | -         |    -7.43 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     3025 | 2024-04-09 | Carpe Diem       | W   | 0.415      | -            | -                | -                | -         |     3.29 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     3028 | 2024-04-09 | Carpe Diem       | W   | 0.415      | -            | -                | -                | -         |     3.38 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3328 | 2024-03-27 | Nouns            | W   | 0.329      | 0.477        | 0.057 (0.009)    | -                | -         |     6.25 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3332 | 2024-03-27 | Nouns            | L   | 0.329      | -            | -                | -                | -         |    -4.18 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3380 | 2024-03-26 | MIGHT            | W   | 0.322      | -            | -                | -                | -         |     1.53 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3385 | 2024-03-26 | MIGHT            | W   | 0.322      | -            | -                | -                | -         |     1.55 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3551 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.249      | -            | -                | -                | -         |     3.02 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3553 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.249      | -            | -                | -                | -         |    -4.90 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3571 | 2024-03-14 | Limitless        | W   | 0.242      | -            | -                | -                | -         |     1.89 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3575 | 2024-03-14 | Limitless        | W   | 0.242      | -            | -                | -                | -         |     1.91 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3650 | 2024-03-12 | Carpe Diem       | L   | 0.229      | -            | -                | -                | -         |    -5.20 | autimatic, Brehze, HexT, oSee, Walco |
|           10 |     3905 | 2024-03-02 | MIBR             | L   | 0.160      | -            | -                | -                | -         |    -0.21 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3924 | 2024-03-01 | Imperial         | L   | 0.154      | -            | -                | -                | -         |    -0.45 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     4030 | 2024-02-24 | Wildcard         | L   | 0.115      | -            | -                | -                | -         |    -1.70 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     4032 | 2024-02-24 | Limitless        | W   | 0.115      | -            | -                | -                | -         |     0.91 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     4038 | 2024-02-24 | Mythic           | W   | 0.115      | -            | -                | -                | -         |     1.51 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     4074 | 2024-02-22 | Party Astronauts | L   | 0.102      | -            | -                | -                | -         |    -1.28 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4079 | 2024-02-22 | Wildcard         | W   | 0.101      | -            | -                | -                | -         |     1.70 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4127 | 2024-02-20 | Party Astronauts | L   | 0.089      | -            | -                | -                | -         |    -1.12 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4152 | 2024-02-19 | Party Astronauts | W   | 0.082      | -            | -                | -                | -         |     1.56 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4154 | 2024-02-19 | Mythic           | W   | 0.081      | -            | -                | -                | -         |     1.08 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,436.03)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.822 | $4,250.00      | $3,491.49       |
| 2024-05-18 |      0.675 | $1,000.00      | $675.05         |
| 2024-05-12 |      0.635 | $2,000.00      | $1,269.49       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
