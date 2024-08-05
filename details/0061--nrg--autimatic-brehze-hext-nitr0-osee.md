### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [61](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  990.8<br />
<br />
Final Rank Value (990.8) = Starting Rank Value (850.5) + Head To Head Adjustments (140.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.348[<sup>2</sup>](#table1)
- Opponent Network: 0.163[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.5
- 400 + ( ( 0.220 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 850.5


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
|           75 |       30 | 2024-08-03 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.76 | autimatic, Brehze, HexT, nitr0, oSee |
|           74 |      138 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.332 (0.158)    | 0 (0.000) |     8.30 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |      142 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.332 (0.158)    | 0 (0.000) |     8.90 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      186 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.50 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      190 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.93 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      479 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -20.09 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      483 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.057 (0.017)    | 0.561 (0.170)    | 0 (0.000) |    14.40 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      509 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.72 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      577 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.390 (0.186)    | 0 (0.000) |     8.36 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      581 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.390 (0.186)    | 0 (0.000) |     8.97 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      643 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.299 (0.142)    | 0 (0.000) |     7.48 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      648 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.99 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      705 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.314 (0.150)    | 0 (0.000) |     5.73 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      710 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.314 (0.150)    | -         |     6.05 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |      757 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.50 | autimatic, Brehze, HexT, nitr0, oSee |
|           60 |      760 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     8.01 | autimatic, Brehze, HexT, nitr0, oSee |
|           59 |     1218 | 2024-06-09 | M80              | W   | 0.824      | 0.143        | 0.188 (0.022)    | -                | -         |    22.42 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1290 | 2024-06-08 | Party Astronauts | W   | 0.818      | -            | -                | -                | -         |    15.69 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1336 | 2024-06-07 | Party Astronauts | L   | 0.812      | -            | -                | -                | -         |    -9.99 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1380 | 2024-06-06 | Party Astronauts | L   | 0.807      | -            | -                | -                | -         |   -11.13 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1389 | 2024-06-06 | Wildcard         | W   | 0.806      | 0.143        | 0.048 (0.006)    | -                | -         |    14.16 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1393 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.805      | -            | -                | -                | -         |     6.57 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1414 | 2024-06-06 | Wildcard         | L   | 0.804      | -            | -                | -                | -         |   -10.88 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1447 | 2024-06-05 | LAG              | W   | 0.800      | -            | -                | -                | -         |    10.14 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1461 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.798      | -            | -                | -                | -         |     6.90 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1498 | 2024-06-04 | Nouns            | L   | 0.794      | -            | -                | -                | -         |    -9.60 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1793 | 2024-05-23 | Nouns            | L   | 0.713      | -            | -                | -                | -         |    -9.22 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1809 | 2024-05-22 | Elevate          | L   | 0.707      | -            | -                | -                | -         |    -8.81 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1815 | 2024-05-22 | Elevate          | L   | 0.707      | -            | -                | -                | -         |    -9.36 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1838 | 2024-05-22 | Legacy           | W   | 0.704      | 0.384        | 0.122 (0.033)    | 0.644 (0.174)    | -         |    13.88 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1861 | 2024-05-21 | Phoenix          | L   | 0.700      | -            | -                | -                | -         |   -16.27 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1863 | 2024-05-21 | Phoenix          | W   | 0.700      | -            | -                | -                | -         |     5.69 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1894 | 2024-05-20 | M80              | L   | 0.694      | -            | -                | -                | -         |    -3.08 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1898 | 2024-05-20 | M80              | L   | 0.693      | -            | -                | -                | -         |    -3.18 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1957 | 2024-05-18 | Nouns            | L   | 0.680      | -            | -                | -                | -         |   -10.78 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1962 | 2024-05-18 | Party Astronauts | W   | 0.678      | 0.303        | 0.041 (0.008)    | -                | -         |    10.70 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     1996 | 2024-05-17 | BOSS             | W   | 0.672      | -            | -                | -                | -         |     6.68 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     2065 | 2024-05-15 | LAG              | W   | 0.660      | -            | -                | -                | -         |     7.38 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2072 | 2024-05-15 | LAG              | W   | 0.660      | -            | -                | -                | -         |     7.79 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2117 | 2024-05-14 | Take Flyte       | W   | 0.654      | -            | -                | -                | -         |     4.98 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2122 | 2024-05-14 | Take Flyte       | W   | 0.653      | -            | -                | -                | -         |     5.20 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2187 | 2024-05-12 | Phoenix          | W   | 0.640      | -            | -                | -                | -         |     6.28 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2189 | 2024-05-12 | Elevate          | W   | 0.639      | -            | -                | -                | -         |    12.76 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2217 | 2024-05-11 | Phoenix          | W   | 0.632      | -            | -                | -                | -         |     6.26 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2219 | 2024-05-11 | BOSS             | W   | 0.632      | -            | -                | -                | -         |     8.13 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2323 | 2024-05-06 | Party Astronauts | W   | 0.600      | 0.477        | 0.041 (0.012)    | 0.531 (0.152)    | -         |    11.67 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2324 | 2024-05-06 | Party Astronauts | L   | 0.600      | -            | -                | -                | -         |    -7.32 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2560 | 2024-04-25 | Wildcard         | L   | 0.527      | -            | -                | -                | -         |    -8.01 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2562 | 2024-04-25 | Wildcard         | W   | 0.527      | 0.477        | 0.048 (0.012)    | -                | -         |     8.79 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2798 | 2024-04-17 | Akimbo           | L   | 0.473      | -            | -                | -                | -         |    -9.67 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2857 | 2024-04-15 | Mythic           | W   | 0.460      | -            | -                | -                | -         |     5.21 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2858 | 2024-04-15 | Mythic           | W   | 0.460      | -            | -                | -                | -         |     5.41 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2945 | 2024-04-10 | BOSS             | W   | 0.427      | -            | -                | -                | -         |     6.10 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2949 | 2024-04-10 | BOSS             | L   | 0.427      | -            | -                | -                | -         |    -7.51 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     3003 | 2024-04-09 | Carpe Diem       | W   | 0.420      | -            | -                | -                | -         |     3.32 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     3006 | 2024-04-09 | Carpe Diem       | W   | 0.420      | -            | -                | -                | -         |     3.41 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3306 | 2024-03-27 | Nouns            | W   | 0.334      | 0.477        | 0.057 (0.009)    | -                | -         |     6.35 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3310 | 2024-03-27 | Nouns            | L   | 0.334      | -            | -                | -                | -         |    -4.24 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3358 | 2024-03-26 | MIGHT            | W   | 0.327      | -            | -                | -                | -         |     1.55 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3363 | 2024-03-26 | MIGHT            | W   | 0.327      | -            | -                | -                | -         |     1.57 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3529 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.254      | -            | -                | -                | -         |     3.08 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3531 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.254      | -            | -                | -                | -         |    -5.00 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3549 | 2024-03-14 | Limitless        | W   | 0.247      | -            | -                | -                | -         |     1.92 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3553 | 2024-03-14 | Limitless        | W   | 0.247      | -            | -                | -                | -         |     1.95 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3628 | 2024-03-12 | Carpe Diem       | L   | 0.233      | -            | -                | -                | -         |    -5.32 | autimatic, Brehze, HexT, oSee, Walco |
|           10 |     3883 | 2024-03-02 | MIBR             | L   | 0.165      | -            | -                | -                | -         |    -0.21 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3902 | 2024-03-01 | Imperial         | L   | 0.159      | -            | -                | -                | -         |    -0.46 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     4008 | 2024-02-24 | Wildcard         | L   | 0.120      | -            | -                | -                | -         |    -1.77 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     4010 | 2024-02-24 | Limitless        | W   | 0.120      | -            | -                | -                | -         |     0.94 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     4016 | 2024-02-24 | Mythic           | W   | 0.119      | -            | -                | -                | -         |     1.58 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     4052 | 2024-02-22 | Party Astronauts | L   | 0.106      | -            | -                | -                | -         |    -1.33 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4057 | 2024-02-22 | Wildcard         | W   | 0.106      | -            | -                | -                | -         |     1.78 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4105 | 2024-02-20 | Party Astronauts | L   | 0.094      | -            | -                | -                | -         |    -1.18 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4130 | 2024-02-19 | Party Astronauts | W   | 0.087      | -            | -                | -                | -         |     1.65 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4132 | 2024-02-19 | Mythic           | W   | 0.086      | -            | -                | -                | -         |     1.15 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,471.27)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.826 | $4,250.00      | $3,512.15       |
| 2024-05-18 |      0.680 | $1,000.00      | $679.91         |
| 2024-05-12 |      0.640 | $2,000.00      | $1,279.21       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
