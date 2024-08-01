### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [18]( ../standings_americas.md)<br />
<br />
Final Rank Value:  999.7<br />
<br />
Final Rank Value (999.7) = Starting Rank Value (853.8) + Head To Head Adjustments (145.9)<br />

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
|           76 |       17 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.334 (0.159)    | 0 (0.000) |     8.27 | autimatic, Brehze, HexT, nitr0, oSee |
|           75 |       21 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.334 (0.159)    | 0 (0.000) |     8.87 | autimatic, Brehze, HexT, nitr0, oSee |
|           74 |       65 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.51 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |       69 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.94 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      360 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.45 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      364 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.058 (0.018)    | 0.557 (0.169)    | 0 (0.000) |    14.52 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      391 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.87 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      462 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     7.95 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      467 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     8.51 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      532 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.92 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      537 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.36 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      594 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.305 (0.145)    | 0 (0.000) |     5.54 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      599 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.305 (0.145)    | 0 (0.000) |     5.84 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      651 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.33 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      655 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.82 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |     1106 | 2024-06-09 | M80              | W   | 0.847      | 0.143        | 0.190 (0.023)    | -                | -         |    23.09 | autimatic, Brehze, HexT, oSee, Walco |
|           60 |     1180 | 2024-06-08 | Party Astronauts | W   | 0.840      | -            | -                | -                | -         |    16.04 | autimatic, Brehze, HexT, oSee, Walco |
|           59 |     1233 | 2024-06-07 | Party Astronauts | L   | 0.834      | -            | -                | -                | -         |   -10.31 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1278 | 2024-06-06 | Party Astronauts | L   | 0.829      | -            | -                | -                | -         |   -11.52 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1288 | 2024-06-06 | Wildcard         | W   | 0.828      | 0.143        | 0.055 (0.007)    | -                | -         |    15.31 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1292 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.828      | -            | -                | -                | -         |     6.35 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1313 | 2024-06-06 | Wildcard         | L   | 0.827      | -            | -                | -                | -         |   -10.35 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1347 | 2024-06-05 | LAG              | W   | 0.822      | 0.477        | -                | 0.371 (0.145)    | -         |    10.89 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1362 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.820      | -            | -                | -                | -         |     6.70 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1400 | 2024-06-04 | Nouns            | L   | 0.816      | -            | -                | -                | -         |   -10.13 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1698 | 2024-05-23 | Nouns            | L   | 0.736      | -            | -                | -                | -         |    -9.80 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1714 | 2024-05-22 | Elevate          | L   | 0.729      | -            | -                | -                | -         |    -9.22 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1720 | 2024-05-22 | Elevate          | L   | 0.729      | -            | -                | -                | -         |    -9.82 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1743 | 2024-05-22 | Legacy           | W   | 0.727      | 0.384        | 0.119 (0.033)    | 0.562 (0.157)    | -         |    14.16 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1776 | 2024-05-21 | Perseverance     | L   | 0.722      | -            | -                | -                | -         |   -17.11 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1779 | 2024-05-21 | Perseverance     | W   | 0.722      | -            | -                | -                | -         |     5.53 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1815 | 2024-05-20 | M80              | L   | 0.716      | -            | -                | -                | -         |    -3.14 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1819 | 2024-05-20 | M80              | L   | 0.716      | -            | -                | -                | -         |    -3.24 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1858 | 2024-05-19 | Perseverance     | W   | 0.708      | -            | -                | -                | -         |     5.58 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1887 | 2024-05-18 | Nouns            | L   | 0.702      | -            | -                | -                | -         |   -11.36 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1892 | 2024-05-18 | Party Astronauts | W   | 0.701      | 0.303        | 0.042 (0.009)    | -                | -         |    11.07 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1927 | 2024-05-17 | BOSS             | W   | 0.695      | -            | -                | -                | -         |     6.90 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     1996 | 2024-05-15 | LAG              | W   | 0.682      | -            | -                | -                | -         |     7.87 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     2003 | 2024-05-15 | LAG              | W   | 0.682      | -            | -                | -                | -         |     8.32 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2054 | 2024-05-14 | Take Flyte       | W   | 0.676      | -            | -                | -                | -         |     5.02 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2059 | 2024-05-14 | Take Flyte       | W   | 0.676      | -            | -                | -                | -         |     5.25 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2127 | 2024-05-12 | Perseverance     | W   | 0.662      | -            | -                | -                | -         |     6.45 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2129 | 2024-05-12 | Elevate          | W   | 0.661      | -            | -                | -                | -         |    13.22 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2157 | 2024-05-11 | Perseverance     | W   | 0.654      | -            | -                | -                | -         |     6.43 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2159 | 2024-05-11 | BOSS             | W   | 0.654      | -            | -                | -                | -         |     8.47 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2265 | 2024-05-06 | Party Astronauts | W   | 0.622      | 0.477        | 0.042 (0.012)    | 0.532 (0.158)    | -         |    12.22 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2266 | 2024-05-06 | Party Astronauts | L   | 0.622      | -            | -                | -                | -         |    -7.46 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2505 | 2024-04-25 | Wildcard         | L   | 0.549      | -            | -                | -                | -         |    -7.57 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2507 | 2024-04-25 | Wildcard         | W   | 0.549      | 0.477        | 0.055 (0.014)    | -                | -         |     9.97 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2751 | 2024-04-17 | Akimbo           | L   | 0.495      | -            | -                | -                | -         |   -10.11 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2812 | 2024-04-15 | Mythic           | W   | 0.482      | -            | -                | -                | -         |     5.48 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2813 | 2024-04-15 | Mythic           | W   | 0.482      | -            | -                | -                | -         |     5.70 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2901 | 2024-04-10 | BOSS             | W   | 0.449      | -            | -                | -                | -         |     6.55 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2905 | 2024-04-10 | BOSS             | L   | 0.449      | -            | -                | -                | -         |    -7.77 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2959 | 2024-04-09 | Carpe Diem       | W   | 0.442      | -            | -                | -                | -         |     3.47 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     2962 | 2024-04-09 | Carpe Diem       | W   | 0.442      | -            | -                | -                | -         |     3.58 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     3270 | 2024-03-27 | Nouns            | W   | 0.356      | 0.477        | 0.058 (0.010)    | -                | -         |     6.82 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3274 | 2024-03-27 | Nouns            | L   | 0.356      | -            | -                | -                | -         |    -4.47 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3323 | 2024-03-26 | MIGHT            | W   | 0.349      | -            | -                | -                | -         |     1.66 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3328 | 2024-03-26 | MIGHT            | W   | 0.349      | -            | -                | -                | -         |     1.69 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3498 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.276      | -            | -                | -                | -         |     3.39 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3500 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.276      | -            | -                | -                | -         |    -5.39 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3518 | 2024-03-14 | Limitless        | W   | 0.269      | -            | -                | -                | -         |     2.07 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3522 | 2024-03-14 | Limitless        | W   | 0.269      | -            | -                | -                | -         |     2.11 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3601 | 2024-03-12 | Carpe Diem       | L   | 0.256      | -            | -                | -                | -         |    -5.83 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3863 | 2024-03-02 | MIBR             | L   | 0.187      | -            | -                | -                | -         |    -0.25 | Brehze, daps, FaNg, HexT, oSee       |
|           10 |     3883 | 2024-03-01 | Imperial         | L   | 0.181      | -            | -                | -                | -         |    -0.50 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3992 | 2024-02-24 | Wildcard         | L   | 0.142      | -            | -                | -                | -         |    -1.87 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     3994 | 2024-02-24 | Limitless        | W   | 0.142      | -            | -                | -                | -         |     1.11 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     4000 | 2024-02-24 | Mythic           | W   | 0.142      | -            | -                | -                | -         |     1.89 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     4040 | 2024-02-22 | Party Astronauts | L   | 0.129      | -            | -                | -                | -         |    -1.58 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     4045 | 2024-02-22 | Wildcard         | W   | 0.128      | -            | -                | -                | -         |     2.37 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4095 | 2024-02-20 | Party Astronauts | L   | 0.116      | -            | -                | -                | -         |    -1.43 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4120 | 2024-02-19 | Party Astronauts | W   | 0.109      | -            | -                | -                | -         |     2.10 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4122 | 2024-02-19 | Mythic           | W   | 0.108      | -            | -                | -                | -         |     1.46 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4434 | 2024-02-03 | Elevate          | L   | 0.001      | -            | -                | -                | -         |    -0.01 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,632.38)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.849 | $4,250.00      | $3,606.60       |
| 2024-05-18 |      0.702 | $1,000.00      | $702.13         |
| 2024-05-12 |      0.662 | $2,000.00      | $1,323.66       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
