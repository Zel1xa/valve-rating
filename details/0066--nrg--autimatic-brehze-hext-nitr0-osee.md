### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [19]( ../standings_americas.md)<br />
<br />
Final Rank Value:  976.2<br />
<br />
Final Rank Value (976.2) = Starting Rank Value (845.9) + Head To Head Adjustments (130.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.145[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.216<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 845.9
- 400 + ( ( 0.216 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 845.9


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
|           76 |       33 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.41 | autimatic, Brehze, HexT, nitr0, oSee |
|           75 |       37 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.84 | autimatic, Brehze, HexT, nitr0, oSee |
|           74 |      326 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.38 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |      330 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.058 (0.017)    | 0.546 (0.165)    | 0 (0.000) |    14.39 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      356 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.76 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      424 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | 0.011 (0.005)    | 0.347 (0.166)    | 0 (0.000) |     7.93 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      428 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | 0.011 (0.005)    | 0.347 (0.166)    | 0 (0.000) |     8.48 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      490 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.266 (0.127)    | 0 (0.000) |     7.50 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      495 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.266 (0.127)    | 0 (0.000) |     8.00 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      552 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.38 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      557 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.67 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      604 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.50 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      607 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.00 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |     1065 | 2024-06-09 | M80              | W   | 0.852      | 0.143        | 0.189 (0.023)    | -                | -         |    23.32 | autimatic, Brehze, HexT, oSee, Walco |
|           62 |     1137 | 2024-06-08 | Party Astronauts | W   | 0.846      | -            | -                | -                | -         |    16.31 | autimatic, Brehze, HexT, oSee, Walco |
|           61 |     1183 | 2024-06-07 | Party Astronauts | L   | 0.839      | -            | -                | -                | -         |   -10.19 | autimatic, Brehze, HexT, oSee, Walco |
|           60 |     1227 | 2024-06-06 | Party Astronauts | L   | 0.835      | -            | -                | -                | -         |   -11.40 | autimatic, Brehze, HexT, oSee, Walco |
|           59 |     1236 | 2024-06-06 | Wildcard         | W   | 0.834      | 0.143        | 0.055 (0.007)    | -                | -         |    15.48 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1240 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.833      | -            | -                | -                | -         |     6.42 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1261 | 2024-06-06 | Wildcard         | L   | 0.832      | -            | -                | -                | -         |   -10.34 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1294 | 2024-06-05 | LAG              | W   | 0.828      | 0.477        | -                | 0.344 (0.136)    | -         |    10.91 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1308 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.826      | -            | -                | -                | -         |     6.78 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1345 | 2024-06-04 | Nouns            | L   | 0.822      | -            | -                | -                | -         |    -9.95 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1640 | 2024-05-23 | Nouns            | L   | 0.741      | -            | -                | -                | -         |    -9.63 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1656 | 2024-05-22 | Elevate          | L   | 0.735      | -            | -                | -                | -         |    -9.08 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1662 | 2024-05-22 | Elevate          | L   | 0.735      | -            | -                | -                | -         |    -9.67 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1685 | 2024-05-22 | Legacy           | W   | 0.732      | 0.384        | 0.118 (0.033)    | 0.562 (0.158)    | -         |    14.16 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1708 | 2024-05-21 | Perseverance     | L   | 0.728      | -            | -                | -                | -         |   -16.94 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1710 | 2024-05-21 | Perseverance     | W   | 0.728      | -            | -                | -                | -         |     5.88 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1741 | 2024-05-20 | M80              | L   | 0.722      | -            | -                | -                | -         |    -3.05 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1745 | 2024-05-20 | M80              | L   | 0.721      | -            | -                | -                | -         |    -3.15 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1804 | 2024-05-18 | Nouns            | L   | 0.708      | -            | -                | -                | -         |   -11.34 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1809 | 2024-05-18 | Party Astronauts | W   | 0.706      | 0.303        | 0.041 (0.009)    | 0.533 (0.114)    | -         |    11.23 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1843 | 2024-05-17 | BOSS             | W   | 0.700      | -            | -                | -                | -         |     6.97 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1912 | 2024-05-15 | LAG              | W   | 0.688      | -            | -                | -                | -         |     8.02 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1919 | 2024-05-15 | LAG              | W   | 0.688      | -            | -                | -                | -         |     8.50 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1964 | 2024-05-14 | Take Flyte       | W   | 0.682      | -            | -                | -                | -         |     5.17 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     1969 | 2024-05-14 | Take Flyte       | W   | 0.681      | -            | -                | -                | -         |     5.41 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     2034 | 2024-05-12 | Perseverance     | W   | 0.668      | -            | -                | -                | -         |     6.61 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2036 | 2024-05-12 | Elevate          | W   | 0.667      | -            | -                | -                | -         |    13.44 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2064 | 2024-05-11 | Perseverance     | W   | 0.660      | -            | -                | -                | -         |     6.60 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2066 | 2024-05-11 | BOSS             | W   | 0.660      | -            | -                | -                | -         |     8.59 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2170 | 2024-05-06 | Party Astronauts | W   | 0.628      | 0.477        | 0.041 (0.012)    | 0.533 (0.160)    | -         |    12.47 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2171 | 2024-05-06 | Party Astronauts | L   | 0.628      | -            | -                | -                | -         |    -7.38 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2407 | 2024-04-25 | Wildcard         | L   | 0.555      | -            | -                | -                | -         |    -7.75 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2409 | 2024-04-25 | Wildcard         | W   | 0.555      | 0.477        | 0.055 (0.014)    | 0.501 (0.132)    | -         |     9.97 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2645 | 2024-04-17 | Akimbo           | L   | 0.500      | -            | -                | -                | -         |   -10.13 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2704 | 2024-04-15 | Mythic           | W   | 0.488      | -            | -                | -                | -         |     5.61 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2705 | 2024-04-15 | Mythic           | W   | 0.488      | -            | -                | -                | -         |     5.84 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2792 | 2024-04-10 | BOSS             | W   | 0.455      | -            | -                | -                | -         |     6.67 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2796 | 2024-04-10 | BOSS             | L   | 0.455      | -            | -                | -                | -         |    -7.84 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2850 | 2024-04-09 | Carpe Diem       | W   | 0.448      | -            | -                | -                | -         |     3.62 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2853 | 2024-04-09 | Carpe Diem       | W   | 0.448      | -            | -                | -                | -         |     3.73 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     3153 | 2024-03-27 | Nouns            | W   | 0.362      | 0.477        | 0.058 (0.010)    | -                | -         |     7.03 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     3157 | 2024-03-27 | Nouns            | L   | 0.362      | -            | -                | -                | -         |    -4.43 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     3205 | 2024-03-26 | MIGHT            | W   | 0.355      | -            | -                | -                | -         |     1.75 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     3210 | 2024-03-26 | MIGHT            | W   | 0.355      | -            | -                | -                | -         |     1.78 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3376 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.282      | -            | -                | -                | -         |     3.57 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3378 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.282      | -            | -                | -                | -         |    -5.41 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3396 | 2024-03-14 | Limitless        | W   | 0.275      | -            | -                | -                | -         |     2.19 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3400 | 2024-03-14 | Limitless        | W   | 0.275      | -            | -                | -                | -         |     2.22 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3475 | 2024-03-12 | Carpe Diem       | L   | 0.261      | -            | -                | -                | -         |    -5.88 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3730 | 2024-03-02 | MIBR             | L   | 0.193      | -            | -                | -                | -         |    -0.23 | Brehze, daps, FaNg, HexT, oSee       |
|           13 |     3749 | 2024-03-01 | Imperial         | L   | 0.187      | -            | -                | -                | -         |    -0.46 | Brehze, daps, FaNg, HexT, oSee       |
|           12 |     3855 | 2024-02-24 | Wildcard         | L   | 0.148      | -            | -                | -                | -         |    -1.98 | Brehze, daps, FaNg, HexT, oSee       |
|           11 |     3857 | 2024-02-24 | Limitless        | W   | 0.148      | -            | -                | -                | -         |     1.20 | Brehze, daps, FaNg, HexT, oSee       |
|           10 |     3863 | 2024-02-24 | Mythic           | W   | 0.147      | -            | -                | -                | -         |     2.00 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3899 | 2024-02-22 | Party Astronauts | L   | 0.134      | -            | -                | -                | -         |    -1.61 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     3904 | 2024-02-22 | Wildcard         | W   | 0.134      | -            | -                | -                | -         |     2.44 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     3952 | 2024-02-20 | Party Astronauts | L   | 0.122      | -            | -                | -                | -         |    -1.47 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     3977 | 2024-02-19 | Party Astronauts | W   | 0.115      | -            | -                | -                | -         |     2.25 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     3979 | 2024-02-19 | Mythic           | W   | 0.114      | -            | -                | -                | -         |     1.56 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4281 | 2024-02-03 | Elevate          | L   | 0.007      | -            | -                | -                | -         |    -0.06 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4307 | 2024-02-02 | Party Astronauts | W   | 0.001      | -            | -                | -                | -         |     0.03 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4311 | 2024-02-02 | Wildcard         | L   | 0.001      | -            | -                | -                | -         |    -0.01 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4313 | 2024-02-02 | Party Astronauts | W   | 0.001      | -            | -                | -                | -         |     0.01 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,673.90)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.854 | $4,250.00      | $3,630.94       |
| 2024-05-18 |      0.708 | $1,000.00      | $707.86         |
| 2024-05-12 |      0.668 | $2,000.00      | $1,335.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
