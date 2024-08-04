### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [62](../standings_global.md)<br />
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
|           74 |      102 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.333 (0.159)    | 0 (0.000) |     8.15 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |      106 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.333 (0.159)    | 0 (0.000) |     8.74 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      150 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.48 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      154 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.91 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      443 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.40 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      447 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.057 (0.017)    | 0.548 (0.166)    | 0 (0.000) |    14.27 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      473 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.72 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      541 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.186)    | 0 (0.000) |     8.26 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      545 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.186)    | 0 (0.000) |     8.86 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      607 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.300 (0.143)    | 0 (0.000) |     7.47 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      612 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.300 (0.143)    | 0 (0.000) |     7.97 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      669 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.274 (0.131)    | 0 (0.000) |     5.58 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      674 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.88 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |      721 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.49 | autimatic, Brehze, HexT, nitr0, oSee |
|           60 |      724 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     8.00 | autimatic, Brehze, HexT, nitr0, oSee |
|           59 |     1182 | 2024-06-09 | M80              | W   | 0.829      | 0.143        | 0.188 (0.022)    | -                | -         |    22.51 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1254 | 2024-06-08 | Party Astronauts | W   | 0.822      | -            | -                | -                | -         |    15.75 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1300 | 2024-06-07 | Party Astronauts | L   | 0.816      | -            | -                | -                | -         |   -10.04 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1344 | 2024-06-06 | Party Astronauts | L   | 0.811      | -            | -                | -                | -         |   -11.19 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1353 | 2024-06-06 | Wildcard         | W   | 0.810      | 0.143        | 0.055 (0.006)    | -                | -         |    15.05 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1357 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.810      | -            | -                | -                | -         |     6.45 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1378 | 2024-06-06 | Wildcard         | L   | 0.809      | -            | -                | -                | -         |   -10.05 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1411 | 2024-06-05 | LAG              | W   | 0.804      | -            | -                | -                | -         |    10.46 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1425 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.802      | -            | -                | -                | -         |     6.80 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1462 | 2024-06-04 | Nouns            | L   | 0.798      | -            | -                | -                | -         |    -9.84 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1757 | 2024-05-23 | Nouns            | L   | 0.718      | -            | -                | -                | -         |    -9.48 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1773 | 2024-05-22 | Elevate          | L   | 0.711      | -            | -                | -                | -         |    -8.91 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1779 | 2024-05-22 | Elevate          | L   | 0.711      | -            | -                | -                | -         |    -9.47 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1802 | 2024-05-22 | Legacy           | W   | 0.709      | 0.384        | 0.122 (0.033)    | 0.643 (0.175)    | -         |    13.92 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1825 | 2024-05-21 | Perseverance     | L   | 0.704      | -            | -                | -                | -         |   -16.40 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1827 | 2024-05-21 | Perseverance     | W   | 0.704      | -            | -                | -                | -         |     5.69 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1858 | 2024-05-20 | M80              | L   | 0.698      | -            | -                | -                | -         |    -3.12 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1862 | 2024-05-20 | M80              | L   | 0.698      | -            | -                | -                | -         |    -3.22 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1921 | 2024-05-18 | Nouns            | L   | 0.684      | -            | -                | -                | -         |   -11.09 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1926 | 2024-05-18 | Party Astronauts | W   | 0.682      | 0.303        | 0.041 (0.009)    | -                | -         |    10.77 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     1960 | 2024-05-17 | BOSS             | W   | 0.677      | -            | -                | -                | -         |     6.69 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     2029 | 2024-05-15 | LAG              | W   | 0.664      | -            | -                | -                | -         |     7.63 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2036 | 2024-05-15 | LAG              | W   | 0.664      | -            | -                | -                | -         |     8.06 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2081 | 2024-05-14 | Take Flyte       | W   | 0.658      | -            | -                | -                | -         |     4.95 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2086 | 2024-05-14 | Take Flyte       | W   | 0.657      | -            | -                | -                | -         |     5.17 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2151 | 2024-05-12 | Perseverance     | W   | 0.644      | -            | -                | -                | -         |     6.30 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2153 | 2024-05-12 | Elevate          | W   | 0.643      | -            | -                | -                | -         |    12.79 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2181 | 2024-05-11 | Perseverance     | W   | 0.636      | -            | -                | -                | -         |     6.28 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2183 | 2024-05-11 | BOSS             | W   | 0.636      | -            | -                | -                | -         |     8.13 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2287 | 2024-05-06 | Party Astronauts | W   | 0.604      | 0.477        | 0.041 (0.012)    | 0.531 (0.153)    | -         |    11.78 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2288 | 2024-05-06 | Party Astronauts | L   | 0.604      | -            | -                | -                | -         |    -7.33 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2524 | 2024-04-25 | Wildcard         | L   | 0.531      | -            | -                | -                | -         |    -7.37 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2526 | 2024-04-25 | Wildcard         | W   | 0.531      | 0.477        | 0.055 (0.014)    | -                | -         |     9.59 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2762 | 2024-04-17 | Akimbo           | L   | 0.477      | -            | -                | -                | -         |    -9.76 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2821 | 2024-04-15 | Mythic           | W   | 0.464      | -            | -                | -                | -         |     5.27 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2822 | 2024-04-15 | Mythic           | W   | 0.464      | -            | -                | -                | -         |     5.47 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2909 | 2024-04-10 | BOSS             | W   | 0.431      | -            | -                | -                | -         |     6.16 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2913 | 2024-04-10 | BOSS             | L   | 0.431      | -            | -                | -                | -         |    -7.59 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     2967 | 2024-04-09 | Carpe Diem       | W   | 0.424      | -            | -                | -                | -         |     3.36 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     2970 | 2024-04-09 | Carpe Diem       | W   | 0.424      | -            | -                | -                | -         |     3.45 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3270 | 2024-03-27 | Nouns            | W   | 0.338      | 0.477        | 0.057 (0.009)    | -                | -         |     6.44 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3274 | 2024-03-27 | Nouns            | L   | 0.338      | -            | -                | -                | -         |    -4.28 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3322 | 2024-03-26 | MIGHT            | W   | 0.331      | -            | -                | -                | -         |     1.58 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3327 | 2024-03-26 | MIGHT            | W   | 0.331      | -            | -                | -                | -         |     1.60 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3493 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.258      | -            | -                | -                | -         |     3.14 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3495 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.258      | -            | -                | -                | -         |    -5.07 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3513 | 2024-03-14 | Limitless        | W   | 0.251      | -            | -                | -                | -         |     1.95 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3517 | 2024-03-14 | Limitless        | W   | 0.251      | -            | -                | -                | -         |     1.98 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3592 | 2024-03-12 | Carpe Diem       | L   | 0.238      | -            | -                | -                | -         |    -5.41 | autimatic, Brehze, HexT, oSee, Walco |
|           10 |     3847 | 2024-03-02 | MIBR             | L   | 0.169      | -            | -                | -                | -         |    -0.22 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3866 | 2024-03-01 | Imperial         | L   | 0.163      | -            | -                | -                | -         |    -0.47 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     3972 | 2024-02-24 | Wildcard         | L   | 0.124      | -            | -                | -                | -         |    -1.65 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     3974 | 2024-02-24 | Limitless        | W   | 0.124      | -            | -                | -                | -         |     0.98 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     3980 | 2024-02-24 | Mythic           | W   | 0.124      | -            | -                | -                | -         |     1.63 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     4016 | 2024-02-22 | Party Astronauts | L   | 0.111      | -            | -                | -                | -         |    -1.38 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4021 | 2024-02-22 | Wildcard         | W   | 0.110      | -            | -                | -                | -         |     2.02 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4069 | 2024-02-20 | Party Astronauts | L   | 0.098      | -            | -                | -                | -         |    -1.23 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4094 | 2024-02-19 | Party Astronauts | W   | 0.091      | -            | -                | -                | -         |     1.74 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4096 | 2024-02-19 | Mythic           | W   | 0.090      | -            | -                | -                | -         |     1.20 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,501.48)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.831 | $4,250.00      | $3,529.86       |
| 2024-05-18 |      0.684 | $1,000.00      | $684.07         |
| 2024-05-12 |      0.644 | $2,000.00      | $1,287.55       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
