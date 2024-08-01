### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [18]( ../standings_americas.md)<br />
<br />
Final Rank Value:  999.6<br />
<br />
Final Rank Value (999.6) = Starting Rank Value (853.8) + Head To Head Adjustments (145.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.350[<sup>2</sup>](#table1)
- Opponent Network: 0.161[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.221<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 853.8
- 400 + ( ( 0.221 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 853.8


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
|           76 |       20 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.334 (0.159)    | 0 (0.000) |     8.27 | autimatic, Brehze, HexT, nitr0, oSee |
|           75 |       24 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.334 (0.159)    | 0 (0.000) |     8.87 | autimatic, Brehze, HexT, nitr0, oSee |
|           74 |       68 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.51 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |       72 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.94 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      362 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.45 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      366 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.058 (0.018)    | 0.557 (0.169)    | 0 (0.000) |    14.52 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      393 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.87 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      464 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     7.95 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      469 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     8.51 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      534 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.92 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      539 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.36 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      596 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.305 (0.145)    | 0 (0.000) |     5.54 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      601 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.305 (0.145)    | 0 (0.000) |     5.84 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      653 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.33 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      657 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.82 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |     1108 | 2024-06-09 | M80              | W   | 0.846      | 0.143        | 0.190 (0.023)    | -                | -         |    23.08 | autimatic, Brehze, HexT, oSee, Walco |
|           60 |     1182 | 2024-06-08 | Party Astronauts | W   | 0.840      | -            | -                | -                | -         |    16.03 | autimatic, Brehze, HexT, oSee, Walco |
|           59 |     1235 | 2024-06-07 | Party Astronauts | L   | 0.833      | -            | -                | -                | -         |   -10.31 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1280 | 2024-06-06 | Party Astronauts | L   | 0.829      | -            | -                | -                | -         |   -11.52 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1290 | 2024-06-06 | Wildcard         | W   | 0.828      | 0.143        | 0.055 (0.007)    | -                | -         |    15.30 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1294 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.827      | -            | -                | -                | -         |     6.35 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1315 | 2024-06-06 | Wildcard         | L   | 0.826      | -            | -                | -                | -         |   -10.35 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1349 | 2024-06-05 | LAG              | W   | 0.822      | 0.477        | -                | 0.371 (0.145)    | -         |    10.88 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1364 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.820      | -            | -                | -                | -         |     6.70 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1402 | 2024-06-04 | Nouns            | L   | 0.816      | -            | -                | -                | -         |   -10.13 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1700 | 2024-05-23 | Nouns            | L   | 0.735      | -            | -                | -                | -         |    -9.80 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1716 | 2024-05-22 | Elevate          | L   | 0.729      | -            | -                | -                | -         |    -9.22 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1722 | 2024-05-22 | Elevate          | L   | 0.729      | -            | -                | -                | -         |    -9.81 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1745 | 2024-05-22 | Legacy           | W   | 0.726      | 0.384        | 0.119 (0.033)    | 0.562 (0.157)    | -         |    14.15 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1778 | 2024-05-21 | Perseverance     | L   | 0.722      | -            | -                | -                | -         |   -17.10 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1781 | 2024-05-21 | Perseverance     | W   | 0.722      | -            | -                | -                | -         |     5.53 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1817 | 2024-05-20 | M80              | L   | 0.716      | -            | -                | -                | -         |    -3.14 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1821 | 2024-05-20 | M80              | L   | 0.715      | -            | -                | -                | -         |    -3.23 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1860 | 2024-05-19 | Perseverance     | W   | 0.708      | -            | -                | -                | -         |     5.58 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1889 | 2024-05-18 | Nouns            | L   | 0.702      | -            | -                | -                | -         |   -11.36 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1894 | 2024-05-18 | Party Astronauts | W   | 0.700      | 0.303        | 0.042 (0.009)    | -                | -         |    11.06 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1929 | 2024-05-17 | BOSS             | W   | 0.694      | -            | -                | -                | -         |     6.90 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     1998 | 2024-05-15 | LAG              | W   | 0.682      | -            | -                | -                | -         |     7.86 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     2005 | 2024-05-15 | LAG              | W   | 0.682      | -            | -                | -                | -         |     8.32 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2056 | 2024-05-14 | Take Flyte       | W   | 0.676      | -            | -                | -                | -         |     5.02 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2061 | 2024-05-14 | Take Flyte       | W   | 0.675      | -            | -                | -                | -         |     5.24 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2129 | 2024-05-12 | Perseverance     | W   | 0.662      | -            | -                | -                | -         |     6.45 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2131 | 2024-05-12 | Elevate          | W   | 0.661      | -            | -                | -                | -         |    13.22 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2159 | 2024-05-11 | Perseverance     | W   | 0.654      | -            | -                | -                | -         |     6.43 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2161 | 2024-05-11 | BOSS             | W   | 0.654      | -            | -                | -                | -         |     8.46 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2267 | 2024-05-06 | Party Astronauts | W   | 0.622      | 0.477        | 0.042 (0.012)    | 0.532 (0.158)    | -         |    12.21 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2268 | 2024-05-06 | Party Astronauts | L   | 0.622      | -            | -                | -                | -         |    -7.46 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2507 | 2024-04-25 | Wildcard         | L   | 0.549      | -            | -                | -                | -         |    -7.57 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2509 | 2024-04-25 | Wildcard         | W   | 0.549      | 0.477        | 0.055 (0.014)    | -                | -         |     9.96 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2753 | 2024-04-17 | Akimbo           | L   | 0.494      | -            | -                | -                | -         |   -10.11 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2814 | 2024-04-15 | Mythic           | W   | 0.482      | -            | -                | -                | -         |     5.47 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2815 | 2024-04-15 | Mythic           | W   | 0.482      | -            | -                | -                | -         |     5.69 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2903 | 2024-04-10 | BOSS             | W   | 0.449      | -            | -                | -                | -         |     6.55 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2907 | 2024-04-10 | BOSS             | L   | 0.449      | -            | -                | -                | -         |    -7.77 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2961 | 2024-04-09 | Carpe Diem       | W   | 0.442      | -            | -                | -                | -         |     3.47 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     2964 | 2024-04-09 | Carpe Diem       | W   | 0.442      | -            | -                | -                | -         |     3.57 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     3272 | 2024-03-27 | Nouns            | W   | 0.356      | 0.477        | 0.058 (0.010)    | -                | -         |     6.81 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3276 | 2024-03-27 | Nouns            | L   | 0.356      | -            | -                | -                | -         |    -4.47 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3325 | 2024-03-26 | MIGHT            | W   | 0.349      | -            | -                | -                | -         |     1.66 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3330 | 2024-03-26 | MIGHT            | W   | 0.349      | -            | -                | -                | -         |     1.68 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3500 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.276      | -            | -                | -                | -         |     3.39 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3502 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.276      | -            | -                | -                | -         |    -5.39 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3520 | 2024-03-14 | Limitless        | W   | 0.269      | -            | -                | -                | -         |     2.07 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3524 | 2024-03-14 | Limitless        | W   | 0.269      | -            | -                | -                | -         |     2.11 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3603 | 2024-03-12 | Carpe Diem       | L   | 0.255      | -            | -                | -                | -         |    -5.82 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3865 | 2024-03-02 | MIBR             | L   | 0.187      | -            | -                | -                | -         |    -0.25 | Brehze, daps, FaNg, HexT, oSee       |
|           10 |     3885 | 2024-03-01 | Imperial         | L   | 0.181      | -            | -                | -                | -         |    -0.50 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3994 | 2024-02-24 | Wildcard         | L   | 0.142      | -            | -                | -                | -         |    -1.87 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     3996 | 2024-02-24 | Limitless        | W   | 0.142      | -            | -                | -                | -         |     1.11 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     4002 | 2024-02-24 | Mythic           | W   | 0.141      | -            | -                | -                | -         |     1.88 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     4042 | 2024-02-22 | Party Astronauts | L   | 0.128      | -            | -                | -                | -         |    -1.58 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     4047 | 2024-02-22 | Wildcard         | W   | 0.128      | -            | -                | -                | -         |     2.36 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4097 | 2024-02-20 | Party Astronauts | L   | 0.116      | -            | -                | -                | -         |    -1.43 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4122 | 2024-02-19 | Party Astronauts | W   | 0.109      | -            | -                | -                | -         |     2.10 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4124 | 2024-02-19 | Mythic           | W   | 0.108      | -            | -                | -                | -         |     1.46 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4436 | 2024-02-03 | Elevate          | L   | 0.001      | -            | -                | -                | -         |    -0.01 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,630.37)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.848 | $4,250.00      | $3,605.42       |
| 2024-05-18 |      0.702 | $1,000.00      | $701.85         |
| 2024-05-12 |      0.662 | $2,000.00      | $1,323.10       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
