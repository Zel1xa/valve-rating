### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [18]( ../standings_americas.md)<br />
<br />
Final Rank Value:  989.7<br />
<br />
Final Rank Value (989.7) = Starting Rank Value (849.5) + Head To Head Adjustments (140.2)<br />

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
|           74 |       99 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.333 (0.159)    | 0 (0.000) |     8.15 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |      103 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.333 (0.159)    | 0 (0.000) |     8.73 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      147 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.48 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      151 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.91 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      440 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -15.40 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      444 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.057 (0.017)    | 0.547 (0.166)    | 0 (0.000) |    14.27 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      470 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.71 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      538 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.185)    | 0 (0.000) |     8.25 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      542 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.389 (0.185)    | 0 (0.000) |     8.85 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      604 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.300 (0.143)    | 0 (0.000) |     7.46 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      609 | 2024-07-17 | Mythic           | W   | 1.000      | 0.477        | -                | 0.300 (0.143)    | 0 (0.000) |     7.97 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      666 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.57 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      671 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.87 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |      718 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.48 | autimatic, Brehze, HexT, nitr0, oSee |
|           60 |      721 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.99 | autimatic, Brehze, HexT, nitr0, oSee |
|           59 |     1178 | 2024-06-09 | M80              | W   | 0.832      | 0.143        | 0.188 (0.022)    | -                | -         |    22.60 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1250 | 2024-06-08 | Party Astronauts | W   | 0.825      | -            | -                | -                | -         |    15.81 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1296 | 2024-06-07 | Party Astronauts | L   | 0.819      | -            | -                | -                | -         |   -10.08 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1340 | 2024-06-06 | Party Astronauts | L   | 0.814      | -            | -                | -                | -         |   -11.23 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1349 | 2024-06-06 | Wildcard         | W   | 0.813      | 0.143        | 0.055 (0.006)    | -                | -         |    15.11 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1353 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.813      | -            | -                | -                | -         |     6.46 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1374 | 2024-06-06 | Wildcard         | L   | 0.812      | -            | -                | -                | -         |   -10.08 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1407 | 2024-06-05 | LAG              | W   | 0.807      | 0.477        | -                | 0.341 (0.131)    | -         |    10.50 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1421 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.805      | -            | -                | -                | -         |     6.81 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1458 | 2024-06-04 | Nouns            | L   | 0.801      | -            | -                | -                | -         |    -9.87 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1753 | 2024-05-23 | Nouns            | L   | 0.721      | -            | -                | -                | -         |    -9.52 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1769 | 2024-05-22 | Elevate          | L   | 0.714      | -            | -                | -                | -         |    -8.95 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1775 | 2024-05-22 | Elevate          | L   | 0.714      | -            | -                | -                | -         |    -9.52 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1798 | 2024-05-22 | Legacy           | W   | 0.712      | 0.384        | 0.122 (0.033)    | 0.642 (0.176)    | -         |    13.99 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1821 | 2024-05-21 | Perseverance     | L   | 0.707      | -            | -                | -                | -         |   -16.48 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1823 | 2024-05-21 | Perseverance     | W   | 0.707      | -            | -                | -                | -         |     5.71 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1854 | 2024-05-20 | M80              | L   | 0.701      | -            | -                | -                | -         |    -3.13 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1858 | 2024-05-20 | M80              | L   | 0.701      | -            | -                | -                | -         |    -3.23 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1917 | 2024-05-18 | Nouns            | L   | 0.687      | -            | -                | -                | -         |   -11.14 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1922 | 2024-05-18 | Party Astronauts | W   | 0.686      | 0.303        | 0.041 (0.009)    | -                | -         |    10.81 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     1956 | 2024-05-17 | BOSS             | W   | 0.680      | -            | -                | -                | -         |     6.72 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     2025 | 2024-05-15 | LAG              | W   | 0.667      | -            | -                | -                | -         |     7.66 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2032 | 2024-05-15 | LAG              | W   | 0.667      | -            | -                | -                | -         |     8.09 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2077 | 2024-05-14 | Take Flyte       | W   | 0.661      | -            | -                | -                | -         |     4.97 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2082 | 2024-05-14 | Take Flyte       | W   | 0.661      | -            | -                | -                | -         |     5.19 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2147 | 2024-05-12 | Perseverance     | W   | 0.647      | -            | -                | -                | -         |     6.33 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2149 | 2024-05-12 | Elevate          | W   | 0.646      | -            | -                | -                | -         |    12.84 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2177 | 2024-05-11 | Perseverance     | W   | 0.639      | -            | -                | -                | -         |     6.31 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2179 | 2024-05-11 | BOSS             | W   | 0.639      | -            | -                | -                | -         |     8.18 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2283 | 2024-05-06 | Party Astronauts | W   | 0.607      | 0.477        | 0.041 (0.012)    | 0.532 (0.154)    | -         |    11.85 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2284 | 2024-05-06 | Party Astronauts | L   | 0.607      | -            | -                | -                | -         |    -7.36 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2519 | 2024-04-25 | Wildcard         | L   | 0.534      | -            | -                | -                | -         |    -7.41 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2521 | 2024-04-25 | Wildcard         | W   | 0.534      | 0.477        | 0.055 (0.014)    | -                | -         |     9.65 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2757 | 2024-04-17 | Akimbo           | L   | 0.480      | -            | -                | -                | -         |    -9.83 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2816 | 2024-04-15 | Mythic           | W   | 0.467      | -            | -                | -                | -         |     5.30 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2817 | 2024-04-15 | Mythic           | W   | 0.467      | -            | -                | -                | -         |     5.51 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2904 | 2024-04-10 | BOSS             | W   | 0.434      | -            | -                | -                | -         |     6.21 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2908 | 2024-04-10 | BOSS             | L   | 0.434      | -            | -                | -                | -         |    -7.64 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     2962 | 2024-04-09 | Carpe Diem       | W   | 0.427      | -            | -                | -                | -         |     3.38 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     2965 | 2024-04-09 | Carpe Diem       | W   | 0.427      | -            | -                | -                | -         |     3.48 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3265 | 2024-03-27 | Nouns            | W   | 0.341      | 0.477        | 0.057 (0.009)    | -                | -         |     6.50 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3269 | 2024-03-27 | Nouns            | L   | 0.341      | -            | -                | -                | -         |    -4.32 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3317 | 2024-03-26 | MIGHT            | W   | 0.334      | -            | -                | -                | -         |     1.59 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3322 | 2024-03-26 | MIGHT            | W   | 0.334      | -            | -                | -                | -         |     1.62 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3488 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.261      | -            | -                | -                | -         |     3.18 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3490 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.261      | -            | -                | -                | -         |    -5.13 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3508 | 2024-03-14 | Limitless        | W   | 0.254      | -            | -                | -                | -         |     1.98 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3512 | 2024-03-14 | Limitless        | W   | 0.254      | -            | -                | -                | -         |     2.01 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3586 | 2024-03-12 | Carpe Diem       | L   | 0.241      | -            | -                | -                | -         |    -5.48 | autimatic, Brehze, HexT, oSee, Walco |
|           10 |     3841 | 2024-03-02 | MIBR             | L   | 0.172      | -            | -                | -                | -         |    -0.22 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3860 | 2024-03-01 | Imperial         | L   | 0.166      | -            | -                | -                | -         |    -0.47 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     3966 | 2024-02-24 | Wildcard         | L   | 0.127      | -            | -                | -                | -         |    -1.69 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     3968 | 2024-02-24 | Limitless        | W   | 0.127      | -            | -                | -                | -         |     1.00 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     3974 | 2024-02-24 | Mythic           | W   | 0.127      | -            | -                | -                | -         |     1.67 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     4010 | 2024-02-22 | Party Astronauts | L   | 0.114      | -            | -                | -                | -         |    -1.42 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4015 | 2024-02-22 | Wildcard         | W   | 0.113      | -            | -                | -                | -         |     2.08 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4063 | 2024-02-20 | Party Astronauts | L   | 0.101      | -            | -                | -                | -         |    -1.26 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4088 | 2024-02-19 | Party Astronauts | W   | 0.094      | -            | -                | -                | -         |     1.80 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4090 | 2024-02-19 | Mythic           | W   | 0.093      | -            | -                | -                | -         |     1.24 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,523.63)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.834 | $4,250.00      | $3,542.85       |
| 2024-05-18 |      0.687 | $1,000.00      | $687.13         |
| 2024-05-12 |      0.647 | $2,000.00      | $1,293.66       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
