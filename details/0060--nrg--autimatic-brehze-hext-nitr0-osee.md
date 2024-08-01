### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [18]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1000.3<br />
<br />
Final Rank Value (1000.3) = Starting Rank Value (854.4) + Head To Head Adjustments (146.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.350[<sup>2</sup>](#table1)
- Opponent Network: 0.161[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.221<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 854.4
- 400 + ( ( 0.221 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 854.4


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
|           76 |       13 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.334 (0.159)    | 0 (0.000) |     8.27 | autimatic, Brehze, HexT, nitr0, oSee |
|           75 |       17 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.334 (0.159)    | 0 (0.000) |     8.87 | autimatic, Brehze, HexT, nitr0, oSee |
|           74 |       61 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.51 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |       65 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.94 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      356 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.45 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      360 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.058 (0.018)    | 0.557 (0.169)    | 0 (0.000) |    14.52 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      387 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.86 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      458 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     7.95 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      463 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     8.50 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      528 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.91 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      533 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.36 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      590 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.305 (0.145)    | 0 (0.000) |     5.54 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      595 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.305 (0.145)    | 0 (0.000) |     5.83 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      647 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.33 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      651 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.82 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |     1102 | 2024-06-09 | M80              | W   | 0.848      | 0.143        | 0.190 (0.023)    | -                | -         |    23.11 | autimatic, Brehze, HexT, oSee, Walco |
|           60 |     1176 | 2024-06-08 | Party Astronauts | W   | 0.841      | -            | -                | -                | -         |    16.06 | autimatic, Brehze, HexT, oSee, Walco |
|           59 |     1229 | 2024-06-07 | Party Astronauts | L   | 0.835      | -            | -                | -                | -         |   -10.33 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1274 | 2024-06-06 | Party Astronauts | L   | 0.830      | -            | -                | -                | -         |   -11.54 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1284 | 2024-06-06 | Wildcard         | W   | 0.829      | 0.143        | 0.055 (0.007)    | -                | -         |    15.33 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1288 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.829      | -            | -                | -                | -         |     6.36 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1309 | 2024-06-06 | Wildcard         | L   | 0.828      | -            | -                | -                | -         |   -10.36 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1343 | 2024-06-05 | LAG              | W   | 0.824      | 0.477        | -                | 0.371 (0.146)    | -         |    10.91 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1358 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.822      | -            | -                | -                | -         |     6.71 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1396 | 2024-06-04 | Nouns            | L   | 0.817      | -            | -                | -                | -         |   -10.15 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1694 | 2024-05-23 | Nouns            | L   | 0.737      | -            | -                | -                | -         |    -9.82 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1710 | 2024-05-22 | Elevate          | L   | 0.731      | -            | -                | -                | -         |    -9.24 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1716 | 2024-05-22 | Elevate          | L   | 0.730      | -            | -                | -                | -         |    -9.84 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1739 | 2024-05-22 | Legacy           | W   | 0.728      | 0.384        | 0.119 (0.033)    | 0.562 (0.157)    | -         |    14.19 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1772 | 2024-05-21 | Perseverance     | L   | 0.724      | -            | -                | -                | -         |   -17.14 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1775 | 2024-05-21 | Perseverance     | W   | 0.724      | -            | -                | -                | -         |     5.53 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1811 | 2024-05-20 | M80              | L   | 0.717      | -            | -                | -                | -         |    -3.16 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1815 | 2024-05-20 | M80              | L   | 0.717      | -            | -                | -                | -         |    -3.26 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1854 | 2024-05-19 | Perseverance     | W   | 0.710      | -            | -                | -                | -         |     5.59 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1883 | 2024-05-18 | Nouns            | L   | 0.704      | -            | -                | -                | -         |   -11.38 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1888 | 2024-05-18 | Party Astronauts | W   | 0.702      | 0.303        | 0.042 (0.009)    | -                | -         |    11.09 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1923 | 2024-05-17 | BOSS             | W   | 0.696      | -            | -                | -                | -         |     6.91 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     1992 | 2024-05-15 | LAG              | W   | 0.684      | -            | -                | -                | -         |     7.88 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     1999 | 2024-05-15 | LAG              | W   | 0.684      | -            | -                | -                | -         |     8.34 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2050 | 2024-05-14 | Take Flyte       | W   | 0.677      | -            | -                | -                | -         |     5.03 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2055 | 2024-05-14 | Take Flyte       | W   | 0.677      | -            | -                | -                | -         |     5.25 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2123 | 2024-05-12 | Perseverance     | W   | 0.663      | -            | -                | -                | -         |     6.46 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2125 | 2024-05-12 | Elevate          | W   | 0.663      | -            | -                | -                | -         |    13.25 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2153 | 2024-05-11 | Perseverance     | W   | 0.656      | -            | -                | -                | -         |     6.44 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2155 | 2024-05-11 | BOSS             | W   | 0.655      | -            | -                | -                | -         |     8.48 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2261 | 2024-05-06 | Party Astronauts | W   | 0.624      | 0.477        | 0.042 (0.012)    | 0.532 (0.158)    | -         |    12.25 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2262 | 2024-05-06 | Party Astronauts | L   | 0.624      | -            | -                | -                | -         |    -7.47 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2501 | 2024-04-25 | Wildcard         | L   | 0.551      | -            | -                | -                | -         |    -7.59 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2503 | 2024-04-25 | Wildcard         | W   | 0.550      | 0.477        | 0.055 (0.015)    | -                | -         |    10.00 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2747 | 2024-04-17 | Akimbo           | L   | 0.496      | -            | -                | -                | -         |   -10.14 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2808 | 2024-04-15 | Mythic           | W   | 0.484      | -            | -                | -                | -         |     5.49 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2809 | 2024-04-15 | Mythic           | W   | 0.483      | -            | -                | -                | -         |     5.71 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2897 | 2024-04-10 | BOSS             | W   | 0.451      | -            | -                | -                | -         |     6.57 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2901 | 2024-04-10 | BOSS             | L   | 0.450      | -            | -                | -                | -         |    -7.79 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2955 | 2024-04-09 | Carpe Diem       | W   | 0.444      | -            | -                | -                | -         |     3.48 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     2958 | 2024-04-09 | Carpe Diem       | W   | 0.444      | -            | -                | -                | -         |     3.58 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     3266 | 2024-03-27 | Nouns            | W   | 0.358      | 0.477        | 0.058 (0.010)    | -                | -         |     6.84 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3270 | 2024-03-27 | Nouns            | L   | 0.357      | -            | -                | -                | -         |    -4.49 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3319 | 2024-03-26 | MIGHT            | W   | 0.351      | -            | -                | -                | -         |     1.67 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3324 | 2024-03-26 | MIGHT            | W   | 0.351      | -            | -                | -                | -         |     1.69 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3494 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.278      | -            | -                | -                | -         |     3.41 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3496 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.277      | -            | -                | -                | -         |    -5.42 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3514 | 2024-03-14 | Limitless        | W   | 0.271      | -            | -                | -                | -         |     2.08 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3518 | 2024-03-14 | Limitless        | W   | 0.271      | -            | -                | -                | -         |     2.12 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3597 | 2024-03-12 | Carpe Diem       | L   | 0.257      | -            | -                | -                | -         |    -5.86 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3859 | 2024-03-02 | MIBR             | L   | 0.188      | -            | -                | -                | -         |    -0.25 | Brehze, daps, FaNg, HexT, oSee       |
|           10 |     3879 | 2024-03-01 | Imperial         | L   | 0.183      | -            | -                | -                | -         |    -0.50 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3988 | 2024-02-24 | Wildcard         | L   | 0.144      | -            | -                | -                | -         |    -1.89 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     3990 | 2024-02-24 | Limitless        | W   | 0.143      | -            | -                | -                | -         |     1.13 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     3996 | 2024-02-24 | Mythic           | W   | 0.143      | -            | -                | -                | -         |     1.91 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     4036 | 2024-02-22 | Party Astronauts | L   | 0.130      | -            | -                | -                | -         |    -1.60 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     4041 | 2024-02-22 | Wildcard         | W   | 0.130      | -            | -                | -                | -         |     2.39 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4091 | 2024-02-20 | Party Astronauts | L   | 0.117      | -            | -                | -                | -         |    -1.45 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4116 | 2024-02-19 | Party Astronauts | W   | 0.111      | -            | -                | -                | -         |     2.13 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4118 | 2024-02-19 | Mythic           | W   | 0.110      | -            | -                | -                | -         |     1.48 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4430 | 2024-02-03 | Elevate          | L   | 0.003      | -            | -                | -                | -         |    -0.02 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,642.45)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.850 | $4,250.00      | $3,612.50       |
| 2024-05-18 |      0.704 | $1,000.00      | $703.52         |
| 2024-05-12 |      0.663 | $2,000.00      | $1,326.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
