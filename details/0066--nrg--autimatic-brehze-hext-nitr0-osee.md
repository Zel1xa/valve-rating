### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  989.2<br />
<br />
Final Rank Value (989.2) = Starting Rank Value (849.4) + Head To Head Adjustments (139.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.157[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.218<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 849.4
- 400 + ( ( 0.218 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 849.4


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
|           75 |       72 | 2024-08-03 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.80 | autimatic, Brehze, HexT, nitr0, oSee |
|           74 |      180 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.319 (0.152)    | 0 (0.000) |     8.34 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |      184 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.319 (0.152)    | 0 (0.000) |     8.95 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      228 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.51 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      232 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.94 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      521 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -20.02 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      525 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.057 (0.017)    | 0.541 (0.164)    | 0 (0.000) |    14.38 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      551 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.78 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      619 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.376 (0.179)    | 0 (0.000) |     8.44 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      623 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.376 (0.179)    | 0 (0.000) |     9.06 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      685 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.50 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      690 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.01 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      747 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.304 (0.145)    | 0 (0.000) |     5.78 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      752 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.304 (0.145)    | -         |     6.11 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |      799 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.56 | autimatic, Brehze, HexT, nitr0, oSee |
|           60 |      802 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     8.07 | autimatic, Brehze, HexT, nitr0, oSee |
|           59 |     1260 | 2024-06-09 | M80              | W   | 0.814      | 0.143        | 0.188 (0.022)    | -                | -         |    22.12 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1332 | 2024-06-08 | Party Astronauts | W   | 0.807      | -            | -                | -                | -         |    15.47 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1378 | 2024-06-07 | Party Astronauts | L   | 0.801      | -            | -                | -                | -         |    -9.89 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1422 | 2024-06-06 | Party Astronauts | L   | 0.796      | -            | -                | -                | -         |   -11.01 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1431 | 2024-06-06 | Wildcard         | W   | 0.795      | 0.143        | 0.048 (0.005)    | -                | -         |    13.96 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1435 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.795      | -            | -                | -                | -         |     6.53 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1456 | 2024-06-06 | Wildcard         | L   | 0.794      | -            | -                | -                | -         |   -10.77 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1489 | 2024-06-05 | LAG              | W   | 0.790      | 0.477        | -                | 0.376 (0.142)    | -         |    10.02 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1503 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.788      | -            | -                | -                | -         |     6.85 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1540 | 2024-06-04 | Nouns            | L   | 0.783      | -            | -                | -                | -         |    -9.50 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1835 | 2024-05-23 | Nouns            | L   | 0.703      | -            | -                | -                | -         |    -9.11 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1851 | 2024-05-22 | Elevate          | L   | 0.696      | -            | -                | -                | -         |    -8.66 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1857 | 2024-05-22 | Elevate          | L   | 0.696      | -            | -                | -                | -         |    -9.19 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1880 | 2024-05-22 | Legacy           | W   | 0.694      | 0.384        | 0.122 (0.032)    | 0.621 (0.165)    | -         |    13.62 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1903 | 2024-05-21 | Phoenix          | L   | 0.690      | -            | -                | -                | -         |   -16.00 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1905 | 2024-05-21 | Phoenix          | W   | 0.689      | -            | -                | -                | -         |     5.64 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1936 | 2024-05-20 | M80              | L   | 0.683      | -            | -                | -                | -         |    -3.05 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1940 | 2024-05-20 | M80              | L   | 0.683      | -            | -                | -                | -         |    -3.14 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1999 | 2024-05-18 | Nouns            | L   | 0.669      | -            | -                | -                | -         |   -10.61 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     2004 | 2024-05-18 | Party Astronauts | W   | 0.668      | 0.303        | 0.041 (0.008)    | -                | -         |    10.54 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     2038 | 2024-05-17 | BOSS             | W   | 0.662      | -            | -                | -                | -         |     6.63 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     2107 | 2024-05-15 | LAG              | W   | 0.650      | -            | -                | -                | -         |     7.28 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2114 | 2024-05-15 | LAG              | W   | 0.649      | -            | -                | -                | -         |     7.68 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2159 | 2024-05-14 | Take Flyte       | W   | 0.643      | -            | -                | -                | -         |     4.95 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2164 | 2024-05-14 | Take Flyte       | W   | 0.643      | -            | -                | -                | -         |     5.16 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2229 | 2024-05-12 | Phoenix          | W   | 0.629      | -            | -                | -                | -         |     6.20 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2231 | 2024-05-12 | Elevate          | W   | 0.628      | -            | -                | -                | -         |    12.56 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2259 | 2024-05-11 | Phoenix          | W   | 0.622      | -            | -                | -                | -         |     6.18 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2261 | 2024-05-11 | BOSS             | W   | 0.621      | -            | -                | -                | -         |     8.04 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2365 | 2024-05-06 | Party Astronauts | W   | 0.590      | 0.477        | 0.041 (0.012)    | 0.510 (0.143)    | -         |    11.44 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2366 | 2024-05-06 | Party Astronauts | L   | 0.589      | -            | -                | -                | -         |    -7.22 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2602 | 2024-04-25 | Wildcard         | L   | 0.516      | -            | -                | -                | -         |    -7.86 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2604 | 2024-04-25 | Wildcard         | W   | 0.516      | 0.477        | 0.048 (0.012)    | -                | -         |     8.60 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2840 | 2024-04-17 | Akimbo           | L   | 0.462      | -            | -                | -                | -         |    -9.43 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2899 | 2024-04-15 | Mythic           | W   | 0.449      | -            | -                | -                | -         |     5.11 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2900 | 2024-04-15 | Mythic           | W   | 0.449      | -            | -                | -                | -         |     5.30 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2987 | 2024-04-10 | BOSS             | W   | 0.416      | -            | -                | -                | -         |     5.97 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2991 | 2024-04-10 | BOSS             | L   | 0.416      | -            | -                | -                | -         |    -7.30 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     3045 | 2024-04-09 | Carpe Diem       | W   | 0.410      | -            | -                | -                | -         |     3.26 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     3048 | 2024-04-09 | Carpe Diem       | W   | 0.409      | -            | -                | -                | -         |     3.35 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3348 | 2024-03-27 | Nouns            | W   | 0.323      | 0.477        | 0.057 (0.009)    | -                | -         |     6.13 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3352 | 2024-03-27 | Nouns            | L   | 0.323      | -            | -                | -                | -         |    -4.13 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3400 | 2024-03-26 | MIGHT            | W   | 0.317      | -            | -                | -                | -         |     1.50 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3405 | 2024-03-26 | MIGHT            | W   | 0.316      | -            | -                | -                | -         |     1.52 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3571 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.243      | -            | -                | -                | -         |     2.96 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3573 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.243      | -            | -                | -                | -         |    -4.78 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3591 | 2024-03-14 | Limitless        | W   | 0.237      | -            | -                | -                | -         |     1.85 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3595 | 2024-03-14 | Limitless        | W   | 0.236      | -            | -                | -                | -         |     1.88 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3670 | 2024-03-12 | Carpe Diem       | L   | 0.223      | -            | -                | -                | -         |    -5.07 | autimatic, Brehze, HexT, oSee, Walco |
|           10 |     3925 | 2024-03-02 | MIBR             | L   | 0.154      | -            | -                | -                | -         |    -0.20 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3944 | 2024-03-01 | Imperial         | L   | 0.149      | -            | -                | -                | -         |    -0.45 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     4050 | 2024-02-24 | Wildcard         | L   | 0.110      | -            | -                | -                | -         |    -1.62 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     4052 | 2024-02-24 | Limitless        | W   | 0.109      | -            | -                | -                | -         |     0.87 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     4058 | 2024-02-24 | Mythic           | W   | 0.109      | -            | -                | -                | -         |     1.44 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     4094 | 2024-02-22 | Party Astronauts | L   | 0.096      | -            | -                | -                | -         |    -1.21 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4099 | 2024-02-22 | Wildcard         | W   | 0.096      | -            | -                | -                | -         |     1.60 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4147 | 2024-02-20 | Party Astronauts | L   | 0.083      | -            | -                | -                | -         |    -1.05 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4172 | 2024-02-19 | Party Astronauts | W   | 0.077      | -            | -                | -                | -         |     1.45 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4174 | 2024-02-19 | Mythic           | W   | 0.075      | -            | -                | -                | -         |     1.00 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,394.75)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.816 | $4,250.00      | $3,467.29       |
| 2024-05-18 |      0.669 | $1,000.00      | $669.35         |
| 2024-05-12 |      0.629 | $2,000.00      | $1,258.10       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
