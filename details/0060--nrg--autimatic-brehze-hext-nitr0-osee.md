### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [17]( ../standings_americas.md)<br />
<br />
Final Rank Value:  988.1<br />
<br />
Final Rank Value (988.1) = Starting Rank Value (851.3) + Head To Head Adjustments (136.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.221<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 851.3
- 400 + ( ( 0.221 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 851.3


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
|           74 |       77 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.344 (0.164)    | 0 (0.000) |     8.14 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |       81 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.344 (0.164)    | 0 (0.000) |     8.72 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      124 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.51 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      128 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.95 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      417 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.41 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      421 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.057 (0.017)    | 0.566 (0.171)    | 0 (0.000) |    14.10 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      447 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.70 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      515 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.367 (0.175)    | 0 (0.000) |     8.14 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      519 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.367 (0.175)    | 0 (0.000) |     8.72 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      581 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.311 (0.148)    | 0 (0.000) |     7.44 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      586 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.311 (0.148)    | 0 (0.000) |     7.94 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      640 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.57 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      645 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.87 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |      692 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.55 | autimatic, Brehze, HexT, nitr0, oSee |
|           60 |      695 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     8.07 | autimatic, Brehze, HexT, nitr0, oSee |
|           59 |     1123 | 2024-06-09 | M80              | W   | 0.833      | 0.143        | 0.188 (0.022)    | -                | -         |    22.68 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1193 | 2024-06-08 | Party Astronauts | W   | 0.827      | -            | -                | -                | -         |    15.79 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1235 | 2024-06-07 | Party Astronauts | L   | 0.820      | -            | -                | -                | -         |   -10.15 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1280 | 2024-06-06 | Party Astronauts | L   | 0.816      | -            | -                | -                | -         |   -11.32 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1289 | 2024-06-06 | Wildcard         | W   | 0.815      | 0.143        | 0.055 (0.006)    | -                | -         |    15.14 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1293 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.814      | -            | -                | -                | -         |     6.48 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1314 | 2024-06-06 | Wildcard         | L   | 0.813      | -            | -                | -                | -         |   -10.11 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1347 | 2024-06-05 | LAG              | W   | 0.809      | 0.477        | -                | 0.353 (0.136)    | -         |    10.74 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1361 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.807      | -            | -                | -                | -         |     6.84 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1398 | 2024-06-04 | Nouns            | L   | 0.803      | -            | -                | -                | -         |   -10.02 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1689 | 2024-05-23 | Nouns            | L   | 0.722      | -            | -                | -                | -         |    -9.67 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1705 | 2024-05-22 | Elevate          | L   | 0.716      | -            | -                | -                | -         |    -9.77 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1711 | 2024-05-22 | Elevate          | L   | 0.716      | -            | -                | -                | -         |   -10.41 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1734 | 2024-05-22 | Legacy           | W   | 0.713      | 0.384        | 0.122 (0.034)    | 0.663 (0.182)    | -         |    13.93 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1757 | 2024-05-21 | Perseverance     | L   | 0.709      | -            | -                | -                | -         |   -16.53 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1759 | 2024-05-21 | Perseverance     | W   | 0.709      | -            | -                | -                | -         |     5.70 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1790 | 2024-05-20 | M80              | L   | 0.703      | -            | -                | -                | -         |    -3.13 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1794 | 2024-05-20 | M80              | L   | 0.702      | -            | -                | -                | -         |    -3.23 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1852 | 2024-05-18 | Nouns            | L   | 0.689      | -            | -                | -                | -         |   -11.38 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1857 | 2024-05-18 | Party Astronauts | W   | 0.687      | 0.303        | 0.041 (0.009)    | -                | -         |    10.73 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     1891 | 2024-05-17 | BOSS             | W   | 0.681      | -            | -                | -                | -         |     6.71 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     1960 | 2024-05-15 | LAG              | W   | 0.669      | -            | -                | -                | -         |     7.82 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     1967 | 2024-05-15 | LAG              | W   | 0.669      | -            | -                | -                | -         |     8.26 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2012 | 2024-05-14 | Take Flyte       | W   | 0.662      | -            | -                | -                | -         |     4.99 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2017 | 2024-05-14 | Take Flyte       | W   | 0.662      | -            | -                | -                | -         |     5.21 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2082 | 2024-05-12 | Perseverance     | W   | 0.649      | -            | -                | -                | -         |     6.36 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2084 | 2024-05-12 | Elevate          | W   | 0.648      | -            | -                | -                | -         |    11.89 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2112 | 2024-05-11 | Perseverance     | W   | 0.641      | -            | -                | -                | -         |     6.32 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2114 | 2024-05-11 | BOSS             | W   | 0.641      | -            | -                | -                | -         |     8.16 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2217 | 2024-05-06 | Party Astronauts | W   | 0.609      | 0.477        | 0.041 (0.012)    | 0.550 (0.160)    | -         |    12.01 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2218 | 2024-05-06 | Party Astronauts | L   | 0.609      | -            | -                | -                | -         |    -7.25 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2453 | 2024-04-25 | Wildcard         | L   | 0.536      | -            | -                | -                | -         |    -7.50 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2455 | 2024-04-25 | Wildcard         | W   | 0.536      | 0.477        | 0.055 (0.014)    | -                | -         |     9.60 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2691 | 2024-04-17 | Akimbo           | L   | 0.481      | -            | -                | -                | -         |    -9.88 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2750 | 2024-04-15 | Mythic           | W   | 0.469      | -            | -                | -                | -         |     5.32 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2751 | 2024-04-15 | Mythic           | W   | 0.469      | -            | -                | -                | -         |     5.53 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2838 | 2024-04-10 | BOSS             | W   | 0.436      | -            | -                | -                | -         |     6.22 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2842 | 2024-04-10 | BOSS             | L   | 0.436      | -            | -                | -                | -         |    -7.68 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     2896 | 2024-04-09 | Carpe Diem       | W   | 0.429      | -            | -                | -                | -         |     3.39 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     2899 | 2024-04-09 | Carpe Diem       | W   | 0.429      | -            | -                | -                | -         |     3.49 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3199 | 2024-03-27 | Nouns            | W   | 0.343      | 0.477        | 0.057 (0.009)    | -                | -         |     6.44 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3203 | 2024-03-27 | Nouns            | L   | 0.343      | -            | -                | -                | -         |    -4.43 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3249 | 2024-03-26 | MIGHT            | W   | 0.336      | -            | -                | -                | -         |     1.60 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3253 | 2024-03-26 | MIGHT            | W   | 0.336      | -            | -                | -                | -         |     1.62 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3416 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.263      | -            | -                | -                | -         |     3.20 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3418 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.263      | -            | -                | -                | -         |    -5.17 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3436 | 2024-03-14 | Limitless        | W   | 0.256      | -            | -                | -                | -         |     1.98 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3440 | 2024-03-14 | Limitless        | W   | 0.256      | -            | -                | -                | -         |     2.01 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3514 | 2024-03-12 | Carpe Diem       | L   | 0.242      | -            | -                | -                | -         |    -5.52 | autimatic, Brehze, HexT, oSee, Walco |
|           10 |     3768 | 2024-03-02 | MIBR             | L   | 0.174      | -            | -                | -                | -         |    -0.22 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3787 | 2024-03-01 | Imperial         | L   | 0.168      | -            | -                | -                | -         |    -0.56 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     3893 | 2024-02-24 | Wildcard         | L   | 0.129      | -            | -                | -                | -         |    -1.71 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     3895 | 2024-02-24 | Limitless        | W   | 0.129      | -            | -                | -                | -         |     1.01 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     3901 | 2024-02-24 | Mythic           | W   | 0.128      | -            | -                | -                | -         |     1.69 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     3937 | 2024-02-22 | Party Astronauts | L   | 0.115      | -            | -                | -                | -         |    -1.43 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     3942 | 2024-02-22 | Wildcard         | W   | 0.115      | -            | -                | -                | -         |     2.11 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     3990 | 2024-02-20 | Party Astronauts | L   | 0.103      | -            | -                | -                | -         |    -1.28 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4015 | 2024-02-19 | Party Astronauts | W   | 0.096      | -            | -                | -                | -         |     1.84 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4017 | 2024-02-19 | Mythic           | W   | 0.095      | -            | -                | -                | -         |     1.27 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,536.05)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.835 | $4,250.00      | $3,550.13       |
| 2024-05-18 |      0.689 | $1,000.00      | $688.84         |
| 2024-05-12 |      0.649 | $2,000.00      | $1,297.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
